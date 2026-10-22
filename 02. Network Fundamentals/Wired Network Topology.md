> [!NOTE] [[Exam Objectives.pdf#page=6&selection=8,0,9,10|OBJ 1.6]]
> Compare and contrast network topologies, architectures, and types.

# Network Topology
- Refers to the arrangement of different elements like links, nodes, clients, and servers that make up a computer network
## Physical Topology
- Used to show how the network devices and components are physically cabled and connected together
- Focused on the physical layout of the cabling and devices
## Logical Topology
- Talks about how the traffic is actually going to flow in the network
- Focused on the logical or network flow of the data
## Topology Types
### Point-to-point
- Simplest form of network topology that involves a direct connection between two devices
- ![[Point-to-point Topology.png|266]]
### Ring
- A network configuration where each device is connected to two other devices, forming a circular data path
- Benefits
	- Prevents data collisions due to using unidirectional flow
- Drawback
	- If one node fails, entire network is down
- Not so common anymore
	- FDDI (Fiber Distributed Data Interface)
		- Used to conduct data transmissions on fiber optic lines in a LAN
		- Dual ring structure for redundancy
		- High bandwidth
- ![[Ring Topology.png|272]]
### Bus
- All of the network devices are connected to a single central cable called the bus or backbone
- Data sent from any device is available to any device on the bus
	- Only the intended recipient (determined by MAC or IP) will be able to process the message
- Bennies
	- Easy to install
	- Require less cabling
- Drawbacks
	- Entire network will be disabled if bus cable fails
	- Not very scalable
		- More devices added = more data collisions and decreased network performance
- ![[Bus Topology.png|372]]
### Star
- One of the most common network layouts that is in use today
- Each device connected to a centralized point like a switch
- Bennies
	- Failure of one link does not affect the rest of the links
- Drawbacks
	- Entire network will fail if the central device fails
- ![[Star Topology.png|439]]
### Hub-and-spoke
- Variation on star topology where the central node (hub) is connected to multiple nodes (spokes)
- Spokes are not directly connected to each other, so data must go through a hub before it reaches its final destination
- ![[Hub-and-spoke Topology.png|437]]
### Mesh
- Features a point-to-point connection between every single device on the network to create a robust and redundant network
#### Full-mesh
- Every node is connected to every other node in the network
- High redundancy
- Complex and expensive to install
- Number of connections
- $$
x = n(n-1)/2
$$
	- n = number of nodes
#### Partial-mesh
- Some nodes are organized in a full-mesh scheme, while others are only connected to one or two devices in the network
- Only most critical nodes are connected in full-mesh, the rest are only connected to one or two nodes
- ![[Mesh Topology.png|397]]