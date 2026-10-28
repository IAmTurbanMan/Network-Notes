> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types
## SMTP (Simple Mail Transfer Protocol)
- Port 25
- Standard protocol used for sending emails across the Internet
- Used for transmission of outbound emails
- Only used for SENDING emails from a server
- Insecure protocol because data is sent over plain text
	- SMTPS was introduced
		- Not a protocol itself
		- A way to secure SMTP by transferring data over SSL/TLS
		- Operates over Port 465 or Port 587
## POP3 (Post Office Protocol version 3)
- Port 110
- Used to retrieve emails from a remote server to a local client
- Downloads messages from server into email client
	- Downloaded messages are deleted from server when they are downloaded
- Limits email access on multiple devices as messages are stored only on the initial device
- Updated versions include the option to keep the message on the server after being downloaded
	- Read or delete status not synchronized across devices
- Transmits messages over plain text
	- POP3S introduced
		- Port 995
		- SSL/TLS tunnels
## IMAP (Internet Message Access Protocol)
- Port 143
- Allows users to manage emails directly on the email server
- Access and sync emails across multiple devices
- Initially transmitted emails in plain text
	- IMAPS introduced
		- Port 993
		- SSL/TLS tunnels