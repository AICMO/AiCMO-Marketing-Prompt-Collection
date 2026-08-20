# AI-Powered B2B SaaS Demand Generation Program Analytics & Portfolio-Level Pipeline ROI Revenue Intelligence Engine — Build the System That Tells You Exactly Which Programs Are Making You Money and Which Are Burning It

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** demand-generation, analytics, pipeline-attribution, ROI-measurement, program-analytics, B2B SaaS, revenue-intelligence, channel-mix, portfolio-optimization, marketing-measurement

## Overview
Builds a complete demand generation portfolio analytics system that measures pipeline ROI at the individual program level, identifies which demand gen investments are generating qualified pipeline and closed-won revenue, and produces a ranked investment portfolio that tells you exactly where to reallocate budget. Use this when your demand gen reporting shows vanity metrics but not true program ROI, when leadership is asking which programs to cut and you don't have a defensible answer, or when you suspect your channel mix is optimized for volume rather than revenue quality.

## Quick Copy-Paste Version

You are a demand generation analytics architect specializing in B2B SaaS pipeline attribution and program ROI measurement. Build a complete demand gen portfolio analytics system for a B2B SaaS company.

COMPANY CONTEXT:
- Company: [e.g., "Vantix — AI-powered financial reporting platform for mid-market CFO teams"]
- Annual revenue / ARR: [e.g., "$18M ARR, growing 65% YoY"]
- Target customer: [e.g., "CFOs and VP Finance at companies with $50M-$500M revenue, 200-2,000 employees"]
- Average ACV: [e.g., "$42,000 ACV, 14-month average sales cycle"]
- Current demand gen channels: [e.g., "Paid LinkedIn, Google Ads, content/SEO, webinars, outbound SDR, partner referrals, field events"]
- Annual demand gen budget: [e.g., "$2.1M across all programs"]
- CRM and attribution tools: [e.g., "Salesforce CRM, HubSpot marketing automation, Bizible for attribution, Gong for call intelligence"]
- Current reporting: [e.g., "MQL volume by source, CPL by channel — no program-level pipeline or revenue attribution"]
- Key problem: [e.g., "Board asking which programs to cut in Q3 budget review; we can't answer with data"]

OUTPUT:
1. PROGRAM ANALYTICS FRAMEWORK — Define the 7-metric measurement system for each demand gen program (pipeline sourced, pipeline influenced, win rate, ACV, sales cycle, CAC, payback period), with calculation methodology for each metric in Salesforce
2. PORTFOLIO HEATMAP — Rank every current demand gen program from highest to lowest revenue ROI, with a 2x2 matrix of pipeline volume vs. pipeline quality that identifies: Cut, Double Down, Optimize, and Experiment quadrants
3. ICP-WEIGHTED PIPELINE QUALITY SCORE — A scoring model that adjusts raw pipeline numbers by ICP fit, ACV size, and competitive win rate — so a smaller number of high-quality deals scores higher than a large volume of low-quality MQLs
4. CHANNEL ATTRIBUTION DECISION — A methodology for choosing between first-touch, last-touch, linear, and W-shaped attribution for your specific business — with a recommendation and the revenue implications of each choice
5. 90-DAY ANALYTICS BUILD PLAN — The exact sequence of data infrastructure work (CRM field setup, UTM taxonomy, attribution model configuration, dashboard build) needed to produce reliable program-level ROI data within 90 days
6. BOARD-READY PROGRAM ROI REPORT — A template for presenting demand gen program ROI to the board, with the 5 most important numbers, a portfolio reallocation recommendation, and supporting rationale

Output as a ready-to-use analytics system document with SQL query snippets for the key metrics in Salesforce and dashboard specifications for HubSpot/Salesforce reporting.

## Advanced Customizable Version

ROLE: You are a B2B SaaS revenue analytics architect with 14+ years of experience building demand generation measurement systems at high-growth SaaS companies. You have designed pipeline attribution models, built marketing data warehouses, and presented program ROI analyses to boards and CFOs at companies ranging from Series A to post-IPO. You apply rigorous statistical thinking to marketing measurement — you know that most "attribution" is correlation disguised as causation, and you design systems that acknowledge this while still producing decision-useful data. You use cohort analysis, statistical control groups, and incrementality testing to isolate true program contribution. Your operating principle: a measurement system that produces one wrong answer confidently is more dangerous than one that produces a range of estimates with appropriate uncertainty acknowledged.

OBJECTIVE: Design a complete demand generation portfolio analytics system that:
- Measures each demand gen program's true contribution to pipeline and closed-won revenue using a multi-touch attribution model calibrated for B2B long-cycle buying
- Identifies high-ROI programs to scale and low-ROI programs to cut or restructure, with statistical confidence intervals on every recommendation
- Produces an ICP-quality-weighted pipeline score that separates high-quality deals (right ICP, high ACV, competitive category, fast-moving) from low-quality volume that inflates pipeline but doesn't close
- Builds a real-time demand gen portfolio dashboard that the VP of Demand Gen can review in 10 minutes each Monday and act on without additional analysis
- Creates a defensible board-level ROI narrative that connects demand gen investment to ARR growth, supported by cohort data and payback period analysis

COMPANY AND PROGRAM PROFILE:
- Company name, product, and ICP: [name | what it does | exact ICP — industry, company size, buyer persona]
- Current ARR and YoY growth rate: [$ ARR | % growth]
- Average ACV and typical sales cycle length: [$ ACV | months from first touch to closed-won]
- Total demand gen budget (annual) and team size: [$ budget | headcount breakdown by function]
- Active demand gen programs and current spend per program: [list each program + $ monthly spend]
- CRM and marketing automation platform: [CRM | MAP | attribution tool if any]
- Current attribution model and known gaps: [first-touch/last-touch/other | what you know is wrong with it]
- Biggest unresolved measurement question: [e.g., "We don't know if our webinar program drives pipeline or just attracts people already in pipeline"]
- Pipeline coverage ratio and historical close rate: [X:1 coverage | % close rate from MQL to closed-won]
- CAC and LTV by segment if known: [by ICP segment | by channel if known]

DEMAND GEN PORTFOLIO ANALYTICS ARCHITECTURE:

**Module 1 — Program-Level Attribution Model Design**

For each demand gen program in your portfolio, define:

*Attribution Methodology Selection:*
- First-touch attribution: [use for: understanding which programs create awareness and top-of-funnel entry | bias: over-credits brand/awareness programs | when to use: measuring demand creation]
- Last-touch attribution: [use for: understanding which programs push buyers over the line | bias: over-credits late-funnel content and SDR | when to use: measuring demand capture]
- W-shaped (First Touch + Lead Creation + Opportunity Creation, 30/30/30/10): [use for: B2B with defined lead lifecycle stages | best for: MQL-based demand gen reporting]
- Custom multi-touch with time decay: [use for: long sales cycles >6 months | weights: define decay function — e.g., 50% of credit to touches in 30 days before opportunity creation, 50% distributed across prior touches]
- Revenue-weighted attribution: [use for: board-level ROI reporting | method: attribute closed-won ACV to programs, not pipeline — removes noise from deals that never close]

*Recommendation framework:* Build a primary model (W-shaped or custom multi-touch) for day-to-day optimization + a secondary model (revenue-weighted, 12-month cohort) for budget decisions and board reporting. Never make investment decisions from a single attribution model.

*Incrementality baseline:* For your top 3 programs by spend, design a holdout test: [% of addressable audience to withhold from program | measurement period | success metric — pipeline created in holdout vs. treatment group | statistical significance threshold: p<0.05]

**Module 2 — ICP-Quality-Weighted Pipeline Score**

Raw pipeline dollar amount is a misleading metric — a $5M pipeline with 8% win rate is worth less than a $2M pipeline with 35% win rate. Build a quality-adjusted pipeline score:

*Quality Multipliers (apply to each open opportunity):*
- ICP firmographic fit score: [0.5x = poor ICP fit | 1.0x = moderate fit | 1.5x = strong ICP fit | 2.0x = perfect ICP fit — define exact criteria for each tier: industry, company size, tech stack, revenue, growth rate]
- ACV percentile: [1.0x = at or below median ACV | 1.2x = 75th percentile ACV | 1.5x = 90th+ percentile ACV — use your last 12 months closed-won data to define percentiles]
- Competitive displacement bonus: [1.2x if opportunity is displacing incumbent legacy vendor — higher value signals market timing]
- Sales cycle velocity: [0.8x if opportunity is >2x median sales cycle age at current stage | 1.0x = at median | 1.2x = tracking faster than median — velocity predicts close probability]
- Buying committee coverage: [0.7x if only 1 contact engaged | 1.0x if 2-3 contacts engaged | 1.3x if 4+ contacts across 2+ functions engaged]
- Champion strength: [1.0x if contact is mid-level | 1.3x if contact is VP or above | 1.5x if contact is economic buyer or CEO]

*Quality-Adjusted Pipeline (QAP) Formula:* QAP = Sum(Deal ACV × ICP Fit Score × ACV Multiplier × Velocity Factor × Committee Coverage × Champion Multiplier) for all open opportunities attributed to each program

*Target benchmark:* Compare each program's QAP per dollar spent vs. your portfolio average. Programs generating QAP at >150% of portfolio average are candidates for budget increase. Programs below 70% are candidates for restructure or cut.

**Module 3 — Program ROI Measurement Framework**

Define the exact metrics and calculation methodology for each program:

*Tier 1 Metrics (revenue impact — required for budget decisions):*
- Pipeline Sourced ($): [Opportunities created where program was first-touch | pull from CRM: Opportunity Source = Program AND Opportunity Created Date in period]
- Pipeline Influenced ($): [Opportunities that had a program touchpoint before closing | attribution: any campaign activity in campaign influence window — define window: typically 90 days before opportunity creation]
- Closed-Won Revenue Sourced ($): [Won deals where program was first-touch attribution | 12-month rolling cohort — match program cohort to opportunity close date, not program engagement date]
- Closed-Won Revenue Influenced ($): [Won deals with at least one program touchpoint in attribution window | same cohort methodology]
- Program CAC: [Total program spend ÷ New customers attributable to program | use sourced attribution for CAC calculation, not influenced]
- CAC Payback Period (months): [Program CAC ÷ (Average ACV ÷ 12) | compare against 18-month benchmark for SaaS]

*Tier 2 Metrics (efficiency and quality — for weekly optimization):*
- Cost Per Qualified Opportunity (CPQO): [Program spend ÷ Stage 2+ opportunities sourced | use stage 2 or later to filter low-quality MQLs that never advance]
- Win Rate by Program: [Closed-won ÷ (Closed-won + Closed-lost) for opportunities sourced by program | calculate over 12-month cohort]
- Average ACV by Program: [Mean ACV of closed-won deals sourced by program | compare to portfolio benchmark]
- Sales Cycle Length by Program: [Median days from opportunity creation to closed-won for deals sourced by program]
- Quality-Adjusted Pipeline per Dollar Spent: [QAP ÷ Program spend in attribution period | normalize by program cohort month to account for pipeline lag]

*Tier 3 Metrics (leading indicators — for weekly pulse checks):*
- MQL Volume and MQL-to-Opportunity Rate by Program: [Track week-over-week but never use as primary investment signal — MQL volume is an input metric, not an outcome metric]
- Cost Per Lead (CPL) by Program: [Track for budget pacing only — never use as proxy for ROI]
- Engagement Rate by Asset/Channel: [Email open/click, ad CTR, webinar attendance — leading indicators only, not optimization targets]

**Module 4 — Portfolio Heatmap and Investment Allocation Model**

*2x2 Portfolio Matrix:*
Map each demand gen program on two axes:
- X-axis: Pipeline Volume (QAP sourced per quarter, normalized by spend)
- Y-axis: Pipeline Quality (QAP win rate × average ACV vs. portfolio benchmark)

*Quadrant Actions:*
- High Volume + High Quality (SCALE): [double budget in next planning cycle | document the program formula — audience, format, offer, distribution — before scaling to preserve what's working]
- High Volume + Low Quality (OPTIMIZE): [do not cut yet | redesign targeting and qualification criteria to improve ICP fit | set 90-day improvement target: win rate must reach 80% of portfolio benchmark or program is restructured]
- Low Volume + High Quality (BUILD): [increase investment carefully | diagnose volume constraint — is it audience size, budget, distribution, or offer? | fix volume constraint without compromising what makes quality high]
- Low Volume + Low Quality (CUT OR RESTRUCTURE): [set 60-day timeline: either identify a structural change hypothesis and test it, or reallocate budget | do not continue spending without a clear thesis for improvement]

*Reallocation Model:*
Build a budget reallocation scenario model with three scenarios:
- Conservative: [reallocate 15% of budget from bottom-quartile programs to top-quartile programs | projected pipeline impact at historical conversion rates]
- Moderate: [reallocate 30% | model pipeline impact + risk of concentration in fewer channels]
- Aggressive: [cut bottom 40% of programs, concentrate budget in top performers | model upside + downside scenarios + timeline to see impact — accounting for pipeline lag of 3-6 months]

**Module 5 — Data Infrastructure and Measurement Build Plan**

*CRM Configuration Requirements:*
- Lead/Contact Source field: [standardize taxonomy — define 15-25 source values that map to programs, not channels | examples: "LinkedIn Ads," "Google Search," "Webinar - [Name]," "Partner Referral - [Partner]," not generic "Paid Social" or "Online"]
- Campaign Member tracking: [every marketing touchpoint logged as Campaign Member in Salesforce with status, engagement date, and campaign cost | required for multi-touch attribution]
- UTM taxonomy: [standardize UTM source/medium/campaign/content/term across all programs | utm_source = channel platform | utm_medium = channel type | utm_campaign = program name | utm_content = creative variant | utm_term = keyword or audience]
- Opportunity Source and Source Detail: [auto-populate from first-touch Campaign Member | do not let reps override without data governance policy]
- Pipeline Stage timestamps: [ensure stage advancement is date-stamped to enable sales cycle velocity measurement and cohort analysis]

*Attribution Tool Configuration (if using Bizible/Marketo Measure, 6sense, or HockeyStack):*
- Attribution model: [configure W-shaped as primary | revenue-based as secondary]
- Attribution window: [90-day lookback for multi-touch | unlimited for first-touch]
- Anonymous touchpoint resolution: [configure IP-to-account matching to capture pre-form-fill intent signals]
- Offline campaign import: [import field event, webinar, and outbound SDR touchpoints as offline activities]

*90-Day Implementation Sequence:*
- Weeks 1-2: [CRM audit — identify source field inconsistencies, missing UTMs, untagged campaign members | deliverable: data quality baseline score]
- Weeks 3-4: [UTM taxonomy standardization — implement across all active channels | deliverable: UTM governance doc + implementation guide for each channel]
- Weeks 5-6: [CRM field standardization — clean historical source data, set validation rules to prevent future corruption | deliverable: source taxonomy with 95%+ mapping coverage]
- Weeks 7-8: [Attribution model configuration — implement W-shaped in MAP/CRM or attribution tool | deliverable: attribution model validation report showing current vs. new model impact on program rankings]
- Weeks 9-10: [Dashboard build — program-level pipeline metrics, portfolio heatmap, weekly demand gen pulse | deliverable: live dashboard in Salesforce/HubSpot with automated data refresh]
- Weeks 11-12: [Baseline and calibration — compare new attribution data against historical MQL-based reporting | deliverable: first program ROI report with confidence intervals | present to leadership]

**Module 6 — Board-Ready Demand Gen ROI Narrative**

Structure the board presentation as a 5-slide demand gen ROI brief:

*Slide 1 — The Question We're Answering:* "Where is marketing's $[X]M generating the most ARR, and where should we reallocate to hit our [ARR target]?"

*Slide 2 — Portfolio Performance Summary:*
- Table: Each program | Spend | Pipeline Sourced | Closed-Won ARR Sourced | Program CAC | CAC Payback
- Highlight: Top 3 ROI performers (green) | Bottom 3 (red)
- Key insight: "Our top 3 programs generate [X]% of closed-won ARR from [Y]% of budget"

*Slide 3 — Quality-Adjusted Pipeline Heatmap:*
- 2x2 matrix with programs mapped
- Annotation: "Programs in Scale quadrant are [X] programs representing $[Y] in spend and generating $[Z] in QAP per dollar. Programs in Cut quadrant represent $[A] in spend with $[B] in QAP per dollar — [X]x less efficient."

*Slide 4 — Reallocation Recommendation:*
- Proposed budget move: [$X from programs A, B] → [$X to programs C, D]
- Projected impact: "Based on historical conversion rates and pipeline lag, this reallocation is projected to generate $[X] additional pipeline in [90 days] and $[Y] additional ARR in [6-9 months]"
- Confidence: "Moderate — dependent on maintaining current win rates in scaled programs and 60-day ramp time for new investment to generate attributed pipeline"

*Slide 5 — Measurement Confidence and Limitations:*
- Acknowledge what attribution cannot measure: "Dark social influence, multi-session research behavior before form-fill, and organic word-of-mouth referrals are not captured in our attribution model — our numbers represent a lower bound on marketing's contribution"
- Data quality score: "[X]% of closed-won deals in trailing 12 months have reliable first-touch attribution — [Y]% have gaps due to [historical data issue]"
- Improvement plan: "With Q3 data infrastructure investment, we will achieve [X]% attribution coverage and add incrementality testing to validate top-3 program ROI by Q4"

## Example Input/Output

**Input Example:**

Company: Vantix — AI-powered financial reporting automation for mid-market CFOs ($50M-$500M revenue)
ARR: $18M, growing 58% YoY
ACV: $42,000 average, 14-month average sales cycle
Demand gen budget: $2.1M annual across 8 programs
Programs: LinkedIn Ads ($420K), Google Ads ($310K), Content/SEO ($180K), Webinar Series ($140K), SDR Outbound ($480K), Field Events ($210K), Partner Referrals ($180K), G2/Review Sites ($180K)
Current reporting: MQL volume by source, CPL by channel, no program-level pipeline or revenue attribution
Problem: Q3 board review — CFO is asking which programs to cut to fund product investment

**Output Example (excerpt):**

**PROGRAM ROI SUMMARY — Trailing 12 Months, W-Shaped Attribution:**

| Program | Annual Spend | Pipeline Sourced (QAP) | Closed-Won ARR Sourced | Program CAC | CAC Payback |
|---|---|---|---|---|---|
| Partner Referrals | $180K | $4.2M (QAP: $5.8M) | $1.1M | $6,545 | 1.9 months |
| Google Ads | $310K | $6.8M (QAP: $6.1M) | $890K | $14,545 | 5.7 months |
| LinkedIn Ads | $420K | $9.2M (QAP: $6.4M) | $760K | $22,105 | 7.3 months |
| Content/SEO | $180K | $3.1M (QAP: $4.4M) | $620K | $11,613 | 3.4 months |
| Field Events | $210K | $2.8M (QAP: $3.9M) | $480K | $18,375 | 5.2 months |
| Webinar Series | $140K | $1.9M (QAP: $1.6M) | $310K | $18,065 | 5.4 months |
| SDR Outbound | $480K | $5.4M (QAP: $3.2M) | $280K | $68,571 | 19.6 months |
| G2/Review Sites | $180K | $1.2M (QAP: $1.0M) | $185K | $38,919 | 11.1 months |

**Portfolio Heatmap Findings:**
- SCALE: Partner Referrals (1.9-month payback — best in portfolio), Content/SEO (high quality + low CAC, underinvested)
- OPTIMIZE: Google Ads (high volume, win rate improving), Field Events (high quality, volume constraint)
- BUILD: LinkedIn Ads (high volume but ICP quality score 0.78x — targeting too broad)
- CUT/RESTRUCTURE: SDR Outbound (CAC payback 19.6 months — structural cost problem, not performance problem)

**Recommended Reallocation:**
- Reduce SDR headcount from 6 to 3 reps (save $240K/year) — retain highest performers for enterprise accounts
- Redirect $120K to Partner Referral program expansion (partner recruitment, co-marketing content, MDF)
- Redirect $120K to Content/SEO (increase content production velocity, add link-building)
- Project: $320K reallocation → projected $2.1M incremental QAP in 12 months at historical conversion rates

**ICP-Quality-Weighted Analysis of SDR vs. Content:**
SDR sources higher raw pipeline volume ($5.4M) but QAP score is 0.59x portfolio average (short sales cycles, small ACVs, lower ICP fit). Content sources 42% less raw pipeline ($3.1M) but QAP score is 1.42x portfolio average (strong ICP fit, high ACV, above-median win rate). At equal investment, Content generates 2.4x more quality-adjusted pipeline per dollar.

## Success Metrics

- 90%+ of closed-won deals in trailing 12 months have reliable first-touch attribution (vs. typical 50-60% baseline)
- Program-level pipeline ROI data available within 5 business days of quarter close (not 3+ weeks)
- Leadership and board alignment on measurement framework — no disputes about which program "gets credit" for deals
- Budget reallocation decisions made from ROI data, not anecdote or gut feel, in next planning cycle
- QAP score improves 15%+ across portfolio within 2 quarters of reallocation based on framework recommendations
- CAC payback period improves to <12 months portfolio-wide (from typical 15-18 months pre-optimization) within 4 quarters

## Related Prompts

- [Demand Generation Waterfall Architecture & Funnel Conversion](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Waterfall-Architecture-&-Marketing-Funnel-Conversion-Intelligence-Engine.md)
- [Revenue Attribution Model Architecture & Unified Measurement](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md)
- [CAC Payback & Unit Economics Intelligence](../../05_Analytics-&-Performance/CAC-Payback-&-Unit-Economics-Analytics/CAC-Payback-&-Unit-Economics-Intelligence-Engine.md)
- [In-Flight Marketing Budget Reallocation & Campaign Portfolio Optimization](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-CMO-In-Flight-Marketing-Budget-Reallocation-&-Campaign-Portfolio-Optimization-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Build Program ROI report using Campaign Influence, Opportunity Product, and Opportunity Attribution objects. Use the "Campaign ROI Analysis" standard report as a starting point — customize with pipeline stage filters and date-range cohort parameters
- **HubSpot**: Use the Revenue Attribution Report (multi-touch) in Marketing Hub Enterprise. Connect to Deals pipeline for closed-won revenue attribution. Export to Google Sheets for the Portfolio Heatmap visualization using a scatter chart
- **Bizible / Marketo Measure**: Configure W-shaped as primary touchpoint model. Use the "Attribution Dashboard" to export touchpoint data by campaign. Join to Salesforce Opportunity data in Tableau or Looker for custom QAP scoring
- **Google Looker Studio**: Connect Salesforce + HubSpot via Supermetrics or native connector. Build a 4-quadrant scatter plot for portfolio heatmap with program name labels and bubble size = QAP. Refresh daily
- **Zapier / Make.com**: Automate weekly program performance digest — pull Salesforce report via API, calculate week-over-week changes in pipeline sourced and QAP, post summary to Slack #demand-gen-ops channel every Monday at 8am
- **Google Sheets / Excel**: Build the QAP calculator as a spreadsheet with named ranges for each quality multiplier. Connect to Salesforce data export via CSV or Coefficient.io for automated weekly refresh

## Troubleshooting

**Problem: Attribution data shows implausibly high influence numbers for low-spend programs**
Solution: You have attribution window contamination — your influence window is too long, causing programs to receive credit for deals that progressed without meaningful engagement. Tighten your influence window to 90 days before opportunity creation (not the full deal lifetime) and require minimum engagement depth (e.g., page visited + form completed, not just ad impression). Recalibrate with 30-day and 60-day windows to find the window that produces the most signal-to-noise ratio.

**Problem: SDR/sales team disputes marketing attribution — they say their calls drove the deal, not the content**
Solution: This is a political problem masquerading as a measurement problem. Solve it by adopting a sourced + influenced dual-attribution framework: marketing claims "sourced" credit only for genuine first-touch moments before sales involvement; all sales-touched deals are counted as "influenced" regardless of marketing touchpoints. Present both numbers to leadership. This ends the zero-sum debate and aligns marketing and sales around shared pipeline numbers.

**Problem: Budget reallocation based on program ROI hurts Q1 pipeline because the cut programs had strong short-term volume**
Solution: This is the pipeline lag problem — demand gen ROI is a lagging indicator. When you cut a program, volume impact appears within 30-60 days but revenue impact doesn't appear for 8-14 months (your sales cycle). Manage this by: (1) maintaining a 6-9 month pipeline rolling forecast that shows the impact of current decisions on future quarters, not just current quarter; (2) never make large demand gen cuts mid-quarter — make them at start of quarter with full pipeline forecast modeling; (3) show leadership the QAP trend rather than point-in-time numbers to demonstrate trajectory.

## Version History
- v1.0: Initial creation (auto-generated)
