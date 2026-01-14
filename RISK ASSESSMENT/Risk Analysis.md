# Risk Analysis

This document covers the **analysis phase** of the enterprise risk management process.  
In this phase, each identified risk is assessed for **likelihood** and **impact**.  
The results are summarized in a **risk matrix** to determine overall risk levels.

---
## Risk Matrix Heat Map
<img width="443" height="212" alt="risk heatmap" src="https://github.com/user-attachments/assets/53c04b25-74b8-4c09-ae43-a67e0a839fda" />


## Likelihood Assessment
- Assign a likelihood score (1–5) for each risk based on probability of occurrence.
- Example:
  - 1 = Rare
  - 2 = Unlikely
  - 3 = Possible
  - 4 = Likely
  - 5 = Almost Certain

| Risk ID             | Risk Description | Likelihood (1-5) |
|---------------------|------------------|------------------|
| 1 RISK-TPR-001      | Third-Party Vendor Breach|    5             | 
| 2 RISK-SEC-002      | Ransomware Attack               |     4           | 
| 3 RISK-COM-003      | Non-compliance with data protection laws               |  3               |
| 4 RISK-OPS-004      | System downtime affecting availability                |   3              |
| 5 RISK-OPS-005      | Inadequate Enterprise Risk Oversight                | 4                |

---

## Impact Assessment
- Assign an impact score (1–5) for each risk based on severity.
- Example:
  - 1 = Insignificant
  - 2 = Minor
  - 3 = Moderate
  - 4 = Major
  - 5 = Catastrophic

| Risk ID | Risk Description | Impact (1-5) |
|---------|-----------------|---------------|
| 1 RISK-TPR-001      | Third-Party Vendor Breach                |   4            |
| 2 RISK-SEC-002      | Ransomware Attack                |  4             |
| 3 RISK-COM-003      | Non-compliance with data protection laws                |   3            |
| 4 RISK-OPS-004       | System downtime affecting availability                |   4            |
| 5 RISK-OPS-005      | Inadequate Enterprise Risk Oversight                |     3          |

---

## Risk Matrix
- This **5x5 matrix** visually combines likelihood and impact to determine risk level.

| Impact \ Likelihood | 1 Rare | 2 Unlikely | 3 Possible | 4 Likely | 5 Almost Certain |
|--------------------|--------|------------|------------|----------|----------------|
| **5 Catastrophic** | moderate       | high/major           | very high/extreme           | very high/extreme         |  catastrophic              |
| **4 Major**        | low       |  moderate          | high/major           | very high/extreme         | very high/extreme               |
| **3 Moderate**     |  low      |  moderate          |  high/major          | high/major         | very high/extreme               |
| **2 Minor**        |  low      |  low          |  moderate          | moderate         |   high/major             |
| **1 Insignificant**| low       | low           |   low         |   low       |  moderate              |

> For reference **risk level** (Low, Moderate, High, Very High/Extreme and Catastrophic) 



---

## Risk Scoring Table
- Multiply **Likelihood × Impact** to calculate **Risk Score**.  
- Use this score to categorize risks and prioritize treatment.

| Risk ID | Description | Likelihood | Impact | Risk Score (L×I) | Risk Level |
|---------|------------|-----------|--------|-----------------|------------|
| 1 RISK-TPR-001       |     Third-Party Vendor Breach      |    5     |    4   |       20          |  Very High/Extreme          |
| 2 RISK-SEC-002      |     Ransomware Attack      |     4     |    4   |        16         |   Very High/Extreme         |
| 3 RISK-COM-003      |     Non-compliance with data protection laws       |     3      |   3    |         9        |  High/Major          |
| 4 RISK-OPS-004      |    System downtime affecting availability       |      3    |   4    |        12         |   High/Major         |
| 5 RISK-OPS-005       |    Inadequate Enterprise Risk Oversight         |     4     |   3    |       12          |  High/Major          |

---

## Notes:
- All scoring and evaluation in this phase feeds into **Risk Evaluation** and **Treatment Planning**.
