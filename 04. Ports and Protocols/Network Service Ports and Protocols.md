> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types

> [!Tip] Network Service Ports and Protocols
> Different services that ensure that network devices can discover each other, communicate efficiently, and relay important system information to each other

## DNS (Domain Name System)
- Port 53
- Used to translate human-friendly domain names into an IP address that computers can use to identify each other on a network
- Operates over [[Layer 4 (Transport)|TCP and UDP]]
	- Uses UDP by default for smaller messages
	- Uses TCP for larger messages
## DHCP (Dynamic Host Configuration Protocol)
- Port 67, Port 68
- Used to automate the assignment of IP addresses, subnets, mass gateways, and other networking parameters to a client device
- DHCP servers listen for client requests over port 67, and the clients will receive responses back over port 68 using UDP
## SQL Services
- Microsoft SQL
	- Port 1433
- MySQL
	- Port 3306
- Protocols used by database servers to manage queries and control operations from the client applications that are requesting them
## SNMP (Simple Network Management Protocol)
- Port 161, Port 162
- Uses UDP
- Used for collecting information from and configuring different network devices like servers, printers, hubs, switches, and routers over an IP network
- Port 161 is used by SNMP managers that are communicating with SNMP agents on the different devices to conduct polling
- Port 162 is used by SNMP agents that want to send unsolicited trap messages back to the SNMP manager
	- reporting information back to the manager about the client device
- Crucial for network diagnostics and troubleshooting
## Syslog (System Logging)
- Port 514
	- UDP or TCP
		- Defaults to UDP
		- If more reliability is needed, can be configured to use TCP
- Standard for message logging that allows devices to send event messages across IP networks to an event message collector known as a Syslog server