# Customer Segmentation & Behavioral Targeting Engine - AI-Powered Audience Intelligence

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** segmentation, behavioral-analytics, personalization, crm, b2b, b2c, d2c, lifecycle-marketing, rfm

## Overview
This prompt builds a full customer segmentation system using RFM scoring, behavioral signals, and predictive clustering — then maps each segment to specific campaign tactics, messaging angles, and channel strategies. Use it whenever you need to move beyond demographic targeting and activate data-driven audience personalization across email, paid ads, and CRM workflows.

## Quick Copy-Paste Version

You are a customer analytics expert. Analyze the following customer data and build a complete segmentation model:

Business: [Your Company] — [brief description, e.g., B2B SaaS project management tool for mid-market companies]

Customer data available:
- Total customers: [X]
- Recency: [date range of last purchases/logins, e.g., "last activity 0-730 days ago"]
- Frequency: [purchase/usage frequency range, e.g., "1-48 sessions/month"]
- Monetary/Value: [revenue or usage tier range, e.g., "$0-$2,400 ARR"]
- Behavioral signals: [key actions available, e.g., "feature adoption, support tickets, NPS score, integrations used"]
- Lifecycle stage data: [trial, active, at-risk, churned, etc. — if available]

Deliver:
1. An RFM scoring matrix with 4-6 named segments (e.g., Champions, At-Risk, Hibernating)
2. Behavioral profile for each segment (what they do, what they don't do)
3. Primary business risk or opportunity each segment represents
4. One specific campaign action to take for each segment THIS WEEK
5. Recommended channel mix and message angle per segment
6. A segment migration map — what would move each group up to the next tier

Format output as a table + action plan I can paste into a project doc.

## Advanced Customizable Version

ROLE:
You are a Senior Customer Intelligence Strategist with 15+ years of experience in lifecycle marketing and behavioral analytics at companies like Amplitude, HubSpot, Klaviyo, and Braze. You specialize in translating raw behavioral data into high-precision audience segments that drive measurable revenue outcomes. You combine RFM analysis, Jobs-to-be-Done theory, and predictive propensity modeling.

CONTEXT:
Company: [Company Name]
Business model: [B2B SaaS / D2C ecommerce / marketplace / subscription box / etc.]
Current CRM/MAP: [HubSpot / Salesforce + Marketo / Klaviyo / ActiveCampaign / other]
Primary revenue motion: [product-led growth / sales-assisted / fully self-serve / channel/reseller]
Total addressable customer base: [X active + Y lapsed/churned]
Key monetization lever: [expansion revenue / repeat purchase / subscription renewal / upsell]

AVAILABLE DATA SIGNALS (check all that apply and provide ranges/distributions):
- Last activity date (recency): [e.g., 0-180 days; median = 23 days]
- Engagement frequency: [e.g., logins/month; 0-60; median = 8]
- Revenue/contract value: [e.g., MRR $0-$5,000; median = $149]
- Feature adoption: [list key features and % of customers using each]
- Support interaction history: [ticket volume, CSAT, escalation rate]
- NPS or satisfaction score: [range and distribution if available]
- Acquisition source: [paid/organic/referral/partner breakdown]
- Integrations or product connections: [e.g., Slack, Salesforce, Zapier connected]
- Content/email engagement: [open rate, click rate by persona if segmented]

OBJECTIVE:
Build a production-ready customer segmentation model that can be immediately operationalized in [CRM/MAP system] to trigger automated campaigns, sales alerts, and product nudges.

DELIVERABLES:

1. SEGMENTATION ARCHITECTURE
   - Define 5-7 named segments with precise RFM thresholds (R score 1-5, F score 1-5, M score 1-5)
   - Assign a strategic label to each (e.g., "Power Users," "Sleeping Giants," "One-Hit Wonders," "Price-Sensitive Loyalists")
   - Estimated % of customer base in each segment
   - Primary behavioral signature — what specific actions define membership

2. SEGMENT INTELLIGENCE PROFILES
   For each segment, provide:
   - Jobs-to-be-Done: Why they bought, what outcome they're seeking
   - Emotional state: Satisfied / frustrated / indifferent / at-risk
   - Biggest barrier to upgrade or re-engagement
   - Expansion/retention probability score (High/Medium/Low with rationale)
   - Churn risk rating and early warning signals to monitor

3. ACTIVATION PLAYBOOK
   For each segment, define:
   - Campaign type: [nurture sequence / win-back / expansion / loyalty / save]
   - Channel priority: [email / in-app / SMS / paid retargeting / sales outreach]
   - Message angle: Use AIDA or Before/After/Bridge framework
   - Specific CTA: One clear next action (not "learn more" — a real conversion action)
   - Cadence: Frequency and timing recommendation
   - Success KPI: The one metric that defines if this segment is moving in the right direction

4. SEGMENT MIGRATION MAP
   - What behavioral milestone moves a customer FROM each segment TO the next tier up
   - Specific product actions, email triggers, or sales motions to catalyze migration
   - Estimated revenue impact of moving X% of each segment one tier up

5. OPERATIONALIZATION GUIDE
   - Exact filter logic to build each segment in [CRM]: field names, operators, values
   - Recommended re-segmentation frequency (daily/weekly/monthly)
   - Which segments should trigger a sales alert vs. run fully automated
   - Integration hooks: How to sync segments to ad platforms (Google, Meta, LinkedIn) for lookalike and exclusion audiences

CONSTRAINTS:
- All segment definitions must be buildable with the data signals I've listed — no hypothetical data sources
- Each activation tactic must be executable within 5 business days with a team of 2
- Prioritize segments by revenue impact: show me where to focus first
- Design for full automation — every recommended action should be triggerable by a workflow rule or webhook, with zero manual intervention for routine execution

OUTPUT FORMAT:
- Executive Summary: 3-sentence segment landscape overview
- Segment Architecture Table (name, RFM thresholds, % of base, churn risk, revenue opportunity)
- Per-Segment Intelligence Cards (one card per segment, structured as above)
- 30-Day Activation Roadmap: Which segments to tackle week by week
- CRM Implementation Checklist: Step-by-step setup instructions

## Example Input/Output

**Example Input:**
- Company: Nexlify — B2B SaaS project management tool, 2,400 active customers, $1.8M ARR
- CRM: HubSpot + Klaviyo
- Recency: 0-540 days since last login; median = 18 days
- Frequency: 0-45 logins/month; median = 11
- Revenue: $49-$799/month; median = $99 (Starter plan)
- Feature adoption: 68% use task creation; 34% use automations; 12% use API/integrations; 5% use reporting dashboards
- NPS: 32 (Promoters = 28%, Detractors = 22%)
- Acquisition: 44% organic/SEO, 31% paid, 25% referral

**Example Output (Segment 1 of 6 — "Power Builders"):**

**Segment: Power Builders**
- RFM: R=5, F=4-5, M=3-5 | ~11% of base (~264 customers) | MRR contribution: ~$38,000
- Behavioral signature: Login 20+ times/month, use automations + 2+ integrations, fewer than 2 support tickets/quarter, NPS Promoter
- Jobs-to-be-Done: Replace fragmented toolstack with one system of record; reduce project admin overhead
- Emotional state: Satisfied, achievement-oriented, looking for power features
- Churn risk: LOW (3%)
- Expansion probability: HIGH — 74% are on Starter or Growth plans, not yet on Business
- Barrier to upgrade: Don't know the Business plan's advanced reporting exists

**Activation:**
- Campaign type: Expansion / Feature discovery
- Channel: In-app tooltip + triggered email sequence (3-part)
- Message angle (Before/After/Bridge): "Right now your reports live in spreadsheets outside Nexlify. After upgrading, your entire project performance dashboard is inside the tool. Here's how 3 similar teams did it."
- CTA: "Start your Business plan trial — 14 days free, no card required"
- Cadence: In-app trigger fires when user hits 20 logins in a month; email Day 1, Day 5, Day 12
- KPI: Upgrade conversion rate from Starter/Growth to Business within 30 days
- Migration trigger: Completes first automated report — moves to "Expansion Ready" sales queue

**CRM Filter Logic (HubSpot):**
Contact Property: Last Login Date >= 30 days ago (within)
AND Deal Property: MRR >= $49
AND Custom Property: automations_used = true
AND Custom Property: integrations_count >= 2
AND NPS Category = Promoter

## Success Metrics

- Segment definition quality: Every segment is non-overlapping, mutually exclusive, and covers 100% of customer base
- Actionability test: Each segment has at least one campaign live within 5 business days
- Revenue lift: Expansion segments show >15% upgrade rate within 30 days of activation
- Retention lift: At-risk/hibernating segments show >20% re-engagement rate within 60 days
- Automation coverage: >80% of recommended actions run via workflow triggers with no manual sends

## Related Prompts

- `../Advanced-Marketing-Intelligence/Marketing-Mix-Modeling-Framework.md`
- `../Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Email-Personalization-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Lead-Generation-Campaigns/Lead-Scoring-Automation.md`

## Integration Tips

- **HubSpot:** Build Active Lists using the filter logic from the operationalization guide. Set up Workflows triggered by list membership changes to auto-enroll contacts into email sequences or create tasks for sales reps.
- **Salesforce + Marketo:** Use Marketo Smart Lists with custom field filters. Sync segment labels back to Salesforce as a Contact/Account field so AEs can see segment tier in the CRM sidebar.
- **Klaviyo (ecommerce):** Use Klaviyo's built-in RFM tool as a starting point, then layer behavioral properties (product categories browsed, discount sensitivity, review submitted) to create sub-segments. Use Flow triggers on segment entry/exit.
- **Google Ads / Meta Ads:** Export segment member lists as Customer Match audiences. Use Power Builders as a seed audience for lookalike campaigns. Exclude Churned/Detractor segments from acquisition campaigns to protect CAC.
- **Amplitude / Mixpanel:** Build cohorts in your product analytics tool that mirror each segment's behavioral criteria. Use these cohorts to monitor in-product behavior separately and validate that your activation campaigns are changing behavior.
- **Zapier/Make:** Set up a webhook trigger when a contact transitions between segments (via HubSpot property change or Salesforce field update). Route the event to Slack for sales-alerts on high-value at-risk accounts, and to your email platform for automated nurture enrollment.
- **Google Sheets / Notion:** Export the segment architecture table to a shared doc and link it in your marketing wiki. Assign segment ownership (email team, sales, CS) and review monthly.

## Troubleshooting

**Problem: Data is too thin — I only have email engagement data, no product usage or revenue data.**
Fix: Adapt RFM to email-native signals: Recency = days since last email open, Frequency = emails opened in last 90 days, Monetary = lead score or estimated deal value from firmographic enrichment (Clearbit, Apollo). Use the Quick Copy-Paste version with these proxies. The segments will be less precise but still directionally useful for nurture prioritization.

**Problem: Segments are lopsided — 80% of customers land in one segment.**
Fix: Adjust the percentile thresholds for RFM scoring. Instead of using absolute values (e.g., "logged in 10+ times"), use relative quintiles: top 20% = R5, next 20% = R4, etc. Re-run the prompt specifying "use percentile-based scoring on the distributions I've provided" and request a segment size sanity check before finalizing.

**Problem: Sales team ignores the segment playbook and keeps doing ad-hoc outreach.**
Fix: Operationalize the segments directly in CRM as Views/Queues with pre-written email templates attached. Remove the sales rep's need to interpret the model — surface only the segment name, the recommended CTA, and a one-sentence "why now" rationale. Then use Salesforce Sequences or HubSpot Sequences to auto-enroll accounts so the playbook executes even without conscious rep action.

## Version History
- v1.0: Initial creation (auto-generated)
