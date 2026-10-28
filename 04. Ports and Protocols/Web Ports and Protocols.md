> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types

## HTTP (Hypertext Transfer Protocol)
- Port 80
- Foundation of data communication on the World Wide Web
- An [[Layer 7 (Application)|application layer]] protocol that enables plain text =communication between clients and servers
	- Sends plain text requests from a client (web browser) to a server that sends back a plain text response with the website
### Drawback
- Lack of security
	- Sent in plain text
	- Vulnerable to eavesdropping and On-path attacks
		- Problematic when using log-in credentials or other sensitive data
## HTTPS (Hypertext Transfer Protocol Secure)
- Port 443
- Same as HTTP but adds encryption by sending the data an SSL Tunnel or a TLS Tunnel
	- Use encryption to make sure any data moving between client and server remains encrypted
- Important for any website that handles sensitive data
	- Banking, Medical, etc
	- These types of sites will auto-redirect from HTTP to HTTPS for enhanced data encryption and security
## Differences
### Security and Encryption
- Port 80 is sent in plain text
- Port 443 is encrypted via SSL/TLS encryption
### Default Usage
- Port 80 was the default since 1991
- Port 443 introduced in 1994
	- Did not become default until 10-15 years ago
	- Over 95% of web traffic over 443 now
### SEO (Search Engine Optimization) and Trust
- Modern web practices prioritize HTTPS over HTTP for enhanced security
- Search engines will rank sites higher when they use HTTPS