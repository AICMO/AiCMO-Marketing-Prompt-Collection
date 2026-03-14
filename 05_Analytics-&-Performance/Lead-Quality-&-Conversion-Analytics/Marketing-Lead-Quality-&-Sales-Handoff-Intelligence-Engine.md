# Marketing Lead Quality & Sales Handoff Intelligence Engine - Diagnose and Fix Marketing-to-Sales Conversion Breakdown

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, analytics, lead-quality, sales-alignment, mql, sql, conversion, automation, saas, pipeline

## Overview
Automatically analyzes your full MQL→SQL→Opportunity→Close conversion funnel, identifies which marketing channels and campaigns produce the highest-quality leads (not just volume), diagnoses handoff friction between marketing and sales, and generates a data-driven SLA scorecard with prescriptive fixes. Use this when marketing and sales disagree on lead quality, when SQL-acceptance rates are declining, or when you need to defend marketing's contribution to pipeline.

## Quick Copy-Paste Version

You are a senior B2B revenue analytics consultant specializing in marketing-to-sales alignment. Analyze my lead quality and handoff performance data and produce a complete diagnostic report.

My data:
- Total MQLs last quarter: [number]
- MQL sources: [e.g., Content 40%, Paid Search 25%, Events 20%, SDR 15%]
- MQL→SQL conversion rate by source: [paste data or describe: e.g., Content 28%, Paid 19%, Events 41%]
- SQL→Opportunity rate: [X%]
- Opportunity→Closed-Won rate: [X%]
- Average deal size by lead source: [data or "unknown"]
- Average sales cycle by lead source: [data or "unknown"]
- Current MQL definition/scoring criteria: [describe your scoring model or paste it]
- Marketing-sales SLA (if any): [describe or "none defined"]
- Top sales complaints about marketing leads: [list them]
- Top marketing complaints about sales follow-up: [list them]

Deliver:
1. Lead quality score by channel (composite score: SQL rate × Opp rate × Win rate × deal size)
2. The 3 channels producing the highest-quality leads vs. highest-volume leads (they're different)
3. Funnel leak analysis: where exactly are leads dying and why
4. MQL definition audit: is your scoring model predicting actual buyers or just form-fillers?
5. Marketing-sales SLA scorecard: what metrics each team owns and is missing
6. 5 specific fixes to improve MQL quality within 30 days
7. Recommended changes to lead scoring weights based on actual conversion data
8. Executive summary: the business cost of current lead quality issues (in $ pipeline lost)

Be specific. Use the data I've provided. Flag any gaps in my data that are preventing accurate diagnosis.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations with 12 years of B2B SaaS experience, specializing in lead lifecycle analytics, marketing-sales alignment, and funnel optimization. You have deep expertise in Salesforce, HubSpot, Marketo, 6sense, Bombora, and SQL-based funnel analysis.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Series A / Series B / Series C / Growth / Enterprise]
- ARR: [$X] | ACV: [$X] | Sales cycle: [X days avg]
- Sales motion: [Inbound-led / Outbound-led / PLG / Hybrid]
- Team: [X AEs, X SDRs, X marketing headcount]
- CRM: [Salesforce / HubSpot / Other]
- MAP: [Marketo / HubSpot / Pardot / Other]
- ICP definition: [Company size, industry, tech stack, job titles of buyers]

FUNNEL DATA (paste raw CSV/table or describe):

MQL Volume & Sources (last [90 days / Q / 6 months]):
| Source | MQLs | MQL→SQL % | SQL→Opp % | Opp→Close % | Avg ACV | Avg Cycle (days) |
|--------|------|-----------|-----------|-------------|---------|-----------------|
| [Channel 1] | | | | | | |
| [Channel 2] | | | | | | |
| [Channel 3] | | | | | | |
[paste your data]

CURRENT LEAD SCORING MODEL:
Behavioral scores: [e.g., Email open +5, Demo request +25, Pricing page +15, Webinar attended +10]
Firmographic scores: [e.g., Company size 201-1000 +15, Target industry +10, Job title VP+ +20]
MQL threshold: [score needed to become MQL]
Disqualifying signals: [e.g., competitor domain, free email, student]

SALES FEEDBACK DATA:
- SQL rejection reasons (from CRM disposition codes): [paste rejection reasons + counts]
- Average time from MQL to first sales contact: [X hours/days]
- SDR follow-up sequence: [describe or attach]
- Win/loss themes from recent deals: [describe or attach]

MARKETING CAMPAIGN DATA:
- Top 10 campaigns by MQL volume with source and content type: [paste]
- Content-to-MQL mapping: [which assets are converting to MQLs]
- Paid media campaigns: [campaign names, spend, MQL volume, CPL]

OBJECTIVE: [Choose one or more]
□ Diagnose why SQL acceptance rate dropped [X% → X%]
□ Rebuild lead scoring model from conversion data
□ Create marketing-sales SLA with enforcement metrics
□ Identify our highest-quality lead sources for budget reallocation
□ Build a lead quality dashboard framework
□ Prepare executive presentation on marketing's pipeline contribution

---

ANALYSIS FRAMEWORK: Apply the following methodologies:

1. LEAD QUALITY COMPOSITE SCORE (LQS)
For each lead source, calculate:
LQS = (MQL→SQL rate × 0.25) + (SQL→Opp rate × 0.30) + (Opp→Win rate × 0.25) + (ACV index × 0.20)
Rank all channels by LQS, not by raw MQL volume.
Flag any channel where volume is in the top 3 but LQS is in the bottom 3 (volume trap).

2. FUNNEL LEAK DIAGNOSTIC
Apply the "5-Why Funnel Analysis" to each stage:
- MQL stage: Are MQLs meeting threshold due to genuine intent or gaming/noise?
- MQL→SQL: What % are being rejected? What are the top 3 rejection reasons? Are rejections concentrated in specific campaigns?
- SQL→Opp: Where are qualified leads stalling? Is this a sales motion problem or a lead quality problem?
- Opp→Close: What are the win/loss patterns by lead source? Do marketing-sourced leads have different win rates than outbound?

3. LEAD SCORING AUDIT
Evaluate the current scoring model against actual conversion outcomes:
- Correlation analysis: which score components actually predict SQL conversion?
- Score inflation check: are there behavioral signals that inflate scores without predicting quality? (e.g., re-opens same email 10 times = high score but low intent)
- Firmographic fit gap: is the scoring penalizing or rewarding the right company profiles?
- Recency weighting: are older engagements decaying appropriately?
- Recommended scoring recalibration: new weights based on conversion data

4. MARKETING-SALES SLA FRAMEWORK
Define bilateral commitments:
Marketing SLA to Sales:
- Lead volume: [X MQLs/month by segment]
- Lead quality floor: minimum LQS threshold before handoff
- Lead context: required enrichment fields complete before SQL pass
- Response time SLA for hot signals (demo request, pricing visit + high fit score)

Sales SLA to Marketing:
- Contact attempt: first touch within [X hours] of MQL
- Disposition feedback: SQL rejection reason logged within [X days]
- Qualification rigor: using agreed MEDDIC/BANT/SPICED criteria
- Feedback loop: weekly/monthly lead quality review meeting

5. CHANNEL ROI RECALIBRATION
Reframe marketing investment decisions using quality-adjusted metrics:
- Quality-Adjusted CPL: traditional CPL × (1 / LQS)
- Pipeline Quality Rate: $ pipeline generated per $1 marketing spend, by channel
- Revenue-per-MQL by source: closed-won revenue attributable to each channel / MQLs from that channel
- Identify "budget misalignment": channels getting high spend but generating low-quality pipeline

6. PREDICTIVE SIGNALS ANALYSIS
Based on patterns in your closed-won data, identify:
- The 3-5 behavioral signals that are most predictive of becoming a customer (not just becoming an SQL)
- The firmographic profile that produces the shortest sales cycles
- The content/campaign combination with the highest win rate (not just highest volume)
- Intent signals that, when combined with fit score, predict 60-day close probability

---

DELIVERABLES:

**Section 1: Executive Diagnostic (1 page)**
- Current state: lead quality score by channel (table)
- Business impact of lead quality gap ($ pipeline lost to poor-quality MQLs annually)
- Top 3 root causes of lead quality issues
- Confidence level in data and key assumptions

**Section 2: Lead Quality Scorecard by Channel**
Full table: Channel | MQLs | LQS | CPL | Quality-Adjusted CPL | Pipeline Generated | Revenue Won | Verdict (Scale / Cut / Test)

**Section 3: Lead Scoring Model Rebuild**
- Current model weaknesses (with evidence)
- Recommended new scoring weights (behavioral + firmographic)
- New MQL threshold recommendation with rationale
- Signals to add, remove, or reweight

**Section 4: Funnel Leak Repair Plan**
Stage-by-stage: what's leaking, why, and the specific fix (with owner and timeline)

**Section 5: Marketing-Sales SLA Document**
Ready-to-present SLA with metrics, owners, review cadence, and escalation path

**Section 6: 30/60/90 Day Improvement Roadmap**
- 30 days: quick wins (scoring adjustments, SLA rollout, data cleanup)
- 60 days: structural fixes (campaign optimization, intent data integration)
- 90 days: measurement (re-score all MQLs with new model, measure SQL acceptance lift)

**Section 7: Lead Quality Dashboard Specification**
Key metrics to track weekly, the calculation for each, and which system owns the data

## Example Input/Output

**Input Example:**

Company: DataSync Pro (B2B SaaS, data integration platform)
ARR: $18M | ACV: $45,000 | Sales cycle: 67 days avg
Stage: Series B | Team: 8 AEs, 4 SDRs, 6 marketing

Funnel data (last 90 days):
| Source | MQLs | MQL→SQL % | SQL→Opp % | Opp→Close % | Avg ACV |
|--------|------|-----------|-----------|-------------|---------|
| Google Ads (non-brand) | 312 | 14% | 38% | 19% | $38,000 |
| Content/SEO | 189 | 31% | 52% | 28% | $52,000 |
| LinkedIn Ads | 156 | 22% | 45% | 24% | $49,000 |
| Webinars | 94 | 44% | 61% | 31% | $58,000 |
| Gated Whitepapers | 203 | 8% | 29% | 15% | $31,000 |

MQL threshold: 45 points. Email open +3, content download +10, webinar attend +20, demo request +35, pricing page +15, job title VP+ +10, company 201-500 +8.

Top SQL rejection reasons: "Not the right contact" (34%), "Too small / wrong segment" (28%), "No budget / early stage" (21%), "Competitor / not a fit" (17%).

Marketing budget allocation: Google Ads 40%, LinkedIn 25%, Content 20%, Webinars 10%, Other 5%.

---

**Output Example (excerpt):**

**Lead Quality Composite Score by Channel:**

| Channel | MQL→SQL | SQL→Opp | Opp→Close | ACV Index | LQS | vs. Budget Allocation |
|---------|---------|---------|-----------|-----------|-----|-----------------------|
| Webinars | 44% | 61% | 31% | 1.29 | **82.4** | Underinvested (10% budget) |
| Content/SEO | 31% | 52% | 28% | 1.16 | **71.2** | Slightly underinvested (20%) |
| LinkedIn Ads | 22% | 45% | 24% | 1.09 | **58.1** | Appropriately invested (25%) |
| Google Ads | 14% | 38% | 19% | 0.84 | **37.8** | **Massively overinvested (40%)** |
| Gated Whitepapers | 8% | 29% | 15% | 0.69 | **22.3** | **Volume trap — cut or restructure** |

**Business Impact of Lead Quality Gap:**
Google Ads generates 312 MQLs but only 8 close. Average ACV $38K. At 100% efficiency (matching webinar LQS), those 312 MQLs would yield ~26 deals = $988K additional closed-won revenue. The gap cost: **$760K in lost annual revenue from budget misallocation alone.**

**Immediate Fixes (30 days):**
1. Increase webinar MQL score from +20 to +30 (data shows 44% SQL rate vs. 14% for downloads)
2. Add "pricing page viewed" as required intent signal before Google Ads leads reach MQL threshold
3. Implement firmographic disqualification: auto-reject companies <50 employees (28% of rejections)
4. Redirect $80K/quarter from Google non-brand to webinar production (3 additional webinars/quarter)
5. Create SDR fast-lane for "demo request + high-fit score" leads: 15-minute response SLA

## Success Metrics

- MQL→SQL acceptance rate improves from baseline by 15%+ within 60 days of implementing new scoring
- Quality-adjusted CPL decreases across all channels within one quarter
- Marketing-sales SLA disputes drop (track in CRM: count of "no SLA violation" vs. "violation" dispositions)
- Revenue-per-MQL increases within 2 quarters across the lowest-LQS channels
- Sales team satisfaction with lead quality (measured via monthly NPS survey, target 7+/10)
- Time from MQL to first sales contact decreases to under 4 business hours for hot signals

## Related Prompts

- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [Demand Generation Waterfall & Pipeline Coverage Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Demand-Generation-Waterfall-&-Pipeline-Coverage-Intelligence-Engine.md)
- [Lead Scoring Automation](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md)
- [Marketing-Sales Revenue Alignment & SLA Engine](../../01_CMO-&-Leadership/Strategy-&-Planning/Marketing-Sales-Revenue-Alignment-&-SLA-Engine.md)

## Integration Tips

- **Salesforce:** Pull the MQL→SQL→Opp→Close funnel data using the "Lead Conversion Report" and "Opportunity Source" reports. Use Campaign Influence reporting to tie campaigns to revenue.
- **HubSpot:** Use the Funnel Report builder (Reports → Funnels) to generate stage-by-stage conversion by original source. Export to CSV and paste into the prompt.
- **Marketo:** Run the "Program Performance" report filtered by time period and lead source to extract campaign-level MQL data.
- **6sense / Bombora:** Overlay intent data scores onto your existing MQL population to identify which existing MQLs have in-market signals — prioritize those for immediate SDR follow-up.
- **Gong / Chorus:** Export call disposition data and objection themes to identify why SQLs stall. Feed this into the "funnel leak" section of the prompt.
- **Google Sheets / Notion:** Use the SLA scorecard output as a shared live doc reviewed weekly in marketing-sales sync meetings.
- **Zapier / Make:** Automate lead quality alerts — when a high-fit + high-intent lead hits MQL threshold, trigger a Slack notification to the AE assigned to that account.

## Troubleshooting

**Problem:** I don't have stage-by-stage conversion data broken down by channel — my CRM doesn't track lead source through the full funnel.

**Solution:** Use the Quick Version with estimated ranges if you have no data. Prioritize fixing the data problem: add "Original Lead Source" as a required field on Opportunity records in Salesforce/HubSpot. In the interim, survey your AEs on which channels they see as highest quality — their perception data is still useful as a proxy. The prompt will flag your data gaps and recommend which fields to start tracking.

---

**Problem:** Sales says "all marketing leads are bad" but won't give specific rejection data.

**Solution:** This is a process problem, not a data problem. Use the Advanced Version's SLA section to propose a 30-day "lead quality audit" where sales logs detailed rejection reasons on every MQL. Frame it as marketing wanting to help sales, not defend marketing. The prompt will generate a joint scorecard where both teams have accountability metrics — this defuses the political dynamic by making it bilateral.

---

**Problem:** My lead scoring model is new and I don't have enough historical conversion data to validate it.

**Solution:** Run the Quick Version with whatever data you have (even 30 days), focus on the "signals audit" section, and use the output to identify which data to collect going forward. Ask the prompt to generate a "minimum viable scoring model" based on your ICP definition alone if you have no behavioral data. Revisit the full analysis once you have 90 days of MQL-to-close data.

## Version History
- v1.0: Initial creation (auto-generated)
