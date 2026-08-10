# AI-Powered B2B SaaS Product-Led Growth Free-to-Paid Conversion & Self-Serve Expansion Revenue Intelligence Engine - Automate the Full PLG Flywheel from Free User to Expanding Customer

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** product-led growth, PLG, free-to-paid conversion, PQL, self-serve, expansion revenue, behavioral marketing, usage-based growth, product marketing, B2B SaaS

## Overview
Designs a fully autonomous PLG revenue engine that identifies product-qualified leads (PQLs) from behavioral signals, triggers personalized upgrade campaigns at peak conversion moments, and orchestrates expansion plays when usage limits and team growth patterns signal willingness to buy more. Use this when you have a free tier, freemium model, or trial offering and need to systematically convert self-serve users to paid customers — and existing paid customers to higher tiers — without relying on sales intervention.

## Quick Copy-Paste Version

You are a Product Marketing expert specializing in product-led growth for B2B SaaS companies. Design a complete PLG conversion and expansion revenue system that uses product usage signals to automatically identify ready-to-convert users, deploy the right upgrade message at the peak psychological moment, and orchestrate expansion campaigns when accounts show growth signals — all without requiring a sales rep to initiate.

COMPANY CONTEXT:
- Company: [e.g., "Canopy — AI-powered project management platform for agency teams"]
- Free tier / trial model: [e.g., "Free tier: up to 3 users, 5 active projects, 2GB storage. Paid tiers: Team ($19/seat/mo), Business ($45/seat/mo), Enterprise (custom)"]
- Current free-to-paid conversion rate: [e.g., "3.8% of free accounts convert within 90 days"]
- Average time to convert: [e.g., "42 days from signup to first paid seat"]
- Top expansion trigger: [e.g., "Accounts hitting the 3-user limit or 5-project limit have 4.2x higher conversion probability"]
- Tech stack: [e.g., "Segment for event tracking, Amplitude for analytics, Customer.io for behavioral email, Appcues for in-app messaging, Stripe for billing, HubSpot CRM for PQL routing"]
- Self-serve vs sales-assisted: [e.g., "Pure self-serve for Team tier. Business tier = 60% self-serve, 40% sales-assisted for >10 seats. Enterprise = full sales motion"]

THREE CONVERSION BARRIERS TO SOLVE:
1. TIMING BARRIER — Upgrade prompt shown at wrong moment (during setup frustration vs. peak success moment)
2. FRICTION BARRIER — Too many steps, unclear pricing, or no urgency to upgrade now vs. later
3. VALUE REALIZATION BARRIER — Free user hasn't experienced enough value to justify paying

OUTPUT REQUIRED:
1. PQL SCORING MODEL: Behavioral signals that predict upgrade readiness — which events, thresholds, and frequency patterns separate converters from churners
2. CONVERSION TRIGGER LIBRARY: 8-12 specific in-product moments where upgrade prompts should fire, with the exact psychological trigger for each
3. UPGRADE CAMPAIGN COPY: Full message templates for each trigger — in-app modal, email, push notification — with A/B variants
4. EXPANSION PLAYBOOK: How to identify accounts ready to expand to higher tiers or add seats, with automated outreach sequences
5. SALES HANDOFF PROTOCOL: When to route a self-serve PQL to a sales rep vs. keep fully automated, including the enrichment data to pass
6. MEASUREMENT FRAMEWORK: Conversion funnel metrics, revenue attribution, and experiment design to optimize each conversion touchpoint

## Advanced Customizable Version

ROLE: You are a senior Product Marketing Manager with 13+ years building PLG revenue engines at B2B SaaS companies including pure self-serve tools, freemium platforms, and hybrid PLG+sales organizations. You have personally designed PQL scoring systems that improved free-to-paid conversion by 60-120%, built in-app upgrade flows generating $2M–$8M ARR from fully automated self-serve revenue, and architected expansion programs that drove NRR above 120% by intercepting growth signals before account contacts requested upgrades. You think in activation cohorts, conversion events, and expansion triggers — not email campaigns. You know that the best PLG conversion moment is the one that coincides with a customer's "peak success" experience, not a calendar anniversary or arbitrary trial day.

OBJECTIVE: Design a production-ready PLG revenue system that:
- Builds a PQL scoring model from first-principles behavioral data (events, milestones, frequency, depth) that identifies accounts with 3x+ higher upgrade probability
- Creates a conversion trigger library tied to specific product moments — not time-based drips — so upgrade prompts fire when value has been demonstrated
- Deploys personalized upgrade experiences by persona, team size, and use case — not one-size-fits-all paywalls
- Orchestrates expansion plays when existing paid accounts show seat demand, usage ceiling pressure, or team growth signals
- Determines programmatically when to keep a conversion fully automated vs. route to a sales rep for a human assist
- Instruments every touchpoint with experiment infrastructure so you can optimize conversion rates continuously

---

COMPANY PROFILE:
- Company name & product: [name + one-sentence description of what the product does]
- Business model: [freemium / free trial / reverse trial / usage-based — be specific about what's free and what's gated]
- Free tier constraints: [exact limits — seats, usage, features — that create natural upgrade pressure points]
- Pricing tiers: [tier names, prices, and what unlocks at each tier]
- Current ARR: [range — e.g., "$6M–$20M ARR self-serve, $8M enterprise"]
- Stage: [Seed–Series C — affects resource allocation for self-serve vs. sales-assisted motion]
- GTM motion: [pure self-serve / PLG + sales assist / product-led sales]
- Monthly free signups: [e.g., "3,200 new free accounts/month"]
- Current free-to-paid conversion rate: [e.g., "4.1% within 90 days of signup"]
- Average days to convert: [e.g., "38 days — but top quartile converts in 11 days"]
- Current NRR: [e.g., "108% — but 94% for self-serve cohort vs. 127% for sales-assisted"]
- Primary expansion motion: [seat expansion / usage-based / feature tier upgrades]

---

ACTIVATION & CONVERSION SIGNAL MAPPING:

Map the customer's journey from signup to expansion with specific behavioral events:

**Step 1 — Aha Moment Identification:**
Define 3 candidate "aha moments" — specific in-product events that correlate most strongly with long-term retention:
- Aha Moment 1: [e.g., "User completes first project with team collaboration — invites 2+ teammates and marks first milestone complete within session"]
- Aha Moment 2: [e.g., "User runs first automated report and shares output externally (client PDF export)"]
- Aha Moment 3: [e.g., "User creates recurring workflow template and schedules automated task assignments"]

Rank these by correlation to 90-day retention (you'll need Amplitude/Mixpanel cohort analysis to validate).

**Step 2 — PQL Scoring Model:**
Build a behavioral scoring system using these signal categories:

| Signal Category | Signal | Weight | Threshold |
|----------------|--------|--------|-----------|
| Depth | Core feature uses per week | High | ≥7 uses/week = PQL trigger |
| Breadth | Features touched | Medium | ≥4 of 8 core features used |
| Team | Teammates invited | High | ≥2 invites sent AND accepted |
| Limits | % of tier limit consumed | Critical | ≥80% of any limit = immediate trigger |
| Recency | Days since last login | Inverse | >7 days = deactivation risk |
| Intent | Pricing page visits | High | ≥2 pricing page visits in 14 days |
| Intent | Upgrade button clicks (without converting) | Critical | Any = immediate PQL |

PQL threshold: Account reaches [X] total points within [Y] days of signup. Route to:
- Score ≥80 + team size ≥3: Sales-assisted (AE outreach within 4 hours)
- Score ≥60 + self-serve eligible: Automated upgrade sequence
- Score ≥40 + early in trial: Nurture sequence with value-demonstration content
- Score <40 after 30 days: Re-engagement or graceful offboarding

**Step 3 — Conversion Trigger Library:**
For each trigger, define: the event, the channel, the message angle, and the CTA.

TRIGGER 1 — LIMIT APPROACH (Highest urgency):
- Event: User or team reaches 80% of any free tier limit (seats, projects, storage, API calls)
- Channel: In-app banner + email within 2 hours
- Psychological angle: Loss aversion + continuity ("You're about to hit your project limit — your team is building momentum, don't stop now")
- Message: "You've used 4 of your 5 free projects. Your team is on a roll — upgrade to unlimited projects and keep the momentum going. [Upgrade now — takes 60 seconds]"
- A/B variant: Show the specific ROI of the work done so far ("You've completed 47 tasks across 4 projects this month")

TRIGGER 2 — FIRST AHA MOMENT (Highest conversion potential):
- Event: User completes their defined aha moment action for the first time
- Channel: In-app celebration modal (non-blocking) + follow-up email within 1 hour
- Psychological angle: Peak-end rule — capture upgrade intent at the peak satisfaction moment
- Message: "You just [specific achievement]. Teams that [aha moment description] grow 3x faster with [Product]. See what's possible with [next tier] → [CTA]"
- Timing: Fire within the session, before the user exits the product

TRIGGER 3 — TEAM INVITATION ACCEPTANCE:
- Event: Invited teammate accepts invitation and completes first action
- Channel: Email to account owner within 30 minutes
- Psychological angle: Social proof + investment ("Your team is joining — give them the full experience")
- Message: "[Teammate name] just joined your workspace. As your team grows, you'll want [feature unlocked at next tier]. Upgrade now and get [specific benefit] for every team member."

TRIGGER 4 — PRICING PAGE INTENT SIGNAL:
- Event: User visits pricing page 2+ times in 7-day window without converting
- Channel: In-app chat message + personalized email within 4 hours
- Psychological angle: Reduce purchase anxiety — they want to buy but something is blocking them
- Message: "Looks like you're exploring plans. What questions can I answer? Most teams in [industry/use case similar to theirs] choose [recommended tier] because [specific reason]. Happy to walk you through it → [Book 15 min] or [Start free trial of paid plan]"

TRIGGER 5 — POWER USER EMERGENCE:
- Event: Single user logs in 5+ days in 7-day period AND uses 6+ features
- Channel: In-app tooltip + email to the power user (not just admin)
- Psychological angle: Identity-based persuasion ("You're one of our most engaged users")
- Message: "You're getting serious value from [Product]. Power users like you unlock [specific advanced feature] on [next tier] — it's designed for exactly how you're working. [Start your upgrade] — takes 2 minutes."

TRIGGER 6 — COLLABORATION DEMAND:
- Event: User attempts to invite a teammate beyond the free seat limit
- Channel: Immediate in-app modal (blocking — can't complete action without acting)
- Psychological angle: Blocked momentum + social commitment ("Your teammate is waiting")
- Message: "You've hit the 3-user limit. [Invitee's name] is waiting to join your workspace. Upgrade to [next tier] for unlimited team members — or start a 14-day full-access trial right now."
- CTA: [Upgrade Now — $X/month] [Start Free Trial of Business Plan]

TRIGGER 7 — EXPORT/SHARE INTENT:
- Event: User attempts to export to an integration or format that requires a paid plan
- Channel: In-app gate modal
- Psychological angle: Completion drive — they're in the middle of a task
- Message: "PDF export with your branding is available on [next tier]. You're one step from sending this to [client/stakeholder]. Upgrade now and send it in 60 seconds."

TRIGGER 8 — RENEWAL SIGNAL FOR ANNUAL DISCOUNT:
- Event: Monthly paid account reaches 90-day mark with healthy usage
- Channel: Email + in-app notification
- Psychological angle: Savings + commitment
- Message: "You've been consistent for 90 days — teams like yours save $[X] by switching to annual billing. Lock in your rate and get [bonus feature or seats] free for the first year."

---

EXPANSION PLAYBOOK:

For existing paid accounts, monitor these expansion signals:

**Seat Expansion Signals:**
- New employee hires in ATS/LinkedIn data matching ICP role (via enrichment tool like Clearbit, 6sense)
- Account adds 3+ seats in 30 days → SDR outreach for volume discount conversation
- Usage per seat rising above 85% capacity → proactive outreach before pain is felt
- Manager-level user creates 3+ sub-teams → signal of organizational adoption spread

**Tier Expansion Signals:**
- Mid-market account consistently hitting API rate limits
- Account using workarounds documented in support tickets for features in next tier
- Power user requesting feature in support chat that exists in Enterprise tier
- Admin runs pricing page comparison with Enterprise column 2+ times

**Expansion Campaign Sequence (Automated):**
1. Day 0: Trigger fires → Personalized in-app notification to account admin
2. Day 0+2hr: Email to admin with specific usage data showing the expansion need
3. Day 3: CSM alert (if account has CSM) with expansion play brief
4. Day 7: Follow-up email if no response — include peer benchmark ("Similar teams at [company stage] typically [action]")
5. Day 14: SDR outreach if high-value account (>$15K ARR potential); else continue automated sequence
6. Day 21: Final automated touch with urgency (end of quarter pricing, limited-time offer)

---

SALES HANDOFF PROTOCOL:

Route to sales when:
- PQL score ≥80 AND company size ≥50 employees (enrichment via Clearbit/Apollo)
- Self-serve account reaches $500+/month on usage-based billing
- Account has 10+ seats and admin visits enterprise pricing page
- Support ticket contains phrases: "security review," "SSO," "SOC 2," "custom contract," "procurement"
- Free account with Fortune 1000 domain signs up (flag immediately)

Data to pass to sales at handoff:
- Activation milestones completed (in Salesforce custom fields)
- PQL score breakdown (which signals triggered handoff)
- All product usage metrics (Amplitude link)
- Account enrichment (company size, industry, funding, tech stack from Clearbit)
- All prior marketing touches (email opens, page visits, content downloaded)
- Recommended opener based on their usage pattern (auto-generated by AI from playbook templates)

Sales SLA: Contact within 4 hours of handoff during business hours. Automated SMS alert to AE.

---

MEASUREMENT FRAMEWORK:

**Free-to-Paid Conversion Funnel:**
- Signup → Activation Rate (complete aha moment within 7 days): Target ≥35%
- Activated → PQL Rate (reach scoring threshold within 30 days): Target ≥25%
- PQL → Converted (upgrade within 14 days of PQL designation): Target ≥40%
- Overall Free-to-Paid Conversion (90-day cohort): Target ≥8%

**Expansion Revenue Metrics:**
- Net Revenue Retention (NRR): Target ≥115% for self-serve cohort
- Expansion MRR as % of total new MRR: Target ≥30%
- Average Account ARR Growth Rate at 12 months: Target ≥25% for expanded accounts
- Seat expansion triggered by automated signal vs. sales-initiated: Track ratio

**Experiment Infrastructure:**
Run 3 concurrent A/B tests at all times across:
1. Conversion trigger timing (immediate vs. +2hr delay vs. next login)
2. Message framing (benefit-led vs. limit-focused vs. social proof)
3. CTA design (single CTA vs. two-option CTA — [Upgrade] vs. [Upgrade / Start paid trial])

Minimum sample per variant: 500 accounts. Statistical significance threshold: 95%.

---

INTEGRATION SPECIFICATIONS:

| System | Role in PLG Engine | Key Events/Data |
|--------|-------------------|-----------------|
| Segment | Event pipeline backbone | All product events → downstream tools |
| Amplitude | Behavioral analytics + cohort analysis | PQL score inputs, funnel analysis |
| Customer.io | Behavioral email automation | Trigger-based sequences, expansion emails |
| Appcues/Pendo | In-app messaging & modals | Upgrade prompts, onboarding tooltips |
| Stripe | Billing + upgrade flow | Self-serve upgrade completion, MRR data |
| Clearbit | Account enrichment | Company size, industry for PQL routing |
| HubSpot/Salesforce | CRM + PQL handoff | Sales handoff data package |
| Slack | Internal alerts | PQL notifications to sales Slack channel |

---

OUTPUT FORMAT: Deliver the following as a production-ready PLG playbook:
1. PQL Scoring Model with weights, thresholds, and routing logic (table format)
2. Conversion Trigger Library (8-12 triggers with full message copy, A/B variants, channel specs)
3. Expansion Signal Taxonomy with automated sequence details
4. Sales Handoff Protocol with enrichment data spec
5. Measurement Framework with target benchmarks
6. 90-Day Implementation Roadmap (prioritized by revenue impact)

## Example Input/Output

**Example Input:**
- Company: Notation — AI-powered meeting intelligence platform for RevOps and sales teams
- Free tier: 3 users, 10 meetings/month recorded, basic transcription only
- Paid tiers: Starter $29/seat/mo (unlimited meetings, AI summaries), Pro $59/seat/mo (CRM sync, deal intelligence), Enterprise custom (SSO, admin controls, custom AI models)
- Current free-to-paid conversion: 3.1% in 90 days
- Monthly free signups: 2,100
- Primary expansion signal: Teams adding new reps → new seat demand
- Tech stack: Segment, Mixpanel, Customer.io, Intercom, HubSpot CRM, Stripe

**Example Output Excerpt:**

*PQL Scoring Model:*

| Signal | Event Name | Score | Notes |
|--------|------------|-------|-------|
| 10 meetings recorded | `meeting.recorded` count ≥10 | +30 | Hits monthly free limit — strongest signal |
| CRM sync attempted | `integration.crm_connect_attempt` | +25 | Intent to use Pro feature — gate creates PQL |
| 3+ team invitations sent | `user.invite_sent` count ≥3 | +20 | Team adoption = expansion surface |
| AI summary shared externally | `summary.shared_external` | +15 | Demonstrating value to stakeholders |
| Pricing page 2+ visits | `page.pricing_view` count ≥2 in 14d | +15 | Conscious consideration |
| Deal intelligence feature click | `feature.deal_intelligence_click` | +10 | Pro feature discovery |

PQL threshold: 50 points → automated sequence. 75+ points + company ≥20 employees → sales handoff.

*Trigger 1 — Meeting Limit Approach (fires at 9/10 meetings):*
- In-app banner: "You've recorded 9 of 10 meetings this month. Your team relies on these insights — don't lose momentum at month end. [Upgrade to Starter — $29/seat]"
- Email subject: "Your last free meeting is coming up"
- Email body: "Your team recorded 9 meetings this month in Notation — that's 9 deals better documented, 9 calls easier to coach from. At 10, you'll hit the free limit. Upgrade to Starter for $29/seat and record every call your team has, forever. [Upgrade now →]"

*Aha Moment Trigger (fires after first AI summary shared externally):*
- In-app modal: "Your first Notation summary just landed in someone's inbox. Teams that share AI summaries externally close deals 22% faster. With Pro, every summary auto-syncs to HubSpot with deal stage context. [See Pro features →] [Upgrade to Pro — $59/seat]"

## Success Metrics

The PLG engine is working when you see:
- **Free-to-paid conversion rate ≥6%** within 90 days of signup (vs. typical 2-5% baseline)
- **PQL-to-paid conversion ≥35%** within 14 days of PQL designation
- **Expansion MRR ≥25% of total new MRR** (self-serve expansion reducing CAC)
- **NRR ≥115%** for the self-serve cohort (vs. <100% typical for unmanaged free users)
- **Time-to-upgrade reduced by ≥30%** vs. non-triggered cohort baseline
- **Sales-assisted close rate on routed PQLs ≥45%** (vs. cold outbound at 8-15%)

Review these metrics weekly. If free-to-paid conversion is below target, diagnose using funnel drop-off: Signup → Activation is the most common leak (fix onboarding), not PQL → Convert.

## Related Prompts

- [`AI-Powered-B2B-SaaS-Feature-Adoption-Campaign-Architecture-&-Product-Led-Retention-Intelligence-Engine.md`](./AI-Powered-B2B-SaaS-Feature-Adoption-Campaign-Architecture-&-Product-Led-Retention-Intelligence-Engine.md) — Driving existing paid customers to adopt features for retention
- [`AI-Powered-B2B-SaaS-New-Customer-Product-Activation-Sprint-&-First-Value-Moment-Marketing-Intelligence-Engine.md`](./AI-Powered-B2B-SaaS-New-Customer-Product-Activation-Sprint-&-First-Value-Moment-Marketing-Intelligence-Engine.md) — First-value-moment marketing for new customers
- [`../../02_Product-Marketing/Sales-Enablement-Content/POC-Free-Trial-Conversion-Intelligence-Engine.md`](../../02_Product-Marketing/Sales-Enablement-Content/POC-Free-Trial-Conversion-Intelligence-Engine.md) — Converting trial users via sales-assisted POC process
- [`../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md) — CRO for free trial activation funnels
- [`../../05_Analytics-&-Performance/Product-Adoption-Analytics/AI-Powered-B2B-SaaS-Product-Engagement-Scoring-&-User-Behavioral-Intelligence-Analytics-Engine.md`](../../05_Analytics-&-Performance/Product-Adoption-Analytics/AI-Powered-B2B-SaaS-Product-Engagement-Scoring-&-User-Behavioral-Intelligence-Analytics-Engine.md) — Product engagement scoring and behavioral analytics

## Integration Tips

- **Segment + Customer.io**: Use Segment's Destination Functions to route PQL score updates to Customer.io as user traits. Customer.io segments fire behavioral email sequences based on score thresholds — no manual list management needed.
- **Amplitude → HubSpot**: Set up Amplitude Cohorts to sync PQL cohorts directly to HubSpot contact lists. Sales reps see "PQL - High Score" as a contact property and can filter their outreach queue without leaving HubSpot.
- **Stripe Billing Events**: Connect Stripe webhooks to Segment to track self-serve upgrades as conversion events. This closes the attribution loop between marketing triggers and revenue — essential for calculating trigger-level ROI.
- **Intercom / Appcues in-app messages**: Trigger upgrade modals using Segment events so they fire based on behavior (event-based) rather than page loads (page-based). Event-based triggers have 2-4x higher engagement rates.
- **Notion / Confluence**: Document your PQL scoring model and trigger library in a shared internal wiki so Product, CS, and Sales teams can see what automated messages a customer has received — prevents double-outreach conflicts.
- **Slack Alerts**: Use Zapier or Make to pipe HubSpot PQL designation events to a #plg-pqls Slack channel. Include company name, size, PQL score, and recommended play. Sales reps can claim accounts instantly without logging into CRM.

## Troubleshooting

**Problem: Free-to-paid conversion rate is below 3% despite triggers firing.**
*Fix:* Run a funnel analysis from Signup → Activation. If <20% of free users complete the aha moment, the conversion rate will always be low — you're triggering upgrade prompts before users have experienced enough value. Focus first on improving activation rate (onboarding optimization, better in-app guidance) before optimizing conversion triggers. Conversion optimization only works after activation is strong.

**Problem: Upgrade triggers are firing but users are ignoring them.**
*Fix:* Check the timing — most teams fire too early (day 3 of signup, before value is demonstrated) or too late (day 45, when inertia sets in). The highest-converting triggers fire within 30 minutes of a success event, not on a schedule. Audit your trigger library: every trigger should be tied to a specific product event, not a time-based drip. If all triggers are time-based, rebuild them as event-based.

**Problem: PQL routing is sending too many low-quality leads to sales.**
*Fix:* Add enrichment scoring to the routing decision. A PQL from a 5-person startup should not receive the same sales treatment as a PQL from a 200-person company even if behavioral scores are equal. Add a company size multiplier (Clearbit enrichment) to your routing threshold — require both a behavioral score AND minimum company size for sales handoff. Sales-qualified PQLs convert at 45%+; enrichment-only routing converts at 12-18% and wastes AE time.

## Version History
- v1.0: Initial creation (auto-generated)
