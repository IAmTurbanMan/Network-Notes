> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types
## NTP (Network Time Protocol)
- Port 123
	- UDP
- Used to synchronize the clocks of a computer over a given network
- Enables networks to maintain accurate time
	- Crucial for transaction logging, security protocols, and coordination of system protocols
## SIP (Session Initiation Protocol)
- Port 5060
	- Unencrypted signaling using UDP or TCP
- Port 5061
	- Encrypted signaling over TCP using TLS tunnels
- Used for initiating, maintaining, and terminating real-time sessions that involve voice, video, messaging, and other communication services
## LDAP (Lightweight Directory Access Protocol)
- Port 389
	- TCP and UDP
- Protocol for accessing and maintaining distributed directory information services over and IP network
- Sends information as plain text
	- LDAPS (LDAP over SSL)
		- Port 636
			- TCP
		- Encrypted with SSL or TLS for increased security