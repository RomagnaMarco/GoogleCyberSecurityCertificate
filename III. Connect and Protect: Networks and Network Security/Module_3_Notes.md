# The Case for Securing Networks

## Common Network Intrusion Attacks
- **Malware:** Malicious software designed to damage or disrupt systems.
- **Spoofing:** Pretending to be another device or user on a network.
- **Packet Sniffing:** Intercepting and capturing network packets.
- **Packet Flooding:** Overloading a network with excessive traffic to cause disruption.

## Impact of Network Attacks on Organizations
- **Leaking Valuable or Confidential Information:** Sensitive data can be exposed to unauthorized parties.
- **Damaging an Organization's Reputation:** Loss of trust from customers, partners, and stakeholders.
- **Impacting Customer Retention:** Customers may leave due to concerns over data security.
- **Costing Money and Time:** Financial losses and the need for resources to mitigate and recover from attacks.

# How Intrusions Compromise Your System

## Network Interception Attacks
- **Packet Sniffing:** Malicious actors use hardware/software tools to capture and inspect data in transit.
  - Can see information they're not entitled to.
  - Can intercept network traffic and alter it.

## Backdoor Attack
- **Backdoor:** A less monitored workaround for an employee to bypass security measures. Often intentionally left to help programmers with troubleshooting or administrative tasks.
  - Vulnerable to hackers.
  - Can allow for extensive damage from hackers.

## Denial of Service (DoS) Attack
- **DoS:** An attack that targets a network or server and floods it with network traffic.

## Possible Impacts on an Organization
- **Financial:** Losses due to theft, downtime, or recovery efforts.
- **Reputation:** Damage to the organization's image and loss of trust.
- **Public Safety:** Risks to the safety of the public if critical systems are compromised.

# Denial of Service (DoS) Attacks

## Distributed Denial of Service Attack (DDoS)
- A type of denial of service attack that uses multiple devices or servers in different locations to flood the target network with unwanted traffic.

## SYN (Synchronize) Flood Attack
- A type of DoS attack that simulates a TCP connection and floods a server with SYN packets.
  - If SYN requests exceed the number of available ports on the server, it will be overwhelmed and unable to function.
  - TCP Handshake Process:
    1. --> SYN
    2. <-- SYN/ACK
    3. --> ACK
    4. TCP connection is established.

## Internet Control Message Protocol (ICMP)
- An internet protocol used by devices to tell each other about data transmission errors across the network.

## ICMP Flood
- A type of DoS attack performed by an attacker repeatedly sending ICMP packets to a network server.

## Ping of Death Attack
- A type of DoS attack caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64KB.

# Read tcpdump Logs

## Network Protocol Analyzer
- Also known as a packet sniffer, it is commonly used to investigate and monitor networks to identify suspicious activity.

## Common Analyzers
- SolarWinds NetFlow Traffic Analyzer
- ManageEngine OpManager
- Azure Network Watcher
- WireShark
- tcpdump

## tcpdump
- A command-line interface (CLI) network protocol analyzer providing a brief analysis of packets and converting key information about network traffic into a human-readable format.
- Lightweight (little memory and low CPU usage)
- Uses the open-source libpcap library
- Text-based for terminal
- Can be installed on Unix-based systems as well as Linux
- Prints packet information to terminal
- Displays source IP address, destination IP address, and used port numbers

## Information Received by a Packet Capture
- **Timestamp:** Hours, minutes, seconds, and fractions of a second format
- **Source IP:** Packet's origin via source IP address
- **Source Port:** The port number where the packet originated
- **Destination IP:** The destination IP address where the packet is being transmitted to
- **Destination Port:** The port number where the packet is being transmitted to

## Common Uses of tcpdump
- Establish a baseline for network traffic patterns and network utilization metrics
- Detect and identify malicious traffic
- Create customized alerts to send the right notifications when network issues or security threats arise
- Locate unauthorized instant messaging (IM) traffic or wireless access points

##  Botnet
- a collection of computers infected by malware and under control of a single threat actor, known as a bot-herder.
- this leads to a type of attack where the herder can have all the bots send packets to a target system resulting in a DDoS attack.

# Malicious packet sniffing

Malicious actors use packet sniffing to spy on packet data and use them to their advantage. They can also change data with a packet sniffer.

Two types of packet snifffing
- passive: where data packets are read in transit
- active: where data packets are manipulated in transit

To prevent packet sniffing:
- VPN Tunnel
- use HTTPS domain websites
- avoid unprotected Wifi in protected places (they don't use encryption)

# IP spoofing

IP spoofing: a network attack performed when an attacker changes the source IP of a data packet to impersonate an authorized system and gain access to a network.

## Common IP spoofing attacks
- On-path attack: malicious actor places themselves in the middle of an authorized connection and intercepts or altlers the data in transit
- Replay attack: malicious actor intercepts a data packet in transit and delays it or repeats it at another time.
- Smurf attack: an attacker sniffs an unauthorized user's IP address and floods it with packets

Firewalls can be configured to protect against IP spoofing and encryption should always be implemented to protect your data.

