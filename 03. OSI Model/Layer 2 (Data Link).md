> [!NOTE] [[Exam Objectives.pdf#page=4&selection=7,0,8,22|OBJ 1.1]]
> Explain concepts related to the Open Systems Interconnection (OSI) reference model.

## Data Link Layer
- <mark style="background: #ADCCFFA6;">Switches, Bridges and MAC addresses are great examples of things that operate on Layer 2</mark>
- Layer 2 devices view networks logically
- Packages data into frames and transmits those frames on the network
- Performs error detection and correction
- Identify unique network devices using MAC addresses
- Flow control
### MAC Addresses
- A unique 48-bit physical addressing system is assigned to every NIC produced
- Written in hexadecimal, each digit is considered 4 bits
	- First 24 bits (6 digits)
		- Identifies vendor that made the card
	- Last 24 bits
		- Unique value
	- ![[MAC Address.png|259]]
### Flow Control
- LLC
	- Most basic form of flow control
	- Limits the amount of data a sender can send at once
	- Allows receiver to keep from being overwhelmed
	- Provides basic error control functions
		- allows receiver to inform sender that the data frame wasn't received or if it was received corrupted
		- uses Checksum
### Communication
- Isochronous
	- Network devices use a common reference clock source and create time slots for transmission
	- similar to synchronous and TDM
	- Less overhead
		- Both devices know when they can communicate and for how long
- Synchronous
	- Network devices agree on clocking method to indicate beginning and end of frames and can use control characters
	- Allows for beginning and ending frames and special control characters
	- Drawback
		- Devices can only communicate at frequencies specified by the clock cycles
			- Not a lot of gap time that isn't properly utilized
- Asynchronous
	- Network devices reference internal clocks and use start and stop bits for synchronization
	- No real control over when devices can communicate
### Devices
- Network Interface Cards
- Bridges
- Switches
	- Uses logic to determine which ports are connected to which MAC addresses
	- [[Layer 3 (Network)#^03002|A Switch is always a Layer 2 device unless specifically called a Multi-Layer Switch]] ^03001

Multi-Layer switch is a Layer 3 device