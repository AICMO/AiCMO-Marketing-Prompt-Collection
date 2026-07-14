# AI-Powered B2B SaaS PLG Churned User Win-Back & Dormant Account Reactivation Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** b2b, plg, win-back, churn, reactivation, dormant-users, product-led-growth, lifecycle-marketing, saas, email-automation, behavioral-triggers, revenue-recovery

## Overview
This prompt designs a complete AI-powered system to identify, segment, and systematically reactivate churned or dormant PLG users — transforming your existing user database into a predictable reactivation revenue channel. Use it when you have a growing backlog of churned or inactive free/paid users, when reactivation rates are below 10%, or when your team is sending one-size-fits-all "we miss you" emails with no measurable results.

## Quick Copy-Paste Version

You are a senior B2B SaaS PLG growth strategist specializing in churned user reactivation and dormant account recovery. Design a complete AI-powered win-back system for my product.

My company: [What we do — one sentence]
Business model: [Freemium / Free Trial / Usage-Based / Subscription]
Product type: [e.g., project management tool, analytics platform, developer tool, CRM]
Churned/dormant user database size: [X users]
Definition of "churned" in our system: [e.g., no login for 30 days / cancelled paid plan / trial expired without converting]
Definition of "dormant": [e.g., free user, no login for 14+ days / paid user, no core action in 21+ days]
Average contract value: [ACV $X for paid users; $0 for free → target plan $Y/mo]
Primary "aha moment" (the action that predicted conversion): [e.g., "user publishes first report," "team invites 3+ members"]
Churn reasons we know about: [e.g., too complex, not enough integrations, competitor switch, budget cut, role change]
Current reactivation approach: [e.g., "we send one email at 30 days inactive" or "nothing systematic"]
Tech stack: [Product analytics tool, CRM, email tool, in-app messaging]

Design the following:

1. CHURNED USER SEGMENTATION MODEL — Classify dormant/churned users into 4–6 actionable segments by: reason for leaving, usage depth at churn, account type (free vs. paid), and reactivation potential. For each segment: segment name, defining criteria, estimated % of database, primary win-back angle, and channel priority.

2. REACTIVATION TRIGGER SYSTEM — Define 6 automated triggers that should fire win-back campaigns: 3 based on product events (feature launch, integration added, product milestone relevant to their use case), 2 based on external events (competitor pricing change, industry news, end of fiscal quarter), and 1 based on timing (re-engagement window). For each trigger: event, the segment it applies to, and the message angle.

3. WIN-BACK SEQUENCE ARCHITECTURE — Design a 5-email win-back sequence for your highest-potential churn segment. For each email: subject line, preview text, 3-paragraph body, primary CTA, send timing, and suppression rule (send only if user has NOT re-engaged).

4. SALES-ASSISTED REACTIVATION PROTOCOL — For high-ACV churned accounts (paid users, company size >50 employees), define the human-touch reactivation playbook: the research required before outreach, the outreach message template that references their usage data, and the offer to bring them back.

5. REACTIVATION ANALYTICS FRAMEWORK — Define the 5 metrics to measure win-back program success, with formulas and benchmarks.

Output as a structured playbook with email templates, segmentation rules, trigger specifications, and analytics definitions ready to load into [your email + CRM stack].

## Advanced Customizable Version

ROLE: You are a senior PLG Reactivation Architect with 12+ years designing win-back systems for product-led B2B SaaS companies. You have rebuilt dormant user programs that recovered 8–22% of churned accounts at companies with freemium and free-trial motions. You combine expertise in behavioral segmentation, lifecycle email strategy, product analytics, and AI-powered personalization to engineer reactivation systems that treat churned users as a revenue asset — not a lost cause.

CONTEXT:
Company: [Company name]
Product description: [What it does, who uses it daily, the core job-to-be-done]
Business model: [Freemium / Free trial / Reverse trial / Usage-based / Subscription]
Pricing tiers: Free ([limits]) → [Pro/Growth] ($[X]/mo) → Enterprise (custom)
Primary ICP: [Role, seniority, company size, industry]
Churn definition: [Exact definition used in your system — be precise]
Dormant definition: [Exact definition — distinguish from churned]
Churned user database: [Total size; breakdown by free vs. paid if known]
Known churn reasons: [List all reasons you know — from cancellation surveys, CS calls, product data]
Current activation rate at time of churn: [% of churned users who had reached the aha moment before leaving]
ACV of paid churned users: [$X average / $Y top decile]
Win-back budget available: [$ per month or per campaign]
Current win-back activity: [Describe what you do today]
Toolstack: [Product analytics: Amplitude/Mixpanel/PostHog] + [Email: Customer.io/HubSpot/Iterable/Klaviyo] + [In-app: Intercom/Appcues] + [CRM: Salesforce/HubSpot]
Key constraint: [e.g., "GDPR limits re-engagement to users who opted in," "no product analytics for churned users pre-2023," "small team, can't do sales-assisted for <$5K ACV"]

OBJECTIVE: Design a production-ready PLG win-back system that systematically identifies reactivation opportunities, segments churned users by recovery potential, delivers precisely timed and personalized re-engagement campaigns, and recovers 10–25% of dormant accounts as active users — with a clear path from reactivation to paid conversion.

---

DELIVERABLE 1 — CHURNED USER SEGMENTATION MODEL

Classify all churned/dormant users into exactly 5 segments. Use a scoring model based on three dimensions:

DIMENSION A — Usage Depth at Churn (what they did before leaving):
- Tier 1 (High depth): Reached and exceeded aha moment; used core features 3+ times; invited teammates
- Tier 2 (Medium depth): Reached aha moment once but never repeated; used 1–2 features only
- Tier 3 (Low depth): Never reached aha moment; minimal product interaction; churned in first 7 days

DIMENSION B — Reason for Leaving (from cancellation data, surveys, or inference):
- Fit problem: Product didn't solve their job-to-be-done (wrong ICP, wrong use case)
- Timing problem: Right product, wrong time (budget freeze, team restructure, competing priorities)
- Experience problem: Too complex, bad onboarding, missing integrations, bugs
- Competitive problem: Switched to a named competitor
- Unknown: No data (ghost churn — just stopped using)

DIMENSION C — Reactivation Potential:
- High: Paid user, correct ICP profile, used product meaningfully, left for timing/experience reasons
- Medium: Free user with team usage, reached aha moment, left for unknown/competitive reasons
- Low: Never activated, wrong ICP, left for fit reasons

SEGMENTATION OUTPUT — Define each segment with:

Segment name: [Memorable, action-oriented label]
Defining criteria: [Specific rules using all three dimensions — be explicit about what qualifies]
Estimated % of typical B2B SaaS PLG dormant database: [Provide range, e.g., 15–25%]
Reactivation potential score: [High / Medium / Low]
Primary win-back angle: [The core message that would resonate — what has changed, what they're missing, what new value exists]
Recommended channel mix: [Email only / Email + in-app / Email + direct outreach / Direct outreach only]
Recommended sequence length: [Number of touches; timing cadence]
Suppression rules: [When to permanently suppress — protect sender reputation and respect churned users]
Exclusion criteria: [Segments NOT worth pursuing — save budget]

REQUIRED SEGMENTS (customize criteria and messaging, but include these 5):
1. High-Value Churned (paid, activated, experience-problem churn) — highest ROI, most personalized approach
2. Timing-Gated Returners (paid or free, correct ICP, left for timing/budget reasons) — re-engage at external triggers
3. Never-Activated Ghost Churners (churned before aha moment, unknown reason) — re-onboarding angle, not win-back
4. Competitive Defectors (explicitly left for a named competitor) — triggered by competitor's pricing/outage/customer review news
5. Team Account Orphans (workspace still exists, original champion left, but teammates remain) — reach surviving users, not the churned champion

---

DELIVERABLE 2 — REACTIVATION TRIGGER SYSTEM

Define 8 automated trigger events that should fire win-back campaigns. Structure each trigger as:

Trigger name: [Action-oriented name]
Trigger condition: [Exact event or data condition that fires the trigger — must be machine-detectable]
Target segment(s): [Which of the 5 segments this applies to]
Win-back angle: [The specific message hook enabled by this trigger — why NOW is the right time to come back]
Channel: [Email / In-app re-engagement / Direct outreach / LinkedIn / SMS]
Suppression: [Do not fire if user [condition] within [timeframe]]
Priority score: [High/Medium/Low — for teams that can't run all 8 simultaneously]

REQUIRED TRIGGERS:

Product-event triggers (must include all 3):
T1 — Feature Launch Trigger: A new feature directly addresses a known pain point of the churned segment. Use product release notes + churn reason data to match churned user's stated frustration with the new fix.
T2 — Integration Added Trigger: A new native integration with a tool the churned user was using (infer from their job title + industry; confirm via tech stack data if available via Clearbit/ZoomInfo enrichment).
T3 — Personalized Milestone Trigger: An anniversary trigger (e.g., "1 year since you built [X] in [Product]") that surfaces the work the churned user created — reactivates nostalgia and sunk cost psychology.

External-event triggers (must include all 3):
T4 — Competitor Disruption Trigger: Target competitive defectors when their current vendor has a documented pricing increase, major outage (check DownDetector/Reddit), security breach, or acquisition. Monitor via Google Alerts + Reddit + G2 reviews.
T5 — Industry/Regulatory Trigger: Target timing-gated churners when a regulatory deadline, industry event, or market shift (e.g., new compliance requirement, AI-driven workflow change) makes your product suddenly relevant again.
T6 — Budget Cycle Trigger: Target timing-gated churners at Q4 (new budget season), Q1 (new fiscal year goals), or the calendar anniversary of their original paid cancellation date — when budget is being allocated and your product is likely being re-evaluated.

Behavioral re-engagement triggers (must include both):
T7 — Return Visit Trigger: Churned user revisits your website or opens a product email without converting. Shows re-evaluation signal — fire personalized re-engagement before they go cold again.
T8 — Peer Network Trigger: A colleague from the churned user's company (different email, same domain) signs up for or activates the product. Target Team Account Orphans and High-Value Churned users with social proof from their own organization.

---

DELIVERABLE 3 — WIN-BACK SEQUENCE ARCHITECTURE

Design complete win-back email sequences for each of the 5 segments. For EACH segment, produce:

SEGMENT WIN-BACK SEQUENCE:

Email 1 — Reactivation Hook (send at churn + X days / on trigger event):
- Subject line (A/B test two variants): [Write both — one curiosity-based, one value-based]
- Preview text: [25–45 characters, complements subject line]
- Email body (3 tight paragraphs max):
  - P1: Acknowledge the gap without apology — reference their specific usage or the trigger event
  - P2: Deliver the core win-back value proposition — what's new, what's better, what they're missing
  - P3: Remove friction — make returning frictionless (restore their data, offer a free month, skip setup)
- Primary CTA: [Specific, action-driven — not "Come Back" or "Log In"]
- Send condition: [User has NOT logged in since churn date AND trigger event has fired]
- Suppression: [Suppress if user re-engages at any point after Email 1 send]

Email 2 — Social Proof & Peer Validation (send 5 days after Email 1, if no re-engagement):
- Lead with a customer story from someone in the same role/industry as the churned user
- Include a specific metric (e.g., "Teams like yours save 6 hours per week on [exact workflow]")
- CTA: Offer a live 20-minute return session — "Let us show you what's changed"

Email 3 — Competitive Comparison or Feature Spotlight (send 10 days after Email 1):
- For competitive defectors: Directly address the reason they left for the competitor (without naming the competitor) — address the gap that has now been closed
- For all others: Spotlight the single most-relevant new feature or improvement released since they churned
- CTA: One-click access to a live demo, video walkthrough, or sandbox environment

Email 4 — Stakes/FOMO + Incentive (send 18 days after Email 1, if no re-engagement):
- Introduce a time-limited offer: free month, waived setup fee, locked-in rate, migration support, extended trial
- Anchor the offer to a specific deadline (7 days) — vague offers don't convert
- For High-Value Churned (paid): SDR sends personalized email/LinkedIn note simultaneously; remove from automated sequence

Email 5 — Final Breakup (send 28 days after Email 1, if no re-engagement):
- "Is this goodbye?" subject line — acknowledge this is the last message
- Give them a clean exit with a feedback form (one question: "What would need to change for you to come back?")
- Offer to stay in touch via newsletter or LinkedIn — preserve the relationship for future cycles
- Permanently suppress from win-back campaigns for 90 days after this email

PERSONALIZATION RULES (apply across all sequences):
- Reference their last product action by name: "When you [built X / analyzed Y / set up Z] in [Product]..."
- Address their specific role, not a generic "you": "As a [Job Title], you probably..."
- Use trigger-specific hooks: If firing on a product launch, name the feature and connect it explicitly to their known pain point
- Dynamic product screenshots: Include a screenshot of their actual workspace/data (requires product + email integration) OR the most relevant new feature UI
- Company-size personalization: Adjust case studies and social proof to match their company's employee count

---

DELIVERABLE 4 — SALES-ASSISTED REACTIVATION PROTOCOL

For High-Value Churned accounts (paid users, ACV >$X, company size >50 employees), define the human-touch reactivation protocol:

PRE-OUTREACH INTELLIGENCE BRIEF (what the SDR/CSM must know before reaching out):

Required data pull from CRM + product analytics:
- Original paid plan + ACV
- Months as a paying customer
- Features used (list all core features they activated + ones they never touched)
- Last login date + last meaningful action
- Cancellation reason (from survey or CSM notes)
- Current tech stack (from Clearbit/ZoomInfo/LinkedIn enrichment)
- Any support tickets or complaints logged during their tenure
- LinkedIn activity of the key contact in the last 30 days (new job? new initiative?)

Scoring rubric — only reach out if account scores 4+ out of 5:
[ ] ACV was $[X]+ per year (1 point)
[ ] Used 3+ core features before churning (1 point)
[ ] Churned for timing/experience reasons, not fit (1 point)
[ ] Key contact is still at the same company AND has the same or expanded scope (1 point)
[ ] A specific trigger event has fired (new feature, competitor issue, budget cycle) (1 point)

SDR OUTREACH TEMPLATE (personalized for each account):

Subject: [First name], [Product] since you left — [specific improvement relevant to their churn reason]
Body:
"[First name] — quick note because you crossed my mind.

When [Company] was using [Product] last [timeframe], you had [X feature or workflow] set up. I noticed your team left around [timeframe] — and I suspect [specific friction point you know from churn data or CS notes] was part of the reason.

Since then, we've [specific product improvement that directly addresses that friction]. I think it changes the calculus if you were to look again.

Worth a 20-minute call to see if it's worth re-evaluating? I'll come prepared with a custom migration plan and [specific incentive relevant to their situation]."

CTA options (match to account profile):
- High-intent: "Book a 20-minute call" [Calendly direct]
- Warm signal: "Want me to send over a quick comparison of how things have changed?"
- Lower trust: "Would a 1-page update be helpful?" [lower commitment ask]

PARALLEL OUTREACH PLAYBOOK:
- Day 1: SDR sends personalized email (above)
- Day 3: LinkedIn connection request with note (reference a specific piece of content they liked/shared)
- Day 7: Second email with social proof from a peer company that came back
- Day 14: Final call attempt with voicemail, then tag account for 90-day re-engagement trigger

HAND-OFF TO AE CRITERIA:
- Account responds positively to SDR outreach → schedule AE discovery call within 48 hours
- Account requests pricing or migration plan → AE assumes ownership immediately
- Account says "not right now" → SDR sets reminder for 60-day trigger; CSM added to watch list

---

DELIVERABLE 5 — REACTIVATION ANALYTICS FRAMEWORK

Define the complete measurement system for win-back program performance:

CORE METRICS (define formula, data source, and benchmark for each):

1. Reactivation Rate by Segment
- Formula: (Churned users who logged in and completed at least 1 core action / Total churned users in segment targeted) × 100
- Measure at: 30 days and 90 days after sequence start
- Benchmark: High-Value Churned: 15–25%; Timing-Gated: 10–20%; Ghost Churners: 3–8%
- Alert: Flag any segment performing >10pp below benchmark after 500+ sends

2. Win-Back Revenue Recovery Rate
- Formula: (ACV recovered from reactivated paid users in period / Total ACV lost from churned users in same cohort) × 100
- Why track both count AND revenue: A 10% reactivation rate on high-ACV accounts > 25% on low-ACV accounts
- Target: Recover 5–15% of churned ARR annually from win-back programs
- Segment by: Original plan tier, churn reason, and win-back sequence variant

3. Reactivation-to-Retention Rate
- Formula: (Reactivated users still active at Day 60 / Total reactivated users) × 100
- Why this matters: Reactivations without retention are phantom wins — the underlying problem wasn't fixed
- Target: >50% of reactivated users still active at Day 60 (lower than new user retention benchmark — normal)
- Action: If below 30%, the win-back message is overpromising; audit the gap between re-engagement promise and actual product experience

4. Email Sequence Performance by Touch
- For each of the 5 emails in the sequence, track: Open rate / Click rate / Reactivation rate (downstream)
- Insight: If Email 4 (incentive) drives disproportionate reactivations but Email 1 has low opens, test Email 1 subject lines more aggressively
- Benchmark: Win-back open rates (15–30%) are typically 1.5–2x higher than standard lifecycle emails — if below 15%, list quality or segmentation is wrong

5. Sales-Assisted vs. Automated Reactivation ROI
- Formula: (Revenue recovered from sales-assisted accounts / Cost of SDR time spent) vs. (Revenue from automated sequence / Cost of email infrastructure)
- Target: Sales-assisted ROI benchmark: >10x SDR time cost; Automated ROI: >50x email cost
- Decision rule: If sales-assisted ROI <5x, expand automated and restrict sales-assisted to ACV >$[X]

COHORT ANALYSIS APPROACH:
Build a quarterly win-back cohort table:
- Cohort (quarter churned)
- Segment distribution
- Total targeted / Total reactivated / Reactivated → paid
- Revenue recovered
- 60-day retention rate for reactivated users
- Top trigger event that drove reactivations
Compare cohorts to identify if win-back performance improves over time as segmentation and sequencing are refined.

SUPPRESSION HEALTH METRICS:
- Unsubscribe rate from win-back campaigns: Target <0.5% (higher than typical lifecycle = list is being pushed too hard)
- Spam complaint rate: Target <0.1% (win-back campaigns to lapsed users are highest-risk for spam flags — monitor daily)
- Hard bounce rate: Target <2% (churned user email lists have high decay; validate email addresses before sending)

OUTPUT FORMAT: Structured playbook with segmentation rules, trigger definitions, complete email copy for all 5 segments × 5 emails = 25 email templates with subject lines and CTAs, sales outreach templates, scoring rubric, and analytics dashboard definitions. All templates include [bracketed_variable_names] for dynamic personalization. Default toolstack assumed: PostHog (product analytics) + Customer.io (email sequences) + Salesforce (CRM) + LinkedIn Sales Navigator (sales-assisted), with adaptation notes for HubSpot, Iterable, and Braze.

## Example Input/Output

**Input Example:**
Company: Vanta — a B2B SaaS compliance automation platform (automated SOC 2, ISO 27001, GDPR compliance monitoring)
Business model: Free trial (14 days) → paid subscription starting at $7,500/year for SMB → Enterprise custom
Churned/dormant database: 4,200 churned free trial users + 380 cancelled paid accounts
Churn definition: Trial expired without conversion (free) / Cancellation date reached (paid)
Dormant definition: Paid user, no login for 21+ days OR no new evidence uploaded in 45+ days
ACV paid churned: $9,200 average; $31,000 top decile
Primary aha moment: "User connects 3+ cloud infrastructure integrations AND runs first automated evidence collection"
Known churn reasons: 45% — too expensive at current stage; 30% — hired dedicated compliance person internally; 15% — switched to Drata or Secureframe; 10% — project deprioritized
Tech stack: Amplitude + Customer.io + Salesforce + LinkedIn Sales Navigator

**Output Example (excerpts):**

**Segment 1: High-Value Churned (24% of database — 91 paid accounts)**
Criteria: Paid plan cancelled; ACV >$7,500; had 3+ integrations connected; ran at least 2 evidence collection cycles; left for budget or timing reasons
Reactivation potential: High
Win-back angle: "Your compliance infrastructure is still there — and the cost of rebuilding it from scratch has only increased"
Channel: Sales-assisted (SDR) + Email sequence running in parallel
Suppression: Suppress after 90 days of no engagement OR if contact leaves the company (monitor via LinkedIn)

**Trigger T4 — Competitor Disruption (for Competitive Defectors segment):**
Trigger condition: Google Alert fires for "[Drata] pricing increase" OR G2 review mentioning "[Secureframe] support quality dropped" OR Reddit r/compliance post with >20 upvotes criticizing a named competitor
Target segment: Competitive Defectors (15% of database)
Win-back angle: "We've heard from [X] teams who came back after [trigger event]. Here's what they said."
Channel: Email (immediate, same day as trigger)
Message hook: "We noticed there's been some conversation about [industry topic]. We'd love to show you what's changed at [Product] in the last [X months] — including [specific improvement relevant to the competitive gap they left for]."

**Email 1 — High-Value Churned Segment:**
Subject A: Your SOC 2 evidence is still live in [Product] — here's what changed
Subject B: [First name], we fixed the [specific friction] that most of our churned customers mentioned
Preview: The compliance infrastructure you built is still there.

"[First name] — you ran [X evidence collection cycles] in [Product] before your [Company] subscription ended [X months ago]. That work isn't gone.

Since then, we've [specific improvement — e.g., added a dedicated pricing tier for companies pre-Series A + a new integration with AWS GovCloud + cut median audit completion time from 4 months to 6 weeks]. If the cost-to-value equation was the blocker last time, I think that equation looks different now.

Coming back takes about 15 minutes — your integrations and evidence are exactly where you left them. We'll also waive the onboarding fee and give you 30 days free to re-verify your progress."

CTA: "Reactivate my [Product] account →" [deep link to workspace restoration flow]
Send timing: Day 0 of churn + 90 days (budget cycle re-evaluation window) OR immediately on T6 (budget cycle trigger)

**Sales-Assisted Outreach — SDR Template (High-Value Churned):**
Subject: [First name] — your SOC 2 infrastructure + what's changed at [Product]
Body:
"[First name] — quick note.

When [Company] was on [Product] last [quarter/year], you had [3 integrations] running automated evidence collection for your SOC 2. I know the subscription ended around [timeframe] — and based on what I've heard from other companies at your stage, budget allocation for compliance tooling at that moment can be tough to justify.

Since then, we launched a new pricing tier specifically designed for [Company size]-stage companies — [specific plan] at [$X/year] with all the core automation. We've also added [specific integration they didn't have] and cut the average time-to-audit from [X] to [Y].

Worth a 20-minute call to walk through what's changed and see if the timing makes more sense now? I can put together a custom proposal based on your existing evidence baseline — you'd be starting from 60% complete, not from scratch."

CTA: "Book 20 minutes with me" [Calendly link]

## Success Metrics

**Win-Back Program Health KPIs:**
- **Reactivation Rate at Day 30 (High-Value Churned segment):** Target 15–25%. Measure weekly after sequence launch. If below 10% after 200 sends, audit segmentation criteria — wrong users in the segment.
- **Win-Back Revenue Recovery Rate:** Target recover 8–15% of churned ARR annually. Baseline in Month 1 before optimization; expect 3–4 month ramp to full performance.
- **Reactivation-to-Retention Rate at Day 60:** Target >50% of reactivated users still active. Signals the product experience matches the win-back promise. Below 35% = product-message mismatch.
- **Sales-Assisted Reactivation Close Rate:** Target 20–35% of sales-assisted conversations convert to paid. If below 15%, the SDR scoring rubric is too broad — tighten ACV threshold.
- **Email Sequence Unsubscribe Rate:** Target <0.5% per email. Win-back lists decay fast — run email validation (ZeroBounce/NeverBounce) before each sequence launch to protect sender reputation.

**Quality Signals:**
- Trigger precision: >60% of trigger-activated campaigns sent to the correct target segment (verify manually on a monthly sample)
- Personalization accuracy: <5% of emails containing "[bracketed_variable]" errors due to missing CRM data — fill data gaps before sending
- Re-churn rate: Track if reactivated users churn again within 90 days; target <20% re-churn rate; high re-churn means the root cause of original churn was not addressed

## Related Prompts
- [PLG New User Onboarding Orchestration & Aha Moment Acceleration](./AI-Powered-B2B-SaaS-PLG-New-User-Onboarding-Orchestration-&-Aha-Moment-Acceleration-Revenue-Intelligence-Engine.md)
- [PLG PQL Pipeline Architecture & Free-to-Paid Revenue Conversion](./AI-Powered-B2B-SaaS-Product-Led-Growth-PQL-Pipeline-Architecture-&-Free-to-Paid-Revenue-Conversion-Intelligence-Engine.md)
- [PLG In-App Behavioral Activation & Product Usage-Triggered Revenue Campaign](./AI-Powered-B2B-SaaS-PLG-In-App-Behavioral-Activation-&-Product-Usage-Triggered-Revenue-Campaign-Intelligence-Engine.md)
- [Customer Win-Back & Cold Lead Reactivation](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Customer-Win-Back-&-Cold-Lead-Reactivation-Engine.md)

## Integration Tips

**Customer.io + PostHog (Recommended for PLG teams <$20M ARR):**
- Define churn/dormancy events in PostHog as computed properties: `last_seen_at < NOW() - INTERVAL 30 DAYS` filtered to free users = dormant segment; cancelled plan events = churned
- Sync churned/dormant cohorts to Customer.io via PostHog's Destinations (webhook) — update daily so new churn adds to win-back sequences automatically
- Build Customer.io Campaigns with "Time delay" + "Event not fired" conditions: "Send Email 2 if `reactivation_login` NOT fired within 5 days of Email 1 send"
- Use Customer.io's Liquid tags for personalization: `{{customer.last_feature_used}}`, `{{customer.days_since_churn}}`, `{{customer.original_plan_name}}`
- Set global unsubscribe category "win-back" separate from "product" emails — lets churned users opt out of win-back without blocking future product transactionals

**Salesforce + HubSpot Sequences (Sales-assisted reactivation):**
- Create custom Salesforce object "Win-Back Opportunity" linked to original Account — tracks SDR outreach separate from new pipeline
- Build SFDC report: "High-Value Churned Accounts — Reactivation Scoring" refreshed daily; SDR reviews each morning
- Use HubSpot Sequences for the 4-touch sales-assisted protocol — auto-pause sequence on positive reply, auto-enroll on trigger event
- Sync Salesforce Win-Back Opportunities to HubSpot Deals on positive response (prevent revenue from being lost in tool gaps)

**Iterable (Enterprise win-back for >$30M ARR):**
- Use Iterable's Journey builder to build parallel tracks: automated email sequence + sales-assist notification (Slack webhook to SDR channel when high-value churned account opens Email 1)
- Leverage Iterable's Catalog feature to store churned user's last product actions — dynamically inject into email templates at send time without manual data management
- Use Iterable's A/B testing at the Journey level to test sequence length (3-email vs. 5-email win-back) and measure reactivation rate + 60-day retention by variant

**Klaviyo (for PLG products with B2C / prosumer / self-serve segment):**
- Build win-back flow with Klaviyo's Flow Filters: "Person has property churned_date is not blank AND churned_date is before 90 days ago"
- Use Klaviyo's Predictive Analytics to score "Expected Date of Next Order/Return" — prioritize re-engagement sequences to users with high predicted return probability
- A/B test subject lines using Klaviyo's built-in email testing; automatically send winner after 4 hours to remaining audience

**Zapier automation (for lean teams without engineering support):**
- PostHog → Zapier → Customer.io: Trigger on PostHog "user_churned" event → Zap adds tag "win-back-eligible" to Customer.io contact → enrolls in win-back sequence
- Trigger-alert Zap: Google Alerts RSS feed (monitoring competitor terms) → Zapier → Customer.io API call: tag "competitor_trigger_fired" on all Competitive Defector segment contacts → fires Trigger T4 campaign
- LinkedIn alerts: When a churned contact changes jobs (monitored via PhantomBuster or Dux-Soup), fire Zapier → update CRM contact → suppress from win-back (targeting a contact who left the company is a waste of budget)

## Troubleshooting

**Problem: Win-back emails have high open rates but near-zero reactivation — people are reading but not returning**
*Solution:* Three likely causes: (1) The product hasn't actually fixed the reason they left — your win-back copy promises improvement but the churned user tries to log in and hits the same wall. Audit whether the feature/fix highlighted in Email 1 is genuinely live and discoverable within 5 minutes of login. (2) The return experience is too high-friction — if a churned user has to reset their password, re-setup integrations, or re-enter billing information before experiencing value, most won't. Remove every possible barrier: pre-populate login, restore their workspace exactly as they left it, surface their saved work on the first post-reactivation screen. (3) The CTA sends them to the homepage instead of directly to their workspace — replace every win-back CTA with authenticated deep links that bypass login friction entirely.

**Problem: Reactivation rate is strong (15%+) but re-churn within 60 days is very high (>40%)**
*Solution:* The win-back is working as a campaign but failing as a retention event — meaning users come back, find nothing meaningfully different, and leave again. This is a product problem, not a marketing problem. Audit the re-churned users: run a product session replay (FullStory/Hotjar) on their return session to see where they dropped off. Common finding: they log in, see the new feature mentioned in the win-back email, realize it doesn't actually solve their specific workflow gap, and leave. Fix: build a "returning user" onboarding experience that is distinct from new user onboarding — surfacing the specific new feature/improvement mentioned in the email as the first interaction on return, with a 3-step guided flow.

**Problem: Sales-assisted reactivation SDR is sending to wrong contacts — original champion left the company**
*Solution:* Implement a pre-send data verification step. Before loading High-Value Churned accounts into the SDR outreach queue, run domain through LinkedIn's People Search to confirm the original contact is still at the company AND still in a relevant role. Use tools like Lusha, Clearbit, or LinkedIn Sales Navigator's "Signal" alerts to get notified when a contact changes jobs — automatically suppress them and identify their replacement at the account. The replacement may be a warm outreach opportunity: "Your colleague [Name] set up [Product] at [Company] last year — I wanted to make sure you knew about it, and share what's changed since then."

## Version History
- v1.0: Initial creation (auto-generated)
