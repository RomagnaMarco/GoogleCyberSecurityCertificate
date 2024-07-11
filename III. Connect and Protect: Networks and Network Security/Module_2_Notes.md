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

# Additional Network Protocols

## Internet Assigned Numbers Authority (IANA)
- Assigns port numbers to protocols.

## Network Address Translation (NAT)
- Each device on your network has a private IP address for internal communication.
- To connect to the public internet, devices need a single public IP address.
- NAT replaces private IP addresses with a public one via the router, which can also reverse this process.
- Requires a router or firewall configured for NAT.
- Operates in Layer 2 (Internet) and Layer 3 (Transport) layers of the TCP/IP model.

## IP Addresses

### Private IP Addresses
- Assigned by the router.
- Unique only within a private network.
- No cost to use.
- Address ranges:
  - 10.0.0.0 - 10.255.255.255
  - 172.16.0.0 - 172.31.255.255
  - 192.168.0.0 - 192.168.255.255

### Public IP Addresses
- Assigned by the ISP and IANA.
- Unique address on the global internet.
- Cost to lease a public IP address.
- Address ranges:
  - 1.0.0.0 - 9.255.255.25
  - 11.0.0.0 - 126.255.255.255
  - 128.0.0.0 - 172.15.255.255
  - 172.32.0.0 - 192.167.255.255
  - 192.169.0.0 - 233.255.255.255

## Dynamic Host Configuration Protocol (DHCP)
- Application layer protocol used to configure devices on a network.
- Works with the router to assign unique IP addresses to each device.
- Provides addresses of appropriate DNS servers and default gateway for each device.
- Operates on UDP port 67.
- DHCP clients operate on UDP port 68.

## Address Resolution Protocol (ARP)
- Translates IP addresses to MAC addresses on the network access layer in the TCP/IP model.
- Used to find an unknown MAC address.

## Telnet
- Protocol used to create a connection with a remote system.
- Application layer in the TCP/IP model.
- Sends data in clear text, less secure than SSH.
- Uses TCP port 23.

## Secure Shell Protocol (SSH)
- Protocol used to create a secure connection with a remote system.
- Application layer in the TCP/IP model.
- Uses TCP port 22.
- Replaces less secure protocols such as Telnet.

## Email Protocols

### Post Office Protocol (POP)
- Manages and retrieves email from a mail server.
- Application layer of the TCP/IP model.
- POP3 is the most commonly used version.
- Uses TCP/UDP port 110 for plaintext.
- Uses TCP/UDP port 995 for encrypted via SSL/TLS.

### Internet Message Access Protocol (IMAP)
- Manages and retrieves email from a mail server, downloading headers of emails and the message content.
- Content remains on the email server for access from multiple devices.
- Uses TCP port 143 for unencrypted.
- Uses TCP port 993 over TLS protocol.

### Simple Mail Transfer Protocol (SMTP)
- Transmits and routes email from the sender to the recipient's address.
- Works with Message Transfer Agent (MTA) software to resolve email and IP addresses, ensuring delivery.
- Uses TCP/UDP port 25 for unencrypted (often used by spam).
- Uses TCP/UDP port 587 for TLS encrypted.
- Helps filter out spam and regulates the number of emails sent.

# Wireless Protocols

## IEEE 802.11 (WiFi)
- A set of standards that define communication for wireless LANs.
- Developed by the Institute of Electrical and Electronics Engineers (IEEE).

## WiFi Protected Access (WPA)
- A wireless security protocol for devices to connect to the internet.
- WPA2 and WPA3 are newer versions with more advanced encryption and security.

# The Evolution of Wireless Security Protocols

## Wireless Ethernet Compatibility Alliance (WECA)
- Coined the term Wi-Fi.
- Renamed later to Wi-Fi Alliance.

## Wired Equivalency Privacy (WEP)
- Designed to provide the same level of privacy on wireless network connections as on wired network connections.
- Established in 1999, the oldest of wireless security standards.
- Flaws:
  - Weak protocol design.
  - Ineffective use of encryption.

## Wi-Fi Protected Access (WPA)
- Introduced in 2003 as a transitional measure to improve upon WEP.
- Uses Temporal Key Integrity Protocol (TKIP) to address WEP encryption weaknesses with larger keys.
- Includes integrity checks (message authentication tag with each transmission).
- Vulnerabilities:
  - Key Reinstallation Attacks (KRACK) to decrypt transmissions.
  - Attackers can insert themselves in the authentication handshake process and set the encryption key to all 0s, making it unencrypted.

## WPA2 & WPA3
- **WPA2:**
  - Introduced in 2004, uses Advanced Encryption Standard (AES) to improve on WPA.
  - Utilizes Counter Mode Cipher Block Chain Message Authentication Code Protocol (CCMP) for encapsulation, message integrity, and authentication.
  - Considered the security standard for all Wi-Fi transmissions today.
  - Vulnerabilities:
    - Still susceptible to KRACK attacks.
  - **WPA2 Personal:**
    - Best suited for home networks.
    - Easy to implement and faster setup than the enterprise version.
    - Not suitable for organizational use.
  - **WPA2 Enterprise:**
    - Best for business applications.
    - More complicated than personal mode but offers more individualized and centralized control over Wi-Fi access.
    - Admins can easily manage network access.
    - Users never have to access encryption keys, reducing the risk of exploitation.
- **WPA3:**
  - Addresses authentication handshake vulnerability to KRACK attacks.
  - Uses Simultaneous Authentication of Equals (SAE), a password-authenticated, cipher-key sharing agreement.
  - Offers increased encryption compared to WPA2, with 128-bit encryption for WPA3 Personal and 192-bit encryption for WPA3 Enterprise.

# Firewalls and Network Security Measures

## Firewall
A firewall is a network security device that allows or blocks traffic based on a defined set of security rules.

### Port Filtering
Port filtering is a firewall function that blocks or allows certain port numbers to limit unwanted communication.

### Firewall Types
- **Hardware:**
  - Inspects each data packet before allowing it to go to the network.
- **Software:**
  - Functions like a hardware firewall but as a software application installed on a computer or server.
  - Typically costs less than a separate device but adds some processing burden to individual devices.
- **Cloud-based:**
  - Functions like software firewalls but hosted by a cloud provider.

### Firewall Classes
- **Stateful:**
  - Keeps track of information passing through it and proactively filters out threats.
- **Stateless:**
  - Operates based on predefined rules and does not keep track of information from data packets.
  - Only acts according to preconfigured rules set by the firewall admin.
  - Considered less secure than stateful firewalls.

### Next Generation Firewalls (NGFWs)
#### Benefits:
- **Deep Packet Inspection:**
  - Analyzes the data part (and possibly the header) of a packet as it passes an inspection point.
- **Intrusion Protection:**
  - Detects and prevents cyber threats and attacks.
- **Cloud-based Threat Intelligence Services:**
  - Leverages cloud-based intelligence to identify and mitigate threats.

# Virtual Private Networks (VPNs)

## VPN
A VPN (Virtual Private Network) is a network security service that changes your public IP address and hides your virtual location to keep your data private when using a public network like the internet.
- **Encryption:** Encrypts your data in transit.
- **Encapsulation:** Encapsulates your data in transit.

### Encapsulation
Encapsulation is a process performed by a VPN service that protects your data by wrapping sensitive data in other packets.
- Allows for your personal data to be encrypted while letting the router know the destination.

### VPN Tunnel
A VPN tunnel is an encrypted tunnel between your device and the VPN server, which is unhackable without a cryptographic key.

# Security Zone

## Security Zone
A security zone is a segment of a network designed to protect the internal network from the internet. It is a part of network segmentation.

### Network Segmentation
Network segmentation is a security technique that divides the network into segments.
- Different organizations will have different subnets for different groups.
- Allows administrators to isolate issues in one network segment and prevent contamination of others.

### Types of Security Zones
- **Uncontrolled Zone:** Any network outside the organization's control.
- **Controlled Zone:** A subnet that protects the internal network from the uncontrolled zone.

### Areas in the Controlled Zone
1. **Demilitarized Zone (DMZ)**
2. **Internal Network**
3. **Restricted Zone**

### Example Layout

Internet - Firewall - DMZ - Firewall - Internal Network - Firewall - Restricted Zone

# Subnetting and CIDR

## Subnetting
Subnetting is the subdivision of a network into logical groups called subnets.
- **Concept:** Like a network inside a network.
- **Function:** Divides address range into smaller subnets within the network, which form based on the IP addresses and network mask of the devices on the network.
- **Benefit:** Creates a network of devices to function as its own network, making the network more efficient and able to create security zones.

## Classless Inter-Domain Routing Notation (CIDR)
CIDR is a method of assigning subnet masks to IP addresses to create a subnet.
- **Replacement:** Replaces classful addressing.
- **Function:** Allows professionals to segment classful networks into smaller chunks.
- **Format:** CIDR IP addresses are formatted like IPv4 addresses but include a / followed by a number at the end of the address (known as the IP network prefix).
- **Benefits:**
  - Reduces the number of entries in routing tables.
  - Provides more available IP addresses within networks.

## Benefits for Security
- **Network Creation:** With subnetting, professionals can create a network within their own network without requesting another network IP address from their ISP.
- **Bandwidth Efficiency:** Uses network bandwidth more efficiently.
- **Performance:** Improves network performance.

# Proxy Servers

Proxy servers: a server t hat fulfills the request of a client by forwarding them on to other servers
- sits between the internet and the rest of the network.
- uses temporary memory to store common data to prevent fetching data from internal servers each time.

Different types of proxy servers:
- forward: regulates and restricts a person's access to the internet
- reverse: regulates and restricts the internet's access to an internal server
- email: filters spam email by verifying whether a sender's address was forged.




