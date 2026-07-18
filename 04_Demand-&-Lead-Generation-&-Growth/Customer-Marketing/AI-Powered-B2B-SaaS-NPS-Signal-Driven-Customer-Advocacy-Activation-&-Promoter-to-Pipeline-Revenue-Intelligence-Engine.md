# AI-Powered B2B SaaS NPS Signal-Driven Customer Advocacy Activation & Promoter-to-Pipeline Revenue Intelligence Engine - Systematic Conversion of Satisfaction Signals Into Advocates, Reviews, References & Net-New Pipeline

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, customer-marketing, nps, csat, advocacy, promoter, pipeline, referral, reviews, g2, saas, customer-led-growth, revenue-intelligence

## Overview
Designs a complete AI-orchestrated system that intercepts NPS and CSAT survey responses in real time, segments respondents by score and intent, and automatically activates Promoters into revenue-generating advocacy roles — G2 reviews, reference calls, warm introductions, co-marketing participation, and community evangelism — while routing Detractors to CS recovery programs before they churn or post negative reviews publicly. Use this when you're sending NPS surveys but not systematically converting high scores into revenue actions, or when advocacy and pipeline are managed as separate programs with no feedback loop between them.

## Quick Copy-Paste Version

You are a B2B SaaS customer marketing strategist specializing in converting customer satisfaction signals into revenue. Design a complete NPS/CSAT signal activation system that turns survey responses into advocacy actions and measurable pipeline.

**Company profile:**
- Product: [e.g., marketing automation platform, revenue intelligence SaaS, HR tech]
- ARR: [$X] | Stage: [Series A/B/C/Growth]
- Customer base: [#] paying accounts | [#] trackable contacts
- NPS: [overall score] | Promoters: [X%] | Passives: [X%] | Detractors: [X%]
- Survey cadence: [Relationship NPS: quarterly/biannual | Transactional CSAT: post-onboarding/post-support]
- Current advocacy state: [No program / Informal / Formal but low conversion]

**Revenue context:**
- G2 reviews today: [#] | Target: [#]
- Active references available: [#] | Demand from sales: [# reference requests/month]
- Customer-sourced pipeline last quarter: [$X or unknown]
- Current NPS follow-up process: [None / Manual outreach by CS / Partially automated]

**Tech stack:**
- Survey tool: [Delighted/Medallia/Qualtrics/Wootric/HubSpot]
- CRM: [Salesforce/HubSpot]
- MAP: [Marketo/HubSpot/Pardot]
- CS platform: [Gainsight/ChurnZero/Totango/None]
- Advocacy platform: [Influitive/Orca/ReferenceEdge/None]

Design:
1. **NPS Signal Segmentation Model** — how to classify every NPS response (score + verbatim text) into an advocacy propensity tier using AI sentiment analysis, not just the 0-10 score
2. **Promoter Activation Cascade** — the automated sequence that converts a Promoter (score 9-10) into a specific advocacy action within 72 hours of survey submission, before their enthusiasm fades
3. **Passive Conversion Playbook** — how to move Passives (7-8) into Promoter territory through targeted engagement, feature adoption nudges, and milestone celebration
4. **Detractor Recovery & Reputation Defense** — automated CS escalation, closed-loop resolution tracking, and proactive reputation management before negative reviews appear on G2/Capterra
5. **Advocacy Attribution to Revenue** — how to track which NPS-triggered advocacy actions influenced pipeline creation and closed revenue
6. **Survey Cadence Architecture** — relationship NPS, transactional CSAT, and product NPS timing to maximize signal quality without survey fatigue

Be specific about trigger logic, automation rules, and how each response type flows through your MAP and CRM. No generic "follow up with happy customers" advice — give me the exact activation playbook.

## Advanced Customizable Version

### Role & Context
You are a Senior Customer Marketing Manager at a B2B SaaS company with a mandate to build a measurable, AI-automated system that converts every NPS and CSAT survey response into a downstream revenue action — turning Promoters into advocates who generate pipeline, recovering Detractors before they churn or post negative reviews, and systematically moving Passives toward advocacy readiness. Your North Star metric is "Advocacy-Generated Pipeline" — the dollar value of opportunities created where an NPS-triggered advocacy action (review, reference, warm introduction, co-marketing) played an attributable role. You own the intersection of customer satisfaction data and revenue generation.

**Company context:**
- Company: [Company Name]
- Product category: [e.g., Revenue Operations / Cybersecurity / Data Platform / HR Tech / Marketing Automation]
- ARR: [$X] | Stage: [Series B / C / Growth / Pre-IPO]
- Customer base: [#] paying accounts | Average ACV: [$X] | Customer health data source: [Gainsight/ChurnZero/Manual]
- NPS program maturity: [No program / Launched < 12 months / Running 12+ months with [#] responses collected]
- Current NPS score: [X overall] | Promoters: [X% — score 9-10] | Passives: [X% — score 7-8] | Detractors: [X% — score 0-6]
- Survey platform: [Tool name] | Survey type in use: [Relationship NPS / Transactional CSAT / Product NPS / All three]
- Response rate today: [X%] | Target response rate: [X%]
- Verbatim capture rate: [X% of respondents leave a comment]

**Advocacy program current state:**
- G2/Capterra reviews: [# total] | [# in last 12 months] | Average star rating: [X]
- Reference program: [No formal program / Informal — CS manages manually / ReferenceEdge or similar with # active references]
- Reference call demand from sales: [# requests/month] | Current fulfillment time: [X business days]
- Reference gap: [# requests that go unfulfilled or take > 5 days]
- Customer-sourced pipeline: [$X last quarter / "not tracked"]
- NPS follow-up today: [Nothing automated / CS manually reaches out to Promoters occasionally / Partial automation with tool X]

**Revenue and pipeline context:**
- New logo ACV: [$X] | Marketing-sourced pipeline target: [$X/quarter]
- Expansion ACV target per account: [$X/year] | NRR target: [X%]
- Sales reference requests by deal stage: [Stage 3 Evaluation = # references/deal | Stage 4 Proposal = # references/deal]
- Competitive deals: [X% of pipeline is competitive vs. incumbent or specific competitor]

**Tech stack for automation:**
- Survey: [Delighted / Medallia / Qualtrics / Wootric / SurveyMonkey / HubSpot Surveys]
- CRM: [Salesforce / HubSpot] | CS platform: [Gainsight / ChurnZero / Totango / Planhat / None]
- MAP: [Marketo / HubSpot / Pardot / Salesforce Marketing Cloud]
- Advocacy/reference platform: [Influitive / Orca / ReferenceEdge / Gong / None]
- Community: [Slack / Circle / Discourse / None]
- Integrations available: [Zapier / native webhooks / Salesforce Flow / Workato]

**Constraints and guardrails:**
- CS relationship protection: [CS team owns the customer relationship — any marketing automation triggered by NPS must be reviewed by CS before sending / Marketing can automate Promoter outreach without CS approval if health score is Green / Other]
- Survey fatigue limits: [Maximum [#] surveys per customer per quarter / Suppression list rules]
- Legal/GDPR considerations: [Customer communications must comply with [regulation] in [regions]]

---

### System Architecture: NPS Signal-to-Revenue Activation Engine

#### Section 1: Survey Program Architecture (Signal Quality First)

Before automating advocacy activation, the signal input must be high quality. A weak survey program produces noisy NPS data that misleads automation.

**Three NPS Signal Types — When to Deploy Each:**

**Signal Type 1: Relationship NPS (R-NPS)**
*Question*: "How likely are you to recommend [Product] to a colleague or peer in your industry?"
*Trigger*: Time-based. Deploy 60-90 days after onboarding completion (first signal), then every 6 months for active accounts.
*Audience targeting*: The contact most actively using the product — identified via product analytics as the power user, not just the billing contact. Power user NPS is 15-25 points higher than billing contact NPS and produces more accurate advocacy propensity signals.
*Suppression rules*:
- Account health = Red → suppress all NPS surveys until health recovers to Amber; CS escalation owns the relationship
- Renewal within 45 days → suppress to avoid commercial pressure contaminating satisfaction signal
- Open support ticket (P1 or P2) → suppress until resolved + 7 days
- Already surveyed within 90 days → suppress

**Signal Type 2: Transactional CSAT (T-CSAT)**
*Question*: "How satisfied were you with [specific interaction: onboarding / support ticket resolution / implementation / quarterly business review]?"
*Trigger*: Event-based. Fire within 24-48 hours of: onboarding milestone completion, support ticket closure (any severity), QBR delivery, professional services project handoff.
*Why separately*: T-CSAT measures a specific experience quality, not overall product satisfaction. A customer may give R-NPS 9 but T-CSAT 6 on a slow support interaction. Treating these as the same signal produces false negatives in advocacy activation.
*Automation rule*: T-CSAT ≥ 9 after onboarding → trigger "New Aha Moment" advocacy sequence (fresh enthusiasm, highest willingness to review or refer). T-CSAT ≤ 5 after support → trigger CS escalation independently of R-NPS history.

**Signal Type 3: Product NPS (P-NPS)**
*Question*: "How likely are you to recommend [specific feature / workflow / integration] to a peer facing the same challenge?"
*Trigger*: Behavioral. Fire when product analytics detect a user completing a key workflow for the first time (first successful export, first dashboard built, first automated workflow run). This catches the "Aha Moment" — the highest-satisfaction instant in the product lifecycle.
*Value*: P-NPS responses include verbatim quotes that are product-feature specific — invaluable for use case marketing and persona-specific proof content. A P-NPS 10 with verbatim "This cut my reporting time from 4 hours to 20 minutes" is more usable as marketing proof than a generic R-NPS 10 with no comment.

**Survey Design for Maximum Verbatim Quality:**
- Follow the NPS question with a second open field: "What's the primary reason for your score?" — this is mandatory to enable AI sentiment classification
- For Promoters (9-10), add a third question: "What would you tell a peer at another company who is evaluating tools like ours?" — this surfaces pre-written advocacy language the customer has already articulated and is willing to share

---

#### Section 2: AI-Powered Signal Classification & Advocacy Propensity Scoring

Not all Promoters are equal. A score of 9 from a Director of RevOps at a $500M company with 500 LinkedIn followers who said "This transformed how my team operates" is worth 10x more advocacy effort than a score of 9 from a junior analyst at a 10-person startup with no stated reason. The AI classification layer turns raw NPS data into prioritized advocacy action queues.

**Classification Dimensions (applied to every response via LLM API or Gainsight AI):**

**Dimension 1: Score Band**
- Promoter (9-10): Primary advocacy activation pool
- Passive (7-8): Nurture-first, advocacy-second pool
- Detractor (0-6): Recovery pool — advocacy suppressed entirely until resolution

**Dimension 2: Verbatim Sentiment Depth (AI Sentiment Analysis)**
Run every verbatim response through sentiment + intent classification:
- Tier 1 (Advocacy-Ready): Language expressing transformation, enthusiasm for sharing, peer recommendation intent. Keywords: "transformed," "game-changer," "told my colleagues," "recommended to my network," "wouldn't go back." → Highest priority for immediate advocacy ask.
- Tier 2 (Satisfied-Specific): Language referencing a specific feature or workflow value. "Saves me 3 hours per week," "finally have visibility into X." → High value for feature-specific proof content and G2 reviews.
- Tier 3 (Generic Positive): "Great product," "happy with the service" — no specific language. → Still eligible for advocacy but requires more activation effort; do not lead with a reference ask.
- Tier 4 (Mixed/Ambiguous): Positive score but verbatim includes a concern: "Love the product but the reporting module needs work." → Do not activate for advocacy until the concern is acknowledged and resolved by CS.

**Dimension 3: Contact Influence Score (Network Value)**
Pull from CRM + LinkedIn data (if enriched via Clearbit/Clay/Apollo):
- LinkedIn follower count: > 2,000 = High influence
- Job seniority: Director+ = High influence
- Conference speaker history or published author: Boolean flag
- Company brand recognition score: Fortune 1000 / category leader / unknown
→ Weight: High-influence Promoters get first access to co-marketing and speaker opportunities. Low-influence Promoters go to G2 reviews and direct reference calls.

**Dimension 4: Account Strategic Value**
Pull from CRM:
- Account ARR tier (Tier 1 / Tier 2 / Tier 3 / Long-tail)
- Customer tenure: < 6 months = too early for reference calls; 6-18 months = ideal; > 18 months = risk of "known story" fatigue
- Renewal date: > 90 days away = safe to activate; < 90 days = CS approval required before any advocacy ask
- Customer health score: Green = activate immediately; Amber = CS approval first; Red = suppressed

**Output: Advocacy Action Queue (populated daily in CRM)**
Every NPS response routes to one of five queues:

| Queue | Criteria | First Action | Owner |
|-------|----------|-------------|-------|
| Priority Advocate | Score 9-10 + Tier 1/2 verbatim + High influence + Green health | G2 Review Ask → Reference Pool → Co-Marketing invite | Customer Marketing |
| Standard Advocate | Score 9-10 + Tier 3 verbatim or lower influence | G2 Review Ask → Reference Pool | Customer Marketing |
| Passive Nurture | Score 7-8 | Feature adoption nudge → Milestone celebration → Resurvey at 60 days | Customer Marketing + CS |
| CS Recovery | Score 0-6 | Immediate CS alert → Executive escalation if strategic account | CS (Marketing suppressed) |
| Hold | Score 9-10 + Tier 4 verbatim (mixed) OR renewal < 90 days | No advocacy action — log for 30-day follow-up | Customer Marketing monitors |

---

#### Section 3: Promoter Activation Cascade (72-Hour Window)

Research on NPS response behavior shows advocacy willingness peaks within 72 hours of submitting a positive survey — the same moment of enthusiasm that drove them to give a 9 or 10 is still active. After 7 days, willingness to act on an advocacy request drops by approximately 40%. The system must move fast.

**Trigger**: Survey webhook fires → CRM creates "NPS Response" record → Classification engine scores response → Routes to Priority or Standard Advocate queue → First automation fires within 4 hours.

**Step 1 — Immediate Acknowledgment (4 hours post-survey):**
*From: Customer Marketing Manager (named individual, not noreply@)*
*Subject: "Thank you — your [Product] experience means a lot"*

"[First Name],

Thank you for taking a moment to share how [Product] is working for you — a score of [X] genuinely made my day.

[If verbatim captured — reference it specifically]: What you said about [paraphrase their verbatim] is exactly the kind of impact we're working toward.

I'll be reaching out in the next day or two with a small ask — nothing time-consuming, and completely optional. Just wanted to say thank you first.

[Signature — Customer Marketing Manager name + photo]"

*Why this works*: The acknowledgment is personal and does NOT include the advocacy ask yet. It signals that a human read their response, establishes a relationship, and creates a warm context for the next message.

**Step 2 — Primary Advocacy Ask (24-48 hours post-survey):**
*From: Same Customer Marketing Manager*
*Subject line: "Quick ask — could you share your experience?"*

The ask is personalized to the Advocacy Action Queue:

**For Priority Advocate — G2 Review First:**
"[First Name], I have a quick favor to ask. [X] companies evaluate [Product] on G2 before reaching out to us — and they're looking for real practitioner perspectives from people doing exactly what you do at [Company Name]. Would you take 5-7 minutes to share your experience? [Direct G2 review link — pre-populated with their company and role where possible]. Your review would directly help peers in [their industry] make a better-informed decision. No obligation, but it would mean a lot."

→ Estimated completion rate with this sequence vs. generic blast: 25-40% vs. 8-12%

**For Priority Advocate — Reference Program:**
"[First Name], we occasionally have prospects who are evaluating [Product] for a use case similar to yours — [use case specific to their verbatim]. Would you be open to a 20-minute conversation with one of them to share your experience? You'd hear about their challenges, share what's worked for you, and that's it — no sales pressure on your end, and you'd be doing a real service to someone making a significant decision. If yes, I'll only send you requests that match your specific context. Just reply with a yes and I'll add you to our reference pool."

→ Estimated acceptance rate: 40-60% when the ask is specific and low-pressure

**For High-Influence Priority Advocate — Co-Marketing Invite:**
"[First Name], given your [specific role / your team's experience with X feature], I'd love to explore something with you. We're building a practitioner-led [webinar series / roundtable / podcast / research report] for [their industry/persona], and your perspective would be genuinely valuable. This is a thought leadership opportunity, not a customer testimonial — we'd ghostwrite, handle all the logistics, and position you as the expert. Interested in a 20-minute call to explore what this could look like?"

→ Estimated acceptance rate: 25-40% among Director+ with >1,000 LinkedIn followers

**Step 3 — Non-Response Follow-Up (5 days after Step 2):**
Single follow-up only. Shorter. Acknowledge they might be busy.

"[First Name] — following up briefly on my note from [X] days ago. Completely understand if the timing isn't right. If you do have 5 minutes for a G2 review [link], or if you'd like to be added to our reference pool for future calls, just let me know. Either way, thank you for being a customer."

**Step 4 — Long-Tail Engagement (30-60 days after survey, if no advocacy action taken):**
For Promoters who haven't acted on advocacy asks, enroll in a content-based nurture that delivers exclusive practitioner content, early access to new features, or invitations to exclusive events. These build goodwill and resurface advocacy willingness at the next major customer milestone. Do NOT resurvey for 90 days from original NPS date.

---

#### Section 4: Passive Conversion Playbook (Turning 7-8s Into 9-10s)

Passives are your highest-leverage cohort. A 2-point NPS score increase — from 7 to 9 — unlocks the full advocacy engine and prevents churn risk from ambivalent customers who are still evaluable by competitors.

**Passive Scoring: Why They're Not at 9 Yet**
Use AI to classify Passive verbatim into root cause categories:

| Root Cause Category | Verbatim Signals | Activation Strategy |
|--------------------|-----------------|-------------------|
| Feature Gap | "Wish it had X," "Missing Y functionality" | Product roadmap update when gap closes; feature request acknowledgment within 7 days |
| Adoption Plateau | "Haven't explored everything yet," "Haven't gotten full value" | Targeted feature adoption campaign; CSM check-in invitation |
| Onboarding Incomplete | "Still getting used to it," "Learning curve" | Customer Education team enrollment; interactive tutorial sequence |
| Support Experience | "Had a rough onboarding," "Slow response time once" | CS service recovery sequence; "How are things now?" personal outreach |
| Price/Value Tension | "Good product but expensive" | ROI calculator + customer success metrics report; business case content |
| No Comment | Score 7-8 with no verbatim | Standard Passive Nurture: milestone celebration + resurvey at 60 days |

**Passive Activation Sequence (MAP-automated):**

*Week 1*: CS receives Passive alert (if health score is Amber) or Customer Marketing takes the lead (if health score is Green). Personalized email from CSM or Customer Marketing: "We saw your recent feedback — thank you for sharing. I'd love to understand if there's anything we could be doing better for you." No advocacy ask.

*Week 2-4*: Enroll in feature adoption email sequence specific to their root cause category. Example: if root cause is Adoption Plateau → "3 features [Company name] customers like [their company size] are using to [specific outcome]" — with one-click activation link for each feature.

*Day 30*: Milestone report email — "Here's what [Product] has done for [Company Name] in the last 90 days" — personalized metrics pulled from product analytics via API: [# of workflows automated, # hours saved, $ identified, etc.]. Seeing concrete ROI data is the single highest-impact driver of Passive → Promoter movement.

*Day 45-60*: Resend relationship NPS. If score moves to 9-10 → immediately route into Promoter Activation Cascade. If score remains 7-8 → loop CSM for manual relationship investment. If score drops to 0-6 → immediate CS escalation.

**Expected Passive → Promoter conversion rate with this playbook**: 18-28% within 90 days (vs. 5-8% with no structured follow-up).

---

#### Section 5: Detractor Recovery & Reputation Defense

Detractors (0-6) are a retention emergency AND a reputation risk. The window to prevent a negative G2 review or a churn decision is typically 14-30 days post-survey submission.

**Immediate Triage (within 2 hours of response):**

*Step 1*: Survey webhook → CRM creates Detractor alert → CS lead receives Slack/email notification with full response (score + verbatim + account ARR tier).

*Step 2 (Strategic account, ARR > $X threshold)*: Executive escalation within 4 hours. VP of Customer Success or CEO (if < Series B) sends personal email to primary contact: "I personally read your feedback and want to make this right. Can we connect this week?" Do NOT delegate to a junior CSM for strategic account Detractors.

*Step 3 (Standard account)*: Assigned CSM receives automated task in Gainsight/CRM: "Detractor NPS — outreach required within 24 hours." CSM email template (personalized): "I saw your recent feedback and I want to understand what's not working. Can we schedule 20 minutes this week? I want to make sure we're delivering the value we promised."

*Step 4 (Long-tail account with low ARR)*: Automated email from Customer Marketing / CS pooled team: "Thank you for your honesty. We clearly haven't delivered the experience you deserve. I'd love 15 minutes to understand what's fallen short. [Calendly link]" — streamlined but still human-feeling.

**Closed-Loop Resolution Tracking (CRM):**
- Detractor Response Date + Score
- CS Outreach Date (must be within 24 hours or flag for manager review)
- Resolution Meeting Held: Yes/No + Date
- Root Cause Category: [Product Bug / Feature Gap / Support Failure / Implementation Problem / Business Problem Unrelated to Product / Other]
- Recovery Action: [Bug fix committed / Feature roadmap / Process improvement / Executive escalation / Refund/credit / Account review]
- Resolved: Yes/No | Resolution Date
- Resurvey Date: 45 days after resolution confirmation
- Post-Recovery Score: [New NPS score from resurvey]

**Reputation Defense — Pre-Emptive:**
A key intelligence insight: Detractors who receive NO follow-up contact post-survey are 3-4x more likely to leave a negative review on G2/Capterra within 30 days than Detractors who received a meaningful CS recovery conversation. The act of following up — even if the problem isn't fully resolved — reduces negative review probability significantly because it demonstrates the company cares.

*Monthly Detractor Review Board*: Customer Marketing + CS + Product review all Detractor responses categorized by root cause. Any root cause affecting ≥ 10% of Detractor volume in a quarter is escalated to the Product team as a product debt priority. This closes the feedback loop from customer signal to product roadmap.

---

#### Section 6: Advocacy Attribution to Revenue

The program's business case depends on demonstrating that NPS-triggered advocacy actions produce attributable pipeline and closed revenue.

**CRM Data Model (Salesforce-based):**

*Object: NPS Response (custom or native)*
- Response ID, Date, Score, Verbatim, Contact ID, Account ID
- Classification: Promoter / Passive / Detractor
- Advocacy Tier: Priority / Standard / Passive Nurture / Recovery / Hold
- Advocacy Actions Taken: [G2 Review Submitted / Reference Call Completed / Co-Marketing Agreed / Introduction Made / None]
- NPS Outcome: Advocate Activated / Passive Converted / Detractor Recovered / Detractor Churned

*Opportunity Attribution:*
When an opportunity is created where a contact was previously in the Advocate pool or where a G2 review, reference call, or introduction was logged in the prior 90 days:
- Salesforce Campaign tagged: "NPS-Triggered Advocacy — [Type]"
- Opportunity field "Customer Advocacy Influence" = Yes + advocacy action type
- Marketing contribution type = "Advocacy-Influenced"

*Monthly Advocacy Pipeline Report:*

| Metric | Definition | Month | Quarter | Year |
|--------|-----------|-------|---------|------|
| NPS Surveys Sent | Total sent in period | | | |
| Response Rate | Responses ÷ sent | | | |
| Promoter % | Score 9-10 ÷ responses | | | |
| Advocacy Actions Triggered | Emails sent by queue | | | |
| G2 Reviews Submitted | From NPS-triggered asks | | | |
| Reference Pool Growth | Net new references added | | | |
| Reference Calls Completed | For active sales deals | | | |
| Warm Introductions Made | From Promoter network mapping | | | |
| Advocacy-Influenced Opps Created | New opps with advocacy touch | | | |
| Advocacy-Influenced Pipeline ($) | $ value of influenced opps | | | |
| Advocacy-Influenced Closed Won ($) | ARR closed with advocacy influence | | | |
| Passives Converted to Promoter | Via 90-day nurture sequence | | | |
| Detractors Recovered | Post-outreach rescore ≥ 7 | | | |
| Detractors Churned | Left within 90 days of survey | | | |
| Advocacy Program ROI | Closed ARR influenced ÷ program cost | | | |

**Board-Level Metric:**
"NPS-to-Revenue Yield" — for every 100 Promoter responses collected, how many dollars of new logo pipeline is generated through advocacy actions? Benchmark target: $25,000-$80,000 of influenced pipeline per 100 Promoters, depending on ACV. Report quarterly. This metric makes the NPS investment and the customer marketing investment defensible in the CFO and board conversation.

---

### Output Format

Structure your NPS activation system design as:
1. **Survey Architecture** (which survey types to run, targeting logic, suppression rules, verbatim question design)
2. **Classification Engine** (how to score each response across 4 dimensions; tool configuration needed)
3. **Promoter Activation Playbook** (exact email sequence, timing, ask hierarchy by influence tier)
4. **Passive Conversion Sequence** (root cause classification, 60-day nurture map, resurvey logic)
5. **Detractor Recovery SLA** (escalation tiers by ARR, outreach templates, closed-loop tracking)
6. **Attribution Configuration** (CRM fields, campaign tagging, pipeline reporting structure)
7. **90-Day Launch Plan** (week-by-week from survey audit → automation build → first Promoter activated → first attribution report)
8. **Resource & Tool Requirements** (headcount, integration effort, tooling gaps to fill)

## Example Input/Output

**Input (Sample Company):**

Company: Meridian Analytics — B2B SaaS pipeline forecasting platform
ARR: $22M | Stage: Series B | ACV: $38,000
Customers: 420 accounts | Power users trackable: ~840 contacts
Current NPS: 47 (38% Promoters, 42% Passives, 20% Detractors)
Verbatim capture rate: 34%
Survey tool: Delighted | CRM: Salesforce | MAP: HubSpot | CS: Gainsight | No advocacy platform
G2 reviews: 43 total (8 in last 12 months) | Sales reference demand: 11 requests/month
Reference fulfillment time: 6-8 business days | 3 requests/month unfulfilled
Customer-sourced pipeline: Not tracked | NPS follow-up: CS manually reaches out to maybe 30% of Detractors

**Output (Promoter Activation segment):**

**Meridian's Advocacy Action Queue — Week 1 after system launch:**

Delighted webhook → Salesforce custom object "NPS Response" → HubSpot workflow trigger

Classification engine run on 47 Promoter responses collected in last 30 days:

*Priority Advocates (13 contacts):*
- Score 9-10 + Tier 1/2 verbatim + Director+ seniority + Green health + Renewal > 90 days
- Example: **Sarah Chen, VP Revenue Operations, CloudScale (Series C, 380 employees)** — score: 10, verbatim: "Meridian cut our forecast variance from 22% to under 6% — I've already recommended it to two peers." LinkedIn: 3,200 followers, posts regularly on RevOps. Network value: RevOps community with peers who are Meridian's ICP.
  - Day 1 action: Personalized acknowledgment from Customer Marketing Manager
  - Day 2 action: Primary ask = co-marketing invite (ghostwritten article: "How CloudScale Reduced Forecast Variance by 73%")
  - Day 4 action (if no response): G2 review ask as alternative
  - Day 9 action (if still no response): Single follow-up, G2 link, close the sequence

*Standard Advocates (21 contacts):*
- Score 9-10 but Tier 3 verbatim ("great product, love the team") or Analyst/Manager level
  - Day 1 action: Acknowledgment email
  - Day 2 action: Primary ask = G2 review (5 minutes) → reference pool enrollment
  - Day 7 action (if no review): Follow-up with direct review link, note: "15 of your peers at [similar companies] have reviewed us — your perspective would round out the picture for someone making this decision right now."

**Expected output Week 1:**
- 34 Promoters in activation queue
- 8-12 G2 review submissions (vs. Meridian's current rate of 8/year total)
- 3-5 new references added to pool (vs. current backlog of 3 unfulfilled/month)
- 1-2 co-marketing conversations started

**Passive Conversion — Month 1 (Meridian's 42 Passive responses):**

AI root cause classification of 42 Passive verbatim (34% of respondents = ~18 responses):
- Adoption Plateau (8): "Haven't used all the features yet" → Feature adoption email series featuring top 3 underutilized workflows for RevOps teams
- Feature Gap (4): "Wish it had better CRM sync with [non-Salesforce CRM]" → Product roadmap update notification + workaround guide
- No Verbatim (18): Standard 30-day milestone report — "Meridian has helped your team [X specific outcomes from product analytics]" + resurvey at Day 60

Expected Passive → Promoter conversion in 90 days: 7-12 contacts (18-28% of 42)
Each conversion generates new Promoter activation sequence → 2-4 additional advocacy actions

**Detractor Recovery — Month 1 (17 Detractor responses):**
- 3 strategic accounts (ARR > $50K): VP CS executive escalation within 4 hours
- 9 standard accounts: CSM outreach within 24 hours, root cause survey
- 5 long-tail accounts (ARR < $10K): Automated email + CSM pool assignment
- Expected recovery (rescore ≥ 7 in 45 days): 4-6 accounts
- Expected churn prevention value: $120K-$180K ARR (4-6 accounts at $30K average)

## Success Metrics

A high-quality NPS activation system design from this prompt will:
- Define a classification model that differentiates advocacy action priority beyond the raw 0-10 score, incorporating verbatim sentiment, contact influence, and account health
- Build an activation sequence where the first advocacy ask arrives within 72 hours of survey submission (not 2 weeks later when enthusiasm has faded)
- Design Detractor recovery with clear SLA tiers by account ARR — not all Detractors get the same response
- Produce attribution logic that links specific advocacy actions (G2 review, reference call, introduction) to downstream opportunities in the CRM without relying on manual data entry
- Calculate a realistic program output: [% Promoters who take advocacy action] × [advocacy actions per activated Promoter] × [% advocacy-influenced opportunities] × [average deal ACV] = projected advocacy-influenced pipeline per quarter

**Program maturity benchmarks:**
- Month 1: Automation live; first 20+ Promoters activated; first G2 review submissions from NPS-triggered sequence
- Month 3: G2 review velocity: 6-12 new reviews/month; reference pool grown by 15-25 contacts; 3-5 advocacy-influenced opportunities created
- Month 6: Reference SLA consistently < 48 hours; Passive → Promoter conversion rate measurable; first advocacy-influenced closed-won deal attributed
- Month 12: Advocacy-Generated Pipeline contributing $X (target: 10-20% of total marketing-sourced pipeline); NPS response rate improved via trust-building follow-up program; Net Promoter Score increased 8-15 points from systematic Passive nurture and Detractor recovery

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Customer-Led-Growth-Program-Architecture-&-Customer-Network-Pipeline-Revenue-Intelligence-Engine.md` — for the full champion warm introduction and co-marketing program that NPS-identified Priority Advocates feed into
- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/NPS-CSAT-Closed-Loop-Intelligence-Engine.md` — for the CS-side closed-loop workflow and Detractor recovery case management that integrates with this marketing activation system
- `../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/G2-Review-Social-Proof-Automation-Engine.md` — for the G2 review generation campaign mechanics and review velocity optimization that plugs into the Promoter activation cascade
- `../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/AI-Powered-B2B-Customer-Marketing-Program-Automation-&-Revenue-Intelligence-Engine.md` — for the broader customer marketing automation program architecture that this NPS signal system feeds into

## Integration Tips

**Delighted / Qualtrics / Wootric → Salesforce (Webhook Architecture):**
- Configure survey tool to fire a webhook on every survey submission → Salesforce receives JSON payload with: Contact email, NPS score, verbatim text, survey type, timestamp
- Salesforce Flow creates "NPS Response" custom object record, performs CRM lookup to match Contact and Account, pulls health score from Gainsight (via API) and renewal date from Opportunity object
- Classification logic runs in Salesforce Flow (score-based routing) with verbatim text sent to an AI classification API (OpenAI or Claude API via Salesforce External Services) returning sentiment tier and root cause category within 30 seconds
- Output: NPS Response record is fully classified and routed to the correct queue within 5 minutes of survey submission

**Gainsight → Salesforce → HubSpot (Tri-System Orchestration):**
- Gainsight health score sync to Salesforce Account (standard Gainsight connector): "Account Health Color" field updated in real time
- Salesforce Flow condition: if NPS Response classification = "Priority Advocate" AND Salesforce Account.Health_Color = "Green" AND Account.Days_Until_Renewal > 90 → create HubSpot enrollment record via Zapier or native HubSpot-Salesforce sync → HubSpot enrolls contact in "Promoter Priority Activation" workflow
- CS override: If Gainsight health drops to Amber/Red AFTER enrollment — Gainsight triggers a Salesforce Flow that pauses or unenrolls the HubSpot workflow and alerts the Customer Marketing Manager via Slack

**HubSpot Workflow Automation (Promoter Activation Cascade):**
- Workflow 1: "Promoter Priority Activation" — Enrollment trigger: contact added to "Priority Advocate" static list in Salesforce. Steps: Delay 4 hours → Send email (Acknowledgment). Delay 24 hours → Send email (Primary ask — dynamic content token pulls in their specific advocacy action). Delay 5 days → If-then: G2 review property = Not Submitted → send follow-up. If G2 review = Submitted → enroll in "Reference Pool Welcome" workflow instead.
- Workflow 2: "Passive Nurture — NPS" — 60-day multi-step sequence with feature adoption emails. Day 30 trigger: pull product analytics data via API (Segment/Amplitude webhook) → populate milestone email with actual usage metrics for that account.
- All email sends logged as HubSpot Activities → sync back to Salesforce Contact timeline for unified view

**G2 Review Integration (Salesforce → G2 Buyer Intelligence → HubSpot):**
- G2 Buyer Intent (if licensed): When a target account shows G2 intent signal for your product category → HubSpot workflow checks if any contact at that account has NPS ≥ 9 but has NOT yet submitted a G2 review → trigger Promoter email sequence to that contact immediately (they are more likely to review when their peers are actively searching)
- G2 Review submitted → G2 sends webhook to Salesforce → Update Contact "G2 Review Submitted" = Yes + date. Removes contact from future G2 ask workflows. Adds contact to Reference Pool with "G2 Review Proof Point" tag.

**Slack Integration (CS + Customer Marketing Real-Time Alerts):**
- Detractor alert: Zapier → Salesforce NPS Response record created with Score ≤ 6 → Slack message posted to #cs-alerts: "⚠️ Detractor NPS: [Contact Name] at [Account Name] ($[ARR] ARR) scored [X]. Verbatim: '[quote]'. Owner: [CSM Name]. SLA: 24 hours."
- Promoter activation win: When HubSpot logs G2 review submission or reference acceptance → Salesforce activity created → Zapier posts to #customer-wins: "✅ [Contact Name] at [Account] just submitted a G2 review / accepted a reference request — triggered by NPS activation sequence."
- Weekly digest: Automated Slack message to #customer-marketing every Monday with previous week's NPS activation metrics: [# surveys sent, # Promoters activated, # G2 reviews submitted, # references added, # Passives resurveyed]

## Troubleshooting

**Problem:** NPS survey response rate is below 15%, making the activation engine data-sparse — not enough Promoters in the pipeline to justify building the automation system.
**Solution:** Low response rates almost always trace to three causes: (1) Survey timing is wrong — surveys sent via a generic blast cadence rather than triggered by product activity achieve 8-12% response rates; switch all surveys to event-triggered (post-onboarding, post-feature adoption, post-QBR) and response rates climb to 25-40%. (2) The survey email sender is "noreply@" or a generic "Team@" address — response rates improve 30-50% when the email comes from a named individual (CSM or Customer Marketing Manager) with a photo. (3) Survey emails arrive at 9am Monday or Friday afternoon — optimize send time by account timezone to mid-week, mid-morning. Implement all three changes before investing in activation automation; even 3-4 weeks of improved data collection will give you enough Promoters to validate the first workflows.

**Problem:** Sales team is skeptical that reference calls from the NPS program are producing pipeline influence — they say "we were already going to close this deal" when advocacy-influenced opportunities close.
**Solution:** This is an attribution education problem, not an attribution measurement problem. Run a 90-day controlled analysis comparing two deal cohorts: deals where a reference call, G2 review, or co-marketing touch was logged to the opportunity vs. deals where no advocacy touch was logged. In most B2B SaaS companies, advocacy-touched deals close 15-30% faster and at 8-15% higher win rates. Present this analysis to the sales leadership team in a 30-minute revenue review, not in a Slack message. Frame it in terms that matter to them: "Advocacy-touched deals close faster, which improves your forecast accuracy — that's a Sales benefit, not a Marketing metric." Once sales leaders see the velocity impact, they will start requesting reference matches earlier in deals rather than treating it as a late-stage risk-reduction tool.

**Problem:** G2 review requests from the NPS activation sequence are generating clicks but not completions — Promoters start the review process but abandon it.
**Solution:** G2 review completion friction has two root causes: (1) The G2 review form requires respondents to log in or create an account — some Promoters don't have an existing G2 account and abandon at the login screen. Fix: include instructions in your email: "If you haven't reviewed on G2 before, it takes about 2 minutes to create a free account — just use your LinkedIn login." Even better: configure G2 to offer LinkedIn SSO login in your review invitation link, reducing account creation friction by ~70%. (2) The review form is presented cold with no guidance on what to write. Fix: in your email, include 2-3 guiding questions the customer can answer in the review: "What problem were you solving before using [Product]? What's the measurable outcome you've seen? What would you tell a peer evaluating similar tools?" These prompts reduce the blank-page anxiety that causes abandonment, and they also produce higher-quality, longer reviews that rank better in G2 search results.

## Version History
- v1.0: Initial creation (auto-generated)
