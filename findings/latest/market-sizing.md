# Advocedu Market Sizing v2 (Conservative / Base / Upside)

_Last updated: 2026-03-25_

## Inputs (current best-available)
- IDEA-served students (ages 3–21): **7.5M** (NCES 2022–23)
- Public school enrollment: **49.5M** (NCES fall 2023)
- Section 504-only students: **~1.4M** (CRS reference to ED 2017–18; older proxy)

## Important caveats
- 504-only figure is older and should be refreshed before investor-final use.
- Not all eligible families are immediate buyers.
- Early GTM likely over-indexes on high-friction states and parent communities.

---

## Sizing logic
Define potential parent households in scope as:

`Households_in_scope = IDEA_students + 504_only_students`

Using current inputs:

`Households_in_scope ≈ 7.5M + 1.4M = 8.9M`

### Pricing assumptions (monthly)
- Essential: $5
- Plus: $10
- Pro: $25

Modeled blended ARPU scenarios:
- Conservative: **$7/mo**
- Base: **$10/mo**
- Upside: **$14/mo**

---

## TAM (top-down, subscription only)

`TAM = Households_in_scope × ARPU × 12`

- Conservative: 8.9M × $7 × 12 = **$748M ARR-equivalent**
- Base: 8.9M × $10 × 12 = **$1.07B ARR-equivalent**
- Upside: 8.9M × $14 × 12 = **$1.50B ARR-equivalent**

> Interpretation: this is total subscription spend ceiling if all in-scope households adopted.

---

## SAM (serviceable in next phase, U.S. near-term)
Assume near-term reachable share of in-scope households (channel + trust + product readiness), excluding full national saturation.

- Conservative SAM reach: **5%** of in-scope
- Base SAM reach: **10%**
- Upside SAM reach: **15%**

SAM households:
- Conservative: **445k**
- Base: **890k**
- Upside: **1.34M**

SAM subscription ARR:
- Conservative: 445k × $7 × 12 = **$37.4M**
- Base: 890k × $10 × 12 = **$106.8M**
- Upside: 1.34M × $14 × 12 = **$224.3M**

---

## SOM (24–36 month realistic execution target)
Model paying families under three execution levels:

- Conservative: **12,000** paying families
- Base: **30,000** paying families
- Upside: **75,000** paying families

SOM subscription ARR:
- Conservative: 12,000 × $7 × 12 = **$1.0M ARR**
- Base: 30,000 × $10 × 12 = **$3.6M ARR**
- Upside: 75,000 × $14 × 12 = **$12.6M ARR**

---

## Advocate platform upside (separate from subscription)
If/when advocate-side product launches, revenue can layer in:

`Platform_revenue = Advocates × Average_caseload_revenue × take_rate`

Illustrative cases (10% take-rate):
- 250 advocates × $30k annual caseload processed = **$0.75M**
- 750 advocates × $35k = **$2.63M**
- 1,500 advocates × $40k = **$6.0M**

---

## Practical investor framing (safe)
- The large-market story is credible, but **SOM and retention** are what matter pre-seed.
- Near-term milestone to prove: sustained weekly usage + paid conversion in initial parent cohorts.
- Present TAM/SAM/SOM as **assumption-led ranges**, not single-point claims.

---

## Next hardening tasks
1. Refresh 504-only estimate with latest authoritative source.
2. Build state-level bottom-up for Tier 1 states (NY, MA, NJ, CT, CA).
3. Attach channel-level CAC and 90-day retention assumptions to each scenario.
