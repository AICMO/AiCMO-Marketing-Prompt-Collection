# AI-Powered B2B SaaS PLG In-App Behavioral Activation & Product-Usage-Triggered Revenue Campaign Intelligence Engine - Convert Product Behavior Into Upgrade Revenue Through Automated, Signal-Driven Campaigns

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, saas, plg, product-led-growth, in-app, behavioral-marketing, activation, upgrade, automation, revenue-expansion

## Overview
Takes raw product usage data — activation milestones, feature engagement patterns, usage limits, collaborative triggers, and abandonment signals — and generates a complete in-app and out-of-app behavioral marketing campaign system that autonomously converts free/trial users into paying customers and expands existing accounts without requiring manual SDR intervention. Designed for teams running Appcues, Pendo, Intercom, Braze, Customer.io, or any behavior-triggered marketing stack.

## Quick Copy-Paste Version

You are an expert PLG (Product-Led Growth) marketing strategist who specializes in behavioral trigger campaigns for B2B SaaS. I need to build an automated campaign system that converts product usage signals into upgrade and expansion revenue.

PRODUCT CONTEXT:
- Product name and one-line description: [e.g., "Clarix — a collaborative document automation platform for legal and finance teams"]
- Pricing model: [Freemium / Free trial (days: ___) / Usage-based / Reverse trial]
- Primary activation milestone (the "aha moment"): [e.g., "User creates their first automated document template and shares it with a teammate"]
- Key features locked behind paid plan: [list 2-4]
- Current free-to-paid conversion rate: [e.g., "4.2%"]
- Average days from signup to upgrade (for users who do convert): [e.g., "18 days"]
- Primary ICP persona using the product: [e.g., "In-house legal counsel and operations managers at 100-500 person companies"]

BEHAVIORAL SIGNALS AVAILABLE (check what you can track):
- [ ] First login / account creation
- [ ] Activation milestone reached (aha moment)
- [ ] Feature limit approached (e.g., used 8 of 10 free documents)
- [ ] Collaboration trigger (e.g., user invites a teammate)
- [ ] High-frequency usage (e.g., logged in 5+ times in 7 days)
- [ ] Feature discovery gap (e.g., active user who has never used Feature X)
- [ ] Dormancy signal (e.g., no login in 14 days after activation)
- [ ] Upgrade page visit without conversion
- [ ] Integration attempt (tried to connect a paid integration)

Generate the following campaign assets for each behavioral signal checked above:
1. In-app message (tooltip/modal/banner) — trigger condition, headline, body, CTA
2. Triggered email — subject line, preview text, full body copy, CTA
3. Upgrade prompt sequence — what to show if they dismiss the first prompt
4. Slack/Teams push notification (if applicable)
5. A 30-60-90 day behavioral trigger map showing when each campaign fires

## Advanced Customizable Version

ROLE: You are a senior PLG marketing architect with 14+ years building product-led revenue systems for B2B SaaS companies at the intersection of product, marketing, and revenue operations. You've helped companies like those using Segment, Amplitude, Mixpanel, and Heap translate raw event data into revenue-generating behavioral campaigns. You understand that PLG marketing is not "email marketing for free users" — it's a precision system that fires the right message at the moment a user has just demonstrated intent, capability, or friction. You apply Nir Eyal's Hook Model (trigger → action → variable reward → investment) to design habit loops that make upgrading feel like the natural next step, not a sales pitch. You use JTBD (Jobs-to-be-Done) to connect the specific moment of product behavior to the user's underlying progress goal — so your in-app messages feel helpful, not promotional. Every campaign you design can run end-to-end without a human touching it.

---

PRODUCT & BUSINESS CONTEXT:

*Product Architecture:*
- Product name and category: [e.g., "Clarix — collaborative document automation for legal and finance teams"]
- Pricing model: [Freemium / Free trial with days / Usage-based / Reverse trial / Hybrid]
- Free tier limits: [e.g., "10 documents/month, 1 user, no integrations, no audit trail"]
- Paid plan entry point: [e.g., "Starter: $49/month — 50 docs, 3 users, 2 integrations, basic audit trail"]
- Growth/Team plan: [e.g., "Growth: $149/month — unlimited docs, 10 users, unlimited integrations, full audit trail + e-sign"]
- Primary activation milestone (the aha moment): [e.g., "User creates their first automated template AND shares it with at least one teammate — this is the moment retention jumps from 30% to 71%"]
- Secondary activation milestones: [e.g., "Connected a data source (CRM/spreadsheet); Downloaded first completed document; Used a pre-built template"]

*Conversion & Retention Benchmarks:*
- Current free-to-paid conversion rate: [e.g., "4.2%"]
- Activation rate (% of signups who hit aha moment): [e.g., "31%"]
- D7 retention for activated vs. non-activated users: [e.g., "71% vs. 18%"]
- Average days to upgrade for converters: [e.g., "18 days"]
- Top 3 reasons users cite for not upgrading (from churned user surveys): [e.g., "Don't need more than 10 docs/month yet, Can't get team buy-in, Price feels high before I've proven value internally"]
- Top 3 reasons users cite for upgrading (from upgrade survey or CS interviews): [e.g., "Hit the document limit, Needed to add teammates, Wanted the audit trail for compliance"]

*ICP Persona Profile (the user running the product):*
- Primary persona: [e.g., "Legal Operations Manager — responsible for contract workflow efficiency, reports to GC or COO"]
- Secondary persona: [e.g., "Finance Controller — uses it for financial reporting templates and board prep automation"]
- Their primary job-to-be-done: [e.g., "Turn repetitive, error-prone manual document work into a reliable, repeatable system their team can run without them"]
- Emotional state when they first sign up: [e.g., "Hopeful but skeptical — they've tried other tools that didn't stick. They need to see a win fast or they'll deprioritize."]
- What success looks like to them in 30 days: [e.g., "Their team is using it independently, documents are getting done faster, and they haven't had to manually edit a template in 2 weeks"]

*Tech Stack & Integration Environment:*
- Product analytics platform: [Amplitude / Mixpanel / Heap / Segment / PostHog / Custom]
- In-app messaging tool: [Appcues / Pendo / Intercom / Chameleon / Custom]
- Marketing automation platform: [HubSpot / Marketo / Customer.io / Braze / Iterable / Klaviyo]
- CRM: [Salesforce / HubSpot CRM / Pipedrive]
- Available event data from product: [list the key events you track, e.g., "document_created, template_saved, teammate_invited, integration_connected, export_downloaded, upgrade_page_viewed, limit_approaching"]

---

BEHAVIORAL CAMPAIGN ARCHITECTURE:

**Module 1 — Activation Campaigns (Drive Users to the Aha Moment)**

*Target: New signups who have NOT yet hit the activation milestone*
*Window: Days 0-14 post-signup*

For each activation stage below, generate a complete campaign:

*1A — Day 0-2: Fast-Start In-App Onboarding Campaign*

Trigger condition: User completes signup but has not created their first document/template within 48 hours.

Generate:
- Welcome modal (shown on login Day 1 if no key action taken):
  - Headline: Progress-framed, not feature-framed (e.g., "You're 3 steps from your first automated document")
  - Body: What they'll be able to do, not what the product does — frame it as the job they hired the product for
  - CTA: Single, specific action (not "Explore the Product") — e.g., "Start with a template" → opens template gallery
  - Dismissal handling: If dismissed, reappear on Day 3 login with a different angle

- Activation email (sent 24 hours post-signup if activation milestone not reached):
  - Subject line (3 variants): [Progress-framed / Social proof / Low-stakes / Fear of missing out]
  - Preview text: Complement the subject — doesn't repeat it
  - Body structure:
    - Opening line: Start with the outcome they came for, not "Welcome to [Product]"
    - The 3-step path: Make activation feel achievable in under 10 minutes
    - Social proof: "Teams like yours complete this in [X minutes] on average" or equivalent peer reference
    - CTA: Deep link directly to the activation step they need to take — not the homepage
  - If no response, Day 3 follow-up: Different angle, shorter, more direct

- In-app tooltip sequence (contextual, appears during product interaction):
  - Tooltip 1: Appears when user hovers over or reaches the first step — explains the "why" before the "how"
  - Tooltip 2: Appears at the second friction point (where users most commonly abandon) — validation that they're doing it right
  - Tooltip 3: Appears immediately after the activation milestone is hit — celebrates the achievement and shows what's unlocked next (creates anticipation for what's next)

*1B — Day 3-7: Re-Engagement for Stalled Signups*

Trigger condition: User logged in at least once but has NOT hit activation milestone AND has not logged in for 3+ days.

Generate:
- Re-engagement in-app message (shown on their next login):
  - Tone: Empathetic, not pushy — acknowledge that they got busy, not that they failed
  - Show a "pick up where you left off" experience if possible
  - Headline options that don't sound like a re-engagement email (3 variants)

- Re-engagement email:
  - Subject: Something that makes them curious, not guilty (3 variants)
  - Body: A customer story or peer benchmark — "Teams in [their industry] using [product] for [use case] typically see [result] in their first week"
  - CTA: Lower friction than activation — something they can accomplish in 2 minutes, not 20

*1C — Activation Milestone Celebration (The Inflection Moment)*

Trigger condition: User has just hit the primary activation milestone.

This is the most important moment in the PLG funnel — this is when habit is forming. Do not send a generic "Congrats!" message.

Generate:
- In-app celebration modal:
  - Acknowledge the specific achievement using the actual action they took (pull their data if possible — "You just created your first automated contract template")
  - Show them what's now possible that wasn't possible before — open the door to the next value layer
  - Soft upgrade teaser: Don't pitch yet — just show a glimpse of what the next level unlocks ("When your team is ready to [advanced use case], Starter gives you...")
  - No CTA to upgrade — this is a trust moment, not a conversion moment

- Celebration email (sent within 1 hour of milestone):
  - Subject: [First name], you just did something most users never do
  - Body: Personalize to their exact achievement. Make them feel like a power user. Reference what % of users reach this milestone (even if invented: "Only 31% of signups ever get here — you're already ahead")
  - Forward-looking: "What users who reach this stage typically do next" — behavioral breadcrumb toward deeper engagement

---

**Module 2 — Upgrade Trigger Campaigns (Convert Activated Users to Paid)**

*Target: Users who have hit activation milestone but have not upgraded*
*Window: Days 3-45 post-activation*

*2A — Limit-Approaching Campaign*

Trigger condition: User has consumed 70%, 85%, and 95% of their plan limit (document count, seat count, API calls, etc.) — three escalating touchpoints.

For each threshold, generate:

**70% Limit Warning (soft, educational tone):**
- In-app banner (non-blocking):
  - Copy that frames the limit as progress, not restriction: "You've created 7 of your 10 free documents — you're clearly getting value from this"
  - Upgrade preview: Show what Starter unlocks without hard-selling it
  - No CTA to buy yet — CTA is "See what Starter includes" → opens upgrade comparison page

- Triggered email:
  - Subject: "You're 3 documents from your limit — here's what's on the other side"
  - Body: Lead with what they've accomplished (evidence they're a power user), bridge to what the limit means for their momentum, show the upgrade path as "continuing what you've started"
  - CTA: "See Starter plan" — not "Upgrade Now"

**85% Limit Warning (motivational, urgency-building tone):**
- In-app modal (mildly blocking — shows once, dismissible):
  - Lead with the velocity: "You've used 8.5 of your 10 documents in just [X days] — that's faster than 80% of users who stay on the free plan"
  - Show the cost of stopping vs. the cost of upgrading
  - Upgrade CTA with social proof: "[X] teams upgraded this week"

**95% Limit Warning (direct, action-required tone):**
- In-app modal (blocking — requires action):
  - Be direct: "You have 1 document left on your free plan"
  - Two options: Upgrade (primary CTA) + "Download my work and pause" (secondary — preserves trust)
  - Show upgrade cost in per-document terms: "$49/month = $0.98 per document at 50/month vs. blocking your workflow"

*2B — Collaboration Trigger Campaign*

Trigger condition: Activated user invites a teammate OR a teammate accepts an invitation (high-intent signal — they're embedding the product in their team's workflow).

Generate:
- In-app message (shown to the admin/inviter within the session they triggered the invite):
  - Headline: "Your team just got access — here's what they can (and can't) do on the free plan"
  - Body: Show the team permissions table — not as a limitation, as a transparency play
  - CTA: "Unlock full team features" with the specific features that matter to the inviter role
  - Urgency without pressure: "Your team's experience depends on what plan you're on — here's the difference"

- Triggered email to inviter (sent 2 hours post-invite acceptance):
  - Subject: "[Teammate name] just joined — here's how to set them up for success"
  - Body: 
    - Open with the positive signal: Their team is adopting
    - Show the free plan team limitations concretely (invite-able users, permissions, shared features)
    - Upgrade frame: "For teams doing [their use case], the Growth plan removes [specific friction]"
    - CTA: "Upgrade before [teammate name] hits the free plan walls"

*2C — High-Frequency Power User Campaign*

Trigger condition: User has logged in 5+ times in a 7-day window and has NOT upgraded (they're clearly getting value — time to show what more looks like).

Generate:
- In-app experience (not an interstitial — woven into their active session):
  - Style: A "You've been active" insight card in their dashboard
  - Content: Behavioral mirror — show them their own usage data ("You've created 6 documents and saved [estimated X hours] this week")
  - Power user validation: Frame them as a power user category — "Users as active as you typically upgrade to unlock [feature] within [timeframe]"
  - Non-pushy upgrade path: "If you're finding yourself limited by [specific constraint they've hit], [paid feature] was built for that"

- Email (send on Day 7 of the active streak, only if no upgrade):
  - Subject: "You've been busy — what most power users do next"
  - Body: 
    - Mirror their activity back to them (use behavioral data)
    - Introduce a feature they haven't used yet that's available on their current plan (first — show there's more free value to explore)
    - Then: Introduce the paid feature most correlated with long-term power user retention
    - CTA: [Try the advanced feature free for 7 days / See Growth plan] — depending on trial availability

*2D — Feature Discovery Gap Campaign*

Trigger condition: User has been active 10+ days and has never used a specific high-value feature (integration, collaboration, export, advanced template) that is available on their current plan.

Generate:
- In-app contextual hint (appears when user is in the relevant workflow area):
  - "Did you know you can [feature description] from here?" — make it a discovery, not a tutorial push
  - One-click to activate: Don't require them to find documentation

- Email campaign (if in-app hint was dismissed or not seen within 5 days):
  - Subject: "Most [user role] on [product] use this — you haven't tried it yet"
  - Body: Short, specific — one feature, one outcome, one step to try it
  - Goal: Drive them to use the free feature first, because features discovered during the free plan increase paid conversion by 2-3x

*2E — Upgrade Page Abandon Campaign*

Trigger condition: User visited the pricing/upgrade page but did NOT convert (high-intent signal — they were considering it).

Generate:
- In-app message (shown on their NEXT login if they haven't upgraded):
  - Tone: Helpful, not salesy — acknowledge they were researching
  - Address the most common objection for their persona without asking what the objection is
  - Offer a new value hook they may not have seen: a use case, a customer story, or a limited-time incentive
  - CTA: "Still have questions? Chat with us" (low friction) OR "See the plan that's right for [their company size]"

- Email (sent 4 hours after pricing page visit, non-upgrade):
  - Subject: "Still deciding? Here's what most [their role] told us helped them choose"
  - Body:
    - Don't reference the page visit — it feels creepy to users who don't expect personalization
    - Instead: Proactively address the top 3 upgrade hesitations for their persona
    - Hesitation 1: Price (ROI frame — "Starter pays for itself if it saves your team X hours per month")
    - Hesitation 2: Commitment (easy cancellation language, no hidden fees, month-to-month)
    - Hesitation 3: Team buy-in (internal champion toolkit — an email template they can forward to their manager)
    - CTA: Book a 15-minute product walkthrough OR Start the paid trial (lower friction than full credit card commit)

---

**Module 3 — Dormancy Recovery Campaigns (Re-Engage Before Churn)**

*Target: Activated users who have gone dormant (10+ days since last login)*

*3A — Day 10 Soft Re-Engagement*

Generate:
- Email triggered at Day 10 post-last-login (if user previously activated):
  - Subject: Something that reconnects to their reason for signing up — not "We miss you"
  - Body: Remind them of a specific value moment they had (their last document, their last collaboration)
  - New value: What's changed or improved since they were last active (new template, new integration, usage insight)
  - CTA: One specific thing to do in under 5 minutes

*3B — Day 21 Winback + Upgrade Offer*

Generate:
- Email triggered at Day 21 post-last-login (for activated but dormant users who have NOT upgraded):
  - This is a last-chance email before they likely churn — make it count
  - Subject: A question, not a statement (3 variants — test curiosity vs. value reminder vs. social proof)
  - Body: Be honest — acknowledge they've been away. Ask one question: "Is [product] still useful to you, or did something change?"
  - Two CTAs: Primary = "Pick up where you left off" (deep link to their last active session). Secondary = "Tell us what got in the way" (survey link — feeds your product/marketing feedback loop)
  - Upgrade incentive (optional): "If you do come back, we'll extend your free plan by 30 days" — value before ask

*3C — In-App Winback Modal (for users who log back in after 10+ day absence)*

Generate:
- Modal (shown on first login after dormancy period):
  - Acknowledge the return warmly: "Welcome back, [name] — your [X] documents are right where you left them"
  - Give them a fresh reason to re-engage: New feature, new template, or a benchmarking insight ("Teams in your industry are using [product] for [new use case] — here's a template to try it")
  - Soft re-activation nudge: The next milestone they haven't hit yet — make it feel achievable in this session

---

**Module 4 — Expansion Revenue Campaigns (Upgrade Free → Starter → Growth)**

*Target: Paid Starter users who are showing signals for Growth plan*

*4A — Seat Expansion Triggers*

Trigger condition: Paid Starter user has invited 2 of their 3 allowed seats — Growth plan has 10 seats.

Generate:
- In-app message: Seat utilization chart showing how close they are to the limit + Growth plan benefits in the context of team scale
- Email: "Your team is growing — your plan should too" (specific seat count data, team growth metrics if trackable)

*4B — Integration Depth Triggers*

Trigger condition: Starter user has connected their maximum allowed integrations and is attempting to connect a Growth-only integration.

Generate:
- In-app blocker message (when they attempt the blocked integration):
  - Don't just say "This feature requires Growth" — show them what the integration does and what workflow it unlocks
  - CTA: "Unlock [integration name]" → upgrade flow with pre-selected Growth plan

*4C — Power User Behavior Triggers (Usage Velocity)*

Trigger condition: Starter user is consistently using 80%+ of their plan limits for 2+ consecutive months.

Generate:
- Monthly "Your Usage Report" email (sent on the 1st of each month for qualifying users):
  - Data visualization in email: Their usage vs. their plan limits
  - ROI summary: Estimated hours saved, documents automated, team members served
  - Growth frame: "Here's what you could do at scale — here's what Growth users with similar usage accomplish"
  - Upgrade CTA: Annual plan with cost savings calculated specifically for their usage pattern

---

**Module 5 — PLG-to-SLG Handoff Campaigns (When Product Signals Warrant a Human Touch)**

*Target: High-value accounts showing signals that warrant a sales conversation*

*5A — Sales-Qualified Product User (SQPU) Identification*

Generate scoring criteria for surfacing PLG users who warrant an outbound SDR touch:
- Signal category weights for composite score:
  - Company size signals (ICP firmographic match): [weight]
  - Usage depth signals (frequency + breadth of feature usage): [weight]
  - Team expansion signals (multi-user, multi-department): [weight]
  - Integration signals (connecting to enterprise tools like Salesforce, Workday, SAP): [weight]
  - Role signals (if an economic buyer persona has signed up or been invited): [weight]
  - Limit signals (consistently at 85%+ of plan capacity): [weight]
- SQPU threshold: Score ≥ [X] triggers sales alert
- SLA for SDR follow-up: Within [X hours] of threshold crossing

*5B — SDR Outreach Triggered by Product Signal*

Trigger condition: User meets SQPU threshold — SDR receives an alert in Salesforce/HubSpot with a prepared outreach brief.

Generate:
- SDR product-informed outreach email (sent by SDR from personal email, references product behavior without being creepy):
  - Subject: "[Their company] is using [product] in a way that usually signals something bigger — worth a conversation?"
  - Body:
    - Opening: Reference what they've accomplished without citing specific behavior that feels surveillance-like ("I noticed you've been pretty active with Clarix lately — teams that use it the way you are often hit a point where a quick conversation saves a lot of time")
    - Value: What a brief call unlocks — custom implementation review, team training, integration architecture session
    - Not a sales pitch: This is an "I want to be helpful" call, not a "I want to close you" call
    - CTA: "15-minute call this week? I'll bring an agenda based on what your team is trying to accomplish"

- SDR call script:
  - Opening line: "[Name], you've been getting real value out of [product] — I reached out because teams your size usually hit [specific friction point] around this stage. Is that on your radar?"
  - Discovery questions (3): Designed to uncover expansion use cases, team growth plans, and integration needs
  - Value bridge: Connect their current product usage to a paid feature that eliminates a friction they'll discover in the next 30 days
  - Close: Meeting to do an account architecture review, not a sales demo

---

CONSTRAINTS:
- Every in-app message must read like product guidance, not a marketing message — users should feel helped, not marketed to
- Every email must be personalized to the user's actual behavior — no "We haven't seen you in a while" for users who logged in 11 days ago; say "It's been about 2 weeks since your last document"
- Upgrade CTAs must always be framed as unlocking something, never as removing a limitation
- No dark patterns: No countdown timers that aren't real, no false scarcity, no guilt-tripping about their free plan
- Every campaign must have a clear suppression rule: If user upgrades during any sequence, all other upgrade sequences suppress immediately
- All email subject lines must be A/B tested — provide 2-3 variants per email with a hypothesis for which will win and why
- Every in-app message must have a dismissal path that doesn't feel punitive — if they dismiss, they should not see the same message for at least 7 days

## Example Input/Output

**Input Example:**
- Product: Clarix — collaborative legal document automation
- Pricing: Freemium (10 docs/month free, Starter $49/month for 50 docs + 3 seats)
- Activation milestone: User creates first automated template AND invites one teammate
- Tracking: Amplitude + Appcues + Customer.io
- Current free-to-paid conversion: 4.2%
- Days to upgrade for converters: 18 days
- Top upgrade reason: "Hit the document limit"
- Persona: Legal Operations Manager at 200-500 person companies

---

**Output Example (Module 2A — 85% Limit Warning, In-App Modal):**

---

**Headline:** You've built 8.5 documents — and you're not done yet.

**Body:** Your free plan includes 10 documents per month — you've used 8 of them in just [X days]. That's faster than 83% of Clarix users who stay on free.

The next 2 documents will feel different. Because after that, you'll either stop — or you'll keep going.

Clarix Starter gives you 50 documents per month, 3 teammate seats, and 2 integrations for $49/month. Most legal ops teams run 15-25 documents in a typical month.

At your current pace, you'll hit that in your first week.

**[See what Starter includes →]** [Secondary: Remind me later]

*42 teams upgraded this week.*

---

**Output Example (Module 3A — Day 10 Dormancy Re-Engagement Email):**

**Subject A:** The contract template you built is still there
**Subject B:** What happened to your automation workflow, [First Name]?
**Subject C:** Legal ops teams using Clarix save 6.4 hours/week — still relevant?

**Preview text:** You left off right before the interesting part.

---

[First Name],

The last thing you did in Clarix was [save a contract template / invite [teammate name] / complete document #7] — 10 days ago.

Whatever pulled you away, your work is still there.

One thing that might be worth knowing: legal ops managers who use Clarix consistently for 3 weeks report saving an average of 6.4 hours per week on document-related work. You're 10 days in. The payoff usually shows up in week 2-3.

If something's not working or you hit a snag, reply to this email — I read every response.

Or just log back in. Your templates are where you left them.

[Continue where I left off →]

— [Name], PLG Success Team at Clarix

P.S. — If Clarix isn't the right tool for your workflow, I'd genuinely like to know why. It helps us improve. Hit reply.

---

## Success Metrics

- **Free-to-paid conversion rate improvement:** Behavioral trigger campaigns targeting activated users should lift conversion by 1.5-3.0 percentage points (e.g., from 4.2% to 6-7%) within 90 days of full implementation — measure weekly cohorts by signup date
- **Time-to-upgrade compression:** Limit-approaching and collaboration trigger campaigns should reduce average days-to-upgrade from baseline by 20-35% — track by cohort (users exposed to campaigns vs. control)
- **Activation rate lift:** Day 0-2 activation campaigns should increase the % of signups hitting the activation milestone within 7 days by 8-15 percentage points — this is the highest-leverage metric in PLG
- **Dormancy recovery rate:** Day 10 and Day 21 re-engagement campaigns should recover 8-15% of dormant activated users back to active within 14 days of campaign send
- **In-app message CTR:** Well-designed, contextual in-app messages should achieve 15-35% CTR for modal triggers on high-intent events (limit approaching, post-activation celebration); 5-12% for banner/tooltip campaigns — if below 5% on modals, the trigger condition or copy needs revision
- **Email open rates:** Behavioral trigger emails should achieve 35-55% open rates (vs. 22-28% for broadcast marketing emails) — if below 30%, the subject line is failing the personalization test
- **SQPU-to-opportunity conversion:** SDR outreach triggered by PLG product signals should convert at 18-28% to qualified opportunity (vs. 4-8% for cold outbound) — track by SQPU threshold score and signal type to optimize the scoring model
- **Campaign suppression accuracy:** Track upgrade events that occur within any active campaign sequence — if > 5% of upgrades happen after 3+ campaign touches, your early-signal campaigns are underperforming and the limit-approaching campaigns are doing all the work

## Related Prompts
- [AI-Powered B2B SaaS Product-Led Growth PQL Pipeline Architecture & Free-to-Paid Revenue Conversion Intelligence Engine](./AI-Powered-B2B-SaaS-Product-Led-Growth-PQL-Pipeline-Architecture-&-Free-to-Paid-Revenue-Conversion-Intelligence-Engine.md)
- [AI-Powered B2B SaaS PLG Viral Loop & Network Effect Organic Acquisition Intelligence Engine](./AI-Powered-B2B-SaaS-PLG-Viral-Loop-&-Network-Effect-Organic-Acquisition-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Free Trial Activation Funnel CRO & Time-to-Value Conversion Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Free-Trial-Activation-Funnel-CRO-&-Time-to-Value-Conversion-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Self-Serve Onboarding Funnel Optimization & Time-to-Value Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Onboarding-&-Activation/AI-Powered-B2B-SaaS-Self-Serve-Onboarding-Funnel-Optimization-&-Time-to-Value-Intelligence-Engine.md)

## Integration Tips
- **Customer.io / Braze / Iterable:** Define each behavioral trigger as a named Event in your event schema (e.g., `limit_70_pct_reached`, `activation_milestone_completed`, `pricing_page_visited_no_upgrade`). Build individual journeys per trigger — never combine multiple triggers into one campaign flow, as suppression logic becomes unmanageable. Use Customer.io's People conditions to suppress entire Journey categories when `plan_status = paid`.
- **Appcues / Pendo:** Tag every flow with the trigger event name and the campaign module number from this document (e.g., "Module 2A — 85% Limit Warning"). This makes suppression logic, A/B test analysis, and iteration far easier when you have 15+ active flows. Use Appcues' checklist component for Module 1A activation campaign — completion-based checklists outperform static modals for multi-step activation sequences.
- **Amplitude / Mixpanel:** Build a PLG Conversion Funnel chart with the following steps: Signed Up → Activation Milestone Reached → Limit-Approaching Signal Fired → Pricing Page Visited → Upgrade Completed. Track daily cohorts. This funnel tells you where to focus your campaign optimization effort — if 50% of activated users never hit a limit signal, your pricing limits may be too generous.
- **Segment:** Create a PLG-specific Computed Trait for each SQPU scoring dimension (usage frequency, seat expansion, integration depth, company size). Output the composite SQPU score as a HubSpot/Salesforce property so SDRs can filter their prospecting queue by score threshold without needing Segment access.
- **HubSpot / Salesforce:** Create a PLG Campaign object that tracks every touchpoint — in-app message impressions (via webhook from Appcues/Pendo), email sends, email opens, CTA clicks, and upgrade events. This lets you calculate true campaign influence, not just last-touch attribution. Build a dashboard showing campaign-influenced revenue by module (Module 2A limit campaigns vs. Module 2B collaboration triggers) to identify which signals are highest ROI to invest in further.
- **Intercom:** Use Intercom's Product Tours for Module 1A activation tooltips — the built-in targeting rules (page URL + user property conditions) handle the trigger logic without engineering support. Use Intercom Series for dormancy re-engagement (Module 3) — the multi-step automation with conditional branching handles the "did they log back in?" check natively.
- **Zapier / Make:** Build an automation that fires when a user's SQPU score crosses the threshold in Amplitude → creates a task in Salesforce with the outreach brief → assigns to the relevant SDR based on account territory → logs the task creation back to Amplitude as an event (so you can track SDR response time as part of your PLG-to-SLG conversion funnel).

## Troubleshooting

**Problem: In-app messages are getting dismissed immediately with no engagement — CTR is below 5% even for limit-approaching campaigns**
Solution: The most common cause is poor trigger timing — the message is appearing at the wrong moment in the session flow. Limit-approaching modals that appear the moment a user opens the app feel like an ambush; showing them after the user has completed an action (e.g., just saved a document that brought them to 85% of limit) achieves 3-4x higher engagement because the user has just experienced the value and is in a receptive state. Audit your trigger conditions first — then audit your copy. The second most common cause is that your headline is product-centric ("You've reached 85% of your plan limit") rather than user-progress-centric ("You've built 8 of 10 documents this month — here's what comes next"). Reframe every headline from the user's perspective, not the product's.

**Problem: Behavioral trigger emails are getting good open rates but almost zero clicks — users are reading but not acting**
Solution: This almost always means the CTA is asking for too much relative to where the user is in their decision process. A user who received a Day 10 dormancy email and opened it is showing low-intent signals — they're curious, not ready to upgrade. The CTA should match that intent: "Log back in" or "See your saved work" beats "Upgrade to Starter" by 3-5x in click-through for re-engagement sequences. Reserve direct upgrade CTAs for high-intent signals (pricing page visits, limit breaches at 95%, collaboration triggers). For all other campaigns, the CTA goal is the next micro-commitment, not the conversion event.

**Problem: The PLG-to-SLG handoff isn't working — SDRs aren't following up on SQPU alerts, or are following up too late to matter**
Solution: There are two separate problems here. If SDRs aren't following up, it's a prioritization problem — SQPU alerts are competing with their existing outbound queue and losing. Fix: Make SQPU alerts a separate, high-priority queue in Salesforce/Outreach with a 4-hour SLA, and have the CRO or VP Sales visibly review the queue in the weekly pipeline call. If they're following up but conversion is low, the outreach itself is the problem — SDRs are treating SQPU leads like cold outbound (generic pitch) instead of like warm, product-qualified prospects (consultative, behavior-informed opening). Run a 2-week calibration sprint where every SDR follows the exact outreach script in Module 5B verbatim — before they start customizing. Measure conversion rate before and after the script enforcement.

## Version History
- v1.0: Initial creation (auto-generated)
