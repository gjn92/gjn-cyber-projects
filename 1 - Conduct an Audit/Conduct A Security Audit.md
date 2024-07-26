## Case Study

This is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.

## Scenario
Botium Toys: Scope, Goals, and Risk Assessment Report
### Scope: 
The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. 
### Goals: 
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to improve Botium Toys’ security posture.
### Current assets
Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring
### Risk assessment
#### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.
##### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
#### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.
#### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure. Review the following bullet points for specific details:

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
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

## Controls and Compliance Checklist
### Controls Assessment Checklist

| Control                                               | Yes | No  |
|-------------------------------------------------------|-----|-----|
| Least Privilege                                       |     |  X  |
| Disaster recovery plans                               |     |  X  |
| Password policies                                     |     |  X  |
| Separation of duties                                  |     |  X  |
| Firewall                                              |  X  |     |
| Intrusion detection system (IDS)                      |     |  X  |
| Backups                                               |     |  X  |
| Antivirus software                                    |  X  |     |
| Manual monitoring, maintenance, and intervention for legacy systems |  X  |     |
| Encryption                                            |     |  X  |
| Password management system                            |     |  X  |
| Locks (offices, storefront, warehouse)                |  X  |     |
| Closed-circuit television (CCTV) surveillance         |  X  |     |
| Fire detection/prevention (fire alarm, sprinkler system, etc.) |  X  |     |

### Compliance Checklist

**Payment Card Industry Data Security Standard (PCI DSS)**

| Best practice                                                                           | Yes | No  |
|-----------------------------------------------------------------------------------------|-----|-----|
| Only authorized users have access to customers’ credit card information.               |     |  X  |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |     |  X  |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. |     |  X  |
| Adopt secure password management policies.                                              |     |  X  |

**General Data Protection Regulation (GDPR)**

| Best practice                                                                           | Yes | No  |
|-----------------------------------------------------------------------------------------|-----|-----|
| E.U. customers’ data is kept private/secured.                                           |  X  |     |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |  X  |     |
| Ensure data is properly classified and inventoried.                                     |     |  X  |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. |  X  |     |

**System and Organizations Controls (SOC type 1, SOC type 2)**

| Best practice                                                                           | Yes | No  |
|-----------------------------------------------------------------------------------------|-----|-----|
| User access policies are established.                                                   |     |  X  |
| Sensitive data (PII/SPII) is confidential/private.                                       |     |  X  |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated. |  X  |     |
| Data is available to individuals authorized to access it.                               |  X  |     |

### Recommendations

**Immediate Actions:**

1. **Implement Least Privilege and Separation of Duties:**
   - Reduce the risk of malicious insider actions and compromised accounts.
   - Establish role-based access controls to limit data access.

2. **Develop Disaster Recovery Plans:**
   - Ensure business continuity in case of a disaster.
   - Regularly backup critical data and systems.

3. **Update Password Policies:**
   - Adopt secure password management practices to reduce the likelihood of account compromises.
   - Implement a centralized password management system.

4. **Install and Configure an Intrusion Detection System (IDS):**
   - Detect and respond to anomalous traffic and potential security incidents.

5. **Encrypt Sensitive Data:**
   - Ensure the confidentiality of customer credit card information and other sensitive data.
   - Implement encryption for data in transit and at rest.

**Short-term Actions:**

1. **Establish User Access Policies:**
   - Define and enforce policies for user access to sensitive data.
   - Regularly review and update access permissions.

2. **Regular Maintenance for Legacy Systems:**
   - Develop a regular maintenance schedule for legacy systems to ensure they are secure and up-to-date.

3. **Ensure Compliance with PCI DSS:**
   - Restrict access to customer credit card information to authorized users only.
   - Secure the storage, processing, and transmission of credit card information.
   - Adopt encryption and secure password management procedures.

**Long-term Actions:**

1. **Conduct Regular Security Awareness Training:**
   - Educate employees on security best practices and their role in protecting the organization.
   - Develop a culture of security awareness within the organization.

2. **Ensure GDPR Compliance:**
   - Classify and inventory E.U. customer data to ensure it is kept private and secure.
   - Enforce privacy policies, procedures, and processes to maintain data integrity.

3. **Improve Data Integrity and Availability:**
   - Ensure data is consistent, complete, accurate, and validated.
   - Maintain data availability for authorized individuals.

By implementing these controls and compliance best practices, Botium Toys can significantly reduce risks to their assets and improve their overall security posture.
