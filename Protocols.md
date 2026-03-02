## Protocols

- There are many protocols for sending packets between devices on the same network(Ethernet)
    - For sending packets from network to network(IP)
    - For ensuring those packets successfully arrive in order(TCP)
    - For formatting data for websites and applications(HTTP)

- In addition, there are protocols for routing, testing, and encryption.
For example, UDP is used for streaming instead of TCP

## Physical Infrastructure that makes internet work

- Routers: Forward packets to different computer networks based on their destination
    - They ensure that traffic goes to the right network

- Switches: Connect devices that share a single network. 
    - Packet switching to forward packets to the correct devices.
    - Recieve outbound packets from those devices and pass them along to the right destination.

- Web Servers are specialized high-powered computers that store and serve content
(webpages, images, and videos) to users, in addition to hosting applications & databases

## Example when rendering a webpage

1) DNS query: When opening the browser, it likely first made a DNS query to find out the
website's IP address
2) TCP handshake: The browser opened a connection with the IP address
3) TLS handshake: Setup encryption between web server and device so that attackers can't read
the packes that travel between those two endpoints. 
4) HTTP request: The browser requested the content that appears on the webpage.
5) HTTP response: The server transmitted the content in the form of HTML, CSS, and Javascript
into multiple series of data packets. The device will verify it recieved all the packets, the 
browser interprets the code contained in the packets to render the article.