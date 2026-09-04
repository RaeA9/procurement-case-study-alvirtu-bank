# Stakeholder Matrix – Core Banking System Replacement Project (AlVirtu Bank)

**Date of Issue:** July 10, 2026  
**Version:** 1.0  
**Document Classification:** Top Secret (Internal Circulation Only)

---

## 1. Introduction

This document maps the internal power dynamics and influential stakeholders guiding the decision to replace the Core Banking System. This matrix is designed to define communication channels, manage expectations, and ensure executive alignment behind the Strategic Procurement department before issuing the RFP, in compliance with SAMA's "Outsourcing Risk Management Framework" and "Cloud Computing Framework."

---

## 2. Power/Interest Grid

### High Power – High Interest (Proactive Management / Strategic Partnership)

**CEO (Chief Executive Officer):**
- **Role:** Executive Sponsor of the project.
- **Core Interest:** Protecting the bank's reputation, strict adherence to SAMA mandates, market share growth, and ensuring zero disruption to critical banking operations during the transition.
- **Veto Power:** Can freeze or cancel the project entirely if any risk threatens the bank's stability or financial sector reputation.
- **Engagement Strategy:** Monthly steering committee meetings and concise (3-page) executive dashboards.

**COO (Chief Operating Officer):**
- **Role:** Business Continuity Kingpin and final recipient of system stability.
- **Core Interest:** Branch and digital channel stability, Transactions Per Second (TPS) velocity, clearing and settlement efficiency, and End-of-Day (EOD) processing times. Focused on avoiding "operational chaos" and manual double-entry during migration.
- **Veto Power:** Authority to halt the Go-Live decision if the system fails to demonstrate 100% stability in the pilot environment, or if the Rollback Plan is deemed unsafe.
- **Engagement Strategy:** Appointed as Deputy Chair of the Steering Committee; directly involved in drafting SLAs and operational liquidation damages.

**CIO (Chief Information Officer):**
- **Role:** Technical owner and overseer of Enterprise Architecture.
- **Core Interest:** System modernity, scalability, API flexibility, ease of integration with legacy systems, and minimizing heavy customization.
- **Veto Power:** Rejection of any vendor whose solution does not align with the bank's strategic technology roadmap or relies on outdated programming languages.
- **Engagement Strategy:** Appointed as Head of the Technical Evaluation Committee; involved in first-line technical capability assessments.

**CISO (Chief Information Security Officer):**
- **Role:** First line of cyber defense for the bank and customer data.
- **Core Interest:** Preventing data exfiltration outside KSA (Data Residency), encryption of data at-rest and in-transit, and strict IAM (Identity and Access Management) for third-party developers.
- **Veto Power:** Immediate and retroactive exclusion of any vendor failing to meet SAMA cybersecurity controls, regardless of financial attractiveness.
- **Engagement Strategy:** Leading the drafting of the mandatory cybersecurity appendix in the RFP; overseeing continuous SAST/DAST code reviews.

**CRO (Chief Risk Officer):**
- **Role:** Assessing operational, credit, and sovereign risks arising from outsourcing the Core Banking system.
- **Core Interest:** Vendor financial viability, vendor concentration risk, and verification of a secure Exit Strategy.
- **Veto Power:** Refusal to sign off on the project risk assessment (a SAMA mandatory requirement) if the vendor relies on legally unapproved subcontractors.
- **Engagement Strategy:** Provision of detailed financial reports on vendors; involvement in Third-Party Risk Matrix (TPRM) review.

**General Counsel:**
- **Role:** The bank's contractual shield and guardian of judicial rights.
- **Core Interest:** Limitation of Liability, Indemnities, Termination Clauses, and Source Code Escrow Agreements.
- **Veto Power:** Halting RFP issuance if it lacks legal formulations protecting the bank from IP disputes or finger-pointing liabilities.
- **Engagement Strategy:** Permanent membership in the Strategic Negotiation Committee; pre-review of the draft contract.

**Head of Compliance:**
- **Role:** Ensuring project adherence to all SAMA and SDAIA regulations.
- **Core Interest:** 100% Data Residency, PDPL (Personal Data Protection Law) compliance, and Outsourcing Rules.
- **Veto Power:** Rejection of any vendor proven to deal with locally unlicensed cloud providers.
- **Engagement Strategy:** Audit review of all regulatory contract clauses; drafting the SAMA prior notification package.

**Head of Corporate & Treasury:**
- **Role:** Financial and commercial representative for large corporate clients and liquidity management.
- **Core Interest:** Complex integration with Trade Finance, Cash Management, and Treasury systems (spot and forward markets).
- **Veto Power:** Disabling RFP approval if it omits corporate sector operational requirements, risking loss of key clients.
- **Engagement Strategy:** Corporate representatives as key members in requirements workshops and UAT (User Acceptance Testing).

---

### High Power – Medium Interest (Keep Satisfied & Aligned)

**CFO (Chief Financial Officer):**
- **Core Interest:** Budget adherence, TCO model accuracy, milestone-based payment structures, and ROI.
- **Veto Power:** Financial veto if costs exceed the approved feasibility study range without strategic justification.
- **Engagement Strategy:** Dynamic financial models that expose hidden fees and prohibit random Change Orders.

---

### Medium Power – High Interest (Keep Informed & Engaged)

**Head of Retail Banking:** Focuses on the system's impact on individual sales, account opening speed, loans, and cards via apps and branches to achieve sales KPIs.
**Retail Operations & Treasury Operations Managers:** Focus on staff interface ease and instantaneous trade pricing stability.

---

## 3. Strategic Conflicts & Alliances Analysis

- **Conflict 1: COO & CISO vs. CIO (Stability/Security vs. Digital Innovation).**
  - *Nature:* CIO may prefer cutting-edge Cloud-Native/Microservices, while COO/CISO favor established, locally-proven legacy solutions to avoid operational shocks or cyber gaps.
  - *Procurement Solution:* Mandate that all vendors submit proven track records of the exact proposed version used in regional banks, with independent cyber audits.

- **Conflict 2: COO vs. CFO (Operational Quality/Support vs. Budget Pressure).**
  - *Nature:* CFO pressures to minimize post-sale support costs, while COO demands 24/7 Premium Support with on-site vendor consultants in Riyadh during launch.
  - *Procurement Solution:* Draft an "All-Inclusive" pricing clause in the RFP that bundles premium support and on-site emergency engineers into the base price to prevent later Change Orders.

- **Strategic Alliance (The Power Triangle):** (CEO + COO + CISO + Compliance). This unified internal front ensures procurement negotiates with the authority of operations, national sovereignty, and security, cutting off any vendor attempting "technical concessions" for lower prices.

---

## 4. Governance & Communication Plan

- **Steering Committee:** (CEO, COO, CIO, CISO, CRO, GC, Head of Compliance) meets bi-weekly to review Gate progress and strategic decisions.
- **Joint Technical/Operational Committee:** (IT, InfoSec, Corporate/Retail/Treasury representatives, Procurement) meets weekly to draft and review RFP specifics.
- **Transparent Reporting:** Monthly newsletters to all bank departments and regional branches to psychologically and operationally prepare staff for the upcoming transformation.