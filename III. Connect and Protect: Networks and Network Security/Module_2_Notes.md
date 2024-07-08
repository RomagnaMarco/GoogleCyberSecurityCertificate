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

3 main categories of protocols:
- Communication: govern exchange of information in internet transmission.
  - how data is transmitted
  - handle timing of communication
  - methods of data recovery from transit
  - Include
    - TCP: 3 way handshake, Synchronize (SYN) and acknowledgement (ACK) to establish handshake. Transport Layer of TCP/IP model
    - UDP: Transport Layer of TCP/IP model
    - HTTP: Port 80, insecure. Application Layer of TCP/IP model
    - DNS : normally port 53, application layer of TCP/IP model
- Management: monitoring and managing devices on a network
  - include protocols for error reporting and optimizing network performance
  - Include:
    - Simple Network Management Protocol (SNMP): used for monitoring and managing devices on a network. Checks Bandwidth usage. Application layer of TCP/IP model
    - Internet Control Message Protocol (ICMP): used by devices to tell each other about data transmission errors across a network. useful in troubleshooting network connectivity and latency via Ping command. Internet Layer of TCP/IP model
- Security: ensure data is sent and recieved securely across a network
  -  use encryption algorithms
  -  Includes:
    - HTTPS: Secure version of HTTP, secure sockets layer/transport layer security (SSL/TLS) encryption on all transmissions. Port 443. Application layer of TCP/IP model
    - Secure File Transfer Protocol (SFTP): used to transfer files from one device to another over a network. uses secure shell(SSH) which uses Advanced Encryption Standard (AES) and others to prevent transmission interceptions. Typically port 22. Often used with cloud storage.
 


- 
