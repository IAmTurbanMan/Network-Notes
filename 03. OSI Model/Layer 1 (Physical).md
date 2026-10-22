> [!NOTE] [[Exam Objectives.pdf#page=4&selection=7,0,8,22|OBJ 1.1]]
> Explain concepts related to the Open Systems Interconnection (OSI) reference model.
## Physical Layer
- Where transmission of bits across the network occurs and includes physical and electrical network characteristics
	- Ethernet
		- Cat5 or Cat6
	- Fiber
	- Radio Frequency
		- for Wi-Fi
- Bit represented on cables
	- Copper wire cables
		- 0 volts for 0
		- 5/12 volts for 1
	- Fiber wire
		- Light off for 0
		- Light on for 1
- Cables are part of the physical layer
	- Cat5 and Cat6
		- RJ45 connector
		- Use two different standards
			- TIA/EIA-568A
			- TIA/EIA-568B
### Network topology
- Layer 1 devices view networks from a physical topology perspective
	- [[Wired Network Topology]]
### Synchronizing comms

- Asynchronous
	- Uses start and stop bits to indicate when transmissions occur from the sender to the receiver
	- Voice note
		- Call friend, no answer, leave voice note, wait for response
		- Comm happens out of sync
- Synchronous
	- Uses a reference clock to coordinate the transmissions by both sender and receiver
	- Phone call
		- Synchronized conversation
		- Comm happens in real time
### Bandwidth
- Broadband
	- Divides bandwidth into separate channels
	- TV
		- Single cable into house carries hundreds of channels
- Baseband
	- Uses all available frequencies on a medium (cable) to transmit data
	- Telephone
		- Uses all bandwidth dedicated to that phone line
		- Can only make one phone call on line
	- Uses a reference clock
		- Synchronous comm
	- Wired home Ethernet network
### Multiplexing
- Involves optimizing a limited amount of resources for more efficient utilization
	- Allows multiple people to use a baseband connection at the same time
- TDM (Time-Division Multiplexing)
	- Each session takes a turn, using time slots, to share the medium between all users
	- Sometimes time slot doesn't match when show is on
- StatTDM (Statistical Time-Division Multiplexing)
	- Dynamically allocates the time slots on an as-needed basis
	- Take turns based on necessity
- FDM (Frequency-Division Multiplexing)
	- Divides the medium into channels based on frequencies and each session is transmitted over a different channel
### Devices/Media
- Layer 1 devices/media are essentially repeaters, passing along whatever is received
	- Dumb devices
- Cables
	- Fiber optic cable
	- Ethernet cable
	- Coaxial cable
	- What goes in one end of the cable, same thing comes out the other end
- Wireless/RF
	- Bluetooth
	- Wi-Fi
	- NFC
- Infrastructure devices
	- Hubs
	- Access points
	- Media converters
	- These repeat what they get