# Stage 2 — Comparative Shortlisting

**Goal:** take the ~10 plans that survived Stage 1 hard filters and cut to the **5 finalists** that go into full 6-module deep study.

Unlike Stage 1 (binary pass/fail), Stage 2 is **comparative** — plans are scored relative to each other on the variables that separate a good plan from a great one.

## Scoring dimensions (1–5 each)

| Dimension | 5 (Excellent) | 1 (Weak) | Source |
|-----------|---------------|----------|--------|
| **Claims track record** | High ICR in healthy band, low complaints, low repudiation, high cashless % | Poor on all | IRDAI report |
| **Coverage richness** | No room cap + restoration + high NCB + consumables + modern treatments | Bare-bones | Wording |
| **Waiting periods** | PED ≤ 2yr, short specific-disease waits | PED 4yr, long waits | Wording |
| **Network quality** | Wide network incl. top hospitals in your city | Thin / poor local network | Insurer |
| **Value for premium** | Rich cover at competitive premium; gentle age-loading | Expensive for what you get | Quote engine |
| **Insurer stability** | High solvency, long track record, strong promoter | Marginal | IRDAI / financials |

---

# Stage 2 Results — Run July 2026

**Inputs:** 10 plans that passed Stage 1. Scored 1–5 on each dimension using IRDAI FY2024-25 claims/complaint data, brochure coverage features, published network-hospital counts, and indicative premiums (25yo, ₹15L, Delhi).

**Key data used:**
- Network size: SBI ~18,000 · Aditya Birla ~16,500 · HDFC ERGO ~16,000 · Bajaj ~12,600 · Care ~11,400 (others moderate)
- Complaints: HDFC, Bajaj, Aditya Birla **below** industry average (good); Care & Niva Bupa **above** average (poor)
- Premium (₹15L @25, Delhi): Optima Secure+ ~₹13,459 · Care Supreme ~₹15,111
- Coverage standouts: Niva ReAssure Booster+ carry-forward 5x · Aditya Birla consumables default + bonus to 500% · HDFC 2x day-1 + infinite bonus
- Weak spots: ICICI Elevate base has room-rent cap + consumables via rider; Star has zonal co-pay on some plans

## Scoring table

| Plan | Insurer | Claims | Coverage | Waiting | Network | Value | Stability | **Total /30** | Rank |
|------|---------|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Optima Secure+ | HDFC ERGO | 5 | 5 | 4 | 5 | 5 | 5 | **29** | 🥇 1 |
| Activ One (MAX) | Aditya Birla | 4 | 5 | 4 | 5 | 5 | 4 | **27** | 🥈 2 |
| Health Guard / Global Health | Bajaj Allianz | 5 | 4 | 4 | 4 | 4 | 5 | **26** | 🥉 3 |
| Super Health | SBI General | 4 | 4 | 5 | 5 | 4 | 4 | **26** | 4 |
| Care Supreme | Care Health | 3 | 4 | 5 | 4 | 4 | 4 | **24** | 5 |
| Elevate | ICICI Lombard | 4 | 3 | 4 | 4 | 4 | 5 | **24** | 6 (reserve) |
| ReAssure 2.0 | Niva Bupa | 2 | 5 | 4 | 3 | 4 | 5 | **23** | 7 (reserve) |
| ProHealth Prime | ManipalCigna | 4 | 4 | 4 | 3 | 4 | 3 | **22** | 8 |
| Medicare Premier | Tata AIG | 4 | 3 | 4 | 3 | 3 | 4 | **21** | 9 |
| Comprehensive / Superstar | Star Health | 3 | 3 | 4 | 4 | 3 | 4 | **21** | 10 |

## Tie-break at rank 5 (Care 24 vs ICICI Elevate 24)
Both scored 24. **Care Supreme wins the finalist slot on diversity grounds:** ICICI Elevate's profile (strong-insurer stability, but base room-rent cap + consumables rider) overlaps the stability strength HDFC/Bajaj already bring, while its coverage is the weakest of the tie. Care Supreme adds a genuinely distinct profile to the study set — a best-value SAHI with the shortest PED wait (2yr) **and** a low-ICR question worth interrogating in Module 3. **ICICI Elevate is held as first reserve.**

## Output: the 5 finalists

| # | Finalist plan | Represents (diversity role) | Folder |
|---|---------------|------------------------------|--------|
| 1 | HDFC ERGO **Optima Secure+** | Benchmark all-rounder — reference frame | `policies/hdfc_optima_secure/` |
| 2 | Aditya Birla **Activ One MAX** | Coverage + value maximiser | `policies/aditya_birla_activ_one/` |
| 3 | Bajaj Allianz **Health Guard / Global Health** | Claims-reliability leader (ICR 87%) | `policies/bajaj_health_guard/` |
| 4 | SBI General **Super Health** | Largest network + shortest waiting + value | `policies/sbi_super_health/` |
| 5 | Care Health **Care Supreme** | Best-value SAHI — low-ICR stress test | `policies/care_supreme/` |

**Reserves:** ICICI Lombard **Elevate** (rank 6), Niva Bupa **ReAssure 2.0** (rank 7) — promote if a finalist is disqualified during deep study.

> **Carry-forward flags into deep study:**
> - **Care Supreme (M3):** ICR 64.5% + above-average complaints — is this a young book or a stingy culture?
> - **SBI Super Health (M3/M5):** strong on paper but a newer product — verify claims experience is real, not just projected.
> - **SBI Super Health (M3 — network):** network score of 5 rests on an **unverified raw count (~18,000)**. Per the network-density image (HDFC/AB/Bajaj lead per-district; SBI not in top 5), **verify SBI's real per-district density and whether your city's top hospitals are in-network** before trusting the score. Score retained pending this check (user decision, Jul 2026).
> - **Bajaj (M1):** confirm whether "Global Health Care" (international) or "Health Guard" is the right variant for a domestic individual buyer.

> **Note on network scoring:** Stage 2 network scores used raw brochure counts. The user's density image shows deduplicated per-district figures are the better metric (HDFC ≈17.4 > AB ≈15.8 > Bajaj ≈15.6 per district). HDFC/AB/Bajaj scores are confirmed under both; only SBI's is in question (see flag above).
