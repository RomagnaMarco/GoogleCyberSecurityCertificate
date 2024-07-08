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
