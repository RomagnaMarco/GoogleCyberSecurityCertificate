# Logs and SIEM Tools

**Log:** A record of events that occur within an organization's systems and networks.

## Common Log Sources:
- **Firewall logs:** A record of attempted or established connections for incoming traffic from the internet and outbound requests from the network to the internet.
- **Network logs:** A record of all computers and devices that enter and leave the network. Records connections between devices and services on the network.
- **Server logs:** A record of events related to services such as websites, emails, or file shares. It includes actions such as login, password, and username requests.

**SIEM Tools:** Used to analyze log data to monitor critical activities.

SIEM tools must be configured and customized to meet each organization's unique security needs.

 # SIEM Dashboards

**SIEM tools** can be used to create dashboards. These dashboards help security analysts quickly access their security information as charts, graphs, or tables. 

Dashboards enable analysts to identify outliers and unusual behavior more easily.

**Metrics:** Key technical attributes, such as response time, availability, and failure rate, are used to assess the performance of a software application.

# The Future of SIEM Tools

Currently, SIEM tools require human interaction for the analysis of events.

## Increasing Need for Cloud Functionality:
- **Cloud-hosted tools:** Accessed through the internet, helping organizations avoid the investment in creating and maintaining their own infrastructure.
- **Cloud-native tools:** Also accessed through the internet, but designed to leverage cloud computing capabilities (availability, flexibility, scalability).

## Internet of Things (IoT):
- The development of interconnected devices with internet access.
- More devices mean a larger attack surface and more exploitable data.

## Advancements in AI and ML:
- Progress in AI and machine learning will enhance SIEM capabilities.

## Security Orchestration, Automation, and Response (SOAR):
- A collection of applications, tools, and workflows that use automation to respond to security events.

# Explore Common SIEM Tools

## Different Types of SIEM Tools:

### Self-hosted:
- Require the organization to install, operate, and maintain the tool using their own physical infrastructure.
- Managed and maintained by the organization's IT department, not a third-party vendor.
- Ideal when there is a requirement to maintain physical control over confidential data.

### Cloud-hosted:
- Maintained and managed by SIEM providers (accessible through the internet).
- Ideal for organizations that do not want to create or maintain their own infrastructure.

### Hybrid:
- Leverages the benefits of physical control over confidential data while being over the cloud.

## Common SIEM Tools:

### Splunk Enterprise
- Self-hosted tool.
- Used to retain, analyze, and search log data to provide security information and alerts in real time.

### Splunk Cloud
- Cloud-hosted tool.
- Used to collect, search, and monitor log data.

### Chronicle
- Cloud-native tool.
- Used to retain, analyze, and search data.

# More About Cybersecurity Tools

## Open Source
**Objective:** Provide users with software built collaboratively by the public, leading to more secure software.
**Benefits:** 
- Allows for more customization by users.
- Results in a variety of services built from the same open-source software package.

## Proprietary Tools
- Users pay a fee for usage and training.
- Only the owner can modify/access the source code.
- Users need to wait for updates and might need to pay for them.
- Allows users to modify a limited number of features to meet organizational or individual needs.

**Common Misconception:**
- Open source tools are not necessarily less effective or safe than proprietary tools.
- Being widely exposed makes it easier for a large number of well-intentioned and informed users/professionals to spot and fix issues.

## Examples of Open Source Tools:
- **Linux:** Widely used OS. Allows tailoring the operating system to your needs using a command-line interface.
- **Suricata:** Open source network analysis and threat detection software. Developed by the Open Information Security Foundation (OISF).

# Use SIEM tools to protoect organizations

Chronicle helps you collect and analyze log data according to:
- a specific asset
- a domain name
- a user
- AN IP Address


Splunks Dashboards:
Security Posture Dashboard
- designed for security operation centers (SOCs)
- Display last 24 hours of notable security related events and trends
- determines if security infrastructure and policies are performing as designed.
- can help monitor and investigate threats in real time.

Executive summary Dashboard
- analyzes and monitors the overall health of the organization over time.
- helps  security teams improve seecurity measuers that reduce risk
- can provide high-level stakeholders insights. (trends of security incidents over a period of time)

Incident Review Dashboard
- identify suspicious patterns that can occur in the event of an incident.
- highlights higher risk items that need immediate review
- provides a visual timeline of events leading up to an incident.

Risk Analysis dashboard
- identifies the risk for each risk objecct )users, computers, IP addresses)
- shows changes in risk-related activity or behavoir
- used to analyze the potential impact of vulnerabilities in ciritcal assets, helping analysts prioritize their risk mitigation efforts

Chronicles Dashboards:

Enterprise insights dashboard
- highlights recent alerts
- identifies suspicious domain names in logs, aka indicators of compromise (IOCs).
- results are each labaled with confidence score to indicate likelihood of a threat
- provides a security level that indications the significance of each threat to the organization
- can be used to monitor login or data access attempts to critical assets
  
Data ingestion and health dashboard
- shows the number of event logs, log sources, and success rates of data being processed into chronicle
- used to ensure that log sources are correctly configued and logs are recieved without error

IOC matches dashboard
- indicates the top threats, risks, and vulnerabilities to the organization
- used to observe domain names, IP addresses, and device IOCs over time in order to identify trends

Main dashboard
- displays a high-level summary of information related to the organization’s data ingestion, alerting, and event activity over time
- used to access a timeline of security events to identify threat trends across log sources, devices, IP addresses, and physical locations.

Rule detections dashboard
- provides statistics related to incidents with the highest occurrences, severities, and detections over time
- used to access a list of all the alerts triggered by a specific detection rule
- statistics used to help manage recurring incidents and establish mitigation tactics to reduce an organization's level of risk.

User sign in overview dashboard
- provides information about user access behavior across the organization
- use this dashboard to access a list of all user sign-in events to identify unusual user activity, such as a user signing in from multiple locations at the same time
- information is used to help mitigate threats, risks, and vulnerabilities to user accounts and the organization’s applications.

