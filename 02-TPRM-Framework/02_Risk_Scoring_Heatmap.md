# Third-Party Risk Scoring Heatmap

**Document ID:** TPRM-RSK-002  
**Institution:** AlVirtu Bank (simulated)  
**Companion:** TPRM-DDQ-001  
**Date:** 1 February 2026

---

## 1. Method

Score each factor **1 (low) to 5 (high)** for inherent **likelihood** and **impact**.  
Inherent risk = likelihood × impact (max 25).  
Residual risk uses the same grid after planned controls.

| Band | Score | Meaning | Award rule |
| ---: | ---: | :--- | :--- |
| Low | 1–6 | Accept with standard clauses | Eligible |
| Medium | 7–12 | Accept with named treatments | Eligible if owner signs |
| High | 13–19 | CRO + Compliance approval | Eligible only with treatments before signature |
| Extreme | 20–25 | Outside appetite | No award unless the factor is removed |

**Override:** a fail on DDQ Section B is Extreme on Data residency and **stops scoring**.

---

## 2. Scoring factors (CBS category)

| ID | Factor | What “5 / 5” looks like |
| :--- | :--- | :--- |
| F1 | Data residency | Any environment outside KSA |
| F2 | Concentration | Incumbent already >50% of the category ledger |
| F3 | Cyber control gap | No current SOC 2 or ISO 27001, or open critical findings |
| F4 | Subcontractor opacity | SI or cloud not named, or no flow-down of residency |
| F5 | Continuity | No tested DR, or RTO/RPO worse than 4h / 15m |
| F6 | Financial standing | Weak audits, going-concern note, or thin PI cover |
| F7 | Regulatory fitness | History of SAMA / PDPL / NCA findings on similar work |
| F8 | Exit difficulty | No escrow, no open-format extract, staff lock-in |

---

## 3. Heat map

Impact →

| Likelihood ↓ | 1 Slight | 2 Minor | 3 Moderate | 4 Major | 5 Severe |
| :--- | :---: | :---: | :---: | :---: | :---: |
| 5 Almost certain | 5 | 10 | 15 | 20 | 25 |
| 4 Likely | 4 | 8 | 12 | 16 | 20 |
| 3 Possible | 3 | 6 | 9 | 12 | 15 |
| 2 Unlikely | 2 | 4 | 6 | 8 | 10 |
| 1 Rare | 1 | 2 | 3 | 4 | 5 |

Colour rule for presentation: 1–6 green · 7–12 amber · 13–19 red · 20–25 black.

---

## 4. Worked example — three bidders (inherent)

| Factor | Vendor A | Vendor B | Vendor C |
| :--- | ---: | ---: | ---: |
| F1 Data residency | 5×5 = **25** Fail | 2×5 = 10 | 5×5 = **25** Fail |
| F2 Concentration | 4×4 = 16 | 2×3 = 6 | 2×3 = 6 |
| F3 Cyber | 2×4 = 8 | 2×4 = 8 | 3×4 = 12 |
| F4 Subcontractors | 3×4 = 12 | 2×4 = 8 | 4×5 = 20 |
| F5 Continuity | 2×4 = 8 | 2×4 = 8 | 3×4 = 12 |
| F6 Financial | 2×3 = 6 | 2×3 = 6 | 3×3 = 9 |
| F7 Regulatory | 3×5 = 15 | 2×5 = 10 | 4×5 = 20 |
| F8 Exit | 4×4 = 16 | 2×4 = 8 | 4×4 = 16 |
| **Highest unfixed cell** | **25 — out** | **10 — medium** | **25 — out** |

Vendor A and Vendor C are not scored for award. Vendor B remains on the medium band pending contract treatments in TPRM-CLS-003.

---

## 5. Residual target for the awarded vendor

| Factor | Inherent | Treatment | Residual target |
| :--- | ---: | :--- | ---: |
| F1 | 10 | Contractual residency + CST-licensed host + quarterly attestation | 5 |
| F2 | 6 | BATNA file kept live; no single-source clause | 6 |
| F4 | 8 | Named SI, joint and several liability, flow-down | 4 |
| F8 | 8 | Escrow + 30-day open-format extract + 90-day exit support | 4 |

CRO sign-off is required before the letter of award if any residual cell stays High.

---

*AlVirtu Bank — TPRM. Simulated scoring. Not a live vendor rating.*
