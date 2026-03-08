## What is Routing?
    - Network routing is the process of selecting a path across one or more networks.
    - In packet-switching networks, such as the Internet, routing selects the paths for Internet Protocol (IP) packets to travel from their origin to their destination.
    - Made possible by routers

## How does routing work?
    - When a router recieves a packet:
        - It reads the headers of the packets to see its intended destination.
        - Then determines where to route the packet based on info. in its routing tables
        - In short, it determines the WHERE
    
    - There are static routing tables and dynamic routing tables
        - A static routing tables do not change, a network administrator manually sets up
        static routing tables.
        - Dynamic routing tables update automatically. They use various routing protocols
        to determine the shortest and fastest paths. One caveat is that these routing tables
        need more compute power.

## Main Routing Protocols
    - IP(Internet Protocol) specifies the origin and destination for each data packet. Routers read this information
    - BGP(Border Gateway Protocol) announce which networks control which IP addresses, and which networks
    connect to each other. This is a dynamic routing protocol. 
        - The networks that make these announcements are knowns as autonomous systems(AS)

## Protocols used in an AS
    - OSPF(Open Shortest Path First): used by network routers to dynamically identify the fastest and shortest
    available routes for sending packets to their destination
    - RIP(Routing Information Protocol): "hop count" to find the shortest path from one network to another, where "hop count" means number of routers a packet must pass through on their way. 