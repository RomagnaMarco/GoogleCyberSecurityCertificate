# Network Protocols

## Definition
Network Protocols: A set of rules used by two or more devices on a network to describe the order of delivery and the structure of the data.

## Key Protocols

### Transmission Control Protocol (TCP)
- **Purpose:** Used for connecting and streaming data directly between two endpoints.
- **Capabilities:** Handles routing over multiple devices.
- **TCP Handshake:** The verification of both devices before allowing further communications to take place.

### Address Resolution Protocol (ARP)
- **Purpose:** Determines the MAC address of the next router/device on the path.

### Hypertext Transfer Protocol Secure (HTTPS)
- **Purpose:** Provides a secure method of communication between clients and website servers.

### Domain Name System (DNS)
- **Purpose:** Translates internet domain names into IP addresses.

## Example of Network Communication (Going to a Website)
- **Protocols Used:**
  - TCP
  - ARP
  - HTTPS
  - DNS

## Security Protocols
- **HTTPS**
- **SSL/TLS**

# Common Network Protocols

## Categories of Protocols

### 1. Communication Protocols
Govern the exchange of information in internet transmission.
- **Responsibilities:**
  - How data is transmitted
  - Timing of communication
  - Methods of data recovery from transit
- **Examples:**
  - **TCP (Transmission Control Protocol):**
    - 3-way handshake: Synchronize (SYN) and acknowledgement (ACK) to establish handshake.
    - Transport Layer of TCP/IP model.
  - **UDP (User Datagram Protocol):**
    - Transport Layer of TCP/IP model.
  - **HTTP (Hypertext Transfer Protocol):**
    - Port 80, insecure.
    - Application Layer of TCP/IP model.
  - **DNS (Domain Name System):**
    - Normally port 53.
    - Application Layer of TCP/IP model.

### 2. Management Protocols
Monitor and manage devices on a network.
- **Responsibilities:**
  - Error reporting
  - Optimizing network performance
- **Examples:**
  - **SNMP (Simple Network Management Protocol):**
    - Used for monitoring and managing devices on a network.
    - Checks bandwidth usage.
    - Application Layer of TCP/IP model.
  - **ICMP (Internet Control Message Protocol):**
    - Used by devices to report data transmission errors across a network.
    - Useful in troubleshooting network connectivity and latency via Ping command.
    - Internet Layer of TCP/IP model.

### 3. Security Protocols
Ensure data is sent and received securely across a network.
- **Responsibilities:**
  - Use of encryption algorithms
- **Examples:**
  - **HTTPS (Hypertext Transfer Protocol Secure):**
    - Secure version of HTTP using SSL/TLS encryption on all transmissions.
    - Port 443.
    - Application Layer of TCP/IP model.
  - **SFTP (Secure File Transfer Protocol):**
    - Used to transfer files securely from one device to another over a network.
    - Uses Secure Shell (SSH) which employs Advanced Encryption Standard (AES) and other algorithms to prevent transmission interceptions.
    - Typically port 22.
    - Often used with cloud storage.

# Additional network protocols

 Internet Assigned Numbers Authority (IANA): assign some port numbers to protocols.

 Network Address translation
 1. Each device on your network has a private IP address to communicate amongst each other.
 2. to have these devices connect to the public internet, they need a single public IP address for all devices on the LAN for the public to see.
 3. Outgoing messages can have the priave Ip replaced by the public one via the router. The router can also reverse this process.

Network Address Translation (NAT):  generally requires a router or firewall specifically configured to perform NAT.
- is part of Layer 2 (internet) and 3 (transport) layers of the TCP/IP Model.

Private IP Addresses:
- Assigned by the Router
- Unique only within private network
- No cost to use
- Address ranges:
  - 10.0.0.0-10.255.255.255
  - 172.16.0.0-172.31.255.255
  - 192.168.0.0-192.168.255.255

Public IP Addresses:
- Assigned by the ISP and IANA
- Unique address in global internet
- Cost to lease a public IP address
- Assignable Address ranges:
  - 1.0.0.0-9.255.255.25
  - 11.0.0.0-126.255.255.255
  - 128.0.0.0-172.15.255.255
  - 172.32.0.0-192.167.255.255
  - 192.169.0.0-233.255.255.255
 
Dynamic Host Configuration Protocol (DHCP): The management family of network protocols. Its used on a network to configure devices.
- application layer protocol
- works with router to assign Unique IP addresses to each device
- provides the addresses of appropriate DNS server and default gateway for each device
- operate on UDP port 67
- HDCP clients operate on UDP port 68

IP addresses on a device can change over time, but a MAC address is permanent due it being on the network interface card.
Address Resolution Protocol (ARP) can help find an unknown MAC address. It translates IP addresses to MAC addresses  on the network access layer in TCP/IP model

Telnet: protocol used to create a secure connection with a remote system
- application layer in TCP/IP model
- sends in clear text
- uses CLE, not as secure as SSH.
- TCP Port 23
- connects to local or remomte devices

Secure shell protocol (SSH): used to create a secure connection with a remote system.
- application layer in TCP/IP model
- TCP port 22.
- replaces less secure protocols such as Telnet

Post Office Protocol (POP): used to manage and retrieve email from a mail server.
- application layer of TCP/IP model
- POP3 is most commonly used version.
- Refresh an email application to see new emails pop up is POP and internet message access protocol (IMAP)
- plaintext use TCP/UDP port 110
- encrypted use TCP/UDP port 995 via SSL/TLS

Internet Message Access Protocol (IMAP): used for incoming email. It downloads the headers of email and the message content.
- content also remains on email server, for multiple devices to access.
- uses TCP port 143 unencrypted
- uses TCP port 993 over TLS protocol

Simple Mail Transfer Protocol: used to transmit and rotue email from the sender to the recipient's address
- works with Message Transfer Afent (MTA) software: searches DNS servers to resolve email and IP addresses, ensuring they reach their destination.
- uses TCP/UDP port 25 for unencrypted, often used by high volume spam
- uses TCP/UDP port 587 for TLS encrypted
- helps filter out spam, regulating the number of emails able to be sent.




