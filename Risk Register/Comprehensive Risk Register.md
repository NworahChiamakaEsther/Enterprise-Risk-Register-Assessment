# Comprehensive Risk Register

## Purpose
This register documents all identified risks, their analysis, existing controls, and planned treatment strategies.  
It captures the initial assessment before treatment and serves as the foundation for risk monitoring and reporting.  

---

## Risk Register

| Risk ID        | Risk Description                                         | Category        | Likelihood (1–5) | Impact (1–5) | Risk Score | Risk Level | Existing Controls                                | Treatment Strategy | Risk Owner |
|---------------|----------------------------------------------------------|-----------------|------------------|--------------|------------|------------|-------------------------------------------------|------------------|------------|
| RISK-TPR-001  | Unauthorized access or exposure of sensitive customer data by third-party vendors | Third-Party     | 4                | 5            | 20         | Critical   | Vendor onboarding, NDA, limited system access, annual vendor assessments | Mitigate – implement stricter access controls, SOC 2/ISO 27001 certifications, regular audits | Compliance Lead |
| RISK-CYB-002  | Ransomware infection encrypting critical systems, disrupting operations | Cybersecurity   | 3                | 5            | 15         | High       | Endpoint Detection and Response (EDR), regular backups, firewall, patch management | Mitigate – strengthen incident response plan, phishing awareness, network segmentation | IT Manager |
| RISK-OPS-003  | Key service disruption due to cloud system downtime affecting clients | Operational     | 3                | 4            | 12         | High       | Redundant infrastructure, monitoring tools, SLA with cloud provider | Mitigate – enhance disaster recovery plan, failover testing | Operations Lead |
| RISK-COM-004  | Regulatory non-compliance related to NDPR/GDPR affecting operations | Compliance      | 2                | 5            | 10         | Medium     | Internal audits, compliance checks, employee training | Monitor – continuous regulatory review and updates | Compliance Lead |

---

## Notes
- **Risk Score** = Likelihood × Impact  
- **Risk Level**:
  - Low: 1–5  
  - Medium: 6–10  
  - High: 11–15  
  - Critical: 16–25  
- **Treatment Strategy** options: Mitigate, Transfer, Accept, Avoid  
- All risk owners are responsible for **monitoring their risks** and reporting updates regularly.  
- This register serves as the **primary reference for residual risk tracking** after treatment.

---

## References
- ISO 31000:2018 – Risk Management Guidelines  
- COSO Enterprise Risk Management Framework  
  
