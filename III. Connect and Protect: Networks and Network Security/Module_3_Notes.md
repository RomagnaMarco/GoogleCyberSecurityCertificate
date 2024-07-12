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

# Read tcpdump logs

Network protocol analyzer: AKA a packet sniffer is commonly used to investigate and monitor networks to identify suspicious activity.

Common analyzers:
- SolarWinds NetFlow  Traffic Analyzer
- MangeEngine OpManager
- Azure Network Watcher
- WireShark
- tcpdump

tcpdump: a CLE network protocol analyzer, providing a brief analysis of packets and converts key info about network  traffic into a human readable format.
- lightweight (little memory and low CPU usage)
- open source libpcap library.
- text based for terminal
- can be installed on Unix-based systems as well as Linux
- prints packet info to terminal
- displays source IP address, destination IP address, used port numbers

Information recieved by a packet capture includes:
- Timestamp: hours, minutes,  seconds, and fractions of a second format
- Source IP: packets origin via source IP address
- Source Port: the port number where the packet originated
- Destination IP: the destination IP address where the packet is being transmitted to
- Destination Port: the port number wher ethe packet is being transmitted to.

Common uses of tcpdump:
- establish a baseline for network traffic patterns and network utilization metrics
- detect and identify malicious traffic
- create customized alerts to send the right notifications when network issues or security threats arise
- locate unauthorized instant messaging (IM), traffic, or wireless access points


