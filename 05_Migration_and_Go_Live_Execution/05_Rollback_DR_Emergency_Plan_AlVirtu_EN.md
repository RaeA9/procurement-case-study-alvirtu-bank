# Rollback & Disaster Recovery Emergency Plan – AlVirtu Bank

**Date of Preparation:** July 10, 2026  
**Document Status:** Official (Approved by the Senior Risk Committee and the CEO)  
**Reference:** SAMA Business Continuity Requirements

---

## 1. The Core Emergency Principle

> **"A safe retreat is always better than dangerous persistence."**

In the event of a critical failure during migration (e.g., balance discrepancies, system outage, or critical security vulnerability), the emergency plan is immediately activated to restore the legacy system to service, ensuring no data is lost during the transition.

---

## 2. Rollback Activation Triggers

The Rollback plan is activated immediately in any of the following cases:

1. **Balance Discrepancies:** A difference in customer or internal account balances exceeding (0.01%) appears 24 hours after the launch.
2. **Critical System Outage:** The new system experiences a complete outage for more than 30 consecutive minutes without resolution.
3. **Critical Security Vulnerability:** Discovery of a Critical vulnerability that allows unauthorized access to customer data.
4. **Integration Failure:** The new system fails to integrate with one of the national systems (e.g., SADAD or SARIE) for more than 2 hours.

---

## 3. Emergency Response Team

| Role | Responsible Party |
| :--- | :--- |
| **Overall Commander** | CEO – Holds the final authority to activate the Rollback. |
| **Technical Lead** | CIO – Responsible for the technical execution of the Rollback. |
| **Operational Lead** | COO – Responsible for re-opening branches and digital channels on the legacy system. |
| **Legal Lead** | General Counsel – Responsible for documenting the decision and notifying SAMA (if required). |

---

## 4. Rollback Procedure (Step-by-Step)

| Step | Action | Time Target |
| :--- | :--- | :---: |
| 1 | The CEO declares a state of emergency. | 5 Minutes |
| 2 | Halt all input and transaction processing on the new system. | 10 Minutes |
| 3 | Restore the legacy system from the last known good backup (manual or automated migration of transactions that occurred during partial operation will be handled as necessary). | 60 Minutes |
| 4 | Verify the integrity and matching of all client balances in the legacy system against external records (e.g., Central Bank statements). | 60 Minutes |
| 5 | Gradually re-open branches and digital channels on the legacy system with a customer notification campaign. | 30 Minutes |
| 6 | Form an Investigation Committee to determine the root cause of the failure and establish a corrective action plan before any future migration attempt. | 7 Days |

---

## 5. Disaster Recovery Plan (DRP)

- **Recovery Site:** A backup data center located within the Kingdom (in a different city, e.g., Dammam or Jeddah).
- **Recovery Time Objective (RTO):** Less than 4 hours from the moment the disaster is declared.
- **Recovery Point Objective (RPO):** Less than 15 minutes (real-time backups).
- **Plan Testing:** The DRP must be tested bi-annually, with SAMA observers present upon request.

---

## 6. CEO Sign-off Commitment

> **"I, the CEO of AlVirtu Bank, hereby confirm that I have reviewed this Rollback and Emergency Plan in full. I authorize its activation at any time under the conditions stated above. I bear full responsibility for the Rollback decision should the need arise."**

**Signature:** _________________  
**Date:** _________________

---

*© 2026 AlVirtu Bank – Senior Risk Committee*