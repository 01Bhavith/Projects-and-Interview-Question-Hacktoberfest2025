Basic Computer Networks Questions
---------------------------------
###1. What is a Computer Network?
**Answer:**  
  A computer network is a collection of interconnected devices (computers, printers, servers) that can communicate and share resources and data using physical or wireless media.​

###2. What are the different types of networks?
**Answer:**  
  >LAN (Local Area Network): Covers small areas like homes, offices, or schools.​

  >MAN (Metropolitan Area Network): Covers larger areas like cities.​

  >WAN (Wide Area Network): Covers large geographical areas like countries; the Internet is a WAN.​

  >PAN (Personal Area Network): Small network for personal devices like Bluetooth connections.​

###3. What is an IP Address?
**Answer:**  
An IP address is a unique numerical identifier assigned to each device on a network to enable communication. There are two versions: IPv4 (e.g., 192.168.1.1) and IPv6.​

###4. What are the different classes of IPv4 addresses?
**Answer:**  
>Class A: 1.0.0.0 to 126.255.255.255 (large networks)

>Class B: 128.0.0.0 to 191.255.255.255 (medium networks)

>Class C: 192.0.0.0 to 223.255.255.255 (small networks)

>Class D: Multicast addresses

>Class E: Reserved for experimental purposes.​

###5. What is the OSI Model?
**Answer:**  
The OSI (Open Systems Interconnection) model is a 7-layer conceptual framework that standardizes network communication:​

>Physical Layer

>Data Link Layer

>Network Layer

>Transport Layer

>Session Layer

>Presentation Layer

>Application Layer

###6. What is the difference between TCP and UDP?
**Answer:**  
>TCP (Transmission Control Protocol): Connection-oriented, reliable, ensures data delivery in correct order (used for emails, web browsing).​

>UDP (User Datagram Protocol): Connectionless, faster, no guarantee of delivery (used for streaming, gaming).​

###7. What is a MAC Address?
**Answer:**  
A MAC (Media Access Control) address is a unique hardware identifier assigned to a network interface card (NIC) by the manufacturer. It operates at the Data Link Layer (Layer 2).​

###8. What is DNS?
**Answer:**  
DNS (Domain Name System) translates human-readable domain names (like www.google.com) into IP addresses that computers use to identify each other on the network.​

###9. What is DHCP?
**Answer:**  
DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses and other network configuration parameters to devices on a network.​

###10. What is a subnet mask?
**Answer:**  
A subnet mask divides an IP address into network and host portions, helping to identify which part of the address refers to the network and which part refers to the host.​

Intermediate Questions
----------------------
###11. What is the difference between a router and a switch?
**Answer:**  
>Router: Connects different networks, operates at Layer 3 (Network Layer), uses IP addresses.​

>Switch: Connects devices within the same network, operates at Layer 2 (Data Link Layer), uses MAC addresses.​

###12. What is a gateway?
**Answer:**  
A gateway is a network device that acts as an entry/exit point between two different networks, often connecting a local network to the Internet.​

###13. What is Network Topology?
**Answer:**  
Network topology is the physical or logical arrangement of devices in a network. Types include Star, Bus, Ring, Mesh, and Hybrid topologies.​

###14. What is a VPN?
**Answer:**  
A VPN (Virtual Private Network) creates a secure, encrypted connection over a less secure network (like the Internet), enabling remote access and privacy.​

###15. What is NAT?
**Answer:**  
NAT (Network Address Translation) translates private IP addresses to public IP addresses, allowing multiple devices on a local network to share a single public IP address.​

###16. What is ARP?
**Answer:**  
ARP (Address Resolution Protocol) maps IP addresses to MAC addresses, enabling communication within a local network.​

###17. What is a firewall?
**Answer:**  
A firewall is a security device that monitors and controls incoming and outgoing network traffic based on predetermined security rules.​

###18. What are the different types of network cables?
**Answer:**  
>Twisted Pair (Ethernet cables): UTP, STP

>Coaxial Cable: Used for cable TV

>Fiber Optic Cable: High-speed data transmission using light.​

###19. What is bandwidth?
**Answer:**  
Bandwidth is the maximum rate of data transfer across a network path, typically measured in bits per second (bps).​

###20. What is latency?
**Answer:**  
Latency is the time delay between sending a data packet and receiving a response, measured in milliseconds.​

Advanced Questions
------------------
###21. What is the difference between HTTP and HTTPS?
**Answer:**  
>HTTP: Hypertext Transfer Protocol, data is transmitted in plain text

>HTTPS: Secure HTTP with SSL/TLS encryption for secure communication.​

###22. What is a proxy server?
**Answer:**  
A proxy server acts as an intermediary between a client and the Internet, providing anonymity, caching, and content filtering.​

###23. What is ICMP?
**Answer:**  
ICMP (Internet Control Message Protocol) is used for error reporting and diagnostic purposes, such as the ping command.​

###24. What is the three-way handshake in TCP?
**Answer:**  
TCP establishes a connection using three steps:

>SYN (client to server)

>SYN-ACK (server to client)

>ACK (client to server).​

###25. What is port forwarding?
**Answer:**  
Port forwarding redirects network traffic from one IP address and port to another, commonly used for remote access or hosting services.​

###26. What is a VLAN?
**Answer:**  
A VLAN (Virtual Local Area Network) segments a physical network into multiple logical networks for improved security and traffic management.​

###27. What is QoS?
**Answer:**  
QoS (Quality of Service) prioritizes certain types of network traffic to ensure performance for critical applications like VoIP or video streaming.​

###28. What is the difference between hub, switch, and router?
**Answer:**  
>Hub: Broadcasts data to all devices (Layer 1)

>Switch: Sends data only to the intended device (Layer 2)

>Router: Routes data between different networks (Layer 3).​

###29. What is IPv6 and why is it needed?
**Answer:**  
IPv6 is the newer version of the Internet Protocol with a 128-bit address space, designed to replace IPv4 due to address exhaustion.​

###30. What happens when you type www.google.com in your browser?
**Answer:**  
>Browser checks cache for IP address

>DNS query to resolve domain to IP

>TCP connection established (3-way handshake)

>HTTP/HTTPS request sent to server

>Server responds with web page data

>Browser renders the page.​

