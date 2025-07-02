# Controls and compliance checklist 

Select “yes” or “no” to answer the question: *Does Botium Toys currently have this control in place?*

**Controls assessment checklist**

|   Yes |     No | Control | *Explanation* |
| ----- | ----- | :---- | :---- |
|  |  √ | Least Privilege  | **Security Gap:** Universal employee access to customer data poses an inherent and elevated risk of data compromise.  **Proposed Control:** Implement role-based access controls (RBAC) to enforce the principle of least privilege, ensuring only authorized personnel have access to specific customer data sets, thereby significantly reducing breach exposure. |
|  | √ | Disaster recovery plans | ***Security Gap:** Lack of documented and tested disaster recovery plans, representing a critical deficiency in organizational resilience. **Proposed Control:** Implement a comprehensive Disaster Recovery (DR) framework to  ensure business continuity.* |
|  | √ | Password policies | ***Security Gap:** Minimal employee password requirements significantly elevate the risk of credential compromise, enabling unauthorized access to sensitive data and internal network assets.  **Proposed Control:** Implement and enforce a robust password policy that mandates strong complexity, minimum length, and regular rotation to mitigate this risk.* |
|  | √ | Separation of duties | ***Security Gap:** The CEO's direct management of both day-to-day operations and payroll creates an inherent conflict of interest and a significant risk of fraud or unauthorized access to critical data.  **Proposed Control:** Implement **segregation of duties** to distribute responsibilities, thereby reducing the possibility of fraud and enhancing the integrity of financial and operational data.* |
| √ |  | Firewall | ***Effective Control:** The firewall is configured to effectively block traffic based on a proactively defined and regularly updated set of security rules, demonstrating a strong perimeter defense.* |
|  |  |  |  |
|  | √ | Intrusion detection system (IDS) | ***Security Gap:** The absence of an Intrusion Detection System (IDS) leaves the network vulnerable to undetected malicious activity and potential intrusions.  **Proposed Control:** Implement a robust IDS solution to proactively identify and alert on suspicious network behavior and potential threat actor activity.* |
|  | √ | Backups | *The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity.* |
| √ |  | Antivirus software | ***Security Gap:** The lack of established backups for critical data creates a high risk of irreversible data loss and prolonged operational disruption in the event of a breach or system failure.  **Proposed Control:** Implement a comprehensive data backup and restoration strategy to ensure business continuity and minimize data loss following a disruptive incident.* |
|  | √ | Manual monitoring, maintenance, and intervention for legacy systems | ***Security Gap:** While legacy systems are monitored and maintained, the absence of a defined schedule and clear intervention procedures creates an elevated risk of compromise.  **Proposed Control:** Establish and enforce a regular maintenance and monitoring schedule for all legacy systems, alongside clear, documented incident response procedures for identified vulnerabilities or anomalies, to mitigate potential breaches.* |
|  | √ | Encryption | ***Security Gap:** The absence of encryption for sensitive information creates a significant risk of unauthorized access and compromise of data confidentiality.  **Proposed Control:** Implement robust encryption mechanisms for both data at rest and data in transit to provide enhanced protection for sensitive organizational data.* |
|  | √ | Password management system | ***Security Gap:** The absence of a centralized password management system introduces heightened risks associated with weak or reused credentials.  **Proposed Control:** Implement a robust password management solution to enhance overall authentication security, reduce the burden of password-related IT support issues, and improve employee productivity.* |
| √ |  | Locks (offices, storefront, warehouse) | ***Effective Control:** The company's physical location, encompassing main offices, the storefront, and the product warehouse, is secured with robust and appropriately implemented physical access controls, including comprehensive locking mechanisms.* |
| √ |  | Closed-circuit television (CCTV) surveillance | ***Effective Control:** Closed-Circuit Television (CCTV) systems are fully operational and strategically deployed throughout the store's physical location, providing continuous surveillance.* |
| √ |  | Fire detection/prevention (fire alarm, sprinkler system, etc.) | ***Effective Control:** Botium Toys' physical location is equipped with a fully functional fire detection and prevention system, enhancing safety and asset protection.* |

---

**Compliance checklist**

Select “yes” or “no” to answer the question: *Does Botium Toys currently adhere to this compliance best practice?*

Payment Card Industry Data Security Standard (PCI DSS)

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  | √ | Only authorized users have access to customers’ credit card information.  | ***Security Gap:** Unrestricted access to the company's internal data by all employees significantly elevates the risk of unauthorized disclosure or data compromise.  **Proposed Control:** Implement a robust least privilege model to restrict data access based on job function, thereby fortifying data confidentiality.* |
|  | √ | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | ***Critical Security Gap:** The lack of encryption for sensitive credit card information, combined with universal employee access to internal data, poses an extreme risk of data compromise, fraud, and regulatory non-compliance. **Proposed Control:** Implement robust encryption-at-rest and encryption-in-transit for all credit card data. Concurrently, enforce a strict least privilege model and Role-Based Access Controls (RBAC) to ensure only authorized personnel have access to this highly sensitive information on a need-to-know basis.* |
|  | √ | Implement data encryption procedures to better secure credit card transaction touchpoints and data.  | **Security Gap:** The current absence of encryption for customers' financial information presents a significant risk of unauthorized access and severe compromise of data confidentiality. **Proposed Control:** Implement robust encryption-at-rest and encryption-in-transit solutions to ensure the confidentiality and integrity of all customer financial data. |
|  | √ | Adopt secure password management policies. | ***Critical Security Gap:** The combination of nominal password policies and the absence of a password management system significantly elevates the risk of credential compromise and unauthorized access to organizational assets. **Proposed Control:** Implement a robust enterprise password management system and enforce a comprehensive password policy that mandates strong complexity, minimum length, multi-factor authentication (MFA), and regular credential rotation to fortify authentication security.* |

General Data Protection Regulation (GDPR)

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  | √ | E.U. customers’ data is kept private/secured. | ***Security Gap:** The current absence of encryption for customers' financial information presents a significant risk of unauthorized access and severe compromise of data confidentiality. **Proposed Control:** Implement robust encryption-at-rest and encryption-in-transit solutions to ensure the confidentiality and integrity of all customer financial data.* |
| √ |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | ***Effective Control (Planned):** A documented plan is in place to notify E.U. customers within 72 hours of data breach discovery, aligning with regulatory requirements.* |
|  | √ | Ensure data is properly classified and inventoried. | ***Security Gap:** While assets are inventoried, the lack of classification prevents effective risk prioritization and targeted security control implementation. **Recommendation:** Implement an asset classification scheme to categorize assets based on their criticality and sensitivity, enabling more strategic security management.* |
| √ |  | Enforce privacy policies, procedures, and processes to properly document and maintain data. | ***Effective Control:** Comprehensive privacy policies, procedures, and processes have been formally developed and are consistently enforced across all relevant IT and business units, ensuring adherence to data protection principles.* |

System and Organizations Controls (SOC type 1, SOC type 2\) 

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  | √ | User access policies are established. | ***Critical Security Gap:** The absence of Least Privilege and Segregation of Duties controls results in all employees having unrestricted access to internally stored data, creating an unacceptable risk of data compromise and insider threat. **Proposed Control:** Implement stringent Role-Based Access Controls (RBAC) to enforce the principle of Least Privilege and establish clear Segregation of Duties across all critical functions, ensuring access to internal data is granted strictly on a need-to-know basis.*  |
|  | √ | Sensitive data (PII/SPII) is confidential/private. | ***Security Gap:** The absence of encryption for Personally Identifiable Information (PII) and Sensitive Personally Identifiable Information (SPII) creates a significant risk of unauthorized access and severe compromise of data confidentiality. **Proposed Control:** Implement robust encryption-at-rest and encryption-in-transit solutions to ensure the confidentiality and integrity of all PII/SPII.*  |
| √ |  | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | ***Effective Control:** Robust data integrity controls are effectively implemented, ensuring the accuracy, consistency, and trustworthiness of organizational data.* |
|  | √ | Data is available to individuals authorized to access it. | ***Security Gap:** Broad data availability to all employees without granular authorization significantly elevates the risk of unauthorized access and data compromise. **Proposed Control:** Implement a robust least privilege model, ensuring data access is limited strictly to individuals who require it for their specific job functions.* |

---

**Overall Recommendation:**

To significantly enhance Botium Toys' security posture and mitigate critical risks, it is imperative to implement a holistic set of foundational security controls. This includes fortifying access management through Least Privilege and Segregation of Duties, deploying comprehensive encryption for sensitive data, establishing a centralized password management system with strong policies, integrating an Intrusion Detection System (IDS) for proactive threat detection, developing and testing robust Disaster Recovery plans, and formalizing legacy system management.

These comprehensive control implementations are crucial for safeguarding sensitive information and ensuring business continuity. Moreover, a foundational asset classification initiative is essential to identify any additional necessary controls, thereby enabling a robust, risk-based approach to security that ensures adherence to regulatory obligations and strengthens overall data protection and compliance.

