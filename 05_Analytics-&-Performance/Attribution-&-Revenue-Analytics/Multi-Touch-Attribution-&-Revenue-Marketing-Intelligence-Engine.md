# Multi-Touch Attribution & Revenue Marketing Intelligence Engine - Prove Marketing's True Revenue Impact

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, analytics, attribution, revenue, automation, saas, reporting

## Overview
Automatically constructs a full multi-touch attribution model from your CRM and marketing data, maps every channel's contribution to closed-won revenue, and generates an executive-ready report with budget reallocation recommendations. Use this when your CFO asks "what is marketing actually driving?" or when planning quarterly budget reviews.

## Quick Copy-Paste Version

You are a senior marketing analytics consultant. I need you to build a complete multi-touch attribution analysis and revenue impact report.

Here is my marketing and CRM data summary:
- Channels used: [list channels: Google Ads, LinkedIn, Email, Content, Events, etc.]
- Time period: [e.g., Q1 2025, last 90 days]
- Total closed-won deals: [number]
- Total revenue: [$X]
- Marketing-sourced pipeline: [$X]
- Marketing-influenced pipeline: [$X]
- Top 5 deal sizes: [$X, $X, $X, $X, $X]
- Average sales cycle: [X days]
- Touch point data (paste your raw data or describe it): [your data]

Please deliver:
1. Multi-touch attribution model comparison (First Touch, Last Touch, Linear, Time-Decay, U-Shaped, W-Shaped) with a recommendation for which model best fits my business
2. Revenue attribution by channel with % contribution
3. Cost per opportunity and cost per closed-won deal by channel
4. ROI by channel (revenue attributed / spend)
5. Top 3 underinvested channels based on ROI efficiency
6. Top 3 overinvested channels with diminishing returns
7. Recommended budget reallocation (show current vs. recommended allocation as a table)
8. 90-day action plan to improve attribution accuracy
9. Executive summary paragraph for board presentation

Use data-driven reasoning. Flag any data quality issues you identify. Format as a structured report with tables where appropriate.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Analytics with 15 years of B2B SaaS experience, specializing in multi-touch attribution modeling, marketing mix optimization, and revenue operations. You have deep expertise in Salesforce, HubSpot, Marketo, Google Analytics 4, and Tableau.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Series A/B/C/Public/SMB/Enterprise]
- ARR: [$X]
- ACV: [$X average contract value]
- Sales cycle length: [X days average]
- Buyer committee size: [X stakeholders typical]
- Primary ICP: [job titles, company sizes, industries]
- Sales motion: [Inbound/Outbound/Product-Led/Channel]

MARKETING CHANNELS IN SCOPE:
Paid: [Google Ads / LinkedIn Ads / Meta / Display / Retargeting]
Organic: [SEO/Blog / Organic Social / YouTube]
Demand Gen: [Webinars / Events / Content Syndication / Intent Data]
Outbound: [Cold Email / SDR Sequences / Direct Mail]
Partnerships: [Channel Partners / Alliances / Affiliate]
Product: [Free Trial / Freemium / PLG Viral Loops]

RAW DATA (paste or describe):
- CRM pipeline data: [deals, stages, sources, close dates, ARR]
- Marketing touch point log: [campaign name, channel, date, contact, account]
- Marketing spend by channel: [channel, monthly spend, Q total]
- Website analytics: [sessions, conversions, by source/medium]
- Lead/MQL volume by source: [source, volume, MQL rate]

ANALYTICAL FRAMEWORK:
Apply ALL of the following attribution models and compare outputs:
1. First Touch: 100% credit to first marketing interaction
2. Last Touch: 100% credit to last marketing interaction before opportunity creation
3. Linear: Equal credit across all touches
4. Time Decay: More credit to recent touches (half-life: 7 days)
5. U-Shaped (Position-Based): 40% first touch, 40% opportunity creation touch, 20% distributed across middle
6. W-Shaped: 30% first touch, 30% lead creation, 30% opportunity creation, 10% distributed
7. Custom Data-Driven: Weight touches based on observed conversion lift at each stage in my data (if sufficient data)

ANALYSIS REQUIRED:

**Section 1: Attribution Model Comparison Matrix**
Create a table showing revenue attributed to each channel under each model. Highlight where models diverge significantly (>20% variance) — these are your most contested channels requiring additional analysis.

**Section 2: Channel Performance Scorecard**
For each channel, calculate:
- Total touches (awareness, consideration, decision)
- Pipeline influenced ($) and pipeline sourced ($)
- Revenue attributed (use recommended model)
- Total spend in period
- Cost per MQL
- Cost per opportunity
- Cost per closed-won
- Pipeline ROI (pipeline / spend)
- Revenue ROI (revenue / spend)
- Velocity contribution (does this channel accelerate or slow deal cycles?)
- Score: A/B/C/D based on composite efficiency

**Section 3: Funnel Analysis by Channel**
Map conversion rates at each stage:
- Impression/Visit → Lead
- Lead → MQL
- MQL → SAL/SQL
- SQL → Opportunity
- Opportunity → Closed-Won
Identify the biggest drop-off points per channel. Flag channels with high top-of-funnel volume but poor close rates (potential quality issues).

**Section 4: Cohort & Seasonality Analysis**
- Compare attribution patterns across monthly cohorts in the time period
- Identify seasonal patterns in channel effectiveness
- Flag any anomalies (spike/drops >30% vs. trend)

**Section 5: Budget Optimization Recommendations**
Using marginal ROI analysis:
- Calculate current budget allocation %
- Identify channels operating below/above efficiency threshold
- Model 3 budget scenarios: Conservative (+10% total budget), Moderate (flat budget reallocation), Aggressive (-15% budget with reallocation)
- For each scenario, project: expected pipeline, expected revenue, expected ROI
- Show a "steal from X, invest in Y" table with projected impact

**Section 6: Attribution Data Quality Audit**
Flag:
- Channels with >15% "direct/none" source attribution (dark funnel leakage)
- Incomplete touch logs (deals with <3 touches in a 90+ day cycle)
- UTM parameter coverage gaps
- CRM field hygiene issues affecting attribution
- Offline touch points not being tracked (events, calls, referrals)

**Section 7: Dark Funnel & Untracked Influence**
Estimate the volume of untracked influence from:
- LinkedIn organic (no UTMs)
- Word-of-mouth / referral (not in CRM source)
- Review sites (G2, Capterra — buyer research you can't see)
- Executive network effects
- Community participation
Recommend instrumentation to capture these signals (e.g., "How did you hear about us?" survey, LinkedIn matched audiences, G2 buyer intent).

**Section 8: 90-Day Attribution Improvement Roadmap**
Prioritize 10 specific actions to improve attribution accuracy and coverage:
- Each action: What to do, which tool/system, expected impact on data completeness, effort (Low/Med/High)

**OUTPUT FORMAT:**
- Executive Summary (200 words, board-ready)
- Full analysis with labeled sections and subsections
- All recommendations in tables where possible
- Channel scorecard as sortable table (A-D grades)
- Budget reallocation table (current vs. scenario 1/2/3)
- Risk flags highlighted in bold
- Final recommendation: which attribution model to standardize on and why

CONSTRAINTS:
- Do not recommend vanity metrics (impressions, clicks) as primary KPIs — focus on pipeline and revenue
- All ROI calculations must show formula and data inputs
- Where data is insufficient, state assumptions explicitly and show sensitivity analysis
- Recommendations must be implementable in HubSpot, Salesforce, or GA4 without custom engineering (unless flagged as "Requires Engineering")

## Example Input/Output

**Input Example:**

Company: NexusIQ (B2B SaaS, Series B, $8M ARR, $45K ACV)
Period: Q4 2024 (Oct–Dec)
Closed-won: 48 deals, $2.16M new ARR
Channels: Google Ads ($45K spend), LinkedIn Ads ($62K spend), Webinars ($18K), Content/SEO ($8K), SDR Outbound ($85K fully-loaded), Events ($30K)
Pipeline sourced (marketing): $6.8M
Average sales cycle: 67 days

Touch data highlights:
- Google Ads: 1,840 clicks, 94 leads, 31 MQLs, 8 opps, 4 closed
- LinkedIn Ads: 3,200 clicks, 67 leads, 48 MQLs, 19 opps, 11 closed
- Webinar attendees: 430, 89 leads, 52 MQLs, 22 opps, 14 closed
- Blog/SEO: 12,400 sessions, 44 leads, 18 MQLs, 9 opps, 6 closed
- SDR Outbound: 2,100 sequences, 210 meetings, 87 MQLs, 41 opps, 11 closed
- Events: 1 tradeshow, 140 contacts, 28 MQLs, 16 opps, 2 closed

---

**Output Example (abbreviated):**

**EXECUTIVE SUMMARY**
In Q4 2024, NexusIQ's marketing investment of $248K drove $2.16M in closed-won ARR and $6.8M in sourced pipeline — a blended pipeline ROI of 27x. Webinars emerged as the highest-efficiency channel at $1,286 cost-per-closed-won vs. the $5,159 portfolio average. LinkedIn Ads delivered the highest volume but at 2.4x the cost efficiency of webinars. Google Ads shows significant funnel leakage at the SQL→Close stage (50% close rate vs. 73% portfolio average), suggesting lead quality issues. Recommended reallocation: shift $20K from Google Ads into Webinar production and LinkedIn Thought Leadership, projecting $420K additional pipeline in Q1 2025.

**Channel Scorecard (W-Shaped Attribution)**

| Channel | Spend | Opps | CW Deals | Revenue Attr. | Pipeline ROI | Rev. ROI | Grade |
|---------|-------|------|----------|---------------|--------------|----------|-------|
| Webinars | $18K | 22 | 14 | $432K | 48x | 24x | A |
| LinkedIn Ads | $62K | 19 | 11 | $378K | 19x | 6.1x | B+ |
| Blog/SEO | $8K | 9 | 6 | $198K | 52x | 24.8x | A |
| SDR Outbound | $85K | 41 | 11 | $324K | 11x | 3.8x | B- |
| Google Ads | $45K | 8 | 4 | $108K | 8x | 2.4x | C |
| Events | $30K | 16 | 2 | $54K | 4x | 1.8x | D |

**Top Recommendation:** Reallocate $20K from Events → Webinar (2 additional webinars/quarter). Projected impact: +14 opportunities, +$420K pipeline.

## Success Metrics

- Attribution model covers ≥85% of closed-won revenue with traceable touch history
- Channel scorecards show ROI variance of <15% between recommended model and data-driven model (validates model choice)
- Budget reallocation scenarios show projected pipeline improvement of ≥15%
- Data quality audit identifies <20% "direct/unknown" source attribution
- Roadmap identifies ≥5 actionable improvements implementable within 30 days
- Executive summary passes the "CFO test" — can be read in 90 seconds and answers "what did marketing drive?"

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Demand-Generation-Waterfall-&-Pipeline-Coverage-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-ROI-Reporting-Automation.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-Pipeline-Velocity-Weekly-Revenue-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-Budget-Defense-&-CFO-Finance-Intelligence-Engine.md`

## Integration Tips

- **HubSpot:** Use Revenue Attribution Reports (Marketing Hub Enterprise) → export deal touchpoint data as CSV → paste into prompt. Enable "Original Source" and "Latest Source" tracking on all contacts. Set up HubSpot's built-in multi-touch attribution under Reports → Attribution.
- **Salesforce + Pardot/Marketing Cloud:** Use Campaign Influence reports with Customizable Campaign Influence model. Export "Campaign Member + Opportunity" junction object data. Use Salesforce's Einstein Attribution if available.
- **Google Analytics 4:** Use GA4's Data-Driven Attribution model under Advertising → Attribution. Export conversion paths via Explorations → Path Exploration. Compare with CRM data to reconcile offline conversions.
- **Looker/Tableau:** Feed the prompt output's recommended channel weights back into your BI tool as a custom attribution dimension. Automate quarterly refreshes with scheduled exports.
- **Zapier/Make:** Build automation: New closed-won deal in Salesforce → pull all campaign touches → append to Google Sheets attribution log → trigger monthly AI analysis run via API.
- **Notion/Confluence:** Publish the executive summary section as a recurring "Marketing Revenue Report" page with monthly update cadence.

## Troubleshooting

**Problem: "I don't have clean touch point data — only lead source (first touch only)"**
Solution: Start with first-touch analysis and use the Data Quality Audit section to build the roadmap for capturing multi-touch data. The prompt will still deliver channel scorecards, funnel conversion rates, and budget recommendations — just flag that all attribution is first-touch until instrumentation improves. Prioritize UTM parameter coverage and CRM campaign association as your first 30-day fix.

**Problem: "The model recommends cutting our top SDR investment but leadership won't accept it"**
Solution: Use the scenario modeling section — present the "Conservative" scenario that maintains SDR headcount but reallocates within the budget. The prompt will show the opportunity cost numerically. Frame as "we're not cutting SDR, we're adding high-ROI channels that make each SDR more effective" — then use the webinar/content output as SDR pre-call warming assets.

**Problem: "My data has too much 'direct/none' traffic — up to 40%"**
Solution: This is the dark funnel problem. Use Section 7 (Dark Funnel & Untracked Influence) output to present leadership with a "true cost of bad instrumentation" number. Immediately implement: (1) post-demo "how did you hear about us?" field in your CRM, (2) UTM enforcement policy for all campaigns, (3) LinkedIn Insight Tag for B2B visitor identification, (4) G2 buyer intent data integration. Re-run analysis in 90 days after instrumentation improvements.

## Version History
- v1.0: Initial creation (auto-generated)
