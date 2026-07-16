# Module 4 — Cost & Premium

_Source: insurer quote anchors + binding wording (Section E, instalments) + brochure (HealthReturns, zones). Exact age×SI tables live in the quote engine — figures marked **(indicative)** must be confirmed there; only sourced anchors are exact._

> **Read this first — plain-English framing**
> The premium is the yearly price. Activ One's headline trick is **HealthReturns** — it pays you *back* a slice of your premium for staying active, so your *real* cost can be far below the sticker. This module asks: what's the sticker, and how low can HealthReturns + discounts push it?

## Plain-English glossary
| Term | In simple words |
|------|-----------------|
| **HealthReturns** | Cash you earn (a % of premium) for being active — usable to pay next year's premium or medical bills |
| **Zone-based pricing** | Your city's price band; metros (Delhi/Mumbai) cost the most |
| **Age-banded premium** | Price jumps only when you cross an age band (e.g. every 5 yrs), not every single year — gentler |
| **Deductible** | An amount you agree to pay first, in return for a cheaper premium |
| **GST** | 18% government tax added on top of the premium |
| **Section 80D** | Tax rule — your premium is subtracted from taxable income, saving you tax |

## Premium by age — the shape (entry age 26, metro Zone 1)
Exact rupees need a quote; the reliable part is the **shape** — cheap in your 20s–30s, steep after 50. Index below = **26-year-old premium set to 100**. Activ One is **age-banded**, so it rises in *steps* (flat within a band), not a smooth line:

```
Age   Premium index (26 = 100)          (indicative, age-banded steps)
26   |██████ 100      ┐ same band
30   |██████ 100      ┘
35   |████████ 125
45   |████████████ 190
55   |████████████████████ 320
65   |███████████████████████████████████ 560
75   |██████████████████████████████████████████████████████████████ 1000
```

## Real anchor premium (sourced)
| Profile | Cover (SI) | Premium | Source |
|---------|-----------|---------|--------|
| Individual, **age 25**, Activ One NXT | SI unspecified (likely ~₹10–25L) | **₹10,877/yr** | Ditto review |
| Individual, age 26, ₹10L / 25L / 50L / 1Cr | — | **quote-engine only** — *not fully published* | adityabirlahealthinsurance.com |

> One clean anchor (₹10,877 @25). Pull the full ₹10L/25L/50L/1Cr table from the AB calculator before final scoring.

## Premium dynamics (the levers)
| Lever | Detail (plain-English) |
|-------|------------------------|
| Claims-experience discount | No claim-based loading (banned). HealthReturns (below) is the earn mechanism, not a no-claim discount |
| Underwriting risk loadings (max %) | Declared health conditions can be loaded/excluded via counter-offer; healthy 26-yo → usually none |
| Deductible-linked discount | Optional **Per Claim Deductible** (₹15k/₹25k) lowers premium; trade-off is more out-of-pocket per claim |
| Discount stack (family / loyalty / long-term / lifetime) | Family discount; long-term (multi-year) discount; online/digital discount; **PPN 10% discount** (but adds a 10% co-pay outside preferred hospitals) |
| Instalment-premium option | Half-yearly / quarterly / monthly available |
| **Wellness earn-back (net premium)** | ⭐ **HealthReturns — up to 100% of premium back.** Earned via Healthy Heart Score + **Active Dayz** (10k steps or 300 cal/day; ~325 active days/yr for the top tier). Usable for renewal premium, medical bills, diagnostics. **Unique vs HDFC (none)** — for an active 26-yo, a big *net* cost cut |
| Section 80D effective cost | Premium (incl GST) deductible up to **₹25,000/yr** (self <60). SAVR variant adds parents (up to ₹50k). 30% slab → up to ₹7,500 back |
| Zone-based pricing / zone co-pay | 3 zones; **Delhi/Mumbai = Zone 1 (priciest)**. No zone co-pay (M2) |
| GST on premium (18%) | Sticker is pre-tax; you pay **base × 1.18** |
| Age-banded vs annual increase | **Age-banded** — premium steps up only at band boundaries, **not every year** (brochure). Gentler, more predictable than annual-increase plans |
| Medical-inflation / block-repricing risk | UIN `...V022627` = **version 02** — a **newer product (launched ~2024)**, so little revision history yet; expect periodic hikes with 30-day notice (M6) |
| Base-vs-(base+super top-up) cost | AB also sells **Super Health** super top-up — price a moderate Activ One base + top-up vs a large base (see Coverage Architecture) |
| Premium revision history | Newer product (v02) — limited history; *unverified* |

## How your real cost is built
```
Base rate (AGE band + SI)  ×  ZONE (Delhi = highest)
        ▼   + 18% GST
   = STICKER PREMIUM
        ▼   − HealthReturns earned (up to 100% for an active, healthy year)
        ▼   − Section 80D tax saved
   = REAL COST  ◄── can be dramatically below sticker for an active 26-yo
```

## Projected lifetime outgo (indicative)
- **10-yr (26→35):** cheapest decade, age-banded so it barely moves early; HealthReturns can offset a large share if you stay active.
- **20-yr (26→45):** still moderate; steep climb is after 50. **Net** outgo is materially lower than sticker if HealthReturns is earned consistently.

## Sources
- [Ditto — Activ One NXT review](https://joinditto.in/health-insurance/aditya-birla/activ-one-nxt/) (₹10,877 @25, HealthReturns 100%, zone pricing, no co-pay)
- [Aditya Birla Activ One — official page](https://www.adityabirlacapital.com/healthinsurance/activ-one) (HealthReturns mechanics)
- Binding wording `resources/Policy Document_NXT.pdf` — C.9 Health Management/HealthReturns, E.1.17 instalments, UIN ADIHLIP27048V022627
- `resources/Brochure_NXT.pdf` — age-banded premium, 3-zone pricing, tax (SAVR)

## Module 4 score: **5 / 5**
Value is Activ One's strength — exactly why it was shortlisted. A competitive sticker (~₹10,877 @25) is layered with two edges HDFC lacks: **HealthReturns can hand back up to 100% of premium** for an active, healthy 26-yo (your profile), and **age-banded pricing** means the premium steps up gently rather than every year. Add 80D relief and a deductible option and the *net* cost is very low. Watch-outs are mild: HealthReturns is effort/health-score-dependent (not guaranteed), and the same instalment-claim trap applies (M6).
