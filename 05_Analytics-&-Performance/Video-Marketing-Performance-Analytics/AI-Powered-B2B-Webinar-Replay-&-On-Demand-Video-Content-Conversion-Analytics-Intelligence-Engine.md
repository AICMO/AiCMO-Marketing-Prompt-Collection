# AI-Powered B2B Webinar Replay & On-Demand Video Content Conversion Analytics Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** video-analytics, webinar, on-demand-content, lead-scoring, pipeline-attribution, b2b, saas, demand-gen, content-performance

## Overview
Transforms your library of recorded webinars and on-demand video assets into a fully instrumented demand-generation engine — scoring viewer intent, attributing pipeline influence, and triggering automated follow-up based on watch behavior. Use this when you need to extract measurable revenue contribution from content you've already produced and stop treating replays as passive archive material.

## Quick Copy-Paste Version

You are a B2B demand generation analyst specializing in video content performance and pipeline attribution. Analyze the on-demand video and webinar replay program for a B2B SaaS company and build a complete analytics and conversion optimization system.

Company context:
- Product: [Your product, e.g., "AI-powered procurement automation for mid-market and enterprise companies"]
- On-demand video library size: [e.g., "42 webinar recordings, 18 demo videos, 12 product walkthroughs"]
- Current video hosting platform: [e.g., "Wistia, Vidyard, Vimeo, YouTube"]
- CRM/MAP: [e.g., "Salesforce + HubSpot Marketing Hub"]
- Average replay views per webinar in first 30 days: [e.g., "280 views"]
- Current lead scoring system: [e.g., "MQL threshold = 50 points; no video watch events currently scored"]
- Known pipeline attribution gaps: [e.g., "Can't tell if replay viewers became pipeline; no post-replay nurture sequence"]

Build a complete on-demand video analytics and conversion system that includes:

1. VIDEO ENGAGEMENT SCORING MODEL
   Define a behavioral scoring framework that assigns lead score points based on video watch events: completion percentage thresholds (25%, 50%, 75%, 100%), rewatch behavior, multi-video sessions, and chapter/topic-level engagement. Specify point values for each behavior and how they integrate with your existing MQL scoring model.

2. INTENT SIGNAL SEGMENTATION
   Segment on-demand viewers into four intent tiers (High/Medium/Low/Research) based on their watch behavior profile. For each tier: define the behavioral criteria, estimated pipeline conversion probability, and recommended marketing response within 24 hours.

3. VIDEO-TO-PIPELINE ATTRIBUTION FRAMEWORK
   Design a multi-touch attribution model that credits video content for its role in buyer journeys. Include: first-touch video attribution (video was the first known touchpoint), assist attribution (video watched during active pipeline stage), and acceleration attribution (video watch compressed deal cycle). Specify the Salesforce/HubSpot field mapping and reporting structure.

4. CONTENT PERFORMANCE SCORING MATRIX
   Build a scoring matrix to rank your on-demand video assets by revenue impact. Score each asset on: average completion rate, lead-to-opportunity conversion rate for viewers, pipeline influence per 100 views, topic-to-ICP relevance, and recency/freshness. Use this matrix to identify which assets to promote, retire, gate, or update.

5. GATING STRATEGY & PROGRESSIVE PROFILING DESIGN
   Recommend an intelligent gating strategy that balances lead capture with viewer experience. Define: which video types should be fully gated, partially gated (watch 30%, then gate), or ungated with reverse IP enrichment. Design a progressive profiling sequence that captures 3-5 additional data points across multiple video views without form fatigue.

6. AUTOMATED POST-WATCH NURTURE SEQUENCES
   Design intent-triggered email sequences that fire within 4 hours of a video watch event. For each intent tier, specify: sequence length, messaging angle, content recommendations for next watch, and escalation path to SDR outreach. Include subject line templates and CTA recommendations.

7. REPLAY PROMOTION & DISTRIBUTION ANALYTICS
   Build a performance dashboard for on-demand content distribution channels: email promotion, organic social, paid amplification, SEO (show notes/transcripts), and in-app recommendations. Define the KPIs for each channel and the 30-day decay model for replay promotion ROI.

8. AI AGENT AUTOMATION ARCHITECTURE
   Specify the AI agent workflows that make this system autonomous: watch event → CRM update → score recalculation → segment assignment → nurture enrollment → SDR alert (if high-intent). Include the data inputs, trigger logic, and tool integrations required for each automation step.

Output a complete system specification that a marketing operations manager can implement in HubSpot or Marketo within 30 days, with all scoring logic, attribution rules, and automation triggers defined.

## Advanced Customizable Version

ROLE: You are a senior marketing analytics architect with 15+ years of experience designing B2B content attribution systems. You specialize in converting passive content consumption into active pipeline signals using behavioral scoring, AI-assisted intent detection, and CRM automation. You have deep expertise in Wistia, Vidyard, HubSpot, Marketo, and Salesforce integrations.

OBJECTIVE: Design a complete on-demand video and webinar replay analytics system that transforms passive video consumption into a measurable, automated pipeline-generation channel for a B2B SaaS company.

COMPANY PROFILE:
- Company: [Company name]
- Product category: [e.g., "RevOps automation platform"]
- ICP: [e.g., "VP of Revenue Operations and CROs at 200-2000 employee SaaS companies"]
- Video library: [Asset count and types — webinars, demos, product tours, customer stories, thought leadership]
- Tech stack: [Video hosting / CRM / MAP / BI tool]
- Current video performance baseline: [Average views, completion rates, any existing pipeline attribution]
- Sales cycle length: [e.g., "60-90 days"]
- Primary gap to solve: [e.g., "We generate 300+ replay views per webinar but have zero pipeline attribution and no automated follow-up"]

FRAMEWORK: Apply the following methodology across all deliverables:
- DACE Model: Detect → Attribute → Convert → Expand (video signals driving all four buyer journey phases)
- Engagement Quality Score (EQS): Composite score of depth × breadth × recency of video consumption
- Revenue Influence Mapping: Connecting video touchpoints to pipeline stages using time-to-event analysis

DELIVERABLE 1: VIDEO BEHAVIORAL SCORING ARCHITECTURE

Design a granular lead scoring model for video engagement:

A. Watch Depth Events (primary intent signals):
   - 0-25% completion: [Score] points — curiosity/awareness signal
   - 25-50% completion: [Score] points — active evaluation signal
   - 50-75% completion: [Score] points — strong interest signal
   - 75-100% completion: [Score] points — high-intent signal
   - 100% completion + rewatch: [Score] bonus points — purchase consideration signal

B. Engagement Quality Multipliers:
   - Watched 3+ videos in single session: 1.5x multiplier
   - Watched video within 48 hours of email send: 1.3x multiplier (intent recency bonus)
   - Watched competitor comparison or pricing-adjacent video: 2x multiplier
   - Watched customer success story or case study video: 1.75x multiplier

C. Content Type Weighting:
   Assign different base scores by video category:
   - Demo/product walkthrough: [Score] — highest purchase intent signal
   - Customer success story: [Score] — social proof consumption signal
   - Thought leadership/educational: [Score] — awareness/research signal
   - ROI/pricing/comparison: [Score] — late-stage evaluation signal
   - Onboarding/feature deep-dive: [Score] — existing customer expansion signal

D. Decay Model:
   Define score decay rates: video watch scores should decay X% per week after 14 days to ensure scoring reflects recent, active interest rather than historical consumption.

DELIVERABLE 2: INTENT TIER CLASSIFICATION & SALES HANDOFF PROTOCOL

Define four intent tiers with precise behavioral criteria and recommended response:

TIER 1 — PURCHASE INTENT (SDR Alert within 4 hours):
Behavioral criteria: [e.g., "Watched 2+ high-intent videos (demo, pricing, comparison) at 75%+ completion in the past 7 days, reached MQL threshold of 75+ points"]
Marketing response: [Immediate SDR email + LinkedIn connect + personalized outreach brief]
SDR outreach context to provide: Topics watched, chapters engaged, company firmographics, behavioral timeline

TIER 2 — ACTIVE EVALUATION (High-Velocity Nurture):
Behavioral criteria: [e.g., "Watched 1 high-intent or 3+ mid-intent videos, 50%+ completion, total score 40-74 in past 14 days"]
Marketing response: [Personalized email sequence, relevant case study, demo invitation, sales chat widget activation]

TIER 3 — ENGAGED RESEARCH (Standard Nurture Acceleration):
Behavioral criteria: [e.g., "Watched 2+ educational videos at 25%+ completion, total score 20-39"]
Marketing response: [Relevant content recommendations, topic cluster nurture, invite to next live webinar]

TIER 4 — PASSIVE CONSUMPTION (Long-Cycle Nurture):
Behavioral criteria: [e.g., "Single video view at <25% completion, score <20, or 30+ days since last watch event"]
Marketing response: [Monthly newsletter, relevant blog content, soft retargeting]

DELIVERABLE 3: VIDEO CONTENT PERFORMANCE MATRIX & EDITORIAL DECISION FRAMEWORK

Build a ranking system for all on-demand assets using the Revenue Impact Score (RIS):

RIS Formula: (Completion Rate × 0.30) + (Lead-to-Opp Rate × 0.35) + (Pipeline Influence/100 Views × 0.25) + (ICP Relevance Score × 0.10)

For each asset category, provide:
- Performance benchmark thresholds (P90/P50/P10 performance bands)
- Editorial recommendations based on performance tier:
  * Promote: RIS in P90 — feature in email, paid amplification, homepage placement
  * Refresh: RIS in P50 but strategic topic — update with new data, re-promote
  * Retire: RIS in P10 and < 6 months old — archive and 301 redirect to replacement
  * Gate/Ungate Decision: High-completion ungated assets may perform better as leads via reverse IP enrichment vs. form completion

DELIVERABLE 4: PIPELINE ATTRIBUTION MODEL DESIGN

Define three attribution models and when to use each:

Model A — VIDEO-FIRST ATTRIBUTION (for proving content ROI to leadership):
Count a video touchpoint as "pipeline attributed" if: a video watch event occurred within the 90 days before opportunity creation, at 50%+ completion, from an account with no prior CRM contact record.
Metric to report: Video-first opportunities as % of total MQL-sourced pipeline.

Model B — VIDEO-ASSIST ATTRIBUTION (for optimizing nurture programs):
Count a video touchpoint as "assist" if: video was watched after a contact existed in CRM but before opportunity stage 2 (Discovery → Technical Evaluation transition).
Metric to report: Stage velocity improvement (days from stage 1 to stage 2) for contacts with ≥1 video-assist touchpoint vs. those without.

Model C — VIDEO-ACCELERATION ATTRIBUTION (for proving deal cycle compression):
Measure the average sales cycle length for opportunities where at minimum 1 high-intent video was watched (demo, pricing, customer story) between stages 2-4 vs. opportunities with no video engagement.
Metric to report: Days saved per deal with video engagement; annualized pipeline value of compressed cycles.

DELIVERABLE 5: AUTOMATED NURTURE SEQUENCE ARCHITECTURE

Design AI-triggered email sequences for each intent tier, specifying:
- Trigger event: [specific watch event that fires the sequence]
- Delay window: [time between trigger and first email]
- Sequence length and send cadence
- Subject line formula by message position
- CTA architecture (soft → medium → direct ask progression)
- Branching logic: [if email opened but no click → variant B; if no open → sequence hold for 5 days]
- Suppression rules: [active opportunities, existing customers, unsubscribed domains]

Include specific templates for a high-intent trigger sequence (Tier 1) with:
- Email 1 (4 hours post-watch): Subject formula: "[Video topic] + your specific challenge at [Company]" — reference the exact video watched, add relevant social proof
- Email 2 (Day 2): Subject formula: "What [Customer Name] achieved with [Product] after asking the same question" — case study relevant to watched content
- Email 3 (Day 4): Subject formula: "The 15-minute [Product] walkthrough built for [Job Title]s" — personalized demo invite

DELIVERABLE 6: REPORTING DASHBOARD SPECIFICATION

Define the exact metrics, visualizations, and cadence for each audience:

WEEKLY MARKETING OPS DASHBOARD:
- Video views by intent tier (trending up/down vs. prior week)
- High-intent viewer count and SDR conversion rate
- On-demand MQL creation (video-first attribution)
- Top 5 performing assets by EQS-weighted views
- Automation health: trigger fire rate, sequence enrollment, deliverability

MONTHLY CMO DASHBOARD:
- Video-influenced pipeline ($) and % of total marketing pipeline
- Stage velocity improvement for video-engaged opportunities
- Content library ROI: total pipeline influenced / video production cost
- Replay decay curves: % of total views captured in days 1-7, 8-30, 31-90 post-production
- Recommended editorial actions (promote/refresh/retire) based on RIS scores

QUARTERLY BOARD-READY METRIC:
- Video Content Revenue Contribution = (Video-Assist Pipeline × Win Rate) + (Video-Acceleration Savings × Margin)

DELIVERABLE 7: 30-DAY IMPLEMENTATION ROADMAP

Provide a phased implementation plan:
Week 1 — Instrumentation: Wistia/Vidyard HubSpot/Salesforce integration, event tracking setup, custom properties and scoring rules configured
Week 2 — Scoring & Segmentation: Intent tier logic deployed, existing contact database retroactively scored on historical watch data (past 90 days), tier assignments validated with sales
Week 3 — Automation: Post-watch sequences built and tested, SDR alert templates configured, Slack/CRM notification routing live
Week 4 — Reporting: Dashboard builds complete, first weekly review cadence initiated, baseline metrics established for future optimization

CONSTRAINTS:
- All automation must be implementable in HubSpot Marketing Hub Professional or Marketo Engage without custom code
- Attribution model must be explainable to a CFO in under 2 minutes
- Scoring model must not create more than 10% false positive "high-intent" classifications (validated against historical close rate data)
- All AI agent recommendations must include a human-review checkpoint before SDR outreach triggers

OUTPUT FORMAT:
Deliver a complete 12-section technical specification document that a marketing operations manager with HubSpot certification can implement without additional consulting. Include all scoring values, field names, workflow trigger logic, and KPI benchmarks using specific numbers, not placeholders.

## Example Input/Output

**Input Example:**

Company: Velorum AI — AI-powered financial close automation for CFOs and accounting teams at $50M-$500M revenue companies.

Video library: 28 webinar recordings (average 45 min), 6 product demo videos (15-20 min), 4 customer success stories (8-12 min), 3 ROI calculator walkthroughs (5 min).

Tech stack: Vidyard + HubSpot Enterprise + Salesforce.

Baseline: 180-250 webinar replay views per recording in first 30 days, 3-8% form completion rate on gated replays, no watch events flowing to CRM, no post-watch automation, zero pipeline attribution for on-demand content.

**Output Example:**

**VELORUM AI — ON-DEMAND VIDEO CONVERSION SYSTEM**

**Video Behavioral Scoring Model:**
| Watch Depth | Score | Rationale |
|-------------|-------|-----------|
| 0-25% | 3 pts | Awareness signal; low intent |
| 25-50% | 8 pts | Active interest; content matched search intent |
| 50-75% | 18 pts | Strong evaluation signal; prioritize for nurture |
| 75-100% | 30 pts | High-intent; 4.2x more likely to request demo |
| 100% + rewatch | 42 pts | Purchase consideration; SDR alert at this threshold |

**Content Type Multipliers for Velorum AI:**
- Demo video watch (50%+): 2.5x — CFOs watching full product demos have 7x higher close rates than email-only contacts
- ROI calculator walkthrough (75%+): 3x — late-stage financial decision trigger
- Customer success story (75%+): 1.8x — social proof, high close rate correlation
- Webinar replay (educational, 50%+): 1x base — research phase, high volume but lower individual intent

**Sample Tier 1 High-Intent Profile (SDR Alert):**
Sarah Chen, VP of Finance, Series C SaaS company (480 employees), watched "Velorum AI: The 30-Day Financial Close Demo" at 94% completion, rewatched the reconciliation automation segment twice, then watched "How Stripe Finance Team Reduced Close Time by 40%" at 87% completion — all within a 2-hour session. Total EQS: 118 points.

SDR Alert Payload Sent to Salesforce:
Account: TechNova Inc | Contact: Sarah Chen | Score: 118
Videos Watched: Demo (94%) + Customer Story (87%)
High-Intent Signals: Rewatch detected on "Reconciliation Automation" (3:45-5:20 mark)
Recommended Opener: "I saw you explored how Stripe Finance reduced their close cycle — happy to show you what that looks like for a Series C SaaS at your scale."
Next Best Asset: Velorum AI ROI Calculator — Finance Team

**30-Day Attribution Results (Pilot):**
- Video-first opportunities created: 14 ($892K pipeline)
- Stage 2→3 velocity: 8.3 days faster for video-engaged contacts vs. control group
- Demo-to-close correlation: 68% of closed/won deals in Q3 had watched ≥1 demo video at 75%+
- Top performing asset: "The Month-End Close Automation Demo" — 34 pipeline-attributed opportunities, $2.1M influenced

## Success Metrics

- **Video-first MQL rate**: Target ≥ 15% of on-demand viewers converting to scored MQL within 30 days
- **Stage velocity improvement**: ≥ 10% reduction in days from Stage 1 to Stage 3 for video-engaged contacts
- **SDR conversion rate from Tier 1 alerts**: ≥ 25% of Tier 1 alerts converting to booked meeting
- **Post-watch sequence open rate**: ≥ 40% (personalized video-reference subject lines outperform generic)
- **Pipeline attribution coverage**: ≥ 30% of all MQL-sourced pipeline has at least one video-assist touchpoint within 90 days
- **Content library ROI**: Video-influenced pipeline value ≥ 10x annual video production budget
- **False positive rate**: < 10% of Tier 1 SDR alerts result in "not in market" feedback from sales

## Related Prompts

- [AI-Powered B2B Video Marketing Performance Analytics & Cross-Platform Pipeline Revenue Attribution Intelligence Engine](./AI-Powered-B2B-Video-Marketing-Performance-Analytics-&-Cross-Platform-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B LinkedIn & Multi-Platform Organic Video Intelligence & Pipeline Revenue Attribution Engine](./AI-Powered-B2B-LinkedIn-&-Multi-Platform-Organic-Video-Intelligence-&-Pipeline-Revenue-Attribution-Engine.md)
- [AI-Powered Webinar & Virtual Event Performance Analytics Intelligence Engine](../../05_Analytics-&-Performance/Event-Marketing-Analytics/AI-Powered-Webinar-&-Virtual-Event-Performance-Analytics-Intelligence-Engine.md)
- [AI-Powered B2B Gated Content Lead Magnet Performance Analytics & Pipeline Contribution Intelligence Engine](../../05_Analytics-&-Performance/Content-Marketing-Performance-Analytics/AI-Powered-B2B-Gated-Content-Lead-Magnet-Performance-Analytics-&-Pipeline-Contribution-Intelligence-Engine.md)

## Integration Tips

- **Vidyard + HubSpot**: Enable Vidyard's native HubSpot integration to push watch events as timeline activities; create custom contact properties for `video_qs_total`, `video_tier_assigned`, `last_video_watched_date`, `video_completion_max`
- **Wistia + Salesforce**: Use Wistia's Turnstile for in-video gating and the Wistia Salesforce connector to map viewer data to Leads/Contacts; build a Process Builder flow to update Lead Score field when video watch event is logged
- **Marketo + Vidyard**: Use Vidyard's Marketo integration to trigger Smart Campaigns on watch milestones; add `Video Watch Score` as a scoring behavior in your existing Marketo scoring program
- **Slack Alerts**: Pipe Tier 1 SDR alerts to a dedicated `#hot-video-leads` Slack channel using Zapier (HubSpot workflow webhook → Zapier → Slack message) with company name, contact, videos watched, and EQS score
- **Google Sheets Dashboard**: Use HubSpot's reporting API or a Databox integration to auto-populate a weekly Google Sheet scorecard with top 10 performing assets by pipeline influence — share with marketing leadership every Monday AM
- **Gong Integration**: When a Tier 1 video alert converts to a booked demo, pass the video watch history to Gong as pre-call research notes so AEs can reference what the prospect watched in their opening minutes

## Troubleshooting

**Problem: Watch events appear in video platform but are not flowing to HubSpot/Salesforce CRM.**
Solution: Confirm the video embed code on your landing pages includes the Vidyard/Wistia identification pixel tied to your contact's email. Anonymous views don't connect to CRM records until the contact is cookied. Implement email-gated replay access for all Tier 1 assets; ungated views should use reverse IP enrichment (Clearbit Reveal or 6sense) to identify company-level engagement even without contact match.

**Problem: SDR team is complaining that Tier 1 alerts are producing low-quality meetings — "these people just watched a video, they're not ready."**
Solution: Tighten Tier 1 criteria to require a minimum of two high-intent video watches (not one) plus a total EQS of 80+ points within a 7-day window. Add firmographic filters (revenue ≥ $25M, ICP industry match, no "Out of Business" status) before alert fires. Also review SDR outreach scripts — subject lines referencing the specific video watched and the specific topic they rewatched consistently outperform generic "I saw you checked out our content" openers by 3x.

**Problem: On-demand content attribution numbers are very low — showing video influenced only 2% of pipeline.**
Solution: This usually means attribution lookback window is too short or watch depth threshold is too high. Start by setting your attribution lookback to 180 days (not 90) and your completion threshold to 25% (not 50%) for the first 60 days to establish baseline volume. Then tighten thresholds once you've validated that higher-completion videos actually correlate with higher close rates in your data. Also confirm that historical watch data (past 90 days) was retroactively synced to CRM records — new implementations often only capture forward-looking events.

## Version History
- v1.0: Initial creation (auto-generated)
