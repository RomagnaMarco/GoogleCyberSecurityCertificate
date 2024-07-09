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




