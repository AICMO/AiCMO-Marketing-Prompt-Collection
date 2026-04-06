# AI-Powered B2B Sales Diagnostic Tool & Personalized Action Plan Intelligence Engine - Build Consultative Assessment Tools That Qualify, Educate, and Close

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b, interactive-content, sales-enablement, lead-generation, personalization, conversion, demand-generation, pipeline-acceleration

## Overview
Designs and scripts a complete B2B diagnostic assessment tool that pinpoints a prospect's specific operational, strategic, or technical problem, generates a personalized scored report with prioritized action recommendations, and produces the full content infrastructure — assessment logic, response copy, follow-up email sequences, and sales handoff intelligence — that an AI agent can deploy as a self-service web experience or sales-guided discovery tool. Use it when you want to convert expert consulting knowledge into a scalable, repeatable pipeline acceleration asset that creates urgency by making the cost of inaction visible.

## Quick Copy-Paste Version

You are a B2B product marketing strategist specializing in consultative interactive content and diagnostic selling tools. Design a complete sales diagnostic assessment that helps [Target Buyer] identify and quantify [Specific Problem] and receive a personalized action plan.

Company/Product: [e.g., Stackwise AI — data pipeline observability platform for data engineering teams]
Target Buyer: [e.g., VP of Data Engineering or Data Engineering Manager at Series B–D SaaS companies with 50–300 engineers]
Core Problem We Solve: [e.g., data teams can't detect silent pipeline failures before they corrupt dashboards and break downstream models]
Diagnostic Title: [e.g., "Data Pipeline Health Diagnostic — Discover Your Biggest Hidden Risk in 4 Minutes"]

Design the following complete diagnostic system:

1. DIAGNOSTIC FRAMEWORK (8–12 questions)
   - Map questions to 3–4 diagnostic dimensions (e.g., Visibility, Reliability, Recovery Speed, Team Process)
   - Each question should force a choice that reveals severity — no neutral "it depends" options
   - Score each answer 1 (healthy) to 4 (critical risk)
   - Include 2–3 questions that surface the quantified business cost (pipeline downtime frequency, hours to detect failure, number of incidents per month)

2. SCORING & RESULT TIERS
   - Define overall score bands:
     * 0–25 (Critical): immediate revenue risk, reactive firefighting mode
     * 26–50 (At Risk): problems are known but unresolved, technical debt accumulating
     * 51–75 (Developing): some processes in place, but coverage gaps remain
     * 76–100 (Advanced): proactive detection, fast recovery, strong team process
   - For each tier: write a 3-sentence "Your Situation" narrative, quantify average business cost for this tier (use industry research or reasonable estimates), and list the top 3 specific problems companies at this tier experience

3. PERSONALIZED ACTION PLAN TEMPLATE
   - Based on score + dimension breakdown, prescribe a prioritized action plan:
     * Quick Wins (Week 1–2): 2–3 things they can change immediately without budget
     * Tactical Fixes (Month 1–3): Specific process, tooling, or workflow changes
     * Strategic Initiatives (Quarter 2+): Infrastructure investments and team capability building
   - For each action, estimate: time to implement, who owns it, measurable outcome

4. CTA LOGIC BY SCORE
   - Critical (0–25): "Get an emergency architecture review" — direct to SDR-booked call
   - At Risk (26–50): "See how companies like yours fixed this in 90 days" — case study + demo offer
   - Developing (51–75): "Get your personalized implementation roadmap" — gated PDF download + nurture
   - Advanced (76–100): "Benchmark against the top 10% of data teams" — community invite + expansion offer

5. FOLLOW-UP EMAIL SEQUENCE (4 emails)
   - Email 1 (Immediate — 0 min): Personalized score delivery with top 3 findings specific to their answers
   - Email 2 (Day 2): "The #1 thing [their tier] companies fix first" — specific, tactical, no pitch
   - Email 3 (Day 5): Case study of a company with similar diagnostic profile — before/after story
   - Email 4 (Day 10): "How has your pipeline health changed?" — re-engagement + CTA escalation

6. SALES HANDOFF BRIEF
   - One-page diagnostic summary for the AE/SDR: prospect's score, top 3 risk areas, likely objections based on their answers, recommended discovery questions to ask in the first call

Output the complete diagnostic as a structured implementation brief that a no-code tool builder (Outgrow, Typeform, Tally, involve.me) can configure directly — include exact question wording, answer options, scoring weights, and conditional logic rules.

## Advanced Customizable Version

ROLE: You are a Senior B2B Product Marketing Strategist and Consultative Selling Expert with 15+ years of experience designing interactive diagnostic tools for enterprise software, SaaS, and professional services firms. You understand how to translate deep domain expertise into structured assessment frameworks that surface buyer pain with surgical precision — making invisible problems visible, quantifying the cost of inaction, and engineering urgency without manufactured pressure. You've built diagnostic tools that generate qualified pipeline for companies like MongoDB (database infrastructure), Snyk (developer security), and Gong (revenue intelligence), where the diagnostic itself becomes a trusted market asset that prospects share internally with buying committee members. You combine behavioral psychology (loss aversion, the IKEA effect, commitment and consistency), B2B buying science (challenger selling, SPIN discovery, MEDDIC qualification), and content marketing strategy (interactive content driving 2x engagement vs. static assets) to create tools that close the gap between awareness and action.

OBJECTIVE: Design a complete, ready-to-deploy B2B diagnostic assessment tool — including the assessment framework, scoring architecture, personalized content for every result segment, follow-up automation, and sales handoff intelligence — that an AI agent can orchestrate end-to-end without human intervention from first touchpoint through sales-ready handoff.

---

COMPANY & PRODUCT CONTEXT:
- Company Name: [e.g., Stackwise AI]
- Product Description: [What it does in one sentence — avoid jargon]
- Category / Space: [e.g., Data Observability, Revenue Intelligence, Security Posture, Marketing Attribution]
- ICP Definition:
  * Job Titles: [e.g., VP Data Engineering, Director of Analytics, Data Engineering Manager]
  * Seniority Level: [e.g., Manager, Director, VP/SVP]
  * Company Profile: [e.g., Series B–D SaaS, 200–2,000 employees, >50 data engineers]
  * Buying Trigger Events: [e.g., recent data incident, new compliance requirement, scaling team beyond 20 engineers]
  * Annual Contract Value: [e.g., $40K–$200K ACV, 60-day average sales cycle]
  * Primary Competitor: [e.g., Monte Carlo, Bigeye, Soda — so our diagnostic differentiates on dimensions they don't measure]

DIAGNOSTIC DESIGN SPECIFICATIONS:
- Diagnostic Name: [e.g., "B2B Data Pipeline Health Assessment" / "Revenue Operations Readiness Diagnostic" / "Cybersecurity Posture Score"]
- Core Problem Being Diagnosed: [e.g., "Inability to detect and recover from silent data pipeline failures before they reach business stakeholders"]
- Business Cost of This Problem: [e.g., "Fortune 500 companies lose avg. $1.7M per data quality incident; mid-market companies report 4–8 hours of remediation time per event, occurring 3–5 times per month"]
- Diagnostic Dimensions to Assess (3–4 categories):
  * Dimension 1: [e.g., Observability Coverage — how much of the pipeline has automated monitoring?]
  * Dimension 2: [e.g., Detection Speed — how quickly does the team know when something breaks?]
  * Dimension 3: [e.g., Recovery Process — how structured is the incident response workflow?]
  * Dimension 4: [e.g., Team Maturity — does the team have dedicated data quality ownership?]
- Number of Questions: [e.g., 10 questions, 2–3 per dimension]
- Completion Time Target: [e.g., 4–6 minutes — do not exceed 12 questions]
- Tone: [e.g., Peer-level consultant / Direct / Data-driven / Non-judgmental]

---

SECTION 1: ASSESSMENT ARCHITECTURE

Design the complete question set using these principles:
- BEHAVIORAL SPECIFICITY: Ask about what they DO, not what they THINK. "When a pipeline fails, how does your team typically find out?" reveals more than "How would you rate your monitoring?"
- FORCED REVELATION: Every answer option must clearly map to a severity tier — no neutral midpoint options that let prospects self-rate as "moderate" to avoid commitment
- QUANTIFICATION ANCHORS: Include 2–3 questions that force the prospect to name a number (incidents per month, hours to detect, % of pipelines monitored) — these become the basis of their personalized ROI calculation
- BUYING SIGNAL CAPTURE: Include 1–2 questions that reveal timeline, urgency, and budget (e.g., "How often does this problem come up in executive conversations?")
- INTERNAL SELLING AMMUNITION: Design questions so that a Champion who shares the diagnostic results internally will trigger concern from the economic buyer

For each of the [3–4] dimensions, produce:
- 2–3 questions with 4 answer options each
- Scoring weight for each answer (1=healthy, 4=critical)
- Conditional logic: "If they answer X on Q3, show follow-up question Y"
- The insight this question cluster reveals about their operational maturity

---

SECTION 2: SCORING ENGINE & RESULT SEGMENTATION

Build a multi-dimensional scoring architecture:

OVERALL SCORE CALCULATION:
- Weighted average across dimensions (assign % weight to each dimension based on business impact)
- Output: Score 0–100, Percentile vs. industry benchmark (use plausible estimates)
- Dimension sub-scores: Separate scores for each category (e.g., Observability: 34/100, Detection: 67/100)

RESULT TIER DEFINITIONS (4 tiers):
For each tier, produce:
a) TIER LABEL & SCORE RANGE: [e.g., "Pipeline Blind Zone" (0–25) / "Early Warning" (26–50) / "Controlled Operations" (51–75) / "Proactive Reliability" (76–100)]

b) SITUATION NARRATIVE (150 words): Written as "You are..." — second person, specific, empathetic, not condescending. Describe exactly what their team's day looks like at this tier. Include: what they're firefighting, what they're missing, and what the board/leadership sees vs. what's actually happening.

c) QUANTIFIED BUSINESS COST: 3 specific cost/risk metrics for this tier. Calculate in: engineering hours lost/month, incident frequency, business stakeholder trust erosion (e.g., "teams at this tier report 6.2 data incidents per month, consuming avg. 27 engineering hours in remediation — $216K in eng. labor cost annually at $8K/month blended rate").

d) TOP 3 PROBLEMS AT THIS TIER: Specific, named problems with consequences. Not "poor monitoring" — "Your data team learns about failures from a Slack message from the analytics lead, not from automated alerting, meaning 2–4 hours pass before remediation begins."

e) WHAT COMPANIES AT THE NEXT TIER HAVE DONE: 2–3 specific changes that elevated companies from this tier to the next. Makes the path forward concrete without being a product pitch.

---

SECTION 3: PERSONALIZED ACTION PLAN GENERATOR

For each tier + dimension combination, generate a prioritized action plan with three time horizons:

QUICK WINS (Week 1–2, zero additional budget required):
- 2–3 immediate process changes the team can implement this week
- Each action: What to do, who owns it, how to measure success in 2 weeks
- Frame as "wins your team will feel immediately" — builds momentum and goodwill

TACTICAL FIXES (Month 1–3, minimal tooling investment):
- 3–4 workflow, process, or lightweight tooling changes
- Estimate: time to implement, rough cost, measurable outcome at 90 days
- Include: internal communication template for getting buy-in from the manager/VP

STRATEGIC INITIATIVES (Quarter 2+, requires stakeholder alignment and budget):
- 2–3 infrastructure, platform, or organizational changes
- Include: business case framing for internal approval ("Here's how to present this to your VP of Engineering")
- Connection to company-level OKRs this solves (e.g., "Engineering reliability → NPS → expansion revenue")

---

SECTION 4: PERSONALIZED FOLLOW-UP CONTENT ENGINE

EMAIL 1 — RESULTS DELIVERY (Sent immediately upon completion):
Subject line: "Your [Diagnostic Name] Results: [Tier Label] ([Score]/100)"

Structure:
- Opening: Acknowledge their score, their top risk area, and the specific answer that revealed the most critical gap
- 3 key findings: Pulled from their specific answers — not generic tier copy
- Personalized benchmark: "You scored higher than X% of [ICP title]s we've assessed — here's what separates the top 25%"
- One specific action they can take TODAY (no product pitch)
- CTA: Tier-appropriate (see CTA logic in Quick Version above)

EMAIL 2 — TACTICAL INSIGHT (Day 2–3):
Subject: "The one thing [their tier]-level teams fix first"
- Specific, tactical advice for their tier and lowest-scoring dimension
- Zero product mention — pure value
- 1 internal resource they can share (template, framework, or checklist)
- Soft CTA: "Is this useful? Hit reply — I read all responses"

EMAIL 3 — SOCIAL PROOF (Day 5–7):
Subject: "[Similar Company] had a [X] score. Here's what changed in 90 days."
- Case study of a customer with a similar diagnostic profile (same tier, same top risk area)
- Structure: Situation → Diagnostic finding → Action taken → Specific measurable outcome
- Bridge to their situation: "You have [X] in common with [Customer]. Here's the one difference in their approach."
- CTA: "See the full implementation story" → Case study download or demo offer

EMAIL 4 — RE-ENGAGEMENT (Day 10–14):
Subject: "Quick check: has your [problem area] improved?"
- Acknowledge time has passed since their diagnostic
- Ask one specific question about whether their situation has changed
- Offer a "30-minute diagnostic debrief" call — positioned as helping them interpret their results, not selling
- CTA: Calendar link for "Diagnostic Debrief" call (sales call disguised as consultation)

---

SECTION 5: SALES HANDOFF INTELLIGENCE BRIEF

When a prospect scores in Critical or At Risk and meets ICP criteria, auto-generate a Sales Handoff Brief:

STRUCTURE:
- Prospect Name, Company, Title (from form capture)
- Diagnostic Score: Overall + dimension breakdown
- Top 3 Risk Areas: Specific, tied to their exact answers
- Quantified Business Cost: Their personalized cost estimate based on answers
- Buying Signal Indicators: Which answers suggest urgency, authority, or active evaluation
- Recommended Opening: "Based on their score, open with: 'I noticed [specific finding from their diagnostic]. Most teams we work with at that stage are dealing with [specific consequence] — is that showing up for you?'"
- Suggested Discovery Questions: 5 questions specific to their diagnostic profile
- Potential Objections & Responses: Based on their tier and dimension gaps
- Competitive Context: If they mentioned using a competitor in the assessment, provide counter-positioning
- Internal Champion Opportunity: Identify if this person has the profile to be a Champion (individual contributor who benefits + access to decision-maker) vs. Economic Buyer (needs executive framing and business case)

---

SECTION 6: IMPLEMENTATION SPECIFICATIONS

Produce a complete technical implementation brief for deploying in a no-code tool (Outgrow / Typeform / Tally / involve.me):

- Question flow with exact wording and answer copy
- Scoring formula: Question weights, dimension weights, tier thresholds
- Conditional logic map: Show branching paths for key question responses
- Required form fields for CRM capture: Name, Work Email, Company, Title, Company Size, "How did you hear about us?"
- Webhook configuration: Events to fire to HubSpot/Salesforce (assessment started, assessment completed, score tier, dimension scores)
- Custom properties to create in CRM: diagnostic_score, diagnostic_tier, top_risk_dimension, assessment_completion_date
- UTM tracking: How to tag diagnostic links for attribution across paid, organic, and sales-shared links
- A/B test recommendations: 2 elements to test in first 90 days (diagnostic title, first question framing)

## Example Input/Output

**Input Example:**

Company: Stackwise AI — data pipeline observability platform
Target Buyer: Data Engineering Managers at Series B–D SaaS companies, 100–500 engineers
Core Problem: Teams don't know pipelines are failing until business stakeholders complain
Diagnostic: "Data Pipeline Health Assessment"
Dimensions: Observability Coverage, Detection Speed, Recovery Process, Team Ownership
ACV: $55K, 55-day avg sales cycle
Primary Competitors: Monte Carlo, Bigeye

**Output Example (Excerpt):**

---

**Diagnostic Name:** Data Pipeline Health Assessment — Find Your Hidden Risk in 4 Minutes

**Sample Question — Dimension: Detection Speed**
*"When a data pipeline fails silently (no error thrown, just wrong data), how does your team typically find out?"*

A) A business stakeholder sends a Slack message or files a ticket [Score: 4 — Critical]
B) An analyst notices the dashboard looks wrong during their work [Score: 3 — At Risk]
C) An automated alert fires, but usually 1–4 hours after the failure [Score: 2 — Developing]
D) Our monitoring detects anomalies within 15 minutes and pages the on-call engineer [Score: 1 — Healthy]

**Scoring Logic:** Detection Speed dimension weight = 35% of total score (highest weight because detection latency directly correlates to business impact and is the primary differentiator for Stackwise AI vs. competitors)

---

**Result Tier: "Pipeline Blind Zone" (Score: 0–25)**

*Your Situation:*
Your data team is operating in reactive mode — and you know it. Business stakeholders are your monitoring system, which means every data incident becomes a trust incident before your team even knows there's a problem. Your engineers are skilled, but they're spending 20+ hours per week on incident response that's indistinguishable from guesswork. You've talked about building better monitoring internally, but every sprint it loses to feature work. The analytics team has started adding a mental asterisk to every dashboard — "verify before presenting" — and your VP of Product asked last quarter why the churn dashboard was wrong again. This is fixable. But the window before it becomes a cultural and organizational problem is shorter than it seems.

*Quantified Business Cost:*
- Average incidents per month at this tier: 6.2 pipeline failures reaching business stakeholders
- Average remediation time: 4.5 hours per incident × 2 engineers = 9 engineering hours
- Monthly engineering cost of reactive incidents: ~$18,000 at $2K/engineer/week blended rate
- Annual impact: $216,000+ in engineering labor, not counting the cost of business decisions made on bad data

*Action Plan Excerpt:*

**Quick Win (This Week, Zero Budget):**
→ Create a shared "Data Incident Log" in Notion/Confluence. Every time a business stakeholder reports a data problem, log: date, who reported it, which pipeline, time to detection, time to resolution. After 30 days, you'll have the internal business case for infrastructure investment — in your own team's words.

**Owner:** Data Engineering Lead or any senior engineer
**Measurement:** 30-day incident frequency count, detection time average
**Expected Outcome:** Visibility into true incident volume that's currently invisible in your metrics

---

**Sales Handoff Brief (Auto-Generated):**

> **Prospect:** Sarah Chen, Head of Data Engineering, Cloudleap Inc. (SaaS, 220 engineers)
> **Score:** 18/100 — Pipeline Blind Zone
> **Top Risk:** Detection Speed (score: 9/25) — Reporting via business stakeholders, avg. 3.5 hours to detection
> **Quantified Cost Estimate:** ~$194K/year in reactive engineering labor based on reported incident frequency
> **Urgency Signal:** Answered "yes" to "Has this problem come up in exec conversations in the last 90 days?"
> **Recommended Opening:** "I saw you completed our pipeline health diagnostic — your detection speed score of 9 stood out. Most teams we talk to at that level are getting incident reports from Slack before their monitoring fires. Is that what's happening at Cloudleap?"
> **Top Discovery Question:** "When did you last have a data incident that your VP of Product or CEO noticed before you did?"

## Success Metrics

- **Completion Rate:** Target >65% of diagnostic starts complete all questions (industry avg: 45–55% for quizzes; diagnostics score higher due to personalization promise)
- **Email Capture Rate:** >80% of completions provide a valid work email (vs. ~40% for gated PDF downloads)
- **Qualified Lead Rate:** >35% of completions meet ICP criteria (company size, title, industry) — diagnostic self-selects relevant buyers
- **Sales Acceptance Rate:** >70% of Critical/At Risk handoffs accepted by sales as sales-qualified (vs. ~40% for typical MQLs)
- **Pipeline Contribution:** Track diagnostic-sourced pipeline separately in CRM — target 15–25% of total inbound pipeline within 6 months of launch
- **Sales Cycle Impact:** Compare avg. sales cycle for diagnostic-sourced leads vs. standard inbound — diagnostic leads should close 10–20% faster due to pre-qualification and urgency creation
- **Content Shareability:** >20% of completions share their results internally (forward the email) — indicates Champion activation and internal selling motion initiated

## Related Prompts

- [B2B Buyer Assessment Quiz Lead Generation Engine](./B2B-Buyer-Assessment-Quiz-Lead-Generation-Engine.md) — Top-of-funnel quiz for initial prospect engagement and lead capture
- [AI-Powered ROI Calculator Lead Generation Engine](./AI-Powered-ROI-Calculator-Lead-Generation-Engine.md) — Quantify financial return to accelerate deal velocity
- [AI-Powered Organizational Maturity Assessment & Benchmark Report Engine](./AI-Powered-Organizational-Maturity-Assessment-&-Benchmark-Report-Engine.md) — Benchmark-driven maturity scoring for category leadership positioning
- [AI-Powered Conversational Marketing & Chatbot Lead Qualification Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-Conversational-Marketing-&-Chatbot-Lead-Qualification-Intelligence-Engine.md) — Real-time chatbot-based qualification as a complement to async diagnostics

## Integration Tips

- **HubSpot:** Create a custom "Diagnostic Score" contact property (number field) and "Diagnostic Tier" property (dropdown). Use HubSpot workflows to auto-enroll scored contacts into tier-specific email sequences and notify assigned SDR/AE when score falls in Critical/At Risk range. Use Contact Score to boost MQL threshold for diagnostic completers.
- **Salesforce:** Map diagnostic results to Lead fields using Zapier or native webhook. Create a custom "Diagnostic Intelligence" section on the Lead/Contact record visible in Sales Cloud. Configure assignment rules to route Critical-tier leads directly to senior AEs vs. SDR sequence.
- **Outgrow/involve.me:** Use these no-code platforms to build the diagnostic UI with conditional logic. Connect via Zapier to HubSpot/Salesforce. Enable "partial lead capture" — collect email before showing results to reduce abandonment without blocking completion.
- **Slack:** Use Zapier or HubSpot automation to post a Slack notification to the #sales-alerts channel when a Critical-tier completion occurs with ICP-matching attributes — enables real-time outreach while the prospect is still engaged.
- **Notion/Confluence:** Embed diagnostic link in sales outreach templates so AEs can send prospects the diagnostic as a pre-meeting "homework" assignment — "Complete this 4-minute assessment before our call so I can tailor the conversation to your specific situation."
- **LinkedIn Ads:** Use diagnostic completion audiences as retargeting seeds. Completers who didn't book a demo get a LinkedIn retargeting campaign with case study content matching their tier result. Use Matched Audiences to suppress diagnostic completers who already booked from demo campaigns.
- **Google Sheets:** Export diagnostic responses weekly to a Google Sheet using Zapier for a scoring review meeting. Identify patterns in which answer combinations correlate with fastest closes — use to refine scoring weights quarterly.

## Troubleshooting

**Problem: Diagnostic completion rate is below 50%**
Solution: The diagnostic is too long or the value exchange isn't clear upfront. Audit: (1) Are you asking for email before showing any results? Move email capture to after Q4 of 10 to build commitment first. (2) Does the intro screen clearly state the value ("See how you compare to 1,200 data teams" beats "Take our assessment"). (3) Are questions >15 words? Cut question length by 40%. (4) Add a progress bar — visibility of progress increases completion by 28%.

**Problem: Sales team ignores diagnostic handoffs and treats them like standard form fills**
Solution: Diagnostic handoffs must be visually different from standard MQLs in the CRM. Create a custom "Diagnostic Lead" view in Salesforce/HubSpot that shows: Score, Tier, Top Risk Area, and the specific "Recommended Opening Line" generated by the AI. Run a 30-minute training session showing reps exactly how to open a call using the diagnostic data — role-play with the handoff brief as the script. Track diagnostic-sourced pipeline separately and share win rates weekly in the sales all-hands until adoption is habitual.

**Problem: High completion rate but low ICP match (personal emails, small companies)**
Solution: Add a company size qualifier question early in the diagnostic flow ("How many engineers are on your data team?") with an answer threshold. Use conditional logic to show a "This diagnostic is optimized for teams of 20+ engineers" message and redirect small-team completers to a different resource (documentation, community, self-serve trial) rather than routing them to sales. Add work email validation at the form level to filter personal addresses before they enter the CRM.

## Version History
- v1.0: Initial creation (auto-generated)
