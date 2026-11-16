> [!NOTE] [[Exam Objectives.pdf#page=9&selection=4,0,4,52|OBJ 2.4]]
> Explain important factors of physical installations.

- Ensure consistent and reliable power delivery for networking equipment, infrastructure, and environments
## UPS (Uninterruptible Power Supply)
- Electrical apparatus that provides emergency power to a load when the input power source fails
- Great for short-duration power outages depending on the amount of electrical load
	- Last for 15 to 30 minutes
- Most data centers place an UPS unit at the bottom of each rack
## PDU (Power Distribution Unit)
- Specialized device for distributing electric power to various network components and computing equipment
- Can be rack mounted or as large cabinets
- Designed to provided power protection from surges, spikes, and brownouts
	- Not designed for providing power during complete power outage
## Generator
- Installed outside of a datacenter to provide longer-term power during a power outage in a region
- Powered by diesel, propane, or gasoline
- Take a little bit of time to start up
	- Paired with UPS or PDU for redundant power solution
## Managing Power Loads
- Critical in preventing circuit overloads and ensuring efficient power usage inside data centers
- Proper load balancing ensures the power supply is evenly distributed so no single circuit is under excessive load
## Understanding Voltage Considerations
- Voltage= Electric potential difference and is a key factor in power distribution systems
- EU devices in US will not power on
- US devices in EU will catch fire
- Most devices these days are considered to be dual-voltage and can be configured to run on either 120V or 230V