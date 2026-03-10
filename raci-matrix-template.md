# RACI / DACI Matrix Templates for GRC & AI Governance Programs

**Purpose:** Define cross-functional accountability for governance, risk, and compliance workstreams  
**Format:** Adaptable for Confluence, Notion, SharePoint, or Google Sheets

---

## Key: RACI Definitions

| Letter | Role | Description |
|---|---|---|
| **R** | Responsible | Does the work; executes the task |
| **A** | Accountable | Owns the outcome; single throat to choke; approves deliverables |
| **C** | Consulted | Provides input; two-way communication required before decisions |
| **I** | Informed | Receives updates; no action required |

> **Rule:** Each row must have exactly **one A**. Multiple R's are allowed. Blank = not involved.

---

## Key: DACI Definitions (Decision-Making Variant)

| Letter | Role | Description |
|---|---|---|
| **D** | Driver | Owns the decision process; moves it forward |
| **A** | Approver | Has final decision authority |
| **C** | Contributor | Provides expertise and input |
| **I** | Informed | Notified of outcome |

---

## Template 1: AI Governance Program RACI

**Roles across top (customize to your org):**

| Activity | AI Gov Lead | Legal / Compliance | Privacy | Security | BU Lead | Data Gov | Executive Sponsor | HR / Ethics |
|---|---|---|---|---|---|---|---|---|
| AI use case intake & registration | R/A | C | C | C | R | C | I | I |
| Risk tier assignment | R/A | C | C | C | C | I | I | I |
| Bias & fairness assessment | R | C | C | I | C | I | I | A |
| Model card creation | R | I | C | C | A | R | I | I |
| Pre-production approval gate | C | C | C | C | R | I | A | C |
| Vendor AI risk assessment | R/A | C | C | C | C | I | I | I |
| AI incident response (Tier 1/2) | R | C | C | R | C | I | A | I |
| Executive / Board reporting | R | C | I | I | I | I | A | I |
| Policy review and maintenance | R/A | R | C | C | I | C | I | I |
| Annual AI system reassessment | R/A | C | C | C | R | R | I | I |
| Regulatory change monitoring | C | R/A | C | I | I | I | I | I |

---

## Template 2: GRC Program RACI

| Activity | GRC Program Lead | CISO / Security | Legal | Compliance | Internal Audit | BU Owner | CRO / Executive |
|---|---|---|---|---|---|---|---|
| Risk register ownership & maintenance | R/A | C | C | C | I | C | I |
| Control design and documentation | R | C | C | R | C | A | I |
| Control testing / evidence collection | C | R | I | R | A | R | I |
| Risk assessment (BU-level) | R | C | C | C | I | A | I |
| Policy creation and review | R | C | A | R | I | C | I |
| Audit coordination | C | C | C | R | A | R | I |
| Regulatory filing / submission | I | I | A | R | I | I | I |
| Board / committee reporting | R | C | C | C | I | I | A |
| Third-party / vendor risk | R/A | C | C | C | I | R | I |
| Incident management (GRC scope) | R | R | C | R | I | C | A |
| Training and awareness | R | C | C | R | I | A | I |

---

## Template 3: DACI — AI Use Case Approval Decision

**Decision:** Approve or deny a new AI system for production deployment

| Role | Who | Responsibility |
|---|---|---|
| **Driver** | AI Governance Lead / TPM | Coordinates review, assembles documentation, runs the approval process |
| **Approver** | Executive Sponsor | Final sign-off authority for Tier 1 systems |
| **Approver** | BU Lead | Final sign-off authority for Tier 3–4 systems (delegated) |
| **Contributor** | Legal & Compliance | Regulatory and contractual review |
| **Contributor** | Privacy | Data handling and consent review |
| **Contributor** | Security | Threat model and access control review |
| **Contributor** | Data Governance | Training data quality and lineage review |
| **Informed** | Internal Audit | Notified of approval; added to audit schedule |
| **Informed** | HR / Ethics | Notified for workforce impact awareness |

---

## Template 4: DACI — GRC Risk Escalation Decision

**Decision:** Escalate an identified risk to the executive or board level

| Role | Who | Responsibility |
|---|---|---|
| **Driver** | GRC Program Lead | Identifies escalation need; prepares risk brief |
| **Approver** | CRO / CFO / CEO (based on risk type) | Accepts, mitigates, or transfers the risk |
| **Contributor** | Legal | Assesses regulatory or litigation exposure |
| **Contributor** | CISO | Assesses technical or security dimensions |
| **Contributor** | BU Owner | Provides operational context and impact |
| **Informed** | Board / Audit Committee | Informed via executive reporting cycle |
| **Informed** | Internal Audit | Tracks open risk items |

---

## Template 5: Program Launch RACI (Generic)

Use this for standing up a new GRC or governance workstream.

| Activity | Program Lead | Executive Sponsor | Workstream Leads | SMEs | Stakeholders |
|---|---|---|---|---|---|
| Define program scope and objectives | R/A | A | C | C | I |
| Stakeholder identification and mapping | R/A | I | C | I | I |
| Current state assessment | R | I | R | R | C |
| Gap analysis and roadmap development | R/A | C | R | C | I |
| Resource and budget planning | R | A | C | I | I |
| Communications and change management | R/A | C | C | I | I |
| Milestone tracking and status reporting | R/A | I | R | I | I |
| Executive steering updates | R | A | C | I | I |

---

## Tips for Operationalizing RACIs

1. **Review with the team before finalizing** — alignment on accountability prevents future conflict
2. **One A per row is a hard rule** — if two people claim ownership, escalate to resolve before go-live
3. **Revisit quarterly** — org changes and role shifts make RACIs stale fast
4. **Link your RACI to your risk register** — each risk line item should have a clear owner (A)
5. **Use in kickoff meetings** — presenting the RACI at program launch sets expectations early and reduces ambiguity

---

*Format compatible with: Confluence | Notion | Google Docs | SharePoint | Excel/Sheets*
