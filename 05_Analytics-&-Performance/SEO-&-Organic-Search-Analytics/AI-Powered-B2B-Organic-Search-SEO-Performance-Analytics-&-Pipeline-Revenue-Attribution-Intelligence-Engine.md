# AI-Powered B2B Organic Search SEO Performance Analytics & Pipeline Revenue Attribution Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-25 min | **Tags:** seo, organic-search, pipeline-attribution, revenue-analytics, google-search-console, keyword-ranking, content-decay, b2b, demand-generation, marketing-analytics

## Overview
This engine builds a complete, AI-automatable analytics system that connects B2B organic search performance — keyword rankings, organic traffic, and content engagement — to pipeline influence and closed revenue. Use it when your CFO demands proof that SEO investment generates pipeline, when your organic traffic is growing but MQL volume is flat, or when you need to prioritize a content refresh roadmap by revenue impact rather than traffic volume.

## Quick Copy-Paste Version

You are a senior B2B SEO analytics strategist who specializes in connecting organic search performance to pipeline and revenue outcomes. Your client is a B2B SaaS company that invests in SEO but struggles to prove ROI to finance leadership.

The company profile:
- Industry: [e.g., HR technology / cybersecurity / data infrastructure SaaS]
- Monthly organic sessions: [e.g., 28,000 sessions/month]
- Target buyer: [e.g., CHRO and VP HR at companies 500–5,000 employees]
- CRM: [HubSpot / Salesforce]
- Average contract value: [e.g., $36,000 ACV]
- Primary attribution problem: [e.g., "Organic traffic is up 40% YoY but we don't know which keyword clusters drive demos — our GA4 shows sessions but HubSpot pipeline has no keyword data"]

Build a complete organic search analytics and pipeline attribution system that includes:

1. KEYWORD-TO-PIPELINE ATTRIBUTION FRAMEWORK: Design a 3-method system to connect Google Search Console keyword data to CRM pipeline records:
   - Method A: UTM + hidden form field protocol — the exact hidden field setup to capture organic landing page URL and keyword intent tier (top-of-funnel, mid-funnel, bottom-of-funnel) in every HubSpot/Salesforce form submission
   - Method B: Content cluster pipeline scoring — how to tag every page in your CMS with a "keyword intent cluster" property and use GA4 landing page reports to build a funnel from organic entry page → MQL → pipeline
   - Method C: Self-reported attribution backup — the exact question to add to demo request forms to capture "How did you find us? → Google search (what were you searching for?)"

2. SEO PERFORMANCE KPI HIERARCHY: Define a three-tier metrics framework:
   - TIER 1 (pipeline-predictive, report weekly): Organic sessions from bottom-of-funnel keyword clusters, organic-sourced demo requests, share of voice on your 20 highest-intent commercial keywords vs. top 3 competitors
   - TIER 2 (content health, review monthly): Pages ranking positions 4–10 that are within striking distance of page-1 with a refresh, content decay rate (pages that lost >20% of clicks in 90 days), crawl error count affecting indexed pages
   - TIER 3 (acknowledge but deprioritize): Total organic sessions (manipulated by brand traffic and informational queries), domain authority score (correlation to pipeline is weak), total keywords ranking (volume without intent segmentation is meaningless)

3. CONTENT DECAY DETECTION & REFRESH PRIORITIZATION: Build a process to identify the highest-ROI refresh opportunities using GSC + GA4 data:
   - The exact GSC query to export all pages that have lost >20% click volume in the last 90 days vs. prior 90 days
   - How to score each decaying page by: (a) historical pipeline contribution, (b) keyword commercial intent score, (c) competitive ranking gap, and (d) estimated traffic recovery from a refresh
   - Output format: A prioritized refresh queue sorted by "revenue recovery potential" — pages with high past pipeline contribution AND recoverable ranking positions get refreshed first

4. ORGANIC SEARCH COMPETITIVE SHARE OF VOICE: Design a weekly share-of-voice tracking system for your 25 most commercially important keywords:
   - How to use Semrush or Ahrefs API + Google Sheets to track weekly ranking positions for [Your Company] and 3 competitors across your target keyword list
   - Calculate "Keyword SOV Score": Your estimated organic clicks ÷ total available organic clicks for each keyword cluster
   - Alert system: When a competitor gains >3 positions on a high-intent keyword, trigger a Slack alert to the SEO team within 24 hours

5. SEO ROI CALCULATION MODEL: Build a defensible ROI formula that a CFO will accept:
   - Input variables: Monthly organic sessions by intent tier, conversion rate from organic to MQL by intent tier, MQL-to-pipeline rate, average ACV, SEO program monthly cost
   - Output: Monthly organic-sourced pipeline value, organic-influenced pipeline value (for assists), and SEO program ROI percentage
   - Include a realistic worked example with specific numbers for your industry segment

6. BOARD-READY SEO REPORTING NARRATIVE: Write a 5-bullet executive summary for a CMO board presentation using finance-friendly language — no "domain authority improvements" or "impressions growth" — only pipeline, revenue, and CAC efficiency metrics.

Output each section with specific frameworks, formulas, and copy-paste-ready structures. Everything must be immediately executable by a marketing analyst with access to Google Search Console, GA4, and a CRM.

## Advanced Customizable Version

ROLE: You are a Principal B2B Marketing Analytics Strategist with 14+ years of experience connecting organic search investment to revenue outcomes in B2B SaaS, enterprise software, and professional services companies. You are an expert in Google Search Console API, GA4 exploration reports, Ahrefs and Semrush enterprise platforms, and CRM attribution architecture (HubSpot and Salesforce). You understand the fundamental attribution challenge in B2B SEO: Google encrypted most keyword data in 2013 (the "(not provided)" problem), making it nearly impossible to pass keyword-level data into CRM deal records — and you know the 4 proxy methods that sophisticated revenue teams use to work around this. You also understand that B2B SEO success is measured in pipeline and revenue quarters in advance — a piece of content ranking #1 today influences a deal that closes in 4–8 months — which creates a reporting lag that finance teams misinterpret as "SEO doesn't work."

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Category: [e.g., enterprise compliance automation SaaS / AI-powered sales intelligence / B2B data enrichment platform]
- Annual Revenue / ARR: [e.g., $22M ARR]
- Average Contract Value: [e.g., $48,000 ACV]
- Sales Cycle Length: [e.g., 3–6 months]
- Primary Buyer Persona: [e.g., Chief Compliance Officer, VP of Revenue Operations, Head of Data Engineering]
- CRM Platform: [HubSpot / Salesforce — specify tier/edition]
- Analytics Stack: [e.g., GA4 + BigQuery / GA4 standard / Adobe Analytics]
- SEO Tooling: [e.g., Ahrefs Teams / Semrush Business / Moz Pro / Google Search Console only]
- CMS Platform: [e.g., WordPress + Yoast / Webflow / Contentful / HubSpot CMS]
- Monthly Organic Sessions: [e.g., 34,000 sessions/month]
- Estimated Organic Traffic Value (Ahrefs): [e.g., $85,000/month equivalent]
- Organic Search Share of Leads: [e.g., "organic generates ~18% of MQLs but we've never formally measured pipeline attribution"]
- Top 5 Organic Landing Pages by Traffic: [list URLs or page types — e.g., "homepage ranks #3 for brand, two blog posts drive most non-brand traffic, one comparison page drives most demos"]
- Primary SEO Challenge: [Describe specifically — e.g., "Our blog traffic grew 55% YoY but MQL volume from organic is flat. We're spending $18K/month on content and SEO but the CFO is asking for a direct line to revenue. We have no keyword-level pipeline data because GA4 shows (not provided) for 92% of organic sessions."]
- SEO Budget Breakdown: [e.g., "$8K/month content production, $4K/month technical SEO, $3K/month link building, $3K/month tooling and agency management"]
- Competitive Context: [e.g., "We compete with two well-funded category leaders (both have 10x our domain authority) and 3 niche point solutions. We're winning on long-tail commercial intent keywords but losing on head terms."]

---

PHASE 1: ORGANIC SEARCH ATTRIBUTION ARCHITECTURE

1.1 THE "(NOT PROVIDED)" ATTRIBUTION PROBLEM — DIAGNOSIS AND WORKAROUNDS

Diagnose the keyword attribution gap and implement 4 concurrent proxy methods:

METHOD A — LANDING PAGE INTENT TIER CLASSIFICATION (Foundation Layer):
- Build a keyword intent taxonomy for your content library with 4 tiers:
  | Tier | Intent Type | Example Keyword Patterns | Pipeline Conversion Rate Expectation |
  |------|-------------|--------------------------|--------------------------------------|
  | T1 — Commercial High Intent | Ready-to-buy evaluation | "[product] pricing", "[product] vs [competitor]", "best [category] software", "[product] demo" | 8–15% organic-to-MQL |
  | T2 — Commercial Mid Intent | Active problem-solution research | "how to [solve specific pain]", "[category] platform", "[use case] solution", "enterprise [category]" | 2–5% organic-to-MQL |
  | T3 — Informational/Educational | Category awareness, early research | "what is [category]", "how does [technology] work", "[industry] best practices" | 0.3–0.8% organic-to-MQL |
  | T4 — Brand/Navigational | Existing audience, brand search | "[company name]", "[product name] login", "[executive name]" | 15–40% organic-to-MQL (but not "new" pipeline) |

- Tag every page in your CMS with its intent tier using a custom metadata field (or CMS custom field). Implement this in [WordPress custom fields / Webflow CMS field / Contentful content type property].

- GA4 landing page segmentation: Create 4 GA4 audience segments filtered by the landing page URL pattern matching each intent tier. Build a GA4 exploration with these segments showing: Sessions → Engaged Sessions → Conversions (form fill) → [HubSpot/Salesforce CRM import]. This becomes your organic funnel by intent tier.

METHOD B — HIDDEN FORM FIELD KEYWORD INTENT CAPTURE:
- Add 3 hidden fields to every conversion form (demo request, content download, contact us):
  | Hidden Field | Data Captured | Source |
  |-------------|---------------|--------|
  | hs_organic_landing_page (HubSpot) / utm_landing_page (Salesforce) | First organic landing page URL | JavaScript sessionStorage: capture first page URL on organic session start, persist through form fill |
  | hs_organic_intent_tier | Intent tier (T1/T2/T3/T4) from CMS tag | Server-side lookup: match landing page URL to CMS intent tier database and pass to form |
  | hs_organic_search_cluster | Content cluster name | Same CMS lookup — e.g., "compliance-automation", "data-pipeline-management" |

- Implementation: Add this JavaScript to your site's <head> to capture the first organic landing page and persist it for the session:
  ```javascript
  // Capture organic landing page for attribution
  if (document.referrer.includes('google.') || document.referrer.includes('bing.') || document.referrer.includes('yahoo.')) {
    if (!sessionStorage.getItem('organic_landing_page')) {
      sessionStorage.setItem('organic_landing_page', window.location.pathname);
    }
  }
  // On form load, populate hidden field
  document.querySelector('input[name="organic_landing_page"]').value = 
    sessionStorage.getItem('organic_landing_page') || 'direct';
  ```
- HubSpot: Map hidden field to a custom contact property "Organic Landing Page" — use this in workflows to auto-tag contacts with organic intent tier when they convert.
- Salesforce: Use a Lead Field "Organic Landing Page" and a Process Builder/Flow that maps landing page URL patterns to a picklist field "Organic Intent Tier" on Lead creation.

METHOD C — GOOGLE SEARCH CONSOLE TO GA4 PIPELINE CORRELATION:
- GSC exports keyword data (actual search queries, clicks, impressions, average position) at the page level. GA4 exports landing page conversion data. Join them on landing page URL to reconstruct a partial keyword picture:
  - Step 1: Export GSC data via Google Search Console API or Looker Studio connector — get top 1,000 queries by page for the last 90 days
  - Step 2: In GA4, export landing page → conversion data for the same period
  - Step 3: JOIN on landing page URL in Google Sheets or BigQuery (if available): 
    ```
    GSC clicks per page × GA4 conversion rate per page = estimated keyword-driven conversions per page
    Then: estimated conversions × MQL-to-pipeline rate × ACV = estimated pipeline per keyword cluster
    ```
  - Step 4: This gives you a "pipeline per keyword cluster" estimate accurate to ±25% — good enough for strategic prioritization, defensible to finance with the assumption methodology documented

METHOD D — SELF-REPORTED ATTRIBUTION CAPTURE:
- Add to every demo request form: "What were you searching for when you found us?" (open text, optional)
- Alternative structured version: "Which topic brought you to [Company Name]?" with options matching your intent tier clusters — e.g., "Automating [specific use case]", "Comparing [Company] to alternatives", "Learning about [category]", "Recommendation from colleague/peer"
- CRM mapping: Store responses in a custom field "Self-Reported SEO Topic" — use this as a quality check on your landing page intent model and to identify keyword gaps (if 20% of respondents say they were searching for a topic you don't rank for, that's your next content investment)

1.2 PIPELINE ATTRIBUTION MODEL ARCHITECTURE
Build a tiered attribution model that synthesizes all 4 methods:

SOURCED PIPELINE (Strongest Signal):
- Criteria: Contact has organic landing page data (Method B) showing a T1 Commercial High Intent page as first touch, AND self-reported attribution confirms organic search (Method D)
- CRM Workflow: When both conditions are true, stamp deal property "SEO Sourced Pipeline" = TRUE and record pipeline value
- Expected coverage: 12–20% of all organic-converted pipeline (the subset with full data integrity)

INFLUENCED PIPELINE (Broader Attribution):
- Criteria: Contact has any organic landing page data (Methods B/C) in their multi-touch history before pipeline creation, regardless of whether organic was first touch
- CRM Workflow: Stamp deal property "SEO Influenced Pipeline" = TRUE for all deals where any touchpoint in contact journey includes organic intent tier T1 or T2
- Expected coverage: 30–55% of all pipeline (reflects organic's role in the multi-touch B2B buying journey)

ESTIMATED PIPELINE (For Board Reporting):
- Methodology: Use Method C correlation (GSC-to-GA4 pipeline estimate) as the third data point, presented as a range
- Report format: "Organic search sourced $[X] in pipeline (verified), influenced $[Y] in pipeline (multi-touch), and we estimate an additional $[Z] in pipeline from content assists not captured by direct attribution (GSC correlation model)"

---

PHASE 2: SEO PERFORMANCE ANALYTICS FRAMEWORK

2.1 METRICS HIERARCHY AND WEEKLY REPORTING CADENCE

TIER 1 — PIPELINE-PREDICTIVE METRICS (Report weekly to CMO, monthly to board):

Metric 1: Organic-Sourced MQL Rate
- Formula: Organic-sourced MQLs ÷ Total organic form conversions
- Target benchmark: T1 intent pages should convert to MQL at 8–18%; if below 8%, investigate page intent alignment (is traffic actually T1 or misclassified as T1?)
- Alert: If organic MQL rate drops >15% week-over-week, investigate for ranking changes on T1 pages, form friction issues, or audience quality shift

Metric 2: Commercial Keyword Share of Voice (SOV)
- Definition: Sum of your estimated organic clicks ÷ sum of total available organic clicks for your 25 most commercially important keywords
- Calculation: For each keyword, use Ahrefs/Semrush to get total monthly search volume and top-10 CTR curve. Estimate your clicks = your ranking position's CTR × search volume. Sum your estimated clicks ÷ sum of all clicks going to positions 1–10 across all 25 keywords.
- Target: Increase commercial keyword SOV by 2–3 percentage points per quarter
- Alert: If any single T1 commercial keyword drops from page 1 to page 2 (positions 11+), trigger an immediate content review

Metric 3: Organic Pipeline Coverage Ratio
- Formula: Organic-influenced pipeline ÷ Total pipeline coverage goal
- Context: If your quarterly pipeline goal is $3M and organic-influenced pipeline is $600K, your organic pipeline coverage is 20%. Compare this to your organic budget as % of total marketing budget — if organic is 25% of budget but only 20% of pipeline, you have an efficiency problem to investigate.

Metric 4: SEO CAC (Customer Acquisition Cost via Organic)
- Formula: Total SEO program monthly cost ÷ Monthly organic-sourced new customers (or new pipeline / win rate)
- Compare against: Paid CAC, total blended CAC, and CAC payback period
- Target: SEO CAC should be 40–70% lower than paid CAC after the first 12 months of investment — this is the compounding advantage of organic

TIER 2 — CONTENT HEALTH METRICS (Review monthly with SEO and content teams):

- Content decay rate: % of indexed pages that lost >20% of organic clicks vs. prior 90-day period (via GSC query export and comparison)
- Keyword ranking velocity: Average position change across tracked keyword set (weekly) — positive = gaining, negative = losing ground
- Click-through rate by average position: Your CTR at each ranking position vs. industry average (benchmark: position 1 = 28–35% CTR; position 3 = 10–14%; position 10 = 1.5–2.5%). If your CTR is below benchmark for your position, titles and meta descriptions need optimization.
- Core Web Vitals pass rate: % of top organic landing pages passing Google's CWV thresholds (LCP <2.5s, INP <200ms, CLS <0.1) — a direct ranking factor and conversion rate driver
- Index coverage ratio: Total indexed pages ÷ total submitted pages — if below 85%, crawl/indexation issues are suppressing your organic reach

TIER 3 — VANITY METRICS (Acknowledge but exclude from executive reporting):
- Total organic sessions (includes branded, navigational, irrelevant geographic traffic — meaningless without intent segmentation)
- Total keywords ranking (5,000 keywords at position 60+ generates zero pipeline)
- Domain Rating/Authority Score (a lagging indicator of link building — has low direct correlation to pipeline in 12-month windows)
- Page 1 keyword count (position 10 and position 1 are radically different; this metric obscures more than it reveals)

2.2 ORGANIC SEARCH ANALYTICS DASHBOARD ARCHITECTURE

Dashboard 1 — Executive SEO Performance (CMO → Board):
- Data sources: Google Search Console (via Looker Studio GSC connector), GA4 (Looker Studio GA4 connector), HubSpot/Salesforce (via native connector or Google Sheets export)
- Widgets:
  - 13-week trend chart: Organic-sourced pipeline $, organic-influenced pipeline $, and total MQLs from organic (three lines on one chart — shows SEO's revenue trajectory)
  - Commercial keyword SOV tracker: Current SOV vs. 3 months ago vs. 12 months ago for your target keyword set, with competitor comparison
  - Pipeline by intent tier table: T1/T2/T3 breakdown of organic sessions, MQLs, and pipeline — identify which tier is over/underperforming
  - SEO CAC vs. Paid CAC comparison: Side-by-side bar chart updated monthly
  - Top 10 organic revenue-generating pages: Ranked by pipeline contribution (not traffic) — this is the key "prove SEO ROI" asset

Dashboard 2 — Content & SEO Operations (SEO team + content team):
- Keyword ranking tracker: Your top 100 tracked keywords with weekly position, estimated traffic, and delta vs. prior week — color coded (green = gained, red = lost, yellow = volatile)
- Content decay alert queue: Pages that have lost >20% of clicks in last 90 days, sorted by historical pipeline contribution — immediate refresh candidates
- Technical health scoreboard: Core Web Vitals status by template type, crawl error count, index coverage ratio — updated weekly via Google Search Console API
- Content pipeline view: Posts in draft/review/published this month, estimated traffic value on publication (based on target keyword search volume × expected CTR at target position)

---

PHASE 3: CONTENT DECAY DETECTION & REFRESH PRIORITIZATION ENGINE

3.1 AUTOMATED DECAY DETECTION PROCESS

Weekly GSC Query Export Protocol:
Step 1: In Google Search Console → Performance → Search Results
  - Date range: Last 90 days (comparison: Previous period — same range 90 days earlier)
  - Filter: Page → specific page URL patterns (your blog, pillar pages, comparison pages)
  - Export: CSV with columns [Page, Clicks (current), Clicks (prior), % change, Average Position (current), Average Position (prior)]

Step 2: Import to Google Sheets. Add filter: % change < -20% (pages that lost >20% of clicks)

Step 3: Cross-reference with GA4 export (landing page → MQL conversions, last 180 days) to add a "Historical Pipeline Contribution Score" column — join on page URL

Step 4: Add Ahrefs/Semrush ranking data: For each decaying page, what position are you now? What's the #1 ranking competitor? What's the gap in backlinks and content quality?

Decay Root Cause Classification (assign each page to one category):
| Root Cause | Diagnosis Signal | Recommended Action |
|-----------|-----------------|-------------------|
| SERP Feature Displacement | Position unchanged but CTR dropped | Optimize title/meta for featured snippet, add FAQ schema |
| Ranking Loss (Competitor Gains) | Average position dropped >3 positions | Content refresh with depth, add recency signals, build links |
| Freshness Decay (Outdated Stats) | Content >18 months old, topic is time-sensitive | Update statistics, add 2025 data, refresh publish date |
| Algorithm Update Impact | Traffic drop coincides with known Google algorithm update date | Full content quality audit against Google's helpful content guidelines |
| Technical Issue | Index coverage error, Core Web Vitals fail | Fix technical issue first; content quality is secondary |
| Search Intent Shift | Keyword still ranking but user intent evolved | Rewrite to match current SERP intent (e.g., informational intent shifted to commercial) |

3.2 REFRESH PRIORITIZATION SCORING MODEL

Score each decaying page on 4 dimensions (1–5 scale each, max 20 points):

| Dimension | Scoring Criteria |
|-----------|-----------------|
| Historical Pipeline Value (1–5) | 5 = page generated >$200K influenced pipeline in last 12 months; 1 = no pipeline data or <$10K |
| Keyword Commercial Intent (1–5) | 5 = T1 commercial intent (competitor comparison, pricing, demo request path); 1 = T3 informational |
| Ranking Recovery Probability (1–5) | 5 = currently ranking positions 6–15 with clear refresh opportunity; 1 = ranking position 40+ with high competition |
| Traffic Recovery Potential (1–5) | 5 = page had >2,000 monthly clicks before decay; 1 = page had <100 monthly clicks at peak |

Pages scoring 15–20: Immediate refresh (within 2 weeks) — these are revenue recovery priorities
Pages scoring 10–14: Quarterly refresh backlog — schedule in next sprint
Pages scoring <10: Deprioritize or redirect/consolidate with stronger content

---

PHASE 4: COMPETITIVE SEO SHARE OF VOICE INTELLIGENCE

4.1 COMMERCIAL KEYWORD SOV TRACKING SYSTEM

Build a 25-keyword SOV tracker in Google Sheets (updated weekly via Ahrefs or Semrush API):

Keyword Selection Criteria for SOV Tracking Set:
- T1 intent keywords (bottom of funnel): "[Product category] software", "[Use case] platform", "[Category] for [industry]", "[Competitor] alternative", "Best [category] tools", "[Product] pricing"
- T2 intent keywords (mid-funnel): "How to [solve core problem]", "[Industry] [use case] guide", "[Pain point] solutions"
- Include at least 5 branded competitor keywords to track displacement opportunity

SOV Calculation:
For each keyword in the tracking set:
1. Pull current ranking position for [Your Company] and 3 competitors
2. Apply the organic CTR curve to estimate monthly clicks per position:
   Position 1: 28%, Position 2: 15%, Position 3: 11%, Position 4: 8%, 
   Position 5: 7%, Position 6: 5%, Position 7: 4%, Position 8: 3%, 
   Position 9: 2%, Position 10: 2%, Positions 11+: 0.4%
3. Multiply by monthly search volume to get estimated monthly clicks
4. SOV for keyword = Your estimated clicks ÷ Sum of all top-10 estimated clicks
5. Weighted SOV = Average SOV across all keywords, weighted by search volume

Weekly Alert System (via Zapier → Slack):
- Alert 1 (URGENT): Competitor gains >3 positions on any T1 keyword → Slack #seo-alerts: "[Competitor] moved from position [X] to [Y] for '[keyword]' — we are now at position [Z]. This keyword generates an estimated [N] monthly visits. Trigger immediate content review."
- Alert 2 (MONITOR): You gain >3 positions on any tracked keyword → Slack #seo-wins: "Ranking gain: '[keyword]' moved from position [X] to [Y]. Estimated additional monthly visits: [N]. Potential pipeline impact at T[intent tier] conversion rate: $[estimate]."

4.2 COMPETITIVE CONTENT GAP ANALYSIS (Quarterly)
Run a structured competitive content audit every quarter:

For each of your top 3 competitors:
1. Export Ahrefs/Semrush "Content Gap" report: Keywords competitor ranks for in positions 1–20 that you do NOT rank for (or rank below position 20)
2. Filter to: T1 and T2 intent only (using your intent taxonomy), minimum 200 monthly searches, maximum keyword difficulty 60 (for new content creation feasibility)
3. Score each gap keyword by: Search volume × T1/T2 pipeline conversion rate × ACV = estimated annual pipeline value if you captured position 1
4. Prioritize top 10 gap keywords by estimated pipeline value for new content creation

---

PHASE 5: SEO ROI MODEL AND BOARD REPORTING NARRATIVE

5.1 SEO PROGRAM ROI CALCULATION

INPUTS (collect monthly):
- Organic-sourced MQLs: [number] (from HubSpot/Salesforce, filtered by organic source + T1/T2 landing page)
- Organic-influenced pipeline: $[amount] (deals where any organic touchpoint appears in pre-pipeline history)
- MQL-to-pipeline rate (organic channel): [%] (benchmark: 18–28% for well-qualified organic MQLs)
- Pipeline-to-close rate: [%] (your company's blended win rate)
- Average contract value: $[ACV]
- SEO program total monthly cost: $[amount] (content + technical + link building + tooling + team time)

CALCULATION MODEL:
Organic-sourced pipeline = Organic MQLs × MQL-to-pipeline rate × ACV
Example: 45 MQLs × 22% pipeline rate × $48,000 ACV = $475,200 in organic-sourced pipeline

Organic-attributed revenue (monthly, at win rate) = Organic pipeline × Win rate
Example: $475,200 × 24% win rate = $114,048 organic revenue/month

SEO ROI = (Organic revenue / SEO cost) - 1
Example: ($114,048 / $18,000) - 1 = 5.3x ROI (533%)

SEO CAC = SEO cost / Organic new customers
Example: $18,000 / (45 MQLs × 22% × 24%) = $18,000 / 2.4 customers = $7,500 SEO CAC
vs. Paid CAC benchmark: $18,000–32,000 for equivalent B2B SaaS companies

IMPORTANT CAVEATS FOR FINANCE PRESENTATION:
- SEO revenue attribution has a 4–8 month lag (organic content published today closes deals 4–8 months from now) — present trailing 12-month performance, not current month
- Use "organic-influenced" pipeline as the primary metric (broader, more defensible) and "organic-sourced" as the conservative floor
- Present SEO ROI as a range using conservative (sourced only) and optimistic (influenced) methodologies

5.2 BOARD-READY SEO NARRATIVE (5 bullets, CFO language)

Write the exact 5-bullet narrative for a board slide titled "Organic Search: Pipeline Contribution & Efficiency ROI":

• "[Quarter] organic search generated [N] MQLs representing $[X]M in sourced pipeline (confirmed via landing page attribution) and influenced an estimated $[Y]M in additional pipeline across [N] closed/won deals where organic touchpoints appeared in the buying journey."

• "Our commercial keyword share of voice increased from [X]% to [Y]% this quarter — we now rank page 1 for [N] of our 25 highest-intent commercial keywords vs. [N-4] last quarter. Each percentage point of SOV gained represents an estimated $[X]K in incremental monthly pipeline based on current conversion rates."

• "Organic search CAC of $[X] is [Z]x lower than our paid acquisition CAC of $[Y] and continues to improve as our content library compounds — organic sessions grew [X]% while program costs grew only [Y]%, improving efficiency by [Z]% YoY."

• "We identified [N] high-value content decay opportunities (pages that previously drove pipeline but lost >20% of traffic) and refreshed [N] pages this quarter, recovering an estimated [N,000] monthly sessions and $[X]K/month in pipeline opportunity value."

• "Recommended: Increase SEO program investment from $[current] to $[proposed]/month — content gap analysis identifies [N] unranked commercial keywords where competitors rank page 1 and we rank page 3+, representing an estimated $[X]M in annual pipeline opportunity if captured over the next 4 quarters."

---

PHASE 6: AUTOMATION & CONTINUOUS MONITORING STACK

6.1 WEEKLY AUTOMATION WORKFLOW (No-Code/Low-Code)

Automation 1 — GSC Weekly Performance Pull (Looker Studio + Sheets):
- Connect Google Search Console to Looker Studio (free GSC connector)
- Schedule weekly automated email report delivery to CMO and SEO team every Monday 7AM: Key metrics — clicks, impressions, average position for T1/T2 keyword clusters vs. prior week, plus top 5 ranking gains and losses

Automation 2 — Decay Detection Alert (Google Sheets + Apps Script):
- Weekly Google Sheets Apps Script that runs the decay detection query (pages losing >20% clicks), scores pages against the prioritization model, and sends a Slack message to #seo-queue with the top 5 refresh priorities and their estimated pipeline recovery value

Automation 3 — CRM SEO Attribution Workflow (HubSpot/Salesforce):
- HubSpot Workflow: When a contact converts with organic_intent_tier = "T1" and no existing pipeline is associated, auto-create a task for the AE: "Organic T1 Lead: [Contact Name] from [Company] converted via '[landing_page_url]' — researching [cluster topic]. Recommend outreach within 24 hours."
- Salesforce Process Builder: When Lead Source = "Organic Search" AND Organic_Intent_Tier__c = "T1", auto-enroll in a 3-step outbound sequence with personalized messaging based on the content cluster they engaged with

Automation 4 — Monthly SEO Pipeline Report (Google Sheets → Email):
- Make.com or Zapier scenario: First Monday of every month, pull HubSpot/Salesforce organic-sourced pipeline data via API, update the master SEO ROI Google Sheet, auto-generate the board-ready summary table, and email to CMO and CFO with the 5-bullet narrative pre-populated with current month's numbers

OUTPUT FORMAT:
For each phase, deliver:
1. Specific framework, formula, or process with exact fields/queries/thresholds
2. Tool recommendation with cost tier (free / <$500/month / enterprise) and implementation time estimate
3. One "quick win" action executable in under 2 hours with no engineering support
4. The most common mistake teams make with this component and how to avoid it

## Example Input/Output

**Input Example:**
Company: Vantage Compliance — B2B compliance automation SaaS for financial services, $14M ARR, ACV $42,000, 5-month sales cycle
Monthly organic sessions: 22,000 (60% blog, 25% comparison/commercial pages, 15% branded)
CRM: HubSpot Professional
SEO tooling: Ahrefs Teams + Google Search Console
Primary challenge: "Our blog traffic is up 45% YoY but organic MQL volume is flat at ~28 MQLs/month. Finance wants to know why we're spending $15K/month on content with no visible pipeline impact. We have zero keyword-level data in HubSpot — everything organic shows as 'organic search' source with no intent information."
Top competitors: ComplianceNext (DR 72), RegTrack (DR 58) — both outrank Vantage on head terms

**Output Example (excerpts):**

*Phase 1 — Attribution Architecture:*
"Vantage's flat MQL problem is almost certainly an intent misalignment issue. Your 45% traffic growth is coming from informational/T3 content (compliance education posts) while your T1 commercial pages (the '/financial-services-compliance-software' page and '/vs-compliancenext' comparison) are either not being produced or not ranking. Immediate action: Build the landing page intent tier audit by exporting your top 100 organic landing pages from GA4 and manually classifying each as T1/T2/T3. I predict you'll find >80% of your organic traffic is T3 (educational) and <5% is T1 (commercial). That's a content strategy problem, not an SEO problem.

For attribution recovery: Implement the hidden form field capture (Method B) this week — zero engineering required for HubSpot forms. In 30 days, you'll have intent tier data on every new organic conversion. Then run the 90-day GSC-to-GA4 correlation (Method C) to retroactively estimate which existing content clusters have historically driven pipeline, even without keyword-level data. My estimate: Vantage's '/financial-regulatory-compliance-checklist' guide (your highest-traffic non-brand page at 3,200 sessions/month) likely influenced 4–8 closed deals in the last 12 months based on conversion rate benchmarks — you just can't see it in HubSpot yet."

*Phase 3 — Content Decay Detection:*
"Running the GSC 90-day comparison query for Vantage, I identified 14 pages with >20% click decline. Top 3 refresh priorities by pipeline recovery score:

1. '/sec-reporting-requirements-guide' (Score: 17/20): Previously ranked #4, now #9 for 'SEC reporting requirements software' (T1, 2,400 monthly searches). Lost 38% of clicks in 90 days. Root cause: ComplianceNext published a more comprehensive guide in February 2025. Recovery action: Expand from 1,800 to 3,500 words, add 2025 SEC rule updates, include comparison table vs. manual process, add 3 customer quotes. Estimated pipeline recovery: $85K/month in influenced pipeline at T1 conversion rates.

2. '/bank-secrecy-act-compliance-checklist' (Score: 15/20): High past pipeline contribution (13 deal assists in last 12 months), now losing ranking on mobile due to CWV failure (LCP: 4.2s). Fix Core Web Vitals first (2 hours of engineering time), then add 2025 BSA regulatory updates. Estimated pipeline recovery: $60K/month."

*Phase 5 — ROI Model:*
"Vantage SEO ROI calculation (current state):
- Organic MQLs/month: 28 (from HubSpot organic source)
- MQL-to-pipeline rate (organic, estimated): 20%
- Organic pipeline/month: 28 × 20% × $42,000 = $235,200
- Revenue attribution (at 22% win rate): $51,744/month
- SEO CAC: $15,000 cost ÷ 28 × 20% × 22% = $15,000 ÷ 1.2 customers = $12,500
- Paid social CAC (comparison): $28,000 (HubSpot reporting)
- Current SEO ROI: $51,744 ÷ $15,000 = 3.4x (245%)

Projected state (12 months, if T1 content gap is addressed):
- Organic T1 sessions grow from 1,100 to 3,500/month (based on ranking target keywords)
- MQL volume: 45–55/month
- Revenue attribution: $82,000–$100,000/month
- SEO ROI: 5.5–6.7x

Board recommendation language: 'Current SEO program delivers $51K/month in attributed revenue on $15K/month investment (3.4x ROI, $12,500 SEO CAC vs. $28,000 paid CAC). Targeting $85K–100K/month in attributed revenue within 12 months by resolving T1 commercial content gaps identified in the keyword SOV analysis — requires $3K/month incremental content investment.'"

## Success Metrics

- **Attribution coverage rate**: Within 90 days of implementing the hidden form field capture, >65% of new organic MQLs should have intent tier classification in your CRM
- **T1 keyword SOV improvement**: Commercial keyword share of voice should increase by a minimum of 2 percentage points per quarter
- **Content decay recovery**: Refreshed pages should recover to within 15% of their peak click volume within 60 days of refresh publication
- **SEO pipeline coverage ratio**: Organic-influenced pipeline should represent at least the same percentage of total pipeline as the SEO budget represents of total marketing spend — if SEO is 20% of budget, organic should influence at least 20% of pipeline
- **Board narrative acceptance**: Finance team accepts the SEO attribution methodology and approves budget based on documented ROI range — success means moving from "we believe SEO works" to "here's the tiered attribution model and its assumptions"
- **SEO CAC trajectory**: SEO CAC should decline by 15–25% year-over-year as content compounds and traffic volume grows without proportional cost increases

## Related Prompts

- `../../03_Content-&-Creative/Blog-&-Article-Writing/AI-Powered-Pain-Point-SEO-&-Buyer-Intent-Content-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/GEO-&-AI-Search-Analytics/AI-Powered-GEO-Performance-Analytics-&-AI-Search-Share-of-Voice-Intelligence-Engine.md`
- `../../03_Content-&-Creative/Reporting-&-Analytics/Content-Decay-Detection-&-Strategic-Refresh-Intelligence-Engine.md`

## Integration Tips

- **Google Search Console + Looker Studio**: The free GSC Looker Studio connector gives you a fully automated weekly dashboard — connect GSC + GA4 + a Google Sheet (for CRM pipeline data exported weekly) in a single Looker Studio report. Build the commercial keyword SOV and organic pipeline trend charts in 3 hours with no engineering.
- **HubSpot**: Create 4 custom contact properties: "Organic Landing Page", "Organic Intent Tier" (T1/T2/T3/T4 picklist), "Organic Content Cluster" (text), and "Organic Pipeline Flag" (checkbox). Build a workflow that auto-populates intent tier and cluster from landing page URL using regex matching. Create a custom report: Deals where Organic Pipeline Flag = TRUE, grouped by Original Source = Organic Search — this is your SEO pipeline dashboard.
- **Salesforce**: Use a Campaign with Type "Organic Search" and sub-types for each intent tier. Create Campaign Members for each contact who converts via organic intent tier T1/T2. Build a Campaign Influence report that shows organic campaign contribution to Opportunity pipeline — use the "Even Distribution" attribution model as your conservative baseline.
- **Ahrefs/Semrush**: Use the API (available on Ahrefs Teams at $399/month or Semrush Business at $449/month) to auto-pull weekly keyword rankings into Google Sheets via a Google Apps Script API call. This eliminates manual rank checking and enables the automated SOV calculation and alert system.
- **Clay.com**: For high-intent organic visitors (identified via Clearbit Reveal or RB2B to de-anonymize company name from IP), enrich company data and auto-create a CRM task: "[Company Name] had 3+ organic visits to T1 commercial pages this week — assign to AE for intent-based outbound outreach."
- **Slack**: Create a #seo-intelligence channel with three types of automated alerts: (1) weekly top 5 ranking changes, (2) content decay alerts for pages scoring >15 on the prioritization model, (3) competitor ranking gains on T1 keywords. These Slack messages convert SEO from a "monthly report" function to a real-time revenue intelligence signal.

## Troubleshooting

**Problem: GA4 shows 90%+ "(not provided)" for organic search keywords — we can't segment pipeline by keyword despite setting up the attribution system.**
Solution: This is expected and permanent. Google has fully encrypted keyword data for privacy since 2023. The solution is NOT to find a workaround to get keyword data back — it's to use the landing page as your keyword proxy. A visitor landing on your `/enterprise-hr-software-pricing` page was searching for something commercially relevant to that page's target keywords — you don't need the exact query. Build your attribution system around landing page intent tiers (as described in Phase 1) rather than keywords. For the small % of keyword data available in GSC (your own site's data, not per-user), use GSC's Performance Report to validate that your T1 pages are attracting T1-intent queries — this is sufficient for strategy, even without person-level keyword data in your CRM.

**Problem: The content refresh improved rankings and traffic but organic MQL volume didn't increase proportionally — traffic went up 30% but MQLs only increased 8%.**
Solution: Ranking improvement drove traffic from different user intent than expected. Diagnose with 3 checks: (1) Review the actual search queries now driving traffic to the refreshed page in GSC — if new queries are more informational than commercial, the refresh inadvertently shifted the page's intent targeting. (2) Check the conversion form placement and CTA on the refreshed page — if you added more content but didn't add or improve the CTA, visitors read and leave without converting. (3) Audit who is now visiting — use Clearbit or RB2B to sample the companies visiting the page. If the audience profile changed (smaller companies, different industries), the expanded content attracted a different audience than your ICP. Fix: Add a clear commercial CTA (demo request, ROI calculator, or pricing page link) in the first scroll of refreshed content, targeting your ICP explicitly.

**Problem: CFO sees the SEO ROI calculation but says "the 4–8 month attribution lag means you can't really claim this revenue was caused by SEO — it might have come in anyway."**
Solution: Run a controlled experiment to prove causality, not just correlation. Identify 20 keywords where you have page-1 rankings and are generating pipeline. For a 60-day period, intentionally reduce the quality/freshness of 5 of those pages (introduce obvious date staleness signals without removing content). Track whether pipeline from those specific pages declines while your 15 control keywords maintain pipeline flow. Even a 20% decline in the test group is statistically meaningful evidence that organic ranking directly caused pipeline. Present this as "we ran a search ranking experiment that demonstrates causal attribution — not just correlation — between our organic rankings and pipeline generation." Finance teams universally respond better to experimental evidence than correlation-based attribution models.

## Version History
- v1.0: Initial creation (auto-generated)
