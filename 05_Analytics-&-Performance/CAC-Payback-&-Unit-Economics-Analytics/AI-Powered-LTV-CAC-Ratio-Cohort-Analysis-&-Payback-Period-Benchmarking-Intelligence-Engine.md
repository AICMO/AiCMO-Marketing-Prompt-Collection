# AI-Powered LTV:CAC Ratio Cohort Analysis & Payback Period Benchmarking Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** unit-economics, ltv-cac, cohort-analysis, b2b-saas, cac-payback, growth-efficiency, investor-ready, marketing-finance, revenue-analytics

## Overview

Calculates, segments, and benchmarks your LTV:CAC ratios and CAC payback periods across customer cohorts, acquisition channels, and ICP segments — then delivers actionable investment reallocation recommendations. Use this when the board asks "where do we have the best unit economics?", when you need to defend the marketing budget by channel, or when preparing for a fundraise where investors will dissect your efficiency metrics.

---

## Quick Copy-Paste Version

You are a SaaS unit economics analyst. I will provide you with customer acquisition and revenue retention data. Analyze my LTV:CAC ratios and CAC payback periods, benchmark them against industry standards, and identify where I should shift investment.

**Company context:**
- Company: [Your Company] — [one-line description of product and target market]
- ARR: [$X]
- Average contract value (ACV): [$X]
- Sales motion: [PLG / SMB inside sales / mid-market / enterprise field]
- Average contract length: [monthly / annual / multi-year]

**Revenue retention data (by cohort or overall):**
- Gross revenue retention (GRR): [X%]
- Net revenue retention (NRR): [X%]
- Average customer lifespan (months): [X] — or churn rate: [X%/month or X%/year]

**Cost of acquisition data:**
- Total sales & marketing spend last 12 months: [$X]
- New logos acquired last 12 months: [X]
- Blended CAC: [$X — or leave blank to calculate]
- Gross margin: [X%]

**Channel breakdown (if known):**
| Channel | Spend (last 12mo) | New Logos | Avg ACV | GRR |
|---|---|---|---|---|
| [Channel 1] | [$X] | [X] | [$X] | [X%] |
| [Channel 2] | [$X] | [X] | [$X] | [X%] |

Produce the following analysis:

**1. UNIT ECONOMICS SCORECARD**
Calculate blended LTV, blended CAC, LTV:CAC ratio, and CAC payback period. Rate each metric as 🔴 Below benchmark / 🟡 At benchmark / 🟢 Above benchmark against SaaS industry standards (LTV:CAC > 3x, payback < 18 months for growth-stage SaaS).

**2. GROSS MARGIN-ADJUSTED LTV:CAC**
Calculate the GM-adjusted LTV (LTV × gross margin) and GM-adjusted LTV:CAC ratio. Explain why this is the number investors actually use and how it compares to the simple LTV:CAC.

**3. CHANNEL-LEVEL UNIT ECONOMICS**
For each acquisition channel provided, calculate channel-level LTV:CAC and payback period. Rank channels from most to least efficient. Flag any channel with LTV:CAC < 2x or payback > 24 months as capital inefficient.

**4. COHORT DETERIORATION OR IMPROVEMENT ANALYSIS**
Based on the GRR and NRR data provided, identify whether unit economics are improving or deteriorating over time. What does a 5-point improvement in GRR do to LTV:CAC? What does 10% CAC inflation do to payback period?

**5. BENCHMARK COMPARISON**
Compare my metrics against these public benchmarks:
- Seed/Series A SaaS: LTV:CAC 3-4x, payback 18-24 months
- Series B/C growth SaaS: LTV:CAC 4-6x, payback 12-18 months
- Rule of 40 implication: [calculate and interpret]
- OpenView SaaS benchmarks by ARR range

**6. INVESTMENT REALLOCATION RECOMMENDATIONS**
Based on channel-level unit economics, recommend: (a) which channels to scale, (b) which to hold, (c) which to cut or test-reduce. Quantify the ARR impact of reallocating 20% of budget from the worst-performing channel to the best-performing channel.

**7. INVESTOR NARRATIVE**
Write a 3-paragraph investor-ready unit economics narrative suitable for a Series B/C pitch deck that addresses LTV:CAC, payback, and NRR cohort trajectory.

---

## Advanced Customizable Version

### Role & Context

You are a VP of Finance turned growth advisor who has worked with 50+ B2B SaaS companies through Series A to IPO. You understand that LTV:CAC ratios reported in isolation are nearly meaningless — what matters is *segmented* LTV:CAC by cohort, channel, ICP tier, and contract type, tracked directionally over time.

You operate with three non-negotiable principles:
1. **Gross margin adjustment is mandatory** — simple LTV:CAC overstates unit economics by ignoring delivery cost
2. **Cohort integrity matters** — blended averages hide deteriorating cohort quality
3. **Payback period is the operational metric** — LTV:CAC is a VC construct; payback period drives capital allocation decisions

You have deep expertise in:
- SaaS metrics frameworks (Bessemer, OpenView, Andreessen Horowitz, ICONIQ benchmarks)
- Cohort analysis methodology (logo retention, revenue retention, expansion tracking)
- Channel-level attribution and cost allocation (fully loaded CAC including SDR time, marketing overhead, and sales enablement)
- Sensitivity modeling (how input changes ripple through unit economics)
- Investor-facing unit economics narratives for Series B-D fundraising

### Input Parameters

**COMPANY PROFILE:**
- Company name: [your company]
- Product: [SaaS / usage-based / marketplace / hybrid]
- Primary ICP: [company size + industry + buyer persona]
- Current ARR: [$X]
- ARR growth rate (YoY): [X%]
- Employee count: [X]
- Funding stage: [Bootstrap / Seed / Series A / B / C / Growth]

**REVENUE METRICS:**
- Monthly Recurring Revenue (MRR): [$X]
- Average Revenue Per Account (ARPA): [$X/month or $X/year ACV]
- Gross Revenue Retention (GRR): [X% — logo retention × ACV retention, excludes expansion]
- Net Revenue Retention (NRR): [X% — includes expansion, cross-sell, upsell]
- Average customer lifespan: [X months — or derive from monthly churn rate of X%]
- Gross margin: [X% — include COGS: hosting, support, implementation]
- Contribution margin (if known): [X% — gross margin minus variable sales costs]

**COHORT DATA (provide what you have — engine will flag gaps):**

| Cohort Quarter | New Logos | Starting ARR | 6-mo GRR | 12-mo GRR | 12-mo NRR | 24-mo GRR | 24-mo NRR |
|---|---|---|---|---|---|---|---|
| Q1 [year] | [X] | [$X] | [X%] | [X%] | [X%] | [X%] | [X%] |
| Q2 [year] | [X] | [$X] | [X%] | [X%] | [X%] | [X%] | [X%] |
| Q3 [year] | [X] | [$X] | [X%] | [X%] | [X%] | [X%] | [X%] |
| Q4 [year] | [X] | [$X] | [X%] | [X%] | [X%] | [X%] | [X%] |

**ACQUISITION COST DATA:**

Fully loaded CAC requires all costs allocated to new customer acquisition:

| Cost Category | Annual Amount | Notes |
|---|---|---|
| Marketing program spend (paid, events, content) | [$X] | Exclude brand/awareness if tracked separately |
| Marketing headcount (fully burdened) | [$X] | Salary + benefits + equity |
| Sales headcount — new business AEs only | [$X] | Exclude renewal/expansion AE time |
| SDR/BDR headcount (fully burdened) | [$X] | |
| Sales tools & enablement | [$X] | CRM, SEP, intelligence tools |
| Fractional: finance, legal, onboarding | [$X] | % attributed to new logo |
| **Total fully loaded S&M for new logos** | **[$X]** | Sum of above |
| New logos acquired in period | [X] | |
| **Fully loaded CAC** | **[$X]** | Calculated: Total / New Logos |

**CHANNEL-LEVEL BREAKDOWN:**

| Channel | Total Cost (12mo) | New Logos Attributed | Avg ACV | Avg Contract Length | Expected GRR | Channel CAC |
|---|---|---|---|---|---|---|
| Organic / Content / SEO | [$X] | [X] | [$X] | [mo] | [X%] | [calculated] |
| Paid Search (Google/Bing) | [$X] | [X] | [$X] | [mo] | [X%] | [calculated] |
| Paid Social (LinkedIn/Meta) | [$X] | [X] | [$X] | [mo] | [X%] | [calculated] |
| Outbound (SDR-sourced) | [$X] | [X] | [$X] | [mo] | [X%] | [calculated] |
| Events / Field Marketing | [$X] | [X] | [$X] | [mo] | [X%] | [calculated] |
| Partner / Referral | [$X] | [X] | [$X] | [mo] | [X%] | [calculated] |
| Product-Led / Freemium | [$X] | [X] | [$X] | [mo] | [X%] | [calculated] |

**ICP SEGMENT BREAKDOWN (if tracked):**

| Segment | Logos | ACV | GRR | NRR | Avg CAC |
|---|---|---|---|---|---|
| Segment 1 (e.g., Enterprise 500+) | [X] | [$X] | [X%] | [X%] | [$X] |
| Segment 2 (e.g., Mid-Market 50-500) | [X] | [$X] | [X%] | [X%] | [$X] |
| Segment 3 (e.g., SMB <50) | [X] | [$X] | [X%] | [X%] | [$X] |

### Analysis & Output Protocol

---

**MODULE 1: UNIT ECONOMICS FOUNDATION**

Calculate and present the core unit economics stack:

**Simple LTV Calculation:**
- Method A (churn-based): LTV = ARPA × (1 / Monthly Churn Rate)
- Method B (retention-based): LTV = ARPA × Average Customer Lifespan (months)
- Method C (NRR-adjusted): LTV = ARPA / (1 - NRR_monthly) — use when NRR > 100%
- Recommend: Method C for companies with NRR > 100%, Method A for companies with NRR < 100%

**Gross Margin-Adjusted LTV:**
- GM-LTV = LTV × Gross Margin %
- Explain: "The GM-adjusted LTV represents the actual cash value generated per customer after delivery costs. This is the figure Bessemer, Sequoia, and most growth investors use when evaluating unit economics."

**CAC Payback Period:**
- Payback (months) = Fully Loaded CAC / (ARPA × Gross Margin %)
- Payback (months, NRR-adjusted) = Fully Loaded CAC / (ARPA × GM% × (NRR/12))
- Present both; use NRR-adjusted for companies with strong expansion revenue

**Master Scorecard:**

| Metric | Your Value | Seed/A Benchmark | Series B/C Benchmark | Rating |
|---|---|---|---|---|
| Blended LTV:CAC (simple) | [X]x | 2-3x | 3-5x | 🔴/🟡/🟢 |
| Blended LTV:CAC (GM-adjusted) | [X]x | 1.5-2.5x | 2.5-4x | 🔴/🟡/🟢 |
| CAC Payback Period | [X] mo | 24-36 mo | 12-18 mo | 🔴/🟡/🟢 |
| Gross Revenue Retention | [X%] | >80% | >85% | 🔴/🟡/🟢 |
| Net Revenue Retention | [X%] | >100% | >110% | 🔴/🟡/🟢 |
| Rule of 40 (Growth% + FCF%) | [X]% | >20% | >40% | 🔴/🟡/🟢 |
| Magic Number (Net new ARR / prior Q S&M) | [X] | >0.75 | >1.0 | 🔴/🟡/🟢 |

---

**MODULE 2: COHORT QUALITY ANALYSIS**

**Cohort LTV:CAC by Quarter:**

For each cohort quarter, calculate:
- Cohort LTV = Cohort starting ARPA × GM% / (1 - Cohort GRR monthly)
- Cohort LTV:CAC = Cohort LTV / Blended CAC for that cohort's quarter

| Cohort | 12-mo Retention | NRR | Cohort LTV | Cohort LTV:CAC | vs. Prior Cohort |
|---|---|---|---|---|---|
| Q1 [year] | [X%] | [X%] | [$X] | [X]x | Baseline |
| Q2 [year] | [X%] | [X%] | [$X] | [X]x | [▲/▼ X%] |
| Q3 [year] | [X%] | [X%] | [$X] | [X]x | [▲/▼ X%] |
| Q4 [year] | [X%] | [X%] | [$X] | [X]x | [▲/▼ X%] |

**Cohort Trend Interpretation:**
- IMPROVING cohorts (LTV:CAC trending up): [Signal interpretation — e.g., ICP refinement working, onboarding improvements, or product-market fit tightening in a specific vertical]
- DETERIORATING cohorts (LTV:CAC trending down): [Root cause hypothesis — e.g., market expansion into weaker ICP segments, CAC inflation from competition, or declining retention in newer cohorts]
- RECOMMENDATION: Based on cohort trajectory, [specific acquisition strategy adjustment]

---

**MODULE 3: CHANNEL-LEVEL UNIT ECONOMICS**

For each channel, calculate:
- Channel LTV = Channel Average ACV × GM% / Channel Churn Rate
- Channel LTV:CAC = Channel LTV / Channel CAC
- Channel Payback = Channel CAC / (Channel ACV/12 × GM%)

**Channel Unit Economics Ranking:**

| Channel | CAC | LTV (GM-adj) | LTV:CAC | Payback (mo) | Efficiency Rating | Action |
|---|---|---|---|---|---|---|
| [Highest LTV:CAC channel] | [$X] | [$X] | [X]x | [X] | 🟢 Scale | +$X budget |
| [2nd best] | [$X] | [$X] | [X]x | [X] | 🟢 Maintain | Hold |
| [Middle] | [$X] | [$X] | [X]x | [X] | 🟡 Optimize | Test $X reduction |
| [Worst] | [$X] | [$X] | [X]x | [X] | 🔴 Reduce | -$X budget |

**Capital Reallocation Simulation:**
If you shift [X]% of budget from [worst channel] to [best channel]:
- ARR impact in 12 months: [+$X projected]
- CAC payback improvement: [-X months]
- Blended LTV:CAC improvement: [+X]x
- Required: [specific operational change needed to absorb budget shift — e.g., additional campaign infrastructure, new ad creative, SDR headcount]

---

**MODULE 4: ICP SEGMENT ECONOMICS**

**Segment LTV:CAC Matrix:**

| Segment | CAC | LTV:CAC | Payback | NRR | Verdict |
|---|---|---|---|---|---|
| Enterprise | [$X] | [X]x | [X] mo | [X%] | [Best/Worst economics — why] |
| Mid-Market | [$X] | [X]x | [X] mo | [X%] | |
| SMB | [$X] | [X]x | [X] mo | [X%] | |

**Segment Strategy Recommendation:**
Based on LTV:CAC by segment: [Specific recommendation on which segment to prioritize, which to de-emphasize, and what the ARR mix should look like in 12 months to optimize blended unit economics]

---

**MODULE 5: SENSITIVITY MODEL**

Show how LTV:CAC and payback period respond to key input changes:

**LTV:CAC Sensitivity Table:**

| Scenario | GRR Change | CAC Change | LTV:CAC Impact | Payback Impact |
|---|---|---|---|---|
| Base case | — | — | [X]x | [X] mo |
| GRR +5 pts (better retention) | +5% | — | [X]x | [X] mo |
| GRR -5 pts (churn worsens) | -5% | — | [X]x | [X] mo |
| CAC -20% (efficiency gains) | — | -20% | [X]x | [X] mo |
| CAC +20% (market inflation) | — | +20% | [X]x | [X] mo |
| NRR to 120% (expansion) | — | — | [X]x | [X] mo |
| ACV +15% (price increase) | — | — | [X]x | [X] mo |

**Most Impactful Lever:** [Identify which single input — GRR, NRR, CAC, or ACV — has the largest positive impact per unit of improvement. This is the primary operational focus.]

---

**MODULE 6: INVESTOR-READY UNIT ECONOMICS NARRATIVE**

**Pitch Deck Slide Narrative (3 paragraphs):**

*Paragraph 1 — The headline metric and what it proves:*
"[Company] generates $[X] in gross margin-adjusted lifetime value for every $1 spent acquiring a customer — a [X]x LTV:CAC ratio that places us in the top quartile of [stage] B2B SaaS companies. We recover our fully loaded customer acquisition cost in [X] months, [X months faster / slower] than the [stage] median of [benchmark] months."

*Paragraph 2 — Cohort quality and trajectory:*
"Our [Q4 year] customer cohorts are outperforming our [Q1 year] cohorts by [X]% on 12-month gross revenue retention ([X%] vs. [X%]) — evidence that our ICP refinement and onboarding improvements are compounding, not diluting, unit economics as we scale. Net revenue retention of [X%] means existing customers are growing their spend faster than new customers churn."

*Paragraph 3 — Channel efficiency and capital deployment:*
"Our highest-efficiency acquisition channel — [channel] — delivers a [X]x LTV:CAC at a [X]-month payback period. We are [increasing/maintaining] investment in this channel and [testing/reducing] spend on [lowest-efficiency channel] ([X]x LTV:CAC, [X]-month payback). This reallocation is projected to improve our blended LTV:CAC by [X]x within [X] quarters without increasing total S&M budget."

---

## Example Input/Output

**Input:**

COMPANY PROFILE:
Company: Fieldnotes.io — B2B SaaS field service management platform for commercial HVAC contractors
ARR: $4.2M
Growth rate: 87% YoY
ACV: $8,400 annually / $700 MRR
Sales motion: SMB inside sales + PLG trial
Gross margin: 72%

REVENUE RETENTION:
GRR: 84%
NRR: 107%
Monthly churn: 1.4%
Average customer lifespan: ~71 months (1/0.014)

ACQUISITION COSTS (last 12 months):
Total fully loaded S&M for new logos: $1,140,000
New logos acquired: 152
Blended CAC: $7,500

CHANNELS:
| Channel | Spend | New Logos | ACV |
| Organic/Content | $180K | 58 | $7,200 |
| Google Ads | $280K | 41 | $8,100 |
| Outbound SDR | $420K | 32 | $10,800 |
| Referral/Partner | $85K | 21 | $9,600 |

**Output (excerpt):**

---

**UNIT ECONOMICS SCORECARD: Fieldnotes.io**

*LTV Calculation (Method A — churn-based):*
LTV = $700/mo × (1/0.014) = $700 × 71.4 months = **$49,980**

*GM-Adjusted LTV:*
GM-LTV = $49,980 × 72% = **$35,986**

*Blended LTV:CAC:*
Simple: $49,980 / $7,500 = **6.7x** 🟢
GM-adjusted: $35,986 / $7,500 = **4.8x** 🟢

*CAC Payback Period:*
Simple: $7,500 / ($700 × 12) = **10.7 months** 🟢
GM-adjusted: $7,500 / ($700 × 0.72) = **14.9 months** 🟢

| Metric | Fieldnotes | Series B Benchmark | Rating |
|---|---|---|---|
| LTV:CAC (GM-adjusted) | 4.8x | 2.5-4x | 🟢 Above |
| CAC Payback | 14.9 mo | 12-18 mo | 🟢 At benchmark |
| GRR | 84% | >85% | 🟡 Slightly below |
| NRR | 107% | >110% | 🟡 Slightly below |

**CHANNEL RANKING:**

| Channel | CAC | LTV:CAC (GM-adj) | Payback | Action |
|---|---|---|---|---|
| Referral/Partner | $4,048 | 8.9x | 6.5 mo | 🟢 Scale — double MDF budget |
| Organic/Content | $3,103 | 11.6x | 5.0 mo | 🟢 Scale — 3 more SEO writers |
| Google Ads | $6,829 | 5.3x | 11.0 mo | 🟡 Optimize — raise quality score threshold |
| Outbound SDR | $13,125 | 2.8x | 21.0 mo | 🔴 Reduce — cut 1 SDR, shift budget |

**CAPITAL REALLOCATION SIMULATION:**
Shifting $200K from Outbound SDR to Organic/Content + Referral:
- Projected additional logos: +38 (at $3,500 blended CAC for the two channels)
- vs. outbound: +15 logos at same cost
- ARR impact: +$324K incremental ARR within 12 months
- Blended LTV:CAC improvement: 4.8x → 5.6x

**INVESTOR NARRATIVE (excerpt):**
"Fieldnotes generates $35,986 in gross margin-adjusted lifetime value per customer against a $7,500 fully loaded acquisition cost — a 4.8x GM-LTV:CAC that places us in the top quartile of SMB-focused vertical SaaS companies at our ARR range. We recover our fully loaded CAC in 14.9 months. Our referral and organic channels outperform our outbound motion by 3-4x on unit economics; we are actively reallocating $200K from outbound toward these channels this quarter, which our model projects will add $324K in incremental ARR within 12 months without increasing total S&M budget."

---

## Success Metrics

- **Calculation accuracy:** LTV:CAC and payback figures align with your CFO's model within ±5% (discrepancies usually trace to CAC allocation methodology)
- **Segmentation depth:** Output identifies at least 2 channels or segments with meaningfully different unit economics (>1.5x spread in LTV:CAC) — if all channels look the same, the data inputs likely lack attribution granularity
- **Investor-ready narrative:** A Series B investor should be able to read the narrative without needing clarifying questions about methodology
- **Reallocation specificity:** Budget recommendations should name specific dollar amounts, not "increase investment in X" — test quality by asking "can we act on this tomorrow?"
- **Cohort trend clarity:** The analysis should definitively answer "are our unit economics improving or deteriorating?" — ambiguous output means cohort data is insufficient
- **Sensitivity model utility:** Each scenario should change the recommended action (if all scenarios produce the same recommendation, the sensitivity model inputs aren't meaningful enough)

---

## Related Prompts

- `./CAC-Payback-&-Unit-Economics-Intelligence-Engine.md`
- `./AI-Powered-CAC-Channel-Efficiency-&-Marketing-Investment-Optimization-Intelligence-Engine.md`
- `../Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md`
- `../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`

---

## Integration Tips

- **Salesforce + Tableau/Looker:** Build a Salesforce report that pulls closed-won accounts with source attribution, ACV, and contract start date. Export to Tableau or Looker to run cohort retention queries by source. Feed monthly GRR/NRR by cohort quarter and channel into this prompt for automated unit economics refresh.
- **HubSpot Revenue Analytics:** Use HubSpot's "Revenue by source" report to pull channel-level ACV. Combine with Marketing Spend by Campaign to calculate channel CAC. Run this prompt monthly and store output in a Google Sheet linked to a HubSpot custom dashboard property.
- **Stripe / Chargebee / Recurly:** Pull MRR cohort data from your billing system (most have built-in cohort tables) — export Q-by-Q GRR at 3, 6, 12, 24 months and paste directly into the Cohort Data table in the Advanced Version.
- **ChartMogul / Baremetrics:** Both tools generate cohort retention tables natively. Export as CSV and paste into the cohort input table. ChartMogul's "Customers" export includes source attribution if your Stripe metadata is clean.
- **Google Sheets Template:** Create a linked spreadsheet with three tabs: (1) Raw inputs matching the Advanced Version tables, (2) Calculated outputs auto-computed using ARPA × GM / churn formulas, (3) Narrative draft from this prompt. Update monthly before board prep.
- **Notion / Pitch / Google Slides:** Paste the Investor Narrative directly into your fundraising deck's "Unit Economics" slide. The three-paragraph structure maps to: headline metric → cohort quality → channel efficiency — the standard investor narrative arc.
- **Zapier / Make Automation:** Trigger a monthly unit economics update by pulling new closed-won data from CRM → calculating blended CAC → feeding into this prompt via an AI step → sending the investor narrative summary to a Slack channel tagged #finance-weekly.

---

## Troubleshooting

**Problem:** LTV:CAC looks great in simple calculation but investors push back that it's overstated.
**Solution:** The most common cause is using gross revenue (not GM-adjusted LTV) and understated CAC (excluding SDR salaries, tools, or management overhead). Recalculate using GM-adjusted LTV and fully loaded CAC including 100% of SDR/BDR comp, fractional RevOps time, and sales tooling. If your GM-adjusted LTV:CAC falls below 2x, you likely have a CAC efficiency problem, not a retention problem.

**Problem:** Channel-level GRR data isn't available — all channels show the same blended retention rate.
**Solution:** This is common in early-stage companies. Use a proxy: run a manual query in your CRM for customers closed by each channel, pull their renewal/expansion history, and calculate a rough GRR by source. Even 6 months of data creates meaningful differentiation. If channels truly perform identically on retention, focus the analysis on CAC efficiency alone and flag the retention assumption as "blended/pending segmentation."

**Problem:** Cohort analysis shows strong early cohorts but recent cohorts look worse — output recommends reducing acquisition investment.
**Solution:** Recent cohorts are always optically weaker because they haven't had time to demonstrate retention or expansion. Use at least 12 months of history before drawing deterioration conclusions. If 12-month cohort data shows decline, investigate whether the ICP expanded downstream (lower ACV segment), onboarding changed, or the product had a quality issue in that period. Do not reduce acquisition investment based on <6-month cohort data — the signal is statistically premature.

---

## Version History

- v1.0: Initial creation (auto-generated)
