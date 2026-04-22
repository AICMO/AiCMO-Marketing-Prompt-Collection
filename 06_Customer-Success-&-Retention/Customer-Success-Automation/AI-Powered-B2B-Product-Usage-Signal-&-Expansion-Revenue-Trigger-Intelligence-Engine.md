# AI-Powered B2B Product Usage Signal & Expansion Revenue Trigger Intelligence Engine - Automated Product-Led Expansion Campaign System

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** product-led-expansion, usage-signals, expansion-revenue, nrr, plg, saas, b2b, product-analytics, automation, upsell, retention

## Overview
Transforms raw product telemetry and usage data into automated, personalized expansion revenue campaigns by detecting in-product signals that indicate upgrade readiness, whitespace, and cross-sell timing — before a sales rep ever gets involved. Use it when you want to build a systematic product-led expansion (PLX) motion that converts product engagement into net revenue retention without relying solely on CSM intuition.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue strategist specializing in product-led expansion. Build a complete automated expansion revenue trigger system for the following company.

COMPANY CONTEXT:
- Product: [What your SaaS does — 1-2 sentences]
- Current packaging/tiers: [Free/Starter/Pro/Enterprise or equivalent]
- Core expansion lever: [Seats / usage/consumption / feature tiers / modules]
- Average expansion ACV: [$ amount when an account upgrades]
- Product analytics tool: [Amplitude / Mixpanel / Pendo / Heap / custom]
- CRM: [HubSpot / Salesforce / etc.]
- Marketing automation: [Marketo / HubSpot / Customer.io / Braze / etc.]
- Current NRR: [% — or "unknown"]

Design a complete product-led expansion intelligence system with:

1. **Expansion Signal Library**: Define 12 specific in-product behavioral signals that indicate an account is ready to expand (not just healthy — specifically expansion-ready). For each signal, specify the exact metric, threshold, and what expansion action it should trigger.

2. **Segment Expansion Profiles**: Create 4 distinct expansion-ready account profiles based on usage pattern combinations — the "Limit Hitter," the "Power User Cluster," the "Feature Boundary Crosser," and the "Viral Grower." Define what product data defines each profile and what expansion offer is most relevant.

3. **Automated Campaign Triggers**: Design 8 automated campaign triggers — the exact if/then logic that fires a specific campaign when a usage signal threshold is crossed. Each trigger should specify: the product event or metric, the threshold value, the campaign type (in-app, email, CSM task, or SDR alert), the specific message/offer, and the timing/cadence.

4. **Expansion Campaign Templates**: Write 3 complete email templates — one for "usage limit approaching" (upgrade prompt), one for "feature adjacency" (cross-sell), and one for "seat expansion" (new user activation → account growth). Each template must reference real product usage data to feel personalized, not mass.

5. **Revenue Attribution Model**: Design the logic for attributing expansion revenue to product-led signals vs. CSM-led vs. marketing-led touches — so you know which expansion motion is working and can invest accordingly.

Output as a ready-to-implement playbook with specific metric names, threshold values (use realistic numbers), and tool-specific configuration notes.

## Advanced Customizable Version

ROLE: You are a VP of Marketing and Growth at a B2B SaaS company with 12+ years of experience building product-led expansion (PLX) motions that drove NRR from 105% to 135%+. You have architected expansion programs at companies with $10M–$200M ARR and understand the intersection of product analytics, CRM automation, and customer success. You know that the best expansion signal is invisible to the customer — they don't know they're being scored — but the campaign they receive feels perfectly timed and personally relevant.

OBJECTIVE: Build a fully automated, AI-executable Product Usage Signal & Expansion Revenue Trigger Intelligence System that identifies expansion-ready accounts from product telemetry, segments them into the right expansion motion, and fires personalized campaigns that convert product engagement into pipeline and closed revenue — with minimal CSM intervention.

INPUTS — Complete all fields for a precise output:

PRODUCT & BUSINESS PROFILE:
- Product name and one-line description: ___
- Core product category (analytics / collaboration / security / CRM / data / dev tools / other): ___
- Primary value metric (what customers pay for — seats / API calls / data volume / projects / etc.): ___
- Packaging model: [Seat-based / Consumption / Feature-tiered / Module-based / Hybrid]: ___
- Typical upgrade path (Starter → Pro → Enterprise, or equivalent): ___
- Average expansion deal size ($): ___
- Time from account creation to first expansion opportunity (months): ___
- Current NRR (%): ___
- Target NRR (%): ___
- Primary expansion blocker (customers don't know about features / seats not provisioned / champion not empowered to buy / IT procurement required / budget cycles): ___

PRODUCT DATA INFRASTRUCTURE:
- Product analytics platform (Amplitude / Mixpanel / Pendo / Heap / Segment / custom): ___
- Event tracking maturity (Basic pageviews only / Key feature events / Full funnel tracked / Warehouse-grade): ___
- CRM: ___
- Customer data platform / reverse ETL (Segment / Census / Hightouch / None): ___
- Marketing automation: ___
- CS platform (Gainsight / ChurnZero / Planhat / HubSpot / None): ___
- In-app messaging tool (Pendo / Appcues / Intercom / None): ___
- Data warehouse (Snowflake / BigQuery / Redshift / None): ___

EXPANSION MOTION CONTEXT:
- CS motion (High-touch / Digital-led / Hybrid): ___
- Sales-assist threshold (at what deal size does a sales rep get involved in expansion): ___
- Self-serve upgrade available (Y/N): ___
- Expansion primarily marketing-led / CS-led / sales-led currently: ___
- Biggest untapped expansion segment (SMB self-serve / MM digital / enterprise multi-product): ___

DELIVERABLES:

### 1. Expansion Signal Library — The 15 Behavioral Indicators of Upgrade Readiness

For each signal, output in this structured format:

| Signal Name | Product Event / Metric | Threshold That Indicates Expansion Readiness | Expansion Type Triggered | Revenue Potential | Priority |
|---|---|---|---|---|---|

Organize signals across five categories:

**Category A: Limit & Ceiling Signals (highest conversion rate — customer is hitting a wall)**
- Usage percentage of current plan limit (e.g., >80% of seat license used, >75% of API quota consumed, storage at 85% of plan cap)
- Feature blocks encountered (# of times a locked feature was clicked or "upgrade required" modal was shown in the last 30 days)
- Export/download ceiling hits (# of times a data export was blocked by plan limits)
- Workspace or project count approaching plan maximum

**Category B: Power User Concentration Signals (seed-and-spread expansion)**
- Power user ratio: >30% of licensed seats completing core workflow ≥5x/week (indicates team stickiness that can expand to adjacent teams)
- New user invitation rate: ≥3 new user invites sent by existing licensed users in last 14 days (organic virality signal)
- Cross-team usage: Users from 2+ different departments/teams are now active in a single account (multi-team adoption = departmental expansion opportunity)
- API key creation by non-admin users (signals developer/technical team adoption that often leads to enterprise expansion)

**Category C: Feature Adjacency Signals (cross-sell readiness)**
- Frequent navigation to premium/locked feature areas without clicking upgrade (intent without friction)
- Integration marketplace browsing: Account viewed ≥3 integrations for a specific product category in last 30 days (signals need expansion into adjacent use case)
- Help docs consumption for features not in current plan (indicates researching capabilities they want but don't have)

**Category D: Value Realization & ROI Signals (confidence-based expansion)**
- Core workflow completions hitting a milestone (e.g., 500th report generated, 1,000th task completed, 10,000th API calls processed — signals high ROI realization)
- Time-in-app per session increasing trend (users spending more time = product is becoming more central to workflow)
- Mobile app adoption alongside desktop (multi-surface adoption = deeper product integration into daily work)

**Category E: Relationship & Intent Signals (human-layer expansion)**
- Economic buyer (admin/billing contact) logged in within last 14 days without CS prompting (signals self-directed evaluation)
- Pricing page visits by admin or billing contact (highest intent signal — track via Clearbit Reveal or reverse IP if anonymous)
- Support ticket requesting a feature only available in a higher tier (buying-intent signal disguised as support)

---

### 2. Expansion-Ready Account Profiles — The Four Archetypes

**Profile 1: The Limit Hitter**

Definition: Account is actively constrained by their current plan — hitting seat, usage, storage, or feature limits at least 3x in the last 30 days.

Product signals that define this profile:
- >80% of any plan resource consumed
- Feature block modal shown ≥3x in 30 days
- At least 1 failed action due to plan limits (export blocked, invite rejected, project creation failed)

Expansion motion: Immediate, proactive upgrade offer. This is the highest-converting expansion archetype because the customer has self-identified the need — they just haven't been given the right framing or path to upgrade.

Recommended offer: Plan upgrade with specific resource increase ("Add 10 seats and get [Feature X] included — upgrade takes 60 seconds")
Conversion benchmark: 18–35% of Limit Hitters convert within 14 days of a targeted campaign
Priority: URGENT — campaign fires within 24 hours of 3rd limit hit

---

**Profile 2: The Power User Cluster**

Definition: A subset of users in this account have become highly engaged power users of core features, but licensed seat count hasn't grown proportionally. The company has more potential users who would benefit from the product than are currently provisioned.

Product signals that define this profile:
- ≥4 power users (completing core workflow ≥5x/week) on ≤15 total licensed seats
- New user invite attempts blocked in last 30 days (tried to add colleagues, couldn't)
- 2+ departments active (HR and Finance both using, but only Engineering bought seats)
- DAU/MAU ratio >60% for active licensed users (high engagement = strong internal advocacy)

Expansion motion: Seat expansion through champion enablement. The internal champion is your best sales rep — give them the business case, the ROI data, and the internal talking points to sell the expansion to their manager/procurement.

Recommended offer: "Your team loves [Product] — here's how to bring in your whole [Department]" + custom ROI summary showing value delivered per active user × projected value if all potential users onboard
Conversion benchmark: 12–22% within 30 days; 28–40% within 90 days with multi-touch nurture
Priority: HIGH — campaign fires within 72 hours of profile detection; CSM task created for accounts >$10K ACV

---

**Profile 3: The Feature Boundary Crosser**

Definition: Account is actively using Product A but their usage patterns show clear interest in, and readiness for, Product B or an adjacent feature tier — they've been navigating to premium areas, reading docs about locked capabilities, or their use case has expanded beyond the original purchase scope.

Product signals that define this profile:
- Locked feature area visited ≥5 times in last 30 days without clicking "Upgrade"
- Help center articles read for features not in current plan: ≥3 articles in 30 days
- Integration browsing: Viewed ≥2 integrations from a consistent category (e.g., 3 CRM integrations = need CRM integration feature tier)
- Support ticket asking "Can [Product] do X?" where X is a premium feature

Expansion motion: Educational + low-friction trial. Feature Boundary Crossers often don't know the upgrade path or fear the cost/process. The goal is to make the premium feature feel attainable, not aspirational.

Recommended offer: "You've been exploring [Feature X] — here's a 14-day free trial" or "Add [Module] to your plan for $[amount]/month" with a 1-click activation if self-serve is available
Conversion benchmark: 8–16% within 21 days of trial activation; trial-to-paid rate for feature trials typically 25–45%
Priority: MEDIUM — campaign fires within 7 days of 5th locked feature visit; no CSM needed for SMB, CSM task for MM/Enterprise

---

**Profile 4: The Viral Grower**

Definition: Account is organically spreading the product internally or through referrals — sending invites, sharing public outputs, or using features that increase product virality. This account is a compound growth opportunity.

Product signals that define this profile:
- ≥5 external sharing events (shared reports, exported and linked, invited external collaborators) in last 30 days
- New user join rate accelerating: ≥3 new users added per month for 2+ consecutive months
- User invitations sent to email domains NOT in the current account (potential new customer referral)
- Account has invited users from a company in your ICP list (partner-referral trigger)

Expansion motion: Dual-track — (1) accelerate internal expansion with a "team plan" upgrade that adds value at scale (bulk seats, admin controls, SSO), AND (2) activate referral/partner program to capture the external sharing behavior.

Recommended offer: "Your team is growing fast in [Product] — here's an offer built for teams your size" + referral incentive for the new-company invites
Conversion benchmark: 15–28% for team plan upgrade within 45 days; referred accounts convert at 2.3x the rate of outbound-acquired accounts
Priority: HIGH — CSM task for all accounts showing Viral Grower profile; marketing automation for SMB, CSM-led for MM/Enterprise

---

### 3. Automated Campaign Trigger Logic — 8 Precision Triggers

**Trigger 1: Limit Approach Warning (T-minus 20% from cap)**

IF: (seats_used / seats_licensed) >= 0.80
OR: (api_calls_30d / monthly_api_quota) >= 0.75
OR: (storage_used_gb / storage_quota_gb) >= 0.85
AND: account_tier NOT IN ('Enterprise', 'Custom')

THEN:
- Fire: Automated email to account admin (billing contact)
- Campaign: "You're approaching your [Resource] limit"
- Timing: Immediately on threshold cross; no more than 1x per 14 days
- CTA: One-click upgrade link (if self-serve) OR "Talk to us about your options" (if sales-assist required)
- Channel: In-app banner + email
- Copy angle: Proactive, helpful — "We noticed your team is making great use of [Product]" — not fear-based

Follow-up sequence:
- Day 0: Limit warning (email + in-app)
- Day 3 (if no action): Feature preview email showing what they unlock at next tier
- Day 7 (if no action): CSM task for MM/Enterprise accounts (ACV >$5K); SDR task for high-velocity SMB

---

**Trigger 2: Limit Exceeded — Urgent Upgrade**

IF: (any_resource_usage / resource_quota) >= 1.00
AND: user attempted action was blocked in last 7 days

THEN:
- Fire: Real-time in-app modal + immediate email (within 15 minutes of block event)
- Campaign: "Your team ran into a limit — here's how to keep going"
- CTA: Upgrade now (self-serve) OR "Get unblocked in 24 hours — talk to us"
- Timing: Immediate; no wait
- Priority: HIGHEST — this is a buying-intent signal at peak urgency
- For Enterprise accounts: SDR/AE alert fired simultaneously with "account is blocked — warm call opportunity"

---

**Trigger 3: Power User Cluster Detected**

IF: (power_users_count / licensed_seats) >= 0.30
AND: power_users_count >= 4
AND: days_since_last_expansion_campaign >= 60

THEN:
- Fire: Personalized email to account champion (highest-usage non-admin contact)
- Campaign: "Your team is making serious use of [Product] — here's what's possible at scale"
- Include: Personalized usage stats ("Your team has completed X [core workflows] this month — top 12% of [Product] teams your size")
- CTA: "See your team's full impact" (usage report link) + "Learn about team plans"
- Timing: Fires on day 1 of meeting threshold; CSM review for accounts >$8K ACV

---

**Trigger 4: New User Invite Surge**

IF: new_user_invitations_sent >= 3 in last 14 days
AND: account_tier IN ('Starter', 'Pro')

THEN:
- Fire: Email to account admin within 24 hours
- Campaign: "Your team is growing — here's a plan that grows with you"
- Include: Current seat count, # of invites sent, # accepted, seats remaining
- CTA: "Add [X] seats now" (pre-filled with recommended seat count = current + invited)
- Timing: Day 1 fire, Day 5 follow-up if no upgrade

---

**Trigger 5: Premium Feature Exploration (5th Visit)**

IF: locked_feature_views_30d >= 5 for a specific feature/feature category
AND: upgrade_modal_dismissed_without_clicking >= 2 times

THEN:
- Fire: In-app tooltip or Pendo guide on the locked feature page + email within 24 hours
- Campaign: "We noticed you've been exploring [Feature Name] — want to try it free for 14 days?"
- CTA: Activate 14-day trial (no credit card if self-serve)
- Timing: Fires on 5th locked feature visit; email sends next business day
- Note: Do NOT fire this campaign if account is in active sales cycle (check CRM opportunity stage)

---

**Trigger 6: Cross-Team Usage Detected**

IF: active_user_departments >= 2 (detected via email domain patterns or Clearbit enrichment matching org structure)
AND: licensed_seats < 20
AND: account_tier NOT IN ('Enterprise')

THEN:
- Fire: Email to account admin + champion
- Campaign: "It looks like [Product] has spread to your [Department 2] team — here's how to make it official"
- Include: Usage by team/department breakdown (if available from product analytics)
- CTA: "Get a quote for an enterprise plan" or "Add a team license for [Department]"
- Timing: Fires 3 days after second department detected (allow organic adoption to settle)

---

**Trigger 7: Core Workflow Milestone Reached**

IF: lifetime_core_workflow_completions crosses milestone thresholds: 100 / 500 / 1,000 / 5,000 / 10,000

THEN:
- Fire: Milestone celebration email (not a sales email — relationship email)
- Campaign: "[Company] just completed their [#]th [core workflow] in [Product]"
- Include: What that milestone represents in business value (e.g., "That's approximately X hours saved" or "X reports automated")
- CTA: Soft expansion plant — "See what else [Product] can do for your team" with link to feature tour
- For 1,000+ milestone accounts: CSM task to send personalized video (Loom) from CSM
- Timing: Fires immediately on milestone; 1x per milestone tier, not recurring

---

**Trigger 8: Economic Buyer Re-Engagement**

IF: account_admin or billing_contact logged in AND has not logged in for >30 days
AND: session lasted >3 minutes (not accidental)
AND: pages visited include pricing, settings, or billing pages

THEN:
- Fire: CSM task within 24 hours (not automated email — this is too high-intent for automation)
- Task: "[Admin Name] at [Company] just visited pricing/billing after 30+ days inactive — warm call/email opportunity"
- Include: Account health summary, current plan, expansion recommendation, and any recent product usage highlights
- Campaign type: CSM-led outreach with personalized expansion conversation
- For self-serve accounts <$2K ACV: Automated email from CSM mailbox alias: "I noticed you might be evaluating your plan — can I share some context?"

---

### 4. Expansion Campaign Email Templates

**Template A: Limit Approach Warning Email**

Subject line options (A/B test):
- Option A: "Your [Product] team is growing — a heads-up on your [resource] usage"
- Option B: "[Company]: You're at 82% of your [seat / API / storage] limit"
- Option C: "Good news and a heads-up: [Product] usage is up 34% this month"

Body:

---
Hi [Admin First Name],

Quick update on your [Product] account — your team has been incredibly active lately, and I wanted to give you an early heads-up before you run into any friction.

**Your [Resource] usage this month:**
- [Seats used]: [X] of [Y] licensed seats active
- [Core metric]: [e.g., 847 of 1,000 monthly API calls used]
- [Usage trend]: Up [X%] from last month

At your current pace, you'll reach your plan limit around [estimated date — calculate from current usage rate].

**Your options:**

→ **Upgrade to [Next Tier]** — get [2x/unlimited] [resource] plus [key premium feature they're actively using or have shown interest in] for [price difference/month]
[Upgrade Now — 60 seconds, no downtime]

→ **Stay on your current plan** — we'll send you a heads-up if you get within 5% of your limit

→ **Talk to someone** — if your needs are more complex, [reply to this email / book 15 minutes] and I'll make sure you get the right setup

No pressure — just want to make sure your team never hits a wall mid-workflow.

[CSM Name or "The [Product] Team"]

P.S. The [X] teams that upgraded to [Next Tier] this quarter reported [specific outcome: "saved 6 hours/week on reporting" / "reduced data processing time by 40%"] — happy to share the details if useful.
---

---

**Template B: Feature Adjacency / Cross-Sell Email**

Subject line options:
- Option A: "You've been looking at [Feature Name] — here's a 14-day trial, on us"
- Option B: "The feature [X] of your peers use most — and why it might matter for [Company]"
- Option C: "Quick question about how you're using [Product] for [use case]"

Body:

---
Hi [Champion First Name],

I was reviewing your [Product] usage and noticed your team has been exploring [Feature Name / Module] a few times recently.

I'll be honest — that feature is one of my favorites to show customers in your space, because it directly addresses [specific pain point relevant to their industry/persona]. Teams like [Reference Customer in Similar Industry] use it to [specific outcome with real number].

Since you've been curious, I'd like to offer your team a **14-day trial of [Feature Name]** at no cost — no contract change, no credit card required.

What it does:
- [Benefit 1 — specific, measurable]
- [Benefit 2 — specific, measurable]
- [Benefit 3 — specific, measurable]

If it's useful, great — we can talk about adding it to your plan. If it's not the right fit, the trial just expires and nothing changes.

Want me to activate it for your account? I can have it turned on within the hour.

[CSM Name / AE Name]
---

---

**Template C: Seat Expansion / Power User Cluster Email**

Subject line options:
- Option A: "Your [Product] team is in the top 15% for engagement — here's what that means"
- Option B: "[Company]: [X] of your users are power users. The other [Y] could be too."
- Option C: "A quick look at how [Company] is using [Product] this quarter"

Body:

---
Hi [Champion First Name],

I pulled your team's [Product] activity for the quarter and wanted to share something notable:

**[Company]'s [Product] usage — [Quarter]:**
- [X] active users completing [core workflow] ≥ [threshold]x per week
- [Y] workflows completed in the last 30 days
- Your team is in the top [%] of [similar company size] accounts in terms of [usage metric]

That's a strong signal that [Product] has become genuinely embedded in how your team works.

Here's what I also noticed: your team has sent [Z] invitations to new colleagues in the last month. Some were accepted, some may still be pending — but there's clearly appetite to bring more people in.

The most successful teams we work with at this stage typically [expand to the full [Department] team / upgrade to a plan with [admin controls / SSO / unlimited seats]] so the product scales with them rather than becoming a bottleneck.

I've put together a quick summary of what this looks like for a team your size:

→ [X] additional seats would cover [% of invitations sent] at $[price/month per seat or total]
→ At your usage rate, that works out to approximately $[X] per power workflow completed — the math is compelling when you look at it that way

Happy to walk through the numbers with your manager or finance team if that would help. Or if you'd prefer, I can put together a 1-page ROI summary you can share internally — just say the word.

[CSM Name / AE Name]

P.S. Happy to set up a 20-minute session showing [New User] (who just joined your team) how to get to power-user status in their first 2 weeks — if that would be useful.
---

---

### 5. Expansion Revenue Attribution Model

**Attribution Framework: The PLX Revenue Waterfall**

Goal: Understand which expansion activities drove revenue so you can double down on the highest-ROI motion.

Define four expansion attribution buckets:

**Bucket 1: Product-Initiated, Self-Serve Closed (Pure PLX)**
Definition: Account upgraded directly from in-app modal or automated email without any human contact
Tracking method: CRM opportunity created by automation with source = "PLX_self_serve" + campaign trigger ID logged
Revenue credit: 100% marketing/product; 0% sales/CS
Typical contribution: 15–35% of total expansion revenue for mid-market SaaS

**Bucket 2: Product-Initiated, Human-Assisted Close (PLX-Assisted)**
Definition: Product trigger fired (signal detected, campaign sent), AND a CSM or AE touchpoint occurred within 30 days before close
Tracking method: Multi-touch attribution in CRM — first touch = product trigger, last touch = CSM/AE activity
Revenue credit: 50/50 split between marketing/product and sales/CS
Typical contribution: 25–45% of total expansion revenue

**Bucket 3: Human-Initiated, Product-Informed (CS/Sales-Led)**
Definition: CSM or AE opened the expansion conversation without a product trigger, but referenced product usage data in their outreach
Tracking method: CRM opportunity created by CSM/AE with "product_data_referenced" checkbox; product analytics pull verified usage data was shared
Revenue credit: 80% sales/CS, 20% marketing/product (for infrastructure investment)
Typical contribution: 30–50% of expansion revenue (highest at enterprise segment)

**Bucket 4: Renewal Uplift (Expansion Within Renewal)**
Definition: Expansion occurred as part of a contract renewal conversation (seat add, tier upgrade, or multi-year commit with expansion built in)
Tracking method: CRM renewal opportunity with expansion delta tracked as separate line item; source = "renewal_expansion"
Revenue credit: Split 30/70 (marketing/CS) — renewal process is CS-led but marketing programs influence customer perception and ROI belief going into renewal
Typical contribution: 20–35% of expansion revenue

---

**Attribution KPI Dashboard (Monthly)**

| Metric | Definition | Target Benchmark |
|---|---|---|
| PLX Coverage Rate | % of expanded accounts that had a product trigger fire in the 90 days prior to expansion | >60% |
| Product-Initiated Expansion Revenue | $ ARR from Buckets 1 + 2 | Track MoM growth |
| Signal-to-Upgrade Conversion Rate | % of accounts that hit a Limit Approach trigger and upgraded within 30 days | 15–30% |
| Time-to-Expansion After Signal | Median days from first product signal to closed expansion | Track MoM decline (target <21 days for self-serve, <45 days for assisted) |
| PLX CAC | Total cost of expansion automation infrastructure ÷ expansion ARR from Buckets 1+2 | <0.15 (i.e., $0.15 to generate $1 in expansion ARR) |
| Expansion Pipeline Coverage | Value of active expansion opportunities ÷ expansion ARR target | >3x |
| CSM Expansion Efficiency | Expansion ARR per CSM (per quarter) | Track vs. industry benchmark for your ACV segment |

---

**Revenue Attribution Reporting Cadence:**

Weekly: Product trigger performance snapshot (how many triggers fired, how many campaigns sent, immediate conversion rate) — automated report from marketing automation to #revenue-ops Slack channel

Monthly: PLX Revenue Waterfall report — breakdown of expansion ARR by attribution bucket; which triggers drove the most revenue; which campaigns converted vs. which need optimization

Quarterly: PLX vs. CS-led expansion efficiency comparison — cost per $1 of expansion ARR by motion; recommendation on where to invest next quarter (more automation infrastructure? More CSM capacity?)

---

### 6. Tool Configuration Playbook

**Amplitude → CRM/MAP Integration (via Census or Hightouch)**

1. Define computed traits in Amplitude:
   - `seats_utilization_pct` = seats_active_30d / seats_licensed
   - `power_user_count` = COUNT(user_id WHERE core_workflow_completions_7d >= [threshold])
   - `locked_feature_clicks_30d` = COUNT(events WHERE event_name = "feature_gate_shown" AND timestamp > 30d_ago)
   - `new_user_invitations_14d` = COUNT(events WHERE event_name = "invite_sent" AND timestamp > 14d_ago)

2. Push these traits to Salesforce/HubSpot as custom fields on the Account object via Census or Hightouch reverse ETL (run hourly sync)

3. In HubSpot/Salesforce: Build workflow/trigger logic on these fields (e.g., IF `seats_utilization_pct` >= 0.80, create task + enroll in "Limit Approach" email campaign)

**Pendo → Marketing Automation Integration**

1. Create Pendo Segments matching each expansion profile (Limit Hitter, Power User Cluster, etc.)
2. Use Pendo's Salesforce/HubSpot integration to sync segment membership as a custom field
3. Trigger in-app Pendo Guides for Triggers 1, 2, and 5 (Limit Warning, Limit Exceeded, Feature Exploration)
4. Use Pendo NPS combined with expansion signals for "Value Realized + Expansion Ready" compound trigger

**Customer.io / Braze Campaign Setup**

1. Create a "PLX Campaign" folder with individual campaigns for each of the 8 triggers
2. For each campaign: set entry conditions matching the product signal fields synced from your data warehouse/CDP
3. Configure suppression lists: Do not fire PLX campaigns if: account is in active churn risk (health score < 45), account is in active renewal negotiation, or campaign was already sent to this account in the last 30 days
4. A/B test subject lines for Templates A, B, C with statistical significance target of 95% before rolling out winner

## Example Input/Output

**Input:**
- Product: Screenloop — AI-powered interview intelligence platform for recruiting teams
- Packaging: Starter (5 seats, 50 interviews/month) → Pro (25 seats, 250 interviews/month) → Enterprise (unlimited)
- Primary expansion lever: Interviews/month consumption + seat count
- Average expansion deal size: $18,500 ACV increase
- Product analytics: Amplitude
- CRM: HubSpot
- Marketing automation: Customer.io
- Current NRR: 108%
- Target NRR: 125%

**Sample Output — Trigger 1 Fire for Account "Verano Talent" (Account ID #8831)**

Account status:
- Current plan: Starter (50 interviews/month, 5 seats)
- Interviews used this month: 44 of 50 (88%)
- Trend: Up 31% MoM (they onboarded 2 new hiring managers last month)
- Days left in billing period: 12
- Estimated overage date at current rate: Day 8

Automated actions fired:

**In-app banner (fires immediately):**
> "Your team has used 44 of 50 interviews this month — at your current pace, you'll hit your limit in ~8 days. [Upgrade to Pro →] to continue without interruption."

**Email (fires within 15 minutes):**
Subject: "Verano Talent: you're at 88% of your interview quota — here's what's ahead"

> Hi Priya,
> 
> Quick heads-up: your team has completed 44 of your 50 monthly interviews in Screenloop. At your current pace (which is up 31% since last month — great sign), you'll reach your limit around the 8th.
> 
> **Your options:**
> 
> → **Upgrade to Pro** — 250 interviews/month + 25 seats for $1,450/month (you're currently at $410/month). You also unlock AI interview scorecards, bias detection reports, and candidate experience surveys — features your team has previewed 7 times this month.
> [Upgrade Now — no downtime, takes 60 seconds]
> 
> → **Buy a one-time interview block** — 25 additional interviews for $150, expires end of month
> 
> → **Talk to us** — if your hiring velocity is changing, I'd love 15 minutes to find you the right plan.
> 
> Best,
> Jamie Chen | Customer Success, Screenloop

**HubSpot task created for CSM:**
> "Verano Talent (#8831) — Limit Approach trigger fired. Account at 88% interview quota. $18.5K expansion opportunity. Priya Nair (Admin) is primary contact. Email auto-sent. If no upgrade in 3 days, follow up with personalized ROI summary — they've been browsing the AI Scorecard feature (7 page views this month)."

## Success Metrics

- **PLX Coverage Rate**: ≥60% of expanded accounts had a product trigger fire in the prior 90 days — indicates the signal library is detecting real buying intent
- **Signal-to-Upgrade Conversion Rate**: Limit Approach trigger (Trigger 1) should convert at 18–30% within 14 days; Power User Cluster (Trigger 3) should convert at 12–22% within 30 days
- **Time-to-Expansion**: Median days from first signal fire to closed expansion should decrease MoM; target <21 days for self-serve, <45 days for CS-assisted
- **Email Open Rate**: Expansion emails should hit 45–65% open rates (they're contextual and timely, not mass campaigns) — below 35% indicates the subject lines need work or signals are firing at wrong accounts
- **NRR Impact**: A fully deployed PLX system should contribute 3–7 NRR percentage points within 12 months of launch
- **PLX CAC Ratio**: Total infrastructure + labor cost of PLX program ÷ expansion ARR from product-initiated campaigns should be <0.15

## Related Prompts

- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/Customer-Health-Score-&-Early-Warning-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Upsell-Cross-Sell-Revenue-Intelligence-Engine.md`
- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Net-Revenue-Retention-NRR-Forecasting-&-Cohort-Expansion-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-Product-Led-Growth-Activation-&-Freemium-Conversion-Intelligence-Engine.md`

## Integration Tips

- **Amplitude + Hightouch**: Define computed traits (seats_utilization_pct, power_user_count, locked_feature_clicks_30d) in Amplitude, then use Hightouch to reverse-ETL these traits into HubSpot/Salesforce Account fields hourly. This creates a real-time expansion signal layer in your CRM without custom engineering.
- **Pendo**: Use Pendo Segments to build exact profile definitions (Limit Hitter, Power User Cluster) and sync segment membership to Salesforce via native integration. Deploy in-app Guides for Triggers 1 and 5 — in-app messages convert 2–3x better than email alone for limit and feature expansion signals.
- **Customer.io**: Create a "PLX" campaign workspace. Use entry conditions mapped to HubSpot/Salesforce fields synced from product analytics. Configure suppression lists to prevent campaign overlap: (1) health score < 45, (2) open expansion opportunity already exists in CRM, (3) campaign sent to account in last 30 days.
- **Gainsight / ChurnZero**: Create CTAs (Calls to Action) mapped to each expansion trigger. Build a "Product Expansion Signals" CTA type so CSMs can see all product-triggered expansion opportunities in their daily workflow queue, sorted by ARR × signal urgency.
- **Segment CDP**: If using Segment as your CDP, build Personas (Audiences) matching each expansion profile. Sync Persona membership to your email platform and CRM. Use Segment's Functions to fire webhooks when an account enters a high-priority profile like "Limit Hitter" — this enables real-time campaign firing without batch-job latency.

## Troubleshooting

**Problem: Expansion campaigns are firing but conversion rate is below 5%**
Fix: The signal library is detecting activity but not true buying intent. Run a cohort analysis: look at accounts that DID convert after receiving expansion campaigns and work backwards — what product signals were present 30/60 days before expansion, not just at campaign fire time? The highest-converting triggers are almost always Limit Ceiling signals (accounts that literally cannot proceed without upgrading), not engagement signals. If you're relying heavily on engagement signals (time-in-app, feature exploration), add a MINIMUM usage threshold as a filter — only fire expansion campaigns at accounts that have also completed ≥[X] core workflows in the last 30 days. Low-engagement accounts with high "feature browsing" are often just evaluating, not ready to expand.

**Problem: CSMs are complaining that PLX campaigns are interfering with their expansion conversations**
Fix: This is a coordination failure, not a program failure. Implement a CRM-based suppression rule: if a CSM has logged an "expansion conversation" activity in the last 30 days OR if there is an open expansion opportunity in the CRM, suppress all automated PLX campaigns for that account. Create a Slack notification that fires when a PLX trigger detects an expansion signal on a CSM-managed account — so the CSM gets the intelligence and can choose to act, rather than having automation send an email that undercuts their personal relationship.

**Problem: Expansion signals are accurate but self-serve upgrade rate is low — customers start the upgrade flow but don't complete it**
Fix: This is a checkout friction problem, not a campaign problem. Audit your upgrade flow: (1) How many steps from campaign CTA to completed payment? Should be ≤3 steps. (2) Is the pricing transparent and the ROI case made at the upgrade confirmation screen? (3) Is there a "talk to someone" escape valve for customers who want validation before committing? Companies with high-ACV products ($1K+/month expansion) often need a "get a quote" flow instead of a self-serve checkout — the purchase feels too high-stakes to complete without human confirmation. For these accounts, replace the "Upgrade Now" CTA with "Get your upgrade quote in 60 seconds" and route to a pre-filled order form that triggers a same-day CSM call.

## Version History
- v1.0: Initial creation (auto-generated)
