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

# Use SIEM Tools to Protect Organizations

## Chronicle

### Collect and Analyze Log Data According To:
- A specific asset
- A domain name
- A user
- An IP Address

## Splunk Dashboards

### Security Posture Dashboard
- Designed for security operation centers (SOCs).
- Displays the last 24 hours of notable security-related events and trends.
- Determines if security infrastructure and policies are performing as designed.
- Helps monitor and investigate threats in real time.

### Executive Summary Dashboard
- Analyzes and monitors the overall health of the organization over time.
- Helps security teams improve measures that reduce risk.
- Provides high-level stakeholders insights into trends of security incidents over a period of time.

### Incident Review Dashboard
- Identifies suspicious patterns that can occur in the event of an incident.
- Highlights higher risk items that need immediate review.
- Provides a visual timeline of events leading up to an incident.

### Risk Analysis Dashboard
- Identifies the risk for each risk object (users, computers, IP addresses).
- Shows changes in risk-related activity or behavior.
- Analyzes the potential impact of vulnerabilities in critical assets, helping analysts prioritize their risk mitigation efforts.

## Chronicle Dashboards

### Enterprise Insights Dashboard
- Highlights recent alerts.
- Identifies suspicious domain names in logs, known as indicators of compromise (IOCs).
- Labels results with a confidence score to indicate the likelihood of a threat.
- Provides a security level indicating the significance of each threat to the organization.
- Monitors login or data access attempts to critical assets.

### Data Ingestion and Health Dashboard
- Shows the number of event logs, log sources, and success rates of data being processed into Chronicle.
- Ensures that log sources are correctly configured and logs are received without error.

### IOC Matches Dashboard
- Indicates the top threats, risks, and vulnerabilities to the organization.
- Observes domain names, IP addresses, and device IOCs over time to identify trends.

### Main Dashboard
- Displays a high-level summary of information related to the organization’s data ingestion, alerting, and event activity over time.
- Accesses a timeline of security events to identify threat trends across log sources, devices, IP addresses, and physical locations.

### Rule Detections Dashboard
- Provides statistics related to incidents with the highest occurrences, severities, and detections over time.
- Accesses a list of all the alerts triggered by a specific detection rule.
- Uses statistics to manage recurring incidents and establish mitigation tactics to reduce an organization's level of risk.

### User Sign-In Overview Dashboard
- Provides information about user access behavior across the organization.
- Accesses a list of all user sign-in events to identify unusual user activity, such as a user signing in from multiple locations at the same time.
- Uses information to mitigate threats, risks, and vulnerabilities to user accounts and the organization’s applications.
