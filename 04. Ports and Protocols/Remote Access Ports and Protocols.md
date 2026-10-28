> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types

> [!Tip] Remote Access Ports and Protocols
> Build and manage systems and networks from across the network

## SSH (Secure Shell)
- Port 22
- Protocol used for secure remote login and other secure network services over an unsecure network
- Strong authentication and data encryption
- Control web and server applications remotely
- Creating a secure encrypted tunnel that can operate text-based commands from a remote server
- Text based
## Telnet
- Port 23
- Allows a user on one computer to login remotely to another computer
- Designed for LAN
- Transfers data in plain text
	- No encryption
	- SSH developed as replacement for Telnet
- NEVER use Telnet
	- Unless operating legacy equipment that doesn't support SSH
- Text based
## RDP (Remote Desktop Protocol)
- Port 3389
- Proprietary protocol that was developed by Microsoft to provide users with a graphical user interface to connect to another computer over a network connection
- Supports different network topologies
- Allows for data encryption, smart card authentication, and bandwidth reduction mechanisms
	- Suitable for managing Windows systems remotely
- GUI