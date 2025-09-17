# Networking basics #0
# 0. OSI model
- The OSI model diagram isn't showing details of internal structure and technology: The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology
- "It is organized from the lowest level to the highest level": the OSI model is organized from the lowest to the highest level

# 1. Types of network
- Local network: LAN (Local Area Network)
- Out of reach but in same town: WAN (Wide area network)
- When using mobile data, a mobile phone directly connects to the Internet with mobile network: Internet

# 2. MAC and IP address
- A MAC adress is tied to the hardware: a MAC address is the unique identifier of a network interface
- An IP address is less static and is tied to location: an IP address is to devices connected to a network what postal address is to houses

# 3. UDP and TCP
- UDP is a single agent simply deposits packages in the DNS and to DHCP, so it seems fast, but some packages are seen being lost.
- TCP is a double agent with one doing multiple tasks to ensure packages are not lost. There is few packages lost with TCP, however it seems slower.

So TCP does not ask for increasing the rate of packages, it cares about whether or not the packages are sent.