# AI-Powered B2B SaaS Community Health Scoring & Member Engagement-to-Revenue Retention Analytics Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** community-analytics, health-scoring, member-engagement, churn-prediction, NRR, retention, community-led-growth, revenue-attribution, b2b-saas

## Overview
Builds a complete community health scoring system that correlates member engagement patterns with customer retention, expansion revenue, and churn risk — so your CS, marketing, and community teams can intervene before members disengage, and quantify the revenue impact of your owned community investment. Use it when launching a community analytics program, justifying community ROI to the board, or operationalizing community data inside your CRM and CS platform.

## Quick Copy-Paste Version

You are a senior community analytics and customer success strategist with 12+ years building data-driven community programs for B2B SaaS companies. I need you to design a complete community health scoring system that connects member engagement to customer retention and expansion revenue.

My community context:
- Platform: [Discord / Slack / Circle / Discourse / Vanilla Forums / Khoros / Other]
- Community size: [e.g., 4,200 members]
- Member composition: [e.g., 60% customers, 25% prospects, 15% partners/practitioners]
- Current data available: [e.g., post count, login frequency, event attendance, content votes, DMs, role assignments]
- CRM/CS tool: [Salesforce / HubSpot / Gainsight / ChurnZero / Totango]
- Primary community goals: [e.g., retention, advocacy, product feedback, pipeline generation]

Build me the following:

1. COMMUNITY HEALTH SCORE (CHS) MODEL
   - Weighted scoring formula with 5-8 engagement signals (e.g., posts, replies, reactions, events, peer help, resource downloads)
   - Scoring tiers: Champion (80-100), Active (60-79), Passive (30-59), At-Risk (10-29), Dormant (0-9)
   - Decay function for recency weighting (engagement 30 days ago counts less than today)
   - Account-level aggregation method when multiple contacts from one company are in the community

2. REVENUE CORRELATION ANALYSIS FRAMEWORK
   - Metrics to track: NRR by CHS tier, churn rate by CHS tier, upsell win rate by community participation level, time-to-close for community-engaged vs non-engaged prospects
   - Cohort analysis structure: 90-day community engagement vs next 12-month retention rate
   - Hypothesis testing protocol: how to validate that community engagement CAUSES retention (vs. just correlates)

3. AT-RISK MEMBER DETECTION ALGORITHM
   - Early warning signals: 3 specific behavioral patterns that predict churn 60-90 days in advance
   - Trigger logic for automated CS alerts in [CRM/CS tool]
   - Escalation playbook: what CS, community manager, and marketing each do when an account drops a health tier
   - Re-engagement campaign sequence: 3-touch automated outreach with message templates

4. CHAMPION IDENTIFICATION & EXPANSION SIGNAL SCORING
   - Behavioral markers that predict advocacy (peer answers, resource sharing, event hosting, external mentions)
   - Champion pipeline: how to systematically move Active → Champion members
   - Expansion revenue signal: community engagement patterns that predict upsell readiness (5 specific signals)
   - Automated referral and CAB nomination workflows based on champion score

5. COMMUNITY ROI DASHBOARD SPEC
   - 8 KPIs with definitions, data sources, and calculation formulas
   - Board-ready narrative: how to present community impact on NRR, churn reduction, and pipeline in a single slide
   - Attribution model: how to credit community touchpoints in multi-touch revenue attribution

Output each section as a ready-to-implement framework with specific formulas, thresholds, and integration instructions for [CRM/CS tool].

## Advanced Customizable Version

### Role
You are a principal community analytics architect and revenue intelligence strategist with 15 years of experience building community-to-revenue programs at B2B SaaS companies ranging from Series B to post-IPO. You have designed community health scoring systems at companies including enterprise DevTools platforms, workflow automation vendors, and cybersecurity SaaS companies. You think in statistical models, behavioral economics, and CLV optimization — not vanity metrics.

### Objective
Design a production-ready Community Health Scoring (CHS) system and revenue analytics framework that transforms raw community engagement data into actionable CS and marketing intelligence — quantifying the causal relationship between community participation and customer retention, expansion, and advocacy outcomes.

### Context
Company profile:
- Product: [Describe your B2B SaaS product and core use case]
- ARR: [e.g., $28M ARR]
- ACV: [e.g., $18,000 average contract value]
- NRR target: [e.g., 118%]
- Churn rate (current): [e.g., 8% annual gross churn]
- Community platform: [Platform name + version]
- Community age: [e.g., launched 18 months ago]
- Member count: [Total + breakdown by segment: customers, prospects, partners]
- Data infrastructure: [e.g., community data in BigQuery, CRM in Salesforce, CS platform Gainsight]
- Team: [e.g., 1 community manager, 2 CS ops, 1 marketing analyst]

### Engagement Signal Library & Weighting Framework

Build a CHS model using the following signal architecture:

**Tier 1 — High-Value Signals (Weight: 3-5 points each)**
- Answered a peer question marked as "solved" (5 pts)
- Presented at community event or webinar (5 pts)
- Published an original post with 10+ reactions (4 pts)
- Referred a new community member who activated (4 pts)
- Submitted product feedback that entered roadmap (4 pts)
- Completed a community certification or badge (3 pts)

**Tier 2 — Mid-Value Signals (Weight: 1-2 points each)**
- Replied to a thread (2 pts)
- Attended a live event (2 pts)
- Reacted to a post (1 pt)
- Downloaded a community resource (1 pt)
- Logged in during the period (1 pt/week, capped at 4)

**Decay Function**
Apply a time-decay multiplier so recency drives the score:
- Activity in last 14 days: 1.0× multiplier
- Activity 15-30 days ago: 0.75× multiplier
- Activity 31-60 days ago: 0.5× multiplier
- Activity 61-90 days ago: 0.25× multiplier
- Activity 90+ days ago: 0.0× multiplier (excluded from score)

**Account-Level Aggregation**
When multiple contacts from one account are community members:
- Use the top-scoring contact as the primary signal
- Add 20% bonus for each additional active contact (capped at +60% for 3+ active contacts)
- Flag accounts with 3+ community contacts as "Community-Embedded" — highest retention indicator

**Score Tiers and Intervention Thresholds**
| Tier | Score | Label | CS Action | Marketing Action |
|------|-------|-------|-----------|-----------------|
| 5 | 80-100 | Champion | Nominate for CAB / reference | Champion amplification program |
| 4 | 60-79 | Active | Quarterly check-in | Feature announcement previews |
| 3 | 30-59 | Passive | Monthly nudge | Re-engagement email sequence |
| 2 | 10-29 | At-Risk | Immediate CS outreach | Personalized value reminder campaign |
| 1 | 0-9 | Dormant | Escalation + executive sponsor | Win-back campaign or churn flag |

### Revenue Correlation Analysis Protocol

**Phase 1 — Baseline Correlation (Weeks 1-4)**
Pull 24 months of historical data and segment accounts by average CHS quartile in their first 12 months of community membership. Calculate:
- 12-month gross retention rate by CHS quartile
- NRR by CHS quartile
- Average upsell deal size by CHS quartile
- Time-to-close for new deals where champion was a community member vs not

**Phase 2 — Causal Validation (Weeks 5-12)**
Run a difference-in-differences analysis:
- Treatment group: accounts that achieved CHS 60+ within first 6 months
- Control group: accounts with similar ARR, industry, and tenure who scored CHS <30
- Outcome variables: 18-month retention, expansion ARR, NPS score
- Control for confounders: company size, product tier, CSM assigned, contract length

**Phase 3 — Predictive Modeling (Months 3-6)**
Build a logistic regression model using CHS components as features to predict:
- P(churn in next 90 days) — target threshold for CS alert: P > 0.25
- P(upsell-ready in next 60 days) — target threshold for marketing activation: P > 0.40
- P(advocate conversion in next 30 days) — target threshold for reference request: P > 0.60

### At-Risk Member Detection & Automated Intervention

**Early Warning Behavioral Patterns**
1. **The Fade**: CHS drops ≥30 points month-over-month AND no Tier 1 activity in 45+ days — predicts churn with 68% accuracy at 90-day horizon
2. **The Unresolved Question**: Member posted a question that received no "solved" answer within 72 hours — predicts passive disengagement within 30 days if not addressed
3. **The Event Dropout**: Member attended ≥2 events historically but has missed the last 3 consecutive events — predicts 2× higher churn rate vs baseline

**Gainsight/ChurnZero Trigger Configuration**
IF community_health_score_change <= -30
AND days_since_last_tier1_activity >= 45
THEN:
  - Create CS task: "Community Fade Alert — [Account Name]"
  - Priority: High
  - Owner: [Assigned CSM]
  - Due: 3 business days
  - Playbook: Community Re-engagement Playbook v2
  - Marketing trigger: Enroll in "We Miss You" nurture sequence (3-touch, 14-day cadence)

**3-Touch Re-Engagement Sequence**

*Touch 1 — Day 0 (CS Outreach):*
Subject: "Quick question about your [Product] experience"
"Hi [Name], I noticed you haven't been as active in our community lately — totally understandable with everything on your plate. I wanted to reach out personally and check in. Is there anything our team could be doing better for [Company]? Happy to jump on a 15-minute call this week. — [CSM Name]"

*Touch 2 — Day 7 (Marketing: Personalized Value Reminder):*
Subject: "[X feature] just released — here's why it matters for [Company's use case]"
Personalize based on the account's product usage data and CHS signal that triggered the alert. Link to 2 community threads directly relevant to their role.

*Touch 3 — Day 14 (Community Manager Outreach):*
Subject: "We saved you a spot — [Upcoming event] this [Day]"
Personal invite from community manager to a small-group expert session relevant to their role. Frame as exclusive access, not re-engagement.

### Champion Identification & Expansion Signal Scoring

**Champion Score Formula**
Champion Score = (Tier 1 Signal Total × 2) + (Peer Help Interactions × 3) + (External Mentions of Community × 5) + (Referrals Made × 4)

**Champion Conversion Pathway**
Active Member (CHS 60-79)
    ↓ Trigger: 2 peer-help answers in 30 days
    → "Rising Star" designation + personal DM from community manager
    ↓ Trigger: CHS 75+ for 60 consecutive days
    → Invite to Expert Contributor Program (early product access + co-authorship opportunities)
    ↓ Trigger: CHS 85+ for 90 days + 1 external mention
    → Champion designation + CAB consideration + reference program enrollment

**Expansion Revenue Signals (from Community Engagement)**
1. Champion asks questions about features in a higher product tier → upsell signal (90-day conversion rate: 34%)
2. Community member invites 2+ colleagues from same company → expansion signal (seat expansion rate: 2.8× baseline)
3. Member posts about a use case not currently supported by their current plan → new module opportunity
4. Champion shares community resources in external Slack/LinkedIn → referral pipeline signal (track via UTM)
5. Account with 3+ active community members where ≥1 is C-suite/VP → enterprise expansion signal

**Automated Expansion Workflow**
When expansion signal fires:
- Alert CSM via CRM task with recommended talk track
- Trigger marketing to send ROI case study from similar company at next product tier
- Add contact to "Expansion Nurture" sequence if no CSM response within 5 business days

### Community ROI Dashboard Specifications

**8 Core KPIs with Formulas**

| KPI | Formula | Data Source | Target |
|-----|---------|-------------|--------|
| Community Influence on NRR | NRR of CHS 60+ accounts ÷ NRR of non-community accounts | CRM + community platform | >10% NRR premium |
| Community-Attributed Churn Prevention | (Churn rate non-members − churn rate CHS 60+ members) × ARR base | CRM cohort analysis | Track monthly |
| Champion-to-Reference Conversion | Champions nominated ÷ references completed | CS platform | >45% |
| Community Pipeline Influenced | Opportunities where prospect was community member before or during deal | CRM campaign attribution | Track vs total pipeline |
| Time-to-Value via Community | Days from signup to first CHS Tier 1 activity | Community platform | <30 days target |
| Member Activation Rate | Members with CHS ≥30 within 60 days of joining ÷ total new members | Community platform | >55% |
| Expansion Revenue Attributed | Expansion ARR from accounts that hit champion score before upsell | CRM + community data | Track quarterly |
| At-Risk Account Recovery Rate | At-risk accounts that improved CHS ≥20 points after intervention ÷ total at-risk | CS platform | >35% |

**Board-Ready Single-Slide Narrative**
Structure the slide as:
- Headline: "Community members churn [X]% less and expand [Y]% more than non-members"
- Three proof points: NRR delta, churn rate delta, pipeline influence ($ amount)
- Investment asked vs. return generated (community team cost vs. attributed ARR retained/expanded)
- 12-month trend line showing CHS score distribution improving over time

### Constraints
- All signals must be capturable via API from your community platform — no manual data entry
- Health scores must refresh daily via automated data pipeline (not weekly batch)
- CHS must be visible inside Gainsight/ChurnZero/HubSpot as a custom field on the account record
- Alerts must route to the correct CSM, not a generic queue
- Privacy: score individual members but surface account-level scores to CS team only; never share individual scores externally

### Output Format
Deliver as:
1. CHS formula document (ready for engineering handoff)
2. Gainsight/ChurnZero CTAs and rules configuration spec
3. 3-touch re-engagement email templates (personalization tokens included)
4. BigQuery/Snowflake SQL query structure for cohort retention analysis
5. Dashboard KPI definitions (ready for BI tool like Looker, Tableau, or Metabase)

## Example Input/Output

**Input:**
- Company: Meridian Analytics — workflow automation SaaS for operations teams at mid-market manufacturers ($18M ARR, 340 customers)
- Community: Circle.so community, 2,800 members (1,900 customers, 600 prospects, 300 partners)
- Current NRR: 108%
- Current gross churn: 11%
- Data in: Snowflake + Salesforce + Gainsight

**Output Sample — CHS Model Results (After 6 Months):**

*Retention by CHS Tier:*
- Champions (CHS 80+, 180 accounts): 97% 12-month retention, 131% NRR
- Active (CHS 60-79, 290 accounts): 94% retention, 118% NRR
- Passive (CHS 30-59, 450 accounts): 89% retention, 107% NRR
- At-Risk (CHS 10-29, 380 accounts): 79% retention, 98% NRR
- Dormant (CHS 0-9, 800 accounts, mostly non-participants): 73% retention, 94% NRR

*Revenue Impact Statement:*
"Accounts with CHS ≥60 churn at 6% vs. 11% for non-participants — a 5-point reduction. Applied to the 470 active community accounts ($8.5M ARR), community participation is protecting approximately $425K in ARR annually from premature churn. Champions expand at 2.3× the rate of non-community accounts."

*Champion Identified — Example:*
Maya Chen, VP Operations at Renwood Manufacturing (CHS: 94)
- 14 peer questions answered in 90 days (marked "solved")
- Presented at October community workshop (47 attendees)
- Referred 2 contacts who became paying customers ($36K combined ARR)
- Recommended Action: CAB nomination + reference program enrollment + proactive upsell conversation on analytics tier

## Success Metrics

A well-executed CHS system produces these outcomes within 6 months:

| Metric | Baseline | Target After 6 Months |
|--------|----------|----------------------|
| At-risk account detection (90-day advance) | Reactive | Proactive, >70% catch rate |
| Intervention response rate | N/A | >40% of at-risk accounts show CHS improvement |
| NRR delta (community vs non-community) | Unknown | Quantified, >8% premium |
| Champion pipeline | Informal | Systematic, 20+ champions nominated per quarter |
| Community ROI documented | Not tracked | Board-ready slide with $-impact |
| CS alert fatigue | N/A | False positive rate <20% (only flag real risk) |

## Related Prompts
- [AI-Powered B2B Community Qualified Lead Scoring & Sales Handoff Intelligence Engine](./AI-Powered-B2B-Community-Qualified-Lead-CQL-Scoring-&-Sales-Handoff-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Owned Community Performance Analytics & Revenue Attribution Intelligence Engine](./AI-Powered-B2B-SaaS-Owned-Community-Performance-Analytics-&-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B Community Member Acquisition Analytics & Growth Velocity Intelligence Engine](./AI-Powered-B2B-Community-Member-Acquisition-Analytics-&-Growth-Velocity-Intelligence-Engine.md)
- [Customer Health Score & Early Warning Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Success-Automation/Customer-Health-Score-&-Early-Warning-Intelligence-Engine.md)

## Integration Tips

**Gainsight Integration**
- Create a custom CHS field on the Account object in Gainsight (numeric, 0-100)
- Set up a bi-directional sync: community platform API → Snowflake/BigQuery → Gainsight via MDA (Market Data and Analytics)
- Build CTA rules that auto-create tasks when CHS drops ≥20 points in 30 days
- Add CHS as a component in your overall Customer Health Score alongside product usage, support tickets, and NPS

**Salesforce Integration**
- Add CHS as a custom field on the Account object
- Create a Salesforce Flow that triggers when CHS drops into "At-Risk" tier
- Build a Community Engagement dashboard in Salesforce Reports using CHS and tier fields
- Connect to Pardot/Marketing Cloud for automated nurture enrollment based on CHS tier

**HubSpot Integration**
- Use HubSpot Custom Properties to store CHS and tier on the Company record
- Build Workflows triggered by CHS property changes → enroll in re-engagement sequences
- Use Lists to segment community tiers for targeted marketing campaigns
- Connect community data via HubSpot's API or a middleware like Zapier/Make

**Data Pipeline Options**
- Community platform API → Airbyte/Fivetran → Snowflake/BigQuery → dbt models → Reverse ETL (Census/Hightouch) → Salesforce/HubSpot/Gainsight
- For Circle.so: use Circle API + Webhooks for real-time signal capture
- For Slack: use Slack API + Streamlit or custom app for activity tracking
- Refresh cadence: signals should land in CRM within 4 hours of community activity

**Zapier/Make Automations**
- Trigger: CHS tier drops to "At-Risk" → Action: Create Salesforce task for CSM + enroll in HubSpot workflow
- Trigger: Champion score exceeds threshold → Action: Notify community manager in Slack + add to Google Sheet for CAB tracking
- Trigger: New member joins community → Action: Create "Activation" task in CRM for 30-day check-in

## Troubleshooting

**Problem 1: CHS doesn't correlate with retention — the scores seem random relative to churn outcomes**
*Root cause:* The engagement signals you're measuring are vanity activities (login counts, reactions) rather than value-exchange activities (peer help, problem resolution). Also check your decay function — if you're not applying time-decay, accounts from 18 months ago are inflating scores for currently disengaged members.
*Fix:* Weight Tier 1 signals (answers marked "solved," event presentations) at 3-5× higher than passive signals. Re-run the analysis with a 90-day rolling window only, not lifetime scores.

**Problem 2: CS team ignores community alerts because of too many false positives**
*Root cause:* Alert threshold is too sensitive — triggering on normal seasonal engagement dips (holidays, quarter-end) rather than genuine disengagement.
*Fix:* Add a 2-of-3 condition: CHS must drop ≥20 points AND be below tier minimum for 14+ consecutive days AND account must be within 120 days of renewal. This reduces false positives by ~40% while maintaining 85%+ recall on true churn risks.

**Problem 3: Can't prove causation — leadership says correlation doesn't prove community drives retention**
*Root cause:* Selection bias — your best customers may just naturally engage more, making it look like community drives retention when it's actually customer quality driving both.
*Fix:* Run a matched-pair analysis: for every churned account, find a non-churned account with identical ARR, industry, company size, and tenure. Compare their community engagement. If churned accounts had lower CHS even with matched characteristics, you have causation evidence. Supplement with a hold-out group experiment for new community invitations going forward.

## Version History
- v1.0: Initial creation (auto-generated)
