> [!NOTE] [[Exam Objectives.pdf#page=6&selection=6,0,6,57|OBJ 1.5]]
> Compare and contrast transmission media and transceivers.


> [!TIP] IEEE 802.3 Standard
> Defines the physical layer and data link layer's media access control (MAC) for wired Ethernet networks


## Twisted Pair Cable
- A type of wiring in which two conductors of a single circuit are twisted together
	- To cancel out electromagnetic interference and crosstalk that might occur form neighboring cables
- Preferred method for transmitting data and voice
- Regardless of whether using a STP or UTP, each cable is also categorized using a number

| Category | Speed     | Dist  | Frequency | AKA         | AKA 2               |
| -------- | --------- | ----- | --------- | ----------- | ------------------- |
| CAT 5    | 100 Mbps  | 100 m | 100 MHz   | 100 BASE-T  | Fast Ethernet       |
| CAT 5e   | 1 Gbps    | 100 m | 100 MHz   | 1000 BASE-T | Gigabit Ethernet    |
| CAT 6    | 1 Gbps    | 100 m | 250 MHz   | 1000 BASE-T | Gigabit Ethernet    |
| CAT 6    | 10 Gbps   | <55 m | 250 MHz   | 10G BASE-T  | 10-Gigabit Ethernet |
| CAT 6a   | 10 Gbps   | 100 m | 500 MHz   | 10G BASE-T  | 10-Gigabit Ethernet |
| CAT 7    | 10 Gbps   | 100 m | 600 MHz   | 10G BASE-T  | 10-Gigabit Ethernet |
| CAT 8    | <=40 Gbps | 30 m  | 2 GHz     |             |                     |

### UTP (Unshielded Twisted Pair)
- Composed of pairs of wires twisted together, without additional shielding being added to the cable
- Most common type of twisted pair cables
- Pros:
	- Lightweight
	- Flexible
	- Cost-effective
	- Easier to install
- Cons:
	- More susceptible to EMI and noise
		- Degrades signal quality
### STP (Shielded Twisted Pair)
- Designed with a layer of insulation or shielding
	- Copper tape, conductive polymer, or braided mesh of copper wires
- Protects against EMI by reducing noise
- Used in environments that have a high amount of EMI
- Pros:
	- More protection against EMI and noise
- Cons:
	- Bulkier
	- More expensive
	- Difficult to install
## Coaxial Cable
- Consists of a single copper conductor at its core, with an insulating layer and a conductive shield covering
- Most modern coax cables can support speeds of up to 1 Gbps at a distance of up to 300 meters
### RG-6
- Used to support faster Internet speeds when using a cable modem
- Heavier center copper core
	- Great for high bandwidth and higher frequency applications
		- Cable modems and digital video transmission
### RG-59
- Older cables that are only used in analog video and closed circuit television installations
- Thinner copper core
- Not really used anymore
## Direct Attach Copper Cable
- A form of fixed assembly copper cabling used to connect switches to routers or servers
- DAC active cables
	- 100 Gbps at 15 m or less
- DAC passive cables
	- 100 Gbps at 7 m or less
- Can support high-speed data transmission of 10 Gbps, 40 Gbps, or up to 100 Gbps
	- Depends on distance
## Twinaxial Cable
- Often a component of a DAC assembly and is considered as another specialized form of cab