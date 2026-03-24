# Digital-Led Customer Success & Scaled CS Program Intelligence Engine - Automate High-Quality Customer Outcomes at Scale Without Proportional Headcount

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** customer-success, retention, automation, saas, b2b, plg, tech-touch, nrr

## Overview
Designs and orchestrates a complete digital-led customer success program that delivers personalized, proactive CS motions at scale — using product usage signals, behavioral triggers, and AI personalization to achieve enterprise-quality outcomes across hundreds or thousands of accounts without proportional CSM headcount growth.

## Quick Copy-Paste Version

You are an expert Customer Success strategist specializing in scaled/digital CS programs for B2B SaaS. Design a complete digital-led CS program for my company.

Company context:
- Product: [describe your SaaS product in 1-2 sentences]
- Customer segments: [e.g., SMB <50 seats, Mid-market 50-500 seats, Enterprise 500+]
- Current CSM ratio: [e.g., 1 CSM per 80 accounts]
- Key retention metric: [Net Revenue Retention target, e.g., 110% NRR]
- Tech stack available: [e.g., Gainsight/ChurnZero/Totango + HubSpot + Intercom + Pendo/Mixpanel]

Build a digital-led CS program that includes:

1. CUSTOMER SEGMENTATION FOR SCALED CS
Define which accounts go into tech-touch vs. scaled-touch vs. high-touch based on ARR, product usage, strategic value, and growth potential. Include a decision matrix with specific thresholds.

2. HEALTH SCORE AUTOMATION
Design a composite health score (0-100) using:
- Product adoption metrics (which features, frequency, breadth of users)
- Engagement signals (email opens, support ticket sentiment, NPS/CSAT)
- Business outcome indicators (outcomes achieved vs. success plan goals)
- Risk indicators (exec sponsor change, declining usage, billing issues)
Specify the weighting for each dimension and the red/yellow/green thresholds.

3. AUTOMATED ONBOARDING JOURNEY
Map a 90-day digital onboarding sequence with:
- Day-by-day in-app guidance triggers (what tooltip/modal fires when)
- Email sequence cadence with specific subject lines and CTAs
- Milestone celebrations and early value confirmation touchpoints
- Human escalation triggers (when automation hands off to a CSM)

4. PROACTIVE INTERVENTION PLAYBOOKS
For each health score drop scenario, define:
- Trigger condition (specific metric threshold crossed)
- Automated response (in-app message, email, Slack notification to CSM)
- Escalation path if no response in X days
- Recovery tracking mechanism

5. EXPANSION SIGNAL DETECTION
List the top 5 behavioral signals that indicate expansion readiness and the automated motion to initiate (e.g., 85%+ seat utilization → auto-trigger expansion campaign).

6. DIGITAL TOUCH PROGRAM CALENDAR
A 12-month rolling calendar of proactive digital touches: product update digests, benchmark reports, QBR-in-a-box templates, webinar invitations, and community engagement nudges.

7. AUTOMATION TOOLS CONFIGURATION
Specific configurations for [their tech stack] — which tool owns which motion, data flows between systems, and the minimum viable automation setup.

Output: A complete program blueprint with prioritized implementation roadmap (quick wins in 30 days, full program in 90 days), CSM capacity calculation showing headcount efficiency gain, and success metrics dashboard spec.

## Advanced Customizable Version

ROLE: You are a VP of Customer Success with 12 years of experience scaling CS organizations at B2B SaaS companies from Series B through IPO. You have built digital-led CS programs at companies managing 2,000–15,000 accounts with CSM ratios ranging from 1:50 to 1:300. You specialize in the intersection of product analytics, CS automation, and revenue retention.

COMPANY PROFILE:
- Company name: [COMPANY_NAME]
- Product category: [e.g., Marketing Automation, HR Tech, FinTech, DevTools]
- Business model: [SaaS subscription / usage-based / hybrid]
- ARR range: [$X–$Y ARR]
- Customer count: [X accounts]
- Segment breakdown: [SMB: X%, Mid-Market: Y%, Enterprise: Z%]
- Average contract value: [ACV range by segment]
- Current NRR: [X%] | Target NRR: [Y%]
- Gross churn: [X%] | Target: [Y%]
- Current CSM headcount: [X CSMs]
- Current CSM-to-account ratio: [1:X]
- Tech stack: [List all: CRM, CS platform, product analytics, email, in-app, community, BI tools]

PRIMARY OBJECTIVE: Design a full digital-led customer success program that achieves [TARGET_NRR]% NRR with a CSM ratio of [TARGET_RATIO] (e.g., 1:200 for SMB/lower-ACV segments) by replacing or augmenting manual CSM motions with data-triggered automation.

---

DELIVERABLE 1: CUSTOMER SEGMENTATION FRAMEWORK

Apply the DEAR segmentation model:
- D (Digital/Tech-Touch): [ACV threshold, e.g., <$10K ARR] — fully automated, no dedicated CSM
- E (Emerging/Scaled-Touch): [ACV threshold, e.g., $10K–$50K ARR] — pooled CSM model + automation
- A (Accounts/Mid-Market): [ACV threshold, e.g., $50K–$150K ARR] — named CSM + digital overlay
- R (Revenue/Strategic): [ACV threshold, e.g., >$150K ARR] — dedicated CSM, white-glove

For each tier, define:
- CSM ownership model (named / pooled / fully digital)
- SLA for response time and proactive outreach frequency
- Automation coverage percentage target (e.g., 80% of touches automated for Digital tier)
- Business case: annual CSM hours saved + cost avoidance

DELIVERABLE 2: COMPOSITE CUSTOMER HEALTH SCORE

Design a health score using the PULSE framework:
- P (Product Adoption): [30% weight]
  * Core feature adoption rate (users who activated ≥3 core features / total licensed users)
  * DAU/MAU ratio as engagement depth indicator
  * Feature breadth score (% of purchased modules actively used)
  * Power user identification (top 20% by usage frequency)
  
- U (Usage Trajectory): [20% weight]
  * 30/60/90-day login frequency trend (improving / flat / declining)
  * Session duration trend
  * API call volume trend (for product-led/developer tools)
  
- L (Lifecycle Milestones): [20% weight]
  * Onboarding completion percentage
  * Time-to-first-value achievement
  * Success plan milestone completion rate
  * ROI realization documented
  
- S (Sentiment & Satisfaction): [15% weight]
  * Latest NPS score and trend
  * CSAT from support interactions
  * Executive sponsor engagement score
  * Community participation / advocacy signals
  
- E (Expansion & Engagement Signals): [15% weight]
  * Seat utilization % (current users / licensed seats)
  * Feature request submissions
  * Integration activations
  * Champion job change risk (LinkedIn signal monitoring)

Score interpretation:
- 80-100 (Green): Healthy — expansion eligible, advocacy candidate
- 60-79 (Yellow): At Risk — proactive intervention required within 14 days
- 40-59 (Orange): High Risk — CSM escalation + executive outreach within 7 days
- 0-39 (Red): Critical — save play initiated within 48 hours

DELIVERABLE 3: DIGITAL ONBOARDING JOURNEY (Days 1-90)

Design a milestone-based journey with specific automation triggers:

PHASE 1: ACTIVATION (Days 1-14) — Goal: First Value Moment
Day 1 (0-4 hours post-contract): 
  - Automated welcome email from CSM (or CEO for Digital tier)
  - In-app product tour activation
  - Slack/Teams workspace setup (if applicable)
  - Admin setup checklist sent via email

Day 3: 
  - Check: Has admin completed setup? If NO → automated reminder + help link
  - If YES → trigger "Next Steps: Add Your Team" email sequence

Day 7: 
  - First milestone check: Has user activated [Core Feature 1]?
  - If NO → in-app modal: "Customers who activate [Feature 1] in week 1 see [X% better outcome] — here's a 5-minute guide"
  - If YES → celebrate via in-app banner + email: "You're ahead of 73% of new customers!"

Day 14:
  - Automated health score first snapshot
  - If health <60: trigger CSM alert for manual outreach
  - If health >60: continue digital journey

PHASE 2: ADOPTION (Days 15-45) — Goal: Multi-Feature Expansion
[Define specific feature adoption milestones for YOUR product]
- Identify the "Aha moments" for each core use case
- Map automated nudges for each unactivated feature
- Design peer-success benchmarking emails ("Companies like yours use X, Y, Z features — you're missing Z")

PHASE 3: OUTCOME REALIZATION (Days 46-90) — Goal: Documented ROI
Day 60:
  - Automated ROI calculation email: "Based on your usage, you've [saved X hours / processed X transactions / generated X leads]"
  - Net Promoter Score survey trigger
  - Success plan 90-day check-in (automated QBR-in-a-box for Digital tier)

Day 90:
  - If NPS ≥ 8 → trigger advocacy program enrollment
  - If NPS < 7 → trigger closed-loop follow-up sequence
  - Renewal prediction flag if contract ends in <180 days

DELIVERABLE 4: INTERVENTION PLAYBOOKS (Automated Save Plays)

For each trigger, specify: Detection Signal → Automated Response → Escalation Path → Resolution Tracking

PLAYBOOK A: "Usage Cliff" (30-day login drop >40%)
- Detection: Product analytics alert via [Mixpanel/Pendo/Amplitude]
- T+0: In-app re-engagement modal with "Quick Win" content
- T+3 days (no login): Email "We miss you" + personalized content based on their top use case
- T+7 days: Slack/SMS notification to pooled CSM queue
- T+14 days: Automated escalation to named CSM / CSM manager
- T+21 days: Executive sponsor outreach (auto-generated email for CSM review)

PLAYBOOK B: "Champion Departure" (Key user account deactivated or LinkedIn change detected)
- Detection: [Specify tool: e.g., Champify, People.ai, manual monitoring]
- T+0: Alert CSM immediately
- T+24h: Research new champion candidates from active user list
- T+3 days: Personalized onboarding sequence for new champion auto-triggered
- T+14 days: Executive alignment email template generated

PLAYBOOK C: "Renewal Risk 90-Day Window"
- Detection: Contract end date <90 days + health score <70
- T-90: Renewal preparation email to champion: ROI summary + renewal benefits
- T-75: If no response → executive sponsor email generated for CSM
- T-60: Automated success plan completion push
- T-45: CSM alert for renewal call scheduling
- T-30: Procurement contact outreach + order form generation

PLAYBOOK D: "NPS Detractor Response"
- Detection: NPS score ≤ 6 submitted
- T+2h: Automated acknowledgment email ("We hear you — here's what happens next")
- T+24h: CSM assigned for recovery call with prepared context brief
- T+72h: If no call scheduled → manager escalation
- T+30 days: Follow-up NPS pulse survey

DELIVERABLE 5: EXPANSION SIGNAL PLAYBOOKS

For each expansion trigger, define the automated motion:

Signal 1: Seat Utilization ≥85%
→ Automated email to admin: "You're using 85% of your licenses. Here's how to add seats in 60 seconds."
→ If ACV >$50K → also notify CSM to initiate expansion conversation

Signal 2: Heavy Usage of Locked/Premium Feature
→ In-app upsell message: "You've tried [Feature X] 12 times — it's included in [Premium Tier]"
→ Email case study: "See how [similar company] scaled results with [Premium Tier]"

Signal 3: New Department/Team Using Product (Multi-Dept Detection)
→ Detect: New user with different email domain pattern (e.g., @companydomain engineering vs. marketing)
→ Trigger: Cross-departmental expansion email to original champion
→ CSM alert for multi-threading conversation

Signal 4: API Usage >80% of Rate Limit
→ Automated alert: "You're at 82% of your API limit — upgrade for uninterrupted operations"
→ CSM alert to prepare usage-based expansion proposal

Signal 5: High Advocacy Score (NPS 9-10, peer review submitted, case study published)
→ Trigger referral program enrollment automatically
→ CSM briefed to offer reference program participation + premium benefits

DELIVERABLE 6: DIGITAL TOUCH PROGRAM — ANNUAL CALENDAR

Design a 12-month proactive communication calendar for Digital/Scaled tier accounts:

Monthly Cadence (all automated):
- Month 1-3: Onboarding milestones (per Deliverable 3)
- Month 4: "30-Day Feature Spotlight" — highlight underused high-value feature
- Month 5: Personalized benchmark report: "How your usage compares to top performers in your industry"
- Month 6: Mid-year business review (automated QBR-in-a-box: usage stats + ROI calculation + next-6-month success goals)
- Month 7: Product roadmap preview email (use product marketing content)
- Month 8: Customer education webinar invitation (relevant to their use case)
- Month 9: Community challenge or certification campaign
- Month 10: Annual renewal preparation + executive summary of value delivered
- Month 11: Success story sharing: "Customers like you are achieving [outcome] — want to be featured?"
- Month 12: Annual business review (automated) + renewal confirmation + upsell proposal if signals present

Quarterly Anchors:
- Q1: Annual planning webinar — how to achieve your goals with [Product]
- Q2: Industry benchmark report delivery (original research repurposed from marketing)
- Q3: New feature adoption sprint (3-week campaign for major release)
- Q4: Renewal and expansion season (30/60/90-day countdown sequences)

DELIVERABLE 7: TECHNOLOGY ARCHITECTURE & AUTOMATION CONFIGURATION

For the specified tech stack, provide:

CS Platform Configuration ([Gainsight / ChurnZero / Totango / Planhat]):
- Which health score components to build natively vs. pull from product analytics
- Playbook automation setup (specific playbook builder configuration)
- Timeline event types to track
- Success plan template structure
- Cockpit/workflow priority queues for pooled CSM teams

Product Analytics Integration ([Pendo / Mixpanel / Amplitude / Segment]):
- Key events to instrument (list the top 15 events that drive health score)
- Cohort analysis setup for adoption benchmarking
- Retention curve analysis configuration
- NUX (New User Experience) flow setup

CRM Integration ([Salesforce / HubSpot]):
- CS data fields to sync back to CRM (health score, NPS, adoption tier)
- Renewal opportunity creation automation rules
- Expansion opportunity creation triggers
- Customer 360 view field mapping

Email Automation ([HubSpot / Marketo / Customer.io / Iterable]):
- Lifecycle email programs to build first (prioritized)
- Segmentation logic for CS email lists vs. marketing lists
- Unsubscribe/communication preference management for CS vs. marketing emails
- Transactional vs. marketing email classification

In-App Messaging ([Intercom / Pendo / Appcues / Userflow]):
- Guide and tooltip trigger logic
- NPS survey timing and frequency caps
- Feature announcement targeting (only show to relevant users)
- In-app health score signal collection

DELIVERABLE 8: IMPLEMENTATION ROADMAP & ROI MODEL

Week 1-4 (Foundation):
- [ ] Health score v1 launched (use only 3-4 data sources initially)
- [ ] At-risk playbook automated (usage cliff + renewal risk)
- [ ] Welcome email sequence live for new customers
- [ ] CSM alert dashboards configured

Month 2 (Core Program):
- [ ] Full 90-day onboarding journey automated
- [ ] Expansion signal playbooks live
- [ ] Monthly proactive touch calendar operating
- [ ] QBR-in-a-box template deployed for Digital tier

Month 3 (Optimization):
- [ ] A/B testing framework for intervention emails
- [ ] Health score v2 with ML weighting (if available)
- [ ] Full 12-month calendar live
- [ ] CSM capacity reallocation plan executed

ROI Model:
Calculate expected impact:
- Gross churn reduction: [X% improvement] × [ARR at risk] = $[Y] retained ARR
- NRR improvement: [X% NRR improvement] × [total ARR] = $[Y] expansion
- CSM efficiency: [X hours/CSM saved/month] × [CSM fully loaded cost] = $[Y] cost avoidance
- Total first-year value: $[Z]

OUTPUT FORMAT: Provide the complete blueprint as a structured document with each deliverable clearly separated. Include a one-page executive summary suitable for presenting to CRO/CEO to secure investment in the program. Flag the top 3 risks to implementation success and mitigation strategies.

## Example Input/Output

**Input Example:**

Company: Mosaic Analytics (B2B SaaS revenue intelligence platform)
Product: Real-time revenue analytics and forecasting for B2B SaaS CFOs
Segments: SMB <$25K ACV (400 accounts), Mid-Market $25K-$100K (180 accounts), Enterprise >$100K (45 accounts)
Current NRR: 104% | Target: 118% NRR
Current CSM ratio: 1:40 (overstaffed SMB, under-resourced mid-market)
Tech stack: Gainsight, Salesforce, Pendo, HubSpot, Slack, Intercom

**Output Example (excerpt):**

**Segmentation Framework:**

| Tier | ACV Range | Account Count | ARR | Model | CSM Ratio |
|------|-----------|--------------|-----|-------|-----------|
| Digital | <$15K | 280 | $2.1M | Fully automated | 1:280 |
| Scaled | $15K-$50K | 220 | $6.6M | Pooled (3 CSMs) | 1:73 |
| Named | $50K-$100K | 100 | $7.5M | Named CSM | 1:25 |
| Strategic | >$100K | 25 | $4.2M | Dedicated | 1:8 |

**Health Score Design (Mosaic Analytics-specific):**

| Dimension | Weight | Green | Yellow | Red |
|-----------|--------|-------|--------|-----|
| Dashboard Creation Rate | 25% | >3 dashboards | 1-2 dashboards | 0 dashboards |
| Forecast Accuracy Improvement | 20% | >15% vs. baseline | 5-15% | <5% |
| CFO Active Usage (DAU) | 20% | Weekly | Bi-weekly | Monthly or less |
| Integration Breadth (CRM + ERP connected) | 15% | Both connected | 1 connected | Neither |
| NPS + CSAT Composite | 10% | >8.0 | 6.0-8.0 | <6.0 |
| Renewal Proximity Risk | 10% | >180 days | 90-180 days | <90 days |

**Usage Cliff Playbook (Automated):**

*T+0 (Day of Detection — login drop >40% vs. 30-day avg):*
- Pendo trigger: In-app modal fires on next login: "Mosaic works best when your team [core behavior]. Here's how 3 CFOs at similar companies use it daily →" [link to use case video]

*T+3 days (still no login):*
- HubSpot email from "CSM name": Subject: "Quick check-in on your revenue visibility — 2 minutes?" 
- Body: Personalized with their industry + last dashboard viewed

*T+7 days:*
- Gainsight CTA auto-created in pooled CSM queue: "Account [Name] — Usage Drop — Call or email required"

**Expansion Playbook — Seat Utilization Signal (Specific):**

*Trigger:* Pendo detects 87% of licensed seats active in last 30 days

*Automated action (via HubSpot + Gainsight):*
→ Email to Admin contact: 
Subject: "Your team is loving Mosaic — you're at 87% capacity"
Body: "Hi [Name], great news — 87% of your team is using Mosaic weekly. When you're ready to grow, adding seats takes under 2 minutes. [Add Seats Now →] or [Talk to us about team pricing →]"

→ Gainsight alert to Named CSM: "Mosaic Health — [Account] at 87% seat util — expansion conversation recommended"

**Implementation ROI (Mosaic Analytics):**

- Gross churn reduction from 8% → 5% on SMB tier: $168K ARR retained annually
- NRR improvement Digital tier 98% → 107%: $189K expansion ARR
- CSM capacity freed (2.5 FTE equivalent): $375K cost avoidance
- **Total first-year program value: ~$730K on $20.4M ARR base**

---

## Success Metrics

**Leading Indicators (measure weekly):**
- Time-to-first-value (days from contract to first core feature activation): Target <14 days
- Onboarding completion rate (% reaching Day 90 milestone): Target >75%
- Intervention response rate (% of at-risk accounts that recover within 30 days): Target >45%
- Expansion signal conversion rate (% of triggered accounts that expand within 90 days): Target >20%

**Lagging Indicators (measure quarterly):**
- Net Revenue Retention by segment: SMB target >105%, MM target >115%, Enterprise target >125%
- Gross churn rate: Target <5% annually for SMB, <3% for MM
- CSM-to-account ratio improvement: Target 25%+ efficiency gain in 12 months
- Customer health score distribution: Target >70% of ARR in Green tier

**Program Health Metrics:**
- Automation coverage rate: % of CS touches that are automated vs. manual
- Playbook trigger accuracy: % of intervention triggers that are true positives (not false alarms)
- Digital journey engagement: Open rates and CTA click-through rates on lifecycle emails

## Related Prompts

- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/Customer-Health-Score-&-Early-Warning-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/SaaS-Renewal-Intelligence-&-Automated-Contract-Renewal-Revenue-Engine.md`
- `../../06_Customer-Success-&-Retention/Customer-Onboarding-&-Activation/Product-Adoption-Acceleration-&-Feature-Engagement-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-Churn-Prediction-&-Proactive-Retention-Marketing-Engine.md`

## Integration Tips

**Gainsight / ChurnZero / Totango:**
- Map all 8 health score components as CTAs or Success Metrics
- Build automated playbooks that trigger at health score threshold crossings, not just manual CSM review
- Use Timeline event logging to capture all automated touches alongside manual touches for complete account history
- Configure Cockpit prioritization so CSMs see highest-risk accounts first, not just recently updated

**Salesforce / HubSpot CRM:**
- Sync CS health score as an Opportunity field on renewal opportunities for accurate forecasting
- Build CS data into Customer 360 dashboards accessible to Sales for expansion co-selling
- Create automated tasks/activities when playbooks trigger, so CSM activity is logged without manual entry
- Use Account scoring in Salesforce to de-prioritize at-risk accounts from Sales prospecting (protect relationships)

**Pendo / Mixpanel / Amplitude:**
- Set up product analytics alerts that push directly to CS platform via webhook (not just daily syncs) for real-time intervention
- Build adoption cohorts that segment by CSM tier (Digital vs. Named) to benchmark digital program performance
- Use retroactive analysis to identify which product behaviors at Day 30 best predict 12-month retention — these are your leading health score indicators

**Intercom / Appcues / Userflow:**
- Build separate "CS Lifecycle" flows distinct from "Product Onboarding" flows — CS flows focus on business outcomes, not just feature education
- Segment in-app messages by health score (only show upsell prompts to Green tier accounts)
- Use conversation routing to ensure CS-triggered chats go to CSMs, not support agents

**Slack / Microsoft Teams:**
- Create CS Slack workflow for real-time CSM alerts on usage cliffs and at-risk triggers
- Build automated "Weekly CS Digest" for CSMs showing their at-risk accounts and recommended actions
- Set up executive escalation channel for accounts in Red health status

## Troubleshooting

**Problem: Health score shows too many false positives — CSMs don't trust it and ignore playbooks**
Solution: Audit your health score weighting by pulling historical data — identify which signals actually correlated with churn vs. expansion over the past 12-18 months. Remove or down-weight signals with <30% predictive accuracy. Start with 3-4 highly reliable indicators before expanding to the full 8-component model. Run a "shadow period" for 60 days where playbooks alert but don't auto-execute, so CSMs can validate accuracy before trusting automation.

**Problem: Customers ignore automated emails — open rates below 15%**
Solution: Segment your sending domains — CS lifecycle emails should come from a CSM's named email address (even if automated), not a marketing noreply address. Personalize subject lines with account-specific data points (e.g., "Your [product] usage report for [Company Name]" vs. generic nurture). Reduce frequency and increase relevance — send 1 data-driven insight email worth opening vs. 4 generic "check-in" emails. A/B test CSM name vs. CEO vs. product team sender identity.

**Problem: CSMs resist the digital-led model — feel like they're losing control or relevance**
Solution: Frame digital CS as CSM leverage, not replacement — show CSMs the specific accounts where automation freed their time to focus on strategic conversations. Give CSMs full visibility into automated touches on their accounts via activity timeline. Create a "digital assist" model where CSMs can customize automated messages (not just accept defaults). Track and celebrate CSM efficiency metrics (ARR per CSM) not just churn metrics, making the efficiency gains personally rewarding.

## Version History
- v1.0: Initial creation (auto-generated)
