# Cybersecurity & Cloud Standards – Mandatory Version (AlVirtu Bank)

**Prepared by:** CISO Office & Compliance Department  
**Date:** July 10, 2026  
**Status:** Mandatory for all vendors (attached as a core RFP appendix)

---

## 1. Fundamental Guiding Principle

"All standards listed below are derived from the binding regulations issued by SAMA and SDAIA. Any deviation constitutes a Material Breach."

---

## 2. Adopted Regulatory Frameworks (Explicitly Referenced)

A. SAMA Cyber Security Framework (CSF) – with all mandatory controls.
B. SAMA Cloud Computing Framework (CCF) – requiring all primary and backup data centers to be within KSA.
C. SDAIA Personal Data Protection Law (PDPL) – guaranteeing customer rights to access, correct, and delete data.

---

## 3. Data Residency & Infrastructure Requirements (All Environments)

A. Strictly prohibited: storing, processing, or routing any customer or transaction data through external servers, even temporarily.
B. This prohibition applies without exception to ALL environments: Production, UAT, Disaster Recovery, Development, Testing, and all their simulations and backups.
C. All these environments must be hosted exclusively within data centers located in the Kingdom of Saudi Arabia, via locally licensed cloud providers.

---

## 4. Encryption & Access Control (IAM)

A. Data at Rest: AES-256 minimum.
B. Data in Transit: TLS 1.3 or equivalent.
C. MFA activation for all administrative and remote access users.
D. Strict application of the "Principle of Least Privilege" across all system levels.

---

## 5. Remote Access & Offshoring Controls

A. If vendor engineers outside the KSA require system access, it must be strictly via a Secure VDI/Jump Box under the full control of the bank.
B. Video recording of the entire foreign engineer session must be activated.
C. Prior written approval from the Bank's CISO is required for each session, specifying the scope and duration.
D. All remote access attempts must be logged in Audits viewable to regulators at any time.

---

## 6. Penetration Testing & Vulnerability Management (Advanced Level)

A. **Not** limited to periodic Penetration Test reports (every 6 months).
B. **Replaced with Continuous SAST/DAST:** Vendor must provide monthly reports on Static and Dynamic source code analysis throughout the development period.
C. **Immediate Disclosure:** If a Critical or High vulnerability is discovered during development or pre-launch, the vendor must notify the CISO within 24 hours.
D. **Go-Live Block:** Launch is prohibited until all Critical and High vulnerabilities are closed, with a closure report signed by an independent auditor selected by the bank.

---

## 7. Integration with National Systems (Non-Negotiable Scope)

Vendor must guarantee integration with the following systems without any additional fees:
A. National Government Payments System (SADAD).
B. Local Instant Payments and Transfers System (SARIE).
C. International Correspondent Banking Network (SWIFT).
D. Unified National Identity Authentication System (National Access).

---

## 8. Minimum Certifications Required from Vendor

A. Valid ISO 27001 certification.
B. Recent (within 6 months) SOC 2 Type II report for the local data center.
C. Compliance certificate for SAMA Cybersecurity controls issued by an approved external audit firm.