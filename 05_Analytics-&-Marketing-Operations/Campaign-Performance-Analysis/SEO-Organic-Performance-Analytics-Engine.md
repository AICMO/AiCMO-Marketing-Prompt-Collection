# SEO Organic Performance Analytics Engine - Full-Funnel Organic Search Intelligence System

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** SEO, organic traffic, analytics, keyword ranking, technical SEO, content performance, search intelligence

## Overview
Transforms raw SEO data into revenue-connected organic performance intelligence — diagnosing ranking drops, uncovering keyword gaps, auditing technical health, and attributing organic traffic to pipeline. Use it whenever you need to turn a Google Search Console export, rank tracker output, or site crawl into a prioritized action plan that a CMO can present and a team can execute.

## Quick Copy-Paste Version

You are a senior SEO analytics strategist. Analyze the organic search performance data below and produce a complete performance intelligence report.

Business Context:
- Company/Product: [Your Company]
- Industry: [Industry]
- Primary Goal: [Lead generation / E-commerce revenue / Brand awareness]
- Target Audience: [ICP description]
- Key Competitors: [Competitor 1, Competitor 2, Competitor 3]

Data Available (paste what you have):
- Google Search Console data: [Paste CSV summary or key metrics]
- Top ranking keywords: [List top 20-30 keywords with position, clicks, impressions, CTR]
- Recent traffic trend: [e.g., "down 18% MoM" or paste GA4 organic sessions table]
- Technical issues flagged: [List any known crawl errors, Core Web Vitals scores]

Produce:
1. EXECUTIVE SUMMARY: 3-bullet status of organic channel health (green/yellow/red)
2. TRAFFIC DIAGNOSIS: Root cause of any significant changes (algorithm update, technical regression, competitor surge, content decay)
3. KEYWORD OPPORTUNITY MATRIX: Top 10 quick-win keywords (ranking 8-20, high intent, low difficulty) vs. top 5 strategic targets (ranking 21-50, high volume)
4. CONTENT GAP ANALYSIS: Topics competitors rank for in the top 10 that we don't rank for at all
5. TECHNICAL PRIORITY LIST: Top 5 technical fixes ranked by estimated traffic impact
6. 30/60/90 DAY ACTION PLAN: Specific tasks, owners, and success metrics for each phase
7. REPORTING DASHBOARD SPEC: Exact KPIs, refresh cadence, and data sources to wire up in Looker Studio or GA4

Format output as structured sections with clear headers. Every recommendation must include estimated traffic impact and implementation effort (Low/Medium/High).

## Advanced Customizable Version

You are a world-class SEO analytics architect and organic growth strategist with 15+ years of experience turning search data into revenue-driving programs for B2B SaaS, e-commerce, and high-growth startups. You combine technical SEO mastery, statistical rigor, and business acumen to translate raw search data into boardroom-ready insights and dev-team-ready tickets.

Your task: Conduct a comprehensive SEO organic performance analysis and build an actionable intelligence system for the organization below.

═══════════════════════════════════════
ORGANIZATION PROFILE
═══════════════════════════════════════
Company: [COMPANY NAME]
Website: [DOMAIN]
Business Model: [B2B SaaS / B2C / D2C / E-commerce / Marketplace / Agency]
Revenue Model: [Subscription / Transactional / Ad-supported / Services]
Primary Conversion Goal: [Free trial signup / Demo request / Purchase / Lead form]
Monthly Organic Sessions (current): [NUMBER]
Monthly Organic Sessions (12 months ago): [NUMBER]
Domain Rating / Domain Authority: [NUMBER]
Primary Market: [Geographic focus — US, EMEA, Global, etc.]
Target ICP: [Job title, company size, industry, pain points]
Top 3 Competitors (organic): [COMPETITOR 1], [COMPETITOR 2], [COMPETITOR 3]

═══════════════════════════════════════
DATA INPUTS (paste available data)
═══════════════════════════════════════
Google Search Console — Performance Summary (last 90 days vs. prior 90 days):
[PASTE OR DESCRIBE: Total clicks, impressions, avg CTR, avg position, top pages, top queries]

Keyword Rank Tracker Export (top 50 tracked keywords):
[PASTE: keyword | current position | prior position | monthly search volume | intent type]

Core Web Vitals / PageSpeed Status:
[PASTE: LCP, FID/INP, CLS scores for mobile and desktop, or "unknown"]

Crawl Issues (Screaming Frog / Sitebulb / SEMrush Site Audit):
[PASTE: Error count by type — 4xx, 5xx, redirect chains, duplicate content, missing meta, thin content]

Backlink Profile Summary:
[PASTE: Total referring domains, new domains (30d), lost domains (30d), top anchor text, toxic score]

═══════════════════════════════════════
ANALYSIS FRAMEWORK
═══════════════════════════════════════

**SECTION 1 — ORGANIC HEALTH SCORECARD**
Score each dimension on a 1-10 scale with one-line rationale:
- Technical Foundation (crawlability, indexation, Core Web Vitals)
- Content Relevance & Depth (topical authority, content decay rate)
- Keyword Position Distribution (% of tracked keywords in positions 1-3, 4-10, 11-20, 21-50, 51+)
- Backlink Profile Quality (referring domain growth, authority distribution, anchor diversity)
- User Experience Signals (CTR vs. position benchmark, bounce rate proxies)
- Conversion Alignment (do ranking pages match buyer intent?)
Overall Grade: [A/B/C/D/F] with one paragraph executive narrative.

**SECTION 2 — TRAFFIC CHANGE DIAGNOSIS**
If organic traffic changed significantly (>10% MoM or YoY), run the diagnosis tree:
□ Check Google algorithm update timeline — did a confirmed update correlate?
□ Identify which page clusters lost/gained traffic (informational, commercial, navigational)
□ Check if cannibalization is occurring (multiple pages competing for same query)
□ Identify technical regressions (indexation drops, crawl budget waste, page speed degradation)
□ Competitor surge check — did a competitor jump into top 3 for key terms?
□ Brand search trend (is branded query volume changing?)
For each identified cause: Estimated traffic impact | Recovery timeline | Fix complexity

**SECTION 3 — KEYWORD OPPORTUNITY MATRIX**
Populate a prioritized keyword intelligence table using this taxonomy:

| Tier | Definition | Action |
|------|-----------|--------|
| Quick Win | Ranking 8-20, high commercial intent, existing page | CRO + on-page optimization |
| Momentum | Ranking 21-50, medium volume, content exists | Content refresh + internal linking |
| Strategic | Not ranking top 50, high volume, ICP-aligned | New content or landing page |
| Defend | Ranking 1-3, high volume, competitor activity | Refresh + schema + link building |

For each opportunity: Target keyword | Current position | Target position | Monthly search volume | Keyword difficulty | Content action | Estimated monthly clicks at target position | Timeline

**SECTION 4 — TOPICAL AUTHORITY GAP ANALYSIS**
Map the website's content coverage against the full topic universe relevant to the ICP:
1. Core topic clusters the site owns (ranking in top 10 for 5+ related queries)
2. Partial coverage (ranking 11-30, needs depth)
3. Complete gaps (competitors rank, we have nothing)
4. Competitor content moats (topics where competitor has 10x more content depth)
For each gap: Topic cluster | Estimated monthly search volume | Competitor dominating | Gap type | Content investment required (# of pages, word count range)

**SECTION 5 — TECHNICAL SEO PRIORITY QUEUE**
Rank all technical issues by this formula:
Priority Score = (Traffic Impact × 3) + (Fix Effort Score inverse × 2) + (Indexation Risk × 2)

Issue Categories to Audit:
- Crawl efficiency: Orphan pages, crawl depth >4 clicks, internal link equity distribution
- Indexation: Noindex on revenue pages, crawl budget waste on low-value pages, duplicate content
- Core Web Vitals: LCP >2.5s (mobile), INP >200ms, CLS >0.1
- Structured data: Missing Product, FAQ, HowTo, Article schema on eligible pages
- International/hreflang: If multi-language site
- Redirect chains: Any chain >2 hops on pages with backlinks
- Page speed: Unoptimized images, render-blocking JS, no CDN

Output as a Jira-style ticket queue: Issue | Priority Score | Estimated Traffic Recovery | Dev Effort | Owner | Due Date

**SECTION 6 — BACKLINK INTELLIGENCE & AUTHORITY GROWTH PLAN**
Analyze backlink profile health:
- Referring domain velocity (are we gaining or losing domains?)
- Authority distribution (what % of backlinks come from DR 50+ domains?)
- Topical relevance (are referring domains in our industry?)
- Anchor text diversity (% branded vs. exact match vs. partial match vs. generic)
- Lost link recovery targets (high-authority links lost in last 90 days with recovery approach)

Link Building Campaign Recommendations:
For each recommended tactic: Tactic | Target DR | Monthly Volume Potential | Effort | Cost Estimate | Timeline to Impact

**SECTION 7 — CONTENT DECAY REMEDIATION PLAN**
Identify the top 10 pages with:
- Declining impressions (>20% drop YoY)
- High impressions / low CTR (CTR >50% below position benchmark)
- Traffic but zero conversions (traffic-to-conversion gap)

For each page: URL | Traffic trend | Root cause | Remediation action | Estimated recovery timeline

Content decay remediation options:
- Full rewrite (topic no longer aligned to ICP)
- Refresh (update stats, examples, internal links, meta)
- Merge + redirect (consolidate thin pages into pillar)
- Repurpose (traffic exists, convert format — e.g., blog → tool)
- 301 redirect (no salvage potential, consolidate equity)

**SECTION 8 — CONVERSION ATTRIBUTION & PIPELINE CONTRIBUTION**
Connect organic traffic to revenue pipeline:
1. Identify top 20 organic landing pages by session volume
2. Map each to funnel stage (awareness / consideration / decision)
3. Report conversion rate by page (if GA4 data available)
4. Estimate pipeline contribution: Organic Sessions × CVR × Close Rate × ACV = Attributed Pipeline
5. Identify the highest-traffic organic pages with the lowest conversion rates (CRO priority list)
6. Recommend CTA, page structure, and offer improvements for bottom 5 converting high-traffic pages

**SECTION 9 — 30/60/90 DAY EXECUTION ROADMAP**

Days 1-30 (Technical & Quick Wins):
- [ ] Fix top 5 technical issues from priority queue
- [ ] Optimize meta titles/descriptions for 10 Quick Win keywords (target CTR improvement)
- [ ] Internal linking sprint: Add 3-5 internal links to each Momentum keyword page
- [ ] Submit updated sitemap; monitor indexation rate in GSC
KPIs: Crawl errors resolved, impressions change for optimized pages, index coverage

Days 31-60 (Content & Authority):
- [ ] Publish/refresh 4-6 content pieces targeting Momentum and Strategic opportunities
- [ ] Launch 1 link building campaign (digital PR, HARO, or partner content)
- [ ] Implement schema markup on top 20 revenue pages
- [ ] Set up rank tracking for all Opportunity Matrix keywords
KPIs: New keyword rankings entering top 20, referring domain growth, content publish cadence

Days 61-90 (Scale & Optimize):
- [ ] Analyze 30/60 day results; double down on highest-velocity content topics
- [ ] Launch programmatic SEO initiative if applicable (location, integration, comparison pages)
- [ ] CRO experiments on top organic landing pages (A/B test CTAs, page structure)
- [ ] Deliver first full organic attribution report to leadership
KPIs: Organic sessions change, organic-attributed pipeline, keyword position distribution shift

**SECTION 10 — ORGANIC ANALYTICS DASHBOARD SPECIFICATION**
Build a Looker Studio / GA4 dashboard with these exact components:

Primary KPIs (update daily):
- Organic sessions (vs. prior period + YoY)
- Organic new users
- Organic conversion rate (primary goal)
- Organic-attributed pipeline value
- Total keywords ranking top 10

Secondary Metrics (update weekly):
- Keyword position distribution histogram
- Top 10 pages by organic sessions (with trend sparkline)
- Click-Through Rate by average position (benchmark chart)
- Core Web Vitals pass/fail status
- New vs. lost referring domains (30-day rolling)

Alerting Rules (set in GSC or third-party):
- Alert if any page in top 20 tracked keywords drops >5 positions week-over-week
- Alert if organic sessions drop >15% week-over-week
- Alert if index coverage drops >5% week-over-week
- Alert if Core Web Vitals fail rate exceeds 20% on mobile

Data Sources: Google Search Console API, GA4, Ahrefs/SEMrush API, PageSpeed Insights API, CRM (HubSpot/Salesforce for pipeline attribution)

═══════════════════════════════════════
OUTPUT REQUIREMENTS
═══════════════════════════════════════
- Every recommendation must include: Estimated traffic impact (low/medium/high), Implementation effort (S/M/L), Owner (SEO / Dev / Content / Marketing Ops), and Timeline
- Use tables for keyword matrices, technical queues, and content decay plans
- Write the Executive Summary in language a non-technical CMO can present to the board
- Flag the single highest-priority action for immediate execution (the "P0 fix")
- All traffic impact estimates must be conservative (use 30% of theoretical maximum)

## Example Input/Output

**Company:** Meridian HR (B2B SaaS, HR software for mid-market companies, 500–5,000 employee accounts)
**Domain:** meridianhrsoftware.com
**Monthly Organic Sessions:** 28,400 (down from 34,200 twelve months ago, –17%)
**ICP:** VP HR, HR Directors at companies with 500–2,000 employees in professional services and healthcare

**Sample Input Data Snippet:**
Top Queries (last 90d):
1. "hr software for mid-market" — position 6.2 | 312 clicks | 4,800 impressions | 6.5% CTR
2. "employee onboarding software" — position 14.4 | 89 clicks | 3,200 impressions | 2.8% CTR
3. "meridian hr review" — position 1.1 | 540 clicks | 560 impressions | 96.4% CTR
4. "hr compliance software" — position 28.7 | 14 clicks | 1,900 impressions | 0.7% CTR

Core Web Vitals: LCP 4.2s mobile (FAIL), INP 180ms (PASS), CLS 0.03 (PASS)
Crawl errors: 47 broken internal links, 12 redirect chains (3+ hops), 6 noindexed pricing variants

**Sample Output Excerpt (Section 1 — Organic Health Scorecard):**
ORGANIC HEALTH SCORECARD — MERIDIAN HR

Technical Foundation: 5/10
LCP of 4.2s on mobile is a critical failure — Google's threshold is 2.5s. Combined with 47 broken 
internal links and 12 redirect chains diluting link equity, the technical foundation is actively 
suppressing rankings. Estimated traffic recovery from fixes alone: +8-12% within 90 days.

Keyword Position Distribution:
- Top 3: 8% of tracked keywords (brand-heavy)
- 4-10: 14% (4 commercial terms ready for top-3 push)
- 11-20: 22% (HIGHEST OPPORTUNITY ZONE — 9 terms within striking distance)
- 21-50: 31%
- 51+: 25%

Overall Grade: C+
Meridian HR's organic channel is underperforming relative to its domain authority (DR 52). 
The –17% traffic decline correlates with Google's March 2024 core update penalizing thin 
service pages, combined with a technical regression (LCP degradation) in Q3. The keyword 
opportunity set is strong — 9 commercial terms in positions 11-20 represent recoverable 
pipeline. Priority: Fix LCP + refresh 6 middle-funnel pages before Q2.

P0 FIX: Resolve LCP regression on top 10 organic landing pages. Estimated impact: 
+1,800 sessions/month. Effort: Medium (dev + image optimization). Timeline: 3 weeks.

KEYWORD QUICK WIN TABLE (top 3 of 10):
| Keyword | Pos | Vol | Intent | Action | Est. Δ Clicks |
|---------|-----|-----|--------|--------|---------------|
| employee onboarding software | 14 | 2,900 | Commercial | Add comparison table, FAQ schema, update pub date | +180/mo |
| hr software mid-market | 19 | 1,800 | Commercial | Internal link boost from 3 high-DR pages + CTA above fold | +95/mo |
| hr compliance checklist | 17 | 1,400 | Informational→Commercial | Embed interactive checklist tool, add product CTA | +70/mo |

## Success Metrics

| Metric | Threshold for "Good Output" |
|--------|----------------------------|
| Specificity of recommendations | Every action includes a keyword, URL, or technical ticket — no vague "improve content quality" |
| Traffic impact estimates | Every recommendation has a quantified estimate (even if ranged) |
| Prioritization quality | P0 fix is clearly identified and isolated from the 90-day plan |
| Keyword opportunity accuracy | Quick Win keywords are 8-20, not already top 5 or below 50 |
| Technical issue completeness | At least 5 technical issues identified with priority scores |
| Executive summary readability | A VP of Marketing with no SEO background can understand it in 60 seconds |
| Dashboard spec completeness | All 5 primary KPIs and 5 secondary metrics defined with data sources |

## Related Prompts

- `../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Marketing-Attribution-ROI-Engine.md`
- `../../05_Analytics-&-Marketing-Operations/Campaign-Performance-Analysis/Paid-Media-Cross-Channel-Performance-Intelligence-Engine.md`
- `../../03_Content-&-Creative/Blog-&-Article-Writing/Programmatic-SEO-Content-Factory.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/SEO-Lead-Generation.md`

## Integration Tips

**Google Search Console + Looker Studio:**
Use GSC Data Studio connector to pipe the output of this prompt's dashboard spec directly into a live report. Refresh daily. Share with CMO as a read-only link.

**HubSpot:**
Tag all HubSpot contacts by `Original Source = Organic Search`. Use the organic-attributed pipeline section's CVR estimates to build a HubSpot report that shows closed-won revenue by organic landing page (requires `First Page Seen` property).

**GA4:**
Create a custom Exploration in GA4: Segment by `First user source = google / organic`, break down by Landing Page, and map to Conversions. Export monthly to validate the pipeline attribution model in Section 8.

**Ahrefs / SEMrush API (Zapier or Make):**
Schedule a weekly automated export of your tracked keyword rankings → Google Sheet. Use Google Sheets' AI features or a Claude API call to auto-generate a weekly delta report using Section 3's Keyword Opportunity Matrix format.

**Jira / Linear:**
Copy the Section 5 Technical Priority Queue directly into Jira. Use the Priority Score as the story points proxy. Tag tickets with `seo-technical` label for sprint planning visibility.

**Slack (weekly digest):**
Use Make or Zapier to pull GSC data every Monday → run through Claude API using the Quick Copy-Paste prompt → post summary to #marketing-analytics Slack channel. Full automation: zero human editing required.

## Troubleshooting

**Problem: The output is too generic (e.g., "improve page speed" without specifics)**
Fix: Paste actual data into the prompt. The engine needs real numbers — even rough ones (e.g., "LCP ~4s, no exact score") produce dramatically more specific outputs than empty placeholders. At minimum, provide top 10 GSC queries with position and clicks.

**Problem: The keyword opportunity matrix recommends terms that aren't relevant to our ICP**
Fix: Add a "Keyword Exclusion List" and an "Intent Filter" to your input. Example: "Exclude any keywords with informational-only intent. Prioritize only commercial and transactional intent queries for VP HR and HR Director roles."

**Problem: The 30/60/90 day plan tasks are too many to execute**
Fix: Add this constraint to the prompt: "Limit the 90-day roadmap to a maximum of 3 tasks per phase. Each task must be completable by a team of 2 in one sprint (2 weeks). Eliminate anything that requires more than 20 dev hours."

## Version History
- v1.0: Initial creation (auto-generated)
