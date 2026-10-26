> [!NOTE] [[Exam Objectives.pdf#page=5&selection=4,0,5,18|OBJ 1.4]]
> Explain common networking ports, protocols, services, and traffic types


> [!tip] TCP
> A fundamental protocol with the Internet protocol suite that consists of a set of rules that govern the exchange of data

- Widely used due to its reliability in delivering packets of data
	- Ensures all data arrives in the correct order and without corruption
	- Breaks down larger messages into smaller packets
- Operates on the [[Layer 4 (Transport)|Transport Layer]] in the OSI Model
- Three-way handshake
	- SYN ➡️ SYN-ACK ➡️ ACK
- Error-Checking
	Uses sequence number and ACK messages to assure the data is being received correctly