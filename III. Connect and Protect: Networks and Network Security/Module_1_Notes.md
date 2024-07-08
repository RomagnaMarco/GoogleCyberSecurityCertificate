# What are Networks?

**Network:** A group of connected devices.

The devices can communicate with each other through cables or wirelessly. IP and MAC addresses ensure the devices communicate with each other correctly.

## Devices Can Communicate On:
- **Local Area Network (LAN):** Spans a small area like an office building, school, or home.
- **Wide Area Network (WAN):** Spans a large geographic area like a city, state, or country.

The internet can be considered one big WAN.

# Network Tools

## Hardware Devices

**Hub:**
- A network device broadcasting information to every device on the network.

**Switch:**
- Makes connections between specific devices on a network by sending and receiving data between them.
- More secure than a hub.

**Router:**
- A network device connecting multiple networks together.

**Modem:**
- Connects your router to the internet and brings internet access to the LAN.

## Virtualization Tools
- Pieces of software that perform network operations.
- Offered by cloud service providers.

# Network Components, Devices, and Diagrams

## Network Identifiers
- **MAC Address:** Identifies devices on a network at the hardware level.
- **IP Address:** Identifies devices on a network at the network level.

## Network Interfaces
- Each device has a network interface that sends and receives data packets.

## Network Security Devices

**Firewalls:**
- A network security device that monitors traffic to or from your network.
- Restricts data like a border patrol.
- Positioned between the secured internal network and untrusted external network resources.

## Servers and Clients

**Servers:**
- Provide information and services to devices on the network.
- A client device connects to the server, which may get data from a database it is connected to.

## Traffic Management

**Hubs and Switches:**
- **Hubs:** Direct traffic for local networks by broadcasting information to all connected ports.
- **Switches:** Send data specifically to a MAC address, making them more efficient and secure than hubs.

**Routers:**
- Operate on the network layer in the TCP/IP model.
- Forward packets to the next router on the path to the destination based on IP header information.

## Connectivity

**Internet Service Provider (ISP):**
- Connects your home/office to the internet via coaxial cables or telephone lines.

**Wireless Access Points:**
- Send and receive digital signals over radio waves, creating a wireless network.

**Wi-Fi:**
- A set of standards used by network devices to communicate wirelessly.

## Network Diagrams
- Maps showing network devices and how they connect.
- Use graphics and dotted lines to represent connections and relationships.

# Cloud Networks

A cloud model helps companies reduce costs and streamline network operations.

## Cloud Computing
- **Definition:** The practice of using remote servers, applications, and network services hosted on the internet instead of on local physical devices.

## Cloud Network
- **Definition:** A collection of servers or computers that store resources and data in remote data centers, accessible via the internet.

## Cloud Services Providers Offer:
- **On-Demand Storage**
- **Processing Power**
- **Analytics**

# Cloud Computing and Software Defined Networks

## Cloud Service Provider (CSP)
- A company offering cloud computing services.
- Companies can pay for the storage and services they need and consume them through the CSP's API or web console.

## Cloud Service Models

**Software as a Service (SaaS):**
- A software suite operated by the CSP that a company can use remotely without hosting the software.

**Infrastructure as a Service (IaaS):**
- The use of virtual computer components offered by the CSP.

**Platform as a Service (PaaS):**
- Tools that application developers can use to design custom applications for their company.

### IaaS
- Physical Data Center
- Servers, Networking, Storage

### PaaS
- Operating Systems
- Database Management & Development Tools
- Includes IaaS

### SaaS
- Cloud-Hosted Applications
- Includes PaaS

## Hybrid and Multi-Cloud Environments

**Hybrid Cloud Environment:**
- Using CSP services in addition to on-premise computers, networks, and storage.

**Multi-Cloud Environment:**
- Organizations using more than one CSP.

## Software-Defined Networks (SDN)
- Made up of virtual network devices and services.
- Provide virtual switches, routers, firewalls, and more.

## Benefits of Cloud Computing and Software-Defined Networks

**Reliability:**
- Allow employees and customers to access the resources they need consistently and with minimal interruption.

**Cost:**
- Offers virtual devices and services at fractional costs required for companies to install, patch, upgrade, and manage components and software themselves.

**Scalability:**
- No longer need to upgrade or downgrade physically.
- Use an elastic model and pay for what they need.

# Introduction to Network Communication

Data is sent through a network in the form of data packets.

## Data Packet
A basic unit of information that travels from one device to another within a network.
- **Header:** Contains IP address, MAC address, Protocol Number
- **Body:** Contains the message
- **Footer:** Contains the signature

## Key Concepts

**Bandwidth:**
- The amount of data a device receives every second.

**Speed:**
- The rate at which data packets are received or downloaded.

If either bandwidth or speed are irregular, it can be a sign of an attack.

**Packet Sniffing:**
- The practice of capturing and inspecting data packets across a network.

# The TCP/IP Model

**Transmission Control Protocol and Internet Protocol (TCP/IP):** The standard model used for network communication.

## Transmission Control Protocol (TCP)
- An internet communication protocol that allows two devices to form a connection and stream data.
- Includes a set of instructions to organize data.
- Establishes a connection between two devices and ensures that packets reach the correct destination.

## Internet Protocol (IP)
- A set of standards used for routing and addressing data packets as they travel between devices on a network.
- The IP address functions as an address for each private network.

## Ports

**Port:**
- A software-based location that organizes the sending and receiving of data between devices on a network.
- Divides network traffic into segments based on the service they will perform between two devices.

**Port Number:**
- Allows computers to split the network traffic and prioritize operations they will perform with the data.
- These are part of the instructions in data packets.

### Notable Port Numbers
- **25:** Email
- **443:** Secure internet communication
- **20:** Large file transfers

# The Four Layers of the TCP/IP Model

The TCP/IP model is a framework used to visualize how data is organized and transmitted across the network.

## 4 Layers of the TCP/IP Model

### 1. Network Access Layer
- Responsible for the creation of data packets and their transmission across a network.

### 2. Internet Layer
- IP addresses are attached to data packets to indicate the sender and receiver.
- Focuses on how networks connect to each other.

### 3. Transport Layer
- Protocols control the flow of traffic across a network.
- They permit or deny communication with other devices and include information about the status of the connection.

### 4. Application Layer
- Protocols determine how the data packets will interact with receiving devices.
- Includes services such as file transfers and email services.

# Learn More About the TCP/IP Model

## Network Access Layer
- **HTTP**
- **TLS**
- **DNS**

This layer is also known as the Data Link Layer. It includes the physical hardware.

**Address Resolution Protocol (ARP):**
- Maps IP addresses to MAC addresses for local network communication.

## Internet Layer
- **IP (v4, v6)**

This layer is also known as the Network Layer. It determines which protocol is responsible for delivering data packets and ensures their delivery to the destination host.

**Common Protocols:**
- **Internet Protocol (IP):** Sends data packets to the correct destination and relies on TCP/UDP to deliver them to the corresponding service.
- **Internet Control Message Protocol (ICMP):** Shares error information and status updates of data packets. Useful for detecting and troubleshooting network errors. Reports information about dropped packets, network connectivity issues, and packets redirected to other routers.

## Transport Layer
- **TCP:** Internet communication protocol that allows two devices to form a connection and stream data.
  - Reliable
  - Includes the port number of the destination service in the packet header.
- **UDP:** Connectionless protocol that does not establish a connection between devices before transmission.
  - Used for non-reliability based needs.
  - Not tracked extensively.
  - Suitable for performance-sensitive applications in real-time (e.g., video streaming).

## Application Layer
- **Hypertext Transfer Protocol (HTTP)**
- **Simple Mail Transfer Protocol (SMTP)**
- **Secure Shell (SSH)**
- **File Transfer Protocol (FTP)**
- **Domain Name System (DNS)**

This layer is similar to the Application, Presentation, and Session layers of the OSI model. It defines which internet services and applications any user can access.

## OSI Model
- Visualizes network protocols into different layers.
- Often used to communicate potential sources of security threats when they occur.
- More complex version of the TCP/IP model.

# The OSI Model

The OSI Model is made up of 7 Layers:

## 7. Application
- Includes all the networking protocols that software applications use to connect users to the internet.
- **Purpose:** User connection to the internet via applications and requests.
- **Examples:**
  - Web Browser using HTTP/HTTPS to send/receive information from the website server.
  - Email application using Simple Mail Transfer Protocol (SMTP).
  - Web browser using Domain Name System (DNS) to translate domain names into IP addresses to identify web server hosts.

## 6. Presentation
- Involves data translation and encryption for the network.
- **Purpose:** Adds to and replaces data with formats that can be understood by applications (layer 7) on both sending and receiving systems.
- **Processes:** Require the use of a standardized format.
- **Examples:** Encryption, compression, confirmation that the character code can be interpreted on the receiving system.

## 5. Session
- Manages sessions between two devices.
- **Purpose:** Keeps the session open while data is being transferred and terminates the session once the transmission is complete.
- **Responsibilities:** Authentication, reconnection, and setting checkpoints during a data transfer.
- **Example:** If a session is interrupted, checkpoints ensure that the transmission picks up at the last session checkpoint when the connection resumes.

## 4. Transport
- Responsible for delivering data between devices.
- **Purpose:** Handles the speed of data transfer, flow of the transfer, and breaking data down into smaller segments to make them easier to transport.
- **Examples:** TCP, UDP.
- **Segmentation:** The process of dividing up a large data transmission into smaller pieces that can be processed by the receiving system.

## 3. Network
- Oversees receiving the frames from the Data Link layer (layer 2) and delivers them to the intended destination.
- **Purpose:** Finds the intended destination based on the address that resides in the frame of the data packets.

## 2. Data Link
- Organizes sending and receiving data packets within a single network.
- **Purpose:** Manages switches on the local network and network interface cards on local devices.
- **Examples:** Network Control Protocol (NCP), High-Level Data Link Control (HDLC), Synchronous Data Link Control Protocol (SDLC).

## 1. Physical
- Corresponds to the physical hardware involved in network transmission.
- **Purpose:** Manages the actual hardware used in data transmission.
- **Examples:** Hubs, modems, and the cables and wiring that connect them.
  - **Process:** To travel across an Ethernet or coaxial cable, a data packet needs to be translated into a stream of 0s and 1s. The stream of 0s and 1s is sent across the physical wiring and cables, received, and then passed on to higher levels of the OSI model.

# IP Addresses and Network Communication

**IP Address:** A unique string of characters that identifies the location of a device on the internet.
- Can be public or private.
- Your Internet Service Provider (ISP) assigns a public IP address connected to your geographic location.
- Private IP addresses are only seen by other devices on the same network.

## Types of IP Addresses

### IPv4
- Written as four 1, 2, or 3 digit numbers separated by a decimal point.
- Used for all IPs in the early days of the internet.
- **Example:** 19.117.63.126

### IPv6
- Made of 32 characters.
- **Example:** 684D:1111:222:3333:4444:5555:6:77

**MAC Address:** A unique alphanumeric identifier assigned to each physical device on a network.

## MAC Address Table
- Functions like an address book.
- Used by a switch to direct data packets to the right device by binding the MAC addresses to ports.

# Components of Network Layer Communication

## Format of an IPv4 Packet

### IPv4 Packet Structure
- **Header:** 20-60 bytes
- **Data:** 20-65,535 bytes

### 13 Fields within the Header of an IPv4 Packet
1. **Version (VER):** 
   - Tells receiving devices what protocol the packet is using.
   - 4-bit component.
2. **IP Header Length (HLEN or IHL):**
   - Indicates the packet’s header length, marking the start and end of the header in the data segment.
   - 4-bit component.
3. **Type of Service (ToS):**
   - Provides the router with information on prioritizing packets for delivery.
   - 8-bit component.
4. **Total Length:**
   - Communicates the total length of the entire IP packet, including header and data.
   - Maximum size of an IPv4 packet is 65,535 bytes.
5. **Identification:**
   - Provides a unique identifier for all separated fragments of the original IP packet to be reassembled once they reach their destination.
6. **Flags:**
   - Provides routing devices with more information, such as if it has been fragmented or the amount of fragments in transit.
7. **Fragmentation Offset:**
   - Tells routing devices where in the original packet the fragment belongs.
8. **Time to Live (TTL):**
   - Contains a counter set by the source.
   - Decremented as it passes through each router along its path.
   - When it reaches zero, the router holding the packet will discard it and return an ICMP time exceeded error message to the sender.
9. **Protocol:**
   - Tells the receiving device which protocol will be used for the data portion of the packet.
10. **Header Checksum:**
    - Contains a checksum that can be used to detect corruption of the IP header in transit.
    - Corrupted packets are discarded.
11. **Source IP Address:**
    - The IPv4 address of the sending device.
12. **Destination IP Address:**
    - The IPv4 address of the receiving device.
13. **Options:**
    - Allows for security options to be applied to the packet if the HLEN value is greater than five.
    - Communicates these options to the routing devices.

## Differences Between IPv4 and IPv6

- **Address Length and Format:**
  - IPv4: Up to 4.3 billion possible addresses.
  - IPv6: Up to 340 undecillion addresses.
- **Routing Efficiency:**
  - IPv6 offers more efficient routing and eliminates private address collisions (two devices on the same network attempting to use the same address).
- **Header Layout:**
  - IPv6 header is simpler.
  - **IPv6 Header Fields:**
    - Version, Traffic Class, Flow Label
    - Payload Length, Next Header, Hop Limit
    - Source Address
    - Destination Address
