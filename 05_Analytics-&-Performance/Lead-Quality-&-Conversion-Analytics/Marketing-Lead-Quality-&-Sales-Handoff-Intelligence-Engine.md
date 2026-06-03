# Marketing Lead Quality & Sales Handoff Intelligence Engine - Eliminate Revenue Leakage at the Marketing-to-Sales Boundary

**Difficulty:** Advanced | **Time:** 20-25 min | **Tags:** b2b, saas, mql, sql, sales-handoff, lead-quality, pipeline-velocity, revenue-operations, sla, conversion-optimization

## Overview
Diagnoses and rebuilds the marketing-to-sales handoff process by analyzing MQL definition accuracy, handoff SLA compliance, SQL acceptance rates, rejection reason patterns, and pipeline leakage at every conversion boundary. Use this when marketing generates leads that sales ignores, when MQL-to-SQL conversion is below 20%, or when marketing and sales argue about lead quality every quarter.

## Quick Copy-Paste Version

You are a senior revenue operations analyst specializing in B2B SaaS pipeline conversion and marketing-sales alignment. Analyze my lead handoff data and produce a complete MQL-to-SQL Conversion Intelligence Report with specific fixes.

My current situation:
- Company stage and ACV: [e.g., Series B, $45K ACV]
- Monthly MQL volume: [e.g., 380 MQLs/month]
- Current MQL-to-SQL conversion rate: [e.g., 18%]
- SQL acceptance rate (% of passed MQLs that sales accepts): [e.g., 61%]
- Top lead rejection reasons from sales: [e.g., "wrong company size," "not the right persona," "already a customer," "no budget timeline"]
- Current MQL scoring model: [e.g., demographic fit score + behavioral engagement score, threshold = 80 points]
- Sales SLA for MQL follow-up: [e.g., 24 hours, but actual average is 41 hours]
- CRM used: [HubSpot / Salesforce / Pipedrive / other]

Deliver:
1. **Handoff Failure Diagnosis**: identify the top 3 reasons MQLs fail to convert to SQL at my company
2. **MQL Definition Audit**: recommend specific changes to scoring criteria to improve acceptance rate to 75%+
3. **SLA Compliance Fix**: design an automated SLA enforcement workflow with escalation triggers
4. **Rejection Reason Taxonomy**: build a structured rejection code system sales can use in under 10 seconds
5. **Feedback Loop Architecture**: design a weekly closed-loop process where sales rejection data automatically improves the MQL model
6. **30-day quick win plan**: 3 specific actions to improve MQL-to-SQL rate by 5+ percentage points this quarter

Format as an ops-ready report with specific CRM configuration instructions.

## Advanced Customizable Version

ROLE: You are a Chief Revenue Operations Architect with 15+ years of B2B SaaS go-to-market experience. You apply MEDDIC qualification frameworks, statistical funnel analysis, and process engineering to eliminate revenue leakage at the marketing-to-sales boundary.

OBJECTIVE: Perform a comprehensive MQL-to-SQL Handoff Intelligence Audit and produce a complete revenue conversion optimization system — covering lead definition architecture, SLA engineering, rejection analysis, and closed-loop learning — that increases SQL acceptance rate to 75%+ and MQL-to-pipeline conversion by 30% within 90 days.

COMPANY CONTEXT:
- Company name: [Company]
- Product category: [e.g., B2B SaaS — revenue intelligence platform]
- ARR and stage: [e.g., $31M ARR, Series C]
- ACV range: [e.g., $18K–$120K, average $52K]
- ICP definition: [e.g., VP Sales and CRO at 100–2,000 employee SaaS companies]
- Sales team structure: [e.g., 12 AEs, 8 SDRs, segmented by company size: SMB/Mid-Market/Enterprise]
- GTM motion: [e.g., inbound-led with SDR follow-up, demo request as primary conversion]

CURRENT HANDOFF FUNNEL DATA:
Fill in available metrics (mark "unknown" — model will flag instrumentation gaps):

**Volume metrics (last 90 days):**
- Total MQLs generated: [X]
- MQLs passed to sales: [X] (% of total MQLs that meet threshold)
- MQLs accepted by sales as SQL: [X] (% acceptance rate)
- SQLs converted to Opportunities: [X] (SQL-to-Opp rate)
- Opportunities that reached Proposal stage: [X]
- Closed Won from this MQL cohort: [X]

**Speed metrics:**
- Average time from MQL trigger to sales first touch: [X hours]
- SLA target: [X hours]
- SLA compliance rate: [X%] 
- Average time MQL → SQL qualification decision: [X days]
- Average time MQL → Closed Won (for MQLs that convert): [X days]

**Quality metrics:**
- SQL acceptance rate by segment (SMB / Mid-Market / Enterprise): [X% / X% / X%]
- SQL acceptance rate by lead source (organic / paid / event / outbound / referral): [breakdown]
- Top 5 rejection reasons with frequency: [list]
- Average deal size for MQL-sourced vs. non-MQL-sourced pipeline: [comparison]

**Current MQL scoring model:**
Describe your current scoring criteria:
- Firmographic fit criteria: [e.g., company size 50-5000 employees = 20pts, industry match = 15pts, technology fit = 10pts]
- Behavioral engagement criteria: [e.g., demo request = 40pts, pricing page = 20pts, content download = 5pts, webinar = 10pts]
- Negative scoring: [e.g., -30 for student/EDU domain, -20 for competitor domain]
- MQL threshold: [e.g., 80 points]
- Score decay rules: [e.g., none / 10% per week of inactivity]

ANALYSIS FRAMEWORK — apply these methodologies:

**Framework 1: MQL Definition Validity Test**
A valid MQL definition passes four tests:
1. **Conversion Test**: Do MQLs convert to pipeline at ≥20% rate? (Industry benchmark: 15–25%)
2. **Sales Agreement Test**: Do sales reps accept ≥70% of passed MQLs?
3. **Deal Size Test**: Do MQL-sourced deals close at ≥90% of the company average deal size?
4. **Velocity Test**: Do MQL-sourced deals close within ±20% of average sales cycle?

Flag which tests the current model fails and quantify the failure gap.

**Framework 2: Rejection Reason Root Cause Analysis**
Map every rejection reason to one of five root causes:
- **ICP Mismatch** (wrong company, wrong persona, wrong industry) → fix: firmographic scoring
- **Timing Mismatch** (no active initiative, no budget cycle alignment) → fix: behavioral intent signals
- **Data Quality** (bounced email, wrong contact, duplicate record) → fix: data enrichment workflow
- **Sales Process** (lead passed too early, wrong sales segment routed) → fix: handoff workflow
- **Score Inflation** (lead gamed the score or score model is miscalibrated) → fix: negative scoring, intent verification

**Framework 3: SLA Engineering**
Design a three-tier SLA system:
- **Tier 1 — Hot Leads** (demo request, pricing page + high fit score): 15-minute SLA, Slack alert + auto-enrolled sequence
- **Tier 2 — Warm Leads** (behavior-triggered MQL, high engagement): 4-hour SLA, automated first email + SDR task
- **Tier 3 — Nurture Graduates** (score crossed threshold over time): 24-hour SLA, SDR outreach sequence

**Framework 4: Closed-Loop Learning System**
Design an automated feedback system where every sales rejection automatically:
1. Logs structured rejection code to CRM
2. Triggers lead re-scoring or disqualification
3. Feeds weekly aggregate data to marketing dashboard
4. Adjusts threshold recommendation monthly via regression analysis on rejection patterns

DELIVERABLES:

**Section 1: Handoff Diagnostic Report**
- Current state funnel waterfall: MQL → Passed → Accepted (SQL) → Opportunity → Pipeline → Won
- Conversion rate at each stage vs. SaaS industry benchmark (cite Forrester/SiriusDecisions benchmarks)
- Revenue leakage quantification: "At current conversion rates, you are losing approximately $X in ARR per quarter from MQL-stage funnel failure"
- Top 3 structural root causes of handoff failure (specific, not generic)

**Section 2: MQL Scoring Model Redesign**
Produce a revised scoring model that:
- Separates Fit Score (firmographic/technographic: 0–50 points) from Intent Score (behavioral signals: 0–50 points)
- Requires minimum threshold on BOTH dimensions (not just total score) to prevent high-intent-low-fit or high-fit-low-intent MQLs from slipping through
- Adds a Surge Modifier (+15 points) for leads showing 3+ high-intent signals in 7 days
- Adds 5 specific negative scoring rules based on the rejection patterns identified
- Defines score decay: subtract 5 points per week of zero activity after MQL threshold crossing
- Sets a "Sales-Ready" vs. "Nurture" routing decision tree based on score profile

Provide: revised scoring table with point values, new MQL threshold recommendation, and projected impact on acceptance rate.

**Section 3: SLA Enforcement Architecture**
Design a fully automated SLA system:

For each Tier (1/2/3):
- Trigger conditions (exact score + behavioral criteria)
- Automatic actions at T+0 (instant): CRM task creation, Slack/Teams notification with lead context card, auto-enrollment in first-touch sequence
- Escalation at T+X (SLA miss): manager notification, re-routing to available rep, automatic logging of SLA violation
- CRM configuration instructions: HubSpot workflow steps OR Salesforce Flow logic (specify for the user's CRM)
- Dashboard metric: SLA Compliance Rate — target 90%+

**Section 4: Rejection Code System**
Design a 12-code rejection taxonomy that:
- Takes sales reps under 10 seconds to complete (dropdown in CRM, no free text required)
- Maps directly to marketing corrective actions
- Enables monthly pattern reporting

Provide: complete code list, CRM field configuration, and monthly reporting template.

**Section 5: Closed-Loop Intelligence System**
Design a weekly feedback loop:
- Marketing reviews rejection report every Monday morning (what to look for, what thresholds trigger action)
- Monthly model recalibration trigger: if acceptance rate drops below 65% for 3 consecutive weeks → automatic model review
- Quarterly marketing-sales alignment review agenda (specific agenda items, data to bring, decisions to make)
- "MQL Quality Score" internal KPI: blended metric combining acceptance rate, MQL-to-pipeline rate, and deal size index — report this to CMO weekly

**Section 6: 90-Day Transformation Roadmap**

Month 1 (Foundation):
- Week 1: Instrument rejection code system in CRM + run baseline audit
- Week 2: Launch revised MQL scoring model (parallel run with old model for 2 weeks)
- Week 3: Deploy Tier 1 SLA hot-lead automation
- Week 4: First closed-loop review — validate new model vs. old model acceptance rates

Month 2 (Optimization):
- Launch full three-tier SLA system
- First monthly model recalibration using rejection data
- SDR training on new qualification framework (MEDDIC mini-training: 30-min session)
- Begin weekly MQL Quality Score reporting to CMO

Month 3 (Scale):
- Measure 90-day conversion improvement vs. baseline
- Identify top 3 lead sources with highest post-fix quality improvement
- Build board-ready slide: "MQL Engine ROI" showing revenue recovered from handoff optimization
- Plan next iteration of model improvements

OUTPUT FORMAT:
- Executive summary: 5 bullets, revenue impact framing
- Diagnostic waterfall chart (text-based table)
- Revised scoring model (complete table with criteria and points)
- SLA Architecture (three-tier table with automation instructions)
- Rejection Code System (12-code table with CRM config notes)
- Closed-Loop System design (process diagram in text)
- 90-day roadmap (week-by-week)
- Appendix: benchmark data sources and methodology notes

CONSTRAINTS:
- All scoring thresholds must be validated against the company's actual historical data before hardcoding
- Never recommend eliminating a lead segment entirely without testing a nurture alternative first
- SLA recommendations must account for sales team capacity (don't design a system that requires 3x more rep time)
- Every framework change must include a rollback plan if acceptance rate worsens in first 30 days
- MEDDIC qualification criteria must be adapted to the company's specific deal motion

## Example Input/Output

**Input Example:**

Company: Stackwise (B2B SaaS — engineering workflow automation)
ARR: $19M, Series B
ACV: $34K average, range $12K–$95K
ICP: VP Engineering and Engineering Managers at 50–500 employee software companies

Current state:
- 290 MQLs/month, 52% passed to sales (150 MQLs), 58% SQL acceptance rate (87 SQLs)
- MQL→SQL rate: 30% (87 of 290)
- SQL→Opportunity: 61% (53 opportunities)
- Opportunity→Closed Won: 24% (13 deals/month)
- Average MQL→first-touch: 38 hours (SLA target: 24 hours)
- SLA compliance: 54%
- Top rejection reasons: "Too small" (31%), "Not the right person" (24%), "Already evaluated us" (18%), "No active initiative" (17%), "Other" (10%)

Current scoring: Firmographic (company size 50–500=20pts, SaaS industry=15pts) + Behavioral (demo request=40pts, pricing page=15pts, docs page=10pts, content download=5pts). Threshold: 75 points.

**Output Example:**

**EXECUTIVE SUMMARY**
Stackwise is losing approximately $2.1M in annual pipeline through three structural handoff failures: a scoring model that passes 23% of MQLs with company size outside ICP (the "Too small" and "wrong persona" rejection pattern), 54% SLA compliance that allows high-intent leads to go cold in 38 hours, and zero closed-loop feedback that prevents the model from self-correcting. Fixing these three issues projects a 12-percentage-point improvement in MQL-to-SQL rate (30% → 42%) and $620K in incremental quarterly pipeline.

**HANDOFF DIAGNOSTIC WATERFALL**

| Stage | Volume | Conversion | Benchmark | Gap |
|---|---|---|---|---|
| MQLs Generated | 290/mo | — | — | — |
| Passed to Sales | 150/mo | 52% | 60–70% | Threshold too low |
| SQL Accepted | 87/mo | 58% acceptance | 70–80% | -12 to -22 pts |
| Converted to Opp | 53/mo | 61% SQL→Opp | 55–65% | ✓ On target |
| Closed Won | 13/mo | 24.5% | 20–28% | ✓ On target |
| **MQL→Won** | 13/mo | **4.5%** | **6–9%** | **-1.5 to -4.5 pts** |

Revenue leakage calculation: At 6% MQL-to-Won benchmark with $34K ACV, Stackwise should close 17.4 deals/month from MQLs (not 13). Gap = 4.4 deals/month × $34K × 12 months = **$1.79M/year in recoverable revenue**.

**REVISED MQL SCORING MODEL**

*Fit Score (max 50 points — minimum 25 required to reach SQL threshold):*

| Criterion | Points |
|---|---|
| Company size 50–500 employees | 25 |
| Company size 501–2,000 (stretch ICP) | 10 |
| Company size <50 or >2,000 | 0 |
| SaaS / software industry | 15 |
| Adjacent industry (fintech, edtech, etc.) | 8 |
| Non-ICP industry | 0 |
| Engineering-focused company (GitHub signals, eng blog) | 10 |

*Intent Score (max 50 points — minimum 30 required to reach SQL threshold):*

| Criterion | Points |
|---|---|
| Demo request submitted | 50 |
| Pricing page viewed 2+ times in 7 days | 30 |
| Documentation visited 3+ pages in one session | 20 |
| Integration page viewed (e.g., Jira, GitHub integrations) | 15 |
| Blog post read (3+ in 7 days) | 8 |
| Webinar attended live | 12 |
| Content download | 5 |

*Negative Scoring:*
- Competitor domain: -50 (disqualify)
- Student/EDU email: -50 (disqualify)
- "Already evaluated us" tag in CRM: -50 (route to re-engagement, not sales)
- Company size outside 25–3,000 range: -25
- Free email domain (gmail/yahoo) with no company enrichment match: -20

**New threshold**: Fit ≥ 25 AND Intent ≥ 30 AND Total ≥ 80

Projected impact: Acceptance rate improves from 58% → estimated 74% by eliminating the "wrong size" and "wrong persona" categories from reaching sales.

**TIER 1 HOT LEAD SLA — HubSpot Workflow:**
Trigger: Demo request submitted (any source)
T+0 (immediate):
- Create CRM task: "URGENT: Hot Lead Demo Request — Call within 15 minutes" assigned to routing logic
- Send Slack alert to #hot-leads channel: "[Lead Name] at [Company] just requested a demo. Fit Score: [X]. Company: [size, industry]. View in HubSpot: [link]"
- Enroll in Tier 1 automated email sequence (personalized confirmation + value prop)
T+15 min (SLA miss trigger): If task not marked "In Progress" → escalate to SDR manager via Slack DM
T+30 min (hard escalation): Re-assign to next available rep + log SLA violation in CRM

**TOP REJECTION CODE SYSTEM:**
Configure as a required dropdown on "Disqualify Lead" action in HubSpot/Salesforce:

| Code | Label | Marketing Action |
|---|---|---|
| R1 | Company too small (<25 employees) | Adjust firmographic scoring threshold |
| R2 | Company too large (>2,000 employees) | Adjust firmographic scoring threshold |
| R3 | Wrong persona (not VP Eng / Eng Manager) | Update persona scoring, add job title negative score |
| R4 | Already a customer | Add CRM deduplication check pre-MQL |
| R5 | Already evaluated — no decision | Route to 6-month re-engagement sequence |
| R6 | No active initiative / wrong timing | Move to long-term nurture, remove from sales queue |
| R7 | Wrong industry (non-software) | Add industry negative scoring |
| R8 | Bad data (wrong email / bounced / no answer) | Trigger data enrichment workflow (Clearbit/Clay) |
| R9 | Competitor employee | Add competitor domain suppression list |
| R10 | Student / academic | Add EDU domain suppression |
| R11 | Duplicate / already in pipeline | Merge records, route to owning AE |
| R12 | Other (requires manager review) | Flag for weekly triage |

## Success Metrics

- SQL acceptance rate improves from baseline to ≥75% within 90 days
- MQL-to-Opportunity conversion rate improves by ≥8 percentage points
- SLA compliance rate reaches ≥85% (from baseline) within 60 days
- Sales rejection reason "ICP mismatch" drops by ≥50% (indicating improved scoring)
- Marketing can produce a weekly MQL Quality Score reported to CMO with zero manual data pulls
- Monthly model recalibration takes under 2 hours using the closed-loop data

## Related Prompts

- [AI-Powered B2B Lead Source Quality Scoring & Channel Revenue Contribution Intelligence Engine](./AI-Powered-B2B-Lead-Source-Quality-Scoring-&-Channel-Revenue-Contribution-Intelligence-Engine.md)
- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine](./Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)
- [Marketing Funnel Conversion & Pipeline Velocity Intelligence Engine](../Funnel-Conversion-&-Pipeline-Velocity/Marketing-Funnel-Conversion-&-Pipeline-Velocity-Intelligence-Engine.md)
- [AI-Powered B2B Conversion Rate Benchmarking & Funnel Stage Optimization Intelligence Engine](../Funnel-Conversion-&-Pipeline-Velocity/AI-Powered-B2B-Conversion-Rate-Benchmarking-&-Funnel-Stage-Optimization-Intelligence-Engine.md)

## Integration Tips

- **HubSpot**: Build the three-tier SLA as a Workflow with enrollment triggers on Lead Score change; use HubSpot's "Lead Routing" feature to assign by segment; configure the rejection code as a custom "Disqualification Reason" property with a dropdown list — add it as a required field on the "Disqualify" button in the contact record
- **Salesforce**: Use Salesforce Flow to create the SLA automation; build the rejection code system as a picklist field on the Lead object; use Salesforce Reports with "Lead Status = Disqualified" grouped by Rejection Reason to generate the weekly closed-loop report automatically
- **Slack**: Create a #mql-hot-leads channel for Tier 1 alerts; use Zapier or HubSpot → Slack native integration; include deal context card (company, size, industry, behavior that triggered MQL) so reps have context before calling
- **Clay / Clearbit / Apollo**: Run data enrichment on every MQL at the moment of threshold crossing — auto-populate company size, industry, tech stack, and LinkedIn URL before the lead reaches sales; this alone can reduce "bad data" rejections by 60–80%
- **Google Sheets / Looker**: Build the weekly MQL Quality Score dashboard pulling from HubSpot/Salesforce API; calculate Acceptance Rate, MQL-to-Opp Rate, and Deal Size Index weekly; set up a Google Sheets trigger to email the CMO dashboard every Monday at 8am
- **Gong / Chorus**: Pull call recordings for disqualified leads to validate rejection reason accuracy — do sales reps' actual objections match the rejection codes they log? Use this to calibrate the taxonomy quarterly
- **Salesloft / Outreach**: Configure the three-tier SLA sequences directly as cadences; use Tier 1 as a "hot inbound" cadence with aggressive touchpoint density (call + email + LinkedIn within 15 min, 1 hr, 4 hr, 24 hr)

## Troubleshooting

- **Problem**: Sales reps skip the rejection code dropdown and just disqualify leads without logging a reason, making the closed-loop system useless.
  **Solution**: Make the rejection code field required in your CRM — Salesforce and HubSpot both support mandatory fields on status-change actions. If reps resist, escalate to VP Sales to enforce as a process requirement tied to pipeline accuracy. Alternatively, simplify the taxonomy to 6 codes instead of 12 — fewer options = higher compliance.

- **Problem**: After implementing the revised scoring model, MQL volume drops 40% and the sales team still complains about quality.
  **Solution**: Run the old and new model in parallel for 30 days before fully switching — score every lead with both models and compare acceptance rates on actual sales outcomes. If the new model's volume drop is causing pipeline coverage issues, lower the Fit score minimum threshold from 25 to 20 to capture more edge-of-ICP prospects, while keeping the Intent minimum at 30 to ensure behavioral signals remain required.

- **Problem**: The SLA automation fires correctly but reps ignore the Slack alerts and the 15-minute Tier 1 SLA is consistently missed.
  **Solution**: The problem is incentive misalignment, not technology. Work with VP Sales to add SLA Compliance Rate to the SDR/AE performance dashboard (visible to managers). Consider a simple incentive: reps who maintain ≥90% SLA compliance get first pick of inbound lead routing for the following week. Technology alone will not fix a process adoption problem.

## Version History
- v1.0: Initial creation (auto-generated)
