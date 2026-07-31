# AI-Powered B2B SaaS Signal-Based Social Selling Analytics & Trigger-Event Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** social-selling, signal-based-gtm, revenue-attribution, analytics, pipeline, b2b, dark-social, buyer-intent, revenue-intelligence

## Overview

This prompt builds a complete analytics and attribution system for signal-based social selling programs — measuring trigger-event detection rates, signal-to-pipeline conversion, dark social community selling ROI, and rep-level performance. Use it when you have an active social selling or signal-based outreach motion and need to prove revenue impact, identify which triggers generate the highest-quality pipeline, and continuously optimize signal scoring models.

## Quick Copy-Paste Version

You are a senior B2B marketing analytics strategist with deep expertise in social selling attribution and signal-based GTM measurement. My company sells [PRODUCT/CATEGORY] to [ICP: job titles + company size + industry]. We have [X] SDRs/AEs running a signal-based social selling motion using [TOOLS: Clay, LinkedIn Sales Navigator, Bombora, etc.].

Design a complete analytics framework to measure our signal-based social selling program and attribute revenue to specific trigger events and social selling activities.

1. SIGNAL PERFORMANCE SCORECARD:
   - For each trigger type (job change, funding, hiring surge, competitive churn, tech stack change), calculate:
     * Detection-to-action rate: % of detected signals that result in outreach within the time-to-act window
     * Signal-to-reply rate: % of signal-triggered sequences that receive a reply
     * Signal-to-meeting rate: % of signals that convert to a qualified meeting
     * Signal-to-pipeline rate: % of signals that become opportunities ($)
     * Signal-to-closed-won rate: % of signals that generate revenue
   - Rank trigger types by pipeline-per-signal and closed-won-per-signal
   - Flag which signals are "burning" (high detection, low conversion) vs. "compounding" (low volume but high close rate)

2. DARK SOCIAL ATTRIBUTION MODEL:
   - Define how to credit social selling activities that don't have direct click tracking: LinkedIn comments, DMs, voice notes, video prospecting, community posts
   - Build a "social touch" attribution methodology: assign pipeline influence credit when a prospect engages with a rep's content within 30/60/90 days before a deal opens
   - Specify the self-reported attribution question to add to your discovery call or demo form: ["How did you first hear about us?"] — map responses to social selling activities
   - Create a "social proximity score" — measure how many social touches a closed-won account received vs. average deal

3. REP-LEVEL SOCIAL SELLING ANALYTICS:
   - Track per-rep: signals actioned per week, sequences sent per signal, reply rates by trigger type, LinkedIn connection acceptance rate, content engagement rate (likes/comments on rep posts), meetings booked from social activities
   - Identify the "social selling index" for each rep: composite score of profile completeness, posting frequency, engagement rate, and pipeline sourced
   - Benchmark reps against each other and against industry LinkedIn Social Selling Index (SSI) scores
   - Flag reps who are high-volume/low-conversion (poor personalization) vs. low-volume/high-conversion (selective but effective)

4. SIGNAL SCORING MODEL VALIDATION:
   - Backtest your current scoring model against 90 days of historical data: do 80+ scored signals actually convert at higher rates than 40-60 scored signals?
   - Identify scoring model drift: which signal types have become less predictive over the last quarter?
   - Recommend model recalibration: suggest weight adjustments based on actual conversion data
   - Add "signal stacking" analysis: do prospects who fire 3+ signals in 30 days actually convert faster and at higher rates?

5. WEEKLY SOCIAL SELLING INTELLIGENCE REPORT:
   - Template for a 1-page weekly report showing: top converting signals this week, pipeline added from social selling, at-risk signals (detected but not actioned), rep leaderboard, one insight to optimize next week
   - Include a "signal freshness" metric: % of signals actioned within their optimal time window (before they go cold)

Output: Complete measurement framework, attribution methodology, rep performance scorecard, scoring model validation process, and weekly reporting template — ready to implement in your CRM and BI tool.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Analytics and GTM intelligence specialist with 15+ years of experience building attribution frameworks for signal-based sales and marketing motions at B2B SaaS companies. You specialize in measuring activities that don't leave clean digital footprints — dark social, community selling, LinkedIn outreach, voice prospecting — and proving their revenue contribution to skeptical CFOs and CROs. You understand that in 2026, the majority of B2B buying influence happens in channels that traditional UTM-based attribution can't capture.

COMPANY CONTEXT:
- Product: [PRODUCT NAME] — [1-sentence description]
- ICP: [TARGET JOB TITLES] at [COMPANY SIZE] [INDUSTRY] companies
- ACV: [$X] | Sales cycle: [X days] | Team: [X SDRs + X AEs]
- Social selling tools in stack: [Clay, LinkedIn Sales Nav, Bombora, etc.]
- CRM: [Salesforce/HubSpot/other] | BI tool: [Tableau/Looker/other]
- Current measurement gaps: [Describe what you can't currently measure — e.g., "no way to track which LinkedIn comments influenced deals"]
- Signal types being tracked: [Job changes, funding rounds, hiring signals, competitive churn, tech stack changes]
- Monthly signal volume: [Approx. # signals detected per month]
- Reps running this motion: [# reps, current tools they use]

OBJECTIVE: Build a comprehensive analytics and attribution system that:
1. Quantifies revenue contribution of every trigger-event type and social selling activity
2. Creates defensible dark social attribution methodology that earns CFO trust
3. Identifies which signals and rep behaviors actually produce pipeline and revenue
4. Validates and continuously improves signal scoring model accuracy
5. Produces an executive-ready weekly social selling performance report

---

DELIVERABLE 1 — SIGNAL-TO-REVENUE FUNNEL ANALYTICS:

Build a complete conversion funnel for each trigger event type with these stages and definitions:

Stage 1 — Signal Detection:
- Definition: A qualifying trigger event is identified for an ICP account in our database
- Measurement: Count of signals fired per week/month by trigger type
- Data source: [Clay webhook, Bombora API, LinkedIn alerts, Crunchbase feed]
- SLA: Signal must be acted on within [X hours/days] of detection

Stage 2 — Signal Enrichment & Scoring:
- Definition: Signal is enriched with firmographic + contact data and scored 0-100
- Measurement: % of signals that score 40+ (actionable threshold), average enrichment completeness score
- Data source: Clay enrichment output → CRM custom field
- Quality metric: Enrichment rate (% of signals with complete contact + firmographic data)

Stage 3 — Sequence Activation:
- Definition: Personalized outreach sequence launched for signal within SLA window
- Measurement: Signal-to-sequence rate (target: >85% of 60+ scored signals)
- Time-to-act metric: Median hours from signal detection to first touch by trigger type
- Leakage analysis: Categorize why signals go unactioned (rep capacity, scoring too low, already in pipeline, no contact found)

Stage 4 — Engagement & Reply:
- Definition: Prospect responds to any touch in the signal-triggered sequence (email reply, LinkedIn message reply, voicemail callback, connection acceptance + message)
- Measurement: Reply rate by trigger type, touch type (email vs. LinkedIn DM vs. InMail vs. cold call), and rep
- Quality signal: % of replies that are positive (interested/curious/referred) vs. negative (unsubscribe/not interested)
- Benchmark: Signal-triggered sequences should outperform cold outreach reply rates by 2-3x minimum

Stage 5 — Meeting Booked:
- Definition: Qualified discovery call or demo scheduled
- Measurement: Signal-to-meeting rate by trigger type; meeting-show rate for signal-sourced meetings vs. non-signal-sourced
- Meeting quality metric: % of meetings that advance to Stage 2 in CRM (qualification passed)
- Insight: Which trigger types produce meetings that actually convert vs. "curiosity meetings"?

Stage 6 — Opportunity Created:
- Definition: CRM opportunity created with signal source tagged
- Measurement: Signal-to-opportunity rate; average days from signal detection to opportunity creation
- Pipeline quality: Average stage-weighted pipeline value per signal type
- Attribution tag: Opportunity record must include [trigger_type], [signal_source_tool], [signal_date], [signal_to_opp_days]

Stage 7 — Closed Won:
- Definition: Deal closed with signal-attribution credited
- Measurement: Signal-to-closed-won rate; average deal size by trigger type; sales cycle length for signal-sourced vs. non-signal-sourced deals
- Revenue attribution: Assign full or partial revenue credit to signal type using your chosen attribution model (first touch, last touch, or 40-20-40 custom model)
- ROI calculation: Revenue attributed to signal type ÷ cost of signal detection tools + rep time investment

---

DELIVERABLE 2 — DARK SOCIAL ATTRIBUTION METHODOLOGY:

Social selling activities that resist UTM tracking require an alternative attribution framework. Design a multi-method dark social attribution system:

Method A — Self-Reported Attribution at Deal Entry:
- Add a required CRM field: "How did this prospect first engage with us?" with options: [LinkedIn post, LinkedIn comment, LinkedIn DM, InMail, Community post (Slack/Reddit/Circle), LinkedIn connection request, Peer referral, Other social/digital]
- Make this field required at opportunity creation; build a CRM workflow that prompts the AE to update it after discovery call
- Tracking rate target: >70% of opportunities have valid self-reported attribution

Method B — Social Proximity Score:
- For every closed-won deal, calculate "social proximity" in the 90 days before opportunity creation:
  * Rep posted LinkedIn content seen by the prospect's company (track via LinkedIn analytics export)
  * Rep commented on a post by or related to the prospect
  * Rep was mentioned or tagged by someone in prospect's network
  * Prospect liked, shared, or commented on rep's content
  * Prospect joined or engaged in a community where the rep is active
- Score: 0 = no social proximity, 1-2 = low, 3-5 = medium, 6+ = high
- Hypothesis to test: Do high-proximity deals close faster and at higher ACV than zero-proximity deals?

Method C — Content Influence Attribution:
- If you publish original content (LinkedIn articles, posts, newsletters, video), track which prospects in your pipeline engaged with it before the deal opened
- Use LinkedIn newsletter subscriber lists, post engagement exports, and video view data to cross-reference against open opportunities
- Tag opportunities with: [content_influenced: yes/no] + [content_type] + [days_before_opp_open]
- Benchmark: % of closed-won deals where prospect engaged with content in 60 days before opportunity

Method D — Community Signal Attribution:
- For dark social channels (Slack communities, Discord, Reddit, Quorum, peer review sites), track:
  * Prospects who mentioned your product/company in a community
  * Prospects who asked peers about you or your competitors
  * Prospects who engaged with your brand ambassador/employee in a community
- Use Mention.com, Brandwatch, or manual monitoring; log relevant mentions in CRM as "community signal" activities
- Attribution: If a community signal precedes an inbound lead or outbound sequence within 14 days, tag as community-influenced

---

DELIVERABLE 3 — REP PERFORMANCE ANALYTICS & COACHING FRAMEWORK:

Build individual rep dashboards with these metrics tracked weekly:

Activity Metrics (leading indicators):
- Signals actioned per week (target: >X based on team capacity)
- Time-to-first-touch after signal detection (target: <[X hours])
- Personalization score: measure by having manager rate 5 random outreach messages per rep per month on a 1-5 rubric (generic = 1, highly personalized to trigger = 5)
- LinkedIn post frequency (target: [X posts/week]) + engagement rate (likes + comments / impressions)
- Connection acceptance rate for cold LinkedIn outreach
- LinkedIn Social Selling Index (SSI) score: pull from LinkedIn Sales Navigator weekly

Conversion Metrics (lagging indicators):
- Signal-to-reply rate by rep (vs. team average)
- Reply-to-meeting rate by rep
- Meeting-to-opportunity rate by rep
- Pipeline sourced from signal-based social selling per rep per quarter
- Signal-sourced closed-won revenue per rep per quarter

Rep Archetype Analysis:
- "High Volume / Low Personalization": Many signals actioned, low reply rates → coaching on message quality, trigger-contextualization, and value-leading openers
- "Low Volume / High Conversion": Few signals actioned but high close rates → coaching on scale and time management; replicate their playbook
- "Activity-Rich / Pipeline-Poor": High posting, commenting, connecting but low pipeline → coaching on turning social engagement into direct outreach
- "Silent Seller": Low social activity but somehow still closes signal-sourced deals → investigate if they're doing offline community selling or peer referrals that aren't being tracked

---

DELIVERABLE 4 — SIGNAL SCORING MODEL VALIDATION & OPTIMIZATION:

Run this analysis quarterly to prevent scoring model decay:

Step 1 — Backtest Performance by Score Band:
- Pull all signals from last 90 days, group by score band: <40, 40-59, 60-79, 80+
- Calculate actual closed-won rate, average deal size, and average sales cycle for each band
- Expected result: 80+ scored signals should produce 3-5x higher conversion than <40 scored signals
- If the gap is smaller than 2x, the model needs recalibration

Step 2 — Feature Importance Analysis:
- Examine each scoring factor's actual predictive power vs. assigned weight:
  * Trigger event type (current weight: 40%) — does funding really predict purchase readiness better than job change?
  * Contact seniority (current weight: 25%) — does VP always outperform Director in your segment?
  * ICP firmographic fit (current weight: 20%) — which firmographic factors matter most (ARR, tech stack, headcount, geography)?
  * Signal recency (current weight: 15%) — what's the actual decay curve for signal freshness?
- Recommendation: Run a logistic regression on 90-day signal dataset using closed-won as dependent variable; let data dictate new weights

Step 3 — Signal Stacking Analysis:
- Hypothesis: Accounts that fire 2+ signals in 30 days should convert at materially higher rates
- Test: Pull accounts that fired multiple signals vs. single signals; compare conversion rates and deal sizes
- If stacking adds predictive value, create a "signal stacking" multiplier in your scoring model (+10 points per additional signal within 30 days, up to a maximum)

Step 4 — New Signal Type Discovery:
- Quarterly review of what trigger events preceded 80%+ of your closed-won deals that weren't in your original taxonomy
- Common discoveries: regulatory change announcements, competitor leadership departures, company rebrand/pivot, industry award wins, large-scale RIF (reduction in force)
- Add validated new trigger types to your library and test with a 60-day pilot

Step 5 — Time-to-Act Optimization:
- Analyze conversion rate vs. time elapsed between signal detection and first touch
- Hypothesis: Earlier outreach = higher conversion (but at some point quality suffers)
- Find your optimal time-to-act window per trigger type; set SLA alerts for any signal that approaches the decay threshold

---

DELIVERABLE 5 — EXECUTIVE-READY REPORTING FRAMEWORK:

Weekly Social Selling Intelligence Brief (1-page format):

SECTION 1: Signal Pipeline Health
- Signals detected this week: [#] | Signals actioned within SLA: [#] ([%])
- Top signal type by volume this week: [Type] | Top signal type by conversion: [Type]
- Pipeline added from signal-sourced opportunities: [$X] | vs. last week: [+/-X%]
- At-risk signals: [# of 60+ scored signals not actioned within SLA] — requires manager attention

SECTION 2: Social Selling Activity Summary
- LinkedIn posts published by team this week: [#] | Average engagement rate: [%]
- LinkedIn connections sent: [#] | Acceptance rate: [%]
- DMs/InMails sent: [#] | Reply rate: [%]
- Comments on prospect content: [#] | Follow-on conversations started: [#]
- Self-reported dark social attribution this week: [# opportunities tagged with social source]

SECTION 3: Rep Leaderboard
| Rep | Signals Actioned | Signal→Reply % | Meetings Booked | Pipeline Added |
|-----|-----------------|---------------|----------------|---------------|
| [Name] | [#] | [%] | [#] | [$X] |
(Highlight top performer and rep most improved week-over-week)

SECTION 4: One Optimization Insight
- This week's finding: [e.g., "Series B funding signals are converting at 3x the rate of hiring signals but we're spending 60% of SDR time on hiring signals — recommend rebalancing signal prioritization"]
- Action: [Specific change to make next week]

Quarterly Board-Level Social Selling ROI Summary:
- Total signal-sourced pipeline generated: [$X] | % of total pipeline: [%]
- Total signal-sourced closed-won revenue: [$X] | % of total revenue: [%]
- Average social-selling-influenced deal size vs. non-influenced: [$X vs. $Y] ([%] premium)
- Average sales cycle for signal-sourced deals vs. non-sourced: [X days vs. Y days]
- Social selling tool investment: [$X/quarter] | Revenue attributed: [$Y] | ROI: [X:1]
- Top 3 insight from signal scoring model backtest: [Insights]

## Example Input/Output

**Input Example:**

Company: Velocity RevOps — an AI-powered revenue operations platform. Sells to VP of Revenue Operations and CRO at Series B-D B2B SaaS companies with 50-500 employees. ACV: $85K. 6 SDRs running signal-based social selling using Clay, LinkedIn Sales Nav, Bombora. CRM: Salesforce. BI: Tableau. Monthly signal volume: ~400 signals detected. Three trigger types: job change (new VP RevOps or CRO hired), funding round (Series B/C), and hiring surge (5+ RevOps/sales ops roles posted in 30 days).

**Output Example (Signal Performance Scorecard):**

Signal Type Analysis — Last 90 Days (Velocity RevOps):

| Signal Type | Detected | Actioned (SLA %) | Reply Rate | Meeting Rate | Opp Rate | Avg Deal Size | Signal ROI |
|-------------|----------|-----------------|------------|--------------|----------|---------------|-----------|
| New VP RevOps/CRO hired | 186 | 91% | 18.3% | 8.1% | 4.3% | $92K | 4.2x |
| Series B/C funding | 98 | 78% | 11.2% | 4.6% | 2.1% | $107K | 2.4x |
| Hiring surge (5+ RevOps) | 127 | 83% | 9.7% | 3.9% | 1.6% | $79K | 1.8x |

Key Findings:
- Job-change signals are outperforming funding signals by 1.7x on pipeline-per-signal — recommend increasing job-change detection coverage from LinkedIn + Crunchbase to also include Korn Ferry, HiQ, and company career page monitoring
- Funding signals have 78% SLA adherence (lowest of 3 types) and 13% lower deal size — investigate if VCs are inserting signals that don't match actual buyer readiness; consider raising the score threshold for funding signals from 60 to 70
- Hiring-surge signals at 83% SLA but lowest ROI — consider automating first touch for this trigger type to reduce rep time investment while maintaining coverage
- 22 accounts fired 2+ signals in 30 days (funding + hiring, job change + hiring); these accounts converted at 3.2x the rate of single-signal accounts — implement "signal stacking" scoring multiplier immediately

Dark Social Attribution — Q3 Findings:
- 34% of closed-won deals (22/65) self-reported first contact via LinkedIn (DM: 14, comment: 5, post: 3)
- Social proximity score analysis: deals with 4+ social touches pre-opportunity close 18% faster and at $14K higher ACV than zero-proximity deals
- 6 deals traced to community activity: 4 from RevOps Co-op Slack, 2 from Pavilion

## Success Metrics

- Signal scoring model backtest: 80+ scored signals convert at 3x+ the rate of <40 scored signals
- Signal-to-opportunity rate exceeds 3% for top-performing trigger types
- Dark social attribution: >60% of opportunities have a valid social source tag in CRM
- Social selling ROI is reportable at board level with documented methodology
- Rep leaderboard SSI correlation: highest SSI reps source >2x pipeline vs. lowest SSI reps
- Signal stacking analysis confirms multiplier effect: accounts with 2+ signals in 30 days convert at 2x+ rate

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Social-Selling/AI-Powered-B2B-SaaS-Trigger-Event-Signal-Based-Social-Selling-&-Buyer-Intent-Pipeline-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Social-Selling/AI-Powered-B2B-SaaS-Dark-Social-Community-Selling-&-Off-LinkedIn-Pipeline-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Dark-Funnel-Attribution-&-Anonymous-Buyer-Intent-Intelligence-Engine.md`

## Integration Tips

**Salesforce / HubSpot:**
- Create custom fields: `signal_type`, `signal_detected_date`, `signal_score`, `signal_source_tool`, `signal_to_opp_days`, `social_proximity_score`, `dark_social_source`
- Build a validation rule requiring `signal_type` and `dark_social_source` to be populated before an opportunity advances past Stage 1
- Create a Salesforce report: "Signal-Sourced Pipeline" filtered by `signal_type IS NOT NULL` — segment by signal type, rep, quarter

**Clay:**
- Use Clay's webhook → Salesforce integration to automatically write signal data into CRM when a Clay waterfall completes
- Build a Clay table tracking "Signal Aging" — flag any signal that's been in the system for >72 hours without a sequence launched

**LinkedIn Sales Navigator:**
- Export weekly SSI scores via LinkedIn Sales Navigator Analytics; load into your BI tool to track SSI trend per rep
- Use TeamLink to identify warm paths to signal contacts through existing connections; log these in CRM as "warm intro source"

**Tableau / Looker:**
- Build a "Signal Funnel" dashboard with stage conversion rates by trigger type, drillable to rep level
- Create a "Dark Social Attribution" bar chart comparing self-reported sources vs. UTM-tracked sources quarter-over-quarter

**Zapier / Make (Automation):**
- Set up a weekly Zap: pull Clay signal aging report → if signal older than 72 hours + score >60 + not sequenced → send Slack alert to rep manager
- Automate weekly SSI score ingestion from LinkedIn → append to rep performance table in Google Sheets or BQ

## Troubleshooting

**Problem:** Dark social attribution data is too sparse — less than 30% of opportunities have a social source tag.
**Solution:** Add the attribution question as a mandatory discovery call prep field in your CRM, not at opportunity creation. Brief SDRs and AEs to ask "Before I dive in — I noticed you [connected with us on LinkedIn / saw a post from someone on our team]. Was that actually how you first heard about us?" and log the response immediately after the call.

**Problem:** Signal scoring backtest shows no meaningful conversion difference between score bands — the model appears random.
**Solution:** Your scoring factors may not reflect actual purchase intent for your ICP. Run a cohort analysis on closed-won deals from the last 12 months: what did they have in common at the time of first touch? Rebuild the scoring model bottom-up from actual predictive features rather than assumed ones. Common fix: job change signals are almost always more predictive than funding signals for mid-market SaaS — if funding is weighted too heavily, recalibrate to 20% funding / 50% job change / 30% firmographic.

**Problem:** Reps are gaming the signal leaderboard by actioning low-scored signals to inflate their "signals actioned" count.
**Solution:** Replace raw "signals actioned" with a quality-weighted metric: (signals actioned × average signal score) / (signals detected in rep's territory). This penalizes reps who cherry-pick easy but low-value signals and rewards those who prioritize and act on high-intent accounts.

## Version History
- v1.0: Initial creation (auto-generated)
