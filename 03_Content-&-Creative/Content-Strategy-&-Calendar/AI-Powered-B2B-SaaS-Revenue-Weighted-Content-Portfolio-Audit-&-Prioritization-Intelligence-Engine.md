# AI-Powered B2B SaaS Revenue-Weighted Content Portfolio Audit & Prioritization Intelligence Engine - Know Exactly Which Content to Kill, Keep, Update, or Amplify

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** content-strategy, content-audit, pipeline-attribution, revenue-intelligence, content-operations, b2b, saas, content-prioritization, marketing-operations

## Overview
Analyzes your full content library against pipeline and revenue data to score every asset by actual business impact, identify the "golden" 10-15% of content generating 80%+ of pipeline influence, expose the bloated middle that consumes team bandwidth with zero revenue return, and produce a prioritized 90-day content improvement roadmap. Use when you suspect your content program is producing volume without revenue impact, when you inherit a content library from a prior team and need to make fast decisions, before Q3/Q4 budget planning to justify content investments, or when your content team is overwhelmed and you need to ruthlessly prioritize.

## Quick Copy-Paste Version

You are a B2B content strategy analyst. I need a revenue-weighted audit of my content library to decide what to kill, update, repurpose, or amplify.

**My Content Library:**
[Paste your content inventory — can be a list of URLs, titles, or a table with performance data]

**Performance Data Available:**
- [List what metrics you have: e.g., "GA4 pageviews, HubSpot form submissions per page, Salesforce campaign influence data, Semrush keyword rankings and traffic estimates"]

**Business Context:**
- Company: [Name and what you sell]
- ICP: [Primary buyer — title, company size]
- Average deal size: [e.g., "$52,000 ACV"]
- Marketing-sourced pipeline target: [e.g., "$6.2M/quarter"]
- Content team size and monthly production capacity: [e.g., "3 writers, 6 pieces/month"]

**My Audit Goals:**
[e.g., "Identify which content to delete or no-index, which to update vs. create net-new, and what to amplify through paid/organic distribution"]

Produce a complete content portfolio audit with:

1. **Revenue Attribution Score** for each content piece: composite of pipeline influence %, organic traffic value (traffic × estimated CPC), and conversion rate to demo/trial. Rank all content from highest to lowest.

2. **4D Decision Framework**: For each content piece, assign one of:
   - **Delete/No-Index**: Zero traffic, zero pipeline influence, outdated, irrelevant
   - **Delegate**: Needs update but is low-priority — outsource refresh
   - **Do**: High potential, needs team attention — specific update recommendation
   - **Double Down**: High performer — amplify through paid promotion, backlink building, content refresh, repurposing

3. **The Golden 15 List**: Your top 15 highest-revenue-impact pieces — what makes each one work, and how to compound their impact

4. **The Bottom 25% Kill List**: Content to delete, consolidate, or no-index — with the expected SEO and operational impact of removing them

5. **90-Day Prioritized Action Roadmap**: What your content team should work on first, second, and third — in order of expected pipeline ROI per hour invested

Show me exactly what to focus on and what to stop doing.

## Advanced Customizable Version

ROLE: You are a senior B2B content strategist and marketing performance analyst with 14+ years managing content programs at venture-backed SaaS companies ($8M–$300M ARR). You've audited content libraries ranging from 50 to 3,000 pieces and have developed a proprietary framework for connecting every content asset to pipeline and revenue outcomes. You understand that content marketing's primary failure mode is not quality — it's prioritization: teams keep creating content while their best-performing assets decay, their worst performers waste crawl budget and team credibility, and nobody knows which 15 pieces are doing all the heavy lifting. You think in terms of "Content Return on Investment" (content pipeline influence ÷ content production cost + maintenance cost), and you make recommendations that a CMO can defend to a CFO.

CONTEXT:
Company: [Company Name]
Product/Service: [What you sell and to whom]
Stage & ARR: [e.g., "Series B, $22M ARR, growing 65% YoY"]
ICP: [Primary buyer — title, company size, industry — e.g., "VP of Engineering at 500-5,000 employee B2B SaaS companies"]
Secondary buyers in buying committee: [e.g., "CISO for security review, CFO for budget sign-off"]
Average ACV: [e.g., "$64,000"]
Average sales cycle: [e.g., "4.2 months"]
Marketing-sourced pipeline target: [e.g., "$7.8M/quarter"]
Content library size: [e.g., "287 published URLs — 142 blog posts, 38 landing pages, 24 case studies, 18 white papers/guides, 31 product pages, 34 other"]
Content team capacity: [e.g., "2 FTE writers + 1 SEO specialist, producing 8-10 pieces/month"]
Analytics stack: [e.g., "Google Analytics 4, HubSpot (CRM + MAP), Salesforce, Semrush, Gong, 6sense"]
Attribution model: [e.g., "Multi-touch with first-touch credit for awareness, last-touch for conversion, campaign influence for assisted"]
Current content performance concerns: [e.g., "Traffic is up 22% YoY but MQL volume flat; we publish consistently but can't tell what's working; legacy content from 3 years ago is cluttering our site"]

OBJECTIVE: Conduct a comprehensive revenue-weighted content portfolio audit that tells my team EXACTLY which content to kill, update, amplify, or create — in priority order based on expected pipeline ROI per hour invested.

DELIVERABLE STRUCTURE:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 1: CONTENT REVENUE ATTRIBUTION SCORING (CRAS) FRAMEWORK
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Build the **Content Revenue Attribution Score (CRAS)** for each content piece — a composite metric that combines:

**Component 1 — Pipeline Influence Score (40% weight):**
Using Salesforce Campaign Influence data (or HubSpot contact attribution), calculate for each URL:
- Direct pipeline influence: Sum of Opportunity amounts where this content was a touchpoint in the 90-day pre-Opportunity window
- Assisted influence: Opportunities where this content appeared in the buying journey but was not first or last touch
- CRAS Pipeline Influence = (Direct Influence × 1.0) + (Assisted Influence × 0.3) ÷ content age in months

For companies without complete attribution: Estimate using proxy — [Content conversion rate to form submission × Monthly form submissions × SQL rate × Average ACV × Win rate]

**Component 2 — Organic Traffic Revenue Value (35% weight):**
Calculate the estimated organic traffic value for each piece:
- Monthly organic sessions from GA4 or Semrush Organic Position Tracker
- Weighted by search intent: Bottom-of-funnel keywords (competitor comparisons, "best [category] software", "[problem] solution") × 3.0; Middle-of-funnel (how-to, guide, template) × 1.5; Top-of-funnel (awareness, thought leadership) × 0.8
- Traffic Revenue Value = Monthly sessions × Intent weight × Site CVR × SQL rate × Win rate × ACV
- Flag "traffic without conversion" pieces — high traffic, zero pipeline touchpoints (common with informational content that attracts wrong audience)

**Component 3 — Conversion Efficiency Score (25% weight):**
For each content piece with a measurable conversion path:
- Conversion rate: Sessions → Form submission or CTA click
- Benchmarks: Demo request pages (1.5-4% is average, >4% is strong); Blog posts with inline CTAs (<0.5% weak, >1.5% strong); Case studies (3-8% for bottom-funnel buyers)
- Flag "high traffic, low conversion" pieces — these are your biggest optimization opportunities

**CRAS Calculation:**
CRAS = (Pipeline Influence Score × 0.40) + (Traffic Revenue Value × 0.35) + (Conversion Efficiency Score × 0.25)

Output a ranked table of all content pieces by CRAS, with each component visible:

| URL | Content Type | Monthly Sessions | Pipeline Influence | Conv. Rate | CRAS Score | Recommendation |
|-----|-------------|-----------------|-------------------|-----------|-----------|----------------|

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 2: THE 4D DECISION FRAMEWORK
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Apply the 4D Decision Framework to every content piece based on its CRAS score and qualitative assessment:

**DELETE / NO-INDEX (CRAS < 10, No strategic value):**
Criteria for deletion:
- Zero organic traffic (< 50 sessions/month) for 6+ consecutive months
- Zero pipeline touchpoints in last 12 months
- Covers topic now handled by a better, higher-ranking piece (cannibalization)
- Published > 24 months ago with no updates and topic is time-sensitive
- Targets keyword with negative intent alignment for ICP

For each Delete candidate, specify:
- Current organic traffic risk if removed (301 redirect target or 410 gone)
- Whether to consolidate into an existing piece vs. full removal
- Expected benefit: crawl budget reclaimed, site authority concentration, reduced maintenance burden
- Implementation: Create a redirect mapping table specifying 301 destination for each deleted URL

**DELEGATE (CRAS 10-35, Update needed but not high-priority):**
Criteria for delegation:
- Moderate traffic or pipeline influence but clearly outdated (references deprecated software, old statistics, 2020-era frameworks)
- Strong keyword rank but declining (position 8-15, needs content refresh to recover rankings)
- Good topic coverage but missing key ICP-specific use case or framework
- Refresh estimated at < 2 hours of writing work

For each Delegate candidate, provide:
- Specific content update brief: Which sections need updating, what new information to add, which statistics to replace
- Estimated refresh effort in hours
- Whether this can be outsourced to a freelancer or junior writer without strategic direction
- Expected ranking and traffic improvement from refresh

**DO — Team-Priority Update (CRAS 35-65, High potential, needs strategic work):**
Criteria for Do:
- Strong keyword rank (position 5-20) with declining traffic or flat conversion
- Clear ICP topic fit but thin coverage — competitors outranking with more comprehensive content
- High pipeline influence historically but content no longer reflects current product/ICP
- Conversion rate significantly below benchmark for content type
- Needs strategic repositioning, not just factual updates

For each Do candidate, provide:
- Content upgrade brief: Specific new sections to add, new frameworks to introduce, new examples to include, new CTAs to test
- SEO optimization recommendations: keyword gaps vs. ranking competitors, internal linking gaps
- Conversion optimization recommendations: CTA placement, form placement, content upgrade opportunity
- Priority rank among all Do items — ranked by expected pipeline lift per hour invested
- Estimated production effort in hours

**DOUBLE DOWN — Amplify High Performers (CRAS > 65):**
Criteria for Double Down:
- Already driving significant pipeline influence
- Organic ranking position 1-5 for high-intent keywords
- Conversion rate above benchmark for content type
- Content can generate more impact with amplification, not just maintenance

For each Double Down candidate, provide:
- 3-5 specific amplification actions with expected pipeline impact:
  - Paid promotion strategy: Which LinkedIn/Google targeting would reach ideal ICP at this funnel stage
  - Link building targets: 5 specific high-authority domains to pitch for backlinks to this piece
  - Content repurposing plan: How to convert into LinkedIn carousel, short video, email sequence, podcast episode
  - Sales enablement integration: How to place this in sales sequences at the right buying stage
  - Internal linking optimization: Which other site pages should link to this piece
- Maintenance cadence: How often to update to protect rankings and conversion rates

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 3: THE GOLDEN 15 — YOUR HIGHEST-VALUE CONTENT ASSETS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Identify the top 15 content pieces by CRAS score and conduct a deep analysis of each:

For each Golden 15 piece:
- **Why it works**: Deconstruct the specific factors driving its performance — keyword intent match, content depth, conversion element placement, ICP specificity, differentiated POV
- **Revenue contribution estimate**: Annual pipeline influence in dollars
- **Current vulnerability**: What threatens its performance (competitor content catching up, declining keyword rank, outdated statistics, missing product updates)
- **Compounding action**: The single highest-ROI action to increase its revenue impact in the next 90 days

Build a **Golden 15 Protection Protocol** — a quarterly maintenance checklist that keeps these pieces performing:
- Monthly: Check rankings for primary keywords, monitor for ranking drops > 2 positions
- Quarterly: Refresh statistics and data references, update product screenshots/descriptions, check for broken links
- Semi-annually: Full content expansion review — are competitors now outranking with more comprehensive content?
- Annually: Full rewrite assessment — does this piece still reflect current ICP pain points and your current solution?

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 4: THE BOTTOM 25% KILL LIST
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Identify content candidates for deletion or consolidation. For each:

**Crawl Budget Waste Analysis:**
Calculate the total crawl budget wasted on low-quality content:
- Googlebot crawl allocation: Low-value pages reduce crawl frequency for high-value pages
- For site with [X] URLs: Estimated crawl budget recovery from removing bottom 25% = [N] pages freed, estimated ranking improvement for remaining content from Google's freshness and crawl allocation rebalancing

**Cannibalization Identification:**
Find keyword cannibalization pairs — two URLs competing for the same keyword:
- Identify all URL pairs ranking for the same keyword within same 10 positions
- Recommend consolidation: which URL to keep (higher CRAS), which to redirect
- Content consolidation brief: How to merge the deleted piece's unique content into the surviving piece

**No-Index vs. Delete Decision:**
- No-index (don't remove, just remove from search index): URLs with internal links but zero external SEO value, tools/calculators with utility, gated landing pages not meant for organic discovery
- Delete + 301 redirect: Pure content URLs with zero traffic, zero links, zero pipeline value
- Provide a complete redirect mapping table: [Source URL] → [301 Destination]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 5: CONTENT ROI ANALYSIS & TEAM PRIORITIZATION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Content Return on Investment (Content ROI) Calculation:**
For each major content investment category:
- Annual pipeline influence generated
- Estimated total investment (production time × writer hourly rate + distribution spend + maintenance)
- Content ROI = Annual pipeline influence ÷ Total investment
- Benchmark: Best-in-class B2B content generates $15-40 in pipeline influence per $1 invested in production

**Team Capacity Allocation Analysis:**
With a content team of [size] producing [N] pieces/month:
- Current time allocation by content type: Blog posts X%, Case studies X%, Landing pages X%, etc.
- Recommended reallocation based on CRAS analysis: Shift production toward highest-ROI content types
- Calculate: "If we shifted 30% of blog post production time to case studies, expected pipeline increase = $X"

**90-Day Prioritized Action Roadmap:**
Week 1-2 (Quick wins, < 4 hours each):
- [Specific Delete actions: implement 301 redirects, submit to Google Search Console for removal]
- [Specific conversion optimizations on top Double Down pieces: add inline CTA, update headline, embed video]

Week 3-6 (Medium investment, 4-16 hours each):
- [Priority Do items: content upgrades with specific briefs]
- [Delegate assignments: content refresh briefs for freelancers]

Week 7-13 (Strategic investments, 16+ hours each):
- [New content creation recommendations: highest-gap, highest-CRAS-potential topics not yet covered]
- [Content repurposing projects: convert top performers to new formats]

**New Content Creation Decision Gate:**
Before creating any new content, evaluate against this ROI filter:
- Does this topic have a keyword with commercial intent and measurable search volume?
- Will this content target ICP buyers at a stage where we have demonstrated pipeline influence gap?
- Is this topic already covered adequately by existing content (if yes, upgrade existing vs. create new)?
- Expected production cost vs. 12-month pipeline influence projection — minimum 10:1 ROI threshold

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 6: CONTENT PROGRAM GOVERNANCE & MEASUREMENT CADENCE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

**Quarterly Content Audit Cadence:**
Design a lightweight 4-hour quarterly audit that keeps content performance optimized:
- Pull CRAS data for all content: Identify any piece that dropped > 30% in traffic or pipeline influence
- Promote/demote pieces between 4D categories based on performance trends
- Update quarterly Kill List and Do list based on competitive landscape changes

**Content Performance Dashboard:**
Specify the exact metrics to track weekly in a Content Intelligence Dashboard:
- Golden 15 weekly tracking: Keyword positions, weekly sessions, weekly form submissions
- Do list progress: Which pieces have been updated vs. pending
- Delete list progress: Redirects implemented, crawl budget recovery metrics
- Net Content ROI: Total pipeline influenced by content ÷ Total content investment (tracked monthly)

CONSTRAINTS:
- Every recommendation must be executable by [content team size] — no recommendations requiring 3x headcount to implement
- Delete recommendations require 301 redirect implementation before any URL is removed from site
- No content should be deleted if it has an inbound link from a high-authority domain (DA > 40) without link reclamation strategy
- All Double Down amplification actions must tie to measurable pipeline outcomes within 90 days
- Content ROI projections should use conservative estimates (use 70% of best-case scenario)

## Example Input/Output

**Input Example:**
Company: Veridian Analytics — AI-powered retail analytics platform  
ICP: VP of Merchandising and VP of E-commerce at $100M-$2B revenue retail brands  
ACV: $89,000  
Sales cycle: 5.5 months  
Content library: 312 published URLs (178 blog posts, 41 landing pages, 22 case studies, 18 white papers, 27 product pages, 26 other)  
Content team: 2 FTE writers + 1 SEO specialist  
Q3 pipeline target: $9.4M marketing-sourced  
Analytics: GA4, HubSpot MAP, Salesforce, Semrush, Gong  

**Output Example (Module 3: Golden 15 Analysis — Top 3 Pieces):**

---
**#1 Golden Piece: "Retail Inventory Optimization: How to Reduce Overstock by 34% Without Stockouts" (Blog Post)**

**CRAS Score: 94/100**
- Pipeline influence: $2.1M influenced in last 12 months (7 closed-won deals touched this piece in evaluation stage)
- Monthly organic sessions: 4,200 (ranking #2 for "retail inventory optimization software", #4 for "reduce overstock AI")
- Traffic revenue value: $6,300/month estimated
- Conversion rate: 2.8% to demo request (3× site average)

**Why it works:**
- Targets a hyper-specific pain point (overstock + stockout simultaneously — the real inventory nightmare)
- Uses proprietary data: "34% reduction" based on Veridian customer aggregate
- Includes a free inventory health calculator (embedded tool driving 40% of form submissions)
- Specifically mentions the VP of Merchandising's vocabulary — "open-to-buy," "planogram compliance," "markdown cadence"

**Revenue Contribution Estimate:** $2.1M pipeline influenced annually; estimated $630K in closed-won revenue tied to this content touchpoint

**Current Vulnerability:** Competitor (Crisp Retail) published a comprehensive guide 3 months ago ranking #1 — Veridian slipped from #1 to #2. Traffic down 18% over 90 days.

**Compounding Action (Priority #1 for next 60 days):**
Update the piece to reclaim #1 ranking:
- Add new section: "2026 Retail Inventory Benchmarks" with current data from Veridian customer base (position yourself as the source of truth)
- Expand calculator to include "Markdown Recovery Calculator" — captures users earlier in decision cycle
- Add 2 new customer case study sidebars (Veridian customer examples, specific metrics)
- Target: Recover to #1 within 60 days, project 25% traffic recovery = 1,050 additional monthly sessions = ~29 additional demo requests/month at 2.8% CVR = ~$220K additional annual pipeline

---
**#7 Golden Piece: "Retail Analytics vs. Business Intelligence: What Retail Buyers Get Wrong" (Blog Post)**

**CRAS Score: 81/100**
- Pipeline influence: $890K influenced in last 12 months (appears in evaluation stage for buyers comparing generic BI tools vs. purpose-built retail analytics)
- Monthly organic sessions: 2,800 (ranking #1 for "retail analytics vs business intelligence", #3 for "retail analytics software comparison")
- Conversion rate: 1.9% to demo request (2× site average)

**Why it works:**
- Directly addresses the primary objection Gong call analysis shows in 67% of deals: "Can't we just use Tableau or PowerBI for this?"
- Crushes this objection with specificity — 6 capabilities GA/BI tools can't replicate for retail
- Includes a "Decision Framework" download (47% of form submissions from this page use this CTA)

**Compounding Action:**
- Convert to a Sales Battlecard and integrate into Salesforce as an email link SDRs send when BI/Tableau objection appears in Gong — estimated 12% improvement in objection-handling win rate
- Create a LinkedIn carousel version of the 6-capability comparison — use as Sponsored Content targeting Tableau/PowerBI users at retail companies (retargeting audience from GA4)

---

**Output Example (Module 4: Kill List — Bottom 10% Sample)**

**Delete Candidates (301 Redirect to [mapped URL]):**

1. `/blog/what-is-retail-analytics/` — 12 sessions/month, zero pipeline touchpoints in 24 months, topic fully covered by `/retail-analytics-guide/` (3,400 sessions/month, CRAS 88). → 301 redirect to `/retail-analytics-guide/`

2. `/blog/big-data-in-retail-2021/` — 8 sessions/month, time-stamped title, zero commercial intent, competed with and lost to updated `/retail-big-data-guide-2024/` for all target keywords. → 301 redirect to updated guide. No external links at risk.

3. `/webinar/q2-2022-retail-trends-replay/` — 0 organic sessions, indexed but never trafficked, dated content. → 410 Gone (no redirect needed — no inbound links, no internal links)

**Estimated impact of deleting bottom 25% (78 URLs):**
- Crawl budget reclaimed: ~78 additional crawl slots reallocated to Golden 15 and Do-list pieces
- Expected ranking improvement for retained content: Historical benchmarks show 8-15% ranking improvement for high-value pages when site authority is concentrated
- Team maintenance burden reduced: ~6 hours/month no longer spent checking, updating, and managing underperforming content

## Success Metrics

- **CRAS accuracy**: At least 70% of Golden 15 pieces show confirmed pipeline influence in Salesforce within 12 months of audit
- **Kill list safety**: Zero ranking drops for pages 301-redirected (confirmed in GSC within 90 days)
- **Content ROI improvement**: Overall content program pipeline ROI improves > 20% within 90 days of implementing audit recommendations
- **Team efficiency**: Content team produces fewer but higher-impact pieces — monthly content ROI per piece increases by > 30%
- **Conversion rate lift**: Average site CVR improves 10-20% after removing low-quality URLs and optimizing Double Down pieces
- **Crawl health**: GSC Coverage report shows 25%+ reduction in crawl errors and non-indexed pages within 60 days

## Related Prompts

- `../../03_Content-&-Creative/Blog-&-Article-Writing/AI-Powered-Content-Brief-&-Editorial-Workflow-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Content-Marketing-Performance-Analytics/AI-Powered-B2B-Content-Marketing-Performance-Analytics-&-Content-Program-ROI-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/SEO-&-Organic-Demand-Generation/AI-Powered-B2B-SaaS-Content-Refresh-&-Ranking-Recovery-Intelligence-Engine.md`
- `../../03_Content-&-Creative/Content-Strategy-&-Calendar/AI-Powered-B2B-Revenue-Linked-Content-Strategy-&-Pipeline-Attribution-Intelligence-Engine.md`

## Integration Tips

**Google Analytics 4:**
- Create a custom exploration report: Segment all pages by "Converted to Demo" event, rank by sessions-to-conversion rate, export to Google Sheets as your CRAS Conversion Efficiency input
- Build a GA4 Audience: "High-Intent Content Visitors" — users who visited case study, comparison, or calculator pages — for use in LinkedIn/Google retargeting
- Set up GA4 Content Groups to categorize all content by type (blog, case study, landing page, product page) for aggregate performance comparison

**HubSpot:**
- Use HubSpot's Content Analytics (Marketing Hub Enterprise) to pull "Contacts associated with page views" — this gives you direct pipeline touchpoint data per URL
- Build a custom HubSpot report: "Contacts by first-touch content URL → Closed-Won Deals" to directly tie content pieces to revenue for CRAS Pipeline Influence scoring
- For each Golden 15 piece, create a HubSpot "Smart CTA" that personalizes the CTA based on lifecycle stage — prospects see "Book Demo," leads see "See Pricing," customers see "Expand Your Plan"

**Salesforce:**
- Run a Salesforce Campaign Influence report filtered by Campaign Type = "Content" and Date = Last 12 months → Download as CSV for CRAS Pipeline Influence input
- Create a Salesforce dashboard widget: "Top 15 Revenue-Generating Content Assets" (linked to Campaign Influence) — show to CMO in weekly pipeline review to justify content investment
- Tag every Salesforce Contact with "Last Content Touch" custom field (populated via HubSpot sync) to track content-to-close correlation

**Semrush:**
- Use Semrush's Position Tracking to monitor Golden 15 keyword rankings weekly — set up automated alerts if any Golden 15 page drops more than 2 positions
- Use Semrush's Content Audit tool to bulk import your site's URLs and get traffic + ranking data in one export — use as the foundation for your CRAS spreadsheet
- Run Semrush's Backlink Audit before deleting any URL — confirm no DA > 40 external links point to Delete candidates before implementing 301s

**Notion / Airtable:**
- Build a Content Portfolio Tracker in Notion or Airtable with columns: URL, CRAS Score, 4D Category, Owner, Last Updated, Next Review Date, Notes
- Set up quarterly "Content Audit Sprint" recurring project in Notion — template pre-filled with the 4D Decision Framework and audit checklist
- Connect Airtable to Google Sheets via Zapier to automatically update CRAS scores when new GA4 data is available

**Google Search Console:**
- Before implementing any Delete decisions, export GSC Coverage report to identify pages Google has indexed — confirm which Delete candidates GSC shows as "Valid, indexed"
- After implementing 301 redirects, monitor GSC Coverage weekly for 8 weeks to confirm redirects are being picked up and no new crawl errors appear
- GSC's URL Inspection tool: use to manually force re-crawl of all Golden 15 pieces after major content updates — accelerates ranking recovery by 2-4 weeks vs. waiting for natural crawl cycle

## Troubleshooting

**Problem: We don't have Salesforce Campaign Influence data — we can't connect content to pipeline.**
Solution: Use a two-step proxy instead of direct pipeline influence: (1) Pull HubSpot "Associated Companies" for each form submission that came from content pages, then manually cross-reference against your CRM to find which deals those contacts became. Even 3 months of this manual attribution gives you directional CRAS scores. Alternatively, implement UTM tracking on all content CTAs immediately and set a rule: "Any contact who submits a form from a piece of content gets that URL recorded as their 'Content Attribution' property" — you'll have real data in 60 days.

**Problem: Our content team resists the Kill list — they're attached to content they wrote and don't want to delete pieces.**
Solution: Frame deletion as "content portfolio optimization" not "deletion of work." Show the math: pages removed from a 300-URL site that are getting 5 sessions/month collectively are consuming 25% of Google's crawl budget for your domain and diluting domain authority signals across thin content. Share the GSC data showing crawl coverage improvement after removals. Run a controlled test: delete 10 pages with 301 redirects, measure ranking improvements for top 20 pages within 60 days — the data converts skeptics faster than any argument.

**Problem: After implementing audit recommendations, some redirected pages started ranking for the destination URL but traffic is lower than expected.**
Solution: 301 redirect equity transfer is typically 90-99% for Google, but full ranking consolidation can take 3-6 months. Check three things: (1) Is the destination page topically relevant enough to absorb the redirected content's keyword authority? If not, you may need to add a content section to the destination page that covers the deleted page's primary topic. (2) Check GSC for any "Redirect Chains" — if your 301s redirect through multiple hops, simplify to direct source → destination. (3) Ensure the destination page has adequate internal linking from high-authority pages — orphaned destination pages recover ranking equity more slowly.

## Version History
- v1.0: Initial creation (auto-generated)
