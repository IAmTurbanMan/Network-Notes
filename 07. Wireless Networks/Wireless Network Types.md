> [!NOTE] [[Exam Objectives.pdf#page=8&selection=113,0,114,13|OBJ 2.3]]
> Given a scenario, select and configure wireless devices and technologies.

## Ad Hoc
- AKA: IBSS (Independent Basic Service Set)
- Network where devices connect directly to each other rather than through a central access point
- Operates like a P2P network
	- Great for creating quick and temporary networks
		- Doesn't rely on existing network infrastructure being installed first
- Typically does not provide Internet access
	- Isolated from other networks (like the Internet)
- When to use?
	- Quickly deploy two devices to share files wirelessly between them
- Allows sharing and collaboration, as long as the devices are within range
## Infrastructure
- More organized setup in which devices are connected to the network through a wireless access point into a wired LAN
- Each WAP will have unique identifier known as BSSID (Basic Service Set Identifier)
	- Set to the MAC Address of the WAP by default
- Usually using this kind of network at home
- Configure SSID (Service Set Identifier) for network
- For larger homes/office buildings, use multiple WAPs and use ESS (Extended Service Set)
	- ESS creates a larger network that shares the same SSID to allow for seamless connectivity across a building
## Point-to-point
- Connect two distinct locations over long distances using high-gain antennas
- Highly efficient and offer dedicated bandwidth between two points
	- Ideal for linking buildings within an organization
	- Creating a bridge where cabling is not feasible between both locations
## Mesh
- Versatile and resilient form of wireless networking
- Each node in a mesh network can connect to multiple other nodes
	- Creates potentially infinite paths for data to travel across
- Self-healing capability
	- Can reconfigure themselves over broken or blocked pathways
- Large-scale deployments
### Types of Mesh Networks
1. Uses ESS configuration in a wireless network that operates in infrastructure mode
	- If there are two or more WAPs in the building, this will create a seamless wireless network across the building
2. Uses multiple different types of wireless networks all operating together to provide services to end users