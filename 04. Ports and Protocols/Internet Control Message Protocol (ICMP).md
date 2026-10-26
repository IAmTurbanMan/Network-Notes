> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types

> [!tip] ICMP
> Sends error messages and operational information to an IP destination

- Not used to send data between two systems
- Used on the [[Layer 3 (Network)|Network Layer]] to diagnose network communication issues and to provide hosts information about network problems
	- Encapsulated w/in IP packets
- Essential tool for error reporting and testing
	- When a service or host is unreachable
	- When a packet's time to live has expired
	- When a router cannot forward packets due to its buffer being filled up
- Lacks the reliability mechanisms of TCP
	- Prioritizes speed and simplicity
## Message structure
### Type
- 1 byte long field
- Indicates the type of ICMP message being transmitted
### Code
- 1 byte long field
- Provides additional context about the message type
### Checksum
- 2 byte long field
- Used for error checking message header and data
## Drawbacks
- Hackers using ICMP as part of attacks
	- ICMP Flood Attack
		- Type of attack the involves overwhelming a target machine with a large number of ICMP Echo Request packets
		- Done as fast as possible to consume network resources
		- Leads to a DDoS attack
			- Where the attacker uses a network of compromised machines (a botnet) to generate a significant amount of traffic
			- Hard to trace back to origin of attack
	- Ping of Death
		- Attack that exploits a vulnerability that existed in older, unpatched systems where the attacker sends malformed or oversized packets using the ICMP protocol
		- Traditionally, max size of IP packet (including headers) is 65,535 bytes
			- Ping packet in attack is larger that max size
		- Results in DoS attack
	- Net admins might choose to block ICMP traffic to harden network
		- Cannot use `ping` or `tracert` to troubleshoot network issues