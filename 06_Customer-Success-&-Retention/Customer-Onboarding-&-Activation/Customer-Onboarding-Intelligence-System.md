# Customer Onboarding Intelligence System - AI-Powered Activation & Value Realization Engine

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** customer-success, onboarding, activation, retention, saas, b2b, product-adoption

## Overview
Generates fully personalized onboarding tracks, activation milestone sequences, and value realization playbooks for each customer segment. Use it when launching a new customer, redesigning your onboarding program, or diagnosing why new customers aren't reaching activation.

## Quick Copy-Paste Version

You are a senior customer success architect specializing in B2B SaaS onboarding. Build a complete onboarding intelligence system for my product.

PRODUCT CONTEXT:
- Product: [Your Product Name]
- Core value proposition: [What customers hire your product to do]
- Typical customer: [Company size, role of primary user]
- Key activation milestone (the "aha moment"): [First action that correlates with long-term retention, e.g., "3 team members complete first report"]
- Current median time-to-activation: [X days]
- Average contract value: [ACV]

GENERATE:

1. ACTIVATION MILESTONE MAP
   - Define 3 milestone tiers: Setup (Day 1-3), Activation (Day 4-14), Value Proof (Day 15-30)
   - For each milestone: success criteria, leading behavioral signal, risk signal, intervention trigger

2. PERSONA-BASED ONBOARDING TRACKS (create 3 tracks based on buyer persona or use case)
   - Track name and trigger condition
   - Day-by-day sequence for Days 1, 3, 7, 14, 21, 30
   - Channel per touchpoint (email, in-app, call, video)
   - Message objective and CTA per touchpoint

3. AUTOMATED EMAIL SEQUENCES
   Write subject line + 3-sentence body for each of these emails:
   - Welcome & Quick Win (Day 1)
   - Activation Nudge if milestone not hit (Day 5)
   - First Value Proof celebration (Day 14)
   - 30-Day Business Review invite (Day 28)
   - At-risk intervention (triggered if 0 logins in 7 days)

4. HEALTH SCORE FORMULA
   - List 5 behavioral signals to track (login frequency, feature usage, team invites, etc.)
   - Assign weight to each (must total 100)
   - Define Green/Yellow/Red thresholds
   - Automated action for each threshold

5. INTEGRATION PLAYBOOK
   - What to push to CRM (Salesforce/HubSpot) at each milestone
   - What events to track in product analytics (Amplitude/Mixpanel)
   - Slack/Teams alert conditions for CS team

Output each section as a structured table or numbered list ready to copy into a playbook doc.

## Advanced Customizable Version

You are a world-class customer success architect with 15 years of experience building onboarding systems for B2B SaaS companies from Series A to IPO. You have reduced time-to-value by 60%+ and improved 90-day retention from 70% to 92% at multiple companies. You combine product analytics, behavioral psychology (BJ Fogg's Tiny Habits, Nir Eyal's Hook Model), and automation engineering.

Build a comprehensive Customer Onboarding Intelligence System for the following product.

---
PRODUCT PROFILE:
- Product name: [PRODUCT NAME]
- Category: [CRM / Analytics / DevTools / HR / Finance / Marketing / Other]
- Primary user persona: [Job title, company size, technical sophistication: Low/Medium/High]
- Executive sponsor persona: [Job title, what they care about: ROI, compliance, efficiency]
- Core jobs-to-be-done: [Top 3 outcomes customers hire this product to achieve]
- Critical activation event (single action most predictive of 12-month retention): [DEFINE IT]
- Secondary activation signals: [2-3 additional product behaviors that indicate stickiness]
- Average implementation complexity: [Simple self-serve / Moderate setup / Complex enterprise deployment]
- Integrations customers must complete to see value: [List top 3]
- Current NPS at Day 30: [Score or "unknown"]
- Current 90-day churn rate: [% or "unknown"]

CUSTOMER SEGMENTS (define 3):
Segment A — [Name, e.g., "Solo Power User"]: [trigger condition to assign this track]
Segment B — [Name, e.g., "Team Deployer"]: [trigger condition]
Segment C — [Name, e.g., "Enterprise Rollout"]: [trigger condition]

SUCCESS DEFINITION:
- What does "successful onboarding" look like at Day 30? [Specific, measurable outcome]
- What does "failed onboarding" look like at Day 30? [Specific, measurable outcome]
---

DELIVERABLES — generate all of the following:

### SECTION 1: ACTIVATION MILESTONE FRAMEWORK
Build a 4-tier milestone map using the "Milestone → Signal → Risk → Rescue" model:

| Milestone | Day Target | Success Criteria | Positive Signal | Risk Signal | Automated Rescue Action |
|-----------|------------|-----------------|-----------------|-------------|------------------------|

Tiers:
- Tier 0: Account Setup (Day 0-1)
- Tier 1: First Value Touch (Day 2-7)
- Tier 2: Team/Workflow Activation (Day 8-21)
- Tier 3: Business Value Proof (Day 22-45)

Apply the "minimum viable activation" principle — identify the single smallest action that moves a customer from Tier 0 to Tier 1 within 24 hours.

### SECTION 2: PERSONA-BASED ONBOARDING TRACKS
For EACH of the 3 customer segments, generate a full onboarding playbook:

**Track structure per segment:**
- Track name and qualification criteria
- Assigned CSM motion: High-touch / Tech-touch / Digital-only
- Primary success metric for this segment
- Communication cadence table:

| Day | Channel | Message Type | Objective | CTA | Owner (CSM/Automated) |
|-----|---------|-------------|-----------|-----|----------------------|

Days to cover: 1, 2, 3, 5, 7, 10, 14, 21, 30, 45, 60, 90

**For high-touch segments:** include agenda for onboarding kickoff call (Day 3), 30-day business review (Day 28), and 90-day success review.

### SECTION 3: AUTOMATED EMAIL + IN-APP MESSAGE LIBRARY
Write complete, send-ready copy for each message. Use psychological principles (social proof, loss aversion, progress effect, reciprocity) — note which principle each message uses.

**Email 1 — Welcome & Instant Win (Day 1, automated)**
- Subject line (A/B test two variants)
- Preview text
- Body (150 words max, ends with single CTA)
- Psychological principle used: [name it]

**Email 2 — Feature Discovery (Day 3, automated)**
- Subject + preview + body
- Triggered only if: [specific product event NOT completed]

**Email 3 — Activation Nudge (Day 7, automated if activation milestone not hit)**
- Subject + preview + body
- Include: social proof stat, specific next step, urgency element

**Email 4 — First Win Celebration (triggered when activation milestone IS hit)**
- Subject + preview + body
- Include: what they achieved, what's next, expansion hint

**Email 5 — Stakeholder Update (Day 14, sent to executive sponsor)**
- Subject + preview + body
- Focus: business outcomes, not features

**Email 6 — At-Risk Intervention (triggered: 0 logins for 7 consecutive days)**
- Subject + preview + body
- From: CSM (personalized), not marketing automation
- Include: re-engagement offer, easy re-entry CTA

**Email 7 — 30-Day Success Summary (Day 30, automated)**
- Subject + preview + body
- Include: personalized usage stats, ROI calculation, next milestone

**In-App Messages (3 total):**
- First login welcome tooltip sequence (3 steps, max 15 words each)
- Feature discovery prompt (triggered at Tier 1 completion)
- Expansion hint (triggered at Tier 3 completion)

### SECTION 4: CUSTOMER HEALTH SCORE MODEL
Design a quantitative health score (0-100) using product behavioral data:

| Signal Category | Specific Metric | Measurement | Weight | Green Threshold | Yellow Threshold | Red Threshold |
|----------------|-----------------|-------------|--------|-----------------|------------------|---------------|

Required signal categories:
1. Engagement depth (login frequency, session length)
2. Feature adoption breadth (# of core features used)
3. Team expansion (# of users invited/active)
4. Integration completeness (critical integrations connected)
5. Value realization (customer-defined outcome achieved)

Automated playbook per health score band:
- GREEN (75-100): [Expansion motion trigger]
- YELLOW (40-74): [Intervention sequence]
- RED (0-39): [Executive escalation protocol]

### SECTION 5: IMPLEMENTATION WEEK-BY-WEEK CALENDAR
Provide a 12-week rollout plan to implement this onboarding system:

| Week | Milestone | Owner | Tools Required | Success Criteria |
|------|-----------|-------|---------------|-----------------|

### SECTION 6: ANALYTICS & REPORTING FRAMEWORK
Define the onboarding analytics stack:

**North Star Metric:** [Single metric that best predicts 12-month retention]

**Weekly Onboarding Dashboard (7 metrics):**
- Metric name, definition, target, data source

**Cohort Analysis Template:**
- Which cohort cuts matter most (by segment, acquisition channel, contract size, industry)
- Leading indicator to watch in Week 1 that predicts 90-day outcome

**A/B Testing Roadmap:**
- List 5 highest-impact onboarding experiments to run in first 90 days
- For each: hypothesis, metric, minimum sample size, expected lift

### SECTION 7: TOOL INTEGRATION SPECIFICATIONS

**CRM (Salesforce / HubSpot):**
- Fields to create/update at each onboarding milestone
- Opportunity stage progression tied to onboarding events
- CSM task automation triggers

**Product Analytics (Amplitude / Mixpanel / Heap):**
- Event taxonomy for onboarding funnel
- User property schema
- Funnel definition for activation report

**Customer Success Platform (Gainsight / ChurnZero / Totango):**
- Health score data sync specification
- Automated playbook triggers
- Risk alert conditions

**Communication (Intercom / Customer.io / HubSpot Sequences):**
- Segment/list criteria for each email track
- Event-triggered vs. time-triggered logic map
- Suppression rules to prevent over-communication

Output every section in a format ready to copy directly into Notion, Confluence, or a Google Doc. Use tables wherever possible. Be specific — no vague "engage the customer" instructions. Every action must have an owner, a trigger, and a measurable outcome.

## Example Input/Output

**Input Example:**
Product: Relay — a B2B workflow automation platform for operations teams
Core value: Replace manual Slack-to-spreadsheet handoffs with automated workflows
Primary user: Operations Manager at 50-500 person SaaS company, medium technical sophistication
Activation event: "First workflow runs successfully end-to-end with at least 2 steps and 1 integration"
Implementation complexity: Moderate (requires connecting 1-2 integrations)
Current 90-day churn: 18%
ACV: $12,000

**Output Example (excerpt):**

**Activation Milestone Map:**

| Milestone | Day Target | Success Criteria | Risk Signal | Rescue Action |
|-----------|------------|-----------------|-------------|---------------|
| Account Setup | Day 1 | Admin user + 1 teammate invited, Slack integrated | No teammate invite by Day 2 | CSM email: "Invite your first teammate — workflows are 3x stickier with 2+ users" |
| First Value Touch | Day 5 | First workflow built (even if not live) | No workflow started by Day 4 | In-app prompt: "You're 1 step from your first automation. Start with this template" |
| Team Activation | Day 14 | Workflow runs live, triggers fired 5+ times | Workflow built but never triggered | Automated email from CSM: subject "Your workflow is built — here's why it hasn't run yet" |
| Value Proof | Day 30 | 3+ workflows live, 50+ triggers, 2+ team members active | Only 1 user active at Day 21 | Executive stakeholder email: ROI summary + expansion invitation |

**Welcome Email (Day 1):**
Subject A: "Your first automation is 8 minutes away, [First Name]"
Subject B: "The Relay team just set up your account — here's your first win"
Preview: "Most teams save 3 hours in their first week. Here's how."

Body:
"Hi [First Name], welcome to Relay. The fastest way to see what Relay can do: connect your Slack and build your first workflow in the next 8 minutes using our Handoff Automation template — it's the #1 workflow our customers run first.

[Button: Build My First Workflow]

Already have a use case in mind? Reply to this email and I'll set it up with you.

— [CSM Name], your Relay onboarding specialist"

Psychological principle applied: Progress effect + social proof ("most teams save 3 hours")

## Success Metrics

- **Time-to-activation:** Median days from signup to hitting activation milestone (target: reduce by 30%+)
- **30-day activation rate:** % of new customers who hit activation milestone within 30 days (target: 75%+)
- **90-day retention by cohort:** Compare cohorts with/without structured onboarding
- **NPS at Day 30:** Track net promoter score at onboarding completion (target: 40+)
- **CSM efficiency:** Customers successfully onboarded per CSM per month
- **Email engagement:** Open rate (target: 40%+), click rate (target: 12%+) on onboarding sequences
- **Feature adoption depth:** Average # of core features activated per customer by Day 30

## Related Prompts

- [Customer Success Automation Engine](../../06_Customer-Success-&-Retention/Customer-Success-Automation/Customer-Success-Automation-Engine.md)
- [Voice of Customer Analysis](../../02_Product-Marketing/Customer-&-Market-Research/Voice-of-Customer-Analysis.md)
- [Customer Journey Mapping](../../02_Product-Marketing/Customer-&-Market-Research/Customer-Journey-Mapping.md)
- [Lead Nurturing Workflows](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Lead-Nurturing-Workflows.md)

## Integration Tips

- **HubSpot:** Create a "New Customer Onboarding" pipeline with stages mapped to Tier 0-3 milestones. Use workflow automation to move deals and assign CSM tasks when product events fire via HubSpot's custom behavioral events API.
- **Gainsight / ChurnZero:** Map the 5-signal health score directly to a Gainsight Scorecard. Set CTAs (Calls-to-Action) to auto-assign when score drops below 40. Use Timeline to log every onboarding touchpoint automatically.
- **Amplitude / Mixpanel:** Build an onboarding funnel chart using the 4-tier milestone events. Set up a cohort of "Activated" users (hit Tier 2 within 14 days) and compare their 90-day retention vs. unactivated cohort — this is your business case for onboarding investment.
- **Intercom:** Use "Series" to build the email + in-app message tracks. Trigger each Series based on user segment (set as a user property on signup). Use Intercom's "Goal" feature to auto-exit users from the sequence once they hit the activation event.
- **Notion / Confluence:** Paste the full onboarding playbook into a Notion database with one row per customer. Use the health score formula to create a rollup property that CSMs update weekly.
- **Zapier / Make:** Connect your product database to HubSpot/Salesforce via Zapier to push milestone completions as CRM activities without engineering work.

## Troubleshooting

**Problem:** The activation milestone I defined doesn't actually correlate with retention.
**Solution:** Run a cohort retention analysis in your product analytics tool. Filter for customers who completed your hypothesized activation event in their first 14 days vs. those who didn't, and compare 90-day and 180-day retention curves. If the gap is less than 15 percentage points, your activation metric is wrong — look for a different event with a larger retention delta. Common better activation events: inviting a second user, completing an integration, or running the product's core action 3+ times.

**Problem:** Customers are completing onboarding steps but still churning at 90 days.
**Solution:** Your activation milestone may be capturing product usage but not business value realization. Add a "Value Proof" milestone at Day 30 that requires a customer-reported outcome (e.g., "reported saving time on X process" via in-app survey or QBR). Also check if there's a specific feature cohort that retains — customers who use Feature X may retain at 85% vs. 50% for those who don't. Make that feature part of your activation definition.

**Problem:** CSMs are not following the playbook consistently.
**Solution:** Remove human decision-making from the first 14 days — automate all touchpoints through Day 14 using your CS platform, with CSMs only intervening for Red health score alerts. Build a Gainsight/ChurnZero Cockpit view that shows each CSM exactly which customers need action today, with one-click task completion. Tie CSM performance metrics to onboarding activation rates, not just QBR completion.

## Version History
- v1.0: Initial creation (auto-generated)
