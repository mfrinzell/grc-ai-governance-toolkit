# Third-Party & AI Vendor Risk Assessment

**Purpose:** Evaluate and document risk associated with third-party vendors, with expanded controls for vendors providing AI-enabled products or services  
**Use:** Complete prior to contract execution and annually thereafter for Tier 1/2 vendors

---

## Vendor Information

| Field | Response |
|---|---|
| Vendor Name | |
| Product / Service | |
| Business Owner (Internal) | |
| Assessment Date | |
| Assessor | |
| Contract Renewal Date | |
| Vendor Tier (1–4) | |
| AI-Enabled? (Y/N) | |

---

## Vendor Tiering

| Tier | Risk Level | Criteria | Review Frequency |
|---|---|---|---|
| Tier 1 | Critical | Access to sensitive data; mission-critical; hard to replace | Annual + event-triggered |
| Tier 2 | High | Significant data access; important but replaceable | Annual |
| Tier 3 | Medium | Limited data access; standard service | Every 2 years |
| Tier 4 | Low | No data access; commodity service | Every 3 years or as needed |

---

## Section 1: Security & Data Protection

| # | Question | Response | Notes |
|---|---|---|---|
| 1.1 | Does the vendor have a current SOC 2 Type II report? | Y / N / In Progress | |
| 1.2 | Is the vendor ISO 27001 certified? | Y / N | |
| 1.3 | What data classifications does this vendor access? | PII / Financial / Health / Confidential / Public | |
| 1.4 | Does the vendor store or process data in the cloud? | Y / N | If Y, identify provider |
| 1.5 | Where is data stored geographically? | US / EU / Other | |
| 1.6 | Does the vendor encrypt data at rest and in transit? | Y / N / Partial | |
| 1.7 | What is the vendor's breach notification SLA? | __ hours / days | |
| 1.8 | Has the vendor had a data breach in the past 3 years? | Y / N | If Y, describe |
| 1.9 | Does the vendor have a documented incident response plan? | Y / N | |
| 1.10 | Does the vendor conduct annual penetration testing? | Y / N | |

**Section Score (Y=1, N=0, Partial=0.5):** ___ / 10  
**Section Risk Rating:** 🟢 Low (8–10) | 🟡 Medium (5–7) | 🔴 High (0–4)

---

## Section 2: Privacy & Compliance

| # | Question | Response | Notes |
|---|---|---|---|
| 2.1 | Does the vendor have a documented privacy policy? | Y / N | |
| 2.2 | Is a Data Processing Agreement (DPA) in place or available? | Y / N | |
| 2.3 | Does the vendor comply with applicable regulations (CCPA, GDPR, HIPAA, etc.)? | Y / N / Partial | |
| 2.4 | Does the vendor use subprocessors? | Y / N | If Y, are they disclosed? |
| 2.5 | Does the vendor allow data deletion upon contract termination? | Y / N | |
| 2.6 | What is the vendor's data retention policy? | | |
| 2.7 | Does the vendor support audit rights in the contract? | Y / N | |
| 2.8 | Has the vendor received regulatory enforcement actions? | Y / N | If Y, describe |

**Section Score:** ___ / 8  
**Section Risk Rating:** 🟢 Low | 🟡 Medium | 🔴 High

---

## Section 3: Business Continuity & Resilience

| # | Question | Response | Notes |
|---|---|---|---|
| 3.1 | Does the vendor have a documented Business Continuity Plan (BCP)? | Y / N | |
| 3.2 | Does the vendor have a Disaster Recovery (DR) plan with defined RTOs/RPOs? | Y / N | |
| 3.3 | What is the vendor's documented SLA uptime? | __% | |
| 3.4 | Has the vendor experienced significant outages in the past 12 months? | Y / N | If Y, describe |
| 3.5 | Does the vendor have redundant infrastructure? | Y / N | |
| 3.6 | What is the vendor's financial stability? | Stable / At Risk / Unknown | |
| 3.7 | Is this a sole-source or easily replaceable vendor? | Sole / Replaceable | |

**Section Score:** ___ / 7  
**Section Risk Rating:** 🟢 Low | 🟡 Medium | 🔴 High

---

## Section 4: AI-Specific Controls
*Complete this section only for vendors providing AI-enabled products or services*

| # | Question | Response | Notes |
|---|---|---|---|
| 4.1 | Does the vendor provide documentation of how the AI model works (model card, technical documentation)? | Y / N / Partial | |
| 4.2 | Has the vendor conducted bias or fairness testing on the AI system? | Y / N | If Y, request results |
| 4.3 | Does the vendor provide explainability for AI-generated outputs? | Y / N / Partial | |
| 4.4 | Does the vendor notify customers of significant model changes before deployment? | Y / N | |
| 4.5 | What data is used to train or fine-tune the model? Is customer data used? | | |
| 4.6 | Does the vendor have controls preventing unauthorized use of customer data in training? | Y / N | |
| 4.7 | Does the vendor have a process for handling AI-related incidents or errors? | Y / N | |
| 4.8 | Is the AI system subject to human oversight for high-stakes decisions? | Y / N / Partial | |
| 4.9 | Has the vendor assessed the AI system against NIST AI RMF or equivalent framework? | Y / N | |
| 4.10 | What is the vendor's process for model drift monitoring and updates? | | |
| 4.11 | Does the vendor provide audit logs for AI decisions (where applicable)? | Y / N | |
| 4.12 | Is the AI system used for automated decision-making that affects individuals? | Y / N | If Y, note safeguards |

**Section Score:** ___ / 12  
**Section Risk Rating:** 🟢 Low (10–12) | 🟡 Medium (6–9) | 🔴 High (0–5)

---

## Section 5: Contractual Requirements Checklist

Ensure the following provisions are included in the vendor contract:

| # | Requirement | In Contract? | Notes |
|---|---|---|---|
| 5.1 | Data Processing Agreement (DPA) | Y / N | |
| 5.2 | Security incident notification within 72 hours | Y / N | |
| 5.3 | Audit rights (right to assess or request SOC 2) | Y / N | |
| 5.4 | Data deletion upon contract termination | Y / N | |
| 5.5 | Subprocessor disclosure and approval requirement | Y / N | |
| 5.6 | AI model change notification requirement | Y / N (AI only) | |
| 5.7 | Data use restrictions (no training on customer data without consent) | Y / N (AI only) | |
| 5.8 | Indemnification for data breach or AI-related harm | Y / N | |
| 5.9 | Business continuity / SLA commitments | Y / N | |
| 5.10 | Regulatory compliance representations | Y / N | |

---

## Overall Risk Assessment Summary

| Section | Score | Risk Rating |
|---|---|---|
| 1. Security & Data Protection | / 10 | |
| 2. Privacy & Compliance | / 8 | |
| 3. Business Continuity | / 7 | |
| 4. AI-Specific Controls (if applicable) | / 12 | |
| **Overall** | | |

### Overall Vendor Risk Rating:
- 🟢 **Low Risk** — Approved; standard monitoring
- 🟡 **Medium Risk** — Approved with conditions; document compensating controls
- 🔴 **High Risk** — Escalate for executive review; additional due diligence required before approval

---

## Assessment Outcome

| Field | Response |
|---|---|
| **Recommended Action** | Approve / Approve with Conditions / Escalate / Do Not Proceed |
| **Conditions (if any)** | |
| **Open Items / Follow-ups** | |
| **Next Review Date** | |
| **Approved By** | |
| **Approval Date** | |

---

*Aligned with: NIST AI RMF | ISO 27001 | SOC 2 | CCPA/GDPR vendor management requirements*
