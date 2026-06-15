# Healthcare AI Vendor Risk Assessment Framework

## Overview

This project provides a structured framework for assessing Generative AI vendors operating within healthcare environments.

The assessment model enables organizations to evaluate vendor risk through stakeholder questionnaires, vendor questionnaires, and weighted risk scoring. The framework assesses vendor security, privacy, governance, compliance, and operational risks while providing a transparent methodology for risk classification and approval decisions.

The solution was developed using Microsoft Excel and incorporates configurable scoring logic, weighted risk calculations, and governance-focused evaluation criteria suitable for healthcare and other regulated environments.

---

## Project Highlights

- Developed a Healthcare AI Vendor Risk Assessment Framework using Microsoft Excel.
- Designed a weighted risk scoring methodology across nine assessment domains.
- Created stakeholder and vendor questionnaires to support AI due diligence activities.
- Implemented configurable scoring logic and risk classification criteria.
- Developed a repeatable assessment process aligned with AI Governance and Third-Party Risk Management (TPRM) practices.
- Created a framework suitable for healthcare organizations evaluating Generative AI vendors.

---

## Key Features

### Internal Stakeholder Questionnaire

Captures business requirements, data sensitivity, regulatory considerations, and risk factors before engaging an AI vendor.

### Vendor Security Questionnaire

Evaluates vendors across critical risk domains including:

- Governance
- Data Privacy
- Information Security
- Model Governance
- Technology Integration
- Third-Party Risk
- Legal & Compliance
- Access Management

### Automated Risk Scoring

Uses weighted scoring methodologies to calculate overall vendor risk.

### Decision Support

Provides risk categorization and recommendation outputs to support procurement, risk management, and governance decisions.

---

## Risk Scoring Methodology

The framework uses a weighted scoring model to evaluate the overall risk posture of AI vendors.

### Response Scoring Logic

Responses from stakeholder and vendor questionnaires are converted into numerical values:

| Response | Score | Counted in Assessment |
|-----------|---------|----------------------|
| Yes | 1.0 | Yes |
| Partial | 0.5 | Yes |
| No | 0.0 | Yes |
| N/A | Excluded | No |
| Descriptive Response | Excluded | No |

### Section Score Calculation

Each assessment category is scored independently using the following formula:

**Section Score (%) = Total Score ÷ Total Questions Answered × 100**

### Weighted Assessment Categories

To reflect the relative importance of different risk domains, weighted scoring is applied.

| Assessment Category | Weight |
|---------------------|---------|
| Stakeholder Assessment | 10% |
| General Discovery | 5% |
| Data Privacy | 20% |
| Model Governance | 15% |
| Information Security | 25% |
| Technology Integration | 5% |
| Third-Party Risk | 10% |
| Legal & Compliance | 5% |
| Access Management | 5% |

**Total Weight = 100%**

### Overall Risk Score Calculation

The overall vendor score is calculated by summing the weighted scores from all assessment categories.

**Overall Risk Score (%) = Sum of All Weighted Category Scores**

### Risk Rating Criteria

| Overall Score | Risk Rating | Recommended Decision |
|--------------|-------------|----------------------|
| 90% – 100% | Low Risk | Approved |
| 80% – 89% | Moderate Risk | Approved with Minor Conditions |
| 70% – 79% | Medium Risk | Risk Review Required |
| 50% – 69% | High Risk | Remediation Required |
| Below 50% | Critical Risk | Reject Vendor |

### Example Calculation

If a vendor achieves:

- Information Security Score = 100%
- Information Security Weight = 25%

Then:

**Weighted Contribution = 100% × 25% = 25%**

The same calculation is performed for all assessment categories and summed to determine the final vendor risk score.

> Note: Weightings, thresholds, and scoring criteria can be customized to align with organizational risk appetite, regulatory requirements, and customer-specific assessment objectives.

---

## Risk Domains Covered

- AI Governance
- Data Privacy
- Information Security
- Model Security
- Third-Party Risk
- Human Oversight
- Regulatory Compliance
- Incident Response
- Vendor Management
- Access Management

---


## Author

**Chris Daniel**

Cybersecurity | GRC | ISO 27001 | Third-Party Risk Management | AI Governance

LinkedIn: https://www.linkedin.com/in/chrisdaniel2004

GitHub: https://github.com/Cyber-watchman

---

## Disclaimer

This framework is intended for educational, portfolio, and demonstration purposes. Organizations should adapt the assessment criteria, scoring methodology, governance requirements, and risk thresholds to align with their specific regulatory, legal, and operational obligations.
