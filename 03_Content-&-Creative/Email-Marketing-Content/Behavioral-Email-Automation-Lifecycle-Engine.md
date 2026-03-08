# Behavioral Email Automation Lifecycle Engine - Trigger-Based Revenue Email System

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** email-automation, lifecycle-marketing, behavioral-triggers, b2b-saas, revenue-operations

## Overview
Designs and writes a complete behavioral email automation system triggered by user actions, product signals, and lifecycle milestones — producing ready-to-deploy email sequences, subject lines, personalization tokens, and HubSpot/Klaviyo workflow logic for every stage from onboarding to win-back.

## Quick Copy-Paste Version

You are a senior lifecycle marketing strategist specializing in behavioral email automation for B2B SaaS. I need a complete trigger-based email system for my product.

PRODUCT CONTEXT:
- Product: [Your SaaS product name and one-sentence description]
- ICP: [Ideal customer — e.g., "VP of Engineering at 50-500 person tech companies"]
- Primary value: [Core outcome your product delivers]
- Trial/free tier: [Yes/No — describe if yes]
- Key activation milestone: [The "aha moment" — e.g., "first dashboard created", "first integration connected"]
- Average sales cycle: [e.g., 14 days for PLG, 60 days for sales-assisted]

Generate a complete behavioral email automation system with these 6 trigger sequences:

1. SIGN-UP / TRIAL START (Days 0-3)
   - Welcome email (Day 0): Personal, value-focused, sets expectations
   - Activation nudge (Day 1 if no activation): Addresses the #1 activation blocker
   - Quick win email (Day 2 if activated): Celebrates milestone, shows next value step

2. ACTIVATION ACHIEVED
   - Triggered immediately when user hits activation milestone
   - Reinforce value, introduce power features, set up expansion path

3. TRIAL DAY 7 — ENGAGEMENT CHECK
   - Two variants: engaged users (upgrade path) vs. unengaged users (rescue sequence)

4. TRIAL EXPIRY (72h, 24h before expiry)
   - Urgency without being sleazy — value reminder + friction removal

5. CHURN SIGNAL DETECTED (no login 7+ days post-activation)
   - Re-engagement sequence: 3 emails over 10 days
   - Email 1: "Did something break?" check-in
   - Email 2: New feature or use case they haven't tried
   - Email 3: Direct offer or human outreach trigger

6. EXPANSION / UPSELL (triggered by usage hitting 80% of plan limit)
   - Data-driven upgrade prompt with ROI framing

For EACH email, provide:
- Subject line (+ 2 A/B test variants)
- Preview text (90 chars max)
- Full email body (200-350 words, conversational B2B tone)
- Personalization tokens to use ({{first_name}}, {{company}}, {{activation_event}}, etc.)
- CTA button text + URL structure
- Send timing logic (immediate vs. X hours after trigger)
- Suppression conditions (who should NOT receive this email)

Output in structured format ready to configure in HubSpot Workflows or Klaviyo Flows.

## Advanced Customizable Version

ROLE: You are a lifecycle marketing automation architect with 15+ years building behavioral email systems for B2B SaaS companies from Series A through IPO. You've generated over $50M in pipeline through trigger-based email programs. You combine conversion copywriting (Cialdini principles, Jobs-to-be-Done framing) with marketing automation engineering.

PRODUCT INPUTS:
- Company: [Company name]
- Product: [Product name + one-sentence description]
- ICP Primary: [Title, company size, industry vertical]
- ICP Secondary: [If applicable]
- Core value proposition: [The specific outcome your product delivers in measurable terms]
- Primary activation event: [Exact behavioral trigger that signals value realization]
- Secondary activation events: [2-3 additional milestones]
- Pricing model: [Freemium / Trial / Demo / PLG / Sales-assisted hybrid]
- Trial length: [X days]
- Average time-to-activation: [X hours/days based on your data or estimate]
- Biggest drop-off point: [Where users abandon most frequently]
- Top objection to purchase: [Price / Security / Integrations / Internal buy-in / Other]
- Current email tool: [HubSpot / Klaviyo / Marketo / ActiveCampaign / Customer.io]
- CRM: [Salesforce / HubSpot / Pipedrive]

SEGMENTATION VARIABLES (use to fork sequences):
- Segment A: Self-serve / PLG users (no sales touch)
- Segment B: Sales-assisted (SDR will follow up)
- Segment C: Enterprise (>500 employees, requires security review)
- Segment D: Re-sign-up (churned customer returning)

BEHAVIORAL TRIGGER ARCHITECTURE — Design complete sequences for:

SEQUENCE 1: ONBOARDING (Triggers: account created)
Goal: Get user to primary activation event within 72 hours
Emails: 4-email sequence (Day 0, Day 1 if no activation, Day 2 if no activation, Day 3 final push)
Framework: Jobs-to-be-Done — address the specific job they hired your product for
Psychological principle: Foot-in-the-door (small commitment → big commitment)

SEQUENCE 2: POST-ACTIVATION EXPANSION (Triggers: primary activation event completed)
Goal: Drive to secondary activation and team expansion (seat growth)
Emails: 3-email sequence over 7 days
Framework: Social proof + reciprocity (share a benchmark, case study, or data gift)

SEQUENCE 3: TRIAL-TO-PAID CONVERSION (Triggers: day 7 of trial, day 12, day 14/expiry)
Goal: Convert trial to paid with minimum friction
Variant A (engaged users >3 sessions): Value reinforcement + ROI calculation
Variant B (unengaged users <3 sessions): Diagnose blocker + offer human help
Framework: Loss aversion + commitment/consistency (reference what they've already built)

SEQUENCE 4: WIN-BACK / RE-ENGAGEMENT (Triggers: 7 days no login post-activation)
Goal: Reactivate churned/dormant users before trial expires or after subscription lapses
Emails: 3-email sequence over 14 days
Email 1 (Day 7): Check-in framing — "Did something come up?"
Email 2 (Day 10): New value hook — feature or use case they never tried
Email 3 (Day 14): Final offer or break-up email (honest, respectful, keeps door open)
Framework: Foot-in-the-door reversal — make re-engagement trivially easy

SEQUENCE 5: CHURN PREVENTION (Triggers: usage drops below 20% of prior 30-day average)
Goal: Proactively intervene before cancellation intent
Emails: 2-email sequence + SDR handoff trigger for Segment B/C
Email 1: Business outcome check-in (not product-focused)
Email 2: Success story from similar company at same stage
SDR trigger: If no engagement with Email 1 or 2, create task in CRM

SEQUENCE 6: EXPANSION / UPSELL (Triggers: usage at 80% of plan limit OR new buying signal in CRM)
Goal: Upgrade current tier or expand seats
Emails: 2-email sequence
Email 1: Data-driven framing — "You're about to hit your limit, here's what that means"
Email 2: Case study of company that upgraded + ROI they saw
Framework: Scarcity + social proof

FOR EVERY EMAIL PROVIDE:
1. Subject line (primary) + 2 A/B test variants with predicted open rate lift
2. Preview text (max 90 characters)
3. Full email body (exact copy, 200-400 words)
4. Personalization tokens: List all dynamic variables used
5. CTA: Button text + destination URL template
6. Timing: Exact trigger logic (e.g., "Send 2 hours after trigger event, between 9am-11am recipient local time")
7. Suppression logic: Who to exclude (e.g., "suppress if already converted", "suppress if sales-owned account")
8. Success metric: What KPI determines this email is working
9. Automation tool config note: Specific workflow/flow setup tip for [their email tool]

COPYWRITING STANDARDS:
- Subject lines: Max 45 characters, action-oriented, no clickbait
- Opening line: Never start with "I hope this email finds you well" — start with their context
- Body: Conversational B2B tone. Short paragraphs (2-3 sentences). One idea per email.
- CTA: One primary CTA per email. Avoid "Learn More" — use outcome-focused language.
- Signature: Friendly personal signature from a human (not "The [Product] Team")

OUTPUT FORMAT:
Organize by sequence. For each sequence, include a workflow diagram in text format showing trigger → condition forks → email nodes → exit conditions. Then provide full email copy for each node.

## Example Input/Output

**Input Example:**
- Company: Notably (user research platform)
- ICP: UX Researchers and Product Managers at B2B SaaS companies, 100-1,000 employees
- Core value: Automatically transcribe, tag, and synthesize user interview recordings into actionable insights
- Primary activation event: First project created + first recording uploaded and analyzed
- Trial: 14-day free trial, no CC required
- Biggest drop-off: Day 2-3, users upload a recording but don't return to view the analysis
- Top objection: "We already use Dovetail / Notion for research notes"
- Email tool: HubSpot

**Output Example (Sequence 1, Email 2 — Activation Nudge, Day 1):**

> **Subject:** Your first insight is 4 minutes away (really)
> **Preview text:** You uploaded a recording — here's the one step to unlock the analysis.
>
> **Body:**
> Hey {{first_name}},
>
> You uploaded your first recording to Notably yesterday — nice work. A lot of researchers never get past this step.
>
> Here's the only thing standing between you and your synthesized insights: click "Analyze" on the recording.
>
> That's it. Notably's AI will tag themes, extract quotes, and surface the top 5 insights from your interview in about 4 minutes.
>
> [→ Analyze My Recording Now] — links to {{project_url}}
>
> If you ran into a technical issue (file format, upload size), reply to this email and I'll fix it in 10 minutes.
>
> — Sarah, Head of Customer Success at Notably
>
> **Personalization tokens:** {{first_name}}, {{project_url}}, {{recording_filename}}
> **Suppression:** Do not send if activation event already fired
> **Timing:** 22 hours after sign-up, only if activation event has NOT fired, send between 8am–11am recipient local time
> **HubSpot config note:** Use "Contact property: activation_event_fired is unknown or equal to false" as enrollment condition in Workflow

---

**Sequence 3 Variant B (Unengaged trial, Day 10):**

> **Subject:** Honestly, what got in the way?
> **Preview text:** You haven't logged back in — I'd rather ask than assume.
>
> **Body:**
> Hey {{first_name}},
>
> You signed up for Notably {{days_since_signup}} days ago but haven't had a chance to dig in. That happens — research tooling evaluations tend to compete with actual research work.
>
> I won't send you a feature list. Instead: what got in the way?
>
> Was it the file format? (We support .mp4, .mov, .m4a, .mp3 — and Zoom links directly)
> Did you not have a recording ready to test it with? (I can send you a sample interview)
> Is someone else on your team the right person to evaluate this? (Happy to loop them in)
>
> Just reply and I'll help directly. Takes 2 minutes.
>
> Or if you'd rather see it work on your actual data: [Book a 20-min live demo →]
>
> — Jamie, Solutions at Notably

## Success Metrics

- **Onboarding sequence:** Activation rate within 72h (target: >40% for PLG products)
- **Trial conversion sequence:** Trial-to-paid conversion rate (benchmark: 15-25% for B2B SaaS)
- **Win-back sequence:** Re-engagement rate within 14 days (benchmark: 8-15%)
- **Expansion sequence:** Upgrade click-through rate (benchmark: 5-12%)
- **Overall email health:** Unsubscribe rate <0.3% per send, spam complaint rate <0.08%
- **Per-email benchmarks:** Open rate >30% (behavioral emails outperform newsletters), CTR >4%

## Related Prompts

- [Email Sequence Automation](./Email-Sequence-Automation.md)
- [Customer Retention & Expansion Revenue Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Customer-Retention-&-Expansion-Revenue-Engine.md)
- [Product-Led Growth Revenue Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Product-Led-Growth-Revenue-Engine.md)
- [Customer Onboarding Intelligence System](../../06_Customer-Success-&-Retention/Customer-Onboarding-&-Activation/Customer-Onboarding-Intelligence-System.md)

## Integration Tips

- **HubSpot Workflows:** Use "Contact-based" workflows with enrollment triggers set to behavioral events synced via HubSpot tracking code or API. Use "Branch" steps to fork sequences by segment. Set re-enrollment to "off" after first completion to prevent duplicate sends.
- **Klaviyo Flows:** Use "Metric" triggers (e.g., "Completed Onboarding Step") synced from your product via Klaviyo's Track API. Use Flow Filters to suppress converted users. A/B test subject lines using Klaviyo's built-in split testing at the message level.
- **Customer.io:** Best for event-driven triggers. Use `identify()` calls to sync user properties (plan tier, activation status, usage count) and `track()` calls for behavioral events. Create Segments for suppression logic.
- **Salesforce Marketing Cloud (SFMC):** Map triggers to Journey Builder entry events. Use Decision Splits for Variant A/B branching. Sync suppression lists via Salesforce CRM Contact status fields.
- **Zapier:** Use Zapier to bridge your product database → email tool if you lack a native integration. Trigger: "New row in Airtable matching activation_event = true" → Action: "Add to HubSpot List" → HubSpot Workflow auto-enrolls.
- **Segment.com:** If using Segment as your CDP, route `track()` events to your email tool as a Destination. This gives you a single behavioral data layer powering all sequences across tools.

## Troubleshooting

**Issue: Activation nudge emails are sending to users who already activated**
Solution: The suppression condition is not firing fast enough due to data sync latency. Add a 30-minute delay before the activation check step in your workflow. In HubSpot, use a "Re-check contact property" wait step rather than a static delay. Alternatively, suppress based on a list (e.g., "Activated Users" list) that updates via API webhook from your product.

**Issue: Open rates on Day 0 welcome email are below 25%**
Solution: Check send timing — welcome emails sent instantly after sign-up convert 3-5x better than those sent with a delay. Ensure your from-name is a person ("Sarah from Notably"), not a brand name ("Notably"). Audit your email authentication: SPF, DKIM, and DMARC must all pass or deliverability suffers. Use mail-tester.com to score before launching.

**Issue: Win-back sequence is triggering for active paying customers who temporarily didn't log in**
Solution: Add a contact property filter to exclude users with `subscription_status = active AND mrr > 0` from the churn signal trigger. The 7-day no-login trigger should only fire for trial users or free tier users. Segment your workflows by lifecycle stage (lead, trial, customer) to prevent cross-contamination of sequences.

## Version History
- v1.0: Initial creation (auto-generated)
