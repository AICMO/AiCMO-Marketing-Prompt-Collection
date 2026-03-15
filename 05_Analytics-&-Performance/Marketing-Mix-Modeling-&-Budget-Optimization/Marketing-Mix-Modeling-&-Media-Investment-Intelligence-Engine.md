# Marketing Mix Modeling & Media Investment Intelligence Engine - Prove Channel ROI Without Cookies or CRM Touch Data

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** b2b, b2c, analytics, mmm, budget-optimization, paid-media, forecasting, automation

## Overview
Constructs a Marketing Mix Model (MMM) from your spend, revenue, and business data to quantify each channel's true contribution to revenue — independent of cookies, UTMs, or CRM attribution. Use this when privacy changes have broken your attribution, when leadership demands channel ROI proof, or when you're optimizing a $500K+ annual media budget across 5+ channels.

## Quick Copy-Paste Version

You are a marketing econometrics expert. Build a Marketing Mix Model analysis from my business data.

My data:
- Time period: [e.g., Jan 2024 – Dec 2024, weekly or monthly observations]
- Revenue/conversions by period: [paste data or describe: "Jan: $420K, Feb: $380K..."]
- Marketing spend by channel by period: [channel name, monthly spend]
  - [Channel 1, e.g., Google Ads]: [$X/month]
  - [Channel 2, e.g., LinkedIn Ads]: [$X/month]
  - [Channel 3, e.g., Email/Nurture]: [$X/month]
  - [Channel 4, e.g., Events]: [$X/month]
  - [Channel 5, e.g., Content/SEO]: [$X/month]
- External factors (if known): [seasonality peaks, competitor launches, economic events, price changes]
- Business type: [B2B SaaS / B2C eCommerce / D2C / Other]
- Primary revenue metric: [new ARR / gross revenue / units sold]

Please deliver:
1. Estimated revenue contribution (%) by channel — the MMM output
2. Saturation analysis: which channels are over-invested with diminishing returns vs. under-invested
3. Adstock/carryover analysis: which channels have lagged effects (e.g., brand spend pays off in 3 months)
4. Optimal budget allocation for current total spend
5. Revenue projection under 3 budget scenarios: flat, +20%, -20%
6. Top 3 highest-ROI channels to increase investment
7. Top 2 channels where spend should be reduced or paused
8. Recommended testing plan to validate the model's predictions

Flag all assumptions clearly. Show your reasoning for each channel's contribution estimate.

## Advanced Customizable Version

ROLE: You are a senior marketing science consultant specializing in Marketing Mix Modeling (MMM) and media econometrics, with 12+ years of experience building MMMs for B2B SaaS and B2C brands with $1M–$50M annual media budgets. You apply Bayesian and frequentist regression techniques, adstock transformations, and saturation curves to decompose revenue drivers.

BUSINESS CONTEXT:
- Company: [Company Name]
- Industry: [B2B SaaS / B2C eCommerce / D2C CPG / Financial Services / Other]
- Stage: [Growth / Scale / Mature]
- Annual revenue: [$X]
- Primary conversion metric: [New ARR / Revenue / Units / Trials / Demos]
- Sales cycle: [<7 days (transactional) / 7–90 days (mid-market) / 90+ days (enterprise)]
- Seasonality patterns: [describe peak seasons, e.g., "Q4 strong, summer weak" or "steady"]
- Geographic scope: [US only / North America / Global]

TIME SERIES DATA (provide weekly or monthly, minimum 52 weeks preferred):
Paste or describe your data in this format:
Period | Revenue/Conversions | [Channel 1 Spend] | [Channel 2 Spend] | [Channel 3 Spend] | [Macro Variable 1] | [Macro Variable 2]

CHANNELS TO MODEL:
Paid Digital:
- Search (Google/Bing): [$X total, breakdown by brand vs. non-brand if available]
- Paid Social (LinkedIn/Meta/TikTok): [$X total, by platform if possible]
- Programmatic Display/Video: [$X]
- Retargeting: [$X]

Owned/Earned:
- Email Marketing: [describe send volume and cadence, not just cost]
- SEO/Organic: [describe traffic trend — growing/flat/declining]
- Organic Social: [describe — LinkedIn followers, engagement trend]

Offline/Events:
- Trade Shows/Conferences: [$X, list major events with dates]
- Direct Mail: [$X]
- PR/Earned Media: [describe share of voice trend]

Product/Growth:
- Free Trial/Freemium signups: [volume by month]
- Referral/Word-of-Mouth: [estimated — if tracked]

EXTERNAL VARIABLES (critical for model accuracy):
- Competitor activity: [known competitor campaigns, funding events, product launches — with dates]
- Macro economic indicators: [GDP growth, industry growth rate, relevant indices]
- Pricing changes: [date and magnitude of any price changes]
- Product changes: [major feature launches, packaging changes]
- Seasonality dummies: [flag holiday periods, fiscal year patterns, industry events]

MMM ANALYSIS REQUIRED:

**Section 1: Revenue Decomposition**
Decompose total revenue into:
- Base revenue (what you'd generate with zero marketing spend — brand equity, word-of-mouth, organic)
- Incremental revenue by channel (what each channel is actually driving)
- External factor contribution (seasonality, macro, competitive)
Show as: (a) absolute $ contribution, (b) % of total revenue, (c) $ per $1 spent (ROI multiplier)

Apply adstock transformations per channel:
- Short-decay channels (Search, Retargeting): 1–2 week half-life
- Medium-decay channels (Paid Social, Email): 2–4 week half-life
- Long-decay channels (Brand, Events, PR, Content): 8–16 week half-life
Explain your decay assumptions and flag where you'd want more data to refine them.

**Section 2: Saturation Curve Analysis**
For each channel, model the diminishing returns curve:
- Current operating point: where on the saturation curve is the channel (ascending/plateau/diminishing)?
- Saturation threshold: estimated spend level where marginal ROI approaches 1x
- Optimal spend range: where marginal ROI is highest (typically 2–5x target)
- Overspend indicator: channels spending above saturation threshold
- Underspend indicator: channels with steep ascending curves (room to scale)

Present as a table:
| Channel | Current Spend | Current ROI | Saturation Point | Optimal Spend | Over/Under? |
|---------|--------------|-------------|-----------------|---------------|-------------|

**Section 3: Cross-Channel Interaction & Halo Effects**
Analyze:
- Synergy pairs: which channel combinations produce multiplicative (not just additive) lift?
  - Common: Paid Social + Email (retargeting warm audiences), Events + SDR Outreach, Content/SEO + Paid Search
- Attribution displacement: which channels are stealing credit from others in last-touch models but actually function as assist channels?
- Brand vs. performance balance: what % of spend is building long-term brand equity vs. driving immediate response? Recommend optimal ratio for your business stage.

**Section 4: Budget Optimization Scenarios**
Model the following scenarios using your marginal ROI curves:

SCENARIO A — Flat Budget Reallocation (same total, optimal mix):
- Show current allocation vs. AI-recommended allocation
- Project revenue uplift from reallocation alone
- Show which channels gain/lose budget and by how much

SCENARIO B — 20% Budget Increase (growth mode):
- Where should incremental $X be deployed for highest marginal ROI?
- Project incremental revenue from new spend
- Flag any channels where new spend would immediately hit saturation

SCENARIO C — 20% Budget Cut (efficiency mode):
- Which channels should be cut and in what order (lowest marginal ROI first)?
- Project revenue impact of cuts
- Identify the "floor" below which cuts would have outsized negative impact

SCENARIO D — Channel Pause Test:
- Model the impact of pausing each major channel for 30/60/90 days
- Estimate revenue at risk
- Identify channels with highest vs. lowest revenue at risk per $ paused

Present all scenarios in a comparison table:
| Scenario | Total Spend | Projected Revenue | Revenue Uplift vs. Baseline | ROI |

**Section 5: Holdout Testing Roadmap**
Design a geo-based or time-based holdout experiment to validate the MMM:
- Select 2–3 channels most important to validate (typically the 2 largest spend channels)
- Design a geographic split test: test markets vs. control markets
- Recommend holdout duration (typically 4–8 weeks for short-cycle, 8–16 weeks for enterprise)
- Define success metrics and minimum detectable effect
- Outline how to reconcile holdout results with MMM predictions
- Identify risks (test contamination, seasonality overlap, market size differences)

**Section 6: Model Confidence & Data Quality Assessment**
Be explicit about model confidence:
- Data sufficiency score: how many observations do we have vs. ideal (52+ weeks preferred)?
- Variable completeness: which external variables are missing and would most improve the model?
- Identified data gaps by channel: channels with incomplete or unreliable spend data
- Confidence intervals: where are predictions tight vs. wide?
- Top 3 assumptions that, if wrong, would most change the recommendations
- Recommended data collection improvements for next model iteration

**Section 7: Institutional Memory — Channel Truth Table**
Synthesize findings into a permanent reference:
For each channel, create a "channel truth card":
- Revenue contribution (% of total)
- Efficiency (ROI multiplier)
- Lag/Decay (how long does the effect last?)
- Saturation status (room to scale vs. at limit)
- Interaction effects (what does it amplify?)
- Strategic role (Acquisition / Awareness / Retention / Assist)
- Recommended investment posture: Grow / Hold / Reduce / Test

**OUTPUT REQUIREMENTS:**
- Executive summary: 200 words, board-ready, focused on "what should we do with our budget?"
- All analysis in labeled sections with tables
- Budget reallocation tables with current vs. recommended columns
- Revenue projections with confidence ranges (not point estimates)
- Holdout test plan as a structured brief
- Final prioritized action list: Top 10 budget decisions ranked by expected revenue impact

CONSTRAINTS:
- Do not use vanity metrics (impressions, clicks) as model outputs — focus on revenue and pipeline
- All ROI estimates must show assumption and calculation methodology
- Where data is insufficient, bound the uncertainty explicitly rather than false precision
- Recommendations must be actionable in next budget cycle without requiring new marketing technology
- Distinguish between short-term performance optimization and long-term brand investment tradeoffs

## Example Input/Output

**Input Example:**

Company: Vanterra (B2B SaaS, Series C, $22M ARR, $85K ACV)
Period: Jan 2024 – Dec 2024 (monthly data)
Annual marketing spend: $3.2M across 6 channels
Revenue data: Monthly new ARR ranging from $1.1M (Jan) to $2.4M (Dec)

Channel spend breakdown:
- Google Search (brand + non-brand): $680K
- LinkedIn Ads: $920K
- Meta Ads: $240K
- Webinars & Events: $480K
- Content/SEO (agency + tools): $180K
- Email/Marketing Automation (fully-loaded): $120K
- SDR Outbound (marketing portion): $580K

External factors: Series C announcement in April drove 3x organic traffic spike in May; competitor Acme raised Series D in September; fiscal year-end buying surge in Q4.

---

**Output Example (abbreviated):**

**EXECUTIVE SUMMARY**
Vanterra's $3.2M 2024 marketing investment generated approximately $19.4M in new ARR, with a blended marketing ROI of 6.1x. However, spend allocation is suboptimal: LinkedIn Ads (29% of budget) is operating at saturation — marginal ROI has dropped to 1.8x vs. 4.2x for Webinars/Events and 7.1x for Content/SEO. Google Search remains efficient for brand defense ($280K brand portion) but non-brand search ($400K) shows declining efficiency at 2.1x. Recommended reallocation: shift $320K from LinkedIn and Meta toward Webinars and Content, projecting $2.1M incremental ARR with flat total spend.

**Revenue Decomposition — 2024**

| Channel | Spend | Attributed Revenue | ROI | % of Total Revenue | Saturation Status |
|---------|-------|-------------------|-----|-------------------|-----------------|
| Content/SEO | $180K | $1.28M | 7.1x | 6.6% | Under-invested ↑ |
| Events/Webinars | $480K | $2.02M | 4.2x | 10.4% | Optimal — room to scale |
| Google Search (brand) | $280K | $1.12M | 4.0x | 5.8% | Optimal |
| SDR Outbound | $580K | $2.15M | 3.7x | 11.1% | At capacity |
| Google Search (non-brand) | $400K | $840K | 2.1x | 4.3% | Declining returns |
| LinkedIn Ads | $920K | $1.66M | 1.8x | 8.6% | Saturating ↓ |
| Meta Ads | $240K | $336K | 1.4x | 1.7% | Over-invested |
| Email Marketing | $120K | $1.54M | 12.8x | 7.9% | Under-invested ↑ |
| Base/WOM/Organic | — | $8.44M | — | 43.5% | — |

**Key Insight:** Email is the most efficient channel at 12.8x ROI but receives only 3.8% of budget — a significant misallocation. Increasing email investment by $60K (automated nurture sequences, better segmentation tooling) projects $768K incremental ARR.

**Optimal Budget Reallocation — Flat Budget Scenario**

| Channel | Current Spend | Recommended Spend | Change | Projected Revenue Impact |
|---------|--------------|------------------|--------|------------------------|
| Content/SEO | $180K | $320K | +$140K | +$994K ARR |
| Webinars/Events | $480K | $600K | +$120K | +$504K ARR |
| Email/Automation | $120K | $180K | +$60K | +$768K ARR |
| Google Search Brand | $280K | $300K | +$20K | +$80K ARR |
| SDR Outbound | $580K | $560K | -$20K | -$74K ARR |
| Google Non-Brand | $400K | $280K | -$120K | -$252K ARR |
| LinkedIn Ads | $920K | $760K | -$160K | -$288K ARR |
| Meta Ads | $240K | $0 | -$240K | -$336K ARR |
| **Total** | **$3.2M** | **$3.2M** | — | **+$1.40M net ARR** |

## Success Metrics

- Revenue decomposition accounts for ≥80% of total revenue (base + channel contributions + external factors sum to ≥80% of actual)
- Saturation analysis identifies at least 2 over-invested and 2 under-invested channels
- Budget reallocation scenario projects ≥10% revenue improvement from flat-budget optimization
- Holdout test design is specific enough to execute (markets identified, duration set, KPIs defined)
- Model confidence section explicitly states 3+ assumptions and their sensitivity
- Executive summary passes the "CFO test": can be read in 60 seconds and answers "where should we put the next $100K?"

## Related Prompts

- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-Budget-Defense-&-CFO-Finance-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-(PPC-&-Social)/Cross-Channel-Paid-Media-Budget-Allocation-&-ROAS-Optimization-Engine.md`

## Integration Tips

- **Google Sheets / Excel:** Structure your input data as a weekly or monthly time series table (dates as rows, channels as columns). Export from your ad platforms and CRM into this format. The prompt works directly with pasted tabular data or a structured description of your data.
- **HubSpot:** Export "Revenue by Original Source" and "Revenue by Latest Source" reports as CSV. Combine with ad platform spend exports. For B2B, use Deal pipeline data (closed-won by month) as your revenue signal.
- **Salesforce:** Build a custom report: Closed Won Opportunities by Close Month + Primary Campaign Source. Export to CSV. Supplement with spend data from your marketing finance tracking sheet.
- **Google Analytics 4:** Export "Session default channel group" data with associated goal completions/conversions by month. Use as a top-of-funnel signal alongside CRM revenue data.
- **Northbeam / Triple Whale / Rockerbox:** If you use a paid attribution tool, export its "spend vs. revenue contribution" model as a starting dataset. Use the MMM to cross-validate and identify where last-touch models are distorting investment decisions.
- **Notion/Confluence:** Publish the Channel Truth Table (Section 7) as a standing reference document in your marketing wiki. Update quarterly after each MMM refresh.
- **Looker/Tableau/Power BI:** Feed the Revenue Decomposition table and Saturation Curve data into your BI tool to create an MMM dashboard. Automate monthly data pulls from ad platforms via API to keep the model current.
- **Zapier/Make:** Automate: Monthly → pull spend from Google Ads, Meta Ads, LinkedIn Ads APIs → aggregate in Google Sheets → trigger AI MMM refresh → post summary to Slack #marketing-analytics channel.

## Troubleshooting

**Problem: "I only have 6–12 months of data — is that enough for an MMM?"**
Solution: 6–12 months is below the 52-week ideal but still workable with caveats. The prompt will flag confidence intervals as wider than ideal. Focus on channels where you have the most complete data. Prioritize the Holdout Testing Roadmap section — with limited historical data, running a 6–8 week geo test to validate 2–3 channels will generate better evidence than extending the historical model. Supplement with industry benchmarks for channels where your own data is thin (e.g., "Content/SEO typically has 8–12 week adstock decay in B2B SaaS").

**Problem: "The model says Meta Ads are inefficient but our social team swears they drive pipeline"**
Solution: This is the most common MMM conflict. Use the Cross-Channel Interaction section to test whether Meta is functioning as an assist channel (amplifying LinkedIn or Search conversions) rather than a standalone revenue driver. Run a 4-week Meta pause test in one geographic market while maintaining spend in another. If pipeline drops in the pause market beyond the MMM prediction, Meta has unmeasured assist value. If it doesn't drop, the MMM was right. Document the test and use the data to end the debate with evidence.

**Problem: "My revenue has a strong seasonal spike that's drowning out the channel signals"**
Solution: Include explicit seasonality dummy variables in your data input (e.g., flag Q4 as "1" and other quarters as "0", or flag your peak months). Describe any known seasonal drivers in the External Variables section. Ask the model to decompose seasonality as its own revenue component before attributing the remainder to channels. If you have 2+ years of data, the model can better separate seasonal baseline from channel-driven lift.

## Version History
- v1.0: Initial creation (auto-generated)
