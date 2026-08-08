# AI-Powered B2B SaaS Feature Adoption Campaign Architecture & Product-Led Retention Intelligence Engine - Turn Every Product Release Into a Retention and Expansion Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** product marketing, feature adoption, retention marketing, in-app messaging, customer lifecycle, product-led growth, NRR, expansion revenue, churn prevention, B2B SaaS

## Overview
Builds a fully automated, data-driven system that identifies which customers haven't adopted which features, diagnoses *why* adoption is stalling, and orchestrates targeted multi-channel campaigns — in-app, email, CSM-led, and digital — to close adoption gaps. Use this when you're launching new features, have underperforming adoption rates in your existing base, or want to correlate feature depth with renewal and expansion outcomes to prove PMM's impact on NRR.

## Quick Copy-Paste Version

You are a Product Marketing expert specializing in feature adoption campaigns for B2B SaaS companies. Design a complete feature adoption campaign system that takes product usage data, identifies customer segments with adoption gaps, and deploys the right message in the right channel at the right time to drive measurable adoption lift.

COMPANY CONTEXT:
- Company: [e.g., "Claros — AI-powered contract management platform for legal and procurement teams"]
- Product overview: [e.g., "Core product = contract repository + e-signature. Key upsell features = AI risk analysis, automated approval workflows, vendor portal"]
- Feature being adopted: [e.g., "AI Risk Analysis — launched 90 days ago, available to all Enterprise tier customers"]
- Current adoption rate: [e.g., "18% of eligible customers have used it in the last 30 days"]
- Target adoption rate: [e.g., "60% in 90 days"]
- Customer success structure: [e.g., "12 CSMs covering 340 Enterprise accounts, high-touch for 80+ seat accounts"]
- Tech stack: [e.g., "Salesforce CRM, Gainsight CS platform, Iterable email, Pendo in-app messaging, Intercom for in-app chat"]

THREE ADOPTION BARRIERS TO SOLVE:
1. AWARENESS GAP — Customers don't know the feature exists or what it does
2. ACTIVATION GAP — Customers know it exists but haven't set it up or used it
3. HABIT GAP — Customers activated once but haven't built it into their workflow

OUTPUT REQUIRED:
1. ADOPTION SEGMENTATION MODEL: How to tier customers by adoption status and urgency (renewal timeline × usage gap × account health)
2. CHANNEL PLAYBOOK: Which message goes in which channel (in-app tooltip, email sequence, CSM outreach, webinar, in-product demo) for each barrier type
3. CAMPAIGN COPY: Full message templates for each barrier × channel combination
4. MEASUREMENT FRAMEWORK: How to track adoption lift, attribute it to campaigns, and correlate feature depth with renewal and expansion rates
5. CSM ENABLEMENT: What CSMs need to say and show — talk tracks, one-pagers, success stories — to drive adoption in their book of business
6. FEEDBACK LOOP: How to capture why customers aren't adopting and route those signals back to product and PMM

## Advanced Customizable Version

ROLE: You are a senior Product Marketing Manager with 12+ years driving feature adoption and retention marketing at B2B SaaS companies from Series B through public company stage. You have personally designed adoption campaign systems that lifted feature engagement by 40-80% and demonstrated statistically significant correlation between feature adoption depth and renewal rates — making PMM a measurable contributor to NRR. You understand that feature adoption is not a one-time email blast — it is a sustained campaign across in-app, email, digital, and human channels, personalized by customer segment, coordinated with Customer Success, and measured rigorously. You think in cohorts, activation milestones, and expansion signals, not open rates.

OBJECTIVE: Design a production-ready feature adoption campaign system that:
- Identifies every eligible customer account by adoption status (non-adopter, activated-not-habituated, power user) using product usage data
- Diagnoses the adoption barrier type for each segment (awareness, activation, habit) to deploy the right intervention
- Orchestrates multi-channel campaigns that feel personally relevant, not generic broadcast
- Enables CSMs to have high-quality adoption conversations without becoming product trainers
- Measures adoption lift by campaign type and correlates feature depth with renewal, expansion, and churn risk signals
- Runs autonomously for every future feature launch with minimal campaign setup overhead

---

COMPANY PROFILE:
- Company name & product: [name + one-sentence description of what the product does]
- Business model: [SaaS with tier breakdown — e.g., Starter / Growth / Enterprise, or seat-based, usage-based]
- Current ARR: [range — e.g., "$18M–$45M ARR"]
- Stage: [Series B / C / growth — key because it affects CS-to-account ratios and channel sophistication]
- GTM motion: [Enterprise AE + CSM-led / Mid-market self-serve with light CS / PLG with sales assist]
- Net Revenue Retention target: [current NRR vs. target]
- Average contract value: [e.g., "$28,000/year"]
- Renewal cycle: [quarterly / annual / multi-year]
- Customer count by tier: [e.g., "320 Enterprise, 1,200 Mid-market, 4,800 Starter"]

---

FEATURE PROFILE:
Feature being adopted:
- Feature name: [e.g., "AI Contract Risk Analyzer"]
- Launch date: [when it went live to current customers]
- Eligible customer tier(s): [which plan tiers can access this feature]
- What it does in one sentence: [user-facing benefit, not technical description]
- Who uses it (job title / persona): [e.g., "General Counsel, Contract Managers, Procurement Directors"]
- What the user must DO to activate: [e.g., "Upload 3+ contracts and run first risk scan"]
- What "habituated use" looks like: [e.g., "Running AI risk scan on every new contract before signing, minimum 4x per month"]
- Current adoption funnel:
  - % of eligible accounts with at least 1 usage event: [e.g., "31%"]
  - % of those who used it 2+ times in last 30 days: [e.g., "44% of activators"]
  - % of eligible accounts using it as core workflow (habituated): [e.g., "14%"]

---

ADOPTION SEGMENTATION MODEL:

Tier all eligible accounts into 4 segments:

SEGMENT A — NON-ADOPTERS AT RENEWAL RISK (highest urgency):
Definition: Zero usage of this feature AND renewal date within 90 days AND account health score ≤ 70
Estimated count: [X accounts]
Risk: Feature gap may become a reason to churn or downsize
Campaign priority: CSM-led + executive sponsor outreach
Goal: Get to "first use" in the next 30 days

SEGMENT B — NON-ADOPTERS WITH TIME (medium urgency):
Definition: Zero usage AND renewal date 90+ days out AND account health ≥ 70
Estimated count: [X accounts]
Risk: Accumulating adoption debt — every month of non-adoption increases churn probability
Campaign priority: Automated email sequence + in-app activation prompts
Goal: Drive first activation within 45 days

SEGMENT C — ACTIVATED BUT NOT HABITUATED (conversion target):
Definition: Used the feature 1-3 times total, no usage in the last 30 days
Estimated count: [X accounts]
Risk: Awareness isn't the issue — activation to habit is the gap
Campaign priority: Behavioral trigger emails + in-app milestone nudges + success story
Goal: Reach habituated use definition within 60 days

SEGMENT D — HABITUATED POWER USERS (expansion and advocacy target):
Definition: Using the feature at or above the habit threshold for 60+ days
Estimated count: [X accounts]
Goal: Convert to references, G2 reviewers, co-marketing partners; identify expansion signals (usage ceiling approaching tier limit)

---

ADOPTION BARRIER DIAGNOSIS:

For each non-adopter segment, diagnose the PRIMARY barrier before deploying any campaign:

BARRIER TYPE 1 — AWARENESS ("I didn't know this existed or was relevant to me"):
Signals: Never opened in-app tooltip about this feature, never clicked email about it, never mentioned in CSM call notes
Interventions: High-visibility in-app announcement, onboarding email resend to the right persona (not just the admin), webinar invite specifically for this feature, CSM add to next QBR agenda

BARRIER TYPE 2 — ACTIVATION ("I know it exists but haven't had time/reason to set it up"):
Signals: Clicked in-app tooltip OR opened email about it but never completed first use event
Interventions: Step-by-step guided activation checklist (in-app or email), low-friction demo ("Watch this 4-minute setup video"), time-boxed trial framing ("Takes 8 minutes to activate"), peer benchmark ("87% of accounts similar to yours have already activated")

BARRIER TYPE 3 — VALUE CLARITY ("I tried it but didn't see the value clearly enough to use it again"):
Signals: Had 1-2 usage events, then stopped; CSM notes mention "seemed complicated" or "not sure it applies to us"
Interventions: Role-specific ROI story (not generic, mapped to their use case), side-by-side comparison (what your team does today vs. with AI Risk Analysis), offer a 30-minute "value discovery" session with PMM or CS specialist

BARRIER TYPE 4 — HABIT FORMATION ("I saw value but it's not in my workflow yet"):
Signals: 3-6 usage events spread over 30+ days, inconsistent — used it for one contract type but not others
Interventions: Workflow integration guide (where exactly to add this step in existing contract review process), in-app workflow trigger ("You just uploaded a new contract — run AI Risk Analysis?"), peer comparison ("Teams like yours catch 2.4 high-risk clauses per contract on average")

---

CHANNEL PLAYBOOK BY BARRIER TYPE:

AWARENESS campaigns → CHANNEL MIX:
- Pendo/WalkMe/Appcues: Persistent in-app banner on homepage for 30 days
- Email: Persona-matched announcement from CMO or VP Product (not marketing team — authority sender)
- LinkedIn retargeting: Promoted posts showing the feature in action for existing customer job titles
- CSM talk track: Add to agenda for next check-in call — 3 minutes, led by CSM, focus on "did you know?"
- Webinar: Monthly "What's New" webinar where this feature is the hero for the first 45 days

ACTIVATION campaigns → CHANNEL MIX:
- In-app: Guided tour triggered by "first click" on the feature — 3-step walkthroughs, not 12-step
- Email sequence: 4-touch over 14 days: (1) "Your account is ready" setup invite + video, (2) "It takes 8 minutes" low-friction pitch, (3) "Here's what [Peer Company] found in their first scan" social proof, (4) "Want us to run your first scan for you?" high-touch offer
- Calendar link offer: CSMs offer a "15-minute setup session" for Segment A accounts
- In-product: Feature blocked by "Try it" module — surface it inside the contract upload flow, not as a separate menu item

HABIT FORMATION campaigns → CHANNEL MIX:
- Behavioral trigger email: Triggered when user hasn't used the feature in 21+ days — "You haven't run a risk scan in 3 weeks — here's why [Customer] makes it part of every contract review"
- In-app workflow nudge: Every time they upload a new contract — overlay prompt "Run AI Risk Analysis on this contract?"
- Monthly digest: "Your contract risk report" — showing what your account's AI scans found last month, even if only 2-3 contracts, to reinforce value
- Peer benchmark email: "Accounts your size run an average of 14 scans/month — you ran 2. Here's what you might be missing."
- Success story: Case study or 2-minute customer video showing habit formation journey ("At first we used it on big contracts only, now it's on everything")

POWER USER → EXPANSION AND ADVOCACY campaigns:
- G2 review request: Triggered at day 90 of habituated use — in-app prompt + email + CSM mention
- Reference program invite: CSM asks for reference call permission, PMM routes to relevant prospect requests
- Case study recruitment: PMM outreach to accounts with best usage data and measurable outcomes (e.g., "identified 3 high-risk clauses that avoided $2M in liability")
- Expansion signal: Alert AE when account's usage approaches 80% of tier limit — conversation starter: "You're using AI Risk Analysis at scale — ready to move to Enterprise?"

---

CAMPAIGN COPY TEMPLATES:

AWARENESS EMAIL — from VP Product, for Segment B Non-Adopters:

Subject: [Company] now has AI contract risk analysis — here's why your team should try it

"Hi [First Name],

Quick note from our product team: [Feature Name] has been live for [X] weeks, and I wanted to make sure your team hasn't missed it.

What it does in one sentence: [One-sentence user benefit, e.g., 'It scans every contract for high-risk clauses — data privacy, indemnification, IP ownership — and flags them before you sign.']

Why it matters for teams like yours: [Specific example — e.g., 'Legal teams at companies your size catch an average of 2-3 high-risk clauses per enterprise contract. The ones they miss cost an average of $180K in renegotiation or liability.']

It's available on your current plan. No setup fee, no IT request needed.

[CTA Button: See it in action — 4-minute walkthrough]

If you'd prefer, [CSM Name] can walk you through it on your next call.

[Signature: VP Product]"

---

ACTIVATION EMAIL SEQUENCE — Touch 1 of 4 (Day 0, for Segment B/C):

Subject: Your account is ready for AI Risk Analysis — takes 8 minutes to activate

"Hi [First Name],

[Feature Name] is already enabled on your [Tier] account — you just need to run your first scan.

Here's what you'll have in 8 minutes:
✓ Upload any contract you're currently reviewing
✓ AI scans for 47 risk clause categories (data privacy, IP, liability caps, non-compete, etc.)
✓ Get a risk report highlighting anything worth flagging before you sign

To start: [Button: Run your first scan →]

Or watch how [Peer Company in same industry] set it up: [Link to 2-minute customer video or screen recording]

Questions? Reply to this email or book 15 minutes with [CSM Name]: [Calendar link]

[Signature: PMM or CSM]"

---

HABIT FORMATION TRIGGER EMAIL — Behavioral, fires at day 21 of no usage (Segment C):

Subject: You haven't scanned a contract in 3 weeks — here's what others found

"Hi [First Name],

It looks like your team hasn't used AI Risk Analysis in the last 21 days.

We know getting a new tool into the workflow takes time. Here's what's worked for other [Legal/Procurement] teams at companies like [Account Company Name]:

→ [Customer Name] added a 'Run AI Scan' step to their standard contract review checklist. Now they run it on 100% of contracts before routing for signatures — took 1 week to become automatic.
→ They've flagged 23 high-risk clauses in the last 60 days. 4 went back to vendors for renegotiation.

Want to make it part of your workflow?
[Button: Resume — run your next scan] [Link to 10-minute 'workflow integration' guide]

Or reply and I'll set up a 20-minute session to get it into your team's process: [CSM Calendar link]

[Signature]"

---

CSM TALK TRACK — Adoption check-in, 3-minute version for quarterly review calls:

Opening (30 seconds):
"Before we dive into the QBR agenda, I wanted to spend 3 minutes on AI Risk Analysis — it's the feature our Enterprise customers are getting the most value from right now, and I want to make sure your team is set up to get that same value.

Quick question: has your team had a chance to run any scans yet?"

If NO:
"Totally fine — we see this a lot in the first 90 days. Can I show you something in 2 minutes that usually gets teams off the starting line?" [Screen share: run a live scan on a sample contract]

If YES (1-2 times):
"That's a great start. What contract did you run it on? [...] What would make you want to do that on every contract, not just the occasional one?" [Diagnose the barrier — value clarity or habit]

Closing CTA (30 seconds):
"I'm going to send you [link to the workflow integration guide] after this call. The teams seeing the best results have added it as step 3 in their contract routing checklist — takes 8 minutes to set up. Want me to put a 15-minute 'make it a habit' session on the calendar?"

---

MEASUREMENT FRAMEWORK:

Leading indicators (measure weekly):
- % of eligible accounts in each adoption segment (Segments A-D)
- Campaign engagement by channel: email open rate, click rate, in-app tooltip interaction rate
- Activation events triggered per week (first-ever feature usage by account)
- Activation-to-habit conversion rate (what % of first-time users return within 14 days)

Adoption funnel metrics (measure monthly):
- Overall feature adoption rate by eligible tier: target [X%]
- Adoption by CSM book of business: which CSMs are driving the most activation from their accounts?
- Adoption by cohort: accounts who activated in month 1 vs. month 2 vs. month 3 — how does adoption hold over time?
- CSM outreach conversion: % of CSM adoption conversations that resulted in first activation within 30 days

Revenue impact metrics (measure quarterly):
- Renewal rate: habituated feature users vs. non-adopters — is there a statistically significant difference?
- NRR: do accounts with 3+ features adopted at habit level expand at higher rates?
- Churn rate: % of churned accounts that were non-adopters of this feature in their final 90 days
- Expansion pipeline: # of expansion opportunities sourced from power user adoption signals

---

AUTOMATION ARCHITECTURE:

Gainsight / ChurnZero setup:
- Timeline event: Auto-log "Feature Adoption Campaign — Segment X assigned" to every eligible account when segmentation runs
- Success Plans: Auto-create "Feature Adoption" success plan task for CSMs with Segment A accounts
- Cockpit alerts: Daily digest for CSMs showing Segment A accounts with no adoption activity in last 14 days
- Journey Orchestration: Automated email sequences deployed to Segment B/C accounts based on usage events (triggered by Gainsight → Iterable API)

Pendo / Appcues / WalkMe setup:
- In-app segments: Create behavioral segments matching Segment A-D definitions using product event data
- Guide logic:
  → Segment A: Persistent banner on main dashboard for 30 days
  → Segment B: Tooltip on feature menu item with "Setup in 8 minutes" CTA
  → Segment C: Behavioral trigger — when user hasn't triggered a feature event in 21 days, show a "Resume" prompt the next time they log in
  → Segment D: NPS survey after 90 days of habituated use + G2 review request

Salesforce / HubSpot setup:
- Custom fields on Account object: "Feature Adoption Segment", "Last Feature Usage Date", "Feature Adoption Score (0-100)", "Habituated Since Date"
- Workflow trigger: When "Feature Adoption Score" changes from <30 to >70 → create Task for AE: "[Account] just hit feature adoption threshold — check for expansion opportunity"
- Report: "Feature Adoption vs. Renewal Outcomes" — correlation report shared with CS leadership monthly

---

OUTPUT STRUCTURE REQUIRED:

1. ADOPTION AUDIT: Pull product usage data to populate Segments A-D, with exact count by segment and account list per CSM for immediate actioning

2. 90-DAY CAMPAIGN CALENDAR: Week-by-week sequence of in-app, email, CSM, and webinar touchpoints for each segment — with trigger logic and exit criteria (what removes a customer from the campaign once they reach adoption threshold)

3. FULL CAMPAIGN COPY LIBRARY: All email touches (subject + body), in-app message copy (tooltip, banner, modal), and CSM talk track scripts — organized by barrier type and channel

4. CSM ENABLEMENT PACKAGE: One-page "Feature Adoption Conversation Guide" per feature, with: what it does (in customer language), top 3 objections + responses, activation ask, and 3 most compelling customer outcomes to reference

5. MEASUREMENT DASHBOARD SPEC: Which metrics to track, in which tool, at which frequency — plus how to present "feature adoption ROI" at monthly revenue review, including the NRR correlation analysis

6. PRODUCT FEEDBACK CAPTURE SYSTEM: How to collect, tag, and route "non-adoption reasons" (too complex, doesn't apply to us, no time, missing functionality) back to product and PMM for roadmap prioritization

## Example Input/Output

**Example Company: Claros (AI Contract Management Platform)**

**Input provided:**
- Company: Claros — AI contract management for mid-market and enterprise legal and procurement teams
- Feature: AI Contract Risk Analyzer — launched 11 weeks ago, available to all Enterprise tier (320 accounts)
- Current adoption: 21% have activated (68 accounts), 11% habituated (35 accounts)
- Target: 55% habituated within 90 days
- CS structure: 8 CSMs covering 320 Enterprise accounts (avg. 40 accounts/CSM), high-touch for accounts >100 seats
- Stack: Salesforce, Gainsight, Iterable, Pendo
- Renewal timing: 41 accounts renew in next 90 days

**Segmentation output (actual numbers):**

| Segment | Definition | Count | Priority |
|---------|-----------|-------|----------|
| A — Non-adopter, renewal at risk | 0 usage + renewal <90 days + health ≤70 | 14 accounts | Immediate CSM action |
| B — Non-adopter, time available | 0 usage + renewal 90+ days | 238 accounts | Automated email + in-app |
| C — Activated, not habituated | 1-3 uses, no usage in 30 days | 33 accounts | Behavioral trigger campaign |
| D — Power users | Habituated 60+ days | 35 accounts | Reference + expansion |

**Sample campaign output — Segment A, CSM escalation alert:**

*Gainsight cockpit alert sent to CSM Julia Reyes at 8:00am Monday:*

"🔴 ADOPTION RISK — 3 accounts in your book are non-adopters of AI Risk Analyzer with renewal in <90 days:

• Nexbridge Legal (renewal Feb 14, health score 62) — 0 usage events. Primary contact: Sarah Torres (Director of Legal Ops). Last CSM call: 45 days ago.
• Tarvex Procurement (renewal Mar 2, health score 58) — 0 usage events. Primary contact: Marcus Hall (VP Procurement). Has opened 2 emails about the feature, never clicked.
• Allworth Partners (renewal Feb 28, health score 74) — 0 usage events. Primary contact: Diana Kim (General Counsel). Has a CSM call scheduled this Friday.

Recommended action: Schedule outreach to all 3 this week. Feature adoption brief + one-page talking points attached. Calendar link to book a 'setup session' embedded in Gainsight task."

*PMM one-page enablement brief provided to Julia for all three calls:*

"AI Risk Analyzer — CSM Quick Reference
What it is (in their language): Scans any contract for 47 high-risk clause categories and surfaces the ones worth negotiating before you sign.
Who uses it: Legal Ops, General Counsel, VP Procurement, Contract Managers.
What changed for customers who use it: Average team catches 2.8 risky clauses per enterprise contract they would have previously missed. 3 customers have specific stories they'll share on reference calls.
Activation ask: 'Let me show you one scan on a real contract from your account right now — takes 8 minutes.' [Share screen, use sample contract from their industry]
Top objection — 'We don't have time to train the team': Response: 'It doesn't require training — it's one button during your normal contract review. I can show you how three teams have added it to their existing checklist without any change management.'"

*Outcome (simulated, based on comparable deployments):*
- Nexbridge: CSM call booked Day 3. Live demo during call → first activation event same day. Habituated by Day 47. Renewal secured.
- Tarvex: Activation email sequence re-sent with personalized subject using Marcus's email open history. Activated on Touch 2 (Day 7). Still habituating.
- Allworth: Diana raised it on the Friday call ("I saw your email"). Ran first scan during call. Reference-willing by Day 60. Expanded to 40 additional seats at renewal.

## Success Metrics

**Month 1 (campaign launch validation):**
- All Segment A accounts contacted by CSM within 5 business days of segmentation
- Segment B email sequence deployed: target 35%+ open rate, 8%+ click rate
- Activation events per week: trending toward 8-12 new activations/week from campaign (vs. 2-3 organic/week before campaign)

**Month 2 (adoption acceleration):**
- Segment A: 70%+ of non-adopters with renewal <90 days have at least 1 activation event
- Segment C (activated-not-habituated): 40%+ reached habituated threshold
- Segment B: 25%+ activated from automated campaign (without CSM assist)

**Month 3 (business impact):**
- Overall habituated adoption rate: target ≥55% of eligible accounts
- Renewal rate for habituated adopters: ≥15 percentage points higher than non-adopters
- Churn events where non-adoption was a cited reason: target ≤2 (vs. baseline of ≥5 before campaign)

**Quarterly PMM scorecard metric:**
- Feature adoption lift attributed to PMM campaign (baseline: 2-3 organic activations/week → campaign: 8-12/week): report as "PMM-driven adoption events"
- ARR retained in Segment A accounts: attribute to feature adoption campaign in pipeline reporting

## Related Prompts

- [AI-Powered B2B SaaS New Customer Onboarding Marketing Automation](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-New-Customer-Onboarding-Marketing-Automation-&-First-90-Days-Revenue-Acceleration-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Product Usage Signal-Triggered Customer Marketing Orchestration](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Product-Usage-Signal-Triggered-Customer-Marketing-Orchestration-&-Lifecycle-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Customer Marketing Expansion Revenue Campaign Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Customer-Marketing-Expansion-Revenue-Campaign-Architecture-&-Cross-Sell-Upsell-Pipeline-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Continuous Product Launch Velocity](../../02_Product-Marketing/Product-Launch/AI-Powered-B2B-SaaS-Continuous-Product-Launch-Velocity-&-High-Cadence-Release-Marketing-Architecture-Revenue-Intelligence-Engine.md)

## Integration Tips

**Gainsight:**
- Build a dedicated "Feature Adoption" Journey in Gainsight Journey Orchestration — trigger based on usage event absence (product event data from your data warehouse via Gainsight data ingestion) — this eliminates the need for manual CSM monitoring
- Use Gainsight's "CTA (Call to Action)" framework to auto-create adoption tasks on CSM cockpits: one CTA per Segment A account, with due date, priority, and the PMM one-pager attached as a Gainsaid article
- Build a Scorecard metric: "Feature Adoption Depth" (count of habituated features per account) as a component of overall health score — accounts with 3+ habituated features should score significantly higher, which changes CS prioritization organically

**Pendo:**
- Use Pendo's Paths feature to visualize the adoption funnel: where are users dropping between "feature page load" and "first successful result"? This is your activation friction diagnosis
- Build Segment-specific in-app Guides: Segment B gets a persistent banner, Segment C gets a behavioral "resume" prompt, Segment D gets an NPS survey at 90 days — all using the same feature event data as your email segmentation, keeping channels synchronized
- Use Pendo's NPS response data to enrich your CSM cockpit: accounts with 9-10 NPS AND habituated feature use → flag for PMM as reference/case study candidates

**Salesforce + Iterable:**
- Push product event data to Salesforce via your data warehouse or Segment CDP: "Feature_Last_Used_Date" and "Feature_Usage_Count_30d" as custom fields on the Account object
- Build Iterable campaigns triggered by Salesforce field values: when "Feature_Last_Used_Date" hasn't updated in 21 days → enroll in Segment C habit-formation campaign
- Use Iterable's AI Send Time Optimization to send adoption emails at the time each contact historically opens — meaningfully outperforms fixed send times for this type of behavioral campaign

**HubSpot:**
- Use HubSpot's Custom Objects to create a "Feature Adoption Event" object that tracks: Feature Name, Account, Activation Date, Habituated Date, Segment at Campaign Start, Campaign Source — this gives you the attribution data to prove PMM's contribution to retention
- Workflow: When "Feature Habituated Date" is set → update Account property "Features Habituated Count" → when that count reaches 3 → notify AE via task: "[Account] reached 3-feature adoption — expansion conversation now"

**Slack (for CSM teams):**
- Create a #feature-adoption-pulse channel with weekly automated digest: "This week's activation leaderboard — 12 accounts activated AI Risk Analyzer. Top CSMs by book: [Name] — 4 activations, [Name] — 3 activations."
- Alert format for Segment A escalations: 🔴 [Account Name] | Renewal: [Date] | Feature usage: 0 | Health: [Score] | CSM: @[Name] | Action needed by: [Date + 5 days]

## Troubleshooting

**Problem: Product usage data is incomplete or delayed — can't reliably segment accounts into Segment A-D**
Solution: Start with what you have. Even if product event data is only 70% reliable, use it with a 30-day lag window (treat accounts as non-adopters unless you have confirmed events). Simultaneously, have CSMs do a manual adoption check on all Segment A accounts (renewal <90 days) in their next sync call — human confirmation overrides the data gap. Then prioritize getting reliable data piped to your CS platform as a RevOps project, because this system's ROI grows directly with data quality.

**Problem: CSMs aren't executing on the adoption tasks the system creates — adoption campaign is running but human touchpoints aren't happening**
Solution: This is a CSM incentive and process problem, not a campaign problem. Two fixes: (1) Add "Feature Adoption Rate in Book of Business" as a metric in CSM QBR scorecards and CS leadership reviews — behavioral adoption follows measurement. (2) Reduce friction: the Gainsight CTA should include a one-click "Send adoption email to contact" action that fires the Iterable sequence without the CSM writing anything, so the path of least resistance IS doing the right thing.

**Problem: Adoption lift isn't translating to renewal rate improvement — stakeholders questioning the business case for PMM-led adoption campaigns**
Solution: The correlation analysis takes time — run it at 6-month and 12-month cohorts, not 90 days. In the interim, present leading indicators: "Accounts we reached adoption threshold with have an NRR 12 points higher in the following quarter" is a story you can tell with 60-90 days of data. Also, ensure you're capturing qualitative evidence: CSM call notes where adoption specifically came up as a renewal reason, win/loss data where feature depth was cited, and customer quotes from habituated users about workflow integration — these build the narrative before the quantitative analysis matures.

## Version History
- v1.0: Initial creation (auto-generated)
