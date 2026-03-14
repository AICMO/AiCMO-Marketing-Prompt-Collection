# Freemium Conversion & PQL Nurture Automation Engine - Systematically Convert Free Users Into Paying Customers at Scale

**Difficulty:** Advanced | **Time:** 20 min | **Tags:** plg, saas, freemium, conversion, pql, automation, lifecycle, b2b, revenue

## Overview
Designs a complete Product Qualified Lead (PQL) identification, scoring, and automated nurture system that converts free-tier users into paying customers using behavioral signals, in-app messaging, and multi-channel sequences — without requiring a human SDR to touch every lead.

## Quick Copy-Paste Version

You are a PLG growth engineer specializing in freemium conversion optimization. Build a complete PQL nurture and freemium-to-paid conversion system for my product.

Product: [Your Product Name]
What it does: [1-sentence description]
Free tier structure: [Freemium forever / time-limited trial / reverse trial / usage-capped]
Current free-to-paid conversion rate: [e.g., 3%]
ACV of paid plans: [e.g., Starter $99/mo, Pro $299/mo, Team $799/mo]
Primary ICP: [e.g., "Marketing managers at 50-200 person B2B SaaS companies"]
Key activation event (Aha Moment): [e.g., "User completes first campaign and sees results dashboard"]

Deliver a complete PQL conversion engine with:

1. **PQL Definition & Scoring Matrix** — Define 3 tiers of PQLs (warm, hot, sales-ready). For each tier, list the exact behavioral signals (feature usage, frequency, team invites, export attempts, etc.) and assign point values. Include a SQL-ready scoring formula.

2. **Conversion Friction Map** — Identify the 5 highest-friction moments where free users abandon the upgrade path. For each, write the exact in-app message, email trigger, and CTA that removes the objection.

3. **7-Touch Automated Nurture Sequence** — Day-by-day sequence from activation to conversion. Include: email subject lines, in-app tooltips, push notifications, and the upgrade trigger for each touchpoint. Make each touchpoint behavior-conditional (only fires if user hasn't converted).

4. **Usage Limit Upgrade Triggers** — Design the exact copy and UX for 5 paywall moments: the moment a limit is hit, the soft warning before the limit, the post-limit friction message, the social proof nudge, and the urgency close.

5. **Expansion Revenue Playbook** — For users who convert to Starter, design the behavioral signals and messaging sequence to upgrade them to Pro or Team within 90 days.

6. **PQL-to-Sales Handoff Protocol** — Define exactly when and how a PQL gets routed to a human rep, what context is passed (usage data, company firmographics, intent signals), and the first outreach template the rep sends.

## Advanced Customizable Version

ROLE: You are a Senior PLG Growth Architect with deep expertise in freemium conversion optimization, behavioral email marketing, and product-led sales motions. You have designed PQL systems for companies like Notion, Figma, Loom, and Calendly — driving conversion rates from industry-average 3% to 8-15% through systematic behavioral nurture.

OBJECTIVE: Build a production-ready PQL identification, scoring, and automated conversion engine for [Company Name], a [Product Description] targeting [ICP Description].

COMPANY CONTEXT:
- Product: [Name] — [What it does in 1-2 sentences]
- Free tier: [Structure: freemium / trial / reverse trial / usage cap]
- Current metrics: [Free signups/month], [Current conversion rate %], [Average days to convert], [Average ACV]
- Key features: [List 3-5 core features with usage data if available]
- Top conversion blocker: [The #1 reason free users don't upgrade based on exit surveys or Hotjar data]
- Competitors: [2-3 competitors and their free tier strategy]
- CRM/Marketing stack: [HubSpot/Salesforce, Customer.io/Intercom/Klaviyo, Segment/Amplitude/Mixpanel]

DELIVERABLES:

## 1. PQL Scoring Architecture
Design a multi-dimensional PQL scoring model using the DEPTH framework:
- **D**epth of engagement (feature breadth used, not just login frequency)
- **E**xpansion signals (team invites, workspace creation, integrations connected)
- **P**ain signal events (limit hits, export attempts, advanced feature clicks behind paywall)
- **T**ime compression (accelerating usage trajectory, not just cumulative score)
- **H**igh-intent behaviors (pricing page visits, ROI calculator use, comparison feature checks)

For each dimension: list 5 specific behavioral events, assign point values (1-10), and define the decay curve (points that expire after 30 days of inactivity).

Tier definitions:
- **Cold PQL (40-59 pts):** In-app nurture only, no human touch
- **Warm PQL (60-79 pts):** Automated email sequence + CS chat proactive
- **Hot PQL (80+ pts):** Immediate SDR routing + priority queue flag

## 2. Activation-to-Conversion Journey Map
Map the complete free-user journey from signup to paid conversion:

For each of these 6 stages (Signup → Activation → Regular Use → Power Use → Expansion Trigger → Conversion), define:
- The behavioral milestone that marks stage entry
- The automated message triggered (channel, timing, copy)
- The friction or objection most common at this stage
- The specific CTA and upgrade incentive
- The A/B test hypothesis to optimize this stage

## 3. Behavioral Email Sequences
Write complete email sequences for 4 user segments:

**Segment A: Activated but Stalled (completed Aha Moment, no usage in 14+ days)**
- 3-email re-engagement sequence
- Subject lines, preview text, full body copy
- Personalization tokens ([first_name], [last_feature_used], [days_since_last_login])
- Clear single CTA per email

**Segment B: Active Free User Hitting Limits (reaching 80% of usage cap)**
- 3-email upgrade sequence starting 7 days before limit
- Frame around value delivered, not feature restriction
- Social proof from similar companies at same usage stage
- Time-sensitive offer structure

**Segment C: Team Expansion Signal (invited 2+ collaborators on free plan)**
- 3-email team upgrade sequence
- Lead with collaboration use case, not individual ROI
- Reference the specific number of collaborators invited
- Package pricing framing

**Segment D: Long-Term Free Users (90+ days, never converted, high engagement)**
- 2-email "we appreciate you" sequence + personalized offer
- Win-back framing: "You've gotten X value from free — here's what you're leaving on the table"
- Data-driven ROI calculation based on their actual usage

## 4. In-App Conversion Moments
Design the exact UX copy and logic for 6 in-app conversion moments:

For each moment: trigger condition, modal/tooltip/banner format, headline (max 8 words), body copy (max 30 words), primary CTA, secondary action ("remind me later" vs "not interested"), and the follow-up email if dismissed.

Moments to cover:
1. First paywall hit (feature gated on free plan)
2. Usage limit warning (at 80% of monthly cap)
3. Usage limit reached (hard block)
4. Team invite blocked (requires paid plan)
5. Export/integration blocked (premium feature)
6. 7-day streak (engagement peak — highest conversion probability moment)

## 5. PQL-to-Sales Handoff Intelligence
Design the complete sales handoff system:

**Routing Logic:**
- Hot PQL (80+ pts) AND company size 100+ employees → Senior AE within 4 hours
- Hot PQL (80+ pts) AND company size <100 employees → SDR email within 24 hours
- Warm PQL (60-79 pts) → Automated sequence, SDR review at day 7 if no conversion
- Team signals (5+ users active on free) → Enterprise AE notification regardless of score

**Handoff Data Package (auto-generated for every routed PQL):**
List the 15 data fields that should be passed to CRM/Slack including: usage summary, top features used, team size on platform, company enrichment data, pages visited, pricing page visits, trigger event that caused routing, recommended opening message

**First Outreach Template:**
Write a personalized first outreach email template that references actual product usage data. Include 3 variants based on the trigger signal.

## 6. Conversion Rate Optimization Experiments
Design 5 prioritized A/B tests with:
- Test name and hypothesis
- Control vs. variant
- Primary metric, secondary metric
- Minimum sample size for 95% confidence
- Expected lift and rationale
- ICE score (Impact 1-10, Confidence 1-10, Ease 1-10)

CONSTRAINTS:
- All automated touchpoints must be behavior-triggered, not time-based only
- Every email must have a single clear CTA — no multi-option confusion
- In-app messages must never block the user's current workflow entirely (use banners/tooltips, not full-screen modals for first occurrence)
- Include specific copy, not directions to "write compelling copy"
- All sequences must include suppression logic (stop when user converts)

## Example Input/Output

**Input Example:**

> Product: Screendesk — async video messaging for customer support teams
> Free tier: Freemium — up to 10 videos/month, 2 team members, no analytics
> Current metrics: 8,400 free signups/month, 2.8% conversion rate, 47 avg days to convert, ACV $4,800/yr
> Aha Moment: Customer support rep sends first video reply and ticket response time improves
> Top conversion blocker: "Teams don't see the need to upgrade until they have 3+ agents using it"
> ICP: Customer success leads and support managers at 50-500 person SaaS companies
> Stack: HubSpot, Customer.io, Segment, Amplitude

**Output Example (excerpt):**

---

**PQL Scoring Matrix for Screendesk:**

| Behavior | Points | Decay |
|---|---|---|
| Sends first video reply | 15 | Never |
| Invites a second team member | 12 | Never |
| Ticket closed with video reply (1st time) | 10 | Never |
| Hits 8/10 monthly video limit | 20 | 30 days |
| Clicks "Upgrade" on paywall (dismissed) | 18 | 14 days |
| Visits pricing page (2+ times) | 8 per visit | 7 days |
| Connects Zendesk or Intercom integration | 14 | Never |
| Views analytics dashboard (locked) | 12 | 14 days |
| Invites 3rd team member (blocked) | 25 | 30 days |
| Creates workspace subfolder | 8 | 21 days |

**Tier Thresholds:**
- Cold PQL: 40-59 pts → Intercom in-app tooltips only
- Warm PQL: 60-79 pts → Customer.io 5-email sequence, no human touch
- Hot PQL: 80+ pts → SDR Slack alert within 2 hours + immediate email from assigned rep

---

**7-Touch Nurture Sequence (Warm PQL — Team Invite Signal):**

**Day 0 — Team invite blocked event fires:**
*In-app banner:* "Looks like your team is growing. Add unlimited agents on Screendesk Pro — starting at $149/mo. [Start 14-day trial →]"

**Day 1 — Email:**
Subject: `[First Name], your team just hit a wall`
Preview: `Here's what Julia and 2 others are missing`
Body: `Hi [First Name], You invited [Collaborator Names] to Screendesk, but they're currently blocked on the free plan. Here's what they can't do: [List 3 features]. Companies like [Similar Company] upgraded to Pro when their teams hit this same point — and saw first-reply time drop 34%. [Start your 14-day Pro trial — no credit card required →]`

---

**Usage Limit Upgrade Trigger Copy (Screendesk, hitting 8/10 video limit):**

*Tooltip on video creation:*
**Headline:** "2 videos left this month"
**Body:** "You've sent 8 videos. Upgrade to Pro for unlimited videos and team analytics."
**CTA:** [Upgrade to Pro — $149/mo] [See what you'll unlock]

---

**PQL Handoff Template (SDR first outreach — team expansion trigger):**

Subject: `Re: Your Screendesk team`
Body:
`Hi [First Name],

I saw that you and [X] teammates have been using Screendesk together — you've already sent [N] videos this month, which puts you in the top 15% of our active teams.

A few of our customers at similar-sized CS teams ([Company A], [Company B]) told us the thing that unlocked value for them was getting the whole support org on the same video workflow — response times dropped ~40% in the first 30 days.

Would a 20-minute conversation about how you'd want to roll this out to your full team be worth your time?

[Book a 20-minute call →]

— [Rep Name]
Screendesk Growth Team"`

---

## Success Metrics

- **Primary:** Free-to-paid conversion rate (target: 5-10% within 90 days of activation)
- **PQL volume:** # of users reaching Hot PQL threshold per month
- **Time-to-convert:** Average days from free signup to first payment (target: <30 days from PQL designation)
- **Email sequence performance:** Open rate >35%, click rate >8%, reply rate >3% for hot PQL sequences
- **In-app CTR:** Paywall message click-through rate >15% (industry benchmark: 8%)
- **Sales-accepted PQL rate:** % of SDR-routed PQLs that become pipeline within 14 days (target: >40%)
- **Expansion rate:** % of Starter users upgrading within 90 days (target: >20%)
- **Suppression efficiency:** 100% of sequences stop within 24 hours of conversion

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-PLG-Flywheel-&-Viral-Loop-Design-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-PLG-Flywheel-&-Viral-Loop-Design-Engine.md) — Design the upstream PLG flywheel that feeds your PQL funnel
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-Revenue-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-Revenue-Engine.md) — End-to-end PLG revenue strategy
- [`../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md`](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md) — General lead scoring frameworks that complement PQL scoring
- [`../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Behavioral-Email-Trigger-Lifecycle-Automation-Engine.md) — Behavioral email triggers to power your nurture sequences

## Integration Tips

- **Segment + Amplitude/Mixpanel:** Set up event tracking for every PQL scoring behavior. Create Segment computed traits for PQL score and tier — these sync to HubSpot/Salesforce as contact properties automatically.
- **Customer.io / Klaviyo:** Build the PQL nurture sequences as behavioral campaigns with entry conditions tied to CRM contact properties. Use liquid templating to inject `{{user.last_feature_used}}`, `{{user.videos_sent}}`, and `{{user.team_invites}}` into email copy.
- **Intercom / Pendo:** Use in-app message rules to target users by PQL tier. Set frequency caps (max 1 upgrade message per 48 hours) to avoid fatigue. Intercom's "Goals" feature will auto-suppress when conversion fires.
- **HubSpot / Salesforce:** Create a "PQL" lifecycle stage between MQL and SQL. Set up automated tasks that trigger when a contact crosses 80 PQL points — assign to SDR with the usage summary attached as a note.
- **Slack:** Use Zapier or native integrations to send a Slack alert to the #hot-leads channel the moment a contact hits Hot PQL status. Include: company name, PQL score, trigger event, CRM link, and recommended first message template.
- **Stripe / Chargebee:** Webhook on first payment event to trigger suppression across all active nurture sequences within 5 minutes of conversion.

## Troubleshooting

**Problem: PQL score inflation — too many contacts reaching Hot tier, SDRs overwhelmed**
Solution: Add a recency multiplier — scores older than 21 days are worth 50% face value. Also add a firmographic filter: Hot PQL routing only fires for companies with 25+ employees (from Clearbit/ZoomInfo enrichment). All others stay in automated sequences.

**Problem: Email sequences have good open rates but zero conversions**
Solution: The offer isn't matched to the trigger. If a user hits the team-invite paywall, the email must be about team collaboration value — not generic product features. Audit each sequence's entry condition and ensure the email copy directly references the specific paywall they hit. Use Amplitude or Mixpanel to confirm which paywall events correlate with conversion, and rebuild sequences around those.

**Problem: Free users are converting but churning within 60 days (conversion without retention)**
Solution: Your activation sequence is converting on urgency/FOMO, not genuine value realization. Add a "Value Confirmation" email on Day 3 post-conversion that shows the user a personalized ROI snapshot: "Since upgrading, you've sent X videos, your team has [metric], here's what that's worth." This anchors retention to realized value, not the upgrade offer.

## Version History
- v1.0: Initial creation (auto-generated)
