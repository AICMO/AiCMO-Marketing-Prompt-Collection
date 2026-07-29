# AI-Powered B2B SaaS Marketing Program Win-Rate Attribution & Revenue-Influenced Pipeline Conversion Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, analytics, win-loss, attribution, revenue-intelligence, pipeline, saas

## Overview
This engine systematically analyzes which marketing programs, channels, content assets, and campaign touches are most strongly associated with pipeline that converts to closed-won revenue — versus pipeline that stalls or closes-lost. It produces actionable marketing investment decisions grounded in actual win-rate data, not just pipeline volume.

## Quick Copy-Paste Version

You are a B2B SaaS revenue intelligence analyst. I need you to analyze my marketing program win-rate attribution data and produce a ranked report of which marketing investments drive the highest percentage of closed-won revenue.

Here is my data:
- CRM export of closed-won and closed-lost deals from the last 12 months: [PASTE DATA OR DESCRIBE]
- Marketing attribution data (first touch, last touch, multi-touch) by deal: [PASTE DATA OR DESCRIBE]
- Content asset engagement by deal (which pieces were consumed before/during the deal): [PASTE DATA OR DESCRIBE]
- Program/channel breakdown: [e.g., paid search, organic, webinar, ABM, field events, email nurture, SEO content, review sites, social]

Analyze this data across the following dimensions:

1. WIN RATE BY CHANNEL (first-touch and multi-touch):
   - Rank each marketing channel by closed-won rate, not just lead volume
   - Identify channels that generate high-volume but low-win-rate pipeline vs. low-volume but high-win-rate pipeline
   - Flag any channels with win rates more than 15% above/below the company average

2. WIN RATE BY CONTENT ASSET:
   - Which content assets (case studies, white papers, demos, webinars, ROI calculators) appear most frequently in won deals?
   - Which content assets are consumed by churned pipeline? (loss indicators)
   - Identify the "win content stack" — the content sequence most correlated with closed-won

3. WIN RATE BY CAMPAIGN/PROGRAM:
   - Rank campaigns by win rate, deal velocity, and average deal size for influenced pipeline
   - Identify which programs contribute to Tier 1 accounts (ICP fit) winning vs. off-ICP pipeline
   - Highlight programs that correlate with competitive wins vs. losses

4. DEAL VELOCITY CORRELATION:
   - Do deals touched by certain programs close faster or slower?
   - What is the average sales cycle length for deals with 1 vs. 3 vs. 5+ marketing touches before opportunity creation?
   - Identify the "velocity accelerators" — marketing touches that shorten time-to-close

5. SEGMENTED WIN RATES:
   - Break down win rates by: deal size (SMB/Mid-Market/Enterprise), vertical, and competitor presence
   - Are some programs disproportionately strong in specific segments?

6. INVESTMENT RECOMMENDATIONS:
   - Based on win-rate data, which programs deserve budget increases?
   - Which programs should be restructured or cut despite high lead volume?
   - What is the projected win-rate improvement if budget is reallocated from low-win-rate to high-win-rate programs?

Produce a structured report with: executive summary (3 bullets), ranked program scorecard, top 5 actionable recommendations, and a proposed budget reallocation scenario.

## Advanced Customizable Version

ROLE: You are a senior revenue intelligence analyst embedded in the marketing operations function of a B2B SaaS company. You specialize in marketing-attribution win-loss analysis — the practice of correlating marketing program engagement patterns with actual deal outcomes, not just pipeline creation.

CONTEXT:
Company: [COMPANY NAME]
Product: [PRODUCT DESCRIPTION — e.g., "B2B sales intelligence platform for enterprise revenue teams"]
ACV: [AVERAGE CONTRACT VALUE — e.g., "$45,000"]
Sales cycle: [AVERAGE LENGTH — e.g., "90 days"]
ICP: [IDEAL CUSTOMER PROFILE — e.g., "VP Sales at Series B+ SaaS companies, 50-500 employees"]
Primary competitors: [COMPETITORS — e.g., "ZoomInfo, Apollo, Lusha"]
Marketing programs active: [LIST — e.g., "Google Ads, content/SEO, ABM, field events, outbound SDR, LinkedIn organic, review sites, webinars, email nurture"]
CRM: [e.g., Salesforce, HubSpot]
Attribution model: [e.g., "first-touch, last-touch, W-shaped, Markov chain"]
Data period: [e.g., "Jan 2025 – Jun 2026, 340 closed deals (210 won, 130 lost)"]

INPUT DATA (provide all that are available):
- Closed-won and closed-lost deal export with: deal ID, ACV, stage dates, close date, competitor, vertical, deal source, account segment
- Marketing attribution touchpoints per deal: program name, channel, campaign, content asset, date, touch type (first/mid/last)
- Content engagement log: which assets were viewed/downloaded per account, by deal stage
- Campaign-level metadata: spend per program (if available), campaign dates, campaign type

ANALYTICAL FRAMEWORK:

PHASE 1 — WIN RATE BASELINE
Establish the baseline win rate across all pipeline. Then segment by:
- Channel (paid, organic, outbound, event, partner, referral)
- ICP fit tier (Tier 1 / Tier 2 / Tier 3 accounts)
- Deal size band
- Vertical
Apply Chi-square or Fisher's exact test logic to flag statistically significant win-rate differences (minimum 20 deals per cell for reliability; flag smaller samples).

PHASE 2 — MARKETING TOUCH INFLUENCE ANALYSIS
For each marketing program and content asset:
- Calculate "win influence rate" = % of closed-won deals that had a touch from this program (vs. % of closed-lost deals with same touch)
- Calculate "win lift" = (win rate when program touched) / (baseline win rate) — values above 1.3x are material
- Segment win lift by: deal stage when touch occurred (pre-opportunity, early-stage, mid-stage, late-stage)
- Apply decay weighting if using time-sensitive attribution (touches closer to close date weighted higher)

PHASE 3 — CONTENT ASSET WIN-LOSS CORRELATION
Map content engagement to deal outcomes:
- Build a "win content fingerprint" — the combination of content types consumed most frequently by closed-won accounts
- Build a "stall content pattern" — content consumed by deals that go dark or extend beyond expected cycle length
- Identify "loss content signals" — assets viewed disproportionately by closed-lost accounts (may indicate unresolved objections or wrong-fit content)
- ROI calculator, competitive comparison pages, and technical documentation: are these deal-closers or deal-staller indicators?

PHASE 4 — COMPETITIVE WIN-LOSS BY MARKETING PROGRAM
For deals with known competitors:
- Which marketing programs are associated with competitive wins vs. losses?
- Are certain programs effective vs. Competitor A but not Competitor B?
- Do competitive displacement campaigns show measurably higher win rates against targeted competitors?
- Correlation between sales battlecard content consumption and competitive win rate

PHASE 5 — VELOCITY ANALYSIS
- Sales cycle length distribution by number of pre-opportunity marketing touches (0 touches, 1-2, 3-5, 6+)
- Identify "velocity programs" — programs where touched deals close on average 20%+ faster
- Time-between-touches analysis: what cadence of marketing engagement correlates with fastest close?

PHASE 6 — INVESTMENT SCENARIO MODELING
Using win-rate data:
Scenario A — "Win-Rate Optimization": Reallocate budget from programs in the bottom quartile of win rate to top-quartile programs. Model projected win rate change if pipeline mix shifts.
Scenario B — "Segment Specialization": Double down on programs that over-perform in your highest-ACV segment. Model ARR impact.
Scenario C — "Velocity Focus": Prioritize programs that shorten sales cycle. Model CAC payback period improvement.

OUTPUT FORMAT:
1. Executive Summary (4 bullets: key finding, biggest opportunity, biggest waste, recommended action)
2. Program Win-Rate Scorecard (table: Program | Win Rate | Win Lift vs. Baseline | Avg ACV | Avg Deal Velocity | Volume | Recommendation)
3. Content Win-Loss Fingerprint (which content sequences predict wins vs. losses)
4. Competitive Win-Rate by Program (if competitive data available)
5. Top 5 Prioritized Recommendations (ranked by expected ARR impact, with confidence level)
6. Budget Reallocation Scenario (current vs. recommended allocation, projected win rate delta)
7. Data Quality Gaps (flag any analysis limited by sample size or missing attribution data)

CONSTRAINTS:
- Flag any program with fewer than 15 deals attributed — results are directional only
- Do not recommend cutting any program without 90-day ramp-up time noted for replacement
- Account for the "dark funnel" — some high-performing programs may have unmeasured influence; note where this is likely
- Distinguish between "marketing generated" pipeline (marketing source) and "marketing influenced" pipeline (marketing touch on sales-generated source)

## Example Input/Output

**Example Company:** Stackify — a B2B SaaS platform for DevOps and application performance monitoring, targeting engineering managers and CTOs at mid-market software companies. ACV $28,000, 75-day average sales cycle.

**Example Input:**
Marketing programs: Google Ads (paid), technical blog/SEO, quarterly virtual DevOps summit, outbound SDR (non-marketing), LinkedIn organic, G2 review site, product documentation/free trial, monthly newsletter
Closed deals (last 12 months): 180 won, 97 lost
Competitors present in lost deals: Datadog (41), New Relic (22), Dynatrace (18), other (16)
Attribution model: W-shaped (40% first, 40% last, 20% distributed across middle)

**Example Output (abbreviated):**

**Executive Summary:**
- Technical blog/SEO touches appear in 67% of won deals vs. 38% of lost deals — the single highest win-lift channel (1.76x baseline)
- Google Ads generates 31% of pipeline volume but only a 38% win rate vs. 52% company average — likely attracting bottom-of-ICP accounts
- DevOps Summit attendees close at a 71% win rate with 22% faster deal velocity — the highest-ROI program per dollar
- Recommendation: Shift 25% of Google Ads budget to technical content production and event amplification

**Program Scorecard (excerpt):**
| Program | Win Rate | Win Lift | Avg ACV | Avg Cycle | Volume | Recommendation |
|---|---|---|---|---|---|---|
| Technical Blog/SEO | 68% | 1.76x | $31,200 | 61 days | 89 deals | Increase investment |
| DevOps Virtual Summit | 71% | 1.83x | $33,800 | 58 days | 52 deals | Increase frequency |
| Google Ads | 38% | 0.73x | $22,100 | 84 days | 112 deals | Restructure targeting |
| G2 Review Site | 64% | 1.23x | $29,400 | 67 days | 44 deals | Maintain + amplify |
| LinkedIn Organic | 59% | 1.13x | $30,100 | 69 days | 31 deals | Maintain |
| Email Newsletter | 61% | 1.17x | $28,900 | 70 days | 28 deals | Maintain |

**Content Win Fingerprint:**
Won deals most commonly consumed: technical benchmark report → product documentation → ROI calculator → customer case study (engineering team).
Loss pattern: Accounts that viewed only top-of-funnel blog posts and never engaged with product docs or case studies churned out of pipeline at 2.4x the rate of accounts that consumed technical depth content.

## Success Metrics

Your analysis output is high-quality if it:
- Identifies at least 2 programs with statistically meaningful win-rate differentiation (±15% vs. baseline)
- Produces a content sequence recommendation that differs from current content strategy
- Quantifies the ARR impact of a realistic budget reallocation (not just a ranking)
- Identifies at least one "hidden high-performer" — a low-volume program with outsized win rate
- Provides a data quality assessment noting where conclusions are directional vs. confident

## Related Prompts

- [Win-Loss Analytics Program Architecture](./AI-Powered-B2B-SaaS-Win-Loss-Analytics-Program-&-Competitive-Revenue-Intelligence-Engine.md)
- [Deal Win Pattern Intelligence](./AI-Powered-B2B-SaaS-Deal-Win-Pattern-Intelligence-&-Revenue-Replication-Analytics-Engine.md)
- [Marketing Mix Modeling & Budget Optimization](../../05_Analytics-&-Performance/Marketing-Mix-Modeling-&-Budget-Optimization/AI-Powered-B2B-SaaS-Marketing-Mix-Modeling-&-Budget-Optimization-Intelligence-Engine.md)
- [ABM Program Measurement & Revenue Attribution](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Program-Measurement-&-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

**Salesforce:** Use SFDC reports to export opportunities with campaign influence history (Campaigns > Campaign Influence report type). Join with content engagement data from Marketo or HubSpot activity logs. Schedule a monthly Salesforce report refresh to keep win-rate data current.

**HubSpot:** Use the "Contact Activity" export + "Deal Attribution" report. Enable multi-touch attribution in HubSpot Marketing Hub → Reports → Attribution. Export deals with all associated marketing activities to a Google Sheet for analysis.

**Gong / Chorus:** Pull "topics discussed" data from call recordings and correlate with deal outcome. Gong's "trackers" feature can flag competitive mentions — join this with win/loss data to see if competitor mentions in early calls correlate with loss rate.

**Looker / Tableau / Metabase:** Build a persistent win-rate-by-program dashboard. Create a calculated field: `win_rate = COUNT(closed_won) / (COUNT(closed_won) + COUNT(closed_lost))` grouped by program. Set up automated weekly email of the dashboard to CMO and VP Sales.

**Google Sheets / Zapier:** If you lack a BI tool, use Zapier to push new closed deals from your CRM to a Google Sheet, with deal source and outcome columns pre-populated. Use SUMIF/COUNTIF formulas to build a live win-rate-by-channel tracker with zero coding.

**Segment / Customer Data Platform:** If using Segment, create a "deal_closed" event that fires on opportunity stage change, including all associated marketing source data. This enables real-time win-rate tracking per program without manual exports.

## Troubleshooting

**Problem: Most deals have "direct" or "unknown" as the marketing source, making channel analysis impossible.**
Fix: Retroactively audit last-touch attribution using CRM email activity logs, form submissions, and reverse IP lookup for web visits. For future deals, enforce UTM parameter governance on all marketing links (see UTM Campaign Tracking Governance Engine). Even a 60% attribution coverage rate is sufficient for directional win-rate analysis.

**Problem: Sample sizes are too small — most programs have fewer than 15 attributed deals.**
Fix: Extend the analysis window to 18-24 months, or aggregate similar programs (e.g., all paid social → "Paid Social" category). Flag all results as directional and increase confidence thresholds before making budget cuts. Use win-rate ranges (±10%) rather than point estimates for small samples.

**Problem: The analysis shows high win rates for low-volume programs that are hard to scale.**
Fix: Distinguish between "win rate" and "win rate × volume" (total closed-won deals contributed). A program with 80% win rate on 5 deals is not inherently better than a 55% win rate on 60 deals. Present both metrics and help leadership understand the scaling constraints of each program before recommending investment increases.

## Version History
- v1.0: Initial creation (auto-generated)
