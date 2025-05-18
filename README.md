
# Risk Register: Coastal Community Bank

**Scope:** This project focused on creating a risk register for a fictional commercial bank. Key activities included:

- Assessing the likelihood of each identified risk.
- Determining the severity of each risk's potential impact.
- Calculating a priority score for each risk (Likelihood x Severity).
- Comparing risk scores to facilitate the team's prioritization of remediation efforts.
  
![image](https://github.com/user-attachments/assets/0b3d8dc1-f5f1-4cc3-be92-fef04e639e41)

---
## 📍 Operational Environment
The bank is located in a coastal area with low crime rates. The organization operates with:
- 100 on-premise employees
- 20 remote employees
- 2,000 individual customer accounts
-  200 commercial customer accounts
- Marketing partnerships with a professional sports team and 10 local businesses

📝 The bank is subject to strict financial regulations, including Federal Reserve requirements for daily cash availability.

---

## Risk Matrix

![image](https://github.com/user-attachments/assets/ba25eae2-7a75-417f-be2e-9f2946ce610b)

---

## Risk Register Table

### Asset: Funds 

| ⚠️ Risk(s)                     | 📝 Description                                                   | Likelihood | Severity |  Priority |
|-------------------------------|------------------------------------------------------------------|---------------|-------------|--------------|
| Business email compromise      | An employee is tricked into sharing confidential information.    | 2             | 2           | 4            |
| Compromised user database | Customer data is poorly encrypted.  | 2             | 3           | 6            |
| Financial records leak | A database server of backed up data is publicly accessible.  | 3             | 3           | 9            |
| Theft                  | The bank's safe is left unlocked.                             | 1             | 3           | 3            |
| Supply chain disruption | Delivery delays due to natural disasters.                     | 1             | 2           | 2            |

---

## 🛡️ Remediation Strategies

Based on the identified risks and their severity, the following remediation strategies are recommended:

**High Priority (Financial records leak):**

* **Immediate Action:** Conduct an urgent review of the backup database server's configuration and access controls. Ensure it is not publicly accessible and implement strict firewall rules.
* **Long-Term Strategy:** Implement secure lifecycle management for backup data, including encryption at rest and in transit, and regular access audits. Consider isolating backup infrastructure from the primary network.

**Medium Priority (Compromised user database):**

* **Short-Term Action:** Evaluate the current encryption methods used for customer data. If inadequate, develop a plan for stronger encryption implementation.
* **Long-Term Strategy:** Adopt industry-standard encryption algorithms (e.g., AES-256) for all sensitive data at rest and in transit. Implement robust key management practices. Consider data masking or tokenization where appropriate.

**Medium Priority (Business email compromise):**

* **Short-Term Action:** Implement mandatory security awareness training for all employees, focusing on identifying phishing attempts and social engineering tactics.
* **Long-Term Strategy:** Deploy technical controls such as DMARC, DKIM, and SPF for email authentication. Consider implementing advanced threat protection solutions for email. Enforce multi-factor authentication (MFA) for all employee accounts, especially those with access to sensitive information.

**Low Priority (Theft):**

* **Immediate Action:** Reinforce existing policies and procedures regarding the locking of the bank's safe. Conduct regular reminders and spot checks.
* **Long-Term Strategy:** Consider implementing additional physical security controls such as access control systems with audit trails for the safe, and potentially timed locks.

**Low Priority (Supply chain disruption):**

* **Short-Term Action:** Identify critical dependencies within the supply chain that could impact daily operations (e.g., cash delivery).
* **Long-Term Strategy:** Develop contingency plans for potential disruptions, such as identifying alternative suppliers or adjusting operational procedures to accommodate delays. Consider insurance coverage for significant supply chain disruptions.

These strategies aim to address the identified vulnerabilities and improve the overall security posture of Coastal Community Bank. Regular review and updates to these strategies will be necessary as the threat landscape evolves.

---

> *Every identified risk is an opportunity to strengthen our defenses and build a more secure future.*

