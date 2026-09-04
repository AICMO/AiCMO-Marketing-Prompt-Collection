# AI-Powered B2B SaaS Annual Demand Generation Calendar Architecture & Full-Year Pipeline Revenue Orchestration Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** demand-generation, annual-planning, pipeline-architecture, budget-allocation, campaign-calendar, b2b-saas, revenue-planning, marketing-operations, seasonal-optimization

## Overview
This prompt ingests your ARR targets, historical pipeline conversion rates, channel performance data, and buying cycle patterns to produce a complete 12-month demand generation calendar — with monthly pipeline targets by channel, specific campaign deployments by quarter, budget allocation logic, and autonomous rebalancing triggers. Use it at the start of each fiscal year, after a significant budget change, or when pipeline has fallen below target and you need to rebuild a plan that math checks out.

## Quick Copy-Paste Version

You are a senior B2B SaaS demand generation leader. Help me build a complete 12-month demand generation calendar and pipeline architecture for my company.

My revenue context:
- Annual ARR target: $[X]M new ARR
- Current ARR: $[X]M
- Average ACV: $[X]
- Average sales cycle: [X] days
- Marketing-sourced pipeline target: [X]% of total pipeline
- Required marketing-sourced pipeline (3x coverage): $[X]M

My channel performance (last 12 months):
- Inbound/SEO: [X] MQLs/month, [X]% MQL-to-opportunity, $[X] cost per opportunity
- Outbound/SDR: [X] meetings/month, [X]% meeting-to-opportunity, $[X] cost per opportunity
- Paid search: [X] MQLs/month, [X]% conversion, $[X] CPO
- Paid social (LinkedIn): [X] MQLs/month, [X]% conversion, $[X] CPO
- Events/field: [X] opportunities/quarter from events, $[X] cost per opportunity
- Partner/referral: [X] opportunities/quarter, $[X] CPO
- Content/thought leadership: [X]% of pipeline influenced

My buying cycle patterns:
- Slowest months (fewer buyers in market): [list months]
- Fastest months (peak buying activity): [list months]
- Industry-specific fiscal year end (when budgets open): [month]
- Key industry conferences: [list with months]

My total demand gen budget: $[X]/year

Deliver:
1. PIPELINE MATH: Monthly pipeline targets working backwards from ARR goal with 3x coverage
2. CHANNEL MIX BY QUARTER: Where to concentrate budget each quarter based on buying cycles
3. CAMPAIGN CALENDAR: Specific campaign types, themes, and channel activations by month
4. BUDGET ALLOCATION: Dollar amounts by channel by quarter with rebalancing triggers
5. LAUNCH SEQUENCE: First 90 days of campaigns to execute to hit Q1 targets
6. REBALANCING RULES: When and how to shift budget if a channel underperforms

## Advanced Customizable Version

**ROLE:**
You are a VP of Demand Generation with 15+ years building and managing 8-figure marketing programs for B2B SaaS companies from $10M to $500M ARR. You have designed annual go-to-market calendars for PE-backed SaaS, venture-backed hypergrowth companies, and public SaaS firms. You understand the math of pipeline coverage, seasonal buying cycle patterns, the relationship between brand investment and demand capture, and how to sequence a demand generation calendar so that Q1 and Q2 pipeline targets are achievable given 60-90 day sales cycles. You think in pipeline coverage ratios, cost per opportunity, channel contribution percentages, and program ROI — not vanity metrics. You build plans that are defensible to the CFO and achievable by the team.

**OBJECTIVE:**
Construct a complete 12-month demand generation calendar for [Company Name] that maps pipeline targets by month, allocates budget by channel and quarter, schedules specific campaign programs, defines the campaign theme architecture by quarter, and establishes the autonomous rebalancing triggers that will govern in-flight optimization.

**CONTEXT INPUT:**

Provide the following to build a precision plan:

COMPANY & REVENUE CONTEXT:
- Company: [Name] | Stage: [Series A / B / C / PE-backed / public]
- Current ARR: $[X]M | New ARR target: $[X]M
- Expansion/upsell ARR target (from existing customers): $[X]M
- Net new ARR target (new logos only): $[X]M
- Average new logo ACV: $[X] | Expansion ACV average: $[X]
- Average sales cycle (new logo): [X] days
- Average close rate (SQL-to-closed-won): [X]%
- Marketing-sourced pipeline % target: [X]% (of total pipeline)
- Required pipeline coverage ratio: [X]x (typically 3x–4x for B2B SaaS)
- Fiscal year: [January–December / February–January / other]

CHANNEL PERFORMANCE BASELINE (Last 12 Months):
For each channel, provide: volume, conversion rate, and cost per opportunity (CPO):
- SEO / Inbound content: [X] MQLs/month | [X]% MQL-to-opp | $[X] CPO
- SDR outbound: [X] meetings/month | [X]% meeting-to-opp | $[X] CPO
- Google Paid Search: [X] MQLs/month | [X]% conversion | $[X] CPO
- LinkedIn Ads: [X] MQLs/month | [X]% conversion | $[X] CPO
- Webinars: [X] MQLs/event | [X]% conversion | $[X] CPO per event
- Events/trade shows: [X] opps/event | $[X] CPO | [X] events per year attended
- Partner/referral: [X] opps/quarter | $[X] CPO
- Account-based (ABM): [X] opps/quarter | $[X] CPO
- Email nurture (existing database): [X] opps/month reactivated | $[X] CPO
- Content syndication: [X] MQLs/month | [X]% conversion | $[X] CPO

BUYING CYCLE PATTERNS:
- Industry fiscal year end (when annual budgets are approved): [Month]
- Peak buying seasons (historically highest close rates): [List 2–3 months]
- Slow periods (holidays, summer lulls, budget freezes): [List 2–3 months]
- Major industry conferences you attend or sponsor: [List with month and tier: keynote/booth/attend]
- Annual product launch cadence (when do you typically launch major features): [Q1/Q2/Q3/Q4]

COMPETITIVE & MARKET CONTEXT:
- Primary competitor's most active campaign periods (if known): [Describe]
- Key industry events dominated by competitors: [List]
- Category awareness level among your ICP: [Low/Medium/High — do they know the problem you solve?]
- Current brand awareness vs. category awareness: [Low/Medium/High]

TEAM & EXECUTION CAPACITY:
- Demand gen team headcount: [X FTEs] | Roles: [List]
- Content team: [X FTEs] | Roles: [List]
- Design/creative: [In-house X FTEs / Agency / Hybrid]
- SDR headcount: [X SDRs] | SDR pipeline coverage required: [X opps/SDR/quarter]
- Marketing operations capacity: [Describe automation tools and operator headcount]
- Maximum simultaneous campaigns manageable: [X concurrent campaigns]

BUDGET:
- Total annual demand gen budget: $[X]
- Budget locked vs. flexible: [X]% locked in H1 | [X]% flexibly reallocated
- Headcount (FTEs) included in budget: [Yes/No] — if yes, [X]% of budget is people cost
- Event budget pre-committed: $[X] (events already contracted)
- Agency/vendor retainers already committed: $[X]/month

**ANALYTICAL FRAMEWORK:**

**1. PIPELINE COVERAGE MATH — WORKING BACKWARDS FROM ARR**

Build a month-by-month pipeline factory model:

Step 1 — Required closed-won revenue by month:
- Take annual net-new ARR target
- Weight by historical quarterly distribution (typically Q1: 20%, Q2: 25%, Q3: 25%, Q4: 30% for most B2B SaaS)
- Adjust for your fiscal year patterns and seasonality

Step 2 — Required pipeline created each month (accounting for sales cycle):
- To close revenue in Month X, pipeline must be created in Month (X minus average sales cycle in months)
- Example: 90-day sales cycle means June revenue requires March pipeline creation
- Build this lag matrix for every month of the year

Step 3 — Required pipeline coverage (3x–4x multiplier):
- Monthly pipeline creation target = Monthly revenue target × coverage ratio ÷ close rate
- Split by marketing-sourced % and sales-sourced %

Step 4 — Required marketing-sourced opportunities per month:
- Marketing-sourced pipeline target ÷ average ACV = required opportunities
- Distribute across channels based on historical contribution %

**2. QUARTERLY CAMPAIGN THEME ARCHITECTURE**

Design the narrative arc of the year across 4 quarters:

Q1 — FOUNDATION & PIPE ACCELERATION (January–March):
- Primary objective: Rebuild pipeline from December slowdown; launch new annual narrative
- Campaign theme: [Company's annual "state of the market" narrative — tie to trends, research, or data]
- Primary channel investment: Outbound SDR activation + content syndication + ABM warm restart
- Anchor program: Annual research report or benchmark study (generates H1 pipeline via thought leadership)
- Key events: Industry conferences in Q1; host executive roundtable to warm enterprise accounts
- Campaign ratio: 70% demand capture (search, retargeting, review sites) / 30% demand creation (brand, content)

Q2 — ACCELERATION & EXPANSION (April–June):
- Primary objective: Hit H1 pipeline target; begin building Q3 pipeline buffer
- Campaign theme: [Category education + competitive differentiation — "why now" urgency messaging]
- Primary channel investment: Webinar series + LinkedIn sponsored content + events
- Anchor program: Customer success story campaign using Q1 wins as social proof
- Key events: Major industry conference (Q2 typically has highest event density for B2B SaaS)
- Campaign ratio: 60% demand capture / 40% demand creation — begin investing in longer-cycle brand

Q3 — BRAND INVESTMENT & FALL PREP (July–September):
- Primary objective: Build Q4 pipeline; invest in brand to compress Q4 sales cycles
- Campaign theme: [Vision/future-state messaging — thought leadership, category leadership]
- Primary channel investment: LinkedIn video/thought leadership + executive ABM + partner co-marketing
- Anchor program: Fall conference sponsorships + virtual summit or user conference
- Key events: Last major pre-Q4 conferences; begin SKO prep for sales kickoff
- Campaign ratio: 50% demand capture / 50% demand creation — peak brand investment period

Q4 — CONVERSION & YEAR-END URGENCY (October–December):
- Primary objective: Close-won maximum revenue; generate Q1 pipeline to avoid January gap
- Campaign theme: [Urgency/ROI/cost-of-inaction messaging — fiscal year-end budget use]
- Primary channel investment: Retargeting + paid search + SDR outbound to warm pipeline + direct mail to stalled deals
- Anchor program: "Use it or lose it" budget campaign; year-end pricing incentives (if applicable)
- Key events: Customer advisory board; QBR preparation support
- Campaign ratio: 85% demand capture / 15% demand creation — highest ROI conversion period

**3. MONTHLY CAMPAIGN DEPLOYMENT SCHEDULE**

For each month, output:
- Pipeline target (marketing-sourced opportunities required)
- Primary campaign activation (the anchor campaign that drives volume)
- Secondary campaign activation (supporting programs)
- Channel allocation for this month ($ by channel)
- Content asset to produce or activate this month
- Key launch date and team dependencies
- Success checkpoint: metric to review at month-end to assess if on track

**4. BUDGET ALLOCATION LOGIC**

Annual budget split framework:
- Always-on channels (SEO, paid search, SDR tools, email): [X]% of budget — non-negotiable floor
- Quarterly campaign programs (webinars, events, ABM): [X]% of budget — planned but adjustable
- Experimental/new channels: [X]% of budget — ring-fenced for testing
- Emergency/rebalancing reserve: [X]% held back for Q3-Q4 reallocation based on H1 performance

Quarterly budget distribution:
- Q1: [X]% of annual budget (heaviest investment to restart pipeline after December)
- Q2: [X]% of annual budget (sustain + expand)
- Q3: [X]% of annual budget (brand investment + fall prep)
- Q4: [X]% of annual budget (conversion-focused, lower spend needed as qualified pipeline is higher)

**5. REBALANCING TRIGGERS (AUTONOMOUS OPTIMIZATION RULES)**

Define hard rules for mid-year budget reallocation:

GREEN LIGHT rules (increase investment):
- Channel is delivering CPO ≤ [X]% of target CPO for 30 consecutive days → increase budget by 25%
- Channel is delivering MQLs at ≥120% of plan → increase budget by 15% from experimental reserve
- A specific campaign is converting SQLs at ≥150% of plan → extend campaign by 30 days, increase spend

RED FLAG rules (decrease investment):
- Channel CPO is ≥2x target for 45 consecutive days → reduce budget by 30%, reallocate to best performer
- Event delivers <50% of expected opportunity yield → deprioritize similar events in H2
- A campaign theme shows declining engagement for 3 consecutive weeks → kill the creative, test new angle

PIPELINE SHORTFALL emergency protocol:
- If pipeline coverage drops below 2.5x at any point → trigger emergency response mode
- Activate full outbound sequence to all Tier 1 intent accounts immediately
- Increase paid search budget by 50% focused on bottom-of-funnel keywords
- Launch competitor displacement campaign targeting customers of top 2 competitors
- Activate SDR outbound to entire re-engagement database with new angle

**OUTPUT REQUIREMENTS:**

Structure your response as:

**PIPELINE FACTORY MODEL**
A month-by-month table showing:
| Month | Closed-Won Target | Pipeline Creation Required | Mktg-Sourced Opps Needed | Primary Channels | Budget |
|-------|-----------------|--------------------------|------------------------|----------------|--------|

**QUARTERLY CAMPAIGN MASTER PLAN**
For each quarter: theme, anchor program, channel activation sequence, budget allocation, team assignments

**MONTH-BY-MONTH LAUNCH CALENDAR**
Specific campaign names, launch dates, channel mix, and expected pipeline contribution for each of the 12 months

**ANNUAL BUDGET ALLOCATION TABLE**
| Channel | Q1 Budget | Q2 Budget | Q3 Budget | Q4 Budget | Full Year | % of Total |
|---------|-----------|-----------|-----------|-----------|-----------|------------|

**FIRST 90-DAY EXECUTION PLAN**
The specific campaigns, assets, and activations to execute in January–March to ensure H1 pipeline is on track before any rebalancing opportunity exists

**REBALANCING DECISION TREE**
A flowchart-style decision framework: "If [metric] is [condition] at [checkpoint], then [action]"

## Example Input/Output

**Example Input:**

Company: Nexus — B2B SaaS revenue operations platform, $32M ARR, Series C
Annual new ARR target: $18M new ARR | Average ACV: $47K | Sales cycle: 82 days
Marketing-sourced pipeline target: 55% | Required pipeline coverage: 3.5x
Total demand gen budget: $3.4M/year

Channel performance (last year):
- Inbound SEO: 180 MQLs/month, 18% MQL-to-opp, $320 CPO
- SDR outbound: 55 meetings/month, 38% to opp, $1,100 CPO
- Google Ads: 90 MQLs/month, 15% conversion, $680 CPO
- LinkedIn Ads: 70 MQLs/month, 11% conversion, $920 CPO
- Webinars: 140 MQLs/event, 14% conversion, $2,800 CPO per event (4 events/year)
- Events: 22 opps/quarter, $4,200 CPO
- Partner/referral: 18 opps/quarter, $1,800 CPO

Buying cycle: Customers' fiscal year ends December 31; peak close months are June and December. Slowest periods: August and late December. Major conference: SaaStr Annual (September), Dreamforce (September/October).

Team: 4 demand gen FTEs, 2 content FTEs, agency for design. 8 SDRs. HubSpot MAP. Max 4 simultaneous campaigns.

---

**Example Output:**

**PIPELINE FACTORY MODEL**

To generate $18M new ARR at a 22% close rate (SQL-to-closed-won), Nexus needs $81.8M in total pipeline. At 55% marketing-sourced and 3.5x coverage:

- **Total pipeline required:** $63.6M (81.8M ÷ close rate of 22% × 3.5x... wait, let me recalculate)
  - Required closed-won: $18M
  - At 22% close rate → Required SQL pipeline: $81.8M
  - Marketing-sourced 55% → Marketing pipeline needed: $45M
  - At 3.5x coverage: $45M already IS the coverage target (pipeline needed to generate $13M closed-won from marketing)

- **Monthly marketing-sourced pipeline target:** $45M ÷ 12 = $3.75M/month in pipeline created
- **Monthly opportunity target:** $3.75M ÷ $47K ACV = 80 marketing-sourced opportunities per month

**QUARTERLY DISTRIBUTION (with 82-day lag):**

Pipeline created in March → closes in June. Pipeline created in September → closes in December.

| Month | Revenue Target | Pipeline Create Date | Pipeline $ Needed | Opps Needed (Mktg) | Budget |
|-------|---------------|---------------------|------------------|--------------------|--------|
| Jan | $890K | Oct (created then) | $3.75M | 80 | $245K |
| Feb | $930K | Nov | $3.75M | 80 | $240K |
| Mar | $1.05M | Dec | $3.9M | 83 | $265K |
| Apr | $1.30M | Jan | $4.1M | 87 | $290K |
| May | $1.55M | Feb | $4.3M | 91 | $305K |
| Jun | $1.80M | Mar | $4.6M | 98 | $335K |
| Jul | $1.20M | Apr | $3.5M | 74 | $245K |
| Aug | $1.05M | May | $3.3M | 70 | $220K |
| Sep | $1.30M | Jun | $3.8M | 81 | $285K |
| Oct | $1.55M | Jul | $4.0M | 85 | $295K |
| Nov | $2.10M | Aug | $4.5M | 96 | $335K |
| Dec | $2.30M | Sep | $5.1M | 109 | $340K |

**CHANNEL ALLOCATION FOR NEXUS:**

Given CPO benchmarks, optimal allocation drives maximum opportunities within budget:

| Channel | Q1 | Q2 | Q3 | Q4 | Full Year | % |
|---------|-----|-----|-----|-----|-----------|---|
| SEO/Content (always-on) | $95K | $95K | $95K | $95K | $380K | 11.2% |
| SDR Tools & Headcount Support | $120K | $120K | $120K | $120K | $480K | 14.1% |
| Google Paid Search | $110K | $130K | $105K | $145K | $490K | 14.4% |
| LinkedIn Ads | $95K | $110K | $130K | $90K | $425K | 12.5% |
| Webinars (2 in H1, 2 in H2) | $40K | $45K | $40K | $45K | $170K | 5.0% |
| Events/Trade Shows | $180K | $165K | $195K | $85K | $625K | 18.4% |
| ABM Programs | $75K | $85K | $95K | $100K | $355K | 10.4% |
| Partner Co-Marketing | $35K | $45K | $40K | $50K | $170K | 5.0% |
| Content Syndication | $55K | $50K | $30K | $45K | $180K | 5.3% |
| Experimental Reserve | $0 | $0 | $62.5K | $62.5K | $125K | 3.7% |
| **TOTAL** | **$805K** | **$845K** | **$912.5K** | **$837.5K** | **$3.4M** | **100%** |

**QUARTERLY CAMPAIGN MASTER PLAN FOR NEXUS:**

**Q1 — State of RevOps 2026 (January–March)**
- Theme: "Revenue operations has graduated from a function to a competitive moat — here's the benchmark data proving it"
- Anchor: Publish original "State of Revenue Operations 2026" report (survey 500+ RevOps practitioners in November/December; release January 15). This single asset drives inbound for the entire year.
- Supporting campaigns: LinkedIn Thought Leader Ads amplifying report findings; SDR outbound referencing report data in cold email; G2 review push targeting companies currently evaluating competitors
- Events: Sponsor RevOps Co-op Conference (February); host 3 executive roundtables in New York, Chicago, San Francisco in January (targeting Series B–C companies in Nexus' top 3 verticals)
- Key metric: By March 31, achieve 240 marketing-sourced opportunities (covering expected 3.5x pipeline for Q2 revenue)

**Q2 — The RevOps ROI Campaign (April–June)**
- Theme: "RevOps leaders who invested in their stack in 2024 outperformed their peers by 34% — here's the proof"
- Anchor: Customer ROI spotlight series — produce 6 customer ROI case studies from Q1 wins, each with quantified business impact; distribute via webinar + LinkedIn + SDR prospecting email
- Supporting campaigns: Competitor displacement campaign targeting companies using legacy CRM-only forecasting; webinar "RevOps Benchmark: Is Your Stack Holding You Back?" (target 300+ registrants)
- Events: SaaStr Europa (May) — sponsor bronze tier; co-present with a customer
- Key metric: By June 30, achieve 276 marketing-sourced opportunities for H2 target

**Q3 — Vision & Thought Leadership (July–September)**
- Theme: "The autonomous revenue operating system — what RevOps looks like when AI does the work"
- Anchor: Virtual summit "RevOps Forward 2026" — 1-day virtual conference, 8 speakers, 1,200 registrant target; 3-month pipeline generation engine
- Supporting campaigns: Executive ABM targeting top 50 enterprise accounts; LinkedIn native video series featuring CEO + customers; SaaStr Annual sponsorship (September) — booth + hosted dinner
- Events: Dreamforce (October — begin pre-conference ABM targeting in September)
- Key metric: Summit generates ≥85 marketing-sourced opportunities; Q3 ends with November/December pipeline at 3.5x coverage

**Q4 — Year-End Conversion (October–December)**
- Theme: "Your 2027 RevOps budget is being written now — here's how to justify the Nexus investment"
- Anchor: Business case automation tool — free "RevOps ROI Calculator" available on website; generates qualified leads who have already self-justified the investment; deploy with paid search
- Supporting campaigns: "Use your 2026 budget before it disappears" urgency campaign via email to warm pipeline; direct mail to all stalled opportunities (sending branded ROI analysis printed report); retargeting entire year's website visitor universe with urgency messaging
- Events: No new events — internal QBR support for sales
- Key metric: December achieves ≥109 marketing-sourced opportunities; Q1 next year pipeline hits 2.5x by December 31

**FIRST 90-DAY EXECUTION PLAN (January–March):**

Week 1-2 (January 1–10):
- Launch State of RevOps report — publish gated PDF, set up HubSpot landing page with lead form, configure lead routing to SDR queue
- Activate all SDR sequences referencing report data
- Launch LinkedIn Thought Leader Ads from CEO + 3 senior leaders, promoting report findings (budget: $8K/week)
- Enable retargeting campaign for all website visitors from Q4

Week 3-4 (January 11–24):
- Distribute report via content syndication partners (TechTarget, IDG) — purchase 400 validated download leads at $45 CPL
- Launch Google Search campaigns for high-intent keywords ("revenue forecasting software," "RevOps platform," "sales forecasting tool")
- Host first executive roundtable in New York (January 22) — 15 target accounts, ABM targeting to drive registrations in weeks 1–3

Week 5-8 (January 25 – February 21):
- Analyze Week 1–4 channel performance; if any channel CPO is below target, increase budget allocation
- Launch Chicago and San Francisco roundtables (February 5 and 12)
- Begin ABM warm outreach sequence to all accounts who downloaded the report but haven't engaged with SDR
- Launch first webinar: "State of RevOps: What the 2026 Data Means for Your Team" — target 350 registrants

Week 9-12 (February 22 – March 21):
- Publish derivative content from report: 5 LinkedIn posts per week pulling specific data points; blog posts on top 3 findings
- Sponsor RevOps Co-op Conference — staff with 3 demand gen leads + 2 AEs + 1 SE for demonstrations
- Q1 pipeline review (March 7): if behind target, activate emergency rebalancing protocol (increase SDR outbound reach-outs per rep per day from 50 to 80 for 4 weeks; add $30K emergency to paid search)
- Lock Q2 campaign plans; confirm Q2 event commitments; begin SaaStr Europa pre-conference ABM targeting

**REBALANCING DECISION TREE:**

At each monthly pipeline review:

IF marketing-sourced opps for the month ≥ 100% of target:
  → Continue current allocation | Flag best-performing channel for potential Q-next increase

IF marketing-sourced opps for the month = 80–99% of target:
  → Review channel CPOs | Shift 15% of budget from highest-CPO channel to lowest-CPO channel
  → Increase SDR outbound touch frequency by 20% | Extend best-performing campaign by 2 weeks

IF marketing-sourced opps for the month = 60–79% of target:
  → Activate rebalancing reserve ($62.5K in H2) | Pour into 2 best-performing channels
  → Launch competitor displacement campaign to all accounts using top 2 competitors
  → Increase paid search budget by 30% focused on bottom-of-funnel keywords only

IF marketing-sourced opps for the month < 60% of target for 2 consecutive months:
  → Escalate to CMO | Full demand gen audit | Consider emergency program: 
     (1) ABM blitz to all Tier 1 accounts, (2) Paid media emergency spend, 
     (3) SDR focus shift to re-engagement of full dormant database

## Success Metrics

Evaluate this prompt's output quality by checking:
- **Pipeline coverage validation**: The 12-month pipeline model should show 3.5x coverage of revenue targets with ≥2 months of buffer for sales cycle lag
- **Budget efficiency**: Year-end CPO across all channels blended should be ≤ target CPO from your baseline — if it's significantly higher, the channel mix is wrong
- **Quarterly pacing**: By the end of each quarter, you should be within 15% of the pipeline target set in this plan — if you're consistently off by more, the seasonal weighting assumptions need recalibration
- **Channel contribution accuracy**: After 6 months, validate that actual channel contribution % matches the plan allocation — channels performing above allocation deserve investment shift
- **Lead-to-close lag validation**: Compare the actual revenue closed each month against the pipeline created 82 days earlier — if the correlation is weak, your sales cycle assumption was off and the entire lag matrix needs recalibration

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Marketing-Mix-Modeling-&-Cross-Channel-Budget-Optimization-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Marketing-Mix-Modeling-&-Cross-Channel-Budget-Optimization-Revenue-Intelligence-Engine.md) — Use this for econometric modeling of your channel mix once you have 12+ months of performance data
- [`../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md) — For building the funnel conversion architecture that underpins this calendar's opportunity targets
- [`../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-SaaS-Marketing-Program-Cost-Efficiency-&-Cost-Per-Outcome-Revenue-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-SaaS-Marketing-Program-Cost-Efficiency-&-Cost-Per-Outcome-Revenue-Intelligence-Engine.md) — For tracking in-year program efficiency against this plan's CPO targets
- [`../../05_Analytics-&-Performance/Predictive-Analytics/AI-Powered-B2B-SaaS-Predictive-Pipeline-Health-&-Revenue-Gap-Forecasting-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Predictive-Analytics/AI-Powered-B2B-SaaS-Predictive-Pipeline-Health-&-Revenue-Gap-Forecasting-Intelligence-Engine.md) — Use this monthly to forecast whether the pipeline this calendar is generating will translate to revenue on schedule

## Integration Tips

**HubSpot / Marketo:**
- Build a "Demand Gen Calendar" custom property on the Campaign object with a dropdown for month and quarter. Tag every campaign with the corresponding quarter theme (e.g., "Q1-State-of-Market," "Q2-ROI-Proof"). Create a Marketing Dashboard filtered by quarter tag so you can compare actual pipeline contribution vs. this plan's quarterly targets in real time. Set up automated alerts: when any quarter's pipeline tracking falls below 90% of plan at mid-quarter, trigger a Slack notification to the demand gen lead.

**Salesforce:**
- Create a custom "Pipeline Created Month" date field on Opportunity. Build a report: "Marketing-Sourced Opportunities by Pipeline Created Month" and plot against this plan's monthly targets. This is your primary health-check dashboard — review weekly. Build a second report: "Revenue Closed by Month vs. Pipeline Created (82 days prior)" to continuously validate your sales cycle lag assumption.

**Google Sheets:**
- Build the Pipeline Factory Model from this prompt as a living spreadsheet with three tabs: (1) Monthly targets, (2) Actual performance updated weekly, (3) Variance and rebalancing flags. Color code: green if within 10% of plan, yellow if 10–25% behind, red if >25% behind. Share with CMO, CRO, and CFO as the single source of truth for marketing pipeline performance.

**Asana / Monday.com / ClickUp:**
- Import the monthly campaign deployment schedule directly as project tasks. Create a Campaign Launch Template with the following fields: Campaign name, quarter theme, channel mix, launch date, asset dependencies, budget, pipeline target, and success metric. Assign each campaign to a DRI (directly responsible individual). Set automated status reminders 2 weeks before each launch date to confirm assets are ready.

**6sense / Bombora:**
- At the start of each quarter, pull the intent surge report for your top 10 intent topics. Overlay with this calendar's quarterly focus — in Q4 (conversion quarter), prioritize any accounts showing surge on "pricing" or "vendor evaluation" topics and feed them directly into the SDR urgent outbound sequence. In Q1 (pipeline rebuild quarter), prioritize accounts showing surge on problem/pain-point topics and enroll them in the thought leadership nurture program.

**Looker / Tableau / Power BI:**
- Build a "Demand Gen Calendar Tracker" dashboard with four panels: (1) Monthly pipeline target vs. actuals by channel, (2) Year-to-date marketing-sourced pipeline vs. annual plan, (3) CPO by channel vs. target CPO, (4) 90-day pipeline forecast based on current campaign performance. Review this dashboard in every Monday morning demand gen standup.

## Troubleshooting

**Problem: My sales cycle is highly variable (30 days for SMB, 180+ days for enterprise) — how do I build a single calendar that works for both?**
Build two parallel pipeline models within the same calendar: one for SMB/mid-market (30–60 day cycles) and one for enterprise (90–180 day cycles). Your channel mix will naturally separate: paid search, PLG-sourced trials, and outbound SDR typically feed the shorter-cycle segment; ABM, events, and executive roundtables feed the enterprise pipeline with longer lag. Maintain separate monthly pipeline targets and CPO benchmarks for each segment. When reviewing pipeline health at month-end, check both models independently — the SMB funnel should be self-funding and fast-moving, while the enterprise funnel requires earlier investment and more patience before the pipeline shows up.

**Problem: I don't have 12 months of historical channel performance data — I'm building this for the first time or after a major team change.**
Use the following industry benchmarks as your starting model for B2B SaaS with $40K–$80K ACV: SEO/inbound CPO: $350–$600; SDR outbound CPO: $900–$1,500; Google Search CPO: $550–$950; LinkedIn Ads CPO: $800–$1,400; Webinars: $2,000–$4,500/event; Events: $3,500–$7,000. Run this plan for Q1 with benchmark CPOs, track actual results weekly, and recalibrate the full-year model in April using your real data. Accept that your first year will be imprecise — what matters is having a documented model to iterate on, not a perfect model that never gets tested.

**Problem: My budget is too small to run all four campaign motions the model recommends — I only have $800K total.**
At $800K, prioritize ruthlessly using CPO as your ranking criterion. At an average ACV of $47K and 55% marketing-sourced target, you need approximately 70 marketing-sourced opportunities per month. Map your available channels by CPO: if SEO (CPO $320) and SDR tools (CPO $1,100 blended for tooling + headcount support) are your two lowest-CPO channels, fund them at 100% of capacity first. Apply remaining budget to the next-best CPO channel (typically paid search or webinars). Skip events and LinkedIn Ads until budget increases — their CPO is too high for a constrained budget. With $800K, your realistic pipeline contribution is approximately 55–65 opportunities/month rather than 80 — negotiate down your marketing-sourced pipeline target accordingly or accept that the gap will need to be filled by sales-sourced pipeline.

## Version History
- v1.0: Initial creation (auto-generated)
