> [!NOTE] [[Exam Objectives.pdf#page=4&selection=7,0,8,22|OBJ 1.1]]
> Explain concepts related to the Open Systems Interconnection (OSI) reference model.


> [!info] Encapsulation
> The process of putting headers (and trailers) around some data

> [!info] Decapsulation
> Contents


![[Encapsulation and Decapsulation.png|278]]

- PDU (Protocol Data Unit)
	- A single unit of information transmitted in a computer network
	- L* PDU
		- * = the layer
	- Uses the `Do Some People Fear Birthdays` mnemonic
# Encapsulation
![[Encapsulation Through Layers.png|421]]
## Layer 4
### TCP Header
![[TCP Header.png|418]]
- Source and Destination Ports determine where data is being sent to and from and helps route it to the correct ports
- Sequence Number and Acknowledgement Number ensure all data is properly received by receiver
#### Control Flags
- SYN (Synchronization)
- ACK (Acknowledgement)
- FIN (Finished)
	- always appears when the last packets are exchanged between client and server and host is ready to shut down connection
- RST (Reset)
	- If trying to establish connection to server that doesn't want to accept new connections, it will send back a RST flag
- PSH (Push)
	- Added to a packet at the beginning or end of file transfer
	- Gives higher priority to data
- URG (Urgent)
	- Tells recipient to process data immediately and ignore everything else in the queue
	- Can violate FIFO priority order
		- Only used by particular applications when necessary
### UDP Header
![[UDP Header.png|411]]

## Layer 3
### IP Header
![[IP Header.png|410]]

## Layer 2
### Ethernet Header
![[Ethernet Header.png|406]]
- MAC Address