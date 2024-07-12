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

Distributed Denial of Service attack (DDoS): a type of denial of service attack that uses multiple devices or servers in different locations to flood the target network with unwanted traffic.

SYN (synchronize) flood attack: a type of DoS attack that simulates a  TCP connection and floods a server with SYN packets.
- if SYN requests is > number of available ports on the server, then it will be overwhelmed and unable to function.

1. --> SYN
2. <-- SYN/ACK
3. --> ACK
4. TCP connection is established.

Internet Control Message Protocol (ICMP): internet protocol used be devices to tell each other about data transmission errors across the network.

ICMP Flood: a  type of DoS attack performed by an attacker repeatedly sending ICMP packets to a network server.

Ping of death attack: type of DoS attack caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64KB.

