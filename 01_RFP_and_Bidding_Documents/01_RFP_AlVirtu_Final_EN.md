# Request for Proposal (RFP) – Core Banking System Replacement
## AlVirtu Bank – Kingdom of Saudi Arabia

**RFP No.:** RFP-AlVirtu-2026-001  
**Date of Issue:** July 10, 2026  
**Document Status:** Official (Ready for Vendor Distribution)

---

## 1. Executive Summary

AlVirtu Bank seeks to replace its legacy Core Banking System, which currently hinders growth, innovation, and regulatory compliance. This project aims to enhance operational efficiency, enable advanced digital services, ensure full compliance with SAMA and SDAIA regulations, and support the Kingdom's Vision 2030 for financial sector digital transformation.

**Estimated Project Value:** $50M – $120M USD (Including Licensing, Implementation, 5-year Maintenance, and Integration).

---

## 2. About AlVirtu Bank

| Attribute | Details |
| :--- | :--- |
| **Full Name** | AlVirtu Bank |
| **License** | Licensed by SAMA |
| **Headquarters** | Riyadh, Kingdom of Saudi Arabia |
| **Number of Branches** | 45 branches across the Kingdom |
| **Customer Base** | 2.5 million customers (Individuals & Corporates) |
| **Assets** | 95 Billion SAR |
| **Employees** | 1,800 Employees |
| **Current Systems** | Legacy Core System (12 years old) |
| **Digital Channels** | Mobile App, Web Portal, Centralized Call Center |

---

## 3. Strategic Objectives

1. **Enhance Regulatory Compliance:** Fully and automatically meet all SAMA requirements.
2. **Improve Customer Experience:** Provide seamless and personalized digital services.
3. **Reduce Operational Costs:** By 30% within 3 years through automation.
4. **Accelerate Innovation:** Enable the launch of new products and services in days instead of months.
5. **Ensure Operational Continuity:** Provide a system with 99.999% availability and a SAMA-approved disaster recovery plan.
6. **Governance & Security:** Apply the highest standards of security governance and cyber compliance in line with the SAMA framework.

---

## 4. Project Scope

### 4.1 Functional Scope

| Domain | Details |
| :--- | :--- |
| **Account Management** | Current, Savings, Investment, Joint Accounts, Multi-currency. |
| **Financing & Lending** | Personal, Real Estate, Auto, Corporate, and Microfinance. |
| **Payments & Transfers** | Local (SADAD, IPS), International (SWIFT, Ripple), Instant Payments (Saudi Instant Payment System). |
| **Cards Management** | Debit, Credit, Pre-paid, Integration with Visa/Mastercard. |
| **Digital Services** | Open Banking APIs (per SAMA framework), Mobile App, Web Portal. |
| **Customer Relationship Management (CRM)** | Unified customer data, preferences, transaction history, service. |
| **Anti-Money Laundering (AML)** | Automated system for detecting suspicious activities and reporting to the Financial Intelligence Unit (FIU). |
| **Regulatory Reporting** | Real-time and periodic reports to SAMA (Liquidity ratios, Capital adequacy, International commitments). |
| **Digital Currency Management** | Support for Central Bank Digital Currencies (CBDC) per SAMA directives. |

### 4.2 Technical Scope

- Process 15,000 Transactions Per Second (TPS) with expected growth.
- Support 10 million active accounts (scalable).
- Response time < 150 ms for critical transactions.
- Availability 99.999% (Five 9s).
- Hybrid Infrastructure (On-Premises + Cloud) with horizontal scalability.
- Full Encryption (AES-256, RSA, TLS 1.3).
- Backup and Recovery solution in a geographically isolated environment (per SAMA requirements).
- Secure integration protocols with third-party systems.

### 4.3 Service Scope

- Training for at least 500 employees (practical and theoretical).
- 24/7 Technical Support (with local and international support centers).
- Full Knowledge Transfer to the bank's internal team.
- 5-year warranty on software and services.
- Commitment to monthly security updates and quarterly functional updates.
- Provision of comprehensive technical and operational documentation in both Arabic and English.

---

## 5. SAMA Compliance Requirements

The new system must comply with all SAMA regulations, including but not limited to:

### 5.1 SAMA Cybersecurity Framework (CSF)
- Compliance with the latest version of SAMA CSF.
- Implementation of mandatory cybersecurity controls (regulatory and operational).
- Provision of comprehensive audit logs for cyber activities for at least 5 years.
- Annual Penetration Testing by an external party approved by SAMA.
- Activation of Identity and Access Management (IAM) with Multi-Factor Authentication (MFA).
- Application of "Secure by Design" principles throughout the development lifecycle.

### 5.2 AML/CFT Requirements
- Implementation of an automated system to detect and monitor suspicious transactions per SAMA and FIU requirements.
- Instant reporting to relevant authorities upon detecting suspicious activities.
- Retention of transaction records for a minimum of 10 years.
- Daily updates to sanctions and blacklists (Sanctions Screening).
- Interface for direct electronic AML reporting to SAMA.

### 5.3 Data Protection (PDPL)
- Compliance with the Personal Data Protection Law (PDPL) issued by SAMA/SDAIA.
- Data classification according to sensitivity (Confidential, High, Public).
- Encryption of data at rest and in transit.
- Application of the "Principle of Least Privilege".
- Mechanisms for managing customer consents and withdrawals (Consent Management).
- Guarantee of customer rights to access, modify, or delete their data (per PDPL).

### 5.4 Business Continuity (BCP/DRP)
- Development of a Business Continuity Plan (BCP) and Disaster Recovery Plan (DRP) approved by SAMA.
- Periodic testing of the recovery plan (at least twice annually) with documented results.
- Provision of a recovery environment in a geographically different location within the Kingdom.
- Ensure Recovery Time Objective (RTO) does not exceed 4 hours, and Recovery Point Objective (RPO) does not exceed 15 minutes.
- Retention of encrypted backups in two separate locations.

### 5.5 Regulatory Reporting
- Provision of an automated reporting system according to SAMA requirements (Liquidity, Capital Adequacy, International Commitments).
- Support for SAMA-approved reporting formats (XBRL, XML, PDF).
- Electronic submission of reports via the SAMA portal.
- Retention of report records for at least 5 years.
- Provision of interactive Dashboards for senior management and regulatory bodies.

---

## 6. Detailed Functional Requirements (Summary)

| # | Requirement | Description |
| :-: | :--- | :--- |
| FR-01 | Account Management | Open, modify, close customer accounts (individuals/corporates) with multi-currency support. |
| FR-02 | Transaction Management | Record all financial transactions (deposits, withdrawals, transfers) with automated auditing. |
| FR-03 | Loan Management | Create, modify, settle all types of loans with flexible repayment schedules. |
| FR-04 | Payments | Process local and international payments with integration with national systems (SADAD, IPS, SWIFT). |
| FR-05 | Cards Management | Issue and manage all card types with integration with Visa/Mastercard. |
| FR-06 | Digital Services | Provide open APIs in accordance with the SAMA Open Banking framework. |
| FR-07 | AML/CFT | Automated detection system for suspicious activities with an interface for immediate reporting. |
| FR-08 | Regulatory Reporting | Generate SAMA reports automatically and instantly with required formats. |
| FR-09 | CRM | Integrated CRM system for managing customer data, preferences, and contact history. |
| FR-10 | HR Management | Support employee management (permissions, roles, training). |

---

## 7. Non-Functional Requirements (Summary)

| # | Requirement | Description |
| :-: | :--- | :--- |
| NFR-01 | Performance | Process 15,000 TPS with response time < 150 ms. |
| NFR-02 | Availability | 99.999% availability with a disaster recovery plan. |
| NFR-03 | Scalability | Capable of horizontal scaling to accommodate 10 million future accounts. |
| NFR-04 | Security | Comprehensive encryption, MFA, IDS/IPS, full auditing. |
| NFR-05 | Maintainability | Modular architecture (Microservices) for ease of updates and fixes. |
| NFR-06 | Documentation | Full technical, operational, and training documentation in Arabic and English. |
| NFR-07 | Training | 500 hours of training for employees (theoretical and practical) with completion certificates. |
| NFR-08 | Technical Support | 24/7 support with guaranteed response times (SLA). |
| NFR-09 | Compatibility | Compatibility with SAMA-approved operating systems and databases. |
| NFR-10 | Regulatory Compliance | Ensure compliance with all current and future SAMA requirements. |

---

## 8. Security & Cybersecurity Requirements

- Application of the SAMA CSF with all its controls.
- Periodic Risk Assessment.
- Vulnerability Management System.
- Access Control Policy based on the Principle of Least Privilege.
- Intrusion Detection/Prevention System (IDS/IPS) with 24/7 monitoring.
- Retention of audit logs for 5 years, exportable and analyzable.
- Provision of an isolated environment for security testing (Sandbox).

---

## 9. Integration Requirements with External Systems

- Integration with SADAD (Government Payments).
- Integration with IPS (Local Instant Payments).
- Integration with SWIFT (International Payments).
- Integration with Visa/Mastercard (Cards).
- Integration with SAMA's Central AML System.
- Integration with the SAMA Electronic Reporting Portal.
- Integration with National Identity Systems (Absher, National Unified Access).
- Integration with Data Protection and Privacy Systems.

---

## 10. Project Timeline

| Phase | Duration | Target Date |
| :--- | :--- | :--- |
| RFP Issuance | Day 0 | 1 April 2026 |
| Vendor Questions | 10 Days | Until 11 April 2026 |
| Publish Q&A Responses | 5 Days | Until 16 April 2026 |
| Bid Submission | 30 Days | Until 16 May 2026 |
| Evaluation & Negotiation | 30 Days | Until 15 June 2026 |
| Contract Signing | 10 Days | Until 25 June 2026 |
| Design & Analysis | 60 Days | Until 24 August 2026 |
| Development & Prototyping | 150 Days | Until 21 January 2027 |
| Testing (Unit, Integration, Performance, Security) | 75 Days | Until 6 April 2027 |
| Pilot Launch | 60 Days | Until 5 June 2027 |
| Full Go-Live | 30 Days | Until 5 July 2027 |

---

## 11. Cost Structure & Payment Terms

The financial proposal must detail all costs as follows:

| Cost Item | Description |
| :--- | :--- |
| Base Software Licenses | Permanent or annual license fees for the core system. |
| Additional Licenses | Fees per additional unit (users, transactions, modules). |
| Development & Customization | Costs for developing bank-specific features. |
| Integration with External Systems | Costs for connecting the system to external systems. |
| Training & Knowledge Transfer | Costs for employee training and knowledge transfer. |
| Support & Maintenance | Fees for technical support and warranty for 5 years. |
| Future Upgrades | Fees for mandatory and optional upgrades. |
| Testing Environments | Costs for development and testing environments. |

**Payment Terms:**
- 15% Advance upon signing.
- 25% upon completion of the Design phase.
- 30% upon completion of Development and Testing.
- 20% upon successful Pilot launch.
- 10% upon Full Go-Live and system acceptance.

---

## 12. Evaluation Criteria & Weights

| Criterion | Weight (%) | Details |
| :--- | :---: | :--- |
| **Technical Solution Quality** | 35% | Meeting functional/non-functional requirements, innovation, SAMA compliance. |
| **Total Cost of Ownership (TCO)** | 30% | Analysis of all direct/indirect costs over 5 years. |
| **Vendor Experience & Track Record** | 15% | Similar projects, quality certifications, financial stability, client references. |
| **Implementation Plan & PM** | 10% | Clarity, schedule, team, risk management methodology. |
| **Post-Sales & Support Services** | 10% | Quality of technical support, support centers, response times, maintenance contracts. |

---

## 13. Key Contractual Terms

| Item | Description |
| :--- | :--- |
| Contract Duration | 5 years, renewable for an additional 3 years (based on performance). |
| Performance Guarantee | Bank guarantee enforceable for 10% of the contract value. |
| Delay Penalties | 0.5% of the overdue contract value per week of delay (max 10%). |
| Intellectual Property | Ownership of custom developments remains with the bank; the vendor retains rights to the base software. |
| Confidentiality | Full commitment to maintaining the confidentiality of the bank's and customers' data per PDPL. |
| Arbitration | International Commercial Arbitration in London (LCIA) – English Law. |
| Termination | The bank may terminate the contract without compensation in the event of material breach (performance below 90% for 30 consecutive days). |
| Insurance | The vendor must provide professional indemnity and civil liability insurance. |

---

## 14. Submission Requirements

Vendors must submit:

1. **Technical Proposal:** Detailed description of the technical solution, architecture, security requirements, regulatory compliance, implementation plan, and risk management.
2. **Financial Proposal:** Full cost breakdown (in USD or SAR) with a clear TCO analysis.
3. **Case Studies:** At least 3 similar projects (preferably in the banking sector or the Arab region).
4. **Quality Certifications:** ISO 27001, ISO 22301, PCI-DSS, CMMI, etc.
5. **Team CVs.**
6. **Knowledge Transfer & Training Plan.**
7. **Draft Contract Proposal.**

---

## 15. Frequently Asked Questions & Potential Risks

| Question | Answer |
| :--- | :--- |
| Can public cloud solutions be used? | Yes, but the cloud must be approved by SAMA and within the Kingdom (or with a local backup environment). |
| Will data be migrated from the existing system? | Yes, all customer and transaction data must be securely migrated from the legacy system. |
| What is the expected number of end-users? | 500 internal users (employees) and 5 million customers (via digital channels). |
| Is there a technology preference? | We prefer Java, .NET, or Python, but we accept other proposals if supported by local skills. |

**Potential Risks:**
- **Technical:** Integration issues, substandard performance, security vulnerabilities.
- **Administrative:** Changing requirements, schedule delays, staff turnover.
- **Financial:** Cost overruns, currency fluctuations, hidden fees.
- **Regulatory:** Changes to SAMA regulations during the implementation period.

---

## 16. List of Appendices

- Appendix A: Full list of SAMA CSF requirements.
- Appendix B: List of required integration interfaces.
- Appendix C: Sample SAMA New System License Application.
- Appendix D: Bank's Personal Data Protection Policy (PDPL).
- Appendix E: SAMA Periodic Reporting Requirements.

---

*© 2026 AlVirtu Bank – All Rights Reserved*