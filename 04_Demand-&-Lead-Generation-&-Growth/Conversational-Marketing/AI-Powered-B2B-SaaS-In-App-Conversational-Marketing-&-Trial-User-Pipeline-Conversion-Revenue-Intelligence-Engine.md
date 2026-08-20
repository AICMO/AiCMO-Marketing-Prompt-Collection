# AI-Powered B2B SaaS In-App Conversational Marketing & Trial User Pipeline Conversion Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** conversational-marketing, product-led-growth, trial-conversion, in-app-messaging, revenue-intelligence

## Overview
This prompt architects an autonomous in-app conversational marketing system that intercepts trial users at high-intent behavioral moments, delivers personalized AI-driven conversations using Jobs-to-be-Done and PQL signals, and converts product users into qualified pipeline without human SDR involvement. Use it when your PLG motion has a trial-to-paid gap or when you need to accelerate expansion revenue from existing accounts.

## Quick Copy-Paste Version

You are a senior B2B SaaS product-led growth strategist. Analyze the following trial user behavioral data and design a complete in-app conversational marketing sequence to convert this user to a paid customer.

TRIAL USER PROFILE:
- Product: [Your SaaS product name and category]
- Trial start date: [X days ago]
- Key actions completed: [List of features used]
- Key actions NOT completed: [Critical setup steps skipped]
- Session frequency: [X sessions in last 7 days]
- Time-in-app: [X minutes average per session]
- Team size invited: [X collaborators added]
- Pricing page visits: [X visits, last visit Y days ago]

PRODUCT QUALIFIED LEAD SCORE: [X/100]

Design a 5-touchpoint in-app conversational sequence that:
1. Opens with a behavior-triggered message acknowledging what they've accomplished (not a generic greeting)
2. Uses a Jobs-to-be-Done question to uncover their primary outcome goal
3. Shows them the fastest path to their specific outcome using features they haven't tried
4. Identifies expansion blockers (team adoption, budget approval, technical requirements)
5. Closes with a specific next step matched to where they are in their decision process

For each touchpoint, provide:
- Trigger condition (what user action or inaction fires this message)
- Channel (in-app banner, chat widget, email fallback, or push notification)
- Message copy (under 75 words, conversational tone)
- Response branches (2-3 user reply options and what each triggers next)
- Success metric (what response or action indicates progression)

Output the sequence as a structured playbook ready to configure in Intercom, Pendo, or Appcues.

## Advanced Customizable Version

ROLE: You are an expert B2B SaaS PLG revenue architect with deep expertise in in-app behavioral marketing, Jobs-to-be-Done methodology, and product-qualified lead conversion. You have designed trial conversion systems for companies like Notion, Figma, Loom, and Calendly that convert at 25%+ trial-to-paid rates.

CONTEXT:
Company: [COMPANY_NAME]
Product: [PRODUCT_DESCRIPTION — one sentence on what it does and who it serves]
ICP: [IDEAL_CUSTOMER_PROFILE — role, company size, industry]
Trial model: [Freemium / Time-limited trial / Usage-limited trial]
Trial length: [X days]
Current trial-to-paid rate: [X%]
Target trial-to-paid rate: [X%]
Primary expansion signal: [What action predicts conversion — e.g., "inviting 3+ team members", "creating first project", "exporting data"]
In-app messaging tool: [Intercom / Pendo / Appcues / Chameleon / Custom]
CRM integration: [HubSpot / Salesforce / None]

TRIAL USER SEGMENT DATA:
Segment Name: [e.g., "Power Users Stalled at Team Adoption"]
Behavioral criteria:
- Sessions in last 7 days: [X]
- Core feature engagement: [High/Medium/Low]
- Collaboration features used: [Yes/No]
- Pricing page visits: [X]
- Help docs viewed: [list topics]
- Support tickets: [X, topics: list]
- Days remaining in trial: [X]
PQL Score: [X/100]
Segment size: [X users]

OBJECTIVE: Design a complete autonomous in-app conversational marketing engine for this segment that requires zero human SDR involvement and converts trial users to pipeline within [X days].

DELIVERABLES:

**1. SEGMENT PSYCHOGRAPHIC PROFILE**
Apply Jobs-to-be-Done framework:
- Functional job: What task are they trying to complete?
- Emotional job: How do they want to feel when the job is done?
- Social job: How do they want to be perceived by colleagues?
- Progress blockers: What is preventing them from achieving their job?
- Success metrics they care about (not your metrics — theirs)

**2. CONVERSATIONAL TRIGGER MAP**
For each of these 6 trigger scenarios, define the exact behavioral condition and response:

Trigger A — "Aha Moment Amplifier": User just completed [KEY_ACTION]. Fire within 60 seconds.
Trigger B — "Stall Recovery": User hasn't logged in for [X] days but trial is still active.
Trigger C — "Team Adoption Nudge": User has used product solo but hasn't invited collaborators.
Trigger D — "Expansion Signal": User hits usage limit, exports data, or visits pricing 2+ times.
Trigger E — "Decision Maker Identifier": User mentions budget, team, or approval in any chat response.
Trigger F — "Trial End Countdown": [3 days / 1 day / trial expiration] approaching.

For each trigger, output:
- Trigger condition (exact event name as configured in your tool)
- Audience filter (segment criteria to avoid over-messaging)
- Suppression rules (who should NOT see this — e.g., already converted accounts)
- Delay logic (immediate / 5 min / next session start)

**3. CONVERSATION SCRIPTS**
For each trigger, write a complete conversation with:

Opening message: [Under 60 words. Reference specific user action. No "Hey [name]! 👋" openers. Lead with value or insight.]

Branch A — Engaged response:
User says: [most likely positive response]
Bot reply: [advance toward conversion — next step, demo offer, or feature unlock]
Action fired: [tag in CRM, notify AE, unlock feature, schedule call]

Branch B — Objection response:
User says: [most likely objection — price, timing, team approval]
Bot reply: [address objection with specific proof point or reframe]
Action fired: [send relevant case study, offer extended trial, route to AE]

Branch C — No response:
After [X hours] of no reply:
Fallback: [email or next in-app trigger]

**4. PERSONALIZATION VARIABLES**
List every dynamic variable to pull from your data stack:
- From product analytics: [list fields]
- From CRM enrichment: [list fields — Clearbit, 6sense, ZoomInfo]
- From conversation history: [intent signals to carry forward]
- From support tickets: [pain points to reference]

**5. CONVERSION PATH ARCHITECTURE**
Map the decision journey from trigger to closed-won:

PQL Score 60-74 → [Automated sequence only, no human touch]
PQL Score 75-84 → [Automated sequence + AE notification after Branch B objection]
PQL Score 85-100 → [Immediate AE notification + VIP trial extension offer]

For each path, define:
- Handoff criteria (what triggers human involvement)
- Handoff message to AE (what context to pass via Slack/CRM)
- SLA (how fast AE must respond before automation takes back over)

**6. MEASUREMENT FRAMEWORK**
Primary conversion metrics:
- Conversation start rate (% of segment that engages with first message)
- Response rate by trigger type
- Branch distribution (% choosing each response option)
- MQL generation rate (conversations that result in CRM-qualified lead)
- Trial-to-paid conversion rate by segment
- Time-to-conversion (days from first conversation to purchase)
- Revenue influenced (ARR sourced from in-app conversations)

Secondary health metrics:
- Message fatigue score (opt-out rate, session abandonment after message)
- Suppression rate (% filtered out to protect experience)
- AE handoff acceptance rate (% of routed leads that AEs engage with)

A/B test framework:
- Test 1: Opening message framing (outcome-led vs. feature-led)
- Test 2: Trigger timing (immediate vs. next session)
- Test 3: CTA type (demo booking vs. feature unlock vs. plan upgrade)
- Statistical significance threshold: [80% / 90% / 95%]
- Minimum sample size per variant: [Calculate based on current segment size]

**7. TOOL CONFIGURATION SPEC**
Provide exact configuration steps for [TOOL_NAME]:

Intercom Series setup:
- Series name: [naming convention]
- Audience rules: [exact filter logic]
- Message type: [In-app / Email / Push]
- Goal event: [what marks this series as "won"]
- Exit condition: [what removes user from series]

CRM sync rules:
- On conversation start: [create activity log in HubSpot/Salesforce]
- On Branch B objection: [create task for AE, set lead status to "Sales Ready"]
- On conversion: [update deal stage, log revenue influenced, close series]

Zapier/webhook triggers:
- Event: [conversation_started]
- Action: [create row in Google Sheets pipeline tracker]
- Event: [conversion_completed]
- Action: [update MRR dashboard, notify revenue team in Slack]

**OUTPUT FORMAT:**
Deliver as a complete implementation-ready playbook with:
- Executive summary (3 bullets: segment insight, strategy, projected impact)
- All 6 trigger configurations as structured JSON-like specs
- All conversation scripts with full branch logic
- Measurement dashboard template (Google Sheets column headers)
- 30-day rollout timeline with milestones
- Risk flags (any scenarios that could backfire and how to prevent them)

## Example Input/Output

**Input — Segment Brief:**
- Company: Claritask (B2B SaaS project management for professional services firms)
- Segment: "Solo Power Users" — using product heavily but haven't invited team members
- Trial day 9 of 14, PQL score 78/100
- User: Sarah Chen, Operations Manager at a 45-person consulting firm
- Actions completed: Created 12 projects, used time-tracking 8 times, viewed templates
- Actions NOT completed: Never clicked "Invite Team," never visited client portal feature
- Pricing page visits: 2 (both in last 3 days)
- Support ticket: Asked "how do I bill clients directly from the tool?"

**Output — Trigger C Conversation (Team Adoption Nudge):**

*Trigger: User opens app for 6th session without inviting anyone*

**Opening message:**
"Sarah — you've tracked 23+ hours across 12 projects this week. Quick question: are you the only one managing this workload, or do you have a team that would benefit from seeing this in real time?"

**Branch A (Yes, I have a team):**
Bot: "Perfect timing. Firms like yours typically see 40% faster project delivery when ops managers give consultants direct access. Want me to show you how Meridian Consulting onboarded 8 people in under 10 minutes?"
Action: Unlock "Team Invite" in-app tutorial, tag as "Team Expansion Ready" in HubSpot

**Branch B (Just me for now):**
Bot: "Got it — a lot of ops managers start solo to build the system before rolling it out. Given your billing question earlier, have you seen the client-facing portal? It might change that calculus."
Action: Trigger demo of client portal feature, send relevant case study via email

**Branch C (No response after 4 hours):**
Fallback email subject: "The answer to your billing question (+ something relevant to your 12 projects)"
Email body: [Links to billing tutorial + personalized project summary report]

**Projected results for this segment (320 users):**
- Conversation start rate: 38% (121 users engage)
- Team invite rate: 24% (29 users invite 3+ teammates within 48 hours)
- Upgrade rate from engaged users: 31% (37 trial-to-paid conversions)
- Additional ARR: $74,000 at $2,000 ACV
- Time to results: 14 days

## Success Metrics

**Green (sequence is working):**
- Conversation start rate > 30%
- Trial-to-paid rate improvement > 5 percentage points vs. control
- AE handoff acceptance rate > 70%
- Message opt-out rate < 3%

**Yellow (needs optimization):**
- Start rate 15-30% — test opening message framing
- Opt-out rate 3-7% — reduce trigger frequency, add suppression rules
- Branch B (objection) rate > 50% — price or timing is a structural barrier; escalate to product/pricing team

**Red (pause and diagnose):**
- Start rate < 15% — audience filter too narrow or trigger condition wrong
- Opt-out rate > 10% — sequence is damaging trial experience; disable immediately
- Zero AE handoffs despite 85+ PQL scores — CRM integration broken

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Conversational-Marketing/AI-Powered-B2B-SaaS-Agentic-Inbound-Lead-Qualification-&-Multi-Channel-Conversational-Pipeline-Orchestration-Revenue-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Product-Led-Growth/`
- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/`
- `../../05_Analytics-&-Performance/Funnel-Conversion-&-Pipeline-Velocity/`

## Integration Tips

**Intercom:** Use "Series" to chain triggers. Set goal events at the Series level so Intercom auto-exits converted users. Use "Custom Attributes" to sync PQL score from your data warehouse via REST API.

**Pendo:** Use "Guides" for in-app messages and "Journeys" to sequence them. Sync guide engagement data to Salesforce via Pendo's native connector. Set "Poll" guides to capture JTBD data that flows into CRM notes.

**HubSpot:** Create a custom "In-App Conversation" activity type. Use Workflows to auto-enroll users when PQL score crosses 75. Build a "Trial Conversion" pipeline stage for deals sourced from conversational triggers.

**Zapier:** Connect Intercom → Google Sheets to log every conversation branch choice. Feed this into a Looker Studio dashboard to visualize branch distribution weekly.

**Slack:** Use Zapier or native Intercom integration to post AE handoff notifications to a #plg-pipeline Slack channel with full user context (company, PQL score, conversation transcript, conversation branch chosen).

## Troubleshooting

**Problem: Low conversation start rates (<15%) despite high PQL scores**
Fix: Check your trigger timing — "immediate" fires often catch users mid-task and get dismissed. Switch to "next session start" or "after 2 minutes of inactivity." Also verify your audience filter isn't excluding most of the segment. Start with looser criteria and tighten after initial data collection.

**Problem: Users engaging but not converting to pipeline (high response rate, low MQL rate)**
Fix: Your conversation is likely stopping at feature education rather than surfacing buying intent. Add a direct question in Branch A: "Is this something you'd want to keep using after your trial, or are you still evaluating?" Map "yes" responses directly to an AE notification or in-app plan selection prompt.

**Problem: AEs ignoring handoff notifications**
Fix: Handoff context is probably too thin. Add 5 data points to every AE notification: (1) user's job title, (2) company size, (3) what triggered the handoff, (4) what the user said in the conversation, (5) PQL score with a one-sentence interpretation. Set a 4-hour SLA in your CRM with automated follow-up to AE manager if not actioned.

## Version History
- v1.0: Initial creation (auto-generated)
