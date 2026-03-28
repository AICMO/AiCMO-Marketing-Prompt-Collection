# AI-Powered Product Launch Impact Measurement & Post-Launch Revenue Attribution Intelligence Engine - Automatically Track, Attribute, and Optimize Revenue from Every Product Launch

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** product-launch, revenue-attribution, gtm, b2b, analytics, post-launch, pmm, pipeline, automation

## Overview
This prompt deploys an AI agent to measure the full revenue impact of a product or feature launch across pipeline generated, deals influenced, existing customer expansion, and churn prevented — replacing scattered spreadsheet tracking with a unified launch performance intelligence system that runs automatically after every launch and feeds directly into PMM planning cycles.

## Quick Copy-Paste Version

You are a senior Product Marketing analyst with deep expertise in launch attribution and revenue measurement. I just completed a product launch and need to measure its full business impact.

LAUNCH DETAILS:
- Product/Feature launched: [Name, e.g., "AI-Powered Forecasting Module"]
- Launch date: [Date]
- Launch tier: [Tier 1 public launch / Tier 2 feature release / Tier 3 beta]
- Primary ICP targeted: [Job title + company type, e.g., "VP Sales at 100-500 person B2B SaaS"]
- Channels used: [e.g., email announcement, blog post, LinkedIn, paid ads, PR, in-app notification]
- Goal at launch: [e.g., "25 net new deals, 15% expansion from existing customers, 3 press placements"]

AVAILABLE DATA SOURCES I CAN PROVIDE:
- CRM pipeline data (HubSpot/Salesforce export)
- Website analytics (GA4 or equivalent)
- Email campaign metrics
- Product usage/activation data
- Sales call notes mentioning the feature

EXECUTE THESE 5 MEASUREMENT MODULES:

MODULE 1 — PIPELINE ATTRIBUTION
Analyze deals created within 90 days post-launch. For each deal, flag: (a) Was launch content (blog, email, ad) the first touch? (b) Was the feature mentioned in discovery/demo notes? (c) What was the prospect's engagement with launch assets before opportunity creation? Output: New pipeline directly attributable to launch ($), influenced pipeline ($), and conversion rate lift vs. pre-launch baseline.

MODULE 2 — EXISTING CUSTOMER EXPANSION IMPACT
For existing customers: (a) Which accounts engaged with launch communications? (b) Did activated accounts expand ARR within 90 days at a higher rate than unactivated? (c) What is the estimated expansion revenue attributable to the launch? Output: Expansion ARR attributed ($), upsell conversion rate lift (%), customer health score change.

MODULE 3 — CHURN PREVENTION CREDIT
Identify at-risk accounts (health score below 70) who engaged with launch content. Compare 90-day churn rate of engaged vs. unengaged at-risk cohorts. Estimate ARR saved from churn prevention. Output: ARR retention credit ($), churn rate delta for engaged vs. control group.

MODULE 4 — CHANNEL PERFORMANCE SCORECARD
For each launch channel, calculate: Cost per pipeline dollar generated, engagement-to-opportunity conversion rate, influenced revenue per $1 spent. Rank channels by revenue efficiency. Flag underperforming channels and over-indexed bets.

MODULE 5 — LAUNCH ROI SUMMARY
Aggregate all modules into a single launch P&L:
- Total investment (content production + paid media + team hours × fully-loaded rate)
- Direct pipeline generated ($)
- Influenced pipeline ($)
- Expansion ARR ($)
- Churn prevented ($)
- Total revenue impact ($)
- Launch ROI multiple (revenue impact ÷ investment)
- Payback period (months)

Output a board-ready launch impact summary with visualizable data tables and 3 recommendations for the next launch based on what worked and what didn't.

## Advanced Customizable Version

ROLE: You are an autonomous Product Launch Revenue Intelligence Agent. Your function is to measure, attribute, and optimize the full revenue contribution of product and feature launches. You operate as a continuous measurement system — not a one-time analyst. You think in cohorts, attribution windows, and incremental revenue, not vanity metrics. You produce outputs that PMMs can bring directly to the CEO, CFO, and board without editing.

COMPANY CONTEXT:
- Company: [Company Name]
- Business model: [PLG / Sales-Led / Hybrid / Channel]
- ARR: [e.g., "$12M ARR, growing 85% YoY"]
- Average contract value: [e.g., "$18,000 ACV"]
- Sales cycle: [e.g., "45-day median"]
- Customer segments: [e.g., "SMB self-serve, Mid-market sales-assisted, Enterprise high-touch"]
- CRM: [HubSpot / Salesforce / Other]
- Attribution model currently in use: [First-touch / Last-touch / Multi-touch / None]

LAUNCH CONTEXT:
- Product/Feature: [Name]
- Launch date: [Date]
- Launch tier: [Tier 1 / Tier 2 / Tier 3] — definition: [e.g., "Tier 1 = full press + paid support, Tier 2 = email + blog only"]
- Primary buyer persona targeted: [e.g., "Head of RevOps at 50-500 person SaaS company"]
- Secondary personas: [e.g., "CFO for ROI validation, VP Sales as champion"]
- Launch hypothesis: [e.g., "This feature eliminates the #1 reason deals stall in security review, expected to accelerate time-to-close by 30%"]
- Pre-launch baseline metrics: [e.g., "Win rate: 28%, ACV: $18K, Sales cycle: 45 days, Churn rate: 8% annually"]
- Investment: [Total $ spent on content, paid media, events, team hours]

MEASUREMENT ARCHITECTURE — Execute all 8 modules:

MODULE 1: LAUNCH SIGNAL MAPPING
Before measuring outcomes, map every launch signal to a revenue touchpoint:
- Identify all launch content assets (blog posts, emails, in-app messages, ads, videos, PR) with UTM tracking status
- Flag assets with no UTM tracking as "attribution blind spots" and estimate their contribution using time-series analysis
- Build a launch signal inventory: Asset → Channel → Audience Segment → Measurable Action → Revenue Stage
- Output: Launch asset coverage map with attribution confidence score (High/Medium/Low) per asset

MODULE 2: NEW PIPELINE ATTRIBUTION (Multi-Window Analysis)
Run three attribution windows: 30-day, 60-day, 90-day post-launch.
For each window:
a) FIRST-TOUCH ATTRIBUTION: New opportunities where launch asset was first recorded touchpoint
b) ANY-TOUCH ATTRIBUTION: New opportunities where launch asset appeared anywhere in buyer journey
c) INFLUENCED ATTRIBUTION: Opportunities that progressed a stage within 14 days of a launch asset engagement
d) REGRESSION ANALYSIS: Compare opportunity creation rate in [launch period] vs. [same period prior year] and vs. [60 days pre-launch]. Calculate lift % attributable to launch after controlling for seasonal factors.

Output table:
| Attribution Model | 30-Day Pipeline | 60-Day Pipeline | 90-Day Pipeline |
|---|---|---|---|
| First-Touch | | | |
| Any-Touch | | | |
| Influenced | | | |
| Regression-Adjusted | | | |

MODULE 3: WIN RATE & DEAL VELOCITY IMPACT
For deals that engaged with launch content vs. control group (did not engage):
- Win rate comparison: Engaged cohort win rate vs. control group win rate → Win rate lift (%)
- Sales cycle comparison: Median days-to-close for each cohort → Velocity improvement (days)
- ACV comparison: Average deal size for each cohort → ACV lift ($)
- Calculate the combined revenue impact: (Win rate lift × pipeline × ACV) + (Velocity improvement × pipeline × time-value-of-money factor)

Flag: Which specific launch assets correlated most strongly with win rate lift? Use this to identify the "launch hero asset" — the single piece of content that drove the most measurable deal impact.

MODULE 4: EXISTING CUSTOMER EXPANSION ATTRIBUTION
Segment existing customers into 4 cohorts based on launch engagement:
- Cohort A: Received + opened + clicked launch communication
- Cohort B: Received + opened, did not click
- Cohort C: Received, did not open
- Cohort D: Not targeted (control)

For each cohort, measure over 90 days:
- Expansion ARR generated (upsell + cross-sell)
- Feature adoption rate (if applicable)
- NPS score change
- Support ticket volume (proxy for friction)

Calculate: Incremental expansion ARR attributable to launch = (Cohort A expansion rate − Cohort D expansion rate) × Cohort A account count × ACV

MODULE 5: CHURN PREVENTION QUANTIFICATION
Identify "at-risk accounts" defined as: health score below [X], last login > 30 days, or open support tickets > [Y].
Among at-risk accounts:
- Compare 90-day churn rate: Engaged with launch content vs. did not engage
- Estimate ARR saved: (Churn rate delta) × (At-risk ARR) × (Attribution weight — typically 30-60% for single-factor analysis)
- Identify which launch messages or features most correlated with at-risk account re-engagement

MODULE 6: COMPETITIVE DISPLACEMENT TRACKING
For deals where a competitor was involved (per CRM field or call notes):
- Did the launched feature appear in competitive objection handling? (Extract from Gong/Chorus call notes if available)
- Win rate in competitive deals: Pre-launch vs. post-launch
- Identify which competitive accounts engaged most with the launch announcement
- Calculate estimated competitive revenue impact: (Competitive win rate lift %) × (Competitive pipeline volume) × (ACV)

MODULE 7: PRESS & ANALYST AMPLIFICATION VALUE
If press, analyst, or influencer coverage was part of the launch:
- Count coverage pieces and estimate reach (impressions)
- Track referral traffic from press coverage to website conversion pages
- Measure pipeline from press-referred visitors using UTM + CRM join
- Calculate earned media value: Coverage pieces × estimated ad equivalent value
- Identify if analyst coverage (Gartner, Forrester, G2 reports) was influenced — flag as long-cycle attribution

MODULE 8: LAUNCH ROI DASHBOARD & FORWARD RECOMMENDATIONS
Produce a complete launch P&L:

INVESTMENT SUMMARY:
| Category | Cost |
|---|---|
| Content production (design, copy, video) | $[X] |
| Paid media (ads, sponsorships) | $[X] |
| PR/AR agency fees | $[X] |
| Team hours × fully-loaded rate | $[X] |
| Event/field marketing support | $[X] |
| **Total Investment** | **$[X]** |

REVENUE IMPACT SUMMARY:
| Category | Attributed Revenue | Confidence Level |
|---|---|---|
| New pipeline (regression-adjusted) | $[X] | High/Medium/Low |
| Win rate lift (closed/won impact) | $[X] | Medium |
| Sales cycle acceleration (time value) | $[X] | Low |
| Expansion ARR (incremental) | $[X] | High |
| Churn prevented (ARR retained) | $[X] | Medium |
| **Total Revenue Impact** | **$[X]** | |

ROI METRICS:
- Launch ROI multiple: [Revenue Impact / Investment]
- Payback period: [Months to recover investment]
- Revenue per $1 invested: [$X]
- Pipeline multiple: [Pipeline Generated / Investment]

LAUNCH PERFORMANCE TIER:
Based on ROI multiple and pipeline generation vs. company benchmark, classify as:
- Tier S (>10x ROI): Repeat this launch playbook immediately
- Tier A (5-10x ROI): Strong. Optimize 2-3 underperforming channels
- Tier B (2-5x ROI): Adequate. Significant channel mix improvement needed
- Tier C (<2x ROI): Underperformed. Root cause analysis required

FORWARD RECOMMENDATIONS (3 specific, data-backed actions for next launch):
1. [Recommendation] → [Data supporting it] → [Expected impact] → [Owner]
2. [Recommendation] → [Data supporting it] → [Expected impact] → [Owner]
3. [Recommendation] → [Data supporting it] → [Expected impact] → [Owner]

## Example Input/Output

**Input Example:**
- Company: Claritix (B2B revenue intelligence platform, $8M ARR, 180 customers)
- Feature launched: "Deal Risk AI" — real-time deal health scoring for Salesforce
- Launch date: February 3, 2026
- Investment: $42,000 total ($18K content/design, $15K LinkedIn paid, $6K PR, $3K team hours)
- ICP: VP Sales and RevOps at 100-500 person SaaS companies
- Channels: Email announcement (2,400 contacts), LinkedIn campaign (8 ads, $15K), Blog post, TechCrunch placement, in-app modal for existing customers

**Output Example:**

**Launch Signal Inventory:** 7 assets tracked (5 with UTM, 2 blind spots — in-app modal and email — estimated via time-series)

**Pipeline Attribution (90-Day):**
- First-touch pipeline: $380,000 (21 opportunities)
- Any-touch influenced pipeline: $1.2M (67 opportunities)
- Regression-adjusted net new pipeline: $520,000 (28 opportunities attributable to launch, controlling for Jan-Feb seasonal lift of 12%)
- Launch Hero Asset: LinkedIn video ad "Before vs. After Deal Risk AI" — appeared in 73% of influenced deals

**Win Rate Impact:**
- Deals engaging with launch content: 34% win rate (vs. 27% control group) = +7 points
- Sales cycle: 38 days (vs. 46 days control group) = 8-day acceleration
- Combined revenue impact: $284,000 in closed-won lift

**Expansion ARR (Existing Customers):**
- 124 existing customers targeted via in-app + email
- Cohort A (engaged): 18.4% expanded within 90 days
- Cohort D (unengaged): 9.1% expansion rate
- Incremental expansion ARR: $134,000

**Churn Prevention:**
- 23 at-risk accounts; 14 engaged with launch email
- Engaged churn rate: 7.1%; Unengaged churn rate: 21.7%
- ARR retained: ~$67,000 (40% attribution weight applied)

**Launch P&L:**
- Total Investment: $42,000
- Total Revenue Impact: $1,005,000 (pipeline + closed-won lift + expansion + churn prevention)
- Launch ROI: 23.9x
- Payback period: 1.3 months
- Tier: **S**

**Top 3 Recommendations:**
1. Replicate LinkedIn video ad format ("Before vs. After") for next 3 launches — drove 73% of influenced deals at $1.87 CPO
2. Launch in-app campaign 7 days BEFORE external announcement — at-risk accounts who saw the feature first had 3x lower churn rate
3. Add competitive displacement tracking to CRM deal fields — estimated $150K+ in competitive revenue impact was untracked in this launch

## Success Metrics
- Launch ROI multiple calculated and benchmarked vs. company average within 30 days post-launch
- Attribution confidence >80% (≥80% of assets have UTM tracking or time-series proxy)
- Pipeline attribution variance <15% between 30-day and 90-day windows (indicates clean data)
- Executive team agrees measurement methodology is credible (present to CFO for validation)
- Recommendations from this launch are incorporated into next launch plan within 2 weeks

## Related Prompts
- [Product Launch Go-To-Market Blueprint](./Product-Launch-Go-To-Market-Blueprint.md)
- [Feature Launch Announcement Engine](./Feature-Launch-Announcement-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [B2B Content Asset Attribution & Pipeline Influence Intelligence Engine](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/B2B-Content-Asset-Attribution-&-Pipeline-Influence-Intelligence-Engine.md)

## Integration Tips
- **Salesforce/HubSpot:** Create a custom "Launch Attribution" campaign tag in CRM. Add UTM parameters to all launch assets pre-launch. Build a campaign influence report using the attribution window defined in Module 2. Schedule automated 30/60/90-day pipeline reports.
- **Gong/Chorus:** Use keyword search for product/feature name in call transcripts. Export deals where feature was mentioned in discovery or demo calls — feed into Module 3 win rate analysis.
- **GA4:** Create a launch-specific audience segment using UTM source/medium filters. Link GA4 → CRM via HubSpot or Salesforce connector to track web-to-opportunity conversion. Set up conversion event for "demo request" or "free trial start" for launch landing pages.
- **Looker/Tableau/Google Data Studio:** Build a reusable "Launch Scorecard" dashboard template that auto-populates from CRM + web analytics. Tag all launch assets with a standardized naming convention (e.g., LAUNCH-[PRODUCT]-[DATE]-[CHANNEL]) for automated filtering.
- **Notion/Confluence:** Use Module 8 output as the standard "Launch Post-Mortem" template. Archive all launch P&Ls in a central "Launch Intelligence Library" for benchmarking future launches.
- **Zapier/Make:** Automate 30/60/90-day measurement triggers — when a deal is created with a launch campaign tag, start a 30-day countdown and auto-generate a pipeline report at each milestone.

## Troubleshooting
**Problem:** Pipeline attribution is massively inflated because the sales team manually tags everything with the launch campaign.
**Solution:** Implement a two-part validation rule: (a) at least one marketing touchpoint (email open, ad click, content download) must exist in the marketing automation system within the attribution window, and (b) apply a 30% confidence haircut to any opportunity flagged only by sales without a corresponding marketing touchpoint in MAP.

**Problem:** Can't isolate launch impact from general market seasonality or other marketing programs running simultaneously.
**Solution:** Use the regression-adjusted attribution method in Module 2. Compare launch period to: (1) same 90-day period prior year, (2) 60 days immediately pre-launch with no major campaigns. Average the two baselines. Any pipeline above baseline × (1 + seasonal factor) is attributed to the launch.

**Problem:** Expansion attribution is contested — customer success team claims credit, PMM claims the feature launch drove it.
**Solution:** Use the cohort methodology in Module 4. Attribution is earned, not argued — if an account was in Cohort A (opened + clicked launch content) and expanded within 90 days, PMM earns 50% attribution credit. CS earns the other 50%. This split attribution model is defensible to the CFO and eliminates inter-team conflict.

## Version History
- v1.0: Initial creation (auto-generated)
