# What is a router?
- A router is a device that connects two or more packet-switched networks or subnetworks.

## Several types of Routers
- Most routers pass data between LANs(local area networks) and WANs(wide area networks)
- LANs is a group of connected devices and are restricted to a specific georgraphic area 
- WANs is a large network spread out over a vast geographic area
    - large orgs and companies that operate in multiple locations across the country will
    need seperate LANs for each location, which then connect to other LANs to form a WAN

NOTE: A network switch forwards data packets between group of devices in the same network,
whereas a router forwards data between different networks

## How does routers work?
- Use an internal routing table (a list of paths to various network destinations)
- The router reads a packet's header to determine where it is going, then consults the routing table
to figure out the most efficient path to destination 

## What is the difference between a router and modem?
- Router forms networks and manages the flow of data within and between those networks, while a modem connects
to the Internet
- Modem makes a connection to the Internet by converting signals from an ISP into a digital signal that can 
be interpreted by any connected device. 
- So, if you have both you can have devices that form a LAN with her desktop computer, tablet, and smartphone and connect them all to the Internet at the same time.

## Different types of routers?
- Wireless Router: A wireless router uses an Ethernet cable to connect to a modem. It distributes data by converting packets from binary code into radio signals. Wireless routers do not establish LANs; instead, they create WLANs (wireless local area networks), which connect multiple devices using wireless communication.

- Wired Router: Like a wireless router, a wired router also uses an Ethernet cable to connect to a modem. It then uses separate cables to connect to one or more devices within the network, create a LAN, and link the devices within that network to the Internet.

- Core Router: Unlike the routers used within a home or small business LAN, a core router is used by large corporations and businesses that transmit a high volume of data packets within their network. Core routers operate at the "core" of a network and do not communicate with external networks.

- Edge Router: While a core router exclusively manages data traffic within a large-scale network, an edge router communicates with both core routers and external networks. Edge routers live at the "edge" of a network and use the BGP (Border Gateway Protocol) to send and receive data from other LANs and WANs.

- Virtual Router: A virtual router is a software application that performs the same function as a standard hardware router. It may use the Virtual Router Redundancy Protocol (VRRP) to establish primary and backup virtual routers, should one fail.

## SSID
- This is the "service set identifier," and it is the technical term for the name of the network that WLAN routers broadcast.  