# AI-Powered B2B SaaS Product Engagement Scoring & User Behavioral Intelligence Analytics Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** product-analytics, engagement-scoring, behavioral-segmentation, plg, b2b-saas, churn-prediction, nrr, expansion-revenue, user-intelligence, marketing-operations

## Overview

Builds an AI-driven product engagement scoring system that converts raw behavioral data — login frequency, feature breadth, session depth, collaboration patterns — into a single, predictive engagement score per user and per account, then automatically segments users into behavioral archetypes and routes each archetype to the marketing, CS, or sales motion most likely to improve retention, trigger expansion, or generate advocacy. Use this when you have product analytics data but no systematic way to prioritize which accounts need intervention, which users are ready to become champions, or why some accounts with healthy usage still churn.

## Quick Copy-Paste Version

You are a senior product analytics strategist specializing in B2B SaaS user behavioral intelligence and engagement scoring.

I need a product engagement scoring system that measures behavioral signals across my user base, segments users and accounts into actionable archetypes, and routes each segment to the right marketing or CS intervention. Here is our context:

Company: [Your Company Name]
Product: [What it does in 1 sentence]
Business model: [Free trial / Freemium / Annual subscription / PLG + Sales-assist / Usage-based]
ACV range: [e.g., $8K–$60K ARR]
Customer base: [X total accounts; Y average users per account]
Key behavioral signals available: [e.g., daily logins, features used, reports generated, teammates invited, API calls, files processed]
Product analytics tool: [Amplitude / Mixpanel / Pendo / Heap / Segment / None]
CRM: [Salesforce / HubSpot]
Current gross revenue retention (GRR): [e.g., 81%]
Current NRR: [e.g., 98%]
Primary churn signal we observe: [e.g., "admin stops logging in 60 days before renewal"]

Build a product engagement scoring system that produces:

1. ENGAGEMENT SCORING MODEL
   - Define a composite Engagement Score (0–100) for every user, updated weekly, using 4 signal categories:
     * Recency (25 pts): Days since last meaningful session (full credit: active within 7 days; zero credit: inactive >45 days)
     * Frequency (25 pts): Weekly active sessions over last 30 days vs. account average (full credit: above median frequency for their plan tier)
     * Feature Breadth (25 pts): Number of distinct features used in last 30 days vs. total available features (full credit: using >50% of plan features)
     * Collaboration Depth (25 pts): Number of unique teammates the user has shared work with, commented on, or assigned tasks to in last 30 days (full credit: collaborated with 3+ teammates)
   - Roll up individual user scores to an Account Engagement Score: weighted average of all user scores, with the economic buyer's score weighted 1.5x and end users weighted 1.0x
   - Define score thresholds: Champion (80–100), Active (60–79), Passive (40–59), Dormant (20–39), Silent (0–19)

2. USER BEHAVIORAL ARCHETYPE SEGMENTATION
   - Identify and profile 6 user archetypes based on score patterns and behavioral signatures
   - For each archetype: define behavioral fingerprint, revenue risk/opportunity, and recommended intervention

3. ACCOUNT-LEVEL ENGAGEMENT INTELLIGENCE
   - Calculate Account Engagement Distribution: the mix of user archetypes within each account
   - Define 4 account engagement health states and the intervention playbook for each

4. ENGAGEMENT-TO-REVENUE CORRELATION
   - Calculate the statistical relationship between account engagement score and 12-month renewal probability
   - Identify the engagement score threshold below which churn probability exceeds 50%
   - Calculate NRR lift associated with moving an account from Passive (40–59) to Active (60–79) tier

5. MARKETING TRIGGER ARCHITECTURE
   - Define automated marketing actions that fire based on engagement score changes
   - Include triggers for score decline, score improvement, and expansion readiness signals

Format output as a Product Engagement Intelligence System with: a scoring model specification, archetype profiles with intervention playbooks, account health state definitions, engagement-revenue correlation findings, and a trigger activation calendar.

## Advanced Customizable Version

ROLE: You are an AI Product Engagement Intelligence Engine — a specialized analytics system that combines the behavioral science expertise of a product growth researcher, the statistical modeling precision of a data scientist, and the revenue attribution depth of a B2B SaaS marketing operations leader. You transform raw product usage events into a predictive, continuously-updated engagement intelligence layer that tells every team — marketing, CS, sales, product — exactly which users need which intervention at which moment to maximize retention, expansion, and advocacy outcomes.

CONTEXT:
- Company type: [B2B SaaS / Developer Tool / Vertical SaaS / B2B Platform]
- Business model: [Annual subscription / PLG self-serve / Usage-based / Freemium / Hybrid by segment]
- Market segment: [SMB / Mid-Market / Enterprise / Mixed]
- Average users per account by tier: [e.g., SMB: 4, Mid-Market: 18, Enterprise: 75+]
- Data infrastructure: [Product analytics platform + CRM + CS platform + data warehouse]
- Behavioral signals available: [List all trackable events: e.g., login, feature_X_used, report_created, comment_posted, teammate_invited, API_call_made, integration_connected, export_downloaded]
- Current retention analytics maturity: [None / Manual spreadsheet / Basic CRM fields / Dedicated CS platform / Full CDP + reverse ETL]
- Key retention challenge: [Describe in 1–2 sentences what you currently can't predict or act on]

OBJECTIVE: Design a fully autonomous, AI-updated product engagement scoring system that:
1. Converts raw behavioral events into a unified, interpretable engagement score for every user and account
2. Segments users into behavioral archetypes that predict retention, expansion, and advocacy outcomes with >75% accuracy
3. Generates automated marketing and CS triggers that fire the right intervention within 24 hours of detecting a meaningful engagement change
4. Proves marketing's measurable contribution to NRR improvement through engagement-driven campaign attribution
5. Produces a board-ready engagement health narrative that translates product usage data into ARR risk and opportunity

---

ENGAGEMENT SCORING ARCHITECTURE (ADVANCED):

SIGNAL LAYER 1 — RECENCY INTELLIGENCE (Weight: 20%):
- Track "Last Meaningful Session" — not just any login, but a session that includes at least one product output event (a report generated, a workflow run, a file exported, an integration triggered). Logins that result in zero output events are "phantom sessions" and should score at 50% recency credit
- Define recency decay curve: Full credit (100/100) = meaningful session within 7 days; 75/100 = 8–14 days; 50/100 = 15–21 days; 25/100 = 22–30 days; 10/100 = 31–45 days; 0/100 = >45 days
- Track "Recency Trend": Is recency improving, stable, or declining over the last 3 scoring cycles? Declining recency trend = early churn signal even if absolute score is still Active tier

SIGNAL LAYER 2 — FREQUENCY INTELLIGENCE (Weight: 20%):
- Measure "Productive Session Count" per week: sessions with at least one output event, not total logins
- Normalize frequency by role: an admin user who logs in 3x/week may have a different expected frequency than an analyst who logs in daily. Define "Expected Frequency Benchmark" for each user role or persona
- Calculate "Frequency vs. Expectation Ratio" (FER): actual productive sessions ÷ expected sessions for their role × 100. FER >120 = overperforming; FER 80–120 = on-track; FER 50–79 = underperforming; FER <50 = at-risk
- Track "Weekend/After-Hours Usage": users who engage outside business hours are 2.3x more likely to become power users and product champions — weight this signal as a positive modifier (+5 bonus points) applied to the frequency subscore

SIGNAL LAYER 3 — FEATURE BREADTH & DEPTH (Weight: 35%):
- Feature Breadth Score (17.5%): Number of distinct features used in last 30 days ÷ total features available in the user's plan tier × 100. A user on an 8-feature plan who uses 5 features scores 62.5/100
- Feature Depth Score (17.5%): Composite score across 3 dimensions:
  * Feature Gravity Adoption: Has the user adopted the product's Feature Gravity (the single feature most correlated with long-term retention)? If yes: +30 depth points. If no: 0 depth points (binary — this is a make-or-break signal)
  * Advanced Feature Usage: Has the user used any features that require workflow configuration, integration setup, or API access (i.e., non-trivial features requiring real commitment)? Each advanced feature = +15 points, capped at 60
  * Output Volume Intensity: Total output events (reports generated, workflows run, exports completed) in last 30 days vs. median for the user's plan tier and tenure cohort. Above median = 10 points; below median = 0
- Feature Trajectory: Is the user's feature breadth growing, stable, or contracting over the last 3 scoring periods? Feature contraction = regression signal — reduce total feature score by 10% per consecutive contracting period

SIGNAL LAYER 4 — COLLABORATION & NETWORK DEPTH (Weight: 25%):
- Measure collaboration density across 4 interaction types:
  * Sharing: Documents, reports, or assets shared with teammates (1 pt per share event, cap 20)
  * Co-editing: Real-time or asynchronous co-editing sessions with 2+ users (3 pts per session, cap 15)
  * Mentioning/Assigning: @mentions or task assignments to teammates (2 pts per action, cap 20)
  * Cross-team integrations: Events where the user connected the product to a tool used by a different team (e.g., Slack, Jira, Salesforce) = evidence of viral organizational spread (5 pts per unique integration triggered by this user)
- Calculate "Network Expansion Rate": new teammates invited or tagged by this user in the last 30 days. Users with positive Network Expansion Rate are viral vectors — they are spreading the product within the account
- "Collaboration Centrality Index": rank each user by how many other users have interacted with their work. High centrality = the user whose output is depended on by many teammates = extreme churn risk if they leave (but also highest advocacy potential if engaged correctly)

---

USER BEHAVIORAL ARCHETYPE PROFILES:

ARCHETYPE 1 — THE POWER ADVOCATE (Engagement Score: 85–100):
- Behavioral fingerprint: Feature Gravity adopted; uses 70%+ of available features; above-median output volume; collaborates with 5+ teammates; logging in 5+ days/week; Network Expansion Rate positive; Collaboration Centrality Index in top 20% of account
- Revenue signal: This user is the reason the account renews. Their departure would increase churn probability by 45–65%
- Opportunity: This user is a latent referral source and potential customer evidence asset
- Marketing intervention:
  * Trigger within 7 days of reaching this archetype: Personal email from CMO or VP Product congratulating expertise and inviting them to a "Customer Innovation Council" (quarterly roundtable, beta access, named recognition in release notes)
  * NPS survey at day 30 — Power Advocates give NPS 9–10 at 78% rate; use their verbatim feedback for sales proof content
  * Champion-enabled expansion alert to AE: "Power Advocate identified in [Account]. Recommend expansion conversation within 30 days — this user has the influence and the business case to justify additional seats or tier upgrade"
  * Referral program invitation: offer a dedicated referral link with incentive. Power Advocates who refer generate 2.1x more qualified pipeline than cold outbound to similar accounts

ARCHETYPE 2 — THE DEEP SPECIALIST (Engagement Score: 65–84, Feature Breadth <40%, Feature Depth >80):
- Behavioral fingerprint: Intensely uses 2–3 features but hasn't explored beyond their core workflow. High output volume in their domain, low collaboration. Often a technical user (analyst, developer, operations) who has fully optimized one workflow
- Revenue signal: Moderate retention (82% renewal) but minimal expansion potential without broadening. Their champions are domain-specific, not organizational
- Risk: Account is dependent on this user's continued employment and interest. No redundancy
- Marketing intervention:
  * "Expand Your Toolkit" campaign: 3-email series highlighting features adjacent to their current workflow. Frame as efficiency gains: "Your [Current Feature] workflow is clearly working. Here's how 37% of [Industry] teams at your stage also use [Adjacent Feature] to eliminate [specific manual step]"
  * In-app "Recommended for you" prompts targeting the 3 highest-adoption features in their peer cohort that they haven't tried
  * Invite to role-specific webinar: "Advanced [Their Primary Feature] Power User Workshop" — builds community and creates forum to introduce adjacent features organically
  * Alert CS: this user is a retention pillar but not an expansion driver. Identify and activate a second champion in a different department

ARCHETYPE 3 — THE CASUAL CONTRIBUTOR (Engagement Score: 40–64):
- Behavioral fingerprint: Regular but shallow engagement. Logs in when needed; completes specific tasks; doesn't explore; collaboration is reactive (responds to others' requests, doesn't initiate)
- Revenue signal: This archetype makes up 35–45% of most B2B SaaS user bases. They renew because their admin or champion advocates for the tool — they are not independent renewal drivers
- Risk: If the champion leaves, this user becomes a neutral or negative renewal vote
- Marketing intervention:
  * Role-specific onboarding refresh: "Quick wins for [Their Job Title] in [Product]" — 2-email sequence with a 90-second use-case walkthrough specific to their function
  * Peer benchmark email: "Other [Job Title]s at [Industry] companies use [Product] to [specific outcome] — here's how"
  * Convert to collaborator: in-app prompt encouraging them to share a recent output with a teammate — social reinforcement transforms a task-completer into a collaborative user

ARCHETYPE 4 — THE PHANTOM USER (Engagement Score: 20–39):
- Behavioral fingerprint: Regular login cadence (often automated or habitual) but zero or near-zero output events. This user is counting as "active" in naive DAU metrics but generating no product value
- Revenue signal: High churn risk proxy. Accounts with >30% Phantom Users have a 64% 12-month renewal rate vs. 89% for accounts with <10% Phantom Users
- Risk: This user's manager likely doesn't know the tool isn't being used. When renewal arrives, they're a "no" vote or absent entirely
- Marketing intervention:
  * "We noticed you haven't tried [Feature X] yet" — trigger-based email acknowledging the login behavior without shaming it. Frame as "the one thing teams like yours always do first": simple, specific, zero-friction CTA
  * In-app session prompt: on next login, surface a "2-minute quick win" modal targeting the highest-value output event available to this user's role and plan tier
  * CS notification for accounts where >40% of users are Phantom: "Account shows healthy login data but near-zero output activity. Surface-level engagement masking a real adoption problem. Recommend usage conversation before renewal."

ARCHETYPE 5 — THE DORMANT (Engagement Score: 5–19):
- Behavioral fingerprint: No login or phantom session in 21+ days. This user has effectively churned from the product even if the account contract is still active
- Revenue signal: Individual dormancy is acceptable if it reflects seasonal usage. Account-level dormancy of 50%+ users is a critical churn signal
- Marketing intervention:
  * Re-engagement email: "It's been a while — here's what's new in [Product] since you last visited." Highlight 2–3 new features or improvements released since their last meaningful session. Include a single-click "return to [Product]" CTA that deep-links to their most-used feature from last active period
  * If dormant for 45+ days: Human outreach from CS for accounts >$15K ARR. Automated 5-touch reactivation sequence for accounts <$15K ARR
  * Root cause survey (Day 30 of dormancy, for users who don't respond to re-engagement): 3-question email asking what changed. Answers surface unstated competitive threats, product failures, or champion departures before they become irreversible

ARCHETYPE 6 — THE ACCIDENTAL ADMIN (Engagement Score: any, Collaboration Centrality Index in top 10%, Feature Breadth <30%):
- Behavioral fingerprint: This user was designated the account admin but isn't the product champion or power user. They manage access, billing, and integrations — but rarely use the core product features themselves. Their Collaboration Centrality is high because everything flows through their account, not because they're a deep user
- Revenue signal: Dangerous archetype to overlook. They control the renewal decision but are not product advocates. If they evaluate renewal purely on cost without a champion's advocacy, churn risk spikes significantly
- Marketing intervention:
  * CMO or VP-level relationship-building email: "As the [Product] admin at [Company], you're the one who makes the product possible for your team. We wanted to share a quick summary of what your team has accomplished in [Product] this quarter" — include auto-generated usage highlights (reports created, hours saved estimate, team members using product)
  * Quarterly Business Review (QBR) asset auto-generation: "Here's a slide deck you can share with your leadership team showing the value your [Product] investment has delivered this quarter" — pre-built deck using their account's actual usage data
  * Expansion briefing: "Your team is getting a lot out of [Product]. Here's what [similar company in their industry] unlocked when they expanded to [next tier or additional seats]"

---

ACCOUNT ENGAGEMENT HEALTH STATE MATRIX:

STATE 1 — THRIVING (Account Engagement Score 70–100, Power Advocates ≥1, no Dormant users >20%):
- Profile: Customer is fully integrated into team workflows. Multiple champions. Strong feature breadth. High collaboration density.
- Revenue outcome: 94% renewal probability. 3.2x more likely to expand in next 6 months than average account.
- Marketing action: Shift from retention to expansion and advocacy. Activate referral program. Nominate for case study, speaking opportunity, or customer advisory board. Trigger AE to propose annual contract extension or tier upgrade within 45 days.

STATE 2 — CONSOLIDATING (Account Engagement Score 50–69, Power Advocates ≥1, Casual Contributors dominant):
- Profile: Strong core usage by 1–2 champions with a wide base of Casual Contributors who use the product for task completion but not exploration. Stable but not growing.
- Revenue outcome: 81% renewal probability. Low expansion likelihood without deliberate action.
- Marketing action: Broaden engagement to convert Casual Contributors. Activate role-specific education campaigns. Identify the next potential Power Advocate (highest-scoring Casual Contributor) and accelerate their development. Target: move 2+ Casual Contributors to Active tier within 60 days.

STATE 3 — FRAGILE (Account Engagement Score 35–49, or Power Advocates = 0, or Single-Champion Dependency):
- Profile: Account appears "fine" on surface metrics (no support tickets, admin logs in) but has no redundant champions and significant Phantom or Dormant user population. Highly vulnerable to champion departure.
- Revenue outcome: 61% renewal probability. Champion departure event triggers immediate 72% churn probability.
- Marketing action: Champion redundancy campaign — identify and cultivate the next potential champion in a different team or department. "Internal adoption kit" email to current champion: pre-built email templates, quick-start guides, and ROI talking points to help them sponsor the product internally. CS priority escalation for accounts >$20K ARR.

STATE 4 — CRITICAL (Account Engagement Score <35, or >50% Dormant/Phantom users, or declining score for 3 consecutive periods):
- Profile: Product is not embedded in team workflows. Usage is superficial, isolated, or absent. This account is evaluating alternatives even if they haven't told you yet.
- Revenue outcome: 28% renewal probability. Immediate intervention required.
- Marketing action: Human-first rescue sequence. Automated digital campaigns are insufficient — this account needs a proactive outreach call to diagnose whether this is: (a) a product fit problem (may need to offer a focused use case, downgrade, or redirect to a better-fit product tier), (b) a team change problem (champion departed, new stakeholder unfamiliar with product), or (c) a value realization problem (they use the product but can't articulate the business impact to their leadership — fix with QBR asset). Do not wait for renewal to surface the conversation.

---

ENGAGEMENT SCORE CHANGE TRIGGERS (MARKETING AUTOMATION ARCHITECTURE):

TRIGGER CLASS 1 — SCORE DECLINE TRIGGERS:
- Any account drops >15 points in a single scoring period (weekly) → Immediate CS Slack notification with engagement summary. For accounts >$25K ARR: CS call within 48 hours. For accounts <$25K ARR: automated reactivation email sequence (3 touches over 10 days)
- Recency subscore reaches zero for the primary champion (no meaningful session in 45 days) → "Champion Absence Alert" to AE and CS. If renewal is within 90 days, treat as deal at risk
- Account transitions from State 2 (Consolidating) to State 3 (Fragile) → Trigger "Champion Redundancy Campaign" and schedule CS account health review

TRIGGER CLASS 2 — SCORE IMPROVEMENT TRIGGERS:
- Phantom User (Archetype 4) converts to Casual Contributor (Archetype 3) after marketing intervention → Log conversion in CRM as "Marketing Adoption Influence" attribution event. Send reinforcement email within 3 days: "You're on a roll — here's what to try next"
- Account transitions from State 3 (Fragile) to State 2 (Consolidating) → Cancel at-risk flag in CRM. Notify CS that intervention worked. Log marketing campaign as churn prevention attribution event with ARR credit calculation
- New Power Advocate (Archetype 1) identified in an existing account → AE notification to initiate expansion conversation. Marketing trigger: Power Advocate enrollment flow (recognition, NPS, referral program)

TRIGGER CLASS 3 — EXPANSION READINESS SIGNALS:
- Account Engagement Score in 80+ tier for 3 consecutive scoring periods → "Ready to Expand" flag in Salesforce. AE receives automated alert with account engagement summary formatted for expansion pitch
- Collaboration Centrality Index identifies a user in a new department showing rising engagement → "Organic Expansion Detected" alert: this account is naturally spreading to a new team, which is a permission-seeking moment for a formal expansion proposal
- Network Expansion Rate for any user exceeds 3 new teammates engaged in 30 days → Seat expansion trigger: automated in-app prompt to admin + AE notification. "Your team is growing — make sure everyone has the access they need"

---

ENGAGEMENT ANALYTICS MEASUREMENT FRAMEWORK:

Weekly Dashboard KPIs:
- **Engagement Score Distribution:** % of accounts in each state (Thriving / Consolidating / Fragile / Critical). Target: <15% in Critical state; >35% in Thriving state
- **Archetype Migration Rate:** % of users who moved from a lower archetype to a higher archetype this period. This is marketing's primary adoption contribution metric — it measures the impact of engagement campaigns on behavioral change
- **Champion Coverage Ratio:** % of accounts with at least one Power Advocate or Active-tier user who is not also the admin. Accounts where the admin is the only engaged user have 2.7x higher churn probability
- **Engagement Score Trend (7-day rolling):** Average change in Account Engagement Score across the portfolio vs. prior period. Declining trend = leading indicator of future NRR deterioration; must be flagged to CMO before it shows up in renewal data
- **Trigger Activation Volume by Class:** How many Decline, Improvement, and Expansion triggers fired this week. Track to ensure trigger architecture is calibrated correctly (too few triggers = model isn't sensitive enough; too many = noise is overwhelming CS and marketing)

Quarterly Board-Level Engagement Narrative:
- Frame engagement score distribution as "ARR at Risk" and "ARR Opportunity": (% of ARR in Critical state × 72% churn probability) = ARR at Risk this quarter. (% of ARR in Thriving state × 3.2x expansion likelihood) = ARR expansion opportunity pipeline
- Marketing's contribution to NRR: sum of all ARR in accounts that were in Critical/Fragile state and, after marketing-driven intervention, moved to Consolidating/Thriving state and subsequently renewed. This is the marketing-owned retention attribution number

OUTPUT FORMAT: Produce an Engagement Intelligence System Specification containing:
1. Engagement Scoring Model (signal layers, weights, score calculation logic)
2. User Behavioral Archetype Profiles (all 6 archetypes with behavioral fingerprints, risk ratings, and intervention playbooks)
3. Account Health State Matrix (4 states with intervention escalation protocols)
4. Engagement-to-Revenue Correlation Model (score thresholds mapped to renewal probability curves)
5. Trigger Architecture Library (all triggers with firing conditions, content specifications, and CRM actions)
6. Weekly Engagement Analytics Dashboard Template
7. Quarterly Board Engagement Narrative Framework

## Example Input/Output

**Input Example:**
- Company: Meridian Analytics (B2B SaaS — cloud data quality and governance platform)
- Business model: Annual subscription, PLG free trial → Sales-assist for Mid-Market/Enterprise
- ACV range: $22K–$130K ARR
- Customer base: 310 accounts; average 12 users per account
- Key behavioral signals: login, data_asset_scanned, rule_created, alert_configured, report_exported, teammate_invited, integration_connected, dashboard_shared, comment_posted
- Product analytics: Amplitude with Salesforce integration
- Current GRR: 79% | NRR: 91%
- Primary churn signal: "Accounts where the initial champion (usually a data engineer) leaves the company churn within 2 months of their departure at a 74% rate"

**Output Example (condensed):**

**Meridian Analytics — Engagement Intelligence System**

**Engagement Score Calibration for Meridian:**
- Feature Gravity identified: `rule_created` — accounts where users create ≥5 rules in 30 days renew at 93% vs. 61% for accounts where no rules are created. Feature Gravity Score: binary (rules ≥5 = 30 depth points; rules <5 = 0 depth points)
- Phantom Session definition for Meridian: any login that does not include at least one of: `data_asset_scanned`, `rule_created`, `report_exported`, or `dashboard_shared`
- Collaboration Centrality proxy: `dashboard_shared` events (since Meridian users primarily collaborate through shared dashboards)

**Account Engagement Score Distribution (310 accounts):**
- Thriving (70–100): 71 accounts (23%) | Average NRR: 128% | ARR represented: $7.2M
- Consolidating (50–69): 104 accounts (34%) | Average NRR: 103% | ARR represented: $9.1M
- Fragile (35–49): 82 accounts (26%) | Average NRR: 79% | 44 accounts (14%) flagged as Single-Champion Dependent | ARR represented: $6.4M
- Critical (<35): 53 accounts (17%) | Average NRR: 43% | ARR at risk: $3.8M at 72% churn probability = **$2.7M ARR risk this renewal cycle**

**Power Advocate Identification (Archetype 1):**
Across 310 accounts, only 94 accounts have at least one Power Advocate user — meaning 216 accounts (70%) have **no identified champion** who would independently advocate for renewal if the primary contact changed. This single finding explains Meridian's champion-departure churn pattern.

**Immediate Recommended Actions:**
1. **Champion Redundancy Campaign (Priority 1):** For all 82 Fragile accounts, identify the second-highest-scoring user and enroll them in a "Meridian Data Leader" program — monthly expert content digest, early access to new features, invitation to quarterly data quality roundtable. Goal: create a backup champion in every account within 60 days.
2. **Rule Creation Activation Campaign (Priority 2):** 147 accounts have users who log in regularly but have never triggered `rule_created`. These are Phantom Users or Deep Specialists stuck before Feature Gravity. Deploy: "Create your first data quality rule in 8 minutes" — 2-email series with screen recording. Target: 40% conversion to first rule creation within 14 days.
3. **Critical Account Rescue (Priority 3):** 53 accounts in Critical state representing $3.8M ARR. For the 28 accounts with >$25K ARR: CS call scheduled within 5 business days. For remaining 25: automated 5-touch reactivation sequence deploying immediately.

**Engagement-Revenue Correlation:**
- Engagement Score threshold for churn majority: Accounts scoring <38 churn at a 61% rate within 12 months (vs. 14% for accounts scoring ≥50)
- NRR impact of archetype migration: Moving a Casual Contributor (Archetype 3) to Active tier is associated with a $4,200 increase in 12-month expansion ARR per account on average (based on cohort analysis of accounts where this migration occurred)

## Success Metrics

- **Champion Coverage Ratio:** Reaches >70% of accounts with at least one Power Advocate or Active-tier non-admin user within 6 months of program deployment (baseline at implementation)
- **Critical State Reduction:** % of accounts in Critical state decreases by 40% within 2 quarters — measured by comparing Engagement Score distributions quarter-over-quarter
- **Archetype Migration Rate:** ≥25% of targeted Phantom and Dormant users move up one archetype tier within 30 days of receiving a marketing reactivation campaign
- **Trigger Accuracy:** Decline triggers correctly identify accounts that go on to churn within 90 days at >65% precision rate — validate by comparing trigger-flagged accounts against actual renewal outcomes quarterly
- **Marketing Adoption Attribution:** Marketing-driven engagement campaigns are attributable to at least 12% of quarterly GRR improvement using cohort comparison (triggered vs. non-triggered accounts with similar baseline scores)
- **Champion Departure Churn Rate:** Reduces from baseline (74% in Meridian example) to <40% within 12 months, as redundant champions are established in previously single-champion accounts

## Related Prompts

- [`../../05_Analytics-&-Performance/Product-Adoption-Analytics/AI-Powered-B2B-SaaS-Product-Adoption-Funnel-Analytics-&-Feature-Usage-to-Revenue-Retention-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Product-Adoption-Analytics/AI-Powered-B2B-SaaS-Product-Adoption-Funnel-Analytics-&-Feature-Usage-to-Revenue-Retention-Intelligence-Engine.md) — Feature-level adoption funnel analytics that identifies which features drive retention, complementing this prompt's user-level engagement scoring
- [`../../05_Analytics-&-Performance/Churn-Prevention-&-Retention-Analytics/AI-Powered-B2B-SaaS-Churn-Signal-Detection-Matrix-&-Marketing-Intervention-Architecture-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Churn-Prevention-&-Retention-Analytics/AI-Powered-B2B-SaaS-Churn-Signal-Detection-Matrix-&-Marketing-Intervention-Architecture-Intelligence-Engine.md) — Churn signal detection for accounts already showing renewal risk signals, pairs with engagement scoring for end-to-end retention coverage
- [`../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Health-Score-Intelligence-&-Proactive-Marketing-Intervention-Architecture-Engine.md`](../../05_Analytics-&-Performance/Customer-Lifecycle-Marketing-Analytics/AI-Powered-B2B-SaaS-Customer-Health-Score-Intelligence-&-Proactive-Marketing-Intervention-Architecture-Engine.md) — Broader customer health scoring that incorporates engagement signals alongside support ticket data, relationship strength, and sentiment
- [`../../02_Product-Marketing/Product-Adoption-Marketing/AI-Powered-B2B-SaaS-Feature-Adoption-Campaign-Architecture-&-Product-Led-Retention-Intelligence-Engine.md`](../../02_Product-Marketing/Product-Adoption-Marketing/AI-Powered-B2B-SaaS-Feature-Adoption-Campaign-Architecture-&-Product-Led-Retention-Intelligence-Engine.md) — Campaign execution engine to activate the marketing interventions identified by the engagement scoring system

## Integration Tips

- **Amplitude:** Use Amplitude's Behavioral Cohorts to define each archetype as a saved cohort — Cohort for "Power Advocates" = users who meet the scoring criteria for Archetype 1. Sync these cohorts into HubSpot or Salesforce using Amplitude's native CRM sync or via Hightouch. Update cohort membership daily so engagement score changes trigger marketing sequences within 24 hours of the behavioral shift. Use Amplitude's Dashboard Reports to build the Weekly Engagement KPI view with custom metrics for archetype distribution and score trend.

- **Mixpanel:** Use Mixpanel's User Properties to store each user's current archetype classification and numeric engagement score as custom properties, updated by a weekly scheduled export via Census or Hightouch. Use Mixpanel's Retention and Funnels reports to validate the Engagement-to-Revenue Correlation Model — specifically, use Retention with "Feature Gravity event as Day 0" to confirm the renewal rate differential between Feature Gravity adopters and non-adopters in your actual cohort data.

- **Pendo:** Use Pendo's Segments to mirror each archetype definition using NPS, guide completion, and feature usage filters. Pendo's In-App Guides can deliver the Phantom User "2-minute quick win" modal and the Casual Contributor "expand your toolkit" prompt based on segment membership. Use Pendo's Health Scores if your CS team is already using it — overlay your engagement archetype data as a separate data layer rather than replacing Pendo's health score, so CS sees both the behavioral archetype and the relationship health score side-by-side.

- **Salesforce / HubSpot:** Create a custom "Engagement Archetype" picklist field on the Contact object (values: Power Advocate / Active / Passive / Phantom / Dormant / Accidental Admin) and a numeric "Engagement Score" field on both Contact and Account objects. Create a "Account Health State" picklist on the Account object (values: Thriving / Consolidating / Fragile / Critical). Build automated workflow rules in Salesforce or HubSpot that trigger the appropriate marketing sequence when these fields change — e.g., when Account Health State changes to "Critical," auto-enroll in the reactivation sequence and create a High Priority CS task.

- **Gainsight / ChurnZero:** Map each account health state to a Gainsight Risk tier or ChurnZero Health Score range. Gainsight CTAs should fire automatically when an account enters Critical state — these become the CS team's daily churn prevention queue. Use Gainsight's Journey Orchestrator to automate the State 3 (Fragile) Champion Redundancy Campaign as a digital touch sequence, with CS-assisted touches reserved for accounts above your ARR threshold. Log all marketing-driven engagement events in Gainsight Timeline so CS has full visibility into the digital campaign history when they pick up the phone.

- **Census / Hightouch (Reverse ETL):** If your engagement scoring model runs in a data warehouse (Snowflake, BigQuery, Redshift), use Hightouch or Census to push updated engagement scores and archetype assignments into Salesforce, HubSpot, and your email marketing platform in real time. Schedule syncs every 4–6 hours so marketing triggers fire within half a business day of a behavioral event. This eliminates manual export cycles and ensures the "24-hour trigger" SLA is achievable at scale.

- **Slack:** Create a dedicated `#engagement-intelligence-alerts` Slack channel connected to your CRM or Gainsight. Daily automated post: "Account Engagement Snapshot — [Date]: Decline triggers fired: [X accounts, $Y ARR]. Expansion triggers fired: [Z accounts]. New Power Advocates identified: [N users]. Critical state accounts requiring human outreach this week: [list with ARR, CSM owner, and Salesforce link]." Include a weekly Friday digest showing week-over-week archetype migration rate — this becomes the retention marketing team's primary performance metric.

## Troubleshooting

**Problem:** The engagement scoring model classifies too many accounts as Critical, creating an overwhelming number of CS alerts that the team can't action — alert fatigue causes the entire system to be ignored.
**Solution:** Recalibrate the score threshold for Critical state using historical renewal data before launch. Pull the actual renewal rate for accounts at each 5-point score interval (0–5, 5–10, 10–15, etc.) and identify the empirically correct threshold where churn majority begins. If your current product analytics data shows that accounts scoring <50 churn at >50% rates, set Critical at <50, not <35. Also implement a "New to Critical" filter — only alert on accounts that have *newly transitioned* into Critical state this week, not all accounts already there. This caps weekly alerts at a manageable volume equal to the Critical transition rate, not the total Critical population.

**Problem:** Product usage data lives in a separate system inaccessible to the marketing team, making it impossible to build or update the engagement scoring model without engineering support.
**Solution:** Implement a minimum viable engagement signal set that can be extracted via scheduled CSV export from engineering: (1) last login date, (2) total output events in last 30 days (even a single count of all output event types combined), (3) number of distinct features used in last 30 days, (4) number of unique teammates who interacted with this user's content. Build a simplified 4-signal scoring spreadsheet updated weekly from these exports. This gives you the 80% of scoring power with 20% of the data infrastructure effort. Simultaneously, escalate to the CMO and CRO to prioritize a reverse ETL tool (Hightouch or Census) as a Q1 marketing ops investment — without real-time product data in the marketing stack, every engagement decision is a week behind the behavior it's responding to.

**Problem:** The archetype segmentation produces dramatically different results for enterprise accounts (200+ users) vs. SMB accounts (3–5 users), making it impossible to apply the same intervention playbooks — an SMB with 2 Casual Contributors looks different from an enterprise with 40 Casual Contributors.
**Solution:** Normalize all archetype calculations by account size tier before applying engagement state thresholds. Define separate score ranges for SMB (1–10 users), Mid-Market (11–50 users), and Enterprise (51+ users). For SMB accounts, "Thriving" might require only 1 Power Advocate and 60% Active users; for Enterprise, require 3 Power Advocates across 2+ departments and <20% Dormant users. Similarly, normalize the Critical state threshold — an enterprise account where 30% of users are Dormant is in a different risk category than an SMB account where 1 of 3 users is Dormant. Build separate intervention playbooks for each tier: SMB interventions should be fully automated (email-only); Enterprise interventions should require a human CS touch at every critical state transition.

## Version History
- v1.0: Initial creation (auto-generated)
