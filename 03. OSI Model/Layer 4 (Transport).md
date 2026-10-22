> [!NOTE] [[Exam Objectives.pdf#page=4&selection=7,0,8,22|OBJ 1.1]]
> Explain concepts related to the Open Systems Interconnection (OSI) reference model.

# Transport Layer
- Dividing line between upper layers and lower layers of OSI model
- Data type = Segment or Datagrams
## TCP (Transmission Control Protocol)
- <mark style="background: #ADCCFFA6;">SEGMENT</mark>
- Connection-oriented protocol that is a reliable way to transport segments across the network
- If segment is dropped, the protocol asks for confirmation every time. If no confirmation is received, it will resend the information
	- Connectionful protocol
- Three-way handshake
	- ![[Three-way Handshake.png|281]]
- If packet is missing, server will ask client for missing packets, then retransmission happens with the missing packets.
- Used for all network data that needs to get to end destination completely
## UDP (User Datagram Protocol)
- <mark style="background: #ADCCFFA6;">DATAGRAM</mark>
- Connectionless protocol that is an unreliable way to transport segments across the network
	- Doesn't wait for connections
- If dropped, sender is unaware
- Great for audio and video streaming
	- More data, less overhead
		- Doesn't need three-way handshake
## TCP vs. UDP

| TCP                                                             | UDP                               |
| :-------------------------------------------------------------- | :-------------------------------- |
| Reliable                                                        | Unreliable                        |
| Connection-oriented                                             | Connectionless                    |
| Segment retransmission<br>and flow control<br>through windowing | No windowing or<br>retransmission |
| Segment sequencing                                              | No sequencing                     |
| Acknowledges segments                                           | No acknowledgment                 |
- Use TCP when ensuring someone receives all of something
- For audio or video streaming, UDP does not require every single piece of the file
## Windowing
- Allows the clients to adjust the amount of data in each segment
- If you're sending data and getting a lot of retransmissions, might be sending too much information
	- Back down and close the window a little bit to send less each time
- No retransmissions, might not be going fast enough
	- Open window and send more data in each segment
- Windowing sends information, while minimizing retransmissions and maximizing throughput
## Buffering
- Occurs when devices allocate memory to store segments if bandwidth is not readily available
- Devices, like routers, can store segments if bandwidth isn't readily available
	- If buffer overflows, device runs out of memory, then segment drops
## Devices and Protocols
- TCP and UDP
- WAN accelerators
	- Add compression to IP packets then send segments over through accelerator to get them through the network faster
- Load balancers
- Firewalls