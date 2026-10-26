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
## Message structure
### Type
- 1 byte long field
- Indicates the type of ICMP message being transmitted
### Code
- 1 byte long field
- Provides additional context abot