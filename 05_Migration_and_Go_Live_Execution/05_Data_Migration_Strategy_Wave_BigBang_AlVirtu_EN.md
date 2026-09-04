# Data Migration & Go-Live Strategy – AlVirtu Bank Core Banking Replacement

**Date of Preparation:** July 10, 2026  
**Version:** 1.0 (Approved by the Senior Steering Committee)  
**Document Status:** Confidential (Internal Execution Plan)

---

## 1. The Guiding Principle (Golden Rule)

> **"One system working correctly is better than two systems working incorrectly."**

Based on this principle, the **Parallel Run (2-month) plan has been CANCELLED**, because it leads to:
- Double-entry accounting chaos, creating reconciliation nightmares.
- Severe pressure on branch staff and call centers.
- Conflicting customer balances between the old and new systems.

**Approved Alternative:** A hybrid strategy combining (Wave Migration) and (Big Bang) with intensive (Dry Runs).

---

## 2. The Approved Migration Strategy (Wave + Big Bang Hybrid)

| Phase | Scope | Duration | Action |
| :--- | :--- | :--- | :--- |
| **Pre-Migration (Preparation)** | All Systems | 60 Days | Data cleansing, full preparation of the new production environment, and execution of 3 complete (Dry Runs) of the entire transfer process. |
| **Wave 1** | Retail Current & Savings Accounts (~30% of customers) | Long Weekend (4 days) | Data transfer during the long weekend (Thursday to Sunday). Partial branch closures during the transfer period. |
| **Wave 2** | Credit Cards & Personal Loans (Additional 30%) | Long Weekend (4 days) | Repeat transfer process with a dedicated (War Room) support team to monitor any discrepancies. |
| **Wave 3** | Corporate & Treasury Sector (Additional 30%) | Long Weekend (4 days) | The most complex wave; requires prior coordination with key corporate clients and treasury partners. |
| **Full Go-Live (Big Bang)** | Remaining accounts and services (10%) | Long Weekend (4 days) | Transfer the final segment, permanently decommission the legacy system, and fully activate the new system. |

---

## 3. Dry Runs – The Key to Success

Before each migration wave, a complete **Dry Run** will be executed in an isolated environment, including:
- Transferring a sample of data (Sample Data).
- Running the new system on this sample for 48 hours.
- Performing Data Integrity Checks and comparing them with the legacy system.
- Documenting any errors and correcting them before the actual transfer.

**Critical Condition:** No migration wave can proceed to the next stage without achieving a **100% success rate** on the Dry Run and having the results approved by the Technical Committee.

---

## 4. Communication & Change Management Plan

- **Customer Notification:** SMS and email notifications will be sent 14 days prior to each wave, explaining the expected downtime (if any) and the nature of the update.
- **Branch Training:** Branch staff will be progressively trained on the new system before each wave, with a Quick Reference Guide provided at every branch.
- **War Room (Command Center):** A central command center will operate 24/7 throughout the entire migration period, comprising representatives from (Vendor, SI Partner, Bank IT, and Operations) to resolve any immediate issues.

---

## 5. Migration Success KPIs

| KPI | Target |
| :--- | :--- |
| **Balance Matching Rate** (between old and new systems) | 100% (within 48 hours of launch). |
| **System Recovery Time (RTO)** | Less than 4 hours. |
| **Data Loss Point (RPO)** | Less than 15 minutes. |
| **Customer Complaint Rate** | Less than 0.5% of migrated customers. |

---

*© 2026 AlVirtu Bank – Digital Transformation Management*