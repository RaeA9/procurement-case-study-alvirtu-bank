# Legacy System Decommissioning Plan – AlVirtu Bank

**Date of Preparation:** July 10, 2026  
**Reference:** SAMA Record Retention Policy & Cybersecurity Framework

---

## 1. Primary Objective

To permanently, safely, legally, and audibly decommission the legacy Core Banking System, ensuring:
- No required regulatory data is lost.
- All sensitive data is irreversibly destroyed.
- The process is thoroughly documented to prove compliance with SAMA and PDPL regulations.

---

## 2. Decommissioning Schedule

| Phase | Duration | Action |
| :--- | :--- | :--- |
| **Pre-Decommission Phase** | 30 Days | Identify and prepare a full list of data required for retention (for 10 years) per SAMA requirements, and transfer it to an approved archiving system within KSA. |
| **Cut-off (Shutdown)** | 1 Day | Power down the legacy system, and disconnect all network, database, and external interface connections. |
| **Secure Data Wiping** | 3 Days | Delete all remaining data from physical hard drives using secure erasure standards (e.g., DoD 5220.22-M). |
| **Documentation Phase** | 7 Days | Compile a final comprehensive report detailing the entire decommissioning process, with a list of all wiped drives and timestamps. |

---

## 3. Secure Data Wiping Standards

Data must be destroyed from all hard drives (HDD/SSD) using the following standards:

- **Primary Standard (HDD):** DoD 5220.22-M (7 passes of random data overwriting).
- **Alternative Standard (SSD):** Use the manufacturer's certified ATA Secure Erase command, followed by an additional pass of random data.

**Mandatory Witness Requirement:** The wiping process must be witnessed by a representative from (Cybersecurity) and a representative from (Compliance). This must be formally documented in a signed witness log.

---

## 4. Record Retention (Archiving)

- **What to Keep:** Financial transaction records, client account data, and regulatory reports for the last ten (10) years.
- **Retention Format:** Data must be stored on media located within KSA, in an Open Format (e.g., CSV, XML) to ensure readability in the future.
- **Retention Period:** 10 years from the date of decommissioning (per SAMA requirements).

---

## 5. Final Decommissioning Compliance Report

A final formal report must be prepared, including:
- A complete list of all servers, disks, and media that were decommissioned.
- Date and time of each secure wiping operation.
- Names, titles, and signatures of the witnessing parties (Cybersecurity and Compliance).
- A Certificate of Destruction confirming all sensitive data was purged.
- A documented reference link to the secure physical location of the archived data.

**This report must be retained in the Bank's internal records and be readily available for SAMA inspection at any time.**

---

*© 2026 AlVirtu Bank – Cybersecurity & Compliance Department*