# Module 1 — Coverage & Benefits

_Source: Health Guard policy wording + brochure, Sections A & B_
_Profile studied: Individual, age 26, metro tier-1 (Zone A)_
_Studied across SI tiers: ₹10L / ₹25L / ₹50L / ₹1Cr_

> **Plain-English intro.** "Coverage" = *what the policy pays for and how much*. Two policies with the same ₹25L "sum insured" (SI = the max the insurer pays in a year) can be very different once you read (a) whether you can pick any hospital room, (b) how the free yearly bonus grows your cover, (c) whether your ₹25L can be *refilled* mid-year after a big claim, and (d) the silent gaps (consumables, domiciliary). This module scores all of that.

---

## ⚠️ Variant decision — which Health Guard to study (resolves Stage-2 carry-forward flag)

Health Guard sells **three plan tiers under one product/UIN (BAJHLIP26073V082526)**:

| Tier | SI range | Gets Super Bonus? | Gets Recharge? | Maternity? |
|------|----------|:--:|:--:|:--:|
| Silver | ₹1.5–2L | ❌ | ❌ | ❌ |
| Gold | ₹3L–₹50L | ❌ (standard CB only) | ❌ | ✅ |
| **Platinum** ← **studied** | **₹5L–₹1Cr** | ✅ **Super CB (up to 150%)** | ✅ **Recharge +20%** | ✅ |

**Decision: study the PLATINUM variant.** Reasons: (1) it is the *only* tier that reaches ₹1Cr — Gold caps at ₹50L; (2) it is the only tier with the richer **Super Cumulative Bonus** and the **Recharge** top-up; (3) all four study tiers (₹10L/25L/50L/1Cr) exist in Platinum.

> **Carry-forward flag RESOLVED (Stage-2, Bajaj M1):** "Global Health Care" (international cover) is a **separate product**, *not* a Health Guard variant. Health Guard explicitly **excludes all treatment outside India** (Exclusion 23). For a **domestic individual buyer**, the correct plan is **Health Guard Platinum** — Global Health Care would only matter if the user wanted worldwide cover, which this profile does not.
> ⚠️ **Variant-ladder mis-selling check:** because Silver/Gold/Platinum share one name + one UIN, confirm the policy schedule literally says **"Platinum"** and the SI is **₹10L+** — a Gold policy at the same SI silently loses Super CB + Recharge.

---

## Variant / configuration
| Item | Detail |
|------|--------|
| Product variant studied | **Health Guard – Platinum** (top of 3-tier ladder) |
| Product / UIN | Health Guard · **BAJHLIP26073V082526** (brochure dated 31-10-2025) |
| Wording version in `resources/` | **BAJHLIP25035V072425** (2024-25, current-1) on file + 2021 archive; brochure is one revision newer (V082526) |
| Base sum insured options studied | ₹10L · ₹25L · ₹50L · ₹1Cr |
| Zone bought | **Zone A** (Delhi-NCR/Mumbai/etc.) → **no co-pay** anywhere in India |

---

## 🔑 Claim-lever definitions (Phase-1 wording forensics)
_These are the fine-print levers an insurer uses to trim or deny a claim. Extract them before trusting any headline benefit._

| Definition | Health Guard wording | Why it matters | vs HDFC Optima (benchmark) |
|------------|----------------------|----------------|-----------------------------|
| **Pre-existing disease — lookback** | **36 months** (per current binding wording V072425; the 2021 archive said 48 mo) | How far back they dig to call something "pre-existing" and park it behind the waiting period | Optima 36-mo lookback → **now matches benchmark** (corrected in M2) |
| **PED — waiting period** | **36 months** before PED is covered | Distinct from lookback above; 3-yr wait | Optima 36 mo (same) |
| **Any One Illness — relapse window** | **45 days** from last consultation = *same* claim | A return within 45 days is one claim (affects restore/limits) | Optima 45 days (same) |
| **Reasonable & Customary (R&C)** | Present — "standard charges… consistent with prevailing charges in the geographical area" | Lets insurer trim a bill to "customary" rates — discretionary | Present in Optima too |
| **Medically Necessary** | Present — treatment "must not exceed the level of care necessary…" | Lets insurer reject care it deems excessive/unnecessary | Present in Optima too |
| **Room rent (def.)** | "amount charged for occupancy of a bed per 24h incl. associated medical expenses" | Anchors the proportionate-deduction math | Standard |

---

## Benefit-stacking math (Platinum)

> **How the layers combine (plain English).** Think of it as buckets that fill and empty:
> **Base SI** (what you bought) → **+ Super Cumulative Bonus** (free extra cover earned for each claim-free year, up to +150%) → **+ Recharge** (a one-time +20% top-up, capped at ₹5L, if a claim overshoots) → and separately, **Reinstatement** refills the *whole* base SI once, but only for a *later, different* claim after the first bucket is empty.

| Layer | This plan (Platinum) | Notes |
|-------|----------------------|-------|
| **Base SI** | ₹10L / ₹25L / ₹50L / ₹1Cr | The headline cover |
| **Instant multiplier (day-1)** | ❌ None | No 2×-day-1 style multiplier (HDFC Optima Secure has 2× day-1; Bajaj does not) |
| **Super Cumulative Bonus (Platinum)** | **+50% yr1, +50% yr2, then +10%/yr × 5 → max +150% of SI** | Claim-dependent: a claim drops the bonus *to the previous slab* (SI itself preserved). Accrues only in claim-free years |
| **Recharge Benefit (Platinum)** | **+20% of SI, capped ₹5L**, once/yr, when a claim exceeds available cover | ⚠️ flat ₹5L cap — see Multiplier-cap check below |
| **Restoration / Reinstatement** | **100% of Base SI, once/policy-year** | Unrelated illness only; triggers *after* SI+bonus exhausted; **Cancer & dialysis: only ONCE per lifetime** |
| **Per-claim cap rule** | **Base SI + accrued Super CB + Recharge** | Reinstatement can NOT be drawn on the *same* claim that emptied the SI (Clause iii) — it's for the *next* claim |

### Multiplier hard-cap check (Rule-3 dimension, from ABHI framework) — **Recharge ₹5L ceiling bites at high SI**
The Recharge headline is "+20%", but a **flat ₹5L rupee ceiling** clips it:

| SI | Recharge (20%) | Actual Recharge (₹5L cap) | Effective % delivered |
|----|:--:|:--:|:--:|
| ₹10L | ₹2L | ₹2L | 20% ✅ |
| ₹25L | ₹5L | ₹5L | 20% ✅ (cap just met) |
| ₹50L | ₹10L | **₹5L** | **10%** ⚠️ |
| ₹1Cr | ₹20L | **₹5L** | **5%** ⚠️ |

> **Finding:** Recharge is a *meaningful* top-up only up to ₹25L. At ₹50L it's half-delivered; at ₹1Cr it's a rounding error (5%). The **Super Cumulative Bonus (no rupee cap, scales cleanly with SI)** is the real high-SI growth engine, not Recharge.

### How total cover scales with SI (Platinum, after 7 claim-free years)
```
                 Base SI   + Super CB(150%)  + Recharge(cap ₹5L)  = Peak single-claim ceiling
  ₹10L  ▓▓                    ▓▓▓                ▓                   ≈ ₹27L
  ₹25L  ▓▓▓▓▓                 ▓▓▓▓▓▓▓            ▓                   ≈ ₹67.5L
  ₹50L  ▓▓▓▓▓▓▓▓▓▓            ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓    ▓ (5L)              ≈ ₹1.3Cr
  ₹1Cr  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  ×1.5 = +₹1.5Cr    ▓ (5L)              ≈ ₹2.55Cr
        (+ Reinstatement refills the full Base SI once more for a separate later claim)
```
**Read:** cover scales *linearly and cleanly* with SI because the bonus is percentage-based with no rupee ceiling. The only SI-scaling *weakness* is Recharge (flat-capped).

---

## 🛏️ Room economics — how the room benefit itself scales with SI *(NEW M1 sub-dimension — see Rule-3 note)*

This is Bajaj's most important SI-scaling mechanic and it's easy to miss:

| SI band (Gold/Platinum) | Eligible room | Proportionate-deduction risk? |
|-------------------------|---------------|-------------------------------|
| ₹3L – ₹7.5L | **Single private A/C room only** | ⚠️ Yes — pick a costlier room and *all* charges are cut proportionately |
| **₹10L and above** | **ANY room category (no cap)** | ✅ **No cap → no proportionate deduction** |
| ICU (all bands) | **At actuals** | ✅ No ICU cap |

> **Finding — the ₹10L threshold is the real "no room cap" line.** All four study tiers (₹10L/25L/50L/1Cr) enjoy **no room-rent cap** → you can choose any room without the dreaded *proportionate deduction* (where exceeding the room limit shrinks your whole bill pro-rata). Below ₹10L you're capped to a single A/C room. **For this profile (₹10L+), room economics are excellent — on par with HDFC Optima's "at actuals".**
> - Proportionate deduction, when it does apply (<₹10L), **excludes** pharmacy/consumables/implants/devices/diagnostics from the cut (IRDAI-compliant).
> - Optional **"Room-rent capping" discount**: voluntarily accept a 1.5%-of-SI (max ₹7,500/day) room cap → 8% premium discount (Platinum). Trade-off feature; feeds M4. *Don't opt it if you value the no-cap benefit.*

---

## Feature checklist (Platinum)
| Feature | Detail | Notes |
|---------|--------|-------|
| **Room rent** | **No cap at SI ≥ ₹10L** (any room); ICU at actuals | Single-A/C-room cap only below ₹10L → not relevant to this profile ✅ |
| **Cumulative Bonus ceiling** | **Super CB: max +150% of SI** (50/50/10×5) | Scales with SI, no rupee cap ✅ (Gold tier gets only standard 100% CB) |
| **Claim impact on bonus** | Claim **drops bonus to previous slab** (SI preserved) | ⚠️ Not claim-*proof* — HDFC's "Infinite Benefit" accrues irrespective of claims; Bajaj's does not |
| **Pre / post-hospitalisation** | **60 / 90 days** | ⚠️ Post-hosp **90 days < HDFC Optima's 180** — a real gap for long recoveries |
| **Day-care procedures** | Covered — indicative list (Annexure I); any procedure needing <24h | Not a fixed "count"; broad |
| **Domiciliary hospitalisation** | ❌ **Not covered** (absent from wording) | ⚠️ Gap vs HDFC Optima |
| **Home healthcare** | ❌ **Not covered** | ⚠️ Gap |
| **AYUSH** | Ayurveda/Yoga/Unani/Siddha/Homeopathy inpatient — **up to full Sum Insured** | ✅ **CONFLICT RESOLVED:** current binding wording (V072425, cl. 13) pays AYUSH *"up to the limit of In-patient Hospitalization Treatment Sum Insured"* — the brochure's "₹20,000/yr" sub-limit entry is **stale/erroneous**. Wording binds → AYUSH = full SI |
| **Modern treatments** | Covered (robotic, oral chemo, immunotherapy, deep-brain stim, balloon sinuplasty, stereotactic, etc.) — **up to full Base SI** | ✅ **Corrected in M2:** current wording removed the old 50%/₹5L cap → full SI (2021 archive had the cap) |
| **Day-1 cover for listed chronic conditions** | ❌ **None** | ⚠️ No day-1 diabetes/BP cover; 36-mo PED wait, and these conditions even trigger entry medical tests. Gap vs Aditya Birla |
| **Consumables / non-medical (Protect-type)** | *Medical* consumables paid within inpatient bill; **non-medical items (Annexure II) EXCLUDED** | ⚠️ **No consumables buy-back.** Silent gap vs HDFC Optima (covers non-medicals) |
| **Consumables economics (₹ gap)** | Typical uncovered non-medical spend **₹15k–₹1L per admission** falls on you | Material out-of-pocket risk on big surgeries/ICU |
| **Wellness / earn-back** | **Wellness discount up to 10% (+2.5%)** on renewal premium for meeting health metrics | Premium *discount*, not cash earn-back; feeds M4 (no wallet lock-in) |
| **Ambulance (road / air)** | Road **₹20,000/yr**; **Air = optional paid add-on** (SI ≥ ₹5L, sub-limits ₹5L–₹50L) | Air not inbuilt |
| **Organ-donor cover** | ✅ Donor's harvesting/hospitalisation expenses | Standard |
| **Daily cash / shared room** | **₹500/day × max 10 days** — for a parent accompanying an insured child <12 | Narrow (child-only); not general daily cash |
| **Convalescence benefit** | **₹7,500** (SI ≥ ₹7.5L) if hospitalised >10 continuous days | Doesn't reduce base SI |
| **Preventive health check-up** | **1% of SI, max ₹5,000/insured**, per **2-yr block (Platinum)** | Platinum block = 2 yrs (Gold = 3 yrs) → Platinum slightly better |
| **E-opinion / global-emergency cover** | ❌ No e-opinion; ❌ **no global/overseas cover** (Exclusion 23) | Domestic-only product |
| **Maternity / OPD / add-ons** | Maternity (Gold/Platinum): **₹25k normal / ₹35k caesarean** at SI ≥ ₹10L, **72-mo wait**, 2 deliveries; incl. New-Born cover | Down-weighted; low limits |
| **Bariatric surgery** | 50% of SI, max ₹5L, 36-mo wait | Included (many plans make it optional) |
| **Reinstatement lifetime carve-out** | Cancer & kidney-failure-requiring-dialysis: reinstatement **only once per lifetime** | ⚠️ The two costliest chronic claims get the *weakest* refill |

---

## SI-scaling summary — coverage / room / bonus across tiers

| Dimension | ₹10L | ₹25L | ₹50L | ₹1Cr |
|-----------|:----:|:----:|:----:|:----:|
| Room cap | None (any room) ✅ | None ✅ | None ✅ | None ✅ |
| Super CB peak (+150%) | +₹15L | +₹37.5L | +₹75L | +₹1.5Cr |
| Recharge (20%, ₹5L cap) | ₹2L (20%) ✅ | ₹5L (20%) ✅ | ₹5L (**10%**) ⚠️ | ₹5L (**5%**) ⚠️ |
| Reinstatement (100% base) | ₹10L | ₹25L | ₹50L | ₹1Cr |
| Peak 1-claim ceiling (yr7) | ≈₹27L | ≈₹67.5L | ≈₹1.3Cr | ≈₹2.55Cr |
| Maternity limit | ₹25k/₹35k | ₹25k/₹35k | ₹25k/₹35k | ₹25k/₹35k |
| Modern-treatment cap | Full SI | Full SI | Full SI | Full SI |

> **Takeaway on scaling:** coverage *quality* is uniform across tiers (no room cap, full Super CB %) — the one thing that **doesn't scale** is the flat-rupee cap on **Recharge** (₹5L), which quietly weakens the high-SI (₹50L/₹1Cr) tiers. *(Modern-treatment is full-SI in the current wording — see M2 correction.)* Fixed benefits (maternity, ambulance, daily cash) also stay flat and become trivially small at ₹1Cr.

---

## 🚩 Red flags & brochure-vs-wording conflicts
1. **AYUSH cap conflict — RESOLVED (favourably):** brochure said both "up to Sum Insured" *and* "₹20,000/policy-year". The current binding wording (**V072425, clause 13**) pays AYUSH **up to full In-patient SI** — the brochure sub-limit table entry is stale. *Lesson: the brochure's own sub-limit table contradicted its benefit text; only the wording settled it (wording binds).*
2. **Consumables/non-medical excluded** — no buy-back; ₹15k–₹1L per admission is your risk. Genuine gap vs the HDFC benchmark.
3. **Post-hospitalisation only 90 days** vs benchmark 180.
4. **Bonus is not claim-proof** — a claim knocks the Super CB back a slab.
5. **Recharge & Modern-treatment flat ₹5L caps** erode the ₹50L/₹1Cr tiers.
6. **PED lookback 48 months** (vs benchmark 36) — a wider net for "pre-existing".

## 🌱 NEW dimensions added (Rule 3)
- **M1 template — added rows:** "Domiciliary hospitalisation", "Convalescence benefit", "Bariatric surgery", "Reinstatement lifetime carve-out (Cancer/dialysis)". *(These reflect real Health Guard clauses the base template didn't itemise.)*
- **NEW M1 sub-dimension — "Room-eligibility gated by SI band":** the room benefit *itself* upgrades with SI (single-A/C-room below ₹10L → any-room at ₹10L+). Broad enough to apply to every plan → **propose adding to `study_plan.md` M1** as: *"Check whether the no-room-cap benefit is universal or gated to an SI threshold — some plans grant 'any room' only above a band."* Called out here for the user's approval before editing the shared plan file.
- **Applied existing Rule-3 dimensions:** Multiplier-hard-cap check (Recharge ₹5L) and Variant-ladder mis-selling check (Silver/Gold/Platinum, one UIN).

---

## Sources
- [Health Guard Brochure (current, UIN BAJHLIP26073V082526, 31-10-2025)](https://www.bajajgeneralinsurance.com/download-documents/health-insurance/health-guard/Health-Guard-Brochure-print.pdf) — saved to `resources/brochure.pdf`
- [Health Guard Policy Wording (current, UIN BAJHLIP25035V072425, 2024-25)](https://www.bajajgeneralinsurance.com/download-documents/health-insurance/health-guard/Health-Guard-Policy-Wordings-print.pdf) — saved to `resources/wording_current.pdf` (**binding source**; resolved AYUSH cap via clause 13)
- [Health Guard Premium Rate Chart](https://www.bajajgeneralinsurance.com/download-documents/health-insurance/health-guard/New-Health-Guard-Premium-Chart.pdf) — saved to `resources/premium_chart.pdf` (for Module 4; image-based PDF)
- [Health Guard Gold Policy Wording & CIS (2021, BAJHLIP21185V032021)](https://www.bajajgeneralinsurance.com/download-documents/health-insurance/health-guard-individual-policy/HG_Gold_Policy_Wording_&_CIS.pdf) — saved to `resources/wording_gold.pdf` (archive)
- [IRDAI policyholder repository — Health Guard Gold wording (archive)](https://policyholder.gov.in/documents/37343/931203/BajajAllianz_HealthGuard(GoldPlan)_2016-2017.pdf)

**Module 1 score: 3.5 / 5**

**Rationale:** Strong where it counts for this profile — **no room-rent cap at ₹10L+ (ICU at actuals)**, a rich **Super Cumulative Bonus (+150%, no rupee cap)** that scales cleanly with SI, once-a-year full reinstatement, and Zone-A = zero co-pay. But it lands below the HDFC benchmark on real gaps: **no consumables/non-medical buy-back** (₹15k–₹1L silent exposure), **post-hospitalisation only 90 days** (vs 180), **no domiciliary/home-care**, **no day-1 chronic cover**, a **bonus that isn't claim-proof**, and **flat ₹5L caps** on Recharge + modern treatments that quietly weaken the ₹50L/₹1Cr tiers. (The AYUSH conflict resolved *favourably* — full-SI cover per the binding wording — but the gaps above are what hold it at 3.5, not a 4.) Solid, claims-friendly coverage — but not the feature leader.
