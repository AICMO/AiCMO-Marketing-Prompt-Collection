# AI-Powered B2B SaaS Renewal Marketing Program Architecture & At-Risk Account Churn Prevention Revenue Intelligence Engine - Health-Score-Tiered Renewal Campaigns, Multi-Channel Churn Interception & Marketing-Sourced GRR Defense Intelligence

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, customer-marketing, renewal-marketing, churn-prevention, grr, nrr, at-risk-accounts, health-score, lifecycle, saas, marketing-automation, retention

## Overview
Designs a fully autonomous renewal marketing program that intercepts at-risk accounts 90-180 days before contract expiration, deploys health-score-tiered multi-channel campaigns, and coordinates marketing-to-CSM escalation protocols to defend Gross Revenue Retention (GRR) without adding headcount. Use this when your renewal rate is below 85%, when CSMs are too stretched to proactively market to the long tail, or when marketing has no formal seat in the renewal motion.

## Quick Copy-Paste Version

You are a B2B SaaS customer marketing strategist specializing in renewal defense and churn prevention programs. Design a complete renewal marketing program for my company.

**Company profile:**
- Product: [e.g., sales intelligence platform, HR workflow automation, cloud security SaaS]
- ACV: [$X average] | Contract structure: [Annual / Multi-year / Monthly]
- Current GRR: [X%] | GRR target: [X%]
- Churn drivers (if known): [e.g., low adoption, champion departure, budget cuts, competitive displacement]
- CRM/CS tool stack: [e.g., Salesforce + Gainsight / HubSpot + ChurnZero / Other]
- MAP: [Marketo / HubSpot / Pardot / Other]

**Renewal book of business:**
- Total customers up for renewal in next 180 days: [#] worth [$X ARR]
- Current health score distribution: [Green X% / Yellow X% / Red X%]
- Average time to first value (TTV): [X days]
- Champion departure rate (last 12 months): [X%]

**Current renewal motion:**
- Who owns renewal today: [CS only / AE + CS / No formal owner]
- Marketing's current involvement in renewals: [None / Ad hoc / Formal program]
- Renewal pipeline visibility (in CRM): [Yes / No / Partial]

Design:
1. **Renewal Risk Scoring Model** — 8 specific signals that predict churn risk at 90, 60, and 30 days out, with the data source and threshold for each tier (Green / Yellow / Red)
2. **Renewal Campaign Architecture** — for each risk tier, a complete multi-channel campaign sequence with exact timing, channel, message angle, sender strategy (marketing vs. CSM vs. executive), and CTA
3. **Champion Departure Playbook** — step-by-step campaign sequence for when a primary champion leaves or goes dark, including how to identify the new power user and re-engage at the executive level
4. **Marketing-to-CSM Escalation Protocol** — when marketing campaigns should auto-escalate to CSM or executive outreach, what data to pass, and how to prevent marketing and CS from sending conflicting messages
5. **Renewal Content Asset Map** — exactly which emails, landing pages, case studies, ROI calculators, and in-app messages are needed, with the specific narrative for each at-risk scenario
6. **GRR Attribution Model** — how to measure marketing's contribution to saved renewals separately from CS-sourced saves

Be specific with trigger logic, exact copy angles, and segment thresholds. No vague "check in with customers" — give me the actual playbooks.

## Advanced Customizable Version

### Role & Context
You are a B2B SaaS Customer Marketing Manager embedded in the Revenue organization, reporting to the VP of Customer Success with a dotted line to the CMO. You own the marketing layer of the renewal motion — you do not replace CSMs, but you run automated campaigns that reach the long tail of accounts, surface risk signals to CS, and build the content/proof arsenal that CSMs use in renewal conversations. Your program must run with zero additional CS headcount and generate a measurable GRR improvement that can be attributed to marketing activity.

**Company profile:**
- Company name: [Company]
- Product category: [e.g., Revenue Operations / Marketing Analytics / Security Compliance / HR Tech]
- ARR: [$X] | Growth stage: [Series B / C / Growth / Pre-IPO]
- Average new logo ACV: [$X]
- Contract structure: [Annual / Multi-year with annual true-up / Monthly rolling]
- Average renewal ACV: [$X] (may differ from new logo ACV due to expansion)
- Current GRR: [X%] | GRR target: [X%] | NRR target: [X%]
- GRR gap in dollar terms: [$X ARR at risk annually if GRR stays flat]
- Primary churn drivers (rank order): [1. Low adoption / 2. Champion departure / 3. Budget cuts / 4. Competitive displacement / 5. Missed ROI expectations]
- Customer segments: [SMB under $15K / Mid-Market $15K-$75K / Enterprise $75K+]

**Renewal book of business:**
- Total ARR up for renewal in next 180 days: [$X across # accounts]
- ARR at risk (Yellow + Red health): [$X across # accounts]
- Green (low-risk) accounts: [# accounts / $X ARR — health score X+]
- Yellow (medium-risk) accounts: [# accounts / $X ARR — health score X–X]
- Red (high-risk) accounts: [# accounts / $X ARR — health score below X]
- Accounts with champion departure in last 90 days: [#]
- Accounts with no CS activity in last 60 days (long-tail): [#]
- Average contract end date lead time in pipeline: [X days from today to next renewal wave]

**Data and signals available:**
- Product usage data: [Yes / No — tool: Mixpanel / Amplitude / Pendo / Gainsight PX / Other]
- Health score system: [Gainsight / ChurnZero / Totango / Vitally / Custify / Custom in CRM / None]
- Health score components (if known): [e.g., product usage 40% / support tickets 20% / NPS 20% / engagement 20%]
- Champion contact tracking (knows when contacts go dark or leave): [Yes (tool: ___) / No]
- Executive sponsor mapping in CRM: [Yes / Partial / No]
- In-app messaging platform: [Pendo / Intercom / Appcues / None]
- Support ticket data integration: [Yes / No]
- NPS/CSAT scores available: [Yes — cadence: ___/ No]
- CRM renewal date tracking: [Opportunity close date / Custom renewal field / Not tracked]

**Marketing and CS team context:**
- Customer marketing team: [Solo / Team of X]
- MAP in use: [Marketo / HubSpot / Pardot / Braze / Iterable / Other]
- CRM: [Salesforce / HubSpot / Other]
- CS team size: [X CSMs managing X accounts each]
- CS-to-customer ratio (accounts per CSM): [X]
- Long-tail threshold (accounts CS can't proactively touch): [Accounts under $X ACV — approximately X accounts]
- Executive alignment available for high-risk renewals: [CRO / CEO / Customer Success VP — available for accounts over $X ACV]

**Constraints:**
- Marketing cannot send renewal-related communications to accounts with open renewal conversations owned by an AE or CSM without explicit opt-in from the CS owner
- All renewal campaign sends must suppress accounts flagged as "Do Not Contact — Active Renewal Negotiation" in CRM
- Executive outreach (CRO/CEO emails) requires CSM approval before send
- Marketing attribution for saved renewals must be agreed with CS leadership before reporting

### Objective
Design a complete, autonomous renewal marketing program that:
1. Identifies at-risk accounts 180 days before contract expiration using a multi-signal health score model
2. Deploys tier-specific, multi-channel renewal campaigns that run without CSM intervention for Green/Yellow accounts
3. Automates CSM escalation briefings with pre-packaged talking points, ROI data, and competitive comparison for Red accounts
4. Rebuilds champion relationships when key contacts depart, using executive-to-executive reengagement sequences
5. Provides marketing-attributable GRR defense metrics for board-level reporting

### Output Requirements

**1. Renewal Risk Scoring Model**
Build a complete churn prediction scoring framework:
- Define 10 behavioral and firmographic signals that predict churn, weighted by predictive power
- For each signal: data source, measurement frequency, threshold for Green/Yellow/Red reclassification, and automated workflow trigger
- Design the composite health score calculation (weights, floor/ceiling rules, override conditions)
- Include a "champion departure" flag that automatically reclassifies any account to Yellow/Red regardless of usage signals

Prioritize signals in this order: (a) product engagement drop, (b) support ticket spike, (c) NPS detractor score, (d) champion contact going dark, (e) key contact leaving the company, (f) budget freeze or company contraction signals (layoffs, funding freeze), (g) competitive evaluation activity (intent signals), (h) executive sponsor disengagement, (i) missed onboarding milestones, (j) low feature adoption relative to purchased tier

**2. Renewal Campaign Architecture by Risk Tier**
For each tier, design the full campaign sequence:

*Green Accounts (Low Risk — proactive loyalty and expansion bridge):*
- Goal: convert high satisfaction into reference, case study, or upsell momentum during renewal window
- Timing: 90 days out (single light-touch sequence)
- Channels: personalized email from CSM (written by marketing), in-app celebration message, LinkedIn touchpoint from AE
- Message angles: ROI milestone celebration, peer benchmark comparison ("You're in the top 20% of [Product] users in [Industry]"), early renewal incentive if applicable
- CTA: Schedule renewal QBR / Accept early renewal offer / Nominate for customer advisory board

*Yellow Accounts (Medium Risk — proactive value reinforcement):*
- Goal: re-establish ROI clarity and rebuild confidence before renewal conversation
- Timing: 120 days out through 30 days out (5-touch multi-channel sequence)
- Touch 1 (120 days out): Marketing email — ROI recap with usage stats + specific value delivered vs. goals set at onboarding. Sender: CSM name/email sent via MAP.
- Touch 2 (105 days out): In-app notification — feature spotlight for an underutilized feature relevant to their use case, with a 1-click "schedule a quick training" CTA
- Touch 3 (90 days out): CSM escalation briefing (auto-generated by marketing automation): summary of account health, recommended talking points, ROI data pull, competitive context brief — delivered to CSM Slack or CRM task
- Touch 4 (75 days out): Peer case study email — "How [Similar Company] achieved [X outcome] in [timeframe]" — highly segmented by industry and company size
- Touch 5 (45 days out): Executive sponsor email (from VP CS or CSM manager) — personal check-in, offer to join a product roadmap preview call

*Red Accounts (High Risk — intervention mode):*
- Goal: surface executive relationships, address root cause objection directly, deploy proof assets
- Timing: Immediate upon Red classification + escalating cadence through renewal date
- Day 0 (Red classification): Auto-alert to CSM + Customer Success VP + AE with full account brief (health score history, support ticket log, NPS trend, usage drop analysis, last 5 touchpoints, renewal ARR at risk)
- Day 3: CSM outreach call — marketing provides a pre-built "rescue call deck" with ROI calculation, feature roadmap highlights, competitive differentiation for likely displacement scenario
- Day 7: Marketing sends "We want to make this right" email from VP Customer Success — acknowledges the account may not have gotten full value, offers dedicated success review
- Day 14: ROI calculator landing page sent — auto-populated with their actual usage data, showing realized vs. potential value (build with HubSpot Custom Tokens / Marketo Velocity / Personalize.io)
- Day 21: Executive sponsor mapping — if CSM relationship is damaged, marketing triggers a CXO-to-CXO email (CEO or CRO to their executive buyer), personal, 3 sentences, offering a 15-minute call
- Day 30+: Competitive displacement defense — if intent signal shows competitor evaluation, marketing deploys battle card content, reference customer connection offer, and analyst validation (Gartner/G2 proof assets)

**3. Champion Departure Playbook**
Design the full sequence for when a primary champion leaves or goes dark:
- Signal detection: How to identify departure (email bounce, LinkedIn change, Salesforce contact update, CS flag)
- Immediate response (Day 0–7): Pause all active marketing sequences to that contact; CSM alert with "Champion Departure Brief" — internal champion map showing who else at the account has engaged with product or attended events
- New champion identification (Day 7–21): Marketing runs internal champion discovery — identify next most-engaged user by product login data; run LinkedIn Sales Navigator search for new hire in equivalent role; deploy in-app "Meet your dedicated success team" message to all active users
- New champion onboarding campaign (Day 21–60): 4-touch email sequence introducing the new contact to the full value of the platform, inviting to customer community, webinar, or training — high-touch, personal tone from CSM
- Executive reengagement (Day 30 if new champion not identified): CRO/CEO reaches out to their equivalent at the account, acknowledging the leadership change and reaffirming partnership commitment
- Champion departure + Red health combo: Immediate escalation to CRO/CEO outreach + renewal date extension offer if appropriate

**4. Marketing-to-CSM Escalation Protocol**
Define exactly how marketing and CS coordinate without creating friction:
- Handoff trigger rules: Green (marketing runs autonomously, CSM receives weekly digest only) / Yellow (marketing sends campaigns, CSM receives pre-call briefs before any scheduled touchpoint) / Red (marketing supports, CS leads, all sends require CSM approval)
- "Do Not Contact" list management: Real-time CRM suppression list synced to MAP — any account flagged "Active Renewal Negotiation" or "CS Owner: Do Not Market" is automatically suppressed from all renewal campaigns within 15 minutes of CRM update
- CSM briefing format: Auto-generated Slack message or CRM task containing: (a) account health trend last 30 days, (b) last 3 marketing touches and engagement data, (c) recommended talking points, (d) competitive context if intent signal detected, (e) ROI data snapshot, (f) renewal date and ARR at risk
- Conflict prevention: Marketing campaign sends are blocked on any account where CSM logged a call in the last 5 days or has a meeting scheduled in the next 3 days — implement via CRM field "Last CSM Activity Date" and "Next Scheduled Meeting Date" synced to MAP suppression

**5. Renewal Content Asset Map**
List every content asset needed to support the program, with the specific narrative for each scenario:

| Asset | Format | Scenario | Message Angle | Owner |
|-------|--------|----------|---------------|-------|
| ROI Recap Email | HTML Email (MAP template) | Yellow/Green — 120 days out | "Here's what [Product] delivered for your team this year" | Marketing writes, CSM reviews |
| Feature Spotlight In-App | In-app modal (Pendo/Intercom) | Yellow — underutilized feature | "One feature your team hasn't tried yet that drives [outcome]" | Marketing |
| Peer Case Study — By Vertical | PDF + Email | Yellow/Red | "[Similar Company] achieved [X]% [metric] improvement" | Marketing + Content |
| ROI Calculator Landing Page | Personalized web page | Red — value gap objection | "See your actual ROI from [Product] — calculated from your data" | Marketing + RevOps data |
| Competitive Defense Battle Card | Internal (CSM-facing) | Red — competitive displacement | Point-by-point comparison vs. [Competitor] with customer quotes | PMM + Marketing |
| Executive Rescue Email | Plain-text email | Red — relationship escalation | 3-sentence personal note from CRO/CEO | Marketing drafts, CRO/CEO approves |
| Champion Onboarding Email Series | 4-touch HTML sequence | Champion departure | "Welcome from your dedicated success team" | Marketing |
| Renewal QBR Deck Template | Slide deck | Green — proactive renewal | Business review with ROI, roadmap preview, next 12 months plan | CS + Marketing |
| Analyst/G2 Validation Pack | Email + PDF | Red — credibility objection | Third-party validation of [Product] category leadership | Marketing |
| Renewal Offer Landing Page | Web page | All tiers — early renewal | "Renew early and lock in current pricing + [bonus feature]" | Marketing + Finance |

**6. GRR Attribution Model**
Define how marketing proves its contribution to saved renewals:
- Marketing-sourced save definition: Account was Yellow or Red, received at least one marketing campaign touch, and subsequently renewed — with a CSM confirmation that marketing content or campaign contributed to the save
- Attribution window: If a marketing campaign touch occurred within 60 days of renewal date, and the account was Yellow/Red at time of touch, marketing can claim partial credit
- Measurement cadence: Monthly GRR cohort analysis segmented by (a) accounts that received renewal marketing vs. (b) control group of accounts with no marketing engagement — compare renewal rates
- Dashboard metrics: GRR from marketing-touched cohort vs. non-touched cohort / Number of Red accounts converted to Green post-campaign / ARR saved (marketing-attributed) / Cost per saved renewal / Campaign engagement rate by risk tier
- Board metric: "Marketing-Defended ARR" — total ARR from accounts that were Yellow/Red and renewed after receiving marketing campaigns, reported as a pipeline metric alongside new logo pipeline

### Constraints & Design Principles
- Every campaign sequence must respect CSM ownership — no marketing message should contradict or undercut an active CS conversation
- All renewal campaigns must have an immediate unsubscribe/suppress option for CSMs to invoke from CRM with one click
- Green account campaigns must not feel like "please renew" messages — they should celebrate success and open expansion conversations
- Red account campaigns must acknowledge the relationship, not paper over it — no generic "value of [Product]" messaging; use their actual data
- Never send a renewal campaign to an account in active legal dispute, bankruptcy proceedings, or formal acquisition process — maintain a CRM flag for these scenarios

## Example Input/Output

**Input scenario:**
Meridian Ops (fictional) — B2B SaaS revenue operations platform, $3.2M ARR, 187 customers, ACV $17,100, annual contracts. GRR currently 82%, board target 88%. Primary churn driver: champion departure (38% of churned accounts) and low adoption among SMB segment (under $12K ACV). CS team: 4 CSMs managing 47 accounts each. Marketing: 1 customer marketing manager. Stack: Salesforce + Gainsight + HubSpot MAP + Pendo in-app.

**Renewal book snapshot:** 52 accounts ($890K ARR) renewing in next 180 days. Green: 28 accounts ($480K). Yellow: 17 accounts ($290K). Red: 7 accounts ($120K). 3 accounts had champion departures in last 60 days.

**Output excerpt (Red Account Campaign — Day 0 escalation brief):**

*Auto-generated Slack alert to CSM Sarah Chen + VP CS Daniel Park:*

> 🚨 **At-Risk Renewal Alert — Meridian Ops Customer**
> **Account:** Hartwell Financial Services | **ARR at risk:** $24,800 | **Renewal date:** 89 days
> **Health score:** 34/100 (dropped from 61 last month) | **Risk classification:** RED
>
> **Why it changed:**
> — Product logins dropped 67% in last 30 days (from 23/week avg to 7/week)
> — Champion Matt Kowalski (Director of RevOps) left company Oct 3 — no new champion identified
> — Support ticket submitted Oct 8: "Struggling to use forecasting module" (unresolved 6 days)
> — NPS score from September: 4/10 (Detractor)
>
> **Recommended immediate actions:**
> 1. Call interim contact Jennifer Huang (VP Finance, logged into product 3x last month) within 48 hours
> 2. Offer dedicated onboarding reset session for new RevOps hire (when hired)
> 3. Escalate unresolved support ticket to dedicated engineer — resolve before any renewal conversation
>
> **Marketing will hold all automated sends until you confirm a call is scheduled.**
> [Confirm call scheduled →] [Suppress marketing for 30 days →] [Escalate to CRO →]

**Competitive defense triggered:** Bombora intent signal shows Hartwell Financial evaluated "Clari" and "Gong Revenue Intelligence" last 14 days.

*Marketing-generated battle card excerpt sent to Sarah:*
> **vs. Clari:** Meridian Ops wins on [3 differentiators]. Customer quote from similar FinServ customer: "[Quote]." G2 rating comparison: Meridian 4.7 vs. Clari 4.4 in "Ease of Use." Reference available: [Customer name, title] — cleared for reference calls.

## Success Metrics

**Program health indicators:**
- GRR from marketing-touched cohort vs. control: Target +5–8 percentage points higher renewal rate
- Red account rescue rate: % of Red accounts that renew after receiving full campaign sequence — target 40%+
- Yellow account stabilization rate: % of Yellow accounts that reclassify to Green within 60 days of campaign start — target 55%+
- Champion departure recovery: % of accounts where new champion is identified and engaged within 45 days of departure — target 70%+
- CSM escalation brief engagement: % of auto-generated briefs where CSM takes documented action within 48 hours — target 80%+
- Campaign engagement rate: Open rate 35%+ / Click rate 8%+ for renewal sequence emails (higher than cold outbound benchmarks — these are existing customers)
- Marketing-attributed saves per quarter: Target at minimum 3x marketing program cost in saved ARR

**Lagging indicators (quarterly):**
- GRR improvement vs. prior quarter: Program should show measurable GRR lift within 2 renewal cycles
- ARR saved (marketing-attributed): Total ARR from accounts that were at-risk and renewed post-campaign
- Cost per saved renewal: Total customer marketing program cost ÷ number of at-risk renewals saved

## Related Prompts
- [Customer Marketing Expansion Revenue Campaign](./AI-Powered-B2B-SaaS-Customer-Marketing-Expansion-Revenue-Campaign-Architecture-&-Cross-Sell-Upsell-Pipeline-Intelligence-Engine.md)
- [Customer Reference Program Architecture](./AI-Powered-B2B-SaaS-Customer-Reference-Program-Architecture-&-Peer-Selling-Pipeline-Velocity-Intelligence-Engine.md)
- [Churn Prediction & Proactive Retention Marketing](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/AI-Powered-Churn-Prediction-&-Proactive-Retention-Marketing-Engine.md)
- [Churn Interview Program & Intelligence Mining](../../02_Product-Marketing/Customer-&-Market-Research/AI-Powered-B2B-SaaS-Churn-Interview-Program-&-Churned-Customer-Intelligence-Mining-Revenue-Intelligence-Engine.md)

## Integration Tips

**Gainsight + HubSpot / Marketo:**
- Use Gainsight's Health Score field synced to Salesforce as the enrollment trigger for HubSpot/Marketo renewal workflows — set up a scheduled sync every 4 hours so risk reclassifications propagate quickly
- Create a "Renewal Marketing Status" field in Salesforce populated by your MAP: values = [Not Enrolled / Active Green / Active Yellow / Active Red / Suppressed — CS Owner / Suppressed — Do Not Contact / Completed — Renewed / Completed — Churned]
- Build Gainsight Cockpit CTAs that auto-populate when marketing escalation briefs are triggered — CSM sees the brief as a CTA in their daily workflow, not a Slack message they might miss

**Salesforce + Marketo:**
- Build a Salesforce "Renewal Cohort" report filtered by Close Date = next 180 days, segmented by Health Score tier — sync to Marketo as a Smart List for campaign enrollment
- Use Velocity Script in Marketo to auto-populate ROI recap emails with Salesforce fields: Contract Start Date, Primary Use Case, Key Metrics (if tracked), Number of Seats Used vs. Purchased
- Set up Salesforce workflow rule: when "Last CSM Activity Date" is updated to today, suppress account from all marketing sends for 5 days — prevents dual outreach

**HubSpot (all-in-one):**
- Use HubSpot's Custom Properties to track: Health Score (synced from CS tool), Renewal Date, Risk Tier, Champion Status, Last Marketing Touch (Date), Renewal Marketing Sequence (Active/Suppressed)
- Build HubSpot Workflows with enrollment triggers: "Renewal Date is 180 days from today" AND "Risk Tier = Yellow" → enroll in Yellow Renewal Sequence
- Use HubSpot's "Active List" for real-time suppression: any contact whose company has "Renewal Suppression = True" (set by CSM via CRM) is automatically excluded from all renewal email sends

**Pendo / Intercom (in-app):**
- Trigger in-app renewal messages via API call from your MAP — when a Yellow account hits 90-day mark, your MAP webhook fires a Pendo/Intercom event that shows the feature spotlight modal to active users
- Use Pendo's "Company-level" targeting to suppress in-app messages from Red accounts in active CS conversations — sync suppression list via Pendo API daily

**Slack (CS notification):**
- Connect Salesforce → Zapier → Slack to auto-post escalation briefs to a #renewal-alerts Slack channel with @ mention of the owning CSM and their manager
- Include deep links in Slack alerts: direct link to Salesforce account, Gainsight timeline, and HubSpot email engagement history — CSM should be able to get full context in under 2 minutes

## Troubleshooting

**Problem: CSMs feel marketing is interfering with their renewal conversations and are suppressing all campaigns.**
Fix: Run a joint session with CS leadership to agree on suppression rules upfront. Give CSMs a self-service "pause marketing" button in Salesforce that they can use without going through marketing — this actually increases trust and reduces blanket suppression. Show CSMs the engagement data on marketing emails (open rates, click rates) so they see customers are reading them before CSM calls.

**Problem: ROI recap emails aren't resonating — customers aren't opening or clicking.**
Fix: The problem is usually one of three things: (a) the ROI metrics cited don't match what the customer cares about — interview 5 recently renewed customers to find out what value statement landed with them; (b) the email looks like a marketing blast, not a personal CSM message — make it plain-text with CSM's actual photo and first name in the from line; (c) the timing is off — move the first touch earlier (150 days out instead of 120) when renewal isn't yet a charged topic.

**Problem: Can't measure marketing's contribution to saved renewals — CS claims credit for everything.**
Fix: This is a political problem more than a technical one. Solve it upfront: get CS leadership to agree in writing to a dual-credit model — CS gets credit for the save, marketing gets credit for the campaign support. Build a "Renewal Save Attribution" survey into your CS post-renewal workflow (3 questions, takes 60 seconds) where the CSM rates whether marketing content or campaigns contributed to the save. Use that data to calculate marketing's co-contribution rate quarterly.

## Version History
- v1.0: Initial creation (auto-generated)
