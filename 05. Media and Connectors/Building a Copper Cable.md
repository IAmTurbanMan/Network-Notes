> [!NOTE] [[Exam Objectives.pdf#page=15&selection=9,0,10,23|OBJ 5.5]]
> Given a scenario, use the appropriate tool or protocol to solve networking issues.
## Straight-Through Cable (Patch Cable)
- Contains the exact same pinout on both ends of the cable
- 568-B to 568-B
	- orange-white > orange > green-white > blue > blue-white > green > brown-white > brown
- Connects DTE to DCE
	- DTE to DCE/DCE to DTE
### Data Terminal Equipment (DTE)
- Endpoint devices that connect to a piece of data communications equipment (DCE)
- Includes things like laptops, desktops, servers, and routers
### Data Communications Equipment (DCE)
- Includes things like switches, modems, hubs, and bridges
## Crossover Cable
- Swaps the send and receive pins on the other end of the cable when the connector and its pinout are created
- 568-A to 568-B
	- 568-A
	- green-white > green > orange-white > blue > blue-white > orange > brown-white > brown
- DTE to DTE/DCE to DCE
	- Switch to switch
### MDIX (Medium Dependent Interface Crossover)
- Automated way to electronically simulate a crossover cable even if using a straight through patch cable