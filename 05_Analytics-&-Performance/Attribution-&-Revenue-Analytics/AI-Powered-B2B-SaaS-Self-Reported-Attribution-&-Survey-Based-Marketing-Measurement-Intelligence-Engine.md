# AI-Powered B2B SaaS Self-Reported Attribution & Survey-Based Marketing Measurement Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** attribution, measurement, dark-social, survey, analytics, b2b, revenue-intelligence

## Overview
This prompt designs and operationalizes a self-reported attribution system — collecting "how did you hear about us?" data at every conversion point, triangulating it with digital analytics and CRM signals, and building a blended measurement framework that captures the dark social, word-of-mouth, and brand channels that multi-touch attribution models systematically miss. Use it when your attribution models undercount pipeline from channels like podcasts, community, LinkedIn, and executive thought leadership.

## Quick Copy-Paste Version

You are a B2B marketing analytics expert specializing in attribution modeling and measurement strategy.

I need to build a self-reported attribution program for [Company Name], a B2B SaaS company selling [product category] to [target buyer persona] at [company size] companies. Our ACV is [ACV range] and sales cycle is [sales cycle length].

We currently use [existing attribution tools/CRM] for digital attribution but suspect we're significantly undercounting pipeline from brand, community, podcast, and word-of-mouth channels.

Please design a complete self-reported attribution system including:

1. SURVEY ARCHITECTURE: Design "How did you hear about us?" micro-surveys for:
   - Demo/trial request confirmation pages
   - Post-signup onboarding flows
   - Sales discovery calls (questions for reps)
   - Customer success kickoff calls
   - Win/loss interview templates

2. RESPONSE TAXONOMY: Create a standardized channel taxonomy of 20-30 response options organized by category (paid, organic, community, word-of-mouth, events, analyst/press, direct) — specific enough to be actionable but simple enough for honest responses.

3. BIAS CORRECTION FRAMEWORK: Identify known biases in self-reported data (recency bias, recall bias, multi-touchpoint attribution) and define correction methodologies.

4. DATA INTEGRATION PROTOCOL: Specify how to capture, store, and join self-reported data with CRM records (field naming, deduplication logic, handling multi-select responses).

5. BLENDED MEASUREMENT MODEL: Define how to triangulate self-reported data with multi-touch attribution, sales call notes, and channel spend data to produce a confidence-weighted channel influence score.

6. REPORTING FRAMEWORK: Design a monthly self-reported attribution report for CMO/CFO, including: top acquisition channels by pipeline value, self-reported vs. MTA comparison table, channel-level CPL and CAC using self-reported data, and trend analysis.

7. INSIGHT ACTIVATION: How should self-reported data change budget allocation decisions? Provide a decision framework with thresholds.

Output as a structured implementation guide with templates, field specs, and reporting SQL logic where relevant.

## Advanced Customizable Version

## ROLE
You are a senior marketing analytics architect with deep expertise in B2B revenue attribution modeling, survey research methodology, and marketing measurement. You specialize in building measurement frameworks for companies where 40-60% of pipeline originates from unattributable dark social, word-of-mouth, and brand channels.

## CONTEXT
Company: [Company Name]
Product: [B2B SaaS product description]
Target Buyer: [Persona title, seniority, company size, industry]
ACV: [Average contract value]
Sales Cycle: [Average length, e.g., 45 days enterprise, 14 days SMB]
Current Headcount: [Marketing team size]
Current Attribution Stack: [Tools: HubSpot/Salesforce/Segment/Dreamdata/Bizly/Northbeam/etc.]
Top Suspected Blind Spots: [e.g., "We spend $200K/year on podcast ads but see zero tracked pipeline from podcasts"]
Data Warehouse: [Snowflake/BigQuery/Redshift/None]

## OBJECTIVE
Design a production-ready self-reported attribution (SRA) system that:
1. Captures authentic channel recall data at every buyer conversion point
2. Stores and joins data to CRM/revenue records without creating friction
3. Corrects for known survey biases using statistical methodology
4. Produces a triangulated "True Source" attribution model that blends SRA + MTA + conversation intelligence
5. Generates actionable channel investment decisions and CMO-level reporting

## DELIVERABLES

### MODULE 1: SURVEY DESIGN SPECIFICATIONS

**1A. Conversion-Point Survey Matrix**
For each conversion event, specify:
- Trigger: When survey fires (page load, form completion, X seconds after)
- Placement: Inline, modal, email, or conversation
- Question Phrasing: Exact question copy tested for non-leading language
- Response Format: Multi-select vs. single-select with write-in
- Required vs. Optional: Completion rate impact analysis
- Fallback Mechanism: What captures data if survey is skipped

Conversion Events to Cover:
- Demo/trial request: confirmation page survey
- Free trial activation: in-app onboarding step 1
- Sales discovery call: SDR/AE discovery question ("Before we dive in, how did you come across us?")
- Proposal stage: champion enablement survey
- Post-close: customer success kickoff structured question
- Lost deal: loss survey or sales debrief capture
- Review site conversion (G2/Capterra): review request touchpoint

**1B. Channel Taxonomy Design**
Create a 3-level taxonomy:
- Level 1: Category (Paid, Organic, Community, Referral, Events, Press/Analyst, Direct/Unknown)
- Level 2: Subcategory (Paid Search, Paid Social, Organic Search, LinkedIn Organic, Podcast, Newsletter, Customer Referral, Partner Referral, Industry Event, Trade Show, Tech Press, Analyst Report, etc.)
- Level 3: Specific Source (Google Ads, LinkedIn Ads, specific podcast name, specific newsletter, specific customer name)

Rules for taxonomy:
- Maximum 30 options at Level 2 to avoid choice paralysis
- Include "Multiple channels — it was cumulative" as a valid response
- Include "I don't remember" as an honest option (not "Other")
- Randomize order to prevent primacy bias in online surveys

**1C. Sales Conversation Discovery Protocol**
Train sales reps to capture self-reported attribution during discovery using:
- Non-leading phrasing: "Before we get started, I'm curious — what prompted you to reach out / accept this meeting today?"
- Follow-up probe: "And before that, how did you first become aware of [Company]?"
- CRM field: Specific dropdown + open text field with audio transcript clip

**1D. Customer Success Kickoff Protocol**
Design CS team questions for new customer onboarding:
- Phrasing that feels like relationship-building, not surveying
- Which CS call step to insert (typically call 1, during introductions)
- How to handle multi-stakeholder buying committees (capture for champion + economic buyer separately)

### MODULE 2: BIAS IDENTIFICATION & CORRECTION

**2A. Primary Biases in Self-Reported Attribution**
Document and quantify expected bias magnitude for each:

| Bias Type | Description | Expected Magnitude | Correction Method |
|-----------|-------------|-------------------|-------------------|
| Recency Bias | Last touchpoint over-credited vs. first awareness | High: overweights last 30 days | Compare with first-touch digital data |
| Salience Bias | Memorable/impressive channels over-credited (events, gifts) | Medium | Deflate by # of attendees or touchpoints |
| Social Desirability Bias | Respondents credit "smart" channels like thought leadership vs. actual cold email | Medium | Anonymous surveys reduce but don't eliminate |
| Recall Decay | Awareness from 6-12 months ago poorly recalled | High for long sales cycles | Incentivize early capture (post-signup vs. post-close) |
| Champion Bias | Champion attributes awareness to their own discovery vs. economic buyer's perspective | High for multi-stakeholder | Collect from multiple buying committee members |
| Multi-Touch Collapsing | Respondents simplify complex journeys into one answer | Very High | Allow multi-select + "cumulative" option |

**2B. Statistical Correction Protocol**
For each bias type:
- Correction factor calculation methodology
- Reference dataset requirements (minimum sample size before correction is valid)
- Confidence intervals for corrected figures
- When to apply corrections vs. report raw data

**2C. Triangulation Framework**
Define how to weight and blend three data sources:
- Self-Reported Attribution (SRA): 40% weight (adjusted for biases)
- Multi-Touch Digital Attribution (MTA): 35% weight (from marketing automation/CDP)
- Conversation Intelligence (CI): 25% weight (from Gong/Chorus call transcript analysis)

Specify triangulation logic:
- When sources agree: high-confidence attribution (>80% confidence score)
- When sources conflict: conflict resolution hierarchy and human review triggers
- When MTA shows nothing but SRA shows strong signal: dark social flag

### MODULE 3: DATA ARCHITECTURE

**3A. CRM Field Specifications (Salesforce/HubSpot)**

Lead/Contact Object:
- `Self_Reported_Source_L1__c` (Picklist: Category)
- `Self_Reported_Source_L2__c` (Picklist: Subcategory — dependent on L1)
- `Self_Reported_Source_L3__c` (Text: Specific source, write-in)
- `Self_Reported_Collection_Method__c` (Picklist: Web Survey, Sales Discovery, CS Kickoff, Win-Loss Interview)
- `Self_Reported_Collection_Date__c` (Date)
- `Self_Reported_Confidence__c` (Picklist: High/Medium/Low — based on survey completion and recency)
- `SRA_Triangulated_Source__c` (Formula: Blended source after triangulation logic)

Opportunity Object:
- `SRA_Economic_Buyer_Source__c` (Mirror of economic buyer's contact record)
- `SRA_Champion_Source__c` (Mirror of champion contact record)
- `SRA_Buying_Committee_Consensus__c` (Most common source across buying committee)

**3B. Data Pipeline Architecture**
Web Survey → Typeform/Jotform/HubSpot Form → Webhook → CRM Update
Sales Call → Gong transcript → AI extraction → CRM Update (via Zapier/native integration)
CS Call → Gong transcript → AI extraction → CRM Update
Win/Loss Interview → Notion/Salesforce → Manual entry workflow

**3C. Deduplication Logic**
Priority order when multiple SRA data points exist for one opportunity:
1. CS kickoff (closest to revenue, least decay)
2. Post-close win/loss (authentic reflection)
3. Sales discovery call (AE-captured, lower recall bias than web form)
4. Post-demo web survey (higher completion, higher recency bias)
5. Post-signup web survey (earliest capture, highest recall of true first awareness)

**3D. Multi-Stakeholder Aggregation**
For opportunities with 3+ contacts:
- Capture SRA from minimum: champion + economic buyer
- Store all responses individually
- Aggregate at opportunity level using weighted voting (economic buyer = 2x weight)

### MODULE 4: BLENDED MEASUREMENT MODEL

**4A. Channel Influence Score Calculation**
For each closed-won opportunity, calculate:

Channel_Influence_Score = 
  (SRA_Weight × SRA_Source_Score × SRA_Confidence_Factor)
  + (MTA_Weight × MTA_First_Touch_Score)
  + (MTA_Weight × MTA_Last_Touch_Score)  
  + (CI_Weight × Gong_Mention_Score)

Where:
- SRA_Weight = 0.40 (adjustable parameter)
- MTA_Weight = 0.35 (split between first/last touch)
- CI_Weight = 0.25
- Confidence_Factor = 0.9 (High), 0.7 (Medium), 0.5 (Low)

**4B. Channel Pipeline Value Attribution**
Monthly rollup:
- Sum `Channel_Influence_Score × Opportunity_ARR` per channel
- Compare to `Channel_Spend` for SRA-adjusted CAC
- Compare to MTA-only attribution to surface dark social delta

**4C. Dark Social Quantification**
Define "dark social pipeline":
- SRA shows channel signal + MTA shows no touchpoint in that channel = Dark Social Pipeline
- Target: quantify and report monthly (e.g., "38% of pipeline is dark social — primarily podcast + LinkedIn community")

### MODULE 5: REPORTING FRAMEWORK

**5A. Monthly CMO/CFO Attribution Report (Template)**

Section 1: Executive Summary (1 page)
- Total pipeline this month by blended attribution
- Top 3 channels driving pipeline (vs. last month)
- Dark social as % of total pipeline
- MTA vs. SRA divergence highlight ("MTA underreports podcast by 4.2x")

Section 2: Channel Performance Scorecard
| Channel | SRA Pipeline % | MTA Pipeline % | Delta | Spend | SRA CAC | MTA CAC | Recommendation |
|---------|---------------|---------------|-------|-------|---------|---------|----------------|

Section 3: Confidence Analysis
- High-confidence attributions (>75%): X% of pipeline
- Medium-confidence (50-75%): Y% 
- Low-confidence (<50%): Z% — requires investigation

Section 4: Trend Analysis
- 6-month rolling SRA by channel
- Emerging channels (SRA mentions growing >20% MoM)
- Declining channels (SRA mentions declining >15% MoM)

Section 5: Budget Reallocation Recommendations
- Over-invested channels (high MTA spend, low SRA signal)
- Under-invested channels (high SRA signal, low spend)
- Investment reallocation proposal with confidence level

**5B. SQL Queries for Data Warehouse**

Monthly SRA Pipeline by Channel:
SELECT 
  c.Self_Reported_Source_L2__c AS channel,
  COUNT(DISTINCT o.Id) AS opportunities,
  SUM(o.Amount) AS pipeline_value,
  AVG(o.SRA_Triangulated_Confidence__c) AS avg_confidence,
  SUM(o.Amount) / COUNT(DISTINCT o.Id) AS avg_deal_size
FROM Opportunities o
JOIN Contacts c ON o.Champion_Contact__c = c.Id
WHERE o.CloseDate >= DATEADD(month, -1, CURRENT_DATE)
  AND o.StageName = 'Closed Won'
GROUP BY c.Self_Reported_Source_L2__c
ORDER BY pipeline_value DESC;

MTA vs. SRA Divergence:
SELECT 
  channel,
  sra_pipeline_pct - mta_pipeline_pct AS attribution_delta,
  CASE 
    WHEN sra_pipeline_pct > mta_pipeline_pct * 2 THEN 'Significant Dark Social'
    WHEN sra_pipeline_pct > mta_pipeline_pct * 1.3 THEN 'Moderate Undercount'
    WHEN mta_pipeline_pct > sra_pipeline_pct * 1.5 THEN 'Possible MTA Inflation'
    ELSE 'Attribution Aligned'
  END AS divergence_signal
FROM channel_attribution_comparison
ORDER BY ABS(attribution_delta) DESC;

### MODULE 6: DECISION ACTIVATION FRAMEWORK

**6A. Budget Reallocation Triggers**
Define automated alerts for:
- Channel SRA > 15% of pipeline but receives <5% of budget: "Increase Investment" flag
- Channel SRA < 3% of pipeline but receives >15% of budget: "Reduce Investment" flag
- Channel SRA growing >25% MoM for 3+ consecutive months: "Scale" flag
- Channel SRA declining >20% MoM for 2+ consecutive months: "Investigation Required" flag

**6B. Minimum Sample Size Requirements**
Before acting on SRA data for a channel:
- For <$5M pipeline decisions: n=25 closed-won SRA responses per channel
- For $5-20M pipeline decisions: n=50 closed-won SRA responses per channel
- For >$20M pipeline decisions: n=100 + statistical significance test (p<0.05)

**6C. Leadership Presentation Framework**
When presenting SRA-based findings to board/CFO:
1. Lead with the gap: "Our MTA shows X% from [channel] but SRA shows Y% — a Z× undercount"
2. Explain the mechanism: why this channel doesn't get digital fingerprints
3. Show the math: pipeline value × correction factor × confidence interval
4. Make a specific ask: budget reallocation amount with expected ROI

## CONSTRAINTS
- All survey questions must be validated against non-leading language standards
- Data privacy: specify GDPR/CCPA-compliant data handling for survey responses
- Sales team buy-in: design for minimal rep friction (no more than 1 additional required CRM field per call)
- Minimum viable version: define 80/20 implementation that delivers 80% of value with 20% of effort
- Time-to-insight: prioritize getting first data within 30 days, refinement in 90 days

## OUTPUT FORMAT
Deliver as a complete implementation guide with:
1. 30-60-90 day rollout plan
2. Stakeholder RACI matrix (Marketing Ops, Sales Ops, CS Ops, BI/Analytics)
3. Vendor recommendations for each component
4. Change management talking points for sales and CS team buy-in
5. First 90-day reporting cadence

## Example Input/Output

**Input Example:**

Company: Contractual AI (AI-powered contract intelligence for legal teams)
Buyer: VP Legal / General Counsel at Series C-Enterprise companies
ACV: $85,000
Sales cycle: 60 days average
Current stack: HubSpot + Gong + Segment → Snowflake
Blind spot suspicion: "We've sponsored 6 legal tech podcasts for 8 months and see near-zero tracked attribution, but our sales team says deals constantly mention podcasts in discovery calls."

**Output Example (abbreviated):**

**Survey Architecture — Demo Request Confirmation Page:**

Question: "How did you first become aware of Contractual AI?"
Format: Single-select with write-in
Response Options (randomized):
1. Google / online search
2. LinkedIn post or ad
3. Podcast I listened to (which one? _____)
4. A colleague or peer recommended it
5. A law firm or consulting partner suggested it
6. I saw it mentioned in a legal tech newsletter (which one? _____)
7. At a legal industry conference or event
8. Through a legal tech analyst or report (Gartner, Forrester, Legal Tech News)
9. Direct outreach from the Contractual AI team
10. I've known about it for a while — cumulative exposure
11. I don't remember the first touchpoint

**Expected Finding (sample):**
After 90 days, SRA data reveals:
- 31% of closed-won deals cite "Podcast I listened to" (vs. 0% in HubSpot MTA)
- 22% cite "Colleague/peer recommended" (vs. 4% in MTA — from champion email trail)
- LinkedIn Ads: MTA shows 28%, SRA shows 11% — MTA inflation from last-click model

**Budget Recommendation Generated:**
"Podcast sponsorship is generating 31% of pipeline ($2.7M ARR) against 8% of budget ($160K). Current SRA CAC for podcast = $5,484 vs. overall CAC of $18,700. Recommend increasing podcast budget by $120K and reducing LinkedIn Ads spend by $80K (MTA inflation confirmed by SRA divergence)."

## Success Metrics

- **Survey Completion Rate:** Target >45% on confirmation page surveys, >70% on sales discovery captures
- **Coverage Rate:** % of closed-won deals with SRA data captured (target: >80% within 90 days of launch)
- **MTA-SRA Divergence Reduction:** After 6 months of budget reallocation based on SRA, MTA should better correlate with SRA (alignment improving = better investment)
- **Pipeline Attribution Coverage:** % of pipeline with high-confidence attribution (target: >70% by month 6)
- **Budget Reallocation Decisions:** Number of channel investment changes made using SRA data in first 6 months (leading indicator of impact)
- **CAC Improvement:** Blended CAC reduction after acting on SRA channel insights (target: 15-25% within 12 months)
- **Dark Social Quantification:** Successfully naming and sizing the dark social component of pipeline (even if not reducible to zero)

## Related Prompts

- [Dark Funnel Attribution & Anonymous Buyer Intent Intelligence Engine](./Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](./Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [AI-Powered B2B Revenue Attribution Model Architecture & Unified Measurement Framework Intelligence Engine](./AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md)
- [AI-Powered Marketing Mix Modeling & Media Investment Intelligence Engine](../Marketing-Mix-Modeling-&-Budget-Optimization/AI-Powered-Marketing-Mix-Modeling-&-Media-Investment-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Create a custom survey using HubSpot Forms on the thank-you page after every form submission. Map responses to Contact properties using workflow automation. Use HubSpot custom reports to pull SRA data into pipeline dashboards.
- **Salesforce:** Add SRA picklist fields to Lead, Contact, and Opportunity objects. Create a Process Builder flow to copy SRA data from Lead to converted Contact/Opportunity. Use Salesforce Analytics or Tableau CRM for blended reporting.
- **Gong:** Train Gong's AI tracker to flag "how did you hear" variations in call transcripts. Export flagged snippets via API to populate CRM SRA fields automatically. Use Gong's Deal Intelligence to identify accounts where SRA is captured vs. missing.
- **Typeform/Jotform:** For standalone post-demo surveys, use Typeform with Zapier integration to push responses to CRM. Enable Hidden Fields to pre-populate Company and Contact ID from URL parameters for automatic association.
- **Snowflake/BigQuery:** Store all SRA data in a dedicated `marketing.self_reported_attribution` table. Join to `salesforce.opportunities` on `contact_id` or `opportunity_id`. Schedule monthly blended attribution model refreshes using dbt.
- **Segment:** Capture web survey responses as Segment events (`survey_completed`, `survey_skipped`) with response properties. Route to data warehouse via Segment Connections. Enables cohort analysis of survey completion rates by traffic source.

## Troubleshooting

**Problem: Survey completion rates below 25% on confirmation pages**
Solution: The survey is appearing too early or feeling too lengthy. Implement a 5-second delay before the survey appears. Reduce to a single question with 8-10 options maximum. Test "Thank you + 1 quick question" phrasing. Add a social proof micro-copy: "This helps us improve our marketing — takes 15 seconds."

**Problem: Sales reps aren't consistently capturing "how did you hear about us" in discovery calls**
Solution: Don't rely on rep compliance — use Gong AI tracker instead. Create a Gong tracker for phrases like "how did you come across us," "what prompted you to reach out," "how did you hear about." This auto-flags and extracts responses from transcripts. Supplement with gamified leaderboard: show reps their SRA capture rate in weekly SDR/AE performance reviews, and tie to quota attainment review.

**Problem: SRA data conflicts wildly with MTA and leadership doesn't trust either**
Solution: This is expected during the first 90 days and is actually the point — the divergence is the finding. Present it as: "MTA is a trailing indicator of our last-click digital funnel. SRA is our best proxy for true first-awareness. Neither is the complete truth. Here's our triangulated model." Show 3 specific closed-won deal stories where MTA said 'direct' but SRA + Gong clearly showed podcast/community as first-awareness. Concrete case studies beat abstract models for leadership buy-in.

## Version History
- v1.0: Initial creation (auto-generated)
