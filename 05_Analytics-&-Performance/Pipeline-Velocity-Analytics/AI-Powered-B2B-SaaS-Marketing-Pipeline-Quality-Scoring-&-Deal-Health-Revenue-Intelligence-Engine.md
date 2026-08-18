# AI-Powered B2B SaaS Marketing Pipeline Quality Scoring & Deal Health Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** pipeline quality, deal health, revenue analytics, forecasting, B2B SaaS, marketing accountability

## Overview
Scores and evaluates the health and quality of marketing-sourced and marketing-influenced pipeline deals using multi-dimensional signals — ICP fit, buying committee engagement, stage velocity, and risk indicators — enabling marketing and revenue operations teams to distinguish high-confidence revenue from inflated, stale, or low-quality pipeline before it impacts forecast accuracy.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue operations analyst. Score the quality of my current marketing pipeline using the following deal data and produce a prioritized health report.

PIPELINE DATA (paste your deal list with these fields):
- Deal name / Account
- Deal stage
- ACV / ARR value
- Created date
- Last activity date
- Number of stakeholders engaged
- ICP fit score (if available, otherwise score based on: industry, company size, budget, urgency)
- Marketing source / attribution
- Days in current stage
- Competitor mentioned (Y/N)
- Champion identified (Y/N)
- Executive sponsor engaged (Y/N)

For each deal, assign:

1. PIPELINE QUALITY SCORE (1-10):
   - ICP Fit (0-3): Perfect ICP = 3, Adjacent = 2, Poor fit = 0
   - Buying Committee Coverage (0-3): 3+ stakeholders + exec = 3, 2 stakeholders = 2, single-threaded = 1, unknown = 0
   - Engagement Velocity (0-2): Active in last 14 days = 2, 15-30 days = 1, >30 days = 0
   - Deal Hygiene (0-2): Champion + next step + close date = 2, partial = 1, missing = 0

2. DEAL HEALTH STATUS: Green (8-10) / Yellow (5-7) / Red (1-4)

3. RISK FLAGS: Flag any of these: single-threaded, stale >30 days, no champion, wrong ICP, stuck stage, competitor present without battlecard deployed

4. MARKETING INTERVENTION RECOMMENDED: For each Red/Yellow deal, prescribe the exact marketing action (ABM content, executive outreach, case study, competitive displacement campaign, re-engagement sequence, etc.)

OUTPUT FORMAT:
- Executive summary: pipeline quality distribution (% Green/Yellow/Red), total qualified vs. at-risk ARR
- Deal-by-deal quality scorecard table
- Top 3 highest-quality deals (marketing should double down)
- Top 3 highest-risk deals (immediate intervention required)
- Marketing program recommendations ranked by expected pipeline recovery value

My pipeline ARR target this quarter: [INSERT TARGET]
Current pipeline total: [INSERT TOTAL]

## Advanced Customizable Version

ROLE: You are an elite B2B SaaS Marketing Revenue Intelligence Analyst with deep expertise in pipeline quality modeling, deal health diagnostics, and marketing-influenced revenue optimization. You combine data science rigor with go-to-market expertise.

CONTEXT:
- Company: [Company name]
- Product: [Product/platform description]
- Target market: [ICP definition: industry, company size, title, geography]
- Average deal size: [ACV range]
- Average sales cycle: [X weeks/months]
- Pipeline coverage ratio target: [e.g., 3x]
- Forecast methodology: [e.g., stage-weighted, commit/best case/pipeline]
- CRM system: [Salesforce/HubSpot/other]
- Current quarter: [Q + Year]
- Days remaining in quarter: [X]

PIPELINE INPUT DATA:
[Paste or describe your pipeline — deal name, stage, ACV, created date, last activity, stakeholder count, source, days in stage, key fields]

PIPELINE QUALITY SCORING MODEL:

**Dimension 1: ICP Fit Score (0-25 points)**
- Industry vertical match: Perfect match = 10, adjacent = 5, poor = 0
- Company size (employees/revenue): Ideal range = 10, near range = 5, outside = 0
- Tech stack compatibility: Match = 5, neutral = 2, conflict = 0

**Dimension 2: Buying Committee Engagement (0-25 points)**
- Number of unique stakeholders engaged: 4+ = 15, 3 = 10, 2 = 5, 1 = 0
- Economic buyer / CFO engaged: Yes = 5, Pending = 2, No = 0
- Champion identified and active: Yes = 5, Tentative = 2, No = 0

**Dimension 3: Deal Momentum & Velocity (0-25 points)**
- Days in current stage vs. average: On pace = 15, 1.5x average = 8, >2x average = 0
- Last meaningful activity: <7 days = 10, 7-21 days = 5, 21-30 days = 2, >30 days = 0

**Dimension 4: Qualification & Deal Hygiene (0-25 points)**
- MEDDPICC/BANT completeness: 80%+ = 15, 50-79% = 8, <50% = 0
- Defined next step with date: Yes = 5, Vague = 2, No = 0
- Close date confidence: High = 5, Medium = 2, Low/missing = 0

**TOTAL QUALITY SCORE: 0-100**
- Tier A: 75-100 (High quality — protect and accelerate)
- Tier B: 50-74 (Medium quality — marketing nurture and influence)
- Tier C: 25-49 (At-risk — intervention or re-stage)
- Tier D: 0-24 (Low quality — pipeline hygiene or disqualify)

RISK SIGNAL DETECTION (flag if present):
□ Single-threaded (1 contact only)
□ Stale — no activity >21 days
□ Stage regression indicators
□ Wrong ICP retroactively
□ Competitor present, no counter-narrative deployed
□ No defined business case or ROI justification
□ No mutual close plan agreed
□ Executive sponsor disengaged or unknown
□ Budget unconfirmed
□ Technical champion blocked from evaluating

MARKETING INTERVENTION PLAYBOOK (prescribe for each at-risk deal):
- Single-threaded: Deploy multi-stakeholder ABM content (buying committee guide, persona-specific case studies)
- Stale deal: Re-engagement sequence with new proof point (competitor win story, ROI data, industry insight)
- No business case: Co-create CFO-ready ROI calculator and business value assessment
- Competitive threat: Battlecard activation, reference customer call, G2 review amplification
- Executive not engaged: Executive outreach via LinkedIn, executive briefing offer, peer executive reference
- Technical blocked: Proof-of-concept framework, security review package, developer champion content

ANALYSIS REQUIREMENTS:

1. PORTFOLIO QUALITY DASHBOARD
   - Distribution: Tier A/B/C/D counts and total ARR by tier
   - Quality-weighted forecast: Apply tier-based confidence multipliers
   - Comparison: Marketing-sourced vs. marketing-influenced quality distribution
   - Trend: If prior quarter data available, quality improvement/degradation

2. DEAL-BY-DEAL SCORECARD
   Present as table:
   | Deal | Stage | ACV | Quality Score | Tier | Top Risk Flag | Recommended Action | Priority |

3. HIGH-CONVICTION DEAL LIST (Tier A)
   For each: What marketing can do to accelerate close (reference call, executive event, competitive content)

4. INTERVENTION PRIORITY QUEUE (Tier C & D)
   Ranked by: ACV × recoverability likelihood
   For each: Specific marketing play, owner, timeline, expected outcome

5. PIPELINE QUALITY ROOT CAUSE ANALYSIS
   - Which marketing source / program produces highest-quality deals?
   - Which ICP segments produce consistently higher quality?
   - Which stage has the highest quality degradation?
   - What's the correlation between marketing content engagement and deal quality?

6. BOARD-READY NARRATIVE
   Draft 3-bullet CFO/CEO summary: Quality-adjusted pipeline vs. target, recovery actions underway, expected quality improvement by next review

OUTPUT FORMAT: Executive brief + scorecard table + intervention queue + root cause insights
TONE: Data-driven, direct, revenue-accountable — CMO presents this to CEO/CFO

## Example Input/Output

**Input Example:**

Company: Meridian Analytics (B2B SaaS, data pipeline platform)
Target ICP: Data engineering teams at mid-market and enterprise ($50M-$5B revenue, technology, financial services, healthcare)
Average ACV: $85,000 | Average sales cycle: 67 days | Pipeline target: $2.1M

Pipeline (simplified):

| Deal | Stage | ACV | Created | Last Activity | Stakeholders | Source | Days in Stage |
|------|-------|-----|---------|---------------|-------------|--------|---------------|
| CloudNative Corp | Demo | $120K | 45 days ago | 3 days ago | 4 (CTO, VP Eng, 2 Data Eng) | Paid LinkedIn | 12 days |
| RetailGiant Inc | Proposal | $200K | 68 days ago | 22 days ago | 1 (VP IT) | Trade show | 28 days |
| HealthSys Partners | Eval | $95K | 32 days ago | 8 days ago | 3 (CDO, Data Arch, CIO) | Webinar | 9 days |
| StartupXYZ | Demo | $35K | 18 days ago | 35 days ago | 1 (Founder) | SEO | 18 days |
| Apex Financial | Proposal | $180K | 55 days ago | 5 days ago | 5 (CFO, CTO, CISO, 2 analysts) | SDR outbound | 31 days |

**Output Example:**

**PIPELINE QUALITY EXECUTIVE BRIEF — Meridian Analytics Q3**

*Quality-Weighted Forecast: $407K confident revenue vs. $630K nominal pipeline in active stages*

| Deal | ACV | Score | Tier | Status | Primary Risk | Action |
|------|-----|-------|------|--------|-------------|--------|
| CloudNative Corp | $120K | 82/100 | A | 🟢 Healthy | None significant | Accelerate: executive case study, competitive brief (vs. Databricks) |
| RetailGiant Inc | $200K | 41/100 | C | 🔴 At Risk | Single-threaded, 22-day stale, no champion | URGENT: Multi-thread ABM campaign, VP of IT → CTO bridge content, re-engagement sequence |
| HealthSys Partners | $95K | 79/100 | A | 🟢 Healthy | Stage slightly slow | Healthcare compliance proof package, peer reference (UnitedHealth case study) |
| StartupXYZ | $35K | 18/100 | D | 🔴 Low Quality | Wrong ICP size, single-threaded, 35-day stale | Disqualify or deprioritize; move to long-cycle nurture |
| Apex Financial | $180K | 88/100 | A | 🟢 Healthy | Proposal stage >avg | CFO ROI presentation, security review kit, expedite legal review |

**Pipeline Distribution:**
- Tier A (High Quality): 3 deals = $395K ARR (63%)
- Tier C (At-Risk): 1 deal = $200K ARR (32%)
- Tier D (Low Quality): 1 deal = $35K ARR (6%)

**Root Cause Insights:**
- Best pipeline quality source: SDR outbound (avg score 88) — invest more
- Worst pipeline quality source: SEO/inbound (avg score 18) — lead quality problem, review MQL criteria
- Stage with highest degradation: Proposal → Close (avg 31 days vs. 18-day target)

**CFO Summary:**
Quality-adjusted pipeline confidence is $492K against $630K nominal — a 22% quality discount. Two Tier-A deals totaling $300K have high close probability this quarter. Intervention is underway on RetailGiant ($200K) with multi-threading campaign launched. Recommend removing StartupXYZ from forecast.

## Success Metrics

- **Forecast accuracy improvement**: Quality-scored forecasts should improve quarter-over-quarter forecast accuracy by 15-25%
- **Intervention conversion rate**: Track what % of Tier C/D deals move to Tier B/A after marketing intervention within 30 days
- **Pipeline quality distribution trend**: Target 60%+ of pipeline ARR in Tier A/B week-over-week
- **Marketing source quality score**: Average deal quality by marketing program — optimize investment toward highest-quality sources
- **Revenue recovered from intervention**: Track ARR saved from at-risk deals via targeted marketing plays
- **Time to quality degradation**: Identify average number of days before a deal drops a tier — early warning system threshold

## Related Prompts

- [Pipeline Coverage Analytics & Revenue Gap Intelligence](../../05_Analytics-&-Performance/Pipeline-Velocity-Analytics/AI-Powered-B2B-SaaS-Pipeline-Coverage-Analytics-&-Quarterly-Revenue-Gap-Intelligence-Engine.md)
- [Pipeline Velocity Analytics & Marketing-Led Deal Acceleration](../../05_Analytics-&-Performance/Pipeline-Velocity-Analytics/AI-Powered-B2B-SaaS-Pipeline-Velocity-Analytics-&-Marketing-Led-Deal-Acceleration-Revenue-Intelligence-Engine.md)
- [ABM Buying Committee Engagement Scoring](../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Buying-Committee-Engagement-Scoring-&-Multi-Stakeholder-Deal-Velocity-Intelligence-Engine.md)
- [Sales Enablement Content Analytics & Revenue Impact](../../05_Analytics-&-Performance/Sales-Enablement-Analytics/AI-Powered-B2B-Sales-Enablement-Content-Analytics-&-Revenue-Enabling-Asset-Performance-Intelligence-Engine.md)

## Integration Tips

**Salesforce / HubSpot CRM:**
- Export opportunity data with custom fields (stakeholder count, last activity, stage entry date) to CSV, paste into prompt
- Map quality scores back to a custom CRM field (`Pipeline_Quality_Score__c`) to enable dashboard views
- Create workflow automations: deals dropping below 50 score trigger Slack alert to marketing + sales rep

**Revenue Intelligence Platforms (Gong, Clari, Chorus):**
- Pull conversation intelligence data (call engagement, sentiment, topic frequency) to feed Dimension 3 (momentum) more accurately
- Clari's deal health scores can supplement — use AI quality scoring as a validation/second opinion layer

**Notion / Google Sheets:**
- Build a live Pipeline Quality Dashboard: paste deal data weekly, track Tier distribution over time
- Create a 4-week trend chart: Tier A ARR % trending up = improving pipeline quality culture

**Slack Alerts:**
- Set up a weekly "Pipeline Health Brief" Slack post for sales leadership and marketing with quality tier summary
- Flag new Tier D deals to marketing ops for immediate MQL review and lead scoring calibration

**Zapier / Make.com:**
- Trigger: CRM deal with last activity >21 days → Auto-run re-engagement playbook via marketing automation
- Trigger: New Tier A deal identified → Auto-alert field marketing for executive event invitation

## Troubleshooting

**Problem:** CRM data is incomplete — missing stakeholder counts, last activity is inaccurate, or custom fields not populated.
**Solution:** Run the scoring against available data with explicit "Data Quality Warnings" for each deal. Flag CRM hygiene as a parallel initiative — pair this prompt with the [Marketing Automation Workflow Audit](../../05_Analytics-&-Marketing-Operations/MarTech-Stack-Optimization/Marketing-Automation-Workflow-Architecture-Engine.md) to fix data capture at the source. Use "Unknown = 0 score" default to penalize poor data quality and create a natural incentive for reps to update CRM.

**Problem:** Sales doesn't trust the pipeline quality scores — they feel marketing is second-guessing their deals.
**Solution:** Frame this as a shared tool, not marketing oversight. Co-build the scoring model with sales leadership in a 30-minute working session — let them validate the dimensions and weights. Name it "Revenue Team Pipeline Health Score" rather than "Marketing Pipeline Scoring." Show how Tier A deals close faster and at higher rates — let the data make the case.

**Problem:** Quality scores don't correlate with actual win rates after 2-3 quarters of data.
**Solution:** Recalibrate dimension weights using your actual closed-won/lost data. Run a regression analysis: which quality dimensions have highest correlation with closed-won in your specific market? Adjust weights accordingly. Common finding: ICP fit is the #1 predictor for SMB, while buying committee coverage is #1 predictor for enterprise deals.

## Version History
- v1.0: Initial creation (auto-generated)
