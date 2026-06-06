# AI-Powered B2B SaaS Churn Interview Program & Churned Customer Intelligence Mining Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, customer-research, churn-analysis, product-marketing, retention, voice-of-customer, revenue-intelligence

## Overview
This prompt engineers a fully automated program to recruit, interview, and mine intelligence from churned B2B SaaS customers — transforming departure data into product roadmap priorities, messaging corrections, and retention playbooks that reduce future churn. Use it when you're losing customers and don't know the real reasons why, or when your renewal and expansion revenue is underperforming versus benchmarks.

## Quick Copy-Paste Version

You are a senior B2B SaaS product marketing researcher specializing in churn intelligence. Design a complete churn interview program for my company and generate the first interview analysis.

My company: [What we do and our key value proposition]
ICP: [Company size, industry, primary buyer/user personas]
Average contract value: [$ ACV] | Average customer tenure before churn: [X months]
Current churn rate: [Monthly or annual %]
Primary churn reasons we currently track (if any): [e.g., "price, went with competitor, didn't use product"]

Churned customer segment to analyze: [e.g., "SMB customers who churned in the last 90 days after 6-18 months", or "Mid-market customers who churned at annual renewal"]

Produce the following:

1. CHURN INTERVIEW OUTREACH SEQUENCE — Write 3 emails (initial outreach, follow-up at Day 5, final follow-up at Day 10) to recruit churned customers for a 20-minute interview. Tone should be: curious and appreciative, never defensive or sales-y. Include a compelling reason for them to participate (e.g., gift card offer, product roadmap influence, industry report access).

2. INTERVIEW GUIDE — Create a 20-question interview guide structured in 5 sections:
   a. Context-setting (3 questions): What they were trying to accomplish, their role, their team context
   b. Adoption journey (4 questions): What worked, what didn't, where they got stuck
   c. Decision to leave (5 questions): Timeline of the decision, what triggered the final call, who was involved
   d. Competitive context (4 questions): What they moved to, why, what that solution does better
   e. Re-engagement potential (4 questions): What would have to be true for them to return, what feature or change would have prevented departure

3. ANALYSIS FRAMEWORK — Create an AI analysis prompt that can be applied to interview transcripts to automatically extract:
   - Primary churn driver (product gap / pricing / competitive loss / champion departure / use case mismatch / value not realized)
   - Secondary contributing factors
   - Specific product features mentioned as deficient
   - Specific competitors named and their cited advantages
   - Emotional tone of departure (frustrated / indifferent / regretful)
   - Win-back probability score (1-5) with rationale

4. INSIGHT SYNTHESIS TEMPLATE — Create a one-page insight report template that summarizes findings across 10+ interviews, including: top 3 churn patterns, product gaps to prioritize, messaging corrections needed, and 2-3 retention intervention recommendations.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS product marketing strategist with deep expertise in customer intelligence, churn analysis, and voice-of-customer programs. You've run churn interview programs at hypergrowth SaaS companies (Series B through public) and translated raw customer departure data into measurable product and revenue improvements.

CONTEXT:
Company: [Company name and what it does]
Category: [e.g., B2B project management, revenue intelligence, HR tech]
ICP Primary: [Company size, industry verticals, buyer title, user title]
ACV Range: [$ low to $ high]
Business Model: [Annual/monthly subscriptions, usage-based, seat-based]
Current Churn Rate: [X% monthly or Y% annual] vs. benchmark: [Z% for your segment]
Churn Segments to Analyze: [e.g., "SMB <50 employees churning in first 6 months" AND "Mid-market churning at annual renewal"]
CRM/CS Platform: [e.g., Salesforce + Gainsight, HubSpot + ChurnZero]
Primary CSM coverage model: [e.g., High-touch for Enterprise, tech-touch for SMB]

OBJECTIVE: Design and operationalize a continuous AI-powered churn interview program that generates actionable intelligence for product, marketing, and customer success — producing measurable improvements in retention within 90 days.

DELIVERABLES:

### MODULE 1: PROGRAM ARCHITECTURE & TARGETING

1.1 CHURN SEGMENTATION FRAMEWORK
Define 4-6 churn cohorts that warrant distinct interview tracks, based on:
- Tenure at churn (Early: 0-6 months, Mid: 6-18 months, Late: 18+ months)
- Contract size tier (SMB, Mid-Market, Enterprise)
- Churn type (non-renewal vs. mid-term cancellation vs. downgrade)
- Potential churn reason (competitive loss vs. product gap vs. economic)
For each cohort, specify: sample size target per quarter, interview track, primary intelligence goal.

1.2 RESPONDENT RECRUITMENT STRATEGY
Design a 3-touch outreach sequence for EACH cohort, with:
- Optimal timing after churn event (e.g., 2 weeks post-cancellation for SMB, 4 weeks for Mid-Market)
- Personalization variables to pull from CRM (tenure, last active feature, CSM name, use case)
- Incentive structure calibrated to ACV tier:
  * SMB (<$10K ACV): $50-75 Amazon/Visa gift card
  * Mid-Market ($10K-$50K ACV): $100-150 gift card OR proprietary industry benchmark report
  * Enterprise (>$50K ACV): Executive briefing with CPO/CMO + $200 charity donation in their name
- Subject line variants (3 per email) optimized for response rate
- Send time recommendations by persona

1.3 INTERVIEW CHANNEL STRATEGY
Define the optimal interview format for each cohort:
- 20-minute Zoom for Enterprise/Mid-Market (recorded with consent)
- 15-minute phone call for SMB
- Async video (Loom response) as fallback for hard-to-schedule accounts
- AI-facilitated async text interview (typeform-style) as last resort
Include scheduling automation workflow using Calendly + CRM + notification triggers.

---

### MODULE 2: INTERVIEW METHODOLOGY

2.1 MASTER INTERVIEW GUIDE (20-25 questions, adapt per cohort)

SECTION A — CONTEXT SETTING (5 min)
Questions designed to establish: their role and influence over the buying decision, team size and structure, the core business problem they hired your product to solve, and what "success" meant to them.

Sample questions (generate 5):
[AI generates based on company context, persona, and use case]

SECTION B — ADOPTION & VALUE REALIZATION JOURNEY (5 min)
Questions designed to map: onboarding experience quality, time-to-value, specific moments of delight or friction, feature adoption patterns, and where engagement declined.

Framework: Use the "Progress-Making Forces" model (Jobs-to-be-Done) to identify:
- Push factors: What frustrated them enough to consider leaving?
- Pull factors: What attracted them to the alternative?
- Anxiety: What made them hesitate to switch?
- Habit: What made them continue using even when frustrated?

Sample questions (generate 5):
[AI generates based on cohort and use case]

SECTION C — DEPARTURE DECISION (5 min)
Questions designed to uncover: the triggering event that started evaluation, decision timeline and urgency, who made the final call, evaluation criteria used.

Critical questions to always include:
- "Walk me through the moment you first thought 'this isn't working.' What happened?"
- "Who in your organization was involved in the decision to cancel?"
- "On a scale of 1-10, how much was the decision about our product vs. your budget or business circumstances?"
- "What would have had to be different for you to stay?"
Additional questions (generate 3):
[AI generates based on cohort]

SECTION D — COMPETITIVE ANALYSIS (5 min)
Questions designed to uncover: what alternative they moved to, specific capabilities that drove the switch, implementation experience comparison.

Include trigger question: "I won't take this personally — what does [competitor or 'your new solution'] do better?"
Additional questions (generate 3):
[AI generates based on known competitive landscape]

SECTION E — RE-ENGAGEMENT POTENTIAL (2 min)
Close every interview with: win-back framing, NPS-equivalent question, permission to follow up in 6 months.

2.2 INTERVIEW FACILITATION GUIDE
Write a facilitator briefing (for the PM or PMM running interviews) covering:
- Opening script to build rapport and reduce defensiveness
- Active listening cues: when to probe deeper vs. move on
- How to handle angry/venting customers productively
- When to pause and take verbatim notes vs. trust recording
- Closing protocol to maximize win-back potential

---

### MODULE 3: AI ANALYSIS ENGINE

3.1 TRANSCRIPT ANALYSIS PROMPT
Write the AI analysis prompt that processes each interview transcript and automatically outputs a structured JSON-compatible insight record containing:

{
  "interview_id": "[unique ID]",
  "account_segment": "[SMB/MM/Enterprise]",
  "tenure_at_churn_months": [number],
  "primary_churn_driver": "[one of: ProductGap | Pricing | CompetitiveLoss | ChampionDeparture | UseCaseMismatch | ValueNotRealized | EconomicPressure | Internal-ITBlock | Other]",
  "secondary_drivers": ["[list]"],
  "product_features_cited_as_deficient": ["feature_name: verbatim_quote"],
  "competitors_named": [{"name": "...", "advantage_cited": "..."}],
  "emotional_tone": "[Frustrated | Indifferent | Regretful | Neutral | Positive]",
  "winback_probability": "[1=impossible, 5=highly likely]",
  "winback_rationale": "[1-2 sentences]",
  "verbatim_gold_quotes": ["[3 most compelling quotes for internal sharing]"],
  "time_to_value_assessment": "[TTV achieved / TTV partially achieved / TTV not achieved]",
  "onboarding_issues_cited": ["[list]"],
  "recommended_internal_action": "[Product / Marketing / CS / Sales / No-action]"
}

3.2 CROSS-INTERVIEW PATTERN RECOGNITION PROMPT
Write the AI synthesis prompt that, given a batch of 10+ analyzed interviews, automatically produces:
- Ranked list of churn drivers by frequency and revenue impact
- Product gap cluster analysis (group related feature gaps into themes)
- Competitive win-rate breakdown by competitor
- Cohort comparison (does SMB churn for different reasons than Mid-Market?)
- Statistical confidence thresholds (flag patterns with < 3 data points as "hypothesis, not signal")
- Trend detection: is any churn driver increasing in frequency vs. prior quarter?

3.3 INSIGHT-TO-ACTION MAPPING ENGINE
For each identified churn pattern, automatically generate:

PRODUCT TEAM BRIEF:
- Pattern: [e.g., "37% of SMB churn in months 3-6 cited 'couldn't integrate with our stack' as primary driver"]
- Evidence: [3 verbatim quotes]
- Frequency: [X of Y interviews in this cohort]
- Revenue Impact: [Estimated ARR at risk if pattern persists at current rate]
- Recommended Product Action: [Specific feature or integration to prioritize]
- Urgency: [High/Medium/Low based on competitive risk]

MARKETING TEAM BRIEF:
- Messaging Gap Identified: [e.g., "We overpromise implementation speed; average time-to-value is 6 weeks, not '2 weeks' as stated on website"]
- Required Message Correction: [Specific page, email, or sales asset to update]
- Objection to Add to Sales Enablement: [New objection + recommended response]

CUSTOMER SUCCESS BRIEF:
- Early Warning Indicator Found: [e.g., "Customers who don't complete 3 key actions in Week 2 are 4x more likely to churn"]
- Intervention to Build: [Specific playbook trigger or automated email sequence]

---

### MODULE 4: PROGRAM OPERATIONS & CONTINUOUS IMPROVEMENT

4.1 QUARTERLY CHURN INTELLIGENCE REPORT
Design the template for a quarterly executive report that includes:
- Total interviews completed vs. target
- Churn driver breakdown with quarter-over-quarter trend
- Revenue at risk by churn pattern
- Top 3 interventions implemented and measured impact
- Win-back pipeline generated from interview program
- Net Promoter Score equivalent from churned customers

4.2 CLOSED LOOP MEASUREMENT SYSTEM
Define metrics to track whether churn intelligence is driving improvement:
- Retention rate improvement in targeted cohort (90-day, 180-day)
- Percentage of identified product gaps that shipped in next 2 quarters
- Win-back revenue attributed to interview program
- Reduction in "value not realized" churn as % of total

4.3 PROGRAM AUTOMATION ARCHITECTURE
Map the full automation workflow using [CRM + CS platform + email automation + survey tool + AI analysis]:

Trigger: Customer status changes to "Churned" in CRM
→ Wait 14 days (allow cooling-off period)
→ Automatically enroll in outreach sequence in [MAP]
→ If meeting booked: assign to PMM interview queue in Notion/Asana
→ Post-interview: upload transcript to AI analysis pipeline
→ AI generates structured insight record
→ Monthly: AI aggregates records and generates pattern report
→ Quarterly: Send executive summary to Product, Marketing, CS leadership

CONSTRAINTS:
- All outreach must be compliant with GDPR/CCPA (include unsubscribe, reference data use in privacy policy)
- Interview recordings require explicit verbal consent at start of call
- Anonymize all verbatim quotes before sharing with Product team unless customer gives explicit permission
- Win-back offers must be coordinated with Sales to avoid channel conflict

OUTPUT FORMAT:
Provide all components as copy-ready documents. Format interview questions as numbered lists. Format the analysis prompt as a system-level AI instruction. Format the operations workflow as a numbered process flow.

## Example Input/Output

**Input Example:**
Company: Pactflow — B2B SaaS API contract testing platform
ICP: Engineering-led mid-market and enterprise companies (200-5000 employees) with active microservices/API architecture, buyer = VP Engineering, Champion = Senior Engineer/Architect
ACV: $15,000-$180,000
Churn Rate: 18% annual (vs. 12% benchmark for developer tooling)
Churn Segments: Mid-market (50-500 employees) churning at 12-month renewal after 8-14 months tenure
CRM: Salesforce + Gainsight
Known churn reasons from CRM: "Price" (35%), "Went with competitor" (28%), "No longer needed" (22%), "Other" (15%)

**Output Example (Excerpt — Outreach Email 1):**

*Subject: A genuine question from the Pactflow team (and a small thank-you)*

Hi [First Name],

I'm [Your Name], Product Marketing at Pactflow. I saw your team decided not to renew last month, and I wanted to reach out — not to pitch anything, but to genuinely understand what happened.

We're on a mission to make API contract testing the standard for every engineering team, and we won't get there without honest feedback from teams like yours — especially when things didn't work out the way we hoped.

Would you be willing to spend 20 minutes with me on Zoom? In return, I'll send a $100 Amazon gift card and share our Q3 API testing industry benchmark report (unpublished, 1,200 respondents) as a thank-you.

[Schedule a time → Calendly link]

No sales pitch. No attempts to re-sell. Just genuine curiosity and deep appreciation for your time.

[Your Name]
Product Marketing, Pactflow

---

**Output Example (Excerpt — AI Transcript Analysis Output):**

{
  "interview_id": "CHI-2026-047",
  "account_segment": "Mid-Market",
  "tenure_at_churn_months": 11,
  "primary_churn_driver": "ValueNotRealized",
  "secondary_drivers": ["UseCaseMismatch", "ChampionDeparture"],
  "product_features_cited_as_deficient": [
    "Provider-driven testing: 'We're consumer-driven, and the UI kept defaulting to provider workflows — it slowed us down every session'",
    "CI/CD integration: 'The Jenkins plugin broke twice during our upgrade cycle, and support took 11 days to resolve it'"
  ],
  "competitors_named": [{"name": "Specmatic", "advantage_cited": "Open source, lower friction to get started, no seat licensing"}],
  "emotional_tone": "Frustrated",
  "winback_probability": 2,
  "winback_rationale": "Champion left the company; new VP Engineering prefers open-source tools; price sensitivity is real at $18K ACV for current team size.",
  "verbatim_gold_quotes": [
    "'If Pactflow had a free developer tier, we would have stuck around — the core engineers loved it but couldn't justify the cost to the new VP.'",
    "'The contract coverage reports were genuinely best-in-class. That's what we'll miss.'",
    "'Your onboarding documentation was honestly the best I've seen in any developer tool. The problem wasn't getting started — it was scaling the workflow to our whole team.'"
  ],
  "time_to_value_assessment": "TTV partially achieved",
  "onboarding_issues_cited": ["No team-level workflow templates for consumer-driven pattern"],
  "recommended_internal_action": "Product"
}

## Success Metrics

- **Interview response rate:** Target ≥ 20% of recruited churned customers book an interview (industry benchmark: 15-25% with incentive)
- **Insight-to-action rate:** ≥ 3 product or marketing changes per quarter traced to churn interview data
- **Retention improvement:** 10-15% improvement in targeted cohort churn rate within 2 quarters of acting on findings
- **Win-back conversion:** 5-8% of interviewed churned customers re-engage within 12 months post-interview
- **Pattern coverage:** By interview 15-20 per cohort, new insights should be < 20% novel (signaling pattern saturation)
- **Report completion:** Quarterly executive churn intelligence report delivered within 2 weeks of quarter close

## Related Prompts

- [Win-Loss Interview Program Design](./AI-Powered-B2B-Win-Loss-Interview-Program-Design-&-Competitive-Intelligence-Loop-Intelligence-Engine.md)
- [Voice of Customer Analysis](./AI-Powered-B2B-Continuous-Voice-of-Customer-Program-&-Revenue-Insight-Mining-Intelligence-Engine.md)
- [ICP Signal Intelligence & Continuous Customer Profile Refinement](./AI-Powered-ICP-Signal-Intelligence-&-Continuous-Customer-Profile-Refinement-Engine.md)
- [Churned Customer Win-Back Campaign](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-SaaS-Churned-Customer-Win-Back-&-Reactivation-Revenue-Intelligence-Engine.md)

## Integration Tips

- **Gainsight / ChurnZero:** Configure churn event to auto-trigger recruitment workflow via CRM webhook; use health score data to pre-populate interview context
- **Salesforce:** Create custom "Churn Interview" object linked to Account — log interview status, completion date, primary driver, win-back probability score for tracking and reporting
- **Chorus / Gong:** If customer was active in deals or renewals, mine call recordings for pre-churn sentiment signals to correlate with interview findings
- **Notion / Confluence:** Use the structured JSON output to auto-populate a product intelligence database; tag by feature area for PM team search
- **Slack:** Configure automated weekly digest to PM/CS Slack channels showing new interview insights by churn driver category
- **Calendly + HubSpot/Marketo:** Build interview scheduling automation — Calendly event triggers CRM status update, post-interview email, and gift card fulfillment workflow

## Troubleshooting

**Problem: Response rate below 10% despite incentives.**
Solution: Add personalization — reference their specific use case and tenure ("I saw your team was using Pactflow primarily for payment API testing over the last 11 months"). Send from the CEO or CPO email address rather than a generic marketing address. Test a higher-value incentive ($150 vs. $75) for mid-market segments. Try async video (Loom) as an alternative for time-constrained engineering leaders.

**Problem: Customers only repeat "price" as the reason and won't go deeper.**
Solution: Price is almost always a proxy for undelivered value. Use the reframe technique: "I completely understand price is a factor — and I want to be honest with you. If the product had delivered [specific outcome they were hoping for], would price still have been the dealbreaker?" This usually opens the real conversation. Document both the surface reason and the underlying one separately.

**Problem: Analysis reveals contradictory signals across cohorts (SMB says product is too complex, Enterprise says it lacks depth).**
Solution: This is actually valuable data about product-market fit fragmentation. Separate the cohort analyses and present them as distinct recommendations. Flag to product and leadership that the product may be serving two incompatible ICPs, triggering a segmentation and positioning review.

## Version History
- v1.0: Initial creation (auto-generated)
