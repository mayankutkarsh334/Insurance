# Health Insurance Category

## What we are selecting
An **individual indemnity health insurance policy** (also called mediclaim / hospitalisation cover) that reimburses or cashless-settles hospitalisation and related medical costs, renewable for life.

Out of scope for now (can be separate studies later):
- Family floater / senior-citizen plans
- Super top-up / top-up plans (bought *on top of* a base policy)
- Critical-illness fixed-benefit and personal-accident plans
- Corporate/group cover

## Universe (India retail health insurers, as of 2026)
Roughly **25 insurers** offer retail health cover, in three buckets:

| Bucket | Examples |
|--------|----------|
| Standalone Health Insurers (SAHI) | Star Health, Care Health, Niva Bupa, ManipalCigna, Aditya Birla Health |
| Private general insurers | HDFC ERGO, ICICI Lombard, Bajaj Allianz, Tata AIG, Reliance General, SBI General |
| Public general insurers | New India Assurance, National, Oriental, United India |

Most insurers sell **2–4 retail health products**, so the true universe is **50–70 plans**. Screening cuts this to **5 finalists**.

## Data Sources (there is no single Tickertape-equivalent CSV)
| Source | What it gives | Reliability |
|--------|---------------|-------------|
| **Policy wording** (PDF on insurer site / IRDAI) | The legally binding truth — benefits, exclusions, waiting periods, sub-limits, co-pay | **Authoritative.** Always beats brochure/ads |
| **Brochure / prospectus** | Marketing summary of features | Directional; verify against wording |
| **IRDAI Annual Report** | Incurred Claim Ratio (ICR), solvency ratio, grievance data by insurer | Authoritative, but **insurer-level not plan-level** |
| **IRDAI Handbook / Bima Bharosa** | Complaint volumes, grievance disposal | Authoritative |
| **PolicyBazaar / Ditto / insurer quote engine** | Live premium by age, sum insured, network size | Reliable for premium; features are summarised — verify wording |
| **Insurer financials / rating (CRISIL etc.)** | Financial strength, solvency | Reliable |

## Key reliability note
- **Claim Settlement Ratio (CSR)** headline numbers are easy to game (a rejected small claim and a paid small claim count equally). Prefer **Incurred Claim Ratio (ICR)** + **complaint ratio** + **claim repudiation rate** as the real "will they pay" signal.
- A benefit only counts if it is written in the **policy wording**. If it's in the ad but not the wording, it does not exist.

## Finalist study progress
Deep study runs one module at a time; final score is the weighted sum across 6 modules (see `study_plan.md` for weights). Benchmark-first order.

| # | Finalist | Folder | Status | Weighted /5 | Override veto |
|---|----------|--------|:------:|:-----------:|:-------------:|
| 1 | **HDFC ERGO Optima Secure+** *(benchmark)* | `policies/hdfc_optima_secure/` | ✅ Complete | **4.65** | none |
| 3 | **Aditya Birla Activ One MAX** | `policies/aditya_birla_activ_max/` | ✅ Complete | **4.60** | none |
| — | Aditya Birla Activ One *NXT* *(cheaper rung — reference only)* | `policies/aditya_birla_activ_one/` | ✅ Complete | 4.35 | none |
| 2 | Bajaj Allianz Health Guard *(claims leader)* | `policies/bajaj_health_guard/` | ⬜ Not started | — | — |
| 4 | SBI General Super Health *(network/waiting)* | `policies/sbi_super_health/` | ⬜ Not started | — | — |
| 5 | Care Health Care Supreme *(low-ICR interrogation)* | `policies/care_supreme/` | ⬜ Not started | — | — |

**Module scorecard (completed finalists)**

| Plan | M1 Cov (25%) | M2 Excl (20%) | M3 Claims (25%) | M4 Cost (15%) | M5 Insurer (10%) | M6 Fine (5%) | **Total** |
|------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| HDFC Optima Secure+ | 5 | 4 | 5 | 4 | 5 | 5 | **4.65** |
| Aditya Birla Activ One MAX | 5 | 5 | 4 | 5 | 4 | 4 | **4.60** |

> **MAX vs benchmark:** Activ One MAX ties HDFC on coverage (5) and beats it on exclusions (5 vs 4) and cost (5 vs 4 — HealthReturns earn-back + 0% GST); it trails only on the two insurer-level modules — claims (ICR 68% vs 85%) and insurer strength (younger, still underwriting-loss-making). Net: a near-tie, ₹0.05 apart.

## Files
- `screening/methodology.md` — which variables matter for an individual buyer and why
- `screening/stage1_hard_filters.md` — deal-breaker filters (universe → shortlist)
- `screening/stage2_shortlist.md` — comparative scoring (shortlist → 5 finalists)
- `study_plan.md` — the 6-module deep-study framework
- `policies/` — one folder per finalist (each with its own README + module1–6 + resources)
