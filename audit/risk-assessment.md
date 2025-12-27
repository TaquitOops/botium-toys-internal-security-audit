# Risk Assessment

## Main Security Risks Identified

The internal security audit for Botium Toys revealed a high-risk security posture due to significant gaps in administrative and technical controls.

Key risks identified include:

- **Violation of the Principle of Least Privilege:**  
  All employees have unrestricted access to internal systems and sensitive data, increasing the impact of account compromise and insider threats.

- **Lack of Data Encryption:**  
  Sensitive information, including customer PII and payment card data, is not encrypted in transit or at rest, resulting in non-compliance with PCI DSS requirements.

- **Absence of Disaster Recovery and Backups:**  
  The organization lacks a formal disaster recovery plan and does not perform regular automated backups.

- **Legacy Systems and Manual Processes:**  
  Reliance on legacy systems requiring manual monitoring increases exposure to unpatched vulnerabilities and human error.

- **Weak Authentication Controls:**  
  There are no enforced password policies or Multi-Factor Authentication (MFA), making systems vulnerable to credential-based attacks.

- **Missing Monitoring and Detection Controls:**  
  The absence of an Intrusion Detection System (IDS) prevents the timely detection of malicious activity.

## Business Impact

These risks create a fragile security environment where a single compromised account could lead to full system compromise, prolonged undetected breaches, irreversible data loss, and regulatory violations.

## Potential Consequences

If these risks are not addressed, Botium Toys could face severe financial penalties, loss of payment processing capabilities, business interruption due to ransomware attacks, and long-term reputational damage resulting from customer data breaches.
