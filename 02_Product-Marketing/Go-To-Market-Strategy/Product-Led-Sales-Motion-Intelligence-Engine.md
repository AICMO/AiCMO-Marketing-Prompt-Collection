# Product-Led Sales Motion Intelligence Engine - Convert Free Users to Enterprise Revenue

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** plg, product-led-growth, saas, sales-motion, pql, enterprise, b2b, revenue-expansion

## Overview
Designs and automates the full Product-Led Sales (PLS) motion for SaaS companies that have a self-serve product: identifies product-qualified leads (PQLs), defines usage-triggered sales handoff criteria, builds multi-signal scoring models, and generates outreach sequences that convert active free/trial users into paid enterprise customers—without the cold outreach problem.

## Quick Copy-Paste Version

You are a Product-Led Sales strategist for a B2B SaaS company. Our product has a freemium/free-trial motion and we want to build a systematic PLS playbook to convert high-intent users into enterprise deals.

Company context:
- Product: [Your SaaS product and category]
- Free tier or trial: [Freemium / 14-day trial / reverse trial / etc.]
- Current conversion rate free→paid: [X%]
- Target customer: [SMB / Mid-market / Enterprise, primary ICP]
- ACV target: [e.g., $15K–$80K ARR]

Generate a complete Product-Led Sales motion including:

1. PQL SCORING MODEL
   - Top 5 in-app behavioral signals that predict revenue conversion (e.g., inviting teammates, using core feature 3x, exporting data)
   - Firmographic overlay signals (company size, funding, tech stack, job titles of users)
   - Negative signals / disqualifiers
   - PQL score threshold for sales handoff vs. nurture

2. SALES TRIGGER EVENTS
   - Immediate triggers (sales notified within 1 hour): list 4–5 specific in-app actions
   - Warm triggers (follow-up within 24 hours): list 4–5 specific signals
   - Expansion triggers (for existing paid customers): list 3–4 signals indicating upsell readiness

3. PQL OUTREACH SEQUENCE
   - Email 1 (Day 0 — trigger-based, sent by AE or via automation): subject line + body using the specific feature they used as context
   - Email 2 (Day 3 — value + social proof): subject + body
   - LinkedIn message (Day 5): 3-sentence DM
   - Email 3 (Day 8 — soft close): subject + body
   - All messages must reference their actual usage context—no generic outreach

4. SALES-PRODUCT ALIGNMENT
   - What data must the product team expose in CRM/Slack for this to work
   - 3 internal alignment agreements between Sales and Product
   - PQL SLA: response time standards by tier

5. SUCCESS METRICS DASHBOARD
   - 5 KPIs to track PLS motion health weekly
   - Benchmarks for each metric based on SaaS industry standards

Output everything in a ready-to-implement format with specific examples.

## Advanced Customizable Version

ROLE: You are a senior Product-Led Sales architect with deep expertise in PLG→PLS transitions at companies like Slack, Figma, Notion, Calendly, and Loom. You understand that PLS requires a fundamentally different sales motion than traditional outbound—it's about identifying intent signals, not creating demand.

COMPANY CONTEXT:
- Company: [Company name]
- Product category: [e.g., Project management, data analytics, security, HR tech]
- Business model: [Freemium / Free trial (length) / Reverse trial / Usage-based]
- Free tier limits: [e.g., 3 users, 5 projects, 1GB storage]
- Current MRR from self-serve: [$X]
- Enterprise ARR target: [$X]
- ICP definition: [Company size, industry, tech stack, job title of champion]
- Average Sales Cycle (self-serve to enterprise): [X days]
- CRM: [HubSpot / Salesforce / Pipedrive]
- Product analytics tool: [Amplitude / Mixpanel / Heap / PostHog]

OBJECTIVE: Design a complete, fully-automated Product-Led Sales system that:
1. Identifies and scores PQLs from product usage data
2. Triggers intelligent, context-aware sales outreach
3. Enables AEs to have warm, relevant first conversations
4. Accelerates free→paid conversion and SMB→enterprise expansion
5. Creates a feedback loop between Product and Sales

DELIVERABLE 1 — PQL SCORING FRAMEWORK
Build a weighted scoring model using:

BEHAVIORAL SIGNALS (60% of score):
- Activation milestone completions (list 5 key milestones for our product)
- Feature adoption depth (core feature, collaboration features, admin/enterprise features)
- Usage frequency and recency (DAU/WAU patterns)
- Collaboration signals (team invites, shares, commenting activity)
- Integration usage (connecting to third-party tools = high intent)
- Data import/export actions (signals commitment)
- Upgrade page visits / pricing page views

FIRMOGRAPHIC SIGNALS (25% of score):
- Company size (employee count, Clearbit/ZoomInfo enrichment)
- Funding stage and recency
- Tech stack (do they use enterprise tools like Salesforce, Okta, Slack?)
- Number of users from same domain already active
- Job title of the user (Champion vs. End user vs. Admin)

ACCOUNT-LEVEL SIGNALS (15% of score):
- Multiple users from same company (viral coefficient)
- Different departments using the product
- Time since first sign-up (urgency signals)
- Previous sales touchpoints

OUTPUT: A scoring rubric with point values for each signal, threshold tiers:
- HOT PQL (80+ points): Immediate AE assignment, <1 hour response
- WARM PQL (50-79 points): SDR sequence, <4 hour response
- NURTURE (25-49 points): Marketing automation sequence, monthly check-in
- DISQUALIFY (<25 points): Keep in free tier, product-led nurture only

DELIVERABLE 2 — TRIGGER EVENT LIBRARY
For each trigger, provide: event name, what it means, who it alerts, response SLA, and first action.

TIER 1 TRIGGERS (AE/SDR notified immediately via Slack):
1. Enterprise feature explored (SSO setup, audit logs, SAML, API key generated)
2. Admin invite sent to 10+ team members
3. Pricing page visited 3+ times in 7 days
4. Data migration / bulk import completed
5. Integration with enterprise tool connected (Salesforce, Okta, Jira enterprise)

TIER 2 TRIGGERS (24-hour follow-up queue):
1. Crossed usage limit / bumped into free tier ceiling
2. Invited 5+ collaborators from same company domain
3. Used product 5+ days in a week for 3+ consecutive weeks
4. Created [core workflow] for 3rd time (indicates value realization)
5. Shared exported report / asset externally

EXPANSION TRIGGERS (for existing paid accounts):
1. New department users signing up outside current paid seats
2. Usage at 85%+ of plan limits
3. Admin account added new users manually above seat count
4. Cross-functional feature usage detected (different team using product differently)

DELIVERABLE 3 — PERSONALIZED OUTREACH SEQUENCES
For each sequence type, provide complete email copy that references the specific trigger:

A) IMMEDIATE HOT PQL SEQUENCE (AE-owned, manual + automation assist):
- Email 1 (Hour 1 after trigger): Subject line references their specific action. Body: 3-4 sentences. Acknowledge their usage specifically. Ask one qualifying question about their team's use case. Include a direct Calendly/calendar link.
- Email 2 (Day 3 if no reply): Light follow-up. Include a customer story from their industry. One sentence ask.
- LinkedIn DM (Day 5 if no email reply): 2-3 sentences, warm context reference, connection ask.
- Email 3 (Day 8 final touchpoint): Breakup email with value-add resource specific to their apparent use case.

B) WARM PQL NURTURE SEQUENCE (SDR-owned or fully automated):
- Email 1 (Day 1): Welcome from a real person. Congratulate on specific achievement in product. Offer help. No hard sell.
- Email 2 (Day 5): Share one customer story or case study matched to their industry vertical.
- Email 3 (Day 12): Share a tip to get more value from the feature they used. Soft CTA: "Would a 20-minute walkthrough of [Enterprise Feature] be useful?"
- Email 4 (Day 21): ROI-focused. "Companies like yours see [specific outcome]. Worth exploring?"
- Email 5 (Day 35): Final automated touch. Include self-serve upgrade link.

C) EXPANSION SEQUENCE (Customer Success or AE-owned):
- Message 1 (Trigger: 85% of seat limit): From CSM. Proactive, not reactive. "Noticed your team is growing—here's how [Enterprise Plan] could save you time and money at your current scale."
- Message 2 (Trigger: New department detected): "We noticed [Team B] is starting to use [Product]. Many of our customers expand to [Platform plan] to unify teams—happy to walk through what that looks like."

DELIVERABLE 4 — SALES + PRODUCT ALIGNMENT PROTOCOL
Define the operational infrastructure:

DATA REQUIREMENTS:
- Product analytics → CRM sync: Which events must be sent to HubSpot/Salesforce and how (Segment, RudderStack, or native integration)
- Required properties on Contact record: list 8 specific product data fields
- Required properties on Company/Account record: list 5 fields
- PQL score field: how it's calculated and updated in CRM
- Slack alert configuration: channels, alert format, routing rules by AE territory/segment

SALES-PRODUCT SLA AGREEMENTS:
1. Product commits to: exposing [specific events] via analytics pipeline within [X days]
2. Sales commits to: logging all PQL outreach outcomes in CRM within 24 hours (for model refinement)
3. Joint agreement: bi-weekly PQL review meeting to calibrate scoring thresholds based on conversion data
4. Escalation path: when a free user reports a bug or feature gap that's blocking their upgrade

DELIVERABLE 5 — PLS PERFORMANCE FRAMEWORK
Weekly metrics dashboard with industry benchmarks:

FUNNEL METRICS:
- PQL Identification Rate: % of active free users hitting PQL threshold (benchmark: 3–8% of active users)
- PQL→SQL Conversion: % of PQLs that become qualified opportunities (benchmark: 20–35%)
- SQL→Closed Won: Win rate on PQL-sourced pipeline (benchmark: 25–40%, typically higher than outbound)
- Time to First Contact: Average hours from trigger to first outreach (target: <2 hours for HOT PQLs)
- Free→Paid Conversion Rate by Trigger Type: Which triggers predict conversion best

REVENUE METRICS:
- PQL-Sourced ARR: $ value of new ARR from PLS motion monthly
- Average Contract Value by PQL Tier: Compare HOT vs. WARM vs. inbound
- Expansion ARR from Trigger-Based Outreach: Monthly expansion revenue from CS-triggered outreach
- CAC by Motion: Compare PLS CAC vs. outbound vs. inbound (PLS should be lowest)

QUALITATIVE METRICS:
- Sales conversation quality score (1-5): How relevant was the first conversation?
- AE adoption rate: % of PQL alerts acted on within SLA

CONSTRAINTS:
- All outreach must reference specific product usage—generic outreach is prohibited and will reduce conversion
- Sequences must have opt-out compliance (CAN-SPAM, GDPR for EU users)
- PQL scoring must be recalibrated quarterly based on conversion data
- Never contact a user who has explicitly opted out of sales communication in the product

OUTPUT FORMAT: Deliver each deliverable as a structured, copy-ready artifact. Include specific example email copy for a [SaaS product type] company—not placeholders. Make it so a SDR or AE could use this playbook on Day 1.

## Example Input/Output

**Input Example:**
- Company: Notion for Teams / Slab competitor — "DocuBase" (team wiki + knowledge management SaaS)
- Free tier: 3 users, 50 pages, no admin controls
- ICP: 50–500 employee tech companies, Ops/IT/HR buyers
- ACV target: $20K–$60K ARR
- CRM: HubSpot, product analytics: Amplitude

**Output Example (excerpt — Hot PQL Email 1):**

> **Trigger:** DocuBase admin at Vercel (320 employees) just connected Slack integration AND sent invites to 12 teammates. PQL score: 94.
>
> **Subject:** Your team at Vercel is getting serious about DocuBase
>
> Hi [First Name],
>
> Noticed you just connected Slack and got your whole team onboarded — that's usually when DocuBase starts saving people hours every week.
>
> Most teams your size (I see there are 320 of you at Vercel) eventually run into the 3-user limit and want SSO, permissions, and admin audit logs. Worth a 20-minute call this week to see if our Team plan makes sense?
>
> I've got Thursday at 2pm PT or Friday at 10am open: [Calendar Link]
>
> — [AE Name], DocuBase

**PQL Score Breakdown for this account:**
- Slack integration connected: +20 points
- 12 invites sent (same domain): +25 points
- Admin role (not just end user): +15 points
- Company size 300+ employees: +20 points
- B2B tech company: +10 points
- Pricing page visited once: +5 points
- **Total: 95 — HOT PQL → Immediate AE assignment**

**Sample Trigger Alert (Slack format):**
🔥 HOT PQL ALERT
Account: Vercel (vercel.com)
Champion: [Name], Head of Engineering Operations
PQL Score: 95/100
Trigger: Slack integration + 12 team invites in last 2 hours
Assigned AE: [Territory AE]
Response SLA: 60 minutes
→ View in HubSpot | → Send Email 1

## Success Metrics

- **PQL identification accuracy:** >70% of flagged PQLs should become genuine sales conversations (not noise)
- **First contact time:** <2 hours for Hot PQLs, <8 hours for Warm PQLs
- **Email open rate:** >45% (trigger-based personalized outreach should far exceed cold email benchmarks)
- **PQL→Meeting booked rate:** >15% (benchmark for context-aware PLG outreach)
- **Free→Paid conversion lift:** 2–4x improvement vs. non-PLS baseline conversion
- **AE adoption rate:** >85% of PQL alerts acted on within SLA within 60 days of rollout
- **PLS-sourced ARR contribution:** Should reach 30–50% of new ARR within 6–12 months of full implementation

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-Revenue-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md`
- `../../02_Product-Marketing/Go-To-Market-Strategy/GTM-Motion-Design-Scaling-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Lead-Nurture-Sequence-&-Pipeline-Acceleration-Email-Engine.md`

## Integration Tips

- **HubSpot:** Create a custom Contact property "PQL Score" (number field). Use Workflows to auto-assign deals to AE queues when score crosses 80. Set up Slack notifications via HubSpot → Slack native integration. Use "Product Usage" custom properties populated via Segment or RudderStack.
- **Salesforce:** Build a custom object "Product Qualified Lead" linked to Contact. Use Flow to trigger tasks for assigned AEs. Dashboard shows PQL pipeline stage distribution.
- **Amplitude/Mixpanel → CRM:** Use Segment or RudderStack as the middleware. Create Identify and Track calls for each PQL trigger event. Push computed PQL scores to both CRM and your Slack alerting channel.
- **Slack:** Create a `#pql-alerts` channel. Use Zapier or native webhooks to post formatted PQL cards with one-click links to CRM record, LinkedIn profile, and email template.
- **Salesloft/Outreach:** Pre-build PQL cadence templates for each trigger type. When HubSpot score threshold is met, auto-enroll contact in appropriate cadence via Zapier or native sync.
- **Calendly:** Embed AE-specific Calendly links with UTM parameters (`?utm_source=pql&utm_trigger=slack_integration`) to track meeting bookings by trigger type.

## Troubleshooting

**Problem: PQL alerts are firing too frequently and overwhelming the sales team (alert fatigue)**
Solution: Raise the HOT PQL score threshold from 80 to 90. Move more accounts to WARM tier (SDR sequence) vs. immediate AE assignment. Set a daily cap of 5 HOT PQL alerts per AE. Review score calibration in the bi-weekly joint meeting—signals may need reweighting.

**Problem: AEs are ignoring PQL alerts because the context isn't specific enough in the CRM/Slack**
Solution: Enrich the Slack alert with 3 specific data points: (1) exactly which feature triggered the alert, (2) how long they've been active, (3) one relevant customer story from the same industry. The more specific the context, the higher AE confidence and action rate. Add "Why this is a PQL" field to the alert.

**Problem: Low email reply rates despite personalized triggers**
Solution: First, verify emails are reaching inbox (check domain reputation, use tools like MailReach). Second, make the trigger context even more specific—"You just connected your Salesforce" beats "You've been active lately." Third, shorten Email 1 to 3 sentences max. Add a P.S. with a value-add resource (not a sales ask). Test subject lines A/B: name-drop their company size or industry in the subject.

## Version History
- v1.0: Initial creation (auto-generated)
