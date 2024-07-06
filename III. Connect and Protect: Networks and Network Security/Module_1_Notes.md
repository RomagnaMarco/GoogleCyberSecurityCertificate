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

# Learn more about the TCP/IP Model










