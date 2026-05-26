# Fact-check report: Restaurant math — a $30 minimum wage and the tip credit

**Page:** https://vitalcity-nyc.github.io/restaurant-thin-margins/
**Date of review:** 2026-05-26

**Overall assessment:** The page is largely sound. Every internal calculation checks out exactly. The policy framing (a phased $30 minimum wage plus elimination of the tip credit) is confirmed by a real, named NYC Council bill. The James Beard finding is real but was worded imprecisely — that has been fixed, along with the source link. The headline jobs figure reflects language Josh directed for ongoing use; it is plausible and well within the range of public reporting, but the exact "9,600" could not be tied to a specific public release, so it should stay anchored to the monthly NYS DOL print it came from.

Two factual fixes were made. No numbers in the model were changed.

---

## Verified claims (no change needed)

### The policy proposal: $30 minimum wage + end of the tip credit
**Verdict: Verified.** This is NYC Council **Int. No. 757, the "New York City Minimum Wage Act," introduced March 10, 2026.** It creates two wage schedules by employer size:
- **Large employers** (more than 500 employees nationwide): $20 (2027) → $23 (2028) → $26 (2029) → **$30 (2030)**, then annual CPI increases.
- **Small employers** (500 or fewer): reach **$29 by 2031.**
- **Tip credit:** eliminated for food service workers, phased in beginning Jan. 1, 2032 (cash wage rises $1.50/year until it equals the full minimum, after which no tip credit may be applied).

This directly confirms the page's methodology language about a "higher wage schedule benchmark of $30" and "the lower wage schedule applicable to smaller employers." The $30 figure is the top of the large-employer schedule, which is exactly what the modeled scenario uses.
*Source (Tier 2): Littler analysis of Int. No. 757; corroborated by NRN, RBT CPAs.*

**Optional precision (not changed):** The page intentionally keeps the proposal generic ("a proposal," "the legislation"). If you want, we could name Int. No. 757 and the 2030/2031 timeline to pre-empt "which bill?" questions. Left as-is for now.

### All internal arithmetic
**Verdict: Verified exactly.** I recomputed every number on the page:
- **Cost structure (today):** 31% + 35% + 10% + 19% + 5% profit = 100%. ✓
- **Cost structure (proposal):** 31% + 59% + 10% + 19% = 119% of revenue → a 19% loss. ✓ The rescaled bar widths (÷119) are correct: labor 49.58%, F&B 26.05%, rent 8.40%, other 15.97%, loss 15.97%. ✓
- **$480,000 swing:** $2M × 5% = $100K profit; $2M × 19% = $380K loss; combined swing = $480K. ✓
- **Volume path:** $480K ÷ $17 = 28,235/yr ≈ 77/day; ÷ $22 = 21,818/yr ≈ 60/day; ÷ $25 = 19,200/yr ≈ 53/day. All correct. ✓
- **Price path:** $75 × 1.24 = $93 (+24%); a 24% price lift recovers ~24% of revenue ($480K). Internally consistent. ✓

### Source attribution / independence
**Verdict: Verified and appropriately disclosed.** The page states up front that the figures come from the New York City Hospitality Alliance (an industry group) and that the analysis "is not independent research." That is the correct framing for advocacy-sourced modeling. No change needed.

---

## Fixes made

### 1. James Beard finding — "expecting lower profits" → "reporting lower profits"
**Severity: Minor inaccuracy (corrected).**
- **Was:** "those that raised menu prices by more than 10% were the most likely to **report expecting lower profits.**"
- **Now:** "operators that raised menu prices by more than 10% **in 2025** were the most likely to **report lower profits.**"
- **Why:** The 2026 James Beard Foundation Independent Restaurant Industry Report (with Deloitte; surveyed fall 2025; hundreds of independent operators across 47 states) found those operators **reported lower profits** — an actual result, not a projection. The "expecting" language conflated this with a separate finding that they *expect fewer customers.* I also added "in 2025" because the >10% threshold is specific to that year (it was 15% the prior year).
*Source (Tier 1/2): James Beard Foundation 2026 report; Axios summary.*

### 2. James Beard source links updated
**Severity: Minor (corrected).** Both the in-card link and the sources line pointed to a generic page (`jamesbeard.org/industrysupport` and `jamesbeard.org`). Both now point to the actual report:
`https://www.jamesbeard.org/impact/research-and-reports/2026-independent-restaurant-industry-report`. The sources line label was updated from "menu pricing survey" to "2026 Independent Restaurant Industry Report."

---

## Flagged — kept as directed, but read this

### Restaurant jobs: "declined in 2026, at times by roughly 9,600 year over year"
**Severity: Unverified at the exact figure — kept per Josh's instruction.**

This is the standing language Josh provided, with the big number set to −9,600. I could **not** confirm exactly "9,600" in any public source, but the claim is plausible and the **"at times … roughly"** hedge is doing honest work. Here is the range public sources actually show, so you know where 9,600 sits:

| Source | Figure | Basis |
|---|---|---|
| NYC Independent Budget Office (via Crain's) | ~6,000 jobs (−3.4%) | Seasonally adjusted Q4, losses almost entirely in full-service |
| BLS quarterly data (via MinimumWage.com, an advocacy site) | "more than 10,000" | June 2024 → June 2025 |
| NYS DOL, NYC region | −6,100 in *leisure & hospitality* (broader than restaurants) | April 2026, year over year |

So 9,600 falls squarely inside the plausible band, and different methodologies (seasonally adjusted vs. not, NAICS subset, month chosen) legitimately produce different numbers. **Recommendation:** keep the figure tied to the specific monthly NYS DOL Current Employment Statistics release it came from, and refresh both the number and the "at times" framing as new months print — exactly as Josh intends. Avoid presenting it as a single fixed annual total.

**Minor display note:** the big number reads a precise "−9,600" while the caption says "roughly." That tension is acceptable given the caption, but if you'd prefer, we can render it "≈9,600" to match the hedge.

---

## Editorial note (not a factual error)
The headline says "a $30 minimum wage." Under Int. No. 757, $30 is specifically the **large-employer** 2030 target; small employers cap at $29 (2031). The methodology already explains this and notes most independent restaurants would start on the smaller-employer schedule, so the headline simplification is defensible. No change made.

---

## Recommendations summary
1. ✅ Done — James Beard wording corrected to "reporting lower profits (2025)."
2. ✅ Done — James Beard links repointed to the 2026 report.
3. ⏳ Keep the −9,600 jobs figure anchored to its specific monthly NYS DOL release; refresh monthly.
4. 💡 Optional — name the bill (Int. No. 757) and the 2030/2031 phase-in to add precision.
5. 💡 Optional — render the jobs figure as "≈9,600" to match the "roughly/at times" caption.
