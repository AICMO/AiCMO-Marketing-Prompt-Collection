# AI-Powered Churn Prediction & Proactive Customer Retention Marketing Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** churn-prevention, retention-marketing, predictive-analytics, saas, customer-success, lifecycle-automation, b2b

## Overview

This engine transforms raw customer behavioral and product usage data into AI-driven churn risk scores and automatically generates hyper-personalized retention campaigns, intervention sequences, and escalation playbooks. Use it when you want to move from reactive "save the account" firefighting to a proactive, signal-based retention marketing system that can run autonomously at scale.

## Quick Copy-Paste Version

You are a B2B SaaS retention marketing expert. I'll give you information about a customer segment showing churn risk signals, and you'll build a complete retention intervention program.

Customer context:
- Product: [Your SaaS product name and category]
- Segment: [Customer tier — e.g., Mid-Market, $10K-50K ARR]
- Churn signal detected: [e.g., login frequency dropped 60% over 30 days, no activity in 14 days, support tickets spiked, key champion left]
- Customer health score: [Red/Yellow/Green and current score if available]
- Time to renewal: [e.g., 45 days]
- Key stakeholders: [e.g., Champion: Marketing Manager, Economic buyer: VP Marketing]

Build a complete churn intervention program that includes:

1. CHURN RISK CLASSIFICATION
   - Risk severity: Critical (churns in <30 days), High (30-60 days), Medium (60-90 days)
   - Root cause hypothesis: usage decline / business change / competitor evaluation / champion departure / ROI not realized
   - Confidence level and what additional signals would confirm

2. INTERVENTION SEQUENCE (6-touch, 21-day program)
   - Day 1: Personalized outreach from CSM with specific value proof point
   - Day 3: Executive-to-executive connection request (if high ARR)
   - Day 7: Tailored success story from similar customer
   - Day 10: ROI quantification email with customer-specific numbers
   - Day 14: Product expert session offer + quick win identification
   - Day 21: Renewal risk escalation to sales leadership (if no response)
   Write each email in full — subject line, preview text, body, CTA.

3. PERSONALIZATION TOKENS
   List the exact data fields to pull from CRM/product analytics to personalize each touch.

4. ESCALATION TRIGGERS
   Define the exact behavioral signals that move a customer from Medium → High → Critical risk and trigger the next intervention tier.

5. SUCCESS METRICS
   How to measure if the intervention worked (re-engagement rate, health score change, renewal rate for cohort).

Customer data I'm working with:
[Paste relevant customer usage data, health metrics, or CRM notes here]

## Advanced Customizable Version

SYSTEM ROLE:
You are an elite B2B SaaS retention marketing strategist with deep expertise in customer success operations, behavioral analytics, predictive modeling, and lifecycle marketing automation. You've built retention programs that have improved NRR from 95% to 115%+ at companies from $10M to $500M ARR. You think in cohorts, signals, and automation workflows — not one-off emails.

OBJECTIVE:
Build a complete, fully-automated AI-powered churn prediction and proactive retention marketing program. Every output must be ready to plug directly into HubSpot, Salesforce, Gainsight, ChurnZero, or Intercom without editing.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
COMPANY & PRODUCT CONTEXT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Product: [SaaS product name]
Product category: [e.g., marketing automation, HR tech, BI/analytics]
Primary value delivered: [e.g., reduces CAC by automating ad spend optimization]
Core sticky features (high correlation with retention): [e.g., API integrations, custom dashboards, automated reports]
Key activation milestone (the "aha moment"): [e.g., first campaign sent, first integration connected, first dashboard shared]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
CUSTOMER SEGMENTATION FOR RISK MODELING
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Segment this customer cohort and build risk profiles for each:

Segment A — Enterprise ($100K+ ARR):
- At-risk indicators: [e.g., executive champion departure, competitor evaluation signals, usage drop in top 3 seats]
- Acceptable intervention cost per account: [e.g., up to $2,000 in CSM time + gifts]
- Decision-maker profile: [C-suite + procurement + IT]

Segment B — Mid-Market ($20K-$99K ARR):
- At-risk indicators: [e.g., 40%+ DAU/MAU drop, no logins from power users, open support tickets > 30 days]
- Acceptable intervention cost per account: [e.g., up to $500]
- Decision-maker profile: [VP/Director level]

Segment C — SMB (<$20K ARR):
- At-risk indicators: [e.g., 0 logins in 21 days, payment failed once, last NPS < 7]
- Acceptable intervention cost per account: [Automated-only, <$50]
- Decision-maker profile: [Owner/Manager, fully self-serve]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
CHURN SIGNAL LIBRARY (build AI detection rules for each)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
For each signal below, generate: detection logic, urgency tier, and recommended first response.

PRODUCT SIGNALS:
- Login frequency decline: [e.g., >50% drop vs. 90-day baseline]
- Feature abandonment: [stopped using previously active core features]
- Session duration drop: [<5 min per session vs. >20 min baseline]
- Integration disconnection: [removed key integration]
- Export/data download spike: [potential data extraction before leaving]
- API call volume drop: [>40% decline in 14 days]

RELATIONSHIP SIGNALS:
- Champion departure: [LinkedIn job change detected or email bounces]
- Executive disengagement: [C-suite opens dropped to 0]
- NPS score: [detractor score or recent downgrade from passive to detractor]
- Support ticket sentiment: [negative language detected in tickets]
- QBR no-show: [missed last 2 scheduled check-ins]

COMMERCIAL SIGNALS:
- Payment failure: [credit card declined or ACH bounced]
- Renewal date proximity: [<90 days with health score Yellow/Red]
- Seat contraction request: [asked to reduce licenses]
- Competitor mention: [in support tickets, emails, or social listening]

INTENT SIGNALS:
- Review site activity: [left review on G2/Capterra mentioning competitors]
- Competitor content consumption: [IP-based detection of competitor website visits]
- Job postings: [customer hiring for role your product replaces]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
HEALTH SCORE ARCHITECTURE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Build a composite health score (0-100) using these weighted inputs:
- Product engagement (DAU/MAU, feature breadth): [weight: e.g., 35%]
- Relationship depth (stakeholder coverage, exec engagement): [weight: 25%]
- ROI realization (outcomes achieved vs. promised): [weight: 20%]
- Support health (tickets open, CSAT, resolution time): [weight: 10%]
- Financial health (payment history, growth trajectory): [weight: 10%]

Score thresholds:
- Green (75-100): Healthy, target for expansion
- Yellow (50-74): At risk, proactive outreach required
- Red (0-49): Critical, executive escalation required

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
RETENTION CAMPAIGN ARCHITECTURE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Build three parallel intervention tracks that run simultaneously based on risk tier:

TRACK 1 — AUTOMATED DIGITAL RE-ENGAGEMENT (SMB + early warning for MM)
Trigger: Health score drops to Yellow OR any 2 product signals fire simultaneously
Channel mix: Email (primary) + In-app + LinkedIn retargeting
Duration: 30-day sequence, 8 touches

Touch 1 (Day 0 — Trigger fires):
Email subject: [Generate 3 A/B test variants]
Send from: Customer Success Manager (personalized, not marketing alias)
Message focus: Specific feature they've stopped using + one-click reactivation
CTA: [Generate specific, low-friction CTA]

Touch 2 (Day 3):
Channel: In-app notification
Message focus: Quick win they haven't unlocked yet
CTA: Interactive tutorial or live demo booking

[Continue through all 8 touches with full copy]

TRACK 2 — HUMAN-IN-THE-LOOP OUTREACH (Mid-Market Yellow/Red)
Trigger: Health score drops to Red OR champion departure detected
Owner: CSM + Sales overlay for accounts >$50K ARR
Duration: 21-day high-touch program
Escalation: VP Customer Success at Day 7 if no response

[Generate full 21-day playbook with email templates, call scripts, LinkedIn messages]

TRACK 3 — EXECUTIVE ESCALATION (Enterprise Red)
Trigger: $100K+ ARR account hits Red health score OR renewal < 60 days with Yellow
Owner: VP Customer Success + CRO escalation
Duration: 30-day white glove program
Tactics: Executive sponsor alignment, custom ROI analysis, product roadmap briefing, exec-to-exec dinner/event

[Generate full playbook including executive outreach templates and talking points]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
ROI QUANTIFICATION FRAMEWORK
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
For at-risk accounts, generate a customer-specific ROI summary that answers:
1. What outcomes have they achieved? (use product data + CRM notes)
2. What outcomes were promised but not yet realized? (opportunity framing)
3. What is the cost of churning? (switching costs, ramp time, lost momentum)
4. What is the value of staying + expanding? (compound ROI model)

Generate the ROI summary template with fill-in variables that pull from CRM and product analytics automatically.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
AUTOMATION WORKFLOW SPECIFICATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Map the complete automation architecture:
1. Data sources to connect: [product analytics → CRM → CS platform → email]
2. Trigger logic in pseudocode for each workflow
3. Branching logic (if no response → escalate; if re-engaged → move to expansion track)
4. CSM task creation rules (what triggers a human action vs. automated touch)
5. Reporting dashboard KPIs to track weekly

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
OUTPUT FORMAT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Deliver:
1. Health Score Model (table with weights and scoring logic)
2. Signal Detection Rules (table: Signal | Detection Logic | Urgency | First Response)
3. Intervention Tracks (full email copy, subject lines, CTAs for all 3 tracks)
4. Escalation Decision Tree (visual flowchart in text format)
5. ROI Quantification Template (with variable placeholders)
6. Automation Workflow Spec (pseudocode + tool-specific setup notes for HubSpot/Gainsight)
7. 90-Day Retention Program Launch Checklist

## Example Input/Output

**Input Example:**

Company: Heliograph Analytics (B2B SaaS data visualization platform)
Segment: Mid-Market, $34,000 ARR, 18 months into 2-year contract
Renewal: 47 days away
Churn signals: Power user (Sarah Chen, Head of Data) logged in 0 times in 22 days (vs. daily previously). New support ticket: "How do I export all my data?" opened 5 days ago. LinkedIn shows Sarah updated her job title to "Former Head of Data @ Acme Corp" 8 days ago.
Current health score: Red (31/100)
Other stakeholders: CFO (Tim Rourke, economic buyer) — last engagement was QBR 90 days ago

---

**Output Example (abbreviated):**

**RISK ASSESSMENT:**
- Severity: Critical — renewal in 47 days, champion departed, data export request (strong exit indicator)
- Root cause: Champion departure + potential organizational transition; new stakeholder not yet identified or onboarded
- Confidence: 91% churn risk without immediate intervention
- Missing signal needed: Who replaced Sarah? Does CFO Tim Rourke know the product is at risk?

**HEALTH SCORE BREAKDOWN:**
- Product engagement: 8/35 (near-zero usage for 22 days)
- Relationship depth: 5/25 (champion gone, no new contact identified, exec last touched 90 days ago)
- ROI realization: 18/20 (historically strong — 3 dashboards adopted, cited 40% faster reporting)
- Support health: 6/10 (1 open ticket, negative intent)
- Financial health: 9/10 (no payment issues)
- **Total: 46/100 → Red**

**TRACK 2 INTERVENTION SEQUENCE (Mid-Market Human-in-the-Loop):**

**Day 0 — CSM sends immediately:**
Subject: "Quick question about your Heliograph setup, Tim"
Preview: A heads-up + something that might be useful for your team right now
From: [CSM Name] <csm@heliograph.io>

Hi Tim,

I noticed Sarah recently moved on from Acme — congrats to her on the new role. Transitions like this are always a good moment to make sure your team is set up for success going forward.

I'd love to make sure whoever picks up Sarah's reporting workflows has everything they need — she'd built some really powerful dashboards that your finance team was getting a lot of value from (40% reduction in monthly close reporting time, if I recall correctly).

Could we grab 20 minutes this week? I can walk through what's been built, identify any quick wins for the new owner, and make sure nothing falls through the cracks during the transition.

[One-click calendar link]

P.S. — I can also put together a quick handoff summary for Sarah's replacement. Happy to do that before our call.

[CSM Name]
Customer Success, Heliograph Analytics

**Day 3 — If no response:**
Action: CSM creates LinkedIn connection request to Tim Rourke + researches who replaced Sarah (LinkedIn, company website, email domain search)
Message: "Hi Tim — I sent an email a few days ago about Acme's Heliograph setup during the team transition. Happy to help make the handoff seamless — 15 minutes this week?"

**Day 5 — If Sarah's replacement is identified (let's say: Marcus Webb, new Head of Analytics):**
Subject: "Marcus — welcome to Heliograph. Your setup is ready."
From: [CSM Name]
Body: [Full onboarding re-engagement email walking Marcus through what Sarah built and offering a 1:1 tour]

**Day 7 — VP Customer Success escalates:**
VP CS sends to CFO Tim Rourke directly:
Subject: "Acme + Heliograph — 3 things I want to make sure you know"
[Strategic executive-to-executive email focusing on ROI realized, upcoming renewal, and offer to personally oversee transition]

**Day 14 — ROI Quantification Email:**
Subject: "What Acme got from Heliograph in 18 months (numbers attached)"
[Personalized PDF attachment with: hours saved, reports automated, dashboards active, cost per user vs. alternatives]

**Day 21 — Final decision checkpoint:**
If re-engaged → move to renewal acceleration track
If no response from either Tim or Marcus → CSM escalates to CRO; consider contract restructure or pause option to salvage relationship

---

**AUTOMATION TRIGGERS (HubSpot workflow pseudocode):**

IF contact.last_login_date > 14 days ago
AND contact.product_tier = "power_user"
THEN:
  → Set health_score_flag = "champion_risk"
  → Create CRM task for CSM: "Reach out — power user inactive"
  → Enroll in Track 2: Day 0 email sequence
  → Alert: Slack notification to CSM + CS Manager

IF support_ticket.subject CONTAINS ("export", "download all", "cancel", "leaving")
THEN:
  → Immediately set health_score = Red
  → Create CRM task: "URGENT: Exit intent ticket — intervene today"
  → Alert CS Manager via Slack

## Success Metrics

**Intervention Effectiveness:**
- Re-engagement rate within 14 days of intervention (target: >35% for Red accounts)
- Health score recovery: % of Red accounts that return to Yellow or Green within 30 days (target: >25%)
- Renewal rate for intervened cohort vs. control (target: >15 percentage point lift)
- Time to first human response for Red accounts (target: <4 hours)

**Program Health:**
- Net Revenue Retention (NRR) improvement quarter-over-quarter (target: +5-10 points)
- Churn prediction model accuracy (target: >80% precision at 60-day window)
- Early warning coverage: % of churned accounts that had Red signal >30 days before cancellation (target: >70%)
- CSM capacity utilization: % of alerts resolved without escalation (target: >60%)

**Financial Impact:**
- ARR saved per quarter attributed to retention program
- CAC avoided (retained customers vs. replacing with new acquisition)
- Program ROI: (ARR saved) / (program operating cost + CSM time) — target >10:1

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Customer-Retention-&-Expansion-Revenue-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Customer-Retention-&-Expansion-Revenue-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Customer-Win-Back-&-Cold-Lead-Reactivation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Customer-Win-Back-&-Cold-Lead-Reactivation-Engine.md)
- [`../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md`](../../05_Analytics-&-Marketing-Operations/Advanced-Marketing-Intelligence/Predictive-Revenue-Forecasting-Engine.md)

## Integration Tips

**Gainsight / ChurnZero:**
- Use the health score weights from this prompt to configure your CS platform's native health score model
- Map churn signals to "call to action" (CTA) rules — each signal triggers the corresponding intervention track automatically
- Export the email templates directly into Gainsight's Success Plan templates or ChurnZero's Journey builder

**HubSpot:**
- Build the 3-track intervention sequences as HubSpot Sequences (sales sequences for CSM touches) and Workflows (automated marketing touches)
- Use HubSpot's custom properties to store health score, risk tier, and last intervention date
- Set up Slack integration via HubSpot Operations Hub to alert CSMs in real-time when Red triggers fire

**Salesforce + Gainsight:**
- Sync health scores to the Opportunity record on renewal opportunities
- Set up Gainsight's "Cockpit" to surface churn signals as prioritized CTAs in the CSM dashboard
- Use Revenue Grid or Clari to incorporate churn risk into renewal pipeline forecasting

**Segment / Amplitude / Mixpanel (Product Analytics):**
- Create behavioral cohorts for each risk signal (e.g., "users who haven't activated core feature in 14 days")
- Pipe these cohorts into your CRM via Segment Destinations or Zapier
- Set up Amplitude's notification center to push real-time alerts to Slack when power users go inactive

**Zapier / Make.com (No-code automation):**
- Trigger: New row in "At-Risk Customers" Google Sheet → Create HubSpot task + enroll in sequence + Slack alert
- Trigger: Stripe subscription status changes to "past_due" → Immediately enroll in financial risk intervention
- Trigger: G2 review posted with <3 stars → Alert CSM + schedule executive call

## Troubleshooting

**Problem: Health score is flagging too many false positives (everyone looks at-risk)**
Solution: Calibrate your signal weights against 12 months of historical churn data. Run a logistic regression or use a simple scoring model on your actual churned vs. retained cohorts to determine which signals have the highest predictive power for your specific product. Vacation periods and seasonal usage drops are common false positives — add a "usage seasonality baseline" that compares current usage to the same period last year, not just the trailing 90-day average.

**Problem: CSMs are overwhelmed with alerts and ignoring them ("alert fatigue")**
Solution: Implement a strict tiering protocol — only Red accounts with >$20K ARR or <60 days to renewal generate human tasks. All others are handled by automated Track 1 sequences. Build a daily "top 5 priority accounts" digest for each CSM that surfaces only the accounts requiring immediate action, ranked by ARR × churn probability.

**Problem: Intervention emails feel generic and aren't getting responses**
Solution: The personalization tokens are critical — generic outreach performs <5% better than spam. Require CSMs to add at least one specific, data-backed proof point in every outreach (e.g., "You ran 47 reports last quarter — your team is clearly getting value"). Use AI to auto-generate the personalized proof point by pulling from the customer's product usage data and CRM notes before the email is sent. Build this as a pre-populated draft, not a template the CSM fills in.

## Version History
- v1.0: Initial creation (auto-generated)
