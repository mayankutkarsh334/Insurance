# Stage 1 — Hard Filters (Deal-Breakers)

**Goal:** cut the universe of ~50–70 retail plans down to a **~10-plan shortlist** using binary pass/fail filters. A plan that fails **any** filter is eliminated, regardless of how good it looks elsewhere.

> These are the "would I even consider this?" gates. Nuanced comparison happens in Stage 2.

## The Filters

| # | Filter | Pass condition | Why it's a deal-breaker |
|---|--------|----------------|-------------------------|
| 1 | **Lifelong renewability** | Renewable for life, no exit age | A policy that drops you at 65/70 is useless when you need it most |
| 2 | **Insurer solvency ratio** | ≥ 1.5 (IRDAI minimum) | Below this, the insurer's ability to pay is in question |
| 3 | **Incurred Claim Ratio (ICR)** | 60%–100% band | <60% = stingy claims culture; >110% sustained = pricing/loss-making risk |
| 4 | **Room rent** | No sub-limit / "any room" available (at chosen SI) OR at least single-private-AC with no proportionate deduction | Room caps silently slash the *entire* claim via proportionate deduction |
| 5 | **Mandatory co-pay** | No compulsory co-pay for an individual under 60 | Forced co-pay means you fund every claim partly out of pocket |
| 6 | **Sum insured** | Offers ≥ ₹10L (ideally a ₹25L+ option) | Below ₹10L is inadequate for modern metro hospital bills |
| 7 | **PED waiting period** | ≤ 4 years (prefer ≤ 3) | Longer means years of exposure on the exact conditions you're insuring |
| 8 | **Restoration / recharge benefit** | Present | For a single life, one big claim can exhaust SI mid-year |
| 9 | **Disease-wise sub-limits** | No hard caps on major procedures | Capped procedures leave a large uncovered gap |
| 10 | **Complaint ratio** | Not an outlier vs peers (IRDAI grievance data) | Chronic complaints signal a hostile claims process |

## How to run this stage
1. Pull the current **retail health product list** per insurer (from `../README.md` universe).
2. For each plan, open the **policy wording PDF** and mark each filter Pass/Fail.
3. Pull **ICR, solvency, complaint ratio** from the latest **IRDAI Annual Report / Bima Bharosa** (insurer-level).
4. Eliminate any Fail. Record *why* eliminated (traceability).

---

# Stage 1 Results — Run July 2026

**Data sources:** IRDAI FY2024-25 (ICR, solvency), insurer brochures/wordings (features). ICR & solvency are **insurer-level**; feature filters (F4/F5/F7/F8/F9) are **plan-level** and assessed for each insurer's current **flagship individual** product.

> **Verification note:** ICR and solvency figures below are confirmed from IRDAI FY2024-25 data. Feature-level filters (room rent, co-pay, PED, sub-limits) are from brochures and **must be re-confirmed against the exact policy wording in Module 1/2** during deep study — brochures summarise, wordings bind.

## Key data pulled

| Insurer | ICR FY24-25 | Solvency (Mar-25) | Notes |
|---------|:-----------:|:-----------------:|-------|
| HDFC ERGO | 84.85% | 2.00 | Strong all-round |
| Bajaj Allianz | 87.31% | ~3.00 | Highest ICR of privates |
| ICICI Lombard | 82.24% | 2.69 | |
| SBI General | 82.19% | >1.5 | |
| Reliance (IndusInd Gen) | 87.34% | >1.5 | |
| Tata AIG | 76.24% | >1.5 | |
| ManipalCigna | 74.81% | ~1.7+ | SAHI |
| Aditya Birla Health | 71.50% | 1.98 | SAHI |
| Star Health | 70.30% | 2.21 | SAHI, largest book → highest complaint volume |
| Care Health | 64.53% | >1.5 | SAHI, low-ish ICR |
| Niva Bupa | 61.22% | 3.03 | SAHI, **lowest ICR** — watch |
| New India Assurance | 100.98% | ~1.8 | PSU, ICR >100 |
| National / Oriental / United | high | **< 1.5 (some)** | PSU, solvency & sub-limit issues |

## Filter results

| Flagship plan | Insurer | F1 Renew | F2 Solv | F3 ICR | F4 Room | F5 Co-pay | F6 SI | F7 PED | F8 Restore | F9 Sublimit | F10 Complaint | Verdict |
|------|---------|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|---------|
| Optima Secure+ | HDFC ERGO | ✅ | ✅ | ✅ | ✅ no-cap | ✅ | ✅ | ✅ 3yr | ✅ | ✅ | ✅ | **PASS** |
| Health Guard / Global Health | Bajaj Allianz | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 3yr | ✅ | ✅ | ✅ | **PASS** |
| Elevate | ICICI Lombard | ✅ | ✅ | ✅ | ✅ no-cap | ✅ | ✅ | ✅ reducible | ✅ | ✅ | ✅ | **PASS** |
| Super Health | SBI General | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 2yr | ✅ | ✅ | ✅ | **PASS** |
| ProHealth Prime / Lifetime | ManipalCigna | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 3yr | ✅ | ✅ | ✅ | **PASS** |
| Activ One (MAX) | Aditya Birla | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ reducible | ✅ | ✅ | ✅ | **PASS** |
| Care Supreme | Care Health | ✅ | ✅ | ⚠️ 64.5% | ✅ | ✅ | ✅ | ✅ 2yr | ✅ | ✅ | ✅ | **PASS** (low ICR) |
| ReAssure 2.0 | Niva Bupa | ✅ | ✅ | ⚠️ 61.2% | ✅ | ✅ | ✅ | ✅ 3yr | ✅ | ✅ | ✅ | **PASS** (lowest ICR) |
| Medicare Premier | Tata AIG | ✅ | ✅ | ✅ | ⚠️ verify | ✅ | ✅ | ✅ | ✅ | ⚠️ verify | ✅ | **PASS** (verify F4/F9) |
| Comprehensive / Superstar | Star Health | ✅ | ✅ | ✅ | ✅ no-cap | ⚠️ some plans | ✅ | ✅ 3yr | ✅ | ✅ | ⚠️ high volume | **PASS** (flags) |
| Health Gain / Infinity | Reliance | ✅ | ✅ | ✅ | ⚠️ verify | ⚠️ verify | ✅ | ✅ | ✅ | ⚠️ verify | ✅ | **BORDERLINE** |
| Mediclaim / Floater | New India (PSU) | ✅ | ✅ | ❌ 100.98% | ❌ capped | ❌ co-pay | ✅ | ❌ 4yr+ | ⚠️ | ❌ sub-limits | ⚠️ | **ELIMINATED** (F3/F4/F5/F9) |
| Mediclaim | National / Oriental / United (PSU) | ✅ | ❌ <1.5 | — | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ | ❌ | **ELIMINATED** (F2 solvency + F4/F5/F9) |

## Outcome

**10 plans PASS** and proceed to Stage 2:

1. HDFC ERGO **Optima Secure+**
2. Bajaj Allianz **Health Guard / Global Health Care**
3. ICICI Lombard **Elevate**
4. SBI General **Super Health**
5. ManipalCigna **ProHealth Prime / Lifetime Health**
6. Aditya Birla **Activ One (MAX)**
7. Care Health **Care Supreme** — carried with a low-ICR flag
8. Niva Bupa **ReAssure 2.0** — carried with a lowest-ICR flag (must justify in Module 3)
9. Tata AIG **Medicare Premier** — verify room-rent/sub-limits in wording
10. Star Health **Comprehensive / Superstar** — carried with co-pay + complaint-volume flags

**Reserve (borderline):** Reliance **Health Gain / Infinity** — held back pending wording check on room rent, co-pay and sub-limits.

**ELIMINATED:**
- **New India Assurance** — ICR 100.98% breaches the 60–100% band (F3); legacy Mediclaim carries room-rent caps, co-pay and disease sub-limits (F4/F5/F9).
- **National / Oriental / United India** — one or more below the 1.5 solvency minimum (F2), plus capped rooms, co-pay and disease sub-limits (F4/F5/F9).

> The low-ICR SAHIs (Care 64.5%, Niva Bupa 61.2%) **pass** the ≥60% floor but are flagged — Module 3 must explain whether the low ICR reflects a young/growing book (premium inflow outpacing an ageing claim base) or a genuinely stingy claims culture.
