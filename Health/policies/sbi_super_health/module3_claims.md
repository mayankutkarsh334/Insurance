# Module 3 — Claims & Servicing

_Source: IRDAI FY24-25 data + **Super Health policy wording** (UIN **SBIHLIP24141V022324**), Claims Procedure section + CIS. Files in `resources/`._
_Profile studied: **Individual (single adult), age 26, metro tier-1**_
_**Weight: 25% — the highest.** A plan that won't pay is worthless regardless of features._

> **Plain-English intro.** This module answers three questions: **"Will they pay? Will they pay fast? Can I go cashless near my home?"** The jargon you need:
> - **ICR (Incurred Claims Ratio)** = of every ₹100 of premium collected, how much went back out as claims. **High (85%+) = generous.** Low (60%) = either stingy or a young, cheap book. **Never read it alone.**
> - **CSR (Claim Settlement Ratio)** = what % of claims they actually paid, **counted as claims** (not rupees).
> - **Cashless** = the insurer pays the hospital directly, so you don't front the money. **Only works at "network" hospitals** — which is why the count near *you* matters more than the national total.
>
> **This module carries both of SBI's carry-forward flags** from screening. Both are resolved below — **one favourably, one against.**

---

## Claims track record

| Metric | Value | Trend |
|--------|-------|-------|
| **Incurred Claim Ratio (ICR)** | **FY24-25: 87.86%** · FY23-24: 88% · FY22-23: 74% | **3-yr avg 81.23%** — ⚠️ but the full historic range is **61%–88%**, i.e. **volatile**. FY24-25's 87.86% sits **above the industry health ICR of 86.98%** |
| **Claim repudiation / rejection rate** | **unverified for SBI specifically.** Industry FY24-25: **8% repudiated** (87% settled, 5% pending) across 3.26 crore health claims | *Confirming source: [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports), company-wise claims disposal table* |
| **Complaint ratio (per 10k policies)** | ⚠️ **Denominator corrected — the available figure is per 10,000 CLAIMS, not policies:** **FY24-25: 14.66** · FY23-24: 23.28 · FY22-23: 23.59 | ✅ **Improving sharply — down 38% in two years.** 3-yr avg 20.51. *(Per-10k-**claims** is the framework's preferred denominator — Bajaj M3 dimension. See note below.)* |
| **Grievance disposal %** | **unverified** | *Confirming source: [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports) grievance-disposal table / SBI General [public disclosures](https://www.sbigeneral.in/about-us/public-disclosure)* |
| **Cashless settlement %** | **unverified.** SBI **does participate in "Cashless Everywhere"** (cashless extended to select non-network hospitals, subject to conditions) | *Confirming source: General Insurance Council Cashless Everywhere data / SBI disclosure* |
| **Health claims payout ratio (insurer)** | **CSR by count: FY24-25 96.13%** · FY23-24 98.08% · FY22-23 94.20% · **3-yr avg 96.14%** — vs **industry ~87.6%** | ✅ **Consistently ~8.5 pts above industry, all three years.** Cross-checks *coherently* with the high ICR: SBI both **approves** more claims and **pays out** more rupees than peers |
| **Payout by AMOUNT vs CSR by COUNT** | ⚠️ **UNVERIFIED — not published by SBI, IRDAI or any aggregator found.** The 96.13% CSR is **by count only** | ⚠️ **The framework's sharpest test (HDFC M3) cannot be run.** A 96% count-CSR is compatible with material per-bill disallowances (R&C trims, non-payables). **Partial mitigant:** SBI's **Claims Shield** makes List-I non-payables payable (M1), removing one of the two big deduction channels by contract. *Confirming source: IRDAI company-wise claims-paid-by-amount, or an insurer disclosure of average deduction per settled claim* |

### 🚩 Stage-2 ICR data was stale — and the ranking has **inverted**

| Insurer | Stage-2 screening (used to rank) | **IRDAI FY24-25 actual** | Change |
|---------|:-------------------------------:|:------------------------:|--------|
| **SBI General** | 82.2% | **87.86%** | ⬆️ **now above industry** |
| **Bajaj Allianz** | **87% — "claims-reliability leader"** | **74.59%** | ⬇️ **collapsed −12.4 pts** |
| HDFC ERGO | — | 89.47% | — |
| Care Health | 64.5% | 65% | ↔️ confirmed low |
| Niva Bupa | — | 61.22% | — |
| **Industry (health)** | — | **86.98%** | (down from 88.15%) |

> **Finding with study-wide consequences.** Stage 2 shortlisted **Bajaj at rank 3 explicitly as the "claims-reliability leader (ICR 87%)"**. On FY24-25 IRDAI data **Bajaj's health ICR is 74.59%** and **SBI's is 87.86%** — **the two have swapped places.** SBI, not Bajaj, is now the more generous payer of the two. This does not by itself re-rank the study (ICR is blunt, and Bajaj may simply be pricing better), but **the stated premise of Bajaj's shortlisting is no longer true** and must be revisited in Bajaj's M3 and at the decision tree. → *New framework dimension #4 below.*

> **Reading SBI's numbers honestly.** High ICR alone could mean "generous" *or* "mispriced". Triangulated against **CSR 96.13% (well above industry)** and a **complaint ratio falling 38%**, the coherent reading is **genuinely policyholder-friendly claims behaviour**, not distress. The counter-signal is **volatility** — an ICR that has ranged **61%→88%** is not a settled book, and commentary specifically notes *"sudden spikes above 85%, such as those seen in Bajaj General and SBI General, require monitoring over longer periods."*

---

## Network

> **This is where the carry-forward flag lands.** Stage 2 gave SBI **Network = 5/5** on an **unverified raw count of ~18,000**, explicitly pending this check.

| Metric | Value |
|--------|-------|
| **Network hospital count (raw)** | 🚩 **UNVERIFIABLE — no official figure exists.** SBI General's own network page **publishes no count at all** (only a search tool + *"the network list is dynamic and subject to change"*). Third-party counts span a **2.8× range**: PolicyBazaar **19,169** · Ditto **16,600+** · RenewBuy **7,500+** · Turtlemint/PolicyX **6,704** · Stage-2 screening **~18,000** |
| **Per-district density (÷~780)** | **Cannot be computed reliably** — the input is unusable (range implies **8.6 to 24.6 per district**). ⚠️ **SBI does not appear in the study's top-5 per-district density table at all**, which is led by **HDFC ERGO 13,600 (≈17.4/district)** > Aditya Birla ≈15.8 > Bajaj ≈15.6 > Acko ≈14.7 > Royal Sundaram ≈12.8. **Had SBI's ~18,000 been real and comparable, it would have topped that table at ≈23/district — it is absent.** |
| **Your city's top hospitals in-network?** | ⚠️ **Metro count, same-source comparison (PolicyBazaar, Mumbai):** **SBI 434** vs **HDFC ERGO 520** → **SBI has 17% FEWER cashless hospitals in the buyer's metro**, despite claiming **33% MORE nationally** (19,169 vs 14,431). **Metro concentration: SBI 2.26% of network in Mumbai vs HDFC 3.60%.** Presence of Apollo/Fortis/Max/Manipal specifically: **unverified** — *confirming source: [SBI General hospital locator](https://www.sbigeneral.in/contact-us/cashless-hospitals-networks), searched for the buyer's actual pin code* |

```
Mumbai cashless hospitals (PolicyBazaar, same source, same date)
  HDFC ERGO  ████████████████████████  520      (3.60% of its 14,431 national)
  SBI General ███████████████████      434      (2.26% of its 19,169 national)
                                       ↑ 17% FEWER, despite +33% MORE nationally
```

> ### 🚩 **Carry-forward flag RESOLVED — AGAINST SBI. Network 5/5 is not supportable.**
> Two independent lines of evidence agree: **(1)** SBI is **absent from the per-district density leaderboard** that HDFC/AB/Bajaj lead; **(2)** in the buyer's own metro, SBI has **fewer** cashless hospitals than the benchmark despite a larger claimed national network. The consistent explanation: **SBI's network is broad but thin** — spread wide across districts (plausibly tracking SBI's rural/semi-urban bank-branch footprint) rather than dense in tier-1 metros. **For an individual, age 26, metro tier-1, "largest network" is not a real advantage — it is a national-average artefact.**
>
> **Revised network assessment: ~3/5, not 5/5.** In absolute terms 434 Mumbai hospitals is still ample cover, and **Cashless Everywhere** partially closes any gap — so this is a **downgrade, not a disqualification**. Stage 2's rank-4 placement rested partly on the network 5; **the decision tree must re-run SBI's Stage-2 total with network at ~3** (26/30 → ~24/30).

---

## Claim mechanics (from wording)

| Item | Detail |
|------|--------|
| **Cashless pre-auth deadline (planned / emergency)** | **Planned: at least 72 hours PRIOR to admission** · **Emergency: within 24 hours of hospitalisation** ⚠️ **Stricter than the benchmark** — HDFC Optima requires 48h for planned. ⚠️ **Aggregators (Ditto, InsuranceDekho) state "48 hours" for SBI — the binding wording says 72. Wording wins.** Reimbursement route: intimate **within 48h of admission or before discharge, whichever is earlier** |
| **Reimbursement intimation & doc windows** | Documents to be submitted **within 30 days of discharge**. ✅ **Condonation clause:** late intimation is excused *"on merits where the delay has been proved to be for reasons beyond the claimant's control"* |
| **Settlement TAT** | ✅ **Settle or reject within 15 days** of receipt of claim submission (wording G.A.c) — **matches the HDFC Optima benchmark**. ⚠️ Aggregators claim "30 days" — they appear to have **misread the 30-day *document-submission* deadline as the settlement TAT**. **Wording binds: 15 days.** Pre-authorisation, once issued, is **valid 15 days** |
| **Penal interest for delay** | ✅ **2% above the RBI bank rate**, payable from date of claim submission to date of payment (G.A.c.ii) — matches benchmark, and is a **contractual**, not discretionary, obligation |
| **TPA vs in-house adjudication** | ✅ **IN-HOUSE claims team for retail health** (TPAs used mainly for group business). Claims address: SBI General, Westport, Baner, Pune | 
| **IRDAI 2024 mandate delivery (cashless-anywhere, 1hr/3hr)** | **On paper: fully compliant** — the CIS commits to *"TAT for pre-authorization of cashless facility — **within 1 hour**"* and *"TAT for cashless final bill settlement — **within 3 hours**"*, and SBI participates in **Cashless Everywhere**. ⚠️ **Real-world delivery against these: unverified** — the framework explicitly asks for policyholder/ombudsman evidence rather than brochure claims. *Confirming source: IRDAI/Ombudsman award data; General Insurance Council Cashless Everywhere utilisation stats* |
| **Cashless-outside-India / 100% cashless** | **No cashless abroad.** Medical Treatment Abroad (C.24, Platinum/Infinite only) is **reimbursement-only**, needs India diagnosis, planned treatment, 36-month wait. Several domestic covers are also **reimbursement-only**: Domiciliary (C.7), Child Vaccination, Medical Treatment Abroad, OPD. ✅ **Home Health Care is cashless-only** (pre-auth, *not* available on reimbursement) |
| **Network discretion clause** *(NEW ROW — Rule 3)* | ⚠️ *"We reserve the right to **modify, add or restrict any Network Provider** for Cashless Facilities at **Our sole discretion**"* + **Excluded Providers (Code-Excl 11)** — treatment at a blacklisted hospital is **not admissible at all** (only stabilisation paid in emergencies). **The network you buy is not the network you keep** |

---

## 🚩 The second carry-forward flag — *"newer product: is the claims record real, or just projected?"*

**Status: PARTIALLY resolved — and it cannot be fully resolved by anyone.**

| Question | Finding |
|----------|---------|
| Is Super Health actually new? | **Less new than assumed.** The product line traces to UIN **SBIHLIP23050V012223** (a 2022-23 filing); the current **SBIHLIP24141V022324** is a **2024 re-filing**, not a first launch. So the product has **~3 years of market history**, not zero. |
| Does a **product-level** claims record exist? | ❌ **No — and it cannot.** **IRDAI publishes ICR/CSR/complaints at INSURER level only, never per product/UIN.** No regulator, insurer or aggregator publishes Super-Health-specific claims data. |
| So what is the 87.86% ICR / 96.13% CSR evidence *of*? | **SBI General the company** — across motor, fire, group health, retail health, everything. It is a **strong but indirect proxy** for how a Super Health claim will be handled. It is **not** direct evidence about this product. |

> **Honest verdict:** the flag asked us to *"verify claims experience is real, not just projected."* We can verify that **the insurer's** claims experience is real, strong and improving. We **cannot** verify Super Health's own, and **no amount of research will** — the data does not exist at product granularity. The mitigating facts are that the product is ~3 years old (not a launch), settlement is handled **in-house by the same team** whose insurer-level record we *can* see, and the claim-payment obligations (15-day TAT, penal interest) are **contractual in the wording**, not marketing. **The flag stays permanently open at "proxy-verified" and must be stated as such in the decision tree.**

---

## 🆕 NEW DIMENSIONS discovered in this module *(Rule 3)*

### 1. Metro-concentration ratio — city count ÷ national count *(→ new bullet in study_plan M3; row above)*
The framework already prefers **per-district density over raw count** — but per-district is still a **national average**, and it hid this result. The sharper test for a metro buyer: **take ONE source, and compare the absolute count in *your city* and that city's *share* of the national network, across finalists.** SBI: **434 in Mumbai = 2.26%** of its network. HDFC: **520 = 3.60%**. SBI's network is **broad but thin** — a bigger national number that delivers **fewer hospitals near the buyer**. → **New check: "What is the finalist's absolute count in MY city, and what share of its national network is that? A larger national network can still mean fewer cashless options at home."**

### 2. Network-count source dispersion as a data-quality red flag *(→ new bullet in study_plan M3)*
Published counts for SBI span **6,704 → 19,169 (2.8×)**, and **SBI publishes no official figure**. When the spread is that wide and unaudited, **the count is not a metric — and any score resting on it is unsound** (as Stage-2's 5/5 was). → **New check: "Before scoring network size, check the spread across independent sources and whether the insurer publishes an official count. Treat a wide spread, or a refusal to publish, as a finding in itself — not as licence to pick the biggest number."**

### 3. Cashless-network discretion clause — the network is revocable *(→ new bullet in study_plan M3; row above)*
The wording lets SBI *"modify, add or **restrict** any Network Provider… at Our sole discretion"*, and **Excluded Providers (Excl 11)** makes a blacklisted hospital's claim **wholly inadmissible** (bar emergency stabilisation). **The hospital you chose the policy for can be removed from the network mid-hold, unilaterally.** Over a 40-year horizon this matters more than the count. → **New check: "Is the network a contractual schedule or a unilaterally revocable list? Is there an excluded-provider blacklist, and where is it published?"**

### 4. Screening-stage data goes stale — re-pull IRDAI at module time *(→ new bullet in study_plan, Phase-3 / screening)*
Stage 2 ranked finalists on ICRs (**Bajaj 87%, SBI 82.2%**) that FY24-25 IRDAI data **contradicts and inverts** (**Bajaj 74.59%, SBI 87.86%**). Bajaj's shortlist rationale — *"claims-reliability leader (ICR 87%)"* — **is no longer true**. → **New check: "Re-pull company-wise IRDAI data at Module-3 time for every finalist. Screening ICRs may be a year or more stale, and a stale ICR can invert the very rationale that shortlisted a plan. Where it does, say so and flag the affected plan's module."**

---

## Brochure-vs-wording check *(Rule 2)*

⚠️ **Two conflicts found — both aggregator-vs-wording, both resolved in favour of the wording, and they cut in opposite directions:**

| Item | Aggregators say | **Binding wording says** | Effect on buyer |
|------|-----------------|--------------------------|-----------------|
| **Planned cashless pre-auth** | 48 hours prior | **72 hours prior** | ⚠️ **WORSE** — a buyer relying on aggregator guidance could miss the notice window on a planned admission |
| **Settlement TAT** | "within 30 days" | **15 days** (+2% above bank rate penal interest) | ✅ **BETTER** — aggregators appear to have misread the 30-day *document-submission* deadline as the settlement TAT |

✅ **No conflict between SBI's own documents.** The wording, CIS and prospectus agree on the 1-hour pre-auth / 3-hour discharge TAT, the 15-day settlement, and penal interest. As in M1 and M2, **SBI's own documentation is internally consistent** — the errors here are third-party.

---

## Sources

- [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports) — *industry health ICR 86.98%; 3.26 cr health claims, 87% settled / 8% repudiated / 5% pending; SAHI combined ICR 68.06%; PSU general ICR 99.84%. **Company-wise claims-by-ageing and claims-by-amount tables not retrieved — the two unverified metrics above***
- [Business Standard — "Paying claims or pushing back? What Irdai data reveals about insurers"](https://www.business-standard.com/finance/personal-finance/paying-claims-or-pushing-back-what-irdai-data-reveals-about-insurers-126010100580_1.html) — *SBI General health ICR **87.86%** FY24-25; peer ICRs (HDFC 89.47%, Bajaj 74.59%, ICICI 71%, Care 65%, Niva 61.22%); "spikes above 85%… require monitoring"*
- [Ditto — SBI General Health Insurance Claim Settlement Ratio](https://joinditto.in/articles/health-insurance/sbi-health-insurance-claim-settlement-ratio/) — *CSR 94.20 / 98.08 / **96.13**%; complaints **per 10,000 claims** 23.59 / 23.28 / **14.66**; 3-yr ICR avg 81.23%; network "16,600+"*
- [PolicyBazaar — SBI General network hospitals](https://www.policybazaar.com/network-hospitals/sbi-general-network-hospitals/) (**19,169** national) · [SBI General, Mumbai](https://www.policybazaar.com/network-hospitals/sbi-general-hospitals-maharashtra-mumbai/) (**434**) · [HDFC ERGO network](https://www.policybazaar.com/network-hospitals/hdfc-ergo-network-hospitals/) (**14,431** national) · [HDFC ERGO, Mumbai](https://www.policybazaar.com/network-hospitals/hdfc-ergo-hospitals-maharashtra-mumbai/) (**520**) — *the same-source metro comparison that resolves the network flag*
- [Turtlemint — SBI network hospitals](https://www.turtlemintinsurance.com/health-insurance/sbi/network-hospitals/) (**6,704**) · [RenewBuy](https://www.renewbuy.com/health-insurance/network-hospitals/sbi-general) (**7,500+**) — *the low end of the 2.8× dispersion*
- [SBI General — official network page](https://www.sbigeneral.in/contact-us/cashless-hospitals-networks) — ***publishes no count***; *"network list is dynamic and subject to change"*
- [Super Health Insurance — Policy Wording, UIN SBIHLIP24141V022324](resources/policy_wording_super_health.pdf) — *Claims Procedure (intimation 24h/72h/48h, pre-auth validity 15 days, docs 30 days, condonation, cashless conditions, network discretion); G.A.c settlement 15 days + penal interest 2% above bank rate; Excl 11 Excluded Providers*
- [Super Health Insurance — Customer Information Sheet](resources/customer_information_sheet_cis.pdf) — *1-hour pre-auth / 3-hour cashless final-bill TAT; grievance escalation ladder (Customer Care → GRO → Bima Bharosa → Ombudsman)*
- [Ditto — SBI Cashless Health Insurance](https://joinditto.in/articles/health-insurance/sbi-cashless-health-insurance/) — *in-house retail claims team; Cashless Everywhere participation; the "48-hour" pre-auth claim contradicted by the wording*
- [IRDAI Master Circular on Health Insurance, 29 May 2024](https://irdai.gov.in/) — *the 1-hr pre-auth / 3-hr discharge / cashless-everywhere mandates*
- Framework: [study_plan.md](../../study_plan.md) · carry-forward flags: [stage2_shortlist.md](../../screening/stage2_shortlist.md) · density image: [screening/img.png](../../screening/img.png)
- Benchmarks: [HDFC Optima Secure+ M3](../hdfc_optima_secure/module3_claims.md) · [Bajaj Health Guard M3](../bajaj_health_guard/module3_claims.md)

---

**Module 3 score (1–5): 3.5 / 5**

**Rationale.** The **insurer-level settlement evidence is genuinely strong and internally coherent**: a **96.13% CSR (3-yr avg 96.14%, ~8.5 points above the ~87.6% industry)**, an **87.86% ICR above the 86.98% industry average** and far above the standalone health insurers (Care 65%, Niva 61%), a **complaint ratio falling 38% in two years to 14.66 per 10,000 claims**, an **in-house retail claims team** (no TPA friction), and contractual — not marketing — commitments in the wording to a **15-day settlement with 2%-above-bank-rate penal interest**, plus IRDAI-compliant 1-hour/3-hour cashless TATs and Cashless Everywhere. On "**will they pay?**" SBI reads better than Stage 2 assumed — and notably **better than Bajaj**, whose ICR has collapsed to 74.59%, inverting the premise on which Bajaj was shortlisted as "claims-reliability leader".

It scores only 3.5 because the module's other two questions land badly. On "**can I go cashless near me?**" the **carry-forward flag is confirmed against SBI**: there is **no official network count**, third-party figures span a **2.8× range (6,704–19,169)**, SBI is **absent from the per-district density leaderboard**, and — decisively — in the buyer's own metro SBI has **434 cashless hospitals versus HDFC's 520 (−17%) despite claiming 33% more nationally**. The network is **broad but thin**; **Stage-2's Network = 5/5 is not supportable and should be ~3**, taking SBI's screening total from 26/30 to ~24/30. On "**will they pay fast, and how much of my bill?**" the framework's two sharpest tests — the **claims-paid-by-ageing distribution** and the **payout ratio by amount** — are **unverifiable for every source found**, so a 96% count-CSR cannot be checked against rupees actually paid. Finally, the **product-level claims record does not exist and cannot** (IRDAI reports by insurer, never by UIN), so the second flag closes only at **"proxy-verified"**. Add **ICR volatility (61%–88%)** and a **72-hour planned pre-auth window stricter than the benchmark's 48**, and the honest read is: **a strong payer, an unproven product, and a network that is measurably weaker than advertised where this buyer actually lives.**
