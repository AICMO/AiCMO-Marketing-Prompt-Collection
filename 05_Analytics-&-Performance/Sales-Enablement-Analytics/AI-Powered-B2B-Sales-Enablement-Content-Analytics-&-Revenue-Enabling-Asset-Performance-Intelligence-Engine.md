# AI-Powered B2B Sales Enablement Content Analytics & Revenue-Enabling Asset Performance Intelligence Engine - Know Which Sales Content Wins Deals Before You Waste Another Quarter Building the Wrong Assets

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, sales-enablement, content-analytics, revenue-attribution, product-marketing, win-rate, deal-velocity, saas, highspot, seismic, showpad, salesforce, hubspot

## Overview
Deploys an AI analytics system to measure which sales enablement assets (decks, battle cards, one-pagers, case studies, ROI calculators, objection handlers) actually get used, drive deal velocity, and correlate with wins — then surfaces which content to build next. Use this when your PMM team spends 60% of their time producing assets sales ignores, when you can't tell which battle card actually beats your top competitor, or when leadership asks "what content should we prioritize this quarter" and you have no data to answer.

## Quick Copy-Paste Version

You are a senior B2B sales enablement analytics expert. I need you to design a performance measurement system for our sales enablement content library.

My context:
- Company type: [B2B SaaS / Enterprise Software / Professional Services]
- Sales enablement platform: [Highspot / Seismic / Showpad / Notion / Google Drive / Salesforce Files / None]
- CRM: [Salesforce / HubSpot]
- Current content library size: [Approximate number of sales assets]
- Sales team size: [AEs: X | SDRs: X | SEs: X]
- Average ACV: [$X]
- Average sales cycle: [X days]
- Top 3 use cases I need to measure: [e.g., "which battle cards win competitive deals," "which case studies accelerate mid-funnel," "which decks get shared vs abandoned"]
- Biggest current problem: [e.g., "PMM creates content but sales doesn't use it," "can't tell which assets close deals," "no data on content impact"]

Deliver the following:

1. **Content Performance Scorecard** — a scoring framework (0-100) for each asset type that weights: usage rate by sales reps, deal association rate, win rate lift when used vs not used, stage-specific usage (discovery vs proposal vs close), and buyer engagement signals (shares, time-on-page, re-opens). Include benchmark ranges by asset type.

2. **Content Audit Dashboard Design** — exact metrics to pull from your enablement platform + CRM to build a monthly content performance dashboard. Include: top 10 assets by win-rate lift, top 10 assets by usage frequency, graveyard assets (created but never used), and stage-specific content gaps.

3. **Content Gap Analysis Framework** — a systematic method to identify missing content by analyzing: (a) deal stages where reps manually create one-off materials, (b) objections logged in call recordings that have no corresponding battle card, (c) competitor scenarios where win rate drops below baseline, (d) personas who appear in deals but have no dedicated content.

4. **PMM Prioritization Matrix** — a 2x2 matrix prioritizing content creation by (a) revenue impact potential vs (b) time-to-create, plus a scoring rubric to objectively rank content requests from sales.

5. **30-60-90 Day Implementation Plan** — how to go from zero content analytics to a data-driven enablement program that sales actually trusts.

## Advanced Customizable Version

ROLE: You are a Director of Sales Enablement Analytics with 12 years of B2B SaaS experience building content measurement programs at companies from $15M to $800M ARR. You have deep expertise in sales enablement platforms (Highspot, Seismic, Showpad, Mindtickle), CRM data architecture (Salesforce, HubSpot), conversation intelligence tools (Gong, Chorus, Salesloft), and building the attribution models that connect content consumption to closed revenue. You understand how to design controlled experiments (used vs. not-used deal cohorts) to prove content ROI, how to build sales rep adoption programs that actually change behavior, and how to create board-ready PMM impact reports. You are fanatical about avoiding vanity metrics — you only report metrics that directly correlate with pipeline and revenue.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Stage / ARR: [e.g., Series C / $45M ARR]
- Industry vertical: [e.g., HR Tech, DevSecOps, FinTech, MarTech]
- ICP: [Job titles, company sizes, industries — be specific]
- ACV: [$X]
- Average sales cycle: [X days]
- Win rate overall: [X%]
- Primary loss reasons: [e.g., "lost to [Competitor A] 40%, lost to 'no decision' 30%, lost to budget 20%"]
- Sales motion: [PLG / SLG / PLS / Channel-led / Field sales only]

SALES TEAM STRUCTURE:
- Total AEs: [X] (split by segment: SMB / Mid-Market / Enterprise)
- SDRs / BDRs: [X]
- Sales Engineers / Solutions Consultants: [X]
- Customer Success (if involved in expansion sales): [X]
- Geographic split: [NA / EMEA / APAC breakdown]

CURRENT ENABLEMENT STACK:
- Content repository: [Highspot / Seismic / Showpad / Mindtickle / Google Drive / Confluence / SharePoint / None]
- CRM: [Salesforce / HubSpot — include key custom fields if any]
- Conversation intelligence: [Gong / Chorus / Salesloft / Outreach / None]
- Call recording and transcription: [Yes / No / Partial coverage]
- Buyer engagement tracking: [DocSend / Attach.io / Seismic LiveSend / native platform / None]
- LMS / training platform: [Mindtickle / Lessonly / Workramp / None]

CURRENT CONTENT LIBRARY:
- Total assets in library: [X]
- Asset types: [Pitch decks X | Battle cards X | Case studies X | One-pagers X | ROI calculators X | Objection handlers X | Demo scripts X | Email templates X | Other X]
- Age of library (when was it last audited): [X months/years ago]
- Primary content creator: [PMM team / Sales ops / Outsourced agency / Sales reps create own]
- Publishing cadence: [New assets per month: X]

MEASUREMENT OBJECTIVES (rank 1-5 by priority):
- [ ] Prove PMM content drives revenue (board-level attribution)
- [ ] Identify which assets to sunset vs. double down on
- [ ] Find content gaps causing deal stalls
- [ ] Improve competitive win rates with data-driven battle card optimization
- [ ] Increase sales rep content adoption rates
- [ ] Reduce time-to-ramp for new AEs through content intelligence
- [ ] Optimize content investment (PMM hours vs. revenue impact)

COMPETITIVE CONTEXT:
- Primary competitors: [Competitor A, B, C — list the 3 you most often face in deals]
- Competitive win rate vs. each: [A: X% | B: X% | C: X%]
- Do you have competitive battle cards for each? [Yes / No / Outdated]
- Biggest competitive content gap: [e.g., "no content for when Competitor A drops price 40%"]

---

DELIVERABLE 1: SALES ENABLEMENT ANALYTICS ARCHITECTURE

Design the complete analytics architecture for this company's enablement program.

A. DATA LAYER DESIGN
Map the exact data connections needed:
- Which fields from the CRM (Opportunity: Stage, Close Date, Won/Lost, Loss Reason, Competitor, Deal Size, Industry, Persona, Sales Rep, Sales Cycle Length)
- Which fields from the enablement platform (Asset ID, Asset Name, Asset Type, View Date, View Duration, Share Events, Buyer Opens, Rep ID)
- Which fields from conversation intelligence (Call Date, Stage, Keywords mentioned, Competitor mentioned, Objections raised, Content referenced)
- Which fields from buyer engagement tracking (Document opens, Time on page, Pages viewed, Re-opens, Forwarded to others)

Define the JOIN logic to connect these data sources at the deal level.

B. CONTENT PERFORMANCE SCORING MODEL
Build a weighted scoring algorithm:

Asset Performance Score (0-100) =
- Usage Rate Score (25 pts): % of eligible deals where asset was used
  - Benchmark: Pitch decks >70%, Case studies >40%, ROI calculators >20%, Battle cards >60% of competitive deals
- Win-Rate Lift Score (35 pts): Win rate in deals where asset was used vs. NOT used (requires minimum 30-deal sample for statistical validity)
  - Flag assets with <2% lift as "not working" | >5% lift as "high impact" | >10% lift as "critical"
- Deal Velocity Score (20 pts): Average days-to-close in deals using asset vs. baseline
  - Negative days = accelerating = positive score
- Buyer Engagement Score (15 pts): Buyer opens per deal, re-opens, time-on-page, forwards
- Freshness Score (5 pts): Days since last update (penalize assets >90 days old in fast-moving categories)

C. CONTENT TAXONOMY FRAMEWORK
Define the full content taxonomy by:
- Sales stage: Awareness / Discovery / Evaluation / Proposal / Negotiation / Close / Expansion
- Buyer persona: Economic buyer / Technical evaluator / Champion / Legal/Procurement / End user
- Deal size: SMB (<$25K ACV) / Mid-Market ($25K-$100K) / Enterprise (>$100K)
- Industry vertical: [List top 5 verticals]
- Competitive scenario: [Competitor A scenario / Competitor B scenario / No-decision scenario / Status quo defense]
- Objection type: [Budget / Timeline / Technical fit / Security/compliance / Competitive preference / Executive buy-in]

Map every existing asset to this taxonomy. Identify blank cells = content gaps.

---

DELIVERABLE 2: MONTHLY CONTENT PERFORMANCE DASHBOARD

Design the exact dashboard layout with:

SECTION A: EXECUTIVE SUMMARY (for CMO/VP PMM)
- PMM Content Revenue Attribution: Total pipeline influenced by tracked content this month [$X]
- Content Win-Rate Lift: Deals with 3+ PMM assets used vs. deals with 0-1 assets [X% vs X%]
- Top 3 Revenue-Generating Assets this month [Asset name | Revenue influenced]
- Content Gap Alert: Top 3 deal-stage gaps costing pipeline [Stage | Gap description | Estimated pipeline at risk]

SECTION B: ASSET PERFORMANCE LEADERBOARD
Table: All assets sorted by Performance Score
Columns: Asset Name | Type | Performance Score | Usage Rate | Win Rate Lift | Deal Velocity Impact | Buyer Engagement | Last Updated | Action (Keep/Update/Sunset)

Highlight:
- 🟢 Champions (Score >75): Replicate the format/approach
- 🟡 Needs Update (Score 40-74): Refresh content, not the concept
- 🔴 Sunset Candidates (Score <40 with >20 deal sample): Archive and redirect effort

SECTION C: COMPETITIVE CONTENT ANALYSIS
For each primary competitor:
- Battle card usage rate in competitive deals: [X%]
- Win rate in competitive deals WITH battle card vs. WITHOUT: [X% vs X%]
- Top 3 objections in losing competitive deals with no content coverage
- Recommended battle card updates (based on Gong/conversation data)

SECTION D: CONTENT GAP HEAT MAP
Grid visualization: Buyer Persona (rows) × Sales Stage (columns)
Each cell: Green (well-covered, high-performing) / Yellow (exists but underperforming) / Red (gap — no content exists)
Priority cells for next sprint highlighted with estimated revenue impact.

SECTION E: REP ADOPTION ANALYTICS
- Reps sorted by content adoption rate (% of their deals with 3+ assets used)
- Correlation: Rep adoption rate vs. Rep win rate (is there a relationship?)
- Reps who create their own custom materials (flag: what are they building that PMM hasn't?)
- New rep time-to-first content use (proxy for onboarding efficiency)

---

DELIVERABLE 3: CONTENT GAP IDENTIFICATION SYSTEM

Design an AI-powered content gap detection system using these 5 data sources:

1. GONG/CHORUS TRANSCRIPT MINING
Analyze call recordings for:
- Objections raised that don't have a battle card response documented
- Competitor names mentioned in deals where rep improvised (no card used)
- Questions buyers asked that aren't answered in existing one-pagers
- Phrases buyers used that don't match language in existing assets (terminology gap)
- Stages where reps stall and improvise most often

Output: Weekly "Objection Gap Report" listing top 10 objections with no content coverage, ranked by frequency × deal size

2. DEAL STAGE ANALYSIS
Query CRM for deals that:
- Stalled at a specific stage for >2x average stage duration
- Slipped from "Proposal" back to "Evaluation" (regression = content failure)
- Had "No decision" as loss reason (= couldn't justify ROI)
- Had "Went with competitor" + no battle card used

Output: Stage-level content failure analysis

3. SALES REP SHADOW CONTENT AUDIT
Identify content reps create themselves (Google Docs, email attachments, Canva exports) by:
- Monitoring email attachments sent from sales email platforms
- Analyzing "custom" field in Highspot/Seismic for one-off uploads
- Running quarterly survey: "What materials are you creating that don't exist in the library?"

Output: Top 10 "shadow assets" reps create — these are your highest-priority PMM backlog items

4. WIN/LOSS INTERVIEW SYNTHESIS
Automatically analyze win/loss call transcripts for:
- "What content was most helpful?" → Validate champions
- "What information were you missing?" → Identify gaps
- "What did you use from [Competitor] that was better?" → Competitive content gap

5. BUYER ENGAGEMENT ANALYTICS
Flag assets where buyers:
- Open but spend <30 seconds (= misleading headline, wrong audience)
- Never re-open after initial view (= didn't find value)
- Forward to others (= champion sharing = high value signal)
- Stop reading at page X consistently (= content loses them at that point)

---

DELIVERABLE 4: PMM PRIORITIZATION FRAMEWORK

CONTENT REQUEST SCORING RUBRIC (use for all new content requests from sales):

Score each request 1-5 on:
- Revenue Potential (1-5): How many active deals would immediately use this? × average ACV of those deals
- Urgency (1-5): Is there an active competitive threat or deal stall causing this request?
- Reusability (1-5): Will this serve one deal or 50?
- PMM Build Time (5=<2hrs, 1=>2 weeks): Inverse scoring — quick wins score higher
- Data Confidence (1-5): Do we have enough deal data to validate the use case?

Total Score ÷ 5 = Priority Rating

CONTENT INVESTMENT ROI MODEL:
For each asset category, calculate:
- PMM hours to create: [Estimate by type]
- PMM hourly cost (fully loaded): [$X]
- Total creation cost: [Hours × Rate]
- Deals using asset per quarter: [From analytics]
- Win rate lift: [From performance data]
- Revenue attributable: [Deals × Win Rate Lift × Average ACV]
- Asset ROI: [Revenue attributable ÷ Creation cost]

Target: Every PMM asset should generate >10x cost in influenced revenue within 2 quarters

---

DELIVERABLE 5: IMPLEMENTATION ROADMAP

DAY 1-30: DATA FOUNDATION
Week 1: Audit current content library — assign asset taxonomy tags to every asset
Week 2: Configure CRM tracking — add "Content Used" multi-select field to Opportunity object; train reps to log assets used in closed deals (backfill 6 months)
Week 3: Connect enablement platform to CRM via native integration or Zapier/Make
Week 4: Build first version of Content Performance Dashboard in Tableau/Looker/Google Data Studio; run first Content Gap Analysis from Gong transcripts

DAY 31-60: ANALYTICS ACTIVATION
- Publish first monthly Content Performance Report to PMM + Sales leadership
- Run "Content Champion" analysis — identify top 5 reps by content adoption and interview them
- Launch quarterly content audit cycle — score every asset, sunset bottom 20%
- Build content request scoring rubric; train PMM team to use it

DAY 61-90: PROGRAM OPTIMIZATION
- Establish "Content Council" — bi-weekly 30-min PMM + Sales ops + Sales leadership meeting to review data
- Create first data-driven content sprint — build 3-5 assets identified as gaps in first 60 days
- Measure: Did new assets get used? Did win rate lift in target scenarios?
- Present first board-ready PMM ROI report: "Content investment drove $X in pipeline this quarter"

## Example Input/Output

**Input Example:**

Company: Meridian Security (cybersecurity SaaS, $38M ARR Series C)
ICP: CISO, VP Information Security at 500-5000 employee companies
ACV: $85,000 | Sales cycle: 94 days average | Win rate: 27% overall
Primary competitors: CrowdStrike, SentinelOne, Vectra AI
Sales team: 18 AEs, 12 SDRs, 6 Security Engineers
Enablement platform: Highspot | CRM: Salesforce | Conversation intel: Gong
Content library: 142 assets (created 2021-2024, last audit: never)
Biggest problem: "Our win rate against CrowdStrike is 19% but against Vectra is 41% — we don't know why, and we don't know if our battle cards are even helping."

**Output Example (excerpt):**

**Content Performance Analysis — Meridian Security**

*Asset Performance Leaderboard (Top 5):*
| Asset | Score | Usage Rate | Win Rate Lift | Deal Velocity | Action |
|---|---|---|---|---|---|
| CrowdStrike Displacement Battle Card v3 | 82 | 71% of CS competitive deals | +8.2% | -6 days | 🟢 Champion — replicate format |
| "CISO's Guide to XDR ROI" One-pager | 79 | 44% of enterprise deals | +6.8% | -11 days | 🟢 Champion — update with 2025 data |
| Platform Overview Deck (2024) | 61 | 83% of all deals | +2.1% | +3 days | 🟡 Update needed — used but not converting |
| Gartner Magic Quadrant Positioning Card | 57 | 38% of enterprise deals | +4.3% | +1 day | 🟡 Refresh — buyers now expect 2025 data |
| Technical Architecture Deep-Dive (SE tool) | 21 | 12% of deals | -1.2% | +14 days | 🔴 Sunset — only lengthens cycles |

*Critical Content Gaps Identified (from Gong analysis, 847 calls analyzed):*

1. **"Why now" urgency content for CISO budget cycles** — Objection "we're revisiting in Q4 when the budget is confirmed" appeared in 67 deals this quarter with no documented response. Estimated pipeline at risk: $4.2M. Build: "CISO Budget Timing Guide" one-pager. Build time: 4 hours. Projected impact: +3% close rate on 67 deals = $107K influenced revenue.

2. **Security Engineer technical validation toolkit** — In 34 enterprise deals, SE created custom architecture diagrams that weren't in Highspot. These deals had 51% win rate vs. 24% baseline. Build: Standardize the top 5 SE-created diagrams into a library. Build time: 12 hours. Projected impact: Replicating 51% win rate across all enterprise deals = $850K incremental revenue.

3. **"SentinelOne to Meridian Migration" battle card** — SentinelOne appeared as incumbent in 28 deals this quarter. No dedicated displacement content exists. Current win rate in these deals: 11%. Competitive win rate overall: 27%. Gap cost this quarter: ~$1.1M in lost deals.

*PMM ROI This Quarter:*
- Content-influenced pipeline: $8.4M (deals where 3+ assets used)
- Win rate in content-heavy deals: 38% vs. 19% in content-light deals
- PMM content investment this quarter: $52,000 (7 PMM-hours/week × 13 weeks × $57/hr blended)
- Revenue ROI: $8.4M pipeline × 38% win rate = $3.2M closed revenue influenced
- ROI multiple: 61x cost

## Success Metrics

- **Content adoption rate**: % of AEs using 3+ assets per deal (target: >65% within 90 days)
- **Win-rate lift delta**: Win rate in deals with high content usage vs. low (target: >8% lift)
- **Deal velocity impact**: Average days-to-close in content-heavy vs. content-light deals (target: -10 days)
- **Content gap closure rate**: % of identified gaps filled within 60 days (target: >50%)
- **PMM ROI multiple**: Revenue influenced ÷ PMM investment (target: >20x)
- **Sunset rate**: % of library assets removed quarterly (healthy = 15-20%; zero = hoarding)
- **Shadow content reduction**: % decline in reps creating their own materials (target: -40% in 6 months)

## Related Prompts

- [Sales Enablement Content Factory & Battle Card Revenue Intelligence](../../03_Content-&-Creative/Sales-Enablement-Content/AI-Powered-B2B-Sales-Enablement-Content-Factory-&-Battle-Card-Revenue-Intelligence-Engine.md)
- [B2B Content Asset Attribution & Pipeline Influence Intelligence](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/B2B-Content-Asset-Attribution-&-Pipeline-Influence-Intelligence-Engine.md)
- [B2B Win-Loss Analysis & Deal Forensics Intelligence](../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/B2B-Win-Loss-Analysis-&-Deal-Forensics-Intelligence-Engine.md)
- [PMM Revenue Impact Measurement & Performance Intelligence](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-B2B-Product-Marketing-Revenue-Impact-Measurement-&-PMM-Performance-Intelligence-Engine.md)

## Integration Tips

- **Highspot**: Use Highspot Analytics API to pull asset view data, rep usage, and buyer engagement metrics. Connect to Salesforce via native integration to map content to opportunity outcomes. Build custom dashboards in Highspot Insights.
- **Seismic**: Use LiveInsights to track buyer engagement in real-time. Connect Seismic to Salesforce with the native Seismic connector. Export usage data via Seismic API for advanced analytics in your BI tool.
- **Gong**: Use Gong's Deals and Library search to find calls where competitors were mentioned. Export call data via Gong API and process with LLM to identify objections and content gaps at scale.
- **Salesforce**: Create a "Content Used" multi-select field on the Opportunity object. Train reps to check boxes at each stage. Build Salesforce reports connecting content use to outcome fields.
- **HubSpot**: Use HubSpot's Sales Content Analytics (available in Sales Hub Professional+) to track document opens and time-on-page. Build custom HubSpot reports linking content engagement to deal stage progression.
- **Google Data Studio / Looker Studio**: Connect Highspot/Seismic export + Salesforce via Supermetrics or Coupler.io for free BI dashboarding if your stack doesn't have native analytics.
- **Notion or Confluence**: Use as a PMM Content Backlog tracker. Create a database with the Content Request Scoring Rubric fields — integrate with Salesforce via Zapier to auto-populate requests from lost deal data.

## Troubleshooting

**Problem: Sales reps won't log content used in CRM**
*Solution:* Don't require manual logging. Instead, use your enablement platform's native Salesforce sync (Highspot, Seismic) to auto-log content opens at the opportunity level. If no native sync exists, auto-populate the "Content Used" field using email attachment tracking via your sales engagement platform (Salesloft, Outreach). Manual logging fails within 3 months — build passive tracking from day one.

**Problem: Sample sizes too small to show statistically significant win rate lift**
*Solution:* Aggregate at the asset TYPE level first, not the individual asset level. Instead of "this one battle card lifts win rate 8%," report "deals using ANY competitive battle card have a 34% win rate vs. 21% without — across 187 competitive deals." Once you have 90+ days of data, you'll have enough individual asset data for asset-level analysis. In the interim, use deal velocity (days-to-close) as your primary metric — it shows impact faster with smaller samples.

**Problem: PMM team can't get deal-level data from sales or RevOps**
*Solution:* Bypass the political obstacle by starting with data you DO control. Pull your enablement platform's usage data + the 6-month closed deal list from CRM yourself. Do a manual match in a Google Sheet: for each closed deal, did the rep open an asset within 14 days before close? This gives you 80% of the insight with none of the dependency. Present the results to sales leadership — their demand for better data will unlock RevOps access faster than any internal request.

## Version History
- v1.0: Initial creation (auto-generated)
