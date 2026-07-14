# AI-Powered B2B SaaS Product Usage Signal-Triggered Customer Marketing Orchestration & Lifecycle Revenue Intelligence Engine - Convert Product Analytics Into Automated Marketing Programs That Drive Expansion, Advocacy, and Churn Prevention

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, saas, customer-marketing, plg, product-led-growth, product-analytics, churn-prevention, expansion-revenue, nrr, lifecycle-marketing, marketing-automation, customer-success, advocacy

## Overview
Designs a fully automated AI-agent system that monitors real-time product usage signals — adoption milestones, feature engagement, seat utilization, login frequency, workflow completion rates — and triggers the exact right marketing program for each account at each lifecycle stage. Use it when you have product telemetry data sitting unused in your analytics stack while your CS and marketing teams operate on manual gut-feel cadences instead of data-driven automated interventions.

## Quick Copy-Paste Version

You are a B2B SaaS customer lifecycle marketing strategist specializing in product-led marketing automation. Build a complete system that uses product usage signals to automatically trigger the right marketing program for each customer account at every lifecycle stage.

**Company profile:**
- Product: [e.g., project management platform, revenue intelligence SaaS, HR tech suite]
- ACV: [$X] | ARR: [$X] | Customer base: [#] accounts
- Current NRR: [X%] | Churn rate: [X%/year] | Expansion revenue as % of ARR: [X%]
- Product analytics tool: [Amplitude/Mixpanel/Heap/Pendo/Custom]
- CRM: [Salesforce/HubSpot] | Marketing automation: [Marketo/HubSpot/Pardot]
- CS platform: [Gainsight/ChurnZero/Totango/None]

**Key product events we track today:**
- [e.g., daily active users, feature X adoption rate, integration connections, reports created, team invites sent]

**Current marketing programs in place:**
- [List: onboarding emails, QBR outreach, renewal campaigns, etc. — or "ad hoc only"]

**Revenue signals I care about:**
- Expansion trigger: [e.g., >80% seat utilization, new business unit signed up, API volume threshold]
- Advocacy trigger: [e.g., NPS 9-10 submitted, >6 months tenure + high engagement]
- Churn risk trigger: [e.g., <30% DAU vs. first 30 days, no login in 14 days, support tickets spike]

Build:
1. **Signal Detection Architecture** — the 8-12 product signals that predict expansion readiness, advocacy potential, and churn risk, with specific threshold values and confidence weights
2. **Lifecycle Stage Marketing Programs** — for each stage (onboarding, activation, adoption, expansion-ready, at-risk, renewal, post-renewal), define the exact marketing program that fires, the channel mix (email, in-app, paid retargeting, direct outreach), and the message framework
3. **AI Agent Orchestration Logic** — how an AI agent monitors signals, scores accounts, prevents overlap (account can't receive churn-prevention AND expansion campaign simultaneously), and escalates edge cases to human review
4. **Expansion Revenue Plays** — 3 specific signal-triggered expansion campaigns with subject lines, CTAs, and sequence logic
5. **Advocacy Recruitment Automation** — how to identify and enroll high-NPS, high-engagement customers into a champion program automatically, with the enrollment sequence
6. **Measurement Framework** — how to measure the incremental revenue impact of signal-triggered marketing vs. your control group baseline

Give me specific trigger conditions, decision tree logic, and the exact automation rules — not general best practices.

## Advanced Customizable Version

### Role & Context
You are a Senior Customer Lifecycle Marketing Manager at a B2B SaaS company operating at $20M–$150M ARR. You sit at the intersection of marketing, customer success, and product — responsible for building the automated marketing programs that convert product usage data into measurable NRR improvement. Your mandate: design and deploy an AI-agent-driven system where product telemetry is the "always-on CSM" that triggers marketing interventions at the moment of highest impact, without requiring your CS team to manually identify and flag every account state change. The system must operate autonomously 80% of the time, with human escalation only for high-ACV at-risk accounts (>$50K ACV) and champion recruitment decisions.

### Inputs Required

**Business context:**
- Company name: [Company Name]
- Product category: [e.g., Sales Intelligence / DevOps / FinOps / Marketing Analytics / HR Automation]
- ARR: [$X] | Growth rate: [X% YoY] | Customer count: [#]
- Current NRR: [X%] | Target NRR: [X%] | NRR gap to close: [$X ARR]
- Average ACV: [$X] | ACV distribution: [% <$10K / % $10K–$50K / % >$50K]
- Customer base composition: [% Enterprise / % Mid-Market / % SMB]
- Gross retention rate: [X%] | Net logo churn: [X logos/quarter]

**Product analytics maturity:**
- Primary product analytics platform: [Amplitude / Mixpanel / Heap / Pendo / Gainsight PX / Custom BI]
- Events currently tracked: [List 8-15 key product events]
- Account-level rollup available: [Yes/No — can you aggregate user events to account level?]
- Real-time vs. batch data: [Real-time streaming / Daily batch / Weekly batch]
- Existing health score: [Yes — describe logic / No — needs to be built]

**Current marketing & CS tech stack:**
- CRM: [Salesforce / HubSpot] with [Gainsight / ChurnZero / Totango / None] for CS
- Marketing automation: [Marketo / HubSpot / Pardot / ActiveCampaign]
- In-app messaging: [Pendo / Appcues / Intercom / None]
- Paid retargeting: [LinkedIn / Google / Meta / None]
- Workflow automation: [Zapier / Make / n8n / Workato / Native integrations only]

**Revenue growth priorities (rank 1-3):**
- [ ] Reduce gross churn — current: [X%], target: [X%]
- [ ] Increase expansion revenue — current: [X% of ARR], target: [X% of ARR]
- [ ] Grow advocacy/referral pipeline — current: [$X/quarter], target: [$X/quarter]

### Objectives
Design a complete AI-agent-driven product usage signal-triggered marketing orchestration system that:
1. Monitors 10+ product usage signals continuously and scores each account on Expansion Readiness, Advocacy Potential, and Churn Risk dimensions
2. Triggers the right marketing program automatically when any account crosses a signal threshold
3. Prevents conflicting program enrollments (e.g., an account cannot receive an expansion upsell campaign and a churn rescue campaign simultaneously — churn rescue always takes priority)
4. Personalizes message content, timing, and channel based on account segment (ACV tier, industry, persona, lifecycle stage)
5. Escalates high-stakes decisions (large ACV at-risk, executive-level champion recruitment, complex expansion deals) to human review with context brief
6. Generates weekly performance reports showing NRR impact attribution by signal type and program

### Required Output Sections

**Section 1: Signal Architecture & Scoring Model**
Build the complete signal detection framework:

A. **Expansion Readiness Signals (score 0-100)**
Define 4-5 signals that indicate an account is ready for an expansion conversation:
- Seat/license utilization threshold (e.g., >85% seats filled for 30+ days)
- Feature adoption depth (e.g., using 4+ of 7 core modules)
- Power user density (e.g., 3+ users with >5 sessions/week in past 30 days)
- Integration complexity (e.g., connected 3+ integrations, indicating deep workflow embedding)
- Value realization milestone (e.g., completed first full workflow cycle end-to-end)

For each signal: threshold value, scoring weight, data source, update frequency, confidence multiplier when 2+ signals fire simultaneously.

B. **Advocacy Potential Signals (score 0-100)**
Define 4-5 signals that identify high-probability advocates:
- NPS score ≥9 submitted in last 90 days
- Tenure ≥6 months + engagement score in top 25%
- Unprompted positive support tickets or community posts
- Referral intent indicated in CS conversation (flag from Gainsight/SFDC)
- Social mention of product (LinkedIn, Twitter/X, G2 review submitted)

C. **Churn Risk Signals (score 0-100)**
Define 4-5 early warning signals:
- DAU/WAU decline: >40% drop vs. rolling 30-day baseline
- Login frequency decline: <2 logins/week per licensed user
- Support ticket volume spike: >3x baseline in past 14 days
- Feature regression: was using feature X, stopped using it for 21+ days
- Champion departure: primary contact changed (detected via email domain or contact field update in CRM)

**Section 2: Lifecycle Stage Marketing Programs**
For each of the 7 lifecycle stages, define the complete marketing program:

**Stage 1: Onboarding (Day 0–30)**
- Trigger: Account provisioned + primary contact confirmed
- Signal threshold to advance: First value milestone completed (define for [Product])
- Marketing program: [5-email welcome + value acceleration sequence] + [in-app tooltips for top 3 highest-impact features] + [1 CSM intro video from marketing]
- Message framework: Jobs-to-be-Done framing — focus on the outcome the champion said they wanted in the sales cycle
- Escalation: If no login within 7 days of provisioning → immediate CS alert + day-8 "rescue" email from CSM alias

**Stage 2: Activation (Day 31–90)**
- Trigger: First login milestone reached, not yet at full product adoption
- Signal threshold: <3 of 7 core features activated by day 60
- Marketing program: Feature discovery drip (1 email/week, max 4 emails) + in-app guided tours for unconsumed features + customer success webinar invitation (group onboarding session)
- Escalation: If activation <30% at day 75 → flag for CS review with "30-day activation risk" report

**Stage 3: Adoption (Day 91–180)**
- Trigger: Core workflow established, regular usage pattern
- Signal threshold: DAU/WAU healthy + 3+ features activated
- Marketing program: Peer community invitation + customer spotlight opportunity outreach + case study participation ask (if advocacy score ≥65)
- Goal: Deepen stickiness through community connection and identity reinforcement (psychological principle: identity-based loyalty — customers who publicly associate their success with your product churn at 40% lower rates)

**Stage 4: Expansion Ready (Ongoing)**
- Trigger: Expansion Readiness Score ≥75 for 14+ consecutive days
- Marketing program:
  - Automated email to champion: "You're getting [X% outcome] — here's how [Company Name] teams like yours unlocked [Y%] more by expanding to [Module/Tier]"
  - LinkedIn retargeting: ROI-focused creative to champion + economic buyer simultaneously
  - CS alert: "Account ready for expansion conversation" with AI-generated account brief including usage data, ROI proof points, and recommended expansion SKU
  - Direct mail: For accounts >$25K ACV — personalized printed ROI report mailed to economic buyer
- Sequence: Email day 1 → LinkedIn ad activation day 3 → CS follow-up email day 7 → CSM outreach day 10

**Stage 5: At-Risk (Ongoing)**
- Trigger: Churn Risk Score ≥65 OR any single high-confidence churn signal fires
- Marketing program (tiered by ACV):
  - SMB (<$10K ACV): Automated 3-email rescue sequence + in-app re-engagement module + free "Quick Win" session with implementation specialist offer
  - Mid-Market ($10K–$50K ACV): Above + CSM-branded personal video (Vidyard auto-personalized with usage data) + ROI recalibration report
  - Enterprise (>$50K ACV): Immediate human escalation — AI generates executive brief + recommended rescue plays for CSM + optional executive sponsor letter from VP CS
- Enrollment rule: At-risk enrollment IMMEDIATELY pauses all other marketing programs for that account

**Stage 6: Renewal (90 days pre-renewal)**
- Trigger: Contract end date –90 days, Churn Risk Score <50
- Marketing program: 3-touch renewal sequence from CSM alias + ROI recap report (auto-generated from product usage data) + renewal incentive if applicable + customer expansion case study featuring similar-profile customer
- For healthy accounts: weave in expansion discussion as part of renewal conversation, don't treat as separate

**Stage 7: Post-Renewal / Long-Tenure (180+ days, healthy)**
- Trigger: Renewed + Advocacy Potential Score ≥70
- Marketing program: Champion program enrollment invitation → speaking opportunity outreach → co-authored thought leadership offer → referral program enrollment
- Goal: Convert your 10% highest-satisfaction customers into an active pipeline source generating 15–20% of new logo pipeline within 12 months

**Section 3: AI Agent Orchestration Architecture**
Define the complete automation logic:

A. **Account State Machine**
Each account exists in exactly ONE primary state at any time. Define state transition rules:
ONBOARDING → ACTIVATION (trigger: first value milestone)
ACTIVATION → ADOPTION (trigger: 3+ features active + DAU healthy)
ADOPTION → EXPANSION_READY (trigger: Expansion Score ≥75)
ADOPTION → AT_RISK (trigger: Churn Score ≥65 — overrides all other states)
EXPANSION_READY → AT_RISK (if churn signal fires — immediately halts expansion program)
[Any state] → RENEWAL (90 days pre-contract expiry, unless AT_RISK)
RENEWAL → POST_RENEWAL (on renewal confirmation)

B. **Conflict Resolution Rules**
Priority hierarchy (highest to lowest):
1. AT_RISK (churn prevention — always wins)
2. RENEWAL (contract timing — critical)
3. EXPANSION_READY (revenue growth)
4. ADVOCACY_ELIGIBLE (pipeline generation)
5. ADOPTION (retention)
6. ACTIVATION (time-sensitive in first 90 days)

C. **AI Agent Daily Operating Cadence**
- 6:00 AM: Ingest previous day's product telemetry batch, update all account scores
- 6:30 AM: State machine evaluation — identify accounts that changed state overnight
- 7:00 AM: Enrollment queue generation — list of accounts to enroll in new programs
- 7:30 AM: Conflict check — validate no account enrolled in conflicting programs
- 8:00 AM: Human escalation report — email to CS leads with accounts requiring human judgment
- 8:30 AM: Automated enrollment execution — trigger MAP workflows for eligible accounts
- Real-time: Monitor for high-confidence single signals (e.g., champion departure) that require same-day response

D. **Personalization Variables**
Each triggered program auto-personalizes based on:
- [Account Name], [Champion First Name], [Economic Buyer Name]
- [Product category used most], [Top feature by session time]
- [% utilization vs. industry benchmark]
- [Outcome metric relevant to their use case] — pulled from CRM opportunity "success criteria" field
- [Comparable customer case study] — matched by industry + company size

**Section 4: Measurement & Revenue Attribution Framework**
Define how to prove NRR impact:

A. **Hold-out test design**: 10% of eligible accounts in each program randomly held out as control group (no triggered marketing, only CS-native outreach). Measure NRR, expansion conversion rate, and churn rate delta at 90-day intervals.

B. **Program-level metrics by stage**:
- Onboarding: Day-30 activation rate, time-to-first-value milestone, 90-day retention rate
- Expansion Ready: Pipeline generated by signal-triggered programs vs. control, expansion win rate, days from signal to closed expansion deal
- At-Risk: Churn rate for rescued accounts vs. control, time-to-resolution, rescue program ROI ($ARR saved per $1 marketing spend)
- Advocacy: Champion enrollment rate, referrals generated, pipeline from customer-sourced introductions

C. **Monthly NRR attribution report template**:
- Starting ARR: [$X]
- Expansion from signal-triggered programs: [$X] (vs. [$X] control baseline)
- Churn prevented by at-risk programs: [$X] (estimated based on churn rate delta)
- Net Marketing-Influenced NRR Impact: [$X] (conservative estimate with confidence interval)
- Program cost (marketing automation + content + tools): [$X]
- Marketing NRR ROI: [X:1]

### Constraints & Quality Guardrails
- Never trigger marketing to accounts currently in active escalation with CS (check "CS Escalation" flag in CRM before enrollment)
- Respect opt-out preferences — all triggered emails must include unsubscribe for marketing communications (separate from CS relationship emails)
- Signal thresholds must be validated quarterly — product usage patterns change as the product evolves; stale thresholds fire false positives
- Champion personas only — never contact end users who are not designated contacts in CRM (privacy + relationship protection)
- Maintain a "marketing fatigue" check — no account should receive more than 2 marketing emails per week from any combination of programs

## Example Input/Output

**Input Example:**

Company: Dataforma (fictitious) — B2B SaaS construction project management platform  
ARR: $42M | NRR: 108% | Target NRR: 118% | 680 accounts  
ACV: $62K average | Distribution: 40% SMB, 45% mid-market, 15% enterprise  
Product analytics: Amplitude | CRM: Salesforce | MAP: HubSpot | CS: Gainsight  
Key events tracked: Project created, task assigned, document uploaded, team invited, report exported, integration connected, mobile app login  
Priority: Increase expansion revenue (current: 12% of ARR → target: 20%) + reduce gross churn (current: 7% → target: 4%)

**Output Example (Expansion Ready Program):**

*Signal Detection Result for Acct: Meridian Construction Group*
- Seat utilization: 89% (71/80 seats active) — score: 28/30
- Feature adoption: 6/8 modules active including advanced reporting — score: 22/25
- Power user density: 4 users with daily engagement — score: 18/20
- Integration depth: Connected Procore + QuickBooks + Autodesk — score: 15/15
- Value milestone: Completed 3 full project cycles end-to-end — score: 10/10
- **Expansion Readiness Score: 93/100 — EXPANSION TRIGGER FIRED**

*Automated Actions Initiated (7:32 AM):*
1. Champion email queued (Sarah Chen, Project Operations Director) — send Day 1, 10:00 AM local time:
   Subject: "Meridian is in the top 8% of Dataforma power users — here's what that unlocks"
   Body: Personalized with her project count, team productivity metric vs. industry benchmark, and case study from Turner Construction (similar profile, added 25 seats in 2024, saw 31% faster project close rate)
   CTA: "See Meridian's expansion options" → links to personalized ROI calculator with Meridian's actual usage data pre-populated

2. LinkedIn retargeting activated for Sarah Chen + CFO (David Park, identified in SFDC) — ROI-focused ad featuring Turner Construction case study, running for 21 days, $12/day budget, frequency cap 5 impressions/week

3. CSM (Jennifer Walsh) notified via Gainsight alert with AI-generated account brief:
   "Meridian hit Expansion Readiness Score 93. They're at 89% seat utilization, have connected 3 major integrations, and completed 3 full project cycles. Recommended expansion: add 20 seats + Professional Analytics module ($18K expansion). Turner Construction is the best reference — similar project volume. I've queued a champion email to Sarah Chen for Day 1. Recommended: follow up on Day 10."

4. Day 10: CSM follow-up email queued (from Jennifer Walsh's actual email, MAP sends) — references Sarah's response to Day 1 email if opened (personalization via HubSpot token)

*Day 21 result:* Sarah responded Day 3. CSM called Day 10. Discovery call scheduled Day 15. Expansion quote delivered Day 18 for 22 seats + analytics module ($19,800 expansion ACV).

---

**Churn Risk Program Triggered (same company, different account):**

*Signal Detection Result for Acct: Pinnacle Builders LLC*
- DAU decline: 61% drop in past 28 days (12 DAU → 5 DAU) — Churn Signal CRITICAL
- Feature regression: Document management not accessed in 22 days — Churn Signal MODERATE
- Support tickets: 4 tickets in 14 days (3x baseline) — Churn Signal HIGH
- **Churn Risk Score: 81/100 — AT-RISK PROGRAM ACTIVATED**

*Immediate Actions (real-time, 2:17 PM):*
1. All other HubSpot program enrollments for Pinnacle Builders immediately paused
2. CSM (Marcus Rivera) alerted via Gainsight + Slack: "URGENT: Pinnacle Builders Churn Risk 81. DAU dropped 61% in 28 days + 4 support tickets. Contract value: $28,400. Renewal in 6 months. See attached usage trend. Recommended: call today."
3. AI-generated rescue brief created for Marcus: Timeline of engagement decline, last support issue summary, champion (Tom Walsh, VP Construction Ops) last login date, 3 recommended rescue conversation angles based on their original purchase reasons (pulled from SFDC opportunity notes)
4. Day-2 (if CSM confirms contact made): Mid-Market rescue email sequence queued — CSM alias, subject: "Quick question about your Dataforma experience, Tom" — personal, not salesy, focused on understanding the issue
5. Offer: Complimentary "Value Acceleration Session" with implementation specialist — 45-minute working session to address top pain points

## Success Metrics

- **Expansion conversion rate from signal-triggered programs vs. control**: Target ≥2.5x lift
- **Time from expansion signal to closed expansion deal**: Target <45 days (vs. 90+ days for CS-only outreach)
- **At-risk rescue rate**: Target ≥40% of at-risk accounts return to healthy status within 60 days
- **Gross churn rate reduction**: Target 2-3 percentage point improvement within 2 quarters of full deployment
- **NRR improvement**: Target 4-8 NRR point improvement within 4 quarters
- **Signal accuracy rate**: Track false-positive rate — expansion signals that fire but account is not actually ready (CSM feedback loop). Target: <20% false positive rate
- **Marketing-to-CS overlap**: Measure accounts where marketing and CS were operating in parallel without coordination — target <5% of accounts in any week
- **Program enrollment fatigue**: Monitor email engagement rates by program sequence position — if open rate drops >40% between email 1 and email 3, sequence needs revision

## Related Prompts

- [Customer-Led Growth Program Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Customer-Led-Growth-Program-Architecture-&-Customer-Network-Pipeline-Revenue-Intelligence-Engine.md)
- [Customer Marketing Expansion Revenue Campaign](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Customer-Marketing-Expansion-Revenue-Campaign-Architecture-&-Cross-Sell-Upsell-Pipeline-Intelligence-Engine.md)
- [Product Usage Signal & Expansion Revenue Trigger](../../06_Customer-Success-&-Retention/Customer-Success-Automation/AI-Powered-B2B-Product-Usage-Signal-&-Expansion-Revenue-Trigger-Intelligence-Engine.md)
- [At-Risk Account Marketing Rescue & Churn Prevention](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-At-Risk-Account-Marketing-Rescue-&-Churn-Prevention-Campaign-Intelligence-Engine.md)

## Integration Tips

- **Amplitude → HubSpot**: Use Amplitude's HubSpot integration to sync computed account-level properties (expansion score, churn risk score, lifecycle stage) as custom contact/company properties in HubSpot. Trigger HubSpot workflow enrollment when property value crosses threshold.
- **Gainsight → Salesforce → HubSpot**: Push Gainsight health scores and CSM escalation flags to Salesforce custom fields; HubSpot syncs via native Salesforce integration; use "Do Not Contact (Marketing)" field to suppress at-escalation accounts from all marketing programs automatically.
- **Pendo → Marketo**: Pendo's NPS survey results and in-app engagement data can sync to Marketo via the native connector or Zapier — use NPS score field to enroll 9–10 responders directly into the advocacy recruitment sequence.
- **LinkedIn Campaign Manager**: Use HubSpot's LinkedIn integration to add/remove contacts from LinkedIn Matched Audiences automatically as accounts enter/exit expansion-ready or at-risk programs — no manual audience uploads.
- **Slack alerts**: Use Zapier or HubSpot → Slack integration to push real-time at-risk alerts to a #customer-health Slack channel visible to both CS and marketing teams — prevents situations where CS discovers an issue that marketing already knows about.
- **Vidyard**: For mid-market at-risk accounts, use Vidyard's HubSpot integration to trigger a personalized video message from the CSM's template library — video open notification feeds back into HubSpot to update engagement score and trigger next-step automation.

## Troubleshooting

**Problem: Signal thresholds are firing too many false positives — expansion campaigns are going to accounts that aren't actually ready, damaging CS relationships.**
Solution: Add a 14-day confirmation window to expansion signals — account must hold above threshold for 14 consecutive days before enrollment triggers. Also implement CSM veto: send CSM a 24-hour preview email before enrollment fires, with a single-click "Hold this account" option that delays enrollment 30 days and logs the reason.

**Problem: Marketing and CS teams are duplicating outreach to the same accounts — customers complain of too many contacts.**
Solution: Implement a hard "Marketing Suppression" list in your MAP that the CS team can add accounts to on-demand (via a simple Salesforce/HubSpot field update). Additionally, require that any CSM-owned account in active expansion conversation stage gets automatically added to suppression until deal closes or goes dormant.

**Problem: Product usage data is batched daily but some churn signals require same-day response (e.g., champion departure).**
Solution: Create two signal pipelines: (1) batch pipeline for score-based signals that run nightly, and (2) event-based real-time pipeline for high-urgency binary signals (champion contact change in CRM, NPS detractor submitted, support ticket marked "critical"). Use Zapier or Make to trigger real-time alerts from Salesforce/HubSpot workflow changes without waiting for the daily batch.

## Version History
- v1.0: Initial creation (auto-generated)
