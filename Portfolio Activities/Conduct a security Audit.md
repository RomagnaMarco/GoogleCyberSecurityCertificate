# Scenario

This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

Supporting Materials:
- [Botium Toys: Scope, goals, and risk assessment](https://docs.google.com/document/d/1s2u_RuhRAI40JSh-eZHvaFsV1ZMxcNSWXifHDTOsgFc/template/preview#heading=h.evidx83t54sc)
- [Control Categories](https://docs.google.com/document/d/1HsIw5HNDbRXzW7pmhPLsK06B7HF-KMifENO_TlccbSU/template/preview)

# From supporting Material on scope, goals, and risk assessment: 
**Noted Risk Assessment: 8**
- Lack of controls and adherence to compliance best practices
- Inadequate management of assets
- IT department does not know which assets would be at risk

**Additional Comments:**
- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, storefront, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

# Observations

**Initial prompt observations:**
- Single physical location: the storefront is in the same place as the warehouse and their main office.
  - Customers are near their assets
- They have an online market
- Manager of IT claims they have no clear plan for growth and wants an audit, meeting compliance with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   
- Implementation of the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
- The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

**Initial Asset observations:**
- Surveillance cameras
- Internal network
- Internet access
- Data storage, physical storage
- Legacy system maintenance
- Onsite workstations
- Telecommunications

**Initial comment observations:**
- All employees should not have access to internally stored data and such detailed PII/SPII, this goes against the separation of duties.
- Lack of encryption all around.
- Access controls not adhering to least privilege or separation of duties.
- IT department claims ensured availability and integrated controls to ensure data integrity.
- Firewall blocking based on security rules.
- Antivirus software is installed and regularly monitored.
- No IDS installed.
- No disaster recovery plans in place, no backups of critical data.
- Plan to notify E.U customers within 72 hours of a security breach. Privacy policies, procedures, and processes have been developed and enforced by the employees/members.
- Password policy exists, but not in line with password complexity requirements.
- No centralized password management system.
- Legacy systems monitored and maintained, but no schedule in place for these tasks and intervention methods.
- Physical location has sufficient locks, up-to-date CCTV, and functioning fire detection and prevention systems.

# Checklists 

### Controls assessment Checklist
- [ ] Least Privilege 
- [ ] Disaster recovery plans
- [ ] Password policies
- [ ] Separation of duties
- [x] Firewall 
- [ ] Intrusion detection system (IDS)
- [ ] Backups
- [x] Antivirus software 
- [?] Manual monitoring, maintenance, and intervention for legacy systems
- [ ] Encryption
- [ ] Password management system
- [x] Locks (offices, storefront, warehouse)
- [x] Closed-circuit television (CCTV) surveillance
- [x] Fire detection/prevention (fire alarm, sprinkler system, etc.)

### Compliance checklist
- [x] Only authorized users have access to customers’ credit card information.
- [ ] Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment.
- [ ] Implement data encryption procedures to better secure credit card transaction touchpoints and data. 
- [ ] Adopt secure password management policies.

### General Data Protection Regulation (GDPR)
- [ ] E.U. customers’ data is kept private/secured.
- [x] There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach.
- [ ] Ensure data is properly classified and inventoried.
- [x] Enforce privacy policies, procedures, and processes to properly document and maintain data.

### System and Organizations Controls (SOC type 1, SOC type 2)
- [ ] User access policies are established.
- [ ] Sensitive data (PII/SPII) is confidential/private.
- [x] Data integrity ensures the data is consistent, complete, accurate, and has been validated.
- [x] Data is available to individuals authorized to access it.
