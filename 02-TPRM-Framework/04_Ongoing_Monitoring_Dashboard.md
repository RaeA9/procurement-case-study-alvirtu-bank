# Ongoing Monitoring Dashboard

**Document ID:** TPRM-MON-004  
**Institution:** AlVirtu Bank (simulated)  
**Applies to:** Awarded CBS supplier and named SI  
**Date:** 1 February 2026

---

## 1. Cadence

| Rhythm | Owner | Output |
| :--- | :--- | :--- |
| Monthly | Vendor manager + IT operations | SLA pack, incident log, invoice vs milestone |
| Quarterly | TPRM + Compliance | Residency attestation, subcontractor list, leakage vs ledger |
| Each year | TPRM + CRO | Full reassessment against TPRM-RSK-002 |
| Trigger | Any owner | Incident, regulator letter, change of control, new subcontractor |

---

## 2. Monthly watchlist (traffic light)

| Indicator | Green | Amber | Red | Source |
| :--- | :--- | :--- | :--- |
| Production availability | ≥ 99.95% | 99.50–99.94% | < 99.50% or credit cap hit | SLA report |
| Critical incident response | ≤ 2 hours | 2–4 hours | > 4 hours | Service desk |
| Open critical vulnerabilities | 0 older than 30 days | 1–2 in SLA | Any past SLA | SAST/DAST pack |
| Milestone vs cash | Paid only on accepted output | One invoice in dispute | Advance consumed without accepted design | Finance |
| Named KSA delivery seats | Plan met | One vacancy > 30 days | Key lead gone, no successor | HR / SI |
| New data path | None | Proposed, not live | Live path not on the residency list | Attestation |

Red on any row forces a TPRM incident note within two business days.

---

## 3. Annual reassessment pack

1. Updated DDQ Sections B–E (delta only if the corporate file is unchanged).
2. Fresh heat map (TPRM-RSK-002) with residual scores.
3. Insurance certificates and bond currency.
4. DR test results against RTO 4 hours / RPO 15 minutes.
5. Local-content report for key technical roles.
6. Escrow verification (last deposit date).
7. Recommendation: retain / remediate / exit.

CRO signs the retain-or-exit line. A residual Extreme cell on residency is an exit trigger, not a waiver item.

---

## 4. Dashboard snapshot (template)

| Vendor | Residual peak | SLA YTD | Bond live | Last DR test | Next annual review | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Vendor B (awarded) | Medium → target Low | _insert_ | Yes / No | _insert_ | _insert_ | Watch |
| Named SI | _insert_ | _insert_ | Flow-down Yes / No | _insert_ | _insert_ | Watch |

Replace blanks at first month-end after signature.

---

## 5. Escalation

| Condition | First action | If not closed |
| :--- | :--- | :--- |
| Amber two months running | Vendor manager letter | Quarterly board |
| Any Red | CRO + Compliance same week | Cure plan or step-in review |
| Residency doubt | Suspend new data flows | Termination path under clause 1 |
| Change of control | Refresh Sections A and D in 15 days | Treat as new third party |

---

*AlVirtu Bank — TPRM. Simulated operating rhythm. Not a live control dashboard.*
