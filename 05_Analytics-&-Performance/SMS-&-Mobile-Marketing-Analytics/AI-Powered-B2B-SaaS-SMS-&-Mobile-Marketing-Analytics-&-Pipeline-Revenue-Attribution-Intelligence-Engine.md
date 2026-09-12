# AI-Powered B2B SaaS SMS & Mobile Marketing Analytics & Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** analytics, sms-marketing, mobile-marketing, pipeline-attribution, revenue-intelligence, b2b-saas, compliance

## Overview
This prompt deploys a full-stack SMS and mobile marketing analytics engine for B2B SaaS, transforming raw channel data (SMS, MMS, push notifications, WhatsApp Business API) into pipeline attribution models, revenue contribution proofs, and autonomous optimization playbooks. Use it when you need to demonstrate mobile marketing ROI to finance, identify the highest-converting mobile segments, or optimize cross-channel mobile touchpoints across enterprise demand generation and account-based motions.

## Quick Copy-Paste Version

You are a senior B2B SaaS marketing analytics architect specializing in mobile channel revenue attribution. Analyze my SMS and mobile marketing program and generate a complete pipeline intelligence report.

PROGRAM DATA (replace with actuals):
- SMS/MMS: [X] messages sent to [X] opted-in contacts, [X]% delivery rate, [X]% click rate, [X]% reply rate
- Push notifications: [X] sends to [X] opted-in app users, [X]% open rate, [X]% click-to-conversion rate
- WhatsApp Business: [X] conversations initiated, [X]% response rate, [X]% meeting-booked rate
- Pipeline influence: [X] contacts who received mobile touchpoints progressed to MQL; [X] active opportunities had mobile touchpoints in the 30 days before stage advance
- Revenue: [X] closed-won deals with mobile attribution in the past 90 days, average ACV $[X]
- Total mobile program spend: $[X]/month (platform fees + list management + content creation)
- Compliance: [X]% opt-in rate on list, [X]% opt-out rate, list last cleaned [date]

ANALYSIS REQUIRED:
1. CHANNEL PERFORMANCE SCORECARD: Rate SMS, push, and WhatsApp on delivery health, engagement quality, pipeline influence rate, and cost-per-influenced-opportunity. Flag underperformers.
2. REVENUE ATTRIBUTION BREAKDOWN: Calculate first-touch, last-touch, and W-shaped multi-touch pipeline attribution from mobile channels. Separate mobile-sourced vs mobile-influenced pipeline. Show revenue-per-send for each channel.
3. SEGMENT PERFORMANCE MATRIX: Identify which ICP tiers (enterprise/mid-market/SMB), funnel stages (awareness/consideration/decision), and message types (educational/promotional/transactional) deliver the highest conversion lift.
4. BENCHMARK COMPARISON: Compare my metrics against B2B SaaS industry benchmarks (SMS: 95%+ delivery, 25-35% CTR for high-performers; push: 5-15% open rate; WhatsApp: 40-60% response rate). Flag gaps.
5. OPTIMIZATION PLAYBOOK: Generate 7 specific, measurable recommendations to improve mobile pipeline ROI by 25%+. Include: message timing optimization, segment prioritization, compliance improvements, and channel-mix rebalancing.
6. COMPLIANCE RISK ASSESSMENT: Score TCPA, GDPR, and CCPA risk based on opt-in rate, opt-out rate, list hygiene practices, and double opt-in usage. Flag any category as Red/Yellow/Green.

Output format: Executive summary (4 sentences), channel-by-channel scorecard table, attribution waterfall chart (described in text), segment matrix, benchmark gap analysis, prioritized optimization actions, and compliance dashboard.

## Advanced Customizable Version

ROLE: You are a principal marketing data scientist and revenue operations architect for a B2B SaaS company generating $[ARR] with a [sales-led/PLG/hybrid] GTM motion. You have deep expertise in mobile channel attribution modeling, TCPA/GDPR compliance frameworks, and multi-touch revenue attribution for long B2B sales cycles (average sales cycle: [X] days, average deal size: $[ACV]).

CONTEXT:
- Company: [Company Name], [industry/vertical], selling to [buyer persona] at [company size] companies
- ICP: [describe ICP — e.g., "VP of Engineering at Series B+ SaaS companies, 50-500 employees"]
- GTM motion: [sales-led / PLG / hybrid — describe how mobile fits into your motion]
- Mobile channels active: [list: SMS, MMS, push notifications, WhatsApp Business, in-app messaging]
- Attribution window: [30/60/90 days]
- CRM: [HubSpot / Salesforce / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]
- Mobile platform: [Attentive / Klaviyo / Twilio / Customer.io / Braze / other]

RAW CHANNEL DATA — LAST 90 DAYS:

SMS/MMS Performance:
- Total sends: [X] | Unique contacts: [X] | Opted-in list size: [X]
- Delivery rate: [X]% | Click rate: [X]% | Reply rate: [X]%
- Unsubscribe rate: [X]% | Complaint rate: [X]%
- Campaigns run: [X] | Top performing campaign: [describe]
- Message categories: [X]% promotional, [X]% transactional, [X]% nurture

Push Notification Performance:
- Total sends: [X] | Opted-in users: [X] | Permission rate: [X]%
- Open rate: [X]% | Click rate: [X]% | Conversion-to-MQL rate: [X]%
- Notification categories: [X]% feature/product, [X]% behavioral trigger, [X]% promotional

WhatsApp Business API Performance:
- Conversations initiated: [X] | By sales: [X]%, by marketing: [X]%
- Response rate: [X]% | Meeting-booked rate from conversation: [X]%
- Average response time (inbound): [X] minutes

Pipeline & Revenue Attribution:
- MQLs with mobile touchpoints in 90-day attribution window: [X] of [X] total MQLs ([X]%)
- Open opportunities with mobile touchpoints: [X] of [X] total ([X]%), total influenced pipeline: $[X]
- Closed-won deals with mobile attribution: [X] deals, $[X] revenue, average sales cycle compression vs. non-mobile: [X] days
- Closed-lost deals with mobile touchpoints: [X] deals, [X]% of mobile-touched pipeline lost

Spend:
- Mobile platform cost: $[X]/month
- Content creation + compliance: $[X]/month
- Headcount (FTE allocated): [X] hours/week
- Total mobile program investment: $[X]/month

ANALYSIS OBJECTIVES:
Execute all of the following analytical frameworks:

**OBJECTIVE 1: ATTRIBUTION MODEL CONSTRUCTION**
Apply three attribution models to the mobile channel data:
- Single-touch first-touch: credit mobile for deals where mobile was the first marketing touchpoint
- Single-touch last-touch: credit mobile for deals where mobile was the last touchpoint before opportunity creation
- W-shaped multi-touch: distribute 30% to first touch, 30% to lead-creation touch, 30% to opportunity-creation touch, 10% distributed across middle touches

For each model, output:
- Mobile-attributed pipeline ($)
- Mobile-attributed revenue ($)
- Mobile-sourced vs. mobile-influenced split
- Mobile contribution as % of total marketing pipeline
- Revenue-per-send ratio for each channel

**OBJECTIVE 2: CHANNEL EFFICIENCY SCORING**
Score each active mobile channel (SMS, push, WhatsApp) using this framework:
- Delivery & Reach Score (1-10): based on delivery rate, list health, permission rates
- Engagement Quality Score (1-10): based on CTR, reply rate, time-to-engage
- Pipeline Influence Score (1-10): based on MQL influence rate, opportunity influence rate, sales cycle impact
- Cost Efficiency Score (1-10): based on cost-per-influenced-opportunity, cost-per-attributed-revenue
- Composite Mobile Channel Score (weighted average)
Flag any channel scoring below 6.0 as "Optimize or Eliminate."

**OBJECTIVE 3: SEGMENT PERFORMANCE DECOMPOSITION**
Break down mobile performance by:
- ICP tier (Tier 1 enterprise / Tier 2 mid-market / Tier 3 SMB)
- Funnel stage at time of mobile touchpoint (awareness / consideration / decision / post-sale)
- Message type (educational thought leadership / use case / ROI/proof / competitive / promotional offer / product update)
- Day/time of send cohort (best window analysis)

Identify the top 3 highest-converting combinations of [segment × stage × message type]. Recommend concentrating 60% of mobile budget on these.

**OBJECTIVE 4: COMPLIANCE & LIST HEALTH AUDIT**
Evaluate risk across three regulatory frameworks:
- TCPA (US): assess express written consent evidence, opt-out honor rate (<10 days), quiet hours compliance, message frequency caps
- GDPR (EU): assess lawful basis documentation, data retention practices, right-to-erasure capability
- CCPA (California): assess opt-out mechanisms, data sale disclosures

Score each framework: GREEN (compliant), YELLOW (minor gaps), RED (material risk).
Generate a compliance action plan with priority order and estimated remediation effort.

**OBJECTIVE 5: COMPETITIVE BENCHMARKING**
Compare program metrics against these B2B SaaS industry benchmarks:
- SMS delivery rate benchmark: 95-98% (flag if below 93%)
- SMS CTR benchmark: 15-35% (flag if below 12%)
- SMS reply rate benchmark: 8-15% (flag if below 5%)
- Push notification open rate benchmark: 5-15% (flag if below 3%)
- WhatsApp response rate benchmark: 40-65% (flag if below 25%)
- Mobile-influenced pipeline as % of total: 15-25% for mature B2B SaaS programs
- Mobile program ROI benchmark: 4-8x spend in attributed pipeline (flag if below 3x)

For each metric below benchmark, generate a specific root cause hypothesis and remediation action.

**OBJECTIVE 6: OPTIMIZATION ROADMAP**
Generate a 90-day optimization roadmap organized into three phases:
- Days 1-30 (Quick Wins): 3-5 actions deliverable within 30 days with minimal resource
- Days 31-60 (Core Improvements): 3-5 actions requiring moderate effort, expected to drive 15%+ improvement
- Days 61-90 (Strategic Investments): 2-3 longer-horizon investments that set up compounding returns

For each action specify: expected impact (metric + % improvement), effort level (hours), owner (marketing ops / content / compliance / demand gen), and success KPI.

OUTPUT FORMAT:
Section 1: Executive Dashboard (suitable for CMO review): 5 KPIs with RAG status, top 2 wins, top 2 risks, 90-day outlook
Section 2: Attribution Analysis (for VP Demand Gen): waterfall table showing attribution by model and channel
Section 3: Channel Scorecards (for marketing ops): tabular scoring for each channel
Section 4: Segment Intelligence (for campaign managers): heatmap-style breakdown of winning segments
Section 5: Compliance Dashboard (for legal/marketing ops): RAG status by framework with action list
Section 6: Optimization Roadmap (for program manager): 90-day plan with owners and KPIs

## Example Input/Output

**Input Example:**
Company: Verity AI — AI-powered contract intelligence for corporate legal teams
ICP: VP/Director of Legal Operations at enterprise companies (1,000+ employees), Series C+
GTM Motion: Sales-led, 90-day average sales cycle, $45,000 average ACV
SMS: 4,200 sends to 1,800 opted-in contacts, 96.2% delivery, 28.4% CTR, 11.2% reply rate
Push: 3,100 sends to 2,400 opted-in app trial users, 9.1% open rate, 4.3% CTC rate
WhatsApp: 340 conversations, 52.4% response rate, 18.2% meeting-booked rate
Pipeline: 34 MQLs with mobile touchpoints (of 180 total MQLs = 18.9%)
Open opportunities influenced: 28 deals, $2.1M total pipeline
Closed-won with mobile attribution: 6 deals, $287,000 revenue (90-day window)
Mobile program spend: $4,200/month total

**Output Example (abbreviated):**

**Executive Dashboard:**
| KPI | Value | Benchmark | Status |
|---|---|---|---|
| Mobile-attributed pipeline (W-shaped) | $487K | $340K target | GREEN |
| Program ROI | 6.8x attributed pipeline/spend | 4-8x | GREEN |
| SMS CTR | 28.4% | 15-35% | GREEN |
| WhatsApp meeting rate | 18.2% | 12-20% | GREEN |
| Push open rate | 9.1% | 5-15% | YELLOW (room to grow) |

**Top Wins:**
1. WhatsApp is generating meetings at 18.2% conversation-to-meeting rate — 2.3x above industry average. Allocate more outbound capacity here.
2. SMS CTR of 28.4% confirms strong list quality and message relevance — protect by maintaining strict double opt-in.

**Top Risks:**
1. Push notification reach limited — only 2,400 opted-in users from what should be a much larger trial base. Low permission rate signals onboarding UX problem, not a push strategy problem.
2. Mobile-influenced MQL rate (18.9%) is slightly below the 20-25% benchmark for mature programs; recommend adding mobile touchpoints earlier in the nurture sequence.

**Attribution Summary (W-shaped):**
- Mobile-sourced pipeline: $127K (deals where mobile was first AND lead-creation touch)
- Mobile-influenced pipeline: $360K (mobile as contributing touchpoint in deal journey)
- Mobile-attributed revenue (closed-won, 90-day): $287K
- Revenue-per-send across all channels: $0.068/send
- WhatsApp highest revenue-per-conversation: $844/conversation

**Top Optimization Action (30-day Quick Win):**
Segment trial users by product usage signal (high-engagement vs. dormant) and run a targeted push campaign to dormant users with a "did you know" education message tied to their specific use case. Expected: 40% improvement in push CTC rate within 30 days.

## Success Metrics

- **Attribution Coverage**: Mobile touchpoints represented in 20-30% of all MQLs (benchmark for mature B2B SaaS programs)
- **Program ROI**: 4x minimum attributed pipeline-to-spend ratio; 6x+ for high-performing programs
- **Compliance Score**: All three regulatory frameworks (TCPA, GDPR, CCPA) at GREEN within 60 days of remediation
- **Optimization Adoption**: 70%+ of 30-day quick win actions implemented within the target window
- **Segment Precision**: Identify 3 winning [segment × stage × message] combinations that account for 50%+ of mobile pipeline influence
- **Channel Score Improvement**: All channels scoring 7.0+ on composite channel score within 90 days

## Related Prompts

- [SMS & Mobile Marketing Automation Architecture](../../04_Demand-&-Lead-Generation-&-Growth/SMS-&-Mobile-Marketing/AI-Powered-B2B-SaaS-SMS-Mobile-Marketing-Automation-Architecture-&-High-Intent-Buyer-Conversion-Revenue-Intelligence-Engine.md)
- [Email Marketing Performance Analytics](../Email-Marketing-Analytics/AI-Powered-B2B-SaaS-Email-Marketing-Performance-Analytics-&-Lifecycle-Revenue-Attribution-Intelligence-Engine.md)
- [Omnichannel Conversational AI Program Analytics](../Conversational-Marketing-Analytics/AI-Powered-B2B-SaaS-Omnichannel-Conversational-AI-Program-Analytics-&-Unified-Revenue-Attribution-Intelligence-Engine.md)
- [Multi-Touch Attribution & Revenue Marketing Intelligence](../Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)

## Integration Tips

**Braze / Iterable / Customer.io:**
Export channel-level engagement data via API (delivery events, opens, clicks, conversions) and pipe directly into the Advanced prompt's raw data section. These platforms expose event webhooks to Zapier or Make.com for automated weekly data refreshes.

**Salesforce / HubSpot (CRM Attribution):**
Use CRM campaign influence reports to pull mobile campaign membership against open and closed opportunities. In Salesforce, query `CampaignMember` joined with `Opportunity` via `OpportunityContactRole`. In HubSpot, use the Campaign Analytics report filtered by "SMS" or "Push" campaign types. Feed the resulting pipeline influence numbers into Objective 1 of the Advanced prompt.

**Twilio / Attentive / Klaviyo:**
Pull program-level analytics from the platform API or export. Key fields: message_id, contact_id, sent_at, delivered_at, clicked_at, conversion_event (mapped to your pipeline stages). Join with CRM data using contact email or phone number as the primary key.

**Google Sheets / Looker Studio Dashboard:**
Paste the Attribution Analysis output table into Google Sheets. Use Looker Studio to build a live dashboard by connecting Sheets to your mobile platform's API. This creates a self-updating CMO-ready mobile analytics view without engineering resources.

**Compliance Automation:**
Connect your opt-out list to HubSpot/Salesforce via Zapier to auto-suppress contacts in CRM within minutes of opt-out. Store TCPA consent records in a dedicated Airtable base linked to contact records in your CRM for audit trail documentation.

## Troubleshooting

**Problem: Attribution numbers look inflated — mobile-influenced pipeline exceeds what seems plausible.**
Solution: Check your attribution window length. A 90-day window will capture far more touches than a 30-day window. For B2B SaaS with long sales cycles, 90 days is appropriate but should be disclosed in reporting. Also audit whether your CRM campaign membership is recording mobile touches accurately — duplicate contact records or unmapped phone numbers can inflate reach numbers.

**Problem: SMS delivery rate below 90% even with a clean list.**
Solution: This signals carrier filtering, not list quality. Audit message content for spam trigger words (FREE, URGENT, GUARANTEED), ensure your sending number/short code is registered with The Campaign Registry (TCR) for 10DLC in the US, and verify your SMS platform is using direct carrier connections rather than aggregated routes. Unregistered 10DLC campaigns face 60-70% message blocking rates from major carriers.

**Problem: Low push notification opt-in rate (<20%) from your trial user base.**
Solution: The permission-request timing and copy are the lever, not the channel itself. Best practice is to request push permission after the user has experienced their first "aha moment" in the product (typically day 2-5 of trial, post first value action). A/B test the permission dialog copy — "Get notified when [specific value event] happens" significantly outperforms generic "Turn on notifications." Opt-in rates of 40-60% are achievable with in-context, value-specific permission requests.

## Version History
- v1.0: Initial creation (auto-generated)
