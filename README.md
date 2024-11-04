# Botium

# Table of contents

1. [Introduction](#introduction)
2. [Audit Scope and Goals](#Audit-Scope-and-Goals)
3. [Risk Assessment Report Review](#Risk-Assessment-Report-Review)
4. [Controls and Compliance Checklist](#Controls-and-Compliance-Checklist)
5. [Recommendations](#Recommendations)
6. [Conclusion](#Conclusion)
7. [Appendices](#Appendices)

-----

# Introduction <a name="introduction">

An internal security audit assessment done on Botium Toys, a fictitious toy company, completed as part of my cybersecurity portfolio and as part of Google's <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a> on Coursera in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> Play It Safe: Manage Security Risks </a> Course .

# Audit Scope and Goals <a name="Scope-and-Goals">

### Audit Scope:

- Evaluation of IT Infrastructure:

- Examine the current IT infrastructure and security practices.

- Assess the robustness of systems supporting the online market worldwide.

### Compliance Assessment:

- Ensure compliance with relevant U.S. regulations.

- Evaluate compliance with European Union (E.U.) regulations, particularly GDPR.

- Risk and Vulnerability Identification:

- Identify potential security threats and vulnerabilities to critical assets.

- Analyze risks associated with the company's growth and expansion.

### Secure Payment Processing:

- Assess and secure the systems for processing and accepting online payments.

- Ensure compliance with Payment Card Industry Data Security Standard (PCI DSS).

- Employee and Physical Security:

- Assess the effectiveness of employee cybersecurity training.

- Evaluate physical security measures at the main office, storefront, and warehouse.

### Audit Goals:

- Improving Security Posture:

- Enhance overall security measures to protect against cyber threats and physical breaches.

### Ensuring Compliance:

- Ensure adherence to all relevant regulations and standards, both in the U.S. and the E.U.

### Mitigating Risks:

- Identify and address potential risks, threats, and vulnerabilities to minimize the likelihood of security incidents.

### Protecting Critical Assets:

- Safeguard critical company assets, including customer data, payment systems, and employee devices.

### Enhancing Payment Security:

- Ensure the secure processing and acceptance of online payments to protect against fraud and breaches.

By focusing on these scope areas and goals, Botium Toys can ensure a thorough and effective internal IT audit, addressing key aspects of their infrastructure, compliance, and security.

# Risk Assessment Report Review  <a name="Risk-Assessment-Report-Review">

1. Assets Managed by IT Department:

- Physical Assets: Main office, storefront, warehouse.

- Digital Assets: Website, e-commerce platforms.

- Customer Data: Personal information, purchase history.

- Payment Systems: Online payment processing infrastructure.

- Employee Devices: Computers, mobile devices.

2. Identified Risks and Threats:

- Unauthorized Access: Risk of unauthorized access to sensitive data and systems.

- Cyberattacks: Potential for cyberattacks such as phishing, malware, ransomware.

- Data Breaches: Risk of data breaches leading to loss of customer data and financial information.

- Non-compliance: Risk of non-compliance with regulations (e.g., GDPR, PCI DSS).

- Insider Threats: Risk of malicious actions or negligence by employees.

- Physical Security: Threats to the physical security of office, storefront, and warehouse.

3. Vulnerabilities:

- Outdated Software and Hardware: Vulnerabilities due to outdated systems and lack of regular updates.

- Weak Password Policies: Risk associated with weak or reused passwords.

- Employee Training: Lack of adequate cybersecurity training for employees.

- Network Security: Inadequate network security measures, such as lack of firewalls or intrusion detection systems.

- Physical Security Controls: Insufficient physical security controls to protect the physical location and assets.

Summary of the Risk Assessment Report
The risk assessment report for Botium Toys highlights several critical assets, identifies various risks and threats to these assets, and outlines vulnerabilities in the current infrastructure and practices. The main concerns are unauthorized access, cyberattacks, data breaches, non-compliance with regulations, insider threats, and physical security challenges. Addressing these vulnerabilities through improved security measures, employee training, and regular audits can help mitigate these risks and enhance the overall security posture of Botium Toys.

# Controls and Compliance Checklist  <a name="Controls-and-Compliance-Checklist">

Current Assets 
--------------

Assets managed by the IT Department include:

- On-premises equipment for in-office business needs 

- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.

- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management

- Internet access

- Internal network

- Vendor access management

- Data center hosting services 

- Data retention and storage

- Badge readers

- Legacy system maintenance: end-of-life systems that require human monitoring

### Administrative Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | X | High |
| Access control policies | Preventative; increase confidentiality and integrity of data | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |

### Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |


### Physical Controls
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attack surface/impact of physical threats | X | Medium/Low |
| Adequate lighting | Deterrent; limit “hiding” places to deter threats | X | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | X | High/Medium |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | High/Medium |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | X | Low |
| Locks | Preventative; physical and digital assets are more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | X | Medium |

Compliance checklist
====================

To review compliance regulations and standards, read the [controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance) document.
   
I found that Botium Toys will need to adhere to the following standards:
     
-   General Data Protection Regulation (GDPR)
      - GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens' data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen's data is compromised, they must be informed within 72 hours of the incident.
         - Botium Toys is expanding to offer services and handle the data of customers abroad, GDPR compliance is in scope for the handling of financial and personal information for customers in the European Union.
   

-   Payment Card Industry Data Security Standard (PCI DSS)

    - PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

       - Botium Toys must adhere to PCI DSS as it accepts payments online and person and They also store and processes customer credit card on an international scale. It's requirements and compliance need to be taken seriously based on possible consequences. The consequences of not complying with this standard is more severe in impact: Monetary fines monthly (ranging from 5,000-100,000 USD), costs of forensic audits upon a data breach, payment brand restrictions, damage to brand reputation, and possibility of lawsuit costs in the event of data breaches. 


-   System and Organizations Controls (SOC type 1, SOC type 2)
   - The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization's financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

      - Botium Toys needs to establish and maintain appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safey.
      - Both of these standards evaluate the effectiveness of a company's internal controls. While SOC1 I focused on financial reporting controls, SOC2 is concerned with information security controls, including customer data safety.
    
  By following this comprehensive checklist, Botium Toys can improve their security posture, ensure compliance with regulations, and protect their critical assets and data.


  # Recommendations <a name="Recommendations">

1.  Improve Access Controls:

- Password Policies: Implement stronger password policies requiring complex, unique passwords for all accounts.

- Multi-Factor Authentication (MFA): Deploy MFA to add an additional layer of security for accessing sensitive systems and data.

- Role-Based Access Control (RBAC): Ensure access to sensitive information is restricted based on user roles and responsibilities.

2.  Enhance Network Security:

- Firewalls and Intrusion Detection/Prevention Systems (IDPS): Ensure robust firewalls and IDPS are in place to protect against network threats.

- Software and Hardware Updates: Regularly update software and hardware to protect against vulnerabilities.

- Vulnerability Assessments and Penetration Testing: Conduct regular assessments and testing to identify and address potential weaknesses.

3.  Protect Data:

- Encryption: Implement encryption for sensitive data both in transit and at rest.

- Data Loss Prevention (DLP): Deploy DLP solutions to prevent unauthorized data transfers.

- Backup and Recovery: Establish secure backup and recovery processes to protect data from loss or corruption.

4.  Ensure Compliance:

- GDPR Compliance: Ensure adherence to GDPR requirements for handling data of E.U. customers.

- PCI DSS Compliance: Follow PCI DSS guidelines for secure online payment processing.

- Stay Informed: Keep up-to-date with relevant regulations and industry standards to maintain compliance.

5.  Train Employees:

- Cybersecurity Training: Provide regular training sessions to educate employees on cybersecurity best practices.

- Phishing Simulations: Conduct phishing simulations to raise awareness and improve employees' ability to recognize and respond to threats.

6.  Strengthen Physical Security:

- Access Controls: Implement secure access controls for the main office, storefront, and warehouse.

- Surveillance Systems: Install surveillance cameras and monitoring systems to deter and detect unauthorized access.

7.  Develop Incident Response:

- Incident Response Plan: Create and implement a comprehensive incident response plan to address potential security incidents.

- Regular Drills and Simulations: Conduct drills and simulations to ensure the incident response team is prepared to act swiftly and effectively.

- Timely Reporting and Remediation: Establish clear procedures for timely reporting and remediation of security incidents.

By following these recommendations, Botium Toys can significantly improve their security posture, ensure compliance with relevant regulations, and protect their critical assets and data from potential threats.


# Conclusion <a name="Conclusion">

The internal IT audit for Botium Toys highlights the growing challenges and risks associated with the company's expanding online presence. The primary objectives of the audit were to enhance security measures, ensure regulatory compliance, and protect critical assets and customer data. Through this audit, several key areas were identified for improvement:

-  Risk Assessment: The assessment identified various risks, including unauthorized access, cyberattacks, data breaches, and physical security threats. The vulnerabilities were mainly due to outdated software, weak password policies, and insufficient employee training and network security measures.

-  Controls and Compliance: To address these risks, a comprehensive controls and compliance checklist was developed. This includes implementing strong access controls, enhancing network security, protecting data through encryption and backup solutions, ensuring compliance with GDPR and PCI DSS, providing regular employee cybersecurity training, and strengthening physical security measures.

-  Recommendations: Specific recommendations were provided to improve Botium Toys' security posture. These include enforcing stronger password policies, deploying multi-factor authentication, conducting regular vulnerability assessments, encrypting sensitive data, staying informed about relevant regulations, and developing a robust incident response plan.

By implementing these recommendations, Botium Toys can significantly mitigate potential risks, ensure compliance with regulatory requirements, and enhance the overall security of their infrastructure. This proactive approach will help the company maintain a secure environment as it continues to grow and expand its online market presence.

This concludes the internal IT audit, providing a clear roadmap for Botium Toys to strengthen its security measures and safeguard its critical assets and customer data



# Appendices <a name="Appencies"> 

Glossary of Terms

NIST CSF: National Institute of Standards and Technology Cybersecurity Framework

GDPR: General Data Protection Regulation.

PCI DSS: Payment Card Industry Data Security Standard.

MFA: Multi-Factor Authentication.

RBAC: Role-Based Access Control.

IDPS: Intrusion Detection and Prevention System.

DLP: Data Loss Prevention.

----------------

