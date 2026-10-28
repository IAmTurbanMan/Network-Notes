> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types

> [!TIP] File Transfer Ports and Protocols
> Specialized rules and procedures that are utilized for the transmission of files across networks, operate on the designated ports, and act as doorways for data transfer activities

## FTP (File Transfer Protocol)
- Port 20, Port 21
- Used for transferring files between a client and a server over a network
- Port 20 for actual data transfer
- Port 21 for sending control command
	- "I want to upload or download"
- When FTP connection is established, communication happens over port 21 for command, then data gets sent over port 20
### Drawbacks
- Unencrypted and sent in plain text
	- Usernames and passwords for FTP server can be intercepted
## SFTP (SSH File Transfer Protocol)
- Port 22
- Created to address the security concerns of FTP
- SFTP is tunneling an FTP protocol through an SSH connection, which has already been encrypted
## TFTP (Trivial File Transfer Protocol)
- Port 69
- Simpler and more basic version of FTP
- No user authentication or directory browsing
- Designed for sending files when minimal security is sufficient
- 
## SMB
