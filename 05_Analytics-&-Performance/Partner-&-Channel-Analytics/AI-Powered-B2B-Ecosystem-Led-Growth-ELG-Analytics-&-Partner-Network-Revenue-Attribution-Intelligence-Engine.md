# AI-Powered B2B Ecosystem-Led Growth (ELG) Analytics & Partner Network Revenue Attribution Intelligence Engine - Quantify the Revenue Value of Your Partner Ecosystem with Account Overlap, Warm-Path Attribution, and Network Effect Measurement

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, ecosystem-led-growth, ELG, partner-analytics, account-overlap, crossbeam, revenue-attribution, co-sell, partner-network, integration-analytics, salesforce, revenue-intelligence

## Overview
Builds an AI-powered analytics system for measuring Ecosystem-Led Growth (ELG) revenue contribution — quantifying how account overlap with partners, warm introductions, and co-sell network effects translate into pipeline, win rates, and expansion revenue that outperform cold-path direct selling. Use this when your CRO suspects the partner ecosystem is driving more revenue than the attribution model shows, when you're evaluating Crossbeam or Reveal to justify the investment, when warm-intro deals close faster but you can't prove it in a board deck, or when you need to build the business case for investing in ecosystem partnerships as a primary GTM motion.

## Quick Copy-Paste Version

You are a senior Ecosystem-Led Growth (ELG) analytics strategist with deep expertise in partner network revenue measurement. I need to build a comprehensive AI-powered analytics system that measures how our partner ecosystem drives revenue through account overlap, warm introductions, and co-sell network effects.

My ELG context:
- Company type: [B2B SaaS / Platform / Marketplace]
- Number of integration/technology partners: [X total active integrations]
- Number of co-sell partners: [X GSIs / X resellers / X referral partners]
- Ecosystem data tool: [Crossbeam / Reveal / PartnerStack / Manual overlap matching / None yet]
- CRM: [Salesforce / HubSpot]
- Current ELG visibility: [None — flying blind / Basic deal registration / Partial overlap tracking]
- Biggest ELG analytics gap: [e.g., "We can't tell if partner overlap accounts close faster," "No way to measure warm intro vs cold outbound performance," "Can't attribute integration-driven expansion revenue"]

Please deliver:
1. Account overlap attribution model — define ELG-sourced vs. ELG-accelerated pipeline with exact CRM field logic
2. Warm introduction conversion analytics — win rate, deal velocity, and ACV comparison between warm-path and cold-path deals
3. Partner ecosystem health score — measure each partner's network value by overlap density, introduction conversion rate, and expansion contribution
4. Integration-driven retention and expansion analytics — measure whether multi-integration accounts churn less and expand more
5. ELG executive dashboard — the 8 metrics that prove ecosystem ROI to a CFO and board in under 5 minutes

## Advanced Customizable Version

ROLE: You are a VP of Ecosystem Analytics and Revenue Operations with 12 years of experience building partner network measurement systems at B2B SaaS companies scaling from $30M to $400M ARR. You have deep expertise in designing ELG (Ecosystem-Led Growth) attribution models that correctly credit partner-network-sourced pipeline; in building Crossbeam and Reveal data integrations that surface account overlap signals inside CRM for sales prioritization; in measuring the network multiplier effect — the statistical relationship between ecosystem partner density and deal velocity; in proving that warm-path accounts (introduced through partner overlap) close at materially higher win rates than cold-path outbound; in quantifying how integration depth (number of active integrations per customer account) predicts NRR; and in building CFO-ready ELG ROI models that justify ecosystem investment at Series B through pre-IPO stage. You understand that ELG analytics fails when companies conflate partner-sourced (traditional reseller credit) with ecosystem-sourced (network overlap that created the relationship path) — and you build measurement systems that capture both distinctly.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Stage / ARR: [Series B / $30M ARR | Series C / $90M ARR | Growth / $220M ARR]
- Industry vertical: [e.g., FinTech, HR Tech, MarTech, DevTools, CyberSecurity, HealthTech]
- ICP: [Job titles, company sizes, geographies]
- ACV: [$X average new logo | $X average expansion]
- Sales cycle: [X days median for new logo]
- Partner ecosystem goal: [X% of new logo ARR sourced or accelerated through ecosystem in 12 months]
- Current ecosystem-sourced percentage: [X% or "unknown — that's why we need this"]

ECOSYSTEM ARCHITECTURE:
- Technology / Integration Partners: [List key platforms — Salesforce, HubSpot, Slack, Workday, ServiceNow, AWS, etc.]
- Co-Sell / Referral Partners: [List key GTM partners by type — GSI, VAR, agency, ISV]
- Marketplace Listings: [AWS Marketplace / Salesforce AppExchange / HubSpot App Marketplace / None]
- Ecosystem Data Infrastructure:
  - Overlap tool: [Crossbeam / Reveal (now Crossbeam) / Manual CSV matching / No overlap tracking]
  - Partnership management: [Alliances / PartnerStack / Impartner / Salesforce PRM / Spreadsheets]
  - CRM opportunity tracking: [Salesforce / HubSpot — note relevant custom fields]
  - Sales engagement: [Outreach / Salesloft / Apollo — for cold vs. warm path comparison]
- Current ELG signal capture: [How are warm introductions currently logged — if at all]

MEASUREMENT OBJECTIVES:
Design a comprehensive ELG analytics system that delivers:

**1. ELG ATTRIBUTION MODEL**
Build a rigorous attribution framework that distinguishes ecosystem-driven pipeline from traditional direct and partner-sourced:

ELG-Sourced Definition (design the exact CRM logic):
- Account was identified as an overlap account in Crossbeam/Reveal BEFORE any direct outreach existed in the CRM
- A partner contact made an explicit warm introduction (define: email/LinkedIn introduction, internal champion introduction, or partner-facilitated first meeting) that is logged as an activity in CRM
- No SDR sequence enrollment existed for the Account in the 60 days prior to the partner introduction
- Required CRM fields to implement: ELG_Source_Partner__c (partner who made intro), ELG_Intro_Date__c (date of warm introduction), ELG_Intro_Type__c (picklist: Crossbeam Overlap / Partner Champion / Marketplace Referral / Co-Sell Intro / Community Introduction), Overlap_Identified_Date__c (date account first appeared in overlap data)

ELG-Accelerated Definition (design the exact CRM logic):
- Direct sales motion existed (SDR sequence or AE outreach) BEFORE partner involvement, but
- Crossbeam/Reveal overlap data surfaced a partner relationship that was then leveraged to accelerate the deal (partner made an introduction to economic buyer, provided customer reference, or joined a sales call that advanced deal stage), AND
- Measurable acceleration occurred: deal stage advanced within 21 days of partner involvement, or buying committee expanded within 14 days of partner introduction
- Required CRM fields: ELG_Acceleration_Partner__c, ELG_Acceleration_Date__c, Days_to_Stage_Advance_Post_ELG__c (calculated field: close date minus ELG intro date vs. benchmark)

Co-Sell ELG Attribution Logic:
- When a GSI co-sells alongside your AE using Crossbeam overlap data, define the attribution split for program measurement (NOT commissions)
- Design the dispute resolution process when both direct AE and partner claim the relationship entry point
- Build the deal-level audit trail: Overlap_First_Seen_Date__c, First_AE_Activity_Date__c, Partner_Intro_Date__c, First_Meeting_Date__c — automated logic determines sourced vs. accelerated vs. co-sell

**2. WARM-PATH CONVERSION ANALYTICS**
Build the statistical comparison between warm-path (ELG-sourced/accelerated) and cold-path (direct outbound) deal performance:

Core Metrics to Calculate (with exact formulas):
- Warm-path win rate vs. cold-path win rate by: ICP segment, deal size cohort, industry vertical, and sales cycle month
- Warm-path deal velocity: median days from first meeting to close for ELG-sourced vs. cold outbound — calculate by partner type (GSI warm intro vs. tech partner overlap vs. marketplace referral)
- Warm-path ACV premium: do ELG-sourced deals close at higher ACV? Calculate ACV index: (Warm-path ACV / Cold-path ACV) - 1 = ACV premium %
- Partner network multiplier: for accounts with ≥3 partners that overlap (known to multiple partners simultaneously), calculate the pipeline-to-close conversion rate vs. single-partner overlap accounts
- Warm-path ramp efficiency: time from SDR assignment to qualified meeting for warm-path vs. cold-path accounts — this proves ecosystem reduces CAC through sales productivity improvement

Segmentation Cuts for Conversion Analytics:
- By partner type: integration partner overlap vs. co-sell partner intro vs. marketplace lead vs. community referral
- By overlap depth: single partner overlap vs. multi-partner overlap (2–3 partners know the account vs. 4+ partners know the account)
- By account size: SMB (<200 employees) vs. Mid-Market (200–2,000) vs. Enterprise (2,000+)
- By geography: domestic vs. international (ELG often has stronger international leverage due to partner local relationships)
- By ICP fit score: does warm-path advantage compound with high ICP fit or diminish?

**3. PARTNER ECOSYSTEM HEALTH & NETWORK VALUE SCORE**
Design a per-partner Network Value Score (NVS) that measures each partner's contribution to ecosystem-driven revenue:

NVS Components (define weights and formulas for each):
- Overlap Account Volume (20%): number of unique accounts in the partner's customer base that are also in your CRM as Targets or Prospects — data from Crossbeam/Reveal
- Overlap Account Quality (20%): % of partner's overlapping accounts that match ICP criteria (company size, industry, tech stack) — calculate ICP_Fit_Score for each overlap account
- Introduction Conversion Rate (25%): (ELG-sourced opportunities created from this partner's introductions) / (warm introduction requests made to this partner) — measures how reliably the partner converts overlap into actual meetings
- Deal Acceleration Rate (15%): % of ELG-accelerated deals where this partner's involvement measurably shortened the sales cycle vs. comparable cold-path deals
- Expansion Overlap Value (20%): % of existing customer accounts where this partner also has a customer relationship — these accounts are warm for upsell/cross-sell introductions, not just new logo

NVS Scoring Tiers:
- Tier 1 (NVS 80–100): Strategic Ecosystem Partners — prioritize co-marketing investment, joint QBRs, and dedicated ecosystem manager attention
- Tier 2 (NVS 50–79): Growth Ecosystem Partners — active co-sell programs, regular overlap review cadence (monthly), MDF eligibility
- Tier 3 (NVS 20–49): Potential Partners — monitor overlap growth, pilot one co-sell program per quarter
- Inactive (NVS <20): Technology partners with low overlap — evaluate whether integration drives retention value instead

**4. INTEGRATION-DRIVEN RETENTION & EXPANSION ANALYTICS**
Build the analytics system that proves integration depth predicts NRR:

Integration Depth Metrics:
- Integration Adoption Rate: % of customers who have activated ≥1 integration within 90 days of contract signature — this is a leading indicator of 12-month retention
- Integration Breadth Score per account: number of distinct integrations actively used (define "active": API calls ≥X per month, or user-initiated sync events ≥Y per month)
- Integration-NRR Correlation: calculate the NRR cohort analysis by integration depth bucket (0 integrations, 1, 2, 3, 4+) — this is the most powerful board-level proof of ecosystem value
- Integration-Churn Correlation: churn rate by integration depth — typically customers with 0 integrations churn at 2–4x the rate of customers with 3+ active integrations; calculate your company's specific multiplier
- Integration-Influenced Expansion: % of expansion revenue (upsell/cross-sell) where a partner provided a warm introduction to the expansion opportunity within the customer account — measure ELG for expansion, not just new logo

Ecosystem Stickiness Score (per customer account):
- Define: (Number of Active Integrations × 10) + (Number of Marketplace Reviews × 5) + (Partner Reference Calls Given × 15) + (Community Participation Score × 10)
- Correlate Ecosystem Stickiness Score with Renewal Probability Score in your NRR model
- Provide the SQL query to calculate Ecosystem Stickiness Score from your product analytics (Mixpanel/Amplitude/Segment) and CRM data

**5. ELG CAMPAIGN MEASUREMENT FRAMEWORK**
Measure the ROI of ecosystem-triggered marketing campaigns:

Overlap-Triggered Campaign Analytics:
- When Crossbeam identifies a new batch of overlap accounts (accounts that just became customers of a partner), measure the pipeline creation rate when those accounts receive an ELG-personalized outreach campaign vs. standard ICP outreach
- Define ELG Campaign ROI: (Pipeline Created from Overlap-Triggered Campaigns) / (Campaign Spend + Channel Manager Time Cost)
- A/B test measurement: for the same set of overlap accounts, compare (a) AE cold outreach alone vs. (b) partner-facilitated warm introduction — design the statistical test including required sample size, significance threshold, and measurement period

Marketplace Lead Measurement:
- For leads originating from AWS Marketplace, Salesforce AppExchange, or HubSpot App Marketplace: measure win rate, ACV, sales cycle, and NRR vs. direct-sourced leads
- Marketplace CAC calculation: (Marketplace listing fee + co-marketing spend + transaction fees on closed revenue) / Marketplace-sourced new logo ARR
- Marketplace-to-pipeline velocity: time from marketplace inquiry to qualified opportunity by marketplace platform

**6. ELG EXECUTIVE REPORTING SYSTEM**

Weekly ELG Pulse Report (for Partnerships + Sales Ops):
- New overlap accounts identified this week (by partner, by ICP score)
- Warm introductions requested vs. completed this week
- ELG-sourced and ELG-accelerated pipeline created this week ($X and X deals)
- ELG-sourced deals advanced or closed this week
- Top 3 partnership overlap opportunities to action this week (highest NVS partner + highest ICP-fit account = highest priority)

Monthly ELG Business Review (for VP Partnerships + CRO):
- ELG-sourced pipeline: created, open, closed-won, closed-lost — with win rates vs. cold-path benchmark
- ELG-accelerated pipeline: deals where ecosystem data shortened cycle — days saved and ARR value of time compression
- Partner NVS leaderboard: top 10 partners by Network Value Score — trending up/down vs. prior month
- Integration depth retention chart: NRR by integration cohort — trend vs. prior quarter
- ELG program efficiency: ecosystem-sourced ARR per partnership headcount FTE

Quarterly Board-Ready ELG ROI Report:
- Ecosystem-sourced ARR as % of total new logo ARR: trend over 4 quarters with forecast for next quarter
- Warm-path advantage proof: win rate table (ELG-sourced vs. cold-path) by segment — the single most compelling board slide
- Ecosystem CAC efficiency: fully-loaded CAC for ELG-sourced deals vs. direct outbound (partner investment allocated proportionally)
- Integration-NRR waterfall: NRR by integration depth cohort — show the revenue protection value of ecosystem stickiness
- Ecosystem investment ROI: total partnership investment (headcount + tools + MDF + co-marketing) / ELG-attributed ARR = Ecosystem Program ROI multiple (benchmark: ≥4:1 for mature programs)

**7. ELG ANALYTICS IMPLEMENTATION ROADMAP**
Provide a 90-day plan to build ELG analytics from scratch or upgrade an existing system:

Days 1–30 (Data Foundation):
- Audit CRM for existing partner-touch data quality — what % of closed-won deals have any partner field populated?
- Configure Crossbeam/Reveal integration: connect CRM and partner CRMs to generate first account overlap report within 14 days
- Define the 6 required ELG fields in CRM (see Section 1) and create a data quality workflow to enforce population at opportunity creation for any deal with partner involvement
- Export trailing 12-month closed-won deals and manually back-fill ELG attribution for any deal with known partner involvement — this creates the historical baseline

Days 31–60 (Attribution Model + Warm-Path Analytics):
- Implement ELG-sourced/accelerated attribution logic in CRM using workflow automation
- Build the warm-path vs. cold-path conversion comparison report using the 12-month backdated dataset
- Configure Crossbeam/Reveal to push "new overlap identified" alerts to Slack and AE CRM task queue — this enables the first ecosystem-triggered outreach campaigns
- Calculate Partner NVS for top 20 partners using trailing 12-month data — share with VP Partnerships and get feedback on face validity

Days 61–90 (Health Scoring + Executive Reporting):
- Deploy integration depth analytics: pull integration activation data from product analytics tool and load into CRM as Ecosystem_Stickiness_Score__c on the Account object
- Build the integration-NRR cohort analysis using the trailing 8 quarters of retention data — prepare the board slide version
- Launch the weekly ELG Pulse Report in Slack (#partnerships-ops) using automated Salesforce report export + Zapier formatter
- Run the first monthly ELG Business Review with CRO and VP Partnerships using the new system — document gaps and calibration adjustments needed

OUTPUT FORMAT:
For each section deliver:
- Specific metric definitions with calculation formulas (SQL-ready where applicable)
- CRM field names and workflow automation logic (Salesforce SOQL or HubSpot list filter syntax)
- Crossbeam/Reveal API or export configuration required (field mapping, sync frequency, alert logic)
- Benchmark ranges from B2B SaaS industry data (e.g., "ELG-sourced deals typically close at 20–35% higher win rates than cold outbound")
- One-paragraph executive summary per section suitable for a CRO or board slide
- Specific red flags to watch for that indicate measurement is broken (e.g., "If >80% of deals classify as ELG-sourced, your attribution model has a false-positive problem")

## Example Input/Output

**Input Example:**

Company: Meridian AI (Series C, $82M ARR, B2B SaaS — AI-powered financial planning platform)
Technology partners: 14 active integrations (Salesforce, NetSuite, Workday, Rippling, Carta, Stripe, and 8 smaller fintech ISVs)
Co-sell partners: 6 (2 Big 4 advisory firms, 2 regional accounting SIs, 2 CFO advisory networks)
Ecosystem tool: Crossbeam (just implemented 3 months ago — have overlap data but no attribution model yet)
CRM: Salesforce
Current ELG visibility: "We know warm intros close faster but have no data to prove it to the board"
Goal: Prove to the board that our $1.8M annual partnerships investment generates ≥4:1 ROI

**Output Example (excerpt from Section 2 — Warm-Path Conversion Analytics):**

**Meridian AI Warm-Path Performance Analysis (Trailing 12 Months — Backdated from Salesforce):**

After retroactively tagging 340 closed opportunities with ELG attribution using Crossbeam overlap data and AE interview confirmation:

| Deal Path | Opportunities | Win Rate | Median Days to Close | Avg ACV | NRR at 12 months |
|---|---|---|---|---|---|
| ELG-Sourced (partner intro first) | 47 | 68% | 71 days | $187K | 118% |
| ELG-Accelerated (overlap used mid-cycle) | 63 | 54% | 89 days | $164K | 114% |
| Direct Cold Outbound | 230 | 31% | 128 days | $142K | 107% |

**Key Findings:**
- ELG-sourced deals close at **2.2x the win rate** of cold outbound (68% vs. 31%) — statistically significant at p<0.001 with n=47 ELG-sourced deals
- ELG-sourced deals close **44% faster** (71 days vs. 128 days) — the sales cycle compression saves approximately 0.7 AE-months per deal
- ELG-sourced deals command a **32% ACV premium** ($187K vs. $142K) — likely explained by partner introductions reaching economic buyers directly vs. SDR cold outreach to lower-level contacts
- NRR advantage: ELG-sourced accounts retain at 118% vs. 107% for cold-sourced — $1.1M in incremental retained ARR attributable to ecosystem-sourced new logos from prior year cohort

**Board Slide (Warm-Path ROI Statement):**
"Deals sourced through our partner ecosystem close at 68% win rate vs. 31% for direct outbound — a 2.2x advantage. At Meridian AI's current volume, if we shift 20% more new logo pipeline to ELG-sourced deals (from 14% to 34% of total), our model projects $6.2M in incremental closed ARR with the same sales headcount, by reducing the average sales cycle from 128 to 87 days and lifting overall win rate from 34% to 41%."

**Workday Integration Partner Deep-Dive (NVS Example):**
- Overlap account volume: 312 accounts in Meridian CRM are also Workday customers
- Overlap ICP quality: 71% of overlapping accounts match Meridian ICP (Series B+ / 200–5,000 employees / finance function decision-maker present)
- Introduction conversion rate: 18 warm intros requested from Workday partner team → 14 meetings scheduled → 11 qualified opportunities = 61% intro-to-opportunity rate (benchmark: 40–60% for Tier 1 tech partners)
- Deal acceleration rate: Deals where Workday provided a warm intro closed in avg 68 days vs. 128-day cold benchmark — 47% faster
- Workday NVS: 87/100 — Tier 1 Strategic Ecosystem Partner
- Recommended action: Assign dedicated Ecosystem Manager to Workday relationship; allocate $120K in co-marketing MDF for joint webinar series targeting CFOs at Workday customers; request reciprocal integration placement in Workday Marketplace

## Success Metrics

- ELG attribution coverage: ≥85% of partner-touched closed-won deals have ELG attribution fields populated within 7 days of close
- Warm-path advantage proof: ELG-sourced win rate is statistically significantly higher than cold-path win rate (p<0.05) with minimum 40 ELG-sourced deals in the sample
- Integration-NRR correlation validated: Accounts with 3+ active integrations demonstrate ≥10 percentage point NRR advantage over 0-integration accounts
- Partner NVS coverage: Network Value Score calculated and updated monthly for ≥80% of active technology and co-sell partners
- ELG pipeline contribution: ecosystem-sourced or accelerated pipeline reaches ≥25% of total new logo pipeline within 12 months of implementing the ELG analytics system
- Board confidence: CRO and CFO validate ELG ROI model without requesting independent audit for 2 consecutive quarterly reviews
- Ecosystem Program ROI: total ELG-attributed ARR / total partnership investment ≥4:1 within 18 months of launch

## Related Prompts

- `../../05_Analytics-&-Performance/Partner-&-Channel-Analytics/AI-Powered-B2B-Channel-Partner-Performance-Analytics-&-Partner-Sourced-Revenue-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Partner-&-Channel-Analytics/AI-Powered-B2B-Technology-Partner-Ecosystem-Analytics-&-Integration-Marketplace-Revenue-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Ecosystem-Led-Growth-ELG-&-Partner-Qualified-Pipeline-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Partner-&-Channel-Marketing/AI-Powered-B2B-Technology-Integration-Ecosystem-Demand-Generation-&-ISV-Partner-Pipeline-Intelligence-Engine.md`

## Integration Tips

- **Crossbeam / Reveal**: Configure Population Sync to push "new overlap identified" alerts to Salesforce as a Task on the matching Account record — set Task Subject to "ELG Overlap Alert: [Partner Name] is a mutual customer" and assign to the Account Owner. Set sync frequency to daily. Create a Salesforce list view "ELG Overlap Accounts — Not Yet Contacted" filtered by (ELG_Overlap_Partner__c IS NOT NULL) AND (No AE Activity in last 30 days) — this becomes the SDR/AE warm-path queue.
- **Salesforce**: Create a custom report type "Opportunities with ELG Attribution" joining Opportunity + Account + Activity objects. Build a pipeline dashboard with 4 views: (1) ELG-sourced vs. cold-path win rate comparison, (2) Average deal velocity by ELG attribution type, (3) Integration depth cohort NRR waterfall, (4) Partner NVS leaderboard. Use Salesforce Flows to auto-populate ELG_Source_Partner__c when a matching Crossbeam overlap alert Task is converted to an opportunity within 60 days.
- **HubSpot**: Use the Crossbeam HubSpot integration to create a Contact Property "Ecosystem Overlap Partners" (multi-select) populated from Crossbeam population data. Build a HubSpot List: "ELG Priority Prospects" (Ecosystem Overlap Partners IS NOT EMPTY AND Lifecycle Stage = Prospect AND No Activity in 14 days) — enroll in a dedicated ELG-first outreach sequence with partner-reference messaging.
- **Slack**: Configure a #ecosystem-signals Slack channel. Use Crossbeam Slack integration to post automated alerts: "🤝 New ELG Opportunity: [Account Name] is a shared customer of [Partner]. ICP Score: [X/100]. Account Owner: @[AE Name]. Suggested Action: Request intro from [Partner Name] partner manager." Include one-click link to Salesforce account and to the partner's Crossbeam profile.
- **PartnerStack**: For referral and affiliate partners, use PartnerStack's attribution API to pull partner-referred leads into Salesforce with UTM tracking. Map PartnerStack Partner_ID to Salesforce ELG_Source_Partner__c field. Track PartnerStack-referred leads through the full funnel separately from Crossbeam overlap-sourced leads — these are distinct ELG motions with different conversion profiles.
- **Tableau / Looker**: Build the ELG Revenue Intelligence Dashboard with five panels: (1) Warm-path win rate trend vs. cold-path — rolling 4-quarter chart, (2) Partner NVS heatmap — all active partners in a grid colored by NVS tier, (3) Integration depth NRR cohort waterfall, (4) ELG pipeline contribution as % of total — monthly trend with forecast, (5) Ecosystem ROI summary — ELG-attributed ARR vs. total partnership program cost.
- **Gong / Chorus**: Tag all sales calls where a partner contact was present or where the AE references a partner relationship as "ELG-Assisted Call." Build a Gong tracker: calls with topic "partner" or "introduction" or competitor's name (for displacement ELG plays) + partner contact on attendee list → auto-tag as ELG-Assisted. Export weekly ELG-assisted call list to Salesforce to populate ELG_Acceleration_Date__c on affected opportunities.

## Troubleshooting

**Problem: Crossbeam overlap data shows 400+ overlap accounts but only 12 have been worked as ELG opportunities — AEs aren't acting on the data.**
Solution: The failure mode is prioritization paralysis — 400 accounts with no ranking feels overwhelming. Fix: build an ELG Priority Score for each overlap account = (Partner NVS × 0.4) + (Account ICP Fit Score × 0.4) + (Days Since Last AE Activity × 0.2, inverted so inactive accounts score higher). Surface only the top 10 ELG opportunities per AE per week in a Salesforce list view — not the full list. Pair with a Slack alert to the AE's direct manager when a top-10 ELG account has had no activity in 14 days, so management reinforces the behavior. Target: reduce the overlap-to-worked ratio from 3% to ≥25% within 90 days.

**Problem: AEs resist updating ELG attribution fields — they don't want to share deal credit with partners.**
Solution: This is a structural incentive conflict, not a training problem. Reframe ELG attribution as a sales tool, not a partner credit mechanism: show the AE their own data — their warm-path win rate (from the retroactive tagging exercise) vs. their cold-path win rate. When AEs see that their own ELG-sourced deals close at 2x the rate, attribution compliance follows naturally. Additionally: make ELG field population a condition for requesting partner introductions — AEs must log the opportunity before submitting an intro request via the #ecosystem-signals Slack channel. This creates a natural gate that drives data quality without managerial enforcement.

**Problem: The integration-NRR correlation looks strong in aggregate but the CFO questions whether it's causation or selection bias (i.e., better customers simply adopt more integrations).**
Solution: This is a legitimate statistical challenge. Conduct a propensity score matching analysis: match integration-adopting accounts to non-adopting accounts with identical ICP scores, ACV, industry, and company size. If NRR advantage persists after matching, it is more likely causal. Alternatively, run a time-series analysis: for the same accounts, compare NRR before vs. after integration activation — if NRR improves in the period after activation, the causal direction is supported. Present both the aggregate correlation AND the matched analysis in the board deck — the CFO's objection, if addressed proactively, becomes a credibility signal rather than a vulnerability.

## Version History
- v1.0: Initial creation (auto-generated)
