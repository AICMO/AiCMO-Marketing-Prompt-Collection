# AI-Powered ABM Buying Committee Engagement Scoring & Multi-Stakeholder Deal Velocity Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** abm, b2b, analytics, buying-committee, deal-velocity, intent-data, enterprise

## Overview
This engine analyzes buying committee composition, scores individual stakeholder engagement across digital touchpoints, and predicts deal velocity by modeling multi-thread account coverage. Use it when your ABM programs need to move beyond account-level metrics and drive precision pipeline acceleration through stakeholder-level intelligence.

## Quick Copy-Paste Version

You are a B2B revenue analytics expert specializing in account-based marketing intelligence.

Analyze the following buying committee engagement data and produce a deal velocity score with actionable recommendations:

ACCOUNT: [Company Name]
OPPORTUNITY VALUE: $[ARR]
DEAL STAGE: [Stage]
CLOSE DATE TARGET: [Date]

BUYING COMMITTEE MEMBERS:
- [Name], [Title], [Engagement: email opens/clicks, web visits, content downloads, event attendance]
- [Name], [Title], [Engagement: data]
- [Name], [Title], [Engagement: data]

CONTENT CONSUMED: [List of assets, pages visited, topics researched]

INTENT DATA SIGNALS: [6sense/Demandbase/Bombora signals if available]

Produce:
1. Buying committee map with role classification (Economic Buyer, Champion, Technical Evaluator, User Buyer, Coach, Blocker)
2. Individual stakeholder engagement score (0-100) with rationale
3. Account-level multi-thread score (0-100) — penalize single-threaded deals
4. Deal velocity prediction: on track / at risk / stalled, with specific risk factors
5. Top 3 next-best actions for marketing to accelerate each at-risk stakeholder
6. Content gap analysis: what assets does each persona need but hasn't seen?
7. Recommended marketing plays for the next 14 days with channel, message, and owner

Flag any accounts where only 1-2 contacts are engaged — these are single-thread risk deals requiring immediate multi-stakeholder expansion.

## Advanced Customizable Version

ROLE: You are a Senior ABM Analytics Architect with deep expertise in enterprise B2B buying psychology, MEDDPICC deal qualification, and multi-stakeholder engagement modeling. You have access to intent data platforms (6sense, Demandbase, Bombora), CRM data (Salesforce), marketing automation (Marketo/HubSpot), and sales engagement tools (Outreach/SalesLoft).

OBJECTIVE: Generate a comprehensive buying committee engagement analysis and deal velocity intelligence report for a named account, producing prioritized actions for marketing and sales to accelerate pipeline to close.

CONTEXT:
- Company: [COMPANY_NAME]
- Industry: [INDUSTRY]
- Segment: [SMB/Mid-Market/Enterprise/Strategic]
- ACV: $[VALUE]
- Deal Stage: [STAGE_NAME] (Stage [1-6])
- Days in Current Stage: [DAYS]
- Forecast Category: [Pipeline/Best Case/Commit]
- Close Date: [DATE]
- Sales Rep: [REP_NAME]
- AE's Deal Assessment: [SUMMARY_OF_AE_VIEW]

BUYING COMMITTEE DATA:
For each contact, provide:
[
  {
    "name": "[Full Name]",
    "title": "[Job Title]",
    "department": "[Dept]",
    "seniority": "[C-Suite/VP/Director/Manager/IC]",
    "known_to_sales": [true/false],
    "engagement_signals": {
      "emails_sent": [N],
      "email_open_rate": "[%]",
      "email_click_rate": "[%]",
      "web_sessions_30d": [N],
      "pages_visited": ["[page1]", "[page2]"],
      "content_downloaded": ["[asset1]", "[asset2]"],
      "events_attended": ["[event1]"],
      "ads_clicked": [N],
      "sales_meetings": [N],
      "last_touch": "[DATE]"
    },
    "intent_signals": {
      "6sense_buying_stage": "[Awareness/Consideration/Decision/Purchase]",
      "bombora_surge_topics": ["[topic1]", "[topic2]"],
      "competitor_research": [true/false],
      "competitor_names": ["[comp1]"]
    }
  }
]

ACCOUNT-LEVEL INTENT:
- 6sense Account Score: [0-100]
- 6sense Buying Stage: [Stage]
- Surge Topics Last 30 Days: [list]
- Competitor Pages Visited: [list]
- Pricing Page Visits: [N] in [timeframe]
- Product Demo Requests: [N]

CONTENT CONSUMED (Account-Wide):
[List all assets, blog posts, case studies, comparison pages, pricing pages, ROI calculator interactions]

COMPETITOR INTELLIGENCE:
- Competitors known to be in deal: [list]
- Competitor content consumed by committee: [details]

CURRENT SALES MOTION:
- Sales activities last 30 days: [calls, emails, demos, proposals]
- Identified champion: [Name/Unknown]
- Executive sponsor identified: [Name/Unknown]
- Technical evaluator engaged: [Yes/No]
- Procurement/legal involved: [Yes/No]
- Mutual Action Plan shared: [Yes/No]

ANALYSIS FRAMEWORK — Produce all of the following:

## 1. BUYING COMMITTEE ROLE MAP
Classify each contact using the MEDDPICC + Challenger framework:
- Economic Buyer (controls budget, signs contract)
- Champion (internal advocate, builds internal case)  
- Technical Evaluator (validates product fit, integration)
- User Buyer (uses the product day-to-day)
- Coach (provides intel, guides seller)
- Blocker/Detractor (potential deal killer, resistance source)
- Unidentified (likely exists but not yet in CRM)

For each classified contact, provide:
- Role classification + confidence level (High/Medium/Low)
- Engagement quality score (0-100): weighted across recency, depth, breadth
- Engagement trend (Accelerating/Stable/Declining/Dark)
- Persona messaging alignment score (are they consuming content relevant to their role?)
- Recommended next marketing touch (channel, message type, asset)

## 2. MULTI-THREAD ACCOUNT SCORE (0-100)
Score formula considers:
- Number of unique contacts engaged in last 30 days (weight: 30%)
- Seniority distribution of engaged contacts (weight: 20%)
- Role coverage completeness: Economic Buyer + Champion + Technical = full house (weight: 25%)
- Engagement depth per contact: surface browsing vs. high-intent actions (weight: 15%)
- Recency of last engagement per contact (weight: 10%)

Benchmark:
- 80-100: Highly multi-threaded, strong committee coverage
- 60-79: Moderate coverage, 1-2 role gaps
- 40-59: Thin coverage, single-thread risk, intervention required
- 0-39: Critical single-thread risk, deal at risk of stalling or ghosting

## 3. DEAL VELOCITY PREDICTION
Classify as: ON TRACK / AT RISK / STALLED / ACCELERATING

Provide:
- Predicted close probability: [%]
- Estimated days to close (vs. original target)
- Top 3 velocity accelerators (what's working)
- Top 3 velocity decelerators (what's blocking or missing)
- Slip risk factors: single thread, no champion, no EB engaged, competitor actively evaluated, pricing page not visited

## 4. STAKEHOLDER ENGAGEMENT GAPS & CONTENT PRESCRIPTION
For each identified gap in the buying committee:
- Missing role: [Role Type]
- Why it matters to close: [rationale]
- Recommended identification tactic: [LinkedIn Sales Navigator search, referral from champion, LinkedIn ads targeting title+company, Demandbase audience]
- Content sequence to nurture once identified: [3-touch sequence with assets and messages]

For each known contact not consuming role-appropriate content:
- Current content consumed: [list]
- Missing content gap: [what they should have seen]
- Prescribed asset: [specific asset or content type to create]
- Delivery channel: [email, LinkedIn, retargeting, sales outreach]

## 5. 14-DAY MARKETING ACCELERATION PLAYBOOK
Produce a day-by-day or week-by-week action plan:

For each stakeholder, define:
- Day 1-3: Personalized email with social proof asset (customer story, ROI data) matched to their role
- Day 4-7: LinkedIn retargeting ad creative brief (headline, value prop, CTA) targeted to their title+company  
- Day 8-10: Sales rep outreach with specific talking point based on their content consumption
- Day 11-14: Follow-up with intent-triggered asset (e.g., if they visited pricing page, send pricing guide or ROI calculator)

Flag escalation triggers:
- If Economic Buyer has zero engagement → escalate to executive outreach program
- If competitor research is detected → trigger competitive battle card delivery to champion
- If deal is in stage [3+] and no Mutual Action Plan → trigger MAP delivery sequence

## 6. PIPELINE RISK SCORE & CRM UPDATE RECOMMENDATION
Generate a structured data output for Salesforce/HubSpot update:
{
  "account_multi_thread_score": [0-100],
  "deal_velocity_status": "[On Track/At Risk/Stalled/Accelerating]",
  "close_probability_marketing_model": "[%]",
  "buying_committee_completeness": "[%]",
  "champion_identified": [true/false],
  "economic_buyer_engaged": [true/false],
  "competitor_in_deal": [true/false],
  "recommended_next_action": "[single most important action]",
  "marketing_plays_activated": ["[play1]", "[play2]"],
  "days_to_projected_close": [N]
}

## 7. EXECUTIVE SUMMARY FOR AE BRIEFING
3-5 bullet points an account executive can read in 90 seconds before a meeting:
- Current committee status and key engagement insights
- Biggest risk factor and recommended mitigation
- Highest-signal buying behavior observed this week
- Specific ask of AE to unblock marketing's acceleration plays
- Next meeting recommendation with specific talk track

OUTPUT FORMAT: Structured report with sections as defined above. Use tables for stakeholder scorecards. Use bullet points for action items. Flag critical risks in [RED ALERT] blocks. Prioritize clarity for both marketing ops and sales leadership audiences.

## Example Input/Output

**Input Example:**

Account: Meridian Logistics Group  
Industry: Supply Chain / 3PL  
ACV: $180,000  
Stage: Stage 3 (Technical Evaluation)  
Days in Stage: 22 (avg is 14)

Buying Committee Data:
- Sarah Chen, VP Operations — 4 web sessions, downloaded ROI calculator, attended 1 webinar, last touch 3 days ago
- Marcus Webb, CTO — 1 email open, 0 clicks, 0 web visits, last touch 18 days ago
- Jennifer Okafor, Director of IT — 8 web sessions, visited integration docs 4x, downloaded API guide, last touch 1 day ago
- David Park, CFO — 0 engagement, not in CRM

6sense Account Score: 78/100, Buying Stage: Decision  
Bombora Surges: "warehouse management software," "3PL automation," "supply chain ROI"  
Competitor Research: Visited Blue Yonder comparison page twice

**Output Example:**

**Buying Committee Role Map:**

| Contact | Role Classification | Engagement Score | Trend | Gap |
|---|---|---|---|---|
| Sarah Chen, VP Ops | Champion | 74/100 | Stable | Needs exec sponsor connection |
| Marcus Webb, CTO | Technical Evaluator | 12/100 | Declining | 18-day dark — CRITICAL |
| Jennifer Okafor, Dir IT | Technical Evaluator | 88/100 | Accelerating | Strong — nurture with implementation content |
| David Park, CFO | Economic Buyer | 0/100 | Unknown | **Not in CRM — deal at risk** |

**Multi-Thread Account Score: 41/100 — SINGLE-THREAD RISK**

Risk factors:
- Economic Buyer (CFO) has zero engagement and is not in CRM
- CTO went dark 18 days ago — likely evaluating competitor
- Only Champion and one technical contact actively engaged

**Deal Velocity Status: AT RISK**
- Predicted close probability: 38% (vs. 65% at stage entry)
- Competitor Blue Yonder actively researched — Sarah Chen needs competitive battle card
- CFO not engaged in $180K deal = red flag at Stage 3

**14-Day Acceleration Playbook:**

Day 1-2: Deploy LinkedIn InMail to Marcus Webb (CTO) from sales rep — subject: "Integration architecture Q for Meridian's tech stack"  
Day 1-3: Email Sarah Chen with Blue Yonder vs. [Your Product] battle card — "How Meridian's peers made the switch"  
Day 3-5: Run targeted LinkedIn ads to David Park (CFO, Meridian Logistics) with CFO-specific ROI case study (3PL industry peer)  
Day 5-7: Sales rep to ask Sarah Chen: "Has David Park been looped in on the business case? Can we set up a 20-min CFO briefing?"  
Day 8-10: Jennifer Okafor → send implementation timeline and onboarding checklist (she's in technical evaluation mode — close this lane)  
Day 10-14: If Marcus Webb still dark, escalate to VP Sales for executive-to-executive reach-out to CTO

**CRM Update:**
{
  "account_multi_thread_score": 41,
  "deal_velocity_status": "At Risk",
  "close_probability_marketing_model": "38%",
  "buying_committee_completeness": "55%",
  "champion_identified": true,
  "economic_buyer_engaged": false,
  "competitor_in_deal": true,
  "recommended_next_action": "Identify and engage CFO David Park before end of week",
  "marketing_plays_activated": ["competitive-battle-card", "cfo-executive-briefing-sequence"],
  "days_to_projected_close": 47
}

## Success Metrics

- **Multi-thread coverage rate:** % of target accounts with 3+ stakeholders engaged (target: >60%)
- **Buying committee completeness:** % of deals with Economic Buyer + Champion + Technical Evaluator identified (target: >70% by Stage 3)
- **At-risk deal recovery rate:** % of "At Risk" flagged deals that return to "On Track" within 30 days of intervention
- **Deal velocity improvement:** Average days-in-stage reduction for accounts where playbook was activated (target: 15-25% reduction)
- **CRM data quality score:** % of Stage 3+ deals with complete buying committee data (target: >80%)
- **Marketing-sourced stakeholder identification rate:** % of new contacts identified via marketing plays (LinkedIn ads, intent-triggered outreach)
- **Win rate correlation:** Compare win rates for deals with multi-thread score >70 vs. <40 — validate model accuracy quarterly

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Buying-Committee-Engagement-&-Multi-Stakeholder-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`
- `../../05_Analytics-&-Performance/Account-Based-Marketing-Analytics/AI-Powered-ABM-Account-Intelligence-&-Revenue-Attribution-Engine.md`
- `../../02_Product-Marketing/Sales-Enablement/MEDDPICC-Deal-Qualification-&-Sales-Coaching-Intelligence-Engine.md`

## Integration Tips

**Salesforce:**
- Create a custom "ABM Multi-Thread Score" field on the Opportunity object (Number, 0-100)
- Use Flow automation to trigger this prompt via an AI integration (Einstein GPT or custom Apex callout) when an Opportunity enters Stage 3
- Map the JSON output fields to Opportunity custom fields for dashboard visibility
- Create an "ABM Risk" opportunity list view filtered by multi-thread score <50 for weekly sales-marketing review

**HubSpot:**
- Use Workflows to tag Deals with "At Risk" properties when engagement score thresholds are crossed
- Integrate with HubSpot's Contact Activity timeline to pull engagement data into the prompt automatically
- Use Sequences to execute the 14-day playbook directly from deal record

**6sense / Demandbase:**
- Pull account intent scores and buying stage classifications into your CRM daily via native integration
- Use 6sense Segments to auto-enroll accounts into advertising campaigns when multi-thread score drops below 50
- Set Demandbase Engagement Minutes as a field to include in the prompt context

**Outreach / SalesLoft:**
- Tag sequences with "ABM Acceleration" and tie execution to playbook triggers from this engine
- Use AI summary features to include stakeholder engagement context in sequence personalization fields

**Google Sheets / Looker Studio:**
- Export buying committee scoring table weekly to a shared Google Sheet for sales-marketing pipeline review
- Build a Looker Studio dashboard visualizing multi-thread scores across all Stage 3+ deals with drill-down by AE

**Zapier / Make:**
- Trigger: New Opportunity moves to Stage 3 in Salesforce → Call this prompt with account data → Write results back to Salesforce fields → Notify AE in Slack with executive summary

## Troubleshooting

**Problem:** Engagement data is incomplete — several contacts have no marketing touchpoints and unknown intent signals.  
**Solution:** Use LinkedIn Sales Navigator to identify missing buying committee members by title+company. Run a targeted LinkedIn Message Ad to those titles at the account specifically. Even 1-2 impressions and a profile visit signal will activate their presence. Prompt the AE to add them to CRM manually with a note to marketing.

**Problem:** The multi-thread score is high but the deal is still stalling.  
**Solution:** High engagement breadth with low depth (surface page visits, low open rates) can inflate scores. Add a "depth weight" override: if no contact has downloaded an asset, attended a demo, or had a meeting, cap the multi-thread score at 60 regardless of breadth. Depth signals (demo, ROI calculator, pricing page, mutual action plan) should be prioritized in scoring configuration.

**Problem:** The Economic Buyer is engaged but the Champion is dark.  
**Solution:** This is an executive-led deal without internal buy-in — a high-risk pattern. Activate an "Executive Sponsor at Risk" play: have the AE ask the EB directly who their internal project lead is, then route marketing to that person immediately. If no champion exists, the EB may be shopping casually without intent to close — adjust forecast accordingly.

## Version History
- v1.0: Initial creation (auto-generated)
