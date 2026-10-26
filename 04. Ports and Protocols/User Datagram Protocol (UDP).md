> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types

> [!Tip] UDP
> A communication protocol used across the Internet for especially time-sensitive transmissions

- Losing packets is acceptable
- Low latency
- Reduced processing overhead
- Operates on the [[Layer 4 (Transport)|Transport Layer]]
- No prior communication to establish connection
- No windowing either
- Packets are smaller than TCP packets
	- 8 bytes in size compared to TCP (20 - 60 bytes)
- No error-checking
- Does not maintain the state of the connection or keep track of the packets
	- Doesn't need to send SYN or ACK messages so things arrive faster
	- Also messages can come in out of order or not arrive at all
- Used in situations where the speed of the transmission is much more important than the precision of the data
	- Video/Audio streaming
	- Online gaming
	- VoIP
- Relies on ports to help differentiate between multiple services or apps
- Includes a checksum to provide some minimal protection against potential data corruption during transmission
	- Still not enough to be considered reliable