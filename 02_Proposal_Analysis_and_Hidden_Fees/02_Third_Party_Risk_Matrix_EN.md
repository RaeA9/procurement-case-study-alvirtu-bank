# Third-Party Risk Matrix (TPRM) – AlVirtu Bank

**Date of Preparation:** July 10, 2026  
**Version:** 1.0  
**Document Status:** Confidential (Evaluation & Risk Committee)  
**Reference:** SAMA Outsourcing Risk Management Framework

---

## 1. Executive Dashboard (Summary of Overall Risk)

| Prime Vendor | Number of Subcontractors | Data Residency Compliance | Overall Risk Level | Preliminary Decision |
| :---: | :---: | :---: | :---: | :--- |
| **Vendor (A)** | 2 | ❌ **Non-Compliant** (Data outside KSA) | 🔴 **Very High (Knock-out)** | **Immediate Rejection** |
| **Vendor (B)** | 2 | ✅ **100% Compliant** (All Data in KSA) | 🟢 **Low** | **Proceed to Negotiations** |
| **Vendor (C)** | 2 | ❌ **Non-Compliant** (Data outside KSA) | 🔴 **Very High (Knock-out)** | **Immediate Rejection** |

---

## 2. Detailed Risk Analysis (Per Vendor)

### A. Vendor (A) – Subcontractors

| Subcontractor | Service Provided | Geographic Location | Detected Risks | Impact Level | Required Mitigation Action |
| :--- | :--- | :--- | :--- | :---: | :--- |
| **Cloud Provider** | Hosting Dev, Testing environments, and Backups. | Dublin, Ireland | **Explicit violation of SAMA CCF Article (6)**; storing client and test data outside KSA borders. | 🔴 **Critical (Knock-out)** | **Mandate transfer of all environments to a locally licensed provider within 30 days, with a formal signed affidavit.** |
| **International Consulting Firm (SI)** | Implementation and Integration Management. | India / UK | Difficulty in direct oversight, time-zone delays, and high risk of data leakage via remote access channels. | 🟡 **High** | **Mandate that all implementation team members handling sensitive data be physically present in KSA, with VDI and session recording activated.** |

**Final Classification for Vendor (A):** 🔴 **Rejected** – Violates the fundamental Data Residency knock-out criterion.

---

### B. Vendor (B) – Subcontractors (The Only Qualified Bidder)

| Subcontractor | Service Provided | Geographic Location | Detected Risks | Impact Level | Required Mitigation Action |
| :--- | :--- | :--- | :--- | :---: | :--- |
| **Locally Licensed Cloud Provider** | Hosting ALL environments (Prod, UAT, Dev, DR, Testing, Backups). | Riyadh, KSA | **100% compliant with all SAMA requirements.** No sovereign or legal risks. | 🟢 **Very Low** | Maintain current status, with annual reviews of SOC 2 Type II reports. |
| **Local Major Consulting Firm (SI)** | Implementation, Management, and Knowledge Transfer. | Riyadh, KSA | Stable team, same time-zone, easy direct supervision. | 🟢 **Low** | Strengthen the contract with (Joint & Several Liability) clauses to ensure full coverage. |

**Final Classification for Vendor (B):** 🟢 **Accepted** – The only vendor satisfying all localization and oversight conditions. Proceed to final negotiations.

---

### C. Vendor (C) – Subcontractors

| Subcontractor | Service Provided | Geographic Location | Detected Risks | Impact Level | Required Mitigation Action |
| :--- | :--- | :--- | :--- | :---: | :--- |
| **Global Cloud Provider** | Hosting ALL environments (including Production). | Frankfurt, Germany | **Explicit and severe violation of SAMA CCF Article (6)**. Storing client production data outside KSA is a top-tier sovereign/security breach. | 🔴 **Critical (Knock-out)** | **Immediate rejection; this is not fixable without a complete structural bid rework.** |
| **Low-Cost Consulting Firm** | Implementation and Operational Support. | South East Asia | High financial risk (company is new and financially unstable), severe lack of required Core Banking technical expertise. | 🔴 **Very High** | **Non-mitigable**; due to poor financial stability, the entire vendor is recommended for rejection. |

**Final Classification for Vendor (C):** 🔴 **Rejected** – Violates the knock-out criterion and relies on an unreliable financial partner.

---

## 3. Strategic Gap Analysis

| Critical Risk Factor | Vendor (A) | Vendor (B) | Vendor (C) | Unified Recommendation |
| :--- | :---: | :---: | :---: | :--- |
| **SAMA CCF Data Residency** | ❌ | ✅ | ❌ | Disqualify any vendor not meeting this absolute condition. |
| **Financial Stability of Subcontractors** | 🟡 | ✅ | 🔴 | Adopt an annual financial audit plan for all strategic partners. |
| **Operational Controllability** | 🔴 | ✅ | 🔴 | Mandate that the core implementation team be based inside KSA. |
| **Liability Structure Clarity** | 🟡 | ✅ | 🔴 | Enforce full Joint & Several Liability on the prime vendor. |

---

## 4. Final Recommendation for the Evaluation Committee

1.  **Immediate disqualification of both Vendor (A) and Vendor (C)** for their involvement in an explicit violation of national data sovereignty, as defined in the RFP's Knock-out Criterion.
2.  **Adoption of Vendor (B) as the sole strategic option**, for the following reasons:
    - Full and comprehensive compliance with SAMA's Data Residency requirements.
    - Locally based implementation partners subject to direct oversight.
    - Operational stability ensuring business continuity without legal complications.
3.  **Negotiation Recommendation**: Enter exclusive negotiations with Vendor (B), focusing on improving maintenance terms and fixing developer man-day rates, while keeping Vendor (A) as a theoretical backup only if they completely restructure their offer to localize ALL their environments within a specified timeframe (which is considered unlikely).

---

*© 2026 AlVirtu Bank – Risk Management & Strategic Procurement Unit*