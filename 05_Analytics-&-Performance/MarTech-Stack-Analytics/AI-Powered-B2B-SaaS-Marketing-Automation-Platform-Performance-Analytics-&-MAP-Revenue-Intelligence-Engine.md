# AI-Powered B2B SaaS Marketing Automation Platform Performance Analytics & MAP Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, martech, marketing-automation, analytics, hubspot, marketo, pardot, marketing-operations, pipeline, revenue-attribution

## Overview
Transforms your Marketing Automation Platform (MAP) operational data — campaign performance, database health, automation flows, lead scoring signals, and email deliverability metrics — into an actionable revenue intelligence report. Use this prompt monthly or quarterly to diagnose underperforming programs, fix database decay before it erodes pipeline, and prove the revenue contribution of your MAP investment to the CFO.

## Quick Copy-Paste Version

You are a senior marketing operations analyst specializing in Marketing Automation Platform (MAP) performance analytics for B2B SaaS companies. Analyze the following MAP data and produce a comprehensive performance and revenue contribution report.

MAP IN USE: [HubSpot / Marketo / Pardot / ActiveCampaign / Other]
REPORTING PERIOD: [Last 30 / 60 / 90 days]

DATA TO ANALYZE:

1. DATABASE HEALTH:
   - Total contacts in MAP: [X]
   - Active / marketable contacts: [X]
   - Contacts added last 90 days: [X]
   - Unsubscribe rate last 90 days: [X]%
   - Hard bounce rate: [X]% | Soft bounce rate: [X]%
   - Contacts with no email activity in 180+ days: [X]
   - ICP-fit contacts (matching lead score threshold): [X]

2. EMAIL PROGRAM PERFORMANCE (last 90 days):
   - Campaigns sent: [X] | Total emails delivered: [X]
   - Average open rate: [X]% | Average click rate: [X]%
   - Average click-to-open rate (CTOR): [X]%
   - Top 3 performing campaigns (open rate, CTR, pipeline sourced): [paste]
   - Bottom 3 campaigns by engagement: [paste]
   - Unsubscribe rate per campaign: [X]%

3. AUTOMATION PROGRAM PERFORMANCE:
   - Active automation programs/workflows: [X]
   - Total contacts enrolled in active programs: [X]
   - Programs with >50% drop-off before completion: [list]
   - Nurture sequences: average emails sent before MQL conversion: [X]
   - Triggered programs (behavior-based): average response time and engagement: [paste]

4. LEAD SCORING MODEL:
   - Current scoring model: [demographic weights + behavioral weights, or describe]
   - MQLs passed to sales last 90 days: [X]
   - MQL-to-SQL conversion rate: [X]%
   - MQLs rejected by sales (recycled back): [X] | Rejection reason categories: [paste]
   - Average lead score at time of MQL: [X]
   - Average days from first touch to MQL: [X]

5. PIPELINE CONTRIBUTION:
   - Opportunities with MAP-touched contacts: [X] | Total pipeline value: $[X]
   - MAP-sourced pipeline (first touch via MAP program): $[X]
   - MAP-influenced pipeline (any MAP touch in buying journey): $[X]
   - Closed-won deals with MAP attribution: [X] | Revenue: $[X]

DELIVER THIS ANALYSIS:

1. MAP PERFORMANCE EXECUTIVE SCORECARD
   - Database health score (A/B/C/D) with 3 supporting metrics
   - Email program health score with benchmark comparison (B2B SaaS industry averages)
   - Automation effectiveness score
   - Lead scoring accuracy assessment
   - MAP revenue contribution summary: pipeline sourced $X, influenced $X, closed-won $X

2. DATABASE HEALTH DIAGNOSIS
   - Engagement tier segmentation: Active (opened/clicked in 90 days) / Dormant (91-180 days) / Dead (180+ days)
   - Estimated annual revenue risk from database decay
   - Top 3 database hygiene actions with priority ranking
   - Re-engagement vs. suppression recommendation for dormant segments

3. EMAIL PROGRAM OPTIMIZATION PLAN
   - Campaign performance benchmarks vs. B2B SaaS industry standards (open rate 22-28%, CTR 3-5%, CTOR 12-18%)
   - Subject line patterns driving above-average open rates (extract from top performers)
   - CTA patterns driving above-average CTR
   - 3 specific optimization recommendations for underperforming campaigns

4. AUTOMATION FLOW AUDIT
   - Programs with drop-off > 40%: identify step where engagement breaks
   - Programs with < 5% conversion: recommend pause/rebuild vs. optimize
   - Missing automation gaps: buyer journey stages with no active nurture coverage

5. LEAD SCORING MODEL ACCURACY REPORT
   - MQL-to-SQL conversion rate vs. target (B2B SaaS benchmark: 25-35%)
   - Top rejection reasons and what they reveal about scoring model gaps
   - Specific scoring model adjustments recommended (add/remove signals, reweight)
   - Predicted impact of adjustments on MQL quality

6. REVENUE ATTRIBUTION SUMMARY
   - MAP-sourced vs. MAP-influenced pipeline breakdown
   - Cost per MAP-sourced opportunity: Total MAP cost ÷ Sourced opportunities
   - MAP ROI: (Closed-won revenue attributed to MAP ÷ Annual MAP platform cost) x 100
   - 30/60/90 day action plan to increase MAP revenue contribution by [X]%

Format all outputs as executive-ready tables and bullet points. Flag all metrics against B2B SaaS industry benchmarks. Prioritize recommendations by revenue impact.

## Advanced Customizable Version

SYSTEM ROLE:
You are an AI-powered Marketing Automation Platform (MAP) Revenue Intelligence Engine for a B2B SaaS company. You combine the operational rigor of a senior marketing operations architect (10+ years of MAP administration at Marketo, HubSpot, and Pardot), the analytical depth of a revenue operations analyst, and the commercial judgment of a CFO who demands proof of marketing ROI. Your mandate: transform MAP operational data into a revenue-contribution intelligence system that identifies every program improvement opportunity, fixes database decay before it costs pipeline, and builds an unassailable business case for MAP investment.

You apply these frameworks:
- Demand Waterfall methodology (Sirius Decisions/Forrester) for funnel stage definitions
- Database decay rate modeling (industry standard: B2B contact data decays 30% per year)
- Email performance benchmarks from Mailchimp, HubSpot, and Litmus 2025 State of Email reports
- Lead scoring best practices from LeanData, MadKudu, and 6sense frameworks
- Multi-touch attribution models (W-shaped, full-path, custom)

COMPANY CONTEXT:
- Company: [Your Company Name]
- MAP Platform: [HubSpot Marketing Hub / Marketo Engage / Pardot/MCAE / ActiveCampaign / Eloqua / Other]
- MAP tier/edition: [Starter / Professional / Enterprise — affects feature availability]
- CRM integration: [Salesforce / HubSpot CRM / Microsoft Dynamics] — bidirectional sync? [Yes/No]
- Company stage: [Seed / Series A / Series B / Series C / Growth / Enterprise]
- ARR: $[X]M | Monthly new logo target: [X] | MQL-to-pipeline target: [X]%
- Marketing team size: [X] | Marketing ops headcount: [X]
- Annual MAP license cost: $[X]K
- Reporting period: [Month/Quarter] [Year]
- Attribution model: [First-touch / Last-touch / Linear / W-shaped / Custom]

SECTION 1 — DATABASE INTELLIGENCE

Primary database metrics:
- Total contacts: [X] | Total companies/accounts: [X]
- Marketable contacts (opted-in, valid email): [X]
- Contacts by source: [CRM sync: X | Form fills: X | List import: X | API: X | Other: X]
- ICP-fit contacts meeting lead score threshold (score ≥ [X]): [X]
- Contacts by funnel stage: [Unknown: X | MQL: X | SAL: X | SQL: X | Opportunity: X | Customer: X]

Database health metrics:
- Hard bounce rate (last 30 days): [X]% — (benchmark: <2%)
- Soft bounce rate (last 30 days): [X]% — (benchmark: <5%)
- Global unsubscribe rate (cumulative): [X]% | Unsubscribes last 30 days: [X]
- Spam complaint rate: [X]% — (benchmark: <0.1% for deliverability protection)
- Duplicate contact records: [X] (estimated or actual)
- Contacts with missing critical fields (job title, company, phone): [X]
- Contacts last engaged (opened/clicked) within: 0-30 days: [X] | 31-90 days: [X] | 91-180 days: [X] | 180+ days: [X]
- Email domain health: top 10 email domains by volume and bounce rate: [paste]

Segmentation coverage:
- Contacts with persona/segment tag: [X]% of database
- Contacts enrolled in at least one active nurture program: [X]%
- Contacts with no program enrollment and no sales owner: [X] — (orphan contacts)

SECTION 2 — EMAIL CAMPAIGN PERFORMANCE

[Paste or describe performance for last 10-20 campaigns]:
Campaign Name | Send Date | Segment | Subject Line | List Size | Delivered | Open Rate | CTR | CTOR | Unsubscribes | Conversions (clicks to form/demo) | Pipeline Influenced

B2B SaaS email benchmarks for comparison:
- Open rate: 22-28% (transactional/trigger: 35-55%)
- Click-through rate: 3-5%
- Click-to-open rate: 12-18%
- Unsubscribe rate per campaign: <0.3%

Sender reputation status:
- Current domain reputation: [Good / Fair / Bad] (Google Postmaster Tools)
- DMARC policy: [None / Quarantine / Reject]
- SPF and DKIM: [Configured / Not configured / Partially configured]
- Dedicated sending domain: [Yes / No]
- Email warm-up history for new domains: [paste if applicable]

SECTION 3 — AUTOMATION PROGRAM AUDIT

List all active automation programs/workflows:
Program Name | Type (Nurture/Trigger/Lifecycle) | Goal | Contacts Enrolled | Emails in Sequence | Avg Completion Rate | Avg Conversion Rate (goal completion) | Revenue Influenced (last 90 days)

Program types to audit:
- New lead nurture sequences (MQL intent)
- Trial/freemium activation sequences
- Champion/persona-specific nurture tracks
- Competitive displacement sequences
- Re-engagement / win-back sequences
- Post-demo / post-event follow-up sequences
- Customer onboarding / expansion sequences
- Renewal reminder sequences

Drop-off analysis: For programs with completion rate < 40%, identify:
- Which step has the highest drop-off
- What content/CTA is used at that step
- Hypothesis for drop-off cause

SECTION 4 — LEAD SCORING MODEL AUDIT

Current lead scoring model:
Demographic/firmographic scoring (max [X] points):
- Job title match (C-suite/VP/Director/Manager/IC): [points per level]
- Company size (employees): [points per tier]
- Industry/vertical match to ICP: [points]
- Technology stack signals (using [competitor/complementary tool]): [points]
- Company revenue range: [points]

Behavioral scoring (max [X] points):
- Pricing page visit: [X] pts
- Demo request (incomplete): [X] pts
- Webinar attendance: [X] pts
- Case study download: [X] pts
- Email clicks: [X] pts
- Website visits (high-intent pages): [X] pts
- Free trial signup: [X] pts
- Repeat visits in 7 days: [X] pts
- Score decay (days of inactivity): [-X pts per Y days]

MQL threshold: [X] points
Current MQL-to-SQL conversion: [X]% (target: [X]%)
Sales rejection rate: [X]% | Top rejection reasons: [paste]

Scoring model performance data (last 90 days):
- MQLs created: [X] | MQLs converted to SQL: [X] | MQLs recycled: [X] | MQLs disqualified: [X]
- Average lead score at MQL creation: [X]
- Average score of leads that converted to SQL: [X]
- Average score of recycled/rejected leads: [X]

SECTION 5 — REVENUE ATTRIBUTION

Pipeline data (last 90 days):
- New opportunities created: [X] | Total pipeline value: $[X]
- Opportunities with ≥1 MAP touchpoint: [X] | Value: $[X] — MAP influence rate: [X]%
- Opportunities sourced by MAP program (first touch): [X] | Value: $[X]
- Opportunities where MAP nurture was last touch before demo/trial: [X] | Value: $[X]
- Closed-won with MAP attribution: [X] deals | Revenue: $[X]
- Average MAP touches per closed-won deal: [X]

Program-level attribution (top 5 programs by pipeline influenced):
Program | Contacts in Program | Opportunities Influenced | Pipeline Value | Closed-Won | Revenue

DELIVER THESE OUTPUTS:

SECTION A: EXECUTIVE MAP SCORECARD (board-ready, 1 page)
Metrics dashboard with current vs. target vs. benchmark:
- Database Marketability Index: [X]% (marketable ÷ total) | Target: >70%
- Email Program Health Score: A/B/C/D
- Automation Coverage Rate: [X]% of funnel stages covered by active programs
- Lead Scoring Accuracy: MQL→SQL rate [X]% vs. benchmark 25-35%
- MAP Revenue ROI: $[X] closed-won ÷ $[X] MAP cost = [X]x ROI
- MAP Pipeline Influence Rate: [X]% of pipeline touched by MAP

SECTION B: DATABASE HEALTH REPORT
- Engagement tier breakdown with visualizable table
- Annual database decay projection: at current decay rate, in 12 months you will lose [X] marketable contacts worth $[X] potential pipeline
- Suppression list recommendations: contacts to suppress vs. re-engage (with 2x2 matrix: engagement level x ICP fit)
- Database growth gap analysis: to maintain [X] marketable contacts at 30% annual decay, you must add [X] new contacts per month — current rate: [X]/month — gap: [X]/month
- Top 3 database growth recommendations with estimated contact acquisition cost

SECTION C: EMAIL PROGRAM OPTIMIZATION PLAYBOOK
- Subject line analysis: patterns from top-performing campaigns (length, question vs. statement, personalization tokens, urgency indicators)
- Send time optimization: best day/time for your audience based on historical open patterns
- Segmentation gaps: campaigns sent to broad list vs. targeted segment — performance delta
- A/B test roadmap: 3 highest-priority tests with hypothesis, success metric, and minimum sample size
- Content audit: asset types driving highest pipeline influence (case studies, ROI calculators, demos, webinars)

SECTION D: AUTOMATION PROGRAM REBUILD PRIORITIES
For each underperforming program:
- Diagnosis: where engagement breaks and why (content mismatch, send frequency, wrong audience, irrelevant CTA)
- Recommendation: Optimize / Rebuild / Archive (with effort estimate: Low/Medium/High)
- Impact estimate: [X]% lift in conversion would generate [X] additional MQLs/month

New program recommendations: identify buyer journey stages with no automation coverage and the revenue opportunity each represents

SECTION E: LEAD SCORING MODEL OPTIMIZATION
- Scoring signal accuracy analysis: which signals most strongly correlate with SQL conversion in your historical data
- Over-weighted signals (inflating scores without conversion intent): [list with evidence]
- Under-weighted signals (strong converters not scoring high enough): [list with evidence]
- Recommended score adjustments with before/after MQL volume projection
- Predictive scoring upgrade assessment: readiness for AI-powered predictive scoring (MadKudu, 6sense, Clearbit Reveal) vs. rule-based model — ROI case

SECTION F: 90-DAY MAP PERFORMANCE IMPROVEMENT PLAN
Week 1-2 (Quick Wins — no developer required):
- [Action]: Expected impact: [X more MQLs / X% improvement in open rate / $X pipeline]

Month 1-2 (Program rebuilds — moderate effort):
- [Action]: Expected impact: [X]

Month 2-3 (Strategic: scoring model update, new programs):
- [Action]: Expected impact: [X]

Total projected 90-day impact:
- Additional MQLs: [X]
- Pipeline influenced increase: $[X]
- Estimated revenue impact (at current close rates): $[X]

## Example Input/Output

**Input Example (Quick Version):**

MAP: HubSpot Marketing Hub Enterprise
Period: Q2 2026 (April–June)

Database: 47,000 total contacts | 31,200 marketable | 4,100 added last 90 days | Unsubscribe rate: 0.8% | Hard bounces: 3.2% | Soft bounces: 6.1% | No activity 180+ days: 11,400 contacts | ICP-fit: 8,300

Email performance (last 90 days, 18 campaigns): Avg open rate 19.4% | Avg CTR 2.1% | Avg CTOR 10.8% | Top campaign: "5 Signs Your RevOps Stack Is Costing You Pipeline" — 34.2% open, 6.8% CTR | Bottom: "Q2 Product Newsletter" — 11.2% open, 0.9% CTR

Automation: 14 active workflows, 6,200 contacts enrolled | 4 programs with >50% drop-off at email 3-4 | Avg nurture-to-MQL: 7.3 emails | Triggered (demo no-show follow-up): 28% reply rate

Lead scoring: threshold 85 pts | MQL-to-SQL: 22% | Sales rejection rate: 31% | Avg score at MQL: 87 | Avg score of recycled leads: 84 | Top rejection reasons: "Not the right title" (44%), "Company too small" (29%), "No budget authority" (27%)

Pipeline: 143 new opportunities | $4.2M pipeline | MAP-touched: 108 opps ($3.1M) | MAP-sourced: 34 opps ($890K) | Closed-won with MAP attribution: 11 deals | $312K revenue

**Output Example:**

**MAP PERFORMANCE EXECUTIVE SCORECARD — Q2 2026**

| Metric | Current | Target | Benchmark | Status |
|--------|---------|--------|-----------|--------|
| Database Marketability | 66.4% | >70% | 65-75% | ⚠️ At Risk |
| Avg Email Open Rate | 19.4% | 24%+ | 22-28% | 🔴 Below |
| Email CTR | 2.1% | 3.5%+ | 3-5% | 🔴 Below |
| MQL→SQL Conversion | 22% | 30%+ | 25-35% | 🔴 Below |
| MAP Pipeline Influence | 73.8% | 75%+ | 70-80% | 🟡 On Track |
| MAP Revenue ROI | 3.2x | 5x+ | 4-8x | 🔴 Below |

**Top 3 Priorities:**

1. **Lead Scoring Model Overhaul (Impact: +8pp MQL-to-SQL, ~$180K additional pipeline/quarter)**
   - Problem: 31% rejection rate indicates model is promoting contacts by behavioral score alone without sufficient ICP gating. "Not the right title" (44%) and "too small" (29%) are firmographic failures.
   - Fix: Add hard disqualification rules — contacts at companies < 50 employees or titles below Manager cannot MQL regardless of behavior score. Add +20 pts for VP+ title, +15 for company 200-1000 employees.
   - Before: 87 MQL avg score, 22% conversion | After (projected): fewer MQLs but 32-36% conversion

2. **Database Re-Engagement Campaign + Suppression (Impact: +4.3pp open rate, $60K savings in deliverability protection)**
   - 11,400 contacts with no engagement in 180+ days represent 24% of marketable database
   - 3.2% hard bounce (above 2% threshold) is damaging sender reputation and hurting deliverability for your entire list
   - Immediate action: suppress all 180+ day dormant contacts from campaigns. Run 2-email win-back sequence in isolated sending domain. Those who don't re-engage: suppress permanently.
   - Expected: open rates improve to 24-26% within 60 days as sender score recovers

3. **Automation Drop-Off Fix at Email 3-4 (Impact: +22 MQLs/month, ~$85K additional pipeline/quarter)**
   - 4 programs losing 50%+ of contacts at email 3-4. This is the classic "interest cliff" — your first 2 emails use high-value leads magnets, email 3-4 drops to product pitches.
   - Fix: Insert a "choose your own path" email at position 3 — offer 3 content paths (technical evaluator, business buyer, competitive comparison). This typically recovers 15-25% of drop-off.

---

## Success Metrics

- MAP-sourced pipeline growth: target +15-25% quarter-over-quarter
- MQL-to-SQL conversion rate: 28-35% (from current industry average 22-26%)
- Database marketability rate: >72% of total contacts marketable and engaged
- Email open rate: 24-28% (aligned to B2B SaaS benchmarks)
- Email CTR: 3.5-5% (from B2B SaaS average of 2.1-3.5%)
- Automation completion rates: >60% for strategic nurture programs
- MAP revenue ROI: >5x (MAP-attributed closed revenue ÷ platform cost)
- Database hygiene: hard bounce rate <2%, spam complaint rate <0.08%

## Related Prompts

- [MarTech Stack ROI Analytics & Marketing Technology Investment Optimization](./AI-Powered-B2B-SaaS-MarTech-Stack-ROI-Analytics-&-Marketing-Technology-Investment-Optimization-Intelligence-Engine.md)
- [MarTech Consolidation & AI-Native Stack Migration](./AI-Powered-B2B-SaaS-MarTech-Consolidation-&-AI-Native-Stack-Migration-Revenue-Intelligence-Engine.md)
- [Email Marketing Revenue Attribution & Nurture Program Pipeline Contribution](../../05_Analytics-&-Performance/Email-Marketing-Performance-Analytics/AI-Powered-B2B-Email-Revenue-Attribution-&-Nurture-Program-Pipeline-Contribution-Intelligence-Engine.md)
- [Lead Quality & Marketing-to-Sales Handoff Analytics](../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/)

## Integration Tips

**HubSpot:**
- Export campaign performance data from Reports > Marketing > Email for the Quick Version inputs
- Use HubSpot's Contact Lifecycle Stage reports for funnel attribution
- Connect HubSpot Conversations and Deals to MAP contacts via the CRM sync panel
- Use HubSpot's Attribution Reports (beta) for multi-touch pipeline data

**Marketo:**
- Pull campaign performance from Email Performance Report in Analytics
- Use Revenue Cycle Explorer (RCE) for pipeline attribution by program
- Program Performance Report gives enrollment-to-success conversion by program
- Use Interesting Moments for scoring signal analysis

**Salesforce + Pardot/MCAE:**
- B2B Marketing Analytics Plus gives full MAP-to-pipeline attribution
- Use Engagement Studio performance reports for automation drop-off analysis
- Connected Campaigns syncs Pardot programs to Salesforce campaign attribution

**Zapier / Make.com:**
- Automate MAP performance report assembly by connecting MAP API → Google Sheets → Slack for weekly performance digest
- Trigger re-engagement sequences automatically when contacts pass 90-day inactivity threshold

**Data Warehouses (Snowflake, BigQuery, Databricks):**
- Send MAP event data to your warehouse via vendor native connectors (HubSpot Operations Hub, Marketo's Munchkin.js) for advanced attribution modeling
- Combine with Salesforce opportunity data for full-path, multi-touch attribution

## Troubleshooting

**Problem: Pipeline attribution numbers seem low (MAP influence rate < 50%)**
Solution: Check whether your CRM-MAP sync is capturing all touch events. Common failure: MAP sync only fires on form fills, not email clicks or page visits. Enable activity logging for all contact interactions in both systems. Also verify your attribution window — 90-day windows may miss longer B2B sales cycles; try 6-12 months.

**Problem: MQL volume drops sharply after implementing lead scoring recommendations**
Solution: A 20-40% drop in MQL volume is expected and healthy when fixing an over-inflated model. Brief sales leadership before changes go live — frame as "increasing MQL quality, not reducing quantity." Track MQL-to-SQL rate improvement over the following 30 days; if conversion improves to >28%, the model change is working. If MQL-to-SQL stays flat or declines, you've over-restricted the model — review which firmographic gates are creating false negatives.

**Problem: Email open rates aren't improving after database suppression**
Solution: Open rate improvements take 4-8 weeks as domain reputation recovers with ISPs. Check Google Postmaster Tools and Microsoft SNDS for domain reputation scores before and after. If reputation is "Bad," you may need to warm up a new sending subdomain (e.g., mail2.company.com) over 4-6 weeks. Prioritize Gmail and Microsoft Outlook deliverability separately — they use different reputation signals.

## Version History
- v1.0: Initial creation (auto-generated)
