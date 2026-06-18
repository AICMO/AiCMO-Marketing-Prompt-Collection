# AI-Powered B2B SaaS Marketing-Led Customer Expansion & Account Upsell Revenue Architecture Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** expansion-revenue, upsell, cross-sell, customer-marketing, nrr, product-led-growth, b2b-saas, lifecycle-marketing

## Overview

Designs a fully automated, AI-powered marketing system that identifies expansion-ready customers using product usage signals, health indicators, and business triggers — then orchestrates targeted upsell, cross-sell, and seat-expansion campaigns that generate incremental ARR without a full sales cycle. Converts marketing from a new-logo-only function into a revenue expansion engine responsible for measurable NRR improvement.

## Quick Copy-Paste Version

You are a senior B2B SaaS customer marketing strategist. Build a complete marketing-led expansion revenue program for [Your Company] that sells [Product Description] to [ICP: Title, Company Size, Industry] with an ACV of [ACV] and [list expansion vectors: seats/modules/tiers].

Design the following:

1. EXPANSION SIGNAL DETECTION SYSTEM
Map every signal that indicates a customer is ready to expand:
- Product usage signals: capacity utilization thresholds, feature adoption gaps, power user concentration, API volume growth, integration activations
- Business signals: hiring in buyer persona roles, funding announcements, acquisition activity, new strategic initiatives mentioned in QBRs
- Relationship signals: champion promotions, executive sponsor engagement level, NPS score and trend, support ticket volume and sentiment
- Contract signals: renewal window (90/60/30 days), contract anniversary, unused seat headroom, add-on eligibility

2. EXPANSION OPPORTUNITY SCORING
Build a 0-100 Expansion Readiness Score using:
- Product adoption health (% of features actively used vs. licensed)
- Capacity utilization rate (if at 80%+ of seat/usage limit = upsell trigger)
- Account growth signals (headcount growth, new departments onboarded)
- Relationship strength (executive sponsorship, NPS, champions identified)
- Time-sensitive triggers (renewal date proximity, end-of-quarter)

3. MARKETING-LED EXPANSION PLAYBOOKS
For each expansion type, define a full marketing motion:
- Seat expansion: usage-triggered email sequences + in-app banners + champion enablement kit
- Tier upgrade: ROI proof campaign + executive value report + competitive upgrade messaging
- Cross-sell add-on: feature webinar series + customer success case study + free trial of add-on
- Multi-year renewal: loyalty offer campaign + executive relationship program + reference program enrollment

4. IN-PRODUCT MARKETING ARCHITECTURE
Design contextual in-app messages that drive expansion without feeling pushy:
- Usage milestone celebrations with upgrade invitation
- Feature gate preview: "Your team is approaching the limit — see what's next"
- Peer benchmarking messages: "Teams like yours using [Advanced Feature] see 40% faster [outcome]"
- QBR prep templates auto-delivered to champions 2 weeks before renewal

5. EXPANSION REVENUE ATTRIBUTION & MEASUREMENT
Define how marketing claims credit for expansion revenue:
- Marketing-sourced expansion (campaign directly touched before upsell close)
- Marketing-influenced expansion (account received ≥1 marketing touch within 90 days of close)
- Expansion NRR contribution by marketing motion type
- Expansion CAC (cost per $1 of expansion ARR generated)

Provide specific tool recommendations and a 60-day implementation roadmap.

## Advanced Customizable Version

ROLE: You are a VP of Customer Marketing and Revenue Expansion with 12+ years of experience at B2B SaaS companies scaling from $10M to $500M ARR. You have built marketing-led expansion programs that contributed 25-40% of total ARR growth through upsell and cross-sell. You understand product usage data, CS handoff protocols, in-product messaging (Pendo, Appcues, Intercom), CRM revenue operations, and how to align marketing with CS teams to own measurable expansion revenue — without creating channel conflict.

CONTEXT:
- Company: [Company Name]
- Product: [One-sentence description]
- Current ARR: [$X]
- Customer count: [X customers]
- Average ACV: [$X]
- Expansion vectors available: [Seats / Modules / Tiers / Usage-based / Professional services]
- Current NRR: [X%] — target NRR: [X%]
- CS team size: [X CSMs], ratio: [X accounts per CSM]
- Current expansion motion: [Sales-led / CS-led / Product-led / None]
- Product instrumentation: [Pendo / Mixpanel / Amplitude / None — specify what product data is available]
- CRM: [Salesforce / HubSpot]
- Marketing automation: [Marketo / HubSpot / Pardot / Other]
- In-product messaging tool: [Pendo / Appcues / Intercom / None]
- Key expansion bottleneck: [Not knowing which accounts are ready / CS doesn't have time to expand / No marketing campaigns for existing customers / Attribution unclear / Products not cross-sold effectively]
- Expansion ARR target for next 12 months: [$X]

OBJECTIVE: Design a production-ready, fully automated marketing-led expansion revenue architecture that:
1. Detects expansion-ready customers using product usage + business signals before the CS team identifies them
2. Triggers differentiated marketing plays by expansion type (upsell vs. cross-sell vs. renewal) without requiring CSM manual initiation
3. Enables champions inside accounts to become internal advocates who sell upward
4. Creates marketing-attributable expansion pipeline with clean revenue tracking
5. Improves NRR by [X percentage points] within 12 months

---

SECTION 1: EXPANSION SIGNAL TAXONOMY & DETECTION ARCHITECTURE

Map all signals that indicate a customer account is expansion-ready, organized by category:

A. PRODUCT USAGE SIGNALS (Highest intent, most reliable)
For each signal, specify: what it indicates, detection method, and expansion vector it triggers.

Seat/License Expansion Signals:
- Utilization rate ≥80% of licensed seats: Monitor weekly; trigger seat expansion campaign when crossed. Most reliable upsell signal — account has validated value, just needs room.
- New team members onboarded within 30 days: Detect via user provisioning events; indicates growth; prompt team-tier upgrade.
- Shared account/generic logins detected: Multiple users sharing one seat = suppressed usage; prompt seat expansion with productivity data.
- Admin inviting external users beyond account limit: Permission error events = friction signal; convert to upsell opportunity.

Feature Adoption / Tier Upgrade Signals:
- Power feature usage gap: Customer on Basic tier using 3 of 4 features gated at Premium — send feature unlock email.
- API rate limit approaching threshold: Developer-led adoption growing; triggers API/enterprise tier conversation.
- Integration activated that pairs with premium feature: "You connected [Tool X] — teams that add [Premium Feature] save 3 hours/week" message.
- Reports/exports run more than 20x/month on limited plan: Data-heavy users signal readiness for analytics tier.
- Time-in-product increasing month-over-month (>20% increase): Growing engagement = growing dependence = expansion readiness.

Cross-Sell Signals:
- Core product adoption exceeding 70% of features: Strong depth of adoption = readiness for adjacent product.
- Support tickets requesting functionality that lives in Add-On B: Direct cross-sell signal — route to product marketing campaign.
- Customer industry benchmark shows peers using Module X at 3x rate: Competitive peer pressure campaign trigger.
- Single department using product; other departments visible in org chart: Multi-department expansion opportunity.

B. BUSINESS & RELATIONSHIP SIGNALS (External triggers)
- Headcount growth >15% in 90 days (target department): More team members = more seats needed; detect via LinkedIn or ZoomInfo.
- Funding round announced: Budget availability; triggers executive outreach + premium tier pitch.
- Champion promoted to VP/Director role: Higher budget authority; send congratulatory executive value report + strategic conversation request.
- New executive (buyer persona) hired at account: New decision-maker needs to validate tool choice; send onboarding package + ROI report + executive reference offer.
- Company acquired or merged with another: Consolidation opportunity; reach out with enterprise licensing discussion.
- Champion job change OUT (to a new company): Risk of churn + new expansion opportunity at new company; dual response needed.
- NPS score jumped from Detractor/Passive to Promoter: Sentiment recovery = expansion window; strike while positive.

C. CONTRACT & RENEWAL SIGNALS
- 90 days to renewal: Begin executive relationship campaign + success story sharing.
- 60 days to renewal: Send business review package with ROI data + multi-year offer.
- 30 days to renewal: Champion enablement kit: "how to present renewal internally."
- Contract anniversary: Milestone celebration email + account health report.
- Discount due to expire: Transparent value reinforcement campaign before price normalization.

D. HEALTH RISK SIGNALS (Defensive expansion — retain before expand)
- Login frequency declining >30% month-over-month: Churn risk; trigger re-engagement before expansion attempt.
- NPS score Detractor (0-6): CS priority; marketing holds expansion campaigns until health improves.
- Support tickets >10/month with unresolved status: Block expansion marketing; route to CS escalation.
- Feature adoption below 30% of licensed capacity: Value realization gap; trigger adoption campaign before upsell.

---

SECTION 2: EXPANSION READINESS SCORE ARCHITECTURE

Build a composite 0-100 Expansion Readiness Score per account:

BASE SCORE COMPONENTS:
| Signal | Points | Rationale |
|--------|--------|-----------|
| Seat utilization ≥80% | 30 | Strongest mechanical upsell trigger |
| Feature adoption rate >70% | 20 | High product stickiness = safe to upsell |
| Monthly active user growth >20% | 15 | Active expansion of usage |
| Cross-sell feature interest signal | 25 | Direct cross-sell intent |
| Champion promoted (new budget authority) | 20 | Relationship + budget signal |
| Funding announced | 15 | Budget availability |
| New executive hire (buyer persona) | 12 | Re-evaluation window |
| Renewal within 90 days | 10 | Time-sensitive conversion moment |
| NPS Promoter status | 10 | Safe to ask for more |
| Peer benchmark gap (below industry avg adoption) | 8 | Social proof expansion trigger |

SCORE PENALTIES (subtract from total):
- Login frequency declining: -20
- Active support escalation: -25
- NPS Detractor status: -35 (block expansion campaigns entirely)
- Within 30-day post-implementation: -15 (too early to expand)
- Churned department within account: -10

SCORE MODIFIERS:
- ICP Tier 1 account: +15% multiplier
- Enterprise account (>500 employees): +10%
- Strategic account (custom contract): route to enterprise CS before marketing
- Multi-year contract in place: -5 (less urgency, lower expansion score)

EXPANSION READINESS BANDS:
- PRIME (75-100): Expansion motion active; marketing + CS coordinated outreach
- READY (50-74): Marketing-led expansion campaigns; CS informed
- DEVELOPING (25-49): Adoption marketing only; no expansion pitch
- AT-RISK (0-24): Recovery marketing only; CS owns account; expansion suppressed

---

SECTION 3: MARKETING-LED EXPANSION PLAYBOOKS BY VECTOR

For each expansion type, define the full automated marketing motion:

A. SEAT EXPANSION PLAYBOOK (Score 75+, utilization ≥80%)
Trigger: Account has 80%+ of seats in active use for 2+ consecutive weeks.

Week 0: Automated email to Admin + Power Users
Subject: "[Company] is running at 85% capacity — your team is growing"
Message: Usage data visualization + peer benchmark ("Teams your size typically use [X] seats") + "See seat expansion options" CTA → pricing page with expansion SKU highlighted.

Week 1: Champion enablement kit sent
A one-pager for the champion to share internally: "Why we need more seats" business case template with ROI per user calculations pre-filled with their actual productivity data.

Week 2: In-app banner for Admin
"Your team is bumping into limits. [Expand now] — takes 60 seconds, no new contract needed."

Week 3: CSM alert
If no expansion action taken, CSM receives summary: "Account is at 85% seat capacity for 3 weeks. Marketing has sent 2 touches. Recommend QBR agenda item."

B. TIER UPGRADE PLAYBOOK (Score 50+, feature adoption gap detected)
Trigger: Account is using 3 of 4 Premium-tier features on Basic plan, OR API rate-limit approaching.

Day 0: Feature discovery email to champion
Subject: "Your team keeps hitting the edge of [Basic Feature] — here's what's just above it"
Content: Specific feature they're missing, 3-minute demo GIF, customer story from similar company, "Try Premium free for 14 days" CTA.

Day 3: In-app contextual message
When user hits feature gate: "This is a Premium feature. [See full capabilities] — or [Start free trial]."

Day 7: ROI-focused follow-up
Email to champion + economic buyer (if known): ROI calculator pre-populated with their usage data showing time/revenue impact of Premium features. "Teams like [Similar Customer] saved $X/year after upgrading."

Day 14: Executive value report
Automated PDF report generated with their actual product ROI data, sent to champion with suggested email template to forward to their VP/Director.

Day 21: CSM handoff alert if no conversion
Marketing summary sent to CSM: "Account has received 3 upgrade touches. Recommend including in next check-in."

C. CROSS-SELL PLAYBOOK (Score 50+, add-on interest signal detected)
Trigger: Support ticket mentions functionality of Add-On B, OR peer benchmark shows <30% adoption of cross-sell product in their industry.

Phase 1 (Days 0-14): Education campaign
3-part email series: "How [Add-On B] works with [Core Product]" + customer success story from same industry + product walkthrough video (90 seconds).

Phase 2 (Days 15-28): Proof + trial offer
Case study PDF of similar customer achieving [specific outcome] with combined product. Personalized ROI estimate based on their current usage. "Start a 21-day free trial of [Add-On B]" — no credit card required.

Phase 3 (Days 29-42): Scarcity + enablement
"Your free trial offer expires in 7 days" + champion kit (internal pitch deck template for presenting cross-sell to finance/IT). CSM alert if trial started but not converted.

D. MULTI-YEAR RENEWAL PLAYBOOK (90-60-30-day sequence)
Trigger: Contract renewal within 90 days.

Day 90 (T-90): Executive relationship email
From CMO/VP to Executive Sponsor: "As we approach your renewal, here's what your team accomplished with [Product] this year." Attach automated impact report with their actual metrics (seats used, features adopted, time saved, ROI estimate).

Day 60 (T-60): Champion success package
Automated "Renewal Readiness Kit" sent to champion:
- Business case template for internal approval
- Peer benchmark report (your company vs. industry)
- Multi-year pricing calculator (show savings vs. annual)
- Reference customer list in their industry for procurement calls

Day 30 (T-30): Champion enablement — internal selling
Email with subject: "How to get your renewal approved in one meeting"
Content: 5-slide internal pitch deck (auto-populated with their metrics), objection-handling FAQ for common procurement questions, direct CSM contact for expedited renewal support.

Day 14 (T-14): Executive outreach escalation
If renewal not signed: marketing triggers "executive outreach package" — CSM + AE send coordinated outreach to Executive Sponsor with C-level reference offer and executive briefing invite.

---

SECTION 4: IN-PRODUCT MARKETING ARCHITECTURE FOR EXPANSION

Design contextual in-product messages (via Pendo, Appcues, or Intercom) that convert product engagement into expansion without disrupting the user experience:

MESSAGE TYPE 1: Usage Milestone Celebration
When: User completes [X] actions, reaches [Y] days active, or hits a productivity milestone.
Message: "[Your team just saved its 1,000th hour using [Product]]. Your plan is built for [current tier] — [see what's next] for teams ready to scale."
Tone: Celebratory, not pushy. Expansion is framed as recognition of success, not a sales pitch.

MESSAGE TYPE 2: Feature Gate Preview
When: User attempts to access a Premium feature on a Basic plan.
Message: "This is a [Premium] feature. [Teams like Acme Corp] use it to [specific outcome]. [See a 90-second demo] or [Start a free trial]."
Design: Non-blocking modal, easy to dismiss. Show once per 30 days per user.

MESSAGE TYPE 3: Peer Benchmark Prompt
When: Monthly — surfaced to Admin/Power User via in-app notification.
Message: "Teams your size in [Industry] typically use [X seats] and [Y% of features]. Your team is at [Z% of benchmarks]. [See recommendations] for closing the gap."
Design: In-app notification badge, not modal. Drives to a personalized expansion page.

MESSAGE TYPE 4: Approaching Limit Warning
When: 80% seat/usage threshold crossed.
Message (Admin only): "⚠️ Your team is at 83% capacity. At current growth, you'll hit your limit in ~18 days. [Expand now] to avoid disruption."
Design: Persistent banner in admin console. Auto-dismiss after expansion action taken.

MESSAGE TYPE 5: New Feature Introduction for Upgrade
When: New Premium feature launches — surfaced only to Basic plan users.
Message: "New: [Feature Name] is now available in [Premium]. [Company X] uses it to [outcome]. Available [as part of your upgrade] or [as a 30-day trial]."
Timing: Launch day + day 7 + day 21 (if no action taken).

---

SECTION 5: EXPANSION REVENUE ATTRIBUTION & MEASUREMENT

Define how marketing claims measurable credit for expansion revenue:

ATTRIBUTION MODEL:
- Marketing-sourced expansion: Marketing campaign is the first touch that initiated an expansion conversation (e.g., champion clicked upgrade email and started trial before CS involvement). Full credit.
- Marketing-influenced expansion: Account received ≥1 marketing touch within 90 days of expansion close date AND no CS-initiated expansion conversation recorded. Partial credit (50%).
- CS-sourced expansion: CS initiated expansion in QBR/check-in with no prior marketing touch. Marketing claims 0% unless in-product messaging was involved (then 20% influence credit).

CRM TRACKING REQUIREMENTS:
- Every marketing expansion touch logged as Campaign Member in Salesforce or Contact Activity in HubSpot
- Expansion opportunity "Campaign Source" field populated at opportunity creation
- Custom field: "First Marketing Expansion Touch Date" — enables 90-day influence window calculation
- Revenue type field on Opportunity: New Logo / Expansion Upsell / Expansion Cross-Sell / Renewal — enables clean NRR reporting by motion

PRIMARY METRICS (Monthly reporting):
- Expansion ARR sourced by marketing ($) — target: [X% of total expansion ARR]
- Expansion ARR influenced by marketing ($)
- NRR by cohort: marketing-touched vs. not marketing-touched (should show 5-10pt NRR difference if program is working)
- Expansion pipeline created by marketing motion (seat expansion / tier upgrade / cross-sell / multi-year)
- Expansion conversion rate by playbook type: % of PRIME accounts that convert within 90 days of playbook activation
- Expansion marketing CAC: total expansion marketing spend ÷ expansion ARR sourced

SECONDARY METRICS (Quarterly review):
- Feature adoption rate change after campaign enrollment (are campaigns actually increasing product usage?)
- In-product message engagement: click-through rate, conversion rate by message type
- Champion engagement rate: % of expansion campaigns opened/clicked by champion persona
- CS deflection rate: % of expansions closed without requiring CSM time (fully marketing-led)

CONTINUOUS IMPROVEMENT LOOP:
- Monthly: Review expansion playbook conversion rates; kill underperforming sequences; increase budget on top performers
- Quarterly: Audit Expansion Readiness Score accuracy — compare score band to actual expansion rate; recalibrate weights
- After every 20 expansion closes: Analyze which signals and campaigns correlated to fastest and largest expansions; update playbooks

---

SECTION 6: CS-MARKETING COORDINATION PROTOCOL

Define how marketing and CS teams hand off expansion opportunities without creating confusion or duplication:

RULES OF ENGAGEMENT:
- Marketing owns: READY band (50-74 score) accounts — automated campaigns with CS FYI notification
- Marketing + CS co-own: PRIME band (75-100 score) — coordinated outreach; marketing provides content, CS leads conversation
- CS owns exclusively: At-risk accounts (0-24 score), strategic accounts >$100K ACV, accounts in active churn discussions

WEEKLY SYNC DATA EXCHANGE:
- Marketing sends CS weekly: List of accounts that enrolled in expansion campaigns, accounts that clicked upgrade CTAs, accounts that started free trials, accounts approaching contract signals
- CS sends marketing weekly: Accounts entering QBR cycle (start renewal playbook), accounts CS has flagged as expansion-ready (override marketing scoring), accounts in escalation (suppress all marketing campaigns)

CS OVERRIDE SYSTEM:
CSMs can override marketing suppression or acceleration via a simple Salesforce field:
- "Marketing Hold": [Yes/No] — stops all marketing campaigns to this account
- "Expansion Marketing Priority": [High/Standard/Low] — overrides automated scoring
- "Expansion Type Focus": [Seats/Tier/Cross-sell/Renewal] — directs which playbook runs

RECOMMENDED TECH STACK:
- Product analytics: Amplitude or Mixpanel (behavioral signals) / Pendo (in-app messaging + analytics)
- In-product messaging: Pendo or Appcues (contextual messages) / Intercom (in-app chat + product tours)
- CRM: Salesforce (optimal for complex attribution) or HubSpot
- Marketing automation: Marketo or HubSpot Workflows (for expansion email sequences)
- Customer data platform: Segment (to pipe product events into marketing automation)
- CS platform: Gainsight or ChurnZero (for CS health scores + CS-marketing data exchange)
- Revenue intelligence: Clari or Gong (to track expansion conversations and attribution)

---

60-DAY IMPLEMENTATION ROADMAP:

Week 1-2: Data infrastructure
- Map product events to CRM accounts (Segment → Salesforce/HubSpot)
- Define utilization metrics and calculate current utilization per account
- Identify expansion signal fields to add to CRM Account object
- Audit current in-product messaging setup (Pendo/Appcues)

Week 3-4: Scoring model build
- Build Expansion Readiness Score in CRM using product + firmographic data
- Categorize all accounts into PRIME/READY/DEVELOPING/AT-RISK bands
- Validate scoring against historical expansion deals (do high-score accounts actually expand more?)
- Review with CS team and calibrate overrides

Week 5-6: First playbook launch (seat expansion)
- Build seat utilization trigger in Marketo/HubSpot
- Create email sequence assets (3 emails + champion kit)
- Configure in-app utilization warning banner
- Set up CS alert notifications
- Launch pilot with PRIME accounts only

Week 7-8: Attribution setup + analytics
- Configure Campaign Member tracking for all expansion touches
- Build expansion revenue dashboard in Salesforce/HubSpot
- Define NRR attribution methodology and document for finance alignment
- Run first expansion pipeline review with CS leadership

Day 60: Full program review
- Playbook performance: conversion rates vs. baseline (pre-program expansion rate)
- Score model accuracy validation
- CS-marketing feedback review
- Decide which additional playbooks to build next (tier upgrade, cross-sell, multi-year)

## Example Input/Output

**Input Example:**
- Company: Velocity AI (AI-powered sales coaching platform)
- ICP: VP Sales, Revenue Enablement Director at B2B SaaS, 50-500 person companies
- ACV: $52,000 | Current ARR: $18M | Customers: 346
- Expansion vectors: Seats, Pro tier (advanced analytics), Admin module (add-on)
- Current NRR: 108% | Target NRR: 118%
- CS team: 8 CSMs, ratio: 43 accounts per CSM
- Product instrumentation: Amplitude + Pendo installed; Segment in place
- CRM: Salesforce; Marketing: HubSpot Workflows; In-product: Pendo

**Output Example (abbreviated):**

*Expansion Readiness Score Distribution — Velocity AI Portfolio:*

| Band | Accounts | % of Base | Est. Expansion ARR Opportunity |
|------|----------|-----------|-------------------------------|
| PRIME (75-100) | 41 | 12% | $2.1M (top priority) |
| READY (50-74) | 87 | 25% | $3.4M (marketing-led) |
| DEVELOPING (25-49) | 134 | 39% | Focus on adoption first |
| AT-RISK (0-24) | 84 | 24% | CS-led recovery; no marketing |

*Top Expansion Signals Detected This Week (PRIME accounts only):*
- 18 accounts at ≥80% seat utilization (seat expansion playbook activated)
- 9 accounts with champion promoted in last 30 days (executive value report triggered)
- 7 accounts using 3 of 4 Pro features on standard plan (tier upgrade campaign activated)
- 5 accounts renewed their CRM + started using Velocity AI's new Competitive Intel add-on prompt signals (cross-sell activated)

*Seat Expansion Campaign Performance — Week 8 Results (pilot):*
- 18 accounts entered seat expansion playbook
- 11 opened utilization warning email (61% open rate vs. 22% general marketing benchmark)
- 6 clicked champion kit download (33% CTR)
- 4 expanded seats within 30 days ($186,000 expansion ARR)
- 2 additional in active CS conversation
- Expansion marketing CAC: $2,100 per expansion deal (vs. $18,400 CAC for new logo)

*Best-Performing Campaign Signal Combo:*
Champion promoted to Director + seat utilization ≥80% = 71% expansion conversion rate within 45 days (vs. 23% single-signal baseline).

*Sample In-App Message Performance (Pendo):*
- Approaching Limit Banner (Admin): 8.4% click-to-expand rate; $94K ARR from in-app alone
- Feature Gate Preview (Pro): 3.2% trial start rate; 1.1% converted to paid upgrade (industry benchmark: 0.8%)

## Success Metrics

- **Expansion ARR sourced by marketing** ≥15% of total expansion ARR within 6 months
- **PRIME account conversion rate** ≥30% of PRIME accounts (score 75-100) expanding within 90 days of playbook activation
- **Seat expansion campaign** open rate ≥45% (vs. typical marketing email benchmark of 25%)
- **NRR improvement** +5 to +10 percentage points within 12 months for marketing-touched cohorts vs. control group
- **Expansion marketing CAC** <15% of new logo CAC (expansion should be significantly cheaper)
- **CS deflection rate** ≥40% of expansion ARR closed without requiring CSM-initiated conversation
- **In-product message conversion** ≥3% click-to-upgrade rate on feature gate previews
- **Champion kit engagement** ≥50% of recipients downloading champion enablement kit when seat utilization ≥80%

## Related Prompts

- [Customer Retention & Expansion Revenue Engine](Customer-Retention-&-Expansion-Revenue-Engine.md)
- [B2B Customer Marketing Program & Lifecycle Revenue Intelligence Engine](B2B-Customer-Marketing-Program-&-Lifecycle-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Champion Nurture & Internal Selling Email Intelligence Engine](../Email-Marketing-&-Nurturing/AI-Powered-B2B-SaaS-Champion-Nurture-&-Internal-Selling-Email-Intelligence-Engine.md)
- [AI-Powered Net Revenue Retention & Expansion Revenue Intelligence Engine](../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/AI-Powered-Net-Revenue-Retention-&-Expansion-Revenue-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Add custom Account fields: `Expansion_Readiness_Score__c`, `Expansion_Band__c`, `Seat_Utilization_Pct__c`, `Last_Marketing_Expansion_Touch__c`. Build a Flow to auto-create CSM task when PRIME band crossed. Use Campaign Member objects to track all expansion email touchpoints for attribution reporting. Create a dedicated "Expansion Pipeline" Report Type filtered by Opportunity Type = Expansion.
- **HubSpot**: Use Workflow enrollment triggers based on Custom Properties synced from product analytics. Build separate Pipelines for "Expansion Opportunities" vs. "New Logo Opportunities" to keep NRR reporting clean. Use HubSpot Sequences for personalized CSM+marketing coordinated outreach on PRIME accounts.
- **Pendo**: Install Pendo resource center for in-app expansion content delivery. Build Segments based on feature adoption and utilization data. Configure Guide triggers for usage milestone messages (set to "Seen Once" frequency to avoid fatigue). Export Pendo event data to Salesforce via Segment integration for CRM-level expansion scoring.
- **Amplitude / Segment**: Create Amplitude cohorts for utilization threshold crossings and feature adoption gaps. Use Segment to pipe these cohorts into HubSpot/Marketo as List enrollments that trigger expansion workflows. Set up Segment Computed Traits for "Seat Utilization Rate" and "Feature Adoption Score" — sync to CRM nightly.
- **Gainsight / ChurnZero**: Configure bi-directional sync between CS health scores and marketing expansion scoring. Use Gainsight's "Call to Action" framework to create CS tasks when marketing-expansion signals fire. Surface marketing campaign engagement data inside Gainsight account 360 view so CSMs see what the customer has already received before their next QBR.
- **Intercom**: For product-led or smaller accounts, Intercom can replace Pendo for in-app messaging. Build Intercom Series for usage milestone campaigns. Use Intercom Custom Bots to qualify expansion intent from in-app conversations before routing to CS or self-serve checkout.

## Troubleshooting

- **Problem**: CS team feels marketing is "stepping on their toes" with expansion campaigns — conflict over who owns the customer relationship.
  **Solution**: Establish a published Rules of Engagement document (signed off by VP CS and VP Marketing) that clearly delineates which accounts marketing can touch autonomously (READY band, <$50K ACV) vs. which require CS coordination (PRIME band, >$50K ACV, named accounts). Show CS the data: marketing-touched accounts expand 40% faster and CSMs who use the marketing champion kit in QBRs close upsells 2x more often. Position marketing as the CSM's toolkit, not a competitor.

- **Problem**: Product data isn't syncing into CRM reliably — Expansion Readiness Scores are stale or missing for many accounts.
  **Solution**: Before building scoring, audit the Segment/Amplitude → CRM integration for data latency and coverage gaps. Start with only signals that already exist reliably in CRM (contract dates, NPS from survey tool, CS health scores) to build a baseline score. Add product signals incrementally as data quality improves. Do NOT launch expansion campaigns on accounts with incomplete data — add a "Data Complete" flag as a required filter on all playbook enrollment.

- **Problem**: Expansion campaigns are triggering for accounts that CSMs know are unhappy or at risk — creating awkward situations.
  **Solution**: Implement a hard Marketing Hold field in CRM that CSMs can flip in 30 seconds to suppress all marketing campaigns to an account. Build a weekly automated report that shows CSMs exactly which accounts marketing has enrolled in expansion programs (with campaign names). Add a "Health Gate" to all playbook enrollment: accounts with NPS <7, active escalations, or declining usage are automatically suppressed regardless of Expansion Readiness Score.

## Version History

- v1.0: Initial creation (auto-generated)
