# AI-Powered B2B Community-Qualified Lead (CQL) Scoring & Sales Handoff Intelligence Engine - Convert Your Most Engaged Community Members into Pipeline Without Killing Community Trust

**Difficulty:** Advanced | **Time:** 20-25 min | **Tags:** b2b, analytics, community-led-growth, lead-scoring, CQL, pipeline, sales-handoff, intent-signals, community-analytics, saas, demand-generation, clg

## Overview
Builds a real-time Community-Qualified Lead (CQL) scoring system that identifies the highest-intent community members — those actively researching, asking buying questions, or exhibiting pre-purchase behaviors — and automates warm handoffs to sales with full context. Use this when you're investing in owned community (Circle, Slack, Discord, Discourse, Gainsight) and want to convert that engagement into measurable pipeline without spamming members or destroying the trust that makes the community valuable in the first place.

## Quick Copy-Paste Version

You are a senior B2B marketing operations expert specializing in community-led growth (CLG) and intent-based lead scoring. I need you to build a Community-Qualified Lead (CQL) scoring system for my B2B SaaS company.

My context:
- Company: [Company Name], selling [product category] to [ICP: job titles, company sizes]
- ACV: [$X]
- Community platform: [Circle / Slack / Discord / Discourse / Gainsight Community / Other]
- Community size: [X] members (breakdown: [X% customers / X% free trial users / X% prospects / X% unknown])
- CRM: [HubSpot / Salesforce]
- Current pipeline sourced from community: [none tracked / X% / unknown]

Please deliver:

1. CQL Signal Taxonomy — 15-20 specific community behaviors that indicate purchase intent, organized by signal strength (strong / moderate / weak), with the exact search strings or event types to monitor

2. CQL Scoring Model — A 100-point scoring system that weights community behaviors by purchase intent, including topic engagement signals, post type signals, recency decay, account-level amplification when multiple employees from the same company engage, and negative signals

3. CQL Threshold & Tier Framework — Define 3 tiers:
   - CQL-1 (Hot): Immediate SDR/AE outreach within 24 hours
   - CQL-2 (Warm): SDR sequence trigger within 72 hours
   - CQL-3 (Nurture): Marketing automation enrollment, no direct sales outreach

4. CRM Integration Blueprint — How to sync CQL scores to HubSpot/Salesforce, including custom field names, automation triggers, and the Slack/email alert format sent to the SDR when a prospect crosses the CQL-1 threshold

5. Sales Outreach Playbook — For each top-3 CQL signal type, the exact outreach approach that converts without feeling surveillance-y (including what NOT to say)

6. 30-Day Activation Plan — Week-by-week roadmap to go from zero CQL tracking to first community-sourced opportunity in CRM

## Advanced Customizable Version

ROLE: You are a VP of Marketing Operations with 12+ years of B2B SaaS experience at companies from $5M to $300M ARR. You specialize in intent-based lead scoring, community-led growth (CLG) programs, and revenue operations. You have hands-on experience building CQL frameworks using Circle, Gainsight Community, Vanilla Forums, Discourse, and Slack. You've designed the community data pipelines that connect engagement signals to Salesforce and HubSpot, built scoring models that revenue teams actually trust, and created sales plays that convert community conversations into booked meetings — without killing community culture. You understand the core paradox of community monetization: the harder you sell, the less valuable the community becomes, destroying the very asset you're trying to harvest.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product description: [1-2 sentences on what you sell]
- ARR: [$X] | Stage: [Seed / Series A / Series B / Series C / Growth]
- ICP: [Job titles] at [Company sizes] in [Industries]
- ACV: [$X] | Sales cycle: [X days average]
- Sales model: [Inbound-led / Outbound-led / PLG with sales-assist / Partner-led]
- CRM: [HubSpot / Salesforce] + Marketing Automation: [Marketo / Pardot / HubSpot / Other]

COMMUNITY CONTEXT:
- Platform: [Circle / Gainsight Community / Discourse / Slack / Discord / Vanilla / Custom]
- Total members: [X] | Monthly active members (MAM): [X]
- Member breakdown: [X% paying customers / X% free trial / X% prospects / X% unknown]
- Primary purpose: [Customer success / Demand generation / Developer ecosystem / Thought leadership / All]
- Community staff: [X FTEs / fractional / none]
- Annual cost (platform + staff): [$X]
- Current state: [No CQL tracking / Basic keyword monitoring / Some automation / Fully instrumented]

EXISTING INFRASTRUCTURE:
- Lead scoring model: [None / Basic demographic / Behavioral / Predictive AI-based]
- Integrations available: [Zapier / Make.com / native API / developer resources]
- Analytics stack: [Community native analytics / Segment / Data warehouse / Amplitude / Mixpanel]

OBJECTIVE:
- Pipeline contribution target from community: [X% of new pipeline]
- ROI pressure from leadership: [No pressure yet / Some questions / "Prove it or lose budget"]
- Sales team perception of community leads: [Love them / Skeptical / Don't know community exists]

---

DELIVERABLE 1: CQL SIGNAL TAXONOMY & INTENT CLASSIFICATION

Design a 3-tier signal taxonomy:

TIER 1 — EXPLICIT BUYING INTENT (15-25 points each):
Identify 8-10 specific community behaviors that directly indicate an active evaluation. For each:
- Signal name and exact description
- Example post/question text that triggers this signal
- Why this indicates buying intent (psychological framework — JTBD, decision theory, etc.)
- Detection method (keyword string, topic category, post type, combination)
- Decay rate (how quickly this signal loses weight without reinforcement)

Must include signals for: competitor comparison posts, pricing/packaging questions, implementation scoping ("we need X seats"), timeline urgency statements, ROI/business case building questions, and "who has done this with your product?" social proof seeking.

TIER 2 — IMPLICIT BUYING INTEREST (5-14 points each):
Identify 8-10 behaviors suggesting active consideration pre-decision:
- Feature benefit questions (not "how does X work" but "can X solve Y for us")
- Positive engagement with comparison or ROI content
- Multiple sessions in product-specific categories within 7 days (research sprint)
- Asking for customer introductions
- Budget cycle language ("planning for next fiscal year")

TIER 3 — ENGAGEMENT SIGNALS (1-4 points each):
Identify 5-8 behaviors indicating community investment without clear purchase signal:
- Regular content consumption without posting
- Event/webinar attendance
- Completing new member onboarding sequence
- Content downloads from community resource library

NEGATIVE SIGNALS (Subtract 5-20 points each):
- Active support complaints or unresolved issues
- Explicit competitor loyalty language ("we use [competitor] and plan to stay")
- Non-ICP identifiers (student, individual freelancer, wrong industry vertical)
- Job change signal to non-buying-authority role

---

DELIVERABLE 2: CQL SCORING MODEL ARCHITECTURE

BUILD THE COMPLETE SCORING ENGINE:

A. Individual Score Composition (0-100 points):
- Explicit intent signals: 40% weight
- Implicit interest signals: 30% weight
- Engagement frequency/recency: 20% weight
- Firmographic/demographic ICP fit: 10% weight

Define threshold cutoffs:
- CQL-1 (Sales-Ready): 70+ points → SDR/AE immediate action
- CQL-2 (Sales-Qualified): 45-69 points → SDR sequence enrollment
- CQL-3 (Marketing-Qualified): 25-44 points → Marketing automation only
- Community Member (No action): < 25 points

B. Account-Level Amplification Logic:
When multiple employees from the same company are active:
- 2 employees from same domain: multiply highest individual score × 1.3 (buying interest signal)
- 3+ employees from same domain: multiply × 1.5 (buying committee activation signal)
- C-suite + practitioner from same company simultaneously: automatic CQL-1 upgrade regardless of individual score

C. Signal Velocity Bonus:
When a member accumulates 3+ Tier-1 or Tier-2 signals within any 72-hour window (research sprint behavior): add 15-point bonus. This detects evaluation sprints where buyers consume everything before a vendor decision.

D. Recency Decay Function:
Define how scores depreciate without fresh signals:
- Full score: Days 0-14 post signal
- 80% of score: Days 15-30
- 50% of score: Days 31-60
- 25% of score: Days 61-90
- Score resets: 91+ days without new signal → member re-enters as cold

---

DELIVERABLE 3: CRM INTEGRATION & AUTOMATION ARCHITECTURE

Design the full data pipeline in 5 steps:

Step 1: Community Data Extraction
Specify for [Community Platform]:
- Which API endpoints or webhooks to use
- Native integrations that exist (e.g., Gainsight <> Salesforce native, Circle <> Zapier, Discourse API)
- Community-side custom fields to enable proper tracking (UTM source fields, company domain field, LinkedIn URL field)

Step 2: Score Calculation Engine
Recommend implementation approach for the company's tech stack:
- Simple (Zapier multi-step zap with scoring logic in conditional paths)
- Mid-complexity (Make.com scenario with running score stored in a Google Sheet or Airtable)
- Robust (Segment track calls → dbt scoring model → Salesforce sync via Segment Destination)

Step 3: CRM Field Configuration
Specify exact custom fields to create:

For HubSpot contacts OR Salesforce Leads/Contacts:
- CQL_Score (number, 0-100)
- CQL_Tier (dropdown: CQL-1 / CQL-2 / CQL-3 / Not Qualified)
- CQL_Last_Signal_Type (text: e.g., "Competitor comparison post")
- CQL_Last_Signal_Date (date)
- CQL_Trigger_Event_Text (long text: exact post text that triggered CQL threshold)
- CQL_Community_Username (text)
- CQL_Account_Amplification_Flag (checkbox: true/false)
- CQL_Source_Attribution (text: "Community-Sourced" vs. "Community-Influenced")

Step 4: SDR Alert Notification System
When a contact crosses CQL-1 threshold, trigger:
1. Slack DM to assigned SDR/AE with: contact name + company + ICP fit rating + CQL trigger event description + exact post text + recommended outreach approach + link to CRM record
2. CRM task created with due date (24 hours for CQL-1, 72 hours for CQL-2) and high priority flag
3. Enrollment in CQL-specific sales sequence in Outreach/Salesloft/HubSpot Sequences (separate from cold outbound sequences — different tone, different opener)

Step 5: Attribution Logging
How to track community as lead source in CRM:
- "Community-Sourced": community signal was the FIRST touch before any CRM record existed
- "Community-Influenced": prospect already in CRM and community signal accelerated pipeline
- Pipeline reporting: how to build the community pipeline report in HubSpot/Salesforce that shows both sourced and influenced values

---

DELIVERABLE 4: SALES OUTREACH PLAYBOOK BY CQL SIGNAL TYPE

For each of the top 5 most common CQL signal types, provide:
- Trigger definition (exact behavior that fires the alert)
- SDR/AE assignment logic (who gets this — by segment, territory, or ACV)
- Response timing SLA (hours from trigger to first touch)
- Outreach channel sequence (e.g., Email Day 1 → LinkedIn Day 2 → Phone Day 3 → Email Day 5 → LinkedIn Day 7 → Breakup email Day 10)
- Email template for first touch that references community context WITHOUT being explicit about surveillance ("I saw your post" is forbidden)
- The specific value asset to offer based on the signal type (technical doc, customer story, ROI calculator, competitive comparison)
- Expected meeting booking rate benchmark for this signal type

---

DELIVERABLE 5: COMMUNITY TRUST PROTECTION FRAMEWORK

The monetization paradox: communities that get over-harvested for pipeline see engagement drop 30-50% within 6 months, destroying the demand generation asset. Build the guardrails:

Rules of Engagement:
- What sales is NEVER allowed to do with community intelligence (explicit list of prohibited behaviors)
- How to train SDRs on "curiosity-led" vs. "surveillance-based" outreach
- Maximum outreach attempts per community member per quarter

Community Health Monitoring Dashboard:
- Leading indicators that CQL harvesting is damaging community health
- Alert thresholds that trigger a CQL program pause and community health review
- How to solicit community member feedback on experience with follow-up outreach

Member Privacy Policy:
- Community footer/FAQ language explaining your outreach philosophy
- Opt-out mechanism for members who don't want to receive sales outreach based on community activity
- How to honor opt-outs in your CQL automation

---

DELIVERABLE 6: 30-DAY ACTIVATION PLAN

Week 1 — Audit & Architecture
Day 1-3: Community data audit (what signals you can currently capture vs. what requires new instrumentation)
Day 4-5: CRM field configuration and sandbox testing
Day 6-7: Define initial CQL scoring model (can always refine after data collection)

Week 2 — Integration Build
Day 8-10: Build automation in Zapier/Make.com/Segment
Day 11-12: Test signal detection with 10 historical community posts
Day 13-14: QA CRM field population and alert formatting

Week 3 — Sales Readiness
Day 15-17: SDR/AE training session (30 minutes, live examples, show benchmark conversion rates)
Day 18-19: Build CQL-specific outreach sequences in sales engagement tool
Day 20-21: Dry run with 5 CQL test cases before going live

Week 4 — Launch & First Pipeline
Day 22-24: Go live with CQL monitoring, CQL-1 alerts only
Day 25-27: First week of live CQL activity — SDR daily standup to debrief quality
Day 28-30: First CQL-sourced opportunity created in CRM → celebrate and document the story

Acceptance criteria for each week to know you're on track. Include what "done" looks like for each milestone.

## Example Input/Output

**Example Company:** Fieldline — B2B SaaS field service management for HVAC, plumbing, and electrical contractors (Series B, $18M ARR, ACV $12,000, 90-day sales cycle)

**Community Platform:** Circle.so with 2,400 members (65% existing customers, 22% free trial users, 13% prospects/industry practitioners)

**Example CQL-1 Signal Detected:**

*Community member: Jamie Martinez, Operations Manager at Thornbury Mechanical (18 employees, HVAC contractor, not yet in CRM)*

*Post in "Feature Questions" category:* "Has anyone used the multi-location dispatch feature with 12+ technicians across 3 locations? We're trying to decide if we should migrate from ServiceTitan before our contract renews in 90 days. Specifically wondering how the mobile app handles offline sync when techs are in basements with no cell service."

**CQL Score Calculation:**
- "Evaluating us vs. competitor" signal (ServiceTitan comparison intent): +22 points
- Timeline urgency ("contract renews in 90 days"): +20 points
- Implementation scoping question (12+ technicians, 3 locations): +18 points
- High-intent category engagement (Feature Questions): +8 points
- ICP firmographic fit (HVAC contractor, 18 employees): +10 points
- **Total: 78 points → CQL-1 (Sales-Ready)**

**SDR Slack Alert Generated:**
🔥 CQL-1 | Jamie Martinez | Thornbury Mechanical | Score: 78/100
Trigger: Competitor evaluation + 90-day contract timeline
ICP Fit: ✅ HVAC contractor, 18 employees, matches mid-market ICP

Community Signal:
"Trying to decide if we should migrate from ServiceTitan before our
contract renews in 90 days. Wondering about offline sync in basements."

RECOMMENDED APPROACH: Share our "Fieldline vs. ServiceTitan: Offline
Sync Technical Comparison" doc. Offer to connect with a customer
of similar size who made the same switch.

DO NOT mention you saw this in the community.

Assigned to: Maria Chen (Mid-Market AE, HVAC vertical)
Task due: Within 24 hours | CRM: [link]

**First Outreach Email:**
Subject: Offline sync for multi-location HVAC dispatch — quick resource

Hi Jamie,

Saw you're evaluating field service options with a contract renewal
window coming up — wanted to get this in your hands before you finalize
your decision.

We put together a technical breakdown specifically on offline sync
reliability for basement/low-signal environments: [link]. Written by
our CTO after getting this question repeatedly from multi-location
HVAC teams.

Also happy to connect you with one of our customers who manages 14
technicians across 4 locations — he migrated from a competitor 18
months ago and has detailed notes on what the transition looked like.

Either way, the doc is yours.

[Signature]

**Outcome:** Jamie books discovery call 3 days after first email. Thornbury Mechanical closes 67 days later at $14,400 ACV. CRM attribution: Community-Sourced. Sales cycle: 24 days shorter than average (competitor evaluation + timeline urgency = accelerated decision).

---

## Success Metrics

**Leading Indicators (Weeks 1-4):**
- CQL signals detected per week: benchmark 10-25 per 1,000 MAM
- CQL-1 alert → SDR response rate: target 100% within 24-hour SLA
- CQL prospect-to-CRM match rate: aim for 65%+ match on member emails within 60 days of launch
- Alert quality score: SDR team rates alert context quality weekly (target: 4/5+)

**Pipeline Metrics (Months 2-6):**
- Community-sourced pipeline: $ value of opps where first CRM touch was a CQL signal
- CQL-1 → Discovery Call conversion rate: benchmark 25-35% (vs. 3-5% cold outbound)
- CQL-1 → Closed-Won rate: benchmark 15-25%
- Average ACV: community-sourced deals should run 10-20% higher than average (community members self-select as engaged buyers who know the product)
- Sales cycle length: CQL-1 deals should close 15-25% faster than non-community deals

**Community Health Guard Rails (Monthly):**
- Monthly Active Member (MAM) trend: alert if MAM drops 15%+ over any 30-day window after CQL launch
- New post creation rate: if original posts drop 20%+ month-over-month, pause CQL outreach and audit
- Community NPS: quarterly pulse survey of members; watch for themes around "sales pressure"
- Member opt-out rate from sales contact: if > 5% of CQL-contacted members opt out, recalibrate outreach tone

---

## Related Prompts
- [AI-Powered B2B SaaS Owned Community Performance Analytics & Revenue Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Owned-Community-Performance-Analytics-&-Revenue-Attribution-Intelligence-Engine.md) — Build the upstream community health dashboard and overall ROI measurement framework before instrumenting CQL scoring
- [Lead Scoring Model Optimization & Predictive Buying Signal Intelligence Engine](../Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md) — Integrate CQL scores into your master lead scoring model alongside MQL signals
- [AI-Powered B2B Community-Led Growth & Pipeline Revenue Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-B2B-Community-Led-Growth-&-Pipeline-Revenue-Intelligence-Engine.md) — Design the community-led growth program strategy before you instrument signal tracking
- [Signal-Based GTM Automation & Revenue Trigger Engine](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Signal-Based-GTM-Automation-&-Revenue-Trigger-Engine.md) — Expand CQL signals into a broader intent-signal GTM motion that includes product usage, job postings, and third-party intent data

---

## Integration Tips

**HubSpot:**
- Create all CQL custom properties under a "Community Intelligence" group in HubSpot for clean organization
- Build the CQL-1 workflow triggered when CQL_Score ≥ 70: create task for contact owner with 1-day deadline, send Slack alert via HubSpot's native Slack integration, enroll in "CQL-Hot" sequence (NOT your standard cold outbound sequence)
- Use HubSpot's Operations Hub (Professional+) for real-time data sync if your community platform supports webhooks — this eliminates the 15-minute Zapier polling delay for high-urgency CQL-1 situations
- Build a "Community Pipeline" report using custom report builder: filter deals where Lead Source = "Community-Sourced" and track by close date to show monthly community-attributed ARR

**Salesforce:**
- Add CQL fields to both Lead AND Contact objects — many community members will be unmatched Leads initially, promote to Contact when matched to an Account
- Use Salesforce Flow (not deprecated Process Builder) for CQL threshold automation — build a scheduled flow that recalculates scores nightly and a record-triggered flow that fires immediately when a new signal is logged
- Create a "Community Signals" custom object related to Lead/Contact to store individual signal event history (not just the aggregated score) — this gives your sales team the ability to see what specific posts triggered the CQL
- Use Salesforce High Velocity Sales (Sales Engagement) or integrate with Outreach/Salesloft for automated CQL sequence enrollment triggered via Flow

**Zapier / Make.com (No-Code Path):**
- Circle.so: Circle's native Zapier integration supports "New post in category" and "New comment" triggers — use multi-path Zaps to score by category and post type
- Discourse: Use Discourse's webhook + Zapier's Webhook trigger to capture post events in real time; route through Make.com for more complex conditional scoring logic
- Slack communities: Slack Event API → Make.com scenario with keyword scoring → update HubSpot/Salesforce contact score via API
- Score storage: For simple implementations, store running CQL scores in an Airtable base with one row per community member, update via Zapier, and sync to CRM daily

**Segment / CDP (Robust Path):**
- If you have Segment, this is the cleanest architecture: community events → Segment track() calls (e.g., `community_post_created` with properties: category, post_type, word_count, competitor_mention) → score calculation in your data warehouse (dbt model) → Salesforce sync via Segment's Salesforce Destination
- This approach enables joining community signals with product usage data (PQL signals) in the same scoring model — a CQL + PQL combined score is significantly more predictive than either alone

**Gainsight Community (Customer Communities):**
- Gainsight's native Salesforce integration makes CQL scoring for existing customers significantly easier — community engagement syncs directly to the Gainsight Customer 360
- For expansion revenue plays, route CQL signals to the CSM (not SDR) with a different playbook focused on EBR prep and expansion discovery calls

---

## Troubleshooting

**Problem:** SDRs are ignoring CQL-1 alerts or treating them exactly like cold outbound contacts
**Solution:** Alert context is everything. If the alert says only "Jamie Martinez — CQL Score: 78," SDRs will treat it like a list import. The alert must include: (1) the exact post text, (2) your interpretation of what buying stage this indicates, (3) the specific asset to send that adds genuine value based on the signal, and (4) what NOT to say. Run a 30-minute SDR enablement session with 3 real CQL conversion examples — show the specific email that booked the meeting and the 25-35% meeting rate vs. their 3-5% cold outbound rate. SDRs follow incentives: if CQL leads actually convert at 5x the rate of cold leads, they will prioritize them.

**Problem:** 75%+ of CQL prospects can't be matched to CRM records because you don't have their business email
**Solution:** This is the most common community monetization failure point. Fix the identity gap at the source: (1) Require business email verification at community signup — most platforms support email domain whitelisting. (2) For existing unmatched members, run a "Community Profile Completion" campaign: offer a community-exclusive resource (early access to your benchmark report, a template pack, a private AMA with your CPO) in exchange for completing their profile including company name and LinkedIn URL. (3) Use Apollo.io, ZoomInfo, or Clearbit to reverse-match community usernames against company email patterns when you have company name but not email. Target: 70%+ CRM match rate within 90 days.

**Problem:** Community engagement drops noticeably (posts down 25%, MAM declining) after CQL program launches
**Solution:** You've crossed a trust tripwire. Immediately audit the last 30 SDR outreach emails to CQL-flagged members — look for: emails that explicitly reference community posts ("I saw your post about ServiceTitan..."), follow-up cadences that feel automated/impersonal, or outreach that comes within hours of a post (feels like surveillance). Stop CQL-1 outreach for 2 weeks and implement: a 48-hour minimum delay between signal detection and outreach, a mandatory human review of every CQL-1 before the first email goes out, rewritten email templates that lead with genuine value rather than referencing community context, and a community footer that proactively addresses member privacy ("Our team reads the community to understand how to serve you better. We occasionally reach out when we think we can help — reply STOP to opt out."). Run a community NPS survey to understand sentiment directly.

---

## Version History
- v1.0: Initial creation (auto-generated)
