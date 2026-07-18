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

## Study progress — complete
Deep study runs one module at a time; final score is the weighted sum across 6 modules (see `study_plan.md` for weights). Benchmark-first order. **7 plans studied: the 5 original finalists plus ACKO (deep-studied) and Royal Sundaram (screened).**

| # | Plan | Folder | Status | Weighted /5 | Override veto |
|---|----------|--------|:------:|:-----------:|:-------------:|
| 2 | **HDFC ERGO Optima Secure+** *(benchmark)* | `policies/hdfc_optima_secure/` | ✅ Complete · 🔄 re-tested | **4.55** ⬇️ | none |
| 1 | **Aditya Birla Activ One MAX** | `policies/aditya_birla_activ_max/` | ✅ Complete · 🔄 re-tested | **4.60** | none |
| — | Aditya Birla Activ One *NXT* *(cheaper rung — reference only)* | `policies/aditya_birla_activ_one/` | ✅ Complete | 4.35 | none |
| 3 | **Bajaj Health Guard (Platinum)** *(claims leader ⚠️)* | `policies/bajaj_health_guard/` | ✅ Complete | **4.05** | none |
| 4 | **SBI General Super Health** *(network/waiting)* | `policies/sbi_super_health/` | ✅ Complete | **3.98** | none |
| 5 | **Care Health Care Supreme** *(low-ICR interrogation)* | `policies/care_supreme/` | ✅ Complete | **3.50** | none |
| 6 | **ACKO Platinum Health** *(added post-screening)* | `policies/acko_platinum_health/` | ✅ Complete | **3.325** | none |
| — | Royal Sundaram **Lifeline** *(screened only)* | — | ✅ Screened | ~21/30 at Stage 2 | — |

**Module scorecard — all deep-studied plans**

| Plan | M1 Cov (25%) | M2 Excl (20%) | M3 Claims (25%) | M4 Cost (15%) | M5 Insurer (10%) | M6 Fine (5%) | **Total** |
|------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| HDFC Optima Secure+ 🔄 | 5 | 4 | 5 | 4 | **4** ⬇️ | 5 | **4.55** ⬇️ |
| Aditya Birla Activ One MAX 🔄 | 5 | 5 | 4 | 5 | 4 | 4 | **4.60** |
| Bajaj Health Guard (Platinum) | 3.5 | 4 | 5 ⚠️ | 3.5 | 4 | 4 | **4.05** |
| SBI General Super Health (Platinum) | 4 | 4.5 | 3.5 | 4 | 4 | 4 | **3.98** |
| Care Health Care Supreme | 4 | 4 | 3 | 3.5 | 2.5 | 3.5 | **3.50** |
| ACKO Platinum Health | 3.5 | 3 | 3.5 | 3.5 | 3 | 3 | **3.325** |

> 🔄 **HDFC re-tested (Jan 2026) — M5 cut 5→4, total 4.65 → 4.55, now BELOW Aditya Birla MAX (4.60).** Studied first as the benchmark, HDFC had never been tested against the ~30 dimensions discovered later. **Coverage, claims and fine print held** — it passes the newer checks that damaged Care and ACKO (limits fixed in the wording not the schedule; no tobacco exclusion; no arbitration clause; no subjective non-renewal grounds; express condonation of late claim intimation). **M5 fell on solvency dipping to 1.56× in Jun-2024 — within 0.06 of the floor — restored partly via ₹325 cr sub-debt, with a combined ratio of ~123% and worsening.** Three factual corrections were also made: **GST is 0% not 18% (M4)**, **mental-illness parity is insurer-stated not wording-backed (M2)**, and **a voluntary room-cap modifier does exist (M1)**.
>
> ⚠️ **Bajaj's M3 = 5/5 rests on stale data.** It was shortlisted as the *"claims-reliability leader (ICR 87%)"*; **FY24-25 IRDAI puts Bajaj's health ICR at 74.59%** while SBI's rose to **87.86%** — the two have inverted. **Re-pull Bajaj M3 before the decision tree.**
>
> **MAX vs benchmark:** ties HDFC on coverage (5), beats it on exclusions (5 vs 4) and cost (5 vs 4 — HealthReturns earn-back + 0% GST); trails only on claims record and insurer age. A near-tie, 0.05 apart.
>
> **Bajaj vs benchmark:** the *certainty-of-payout* pick — but see the stale-ICR flag. Trails on coverage (3.5 — no consumables buy-back, 90-day post-hosp, no domiciliary) and cost (3.5 — a **contractual 8%/yr base-rate escalation**).
>
> **SBI vs benchmark:** the **high-floored all-rounder — no module below 3.5, none above 4.5**. Beats the benchmark on **exclusions (4.5 vs 4** — PED 24mo, specific-disease 12mo, no hidden third tier). Held to 3.98 by **claims (3.5)** — not poor payment (ICR 87.86%, CSR 96.13%) but a **"largest network" claim that is a national-average artefact** (434 Mumbai hospitals vs HDFC's 520; Stage-2 network **5→3**) — and a chronic **109.6% combined ratio** that motivates future re-pricing.
>
> **Care Supreme:** a good *product* from the weakest *insurer*. Uncapped rooms, 60/180 pre-post, claim-proof bonus, unlimited recharge, **no medical tests to 65 at any SI**. But **solvency sliding to 1.68×**, FY25 operating profit **−86%**, an **IRDAI ₹1cr governance penalty**, and as a **monoline** only two fixes exist — *raise prices or pay less* — already visible in the study's **worst complaint ratio (42/10k claims)**. Stage-2 corrected: network **4→3**, stability **4→2.5** → **~21.5/30**.
>
> **ACKO Platinum:** best coverage *configuration* and price in the study (**₹1Cr for ₹16,178 at 25 = ₹162/lakh**), on the **weakest contract** — "Platinum" is absent from the wording, **37 limits are delegated to a per-policy Schedule**, and the wording **contradicts itself three times** (per-claim cap, cyber-knife vs stereotactic radiosurgery, two different renewal-denial lists). **Eliminated at Stage 1 on ICR alone, then promoted by explicit decision** — which exposed that the F3 floor was mis-specified.

## Files
- `screening/methodology.md` — which variables matter for an individual buyer and why
- `screening/stage1_hard_filters.md` — deal-breaker filters (universe → shortlist)
- `screening/stage2_shortlist.md` — comparative scoring (shortlist → 5 finalists)
- **`decision_hdfc_vs_abhi.md` — the head-to-head decision document for the top two plans**
- `study_plan.md` — the 6-module deep-study framework
- `policies/` — one folder per finalist (each with its own README + module1–6 + resources)
