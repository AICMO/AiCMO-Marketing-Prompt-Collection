# AI-Powered AI Search Traffic Attribution & Dark Funnel Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** geo, ai-search, attribution, dark-funnel, revenue-analytics, ga4, conversion-analytics, b2b, b2c

## Overview
Tracks, segments, and attributes revenue to AI search referral traffic from ChatGPT, Perplexity, Claude, Gemini, and Copilot — then quantifies the dark funnel influence of AI answers that drive demand without a click. Use this when you need to prove GEO ROI to your CFO, optimize your conversion funnel for AI-referred buyers, and measure whether your GEO investments are translating to pipeline and revenue.

## Quick Copy-Paste Version

You are a senior marketing analytics consultant specializing in AI search attribution. I need to build a complete measurement framework for revenue generated through AI search channels (ChatGPT, Perplexity, Claude, Gemini, Copilot, Bing AI).

My company: [Company Name] — [one-line description, e.g., "B2B project management SaaS for engineering teams at Series A-C companies"]
Analytics stack: [GA4 + CRM, e.g., HubSpot or Salesforce + data warehouse]
Monthly website traffic: [X visitors/month]
Key conversion goals: [e.g., free trial signup, demo request, contact form]

Deliver the following:

1. AI SEARCH TRAFFIC IDENTIFICATION PROTOCOL
   Build a complete taxonomy of AI search referral sources to tag in GA4:
   - Direct referral domains: chatgpt.com, perplexity.ai, claude.ai, gemini.google.com, copilot.microsoft.com, you.com, phind.com, brave.com/search
   - URL parameter signatures that indicate AI-assisted search (e.g., Bing AI referral params)
   - GA4 channel grouping rules to create an "AI Search" channel distinct from "Organic Search" and "Referral"
   - Custom dimension setup: AI_Model (ChatGPT/Perplexity/Claude/Gemini/Other), AI_Query_Type (recommendation/comparison/how-to/unknown)

2. DARK FUNNEL AI INFLUENCE MEASUREMENT
   Design a methodology to measure AI search demand that doesn't produce a direct click:
   - Brand search lift analysis: correlate GEO content investments with increases in branded organic search volume (controls for seasonality, paid brand, PR)
   - Direct traffic cohort analysis: identify "AI-influenced direct" visitors using behavioral fingerprinting (landing page, session behavior, conversion patterns)
   - Survey-based attribution prompt for post-conversion forms: "How did you first hear about us?" with AI search options
   - A/B hold-out experiment design: pause GEO content production for 60 days in test cohort, measure brand search and direct traffic delta

3. AI SEARCH CONVERSION FUNNEL ANALYSIS
   Compare performance metrics for AI Search traffic vs. Organic Search vs. Direct:
   - Landing page distribution (which pages do AI-referred visitors enter on? What does that signal about query intent?)
   - Engagement quality metrics: time on site, pages per session, scroll depth, feature page visits
   - Conversion rate by funnel stage: session-to-lead, lead-to-MQL, MQL-to-opportunity (pull from CRM)
   - Average contract value and sales cycle length for AI-referred vs. other channels
   - Time-to-convert: do AI search visitors convert faster because they arrive pre-educated?

4. REVENUE ATTRIBUTION MODEL FOR GEO
   Build a multi-touch attribution framework that credits AI search appropriately:
   - First-touch AI attribution: deals where AI search was the first recorded touchpoint
   - AI-assist attribution: deals where AI search appeared in the touchpath but was not first or last touch
   - Halo effect calculation: revenue lift in other channels following GEO content investments (measure with geo holdout or time-series analysis)
   - Incremental revenue formula: (AI-referred conversion rate × AI-referred traffic × ACV) + (Dark funnel coefficient × brand search lift × organic conversion rate × ACV)

5. GEO ROI DASHBOARD
   Produce a template for a monthly executive report with these metrics:
   - AI Search Channel Revenue (direct attribution): $X pipeline, $X closed-won
   - AI Search Influence Revenue (multi-touch): $X pipeline influenced
   - Estimated Dark Funnel Revenue (modeled): $X based on brand search lift methodology
   - AI Search CAC vs. Organic Search CAC vs. Paid Search CAC
   - GEO Content Investment ROI: (Total attributed + influenced revenue) / (Content production cost + tooling cost)

Output a complete analytics implementation guide including GA4 configuration steps, CRM field mappings, a sample dashboard layout with metric definitions, and an executive narrative template to present GEO ROI to the CMO and CFO.

## Advanced Customizable Version

ROLE: You are a VP of Marketing Analytics with 12+ years in attribution modeling, marketing mix measurement, and revenue operations. You have built measurement frameworks for companies transitioning from traditional search to AI-first buyer journeys. You understand the technical implementation in GA4, Segment, HubSpot, Salesforce, and Snowflake/BigQuery — and you can translate complex measurement methodology into executive-ready narratives.

CONTEXT:
Company: [COMPANY_NAME]
Business Model: [B2B SaaS ARR: $X | B2C subscription: $X | D2C e-commerce GMV: $X]
Analytics Stack: [GA4 / Segment / Mixpanel] + [HubSpot / Salesforce] + [Snowflake / BigQuery / Redshift]
Monthly Traffic Volume: [X sessions/month] | AI Search Current Share: [estimate or "unknown"]
GEO Content Investment to Date: [e.g., "$50K in structured data markup, 30 AI-optimized articles, 500 G2 reviews solicited over 6 months"]
Current Attribution Model: [Last-touch / first-touch / linear MTA / data-driven]
Primary Conversion Events: [e.g., "Demo Request (CRM: New Lead), Free Trial Signup (Product DB: New User), Pricing Page Visit (GA4: key_event)"]
Key Stakeholder: [CMO needs to justify GEO budget to CFO — current board question: "Show me the ROI on AI search investment"]

OBJECTIVES:
Primary: Attribute direct and influenced revenue to AI search channels with statistical confidence
Secondary: Identify conversion rate differences between AI-referred and traditionally-acquired buyers to inform personalization
Tertiary: Build a repeatable monthly measurement cadence that requires <4 hours of analyst time

---

DELIVERABLE 1 — AI SEARCH TRAFFIC TAXONOMY & GA4 IMPLEMENTATION

A) REFERRAL DOMAIN CLASSIFICATION TABLE

Build a complete lookup table of AI search referral sources:

| AI Model | Referral Domain(s) | UTM Parameters (if any) | Channel Grouping Tag | Dark Traffic Signal |
|---|---|---|---|---|
| ChatGPT | chatgpt.com, chat.openai.com | None standard | AI Search - ChatGPT | High (most answers no-click) |
| Perplexity | perplexity.ai | perplexity_source= | AI Search - Perplexity | Medium (often includes citations) |
| Claude | claude.ai | None | AI Search - Claude | High |
| Gemini | gemini.google.com, bard.google.com | None standard | AI Search - Gemini | Medium-High |
| Copilot/Bing AI | copilot.microsoft.com, bing.com (AI answer) | Various | AI Search - Copilot | Low-Medium (Bing passes referrer) |
| You.com | you.com | you_source= | AI Search - You.com | Low |
| Phind | phind.com | None | AI Search - Phind | High |

For each source, specify:
- Google Analytics 4 referral exclusion: should it be excluded? (NO — you want to track it)
- Channel grouping regex: exact regex expression for GA4 channel definition rule
- Session source/medium expected: e.g., "chatgpt.com / referral" vs. "(direct) / (none)"

B) GA4 CONFIGURATION SPECIFICATION

Provide exact implementation steps:

Step 1 — Custom Channel Group (Admin > Data Display > Channel Groups > Create New):
Channel Name: AI Search
Condition Set 1: Session source matches regex: chatgpt\.com|chat\.openai\.com|perplexity\.ai|claude\.ai|gemini\.google\.com|copilot\.microsoft\.com|you\.com|phind\.com

Step 2 — Custom Dimensions (Admin > Custom Definitions > Create):
Dimension 1: ai_search_model (session-scoped)
  - Populate via GTM: if page_referrer contains "chatgpt.com" → "ChatGPT", if contains "perplexity.ai" → "Perplexity", etc.
  
Dimension 2: ai_traffic_flag (session-scoped)  
  - Value: "true" for sessions matching AI Search channel, "false" for all others
  
Dimension 3: ai_query_intent (event-scoped, manual tagging via UTM when linking from AI-optimized content)
  - Values: recommendation | comparison | how-to | problem-solution | brand-research

Step 3 — Audience Segments for CRM Sync:
Audience: AI Search Visitors (Last 90 Days)
  - Condition: Session channel group = "AI Search" OR ai_traffic_flag = "true"
  - Membership duration: 90 days
  - Export to: HubSpot/Salesforce via GA4 audience export

Step 4 — GTM Dark Funnel Detection Tag:
// Fire on page load — detect AI browser signals
// Check if Perplexity browser extension is active (look for perplexity-extension in navigator)
// Check referrer within session for AI domains even if session restarted
// Push custom event: ai_assisted_session when signals present

C) CRM FIELD MAPPING

For HubSpot / Salesforce, add these fields on the Contact/Lead record:
- `First AI Search Source` (text) — populated via UTM or GA4 audience sync
- `AI Search Touchpoints` (number) — count of sessions from AI search channels
- `AI Search Influence Flag` (boolean) — true if AI search appeared in any touchpath
- `AI Search First Visit Date` (date) — for time-to-close analysis

---

DELIVERABLE 2 — DARK FUNNEL MEASUREMENT METHODOLOGY

The core problem: most AI search influence doesn't produce a trackable click. Design three complementary measurement approaches:

APPROACH A — BRAND SEARCH LIFT REGRESSION MODEL

Hypothesis: Improved GEO content investments increase branded search volume even without direct click attribution.

Methodology:
1. Pull weekly branded keyword search volume from Google Search Console (brand name + brand + product, brand + comparison, brand + review, brand + pricing)
2. Pull weekly GEO content publication dates and investment levels (hours spent, number of articles, review solicitation campaigns)
3. Control variables: seasonality index, paid brand spend (should be held constant or subtracted), PR mentions (from Meltwater/Brandwatch), product launches
4. Run OLS regression or use CausalImpact (Google's Bayesian structural time series) to isolate GEO-driven brand search lift
5. Convert branded search lift to revenue: (lift in branded searches) × (branded search CVR) × (ACV) = Modeled Dark Funnel Revenue

Reporting metric: "For every 100 AI-optimized content assets published, branded search volume increased X% within 90 days (p < 0.05)"

APPROACH B — SELF-REPORTED AI ATTRIBUTION SURVEY

Implementation:
- Add a "How did you first hear about us?" field to your primary lead capture form AND your post-purchase NPS survey
- Options: Google Search | LinkedIn | Word of mouth | AI assistant (ChatGPT/Claude/Perplexity/etc.) | Analyst report | Peer recommendation | Event | Other
- Track this as a CRM field: `First Heard Via AI` (boolean derived from survey response)
- Calculate: AI Self-Reported Attribution Rate = (Leads who say AI) / (Total leads surveyed)
- Cross-reference: Do self-reported AI leads have different ACV, close rate, or sales cycle? This reveals AI buyer quality.

APPROACH C — GEO INVESTMENT HOLD-OUT EXPERIMENT

Design a controlled experiment to measure the true incremental impact of GEO content:
- Test period: 90 days
- Test condition: Pause all new GEO content production (no new AI-optimized articles, no new G2 review solicitations, no new structured data implementations)
- Control condition: Continue GEO investment at current pace
- Geographic split: If you operate nationally, split test/control by DMA or country
- Measure: Difference in AI search traffic, brand search volume, and direct traffic between test and control groups
- Expected output: Marginal value of $1 invested in GEO content (incremental revenue per dollar)

---

DELIVERABLE 3 — CONVERSION FUNNEL ANALYSIS FOR AI-REFERRED BUYERS

Segment all new leads/trials by acquisition channel (AI Search, Organic Search, Paid Search, Direct, Referral, Social) and compare:

FUNNEL STAGE COMPARISON TABLE:

| Metric | AI Search | Organic Search | Paid Brand | Paid Non-Brand | Direct |
|---|---|---|---|---|---|
| Session-to-Lead CVR | ? | Baseline | ? | ? | ? |
| Lead-to-MQL Rate | ? | Baseline | ? | ? | ? |
| MQL-to-Opportunity | ? | Baseline | ? | ? | ? |
| Opportunity Win Rate | ? | Baseline | ? | ? | ? |
| Average Contract Value | ? | Baseline | ? | ? | ? |
| Sales Cycle Length (days) | ? | Baseline | ? | ? | ? |
| Time to First Demo Request | ? | Baseline | ? | ? | ? |
| NPS Score at 90 Days | ? | Baseline | ? | ? | ? |

Hypothesis to validate: AI-referred buyers arrive more educated (they've already asked an AI to compare solutions), which should manifest as:
- Higher MQL-to-Opp conversion (they've done the research)
- Shorter sales cycle (fewer discovery sessions needed)
- Equal or higher ACV (they understand value, less discount sensitivity)
- Higher NPS (expectations are well-set by AI answers)

If the data confirms this hypothesis, the business case for GEO investment becomes: "AI search produces higher-quality pipeline at lower cost than comparable paid channels."

LANDING PAGE ENTRY ANALYSIS:
For AI-referred sessions, which pages are they entering on?
- Home page → Indicates brand-aware AI recommendation ("what is X?")
- Pricing page → High-intent, late funnel (AI answered "how much does X cost?")
- Feature-specific page → Mid-funnel use case research
- Blog/resource page → Early funnel education (AI included your content as a citation)
- Comparison page → Actively evaluating (AI recommended your comparison content)

Map entry pages to AI query intent categories and optimize CRO accordingly.

---

DELIVERABLE 4 — REVENUE ATTRIBUTION MODEL

FRAMEWORK: TRIPLE-TRACK AI ATTRIBUTION

Track 1 — Direct Attribution (Highest Confidence):
Formula: AI Search Direct Revenue = (Sessions with AI Search as first AND last touch) × (Lead CVR) × (MQL CVR) × (Opp CVR) × (Win Rate) × (ACV)
Data source: GA4 channel grouping + CRM first/last touch fields
Confidence: High (directly trackable)

Track 2 — Multi-Touch Influence Attribution (Medium Confidence):
Formula: AI Search Influenced Revenue = (Opps where AI Search appears in any touchpath) × (ACV) × (Influence weight coefficient, default 0.35)
The influence weight (0.35) should be calibrated: if AI search appears in 40% of touchpaths but only represents 15% of first-touch revenue, use 0.375 as the weight
Confidence: Medium (requires multi-touch CRM tracking; validate influence weight quarterly)

Track 3 — Modeled Dark Funnel Revenue (Lowest Confidence, Biggest Number):
Formula: Dark Funnel AI Revenue = (Brand search lift attributable to GEO) × (Branded search CVR) × (Win Rate) × (ACV) + (Self-reported AI attribution rate × total lead volume × ACV)
Data source: GSC brand search volume regression + survey data
Confidence: Low-Medium (modeled, not directly measured)

TOTAL GEO REVENUE ESTIMATE:
Report all three tracks separately. Never add them together in the executive report — they measure different things and adding creates double-counting. Present as: "We have high confidence in $X (direct), medium confidence in an additional $Y (influenced), and a modeled estimate of $Z in dark funnel impact."

---

DELIVERABLE 5 — EXECUTIVE DASHBOARD & ROI REPORT TEMPLATE

MONTHLY GEO PERFORMANCE REPORT — [MONTH YEAR]

**SECTION 1: AI SEARCH TRAFFIC PERFORMANCE**
- Total AI Search Sessions: X (MoM change: +X%)
- AI Search by Model: ChatGPT X%, Perplexity X%, Gemini X%, Claude X%, Other X%
- Top AI Search Landing Pages: [Page 1, Page 2, Page 3]
- AI Search Bounce Rate vs. Organic Search Bounce Rate: X% vs. Y%

**SECTION 2: CONVERSION PERFORMANCE**
- AI Search Session-to-Lead CVR: X% (vs. Organic Search X%)
- AI Search Leads Generated: X (MoM: +X%)
- AI Search MQLs: X | MQL Rate: X%
- AI Search Pipeline Created: $X
- AI Search Closed-Won Revenue: $X

**SECTION 3: DARK FUNNEL INTELLIGENCE**
- Brand Search Volume (this month): X queries (MoM: +X%)
- Estimated Brand Search Lift from GEO: +X% (90-day trend)
- Self-Reported "Found via AI" Rate: X% of surveyed leads
- Modeled Dark Funnel Revenue: $X (methodology: brand search lift regression)

**SECTION 4: GEO ROI CALCULATION**
- GEO Investment This Month: $X (content production: $X, tooling: $X, review programs: $X)
- Direct Attributed Revenue: $X | Direct ROI: Xx
- Influenced Revenue (partial credit): $X | Blended ROI: Xx
- Including Modeled Dark Funnel: $X | Full-funnel ROI estimate: Xx

**SECTION 5: INSIGHTS & RECOMMENDED ACTIONS**
1. [Insight 1 with supporting data and specific action]
2. [Insight 2 with supporting data and specific action]
3. [Insight 3 with supporting data and specific action]

CFO NARRATIVE TEMPLATE:
"Our GEO investment of $[X] this quarter generated $[Y] in directly attributed pipeline and $[Z] in closed revenue. AI-referred visitors convert at [X]x the rate of typical organic search visitors and have [X]% shorter sales cycles, indicating they arrive with higher purchase intent. Factoring in modeled dark funnel influence — measured by the [X]% increase in branded search volume following our GEO content investments — we estimate total revenue influence of $[total]. Our blended GEO CAC of $[X] compares favorably to paid search CAC of $[Y], making GEO our [#] highest-ROI acquisition channel."

---

DELIVERABLE 6 — ONGOING MEASUREMENT CADENCE

Weekly (30 min — analyst):
- Pull AI Search sessions and leads from GA4 report
- Log to GEO tracking spreadsheet: sessions, leads, MQLs
- Flag any unusual spikes (product mention in major AI model update?)

Monthly (3 hours — analyst + marketing ops):
- Full funnel report: AI Search channel through closed-won CRM pull
- Brand search lift analysis from GSC
- Survey data compilation from lead forms
- Update GEO ROI dashboard
- Present to CMO + Revenue team

Quarterly (1 day — marketing analytics lead):
- Recalibrate influence weight coefficient for multi-touch attribution
- Update dark funnel regression model with new data points
- Benchmark: pull competitors' estimated AI search visibility (via GEO audit tool)
- Set GEO investment targets for next quarter based on ROI data

---

## Example Input/Output

**Input Example:**

Company: Stackwise — B2B data observability platform for data engineering teams at Series A-C SaaS companies ($50K-$250K ACV)
Stack: GA4 + Salesforce + Snowflake
Monthly traffic: 45,000 sessions/month
Known GEO investment: 24 AI-optimized technical blog posts published over 6 months, 180 G2 reviews solicited, structured data added to 40 product pages
Current attribution model: First-touch (Salesforce Campaign attribution)
CFO question: "We spent $180K on this GEO program. What did it generate?"

**Output Example (excerpt):**

**AI SEARCH TRAFFIC IDENTIFICATION:**
Current GA4 data shows 1,847 sessions/month referencing chatgpt.com, perplexity.ai, and claude.ai — representing 4.1% of total traffic. This is likely underreported by 40-60% due to AI browse sessions that restart as direct traffic.

GA4 Channel Grouping Rule Created:
Channel: AI Search
Condition: session_source matches regex /(chatgpt|openai|perplexity|claude|gemini|copilot|you\.com|phind)/

**CONVERSION FUNNEL FINDINGS:**
AI Search visitors convert to demo request at 4.2% vs. 2.8% for organic search (+50% higher CVR). Average deal size from AI-referred leads: $87K vs. $73K for organic search average. Sales cycle: 34 days vs. 52 days for organic search (35% faster).

**DARK FUNNEL ANALYSIS:**
Branded search volume increased 28% over the 6-month GEO investment period. Controlling for 3 product launches and seasonality using CausalImpact, GEO-attributable brand lift = +18% (95% CI: +11% to +25%). This translates to approximately $340K in modeled dark funnel pipeline.

**GEO ROI SUMMARY:**
- Direct attributed revenue (18 months lookback): $520K closed-won
- Multi-touch influenced: $1.2M pipeline (partial credit: $420K)
- Modeled dark funnel: $340K
- Total GEO investment: $180K
- High-confidence ROI: 2.9x | Full-funnel estimate: 7.1x

**CFO NARRATIVE:**
"The $180K GEO program generated $520K in directly attributable closed revenue at a 2.9x ROI — comparable to our best-performing organic SEO content. AI-referred buyers convert at 50% higher rates with 35% shorter sales cycles, suggesting the GEO program is capturing buyers at a later decision stage than traditional SEO. Including modeled dark funnel influence driven by an 18% brand search lift (statistically significant, p < 0.01), the total revenue influence is estimated at $1.28M, delivering a 7.1x full-funnel ROI."

---

## Success Metrics

- AI Search is correctly classified as its own channel in GA4 (not lumped into "Referral" or "Direct") within 2 weeks of implementation
- AI Search session count grows as a % of total traffic quarter-over-quarter as GEO investments compound
- Statistically significant conversion rate difference identified between AI-referred and organic traffic (with p < 0.05 confidence) within 90 days of tracking
- Executive team can point to a specific dollar figure of revenue attributable to GEO with documented methodology (ends the "faith-based" GEO budget argument)
- Monthly GEO ROI report takes analyst <4 hours to produce after initial setup
- Dark funnel brand search lift regression achieves R² > 0.6 (demonstrates GEO is the primary driver of brand search growth)

---

## Related Prompts

- [`../../05_Analytics-&-Performance/GEO-&-AI-Search-Analytics/AI-Powered-GEO-Performance-Analytics-&-AI-Search-Share-of-Voice-Intelligence-Engine.md`](../../05_Analytics-&-Performance/GEO-&-AI-Search-Analytics/AI-Powered-GEO-Performance-Analytics-&-AI-Search-Share-of-Voice-Intelligence-Engine.md) — Measure share-of-voice and citation frequency across AI models (use this first, then this prompt to measure what happens after the citation)
- [`../../05_Analytics-&-Performance/GEO-&-AI-Search-Analytics/AI-Powered-Multi-Model-Brand-Citation-Analytics-&-GEO-Performance-Intelligence-Engine.md`](../../05_Analytics-&-Performance/GEO-&-AI-Search-Analytics/AI-Powered-Multi-Model-Brand-Citation-Analytics-&-GEO-Performance-Intelligence-Engine.md) — Track citation frequency and quality across AI models (the upstream measurement to this prompt)
- [`../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-Incrementality-Testing-&-Causal-Revenue-Attribution-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-Incrementality-Testing-&-Causal-Revenue-Attribution-Intelligence-Engine.md) — Design geo holdout and causal experiments to validate GEO's incremental revenue contribution
- [`../../03_Content-&-Creative/GEO-AIO-GEN-AI-Optimization/Commercial-Intent-AEO-&-AI-Answer-Visibility-Engine.md`](../../03_Content-&-Creative/GEO-AIO-GEN-AI-Optimization/Commercial-Intent-AEO-&-AI-Answer-Visibility-Engine.md) — Optimize content to appear in AI answers (the upstream investment this prompt helps you measure)

---

## Integration Tips

**Google Analytics 4:**
- Use the GA4 API (via Looker Studio or BigQuery export) to pull AI Search channel data into a centralized revenue dashboard
- Enable BigQuery export in GA4 to join session-level data with CRM opportunity data for full-funnel attribution
- Create GA4 Explorations: "AI Search Funnel" using Steps: session_start → lead_form_submit → demo_booked → (CRM import) → opportunity_created → closed_won

**HubSpot:**
- Map GA4 audience "AI Search Visitors" to HubSpot contact property via Google-HubSpot integration
- Create a HubSpot workflow: if Contact property `first_touch_source` = "AI Search" → add to AI Search Lead Sequence, notify AE with AI-visitor badge on contact record
- Build a HubSpot custom report: "AI Search Channel Pipeline" showing pipeline by source across deal stages

**Salesforce:**
- Add Campaign source "AI Search - [Model]" to Campaign object; sync from GA4 via UTM where possible
- Create Salesforce Report: "AI Search Attribution" — Leads/Contacts with `Lead Source = AI Search` across Opportunity stage funnel
- Use Salesforce Flow to automatically set `AI_Search_Influence__c = true` on Opportunity when any Contact on the Account has `AI Search` in their touchpath history

**Google Looker Studio / Tableau:**
- Build a 3-panel GEO ROI dashboard: (1) AI Search Traffic Trends, (2) Conversion Funnel by Channel Comparison, (3) Revenue Attribution — Direct / Influenced / Modeled
- Refresh daily for traffic, weekly for leads, monthly for revenue attribution

**Zapier / Make:**
- Zap: When GA4 audience "AI Search Visitor" is updated → push to HubSpot → tag lead → notify sales rep via Slack
- Zap: Monthly → pull brand search volume from GSC API → run against GEO spend CSV → post automated ROI calculation to #marketing-analytics Slack channel

---

## Troubleshooting

**Problem: AI search traffic shows up as "Direct" in GA4, not as a referral from chatgpt.com**
Solution: This is expected for a significant portion of AI-generated traffic. ChatGPT and Claude sessions often strip referrer headers for privacy. Implement the GTM tag described in Deliverable 1 to detect browser-level signals (extensions, navigation patterns). Also check GA4's "Session default channel group" for any sessions with page_referrer containing chatgpt.com that may be miscategorized. Add custom channel grouping to catch edge cases where the referrer is present but grouping rules weren't applied.

**Problem: Not enough AI search traffic to achieve statistical significance for conversion rate comparison**
Solution: Pool 90 days of data rather than monthly. If still insufficient (fewer than 200 sessions/month from AI search), use a combined "AI Search + AI-Influenced Direct" segment defined as: sessions where referrer is AI domain OR where branded search clicked within 24 hours of prior brand search spike. As AI traffic grows, the statistical confidence will improve — track monthly sample sizes and set a milestone to retest significance when N > 500 sessions/month.

**Problem: CFO pushes back on "modeled" dark funnel revenue, wants only hard-attributed numbers**
Solution: Present two numbers explicitly: (1) Directly attributed revenue with full data lineage — this is the conservative floor. (2) A statistical estimate for dark funnel with documented methodology and confidence intervals. Frame the modeled number as "directional evidence, not claimed revenue." Then propose running a 90-day GEO hold-out experiment (described in Deliverable 2, Approach C) — this produces causally defensible evidence that resolves the attribution debate permanently. The CFO who wants certainty will usually approve the experiment.

---

## Version History
- v1.0: Initial creation (auto-generated)
