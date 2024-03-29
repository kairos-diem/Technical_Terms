<h2> Terms & Definitions </h2>

1. Endpoints - Any devices that are used to connect to the network.
2. Servers - The computers or systems like google which take the request from the client and does the appropriate action to get the desired result.
3. OSI and TCP/IP model - OSI is the 7 layer model which is used to understand how a networking application works. TCP/IP model is a much more simplified version with 4 layers.
4. IP address - These are a set of numbers which uniquely identify a system on the network. They can be either IPv4 or IPv6.
5. Ports - They are responsible for receiving the appropriate packets according to the protocols that are being used. Might also be reffered as IPv4 sockets.
6. DNS - Domain naming system is responsible for translating domain names into specific IP address.
7. TCP Handshake - https://www.guru99.com/tcp-3-way-handshake.html
8. SSL Handshake - https://www.ssl.com/article/ssl-tls-handshake-overview/
9. Types of DNS records: <br/>
  a. A record - Indicates the ip address. <br/>
  b. AAAA record - Indicates the IPv6 address. <br/>
  c. CNAME record - Indicates the canonical name or the domain name associated with it. <br/>
  d. NS record - Indicates the authoritative DNS server to look to find the particular domain address to the ISP.<br/>
  e. MX record - Indicates the mail exchange record and directs the incoming mail of the domain. <br/>
10. Multiplexing - Sending multiple signals in a single channel.
11. TCP - Transmission control protocol is used for connection-oriented, reliable delivery and flow control situations. Think of website surfing.
12. UDP - User Datagram Protocol is used for connectionless, unreliable delivery and no flow control is required. Think of brodcasting or streaming.
13. Common Ports <br/>
  a. port 23 - Telnet - clear text remote login. <br/>
  b. port 22 - SSH - Encrypted remote login. <br/>
  c. port 25 - SMTP - Sending mail. <br/>
  d. port 53 - DNS - Domain name to IP address. <br/>
  e. port 20 - FTP - File transfers. <br/>
  f. port 80 - HTTP - web server. <br/>
  g. port 443 - HTTPS - encrypted web server. <br/>
  h. port 3389 - RDP - Remote Desktop protocol. <br/>
  i. port 445 - SMB - Shared file. <br/>
14. MAC address - Physical address associated with each device. Media Access Conrol address.
15. Duplex - Sending and receiving data simultaneously.
16. Switch - A device used to forward or drop frames to devices rather than networks, it also updates the list of MAC addresses and maintain a loop free environment.
17. Unicasts - one to one communication. Web browsing, file transfer and so on. 
18. Broadcast - one to all communication. Limited scope, IPv4, radio, newsletter.
19. Multicast - one to many not all communication. Multimedia delivery, stock exchanges and so on.
20. Network trunk - A communications line or link designed to carry multiple signals simultaneously to provide network access between two points.
21. Tunneling - A way to send private communication packets through public networks by way of encapsulation.
22. Tagged and Untagged VLANs - A tagged VLAN is used to pass data to other/multiple VLAN networks and untagged VLAN is used to access a single VLAN.
23. IGP - Interior Gateway protocol is used for routing within an autonomous system network. Example:RIP, OSPF,...
24. EGP - Exterior Gateway Protocol is used for routing between two or more autonomous system networks. Example:BGP.
25. Access control list (ACL) - a list of rules that specifies which users or systems are granted or denied access to a particular object or system resource.
26. Port mirroring - The process of sending the packets of one switch port to another switch port.
27. Static routing - Manually configure pre-defined pathways. Pros: No overhead, easy to configure and more secure. Cons: Difficult on large networks, no automatic loop prevention, no automatice rerouting on outages and manually update changes.
28. Dynamic routing - Automatic routing. Pros: No manual management, automatically add new routing and scaling. Cons: Higheroverhead and more initial configuration.
29. IPv4 - Internet Protocol version 4. Size is 32 bits or 4 bytes. 4 octets
30. IPv6 - Internet Protocol version 6. Size is 128bits or 16 bytes. Hexa-decimal notation. 8 octets.
31. Dual Stack routing - The process of configuring both ipv4 and ipv6 in the same network.
32. Tunneling - The process of sending packets of one format into another format for security or other purposes.
33. NDP - Neighbour discovery protocol. Used in IPv6.
34. Packet Shaping - The process of limiting bandwidth that can be consumed by certain applications to ensure high performance for critical applications.
35. Class of service - A way of managing traffic in a network by grouping similar types of traffic like email, VoIP, file transfer, ...
36. DSCP - Differentiated Service Code Point, It is a mechanism for classifying network traffic in an IP network using the DS or DSCP field.
37. Circuit Switching - It is similar to telephone service where once established is not removed until the whole conversation or transmission has ended.
38. Packet Switching - It is more dynamic. Data is grouped and send over the network, It requires more bandwidth.
39. SDN - Software Defined Networking is much more programmable and as the name suggests directly programmed and configured. It is also centrally managed.
40. Distributed switching - It is a hierarchical model of switching with a central switch and other switches are distributed between the endpoints.
41. Loopback address - It is an address that refers back to yourself.
42. Z-wave - It is a wireless, radio frequency based communication technology designed particularly for control, monitoring and status reading of household applications. Prominent in the IoT space.
43. Hub - A network hardware device for connecting multiple Ethernet devices together and making them act as a single network segment. Works in layer 1 of OSI model.
44. Bridge - A device used to connect multiple LANs together with a larger Local Area Network (LAN). It is a layer 2 device.
45. Switch - A network switch connects devices in a network to each other, enabling them to talk by exchanging data packets. A switch can be layer 2 or layer 3.
46. Router - A device used to connect different networks together and sends data packets from one network to another. It is used in layer 3.
47. NAS - Network-attached storage is a file-level computer data storage server connected to a computer network providing data access to a heterogeneous group of clients. Connected using normal ethernet.
48. SAN - A storage area network or storage network is a computer network which provides access to consolidated, block-level data storage. Major difference is use of specialised fibre optic channels.
49. Jumbo frame - They are Ethernet frames with more than 1500 bytes of payload, the limit set by the IEEE 802.3 standard. Commonly, jumbo frames can carry up to 9000 bytes of payload, but smaller and larger variations exist and some care must be taken using the term.
50. Types of recovery sites <br/>
 a. Cold site - It is an empty building with only racks, no hardware, no data and no people. <br/>
 b. Warm site - Between a hot and cold site where the hardware is ready and waiting. <br/>
 c. Hot Site - Its an exact replica of the production system with both hardware, data and people. <br/>
51. RADIUS protocol - It provides centralized authentication services to the servers through which remote users connect to the network.
52. EAP - Extensible Authentication Protocol. It is used to pass authentication information between the client and the authentication server.
53. DDoS Amplification - Multiplying the effect of DDoS by reflecting it off another device.
54. Switch Spoofing VLAN hopping - Switch spoofing is a type of VLAN hopping attack that works by taking advantage of an incorrectly configured trunk port.
55. Double tagging VLAN hopping - This type of attack takes advantage of the way that hardware on most switches operates. Most switches perform only one level of 802.1Q de-encapsulation, which allows an attacker to embed a hidden 802.1Q tag inside the frame. This tag allows the frame to be forwarded to a VLAN that the original 802.1Q tag did not specify.
56. Man in the browser -  A proxy Trojan horse[1] that infects a web browser by taking advantage of vulnerabilities in browser security to modify web pages, modify transaction content or insert additional transactions, all in a covert fashion invisible to both the user and host web application. 
 
