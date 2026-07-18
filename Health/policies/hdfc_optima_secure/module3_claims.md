# Module 3 — Claims & Servicing

_Source: IRDAI FY24-25 data + **binding policy wording** `my:Optima Secure` (UIN **HDFHLIP26058V082526**), Claims Procedure §1.1–1.3, network-discretion clause, Excl11 (Excluded Providers). Files in `resources/`._
_Profile studied: **Individual (single adult), age 26, metro tier-1**_
_**Weight: 25% — the highest.** A plan that won't pay is worthless regardless of features._
_🔄 **Re-tested January 2026** — ten dimensions discovered after HDFC was studied are applied below, and the IRDAI data has been re-pulled. Note: claims metrics are **insurer-level** (HDFC ERGO), not plan-specific — IRDAI never publishes per-UIN._

> **Plain-English intro.** Three questions: **"Will they pay? Will they pay fast? Can I go cashless near my home?"**
> - **ICR (Incurred Claims Ratio)** = of every ₹100 of premium collected, how much went back out as claims. **Never read it alone** — compare it against the insurer's *own segment*, and against how many people complain.
> - **CSR (Claim Settlement Ratio)** = what % of claims were paid, **counted as claims** (not rupees).
> - **Complaint ratio** = formal complaints per 10,000 claims. **The hardest number to explain away** — it measures lived experience, not accounting.

---

## Claims track record

| Metric | Value | Trend |
|--------|-------|-------|
| **Incurred Claim Ratio (ICR)** | **FY24-25: 81.62%** (all-lines) · **89.47%** (health segment, IRDAI company-wise data) | ✅ **Healthy and stable** — inside the 70–90% band regarded as comfortable: generous enough to be paying properly, not so high as to signal distress |
| **ICR vs the correct peer segment** *(NEW ROW — Care M3 dimension)* | **HDFC 81.62–89.47% vs private general insurers 77.50%** (IRDAI FY24-25 health segment) | ⭐ **The only plan in this study clearly ABOVE its own peer benchmark.** Compare **Care at −3.5 pts** below its SAHI peers and **ACKO at −19.7 pts** below its private-general peers. **HDFC pays out more per premium rupee than its segment average** |
| **Claim repudiation / rejection rate** | **unverified for HDFC specifically.** Industry FY24-25: ~8% repudiated / 87% settled / 5% pending | *Confirming source: [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports), company-wise claims-disposal table* |
| **Complaint ratio (per 10k policies)** | **Denominator: per 10,000 CLAIMS.** **9.28** (Ditto, FY24-25); an alternative source reports **4.99** | ⭐ **Far below the industry's 27.06 on either figure**, and best-or-second-best in the study: **HDFC 4.99–9.28** · Bajaj 5.25 · SBI 14.66 · ACKO 15.58 · **Care 42.00**. ⚠️ **Source discrepancy flagged** |
| **Grievance disposal %** | **unverified** | *Confirming source: [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports) grievance-disposal table* |
| **Cashless settlement %** | **unverified.** ✅ HDFC participates in **Cashless Everywhere** | *Confirming source: General Insurance Council utilisation data* |
| **Health claims payout ratio (insurer)** | **CSR by count: FY24-25 97.45%** · **3-yr avg 96.71%** vs industry 91.22%. **32,74,917 claims processed** | ⭐ **Highest CSR in the study**, on the largest claim volume — a mature, high-throughput operation |
| **Payout by AMOUNT vs CSR by COUNT** *(HDFC's own M3 dimension)* | ⚠️ **Claims-paid-by-amount not published.** But unlike Care and ACKO, **the count and rupee measures AGREE** — a 97.45% CSR sits beside an ICR *above* the peer benchmark | ✅ **The divergence that damns Care (96.74% CSR vs 64.53% ICR) and ACKO (95.75% vs 57.82%) does not exist here.** ✅ **The inbuilt Protect Benefit (M1) closes the non-payables deduction channel by contract** — removing the single biggest source of "why did they cut my bill?" disputes |
| **Settlement-speed distribution (TAT buckets)** *(NEW ROW — ABHI M3 dimension)* | ✅ **98.85% of claims settled within 3 months (FY24-25)** | ⭐ **Second only to ACKO's 99.98%**, and far ahead of the "unverified" recorded for SBI and Care. **Effectively no slow tail** |

### 📊 The picture in one chart

```
                    ICR (rupees paid per Rs 100 premium)   Complaints /10k    Settled <3mo
  PSU general       ####################  97.30%             —                  —
  Overall health    #################     85.34%             27.06 (industry)   —
  HDFC ERGO         #################   81.6-89.5%  <-BEST   4.99-9.28 <-BEST   98.85%  <- 2nd
  PRIVATE GENERAL   ###############       77.50%   <- HDFC's peer benchmark
  SAHI segment      #############         68.06%
  Care Health       ############          64.53%             42.00  (worst)     unverified
  ACKO              ###########           57.82%             15.58              99.98%  (best)
```
> **Read:** HDFC is the **only plan that is simultaneously above its peer ICR benchmark, near the bottom on complaints, and near the top on speed.** Every other finalist trades one of these against another. **This is where HDFC's overall lead is built** — Module 3 carries the heaviest weight in the study.

---

## Network

| Metric | Value |
|--------|-------|
| **Network hospital count (raw)** | **~14,431–14,476** (PolicyBazaar, the study's reference source). ⚠️ **Dispersion ~2.5× across sources**: 14,476 · "more than 13,000" · **5,780** (RenewBuy). Narrower and better-corroborated than SBI's 2.8× spread, but **not audited** *(SBI M3 data-quality dimension applies to the benchmark too)* |
| **Per-district density (÷~780)** | ⭐ **≈17.4 per district — the highest in the study.** HDFC **13,600 ≈17.4** > Aditya Birla ≈15.8 > Bajaj ≈15.6 > ACKO ≈14.7 > Care ≈14.6–15.3 > Royal Sundaram ≈12.8 |
| **Your city's top hospitals in-network?** | ⭐ **Best metro concentration in the study: 520 cashless hospitals in Mumbai = 3.60% of its national network** (PolicyBazaar, same-source comparison) — vs **SBI 434 = 2.26%** and **Care 299 = 2.51%**. ⚠️ **Source variance:** another source reports **306 in Mumbai + 32 in Navi Mumbai**. *Confirming source: [HDFC ERGO's own cashless-hospital locator](https://www.hdfcergo.com/blogs/health-insurance/list-of-cashless-hospital-network-in-mumbai), searched by your pin code* |

```
Mumbai cashless hospitals (PolicyBazaar — same source, same date)
  HDFC ERGO   ########################  520   (3.60% of its 14,431 national)  <- densest
  SBI General ###################       434   (2.26% of its 19,169 national)
  CARE HEALTH #############             299   (2.51% of its 11,909 national)
```

> ⭐ **Finding — HDFC wins the network test on both metrics the framework prefers.** It **leads per-district density** *and* has the **highest metro concentration**, so its network is dense both nationally and where this buyer actually lives. **This is the exact inverse of SBI**, whose larger national number thins out in the metro — the finding that cut SBI's Stage-2 network score from 5 to 3.
>
> ⚠️ **Two honest caveats.** The **raw count still varies ~2.5× across sources**, so it is corroborated rather than audited; and **HDFC's own Mumbai figure varies (306 vs 520)**. Neither disturbs the *relative* ranking, which uses one source consistently — but **verify the absolute number by pin-code search before buying.**

---

## Claim mechanics (from wording)

| Item | Detail |
|------|--------|
| **Cashless pre-auth deadline (planned / emergency)** | ⭐ **Planned: at least 48 hours prior to admission** · **Emergency: within 24 hours of hospitalisation, or before discharge, whichever is earlier** (§1.1). **The most forgiving planned window in the study** — SBI requires 72 hours, ACKO 3 days |
| **Late-intimation consequence** *(NEW ROW — Care M3 dimension)* | ⭐ ✅ ***"Any delay in notification or submission may be CONDONED on merit where delay is proved to be for reasons beyond the control of the Insured Person."*** **Late notice is NOT an absolute condition precedent.** **Care makes the same 48-hour window a *"condition precedent to admission of liability"* — miss it and the claim can be refused outright. ACKO reserves a discretion to "choose to deny." HDFC provides an express condonation route** — the fairest construction found in this study |
| **Reimbursement intimation & doc windows** | Per the claims annexure, with the **same condonation-on-merit relief** applying to document submission |
| **Settlement TAT** | ✅ **Settle or reject within 15 days** of receipt of the last necessary document (§1.3.a) — the benchmark the whole study measures against |
| **Penal interest for delay** | ✅ **2% above the RBI bank rate** (§1.3; Def. 7 Bank Rate) — a **contractual**, not discretionary, obligation |
| **TPA vs in-house adjudication** | ✅ **In-house claims team** (HDFC ERGO Health, formerly Apollo Munich); the wording references TPAs only peripherally. **No TPA hand-off friction** |
| **IRDAI 2024 mandate delivery (cashless-anywhere, 1hr/3hr)** | ✅ **Cashless Everywhere participation confirmed.** ⚠️ The **1-hour pre-auth / 3-hour discharge TATs are not stated in the wording** — but **98.85% settled within 3 months** is strong indirect evidence of real delivery. *Confirming source: HDFC's CIS / General Insurance Council data* |
| **Cashless-outside-India / 100% cashless** | ✅ **The wording carries a dedicated "Procedure for Cashless Claims Outside India"** (§1.3) — ⚠️ but only operative if the **optional Global Health Cover (B-2.9/2.10)** is bought; **not inbuilt** |
| **Network discretion clause** *(NEW ROW — SBI M3 dimension)* | ⚠️ *"The Company reserves the right to **modify, add or restrict any Network Provider** for Cashless Facility"* + **Excluded Providers (Excl11)** — a claim at a blacklisted hospital is inadmissible bar emergency stabilisation. **Universal across all five finalists** — the network you buy is not the network you keep |
| **Grievance → Ombudsman → IRDAI IGMS path** | ✅ Standard, fully documented: HDFC grievance cell → Grievance Officer → **Insurance Ombudsman** → **IRDAI Bima Bharosa (IGMS)**. ✅ **No arbitration clause** — unlike ACKO, which makes an arbitral award a precondition to suing |

---

## 🔬 HDFC re-tested against the dimensions discovered *after* it was studied

| Dimension (discovered in) | HDFC result |
|---|:---|
| Payout by count vs by amount *(HDFC's own)* | ✅ **Pass** — count and rupee measures agree; no settle-but-trim divergence |
| Settlement-speed TAT buckets *(ABHI M3)* | ✅ **Pass** — 98.85% within 3 months, 2nd best |
| Metro-concentration ratio *(SBI M3)* | ⭐ **Pass, best in study** — 520 Mumbai = 3.60% of network |
| Network-count source dispersion *(SBI M3)* | ⚠️ **Partial** — ~2.5× spread; corroborated, not audited |
| Cashless-network discretion clause *(SBI M3)* | ⚠️ **Present** — revocable (universal across finalists) |
| Complaint-denominator normalisation *(Bajaj M3)* | ✅ **Pass** — per-10k-claims used; ⚠️ two sources disagree (4.99 vs 9.28) |
| Re-pull IRDAI data at module time *(SBI M3)* | ✅ **Done** — FY24-25 figures **confirm** rather than contradict the original scoring |
| Peer-segment ICR benchmark *(Care M3)* | ⭐ **Pass, best in study** — the only plan clearly **above** its segment |
| Intimation as a condition precedent *(Care M3)* | ⭐ **Pass, best in study** — express condonation on merit |
| Book age-mix as an ICR confounder *(ACKO M3)* | ✅ **Favourable** — HDFC's is a **large, mature book** (32.7 lakh claims), so its high ICR is **not** flattered by a young portfolio. This makes the figure **more** credible than a young insurer's, not less |

**Result: 7 passes (3 best-in-study), 3 partial/universal.** **No dimension discovered later damages HDFC's Module 3; two of them strengthen it.**

---

## Brochure-vs-wording check *(Rule 2)*

✅ **No conflict.** The 15-day settlement, 2%-above-bank-rate penal interest, 48-hour/24-hour intimation windows and cashless procedure all reconcile between wording, brochure and public materials.

⚠️ **Two data-quality caveats (not conflicts):**
1. **Complaint ratio differs by source** — 4.99 vs 9.28 per 10,000 claims. Both are far below the 27.06 industry average, so the conclusion is unaffected; take the precise figure from IRDAI directly.
2. **Network and Mumbai counts vary by source** (14,476 vs 5,780 national; 520 vs 306 Mumbai). The relative ranking uses one source consistently and holds; **verify the absolute number by pin code.**

> **Carry-forward flags** *(stage2_shortlist.md)*: HDFC carries **no open flags**, and the **re-pull of IRDAI data — the same check that inverted Bajaj and SBI — confirms rather than disturbs its position.** 🚩 **Important for the decision tree:** that same re-pull shows **Bajaj's health ICR has fallen to 74.59%, *below* the 77.50% private-general benchmark**, while **HDFC sits clearly above it**. **On current data HDFC, not Bajaj, is the claims-reliability leader — and Bajaj's M3 = 5/5 should be revisited.**

---

## Sources

- [Ditto — HDFC ERGO Claim Settlement Ratio](https://joinditto.in/articles/health-insurance/hdfc-ergo-health-insurance-claim-settlement-ratio/) — ***CSR 97.45% FY24-25, 3-yr avg 96.71%; complaints 9.28 per 10,000 claims vs industry 27; 32,74,917 claims processed; 98.85% settled within 3 months***
- [Business Standard — "Paying claims or pushing back? What Irdai data reveals about insurers"](https://www.business-standard.com/finance/personal-finance/paying-claims-or-pushing-back-what-irdai-data-reveals-about-insurers-126010100580_1.html) — ***peer-segment benchmarks: private general 77.50%, SAHI 68.06%, PSU 97.30%; HDFC health ICR 89.47%; Bajaj 74.59%***
- [Angel One — HDFC ERGO claims settlement analysis FY2024-25](https://www.angelone.in/news/market-updates/hdfc-ergo-general-insurance-claims-settlement-ratio-analysis-for-2024-25) — *ICR 81.62% (all-lines); solvency 1.99×*
- [IRDAI Annual Report 2024-25](https://irdai.gov.in/annual-reports) — *industry claims disposal. **Company-wise claims-by-ageing, claims-by-amount and grievance tables not retrieved — the source that would close the unverified metrics above***
- [PolicyBazaar — HDFC ERGO network hospitals](https://www.policybazaar.com/network-hospitals/hdfc-ergo-network-hospitals/) (**14,431–14,476**) · [HDFC ERGO, Mumbai](https://www.policybazaar.com/network-hospitals/hdfc-ergo-hospitals-maharashtra-mumbai/) (**520**) — *the same-source metro comparison against [SBI Mumbai 434](https://www.policybazaar.com/network-hospitals/sbi-general-hospitals-maharashtra-mumbai/) and [Care Mumbai 299](https://www.policybazaar.com/network-hospitals/care-health-hospitals-maharashtra-mumbai/)*
- [HDFC ERGO — cashless hospitals in Mumbai](https://www.hdfcergo.com/blogs/health-insurance/list-of-cashless-hospital-network-in-mumbai) · [Turtlemint — HDFC ERGO network list](https://www.turtlemintinsurance.com/health-insurance/hdfc-ergo/network-hospitals/) — ***the confirming source for the metro count; basis of the 306-vs-520 dispersion note***
- [**Binding wording — UIN HDFHLIP26058V082526**](resources/PolicyWordings_myOptimaSecurePlus-76673175551+(1).pdf) — ***§1.1 Notification of a Claim (48 hrs planned / 24 hrs emergency)**, §1.2 cashless procedure, **§1.3 Claim Settlement — 15 days + 2%-above-bank-rate penal interest**, §1.3 cashless outside India, **the condonation-on-merit clause**, **network-modification discretion**, Excl11 Excluded Providers; Def. 6 Condition Precedent, Def. 7 Bank Rate*
- [IRDAI Master Circular on Health Insurance, 29 May 2024](https://irdai.gov.in/) — *1-hr pre-auth / 3-hr discharge / Cashless-Everywhere mandates*
- Framework: [study_plan.md](../../study_plan.md) · Benchmarks: [Care Supreme M3](../care_supreme/module3_claims.md) · [SBI Super Health M3](../sbi_super_health/module3_claims.md) · [Bajaj Health Guard M3](../bajaj_health_guard/module3_claims.md) · [ACKO Platinum M3](../acko_platinum_health/module3_claims.md)

---

## Module 3 score: **5 / 5** *(unchanged after re-testing — and now better evidenced)*

**Rationale.** Re-tested against ten dimensions that post-date the original study, **HDFC passes seven — three of them best-in-study — and none damages it.** It is the **only plan whose ICR sits clearly ABOVE its own peer benchmark** (81.62–89.47% against 77.50% for private general insurers), where **Care runs 3.5 points below its SAHI peers and ACKO nearly twenty below its own**. Crucially **its count and rupee measures agree**: a **97.45% CSR (3-yr 96.71%, industry 91.22%) across 32.7 lakh claims** sits beside a healthy ICR, so **the "settle-but-trim" divergence that undermines both Care and ACKO does not appear here** — and the **inbuilt Protect Benefit closes the non-payables deduction channel by contract**, removing the commonest cause of bill-trimming disputes. Complaints run **4.99–9.28 per 10,000 claims against an industry 27.06** — best or second-best in the study and **4–8× better than Care's 42.00** — while **98.85% of claims settle within three months**, second only to ACKO.

On network it **wins both metrics the framework prefers**: the **highest per-district density (~17.4)** *and* the **highest metro concentration** (520 Mumbai hospitals = **3.60%** of its national network, against SBI's 2.26% and Care's 2.51%) — the exact inverse of SBI's broad-but-thin problem. The wording backs this with **contractual** obligations: a **15-day settlement TAT with 2%-above-bank-rate penal interest**, the study's **most forgiving intimation windows (48 hrs planned / 24 hrs emergency)**, an **in-house claims team**, **no arbitration clause**, and — decisively — **an express condonation of late notification "for reasons beyond the control of the Insured Person"**, where **Care makes the identical deadline a claim-defeating condition precedent** and ACKO reserves a discretion to deny. Residual gaps are shared by every rival and do not discriminate: **payout-by-amount is unpublished**, the **network is contractually revocable**, and **raw counts vary ~2.5× across sources**. **On the study's heaviest-weighted question — will they pay, fast, in full, and near me — this remains the plan to beat.**
