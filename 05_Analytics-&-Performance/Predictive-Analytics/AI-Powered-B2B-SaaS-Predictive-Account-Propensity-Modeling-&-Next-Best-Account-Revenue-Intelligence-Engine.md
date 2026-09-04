# AI-Powered B2B SaaS Predictive Account Propensity Modeling & Next-Best-Account Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** predictive-analytics, account-scoring, propensity-modeling, abm, pipeline-generation, intent-data, icp, b2b-saas, revenue-intelligence

## Overview
This prompt ingests your ICP definition, historical closed-won account data, technographic and firmographic signals, and third-party intent data to build a predictive account propensity model — scoring your entire target universe by likelihood and timing of purchase — so you can concentrate pipeline generation resources on accounts most likely to buy in the next 30–90 days, before they raise their hand.

## Quick Copy-Paste Version

You are a senior B2B demand generation strategist and predictive analytics expert. Help me build a next-best-account model to identify which companies in my total addressable market are most likely to buy in the next 90 days.

My product and ICP:
- Product: [SaaS platform that does X for Y personas]
- Primary ICP: Companies with [X–X employees], in [industry verticals], using [tech stack], with [pain point triggers]
- Average deal size: $[X] ACV
- Average sales cycle: [X] days
- Primary buyer persona: [Title, function, seniority]

My closed-won account data (last 12 months):
- Total customers acquired: [X]
- Top 5 industries by win rate: [list]
- Top 3 tech stack signals that correlate with wins: [tools your best customers use]
- Company size range of ideal customers: [X–X employees]
- Funding stage of best customers: [bootstrapped / seed / Series A-C / public]
- Common trigger events in 6 months before purchase: [list 3–5 events, e.g., new CRO hire, funding round, competitor contract expiry, compliance deadline]

My current account universe I want to score:
- Total accounts in CRM/target list: [X]
- Accounts with any prior engagement (content, webinar, ad clicks): [X]
- Accounts with active intent signals (6sense / Bombora / G2 / LinkedIn): [X]
- Accounts with hiring signal for relevant roles: [X]
- Accounts with recent funding events (last 90 days): [X]
- Accounts already in active pipeline: [X]

Deliver:
1. PROPENSITY SCORING MODEL: A weighted scoring framework (0–100) I can apply to my account universe, with specific weights for each signal type
2. TIER 1 HOT ACCOUNTS: Identify the profile of accounts scoring 75+ — what does a "buy window open" account look like?
3. TIER 2 WARM ACCOUNTS: Profile of accounts scoring 50–74 — showing early signals, engage now to influence
4. SIGNAL PRIORITIZATION: Rank the top 5 signals by predictive power for my specific product/ICP
5. OUTREACH SEQUENCING: What is the ideal first touch, second touch, and third touch for each tier within the first 2 weeks?
6. PIPELINE MATH: If I have [X] Tier 1 accounts, what pipeline should I model at historical conversion rates?

## Advanced Customizable Version

**ROLE:**
You are a VP of Revenue Intelligence and GTM Analytics with 14+ years of building predictive account models for B2B SaaS companies from $5M to $750M ARR. You have deep expertise in propensity modeling, firmographic and technographic signal weighting, intent data interpretation, and translating predictive scores into executable marketing and sales plays. Your models have consistently outperformed baseline outbound conversion by 3–5x. You combine machine learning principles, behavioral economics, and revenue operations discipline to create account prioritization frameworks that are both statistically rigorous and immediately actionable by sales and marketing teams.

**OBJECTIVE:**
Build a comprehensive predictive account propensity model for [Company Name]'s target market, generate a weighted scoring methodology applicable to their ICP universe, identify which account cohorts represent the highest near-term revenue opportunity, and prescribe the exact GTM plays to activate each cohort at maximum velocity.

**CONTEXT INPUT:**

Provide the following for maximum model accuracy:

COMPANY & PRODUCT PROFILE:
- Company: [Name] | Stage: [Series A / B / C / PE-backed / public]
- Product category: [Category] | Primary value prop: [One-sentence description]
- ARR: $[X]M | Growth rate: [X]% YoY
- Average ACV: $[X] | Sales cycle median: [X] days
- Primary GTM motion: [outbound-led / inbound-led / PLG / ABM-led / partner-led]
- Primary buyer: [Title] | Secondary influencer: [Title] | End user: [Title]

ICP DEFINITION (current):
- Company size (employees): [X–X]
- Revenue range: $[X]M–$[X]M
- Industries (ranked by win rate): [1, 2, 3, 4, 5]
- Geographies: [primary / secondary]
- Tech stack requirements: [must-have technologies / integrations]
- Business model: [SaaS / enterprise / mid-market / SMB / e-commerce / professional services]
- Exclusions: [Company types, industries, sizes you don't sell to]

CLOSED-WON ACCOUNT INTELLIGENCE (last 18 months):
- Total new logos: [X]
- Win rate by industry: [Industry A: X%, Industry B: X%, etc.]
- Win rate by company size band: [50–200: X%, 200–500: X%, 500–2000: X%, 2000+: X%]
- Win rate by funding stage: [Bootstrapped: X%, Seed-A: X%, B-C: X%, Growth/Late: X%, Public: X%]
- Win rate by tech stack overlap: [HubSpot users: X%, Salesforce users: X%, etc.]
- Top 3 trigger events in 6 months pre-purchase:
  1. [Trigger event with % of customers who had this]
  2. [Trigger event with % of customers who had this]
  3. [Trigger event with % of customers who had this]
- Average number of touches before first meeting: [X]
- Average inbound content engagement before purchase: [X pieces]
- Primary discovery channel (how they first heard of you): [X]%

CURRENT ACCOUNT UNIVERSE DATA:
- Total ICP accounts in target universe: [X]
- Currently in CRM (any stage): [X]
- Active pipeline: [X] accounts / $[X] pipeline
- Dark/cold ICP accounts (no prior engagement): [X]

SIGNAL DATA AVAILABLE:
- Third-party intent data platform: [6sense / Bombora / G2 / TechTarget / None]
- Intent topics you track: [list 5–10 topics]
- Accounts showing intent in last 30 days: [X]
- LinkedIn ad engagement data: [accounts with 5+ ad engagements in 30 days]: [X]
- Website visitor intelligence (Clearbit / RB2B / Albacross): [X] anonymous accounts identified
- Hiring signals: [Accounts hiring for relevant roles, e.g., "VP Revenue Operations"]: [X]
- Funding signals: [Accounts with new funding in last 90 days]: [X]
- Technology change signals: [Accounts that added/removed relevant tech in last 60 days]: [X]
- Job change signals: [Accounts with new relevant executive in last 90 days]: [X]
- Competitive signals: [Accounts reviewing competitor on G2/Capterra/review sites]: [X]

CURRENT GTM CAPACITY:
- SDR headcount: [X] | SDR capacity (accounts per week): [X]
- AE headcount: [X] | AE capacity (discovery calls per week): [X]
- Marketing budget available for account activation: $[X]/month
- Channels available: [outbound email / LinkedIn / direct mail / paid ABM / gifting / events]

**ANALYTICAL FRAMEWORK:**

Apply the following predictive methodology:

**1. PROPENSITY SCORE ARCHITECTURE (0–100 SCALE)**

Score each account across four signal dimensions:

**Dimension A — Fit Score (0–35 points): Is this account a strong ICP match?**
- Industry match + win rate correlation: 0–10 pts
  - Top 2 industries by historical win rate: 10 pts
  - Industries 3–5 by win rate: 7 pts
  - Adjacent/adjacent-adjacent industry: 4 pts
  - Poor fit industry: 0 pts
- Company size match: 0–8 pts
  - Perfect size band (highest-converting): 8 pts
  - One band off: 5 pts
  - Two bands off: 2 pts
- Tech stack overlap: 0–10 pts
  - Must-have integration exists: +6 pts per signal (max 10)
  - Relevant complementary tech: +3 pts
  - Conflicting/replacement tech in stack: -5 pts
- Funding stage alignment: 0–7 pts
  - Highest-converting funding stage: 7 pts
  - Adjacent stages: 4 pts
  - Lowest-converting stages: 1 pt

**Dimension B — Timing Score (0–30 points): Are they in an active buying window?**
- Third-party intent signal strength: 0–12 pts
  - High intent (5+ topics, 80th percentile surge): 12 pts
  - Moderate intent (2–4 topics, 50–80th percentile): 7 pts
  - Low intent (1 topic, below 50th percentile): 3 pts
  - No intent data: 0 pts
- Trigger event recency: 0–10 pts
  - Primary trigger event in last 30 days: 10 pts
  - Primary trigger event in last 31–90 days: 7 pts
  - Secondary trigger event in last 90 days: 5 pts
  - No recent trigger events: 0 pts
- Competitive review activity: 0–8 pts
  - Actively reviewing your category on G2/Capterra: 8 pts
  - Reviewed competitor content 3+ times: 5 pts
  - Single competitive search/page visit: 2 pts

**Dimension C — Engagement Score (0–20 points): Have they shown any interest in you?**
- Website / content engagement: 0–8 pts
  - Multiple visits to high-intent pages (pricing, demo, comparison): 8 pts
  - Single high-intent page visit: 5 pts
  - Blog/awareness content only: 2 pts
- Ad engagement: 0–6 pts
  - Video view 75%+ or LinkedIn post engagement: 6 pts
  - Ad click (retargeting or ABM): 4 pts
  - Ad impression only (no click): 1 pt
- Prior outreach response: 0–6 pts
  - Previously replied to email or LinkedIn (any stage): 6 pts
  - Email opened 3+ times without reply: 3 pts
  - No prior outreach history: 0 pts

**Dimension D — Stakeholder Score (0–15 points): Are the right people visible and reachable?**
- Buyer persona identified in account: 0–7 pts
  - Primary buyer AND economic buyer both identified in LinkedIn/CRM: 7 pts
  - Primary buyer only identified: 4 pts
  - No decision-maker identified: 0 pts
- Social signal from key personas: 0–8 pts
  - Target persona actively posting on LinkedIn about pain/category: 8 pts
  - Target persona recently changed job (honeymoon window open): 6 pts
  - Target persona engaged with company competitor content: 4 pts
  - No persona signal: 0 pts

**2. ACCOUNT TIER CLASSIFICATION**
- **Tier 1 — HOT (Score 70–100):** Buying window likely open. Highest-priority for immediate SDR + AE engagement. Activate all channels in parallel. Expected conversion to pipeline: [X–X]% within 45 days.
- **Tier 2 — WARM (Score 45–69):** Signals emerging, not yet at peak readiness. Enroll in ABM nurture sequence + low-touch outbound. Reassess in 30 days. Expected conversion to pipeline: [X–X]% within 90 days.
- **Tier 3 — DEVELOPING (Score 20–44):** ICP fit is strong but timing signals absent. Place in long-cycle ABM nurture. Monitor for trigger events. Expected conversion to pipeline: [X–X]% within 180 days.
- **Tier 4 — WATCH (Score 0–19):** Weak fit or no timing signals. Passive nurture only. Remove from active targeting until score threshold crossed.

**3. SIGNAL DECAY MODELING**
Apply signal decay rates — signals lose predictive power over time:
- Third-party intent surge: 50% decay in predictive power after 30 days
- Website high-intent page visit: 50% decay after 14 days
- Trigger event (funding, hire, reorg): 60% decay after 60 days
- Competitive review activity: 70% decay after 21 days
- LinkedIn engagement: 40% decay after 45 days

Rescore accounts monthly. Accounts that cross from Tier 2 → Tier 1 become urgent pipeline opportunities.

**4. NEXT-BEST-ACCOUNT ACTION ENGINE**
For each tier, prescribe the specific outbound sequence:

**Tier 1 — Immediate Activation Sequence (Days 1–14):**
- Day 1: AE + SDR both review account. SDR sends personalized cold email referencing the specific trigger event ("I noticed [Company] recently hired a new CRO — we've helped 8 companies in your position within 90 days of that hire..."). Subject line uses trigger-event personalization.
- Day 3: LinkedIn connection request from AE with note referencing shared content or mutual connection.
- Day 5: Follow-up email with a 1-page "Why companies like [Company] buy [Your Product]" one-pager — featuring 2 customers in same industry.
- Day 7: CMO/VP LinkedIn InMail to economic buyer (if different from primary contact).
- Day 10: Direct mail send — premium branded item to physical office address (if available).
- Day 14: SDR final "break-up" email with genuine opt-out — "Not the right time? I'll check back in [X] days. Reply STOP and I will never contact you again."

**Tier 2 — Engagement Sequence (Days 1–30):**
- Week 1: Add to LinkedIn ABM campaign serving 3x weekly educational content (pain-point oriented, not product-led).
- Week 2: SDR sends single email referencing content they engaged with + triggers a retargeting ad sequence.
- Week 3: Invite economic buyer to executive webinar or roundtable (if relevant).
- Week 4: Reassess score — if moved to Tier 1, activate full Tier 1 sequence. If static, move to 30-day cadence.

**5. PIPELINE PROJECTION MODEL**
Given historical account-to-pipeline conversion rates:
- Tier 1 accounts: [X]% convert to first meeting within 45 days × [X]% meeting-to-pipeline conversion = [X]% net pipeline rate
- At [X] Tier 1 accounts × [X]% net pipeline rate × $[X] average ACV = $[X]M projected pipeline contribution in 90 days
- Tier 2 accounts: Apply [X]% lower conversion rate × 90-day window

**OUTPUT REQUIREMENTS:**

Structure your response as:

**ACCOUNT UNIVERSE SCORING SUMMARY**
| Tier | Score Range | Estimated Account Count | Projected Pipeline (90-day) | Priority Action |
|------|------------|------------------------|----------------------------|----------------|
| Tier 1 (Hot) | 70–100 | [X] | $[X] | Immediate SDR + AE activation |
| Tier 2 (Warm) | 45–69 | [X] | $[X] | ABM + low-touch outbound |
| Tier 3 (Developing) | 20–44 | [X] | $[X] | Long-cycle nurture |
| Tier 4 (Watch) | 0–19 | [X] | — | Passive only |

**SIGNAL WEIGHT CALIBRATION TABLE**
Specific weights for each signal type, calibrated to your historical win data

**TIER 1 ACCOUNT PROFILE ("PERFECT BUY WINDOW" DESCRIPTION)**
A narrative description of what a maximal-score Tier 1 account looks like for your specific ICP — use this as the definition for your SDR/AE briefings

**TOP 10 ACCOUNTS TO ACTIVATE THIS WEEK**
If account list is provided, rank by propensity score with specific reason per account and personalization hook for the first email

**30-60-90 DAY PIPELINE FORECAST**
Revenue pipeline expected from this program at each milestone

**MODEL REFRESH CADENCE**
How often to rescore, which signals to monitor weekly vs. monthly

## Example Input/Output

**Example Input:**

Company: Flowline — B2B SaaS revenue forecasting platform, $19M ARR, Series B
Product: AI-powered revenue forecasting and pipeline analytics for B2B SaaS companies
ICP: 200–2,000 employee B2B SaaS companies, Salesforce or HubSpot users, VP Sales or CRO primary buyer
Average ACV: $52K | Sales cycle: 74 days | Win rate: 22%
GTM: Primarily outbound + ABM, 6 SDRs, 4 AEs

Closed-won data: Best customers are Series B–C SaaS companies (41% of wins), using Salesforce (68% of wins), that recently hired a new CRO or VP Sales (38% of wins had this trigger in last 90 days), or missed a quarterly revenue target (24% of wins discovered this in discovery).

Signals available: Bombora intent data (topics: revenue forecasting, pipeline management, sales analytics), G2 category reviews, LinkedIn ad engagement data, website visitor identification via RB2B.

Current universe: 3,400 ICP accounts in CRM, 380 showing Bombora intent, 142 with executive sales/revenue hires in 90 days, 67 currently reviewing competitors on G2.

---

**Example Output:**

**ACCOUNT UNIVERSE SCORING SUMMARY**

| Tier | Score Range | Est. Accounts | 90-Day Pipeline Projection | Priority |
|------|------------|--------------|--------------------------|---------|
| Tier 1 (Hot) | 70–100 | 214 | $2.4M | Immediate activation |
| Tier 2 (Warm) | 45–69 | 487 | $1.1M | ABM + light outbound |
| Tier 3 (Developing) | 20–44 | 1,340 | $0.3M (180 days) | Long-cycle nurture |
| Tier 4 (Watch) | 0–19 | 1,359 | — | Passive only |

**CALIBRATED SIGNAL WEIGHTS FOR FLOWLINE:**

Given your 22% win rate and CRO/VP Sales hiring being your #1 trigger event (38% correlation), your model weights should be:

1. **New CRO/VP Sales hire at ICP account (last 90 days):** +12 points — Your single strongest predictor. New sales leaders buy tools in their first 60–90 days. This is your "honeymoon window" signal.

2. **Bombora intent surge: "revenue forecasting" + "pipeline analytics" (70th+ percentile):** +11 points — When companies are actively researching your category, they're in or approaching a buying window. High signal decay rate (rescore every 2 weeks).

3. **Salesforce customer + Series B–C funding stage:** +9 points (combined) — 68% of your closed-won use Salesforce; Salesforce-integrated products accelerate your sales cycle because IT review is simpler. Series B–C correlates with maturity to invest.

4. **G2 competitive review activity in last 21 days:** +8 points — Companies reviewing your competitors are in an active evaluation. This is the highest-urgency signal after the new hire trigger.

5. **Website high-intent page visit (Pricing or Demo Request page via RB2B):** +7 points — Anonymous account visiting pricing page within last 7 days = strong buying signal. Decay fast.

**TIER 1 ACCOUNT PROFILE — "PERFECT FLOWLINE BUY WINDOW":**

A Tier 1 account for Flowline looks like this: A B2B SaaS company with 300–1,500 employees, Series B or C, running Salesforce as their CRM, that appointed a new CRO or VP of Sales in the last 60 days. The new sales leader is posting on LinkedIn about "forecasting accuracy" or "pipeline visibility." The company is simultaneously showing Bombora intent on "revenue forecasting" and "sales analytics." They have either missed a recent quarter or are growing fast enough that their current spreadsheet-based forecasting has broken. They have 8–25 quota-bearing reps and a RevOps or Sales Ops function. They've likely visited your pricing page anonymously or engaged with a LinkedIn ad in the last 30 days.

**TOP 5 ACCOUNTS TO ACTIVATE THIS WEEK:**

1. **Meridian Cloud (Score: 91)** — New CRO hired 22 days ago (LinkedIn confirmed). Bombora intent surge at 84th percentile for "pipeline analytics." Salesforce customer. Series C. First email hook: "Congratulations on bringing [CRO Name] aboard — we've helped 6 Series C SaaS companies build their forecasting foundation in the first 60 days of a new CRO. 15 minutes this week?"

2. **ClearPath Analytics (Score: 87)** — G2 review of Clari posted 11 days ago by VP of RevOps. Bombora intent 78th percentile. HubSpot customer (not Salesforce, slight deduction). First email hook: "Saw your team recently evaluated some forecasting tools — we tend to show up a lot in those comparisons. Happy to run a quick 3-way breakdown. Worth 20 minutes?"

3. **Volta Data (Score: 83)** — CFO posted LinkedIn article about "the forecasting gap in growth-stage SaaS" 8 days ago. Bombora 69th percentile. Salesforce user. Pricing page visit detected via RB2B 3 days ago. First email hook: "Your CFO's post on forecasting gaps last week captured exactly the problem we built Flowline to solve — would love to show you how [similar company] fixed theirs in 6 weeks."

**PIPELINE MATH FOR FLOWLINE:**

- 214 Tier 1 accounts × 28% meeting rate (based on your historical outbound meeting rate to warm ICP accounts) = 60 first meetings in 45 days
- 60 meetings × 35% meeting-to-pipeline rate = 21 new qualified opportunities
- 21 opportunities × $52K average ACV = $1.09M new pipeline
- Apply 22% win rate = $240K projected closed-won from this cohort over 90-day cycle

Tier 2 contribution (90-day window): 487 accounts × 8% net pipeline rate × $52K ACV = $2.0M additional pipeline (longer cycle, lower urgency)

## Success Metrics

Evaluate quality of this prompt's output by checking:
- **Model calibration accuracy**: Historical account scoring retroactively applied to closed-won accounts should yield ≥75% of wins in Tier 1 or 2 buckets
- **Tier 1 meeting conversion rate**: ≥25% of Tier 1 accounts should convert to first meeting within 45 days (vs. baseline cold outbound rate of 5–12%)
- **Pipeline-to-quota coverage**: Model should surface enough Tier 1 + Tier 2 pipeline opportunity to provide 3x+ coverage of quarterly pipeline target
- **Signal weight validation**: After 90 days, run win/loss analysis on the specific signals used — the top-weighted signals should correlate with actual wins at ≥60% accuracy
- **Score refresh cycle**: Model is rescored at least monthly; Tier 1 account count should remain actionable (not more than SDR team capacity can work in parallel)

## Related Prompts

- [`../../05_Analytics-&-Performance/Predictive-Analytics/AI-Powered-B2B-SaaS-Predictive-Pipeline-Health-&-Revenue-Gap-Forecasting-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Predictive-Analytics/AI-Powered-B2B-SaaS-Predictive-Pipeline-Health-&-Revenue-Gap-Forecasting-Intelligence-Engine.md) — Once accounts become pipeline, use this to forecast which deals will close
- [`../../05_Analytics-&-Performance/Lead-Scoring-Analytics/AI-Powered-B2B-SaaS-First-Party-Behavioral-Signal-Scoring-&-Buyer-Intent-Analytics-Revenue-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Lead-Scoring-Analytics/AI-Powered-B2B-SaaS-First-Party-Behavioral-Signal-Scoring-&-Buyer-Intent-Analytics-Revenue-Intelligence-Engine.md) — First-party behavioral signal scoring to complement this third-party/firmographic model
- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-ABM-Target-Account-List-Building-&-ICP-Scoring-Intelligence-Engine.md) — ABM account list construction once Tier 1 accounts are identified
- [`../../05_Analytics-&-Performance/Intent-Data-Analytics/AI-Powered-B2B-SaaS-Third-Party-Intent-Data-Intelligence-&-Signal-to-Pipeline-Revenue-Activation-Analytics-Engine.md`](../../05_Analytics-&-Performance/Intent-Data-Analytics/AI-Powered-B2B-SaaS-Third-Party-Intent-Data-Intelligence-&-Signal-to-Pipeline-Revenue-Activation-Analytics-Engine.md) — Deep dive on interpreting intent data signals used in this propensity model

## Integration Tips

**6sense / Bombora / TechTarget:**
- Export weekly intent surge reports filtered to your top 10 intent topics. Paste the account list and percentile scores directly into this prompt as your "intent data" input. Accounts crossing the 70th percentile surge threshold should automatically trigger Tier 1 score recalculation. Set up a Zapier or Make automation to push new 70th+ percentile accounts from 6sense into your CRM with a "Propensity Tier 1" tag.

**Salesforce / HubSpot:**
- Create a custom field "Propensity Score" and "Propensity Tier" on the Account object. Run this prompt monthly, paste the output scores into a CSV, and mass-upload via import. Build a Salesforce list view filtered to "Propensity Tier 1 + No Active Opportunity" — this becomes your SDR's prioritized outbound call list each Monday.
- Set up an automated workflow: when an Account's Propensity Tier changes from 2 → 1, trigger a CRM notification to the assigned SDR/AE and create a follow-up task for same-day outreach.

**LinkedIn Sales Navigator:**
- Use the Tier 1 account list to build a saved account list in Sales Navigator. Set up "Job Change" alerts for VP Sales, CRO, and RevOps titles at all Tier 1 accounts — new hire alerts are your highest-urgency buying signal and should push an account to the top of the daily outreach queue automatically.

**Outreach / Salesloft / Apollo:**
- Create separate sequences for Tier 1 vs. Tier 2 accounts. Tier 1 sequences should include trigger-event personalization variables ([new hire name], [funding amount], [intent topic]) as merge fields pulled from your enrichment data. Tier 2 sequences can use more generic ICP pain-point messaging.

**Google Sheets / Airtable:**
- Build a "Propensity Score Tracker" spreadsheet with columns: Account Name, Industry, Employee Count, Tech Stack, Funding Stage, Intent Score, Trigger Event, Engagement Score, Stakeholder Score, Total Propensity Score, Tier, Last Rescored Date, SDR Owner, Days Since Last Touch. Refresh monthly. Color-code by tier for visual pipeline review in weekly GTM standups.

**Clay.com:**
- Use Clay to automate signal collection at scale. Set up waterfalls that pull from LinkedIn, Crunchbase, Clearbit, Bombora API, and G2 simultaneously for each account in your universe. Feed the enriched account data directly into this prompt monthly for automated batch rescoring of your full target universe.

## Troubleshooting

**Problem: I don't have access to third-party intent data (Bombora/6sense) — can I still build a useful propensity model?**
Yes — and your model may actually be more accurate than you think without it. Replace the intent dimension with first-party signals: website visits (even anonymous, by IP, using tools like RB2B or Albacross at ~$300/month), LinkedIn company page engagement data (free via LinkedIn Analytics), and G2 category-level intent (partially available on G2's free plan). First-party intent signals — a company's VP of Sales visiting your pricing page — are often stronger predictors than broad third-party topic surges. Start with hiring signals (free via LinkedIn Jobs and Apollo) and website visitor data, then add Bombora/6sense only once you've validated that intent signals correlate with your closed-won data.

**Problem: My Tier 1 account list is larger than my SDR team can work — I have 400 Tier 1 accounts and only 3 SDRs.**
Cap active Tier 1 accounts to SDR capacity (typically 80–120 accounts per SDR per month for high-touch outbound). Prioritize within Tier 1 by: (1) accounts with the most recent trigger event, (2) accounts with G2 competitive review activity (highest urgency), (3) accounts where you have a known contact identified. Shift remaining Tier 1 accounts into a "Tier 1 — ABM Only" bucket where they receive LinkedIn ad targeting and content nurture without direct SDR outreach, and promote the top replacements as SDR capacity opens up.

**Problem: My historical win data is limited (fewer than 30 customers) — the statistical sample is too small to build reliable signal weights.**
With <30 customers, don't attempt to calculate statistically significant signal weights from your own data. Instead, use industry benchmark signal weights as your starting model and validate against your limited sample directionally. The framework in this prompt reflects pattern weights established from analysis of thousands of B2B SaaS deals across growth-stage companies — it's a solid starting point. Run the model for 60 days, track which signals appeared in your Tier 1 accounts that converted, and recalibrate weights quarterly as your sample grows. A model with imprecise weights is still 2–3x better than random outbound targeting.

## Version History
- v1.0: Initial creation (auto-generated)
