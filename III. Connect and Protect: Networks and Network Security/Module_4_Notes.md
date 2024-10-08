# Security Hardening

**Security Hardening**: the process of strengthening a system to reduce the vulnerability and attack surface.
- operated on:
  - Hardware
  - OS
  - applications
  - computer networks
  - Databases 

**Attack Surface**: all the possible vulnerabilities and threat actor could exploit.
**Penetration Testing** (Pen testing): a simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processess.

Security professionals will regularly maintain security hardening procedures to keep devices secure.
- physical security includes areas with security cameras or guards
- software updates (Patches) are common
- Pen testing
- remove unused ports, applications, or services and minimized access to reduce attack surface.

# OS Hardening

**Operating System (OS):** Interface between hardware and the user.
- The first program loaded when a PC turns on.

**Hardening tasks:**
- Performed only once as part of preliminary safety measures.
- Performed at regular intervals:
  - **Patch Update:** A software and operating system update that addresses security vulnerabilities within a program or product.
  - **Hardware and software disposal**
  - **Strong password policy**
  
**Baseline configuration (baseline image):** A documented set of specifications within a system that is used as a basis for future builds, releases, and updates.

**Multifactor authentication (MFA):** A security measure that requires a user to verify their identity in two or more ways to access a system or network.
- Something you know
- Something you have
- Something unique about you

# Brute Force Attacks and OS Hardening

**Brute Force Attack:** A trial and error process of discovering private information.
- **Simple:** Guessing.
- **Dictionary:** List of commonly used passwords and stolen credentials from previous breaches.

**Virtual Machines (VMs):** Software versions of physical computers.
- Add a layer of security by running code in an isolated environment.
  - Can be deleted and replaced with a new VM image after testing malware.
- Useful to investigate infected machines or to run malware.
- Ability to revert to previous states.
- Small risk that a malicious program can escape virtualization and access the host machine.

**Sandbox Environments:** Used for testing software or programs separately from your network. They can be either physical PCs or cloud-based VMs.
- Test patches.
- Identify bugs.
- Detect cybersecurity vulnerabilities.
- Evaluate suspicious software or malicious code.
- Simulate attack scenarios.

**NOTE:** Attackers can program their malware to behave as harmless software when run inside sandbox environments via certain detection methods.

**Prevention Measures:**
- **Hashing:** Converts information into a unique value that can be used to determine its integrity. A one-way function, making decryption impossible.
- **Salting:** Adds random characters to hashed passwords, increasing their complexity and thus security.
- **MFA / 2FA:** Requires several verifications to ensure a user is who they say they are in order to access a system or network.
- **CAPTCHA:** Completely Automated Public Turing test to tell Computers and Humans Apart.
- **reCAPTCHA:** Free CAPTCHA service from Google that helps protect websites from bots and malicious software.
- **Password Policies:** Guidelines on how long or complex a password should be, when to update it, and the maximum number of login attempts.

# Network Hardening

## **Network Security Hardening:**
- **Port Filtering:** 
- **Network Access Privilege:** 
- **Encryption:** 

### **Tasks Performed:**
- **Firewall Rules Maintenance:** Regularly updating and managing firewall rules to control network traffic.
- **Network Log Analysis:** The process of examining network logs to identify events of interest.
- **Patch Updates:** Ensuring that all network devices and software are up to date with the latest security patches.
- **Server Backups:** Regular backups of server data to ensure data integrity and availability.

### **Network Log Analysis:**
- **Security Information and Event Management (SIEM) Tool:** An application that collects and analyzes log data to monitor critical activities in an organization.

### **Tasks Performed Once:**
- **Port Filtering:** A firewall function that blocks or allows certain port numbers to limit unwanted communication.
- **Network Segmentation:** Creates isolated subnets for different departments in an organization. This limits issues to their own subnet and restricts user access to each network.
  - Can also separate different security zones.

### **Encryption:**
- All network communication should be encrypted using the latest encryption standards.

# Network Security Applications

## **Firewall:**
- **Function:** Blocks or allows traffic based on a set of rules. When data packets enter a network, the firewall checks their packet header and decides to allow or deny access based on its port number.
- **Types:**
  - **Stateful:** Tracks the state of active connections and makes decisions based on the context of the traffic.
  - **Stateless:** Makes decisions based on the individual packets without considering the state of the connection.
  - **NGFW (Next-Generation Firewall):** Includes advanced features like application awareness, integrated intrusion prevention, and cloud-delivered threat intelligence.

## **Intrusion Detection System (IDS):**
- **Function:** Monitors system activity and alerts on possible intrusions by detecting malicious traffic signatures.
- **Key Features:**
  - Detects known attacks after configuration.
  - Sniffs data packets as they move across the network.
  - Alerts admins of suspicious activity.
- **Limitations:** 
  - Only scans for known attacks or obvious anomalies.
  - Does not stop incoming traffic; it only alerts.

## **Intrusion Prevention System (IPS):**
- **Function:** Monitors system activity for intrusive activity and takes action to stop the activity.
- **Key Features:**
  - Provides more protection than IDS by stopping anomalies when detected.
  - Sits behind the firewall in the network architecture, disrupting the data stream before it reaches sensitive parts of the network.
- **Limitations:**
  - Inline operation means if it fails, the connection between the private network and the internet can be interrupted.
  - Possibility of false positives, which can drop legitimate traffic.

## **Full Packet Capture Devices:**
- **Function:** Records and analyzes all the data transmitted over a network.
- **Purpose:** Aids in the investigation of IDS alerts by providing a complete view of the network traffic.

## **Security Information and Event Management (SIEM):**
- **Function:** Works in real-time to report suspicious activity through a centralized dashboard.
- **Key Features:**
  - Analyzes network data sourced from IDSs, IPSs, firewalls, VPNs, proxies, and DNS logs.
  - Aggregates security data to provide a comprehensive view of the network's security status.
- **Common SIEM Tools:**
  - **Splunk**
  - **Chronicle (Google)**



 
  
