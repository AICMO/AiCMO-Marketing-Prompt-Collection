# AI-Powered B2B SaaS Account-Based Programmatic Display & CTV Cross-Channel Brand Lift to Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** programmatic-display, connected-tv, account-based-advertising, brand-lift, revenue-attribution, cookieless-measurement, b2b-saas, demand-generation

## Overview
This prompt builds a comprehensive analytics architecture for measuring programmatic display and Connected TV (CTV) advertising performance at the account level — translating brand awareness spend into provable pipeline influence and revenue contribution. Use it when your CFO questions whether upper-funnel programmatic spend is working, when you're migrating to cookieless measurement, or when you need to prove that your CTV investment accelerates deal velocity in target accounts.

## Quick Copy-Paste Version

You are a senior B2B SaaS demand generation and marketing analytics strategist with deep expertise in programmatic advertising measurement, Connected TV analytics, and account-based revenue attribution. You've helped 20+ B2B SaaS companies prove ROI on upper-funnel media spend.

My company context:
- What we sell: [e.g., "AI-powered cybersecurity compliance platform for enterprise companies"]
- ICP: [e.g., "CISOs and VPs of Security at 500-5,000 employee companies in financial services and healthcare"]
- Annual programmatic/CTV budget: [e.g., "$400,000/year across Google DV360, The Trade Desk, and CTV networks"]
- DSP platforms in use: [e.g., "Google DV360 + The Trade Desk"]
- CTV platforms: [e.g., "Hulu, Peacock, programmatic CTV via TTD"]
- ABM/data providers: [e.g., "6sense for account identification, Bombora for intent"]
- CRM: [e.g., "Salesforce"]
- Attribution challenge: [e.g., "Can't connect display impressions to pipeline because cookies are deprecated"]

Please produce:

1. ACCOUNT-LEVEL MEASUREMENT ARCHITECTURE — Design a cookieless account-identification framework that ties programmatic display and CTV impressions to named target accounts. Specify: IP-to-account matching methodology, which data providers to use for identity resolution, how to stitch device graphs across work/home endpoints, and how to handle measurement gaps when deterministic IDs are unavailable. Include confidence scoring for account-level attribution (1-10 scale).

2. BRAND LIFT MEASUREMENT FRAMEWORK — Build a statistically rigorous brand lift study design: control/exposed group methodology, sample size requirements by account tier (Tier 1/2/3), metrics to track (aided awareness, message recall, consideration lift, purchase intent), and measurement cadence. Include a template for running lift studies inside DV360 and The Trade Desk simultaneously.

3. PIPELINE INFLUENCE ATTRIBUTION MODEL — Define the rules for crediting programmatic display/CTV to pipeline and closed-won revenue. Specify: minimum impression threshold for "meaningful exposure," lookback window by sales cycle length, weighted credit model vs. binary exposure credit, how to handle accounts with no CRM activity, and how to present this to a CFO who only believes in last-touch attribution.

4. CROSS-CHANNEL SEQUENCING ANALYTICS — Analyze the optimal sequencing pattern: when display exposure precedes paid search clicks, CTV exposure precedes demo requests, or sequential retargeting flows. Provide SQL query logic or data model schema for tracking cross-channel sequence performance in a CDP or data warehouse. Include frequency optimization thresholds: at what impressions-per-account does incremental reach plateau?

5. CTV-SPECIFIC METRICS & BENCHMARKS — Define KPIs unique to CTV (completion rate, average frequency by daypart, household reach, incremental reach vs. linear TV, co-viewing rate) and B2B-specific CTV benchmarks: expected completion rates for 15s vs. 30s spots, acceptable CPM ranges by audience segment, and how to evaluate OTT publisher quality for B2B audiences.

6. BOARD-READY ROI PROOF FRAMEWORK — Create a one-page executive narrative that quantifies programmatic/CTV contribution: formula for calculating Influenced Pipeline Value, expected halo effect on paid search CVR when display is running vs. dark, estimated brand awareness lift in target accounts, and sensitivity analysis showing what happens to pipeline if display spend is cut by 25%, 50%, or 100%.

Format as a measurement architecture document I can hand to my marketing analytics team and present to my CFO.

## Advanced Customizable Version

ROLE: You are a revenue marketing analytics architect who has built account-based programmatic measurement frameworks at B2B SaaS companies ranging from Series B to post-IPO. You have deep technical expertise in DSP APIs, CDPs, data clean rooms (LiveRamp, Google PAIR, Snowflake Data Clean Room), and cookieless identity resolution. You understand both the media-buying side (DV360, TTD, Amazon DSP) and the analytics side (Salesforce attribution, HubSpot reporting, Looker dashboards). Your north star is connecting brand spend to revenue in a way that CFOs trust and sales leaders respect.

COMPANY CONTEXT:
- Company name: [Company Name]
- Product category: [e.g., "Enterprise contract lifecycle management (CLM) platform"]
- ICP definition:
  - Primary buyer titles: [e.g., "General Counsel, VP Legal, Chief Legal Officer"]
  - Company size: [e.g., "1,000-10,000 employees"]
  - Industry verticals: [e.g., "Technology, financial services, healthcare, manufacturing"]
  - Geography: [e.g., "North America and UK"]
- Current programmatic/CTV setup:
  - DSPs: [e.g., "Google DV360 primary, The Trade Desk for CTV"]
  - Annual programmatic budget: [e.g., "$600,000 display + $200,000 CTV"]
  - Target account list size: [e.g., "2,400 named accounts in Salesforce"]
  - Account tiering: [e.g., "Tier 1: 200 enterprise accounts, Tier 2: 800 mid-market, Tier 3: 1,400 SMB"]
- Identity & data infrastructure:
  - ABM platform: [6sense / Demandbase / Rollworks / other]
  - Intent data providers: [e.g., "Bombora + G2 Buyer Intent"]
  - CDP: [Segment / mParticle / Tealium / none]
  - Data warehouse: [Snowflake / BigQuery / Redshift]
  - Clean room access: [LiveRamp / Google PAIR / Snowflake Collaboration / none]
- CRM/MAP: [Salesforce + Marketo / HubSpot / other]
- Sales cycle length: [e.g., "90-180 days for enterprise, 30-60 days for mid-market"]
- Current attribution challenges:
  - [ ] Cookie deprecation breaking display attribution
  - [ ] No connection between CTV households and B2B accounts
  - [ ] CFO demanding ROAS proof for upper-funnel spend
  - [ ] Inconsistent impression data across DSPs
  - [ ] No baseline to measure brand lift against
  - [ ] Other: [describe]
- Fiscal quarter for board presentation: [e.g., "Q3 FY2026"]

MEASUREMENT ARCHITECTURE OBJECTIVES:
Build a complete, AI-powered analytics system that:
1. Connects programmatic impressions to named accounts without relying on third-party cookies
2. Proves that display + CTV exposure measurably accelerates pipeline velocity and win rates in exposed vs. unexposed accounts
3. Quantifies the halo effect of brand advertising on lower-funnel conversion performance
4. Enables real-time campaign optimization based on account engagement signals, not just click metrics
5. Produces CFO-ready ROI proof that survives scrutiny in a board presentation

SECTION 1: COOKIELESS ACCOUNT-IDENTIFICATION ARCHITECTURE

Design a multi-layer identity resolution system:

Layer 1 — Deterministic Matching:
- IP-to-account mapping: specify primary provider (Clearbit, 6sense, Bombora, DemandBase), expected match rate by company size, refresh cadence, and accuracy SLA
- LinkedIn matched audiences: how to sync target account lists into LinkedIn for cross-platform identity stitching
- First-party login data: if the company has a product or resource portal, how to use authenticated sessions as identity anchors
- Business email hashing: using Google PAIR or LiveRamp RampID to match hashed work emails across publisher inventory

Layer 2 — Probabilistic Matching:
- Device graph methodology: how IP clustering + mobile ad IDs + browser fingerprinting create household-to-company bridges
- Confidence scoring model: assign a confidence score (1-100) to each account-impression match based on signal strength
- Thresholds: define minimum confidence score to count an impression as "account-reached" for attribution purposes

Layer 3 — Measurement Gaps:
- Estimate the % of impressions with no account match (expected: 30-50% for CTV, 15-30% for display)
- Statistical extrapolation model: how to scale attributed reach to estimate total account reach
- Data clean room approach: how to use Snowflake Data Sharing or LiveRamp Clean Room to match DSP impression logs with CRM account data without exposing PII

Deliverable: A data model schema (entity-relationship diagram in plain language) showing how impression data, identity resolution, and CRM account data join in the data warehouse.

SECTION 2: STATISTICALLY RIGOROUS BRAND LIFT STUDY DESIGN

Design a brand lift measurement program that will hold up to statistical scrutiny:

Study Structure:
- Control group design: holdout methodology using geo-based, account-based, or randomized suppression; specify which approach fits the account list size
- Treatment group: minimum impressions required per account to qualify as "meaningfully exposed" (calculate based on ACV and attribution window)
- Sample size calculator: given target account list sizes by tier, calculate statistical power requirements (target: 80% power, 95% confidence interval)

Brand Lift Survey Design:
- Survey delivery mechanism: in-app surveys via DV360 Brand Lift, The Trade Desk's Kantar integration, or Lucid Marketplace
- Question battery for B2B audiences:
  - Unaided brand awareness question
  - Aided brand awareness question
  - Message recall (prompted with ad creative)
  - Category consideration question
  - Purchase intent question
  - Net Promoter Score proxy for brand perception
- Cadence: baseline survey (pre-campaign), in-flight check (4 weeks), post-campaign measurement, 90-day decay study

Account-Tier Lift Targets:
- Tier 1 enterprise accounts: expected aided awareness lift (%) given budget allocation
- Tier 2 mid-market accounts: lift target and minimum budget threshold to achieve statistically significant results
- Tier 3 long-tail: whether brand lift measurement is cost-effective at this tier or should be replaced with proxy metrics

SECTION 3: PIPELINE INFLUENCE ATTRIBUTION MODEL

Define a defensible model for connecting programmatic/CTV exposure to pipeline:

Attribution Rules:
- Minimum exposure threshold: minimum impressions per account to count as "influenced" (recommend 8-15 impressions based on frequency studies, adjusted for ACV)
- Lookback window: define window by sales cycle (e.g., 180 days for 90-day sales cycle; 365 days for enterprise 6-12 month cycles)
- Attribution credit weighting: design a weighted model that gives credit to display/CTV exposure along the buyer journey (e.g., 15% credit if exposure precedes first intent signal, 25% if exposure precedes demo request)

Influenced Pipeline Calculation:
- Formula: [Total Pipeline from Accounts in TAL with ≥N impressions within lookback window] × [Lift in win rate vs. unexposed TAL accounts] = Influenced Pipeline Value
- Control for confounds: how to isolate display/CTV contribution from concurrent paid search, ABM, and outbound SDR activity running on the same accounts
- Incrementality test design: matched-market or geo holdout test to prove incremental pipeline lift

CFO-Ready Proof Points:
- Win rate comparison: exposed accounts (≥threshold impressions) vs. matched unexposed accounts
- Pipeline velocity comparison: days from MQL to SQL, SQL to close for exposed vs. unexposed
- Average deal size comparison: test whether brand-exposed accounts close larger deals
- Cost per influenced opportunity: [Programmatic/CTV spend] ÷ [Number of influenced opportunities]

SECTION 4: CROSS-CHANNEL SEQUENCING ANALYTICS

Build analytics for measuring channel sequence effectiveness:

Sequence Definitions:
- Sequence A: Display exposure → Organic/Direct site visit → Demo request
- Sequence B: CTV exposure → Paid search click → Conversion
- Sequence C: Display exposure → Email open → SDR accepted meeting
- Sequence D: CTV → Display retargeting → Demo request (TV-to-desktop waterfall)

Data Model for Sequence Analytics:
Provide a SQL query structure (BigQuery/Snowflake syntax) that:
1. Joins impression event logs (from DSP API exports) with CRM touchpoint data
2. Sequences events chronologically by account
3. Identifies which sequence patterns produce the highest conversion rates
4. Calculates time-to-conversion by sequence type

Frequency Optimization:
- Optimal frequency analysis: provide methodology for running a frequency response curve analysis — what impression frequency per account per week maximizes conversion probability while minimizing cost?
- Diminishing returns threshold: at what frequency do incremental impressions produce <1% lift in conversion probability?
- Daypart optimization for CTV: morning (6-9am) vs. prime time (8-11pm) vs. weekend performance for B2B audiences by job title vertical

SECTION 5: CTV-SPECIFIC MEASUREMENT & BENCHMARKS

B2B CTV Measurement Architecture:
- Household-to-business matching: methodology for matching CTV household viewing data to target company accounts (ACR data from smart TVs, streaming login data, IP resolution)
- Co-viewing adjustment: estimated co-viewing rate for business-relevant content (news, financial programming) and how it affects reach calculations
- Linear TV vs. CTV incrementality: methodology to prove CTV is reaching accounts not reachable via linear TV buys

CTV KPIs & B2B Benchmarks (2025-2026):
- Video completion rate: target benchmarks by ad length (15s: >85% VCR, 30s: >70% VCR, 60s: >55% VCR)
- CPM ranges by audience quality: broad programmatic ($12-20), premium B2B audience ($25-45), OTT with business targeting ($35-60)
- Account reach targets: % of Tier 1 accounts reached with ≥3 impressions per quarter
- Brand recall lift: expected recall lift from CTV vs. display-only campaigns (CTV typically delivers 2-3x higher unaided recall)
- Publisher quality scoring: framework for evaluating OTT inventory quality (viewability rate, completion rate, brand safety, audience verification)

SECTION 6: REAL-TIME CAMPAIGN OPTIMIZATION ENGINE

Design an AI-powered optimization loop:

Account Engagement Scoring:
- Real-time account signal ingestion: how to pull impression delivery data from DSP APIs into the data warehouse daily/hourly
- Dynamic account score: formula combining (impression frequency) + (intent signal strength) + (website visit recency) + (CRM engagement activity) = Account Engagement Score
- Threshold alerts: trigger SDR outreach when account engagement score crosses a threshold within a 30-day window

Automated Bid Adjustment Rules:
- Increase bids 20-40% for accounts showing high-intent signals on 3rd-party platforms (Bombora surge)
- Shift budget from Tier 3 to Tier 1 accounts when Tier 1 account engagement score drops below baseline
- Suppress impressions for accounts already in active sales cycle (save budget, avoid over-exposure to accounts already engaged with sales)

Creative Fatigue Detection:
- Define creative fatigue threshold: when CTR drops >40% from campaign launch baseline over a 14-day rolling window
- Automated creative rotation trigger: swap creative sets when fatigue detected, A/B test new hooks vs. control

SECTION 7: BOARD-READY ROI PROOF FRAMEWORK

Executive Narrative Structure:

Slide 1 — Investment Summary:
- Total programmatic/CTV investment: $[amount]
- Total target accounts reached: [number] ([%] of TAL)
- Average impressions per account: [number]

Slide 2 — Pipeline Influence Proof:
- Win rate: exposed accounts [X%] vs. unexposed matched accounts [Y%] → [Z%] lift
- Pipeline velocity: [days faster] for exposed accounts to reach SQL stage
- Influenced pipeline created: $[amount] (formula and methodology footnoted)
- Cost per influenced opportunity: $[amount]

Slide 3 — Brand Awareness Lift:
- Aided brand awareness in target accounts: [pre%] → [post%] = [lift%]
- Message recall: [X%] of exposed accounts recall key message
- Purchase consideration: [lift%] among exposed accounts vs. control

Slide 4 — Halo Effect on Performance Channels:
- Paid search CVR during active display/CTV periods vs. dark periods: [X%] higher CVR
- Email open rates for accounts with 8+ display impressions vs. <8 impressions: [X%] difference
- SDR connect rate for accounts with brand exposure vs. cold accounts: [X%] difference

Slide 5 — Scenario Analysis:
- Current state: $[budget] → $[influenced pipeline]
- +25% investment scenario: projected influenced pipeline increase
- -25% budget cut scenario: projected pipeline impact and recovery timeline
- Dark period scenario (0 display/CTV for 90 days): modeling brand equity decay and paid search CVR degradation

Output format: Deliver as a structured measurement architecture document with: (1) executive summary suitable for CMO/CFO review, (2) technical specification for data team implementation, (3) measurement timeline showing when each reporting layer will be operational, and (4) quarterly reporting cadence and format.

## Example Input/Output

**Input Example:**
- Company: Meridian Legal AI (contract intelligence platform for legal teams)
- ICP: Chief Legal Officers and VP Legal Operations at 1,000-5,000 employee companies in technology, financial services, and life sciences
- Budget: $280,000 display + $120,000 CTV annually ($400K total)
- DSPs: DV360 + The Trade Desk
- CTV: Peacock, Hulu, and programmatic CTV via TTD
- ABM platform: 6sense
- Data warehouse: Snowflake
- Target account list: 1,800 named accounts in Salesforce
- CRM: Salesforce + Outreach
- Challenge: CFO demanding proof that $400K in display/CTV is doing anything beyond "making us look big"

**Output Example (abbreviated):**

**Account-Level Measurement Architecture:**

Layer 1 — Deterministic Matching:
- Primary identity provider: 6sense (IP-to-account resolution)
- Expected match rate: Tier 1 enterprise accounts: 78-85% match rate; Tier 2: 60-72%; Tier 3: 45-58%
- Supplement with LinkedIn Matched Audiences sync: upload TAL to LinkedIn, use LinkedIn Insight Tag to build cross-platform identity bridge for accounts with LinkedIn activity
- CRM-to-DSP hash match: export Salesforce account domains → match to DV360 Customer Match and TTD UID2.0 via hashed business email domains

Layer 2 — Probabilistic Gap-Fill:
- Deploy 6sense's intent platform as device graph backbone — already maps IP ranges to company accounts for Meridian's ICP
- Confidence threshold: count impression as "account-reached" if 6sense confidence score ≥65 (deterministic) or ≥40 (probabilistic with volume weight)
- Estimated gap (impressions with no account match): 32% of display, 48% of CTV
- Statistical extrapolation: scale attributed account reach by (1 / match rate) to estimate total TAL reach

**Pipeline Influence Model — Meridian Legal AI Specific:**

Attribution rules:
- Minimum impressions to count: 10 impressions per account within 180-day lookback (based on 90-120 day sales cycle)
- Credit weighting: 10% credit for exposure before any CRM touchpoint; 20% credit for exposure within 30 days of first SDR contact; 30% credit for exposure concurrent with active opportunity

Q2 FY2026 Proof Points (simulated):
- Exposed accounts (≥10 impressions): 847 of 1,800 TAL accounts
- Win rate: exposed accounts 28.4% vs. matched unexposed 21.1% = 34.6% win rate lift
- Influenced pipeline: $12.3M (exposed accounts with open/closed opportunities × win rate lift attribution weight)
- Cost per influenced opportunity: $400,000 ÷ 61 influenced opps = $6,557 per influenced opportunity (vs. $4,200 for SDR-sourced, but 3x larger ACV on display-exposed accounts)

**Brand Lift Study (Q1 FY2026 baseline results):**
- Aided brand awareness among Tier 1 legal operations personas: 31% (pre) → 44% (post) = 42% lift
- Purchase consideration: 18% → 26% = 44% lift
- Message recall ("AI that reads contracts faster than your legal team"): 29% aided recall among exposed accounts

**Halo Effect on Performance Channels:**
- Paid search CVR during display-active months: 4.2% vs. dark months: 2.9% = 45% higher CVR
- SDR connect rate on accounts with ≥8 display impressions: 18% vs. cold accounts: 11% = 64% higher connect rate

**Board Presentation Script (CFO talking points):**
"We spent $400K on programmatic display and CTV to reach 847 of our 1,800 target accounts with meaningful brand exposure. In those exposed accounts, our win rate was 34% higher, our SDR connect rates were 64% better, and our paid search ads converted 45% more efficiently. The influenced pipeline value from those exposed accounts was $12.3M — a 30.75x return on the brand investment. If we cut this budget by 50%, our model shows paid search CVR would drop by approximately 20% within 90 days, costing us an estimated $4.1M in conversion-stage efficiency."

## Success Metrics

**Measurement Quality:**
- Account match rate: >70% of TAL accounts matched to impression data within 30 days of campaign launch
- Statistical confidence: brand lift studies achieve ≥80% statistical power with 95% confidence interval
- Attribution coverage: ≥85% of influenced pipeline opportunities have documented impression data in the data model

**Business Impact Indicators:**
- Win rate lift in exposed vs. unexposed matched accounts: target ≥15% relative lift
- Pipeline velocity improvement: exposed accounts convert from SQL to close ≥10% faster
- Paid search CVR halo effect: >20% higher CVR during display-active periods vs. dark periods
- CFO acceptance: ROI narrative survives 3 rounds of CFO questioning without methodology concessions

**Operational Efficiency:**
- Report latency: account-level impression data available in Snowflake within 48 hours of delivery
- Dashboard refresh: weekly automated pipeline influence report delivered to CMO and CRO
- Creative fatigue alerts: automated Slack notification when creative CTR drops >40% from launch baseline

## Related Prompts
- `../../04_Demand-&-Lead-Generation-&-Growth/Programmatic-Display-&-CTV-Advertising/AI-Powered-B2B-SaaS-Connected-TV-CTV-Account-Based-Advertising-Architecture-&-Streaming-Audience-Pipeline-Revenue-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-SaaS-Marketing-Mix-Modeling-MMM-&-Econometric-Revenue-Attribution-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-Incrementality-Testing-&-Causal-Revenue-Attribution-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Retargeting/AI-Powered-B2B-SaaS-Cross-Channel-Behavioral-Retargeting-&-Intent-Signal-Activation-Revenue-Intelligence-Engine.md`

## Integration Tips

**Google DV360 Integration:**
- Enable DV360 Brand Lift Studies natively within the UI for YouTube and Display campaigns targeting B2B audiences
- Use DV360's Floodlight integration to connect display impressions to Salesforce opportunities via Google Analytics 4 → Salesforce connector or a middleware like Fivetran
- Export DV360 impression logs via BigQuery Transfer Service daily for account-level matching

**The Trade Desk Integration:**
- Use TTD's Unified ID 2.0 (UID2.0) for cookieless identity resolution; sync your CRM email hashes via LiveRamp to TTD for deterministic account matching
- Enable TTD's Koa™ AI for automated bid optimization; feed account engagement signals back as custom audience seeds to prioritize in-market accounts
- TTD's OpenPath for premium direct publisher deals reduces fraud and improves match rates vs. open exchange

**6sense Integration:**
- 6sense Advertising module can serve display ads directly to target accounts with native account-level reporting; use as ground truth for match validation against DV360/TTD
- Sync 6sense account intent scores to Salesforce as a custom field; use this field to segment pipeline reports and prove that brand-exposed + high-intent accounts close faster

**Snowflake Data Clean Room:**
- Set up Snowflake Collaboration with LiveRamp's Data Collaboration platform to match publisher impression data with your CRM account table without exposing raw PII
- Use Snowflake Dynamic Tables to refresh account-level impression aggregations daily

**Salesforce Integration:**
- Create a custom object "Account_Media_Exposure" in Salesforce to store: account ID, total impressions, unique reach dates, DSP source, confidence score, and last impression date
- Build a Salesforce report that compares opportunity win rates and velocity for accounts with Media_Exposure_Count ≥ threshold vs. accounts with 0 exposure
- Feed this report into Tableau or Salesforce Einstein Analytics for CMO/CRO weekly review

**Zapier/Make Automation:**
- Trigger SDR task creation in Outreach or Salesloft when account engagement score crosses threshold in 6sense (6sense → Zapier → Salesforce task creation → Outreach sequence enrollment)
- Automate weekly Slack digest: pull top 25 "high-engagement, low-CRM-activity" accounts from Snowflake → format as Slack message → post to #demand-gen-alerts channel

## Troubleshooting

**Problem: CFO doesn't trust the "influenced pipeline" methodology**
Solution: Run a geo-based holdout test — suppress all programmatic/CTV spend in 2 matched metro areas for 90 days while maintaining full spend in matched control metros. Compare pipeline generated in suppressed vs. control markets, controlling for SDR activity, events, and seasonal variation. This provides causal incrementality evidence that survives scrutiny. Present alongside the correlation analysis, not as a replacement.

**Problem: Account match rate is below 50% on CTV inventory**
Solution: CTV match rates are inherently lower because CTV IP ranges are residential ISPs, not corporate networks. Supplement with: (1) LiveRamp's ATV (Advanced TV) identity graph which connects streaming service login data to business identities, (2) ACR (Automatic Content Recognition) data from smart TV manufacturers which can be matched to business addresses, (3) Extend CTV attribution window to 7 days post-exposure to capture work-to-home device transitions. Accept that CTV measurement will always have higher uncertainty than display and build this caveat into your CFO presentation.

**Problem: DSP impression data doesn't match 6sense account-reached data**
Solution: This discrepancy is normal (expect 20-35% variance). DSPs count impressions by device; 6sense counts by account with their own identity resolution. Reconcile by: (1) using DSP data for frequency/reach metrics, (2) using 6sense for account-level pipeline attribution (their resolution is better for B2B accounts), (3) presenting both data points to the CFO with a clear explanation that they're measuring different things — DSP counts ads served; 6sense counts confirmed business accounts reached.

## Version History
- v1.0: Initial creation (auto-generated)
