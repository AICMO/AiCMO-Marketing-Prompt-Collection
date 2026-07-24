# AI-Powered B2B SaaS Sales Enablement Content ROI Analytics & Win Rate Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** sales-enablement, product-marketing, analytics, win-rate, revenue-intelligence, b2b, saas

## Overview
This prompt deploys an AI analytics agent to audit every sales enablement asset — battlecards, pitch decks, ROI calculators, case studies, objection guides — and correlates usage and timing data with deal outcomes to surface which content drives wins, which content is dead weight, and where the gaps are costing you revenue. Use it quarterly to run a rigorous, data-driven PMM content ROI review that you can present to the CRO with dollar-level attribution.

## Quick Copy-Paste Version

You are a senior product marketing analyst specializing in B2B SaaS sales enablement effectiveness. I need you to analyze our sales enablement content library and correlate asset usage with deal outcomes.

Here is our data:
- Sales enablement platform content usage (views, shares, downloads by asset): [paste data or describe]
- CRM win/loss records for the past 6 months with deal size and close date: [paste data or describe]
- Gong/Chorus call intelligence data showing which assets were mentioned in calls: [paste data or describe]
- Asset inventory: [battlecards, pitch decks, case studies, ROI calculators, demo scripts, objection guides, competitive comparisons]

Analyze this data and produce:

1. **Win Rate by Asset** — For each content asset, calculate the win rate of deals where it was used vs. not used. Identify the top 5 assets with the highest win rate lift.

2. **Revenue Attribution by Asset Type** — Estimate closed-won revenue influenced by each asset category. Show the dollar impact of battlecards vs. case studies vs. ROI tools.

3. **Usage vs. Impact Matrix** — Plot assets on a 2x2: High Usage/High Win Rate (amplify), High Usage/Low Win Rate (fix or retire), Low Usage/High Win Rate (promote), Low Usage/Low Win Rate (kill).

4. **Timing Intelligence** — Identify at which deal stage each asset drives the most impact. Flag assets being used at the wrong stage.

5. **Gap Analysis** — Based on loss reasons and deal stage drop-off, identify 3 specific content gaps where a new asset would likely improve win rate.

6. **PMM Action Roadmap** — Prioritized list of: assets to retire, assets to update, assets to promote to sales, and new assets to build. Include expected revenue impact for each recommendation.

Format output as a board-ready PMM performance review with an executive summary, detailed findings, and an action plan.

## Advanced Customizable Version

ROLE: You are an expert product marketing analyst and revenue intelligence specialist with 12+ years experience in B2B SaaS. You specialize in quantifying the business impact of PMM programs, particularly sales enablement, using data from CRM systems, sales engagement platforms, and content analytics tools.

CONTEXT:
Company: [Company Name]
Product: [Product Name — B2B SaaS, describe category]
ACV Range: [e.g., $25K–$250K ARR]
Sales Motion: [e.g., field sales + SDR, inbound + AE, PLG + enterprise overlay]
Sales Cycle: [e.g., 60–120 days]
Team: [e.g., 3 PMMs supporting 45 AEs across 3 segments: SMB, Mid-Market, Enterprise]
Review Period: [e.g., Q2 2026, January–June 2026]
Competitive Environment: [e.g., competing primarily against Competitor A, Competitor B, open source]

DATA INPUTS (provide what you have; flag gaps):
1. Content Usage Data (from Highspot/Seismic/Showpad/Google Drive):
   [Asset name | Views | Shares | Rep usage rate | Last updated date]
   [Paste your data here]

2. CRM Win/Loss Data (from Salesforce/HubSpot):
   [Deal ID | Segment | ACV | Stage reached | Won/Lost | Loss reason | Primary competitor | Content used in deal (if tracked)]
   [Paste your data here]

3. Conversation Intelligence (from Gong/Chorus — optional but high-value):
   [Asset mentioned by rep | Deal ID | Call stage | Deal outcome]
   [Paste your data here]

4. Rep Feedback (from Slack/survey — optional):
   [Rep sentiment scores or comments by asset]
   [Paste your data here]

5. Current Asset Inventory:
   BATTLECARDS: [list titles]
   PITCH DECKS: [list titles — by segment/persona]
   CASE STUDIES: [list by industry/use case]
   ROI CALCULATORS: [list titles]
   DEMO SCRIPTS / TALK TRACKS: [list titles]
   OBJECTION HANDLING GUIDES: [list titles]
   COMPETITIVE COMPARISON PAGES: [list titles]
   PROPOSAL TEMPLATES: [list titles]
   OTHER: [list]

ANALYSIS FRAMEWORK — Apply ALL of the following:

**MODULE 1: ASSET-LEVEL WIN RATE ANALYSIS**
For each asset in the inventory:
- Calculate win rate in deals where asset was used vs. not used
- Calculate win rate lift (delta vs. baseline)
- Segment by deal size (SMB/Mid-Market/Enterprise) and identify where each asset has disproportionate impact
- Flag assets with statistically meaningful sample sizes (n≥15 deals) vs. directional signals only
- Apply Jobs-to-be-Done lens: what buyer job does this asset help complete, and is that job high-stakes enough to influence the decision?

**MODULE 2: REVENUE ATTRIBUTION MODEL**
Build a PMM-influenced revenue model:
- First-touch content attribution: revenue from deals where PMM content was first meaningful touchpoint
- Multi-touch content attribution: weighted contribution of PMM assets across the deal timeline
- Battlecard influence: deals with battlecard usage — win rate and ACV premium vs. without
- Case study influence: specific industries/use cases where case studies have measurable lift
- ROI tool influence: correlation between ROI calculator usage and ACV, and deal velocity
- Total PMM-attributed pipeline and closed revenue for the period

**MODULE 3: DEAL STAGE TIMING ANALYSIS**
Map each asset to the deal stage where it was used and the outcome:
- Identify "right place, right time" assets: high usage at correct stage → strong outcome
- Identify "stage mismatches": assets used too early (before buyer is ready) or too late (deal already decided)
- Find the "sales playbook gaps": deal stages with no PMM content that show high drop-off rates
- Apply the MEDDPICC lens: which framework elements (Metrics, Economic Buyer, Decision Criteria, Decision Process, Implicate Pain, Champion, Competition) lack dedicated PMM support?

**MODULE 4: COMPETITIVE EFFECTIVENESS ANALYSIS**
For each active competitor:
- Win rate when corresponding battlecard was used vs. not used
- Specific objections/scenarios where PMM competitive content helped close deals
- Competitive scenarios with lowest win rates — likely indicating content gap or messaging weakness
- Rep confidence scores (from surveys/Gong data) in competitive positioning by competitor

**MODULE 5: CONTENT DECAY & FRESHNESS AUDIT**
- Flag assets not updated in 90+ days that are still in active use
- Identify assets using outdated product capabilities, competitor information, or pricing
- Calculate the "staleness risk" for deals in progress using outdated content

**MODULE 6: REP ADOPTION INTELLIGENCE**
- Identify reps with highest and lowest content adoption rates
- Correlate rep content usage with individual quota attainment
- Surface "dark usage" — assets reps are using that aren't tracked (mentioned on calls but not logged)
- Calculate the revenue gap between top-quartile content users and bottom-quartile users

**MODULE 7: GAP IDENTIFICATION & OPPORTUNITY SIZING**
For each identified content gap:
- Describe the specific sales scenario or buyer job the gap affects
- Estimate the number of deals in the review period where this gap was a factor in the loss
- Calculate the revenue opportunity if win rate in those deals improved by 15% (conservative) and 30% (optimistic)
- Priority score = (deal count × ACV × win rate delta) / estimated PMM effort to build

OUTPUT REQUIREMENTS:

**EXECUTIVE SUMMARY (board-ready, 1 page)**
- Total PMM-attributed closed revenue this period: $X
- Top 3 highest-ROI assets (name, win rate lift, revenue attributed)
- Top 3 assets to retire (with reason and risk of keeping them)
- Top 3 content gaps identified (with revenue opportunity sizing)
- Recommended PMM investment for next quarter to close gaps

**DETAILED FINDINGS REPORT**

Section 1: Win Rate Heatmap by Asset
[Asset | Usage Rate | Win Rate WITH | Win Rate WITHOUT | Lift | Confidence Level | Recommended Action]

Section 2: Revenue Attribution Summary
[Total pipeline influenced | Total closed-won influenced | By asset category]

Section 3: Deal Stage Timing Map
[Asset | Optimal Stage | Most Common Stage Used | Stage Mismatch Rate | Revenue Impact of Mismatch]

Section 4: Competitive Content Scorecard
[Competitor | Battlecard Coverage | Win Rate WITH Battlecard | Win Rate WITHOUT | Priority Action]

Section 5: Content Freshness Risk Register
[Asset | Last Updated | Usage Rate | Staleness Risk | Update Priority]

Section 6: Rep Adoption Analysis
[Content adoption quartile distribution | Revenue correlation | Dark usage signals]

Section 7: Content Gap Priority Matrix
[Gap | Affected Deal Scenarios | Revenue Opportunity (Conservative) | Revenue Opportunity (Optimistic) | Build Priority]

**PMM Q[X] ACTION PLAN**

RETIRE IMMEDIATELY (low usage, low impact):
- [Asset name] — Reason: [specific data] — Action: archive by [date]

UPDATE URGENTLY (high usage, outdated or underperforming):
- [Asset name] — Issue: [specific data] — Owner: [PMM name] — Deadline: [date]

PROMOTE TO SALES (high impact, low adoption):
- [Asset name] — Potential lift: [X% win rate increase] — Launch plan: [Slack, SKO, Gong library, etc.]

BUILD NEW (high-priority gaps):
1. [Content gap #1] — Business case: [X deals, $Y revenue opportunity] — Effort: [days] — Owner: [PMM]
2. [Content gap #2] — Business case: [X deals, $Y revenue opportunity] — Effort: [days] — Owner: [PMM]
3. [Content gap #3] — Business case: [X deals, $Y revenue opportunity] — Effort: [days] — Owner: [PMM]

**MEASUREMENT PLAN**
How to track PMM enablement ROI in next quarter:
- KPIs to set up in Salesforce/Highspot
- Gong alerts to configure
- Rep feedback loops to establish
- Next review date and success criteria

## Example Input/Output

**Input Example:**
> Company: Meridian Analytics (B2B SaaS data observability platform)
> ACV: $45K–$180K
> Sales Cycle: 75 days average
> Review Period: Q2 2026 (Jan–June)
> Deals analyzed: 147 (58 won, 89 lost)
> Asset inventory: 12 battlecards, 4 pitch decks (by segment), 8 case studies, 1 ROI calculator, 6 objection guides, 3 competitive comparison pages
> Usage data: Highspot export showing 42% of reps use battlecards, 78% use pitch decks, ROI calculator used in 18% of Mid-Market deals

**Output Example (Abbreviated):**

---
**EXECUTIVE SUMMARY — Meridian Analytics PMM Enablement ROI Report, Q2 2026**

**PMM-Attributed Closed Revenue: $2.1M** (34% of total $6.2M closed-won)

**Top 3 Highest-ROI Assets:**
1. **ROI Calculator (Mid-Market)** — 67% win rate when used vs. 41% without (+26pt lift). Revenue attributed: $420K across 14 deals. Problem: Only 18% of MM reps use it.
2. **Snowflake Displacement Battlecard** — 71% win rate vs. 52% without (+19pt lift). Revenue attributed: $310K. Problem: 38% of reps don't know it exists.
3. **FinServ Case Study (JPMorgan analog)** — Used in 9 financial services deals; 7 closed (78% win rate vs. 44% sector baseline). Revenue attributed: $285K.

**Top 3 Assets to Retire:**
1. **Legacy Competitive Comparison: Dynatrace** — Used in 6 deals in H1, 0 wins. Dynatrace exited this category in 2025; this doc is creating confusion. Risk: still showing up in Google Drive searches.
2. **"Platform Overview" Pitch Deck v2.3** — Updated in 2024 pre-rebrand. 22 views but 0 shares by reps. Replaced by v3.1 but v2.3 still indexed in Highspot.
3. **SMB Objection Guide** — 3 uses, 0 wins, ACV too low to have full discovery calls where this is needed.

**Top 3 Content Gaps + Revenue Opportunity:**
1. **IT Security/InfoSec Buyer Objection Guide** — 23 deals lost in Q2 with "security review" as top-3 factor. No PMM content addresses InfoSec persona objections. Conservative opportunity: $340K in recoverable revenue at +15% win rate.
2. **Databricks + Meridian Integration Story** — 31 prospects running Databricks identified via intent data. No co-sell narrative exists. Estimated opportunity: $520K if win rate matches our overall average.
3. **Mid-Market Business Case Template** — MM AEs building custom business cases from scratch; 40% of MM deals have "ROI not clear to CFO" as loss reason. Opportunity: $280K conservative.

---

## Success Metrics

- **Win rate lift measurement**: Track win rate for assets flagged as high-impact before and after promotion campaigns (8-week lag minimum for statistical validity)
- **Revenue attribution growth**: PMM-attributed revenue should grow from current baseline each quarter as you close content gaps
- **Rep adoption rate**: Target 70%+ usage of tier-1 assets by AEs; track via Highspot/Seismic analytics
- **Content gap closure rate**: 100% of prioritized gaps from the roadmap built within 2 quarters
- **Sales confidence scores**: Post-SKO rep surveys should show 80%+ confidence rating in competitive positioning (up from baseline)
- **Time-to-close correlation**: Measure whether ROI tool and business case template adoption reduces average sales cycle by at least 7 days

## Related Prompts

- `../../02_Product-Marketing/Messaging-&-Positioning/AI-Powered-B2B-SaaS-Competitive-Battlecard-Architecture-&-Real-Time-Sales-Enablement-Intelligence-Engine.md`
- `../../02_Product-Marketing/Sales-Enablement-Content/AI-Powered-Sales-Playbook-&-Revenue-Enablement-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Product-Marketing-Analytics/AI-Powered-B2B-SaaS-PMM-Messaging-Effectiveness-Analytics-&-Pipeline-Impact-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Competitive-Intelligence-Analytics/AI-Powered-Competitive-Win-Rate-Intelligence-&-Displacement-Revenue-Engine.md`

## Integration Tips

- **Salesforce**: Build a custom "PMM Content Used" field on the Opportunity object (multi-select picklist of asset names). Train reps and SDRs to log content usage at each stage. Use Salesforce Reports to pull win rate by asset automatically.
- **Highspot / Seismic / Showpad**: Export the "Content Activity" report monthly — this gives views, shares, downloads, and deal associations. Set up auto-export to a Google Sheet for quarterly aggregation.
- **Gong**: Use Gong's "Trackers" feature to create keyword trackers for each asset name (e.g., "ROI calculator", "battlecard"). Gong will automatically flag calls where these are mentioned and link to deal outcomes. Export to CSV monthly.
- **Notion**: Build a PMM Content Library in Notion with a "Performance Score" property updated quarterly from this analysis. Link each asset to its win rate data so PMs and AEs can self-serve on asset effectiveness.
- **Zapier/Make**: Automate a monthly data pull: Salesforce Opportunities → Google Sheets → trigger a Claude prompt analysis → output report to Notion or email to the PMM team.
- **Tableau / Looker**: If your revenue ops team uses BI tools, request a custom view joining Opportunity data with content usage data. Use this prompt's output structure as the dashboard spec.

## Troubleshooting

**Problem: No CRM data on which content was used in each deal.**
Solution: Don't let perfect be the enemy of good. Start with Gong/Chorus data alone — call intelligence is often more accurate than manual CRM logging. Alternatively, run a 15-minute rep survey asking "which assets did you use in your last 5 deals?" to get directional data. Then implement a lightweight CRM field going forward so next quarter's analysis has clean data.

**Problem: Sample sizes are too small to be statistically meaningful for individual assets.**
Solution: Aggregate by asset *category* (all battlecards vs. no battlecards) rather than individual file names when n<15 per asset. Use directional language ("suggests" rather than "proves") for small samples, and prioritize instrumentation fixes so you have better data in 90 days. Flag to CRO as a data quality investment that directly impacts revenue visibility.

**Problem: Reps say the content exists but they can't find it / don't use it.**
Solution: This is a distribution problem, not a content problem. Run the Usage vs. Impact Matrix first — if high-impact assets have low adoption, the PMM roadmap should prioritize an in-context Gong Assist integration or a Slack digest of "Deal Stage X? Use THIS asset" before building anything new.

## Version History
- v1.0: Initial creation (auto-generated)
