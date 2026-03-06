# Marketing Mix Modeling Framework - Quantify Channel Impact & Optimize Budget Allocation

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** analytics, attribution, budget-optimization, b2b, b2c, strategy, data-driven

## Overview
This prompt builds a structured Marketing Mix Modeling (MMM) analysis that quantifies each channel's true contribution to revenue, separates baseline from incremental sales, and generates budget reallocation recommendations. Use it when you have 12+ months of spend and revenue data and need to move beyond last-click attribution.

## Quick Copy-Paste Version

You are a marketing analytics consultant specializing in Marketing Mix Modeling (MMM). I'll provide you with my channel spend and revenue data. Analyze it to:

1. Estimate each channel's contribution to total revenue (decompose baseline vs. incremental)
2. Calculate Return on Ad Spend (ROAS) and marginal ROAS for each channel
3. Identify diminishing returns thresholds — at what spend level does each channel become inefficient?
4. Recommend an optimized budget allocation to maximize revenue at my current total budget
5. Identify any synergy effects between channels (e.g., paid search amplifying TV/podcast awareness)

My data:
- Business type: [B2B SaaS / B2C ecommerce / etc.]
- Monthly revenue (last 12 months): [paste data or describe trend]
- Monthly channel spend breakdown: [Paid Search: $X, Paid Social: $X, Email: $X, Content/SEO: $X, Events: $X, other channels]
- Key external factors: [seasonality patterns, major promotions, product launches, competitive events]
- Current total monthly budget: $[X]

Deliver: a channel contribution table, ROAS by channel, diminishing returns analysis, and a revised budget allocation with projected revenue impact.

## Advanced Customizable Version

ROLE:
You are a Senior Marketing Science consultant with 15 years of MMM experience at companies like Nielsen, Analytic Partners, and Google. You use Bayesian MMM frameworks and understand the nuances of adstock effects, saturation curves, and carryover modeling.

CONTEXT:
Company: [Company Name]
Industry: [Industry — e.g., B2B SaaS, D2C Apparel, Financial Services]
Business Model: [Subscription / Transactional / Hybrid]
Sales Cycle Length: [e.g., 2 days / 60 days / 180 days]
Primary KPI: [Revenue / Pipeline / MQLs / App Installs]

REVENUE DATA (last 12–24 months, monthly):
[Paste monthly revenue figures — format: Month, Revenue]

CHANNEL SPEND DATA (monthly, same period):
[Paste: Month, PaidSearch, PaidSocial, ProgrammaticDisplay, Email, SEO/Content, Events/Field, TV/Podcast/Sponsorships, Other]

EXTERNAL VARIABLES (describe or provide data):
- Seasonality: [Holiday peaks, fiscal Q patterns, industry events]
- Price changes: [List any pricing changes with dates]
- Product launches: [List with dates]
- Competitive disruptions: [Funding rounds, competitor shutdowns, major campaigns]
- Macro events: [Economic downturns, industry regulation changes]

ANALYSIS TASKS:

1. REVENUE DECOMPOSITION
   - Estimate baseline revenue (what you'd earn with zero marketing spend — brand equity, word-of-mouth, organic)
   - Estimate incremental revenue attributable to each paid channel
   - Express as both absolute dollar contribution and % of total revenue

2. ADSTOCK & CARRYOVER MODELING
   - For each channel, estimate the decay rate: how many weeks does the impact linger after spend stops?
   - Identify channels with long carryover (brand/awareness) vs. short carryover (performance/direct)
   - Highlight which channels are being under-credited by last-click models due to carryover effects

3. SATURATION & DIMINISHING RETURNS
   - For each channel, estimate the saturation point (where each additional $1 generates less than $1 in incremental revenue)
   - Flag channels currently operating past saturation (overspending) vs. below saturation (underspending)
   - Show the response curve shape: linear, logarithmic, or S-curve

4. ROAS ANALYSIS
   - Short-term ROAS (within campaign window)
   - Long-term ROAS (including adstock/carryover periods)
   - Marginal ROAS at current spend levels
   - Break-even ROAS given my gross margin: [X%]

5. SYNERGY EFFECTS
   - Identify channel interaction effects (e.g., does paid social improve paid search conversion rates?)
   - Estimate the halo effect of brand channels on performance channels
   - Flag any cannibalization between channels targeting the same audience

6. BUDGET OPTIMIZATION SCENARIOS
   Scenario A — Maintain current total budget ($[X]/month), optimize allocation
   Scenario B — 20% budget cut: where to cut with minimum revenue impact
   Scenario C — 20% budget increase: where to invest for maximum incremental return

   For each scenario: show revised channel allocations, projected revenue change (%), and confidence range

7. MEASUREMENT GAPS & RECOMMENDATIONS
   - Which channels are hardest to measure (dark traffic, view-through, offline)?
   - Recommend incrementality tests (geo holdout, time-based holdout) to validate MMM findings
   - Suggest cadence for model refresh (quarterly vs. annually)

OUTPUT FORMAT:
- Executive Summary (3 bullet points for CMO)
- Channel Contribution Table (with baseline vs. incremental split)
- ROAS Dashboard (short-term, long-term, marginal)
- Saturation Analysis (over/under-investing flags)
- Budget Optimization Recommendation Table
- 90-Day Action Plan

CONSTRAINTS:
- Be explicit about model assumptions and confidence levels
- Flag when data is insufficient for reliable estimates — do not fabricate precision
- Use ranges, not point estimates, for projections
- Apply adstock half-life assumptions appropriate to each channel type

## Example Input/Output

**Input Example:**

Company: Vantara Health (B2B SaaS — employee wellness platform)
Sales cycle: 45 days
Monthly revenue range: $820K–$1.4M over 18 months
Channel mix:
- Paid Search (Google): $45K/mo
- Paid Social (LinkedIn): $30K/mo
- Content/SEO: $12K/mo
- Email Nurturing: $4K/mo
- Webinars/Events: $18K/mo
- Podcast Sponsorships: $8K/mo
Total budget: $117K/mo
Gross margin: 74%

**Output Example (abbreviated):**

Executive Summary:
- Paid Search and Webinars are your highest-ROI channels; LinkedIn is past saturation at current spend
- An estimated 38% of revenue is baseline (brand equity + organic search) — your floor is protected
- Reallocating $12K/mo from LinkedIn to Content/SEO could yield +$31K–$47K in incremental monthly revenue within 90 days

Channel Contribution Table:

| Channel | Monthly Spend | Incremental Revenue | Short-Term ROAS | Long-Term ROAS | Saturation Status |
|---|---|---|---|---|---|
| Paid Search | $45,000 | $189,000 | 4.2x | 5.8x (adstock) | Healthy — can scale 20% |
| LinkedIn Paid | $30,000 | $61,500 | 2.1x | 2.4x | Overspending — past saturation |
| Content/SEO | $12,000 | $78,000 | 6.5x | 11.2x (long carryover) | Underspending significantly |
| Email Nurture | $4,000 | $44,000 | 11.0x | 11.0x | Underspending — very efficient |
| Webinars/Events | $18,000 | $81,000 | 4.5x | 5.1x | Healthy |
| Podcast Sponsorships | $8,000 | $12,800 | 1.6x | 3.9x (8-week carryover) | Borderline — test pause |

Optimized Allocation (same $117K budget):
- Paid Search: $52K (+$7K) → Projected revenue lift: +$22K/mo
- LinkedIn Paid: $18K (-$12K) → Revenue loss: -$5K/mo (operating past saturation)
- Content/SEO: $22K (+$10K) → Projected revenue lift: +$19K/mo (90-day lag)
- Email Nurture: $7K (+$3K) → Projected lift: +$33K/mo
- Webinars/Events: $18K (unchanged)
- Net projected monthly revenue improvement: +$69K (confidence range: +$41K to +$94K)

## Success Metrics
- Budget reallocation decisions made with quantified projected ROI (not gut feel)
- Identification of at least one overspending channel and one underspending channel
- Long-term ROAS estimates that differ meaningfully from last-click attribution (validates adstock analysis)
- Scenario models used in actual budget planning cycle
- Incrementality tests designed and launched within 60 days to validate key findings

## Related Prompts
- `../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`
- `../Campaign-Performance-Analysis/Funnel-Performance-Diagnostics.md`
- `../KPI-Dashboard-Creation/Marketing-OKR-Goal-Setting-Framework.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/A-B-Testing-Automation.md`

## Integration Tips
- **Google Sheets / Looker Studio:** Export channel spend by month from your ad platforms (Google Ads, Meta, LinkedIn Campaign Manager), consolidate in a single Sheet, then paste the summarized data into the prompt. Use Looker Studio to visualize the output contribution table.
- **HubSpot:** Pull pipeline-sourced revenue attribution reports to compare against MMM outputs — gaps highlight where multi-touch attribution is over/under-crediting channels.
- **Salesforce:** Use Salesforce Reports to extract closed-won revenue by campaign source per month; cross-reference with your MMM channel contribution output to spot discrepancies.
- **Northbeam / Rockerbox / Triple Whale (ecommerce):** Use these MTA tools' channel spend exports as your input data; compare their ROAS figures to MMM estimates to understand view-through and cross-device credit differences.
- **Zapier:** Automate monthly data pulls from ad platforms into a master Google Sheet that feeds your MMM prompt template — set a recurring Zap to trigger on the 1st of each month.

## Troubleshooting

**Problem: "I don't have 12+ months of data — I'm a younger company."**
Solution: Use whatever data you have (minimum 6 months) but reduce your confidence in saturation estimates. Focus the prompt on ROAS comparison and directional budget shifts rather than precise saturation curves. Flag this constraint explicitly to the AI.

**Problem: "The model is giving me wildly different results than my last-click attribution tool."**
Solution: This is expected and usually a sign the MMM is working correctly. Last-click systematically over-credits bottom-funnel channels (paid search, retargeting) and under-credits top-funnel channels (content, podcasts, brand). Use the MMM output for strategic budget decisions and your attribution tool for campaign-level optimization.

**Problem: "The optimized allocation looks right on paper but I can't execute it — LinkedIn is a key channel for our ABM strategy."**
Solution: Add a constraint to the Advanced Version: "Channel [X] must maintain minimum $[Y] spend due to account-based marketing requirements." The model will optimize the remaining budget within your strategic constraints. Treating MMM as a pure optimization engine without business context leads to recommendations that ignore pipeline quality and strategic accounts.

## Version History
- v1.0: Initial creation (auto-generated)
