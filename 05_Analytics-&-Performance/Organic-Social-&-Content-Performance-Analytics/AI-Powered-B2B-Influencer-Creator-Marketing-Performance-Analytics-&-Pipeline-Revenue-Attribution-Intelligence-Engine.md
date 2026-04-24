# AI-Powered B2B Influencer & Creator Marketing Performance Analytics & Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** influencer-marketing, creator-economy, b2b, analytics, pipeline-attribution, revenue-intelligence

## Overview
This prompt transforms raw B2B influencer and creator marketing data into a full revenue attribution framework — mapping creator partnerships (LinkedIn thought leaders, newsletter writers, podcasters, YouTube educators) to pipeline contribution, deal influence, and cost-per-pipeline-dollar. Use it when you need to prove creator program ROI to CFOs, optimize creator mix, or scale a B2B influencer program with confidence.

## Quick Copy-Paste Version

You are a B2B marketing analytics expert specializing in creator and influencer program measurement. Analyze my creator marketing program performance and produce a complete revenue attribution report.

INPUT DATA (paste yours):
- Creator partnerships active: [list creators, category, spend per month]
- Attribution window: [30/60/90 days]
- CRM pipeline data: [deals influenced, deal source tags, MQL count by creator UTM]
- Content performance: [impressions, clicks, CTR, engagement rate per creator]
- Audience quality signals: [ICP match %, company size distribution, seniority mix of engaged audience]

PRODUCE THE FOLLOWING ANALYSIS:

1. CREATOR ROI SCORECARD
For each creator, calculate:
- Cost per ICP Impression (CPII) = Spend ÷ (Impressions × ICP Match %)
- Cost per MQL = Spend ÷ MQLs attributed
- Pipeline Influenced = sum of open deal values where creator touchpoint appears in attribution path
- Pipeline ROI = Pipeline Influenced ÷ Spend

2. ATTRIBUTION METHODOLOGY
Apply a weighted multi-touch model:
- First-touch (creator introduces brand): 40% credit
- Mid-funnel assist (creator accelerates consideration): 30% credit
- Last-touch influence (creator cited in buying decision): 30% credit
Flag any creators with zero attribution — determine if tracking is broken or genuinely zero-impact.

3. AUDIENCE QUALITY SCORING
Score each creator's audience 1-10 using:
- % of followers matching ICP job title/seniority
- % of followers at target account size ($50M+ revenue or 200+ employees for typical enterprise B2B)
- Engagement-to-ICP ratio (engaged ICPs ÷ total engaged audience)

4. CONTENT FORMAT PERFORMANCE
Break down performance by format: sponsored posts, newsletter placements, podcast mentions, video integrations, webinar co-hosts. Rank by cost-efficiency for pipeline generation.

5. CREATOR PROGRAM RECOMMENDATIONS
- Top 3 creators to double down on (highest pipeline ROI)
- Top 3 creators to cut or renegotiate (low ICP quality or zero attribution)
- Recommended budget reallocation table
- Suggested new creator archetypes to test based on ICP targeting gaps

6. EXECUTIVE SUMMARY (3 bullets, board-ready)
State total program spend, total pipeline influenced, blended pipeline ROI, and #1 action.

Format all output as structured tables where data-driven, with a plain-English insight after each section. Flag any data gaps that would improve accuracy.

## Advanced Customizable Version

ROLE: You are a Senior Marketing Analytics Director with 15+ years in B2B SaaS, specializing in creator/influencer program measurement, multi-touch attribution, and CFO-ready ROI reporting. You apply frameworks from Forrester's B2B Influence research, the 6sense demand unit model, and Gartner's buyer journey analytics.

CONTEXT:
Company: [Your Company]
Product: [B2B SaaS product / category]
ICP: [Job title | Company size | Industry | Key pain point]
Creator program stage: [Testing / Scaling / Optimizing]
Total monthly creator spend: $[X]
Measurement stack: [HubSpot/Salesforce + UTM tracking / 6sense / Metadata / Other]
Attribution model in CRM: [First touch / Last touch / Multi-touch / Custom]
Reporting audience: [CMO + CFO / Marketing team / Board]

CREATOR PORTFOLIO INPUT:
[Paste table: Creator Name | Platform | Category (LinkedIn thought leader / Newsletter / Podcast / YouTube) | Monthly Spend | Audience Size | ICP Audience % | Monthly Impressions | Clicks | MQLs | Open Pipeline Influenced | Closed-Won Influenced]

OBJECTIVE:
Produce a complete B2B Creator Marketing Revenue Intelligence Report with:

---

SECTION 1: PORTFOLIO PERFORMANCE MATRIX

Build a 2×2 creator prioritization matrix:
- X-axis: Audience ICP Quality Score (0-100, weighted: 40% job title match, 35% company size, 25% seniority)
- Y-axis: Pipeline ROI (Pipeline Influenced ÷ Monthly Spend)

Quadrants:
- SCALE: High ICP Quality + High Pipeline ROI → increase investment 50-100%
- DEVELOP: High ICP Quality + Low Pipeline ROI → attribution tracking audit + content optimization
- MONITOR: Low ICP Quality + High Pipeline ROI → investigate for ICP drift, set quality guardrails
- CUT: Low ICP Quality + Low Pipeline ROI → exit within 60 days

For each creator, assign quadrant and recommended action.

---

SECTION 2: MULTI-TOUCH ATTRIBUTION DEEP DIVE

Apply a weighted revenue influence model:
- Awareness stage touchpoints (creator content seen before any CRM activity): 25% credit, tag as "brand conditioning"
- Education stage (creator content consumed during active evaluation — 30-90 day pre-MQL window): 35% credit
- Consideration stage (creator touchpoint within 30 days of demo request or MQL): 40% credit

For each open and closed-won deal with creator attribution:
- List touchpoint sequence (first creator exposure → other channels → conversion event)
- Calculate creator's fractional pipeline credit
- Flag deals where creator was the SOLE attribution path (critical dependency signal)

Produce: "Creator Influenced Pipeline Waterfall" — from Impressions → ICP Impressions → Content Engagements → UTM Clicks → MQLs → SALs → SQLs → Closed Won. Calculate conversion rates at each stage, benchmark against your non-creator inbound channels.

---

SECTION 3: CONTENT FORMAT × CREATOR CATEGORY ANALYSIS

For each combination of [Creator Category] × [Content Format], calculate:
- Blended engagement rate
- Cost per engaged ICP
- MQL conversion rate from that format
- Average deal size influenced

Formats to analyze: organic post mentions, dedicated sponsored posts, newsletter placements, podcast integrations (host-read vs. pre-roll), YouTube integrations, LinkedIn Live co-hosting, webinar guest appearances.

Produce a ranked heat map: which format × creator category combination produces the lowest cost-per-MQL and highest average deal size.

---

SECTION 4: CREATOR AUDIENCE OVERLAP & SATURATION ANALYSIS

Check for:
1. AUDIENCE CANNIBALIZATION: Do multiple creators have overlapping audiences? (If Creator A and Creator B share 40%+ of their engaged audience, you are paying twice to reach the same people.)
2. FREQUENCY SATURATION: What is the estimated impressions-per-target-account per month? If target accounts are seeing 8+ creator touchpoints monthly, test a reduced frequency cap.
3. WHITESPACE: Which ICP segments (by job title, industry, or company size) are underserved by current creator coverage? List top 3 audience gaps.

---

SECTION 5: PREDICTIVE CREATOR PROGRAM SCALING MODEL

Given current performance data, model three scenarios for next quarter:

SCENARIO A — Maintain current spend: Project MQLs, pipeline, and closed-won assuming 0% budget change.

SCENARIO B — Scale top performers (+40% budget to Scale quadrant creators): Project incremental pipeline using current Pipeline ROI rates, apply a 20% efficiency discount for scale.

SCENARIO C — Full program optimization (cut Cut quadrant, double Scale quadrant, add 2 new creators): Model budget reallocation, projected MQL uplift, projected pipeline impact.

For each scenario: Total Spend | Projected MQLs | Projected Pipeline Influenced | Projected Closed-Won | Expected Blended Pipeline ROI.

---

SECTION 6: TRACKING & MEASUREMENT INTEGRITY AUDIT

Review the provided attribution data and flag:
- Creators with high engagement but zero UTM-attributed MQLs (likely tracking gap — dark social, email forwarding, or UTM stripping)
- Time-to-MQL lag analysis: what is the average days from first creator exposure to MQL? (B2B influencer attribution typically requires 45-90 day windows)
- Recommended UTM structure for creator campaigns: utm_source=creator|utm_medium=influencer|utm_campaign=[creator-name]|utm_content=[format]
- Suggested CRM workflow for tagging creator-influenced deals at each pipeline stage

---

SECTION 7: EXECUTIVE SUMMARY & CFO-READY ROI STATEMENT

Produce a 5-sentence board-ready summary:
1. Total program investment and total pipeline influenced
2. Blended pipeline ROI and closed-won revenue attributable to creator program
3. Top-performing creator (name, ROI, pipeline contribution)
4. Biggest opportunity identified
5. Recommended next action with expected 90-day pipeline impact

Then produce a one-line CFO soundbite: "For every $1 invested in creator marketing, we generate $X in influenced pipeline and $Y in closed revenue."

OUTPUT FORMAT:
- All data in structured tables
- Insights in plain English below each table
- Executive Summary in a clearly labeled final section
- Flag all data gaps with [DATA NEEDED: description] tags
- Include confidence level (High/Medium/Low) for each attribution claim based on tracking completeness

## Example Input/Output

**Input Example:**

Company: Velaris AI (B2B SaaS, customer success platform)
ICP: VP Customer Success / Head of CS | 200-2,000 employee SaaS companies | North America
Monthly Creator Budget: $18,000/month
Creators:
| Creator | Platform | Category | Spend/mo | Audience | ICP% | Impressions | MQLs | Open Pipeline |
|---|---|---|---|---|---|---|---|---|
| Jason Lemkin | LinkedIn | CS/SaaS Thought Leader | $6,000 | 180K | 62% | 45,000 | 12 | $380,000 |
| CS Insider Newsletter | Newsletter | CS Practitioners | $4,000 | 28,000 | 78% | 28,000 | 9 | $290,000 |
| The Retention Lab Pod | Podcast | CS Leaders | $3,500 | 12,000 | 84% | 12,000 | 7 | $240,000 |
| SaaStr Clips (YouTube) | YouTube | SaaS Leadership | $2,500 | 95,000 | 31% | 18,000 | 2 | $45,000 |
| Tech Marketing Weekly | Newsletter | Marketing/CS crossover | $2,000 | 42,000 | 22% | 22,000 | 1 | $18,000 |

**Output Example (partial):**

**Portfolio Performance Matrix:**
| Creator | ICP Quality Score | Pipeline ROI | Quadrant | Action |
|---|---|---|---|---|
| Jason Lemkin | 74/100 | 63x | SCALE | Increase to $9,000/mo, add LinkedIn Live co-host |
| CS Insider Newsletter | 88/100 | 72x | SCALE | Increase to $6,000/mo, test dedicated issue sponsorship |
| The Retention Lab Pod | 91/100 | 69x | SCALE | Increase to $5,500/mo, negotiate host-read + show notes |
| SaaStr Clips | 42/100 | 18x | MONITOR | Maintain, add ICP audience quality guardrail, reassess in 60 days |
| Tech Marketing Weekly | 28/100 | 9x | CUT | Exit at contract end, reallocate to CS Insider Newsletter |

**CFO Soundbite:** "For every $1 invested in our creator marketing program, we generate $54 in influenced pipeline and $12 in closed-won revenue — a 12x return vs. our blended paid media CAC."

**Key Insight:** The top 3 creators (59% of budget) generate 94% of influenced pipeline. Reallocating the remaining 41% to scale these three would project an additional $390,000 in quarterly pipeline at current conversion rates.

## Success Metrics

- Every active creator has a calculated Pipeline ROI score (not just engagement metrics)
- Attribution window is documented and consistent (recommended: 90 days for B2B enterprise)
- Executive summary can be read in 60 seconds and includes a dollar-denominated ROI statement
- At least one data gap is identified and a fix is recommended (tracking integrity)
- Creator program has a clear prioritization decision for every partner (Scale/Develop/Monitor/Cut)
- Modeling scenarios include at least 3% efficiency discount assumptions for conservative CFO credibility

## Related Prompts

- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [AI-Powered B2B Influencer & Creator-Led Demand Generation Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-B2B-Influencer-&-Creator-Led-Demand-Generation-Intelligence-Engine.md)
- [AI-Powered B2B LinkedIn Organic Analytics & Dark Social Pipeline Attribution Intelligence Engine](../../05_Analytics-&-Performance/Organic-Social-&-Content-Performance-Analytics/AI-Powered-B2B-LinkedIn-Organic-Analytics-&-Dark-Social-Pipeline-Attribution-Intelligence-Engine.md)
- [G2 Review Mining & Voice-of-Market Competitive Intelligence Engine](../../05_Analytics-&-Performance/Demand-Sensing-&-Market-Intelligence/G2-Review-Mining-&-Voice-of-Market-Competitive-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Create a custom contact property "Creator First Touch" and a deal property "Creator Influenced" (multi-select). Build a workflow: if UTM source contains "creator" → tag contact + all associated open deals. Report in a custom report: Deals with Creator Influenced = true, grouped by Creator Name.
- **Salesforce:** Add a Campaign Influence model for creator campaigns. Set creator campaigns as Campaign Type = "Influencer." Use Salesforce's Campaign Influence Attribution Report to pull pipeline influenced by creator, then export to the prompt as input data.
- **6sense / Bombora:** Cross-reference creator-engaged accounts with 6sense intent spikes. If an account that engaged with a creator post shows 6sense "in-market" signal within 30 days, count as a creator-influenced intent signal (weighted 0.5× pipeline credit).
- **Google Sheets / Looker Studio:** Build a Creator Scorecard dashboard with monthly auto-refresh. Pull UTM data from Google Analytics 4 via Sheets connector, merge with CRM export. Update the prompt input table monthly for reanalysis.
- **Zapier:** Automate: when a deal reaches "SQL" stage in CRM → check if any associated contact has a "creator" UTM source in their first-touch field → if yes, log to a Creator Attribution Google Sheet for monthly reporting.

## Troubleshooting

**Problem:** Creators show high engagement but zero MQL attribution in CRM.
**Solution:** B2B influencer content is heavily consumed via dark social (Slack, email forwarding, direct LinkedIn DMs). Run a self-reported attribution survey at MQL form submission ("How did you first hear about us?") with creator names as options. Apply a 30-40% dark social uplift factor to engagement-to-MQL conversion estimates. Also audit UTM stripping — LinkedIn preview cards and email clients often strip UTM parameters.

**Problem:** CFO says influencer ROI numbers look too high compared to paid media benchmarks.
**Solution:** Apply the "influenced vs. sourced" distinction clearly. Influenced pipeline = creator touchpoint appeared somewhere in the buyer journey. Sourced pipeline = creator was the first trackable touch and no other channel reached the account before that point. Report both numbers separately. Sourced will be 20-40% of influenced and will be far more conservative. Lead with sourced, note influenced as supplemental.

**Problem:** Can't determine ICP audience percentage for a creator (they don't share audience demographics).
**Solution:** Run a manual sample audit: pull the last 50-100 engaged commenters/likers on the creator's recent posts, check their LinkedIn profiles for job title and company size, and calculate your own ICP match estimate. This 20-minute audit is typically accurate within ±8% of the true audience composition. Alternatively, request a sponsored post and check UTM click-through audience in LinkedIn Campaign Manager or use HubSpot contact enrichment on form submitters from that creator's UTM.

## Version History
- v1.0: Initial creation (auto-generated)
