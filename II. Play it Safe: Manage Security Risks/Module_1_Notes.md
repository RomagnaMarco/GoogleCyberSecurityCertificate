# Exploring the CISSP Security Domains

## Security Posture
- **Definition**: An organization's ability to manage its defense of critical assets and data, and react to change.

## Security and Risk Management
- **Focus**: Defining security goals and objectives, risk mitigation, compliance, business continuity, and legal regulations.

### Key Concepts:
- **Risk Mitigation**: Procedures and rules to quickly reduce the impact of risks like breaches.
- **Compliance**: Developing internal security policies, regulatory requirements, and independent standards.
- **Business Continuity**: Maintaining everyday productivity by establishing disaster recovery plans.

An organization may use playbooks and implement training as part of their security and risk management program. This domain is related to Information Security (InfoSec) and includes processes to establish secure information.

## Asset Security
- **Focus**: Securing digital and physical assets, including storage, maintenance, retention, and destruction of data.

### Key Concept:
- **Handling PII and SPII**: Ensuring policies and procedures are in place to securely handle and protect Personally Identifiable Information (PII) and Sensitive Personally Identifiable Information (SPII).

A team could conduct a security impact analysis, establish a recovery plan, or manage data exposure to better manage the organization's assets. They may also make backups to restore the environment in the event of a security incident.

## Security Architecture and Engineering
- **Focus**: Optimizing data security by ensuring effective tools, systems, and processes are in place to protect an organization's assets and data.

### Key Concept:
- **Shared Responsibility**: All individuals within an organization actively participate in lowering risk and maintaining both physical and virtual security. Policies should encourage users to report security concerns.

Monitoring unusual logins or activity can be done with SIEM tools.

## Communication and Network Security
- **Focus**: Managing and securing physical networks and wireless communications.

### Key Concept:
- **Removing Unsafe Access**: Teams can remove access to unsafe communication channels or networks at the organizational level, discouraging employees from engaging in insecure behavior that could be exploited by threat actors. This can be considered "restricted network access."

This is important since organizations need to get work done for remote, hybrid, and on-site workers.

## Identity and Access Management
- **Focus**: Managing access and authorization to keep data secure by ensuring users follow established policies to control and manage assets.

### Key Concept:
- **Principle of Least Privilege**: Limit employees' access to only what they need, reducing the overall risk to systems and data.

### Main Components:
1. **Identification**: User verification.
2. **Authentication**: Proof of identity with a password or PIN.
3. **Authorization**: Level of access.
4. **Accountability**: Monitoring and recording user actions.

## Security Assessment and Testing
- **Focus**: Conducting security control testing, collecting and analyzing data, and conducting security audits to monitor risks, threats, and vulnerabilities.

### Key Concept:
- **Effectiveness of Controls**: Examining organizational goals and objectives, and evaluating if the controls in place actually achieve those goals.

Testing user permissions with audits is important to validate correct access levels and ensure the system is secure.

## Security Operations
- **Focus**: Conducting investigations and implementing preventative measures.

### Key Concept:
- **Incident Response**: Mitigating active attacks and preventing escalation is critical. Upon neutralization, physical and digital evidence is collected to start a forensic investigation.

This involves what happens in the event of a potential breach and how to resolve it according to existing guidelines.

## Software Development Security
- **Focus**: Using secure coding practices.

### Key Concept:
- **Security in SDLC**: Security is an additional step in each phase of the software development lifecycle.

Security cannot be an afterthought during development. There must be Quality Assurance (QA) and penetration tester professionals to ensure the software has met security standards.

# Threats, Risks, and Vulnerabilities

## Definitions

- **Threat**: Any circumstance or event that can negatively impact assets.
- **Risk**: Anything that can impact the confidentiality, integrity, or availability of an asset; the likelihood of a threat occurring.
- **Vulnerability**: A weakness that can be exploited by a threat.

## Risk Classification

### Low Risk
- **Description**: Information that wouldn't harm the reputation or ongoing operations and wouldn't cause financial damage if compromised.

### Medium Risk
- **Description**: Information not available to the public that could cause harm to reputation, ongoing operations, or financial damage.

### High Risk
- **Description**: Information protected by regulations/laws that would cause severe negative impact on finances, ongoing operations, or reputation if compromised.

# Key impacts of threats, risks, and vulnerabilities

## Definitions

- **Threat**: Any circumstance or event that can negatively impact assets.
- **Risk**: Anything that can impact the confidentiality, integrity, or availability of an asset; the likelihood of a threat occurring.
- **Vulnerability**: A weakness that can be exploited by a threat.

## Risk Classification

### Low Risk
- **Description**: Information that wouldn't harm the reputation or ongoing operations and wouldn't cause financial damage if compromised.

### Medium Risk
- **Description**: Information not available to the public that could cause harm to reputation, ongoing operations, or financial damage.

### High Risk
- **Description**: Information protected by regulations/laws that would cause severe negative impact on finances, ongoing operations, or reputation if compromised.

## Ransomware
- **Description**: Threat actors encrypt data and demand payment to restore access.

## Layers of the Web
- **Surface Web**: Accessible via standard web browsers.
- **Deep Web**: Requires authorization (e.g., intranet).
- **Dark Web**: Requires special software to access.

## Key Impacts of Security Breaches

### 1. Financial
- **Consequences**:
  - Interrupted production and services.
  - Costs to correct the issue.
  - Fines if data is compromised.

### 2. Identity Theft
- **Considerations**:
  - How long and how to store PII and SPII.
  - Stolen data can be sold on the dark web.

### 3. Damage to Reputation
- **Consequences**:
  - Exploited vulnerability can make customers go elsewhere.
  - Negative press coverage.
  - Legal penalties in addition to fines.

# NIST's Risk Management Framework

## Risk Management Framework (RMF) 7 Steps:

### 1. Prepare
- **Objective**: Manage security and privacy risks before a breach occurs.

### 2. Categorize
- **Objective**: Develop risk management processes and tasks.

### 3. Select
- **Objective**: Choose, customize, and capture documentation of the controls that protect an organization.

### 4. Implement
- **Objective**: Implement security and privacy plans.

### 5. Assess
- **Objective**: Determine if established controls are implemented correctly.
- **Activities**: Identify potential weaknesses and decide if changes are necessary.

### 6. Authorize
- **Objective**: Be accountable for security and privacy risks that may exist.

### 7. Monitor
- **Objective**: Be aware of how systems are operating.

# Manage Common Threats, Risks, and Vulnerabilities

## Common Risk Management Strategies
- **Acceptance**: Accepting a risk to avoid disrupting business continuity.
- **Avoidance**: Creating a plan to avoid the risk altogether.
- **Transference**: Transferring risk to a third party to manage.
- **Mitigation**: Lessening the impact of a known risk.

### Factors Affecting the Likelihood of Risk
- External risk
- Internal risk
- Legacy systems
- Multiparty risk
- Software compliance/licensing

## OWASP Top 10 Common Attack Types
1. Injection
2. Broken Authentication
3. Sensitive Data Exposure
4. XML External Entities (XXE)
5. Broken Access Control
6. Security Misconfiguration
7. Cross-Site Scripting (XSS)
8. Insecure Deserialization
9. Using Components with Known Vulnerabilities
10. Insufficient Logging & Monitoring

## Notable Vulnerabilities
- **ProxyLogon**: Affects Microsoft Exchange server. Allows a threat actor to deploy malicious code from a remote location after completing a user authentication process.
- **ZeroLogon**: Affects Microsoft’s Netlogon authentication protocol. Allows unauthorized access by exploiting a flaw in the authentication process.
- **Log4Shell**: Allows attackers to run Java code or leak sensitive information on a remote device. It enables remote attackers to take control of internet-connected devices and run malicious code.
- **PetitPotam**: Affects Windows NTLM. Allows a LAN-based attacker to initiate an authentication request and steal credentials.
- **Security Logging and Monitoring Failures**: Insufficient logging and monitoring capabilities, allowing attackers to exploit vulnerabilities without detection.
- **Server-Side Request Forgery (SSRF)**: Allows attackers to manipulate a server-side application to access and update backend resources, potentially stealing data.




  
