# Module 3 — Claims & Servicing

_Source: IRDAI FY24-25 data + **Acko Personal Health Policy wording** (UIN **ACKHLIP25035V022425**), **§6.1 Claims Procedure**, §6.2 Grievance Redressal, defs 33/36/42 (Network Provider, Notification, TPA). Files in `resources/`._
_Profile studied: **Individual (single adult), age 26, metro tier-1**_
_**Weight: 25% — the highest.** A plan that won't pay is worthless regardless of features._

> **Plain-English intro.** Three questions: **"Will they pay? Will they pay fast? Can I go cashless near my home?"**
> - **ICR (Incurred Claims Ratio)** = of every ₹100 of premium, how much went back out as claims. Low can mean *stingy* — **or** cheap pricing, a fast-growing book, or **a young customer base that simply doesn't claim much.**
> - **CSR (Claim Settlement Ratio)** = what % of claims were paid, **by count**.
> - **Complaint ratio** = formal complaints per 10,000 claims. The hardest number to explain away.
>
> **This module exists to answer the question that got Acko eliminated at Stage 1: is a 57.82% ICR stinginess, or something else?** The honest answer below is **"probably not stinginess — but it is not fully explained either."**

---

## Claims track record

| Metric | Value | Trend |
|--------|-------|-------|
| **Incurred Claim Ratio (ICR)** | **FY24-25: 57.82%** · FY23-24: 56.91% · FY22-23: 83.88% · **3-yr avg 66.20%** | 🚩 **Collapsed 27 points in one year** (83.88 → 56.91), then flat. **The single most important unexplained number in this study** |
| **ICR vs the correct peer segment** *(framework — Care M3)* | 🚩 **Acko is a PRIVATE GENERAL insurer, so its benchmark is 77.50%** (IRDAI FY24-25 health segment), **not** the SAHI 68.06% or the blended 85.34%. **Acko 57.82% vs 77.50% = −19.7 points** | 🚩 **The peer-segment correction that RESCUED Care does NOT rescue Acko.** Care was only **−3.5 pts** vs its SAHI peers (64.53 vs 68.06); **Acko is nearly 20 points below its own segment.** It is a **genuine outlier even on the right benchmark** |
| **Claim repudiation / rejection rate** | **unverified for Acko specifically.** Industry FY24-25: ~8% repudiated / 87% settled / 5% pending | *Confirming source: [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports), company-wise claims-disposal table* |
| **Complaint ratio (per 10k policies)** | **Denominator: per 10,000 CLAIMS.** **FY24-25: 15.58** · FY23-24: 27.33 · FY22-23: 14.97 · **3-yr avg 19.29** vs **industry 27.06** | ✅ **BELOW industry, and recovering.** Better than every finalist **except HDFC (4.99) and Bajaj (5.25)** — and **2.7× better than Care Supreme's 42.00**. ⚠️ Note the FY23-24 spike to 27.33, the same year the ICR collapsed |
| **Grievance disposal %** | **unverified** | *Confirming source: [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports) grievance-disposal table* |
| **Cashless settlement %** | **unverified.** ✅ Acko **participates in "Cashless Everywhere"** and publishes a dedicated page for it | *Confirming source: General Insurance Council Cashless Everywhere utilisation data* |
| **Health claims payout ratio (insurer)** | **CSR by count: FY24-25 95.75%** · FY23-24 96.31% · FY22-23 97.45% · **3-yr avg 96.50%** vs **industry 91.22%** | ✅ **Above industry all three years** — but **gently declining** (97.45 → 95.75) |
| **Payout by AMOUNT vs CSR by COUNT** | ⚠️ **The same divergence as Care, but wider.** **CSR 95.75% (count) beside ICR 57.82% (rupees).** Claims-paid-by-amount **not published** | 🚩 **Acko approves ~96 of every 100 claims but returns only ₹58 per ₹100 of premium.** M1 and M2 identified concrete narrowing mechanisms: **restore excludes the same illness**, the **possible Base-SI-only per-claim cap (§3.1(d)(4))**, the **tobacco-cancer exclusion**, and **Annexure-1 non-payables unless the §3.3.8 waiver is bought**. *Confirming source: IRDAI claims-paid-by-amount table* |
| **Settlement-speed distribution (TAT buckets)** *(NEW ROW — framework, ABHI M3)* | ✅ **99.98% of claims paid within 3 months (FY24-25) — the best of any private general insurer** | ✅✅ **Acko wins this dimension outright.** The framework asks for the ageing distribution rather than headline CSR; on that test Acko has **effectively no slow tail** — materially better than the "unverified" recorded for SBI and Care |

### 📊 The contradiction, in one picture

```
                    ICR (rupees paid per Rs 100 premium)    Complaints /10k    Speed
  PSU general       ####################  97.30%              —                 —
  Overall health    #################     85.34%              27.06 (industry)  —
  PRIVATE GENERAL   ###############       77.50%   <- Acko's true peer group
  SAHI segment      #############         68.06%
  Care Health       ############          64.53%              42.00  (worst)    unverified
  ACKO              ###########           57.82%  <- lowest    15.58  (good)     99.98% <3mo (best)
```
> **Read this carefully — it is genuinely contradictory.** Acko pays out **the fewest rupees** of any plan studied, yet its customers **complain less than the industry average** and its claims are **settled faster than any private general insurer's**. Stinginess normally produces *complaints and delays*. Acko produces **neither**.

---

## 🚩 Resolving the Stage-1 flag — *"is 57.82% stinginess?"*

**Verdict: NOT fully resolved. The most probable explanation is structural, not behavioural — but it is inference, and the gap is too large to wave away.**

| Candidate explanation | Evidence for | Evidence against | Assessment |
|---|---|---|---|
| **Deliberate claims stinginess** | ICR ~20 pts below peer segment; M1/M2 narrowing clauses are real (restore excludes same illness, possible Base-SI-only cap, tobacco-cancer exclusion, open waiting list) | 🚩 **Complaints are BELOW industry (15.58 vs 27.06)** and **99.98% of claims settle within 3 months**. A stingy insurer generates arguments and delays — Acko generates neither. CSR 95.75% | **Unlikely as the primary driver** |
| **Very cheap pricing** | **₹16,178 for ₹1Cr at age 25 = ₹162/lakh**, roughly **3× more SI-efficient than the cheapest finalist** (M1). ICR is a *ratio* — a large denominator depresses it | — | ✅ **Strong contributor** |
| **Fast-growing book (ballooning denominator)** | ICR fell **27 points in a single year**. You cannot become 27 points stingier in 12 months without complaints exploding — and complaints **fell back** the following year | FY23-24 complaints *did* spike to 27.33 | ✅ **Strong contributor**, consistent with a growth/servicing stress year that was then fixed |
| **⭐ A structurally YOUNG book** | Acko is **digital-first, app-sold, and markets explicitly to 25-year-olds**. A book of 25–35-year-olds claims **far less frequently** than a legacy insurer's 50+ book — depressing ICR with no change in generosity | ⚠️ **Acko's age-mix is not published** | ✅ **Probably the largest single factor — and the framework had no way to test it.** → **New dimension below.** ⚠️ **UNVERIFIED** — *confirming source: IRDAI age-band claims data / Acko public disclosures* |

> **The honest synthesis.** Acko's low ICR is **most plausibly the arithmetic of a young, cheaply-priced, fast-growing digital book** rather than a claims culture that refuses to pay — and the service data (**complaints below industry, 99.98% settled within 3 months, CSR 95.75%**) actively contradicts the stinginess reading. **But three cautions stand: (1)** the gap to its true peer group is **~20 points**, too large to be fully explained by inference; **(2)** the age-mix explanation is **unverified**; and **(3)** M1 and M2 found **real, specific mechanisms** by which Acko pays less per claim than a buyer would expect. **State it as: "fast, low-friction claims service, but the lowest rupee payout in the study, for reasons that are probably structural but remain unproven."**

---

## Network

| Metric | Value |
|--------|-------|
| **Network hospital count (raw)** | ⚠️ **Dispersion ~1.24×** — Acko markets **14,300+**; other sources say **11,500+**; the screening density table used **11,500 (≈14.7/district)**. ✅ **Narrower spread than SBI's 2.8× or Care's 2.3×**, and Acko **does publish a figure** |
| **Per-district density (÷~780)** | **≈14.7–18.3 per district** (11,500–14,300 ÷ 780). On the conservative figure Acko sits **4th** in the study's density table: HDFC ≈17.4 > Aditya Birla ≈15.8 > Bajaj ≈15.6 > **Acko ≈14.7** > Royal Sundaram ≈12.8 — **and ahead of Care (≈14.6–15.3)** |
| **Your city's top hospitals in-network?** | 🚩 **The metro-concentration test CANNOT be run for Acko.** PolicyBazaar — the single source used to compare **HDFC 520 / SBI 434 / Care 299 in Mumbai** — **does not carry Acko**, so no same-source metro count exists. Acko confirms cashless coverage in Delhi, Mumbai, Bengaluru, Chennai, Hyderabad, Pune, Kolkata and Ahmedabad. **Absolute metro count: unverified** — *confirming source: [Acko's cashless hospital locator](https://www.acko.com/gi/p/health/networkhospitals) or the ACKO app, searched by the buyer's pin code* |

> **Finding — adequate nationally, unverifiable locally.** Acko's per-district density is **mid-pack and ahead of Care**, and its count dispersion is the **narrowest of any insurer tested** — a data-quality point in its favour after the SBI debacle. ✅ **Cashless Everywhere participation** further reduces network dependence. ⚠️ **But the framework's decisive test — how many cashless hospitals in MY city — cannot be answered from public data**, so the network cannot be scored with the confidence applied to HDFC, SBI and Care. **Run the pin-code search before buying.**
>
> ✅ **Transparency credit:** Acko **publishes its excluded-hospitals list** on a dedicated public page — better disclosure than rivals, whose blacklists sit in an annexure.

---

## Claim mechanics (from wording)

| Item | Detail |
|------|--------|
| **Cashless pre-auth deadline (planned / emergency)** | **Planned: notify ~3 days (72 hrs) in advance** (§6.1.2, §6.1.3) · **Emergency: within 48 hours of admission, before discharge**. Pre-authorisation letter **valid 15 days**. ⚠️ **Planned window matches SBI's 72 hrs — stricter than HDFC's and Care's 48 hrs** |
| **Reimbursement intimation & doc windows** | Documents on request within set timelines. ✅ **Condonation:** *"if it was not possible for you to submit the documentation earlier, **we will make exceptions to pay your claim**"* (§6.1.1). ✅ **Deficiency handling is unusually pragmatic:** reminders every **10 days, max 3**, and Acko *"may… **deduct the amount of claim for which deficiency is intimated and settle the claim**"* — i.e. **it pays the valid portion rather than holding the whole claim hostage** |
| **Settlement TAT** | ✅ **"We shall settle the claim within 15 days from the date of receipt of the last necessary document"** — **matches the HDFC/SBI/Care benchmark**. Where investigation is warranted: completed **not later than 30 days**, claim settled or rejected **within 30 days** |
| **Penal interest for delay** | ✅ **2% above the bank rate**, from receipt of the last necessary document to the date of payment — a **contractual** obligation, matching the benchmark |
| **TPA vs in-house adjudication** | ⚠️ **MIXED — and this contradicts the marketing.** Acko is widely described as in-house/no-TPA, but the wording **defines TPA (def. 42)**, states *"the list and details of TPA are set out on Our website"*, and §6.1.2 refers to notifying *"through our **TPA partners at the hospital cashless desk**"*. **Acko does use TPAs, at least at the cashless interface.** Claims are otherwise app/digital-first |
| **IRDAI 2024 mandate delivery (cashless-anywhere, 1hr/3hr)** | ✅ **Cashless Everywhere participation confirmed** (dedicated public page). ⚠️ **The 1-hour pre-auth / 3-hour discharge TATs are not stated in the wording** — unlike SBI's CIS, which commits to both. **Real-world delivery: strongly supported indirectly by the 99.98%-within-3-months record**, but the specific mandates are **unverified**. *Confirming source: Acko CIS / General Insurance Council data* |
| **Cashless-outside-India / 100% cashless** | ❌ **No cover outside India** unless option **§3.3.1 Worldwide in-patient** is on the Schedule (not in the Platinum bundle) — and §5.2.3 confirms *"All admitted or payable claims will only be settled in India."* Several benefits are **reimbursement-only** (domiciliary §3.2.7; pre/post-hospitalisation §3.2.4) |
| **Network discretion clause** *(NEW ROW — framework, SBI M3)* | ⚠️ *"**ACKO reserves the right to modify, add or restrict the list of network hospitals** where you can avail a cashless policy"* (§6.1) + **Excluded Providers (§4.1.9, Code-Excl11)** — a claim at a blacklisted hospital is inadmissible bar emergency stabilisation. **The network is revocable, as with every rival.** ✅ **Mitigant: the excluded list is published on a public page**, not buried |
| **Late-intimation consequence** *(NEW ROW — framework, Care M3)* | 🚩 **"In case you delay informing ACKO outside these timelines, ACKO can choose to deny your claim"** (§6.1.2). ⚠️ Drafted as a **discretion to deny**, not an absolute condition precedent. ✅ **Materially softer than Care Supreme**, whose 48-hour intimation is a *"condition precedent to admission of liability."* ✅ **And if the §3.3.4 First Notification option is on your Schedule, late notice converts to a proportionate CO-PAY instead of denial** — the fairest of the three constructions seen |
| **Grievance → Ombudsman → IRDAI IGMS path** *(NEW ROW)* | ✅ §6.2: helpline **1800 266 2256** / 1860 266 2256, email, then Grievance Officer → **Insurance Ombudsman** → **IRDAI Bima Bharosa (IGMS)**. Standard ladder |

---

## 🆕 NEW DIMENSION discovered in this module *(Rule 3)*

### The BOOK'S AGE-MIX as an ICR confounder — a young digital book structurally under-claims *(→ new bullet in study_plan M3)*
The framework now has two ICR safeguards: **benchmark against the correct peer segment** (Care M3) and **cross-check against service data** (Acko/Royal Sundaram screening). **Neither explains Acko.** Its ICR is **~20 points below its own private-general peer group (57.82% vs 77.50%)** — so the peer correction fails — while its **complaints are below industry and 99.98% of claims settle within three months** — so the service cross-check says "not stingy". **The two safeguards give opposite answers, and the missing variable is the age profile of the insured book.**

Claim frequency and severity rise steeply with age. An insurer that **sells digitally to 25–35-year-olds** (Acko markets explicitly to 25-year-olds and sells through an app) will show a **structurally lower ICR** than a legacy insurer carrying decades of 50+ policyholders — **with no difference whatever in generosity**. It also explains the **27-point single-year collapse**: a book growing fast at the young end mechanically dilutes the ratio far quicker than claims behaviour could change.
> **New generalisable check: "Before reading an ICR as generous or stingy, ask what the insurer's BOOK looks like — its age mix, vintage, and growth rate. A young, fast-growing, digitally-acquired book under-claims structurally; a mature or legacy book over-claims. Where the peer-segment benchmark and the service cross-check DISAGREE (as they do for Acko), age-mix is the most likely missing variable — and if it is not published, say so and mark the ICR reading as UNRESOLVED rather than forcing a verdict."** *(Confirming source: IRDAI age-band claims data, or the insurer's public disclosures on portfolio age distribution.)*

---

## Brochure-vs-wording check *(Rule 2)*

⚠️ **Two gaps, one of which reverses a claim recorded at screening:**

| Item | Marketing / secondary sources say | **Binding wording says** | Effect |
|------|-----------------------------------|--------------------------|--------|
| **Claims handling** | Acko is **"in-house, no TPA"** — digital-first, direct | **def. 42 defines TPA**; *"the list and details of TPA are set out on Our website"*; §6.1.2 refers to *"our **TPA partners** at the hospital cashless desk"* | ⚠️ **Acko DOES use TPAs at the cashless interface.** The screening note describing Acko as in-house is **corrected** |
| **Network size** | **"14,300+"** | Not stated in the wording; other sources say **11,500+** | ⚠️ Modest dispersion (~1.24×) — far better than SBI (2.8×) or Care (2.3×), but use the conservative figure |

✅ **No conflict within Acko's own binding document** on claims mechanics — the 15-day settlement, 2%-above-bank-rate penal interest, 3-day/48-hour notification and 15-day pre-auth validity are internally consistent.

> **Carry-forward flags** *(stage2_shortlist.md)*: Acko's flag — **the 57.82% ICR that eliminated it at Stage 1** — is **addressed but NOT closed.** ⚠️ **Update for the decision tree: the Stage-1 challenge is only half-vindicated.** Stage 1 argued the F3 floor was mis-specified because Acko's *service* metrics beat Care's; **that remains true and is reinforced here** (complaints 15.58 vs 42.00; 99.98% settled within 3 months; contractual 15-day TAT). **But Stage 1 did not test Acko against its correct peer segment — and on that test Acko is a ~20-point outlier, whereas Care was only 3.5 points below its own.** **Fair conclusion: Acko is the better *claims experience* and the worse *rupee payout*, and the reason for the latter is probably structural (young, cheap, fast-growing book) but unproven.** **Acko's conditional Stage-2 Claims score of 3 stands — it should not be raised without age-mix or payout-by-amount data.**

---

## Sources

- [Business Standard — "Paying claims or pushing back? What Irdai data reveals about insurers"](https://www.business-standard.com/finance/personal-finance/paying-claims-or-pushing-back-what-irdai-data-reveals-about-insurers-126010100580_1.html) — ***the peer-segment benchmarks: private general insurers 77.50%, SAHI 68.06%, PSU 97.30%, overall health 85.34%*** (FY24-25)
- [Ditto — Acko Health Claim Settlement Ratio](https://joinditto.in/articles/health-insurance/acko-health-insurance-claim-settlement-ratio/) — ***ICR 83.88 / 56.91 / 57.82% (3-yr 66.20%); CSR 97.45 / 96.31 / 95.75% (3-yr 96.50%, industry 91.22%); complaints per 10,000 claims 14.97 / 27.33 / 15.58 (3-yr 19.29, industry 27.06)***
- [SiliconIndia — ACKO health claim settlement ratio](https://www.siliconindia.com/news/general/acko-health-claim-settlement-ratio-what-policyholders-should-know-nid-239522-cid-1.html) · [smallnews.in — IRDAI CSR release 2026](https://smallnews.in/insurance/2026/02/05/latest-claim-settlement-ratio-of-health-and-general-insurers-released-by-irdai-in-2026-acko-aditya-birla-galaxy-lead-shriram-iffco-tokio-fall-below-90/) — ***99.98% of claims paid within 3 months in FY24-25, best among private general insurers*** (the TAT-ageing dimension)
- [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports) — *industry claims disposal (~87% settled / 8% repudiated / 5% pending). **Company-wise claims-by-ageing, claims-by-amount and grievance-disposal tables not retrieved — the source that would close the unverified metrics above***
- [Acko Personal Health Policy — Policy Wording, UIN ACKHLIP25035V022425](resources/policy_wording_acko_personal_health.pdf) — *binding; **§6.1 Claims Procedure** (6.1.1 conditions + document condonation, 6.1.2 registration & the "**can choose to deny**" late-intimation clause, 6.1.3 cashless & pre-authorisation, 6.1.5 deficiency handling, 6.1.6 assessment), **15-day settlement + 2%-above-bank-rate penal interest**, 30-day investigation route; **§6.1 network-modification discretion**; §6.2 grievance ladder; defs 33/36/**42 TPA**; §4.1.9 Excluded Providers; §5.2.3 claims settled in India only*
- [ACKO — Cashless Everywhere](https://www.acko.com/health-insurance/cashless-everywhere/) · [ACKO — Excluded hospitals (published blacklist)](https://www.acko.com/health-insurance/excluded-hospitals/) · [ACKO — Cashless network hospitals](https://www.acko.com/gi/p/health/networkhospitals) — ***the confirming source for the unverified metro count — search by pin code***
- [IRDAI Master Circular on Health Insurance, 29 May 2024](https://irdai.gov.in/) — *1-hr pre-auth / 3-hr discharge / Cashless-Everywhere mandates*
- Framework: [study_plan.md](../../study_plan.md) · screening: [stage1_hard_filters.md](../../screening/stage1_hard_filters.md) · [stage2_shortlist.md](../../screening/stage2_shortlist.md)
- Benchmarks: [Care Supreme M3](../care_supreme/module3_claims.md) · [SBI Super Health M3](../sbi_super_health/module3_claims.md) · [HDFC Optima Secure+ M3](../hdfc_optima_secure/module3_claims.md) · [Bajaj Health Guard M3](../bajaj_health_guard/module3_claims.md)

---

**Module 3 score (1–5): 3.5 / 5**

**Rationale.** On the two questions a policyholder actually experiences — **"will they pay, and will they pay quickly?"** — Acko performs **better than any finalist except HDFC and Bajaj**. It settles **95.75% of claims (3-yr 96.50%, against a 91.22% industry average)**, generates **15.58 complaints per 10,000 claims versus an industry 27.06 — 2.7× better than finalist Care Supreme's 42.00** — and, decisively on the framework's sharpest speed test, pays **99.98% of claims within three months, the best record of any private general insurer**, meaning effectively **no slow tail**. The wording backs this with **contractual** obligations rather than marketing: a **15-day settlement TAT**, **2%-above-bank-rate penal interest**, an explicit **document-delay condonation**, and an unusually pragmatic deficiency rule letting Acko **pay the valid portion of a claim rather than hold the whole thing**. Its **late-intimation clause is a discretion to deny rather than Care's claim-defeating condition precedent** — and converts to a proportionate **co-pay** if the §3.3.4 option is held, the fairest construction in this study. It also **publishes its excluded-hospitals list**, and its network-count dispersion (~1.24×) is the narrowest of any insurer tested.

It cannot score higher because **the rupee question remains genuinely open, and the network is unverifiable where this buyer lives.** Acko returns **₹57.82 per ₹100 of premium against a private-general peer benchmark of ₹77.50 — a ~20-point shortfall — and the peer-segment correction that exonerated Care Supreme does NOT exonerate Acko** (Care was 3.5 points below its own segment; Acko is nearly twenty). The most credible explanation — a **young, cheaply-priced, fast-growing digital book that structurally under-claims** — fits both the 27-point single-year collapse and the absence of complaints, but it is **inference, not evidence**, and the age-mix data that would prove it is unpublished. Meanwhile **M1 and M2 identified concrete mechanisms that narrow payouts** (restore excluding the same illness, the unresolved Base-SI-only per-claim cap, the tobacco-cancer exclusion, non-payables unless the waiver is bought). Add that the **metro-concentration test cannot be run at all**, that the **1-hour/3-hour IRDAI TATs are absent from the wording**, and that **Acko does use TPAs despite the "in-house" marketing**, and the fair verdict is: **the fastest, least contentious claims service in the study, attached to the smallest rupee payout in the study — for reasons that are probably structural but remain unproven.**
