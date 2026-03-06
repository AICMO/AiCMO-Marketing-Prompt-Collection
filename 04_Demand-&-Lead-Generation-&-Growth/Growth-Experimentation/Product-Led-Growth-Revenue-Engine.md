# Product-Led Growth Revenue Engine - PQL Scoring, Trial Conversion & Expansion Automation

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** plg, product-led-growth, pql, free-trial, freemium, activation, expansion-revenue, saas, b2b, growth

## Overview
Converts raw product usage data into a ranked list of Product Qualified Leads (PQLs), generates personalized in-app and email activation sequences, and builds expansion revenue triggers for existing accounts. Use it when your free trial or freemium tier isn't converting at the rate your product deserves — or when you know expansion revenue is being left on the table because no one is watching the usage signals.

## Quick Copy-Paste Version

You are a PLG growth strategist. I will give you product usage data for a cohort of free trial or freemium users. Your job is to score them, identify the highest-conversion opportunities, and generate the outreach or in-app message for each.

My product: [Product Name] — [1-sentence description, e.g., "AI-powered project management for software teams"]
Trial length: [e.g., "14-day free trial"] or Freemium model: [e.g., "free up to 3 users"]
Paid conversion goal: [e.g., "upgrade to Team plan at $49/month per seat"]
Key activation milestone (the "aha moment"): [e.g., "user creates their first automated workflow within 7 days"]

User cohort data:
[Paste in this format — one user/account per line]
- Account: [Company] | Users: [#] | Days in trial: [#] | Actions taken: [list key actions, e.g., "created 3 projects, invited 2 teammates, ran 1 report"] | Last active: [X days ago] | Plan viewed: [yes/no]

For each account, deliver:
1. PQL Score (0-100) with a 2-sentence explanation of why
2. Conversion tier: HOT (act today), WARM (nurture this week), COLD (re-engagement needed), DEAD (deprioritize)
3. The single biggest signal that this account is — or is not — about to convert
4. Exact next action: in-app message, email subject line + first sentence, or sales touch with specific talking point
5. The one friction point most likely blocking their conversion and how to remove it

Rank all accounts HOT to DEAD. HOT accounts need an outreach message ready to send today.

## Advanced Customizable Version

ROLE:
You are a Senior PLG Growth Strategist with 12+ years of experience at product-led SaaS companies including Slack, Figma, Notion, and Calendly. You specialize in PQL model design, activation funnel optimization, and building self-serve expansion loops. You think in behavioral cohorts, not individual users. You know that the difference between a 15% trial conversion rate and a 35% trial conversion rate is almost never the product — it's the activation motion.

CONTEXT:
Company: [Company Name]
Product: [Description — what it does, who it's for, what outcome it delivers]
Business model: [Free trial / Freemium / Reverse trial — describe the limits/duration]
Pricing tiers: [e.g., "Free: up to 3 users / Starter: $29/mo / Team: $99/mo / Business: $299/mo"]
ICP: [e.g., "B2B SaaS companies, 10-200 employees, product managers and engineering leads"]
Defined activation event (the proven "aha moment"): [e.g., "invites a second user AND completes first integration within 5 days"]
Current trial-to-paid conversion rate: [e.g., "18%"]
Average time-to-convert for paying customers: [e.g., "6 days"]
CRM/marketing automation in use: [HubSpot / Salesforce + Marketo / Intercom / Customer.io / other]
In-app messaging tool: [Intercom / Pendo / Appcues / Chameleon / none]

PRODUCT USAGE DATA:
[Paste structured usage data — see format in Quick Copy-Paste Version above, or export from your analytics tool (Mixpanel, Amplitude, Heap, PostHog, Segment)]

OBJECTIVE:
Perform a full PLG revenue analysis covering four layers:

LAYER 1 — PQL SCORING MODEL
Build a weighted PQL score for each account using the DEPTH framework:
- D — Depth of Usage (0-25): How many core features has the account activated? Are they using features that correlate with paid conversion in historical data?
  - 20-25: 3+ core features used, activated aha moment
  - 10-19: 1-2 core features, partial activation
  - 0-9: Surface-level or no meaningful engagement
- E — Expansion Signals (0-25): Are usage patterns showing they are hitting plan limits or growing into paid territory?
  - 20-25: Approaching seat/usage/storage limits, added multiple users, upgraded workspace settings
  - 10-19: Moderate growth signals, some team usage
  - 0-9: Solo user, minimal footprint
- P — Persona Fit (0-25): Does what we know about this account match the ICP?
  - 20-25: Company size, industry, and role match ICP exactly; domain suggests budget authority
  - 10-19: Partial ICP match
  - 0-9: Outside ICP or unknown
- T — Time Sensitivity (0-25): Where are they in the trial lifecycle, and how recently were they active?
  - 20-25: Active in last 48 hours, trial expires within 5 days OR just hit the aha moment
  - 10-19: Active in last 7 days, mid-trial
  - 0-9: No activity in 7+ days, trial nearly expired without activation

Score each account (total max = 100). Classify:
- HOT: 75-100 — sales or high-touch outreach within 24 hours
- WARM: 50-74 — personalized email + in-app nudge this week
- COLD: 25-49 — re-engagement sequence, address identified friction
- DEAD: 0-24 — low-effort win-back only, do not burn cycles

LAYER 2 — ACTIVATION GAP ANALYSIS
For each account not yet at the aha moment, identify:
a) Which specific activation step they are stuck on (based on actions taken vs. actions needed)
b) The most common objection or friction at that step (from your knowledge of PLG patterns)
c) The exact in-app tooltip, checklist item, or email that removes that friction
d) Estimated conversion probability lift if friction is removed (Low / Medium / High)

LAYER 3 — EXPANSION REVENUE TRIGGERS (for existing paying accounts, if provided)
Scan usage data for expansion signals:
- Seat expansion: Multiple users invited but not yet added to paid seats
- Feature upgrade triggers: Repeated use of a feature gated behind a higher tier
- Usage limit proximity: Within 20% of a plan cap (storage, API calls, exports, etc.)
- Cross-sell readiness: Consistent use patterns that indicate a complementary product or add-on would deliver immediate value
For each trigger, output: account name, trigger type, estimated expansion ARR, and the exact message (email subject + 2-sentence pitch) to initiate the conversation.

LAYER 4 — VIRAL LOOP ASSESSMENT
Identify which HOT and WARM accounts have the highest referral/viral potential:
- Multi-user accounts where invited collaborators are from different organizations (network expansion signal)
- Accounts in industries with high peer-to-peer influence (agencies, consultancies, product teams)
- Power users who have completed advanced workflows that generate shareable outputs
For each viral candidate, suggest one specific in-product action or reward to activate the referral loop.

OUTPUT FORMAT:
1. Ranked account table: PQL Score | Tier | Top Signal | Recommended Action
2. Activation gap analysis: one paragraph per stuck account
3. Expansion revenue opportunity list: sorted by estimated ARR impact
4. Viral loop candidates: list with suggested trigger action
5. Cohort-level insight: 3 bullets summarizing the biggest pattern across this entire user cohort and what it implies for onboarding or pricing changes

CONSTRAINTS:
- Every recommended outreach message must be specific to that account's actual usage data — no generic templates
- Expansion pitches must reference the exact feature or limit the account is hitting, not a generic upsell
- Do not recommend a sales call for accounts scoring below 50 unless there is a strong Persona Fit score (20+) combined with a clear expansion trigger
- All email subject lines must be under 50 characters and pass the "would a human write this?" test — no ALL CAPS, no excessive punctuation

## Example Input/Output

**Input:**
Company: Flowdeck (B2B SaaS — visual workflow automation for operations teams)
Trial: 14-day free trial, converts to Team plan at $79/month per seat
Aha moment: Creates and shares a workflow with at least one teammate within 7 days
Current conversion rate: 21%
ICP: Operations managers at companies 50-500 employees

Account data:
- Account: Meridian Logistics | Users: 4 | Days in trial: 9 | Actions: created 6 workflows, shared with 3 teammates, connected Slack integration, viewed pricing page 2x | Last active: 1 day ago | Plan viewed: Team plan
- Account: Cobalt Design Studio | Users: 1 | Days in trial: 11 | Actions: created 1 workflow (incomplete), no teammates invited, visited help docs twice | Last active: 4 days ago | Plan viewed: no
- Account: Apex Insurance Group | Users: 2 | Days in trial: 3 | Actions: completed onboarding checklist, created 2 workflows, invited 1 teammate | Last active: 0 days ago | Plan viewed: Starter plan

**Output:**

**Ranked Account Table:**

| Account | PQL Score | Tier | Top Signal | Recommended Action |
|---|---|---|---|---|
| Meridian Logistics | 91 | HOT | Viewed pricing 2x with 4 active users + 5 days left in trial | Sales email today referencing their Slack integration + 4-seat Team quote |
| Apex Insurance Group | 68 | WARM | Hit aha moment on day 3 — unusually fast activation pace | In-app pop-up: "Your team is off to a fast start — here's what 4+ user teams unlock" |
| Cobalt Design Studio | 28 | COLD | Solo user stuck before aha moment with 3 days left | Rescue email: offer 5-day extension + link to 3-minute workflow template video |

**Meridian Logistics — Sales Email:**
Subject: your Flowdeck team is ready to upgrade
Hi [Name], I noticed your team of four has been building workflows nonstop — and you've been back to the pricing page twice. Happy to put together a Team plan quote for your 4 seats with an operations-team discount we're running this month. Worth a 15-minute call this week?

**Apex Insurance Group — In-App Message:**
"You've already hit the milestone most teams take 8 days to reach. Teams that expand to 4+ users on Flowdeck cut process documentation time by an average of 6 hours/week. Want to see what that looks like for insurance ops workflows?"

**Cobalt Design Studio — Re-engagement Email:**
Subject: your workflow is halfway there
Hi [Name], noticed you started building a workflow in Flowdeck but haven't had a chance to finish. Most ops teams hit their first win within 20 minutes using our process templates — I'm dropping a link to the 3 most popular ones for design studios below. Also extending your trial by 5 days so you have time to see it in action.

**Cohort Insight:**
- Activation speed in the first 3 days is the strongest predictor of conversion in this cohort — teams that create 2+ workflows by day 3 convert at 3x the rate of those who don't.
- Solo users who haven't invited a teammate by day 7 almost never convert — the viral/collaboration trigger is also the conversion trigger for this product.
- The pricing page visit is a strong HOT signal but only when combined with multi-user activity — solo users who visit pricing without inviting teammates rarely convert, suggesting a pricing page CTA specifically for solo users is a conversion gap.

## Success Metrics
- PQL model accuracy: 70%+ of HOT accounts convert within the trial window
- Activation rate lift: Increase in % of trials that hit the aha moment within the first 7 days (target: +10 percentage points)
- Trial-to-paid conversion rate: Overall free-to-paid conversion, measured month-over-month
- Time-to-convert: Days from trial start to first payment (target: reduce by 20%)
- Expansion ARR: Monthly revenue from upgrades and seat expansions triggered by this engine
- PQL-to-sales cycle length: HOT PLG leads should close 40-60% faster than MQL-sourced leads

## Related Prompts
- [Lead Scoring Automation](../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md) — for scoring inbound MQLs alongside PQLs in a unified revenue model
- [Customer Lifecycle Optimization](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Customer-Lifecycle-Optimization.md) — for optimizing the full post-conversion lifecycle after PLG acquisition
- [Email Personalization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Email-Personalization-Engine.md) — for scaling the personalized activation and expansion emails this engine generates
- [A/B Testing Automation](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/A-B-Testing-Automation.md) — for systematically testing which activation nudges and PQL score thresholds perform best

## Integration Tips
- **Amplitude / Mixpanel / PostHog**: Export the "User Activity" or "Account Activity" report filtered to your current trial cohort, paste directly into the Advanced Version's usage data field. Map your event taxonomy to the DEPTH scoring dimensions before pasting.
- **Intercom**: Use the PQL tier output (HOT/WARM/COLD) to create Intercom segments. Trigger HOT in-app messages using Intercom's company-level rules; route WARM accounts into a drip series; suppress DEAD accounts from all sequences to protect deliverability.
- **HubSpot**: Create a custom "PQL Score" property on the Company object. Use a workflow to enroll HOT accounts (score 75+) into a sales task sequence and WARM accounts into a marketing nurture enrollment. Sync the "Top Signal" field as a contact note for sales context.
- **Salesforce + Gainsight**: For expansion triggers, create a Gainsight CTA (Call to Action) rule that fires when usage hits 80% of any plan limit. Route to CSM queue with the expansion ARR estimate pre-populated from this engine's output.
- **Customer.io**: Build behavioral segments using the DEPTH score dimensions as segment conditions. Trigger in-app or email messages based on the specific activation step each account is stuck on — map each step to a Customer.io segment for precise targeting.
- **Zapier / Make**: Connect your product analytics webhook (PostHog, Heap) to a Google Sheet that auto-formats incoming trial data into the input template. Feed the sheet to this prompt via a scheduled AI workflow to get a fresh PQL ranking every Monday morning.

## Troubleshooting

**Problem: PQL scores look right but HOT accounts still aren't converting.**
Check whether your defined aha moment is actually correlated with paid conversion. Re-analyze your last 3 months of converted customers: what were the top 3 actions they all took in their first 7 days? If that doesn't match your current aha moment definition, redefine it before re-running the scoring model. Also audit whether the recommended outreach is actually being sent — PQL scoring without execution is a reporting exercise, not a growth engine.

**Problem: The engine keeps flagging solo users as HOT because they have deep feature usage but they never convert.**
Add a hard multiplier to the Expansion Signals dimension: if Users = 1 and no teammates have been invited by day 5, cap the total PQL score at 60 regardless of other signals. Solo-user deep engagement is a vanity metric for most B2B PLG products — conversion almost always requires team adoption. Alternatively, create a separate "champion activation" track for solo power users focused on getting them to invite a teammate as the primary CTA.

**Problem: Expansion revenue triggers exist but CSMs aren't using them.**
The bottleneck is usually the hand-off format, not the signal quality. Instead of sending CSMs a score or a list, send them a pre-written email they can send in two clicks. The expansion message in Layer 3 output should be copy-paste-ready. If CSMs are still not acting, run the expansion email directly from marketing automation (Customer.io or HubSpot) without requiring a human step — for seat expansion and limit-proximity triggers, a fully automated email from the CSM's email address outperforms a manual outreach in both speed and conversion rate.

## Version History
- v1.0: Initial creation (auto-generated)
