# AI-Powered B2B Competitive Win-Rate Analytics & Revenue-Impact Intelligence Engine - Prove Every CI Dollar Drives Revenue and Prioritize Competitive Battles by ARR at Stake

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** competitive-intelligence, win-rate, revenue-analytics, product-marketing, pmm, salesforce, hubspot, gong, klue, crayon, competitive-revenue-model, pipeline-analytics, b2b-saas

## Overview
Builds an automated competitive win-rate analytics program that continuously measures competitive performance by competitor, deal segment, persona, and geography — then models the revenue impact of improving win rates and generates CFO-ready ROI reports on competitive intelligence investments. Use this when leadership asks "why are we spending $180K/year on Klue?" when you're losing 60% of deals to one competitor but don't know why, when you can't prioritize which competitive battles deserve PMM investment, or when competitive intelligence operates on gut feel instead of a revenue model.

## Quick Copy-Paste Version

You are a senior product marketing strategist specializing in competitive analytics and revenue-linked CI measurement. I need to build an AI-powered competitive win-rate analytics system that connects competitive positioning investments to measurable revenue outcomes.

My competitive situation:
- Company type: [B2B SaaS / Enterprise Software / Developer Tools]
- ARR: [$X] | Growth target: [X% YoY]
- Primary competitors I lose to most: [List 3-5, e.g., "Salesforce 34% of losses, HubSpot 22%, Microsoft 18%"]
- Overall win rate: [X%] | Win rate vs. top competitor: [X% if tracked, or "unknown"]
- Average ACV: [$X] | Average sales cycle: [X days]
- CRM: [HubSpot / Salesforce] | Call intelligence: [Gong / Chorus / None]
- CI tools: [Klue / Crayon / Dealfront / None]
- Annual CI program spend: [$X including tools, PMM time, and external research]
- Biggest competitive intelligence gap: [e.g., "Can't attribute CI to win rate changes," "Don't know which competitors to focus on," "Battlecards exist but don't know if they help"]

Please deliver:
1. Competitive win-rate baseline analysis framework — the exact data model and CRM fields needed to track win rates by competitor, segment, and deal type with statistical confidence
2. Revenue-at-stake model — quantify the ARR impact of improving win rate by 5 percentage points against each primary competitor, segmented by ICP tier
3. Competitive performance dashboard design — the 8 key metrics, visualization types, and update cadence for a competitive analytics dashboard PMM and revenue leadership actually use
4. CI program ROI calculator — how to attribute pipeline won and retained to competitive intelligence investments (battlecards deployed, training sessions, in-deal support)
5. Competitive battle prioritization matrix — a scoring framework to decide which competitive matchups deserve the most PMM investment based on revenue at stake, win rate gap, and deal volume

## Advanced Customizable Version

ROLE: You are a VP of Product Marketing with 15 years of B2B SaaS experience building revenue-linked competitive intelligence programs at companies from Series A through post-IPO. You specialize in connecting competitive intelligence investments to measurable win-rate outcomes; in building competitive analytics models that CFOs accept as credible revenue attribution; in designing competitive performance dashboards used by sales, marketing, and executive leadership; in applying statistical rigor to win-rate analysis to distinguish meaningful competitive trends from noise; and in building the operating model for a CI program where investment prioritization is driven by ARR-at-stake modeling rather than PMM intuition. You operate from the core belief that competitive intelligence programs live or die by their ability to show causation — not just correlation — between CI activity and revenue outcomes, and you design measurement systems from the revenue model backward, not the data collection forward.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Stage / ARR: [Series B / $22M ARR | Series C / $68M ARR | Series D+ / $150M ARR]
- Industry vertical: [e.g., RevOps, HR Tech, FinTech, DevTools, Legal Tech, CX Platform]
- ICP: [Job titles, company sizes, industries — e.g., "VP Finance at 200-2000 employee B2B SaaS companies"]
- ACV: [$X average] | Range: [$X SMB to $X Enterprise]
- Sales cycle: [X days average] | By segment: [SMB: X days / Mid-market: X days / Enterprise: X days]
- Quota-carrying reps: [X AEs] | SE team: [X]
- Gross win rate: [X%] | Net win rate (excl. no-decision): [X%]
- Pipeline volume: [$XM pipeline generated per quarter]
- Annual recurring revenue target: [$X]
- Current ARR churn rate: [X%] | Competitive churn rate (if tracked): [X%]

COMPETITIVE LANDSCAPE:
- Primary competitor 1: [Name] — win rate vs. them: [X%] | volume of competitive deals per quarter: [X] | average ACV in competitive deals: [$X]
- Primary competitor 2: [Name] — win rate: [X%] | deal volume: [X] | avg ACV: [$X]
- Primary competitor 3: [Name] — win rate: [X%] | deal volume: [X] | avg ACV: [$X]
- Primary competitor 4 (emerging): [Name or "None"] — win rate: [X%] | deal volume: [X]
- Status quo / do nothing: [% of losses attributed to "no decision" or "status quo wins"]
- Most common loss reason vs. top competitor: [e.g., "Price 45%, Feature gap 32%, Incumbent advantage 23%"]
- Deals with competitive overlay vs. without: [Are competitive deals tracked as a CRM field? Yes / No / Inconsistently]
- Competitive displacement wins: [# or % of deals where you replaced a competitor's existing customer]

CURRENT CI MEASUREMENT STATE:
- Win/loss data quality: [All opportunities have close reason + competitor field / Inconsistently filled / No structured tracking]
- Competitive field CRM coverage: [X% of closed opportunities have a competitor identified]
- Statistical confidence issue: [Total competitive deal volume per quarter per competitor — needed to assess significance]
- Current CI metrics tracked: [Win rate by competitor / No formal tracking / Only deal-level anecdotes]
- Battlecard usage tracking: [Tracked in enablement platform / Estimated from rep surveys / Not tracked]
- CI program ROI: [Formally measured / Estimated / Not measured]
- Existing competitive dashboards: [Describe what exists today, e.g., "Salesforce report with win rate by competitor — monthly pull"]
- Revenue attributed to CI: [Formally tracked / "We believe it helps" / No attribution]

CI PROGRAM INVESTMENT:
- CI tools annual cost: [$X — e.g., Klue $80K, Crayon $60K, Dealfront $40K]
- PMM time allocated to CI: [X hours/week × X PMMs = X annual FTE hours, valued at $X]
- Sales CI training/enablement time: [X hours/quarter per AE × X AEs = X hours annually]
- External CI research or advisory: [$X annually]
- Total annual CI program investment: [$X]

TECHNICAL STACK:
- CRM: [HubSpot / Salesforce] — competitive tracking fields: [List existing fields]
- Call intelligence: [Gong / Chorus / Clari Copilot / None]
- Sales enablement: [Highspot / Seismic / Guru / Notion / Google Drive]
- CI platform: [Klue / Crayon / Dealfront / Kompyte / None]
- BI / dashboarding: [Tableau / Looker / Power BI / HubSpot Dashboards / Salesforce Reports]
- Revenue intelligence: [Clari / Bowtie / Aviso / None]
- CRM data enrichment: [Clearbit / ZoomInfo / Bombora / None]

DELIVERABLES REQUIRED:

**Section 1: Competitive Win-Rate Baseline Data Model**

Design the definitive competitive win-rate data model with:

*CRM Fields Required (add these if missing):*
- Primary Competitor field (single-select, required on all opportunities at Stage 2+)
- Secondary Competitor field (multi-select, optional)
- Competitive Deal flag (boolean — yes if any competitor involved)
- Competitive Loss Reason (single-select: Price / Feature Gap / Incumbent Advantage / Integration Gap / Implementation Concerns / Champion Left / Relationship / Compliance / Other)
- Competitive Win Reason (single-select: Better ROI Story / Superior Feature / Relationship / Better Implementation / Reference Customer Match / Displaced Incumbent / Other)
- Competitive displacement flag (boolean — was an existing competitor's customer converted)
- Competitor first mentioned stage (Stage 1 / 2 / 3 / 4 — when did competitor first appear in deal)
- Battlecard used in deal (boolean — pull from enablement platform API if available)
- Competitive coaching request (boolean — did AE request PMM competitive support)

*Win-Rate Calculation Methodology:*
- Gross win rate by competitor: Closed-Won vs. Total Closed-Won + Closed-Lost where competitor = X (exclude no-decisions from denominator for competitive win rate; include in total pipeline win rate)
- Minimum sample size threshold: Flag win rates with fewer than 25 closed opportunities as "insufficient sample — directional only"
- Trending methodology: Rolling 90-day win rate vs. prior 90-day period — show trend direction and delta, not just point-in-time
- Segmented win rates: Break down by deal segment (SMB / Mid-Market / Enterprise), primary buyer persona (VP / Director / C-Suite), industry vertical, and geo region
- Statistical significance test: Flag win-rate changes greater than 5 percentage points as "potentially significant — investigate" only when n>30 per period
- Win-rate adjusted for deal quality: Compare win rate in deals where AE reported battlecard usage vs. where no CI asset was used (proxy for CI impact, not causation)

*Data Quality Scoring:*
Score your competitive CRM data on four dimensions (1-5 each):
1. **Coverage** — % of closed opportunities with competitor field populated
2. **Recency** — % of opportunities updated with competitive info within 48 hours of close
3. **Granularity** — # of competitive fields tracked per opportunity
4. **Attribution** — % of opportunities with both loss reason and competitor identified

Data quality score below 12/20 means win-rate analysis is directional only. Provide a 30-day data quality remediation plan.

**Section 2: Revenue-at-Stake Competitive Modeling**

Build the complete ARR-at-stake model for each primary competitor:

*ARR at Stake Calculation (per competitor):*
Annual Revenue at Stake = Quarterly Competitive Deal Volume 
  × 4 quarters 
  × Average ACV in competitive deals 
  × (Target Win Rate - Current Win Rate)

*Full Model Variables:*
- Current quarterly competitive deal volume vs. Competitor X: [Q]
- Current win rate vs. Competitor X: [W%]
- Target win rate (realistic +5pp improvement): [W+5%]
- Average ACV in competitive deals: [$ACV]
- Annual revenue currently won vs. Competitor X: Q × 4 × ACV × W
- Annual revenue at stake from 5pp win-rate improvement: Q × 4 × ACV × 0.05
- Annual revenue at stake from 10pp improvement: Q × 4 × ACV × 0.10
- CI ROI threshold: At what win-rate improvement does CI investment ($X annual spend) pay for itself?

*Revenue at Stake by Segment:*
Run the same model broken down by:
- SMB competitive deals (lower ACV, higher volume)
- Mid-market competitive deals
- Enterprise competitive deals (higher ACV, lower volume — even a 1-2pp win-rate improvement may justify significant CI investment)

*Competitive Churn Revenue at Stake:*
- Annual ARR at competitive churn risk: Total ARR × Competitive Churn Rate
- Revenue recovered per 1pp reduction in competitive churn: Total ARR × 0.01
- CI investment required to reduce competitive churn by 1pp: [Model based on customer success + PMM time for competitive retention plays]

*Build the Full Competitive Revenue Model Table:*
| Competitor | Quarterly Deal Volume | Current Win Rate | ACV | Annual Revenue Won | Revenue at Stake (+5pp) | Revenue at Stake (+10pp) | Competitive Churn ARR at Risk |
|---|---|---|---|---|---|---|---|
| Competitor 1 | X | X% | $X | $X | $X | $X | $X |
| Competitor 2 | X | X% | $X | $X | $X | $X | $X |

**Section 3: Competitive Performance Dashboard Design**

Design the competitive analytics dashboard with these 8 core metrics, visualization type, and update cadence:

*Metric 1: Win Rate Trend by Competitor (Primary Metric)*
- Visualization: Line chart, rolling 90-day win rate for top 5 competitors on one chart
- Update cadence: Refreshes daily from CRM
- Alert threshold: Auto-alert PMM + Sales VP when any competitor's win rate changes by >5pp over rolling 30 days
- Segmentation toggle: All deals / SMB / Mid-market / Enterprise

*Metric 2: Revenue at Stake Heatmap*
- Visualization: 2×2 matrix — X axis = Win Rate Gap from Target, Y axis = Annual Revenue at Stake
- Quadrant interpretation: Top-right (high revenue at stake, large win-rate gap) = highest priority competitive battle; Bottom-left = monitor only
- Update cadence: Monthly recalculation as ACV and deal volume data updates

*Metric 3: Competitive Deal Pipeline Coverage*
- Visualization: Funnel with competitive deal volume and % at each stage vs. non-competitive deals
- Key insight: Do competitive deals stall at a specific stage? (e.g., 40% higher drop-off at Stage 3 vs. non-competitive) — identifies where CI intervention is needed
- Update cadence: Weekly, aligned to pipeline review cadence

*Metric 4: Competitive Loss Reason Pareto*
- Visualization: Stacked bar chart — top 5 loss reasons by competitor (price vs. feature gap vs. integration vs. other)
- Filter: By quarter, competitor, and deal segment
- Key use: Drives CI investment decisions — a pricing-driven loss requires different CI than a feature-gap loss
- Update cadence: Monthly

*Metric 5: CI Asset Utilization vs. Win Rate Correlation*
- Visualization: Scatter plot — X axis = battlecard views per AE per quarter, Y axis = win rate vs. primary competitor
- Caveat display: "Correlation only — causation requires controlled analysis" displayed on chart
- Data source: Enablement platform API (Highspot/Seismic/Guru) + CRM win rate
- Update cadence: Quarterly

*Metric 6: Competitive Displacement vs. Displacement Loss Rate*
- Visualization: Dual bar — deals won displacing competitor / deals lost to competitor displacing your installed base
- Key metric: Net competitive displacement score = wins displacing competitors minus losses from competitors displacing you
- Alert: Flag when displacement loss rate exceeds displacement win rate (net negative competitive position)
- Update cadence: Monthly

*Metric 7: Competitive Win Rate by Sales Rep Tenure*
- Visualization: Bar chart — win rate vs. top competitor segmented by rep tenure: <6 months / 6-18 months / 18+ months
- Key insight: Large win-rate gap between new and tenured reps = CI training opportunity for new hire onboarding
- Update cadence: Quarterly

*Metric 8: CI Program ROI Scorecard*
- Visualization: Scorecard with 4 KPIs: (1) Revenue attributed to battlecard-assisted wins, (2) Win-rate delta in coached vs. uncoached competitive deals, (3) Competitive deal cycle length vs. non-competitive, (4) CI program investment as % of revenue at stake
- Update cadence: Quarterly, reviewed in PMM business review

**Section 4: CI Program ROI Attribution Model**

Design the three-tier CI ROI measurement framework:

*Tier 1: Activity Attribution (Lagging, Correlation-Based)*
- Battlecard-assisted win revenue: Sum of ACV from closed-won deals where enablement platform records a battlecard view by the AE within the deal's sales cycle
- Formula: ΣACV(closed-won deals where battlecard_view_date ≥ opportunity_created_date AND battlecard_view_date ≤ close_date AND competitor = battlecard_topic)
- Limitation: AEs may view battlecards for deals they would have won anyway — this overstates CI impact
- Credibility level: Directional — use for internal PMM reporting and executive updates, not for finance sign-off

*Tier 2: Coaching Attribution (Stronger Signal)*
- PMM competitive coaching requests tracked: Count and outcome of deals where AE formally requested PMM competitive support (via Slack, CI platform, or email)
- Win rate in coached deals vs. uncoached competitive deals: Compare outcomes — statistically meaningful only with n>20 per group
- Average ACV in coached deals: If coached deals skew larger (they will), normalize before comparing win rates
- Time from coaching request to deal close: Proxy for how late in the cycle CI is being engaged

*Tier 3: Holdout Experiment (Causation — for high-stakes CI investment decisions)*
- Experimental design: Randomly assign a cohort of AEs to a 90-day period with enhanced CI support (new battlecard, weekly competitive brief, PMM office hours) vs. control cohort with standard CI access
- Minimum viable experiment: 20+ AEs per group, 90 days minimum, primary metric = win rate vs. designated competitor
- Statistical analysis: Two-sample proportion z-test for win-rate comparison; 95% confidence threshold required to declare CI program impact
- Note: This requires sales leadership buy-in and clean CRM data — budget 60 days for program design and alignment before experiment launch

*CI Program ROI Report (Quarterly Format):*
Section 1: Program Investment ($X tools + $Y PMM time = $Z total)
Section 2: Activity metrics (battlecards updated, AEs trained, coaching sessions run)
Section 3: Tier 1 attributed revenue ($X — conservative, correlation-based)
Section 4: Win-rate trend by competitor (rolling 90-day — directional evidence of program impact)
Section 5: Revenue at stake model update (as ACV and deal volume data refreshes)
Section 6: Next quarter CI investment priorities (ranked by ARR at stake)

**Section 5: Competitive Battle Prioritization Matrix**

Score each competitor on four dimensions to determine CI investment priority:

*Dimension 1: Annual Revenue at Stake (0-25 points)*
- $5M+ annually: 25 points
- $2M-$5M: 20 points
- $1M-$2M: 15 points
- $500K-$1M: 10 points
- Under $500K: 5 points

*Dimension 2: Win-Rate Improvement Potential (0-25 points)*
Win rate gap = Target win rate (industry benchmark or internal best-segment performance) minus current win rate
- Gap >20pp: 25 points (significant improvement possible)
- Gap 10-20pp: 20 points
- Gap 5-10pp: 15 points
- Gap 1-5pp: 10 points
- At or above target: 5 points (maintain, don't over-invest)

*Dimension 3: Deal Velocity Impact (0-25 points)*
Do competitive deals take longer to close than non-competitive deals?
- Competitive deals close >30% slower: 25 points (CI can accelerate sales cycle, high leverage)
- 15-30% slower: 20 points
- 5-15% slower: 15 points
- Similar speed: 10 points
- Faster (competitive urgency helps): 5 points

*Dimension 4: Trend Direction (0-25 points)*
Is your win rate trending up or down vs. this competitor over the last 6 months?
- Win rate declining >5pp: 25 points (urgent — competitive threat accelerating)
- Declining 2-5pp: 20 points
- Flat (±2pp): 15 points
- Improving 2-5pp: 10 points
- Improving >5pp (your CI is working): 5 points (maintain what's working)

*Prioritization Matrix Output:*
| Competitor | Revenue at Stake | Win-Rate Potential | Deal Velocity | Trend | Total Score | Recommended Investment |
|---|---|---|---|---|---|---|
| Competitor 1 | 25 | 20 | 25 | 20 | 90 | Priority 1 — Full PMM program |
| Competitor 2 | 15 | 25 | 10 | 15 | 65 | Priority 2 — Quarterly refresh |
| Competitor 3 | 10 | 10 | 5 | 10 | 35 | Priority 3 — Monitor only |

Investment tiers:
- 80-100 points: Full CI program (dedicated PMM time, real-time monitoring, quarterly battlecard refresh, monthly AE training)
- 60-79 points: Standard CI program (quarterly battlecard update, bi-annual AE training, monthly monitoring)
- 40-59 points: Light CI (semi-annual battlecard review, basic monitoring)
- Below 40: Monitor only (flag for escalation if trends shift)

## Example Input/Output

**Example Input:**
Company: DataStack Inc. — B2B data integration platform, $38M ARR, Series C
ICP: VP Data Engineering and Head of Data Platform at 500-5000 employee companies
ACV: $75K average | Sales cycle: 65 days | 14 AEs
Top competitors: Fivetran (34% of losses), dbt Labs (18% of losses), Informatica (14% of losses, enterprise)
Win rate vs. Fivetran: 38% | Quarterly competitive deal volume vs. Fivetran: 22 deals
CI program spend: $140K/year (Klue $75K + PMM time $65K)
CRM: Salesforce with competitor field populated on 71% of closed deals

**Example Output (Section 2 — Revenue at Stake Model for Fivetran):**

*Current State:*
- Quarterly competitive deals vs. Fivetran: 22 deals
- Annual competitive deal volume: 88 deals
- Current win rate: 38% → Annual wins: 33 deals
- Average ACV in Fivetran competitive deals: $68K (slightly below average — these skew mid-market)
- Annual revenue won vs. Fivetran: 33 × $68K = **$2.24M ARR**

*Revenue at Stake (Win Rate Improvement):*
- +5pp win rate improvement (38% → 43%): 88 × 0.05 × $68K = **$299,200 additional ARR/year**
- +10pp improvement (38% → 48%): 88 × 0.10 × $68K = **$598,400 additional ARR/year**
- Win-rate improvement required to fully cover $140K CI program spend: $140K ÷ ($68K × 88) = 2.3pp win-rate improvement — CI program pays for itself at a 2.3pp improvement vs. Fivetran alone
- Payback period on CI investment at 5pp improvement: $140K ÷ ($299,200/12) = 5.6 months

*Prioritization Score:*
- Revenue at stake: $1M-$2M → 15 points
- Win-rate gap: Target 50% (current best segment), gap = 12pp → 20 points
- Deal velocity: Fivetran deals close in 82 days vs. 65-day average → 25% slower → 20 points
- Trend: Win rate dropped from 43% (Q1) to 38% (Q3) → declining ~5pp → 20 points
- **Total: 75 points → Priority 2 — Standard CI Program**

*Recommendation:* Upgrade Fivetran CI to Priority 1 if win rate drops below 35% or deal volume increases by >25%. Current investment allocation is appropriate but requires quarterly battlecard refresh (Fivetran launched 3 new connectors in 60 days) and a specific focus on the mid-market segment where win rate is 29% vs. 51% in enterprise.

## Success Metrics

**Quantitative output quality:**
- Revenue at stake model includes specific dollar figures by competitor (not ranges) ✓
- Win-rate analysis flags statistical confidence levels for each competitor ✓
- CI ROI calculator shows specific payback period for program investment ✓
- Prioritization matrix produces ranked output with investment tier recommendations ✓
- Dashboard design specifies update cadence and alert thresholds for each metric ✓

**Qualitative quality:**
- Tier 3 holdout experiment design includes specific statistical test and sample size requirements ✓
- Data quality remediation plan is specific to your CRM and field coverage gaps ✓
- ROI attribution model distinguishes correlation from causation with explicit credibility levels ✓
- Output is usable by a PMM in a board update or QBR without additional interpretation ✓

**Output is insufficient if:**
- Win rates are presented without confidence levels or sample size caveats
- Revenue model uses "illustrative" numbers rather than your actual deal volume and ACV
- ROI model doesn't account for attribution bias in battlecard-assisted win calculation
- Dashboard doesn't include alert thresholds triggering action from PMM and Sales VP

## Related Prompts

- [AI-Powered B2B Competitive Intelligence Automation & Battlecard Revenue Impact Engine](./AI-Powered-B2B-Competitive-Intelligence-Automation-&-Battlecard-Revenue-Impact-Engine.md) — Build the CI monitoring and battlecard system this analytics engine measures
- [AI-Powered B2B In-Deal Competitive Intelligence & Real-Time Counter-Messaging Revenue Intelligence Engine](./AI-Powered-B2B-In-Deal-Competitive-Intelligence-&-Real-Time-Counter-Messaging-Revenue-Intelligence-Engine.md) — The deal-level CI activation layer
- [AI-Powered B2B Win-Loss Interview Program Design & Competitive Intelligence Loop Intelligence Engine](../../02_Product-Marketing/Customer-&-Market-Research/AI-Powered-B2B-Win-Loss-Interview-Program-Design-&-Competitive-Intelligence-Loop-Intelligence-Engine.md) — Qualitative win-loss research that feeds competitive analytics
- [AI-Powered B2B Revenue Operations Intelligence & Marketing-Sales Unified Pipeline Analytics Engine](../../05_Analytics-&-Performance/Sales-Enablement-Analytics/AI-Powered-B2B-Revenue-Operations-Intelligence-&-Marketing-Sales-Unified-Pipeline-Analytics-Engine.md) — RevOps analytics layer that competitive win-rate data plugs into

## Integration Tips

**Salesforce:**
- Create a `Competitive_Analytics` custom report type joining Opportunity + Activity + Enablement Platform data via Salesforce API
- Build a Competitive Performance dashboard in Salesforce with the 8 metrics above — refresh via scheduled flows
- Use Salesforce Einstein Analytics (or Tableau CRM) for win-rate trend visualization with statistical confidence bands
- Required custom fields: add `Battlecard_Viewed__c` (boolean, auto-populated via Highspot/Seismic webhook) to Opportunity object to enable Tier 1 CI attribution

**HubSpot:**
- Build competitive win-rate reports using the Deals report builder: filter by `Competitor` property, segment by `Close Date`, group by `Deal Stage`
- Use HubSpot Workflows to auto-create a competitive coaching task in the AE's queue when a deal enters Stage 3 with a competitor identified — triggers PMM review
- Connect HubSpot to Looker Studio (free) for the win-rate trend dashboard if HubSpot's native reporting lacks sufficient time-series capability

**Gong:**
- Run a Gong Tracker for each primary competitor's name — flags every call mention and extracts the context (positive, negative, question from prospect, objection)
- Build a Gong Smart Tracker for top competitive objections: "price," "feature X," "implementation" — feeds directly into the Competitive Loss Reason Pareto (Section 3, Metric 4)
- Monthly Gong competitive trends report: top 5 competitor mentions by volume, sentiment trend, and stage where competitor is first mentioned (Stage 1 mentions are different from Stage 4 mentions — Stage 4 is a CI failure; Stage 1 is normal awareness)

**Klue / Crayon:**
- Klue API → push battlecard view events to Salesforce/HubSpot as activities — enables Tier 1 CI attribution without manual tracking
- Crayon Revenue Intelligence → configure deal alerts for competitive mentions in Gong transcripts, auto-populate competitor field in CRM when call mentions a competitor 3+ times
- Both platforms: export competitive deal data monthly to the BI tool for the win-rate trend dashboard

**Tableau / Looker:**
- Build the 2×2 Revenue at Stake Heatmap using a calculated field: X axis = (Target_Win_Rate - Current_Win_Rate), Y axis = Annual_Revenue_at_Stake (deal volume × 4 × ACV × target improvement)
- Schedule weekly competitive win-rate email digest from Tableau/Looker to PMM, Sales VP, and CRO — include trend arrows and alert flags automatically

**Notion / Google Sheets (lighter-weight alternative):**
- Monthly competitive win-rate tracker: Google Sheet pulling CRM data via Coefficient or Zapier, feeding into a Notion competitive dashboard used in the monthly competitive review meeting
- Win-rate trend chart: Google Sheets native chart with 12-month rolling window — adequate for teams under $25M ARR where Tableau licensing isn't justified

## Troubleshooting

**Problem:** CRM data coverage is below 60% — competitive fields aren't filled consistently, making win-rate analysis unreliable.
**Fix:** Launch a 30-day "data quality sprint" — run a Salesforce/HubSpot report of all closed opportunities from the last 90 days missing a competitor field; assign AE managers to backfill their teams' records in the next 2 weeks; make the competitor field required at Stage 2 in your CRM validation rules (not just a picklist — a hard block that prevents stage advancement without filling the field). Pair with a Slack message to all AEs from the CRO explaining why competitive data is essential for CI investment decisions — reps respond to "we're using this data to build better battlecards" better than compliance messaging.

**Problem:** Win rates show high variance quarter-to-quarter, making it impossible to identify real trends.
**Fix:** The root cause is almost always small sample size. If you close fewer than 25 competitive deals per quarter per competitor, you cannot use quarterly win-rate snapshots to identify trends — the statistical noise will swamp the signal. Switch to a rolling 12-month win rate with a 30-day update cadence: take all closed deals from the last 365 days, calculate win rate, then recalculate each month rolling forward. This smooths quarterly noise while preserving recency sensitivity. Flag competitors where n<25 trailing-twelve-months as "directional only — qualitative research required to supplement quantitative data."

**Problem:** Sales leadership is skeptical of CI ROI attribution — they believe correlation between battlecard use and wins is just because good AEs use both battlecards and win more.
**Fix:** This is a valid methodological critique and you should acknowledge it explicitly. Respond with two approaches: (1) Propose a Tier 3 holdout experiment for 90 days with voluntary AE participation — the only credible causal evidence; frame it as a 90-day pilot to help PMM prioritize CI investment, not a performance evaluation. (2) In the interim, slice battlecard-assisted win rate by rep tenure (control for AE quality) — if junior reps show a larger win-rate delta when using battlecards vs. not, that's a more credible signal that CI is helping rather than that good reps happen to use both. Present the experiment design to sales leadership as the path to CFO-grade attribution; they're usually willing to run 90-day pilots when framed as data-driven investment decisions.

## Version History
- v1.0: Initial creation (auto-generated)
