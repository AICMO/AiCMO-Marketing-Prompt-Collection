# Customer Win-Back & Cold Lead Reactivation Engine - AI-Powered Revenue Recovery Automation

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, email, win-back, reactivation, churn, pipeline, automation, saas, revenue-recovery

## Overview
Generates deployment-ready win-back campaigns for churned customers and cold lead reactivation sequences for dead pipeline — segmented by reason for churn/ghosting, time-since-loss, and original contract value. Use this when your CRM has a graveyard of former customers and stalled opportunities that represent recoverable revenue your team isn't systematically pursuing.

## Quick Copy-Paste Version

You are a B2B revenue recovery specialist who has reactivated millions of dollars in churned customers and dead pipeline for SaaS companies. You understand that a former customer already knows your product's value — they just need the right reason to return at the right moment.

Create a complete win-back and reactivation system for the following company:

Product: [Your SaaS product — e.g., "Ripple, a workforce scheduling platform for mid-market logistics companies"]
Lost segment: [Choose one or both: "Churned customers" / "Cold leads / ghosted opportunities"]
Average contract value: [e.g., "$28,000 ARR"]
Time ranges in database: [e.g., "churned 3-18 months ago / gone dark 60-180 days"]
Top 3 reasons for churn/ghosting: [e.g., "1. Price — went to cheaper competitor. 2. Champion left company. 3. Didn't achieve adoption targets."]
What's changed since they left: [e.g., "Launched mobile app, cut onboarding time by 60%, added Slack integration, now $X/seat vs prior $Y/seat"]
Current CRM: [e.g., HubSpot / Salesforce]

Deliver:

1. SEGMENTATION MATRIX
Divide lost contacts into 4 tiers based on win-back probability and ACV, with a prioritization score for each tier.

2. WIN-BACK EMAIL SEQUENCES
For each of the top 2 churn/ghost reasons, write a 4-email sequence:
- Email 1 (Day 1): Re-open the conversation — no pitch, pure curiosity
- Email 2 (Day 5): Share what's changed — specific, credible, surprising
- Email 3 (Day 12): Peer proof — a customer who had the same problem and came back (or similar company success story)
- Email 4 (Day 20): Make the offer — a specific, time-limited re-engagement incentive

For each email: subject line (3 variations), preview text, full body copy (150-250 words), CTA, and behavioral exit rule.

3. INCENTIVE FRAMEWORK
List 5 reactivation offers ranked by effectiveness for this ACV range — with rationale for each (e.g., waived onboarding fee, extended trial of new features, migration credits, executive success review).

4. MULTI-CHANNEL ESCALATION
For non-responders after email sequence: LinkedIn outreach message, retargeting ad copy (2 versions), and a 1:1 direct mail/gifting trigger for accounts over $25K ACV.

5. SUCCESS METRICS DASHBOARD
Define: reactivation rate target, revenue recovered per campaign run, cost-per-reactivation, and time-to-revenue benchmarks.

Format all emails as ready-to-import sequences with HubSpot/Salesforce workflow trigger logic included.

## Advanced Customizable Version

ROLE: You are a B2B revenue recovery architect. You specialize in systematic, data-driven reactivation of churned customers and stalled pipeline using behavioral psychology, personalization at scale, and multi-channel orchestration. You treat every former customer and cold lead as a warm prospect — they already understand your category, they've evaluated your product, and they hold institutional memory that a net-new lead never has.

CONTEXT:
- Company: [Name and one-line description]
- Product category: [e.g., "Revenue Intelligence Platform" / "Procurement Automation for manufacturing"]
- ICP: [Job title, seniority, company size, industry, buying committee makeup]
- Lost revenue segments:
  * Churned customers: [How many accounts, ACV range, average tenure before churn, when they churned]
  * Cold MQLs/SQLs: [How many, original lead source, deal stage when they went dark, time since last contact]
- Churn/ghost reasons (from exit interviews, CRM notes, or hypothesis): [List top 3-5 with estimated % distribution]
- Product/pricing changes since loss: [Specific improvements, new features, pricing adjustments, new integrations — be precise]
- Competitive context: [Who did churned customers/cold leads go to? What are you hearing about those competitors now?]
- Reactivation offer budget: [What you're willing to give — discount %, free months, credits, premium onboarding]
- Compliance: [GDPR/CAN-SPAM requirements for re-permissioning lapsed contacts]
- Automation stack: [HubSpot / Marketo / Salesforce + Outreach / Apollo / Salesloft / etc.]
- Sales involvement: [At what deal size or signal does a human SDR/AE engage vs. pure email automation?]

OBJECTIVE: Build a complete revenue recovery system covering the full lifecycle from data segmentation to closed-won reactivation.

OUTPUT REQUIREMENTS:

### PART 1: LOST REVENUE AUDIT & SEGMENTATION

**Churn/Ghost Reason Taxonomy**
Create a 5-tier reason classification system:
- Category A: Price/budget (likely price-sensitive, needs ROI proof)
- Category B: Champion departure (new buyer, fresh relationship opportunity)
- Category C: Competitive switch (needs differentiation + competitor weakness proof)
- Category D: Implementation/adoption failure (needs success story + hands-on offer)
- Category E: Business change (M&A, downsizing, strategic shift — often re-emerge later)

For each category: reactivation probability score (0-100), recommended time-delay before outreach, and primary reactivation angle.

**Prioritization Scoring Model**
Score each lost contact 1-100 based on:
- Original ACV (40% weight): $50K+ = 40 pts, $20-50K = 25 pts, <$20K = 10 pts
- Time since loss (25% weight): <6 months = 25 pts, 6-12 months = 15 pts, 12-18 months = 8 pts, >18 months = 3 pts
- Reason category (20% weight): B or D = 20 pts, A or C = 12 pts, E = 6 pts
- Engagement signals (15% weight): Opened previous email/visited pricing page = 15 pts, no signal = 0 pts

Priority Tier 1 (70-100): SDR-assisted outreach within 7 days
Priority Tier 2 (40-69): Automated sequence, SDR escalates on reply
Priority Tier 3 (<40): Quarterly automated touch, no SDR involvement

### PART 2: WIN-BACK EMAIL SEQUENCES BY REASON CATEGORY

For each of the 3 highest-volume churn/ghost reason categories, produce a complete 4-email sequence.

**Sequence Architecture:**
- Email 1 — The Re-Open (Day 1)
  * Goal: Get a reply, not a conversion. Pure curiosity, zero pitch.
  * Tone: Warm, brief, peer-to-peer
  * Length: 80-120 words
  * No links, no CTAs except a simple question
  * Subject line formula: "[First name], quick question about [Company]"

- Email 2 — The Change Story (Day 6)
  * Goal: Reframe their perception of your product
  * Lead with: "Since you last used [Product], we've [specific change that addresses their churn reason]"
  * Proof point: One customer stat or specific improvement metric
  * Length: 150-200 words
  * CTA: "Would it be worth a 20-minute catch-up to show you what's different?"

- Email 3 — The Peer Mirror (Day 14)
  * Goal: Social proof from someone in their exact situation
  * Structure: "[Company similar to theirs] was in the same spot. Here's what happened when they came back."
  * Include: 2-3 sentence mini case study with specific outcome metrics
  * Length: 150-200 words
  * CTA: "Happy to share the full story if helpful"

- Email 4 — The Offer (Day 22)
  * Goal: Create urgency with a specific, time-bounded offer
  * Structure: Acknowledge the silence, make a compelling offer, set a clear expiration
  * Offer must be specific: not "let's talk" but "3 months free migration support + waived onboarding fee if we restart by [date]"
  * Length: 120-160 words
  * CTA: Calendar link or direct reply ask

For each email: write 3 subject line variations (curiosity/specificity/social proof angles), preview text (45 chars), full body copy, and the behavioral trigger logic (reply received → route to SDR; no open after Email 4 → move to quarterly nurture).

### PART 3: INCENTIVE & OFFER DESIGN

Design a tiered reactivation offer framework:

**Tier 1 (ACV $50K+):** Executive-level offers
- Dedicated success architect for 90 days
- Custom migration/implementation project at no cost
- Executive sponsor introduction + QBR commitment
- Preferred pricing lock for 24 months

**Tier 2 (ACV $15-50K):** Mid-market offers
- 2 months free on annual re-commitment
- Waived onboarding + 30-day dedicated CSM
- Free premium feature tier for 6 months
- Migration credits ($X value)

**Tier 3 (ACV <$15K):** Self-serve offers
- Extended trial of new features (30 days)
- First month free on return
- Free training cohort access
- Referral bonus for re-signing

Specify: Which offer to lead with for each churn reason category, how to sequence offers across the email series, and how to present urgency without seeming desperate.

### PART 4: MULTI-CHANNEL ESCALATION PLAYBOOK

For accounts that complete email sequence without converting:

**LinkedIn Outreach (Day 30)**
Write 3 LinkedIn message variants:
- Connection request note (300 char max) for contacts you're not connected to
- InMail message (400 char max) for cold contacts
- DM to mutual connection asking for re-introduction

**Retargeting Ad Creative (Days 15-45)**
Write copy for:
- LinkedIn single-image ad: Headline (150 chars) + Description (70 chars) + CTA
- Google Display remarketing: Headline + 2 descriptions + strong CTA
- Both should address the primary churn reason without being creepy ("We noticed you left" is forbidden)

**High-Value Direct Outreach (ACV $25K+, Day 35)**
- Handwritten note script (75 words, personal, non-salesy)
- Gifting trigger: What physical gift to send (with vendor recommendation) and the note to include
- Executive escalation: Template for VP/CRO to send a personal email to their executive counterpart

**Re-permissioning (GDPR compliance)**
For contacts >12 months lapsed: Write a GDPR-compliant re-permission email before adding to any sequence.

### PART 5: AUTOMATION WORKFLOW ARCHITECTURE

Map the complete workflow in plain language for your marketing ops team to build in [specified platform]:

**Enrollment triggers:**
- Churned customer: [X days post-cancellation date] AND [reason category tag] AND [ACV > $X]
- Cold lead: [X days since last activity] AND [deal stage = Closed Lost or Stalled] AND [no activity in CRM]

**Branch logic:**
- Reply received → notify assigned AE/SDR within 1 hour, remove from automation, log as "reactivation opportunity"
- Link clicked but no reply → add to high-intent segment, trigger SDR task in CRM
- Email opened 3+ times but no click → trigger LinkedIn ad audience addition
- No engagement after full sequence → tag "low-priority reactivation," add to quarterly newsletter

**CRM hygiene rules:**
- Update "Last Reactivation Attempt" date field on each send
- Log all reactivation touchpoints in activity history
- Set automatic re-enrollment check at 6-month intervals for Priority Tier 1-2 accounts

### PART 6: MEASUREMENT & REPORTING FRAMEWORK

Define KPIs for each 30-day campaign cycle:

**Primary Metrics:**
- Reactivation Rate: Reactivated ARR ÷ Total Lost ARR in cohort (target: 8-15%)
- Reply Rate by Sequence: Email reply rate per reason category (target: 8-12%)
- Cost per Reactivated Dollar: Total campaign cost ÷ Recovered ARR (target: <$0.15 per $1 recovered)
- Time to Revenue: Days from first re-touch to closed-won (benchmark: 45-75 days)

**Secondary Metrics:**
- Offer acceptance rate by tier
- Channel attribution: Which touchpoint (email, LinkedIn, retargeting, direct mail) drove the reply
- Reason category win-back rates: Which churn reasons are most/least recoverable

**Monthly Revenue Recovery Report Template:**
Produce a template with: Lost ARR cohort size, % contacted, reply rate, demo rate, reactivation rate, recovered ARR, cost, ROI. Include an executive summary paragraph and recommended adjustments for next cycle.

## Example Input/Output

**Input Example:**
Product: Vantage Analytics — an AI-powered spend analysis platform for procurement teams at $100M-$2B manufacturers
Lost segment: Both churned customers AND cold SQLs
ACV: $35,000 average
Time in database: Churned 4-14 months ago / Cold SQLs 90-240 days dark
Top churn/ghost reasons:
  1. Lost to Coupa (35% of churn) — thought we were "too niche"
  2. Champion left (28%) — new procurement director didn't re-sign
  3. Implementation stalled (22%) — couldn't get IT resources to integrate with SAP
What's changed: New native SAP connector (zero IT involvement), launched Coupa comparison ROI calculator, 40% faster time-to-first-insight, $8K/seat vs prior $12K/seat
Reactivation budget: Up to 2 free months + free SAP connector setup
Stack: Salesforce + Outreach + LinkedIn Sales Navigator
Sales involvement: SDR for $25K+ ACV replies, self-serve demo booking below that

**Output Example (Email 2 for Champion Departure segment):**

Subject line options:
1. "Vantage in 2026 looks very different, [Name]"
2. "What changed at Vantage since [Company] was a customer"
3. "3 manufacturers that came back — and why"

Preview text: "The SAP connector alone changes everything."

Body:
> Hi [First name],
>
> When [Company] was with us, one of the biggest friction points was the SAP integration — it required IT involvement and delayed time-to-value by weeks.
>
> We rebuilt it. The new Vantage-SAP connector is now 100% no-code, deploys in under 4 hours, and pulls live spend data without a single IT ticket. It's the most-requested feature we've ever shipped.
>
> On top of that: we're at $8K/seat now (down from $12K), and our median time-to-first-insight dropped from 3 weeks to 4 days.
>
> We've had 7 former customers return in the last 90 days. Happy to share what pushed them back if it'd be useful.
>
> Worth a 20-minute catch-up to see what's different?
>
> [Name]

CTA: Reply or book a 20-min slot: [Calendly link]
Exit rule: If replied → Salesforce task created for AE within 1 hour; if not opened by Day 14 → advance to Email 3.

**Reactivation Rate Achieved (Example):** In a real-world comparable scenario — a SaaS company with 180 churned accounts in the $30-50K ACV range ran this system, recovered 14 accounts in 90 days = $490K ARR recovered with $12K in campaign costs.

## Success Metrics

- **Reply rate target:** 8-14% across full sequence (industry average cold email is 1-3%; former customers respond at 5-10x that rate)
- **Reactivation conversion rate:** 2-5% of total lost contacts per campaign cycle
- **Revenue recovered per 100 contacts reached:** $40K-$150K ARR (varies by ACV)
- **Cost-per-reactivated-dollar:** Under $0.20 (email + LinkedIn + retargeting combined)
- **Time-to-revenue:** 45-90 days from first touch to closed-won
- **Best indicator of sequence health:** Email 2 open rate — if under 25%, subject lines or segmentation need work

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Lead-Nurture-Sequence-&-Pipeline-Acceleration-Email-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Customer-Retention-&-Expansion-Revenue-Engine.md`
- `../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/Churn-Prevention-Expansion-Revenue-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Outbound-Prospecting/Multi-Channel-Outbound-Sequence-Orchestrator.md`

## Integration Tips

- **Salesforce:** Create a custom "Lost Revenue Recovery" opportunity stage. Enroll churned accounts via a report filter on `Churn Date` + `ACV` fields. Use Salesforce Flows to auto-enroll qualifying accounts into Outreach sequences on a rolling weekly basis.
- **HubSpot:** Build a "Win-Back" workflow triggered by `Customer Status = Churned` AND `Days Since Churn ≥ 30`. Use Contact Score to prioritize; route scores 70+ to an SDR task queue automatically.
- **Outreach / Salesloft:** Create a dedicated "Win-Back" sequence library by churn reason. Use Outreach's sequence analytics to A/B test subject lines across reason categories.
- **LinkedIn Sales Navigator:** Use "Past Customer" filter + "Changed Jobs in Last 90 Days" to find former champions who moved to new companies — they're warm prospects for a net-new deal AND potential internal champions for re-signing their old employer.
- **6sense / Bombora intent data:** Layer in intent signals to prioritize which churned accounts are actively researching your category again — these are Priority Tier 1 regardless of ACV.
- **Zapier automation:** Set up a Zap that fires when a churned account visits your pricing page → immediately notifies the assigned AE and adds to the high-intent retargeting audience in Google Ads.

## Troubleshooting

**Problem:** Very low reply rates (<3%) on Email 1.
**Solution:** Email 1 is probably too long or has a call-to-action. Cut it to 80 words max. Ask exactly one question. Remove all links and product mentions. Test subject lines: the curiosity angle ("Quick question about [Company]") almost always beats feature-focused lines for win-back cold opens.

**Problem:** Legal/compliance team flagging outreach to contacts >12 months lapsed.
**Solution:** Run all contacts >12 months through a GDPR re-permission email first (see Part 4 template). In the US, CAN-SPAM allows outreach to former customers for up to 18 months without re-permission, but best practice is to add an easy unsubscribe and honor all opt-outs immediately. Always remove unsubscribed contacts before importing into sequences.

**Problem:** Reactivation offer (2 free months) isn't moving the needle.
**Solution:** Price discounts rarely win back customers who left for non-price reasons. First, audit your churn reasons — if 60%+ left due to implementation issues or champion departure, switch your lead offer to "dedicated success resource" or "executive introduction" rather than discounting. Discounts train customers to churn and wait for a deal.

## Version History
- v1.0: Initial creation (auto-generated)
