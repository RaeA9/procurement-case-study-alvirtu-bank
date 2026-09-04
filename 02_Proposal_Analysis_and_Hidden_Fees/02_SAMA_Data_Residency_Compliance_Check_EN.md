# SAMA Data Residency Compliance Check – AlVirtu Bank

**Date of Preparation:** July 10, 2026  
**Purpose:** Strict audit of each vendor's commitment to banning data storage outside KSA for ALL environments.

---

## 1. The Decisive SAMA Rule (CCF Article 6)

> *"Banks must store all data (including transaction logs, backups, and audit logs) within the borders of the Kingdom of Saudi Arabia, including development and testing environments."*

**Penalty:** Violations can lead to fines of up to 5% of the bank's annual revenue, or license suspension.

---

## 2. Vendor Compliance Audit

| Environment | Vendor (A) | Vendor (B) | Vendor (C) |
| :--- | :---: | :---: | :---: |
| **Production Environment** | 🇸🇦 KSA | 🇸🇦 KSA | 🇸🇦 KSA |
| **UAT (User Acceptance Testing)** | 🇮🇪 Ireland | 🇸🇦 KSA | 🇩🇪 Germany |
| **Development (Dev) Environment** | 🇮🇪 Ireland | 🇸🇦 KSA | 🇩🇪 Germany |
| **Disaster Recovery (DR)** | 🇸🇦 KSA | 🇸🇦 KSA | 🇩🇪 Germany |
| **Backups** | 🇮🇪 Ireland | 🇸🇦 KSA | 🇩🇪 Germany |
| **Final Compliance Decision** | **❌ Non-Compliant** | **✅ Compliant** | **❌ Non-Compliant** |

---

## 3. Consequences of the Knock-out Criterion

- **Vendor (A):** Immediately disqualified due to storing Dev/Test environments and backups in Ireland.
- **Vendor (C):** Immediately disqualified due to storing ALL environments outside KSA (Germany).
- **Vendor (B):** The ONLY vendor to satisfy the condition, thus **considered the sole qualified candidate for the next stage (Negotiations).**

> **Final Ruling by the Evaluation Committee:**  
> Based on the explicit Knock-out Criterion in the RFP, Vendors (A) and (C) are permanently excluded. Vendor (B) is approved as the sole candidate for final negotiations.