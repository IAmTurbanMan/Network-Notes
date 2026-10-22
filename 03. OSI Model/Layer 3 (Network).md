> [!NOTE] [[Exam Objectives.pdf#page=4&selection=7,0,8,22|OBJ 1.1]]
> Explain concepts related to the Open Systems Interconnection (OSI) reference model.

# Network Layer
- <mark style="background: #ADCCFFA6;">IP and Router are examples of Layer 3 devices/protocols</mark>
- Routing
	- How to forward traffic using logical addresses
## Logical addressing
- IPv4 and IPv6 is most common currently
- In the 80's
	- Apple used AppleTalk
	- Windows/Novell used IPX
	- Stopped being used in favor of IP (Internet Protocol)
## Switching
- Another term for routing
- Most networks use packet switching
### Packet switching
- Known as routing
- Data is divided into packets and then forwarded
- Packets might take different routes to get to final destination
### Circuit switching
- Dedicated communication link is established between two devices
- Same path for the duration of the conversation
- Next conversation might take a different route
### Message switching
- Data is divided into messages which may be stored and then forwarded
## Route Discovery and Selection
- Manually configured as a static route or dynamically through a routing protocol
	- Routing protocols decide how data is going to flow across the network and how the routers are going to communicate the information
	- In a dynamic protocol, all routers are talking to each other and can determine which route is best
## Connection Services
- Augment Layer 2 connection services to improve reliability
- Flow control
- Packet reordering
	- Take big chunk of data, split into little packets, send them off in different directions to reach final destination
	- Ensures that all data reaches the receiver correctly at the end destination
## ICMP (Internet Control Message Protocol)
- Sends error messages and operational information to an IP destination
- Most commonly used is `ping`
## Devices
- Routers and Multi-Layer switches
	- [[Layer 2 (Data Link)#^03001|Normal switch is a Layer 2 device, Multi-Layer switch is a Layer 3 device]] ^03002
- IPv4 and IPv6
	- Both layer 3 protocols
- ICMP