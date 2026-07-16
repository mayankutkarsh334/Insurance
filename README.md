# Insurance Study

## Goal
Select the best **individual health insurance policy** for long-term protection — a policy that actually pays claims, has minimal fine-print traps, and is renewable for life at a fair premium.

## Approach
A structured, data-driven screening and deep study process — not relying on agent tips, ads, or "best plan 2026" listicles. Same methodology as the [Investment](../Investment) Mutual Fund study: screen a large universe down to a shortlist, then study each finalist across a fixed set of modules and score them.

## Profile (the study is tuned to this)
| Parameter | Value |
|-----------|-------|
| Type | Individual (single life, own sum insured) |
| Horizon | Lifelong (renew every year, never lapse) |
| Priority order | Claims reliability > Coverage > Exclusions > Cost |

> Health insurance is bought once and renewed for decades. The variable that matters most is **whether they pay when you claim**, not the lowest premium.

## Folder Structure

```
Insurance/
├── README.md                        ← This file
└── Health/
    ├── README.md                    ← Category overview, data sources, reliability notes
    ├── screening/                   ← Step-by-step insurer/plan elimination
    │   ├── methodology.md           ← What variables matter and why (for an individual)
    │   ├── stage1_hard_filters.md   ← Universe → shortlist via deal-breaker filters
    │   └── stage2_shortlist.md      ← Shortlist → 5 finalists for deep study
    ├── study_plan.md                ← 6-module deep-study framework + order + scoring rubric
    └── policies/                    ← One folder per finalist (created after screening)
```

## Study Flow
1. **Screening** (`Health/screening/`) — apply selection criteria to cut the universe to 5 finalists.
2. **Deep study** (`Health/policies/<plan>/`) — 6 modules per finalist.
3. **Score & decide** — weighted rubric in `study_plan.md`.
