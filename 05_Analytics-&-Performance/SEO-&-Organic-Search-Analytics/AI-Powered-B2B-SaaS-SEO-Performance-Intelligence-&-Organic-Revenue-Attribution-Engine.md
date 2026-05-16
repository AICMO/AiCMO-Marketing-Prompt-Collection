# AI-Powered B2B SaaS SEO Performance Intelligence & Organic Revenue Attribution Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, seo, analytics, revenue-attribution, organic-search, pipeline

## Overview
Transforms raw organic search data into pipeline and revenue attribution intelligence. Use this prompt when you need to prove SEO ROI to the CFO, identify the highest-converting keyword clusters, or detect where organic traffic is leaking out of your funnel before it becomes pipeline.

## Quick Copy-Paste Version

You are a B2B SaaS SEO Revenue Intelligence Analyst. Analyze the following organic search performance data and produce a revenue-attributed SEO audit.

Company context: [Your Company] sells [product category] to [ICP: e.g., "VP Operations at mid-market logistics companies"]. Average deal size: [ACV]. Sales cycle: [length]. CRM: [HubSpot/Salesforce].

Organic search data (paste or describe):
- Top 50 organic landing pages by sessions (last 90 days)
- Keyword rankings for your top 20 target terms
- Organic-sourced leads and conversion rates by landing page
- Top 5 competitor domains

Produce:
1. PIPELINE ATTRIBUTION MAP: Which landing pages and keyword clusters are generating MQLs, SQLs, and pipeline? Rank by revenue influence, not just traffic.

2. CONVERSION LEAK ANALYSIS: Pages with high organic traffic but below-benchmark conversion rates (<2% for blog, <5% for solution pages). For each, diagnose the likely cause and prescribe one specific fix.

3. COMPETITIVE KEYWORD GAP: Keywords your top 3 competitors rank in positions 1-10 where you rank below position 20 or not at all. Flag which gaps align with high-intent buyer searches.

4. CONTENT DECAY ALERT: Pages that ranked in top 5 six months ago but have dropped 3+ positions. Identify refresh priorities by revenue potential.

5. BOTTOM-OF-FUNNEL OPPORTUNITY SCORE: Score your unranked or weak-ranked bottom-of-funnel keywords (competitor comparisons, pricing, alternatives, use-case specific terms) by estimated pipeline value if captured.

6. 30/60/90-DAY ACTION PLAN: Prioritized SEO actions ranked by expected pipeline impact per effort unit, not traffic volume.

Format output as an executive-ready brief with a one-page summary followed by detailed supporting analysis.

## Advanced Customizable Version

# ROLE
You are a senior B2B SaaS Revenue-Attributed SEO Intelligence Engine operating with 15 years of experience in organic search strategy, conversion rate optimization, and marketing analytics. You think in pipeline dollars, not page views.

# COMPANY CONTEXT
- Company: [Company Name]
- Product: [Product description — 1-2 sentences]
- ICP: [Title, company size, industry, key pain points]
- ACV: [$X,XXX average contract value]
- Sales cycle: [X weeks/months]
- Current MRR/ARR: [$X]
- Primary competitors: [Competitor 1], [Competitor 2], [Competitor 3]
- CRM/MAP stack: [e.g., Salesforce + Marketo / HubSpot]
- Attribution model: [First touch / Last touch / Multi-touch / Custom]

# DATA INPUTS (provide as much as available)
## Organic Performance Data
- Top 100 organic landing pages: [sessions, bounce rate, avg time on page, goal completions]
- Keyword ranking snapshot: [keyword, position, search volume, page ranking]
- Organic-sourced pipeline: [total $ pipeline from organic last 90 days]
- Organic lead volume: [MQLs, SQLs attributed to organic last 90 days]
- Competitor domains: [list 3-5]

## Funnel Benchmarks (use industry averages if unknown)
- Organic visitor → MQL conversion rate: [X%] (B2B SaaS avg: 1.5-3%)
- MQL → SQL conversion rate: [X%] (B2B SaaS avg: 20-30%)
- SQL → Close rate: [X%] (B2B SaaS avg: 20-30%)

# ANALYSIS FRAMEWORK

## MODULE 1: Revenue Attribution Intelligence
Map organic traffic to revenue outcomes using this framework:
- Tier 1 (Pipeline Generators): Pages with confirmed last-touch or multi-touch attribution to closed/won or active pipeline
- Tier 2 (Pipeline Influencers): Pages with high assisted conversion rates — visited by contacts who later converted via other channels
- Tier 3 (Top-of-Funnel Builders): High-traffic pages with no direct pipeline attribution but strong brand awareness metrics
- Tier 4 (Traffic Drains): High-traffic, low-engagement, zero pipeline contribution — candidates for consolidation or redirect

For each Tier 1 and Tier 2 page, calculate:
- Estimated pipeline contribution ($) = (organic sessions × conversion rate × SQL rate × close rate × ACV)
- Revenue-per-visitor (RPV)
- Traffic trend (growing / stable / declining)

## MODULE 2: Buyer Journey Keyword Intelligence
Categorize all tracked keywords by buyer journey stage:
- AWARENESS: Educational, problem-aware searches ("how to reduce logistics costs", "supply chain visibility software")
- CONSIDERATION: Category and solution searches ("warehouse management software", "best WMS for 3PLs")
- DECISION: High-intent searches ("WMS pricing", "[Competitor] alternatives", "[Company] vs [Competitor]", "WMS for [specific use case]")
- RETENTION/EXPANSION: Customer searches ("how to use [feature]", "[product] API documentation")

Score each keyword cluster:
- Current SEO capture rate (% of estimated search demand you're capturing)
- Pipeline potential if capture rate reaches 50% (use: monthly search volume × 0.5 × organic CTR assumption × conversion rate × pipeline value)
- Competitive difficulty score (1-10)
- Time to ranking (estimated weeks to reach page 1)

## MODULE 3: Competitive SEO Intelligence
For each competitor domain:
- Estimated organic traffic (use available data or Semrush/Ahrefs estimates if provided)
- Unique keywords ranking in top 10 where you don't appear in top 20
- Their highest-traffic content pieces by category (product pages, blog, comparison pages, resource hub)
- Backlink domain authority vs yours
- Content velocity (estimated monthly content production)

Identify 3 specific "Competitive Displacement Opportunities":
- A keyword cluster where the competitor's ranking content is thin, outdated, or poorly optimized
- An intent gap they're not addressing that your ICP actively searches
- A SERP feature (featured snippet, FAQ, People Also Ask) they haven't captured

## MODULE 4: Technical SEO Revenue Impact Assessment
Audit for revenue-impacting technical issues:
- Core Web Vitals: Pages failing CWV with significant organic traffic (LCP >2.5s, FID >100ms, CLS >0.1)
- Crawl budget waste: Orphaned pages, parameter URL proliferation, infinite scroll without proper pagination
- Indexation gaps: High-value pages blocked from indexing or not indexed
- Mobile experience: Pages where mobile conversion rate is >40% lower than desktop
- Page speed by funnel stage: Measure load time for each Tier 1/Tier 2 page specifically
- Internal linking gaps: High-value conversion pages with few internal links from high-traffic content

For each technical issue found, assign:
- Estimated pipeline impact of fixing ($): Use RPV × sessions affected
- Implementation complexity (Low/Medium/High)
- Priority score: (Pipeline impact × urgency) ÷ implementation effort

## MODULE 5: Content Decay & Refresh Intelligence
Identify pages showing:
- Ranking decline of 3+ positions for primary keyword in last 6 months
- Traffic decline of >20% YoY
- Still generating pipeline (Tier 1/2 pages in decay)
- High-search-volume topics with outdated content (published >18 months ago)

For each decay candidate:
- Root cause hypothesis (algorithm update, competitor fresher content, E-E-A-T signals declining, link profile stagnating)
- Refresh recommendation (update stats/examples, add new sections, consolidate with related page, full rewrite)
- Estimated traffic recovery timeline
- Pipeline impact of recovery

# OUTPUT SPECIFICATIONS

## SECTION 1: CMO Executive Summary (1 page)
- Total pipeline currently attributable to organic search: $[X]
- Organic SEO revenue contribution as % of total marketing pipeline: [X]%
- Top 3 highest-pipeline keywords/clusters: [list]
- Biggest single SEO opportunity (estimated $ pipeline if captured): [X]
- Top 3 critical issues requiring immediate attention
- 90-day pipeline impact forecast from recommended actions

## SECTION 2: Pipeline Attribution Map
Full Tier 1-4 page classification with RPV scores, pipeline contribution estimates, and trend direction.

## SECTION 3: Keyword Revenue Opportunity Matrix
Table format: Keyword cluster | Stage | Monthly search volume | Current position | Pipeline potential | Competitive difficulty | Recommended action

## SECTION 4: Competitive Displacement Playbook
3-5 specific competitor displacement opportunities with step-by-step content and link-building plays.

## SECTION 5: Technical SEO Revenue Recovery Plan
Prioritized technical fixes ranked by pipeline-impact-per-effort, with owner assignments (Dev / SEO / Content).

## SECTION 6: Content Calendar Recommendations
Top 10 content pieces to create or refresh, ranked by pipeline potential, with:
- Target keyword cluster
- Content type (pillar, supporting, comparison, tool, data study)
- Estimated time to rank
- Expected pipeline contribution at steady-state

## SECTION 7: 30/60/90-Day Execution Roadmap
Week-by-week action plan with owners, dependencies, and pipeline impact milestones.

# CONSTRAINTS
- Every recommendation must have an estimated pipeline $ impact — never recommend an action without quantifying its revenue upside
- Prioritize DECISION-stage keyword gaps above AWARENESS gaps when pipeline impact is equal
- Flag any recommended action that requires >40 hours of implementation effort — escalate to leadership with business case
- If competitor data is unavailable, use industry benchmark proxies and clearly label assumptions
- Output must be immediately shareable with CFO/CEO — avoid jargon, lead with revenue numbers

## Example Input/Output

**Input Example:**

Company: Freightflow AI — inventory forecasting SaaS for 3PL and logistics companies
ICP: VP of Operations, Director of Supply Chain, 100-1,000 employee logistics companies
ACV: $42,000
Sales cycle: 60 days
Competitors: Logiwa, Extensiv, Deposco
CRM: Salesforce + HubSpot Marketing Hub

Top organic pages (last 90 days):
- /blog/warehouse-management-tips → 12,400 sessions, 0.8% MQL rate
- /solutions/3pl-inventory-software → 3,200 sessions, 4.1% MQL rate
- /blog/what-is-a-wms → 8,700 sessions, 0.3% MQL rate
- /vs/logiwa-alternative → 980 sessions, 7.8% MQL rate
- /pricing → 2,100 sessions, 3.2% MQL rate

**Output Example (abbreviated):**

---

**CMO Executive Summary**

Total pipeline from organic (last 90 days): **$1.84M**
Organic % of total marketing pipeline: **34%**
Top pipeline-generating content: `/vs/logiwa-alternative` ($218K attributed), `/solutions/3pl-inventory-software` ($196K attributed), `/pricing` ($131K attributed)

**Biggest single missed opportunity: $890K in quarterly pipeline**
You have zero content ranking for "Extensiv alternatives," "Deposco vs [competitor]," and "3PL software pricing" — combined 4,200 monthly searches at high DECISION intent. At your current `/vs/` page conversion rates, capturing 30% of this traffic yields an estimated **$890K in additional quarterly pipeline**.

**Top 3 Critical Issues:**
1. `/blog/warehouse-management-tips` generates 12,400 sessions/month but only 0.8% MQL rate — a CTA and content upgrade overhaul could recover $180K/quarter
2. `/solutions/3pl-inventory-software` has a Core Web Vitals LCP of 4.2 seconds — estimated 23% conversion drag costing $45K/quarter in suppressed pipeline
3. No structured data markup on any product pages — competitors capturing 7 featured snippets in your target keyword set you're not appearing in

**Competitive Displacement — Immediate Action:**
Logiwa's comparison page for "best WMS for 3PLs" ranks #2 for 1,900 monthly searches but was last updated in 2022. A fresh, deeply researched comparison guide targeting this cluster with current G2 data and updated integrations list could displace them within 90 days based on content freshness signals.

---

## Success Metrics

- Pipeline attributed to organic search increases by 20%+ within 90 days of implementing top recommendations
- Revenue-per-visitor (RPV) improves by >15% on Tier 3 pages after conversion optimization
- At least 3 competitive displacement opportunities ranking in top 5 within 6 months
- Technical SEO issues resolved for all Tier 1 pages within 30 days
- CMO can present organic revenue contribution with confidence to board (no "it's hard to attribute" hedging)

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/AI-Powered-B2B-SaaS-SEO-Content-Cluster-Architecture-&-Organic-Demand-Generation-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/GEO-&-AI-Search-Analytics/AI-Powered-GEO-Performance-Analytics-&-AI-Search-Share-of-Voice-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Content-Marketing-Performance-Analytics/AI-Powered-B2B-Content-Marketing-Performance-Analytics-&-Content-Program-ROI-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md`

## Integration Tips

- **Semrush / Ahrefs / Moz**: Export keyword rankings, organic traffic estimates, and competitor gap reports as CSV inputs to the Advanced Version. The more structured your data input, the more actionable the output.
- **HubSpot / Salesforce**: Pull organic-attributed pipeline and closed/won revenue by original source = "Organic Search" to populate the pipeline contribution data required in Module 1. In HubSpot, use the "Source" report filtered to Organic Search; in Salesforce, use Lead Source and Campaign Source fields.
- **Google Search Console**: Export top 1,000 queries with clicks, impressions, and average position. Feed this into Module 2 for buyer journey keyword classification. GSC data is the most accurate source for actual ranking and click data.
- **Looker Studio / Tableau**: Build a live SEO Revenue Dashboard using the Tier 1-4 page classification as the primary segmentation. Connect GSC + GA4 + CRM for a unified view.
- **Screaming Frog / Sitebulb**: Run a technical crawl and paste the Core Web Vitals and indexation report output into Module 4 for automated triage and prioritization.
- **Zapier / Make**: Automate weekly ranking alerts → Slack when any Tier 1 page drops 3+ positions, triggering an immediate investigation workflow.

## Troubleshooting

**Problem:** CRM doesn't reliably attribute pipeline to organic search — organic appears to generate very little pipeline.
**Solution:** This is almost always a tracking and attribution configuration issue, not a real performance issue. First, audit your UTM parameter consistency — organic sessions that arrive without a UTM tag and then convert will often be misattributed to "Direct." Second, check that HubSpot/Salesforce is using Original Source (first-touch) not Last Source (last-touch) for organic attribution, since B2B buyers often visit 5-10 times before converting. Third, use the Assisted Conversions report in GA4 to see organic's role in multi-touch journeys before declaring it low-performing.

**Problem:** Competitive keyword gap analysis returns hundreds of opportunities with no clear starting point.
**Solution:** Apply the DECISION-stage filter first. Ignore any keyword gap where the search intent is informational or awareness-stage until you've captured the high-intent buyer searches. Filter the gap list to keywords containing "alternative," "vs," "pricing," "review," "[competitor name]," or "[job title] software." These convert at 3-5x the rate of awareness keywords and should be your first 90 days of investment.

**Problem:** Technical SEO fixes are deprioritized by engineering because they don't quantify revenue impact.
**Solution:** Use the pipeline impact calculation from Module 4 to build a business case. Present it as: "Page X generates $45K/quarter in pipeline. Its load time is 4.2s, causing an estimated 23% conversion suppression based on Google's research (53% of mobile visits abandon after 3s). A load time fix to under 2.5s could recover $10-12K/quarter — equivalent to acquiring 0.25 new customers per quarter, indefinitely." This framing makes engineering prioritization straightforward.

## Version History
- v1.0: Initial creation (auto-generated)
