# AI-Powered B2B SaaS Marketing Channel Pipeline Quality Attribution & Deal Conversion Prediction - Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** pipeline-quality, channel-attribution, deal-prediction, revenue-analytics, b2b-saas, marketing-ops, revenue-intelligence, forecasting, closed-won, pipeline-velocity

## Overview
Most B2B SaaS marketing teams measure pipeline quantity by channel — they know LinkedIn generated 40 opportunities last quarter. This prompt builds the next layer: which channels generate deals that actually *close*, at what conversion rate, deal size, and sales cycle length, so you can shift budget toward pipeline quality rather than pipeline volume. Use this when you notice your marketing-sourced pipeline isn't converting at the rate your CRO expects, when sales is complaining about lead quality, or when you need to defend or reallocate a marketing budget with revenue-quality evidence.

## Quick Copy-Paste Version

You are a senior marketing analytics strategist with deep expertise in B2B SaaS pipeline quality measurement and revenue attribution. You've built channel quality attribution systems at 20+ SaaS companies and you know exactly how to translate raw pipeline data into actionable channel investment decisions.

My company context:
- What we sell: [e.g., "AI-powered contract intelligence platform for enterprise legal and procurement teams"]
- Average ACV: [e.g., "$65,000"]
- Average sales cycle: [e.g., "90 days"]
- Primary marketing channels currently generating pipeline: [e.g., "LinkedIn Ads, SEO/organic content, webinars, field events, partner referrals, outbound SDR"]
- CRM: [e.g., "Salesforce"]
- Marketing automation: [e.g., "HubSpot / Marketo"]
- Current attribution model: [e.g., "First-touch / Last-touch / No formal model"]
- Biggest current pain: [e.g., "Sales says our MQLs are low quality but we can't prove which channels are actually producing closeable deals"]

Please build me:

1. CHANNEL QUALITY SCORECARD — For each of my marketing channels, define the 5 key quality metrics I should be tracking (beyond volume): stage conversion rates, average deal size by source, sales cycle length, win rate, and revenue-per-marketing-dollar. Give me the exact Salesforce/HubSpot report configurations to pull this data.

2. DEAL CONVERSION PREDICTION MODEL — A framework for predicting which pipeline deals are likely to close based on their marketing origin. What signals in the early funnel (lead source, content consumed, engagement velocity, ICP fit score) correlate most strongly with won deals? How do I build a simple predictive score without a data science team?

3. BUDGET REALLOCATION FRAMEWORK — Based on quality-adjusted pipeline data, how should I prioritize channels? Include a simple decision matrix: if Channel A generates 2x volume but 0.5x win rate vs. Channel B, which should get more budget?

4. BOARD-READY QUALITY METRICS NARRATIVE — Write a 3-paragraph CMO narrative explaining the shift from "pipeline volume" to "pipeline quality" reporting that I can use with my board and CRO.

5. IMPLEMENTATION ROADMAP — A 90-day plan to move from current state (volume tracking) to full quality attribution system.

Format this as a structured analytics framework I can implement in the next 30 days.

## Advanced Customizable Version

ROLE: You are a revenue analytics architect and B2B SaaS GTM strategist with 15+ years building pipeline quality measurement systems for high-growth SaaS companies. You've solved the "lead quality vs. quantity" debate for CMOs at companies from Series A through post-IPO. You understand Salesforce data modeling, attribution methodology limitations, and how to build credible quality metrics that sales and finance will trust — not just marketing will celebrate.

COMPANY CONTEXT:
- Company name: [Company Name]
- Product category: [e.g., "Enterprise data governance and compliance platform"]
- ICP definition:
  - Primary buyer: [e.g., "Chief Data Officer, VP Data Engineering, Chief Compliance Officer"]
  - Company profile: [e.g., "500-10,000 employees, Financial Services, Healthcare, and Retail verticals"]
  - Geographic focus: [e.g., "North America, EMEA"]
- Annual contract value range: $[low] - $[high] (average: $[X])
- Sales cycle: [X] days average (by segment if different: SMB [X] / Mid-market [X] / Enterprise [X])
- Win rate overall: [X]% (by segment if available)
- Current marketing channels generating pipeline:
  - [ ] Paid Search (Google/Microsoft Ads)
  - [ ] Paid Social (LinkedIn, Meta)
  - [ ] SEO / Organic Content
  - [ ] Webinars / Virtual Events
  - [ ] Field Events / Conferences
  - [ ] Partner / Channel Referrals
  - [ ] Outbound SDR (marketing-supported)
  - [ ] Customer Referrals
  - [ ] Direct / Dark Social (unattributed)
  - [ ] Other: [specify]
- CRM: [Salesforce / HubSpot / Other]
- MAP: [Marketo / HubSpot / Pardot / Other]
- Current attribution setup: [First-touch only / Last-touch only / Multi-touch / None / Custom]
- Data available: [What historical deal data do you have? Months of history, data completeness %]
- Primary audience for quality reporting: [CRO / CFO / Board / All three]
- Current pain point: [Most specific description of the quality vs. quantity tension you're experiencing]

OBJECTIVE: Design a comprehensive pipeline quality attribution system that attributes revenue conversion probability — not just revenue generated — to marketing channels, enabling confident budget reallocation decisions and credible quality reporting to executive stakeholders.

---

DELIVERABLE 1: CHANNEL QUALITY METRIC ARCHITECTURE

Design the complete quality metric framework for measuring each marketing channel's pipeline contribution. For each metric below, provide: the calculation formula, the data source in CRM/MAP, the report configuration, and the benchmark ranges for B2B SaaS.

**Tier 1 Quality Metrics (Revenue-Critical)**

METRIC 1 — CHANNEL WIN RATE
Formula: Won Opportunities / (Won + Lost Opportunities) by Lead Source (exclude open opps from denominator for trailing 12-month analysis)
Why it matters: The single most important pipeline quality indicator. A channel generating 40% win rate at $80K ACV is worth 3x more than a channel generating 15% win rate at $60K ACV even if volume is equal.
Salesforce report: Opportunity object → Group by Lead Source → Filter: Close Date within last 12 months AND Stage IN ('Closed Won', 'Closed Lost') → Measure: Count distinct opportunity, Sum of ARR

Calculate and present:
- Win rate by primary lead source
- Win rate by primary lead source × company segment (SMB / Mid-market / Enterprise)
- Win rate trend: Q1 vs. Q2 vs. Q3 vs. Q4 (is channel quality improving or degrading over time?)

METRIC 2 — CHANNEL-ADJUSTED AVERAGE DEAL SIZE (ADS)
Formula: Sum of Closed Won ARR / Count of Closed Won Opportunities by Lead Source
Why it matters: Volume metrics lie. A channel with 50% lower volume but 80% higher ADS may generate more revenue. Quality-adjusted pipeline = Volume × Win Rate × ADS.

Calculate:
- ADS by lead source
- ADS by lead source × ICP segment
- ADS percentile: Is this channel above or below your company-wide ADS benchmark?

METRIC 3 — CHANNEL SALES CYCLE LENGTH
Formula: Average days from Opportunity Create Date to Close Date (Won Opportunities only) by Lead Source
Why it matters: Two channels with equal win rates are not equal if one closes 40 days faster — that's cash flow, AE capacity, and compounding. A 30% faster sales cycle from Channel A means 30% more deals per AE per year.

Calculate:
- Median sales cycle by lead source (use median, not mean — outlier deals skew mean severely)
- Sales cycle by lead source × deal size band (< $25K / $25K-$75K / > $75K)
- Sales cycle trend: Is the channel accelerating or slowing over time?

METRIC 4 — MARKETING-SOURCED REVENUE CONTRIBUTION (MSRC)
Formula: Sum of Closed Won ARR where Lead Source = [channel] AND Marketing_Sourced = TRUE / Total Company ARR in Period
Why it matters: Separates pipeline quality from overall company performance. A channel may have declining MSRC not because quality dropped but because company ARR scaled. Track both absolute and relative.

Calculation note: You MUST define "marketing-sourced" consistently. Recommended definition: Any opportunity where marketing touched the account before Sales created the opportunity, regardless of who "owns" the sourcing credit. Use a Marketing_Sourced__c checkbox field, auto-set to TRUE when any Campaign Influence record exists for that opportunity.

METRIC 5 — REVENUE PER MARKETING DOLLAR (RPMD) BY CHANNEL
Formula: [Channel Closed Won ARR (trailing 12 months)] / [Channel Total Marketing Spend (trailing 12 months)]
Why it matters: This is the ultimate efficiency metric — it converts all quality factors (win rate, ADS, sales cycle) into a single dollar-return-per-dollar-invested comparison across channels.

Calculate RPMD for each channel and rank. Example output format:
| Channel | T12M Spend | T12M Win Rate | T12M ADS | T12M Won Deals | T12M Revenue | RPMD |
|---------|-----------|--------------|---------|----------------|-------------|------|
| SEO/Organic | $180K | 28% | $72K | 45 | $3.24M | $18.0 |
| LinkedIn Ads | $420K | 18% | $58K | 32 | $1.86M | $4.4 |
| Partner Referrals | $85K | 42% | $91K | 28 | $2.55M | $30.0 |
| Webinars | $160K | 24% | $64K | 18 | $1.15M | $7.2 |

**Tier 2 Quality Metrics (Diagnostic)**

METRIC 6 — STAGE CONVERSION WATERFALL BY CHANNEL
Track conversion rate at each pipeline stage (MQL → SQL → Opportunity → Commit → Closed Won) segmented by lead source. This reveals WHERE quality breaks down — some channels produce great SQLs but terrible mid-funnel conversion; others convert poorly from MQL to SQL but have high win rates once qualified.

Salesforce configuration: Create a funnel report that tracks Lead/Contact → Opportunity conversion by Lead Source, then Opportunity stage transitions using Stage History.

METRIC 7 — TIME-TO-FIRST-MEETING BY CHANNEL
Formula: Average days from Lead Create Date to first logged Meeting activity by Lead Source.
Why it matters: This is a leading indicator of pipeline quality — channels that produce buyers who respond quickly and book meetings fast signal higher intent and deal momentum. A 48-hour time-to-meeting vs. a 21-day time-to-meeting from the same channel volume signals dramatically different pipeline quality.

METRIC 8 — CHAMPION STRENGTH BY CHANNEL
Qualitative metric: For Closed Won deals by lead source, what % had an identified Champion (contact with MEDDPICC Champion score ≥ 3) in Salesforce/Gong? Channels that produce deals with strong internal champions close faster, at higher rates, and expand more. This requires conversation intelligence data (Gong, Chorus) or manual CRM field updates.

METRIC 9 — EXPANSION REVENUE CORRELATION BY CHANNEL
Formula: Net Revenue Retention (NRR) at 12-month mark segmented by original Lead Source at first purchase. The best acquisition channels don't just close deals — they bring customers who stay and grow. A channel with 85% win rate but 60% NRR is generating churn, not revenue.

---

DELIVERABLE 2: CHANNEL QUALITY PREDICTION FRAMEWORK (NO DATA SCIENCE TEAM REQUIRED)

Build a practical, spreadsheet-implementable lead quality prediction system using early-funnel signals to predict likelihood of deal closure before opportunity creation.

**The 5-Signal Quality Predictor**

This model assigns a Quality Score (0-100) to every MQL/SQL using five signals available in Salesforce + HubSpot/Marketo without any custom ML:

SIGNAL 1 — ICP FIRMOGRAPHIC FIT (Weight: 30%)
Score each lead/account on ICP alignment:
- Company size match: Perfect ICP range = 10pts / Adjacent range = 6pts / Outside ICP = 2pts
- Industry vertical match: Target vertical = 10pts / Adjacent = 5pts / Non-target = 1pt
- Buyer title match: Perfect title = 10pts / Influencer title = 6pts / Peripheral = 2pts

SIGNAL 2 — CONTENT ENGAGEMENT DEPTH (Weight: 25%)
Track content quality, not just quantity. Use HubSpot/Marketo engagement scoring but weight bottom-of-funnel content heavily:
- Viewed pricing page: +20 pts
- Downloaded competitive comparison content: +15 pts
- Attended product webinar (not just registered): +12 pts
- Read 3+ blog posts in one session: +8 pts
- Opened 5+ emails in last 30 days: +5 pts

SIGNAL 3 — ENGAGEMENT VELOCITY (Weight: 20%)
Time from first touch to current engagement. Buyers who accelerate their research tempo are 2.3x more likely to convert within 90 days (SiriusDecisions benchmark):
- 3+ content engagements in last 7 days: +20 pts
- Returned to site within 72 hours of last visit: +15 pts
- Opened email within 1 hour of send: +10 pts
- No engagement in 30+ days: 0 pts (negative signal — consider suppressing from lead scoring)

SIGNAL 4 — INTENT DATA OVERLAY (Weight: 15%)
If you have intent data (Bombora, G2, 6sense):
- Active surge on your category (score 150+): +15 pts
- Viewed competitor profiles on G2 in last 30 days: +12 pts
- No intent signal: +0 pts

SIGNAL 5 — ACCOUNT PROXIMITY SIGNALS (Weight: 10%)
- Mutual technology stack overlap (Crossbeam/Reveal partner customer overlap): +10 pts
- Existing customer referral in same account: +8 pts
- First-degree LinkedIn connection to your AE or leadership: +5 pts
- Has existing relationship logged in Salesforce: +4 pts

**Quality Score Interpretation:**
- 80-100: Priority 1 — Alert SDR immediately, personal outreach within 2 hours
- 60-79: Priority 2 — Enroll in high-touch sequence, SDR contact within 24 hours
- 40-59: Priority 3 — Marketing nurture sequence, SDR contact within 5 business days
- < 40: Priority 4 — Automated nurture only, revisit if score increases

**Calibration Protocol:**
Run this scoring model retroactively on your last 12 months of won/lost deals. The model is properly calibrated when Priority 1 leads have >35% win rate vs. <10% win rate for Priority 4 leads. If the spread is less than 3:1, adjust signal weights.

---

DELIVERABLE 3: CHANNEL BUDGET REALLOCATION DECISION MATRIX

Build a structured framework for reallocating marketing budget from volume-generating channels to quality-generating channels.

**Step 1: Build the Channel Quality Index (CQI)**

The Channel Quality Index normalizes each channel's performance into a single 0-100 score:

CQI Formula: (Win Rate Score × 35%) + (ADS Score × 25%) + (Sales Cycle Score × 20%) + (RPMD Score × 20%)

Where each component score = (Channel metric / Best-performing channel metric) × 100

Example: If Partner Referrals has 42% win rate and it's the highest win rate channel, it gets a Win Rate Score of 100. If LinkedIn Ads has 18% win rate, it gets (18/42) × 100 = 42.9 on that component.

**Step 2: Reallocation Decision Rules**

Apply the following rules sequentially:

RULE 1 — CUT rule: Any channel with CQI < 35 AND volume < 10% of total pipeline receives a budget reduction of minimum 40% in next quarter. Exception: if channel is the only source for a specific market segment or geography.

RULE 2 — HOLD rule: Any channel with CQI 35-60 maintains current budget but requires a performance improvement plan: identify the one metric dragging the CQI lowest and assign a 60-day improvement test (e.g., if sales cycle is the weak metric, test adding a mid-funnel acceleration campaign for leads from this channel).

RULE 3 — GROW rule: Any channel with CQI > 60 AND RPMD > $10 receives incremental budget. Start with 20% increase and re-measure CQI quarterly.

RULE 4 — INVESTIGATE rule: Any channel with CQI > 70 AND volume < 5% of total pipeline is likely underfunded relative to its quality. Model: if you tripled this channel's investment, what incremental revenue would you expect?

**Step 3: Reallocation Impact Model**

Before executing reallocation, build a simple impact model:

Current state: Channel A ($300K spend, CQI 45, $8M pipeline generated, $1.4M closed won)
Proposed: Reduce Channel A by $100K → reduce pipeline by 33% = $2.67M pipeline reduction → $467K closed won reduction

Reinvest $100K in Channel B ($180K spend, CQI 78, $5.4M pipeline generated, $2.7M closed won at $15 RPMD)
Projected impact: $100K × $15 RPMD = $1.5M additional closed won

Net gain from reallocation: $1.5M - $467K = $1.03M incremental ARR

**Step 4: Risk-Adjusted Reallocation**

Apply a conservatism discount: scale-up isn't always linear. For channels with high CQI but unproven at higher volumes, apply a 50% efficiency discount on the incremental projection. If $100K additional in Channel B is projected to produce $1.5M, assume $750K until you've validated the channel scales efficiently.

---

DELIVERABLE 4: MARKETING-SALES PIPELINE QUALITY SLA

Define a formal marketing-sales quality SLA that moves the conversation from "your leads are bad" to "here's our shared quality definition and the data behind it."

**SLA Structure:**

DEFINITION — Marketing commits to generating pipeline that meets these minimum quality thresholds (measured quarterly by channel):
- Win rate of marketing-sourced opportunities: ≥ [X]% (benchmark: 20% for enterprise, 25% for mid-market, 30% for velocity/SMB)
- Average deal size from marketing-sourced opportunities: ≥ [X]% of company-wide average ADS
- Stage 2→Stage 3 conversion rate (qualification → discovery complete): ≥ [X]%
- Lead-to-meeting rate from marketing-sourced MQLs: ≥ [X]% within 5 business days of handoff

MEASUREMENT — Quality is measured jointly (not by marketing alone) using a shared Salesforce dashboard that both VP Marketing and CRO can access. Metrics auto-update daily.

REVIEW CADENCE — Quality SLA review happens monthly at the Marketing-Sales sync. If any metric drops below threshold, a joint root cause analysis is conducted within 2 weeks and a remediation plan is agreed upon.

CONSEQUENCE — If quality metrics are below SLA for 2 consecutive quarters despite remediation, marketing agrees to reduce volume target and shift budget to channels demonstrating better quality performance.

**SLA Monitoring Dashboard (Salesforce/HubSpot):**

Build a 6-metric dashboard visible to both marketing and sales:
1. MTD marketing-sourced opportunities created (vs. goal)
2. Win rate of marketing-sourced opportunities (vs. SLA threshold)
3. Average ADS from marketing-sourced pipeline (vs. company ADS benchmark)
4. Stage conversion rate: MQL → SQL → Opportunity (vs. SLA threshold)
5. Sales cycle of marketing-sourced deals (vs. company average)
6. RPMD by channel (trending view, trailing 3 months)

---

DELIVERABLE 5: 90-DAY PIPELINE QUALITY TRANSFORMATION ROADMAP

**Month 1: Data Foundation (Days 1-30)**

Week 1: CRM data audit
- Run a data quality assessment on your Salesforce Opportunity object: what % of Closed Won/Lost records have Lead Source populated? If <80%, you cannot run reliable quality attribution. Launch a data backfill project — use marketing automation activity data, campaign influence records, and UTM parameters to retroactively assign lead source to legacy records.
- Map all existing lead source values to standardized channel taxonomy. Most CRMs have 15-30 messy lead source values ("Web," "Website," "Online," "Inbound Web"). Consolidate into 8-12 clean channel categories using a Salesforce picklist update + bulk field update.

Week 2: Metric instrumentation
- Build the 5 Tier 1 quality metrics as Salesforce reports. Save all in a shared "Pipeline Quality" report folder accessible to CRO and VP Sales.
- Implement Quality Score fields on Lead/Contact object in Salesforce. Connect HubSpot scoring logic to auto-populate Salesforce custom fields via API or native sync.

Week 3: Historical baseline
- Run the CQI model retroactively on 12 months of historical Closed Won/Lost data.
- Produce the first Channel Quality Scorecard showing current-state CQI rankings.

Week 4: Stakeholder alignment
- Present initial findings to CRO and VP Sales. This is NOT a budget ask — it's a "here's what the data shows" conversation. Seek alignment on the quality metrics definition before proposing any budget changes.

**Month 2: Calibration and Testing (Days 31-60)**

- Validate Quality Score model against historical outcomes (calibration protocol from Deliverable 2)
- Run the reallocation decision matrix — identify top 2 channels for budget increase, top 1 for reduction
- Build the Marketing-Sales Pipeline Quality SLA (draft) and negotiate thresholds with CRO/VP Sales
- Launch the pilot: shift 10% of budget from lowest-CQI channel to highest-CQI channel as a 60-day test

**Month 3: Operational Excellence (Days 61-90)**

- Implement the 6-metric quality dashboard in Salesforce (both teams have access)
- Sign the Marketing-Sales Quality SLA
- Execute full reallocation based on 60-day pilot results + historical analysis
- Produce first Board-ready pipeline quality report (see Deliverable 4 narrative)
- Set quarterly CQI review cadence with automated Salesforce dashboards refreshing weekly

---

## Example Input/Output

**Input Example:**

Company: Meridian GRC (fictional)
Product: Governance, Risk & Compliance (GRC) platform for mid-market financial services
ICP: Chief Compliance Officer, VP Risk, General Counsel at 200-2,000 employee financial services firms
ACV: $45,000 average ($28K SMB - $90K Enterprise)
Sales cycle: 75 days average
Win rate: 22% overall
Channels: LinkedIn Ads, Google Ads, SEO/organic, sponsored industry webinars, financial services conferences, partner referrals (Big 4 accounting firms)
CRM: Salesforce; MAP: HubSpot
Current pain: "Sales says our LinkedIn leads are garbage — but we can't prove it with data. We think partner referrals are high quality but we're only spending $40K there vs $280K on LinkedIn."

---

**Output Example (Excerpted):**

### CHANNEL QUALITY SCORECARD — MERIDIAN GRC (Q1-Q3 Analysis)

| Channel | T9M Spend | Win Rate | ADS | Med. Sales Cycle | RPMD | CQI |
|---------|----------|----------|-----|-----------------|------|-----|
| Partner Referrals (Big 4) | $40K | 51% | $78K | 48 days | $71.1 | 94 |
| Industry Conferences | $180K | 31% | $62K | 71 days | $16.8 | 67 |
| SEO/Organic | $90K | 27% | $54K | 82 days | $10.8 | 52 |
| LinkedIn Ads | $280K | 14% | $41K | 91 days | $4.4 | 31 |
| Google Ads | $120K | 19% | $44K | 85 days | $5.5 | 38 |
| Sponsored Webinars | $65K | 22% | $38K | 95 days | $5.2 | 35 |

**Analysis:**

Partner Referrals (CQI 94) is dramatically outperforming every other channel — 51% win rate vs. the company-average 22%, $78K ADS vs. $45K company average, and 48-day sales cycle vs. 75-day company average. At $71.1 RPMD, every $1 invested in Big 4 referral relationships returns $71 in closed revenue.

The finding on LinkedIn (CQI 31) validates sales' complaint — but the data is more nuanced. LinkedIn is generating volume at 14% win rate and $4.4 RPMD. The problem isn't LinkedIn as a platform; it's that the audience and offer haven't been calibrated to produce ICP-fit buyers. LinkedIn's ADS of $41K is 9% below company average, suggesting it's attracting smaller, less qualified companies.

**Immediate Reallocation Recommendation:**

Shift $120K from LinkedIn Ads (reduce from $280K to $160K) → reinvest:
- $80K into Partner Referral program (increase from $40K to $120K — double investment in highest-CQI channel)
- $40K into expanding financial services conference presence

Projected impact:
- LinkedIn reduction: -$120K × $4.4 RPMD = -$528K revenue (likely)
- Partner Referral increase: +$80K × $71.1 RPMD × 50% conservatism factor = +$2.84M revenue (projected)
- Net gain: +$2.31M ARR from reallocation alone

**LinkedIn Improvement Plan (before cutting further):**
Run a 60-day test with LinkedIn creative and audience changes targeting: Chief Compliance Officers only (exclude VP/Director level to filter budget authority), Financial Services industry filter ON, company size 500-5,000 only. If win rate doesn't improve to 20%+ within 60 days, reduce LinkedIn budget a further $80K in Q2.

### QUALITY PREDICTION MODEL OUTPUT (Sample Leads)

Lead A: CCO at 800-person insurance company, viewed pricing page, attended product webinar, G2 surge on "GRC" category, Deloitte mutual customer (partner overlap)
Quality Score: 88 → Priority 1 — SDR contact within 2 hours

Lead B: VP Compliance at 45-person startup, downloaded one blog post, no intent data
Quality Score: 24 → Priority 4 — Automated nurture only

Lead C: General Counsel at 400-person bank, opened 4 emails, visited pricing page twice, no intent data but LinkedIn showed job change 30 days ago (buying trigger)
Quality Score: 71 → Priority 2 — High-touch sequence, SDR contact within 24 hours

---

## Success Metrics

- **CQI improvement trajectory**: Best-performing channels should maintain CQI > 60 every quarter; if a channel's CQI drops below 40 for two consecutive quarters, it triggers an automatic budget review
- **Win rate spread**: After 90 days of Quality Score implementation, Priority 1 leads should convert at 3x+ the rate of Priority 4 leads — confirm through Salesforce cohort analysis
- **RPMD improvement**: 12 months after implementing the reallocation framework, blended company RPMD should improve by minimum 25% — this is the primary financial outcome
- **Sales satisfaction score**: Conduct quarterly survey with VP Sales and top 5 AEs rating marketing lead quality on a 1-10 scale; target improvement from baseline by +2 points within 12 months
- **Pipeline quality SLA compliance**: 80%+ of quality SLA metrics met in consecutive quarters within 6 months of implementation
- **Budget efficiency**: Same or higher revenue with 10-20% lower marketing spend — the quality attribution system should enable budget efficiency, not just reallocation

## Related Prompts

- [`AI-Powered-B2B-SaaS-Marketing-Pipeline-Quality-Scoring-&-Deal-Health-Revenue-Intelligence-Engine.md`](./AI-Powered-B2B-SaaS-Marketing-Pipeline-Quality-Scoring-&-Deal-Health-Revenue-Intelligence-Engine.md) — Individual deal health scoring; complements channel-level quality attribution
- [`AI-Powered-B2B-SaaS-Pipeline-Velocity-Analytics-&-Marketing-Led-Deal-Acceleration-Revenue-Intelligence-Engine.md`](./AI-Powered-B2B-SaaS-Pipeline-Velocity-Analytics-&-Marketing-Led-Deal-Acceleration-Revenue-Intelligence-Engine.md) — Accelerating deals already in pipeline, once you've improved channel quality
- [`../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Program-Portfolio-Management-&-Autonomous-Revenue-Program-Optimization-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Demand-Generation-Operations/AI-Powered-B2B-SaaS-Demand-Generation-Program-Portfolio-Management-&-Autonomous-Revenue-Program-Optimization-Intelligence-Engine.md) — Broader demand gen program portfolio management
- [`../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-Marketing-Attribution-Audit-&-Revenue-Proof-of-Contribution-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Reporting-&-ROI/AI-Powered-B2B-Marketing-Attribution-Audit-&-Revenue-Proof-of-Contribution-Intelligence-Engine.md) — Board-level attribution reporting after you've built quality metrics

## Integration Tips

- **Salesforce**: Create a custom field `Channel_Quality_Index__c` on the Campaign object, updated quarterly via a scheduled flow. Build a "Pipeline Quality Command Center" dashboard with 6 custom report charts — one for each Tier 1 quality metric — shared with Marketing, Sales, and Finance. Set up a Salesforce Einstein Activity Capture rule to auto-tag opportunities created within 30 days of specific campaign types.
- **HubSpot**: Build the 5-signal Quality Score as a Contact Score property using HubSpot's scoring tool. Set up Workflows to push the score to Salesforce's Lead_Quality_Score__c field via native sync. Create a HubSpot List "Priority 1 Quality Score" (score ≥ 80) that auto-enrolls in an "Immediate SDR Alert" workflow triggering a Slack notification to the assigned SDR.
- **Gong / Chorus**: Pull "Champion Presence" data by filtering call recordings for mentions of champion indicators ("my sponsor is," "executive sponsor," "champion internally") and building a Salesforce field `Champion_Identified__c` auto-populated when Gong detects champion language in an opportunity call within the first 30 days.
- **Google Looker Studio / Tableau**: Build the Channel Quality Scorecard as a live dashboard connecting to Salesforce data. Auto-refresh weekly. Share the dashboard link in the #marketing-analytics Slack channel every Monday morning with a brief commentary on the prior week's CQI changes.
- **Marketo / Pardot**: If on Marketo, build the Quality Score using Advanced Lead Scoring with separate score fields per signal. Use Smart Campaigns to auto-trigger SDR notifications in Salesloft/Outreach when a lead crosses the Priority 1 threshold. In Pardot, use Engagement Studio to build parallel tracks based on Quality Score tier.
- **Crossbeam / Reveal**: Sync partner overlap data to Salesforce weekly. Map partner customers to a `Partner_Overlap__c` lookup field on Account. Build a custom trigger: when an Account has Partner_Overlap__c populated AND an open Opportunity, alert the Partnership Manager via Slack to activate a co-sell motion. This partner signal should auto-add 10 points to the quality score.

## Troubleshooting

**Problem**: Lead Source data is populated in less than 60% of Salesforce Opportunity records — the quality attribution analysis produces unreliable results because too much pipeline is labeled "Unknown" or blank.
**Solution**: This is the #1 data quality failure in CRM systems. Fix it in two phases: (1) Future state — mandate Lead Source as a required field on Opportunity creation using a Salesforce validation rule: `AND(ISNEW(), ISBLANK(LeadSource))`. Add Lead Source to the opportunity creation page layout with a picklist that sales cannot bypass. (2) Historical backfill — write a Salesforce report that exports all Opportunities with blank Lead Source, then use HubSpot Campaign Influence records, Marketo Program association, UTM parameters from web forms, or Google Analytics session data to retroactively assign lead source. Accept that 15-25% of historical records may be unresolvable — assign these to a "Direct/Unknown" bucket rather than leaving them blank. Run quality attribution only on records with Lead Source populated and exclude "Unknown" from the denominator to avoid diluting channel-specific metrics.

**Problem**: Sales team doesn't trust the Channel Quality Index and dismisses the reallocation recommendation — they believe the quality problem is in sales execution, not marketing channel quality.
**Solution**: This is a politics problem, not a data problem — and it's best solved with collaborative data exploration, not a marketing-only report. Request a 90-minute joint working session with the CRO and top 3 AEs where you walk through the quality data together. Start with a channel they *agree* is high quality (usually partner referrals or customer referrals) and show the data confirming it. Then transition to the underperforming channels using the same data model. Ask the sales team to hypothesize why the quality differs — often they'll surface insights you don't have (e.g., "LinkedIn leads are always from companies too small to afford us because of how we're targeting" or "Google Ads leads ask about the wrong features"). Convert the conversation from "marketing channel quality" to "what would a high-quality lead look like so we can reverse engineer the channel settings to produce more of them."

**Problem**: After 90 days of budget reallocation toward higher-CQI channels, win rate has improved but total pipeline volume has dropped significantly — the CRO is alarmed about pipeline coverage despite quality improvement.
**Solution**: This is the quality-quantity trade-off tension, and it's real. First, validate the actual revenue impact: if win rate went from 20% to 28% and ADS held steady but volume dropped 25%, net revenue is actually higher (28% × 75% volume vs. 20% × 100% volume = 21% vs. 20% net revenue — even with volume reduction, revenue output improves). Second, if the coverage concern is legitimate (pipeline is genuinely short of the 3x coverage target), use the RPMD improvement to justify incremental budget investment in the high-CQI channels rather than reverting to high-volume / low-quality channels. Third, consider a hybrid approach: maintain a "reach" channel (like LinkedIn at reduced budget) that sustains volume while the high-quality channels scale. The goal is never to sacrifice coverage entirely — it's to improve the quality of every pipeline dollar.

## Version History
- v1.0: Initial creation (auto-generated)
