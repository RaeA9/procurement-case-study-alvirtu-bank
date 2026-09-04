# Third-Party Due Diligence Questionnaire

**Document ID:** TPRM-DDQ-001  
**Institution:** AlVirtu Bank (simulated)  
**Scope:** Core Banking System — pre-qualification only  
**Issue date:** 1 February 2026  
**Response deadline:** 15 calendar days from issue  
**Classification:** Educational case study — not a live RFP pack

---

## Instructions to the respondent

1. Answer every question. Use “Not applicable” only with a one-line reason.
2. Attach evidence as numbered annexes (A1, A2…). Do not embed unreadable screenshots.
3. One authorised officer must sign Section F. Marketing language is not a response.
4. **Section B is a knock-out.** An incomplete, qualified, or off-kingdom answer disqualifies the bid. No score is awarded.
5. Language of response: English. Centre addresses and licence numbers may remain in Arabic.

---

## Section A — Corporate standing and financial stability

| # | Question | Response | Annex |
| :--- | :--- | :--- | :--- |
| A1 | Legal name, commercial registration, country of incorporation, and KSA registration if any. | | |
| A2 | Audited financial statements for the last three fiscal years, plus going-concern language if present. | | |
| A3 | Current credit rating or, if unrated, bank reference and latest management accounts. | | |
| A4 | Material litigation, regulatory fines, or enforcement in the last five years. If none, state “None.” | | |
| A5 | Insurance: professional indemnity, cyber, and public liability — limits and expiry. | | |

**Minimum bar:** three years of audits; PI cover not below USD 10 million for this category.

---

## Section B — Data residency and sovereignty (SAMA CCF) — knock-out

| # | Question | Response | Annex |
| :--- | :--- | :--- | :--- |
| B1 | Confirm that **all** data — Production, Development, Test/UAT, backup, logs, and DR — will be processed and stored **only** inside the Kingdom of Saudi Arabia. Answer Yes / No. No partial environments. | | |
| B2 | Physical address of every data centre and DR site that will hold Bank data. | | |
| B3 | Name of the cloud or hosting provider and a copy of its CST licence (or equivalent KSA authorisation). | | |
| B4 | Confirm that support staff outside KSA will not copy Bank data to laptops, tickets, or overseas tools. Describe the control. | | |
| B5 | Name every subcontractor that will touch Bank data. Confirm each one meets B1–B4. | | |

**Scoring rule:** B1 = No, blank, or “except Dev/Test” → **disqualified**. Do not complete Sections C–E for award.

---

## Section C — Cybersecurity and compliance (SAMA CSF / NCA ECC)

| # | Question | Response | Annex |
| :--- | :--- | :--- | :--- |
| C1 | Valid ISO/IEC 27001 certificate. Scope must cover the service offered. | | |
| C2 | SOC 2 Type II report dated within the last 12 months (six months preferred). List exceptions. | | |
| C3 | Vulnerability programme: SAST and DAST on the CBS code path; last two report dates; time to close critical findings. | | |
| C4 | Independent penetration test in the last 12 months. Provide the executive letter, not the full exploit pack. | | |
| C5 | Alignment statement to SAMA CSF and NCA Essential Cybersecurity Controls for this service. | | |
| C6 | Personal-data role under PDPL (processor / joint controller) and name of the DPO contact. | | |

---

## Section D — Subcontractors and supply chain

| # | Question | Response | Annex |
| :--- | :--- | :--- | :--- |
| D1 | Full list of subcontractors: system integrator, cloud, hardware, offshore development, SOC. | | |
| D2 | Written confirmation that every subcontractor is bound to Section B. | | |
| D3 | Oversight method: audit rights, SLA flow-down, step-in, and last audit date of the SI. | | |
| D4 | Confirm joint and several liability with the SI for delivery, delay, and data incidents. | | |

---

## Section E — Continuity, people, and local content

| # | Question | Response | Annex |
| :--- | :--- | :--- | :--- |
| E1 | Disaster-recovery plan. Target **RTO ≤ 4 hours**, **RPO ≤ 15 minutes**, DR site inside KSA. | | |
| E2 | Last DR test date and result (pass / fail / issues). | | |
| E3 | Twelve-month turnover of staff assigned to core-banking delivery. | | |
| E4 | Named delivery leads who will sit in Riyadh at go-live. CVs attached. | | |
| E5 | Share of Saudi nationals in key technical delivery roles and the Nitaqat / local-content plan for this contract. Target discussed with the Bank: **not below 80%** in those roles. | | |

---

## Section F — Declaration

I confirm that the answers and annexes are complete and current. I understand that a false or incomplete Section B is grounds for immediate exclusion and, after award, material breach.

| Field | Entry |
| :--- | :--- |
| Authorised signatory | |
| Title | |
| Date | |
| Company stamp | |

---

## Bank use only — completeness gate

| Gate | Pass / Fail | Reviewer | Date |
| :--- | :--- | :--- | :--- |
| Section B fully answered and on-kingdom | | | |
| Audits and insurance attached | | | |
| Subcontractor list closed | | | |
| Proceed to risk heatmap (TPRM-RSK-002) | | | |

*AlVirtu Bank — TPRM. Simulated pack. Not issued to live vendors.*
