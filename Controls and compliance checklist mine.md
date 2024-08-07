# Controls and compliance checklist

**Controls assessment checklist**

|   Yes |     No | Control | *Explanation* |
| ----- | ----- | :---- | :---- |
|  | * | Least Privilege  | The concept of the least privilege has not been implemented |
|  | * | Disaster recovery plans | *Disaster recovery plans have not been implemented* |
|  | * | Password policies | *Although password policy exist, complexity of passwords with minimum length have not been implemented* |
|  | * | Separation of duties | *All employees have access all the PII/SPII* |
| * |  | Firewall | *Firewall is present based on an appropriate rule* |
|  |  |  |  |
|  | * | Intrusion detection system (IDS) | *Intrusion detection system has not been implemented* |
|  | * | Backups | *Data recovery plans or back ups have not been implemented* |
| * |  | Antivirus software | *Antivirus software has been installed on end user devices* |
| * |  | Manual monitoring, maintenance, and intervention for legacy systems | *Although there is no regular schedule plan, Maintenance of legacy systems is being implemented.* |
|  | * | Encryption | *Passwords are not encrypted* |
|  | * | Password management system | *There is a password policy but it does not meet the standard as of now.* |
| * |  | Locks (offices, storefront, warehouse) | *Proper physical security has been implemented* |
| * |  | Closed-circuit television (CCTV) surveillance | *Proper physical security has been implemented* |
| * |  | Fire detection/prevention (fire alarm, sprinkler system, etc.) | *There is a functioning fire detection and prevention system in place* |

---

**Compliance checklist**


Payment Card Industry Data Security Standard (PCI DSS)

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  | * | Only authorized users have access to customers’ credit card information.  | *All employees have access to PII/SPII* |
|  | * | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | *Credit information is stored locally*  |
|  | * | Implement data encryption procedures to better secure credit card transaction touchpoints and data.  | *Credit card information is not encrypted* |
|  | * | Adopt secure password management policies. | *Do have a password policy but it not up to the industry standard*  |

General Data Protection Regulation (GDPR)

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  | * | E.U. customers’ data is kept private/secured. | *As to prior observation \- no* |
| * |  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | *There is a plan to notify E.U. customers within 72 hours in case of breach* |
|  | * | Ensure data is properly classified and inventoried. | *Policy to properly manage data* |
|  | * | Enforce privacy policies, procedures, and processes to properly document and maintain data. | *Policy to properly manage data* |

System and Organizations Controls (SOC type 1, SOC type 2) 

| Yes |     No | Best practice | *Explanation* |
| ----- | ----- | :---- | :---- |
|  | * | User access policies are established. | *User access policies are not been established* |
|  | * | Sensitive data (PII/SPII) is confidential/private. | *PII/SPII are stored locally and have the ability to be accessed any employee* |
|  | * | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | *Data is not encrypted* |
|  | * | Data is available to individuals authorized to access it. | *No, every employee has access to all data within the company* |

---

# Recommendations to Improve Security Poster

1. **Implement Least Privilege Access**
   - Ensure that employees have only the access necessary to perform their job functions. This reduces the risk of unauthorized access to sensitive information.

2. **Develop and Implement Disaster Recovery Plans**
   - Create comprehensive disaster recovery plans to ensure the company can quickly recover from any catastrophic events. Regularly test these plans to ensure they are effective.

3. **Strengthen Password Policies**
   - Enforce complex password requirements with a minimum length. Implement regular password changes and ensure passwords are stored securely, preferably encrypted.

4. **Implement Separation of Duties**
   - Divide responsibilities among different employees to prevent any single individual from having control over all aspects of sensitive data processing. This reduces the risk of fraud and errors.

5. **Install an Intrusion Detection System (IDS)**
   - Implement an IDS to monitor network traffic for suspicious activities and potential threats. This will help in early detection and response to security incidents.

6. **Regular Data Backups**
   - Establish a robust backup strategy with regular backups of critical data. Ensure that these backups are tested and stored securely, both on-site and off-site.

7. **Encrypt Sensitive Data**
   - Encrypt sensitive information such as passwords and credit card data. This protects the data in case of unauthorized access or data breaches.

8. **Improve User Access Policies**
   - Develop and enforce strict user access policies to ensure that only authorized personnel have access to sensitive data. Regularly review and update these policies.

9. **Enhance Physical Security Measures**
   - Maintain and regularly review physical security measures like locks, CCTV surveillance, and fire detection/prevention systems to protect against physical threats.

10. **Compliance with Industry Standards**
    - Adhere to industry standards such as PCI DSS, GDPR, and SOC. Ensure that only authorized users have access to sensitive information and that proper encryption and secure handling practices are in place.

11. **Ongoing Maintenance and Monitoring of Legacy Systems**
    - Schedule regular maintenance for legacy systems to ensure they are secure and u

