# AI-Powered B2B Lead Source Quality Scoring & Channel Revenue Contribution Intelligence Engine - Rank Every Inbound Channel by Revenue Quality, Not Just Volume

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, analytics, lead-quality, attribution, channel-optimization, revenue-intelligence, saas, pipeline, mql, cac

## Overview
Analyzes every inbound marketing channel by a composite revenue quality score — not just lead volume — combining MQL-to-close conversion rates, average deal size, sales cycle velocity, and CAC payback by source. Use this when you need to defend channel budget decisions, diagnose which sources produce "revenue-ready" buyers vs. vanity metrics, or reallocate demand gen spend toward the highest-ROI channels.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics consultant specializing in channel-level lead quality and marketing ROI. Analyze my lead source performance data and produce a Channel Revenue Quality Scorecard with ranked investment recommendations.

My data:
- Reporting period: [last quarter / last 6 months]
- Total MQLs by source: [e.g., Organic SEO: 420, Paid Search: 310, LinkedIn Ads: 180, Events: 95, Partner: 140, Outbound SDR: 220, Direct: 75]
- MQL→SQL conversion rate by source: [e.g., Organic: 24%, Paid Search: 14%, LinkedIn: 31%, Events: 44%, Partner: 38%, SDR: 19%, Direct: 52%]
- SQL→Closed-Won rate by source: [e.g., Organic: 18%, Paid: 12%, LinkedIn: 22%, Events: 27%, Partner: 33%, SDR: 15%, Direct: 29%]
- Average deal size by source: [e.g., Organic: $38K, Paid: $22K, LinkedIn: $47K, Events: $61K, Partner: $82K, SDR: $34K, Direct: $91K]
- Average sales cycle by source: [e.g., Organic: 74 days, Paid: 51 days, LinkedIn: 88 days, Events: 102 days, Partner: 118 days, SDR: 67 days, Direct: 45 days]
- Channel spend last period: [e.g., SEO/Content: $28K, Paid Search: $41K, LinkedIn Ads: $35K, Events: $48K, Partner MDF: $22K, SDR program: $67K, Brand/Direct: $12K]

Deliver:
1. **Channel Revenue Quality Score** for each source (composite: SQL rate × Win rate × Avg Deal Size / normalized) — ranked 1 to N
2. **Revenue-Per-Lead (RPL)** and **Revenue-Per-Dollar-Spent** by channel
3. **Channel CAC and Payback Period** estimate by source
4. **Quality vs. Volume Matrix**: 2×2 chart positioning each channel (High Quality/Low Volume, High Volume/Low Quality, etc.) with strategic implication for each quadrant
5. **Budget reallocation recommendation**: which channels to scale, maintain, reduce, and test — with estimated pipeline impact
6. **Quality degradation alerts**: signals to watch that indicate a channel's lead quality is declining (engagement drop, SQL rate trend, deal size shrinkage)
7. **30/60/90-day action plan** to shift budget toward highest-revenue-quality channels without cratering total pipeline volume

Format as an executive-ready report with a ranked scorecard table, 2×2 matrix description, and specific dollar reallocation amounts.

## Advanced Customizable Version

ROLE: You are a Chief Revenue Analytics Officer with 15+ years of B2B SaaS marketing measurement experience. You apply Jobs-to-be-Done, Cohort Analysis, and Weighted Composite Scoring methodologies to rank inbound channels by true revenue contribution — not vanity metrics.

OBJECTIVE: Build a comprehensive Channel Revenue Quality Intelligence Report that enables data-driven budget reallocation from low-quality, high-volume channels to high-quality, revenue-accelerating channels.

COMPANY CONTEXT:
- Company: [Company name]
- Stage: [Series A/B/C/Enterprise/public]
- ACV range: [e.g., $15K–$250K]
- Primary ICP: [e.g., VP Engineering at 200–2,000 employee SaaS companies]
- Sales motion: [Inside sales / Field sales / PLG / Hybrid]
- Current ARR: [e.g., $18M]
- Revenue target this year: [e.g., $28M]
- Pipeline coverage ratio needed: [e.g., 3.5x]

CHANNEL DATA INPUTS:
For each channel below, provide data or mark "unknown" — the model will flag data gaps and recommend instrumentation to close them:

| Channel | MQLs | MQL→SQL% | SQL→Opp% | Opp→Won% | Avg Deal $ | Avg Cycle (days) | Spend $ | Notes |
|---|---|---|---|---|---|---|---|---|
| Organic SEO / Content | | | | | | | | |
| Paid Search (Google/Bing) | | | | | | | | |
| LinkedIn Ads | | | | | | | | |
| Meta / Instagram Ads | | | | | | | | |
| Events / Conferences | | | | | | | | |
| Webinars / Virtual Events | | | | | | | | |
| Partner / Channel Sourced | | | | | | | | |
| Outbound SDR / BDR | | | | | | | | |
| Customer Referral | | | | | | | | |
| Review Sites (G2, Capterra) | | | | | | | | |
| Direct / Brand | | | | | | | | |
| AI Search / GEO | | | | | | | | |
| Other: [specify] | | | | | | | | |

SCORING METHODOLOGY — apply this framework:

**Composite Revenue Quality Score (CRQS)** = 
  (MQL→SQL Rate × 0.20) + 
  (SQL→Won Rate × 0.25) + 
  (Normalized Avg Deal Size × 0.25) + 
  (Inverse Sales Cycle × 0.15) + 
  (Revenue Per Dollar Spent × 0.15)

Normalize each dimension to 0–100 scale before weighting. Flag any channel where data is missing and note the assumed value + confidence level.

DELIVERABLES:

**Section 1: Channel Revenue Quality Scorecard**
- Ranked table: Channel | CRQS Score | RPL | Revenue/$ Spent | CAC | Payback (months) | Verdict
- Top 3 "Hidden Gem" channels (high quality score, under-invested)
- Top 3 "Efficiency Drains" (high spend, low quality score)
- Channels with declining quality trend (if multi-period data available)

**Section 2: Strategic Channel Portfolio Matrix**
Categorize each channel across two axes — Volume Contribution (% of total MQLs) vs. Revenue Quality (CRQS):
- **Stars** (High Volume + High Quality): Protect and scale
- **Hidden Gems** (Low Volume + High Quality): Invest aggressively
- **Volume Traps** (High Volume + Low Quality): Optimize or cut
- **Laggards** (Low Volume + Low Quality): Eliminate or test alternative tactics

For each category, provide: strategic implication, specific recommended action, estimated quarterly pipeline impact.

**Section 3: Budget Reallocation Scenario Model**
Given current total demand gen budget of $[X]:
- Scenario A — "Quality Shift" (move 20% of budget from Volume Traps → Hidden Gems): model projected pipeline and revenue impact
- Scenario B — "Aggressive Rebalance" (move 35% + pause Laggards): model projected impact
- Scenario C — "Safe Optimization" (move 10% + A/B test one new channel): model impact
For each scenario: projected new MQL volume, projected new SQL volume, projected pipeline, projected closed revenue change vs. baseline, confidence level.

**Section 4: Lead Quality Early Warning System**
Define a monitoring framework — for each top channel, specify:
- Primary quality KPI to track weekly (e.g., SQL acceptance rate, win rate rolling 30-day, deal size trend)
- Yellow flag threshold (declining quality signal)
- Red flag threshold (budget pause trigger)
- Recommended investigation checklist when quality drops
- Slack/HubSpot/Salesforce alert configuration instructions

**Section 5: Instrumentation Gap Audit**
List every data point that was missing or assumed in this analysis. For each gap:
- Data source needed (CRM field, UTM parameter, revenue attribution tool)
- Effort to instrument (Low/Medium/High)
- Revenue insight unlocked by closing this gap
- Tool recommendation: HubSpot, Salesforce, Segment, Dreamdata, Triple Whale, Rockerbox, etc.

**Section 6: 90-Day Execution Roadmap**
Week-by-week action plan:
- Week 1–2: Instrumentation fixes + data validation
- Week 3–4: Budget reallocation execution (Scenario recommendation)
- Month 2: Performance monitoring + first quality check
- Month 3: Optimization cycle + board-ready channel ROI narrative

OUTPUT FORMAT:
- Executive summary (5 bullets, board-ready)
- Full Channel Quality Scorecard table
- Strategic Portfolio Matrix (described in 4 quadrants with specific channels named)
- Budget Reallocation Scenarios table
- Early Warning System dashboard spec
- Instrumentation Audit table
- 90-day roadmap
- Appendix: methodology explanation for CFO/finance review

CONSTRAINTS:
- Never recommend cutting a channel to zero without a replacement plan
- Flag when sample sizes are too small for statistical confidence (<50 MQLs per channel)
- Always calculate confidence intervals on win rate estimates
- Account for seasonality when comparing across periods
- Separate "influenced" vs. "sourced" attribution in all calculations

## Example Input/Output

**Input Example:**

Company: Vaultline Security (B2B SaaS, cybersecurity compliance automation)
ACV: $42K average, range $18K–$190K
Stage: Series B, $22M ARR, targeting $38M this FY
ICP: CISO and VP IT at 500–5,000 employee companies in financial services and healthcare

Channel data (last 2 quarters):
- Organic SEO: 380 MQLs, 21% MQL→SQL, 19% SQL→Won, $38K avg deal, 82 days cycle, $31K spend
- Paid Search: 290 MQLs, 13% MQL→SQL, 11% SQL→Won, $24K avg deal, 54 days cycle, $58K spend
- LinkedIn Ads: 165 MQLs, 29% MQL→SQL, 24% SQL→Won, $51K avg deal, 96 days cycle, $44K spend
- Cybersecurity Events (RSA, Black Hat): 88 MQLs, 47% MQL→SQL, 31% SQL→Won, $74K avg deal, 118 days cycle, $62K spend
- Partner (MSSPs): 122 MQLs, 41% MQL→SQL, 29% SQL→Won, $89K avg deal, 134 days cycle, $19K spend
- SDR Outbound: 198 MQLs, 17% MQL→SQL, 14% SQL→Won, $37K avg deal, 71 days cycle, $74K spend
- Customer Referral: 41 MQLs, 63% MQL→SQL, 44% SQL→Won, $96K avg deal, 47 days cycle, $8K spend
- G2/Capterra Reviews: 94 MQLs, 38% MQL→SQL, 26% SQL→Won, $29K avg deal, 61 days cycle, $14K spend

**Output Example:**

**EXECUTIVE SUMMARY**
Vaultline's highest-revenue-quality channels (Customer Referral, Partner/MSSP, and Events) represent only 22% of MQL volume but generate 61% of closed ARR. Paid Search — your second-highest spend at $58K — has the lowest revenue quality score (CRQS: 31/100) and a $14.2K CAC with 9.1-month payback. Immediate reallocation of $22K from Paid Search into MSSP Partner MDF and Customer Referral program expansion projects an additional $1.4M in annual pipeline with 20% higher win rates.

**CHANNEL REVENUE QUALITY SCORECARD**

| Channel | CRQS | RPL | Rev/$ Spent | CAC | Payback | Verdict |
|---|---|---|---|---|---|---|
| Customer Referral | 94/100 | $26,611 | $136.6 | $4,700 | 1.3 mo | Scale aggressively |
| Partner / MSSP | 89/100 | $10,604 | $68.1 | $7,200 | 2.1 mo | Invest +$15K immediately |
| Events (RSA/BH) | 82/100 | $10,773 | $15.2 | $21,400 | 6.1 mo | Maintain, optimize mix |
| LinkedIn Ads | 71/100 | $3,557 | $13.3 | $16,300 | 4.7 mo | Test ABM retargeting layer |
| G2/Capterra | 67/100 | $2,862 | $19.2 | $8,100 | 2.3 mo | Hidden Gem — increase reviews program |
| Organic SEO | 58/100 | $1,514 | $18.6 | $11,600 | 3.3 mo | Maintain — BOFU content needed |
| SDR Outbound | 44/100 | $901 | $2.4 | $38,200 | 10.9 mo | Optimize targeting to ICP — reduce volume |
| Paid Search | 31/100 | $374 | $1.1 | $51,800 | 14.8 mo | Cut 40% budget, shift to brand + MSSP |

**HIDDEN GEMS IDENTIFIED:**
1. G2/Capterra Reviews: CRQS 67, only $14K spend, $19.2 revenue per dollar. Increasing review velocity by 50% (programmatic outreach to happy customers) costs ~$3K and projects $180K additional pipeline.
2. Customer Referral: Your highest CRQS at 94/100 with only $8K program investment. A structured referral incentive program with $20K investment is projected to 3x referral volume — adding ~$2.2M ARR opportunity.

**QUALITY DEGRADATION ALERTS — PAID SEARCH:**
- SQL rate trend: -3.2 percentage points over 6 months (declining)
- Deal size trend: -$4.2K average over 2 quarters (declining)
- Red flag: If SQL rate drops below 10% in any 4-week rolling period → pause campaign budget and audit keyword match types and landing page ICP alignment

**30-DAY IMMEDIATE ACTIONS:**
1. Pause bottom 20% paid search keywords by Quality Score → save $8K/month
2. Launch Customer Referral automation sequence in HubSpot for all customers with NPS ≥8 → target 15 referrals in 30 days
3. Add MSSP partner co-sell MDF of $15K → onboard 2 new MSSP partners with dedicated deal registration
4. Instrument G2 review-to-revenue path with UTM tracking and Salesforce campaign influence → close measurement gap

## Success Metrics

- CRQS model explains ≥70% of variance in channel revenue outcomes vs. current reporting
- Identified ≥2 "Hidden Gem" channels with clear investment rationale and projected pipeline impact
- Budget reallocation scenarios include specific dollar amounts and modeled pipeline outcomes (not directional guesses)
- Early Warning System defines concrete thresholds (not "watch closely")
- Every recommendation ties back to a revenue number the CFO can validate in Salesforce
- Instrumentation Gap Audit produces a ticket-ready list for the MarOps team

## Related Prompts

- [Marketing Lead Quality & Sales Handoff Intelligence Engine](./Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md)
- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine](./Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [AI-Powered Marketing Mix Modeling & Media Investment Intelligence Engine](../Marketing-Mix-Modeling-&-Budget-Optimization/AI-Powered-Marketing-Mix-Modeling-&-Media-Investment-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Pull channel data via Salesforce Reports → Opportunities by Lead Source → add SQL rate via custom Campaign Influence report; use Salesforce Einstein Analytics for cohort views by lead source
- **HubSpot**: Use "Revenue by Original Source" and "Revenue by Latest Source" reports in HubSpot CRM; export to Google Sheets for CRQS calculation; set up HubSpot dashboards with SQL rate by source tracked weekly
- **Dreamdata / Rockerbox / Triple Whale**: These multi-touch attribution platforms provide channel-level revenue data automatically — feed their CSV export directly into this prompt for faster scoring
- **Google Sheets automation**: Build the CRQS formula in Sheets with monthly auto-refresh from HubSpot/Salesforce data exports; set conditional formatting to flag yellow/red quality alert thresholds
- **Slack alerts**: Use Zapier → Salesforce trigger (new Closed Won) → Slack webhook to post channel-tagged revenue in real-time to #revenue-ops channel; set weekly summary digest every Monday 8am
- **Looker / Tableau**: Build the Channel Quality Scorecard as a live dashboard pulling from your data warehouse; schedule weekly email delivery to CMO and VP Sales
- **Segment**: Use Segment to instrument every form submission and content download with channel source properties; pipe to your warehouse for cohort-level quality analysis

## Troubleshooting

- **Problem**: Channel sample sizes are too small (fewer than 50 MQLs) to calculate statistically reliable conversion rates.
  **Solution**: Aggregate to a longer time window (6–12 months instead of one quarter) or group similar channels (e.g., combine all paid social into one bucket). The prompt will flag low-confidence channels — treat their scores as directional indicators, not actionable data, until sample size grows.

- **Problem**: Lead source attribution is inconsistent in CRM — many leads tagged "Direct" or "Unknown" even though they came from specific campaigns.
  **Solution**: Before running this analysis, run a UTM audit: identify what % of form submissions have proper UTM parameters. If less than 70% are tracked, fix UTM governance first (use the [UTM Campaign Tracking Governance Engine](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/UTM-Campaign-Tracking-Governance-Engine.md)). For the current analysis, redistribute "Unknown" leads proportionally across known channels based on the known channel mix.

- **Problem**: Partner and referral channels have very high quality scores but sales says the leads "take longer to close" and doesn't prioritize them.
  **Solution**: Add a Sales Cycle Velocity weighting to the CRQS model and re-run. If even with that adjustment partners/referrals score high, build a dedicated fast-path nurture sequence for these leads to compress cycle time — and present the RPL comparison to sales leadership to realign prioritization.

## Version History
- v1.0: Initial creation (auto-generated)
