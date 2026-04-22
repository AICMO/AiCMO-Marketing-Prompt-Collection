# AI-Powered B2B Search Intent Analytics & Content-to-Pipeline Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** SEO, search intent, pipeline attribution, content intelligence, revenue analytics, B2B

## Overview

This engine classifies your entire organic search query universe by buyer intent stage, maps each intent category to pipeline influence and closed revenue, and surfaces the highest-value content gaps at each stage of the buying journey. Use it when you need to stop optimizing for traffic and start optimizing for revenue — connecting every keyword your buyers type to the pipeline it generates or could generate.

## Quick Copy-Paste Version

You are a B2B revenue intelligence analyst specializing in search intent mapping and organic-to-pipeline attribution.

I will provide you with my organic search data. Analyze it using this framework:

**My inputs:**
- Company: [Your Company] — [brief description of what you sell]
- ICP: [describe your ideal customer profile]
- Top 50 organic search queries by clicks (from Google Search Console): [paste data]
- Pages with highest pipeline influence (from CRM/attribution tool): [paste top 10 URLs with pipeline data]
- Current buyer journey stages: [Awareness / Consideration / Decision — or describe your custom stages]

**Your tasks:**

1. INTENT CLASSIFICATION
   Classify every query into one of these intent stages:
   - Problem Aware (buyer knows they have a problem, not yet solution-aware)
   - Solution Aware (buyer is researching categories/approaches)
   - Product Aware (buyer is evaluating vendors, comparing features)
   - Purchase Ready (buyer is ready to buy, searching for pricing, demos, reviews)
   - Customer/Expansion (existing customers searching for support, advanced features, integrations)
   
   For each query, output: Query | Intent Stage | Buyer Persona (if determinable) | Current Ranking Page | Pipeline Influence Score (High/Med/Low/None)

2. REVENUE GAP ANALYSIS
   Identify the top 5 intent stages or sub-topics where you rank but generate zero pipeline, and explain why (likely content-to-conversion mismatch).
   
   Identify the top 5 high-intent queries where you have NO content or rank below position 10.

3. CONTENT OPPORTUNITY SCORING
   For each content gap, calculate an Opportunity Score:
   Opportunity Score = (Monthly Search Volume × Intent-to-Pipeline Conversion Rate Benchmark × Avg Deal Size) / Estimated Months to Rank
   
   Use these B2B benchmarks if I haven't provided actuals:
   - Problem Aware → Pipeline conversion: 0.5%
   - Solution Aware → Pipeline conversion: 1.5%
   - Product Aware → Pipeline conversion: 3.5%
   - Purchase Ready → Pipeline conversion: 6%

4. CONTENT BRIEFS
   For the top 3 highest-opportunity gaps, write a 200-word content brief including:
   - Target keyword cluster (primary + 5 semantically related)
   - Recommended content format and word count
   - Key sections to include
   - Calls-to-action optimized for the intent stage
   - Internal linking strategy

5. 90-DAY REVENUE PROJECTION
   Based on the opportunity scores, project the incremental pipeline value achievable in 90 days if top 3 content gaps are filled.

Output everything in structured sections with tables where appropriate.

## Advanced Customizable Version

ROLE: You are a senior B2B demand intelligence analyst with deep expertise in search intent mapping, organic-to-pipeline attribution modeling, and content strategy. You operate at the intersection of SEO, revenue operations, and product marketing.

CONTEXT:
Company: [COMPANY_NAME]
Product/Service: [PRODUCT_DESCRIPTION — what it does, for whom, at what price point]
ICP Definition: [Industry | Company Size | Buyer Title | Key Pain Points]
Average Contract Value (ACV): $[X]
Average Sales Cycle: [X weeks/months]
Current MQLs/month from organic: [X]
Pipeline from organic (last 90 days): $[X]

DATA INPUTS (provide all that you have):

A. Google Search Console Data (last 90 days):
[Paste top 100+ queries with: Query | Clicks | Impressions | CTR | Average Position]

B. GA4 Engagement Data:
[Paste top landing pages with: URL | Sessions | Avg Engagement Time | Conversion Events | Goal Completions]

C. CRM Pipeline Attribution:
[Paste pages with known pipeline influence: URL | Opportunities Influenced | Pipeline Value | Won Revenue]

D. Competitor Content Intelligence (optional):
[List 3-5 competitor domains and their top organic pages if known]

ANALYTICAL FRAMEWORK:

PHASE 1 — INTENT TAXONOMY CONSTRUCTION
Build a custom intent taxonomy for [COMPANY_NAME]'s buyer journey:

Map queries to a 5-stage intent model:
Stage 1 — PROBLEM AWARE: Buyer experiencing symptoms, not yet framing as a solvable problem
  Examples for SaaS: "how to reduce customer churn", "why is my MQL to SQL rate low"
  
Stage 2 — SOLUTION AWARE: Buyer researching approaches, categories, methods
  Examples: "best practices for customer success", "demand gen vs lead gen"
  
Stage 3 — PRODUCT AWARE: Buyer evaluating vendors, features, integrations
  Examples: "[Category] software", "[Competitor] alternative", "[Feature] tool"
  
Stage 4 — PURCHASE READY: Buyer near decision, high commercial intent
  Examples: "[Competitor] vs [Our Category]", "[Product] pricing", "[Product] demo", "reviews"

Stage 5 — CUSTOMER/EXPANSION: Post-purchase intent, upsell/cross-sell signals
  Examples: "[Product] integration with [Tool]", "[Advanced Feature] tutorial"

For each query in the dataset:
- Assign intent stage
- Identify likely buyer persona
- Note current ranking page (or flag as "no coverage")
- Apply Pipeline Influence Score from CRM data (if available)
- Flag "Revenue Orphan" if: ranks in top 5 but zero pipeline attribution

PHASE 2 — REVENUE ORPHAN DIAGNOSIS
Identify all "Revenue Orphans" — pages that receive significant traffic but generate no measurable pipeline.

For each Revenue Orphan, diagnose root cause:
□ Content-to-CTA mismatch (wrong offer for intent stage)
□ No clear next step (missing internal links to high-converting pages)
□ Wrong audience attracted (keyword draws non-ICP visitors)
□ Conversion friction (form too long, gated asset too demanding)
□ Trust deficit (no social proof at conversion moment)

Output a Revenue Orphan Fix Plan with specific, implementable recommendations for each page.

PHASE 3 — WHITESPACE OPPORTUNITY MAPPING
Using the intent taxonomy, identify gaps in your coverage:

For each intent stage, answer:
- What % of the market's queries do you currently address?
- What is your average ranking position for queries you do address?
- What are the 5 highest-volume unaddressed queries?
- What is the estimated monthly pipeline value of capturing those queries (use conversion rate benchmarks below)?

Pipeline Conversion Rate Benchmarks by Intent Stage (adjust if you have actuals):
| Intent Stage | Organic Visitor → MQL | MQL → Opportunity | Opportunity → Close |
|---|---|---|---|
| Problem Aware | 0.3% | 8% | 20% |
| Solution Aware | 0.8% | 12% | 22% |
| Product Aware | 2.5% | 18% | 25% |
| Purchase Ready | 5.0% | 28% | 30% |
| Customer/Expansion | 1.5% | 35% | 45% |

Revenue Per Visitor Model:
Revenue Per Visitor = Monthly Search Volume × CTR Estimate × Conversion Rate × ACV × Close Rate

PHASE 4 — CONTENT OPPORTUNITY SCORING MATRIX
Build a prioritized content opportunity matrix:

For each content gap, score on:
1. Revenue Potential (0-10): Based on Revenue Per Visitor model
2. Ranking Difficulty (0-10): Estimated based on competitor domain authority and current SERP composition
3. Time to Rank (months): Estimated based on content type and competition level
4. Strategic Fit (0-10): Alignment with ICP, product narrative, and sales motion
5. Content Production Effort (0-10): Complexity and cost to produce

Opportunity Priority Score = (Revenue Potential × Strategic Fit) / (Ranking Difficulty × Time to Rank × Production Effort)

Output the top 10 content opportunities ranked by Opportunity Priority Score.

PHASE 5 — CONTENT BRIEF GENERATION
For the top 5 ranked opportunities, produce a full content brief:

**Content Brief Template:**
Title: [SEO-optimized title]
Primary Keyword: [target query]
Secondary Keywords: [5-8 semantically related terms]
Intent Stage: [stage]
Target Persona: [title, company size, pain point]
Content Format: [Article / Landing Page / Comparison Page / Tool / Video Script]
Recommended Length: [word count]
Content Structure:
- H1: [recommended headline]
- H2 sections: [list each major section]
- Key arguments/data points to include: [3-5 specifics]
- Competitor differentiation angles: [what to do better]
CTA Strategy:
- Primary CTA: [action + offer, matched to intent stage]
- Secondary CTA: [lower-commitment next step]
- Internal Link Map: [3-5 pages to link to/from]
Success Metrics:
- Target ranking position: [X]
- Target organic CTR: [X%]
- Expected monthly visitors at target position: [X]
- Expected monthly pipeline influence: $[X]

PHASE 6 — 90-DAY EXECUTION ROADMAP
Build a prioritized, week-by-week content execution plan:

Weeks 1-4: Revenue Orphan Optimization (fix existing high-traffic, low-conversion pages)
Weeks 5-8: Purchase-Ready Content (create/improve Product Aware + Purchase Ready gaps)
Weeks 9-12: Solution-Aware Content (build authority for consideration-stage queries)

For each initiative, specify:
- Owner role (SEO, Content, PMM, Web)
- Effort estimate (hours)
- Expected timeline to impact (weeks to ranking improvement)
- Success metric and measurement method

OUTPUT FORMAT:
Produce a complete analysis document with:
1. Executive Summary (5 bullet points, board-ready)
2. Intent Distribution Map (table showing % of queries at each stage)
3. Revenue Orphan Report (table with fix recommendations)
4. Content Opportunity Scorecard (ranked priority matrix)
5. Top 5 Content Briefs (full briefs)
6. 90-Day Roadmap (week-by-week plan)
7. Projected Revenue Impact (90-day and 12-month projection)

CONSTRAINTS:
- All recommendations must be implementable without paid SEO tools (use data I provide)
- Prioritize content that supports both inbound AND sales enablement use cases
- Every recommendation must include a measurable success metric
- Do not recommend content that cannot be produced without subject matter expert input — flag those and suggest interview-based production approach

## Example Input/Output

**Company**: DataBridge — a B2B data integration platform for mid-market financial services companies ($50K ACV, 90-day sales cycle)

**Sample Input Data (abbreviated):**
Top Queries (GSC, last 90 days):
"data integration tools" | 847 clicks | Pos 4.2 | Landing: /blog/data-integration-guide
"best ETL tools for finance" | 312 clicks | Pos 6.8 | Landing: /blog/etl-overview  
"databridge pricing" | 203 clicks | Pos 1.1 | Landing: /pricing
"real-time data sync financial services" | 178 clicks | Pos 8.4 | Landing: /solutions/finance
"data warehouse vs data lake" | 412 clicks | Pos 3.1 | Landing: /blog/warehouse-vs-lake
"fivetran alternative" | 134 clicks | Pos 14.2 | No dedicated page
"how to reduce data pipeline errors" | 201 clicks | Pos 11.5 | No coverage

CRM Attribution (top pages by pipeline influence):
/pricing → $840K pipeline influenced, 28 opps
/solutions/finance → $620K pipeline, 19 opps
/blog/data-integration-guide → $47K pipeline, 3 opps (Revenue Orphan — 847 clicks, only $47K influence)

**Sample Output (abbreviated):**

**Intent Classification Snapshot:**
| Query | Intent Stage | Persona | Pipeline Score |
|---|---|---|---|
| "data integration tools" | Solution Aware | VP Engineering | Low (Revenue Orphan) |
| "best ETL tools for finance" | Product Aware | IT Director — FinServ | Medium |
| "databridge pricing" | Purchase Ready | VP Engineering / Procurement | High |
| "fivetran alternative" | Product Aware | Director of Data Engineering | High (uncaptured — no page) |
| "data warehouse vs data lake" | Problem Aware | Data Analyst | Low |
| "how to reduce data pipeline errors" | Problem Aware | Data Engineer | None (no coverage) |

**Revenue Orphan #1 Fix — `/blog/data-integration-guide`:**
- Problem: 847 clicks/month, only 3 opportunities influenced ($47K). Page ranks #4 for "data integration tools" (Solution Aware intent) but has no conversion path beyond a newsletter signup.
- Fix: Add a mid-content CTA for a "Financial Services Data Integration Checklist" (gated asset), insert comparison table of DataBridge vs. alternatives for financial services, and add internal links to `/solutions/finance` and `/pricing`. Estimated pipeline uplift: +$180K/month at current traffic levels.

**Top Content Gap — "fivetran alternative" (134 clicks, Pos 14.2):**
- Opportunity Score: 9.2/10
- Revenue Per Visitor Model: 134 clicks × 4.5% (Product Aware conversion) × $50K ACV × 25% close rate = $75,375/month at target
- Content Brief: Dedicated comparison page `/fivetran-vs-databridge` targeting financial services data teams. Include: side-by-side feature table, financial services compliance section, customer migration stories, ROI calculator embed. CTA: "See DataBridge vs. Fivetran for Financial Services — Book a Demo."

**90-Day Revenue Projection:**
- Revenue Orphan fixes: +$340K pipeline/month (Weeks 1-4)
- New Product Aware pages: +$180K pipeline/month (Weeks 5-8)
- Solution Aware content: +$65K pipeline/month (Weeks 9-12)
- **Total incremental pipeline (90 days): ~$1.75M**

## Success Metrics

| Metric | Baseline | 30-Day Target | 90-Day Target |
|---|---|---|---|
| Organic-to-MQL conversion rate | Measure current | +15% | +35% |
| Pipeline influenced by organic | Measure current | +10% | +40% |
| Revenue Orphan conversion rate | <0.5% | >1.5% | >3% |
| Rankings for Priority Content Gaps | Not ranking | Top 20 | Top 10 |
| Content Opportunity Coverage Score | Measure at start | +20% | +50% |

**Quality indicators for the analysis output:**
- Every query classified (no "uncategorized" rows)
- Revenue Orphan diagnoses include specific, implementable fixes (not "improve the content")
- Content briefs include word count, structure, and specific data points to include
- 90-day projection uses actual ACV and conversion rate data (or clearly stated benchmarks)

## Related Prompts

- [AI-Powered B2B Organic Search SEO Performance Analytics & Pipeline Revenue Attribution Intelligence Engine](./AI-Powered-B2B-Organic-Search-SEO-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SEO Competitive Gap Analysis & Organic Market Share Capture Intelligence Engine](./AI-Powered-B2B-SEO-Competitive-Gap-Analysis-&-Organic-Market-Share-Capture-Intelligence-Engine.md)
- [B2B Content Asset Attribution & Pipeline Influence Intelligence Engine](../Attribution-&-Revenue-Analytics/B2B-Content-Asset-Attribution-&-Pipeline-Influence-Intelligence-Engine.md)
- [Programmatic SEO Topical Authority Engine](../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/Programmatic-SEO-Topical-Authority-Engine.md)

## Integration Tips

**Google Search Console + GA4 Workflow:**
Export GSC queries via API or manual download (Performance report, last 90 days, max rows). Cross-reference with GA4 landing page data using the shared URL dimension. Feed both exports into this prompt for maximum accuracy.

**HubSpot / Salesforce Attribution:**
Pull a report of all closed-won deals from last 12 months with "First Touch Source" or "Last Touch Source" = Organic. Export the landing pages. This gives you ground-truth data for which pages actually close revenue — override the benchmark conversion rates in Phase 3 with your actuals.

**Zapier / Make Automation:**
Automate monthly intent analysis by: (1) scheduling GSC data export to Google Sheets via Zapier, (2) triggering this prompt via Claude API with the sheet data appended, (3) posting the Revenue Orphan report to a Slack channel for your SEO/content team's weekly review.

**Notion Content Database:**
When content briefs are generated, paste them directly into Notion as new database entries with properties for: Intent Stage, Target Keyword, Opportunity Score, Owner, Status, and Target Publish Date. This creates an intake queue your content team can work from directly.

**Ahrefs / Semrush Enrichment:**
After running this analysis, enrich the top 10 content opportunities with Ahrefs Keyword Difficulty and Semrush CPC data to refine the Ranking Difficulty and Revenue Potential scores in Phase 4.

## Troubleshooting

**Problem: I don't have CRM pipeline attribution data connected to specific pages.**
Fix: Use Google Analytics Goal Completions as a proxy. Set up goals for: demo requests, trial signups, content downloads, and pricing page visits. Run the analysis using GA4 conversion events instead of CRM pipeline. Then after running, manually tag the top 10 converting pages in your CRM as "Organic Influence" to start building historical data.

**Problem: The model assigns wrong intent stages to my industry-specific queries.**
Fix: In the Advanced Version, before pasting your data, add a "Custom Intent Signals" section that defines your company's specific vocabulary. Example: "In our market, 'data lineage' is a Product Aware query (buyers comparing vendors) not a Problem Aware query. Queries containing 'compliance' or 'SOC 2' are always Purchase Ready for our ICP." This pre-training step dramatically improves classification accuracy.

**Problem: Revenue projections seem unrealistically high.**
Fix: Apply a 30% discount to all projections to account for ranking uncertainty, SERP feature competition (AI Overviews, featured snippets), and content production delays. If your actual organic-to-pipeline conversion rate is lower than the benchmarks, override them explicitly: "Use our actual conversion rate of 0.2% for Solution Aware content, not the 0.8% benchmark."

## Version History
- v1.0: Initial creation (auto-generated)
