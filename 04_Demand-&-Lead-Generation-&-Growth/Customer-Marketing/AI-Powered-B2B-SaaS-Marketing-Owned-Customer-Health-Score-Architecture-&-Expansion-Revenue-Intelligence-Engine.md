# AI-Powered B2B SaaS Marketing-Owned Customer Health Score Architecture & Expansion Revenue Intelligence Engine - Turn Customer Signals Into Predictable Expansion Pipeline

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** customer-marketing, health-score, expansion-revenue, nrr, churn-prevention, product-signals, b2b-saas, ai-agents, marketing-ops, customer-intelligence, predictive-analytics

## Overview
This prompt builds a marketing-owned customer health intelligence system that aggregates product usage, engagement, relationship, and financial signals into a predictive health score — then automatically routes each customer to the right expansion campaign, churn-rescue motion, or advocacy activation. Use it when your marketing team is being held accountable for net revenue retention (NRR) but lacks the signal infrastructure to predict who needs attention, when, and with what intervention.

## Quick Copy-Paste Version

You are an expert B2B SaaS customer intelligence architect. Build me a complete Marketing-Owned Customer Health Score System for my company.

Company: [Your Company] — [e.g., B2B SaaS revenue intelligence platform, $35M ARR, Series C, 280 customers]
Customer segments: [e.g., SMB accounts $5K-$25K ARR / Mid-Market $25K-$150K ARR / Enterprise $150K+ ARR]
Current data sources available: [e.g., product usage from Amplitude, CRM data in Salesforce, NPS from Delighted, support tickets from Zendesk, email engagement from HubSpot, billing data from Stripe]
NRR target: [e.g., 120% — we're currently at 108% and need to identify $2.8M in expansion opportunities]
Key problem: [e.g., We only find out customers are churning 30 days before renewal. We have no proactive signal system. Marketing owns expansion pipeline but we're flying blind.]

Build a complete Marketing-Owned Customer Health Intelligence System that includes:

1. Health signal inventory — identify the 8-12 highest-predictive signals across product, engagement, relationship, and financial dimensions, weighted by churn/expansion correlation
2. Composite health score model — a 0-100 score with segment-specific weighting for SMB, Mid-Market, and Enterprise customers
3. Health tier definitions — specific thresholds, descriptions, and marketing-motion triggers for Red/Yellow/Green/Champion tiers
4. Automated marketing playbooks — AI-personalized campaigns triggered by health score changes, tier transitions, and signal spikes
5. Expansion opportunity scoring — a secondary score that identifies accounts with highest upsell/cross-sell propensity within healthy accounts
6. Weekly health intelligence brief — a marketing-generated account intelligence digest for the revenue team

Format as a production-ready playbook with signal definitions, score calculations, campaign triggers, and automation logic.

## Advanced Customizable Version

ROLE:
You are a Chief Customer Marketing Officer with 18 years of B2B SaaS experience — a specialist in building the intelligence infrastructure that allows marketing to own and drive net revenue retention. You have built customer health scoring systems at companies including Gainsight (before they productized it), Intercom, Drift, and Lattice. You understand that 90% of B2B SaaS companies have customer health scores owned by Customer Success — but CS health scores are designed to prevent churn, not to generate expansion pipeline. Marketing health scores have a different architecture: they weight buyer intent signals, engagement with expansion content, and champion relationship strength more heavily than CS does. You build systems where marketing can identify an expansion opportunity 60-90 days before the renewal conversation, personalize a campaign to the right stakeholder, and attribute the resulting expansion revenue back to the marketing motion. Your systems run with fewer than 4 hours per week of human maintenance at steady state and produce measurable lift in expansion pipeline within 90 days of deployment.

CONTEXT:
Company: [Company Name]
Business model: [B2B SaaS / B2B PaaS / B2B Marketplace]
Annual revenue / ARR: [e.g., $42M ARR, Series C, 315 customers across 3 segments]
Average contract value: [SMB: $8K ACV / Mid-Market: $65K ACV / Enterprise: $280K ACV]
Current NRR: [e.g., 109% — target is 118%]
NRR gap to close: [e.g., $3.8M in expansion revenue needed to reach 118% from 315 accounts]
Customer segments: [e.g., SMB: <$20K ACV, 180 accounts / Mid-Market: $20K-$100K, 110 accounts / Enterprise: $100K+, 25 accounts]
Current CS tech stack: [e.g., Gainsight for CS health scoring / Totango / ChurnZero / or none — CS uses Salesforce only]
Marketing tech stack: [e.g., HubSpot (MAP) / Marketo / Pardot / Customer.io]
Product analytics: [e.g., Amplitude / Mixpanel / Heap / Pendo / or custom BI tables in Snowflake]
CRM: [e.g., Salesforce with custom opportunity objects for expansion]
Support: [e.g., Zendesk with CSAT scoring enabled]
NPS tool: [e.g., Delighted / Medallia / or manual quarterly surveys]
Billing: [e.g., Stripe / Chargebee / Zuora]
Relationship intelligence: [e.g., Gong call recordings / Chorus / or none]
Current expansion marketing capability: [e.g., We send a generic renewal email 90 days out and occasionally share product updates. No segment-specific expansion campaigns exist. Marketing has no access to product usage data.]
Marketing ownership of NRR: [e.g., Marketing is accountable for sourcing 40% of expansion pipeline per our FY26 plan — currently sourcing 12%]

OBJECTIVE:
Design a production-ready Marketing-Owned Customer Health Score Architecture & Expansion Revenue Intelligence System that:
1. Creates a marketing-specific composite health score powered by 8-12 weighted signals (distinct from CS health scores)
2. Segments customers into 4 health tiers with automated marketing playbook triggers
3. Identifies expansion-ready accounts with a secondary Expansion Propensity Score
4. Automates AI-personalized marketing campaigns triggered by health score changes, not just renewal dates
5. Generates a weekly marketing intelligence brief that routes at-risk and expansion accounts to the right team
6. Attributes expansion revenue sourced by marketing-owned health interventions with full pipeline reporting

DELIVERABLES:

---

**1. MARKETING HEALTH SIGNAL INVENTORY & WEIGHTING MODEL**

Design the complete signal architecture across four dimensions:

**PRODUCT USAGE DIMENSION (40% weight for SMB/MM, 30% for Enterprise)**
For each signal below, define: data source, measurement frequency, healthy benchmark, warning threshold, and correlation to expansion vs. churn:

*Primary usage signals:*
- Daily/Weekly Active Users (DAU/WAU) as % of licensed seats: [Define formula: Healthy = >75% seat activation in last 30 days / Warning = 40-74% / Red = <40%]
- Feature adoption breadth: [Number of core features used in last 30 days vs. features included in current tier — proxy for value realization depth]
- Session frequency trend: [30-day rolling average vs. 90-day prior period — trajectory matters more than absolute level]
- Power user identification: [Users in top 20% of usage within account — indicate champions and expansion advocates]
- New user additions: [Net new seats activated in last 60 days — strongest leading indicator of organic expansion intent]
- Integration connections: [Number of integrations enabled — users who connect 3+ integrations have 4x lower churn rate in most SaaS benchmarks]

*Product-led expansion signals:*
- Feature unlock requests: [Users clicking on locked premium features or upgrade prompts — explicit expansion intent]
- Usage ceiling approach: [Account consuming >80% of their current plan limit — trigger for commercial conversation]
- Cross-product exploration: [Users viewing other product modules or pricing pages — signal of internal champion expansion advocacy]

**ENGAGEMENT DIMENSION (25% weight)**
*Content engagement signals:*
- Marketing email open/click rate trend: [30-day vs. prior 30-day — declining engagement predicts churn 60-90 days out]
- Expansion content consumption: [Downloads of feature release notes, advanced use case guides, ROI calculators — intent to expand]
- Webinar attendance rate: [Account attendance at product education webinars — correlates with feature adoption]
- Help center utilization: [Self-service support success rate — high self-serve resolution = product-value realization]
- Community activity: [Posts, replies, reactions in customer community — community-engaged accounts churn 40-60% less]

**RELATIONSHIP DIMENSION (20% weight)**
*Champion & stakeholder signals:*
- Executive sponsor engagement: [Last meeting with VP+ stakeholder — signal health of executive relationship]
- Champion content sharing: [Customer sharing your content on LinkedIn / internal Slack channels — advocacy strength]
- Reference and referral activity: [Participation in case studies, reference calls, G2 reviews — strongest advocate signal]
- Support escalation pattern: [Number of P1/P2 escalations in last 90 days — relationship strain indicator]
- Renewal stakeholder access: [Do you have 2+ contacts in the renewal decision process — single-threaded = high risk]

**FINANCIAL & CONTRACT DIMENSION (15% weight)**
*Commercial health signals:*
- Payment history: [On-time payment rate over contract life — late payments predict churn at 3x industry average]
- Contract term: [Multi-year vs. monthly — monthly contracts churn at 2-3x annual contract rates]
- Days to renewal: [<120 days without renewal meeting scheduled = risk flag]
- Pending invoices: [Outstanding payment >30 days = immediate intervention trigger]
- Price sensitivity signals: [Downgrade requests, discount history, pricing page visits]

---

**2. COMPOSITE HEALTH SCORE CALCULATION MODEL**

Design segment-specific scoring with explicit weighting rationale:

**SMB HEALTH SCORE (accounts <$20K ACV)**
- SMB churn is driven primarily by product abandonment — weight product usage highest
- Score formula: (Product Usage × 0.45) + (Engagement × 0.30) + (Relationship × 0.15) + (Financial × 0.10)
- Automation threshold: Full automated campaign triggers at all tier changes — no human CSM involvement for SMB
- Refresh cadence: Daily for Red accounts, weekly for Yellow, bi-weekly for Green and Champion

**MID-MARKET HEALTH SCORE (accounts $20K-$100K ACV)**
- Mid-market risk = feature abandonment + single-threaded relationships
- Score formula: (Product Usage × 0.35) + (Engagement × 0.25) + (Relationship × 0.28) + (Financial × 0.12)
- Automation threshold: Automated campaigns + CS alert for any tier downgrade >1 level
- Refresh cadence: Daily for Red, weekly for Yellow and Green

**ENTERPRISE HEALTH SCORE (accounts >$100K ACV)**
- Enterprise risk = relationship attrition + internal champion loss + competitive evaluation
- Score formula: (Product Usage × 0.28) + (Engagement × 0.20) + (Relationship × 0.40) + (Financial × 0.12)
- Automation threshold: Automated campaigns for content delivery only — all commercial actions require human confirmation
- Refresh cadence: Daily for all Enterprise accounts

---

**3. HEALTH TIER DEFINITIONS & MARKETING MOTION TRIGGERS**

Define exact thresholds and immediate marketing actions for each tier:

**TIER 1: RED — At-Risk (Score 0-45)**
Definition: Account shows 3+ warning signals or 1 critical signal (>40% seat abandonment, executive relationship lost, payment overdue)
Immediate marketing actions:
- [Hour 1]: Internal alert to marketing, CS, and account owner via Slack/email
- [Day 1]: Personalized executive outreach from CEO/CMO to executive sponsor (AI-drafted, human-sent)
- [Day 3]: Customer success story specific to their industry sent to all contacts in account
- [Day 7]: ROI business case review offer — "We'd like to show you exactly what [Product] has delivered for your business"
- [Day 14]: Risk escalation to VP/C-Suite if no response — marketing-sourced executive engagement play
- [Day 21]: Competitive intelligence brief sent to champion — "Here's what you'd lose switching"

**TIER 2: YELLOW — Needs Attention (Score 46-65)**
Definition: Account showing declining trend in 2+ signals or stagnant below healthy benchmark
Immediate marketing actions:
- [Week 1]: Product adoption campaign — targeted emails for underused features with specific ROI examples
- [Week 2]: Customer education invitation — invite to advanced training webinar or certification program
- [Week 3]: Peer success story — case study from similar-size company in same industry showing value
- [Week 4]: QBR offer — "Your next business review should show you exactly where you stand vs. your goals"
- [Ongoing]: Monthly executive newsletter from account's CSM + Marketing co-branded

**TIER 3: GREEN — Healthy (Score 66-85)**
Definition: Account meeting benchmarks across primary signals, stable trend
Marketing actions:
- Monthly product update email with feature recommendations based on their usage pattern
- Quarterly ROI benchmark report — how their metrics compare to top-performing customers in their segment
- Expansion content drip — use case guides for features/modules they haven't activated
- Community invitation — nominate for customer community leadership role
- Reference program invitation — approach for case study or speaking opportunity

**TIER 4: CHAMPION — Expansion Ready (Score 86-100 + Expansion Propensity Score >70)**
Definition: Account exceeding benchmarks, showing active expansion signals
Marketing actions:
- [Immediate]: Flag to account owner and CS for commercial conversation
- [Week 1]: Executive briefing invite — new product roadmap session with CPO
- [Week 2]: Personalized expansion pitch — specific next product module with ROI calculation
- [Week 3]: Referral program activation — high-touch outreach to generate peer referrals
- [Ongoing]: Customer advisory board nomination, co-marketing opportunity, speaker slot at user conference

---

**4. EXPANSION PROPENSITY SCORE (Secondary Score)**

Design a 0-100 expansion score to identify WHICH healthy accounts to prioritize for commercial expansion:

**Expansion Propensity Signal Matrix:**

Tier 1 signals (highest weight — 35% combined):
- Feature ceiling approach: Account using >80% of plan limits → immediate commercial trigger
- Cross-product page views: Champion visiting product pages for modules not yet purchased
- Multi-department expansion: New users from departments not currently using the product

Tier 2 signals (strong weight — 30% combined):
- Power user growth: Number of users in top 20% usage percentile growing month-over-month
- Integration connections growth: Adding new integrations — signals expanding use cases
- Champion internal advocacy: Sharing product updates internally (tracked via product sharing features)

Tier 3 signals (moderate weight — 20% combined):
- Company growth signals: Hiring signal data (new job postings), funding announcement, revenue growth news
- Product survey responses: Users rating "Would recommend adding more seats" in in-product surveys
- Webinar attendance: Attending product expansion/advanced features sessions

Tier 4 signals (contextual weight — 15% combined):
- Contract terms: Month-to-month vs. annual — month-to-month with healthy score = upsell to annual
- Historical expansion pattern: Did this account expand in year 1? Strong predictor of year 2 expansion
- Similar customer expansion: Accounts matching this account's profile that have expanded

**Expansion Propensity Score Output:**
- Score 85-100: Immediate expansion opportunity — assign to high-touch commercial play
- Score 70-84: Expansion ready — begin nurture with expansion content, schedule QBR
- Score 55-69: Expansion potential — continue product adoption before commercial approach
- Score <55: Not expansion ready — focus on health improvement first

---

**5. AI-PERSONALIZED CAMPAIGN ARCHITECTURE BY HEALTH MOTION**

For each of the 4 marketing motions below, design the campaign structure:

**MOTION 1: CHURN RESCUE CAMPAIGNS (Red Tier)**

Campaign: "Value Restoration"
Trigger: Health score drops below 45 or falls 20+ points in 30 days
Duration: 45 days
Personalization variables:
- [Industry]: Industry-specific ROI proof points from similar customers
- [Role]: Champion persona (practitioner vs. economic buyer vs. technical buyer)
- [Usage gap]: Which features they're NOT using that their peers are
- [Risk signal]: Which specific signal triggered the campaign (used in subject lines)

Email sequence:
- Email 1 (Day 1): "We noticed [Company] may not be getting full value from [Product]" — specific usage data, peer benchmark
- Email 2 (Day 5): Customer success story from identical company profile — proof of value restoration
- Email 3 (Day 10): "Book a free optimization session" — CSM + Product Specialist, 30-minute value diagnostic
- Email 4 (Day 18): ROI business case — AI-generated calculation of value received vs. potential based on their specific usage gap
- Email 5 (Day 28): Executive escalation — CMO/CEO to executive sponsor if champion unresponsive
- Email 6 (Day 40): "Here's what customers like [Company] have achieved" — final social proof sequence before CS handles renewal

Supporting channels:
- LinkedIn: Targeted ads to all account contacts showing customer success content
- Direct mail (Enterprise only): Personalized impact report with custom metrics

**MOTION 2: ADOPTION ACCELERATION (Yellow Tier)**

Campaign: "ROI Amplifier"
Trigger: Product usage below segment benchmark for 45+ days or declining trend
Duration: 30 days with evergreen maintenance
Personalization variables:
- [Feature gap]: Specific features with low adoption personalized to user's role
- [Time to value]: How long it typically takes similar users to achieve outcomes from underused features
- [Success path]: AI-recommended 3-step path from current usage to benchmark usage

Email sequence:
- Email 1: "[Name], here's what [Company] is leaving on the table" — feature gap analysis with peer comparison
- Email 2: "Quick win: [Specific feature] can save your team [X hours/week]" — single feature ROI case
- Email 3: Invitation to live adoption session — "30-minute feature deep-dive with a product expert"
- Email 4: Video walkthrough from customer who had same usage pattern and expanded value
- Email 5 (30-day mark): Progress report — "Here's how [Company]'s usage has changed" + next recommended step

**MOTION 3: EXPANSION PIPELINE CAMPAIGNS (Champion Tier)**

Campaign: "Growth Accelerator"
Trigger: Health score >85 AND Expansion Propensity Score >70
Duration: Evergreen 90-day sequence per account
Personalization variables:
- [Expansion module]: Specific product module based on their usage pattern and company profile
- [ROI projection]: AI-calculated expansion ROI based on their current metrics + similar customer outcomes
- [Stakeholder path]: Who internally would be the expansion champion vs. economic buyer

Email sequence (to champion):
- Email 1: "How [Similar Company] went from [Current State] to [Expanded State] with [Module]" — peer story
- Email 2: "[Name], you're doing X — here's what the top performers do next" — aspirational benchmark
- Email 3: "Exclusive preview: [Module] early access for customers like [Company]" — FOMO + exclusive access

Executive email sequence (to economic buyer):
- Email 1: "Your peer [CMO/CRO name] at [Similar Company] expanded and achieved [specific metric]"
- Email 2: ROI projection — "Based on [Company]'s current results, adding [Module] would deliver [X] ROI"
- Email 3: "Reserve 20 minutes with our CPO" — executive briefing invitation

**MOTION 4: ADVOCACY ACTIVATION (Champion Tier)**

Campaign: "VIP Advocate Program"
Trigger: Health score >85 sustained for 90+ days
Goal: Convert high-health accounts into active marketing assets (case studies, referrals, speakers)
Email sequence:
- Email 1: Recognition outreach — "You're in the top 15% of [Product] users — here's what that means"
- Email 2: Case study invitation — executive-to-executive request with specific story outline
- Email 3: Customer Advisory Board nomination — quarterly exclusive briefing with product leadership
- Email 4: Conference speaker invitation — "Would you share your story at [Conference/User Summit]?"
- Email 5: Referral program activation — personalized incentive structure

---

**6. WEEKLY MARKETING CUSTOMER HEALTH INTELLIGENCE BRIEF**

Design the automated weekly brief format for the revenue team:

**Brief Structure (automated, sent every Monday by 8am):**

SECTION 1: Portfolio Health Snapshot (automated from score aggregation)
- Total accounts by tier: [Red X / Yellow X / Green X / Champion X]
- Week-over-week tier movement: [Improved: X accounts / Declined: X accounts]
- Revenue at risk (Red + Yellow ARR): [$X]
- Expansion pipeline identified this week: [$X from Champion tier]

SECTION 2: Critical Account Alerts (priority routing)
For each Red account: Account name | ARR | Health score | Score change | Trigger signal | Assigned campaign | Required human action
For each account that dropped a full tier: Same format + recommended escalation action

SECTION 3: Expansion Opportunities Identified
For each account with Expansion Propensity Score >80:
- Account name | Current ARR | Expansion propensity score | Primary expansion signal | Recommended play | Potential expansion ARR

SECTION 4: Campaign Performance Summary
- Churn rescue campaigns: X accounts in program | X responded | X health score improved
- Adoption campaigns: X accounts | Average feature activation change: +X%
- Expansion campaigns: X accounts in program | X opportunities created | $X pipeline

SECTION 5: Next Week's Priority Actions (AI-generated recommendations)
- Top 5 accounts requiring immediate marketing attention with specific recommended action

---

**7. ATTRIBUTION & REVENUE REPORTING**

Design the expansion revenue attribution model for marketing-owned health motions:

**Attribution Framework:**
- Marketing First Touch: Marketing health campaign created first account engagement in expansion journey
- Marketing Last Touch: Marketing campaign triggered commercial conversation (demo request, expansion meeting request)
- Marketing Multi-Touch: Marketing contributed to 2+ touchpoints in expansion journey
- Influenced Attribution: Account health improved during marketing campaign period, correlating with expansion close

**Reporting Metrics:**
- Marketing-sourced expansion pipeline: Opportunities where marketing health campaign was first touch
- Marketing-influenced expansion pipeline: Opportunities where marketing touched account during 90-day window
- Expansion close rate by health tier at deal creation: [Red→close rate vs. Green→close rate vs. Champion→close rate]
- Churn rescue success rate: % of Red accounts that improved to Yellow or above within 90 days
- Average time-to-recovery: Days from Red tier designation to Green tier for rescued accounts

---

**IMPLEMENTATION SEQUENCE:**

Phase 1 — Signal Infrastructure (Weeks 1-4):
- Audit available data sources and API connections
- Define signal calculations and benchmark thresholds by segment
- Build health score calculation in your analytics/BI layer (or use [CustomerOS / Vitally / Gainsight / spreadsheet] depending on tech stack)
- Validate score against known churned and expanded accounts from prior 12 months

Phase 2 — Campaign Architecture (Weeks 5-8):
- Build campaign sequences in MAP (HubSpot/Marketo/Customer.io)
- Configure tier-based enrollment triggers
- Create personalization variables and dynamic content blocks
- Test with 10 accounts per tier before full rollout

Phase 3 — Reporting & Attribution (Weeks 9-12):
- Build health score dashboard in Salesforce/HubSpot/BI tool
- Configure weekly brief automation
- Establish attribution tracking for expansion opportunities
- Define SLAs between marketing (campaign delivery) and CS (commercial conversation)

## Example Input/Output

**Input:**
Company: PipelineIQ — B2B SaaS revenue forecasting platform, $28M ARR, 210 customers
Segments: SMB (70 accounts, avg $12K ACV), Mid-Market (110 accounts, avg $78K ACV), Enterprise (30 accounts, avg $320K ACV)
Tech stack: HubSpot (MAP + CRM), Amplitude (product analytics), Zendesk (support), Delighted (NPS), Stripe (billing)
Current NRR: 106%, target 118%
Problem: We're finding at-risk customers only at renewal. Marketing sends generic renewal emails.

**Output excerpt:**

**PipelineIQ Health Score Architecture:**

Mid-Market Composite Score (110 accounts, $8.6M ARR segment):

Signal 1 — Seat Activation Rate (weight: 18%): Healthy >70% | Warning 45-69% | Red <45%
→ Current benchmark: 64% average — 38 accounts in warning range
→ Automated trigger: any account dropping below 50% activation triggers "ROI Amplifier" campaign within 24 hours

Signal 2 — Weekly Active Users 30-day trend (weight: 15%): Healthy = flat or growing | Warning = -10 to -25% | Red = >-25%
→ Tracked via Amplitude cohort analysis, updated daily
→ 22 MM accounts showing negative 30-day trend

Signal 3 — Feature breadth index (weight: 12%): Healthy = using 6+ of 10 core features | Warning = 3-5 | Red = <3
→ Average MM account uses 4.2 features — below healthy benchmark
→ Most underused features by account: [Forecasting Scenarios, Pipeline Trending, Call Intelligence]

Signal 4 — NPS score (weight: 10%): Healthy = Promoter (9-10) | Warning = Passive (7-8) | Red = Detractor (0-6)
→ Last NPS survey: 31% Promoters, 48% Passives, 21% Detractors in MM segment

Signal 5 — Executive relationship strength (weight: 14%): Healthy = VP+ meeting in last 60 days | Warning = 61-120 days | Red = >120 days
→ 44 MM accounts with no executive contact in 90+ days

**Week 1 Priority Actions:**
→ 12 accounts in Red tier — immediate churn rescue sequence launched
→ 8 accounts with Expansion Propensity Score >80 — expansion pipeline campaigns activated
→ Estimated pipeline impact at 90 days: $420K expansion, $380K churn prevented based on segment benchmarks

## Success Metrics

**Health Score Model Quality:**
- Score correlation with 12-month outcome: Health score at 90 days should predict churn/expansion with >75% accuracy when backtested against prior year data
- Tier-to-outcome validation: Red accounts should churn at 4-6x higher rate than Champion accounts within 6 months

**Campaign Performance:**
- Churn rescue conversion: >30% of Red tier accounts improve to Yellow within 90 days of campaign activation
- Adoption campaign lift: Yellow tier accounts show +15% feature activation within 30 days of campaign
- Expansion campaign pipeline: Champion tier campaigns generate expansion meetings within 45 days for >25% of targeted accounts

**Revenue Impact:**
- NRR lift: 3-5 percentage points improvement in NRR within 6 months of full deployment
- Marketing-sourced expansion pipeline: Marketing health campaigns should source 25-40% of expansion pipeline
- Churn reduction: 20-35% reduction in unexpected churn (accounts flagging Red and churning before intervention)

**Operational Efficiency:**
- Time-to-alert: Marketing-owned health system should identify at-risk accounts 60-90 days earlier than renewal-based detection
- Human time per week: System should run with <4 hours/week of marketing ops maintenance

## Related Prompts

- [AI-Powered B2B SaaS Product Usage Signal Triggered Customer Marketing](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Product-Usage-Signal-Triggered-Customer-Marketing-Orchestration-&-Lifecycle-Revenue-Intelligence-Engine.md)
- [AI-Powered B2B SaaS NRR Marketing Program Architecture](../../06_Customer-Success-&-Retention/Churn-Prevention-&-Expansion/AI-Powered-B2B-SaaS-NRR-Marketing-Program-Architecture-&-Expansion-Revenue-Campaign-Intelligence-Engine.md)
- [Customer Health Score & Early Warning Intelligence Engine](../../06_Customer-Success-&-Retention/Customer-Success-Automation/Customer-Health-Score-&-Early-Warning-Intelligence-Engine.md)
- [AI-Powered B2B SaaS Renewal Marketing Program Architecture](../../04_Demand-&-Lead-Generation-&-Growth/Customer-Marketing/AI-Powered-B2B-SaaS-Renewal-Marketing-Program-Architecture-&-At-Risk-Account-Churn-Prevention-Revenue-Intelligence-Engine.md)

## Integration Tips

**HubSpot:** Create custom contact and company properties for health score, tier, and last tier change date. Use Workflows to enroll contacts in health-triggered sequences. Use custom reports to track tier movement over time and expansion pipeline attributed to health campaigns.

**Salesforce:** Build a "Customer Health" custom object linked to Account. Create List Views for Red/Yellow accounts requiring attention. Use Flow automation to create expansion opportunities when Expansion Propensity Score exceeds threshold. Build a Health Intelligence dashboard using reports and Einstein Analytics.

**Amplitude:** Use Amplitude's Behavioral Cohorts to define your health signal user groups. Create a weekly health signal export via Amplitude's Data Export API and pipe to your CRM or a Google Sheet for score calculation. Use Amplitude's Journeys to visualize the product paths of churned vs. expanded accounts.

**Gainsight/Totango (if CS owns their own health score):** Map fields between CS health score and marketing health score — they intentionally measure different signals. Use Gainsight's CoPilot or Totango's SuccessPlays to trigger marketing campaigns from CS health alerts. Establish a shared "Health SLA" where marketing triggers campaign within 24 hours of CS flagging an account as at-risk.

**Google Sheets + Zapier (no-code option):** Build health score calculation in Google Sheets using IMPORTDATA from product analytics exports. Use Zapier to watch for score changes and trigger HubSpot workflows or send Slack alerts. This approach handles up to 300 accounts effectively without engineering resources.

**Snowflake/BigQuery:** If you have a data warehouse, build health score as a dbt model that refreshes daily. Push scores to Salesforce and HubSpot via Fivetran or Hightouch for campaign triggering. This is the highest-fidelity approach for enterprise-scale deployments with 500+ accounts.

## Troubleshooting

**Problem: Health score doesn't correlate with actual churn outcomes.**
Fix: Backtest your model against the last 12 months of churned and expanded accounts. If your Red tier accounts aren't churning at 4-6x your Green tier accounts, your signal weights are wrong. The most common error is over-weighting NPS (lagging indicator) and under-weighting product usage trends (leading indicator). Reweight toward 30-day trend direction vs. absolute benchmark.

**Problem: Marketing campaigns aren't improving health scores for Yellow/Red accounts.**
Fix: Audit whether your campaigns are reaching the right contact. Health score campaigns often fail because they're sent to the original lead contact, not the active product champion. Map your campaign delivery to contacts with recent product login activity — they're the ones whose behavior will actually move the health score. Sending a feature activation email to an executive who hasn't logged in is wasted sends.

**Problem: CS team is resistant to marketing owning customer health.**
Fix: Position the marketing health score as an expansion intelligence system, not a churn prediction system (CS already owns churn). Demonstrate that the marketing score identifies expansion-ready accounts 60-90 days before the renewal conversation — something CS health scores typically don't surface because they're optimized for risk, not opportunity. Run a 30-day pilot showing CS the expansion pipeline marketing generates from Champion-tier campaigns. Revenue alignment happens when CS sees marketing finding them deals, not competing for ownership.

## Version History
- v1.0: Initial creation (auto-generated)
