# Account-Based Marketing Analytics & Revenue Intelligence Engine - Full-Funnel ABM Performance Attribution

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, abm, analytics, attribution, revenue-intelligence, enterprise

## Overview
Transforms raw ABM campaign data into actionable revenue intelligence by analyzing account engagement depth, pipeline velocity by tier, multi-threaded buying committee influence, and marketing-sourced vs. marketing-influenced pipeline — giving revenue teams a single source of truth to double down on what's working and cut what isn't.

## Quick Copy-Paste Version

You are a B2B revenue analytics expert. Analyze my ABM program performance and produce a complete revenue intelligence report.

Here is my program data:
- Target account list: [paste tier breakdown, e.g., Tier 1: 50 accounts, Tier 2: 150 accounts, Tier 3: 400 accounts]
- Campaign channels active: [e.g., LinkedIn Ads, 6sense intent, direct mail, executive events, SDR sequences]
- Date range: [e.g., Q1 2026, Jan 1 – Mar 31]
- CRM data summary: [paste or describe pipeline stages, deal counts, ARR values by stage]
- Engagement data: [website visits, ad impressions, email opens, event attendance by account — paste CSV or summarize]
- Won/Lost deals this period: [list with ARR and account tier]

Produce:
1. **Pipeline Coverage Analysis** — Marketing-sourced vs. marketing-influenced pipeline by account tier. Flag tiers with coverage gaps vs. quota.
2. **Account Engagement Scoring Summary** — Top 20 highest-engagement accounts not yet in pipeline. Rank by engagement recency + depth + buying committee breadth.
3. **Channel Attribution Matrix** — Which channels drove first touch, last touch, and assist touches for closed-won deals. Include cost-per-pipeline and cost-per-close by channel.
4. **Buying Committee Penetration Report** — Average number of contacts engaged per account in won vs. lost deals. Identify the missing personas in accounts stuck in pipeline.
5. **Pipeline Velocity Dashboard** — Average days in each stage by account tier and deal size. Flag outliers and bottlenecks.
6. **Win/Loss Pattern Analysis** — Top 3 patterns in won accounts vs. top 3 patterns in lost accounts based on engagement signals.
7. **Next-Best-Action Recommendations** — For top 10 stuck deals and top 10 high-engagement, pre-pipeline accounts, prescribe exact next marketing play.

Format as an executive-ready report with a one-page summary scorecard at the top.

## Advanced Customizable Version

ROLE: You are a senior revenue intelligence analyst specializing in B2B Account-Based Marketing measurement. You combine marketing attribution expertise with sales pipeline analytics to produce insights that drive budget allocation, campaign optimization, and revenue forecasting decisions.

CONTEXT:
Company: [Company name]
Segment: [B2B SaaS / B2B Services / B2B Manufacturing / etc.]
ACV Range: [e.g., $25K–$500K]
Sales Cycle: [e.g., 60–180 days]
ABM Tiers:
- Tier 1 (Named Enterprise): [count] accounts, [ARR target per account]
- Tier 2 (Mid-Market Expansion): [count] accounts, [ARR target per account]
- Tier 3 (Broad Market): [count] accounts, [ARR target per account]
CRM: [Salesforce / HubSpot / other]
MAP: [Marketo / HubSpot / Pardot / other]
Intent Platform: [6sense / Bombora / G2 / Demandbase / none]
ABM Channels Active: [LinkedIn Ads, G2 reviews, executive events, direct mail, SDR sequences, display retargeting, content syndication]

OBJECTIVE: Produce a complete ABM Revenue Intelligence Report for the period [start date] to [end date] covering pipeline generation, account engagement quality, buying committee penetration, channel ROI, and forward-looking recommendations.

DATA INPUTS (paste or describe each):
1. Account Tier List with CRM Stage: [upload or describe]
2. Pipeline by Stage and Tier: [total pipeline value, deal counts, avg deal size by tier and stage]
3. Marketing Engagement Log: [impressions, clicks, email opens/clicks, event attendance, content downloads, web visits — by account, by channel]
4. Buying Committee Contacts: [roles/personas engaged per account in CRM]
5. Won Deals This Period: [account name, tier, ARR, sales cycle days, channels touched]
6. Lost Deals This Period: [account name, tier, ARR, stage lost, reason if known]
7. Channel Spend: [budget allocated and spent by channel]
8. Intent Signals: [accounts showing 3rd-party intent spikes, by topic/keyword cluster]

ANALYSIS FRAMEWORK — Execute each module:

MODULE 1: PIPELINE GENERATION SCORECARD
- Marketing-sourced pipeline (MS-Pipeline): deals where first touch = marketing
- Marketing-influenced pipeline (MI-Pipeline): deals where marketing touched ≥1 contact before SQL
- MS-Pipeline and MI-Pipeline by tier vs. targets
- Pipeline coverage ratio = pipeline / quota by tier (flag anything below 3x)
- Quarter-over-quarter pipeline trend if prior period data available

MODULE 2: ACCOUNT ENGAGEMENT QUALITY INDEX
Using a weighted engagement scoring model:
- Recency score (0–30): touches in last 30 days weighted higher
- Depth score (0–30): content consumed, pages visited, event attended
- Breadth score (0–40): number of unique buying committee personas engaged
Produce:
- Top 25 highest-scoring accounts not yet in pipeline → hot list for SDR/AE prioritization
- Bottom 20 Tier 1/2 accounts with zero engagement → dormant account alert
- Accounts showing intent spikes but no pipeline → immediate outreach candidates

MODULE 3: CHANNEL ATTRIBUTION & ROI MATRIX
For each active channel, calculate:
- Accounts reached (unique)
- Engagement rate (accounts that responded / accounts reached)
- Pipeline influenced (# deals, $ value)
- Pipeline sourced (# deals, $ value)
- Closed-won influenced (# deals, $ ARR)
- Cost per account reached
- Cost per pipeline dollar (influenced)
- Cost per closed-won dollar (influenced)
- Attribution model: use linear multi-touch attribution as primary; note where first-touch or last-touch tells a different story
Rank channels by cost efficiency and pipeline impact. Flag underperformers.

MODULE 4: BUYING COMMITTEE PENETRATION ANALYSIS
- Average unique personas engaged per account: won deals vs. lost deals vs. open pipeline
- Missing persona gap: for each open deal, identify which buying committee roles (Economic Buyer, Champion, Technical Evaluator, Legal/Procurement, End User) have zero engagement
- Multi-thread score by deal: deals with <3 engaged personas flagged as single-threaded risk
- Persona-level content gap: which personas are being reached by marketing vs. which are invisible

MODULE 5: PIPELINE VELOCITY DEEP DIVE
For each deal stage and tier:
- Average days in stage (current period)
- Benchmark vs. prior period or industry standard [provide benchmark if known: $25K–$100K ACV median ~60–90 days; $100K–$500K ACV median ~90–180 days]
- Velocity outliers: deals in any stage longer than 2x average → flag for marketing assist
- Stage conversion rates: % of accounts that advance from each stage to next
- Identify the stage with lowest conversion rate → primary bottleneck

MODULE 6: WIN/LOSS PATTERN RECOGNITION
Analyze won vs. lost deals to extract:
- Top 3 engagement patterns in won accounts (channels, sequence of touches, personas engaged, content consumed)
- Top 3 engagement patterns in lost accounts (what was missing or different)
- Competitive displacement signals: lost deals where competitor content was consumed
- Time-to-engage correlation: accounts first engaged within [X] days of intent spike — win rate vs. those engaged later

MODULE 7: FORWARD-LOOKING RECOMMENDATIONS

SECTION A — Immediate Actions (This Week):
- Top 10 pre-pipeline accounts: prescribe exact play (e.g., "Run LinkedIn Conversation Ads targeting VP Engineering + SDR sequence to CTO; use [specific content asset]")
- Top 5 stuck pipeline deals: prescribe exact marketing assist (e.g., "Deploy executive direct mail + invite to roundtable dinner; add missing Economic Buyer persona to nurture")

SECTION B — Campaign Optimization (This Quarter):
- Kill or reduce budget for bottom 2 channels
- Double down on top 2 channels
- Buying committee gap plays: content/campaigns to reach underrepresented personas

SECTION C — Strategic Recommendations (Next Quarter Planning):
- ABM tier adjustments: accounts to promote or demote based on engagement and fit
- New channel experiments to test based on gaps identified
- Forecast: projected pipeline from current engagement trends if conversion rates hold

OUTPUT FORMAT:
1. EXECUTIVE SCORECARD (1 page): Key metrics dashboard — MS-Pipeline, MI-Pipeline, coverage ratio, top channel, win rate, avg velocity vs. target
2. MODULE REPORTS (detailed): One section per module above
3. PRIORITY ACTION LIST: Top 10 actions ranked by revenue impact, with owner (Marketing vs. Sales vs. SDR) and deadline

Tone: Data-driven, direct, executive-ready. Use tables and bullet points. No filler commentary — every sentence must be actionable or evidential.

## Example Input/Output

**Input Example:**

Company: Veridian Security (B2B SaaS, cybersecurity compliance automation)
ACV: $48K average
Tier 1: 40 accounts (Fortune 1000 FSI/Healthcare), Tier 2: 120 accounts (mid-market), Tier 3: 350 accounts (SMB)
Period: Q1 2026
CRM data: 14 Tier 1 deals in pipeline ($2.1M total), 22 Tier 2 deals ($1.4M), 38 Tier 3 deals ($900K)
Q1 quota: $1.8M new ARR
Channels: LinkedIn Ads ($42K spend), 6sense intent ($28K), executive roundtables (2 events, $35K), SDR sequences (no cost separate), G2 review campaign ($8K)
Won this quarter: 6 deals ($287K ARR) — 4 Tier 2, 2 Tier 3
Lost: 3 deals ($340K ARR) — 2 Tier 1, 1 Tier 2
Intent spikes: 12 accounts showing "SOC 2 automation" and "compliance workflow" intent in last 30 days, 7 not in pipeline

**Output Example (Executive Scorecard section):**

VERIDIAN SECURITY — Q1 2026 ABM REVENUE INTELLIGENCE SCORECARD
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PIPELINE HEALTH                          vs. TARGET
Marketing-Sourced Pipeline:   $1.24M     Target: $1.5M    ⚠️ -17%
Marketing-Influenced Pipeline: $3.8M    Target: $3.6M    ✅ +6%
Pipeline Coverage Ratio:       2.4x      Target: 3x       ⚠️ Below threshold
  - Tier 1 Coverage:           2.1x                       🔴 Critical gap
  - Tier 2 Coverage:           2.8x                       ⚠️ Watch
  - Tier 3 Coverage:           3.2x                       ✅ Healthy

VELOCITY
Avg Days Tier 1 (MQL→Close):  142 days   Benchmark: 120   🔴 +18% slower
Avg Days Tier 2 (MQL→Close):  87 days    Benchmark: 90    ✅ On track
Biggest Bottleneck Stage:      Technical Evaluation → Legal (avg 34 days, 2.1x norm)

WIN/LOSS
Win Rate (by count):           67%        Target: 60%      ✅
Win Rate (by ARR):             46%        Target: 55%      ⚠️ Losing big deals
Lost ARR: $340K — 2 Tier 1 losses drove 89% of lost value

TOP CHANNEL (by pipeline influenced $):
#1 Executive Roundtables: $1.9M influenced / $35K spend = $54 pipeline per dollar spent
#2 6sense Intent: $1.4M influenced / $28K spend = $50 pipeline per dollar spent
⚠️ LinkedIn Ads: $800K influenced / $42K spend = $19 pipeline per dollar spent — REVIEW

PRIORITY ALERT: 7 intent-active accounts not in pipeline — estimated $336K pipeline opportunity
if engaged within 14 days at current Tier 2 win rates

**Module 2 Output (excerpt):**

TOP 5 HOT ACCOUNTS — IMMEDIATE OUTREACH PRIORITY

Rank | Account          | Tier | Engagement Score | Missing Personas | Recommended Play
1    | Hargrove Capital | 1    | 94/100           | Economic Buyer   | CFO direct mail + roundtable invite
2    | MedCore Systems  | 2    | 87/100           | Technical Eval   | Demo offer via SDR + G2 review send
3    | PacificTrust Bank| 1    | 82/100           | All — intent only| Cold ABM sequence: SDR + LinkedIn InMail to CISO
4    | RenewPath Health | 2    | 79/100           | Procurement      | Legal/compliance content nurture + case study
5    | AnchorPoint RE   | 2    | 74/100           | Champion/AE      | Internal champion enablement kit + peer intro

## Success Metrics

- Pipeline coverage ratio reaches ≥3x quota for all tiers within 60 days of implementing recommendations
- Channel reallocation reduces cost-per-pipeline-dollar by ≥25% within one quarter
- Buying committee breadth in open pipeline improves from average 2.1 to ≥3.5 unique personas per deal
- Intent-to-pipeline conversion rate: ≥40% of intent-active accounts enter pipeline within 30 days of outreach
- Report generation time reduced from 2–3 days manual analysis to under 2 hours with AI-assisted execution
- Executive team can answer "where should we invest next quarter?" using scorecard alone — no additional data pulls required

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-&-ABM/Account-Based-Marketing-Automation.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-&-ABM/Account-Based-Experience-ABX-Personalization-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Paid-Media-Cross-Channel-Performance-Intelligence-Engine.md`

## Integration Tips

**Salesforce + Tableau/Looker:**
- Pull Opportunity data filtered by `Campaign_Influenced__c = TRUE` and `Lead_Source` for MS vs. MI pipeline split
- Create a custom `ABM_Engagement_Score__c` field on the Account object; populate via Salesforce Flow triggered by campaign member activity
- Build Tableau dashboard with drill-downs by tier, stage, and channel for weekly ABM review

**HubSpot:**
- Use Contact Lists segmented by company property + engagement score to build the buying committee penetration view
- HubSpot's "Companies" report with associated deal stages and contact engagement data feeds directly into Module 2 and 4
- Connect HubSpot → Google Sheets via native integration; use this prompt on the exported sheet data

**6sense / Bombora:**
- Export weekly intent spike report → paste account names + intent topics into the prompt for Module 2 hot list generation
- Map 6sense buying stage (Awareness/Consideration/Decision/Purchase) to your CRM stages for velocity benchmarking

**Zapier / Make Automation:**
- Trigger: New deal created in CRM → auto-populate engagement score from MAP → send to Google Sheets ABM tracker
- Weekly trigger: Run Module 7 recommendations against updated data → Slack alert to ABM team with top 10 priority actions

**Google Sheets Template:**
Set up five tabs: (1) Account Master List with tier/stage/score, (2) Channel Spend & Attribution, (3) Buying Committee Contacts, (4) Won/Lost Log, (5) Weekly Hot List. Paste tab data into prompt sections for automated weekly report generation.

## Troubleshooting

**Problem:** Attribution data is inconsistent — deals show no marketing touches even though campaigns ran.
**Solution:** Check UTM parameter coverage across all landing pages and ensure campaign member records are being created in CRM for every channel. For channels without direct CRM integration (display ads, direct mail), use manual campaign member upload or a tool like Metadata.io or RollWorks that writes directly to Salesforce. Run UTM-Campaign-Tracking-Governance-Engine.md to audit and fix tracking gaps before re-running this analysis.

**Problem:** The engagement scoring in Module 2 surfaces accounts that sales says are "not a fit."
**Solution:** Add a firmographic fit filter before the engagement score — remove any account below your minimum ICP threshold (e.g., <100 employees, wrong industry vertical, no budget signals). The engagement score should only rank accounts that are already ICP-qualified. Update your target account list to remove chronic non-ICP accounts so intent signals aren't wasted.

**Problem:** Win/loss patterns in Module 6 are too vague because lost deal reasons aren't logged in CRM.
**Solution:** Run the prompt with available data and note the gap explicitly in the output. Implement a mandatory "Loss Reason" picklist in CRM (options: Price, Competitor, No Decision, Timing, Fit, Champion Left) and make it required to advance a deal to Closed-Lost. After 60 days of clean data, re-run Module 6 for statistically meaningful patterns. In the interim, use Module 6's engagement pattern analysis (channels, personas, content) as a proxy for loss reason inference.

## Version History
- v1.0: Initial creation (auto-generated)
