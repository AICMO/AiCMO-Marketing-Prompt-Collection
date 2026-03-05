# Funnel Performance Diagnostics - Identify Drop-Off Points and Fix Conversion Leaks

**Difficulty:** Intermediate | **Time:** 20 min | **Tags:** analytics, funnel, conversion-rate-optimization, b2b, demand-gen

## Overview
Systematically diagnose where prospects drop out of your marketing and sales funnel, quantify the revenue impact of each leak, and generate prioritized fixes. Use this when conversion rates feel off, pipeline is stagnating, or you need to defend budget decisions with data.

## Quick Copy-Paste Version

You are a senior marketing analyst specializing in B2B SaaS funnel optimization. Analyze the following funnel data and identify the biggest conversion leaks.

Funnel data:
- Website visitors: 50,000/month
- MQL (marketing qualified leads): 1,200/month
- SQL (sales accepted leads): 480/month
- Opportunities created: 180/month
- Closed-won deals: 36/month
- Average deal size: $18,000 ARR

For each stage transition, calculate:
1. Conversion rate and industry benchmark comparison
2. Revenue lost per month at this stage (assuming downstream conversion rates hold)
3. Root cause hypotheses (3 per stage)
4. Top fix to test in the next 30 days

Then rank all stages by revenue impact of fixing them and give me a 90-day diagnostic roadmap.

## Advanced Customizable Version

ROLE: You are a Director of Marketing Analytics with expertise in full-funnel optimization across B2B SaaS, using frameworks including AARRR (Pirate Metrics), MEDDIC, and demand waterfall modeling.

CONTEXT:
Company: [Company Name]
Business model: [B2B SaaS / B2C / D2C / marketplace]
Average contract value (ACV): $[X]
Sales cycle length: [X days]
Primary acquisition channels: [e.g., paid search, organic, outbound SDR, events]

FUNNEL DATA (fill in your actuals -- leave blank if unknown):
Stage 1 - [Top of Funnel]: [X] visitors/leads/impressions per month
Stage 2 - [Awareness to Interest]: [X] per month | Current rate: [X]%
Stage 3 - [Interest to MQL]: [X] per month | Current rate: [X]%
Stage 4 - [MQL to SQL]: [X] per month | Current rate: [X]%
Stage 5 - [SQL to Opportunity]: [X] per month | Current rate: [X]%
Stage 6 - [Opportunity to Close]: [X] per month | Current rate: [X]%

SEGMENT BREAKDOWNS (if available):
- By channel: [paid / organic / outbound / referral]
- By ICP segment: [enterprise / mid-market / SMB]
- By geography: [North America / EMEA / APAC]

OBJECTIVE:
Perform a complete funnel performance diagnostic with the following outputs:

1. CONVERSION RATE SCORECARD
   For each stage transition:
   - Current conversion rate
   - B2B SaaS benchmark (cite source tier: top quartile / median / bottom quartile)
   - Gap vs. benchmark (in percentage points)
   - Monthly revenue at risk from this gap

2. LEAKAGE ANALYSIS
   Identify the top 3 highest-impact leakage points using this formula:
   Revenue Impact = (Benchmark Rate - Current Rate) x Volume x ACV x Downstream Conversion Rate
   For each leakage point list:
   - Quantified monthly revenue leakage
   - 3 data-backed root cause hypotheses
   - Signals that confirm/deny each hypothesis (what to look for in your data)

3. CHANNEL-LEVEL DIAGNOSIS (if segment data provided)
   - Which channel has the worst MQL-to-SQL conversion? Why?
   - Which segment closes fastest? What can you replicate?
   - Are there cohort anomalies (e.g., one channel driving volume but no revenue)?

4. PRIORITIZED FIX ROADMAP
   Structure as a 30/60/90 day plan:
   - 30 days: Quick wins (< 2 weeks to implement, measurable impact)
   - 60 days: Structural fixes (process changes, new assets, A/B tests)
   - 90 days: Strategic shifts (channel reallocation, ICP refinement, pricing tests)

   For each initiative include:
   - Specific action
   - Owner (Marketing / Sales / RevOps / Product)
   - Expected lift (conservative / base / optimistic)
   - How to measure success

5. EXPERIMENT DESIGN
   Design 2 specific A/B tests to run immediately:
   - Hypothesis
   - Test variant vs. control
   - Sample size needed for statistical significance
   - Success metric and measurement window

6. BOARD-READY SUMMARY
   One paragraph framing the funnel health for executive review: what's working, what's broken, what you're doing about it, and what the revenue upside is if you fix the top 2 issues.

CONSTRAINTS:
- Base recommendations on established frameworks (demand waterfall, MEDDIC for sales stages, PIE scoring for prioritization)
- Flag when data is insufficient and suggest what tracking to implement
- Be specific: no vague "improve content quality" -- every recommendation needs a concrete, testable action

## Example Input/Output

**Input Example:**

Company: Meridian Workflow (project management SaaS for construction firms)
ACV: $24,000
Funnel (monthly): 35,000 website visitors -> 890 free trials -> 267 product-qualified leads (PQLs) -> 89 sales demos -> 22 closed deals

**Output Example:**

**Conversion Rate Scorecard:**
| Stage | Current Rate | B2B SaaS Median | Gap | Monthly Revenue at Risk |
|---|---|---|---|---|
| Visitor to Trial | 2.5% | 3.8% | -1.3pp | $74,880 |
| Trial to PQL | 30.0% | 25.0% | +5pp | (outperforming) |
| PQL to Demo | 33.3% | 40.0% | -6.7pp | $42,912 |
| Demo to Close | 24.7% | 28.0% | -3.3pp | $19,008 |

**Top Leakage Point: Visitor to Trial ($74,880/month)**
Root cause hypotheses:
1. Trial signup friction -- form asks for credit card, reducing intent-to-try (check: heatmaps on signup page, drop-off in funnel analytics)
2. Messaging mismatch -- homepage speaks generic "project management" not construction-specific pain (check: scroll depth + exit surveys)
3. Traffic quality -- paid campaigns targeting broad keywords, driving non-ICP visitors (check: trial conversion by traffic source)

**30-day quick win:** Remove credit card requirement from trial signup. Industry data shows 12-18% lift in trial starts for no-card trials in vertical SaaS. Estimated impact: +107 trials/month -> +$38,500 revenue at downstream rates.

## Success Metrics
- Each identified leakage point has a quantified monthly revenue impact
- Root cause hypotheses are falsifiable (you know what data would confirm or deny them)
- The 30-day roadmap contains at least 2 initiatives you can start within 1 week
- Board summary is under 150 words and includes a dollar figure upside
- A/B test designs specify sample size and measurement window (not just "run a test")

## Related Prompts
- `../KPI-Dashboard-Creation/Marketing-Performance-Dashboard-Generator.md`
- `../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Conversion-Rate-Optimization.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/A-B-Testing-Automation.md`

## Integration Tips
- **HubSpot:** Pull lifecycle stage data via Reports > Funnel Report. Export CSV and paste into the Advanced Version under "Funnel Data." Set up custom properties for PQL scoring to get cleaner stage definitions.
- **Salesforce + Tableau:** Use the Opportunity Stage Duration report to feed the "Sales cycle length" field. Segment by Lead Source to populate channel-level diagnosis.
- **Google Analytics 4:** Use Funnel Exploration (Explore > Funnel Exploration) to get visitor-to-trial and page-level drop-off data. Export as PDF and summarize key stats before inputting.
- **Notion:** Copy the Prioritized Fix Roadmap output into a Notion table with Owner, Status, and Expected Lift columns -- instant project tracker.
- **Zapier:** Automate weekly funnel data pulls from HubSpot into a Google Sheet, then trigger a scheduled prompt run to produce a weekly diagnostic digest.

## Troubleshooting

**Problem: I don't have benchmark data for my specific vertical.**
Solution: Tell the AI your vertical and company stage (seed / Series A / growth). It will use the closest available benchmarks (e.g., Forrester, OpenView SaaS Benchmarks, or Salesforce State of Sales) and flag confidence levels. For highly niche verticals, request the AI derive implied benchmarks from your own historical data instead.

**Problem: The root cause hypotheses are too generic.**
Solution: Add more context to the Advanced Version -- specifically your top 3 acquisition channels, your primary ICP job title, and 1-2 pieces of qualitative feedback from lost deals. The more signal you provide, the more targeted the hypotheses become.

**Problem: My funnel has non-standard stages (e.g., product-led growth with PQL instead of MQL).**
Solution: Rename the stage labels in the prompt to match your actual funnel definition. In the CONTEXT section, add a one-line definition for each custom stage (e.g., "PQL = user who has invited 2+ teammates AND used core feature within 14 days of trial start"). The framework works for any sequential conversion funnel.

## Version History
- v1.0: Initial creation (auto-generated)
