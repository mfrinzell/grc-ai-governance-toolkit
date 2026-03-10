# Enterprise Risk Register Template

**Program:** [GRC / AI Governance / Enterprise Risk Management]  
**Last Updated:** [Date]  
**Owner:** [Risk Program Lead]  
**Review Cadence:** Monthly (active risks) | Quarterly (full register)

---

## Risk Scoring Methodology

### Likelihood Scale (1–5)
| Score | Label | Description |
|---|---|---|
| 1 | Rare | Unlikely to occur; no recent precedent |
| 2 | Unlikely | Could occur but hasn't in recent history |
| 3 | Possible | May occur; has occurred in similar orgs |
| 4 | Likely | Expected to occur; has occurred recently |
| 5 | Almost Certain | Expected to occur within 12 months |

### Impact Scale (1–5)
| Score | Label | Description |
|---|---|---|
| 1 | Negligible | Minimal disruption; no financial or reputational impact |
| 2 | Minor | Limited impact; contained and quickly resolved |
| 3 | Moderate | Noticeable impact; requires escalation and resources |
| 4 | Major | Significant financial, regulatory, or reputational harm |
| 5 | Critical | Existential threat; board-level issue; regulatory action likely |

### Risk Score = Likelihood × Impact
| Score Range | Risk Level | Action |
|---|---|---|
| 1–4 | Low | Monitor; review quarterly |
| 5–9 | Medium | Mitigate; assign owner; review monthly |
| 10–14 | High | Active remediation plan required; executive visibility |
| 15–25 | Critical | Immediate escalation; executive sponsor engaged |

---

## Risk Register

| ID | Risk Category | Risk Description | Likelihood (1–5) | Impact (1–5) | Risk Score | Risk Level | Risk Owner | Mitigation / Controls in Place | Residual Risk | Status | Target Date | Last Updated |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R-001 | AI Governance | AI system deployed without completing risk tiering and governance review | 3 | 4 | 12 | High | AI Governance Lead | Intake process established; use case registry in place | Medium | Mitigating | [Date] | [Date] |
| R-002 | Regulatory / Compliance | Failure to meet emerging AI transparency requirements (EU AI Act, state laws) | 3 | 5 | 15 | Critical | Legal / Compliance | Regulatory monitoring program in place; quarterly review | High | Monitoring | [Date] | [Date] |
| R-003 | Data Governance | Use of personally identifiable information in AI model training without proper authorization | 2 | 5 | 10 | High | Privacy Officer | Data classification policy; training data review required pre-use | Medium | Mitigating | [Date] | [Date] |
| R-004 | Third-Party / Vendor | AI vendor changes model behavior without notifying the organization | 3 | 4 | 12 | High | Vendor Risk Lead | Contractual change notification requirements; annual reassessment | Medium | Mitigating | [Date] | [Date] |
| R-005 | Operational | Bias in automated AI decision-making affects a protected class | 2 | 5 | 10 | High | AI Governance Lead | Disparate impact testing required pre-deployment (Tier 1/2) | High | Mitigating | [Date] | [Date] |
| R-006 | Cybersecurity | Adversarial attack on AI model results in incorrect outputs or data leakage | 2 | 4 | 8 | Medium | CISO | Security review required for all production AI systems | Medium | Monitoring | [Date] | [Date] |
| R-007 | Compliance | Control gaps identified in SOC 2 audit preparation | 3 | 3 | 9 | Medium | GRC Lead | Gap remediation underway; evidence collection in progress | Low | Mitigating | [Date] | [Date] |
| R-008 | Strategic | Lack of executive sponsorship slows AI governance program maturity | 2 | 4 | 8 | Medium | Program Lead | Steering committee established; quarterly executive reviews | Low | Monitoring | [Date] | [Date] |

---

## Risk Summary Dashboard

### Risk Distribution by Level

| Risk Level | Count | % of Register |
|---|---|---|
| 🔴 Critical (15–25) | 1 | 12.5% |
| 🟠 High (10–14) | 4 | 50% |
| 🟡 Medium (5–9) | 3 | 37.5% |
| 🟢 Low (1–4) | 0 | 0% |
| **Total** | **8** | |

### Risk by Category

| Category | # Risks | Highest Score |
|---|---|---|
| AI Governance | 2 | 12 (High) |
| Regulatory / Compliance | 2 | 15 (Critical) |
| Data Governance | 1 | 10 (High) |
| Third-Party / Vendor | 1 | 12 (High) |
| Cybersecurity | 1 | 8 (Medium) |
| Strategic | 1 | 8 (Medium) |

---

## Risk Treatment Options

| Treatment | Description | When to Use |
|---|---|---|
| **Mitigate** | Reduce likelihood or impact through controls | Most common; when controls are cost-effective |
| **Accept** | Acknowledge the risk; no additional action | Low-level risks or when cost to mitigate > impact |
| **Transfer** | Shift risk via insurance, contract, or third-party | Financial or liability-heavy risks |
| **Avoid** | Eliminate the activity that creates the risk | Critical risks with no acceptable mitigation path |

---

## Glossary

- **Inherent Risk:** Risk level before any controls are applied
- **Residual Risk:** Risk level after controls are applied
- **Risk Appetite:** The level of risk the organization is willing to accept in pursuit of its objectives
- **Risk Tolerance:** The acceptable variance around the risk appetite threshold
- **KRI (Key Risk Indicator):** A leading metric that signals when risk is approaching or exceeding tolerance

---

*Aligned with: ISO 31000 | COSO ERM | NIST AI RMF (Map / Measure)*
