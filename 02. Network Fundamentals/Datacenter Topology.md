> [!NOTE] [[Exam Objectives.pdf#page=6&selection=8,0,9,10|OBJ 1.6]]
> Compare and contrast network topologies, architectures, and types.

# Datacenter 🤮
- Any facility that businesses and other orgs use to organize, process, store, and disseminate large amounts of data
## Three-tiered hierarchy
- Core layer
	- Biggest, fastest, most expensive routers
	- Backbone of the network
	- Merge geographically separate networks into one logical network
	- At least two routers operating in a redundant config
- Distribution/Aggregation layer
	- Provides boundary definition by implementing ACLs and filters
	- Defining policies for networks
	- Uses Layer 3 switches
- Access/Edge layer
	- Connects all end-point devices
	- Uses regular switches
- Better performance, management, scalability, and redundancy
- ![[Three-tiered Hierarchy.png|558]]

## Collapsed Core
- Network architecture where the core and the distribution layers are being merged into a single layer
- Functions of Distribution and Core layers are combined
	- Simplifies architecture
- Often seen in small - medium sized datacenters
- Reduces latency and is less expensive
- Not suitable for larger and more complex networks

## Spine and leaf architecture
- An alternative type of network arch that focuses on the communication within the datacenter itself
- Specifically looks at server farm portion of the data center
- Spine
	- Connects switches in a full mesh topology
- Leaf
	- Consist of all the access switches
- Faster speeds and lower latency
- Able to be used together with three-tiered hierarchy architecture
- ![[Spine and leaf Architecture.png|548]]

## Traffic flows
### North-South
- Traffic that enters or leaves the datacenter from a system physically residing outside the datacenter
- Northbound traffic
	- Leaving datacenter
- Southbound traffic
	- Entering datacenter
- In both cases, data is entering/exiting through a firewall boundary
### East-West
- Refers to data flow within a datacenter
- In a spine and leaf arch, all data flow between servers is considered east-west traffic
- Due to SDN, virtualization, private clouds, and converged network, more and more traffic is classified as east-west traffic