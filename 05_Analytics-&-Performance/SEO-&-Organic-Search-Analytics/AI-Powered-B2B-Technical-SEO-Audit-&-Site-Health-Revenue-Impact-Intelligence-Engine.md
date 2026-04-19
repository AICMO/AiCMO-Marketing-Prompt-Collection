# AI-Powered B2B Technical SEO Audit & Site Health Revenue Impact Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** technical-seo, site-health, core-web-vitals, crawlability, indexation, b2b, seo-audit, page-speed, schema-markup, revenue-impact

## Overview
This engine runs a structured, AI-automatable technical SEO audit that translates site health issues into lost pipeline and revenue — not just "errors to fix." Use it when organic traffic is stagnant despite strong content, when rankings fluctuate without explanation, or when you need to prioritize a technical SEO backlog by revenue impact rather than issue count.

## Quick Copy-Paste Version

You are a senior technical SEO strategist specializing in B2B SaaS websites. Your client's organic traffic has plateaued or is declining despite ongoing content investment, and you suspect underlying technical issues are suppressing rankings.

Company profile:
- Industry: [e.g., cybersecurity SaaS / data infrastructure / HR technology]
- CMS/Hosting: [e.g., WordPress on WP Engine / Webflow / Next.js on Vercel / HubSpot CMS]
- Monthly organic sessions: [e.g., 22,000/month]
- Average contract value: [e.g., $42,000 ACV]
- Site size: [e.g., ~800 indexed pages, 4,000 total crawled URLs]
- Core Web Vitals status: [e.g., "Google Search Console shows 68% of URLs are 'Poor' for LCP"]
- Primary complaint: [e.g., "Rankings for our 15 highest-intent commercial keywords dropped 3–6 positions over the last 90 days and we can't identify why"]

Conduct a complete technical SEO audit and revenue-impact analysis that includes:

1. CRAWLABILITY & INDEXATION AUDIT: Identify the exact issues preventing Google from efficiently discovering and indexing your highest-value pages:
   - Crawl budget waste: Which URL patterns (faceted navigation, session parameters, duplicate paginated pages, filtered URL variants) are consuming crawl budget without contributing to rankings — and how to block them via robots.txt or canonical tags
   - Index bloat analysis: How many of your indexed URLs have fewer than 300 words, zero backlinks, and zero organic clicks in the last 90 days in GSC? These are "indexation dead weight" pages — calculate the ratio and recommend a consolidation approach (noindex, canonical, 301, or delete + redirect)
   - Orphan page detection: Identify pages with no internal links pointing to them — these are invisible to both users and crawlers. Provide a prioritized list of high-value orphan pages that need internal link injection
   - XML sitemap health check: Confirm sitemap only includes indexable canonical URLs, is submitted to GSC, returns 200 status codes, and contains no URLs blocked by robots.txt

2. CORE WEB VITALS REVENUE IMPACT CALCULATION: Translate CWV scores into pipeline impact:
   - Largest Contentful Paint (LCP): For each landing page with LCP > 4 seconds, estimate the conversion rate depression using Google's benchmark: every 1-second LCP improvement increases conversions by 7%. Calculate: "Pages X, Y, Z have LCP of 5.2s. Fixing to <2.5s is worth an estimated [N] additional demo requests per month at your current traffic volume."
   - Cumulative Layout Shift (CLS): Identify which ad insertions, late-loading fonts, or dynamic content blocks cause layout instability on your highest-traffic pages — and the specific CSS fix (min-height reservations, font-display: swap, image dimension attributes)
   - Interaction to Next Paint (INP): Flag JavaScript-heavy pages where user interactions (form submissions, navigation clicks) take >200ms to respond — and whether the fix is code-splitting, lazy loading third-party scripts, or backend API optimization

3. TECHNICAL ARCHITECTURE ASSESSMENT: Evaluate the structural factors suppressing ranking potential:
   - Internal link equity audit: Map your internal link distribution using a crawl tool export. Identify (a) pages with too many outbound internal links (>100 on a single page — dilutes equity), (b) high-value commercial pages with fewer than 5 internal links pointing to them, (c) the "orphan cluster" — groups of pages with no path to the homepage in fewer than 3 clicks
   - Duplicate content diagnosis: Find exact-match and near-duplicate pages created by parameter variations, trailing slashes, HTTP vs HTTPS, www vs non-www, and printer-friendly page variants. Specify the canonical tag implementation for each pattern.
   - Structured data / schema markup gaps: Compare your current schema implementation against what competitors rank with for your 10 highest-value keyword types. For B2B SaaS: Software Application, FAQPage, Article, BreadcrumbList, and Organization schema are baseline. Identify which pages are missing schema that could earn rich snippets or improve AI search visibility.
   - Hreflang errors (if multilingual): Identify missing return tags, incorrect language codes, and pages included in hreflang that return non-200 status codes.

4. SITE SPEED & RENDERING AUDIT: Diagnose the specific performance blockers:
   - Render-blocking resource identification: List every render-blocking CSS and JavaScript file loading in the <head> with estimated delay. Provide the exact defer/async attribute or preload hint fix for each.
   - Third-party script impact: Calculate the total page weight and LCP delay contributed by marketing tags (HubSpot tracking, Intercom, Drift, Segment, Google Tag Manager container). Recommend script loading sequence and GTM tag firing rules to reduce impact.
   - Image optimization gaps: Identify pages where images lack width/height attributes, use JPEG instead of WebP/AVIF, exceed 200KB, or lack lazy loading for below-fold images. Calculate total potential page weight reduction.
   - Server response time (TTFB): If TTFB > 600ms, diagnose whether the cause is hosting infrastructure, database query latency, uncached dynamic pages, or CDN misconfiguration — and provide tier-appropriate solutions.

5. PRIORITIZED REMEDIATION BACKLOG: Output a revenue-sorted fix list:
   - CRITICAL (fix within 2 weeks — blocking revenue): Issues that directly prevent high-value pages from being indexed or cause failed crawls
   - HIGH (fix within 30 days — suppressing rankings): CWV failures on commercial pages, internal link equity gaps on bottom-of-funnel content, structured data errors on product pages
   - MEDIUM (fix within 90 days — efficiency improvements): Index bloat cleanup, image optimization, third-party script consolidation
   - LOW (document and monitor): Minor schema gaps, informational page speed issues, low-traffic page optimizations

For each issue: Name → Revenue Impact Estimate → Specific Fix → Implementation Complexity (hours) → Who Fixes It (SEO specialist / developer / designer / CMS editor).

Output every section with specific diagnostic queries, fix specifications, and revenue-impact calculations. Every recommendation must be immediately actionable by a developer or SEO specialist without additional research.

## Advanced Customizable Version

ROLE: You are a Principal Technical SEO Architect with 12+ years of experience auditing and optimizing B2B SaaS websites with 500–50,000 pages. You have deep expertise in Googlebot crawl behavior, Core Web Vitals optimization, JavaScript rendering (client-side vs. server-side vs. hybrid rendering and their SEO implications), structured data strategy, and technical debt prioritization for revenue impact. You understand that for B2B SaaS, the highest-value pages are typically: pricing pages, product feature pages, comparison/alternative pages, and high-intent solution category pages — and that technical issues on these specific pages have outsized pipeline impact compared to blog content issues. You also know that the ROI of technical SEO is almost always understated because it's presented as "errors fixed" rather than "revenue unlocked," and your job is to rebuild that narrative for CMOs and CFOs.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Category: [e.g., AI-powered contract intelligence SaaS / B2B sales acceleration platform / enterprise identity governance]
- ARR / Revenue Stage: [e.g., $18M ARR, Series B / $75M ARR, Series D]
- Average Contract Value: [e.g., $55,000 ACV / $280,000 ACV enterprise]
- Sales Cycle Length: [e.g., 60–90 days mid-market / 6–12 months enterprise]
- Primary Buyer: [e.g., VP Legal & General Counsel / CRO and VP Sales / CISO and VP IT]
- CMS Platform: [e.g., WordPress 6.x + Elementor / Webflow / Next.js 14 App Router / HubSpot CMS Professional / Contentful + Gatsby]
- Hosting / CDN: [e.g., WP Engine + Cloudflare / Vercel Edge Network / AWS CloudFront / Fastly]
- Site Architecture: [e.g., "Marketing site at www.company.com (800 pages), docs at docs.company.com, blog as /blog subdirectory, pricing at /pricing, 12 product feature pages, 8 integration pages, 6 comparison pages"]
- Rendering Method: [Server-side rendering / Client-side SPA (React/Vue/Angular) / Static site generation / Hybrid ISR]
- Google Search Console Access: [Yes — full access / Yes — restricted / No]
- Crawl Tool Available: [Screaming Frog SEO Spider / Sitebulb / Botify / Lumar / GSC only]
- Core Web Vitals Current Status: [e.g., "GSC Field Data: 34% Good LCP, 71% Good INP, 88% Good CLS — majority of failures on blog archive and feature pages"]
- Indexed Page Count (GSC): [e.g., 1,847 URLs indexed]
- Crawled-but-not-indexed Count (GSC): [e.g., 312 URLs — 'Discovered - currently not indexed': 89, 'Crawled - currently not indexed': 223]
- Monthly Organic Sessions: [e.g., 31,000/month]
- Organic Traffic Trend: [e.g., "Down 22% over 6 months — we had a site migration to Next.js in Q3 and traffic has not recovered"]
- Top Technical Pain Points (as you understand them): [e.g., "JavaScript rendering issues — our pricing page and feature pages are not being indexed correctly in GSC coverage report. Intercom and HubSpot tracking scripts are adding 2.1 seconds to LCP on mobile. We have 400+ 'Crawled - currently not indexed' URLs that we don't understand."]
- Developer Resources Available: [e.g., "1 frontend engineer available 20% time / Full-stack engineering team with dedicated 2-week sprint capacity / No dev resources — must use CMS-native tools only"]
- Marketing Analytics Stack: [e.g., GA4 + BigQuery / GA4 standard / Heap / Mixpanel]
- Competitor Technical Benchmarks (if known): [e.g., "Competitor A has PageSpeed mobile score of 82 vs. our 41. Competitor B has 3,200 schema-enhanced pages vs. our 180."]

---

PHASE 1: CRAWL BUDGET & INDEXATION EFFICIENCY ANALYSIS

1.1 CRAWL BUDGET DIAGNOSTIC

Calculate the theoretical crawl budget for your site based on:
- Domain Authority tier (estimated Googlebot crawl frequency for DA 20-40 / 40-60 / 60-80 / 80+)
- Crawl demand signals: How many of your URLs have external backlinks pointing to them? How many received organic clicks in the past 90 days in GSC?
- Crawl budget "leaks" by category: Identify every URL pattern that consumes crawl budget without providing ranking value:
  - Faceted navigation combinations (e.g., /blog?category=X&author=Y&tag=Z)
  - Paginated archive pages beyond page 3 (/blog/page/47/)
  - URL parameters from marketing tools (utm_source, hsa_acc, fbclid carried into site pages)
  - Internal search result pages (/search?q=...)
  - Thin auto-generated pages (tag pages, author archives, date archives in WordPress)
  - Session-based URL variants (/page?session_id=abc123)

For each pattern: Estimated URL count → Recommended fix (robots.txt Disallow / canonical → preferred URL / noindex meta tag) → Implementation method for your specific CMS.

1.2 INDEXATION HEALTH MATRIX

Analyze GSC Index Coverage report and classify every non-indexed URL into actionable buckets:

BUCKET A — Fix Immediately (high-value pages Google can't or won't index):
- "Crawled — currently not indexed": Pages Googlebot visited but declined to index. Primary causes for B2B SaaS: thin content (under 600 words with no substantive unique value), near-duplicate to another indexed page, low E-E-A-T signals on product/feature pages, or JavaScript rendering failure (Googlebot sees blank page or loading spinner instead of content).
- "Discovered — currently not indexed": Pages in sitemap but Googlebot hasn't prioritized crawling. Fix: Increase internal link pointing to these pages from high-authority pages (homepage, pricing, navigation).
- "Duplicate, Google chose different canonical than user": Your canonical tag points to URL A but Google decided URL B is the authoritative version. This is a signal that URL B has stronger signals — either consolidate to Google's preferred URL or fix the signals on your preferred canonical.

BUCKET B — Intentional and Correct (document but don't fix):
- "Excluded by 'noindex' tag": Confirm every noindexed URL is intentionally excluded (thank-you pages, internal search, staging pages, gated content behind login). Create a documented noindex registry.
- "Blocked by robots.txt": Verify no high-value pages are accidentally blocked.

BUCKET C — Clean Up (removing indexation dead weight):
- Pages indexed for 12+ months with zero clicks, zero impressions, and zero backlinks in GSC. These are "zombie pages" — they dilute site quality signals. Recommended action tiered by page type: thin blog posts (301 → related content or category) / outdated event pages (301 → events hub) / superseded product pages (301 → current product page) / truly orphaned low-value pages (delete + 410 Gone).

1.3 XML SITEMAP HEALTH AUDIT

Validate sitemap against 8 technical requirements:
1. Returns HTTP 200 status code when fetched directly
2. Contains ONLY canonicalized, indexable URLs (no noindexed pages, no paginated variations, no parameter URLs)
3. Submitted and accepted in Google Search Console without errors
4. Last-modified dates are accurate and update when content changes (not static)
5. Split into logical sub-sitemaps if total URL count exceeds 10,000 (sitemap index file)
6. Image and video sitemaps exist if site has significant visual/video content that should rank
7. Hreflang sitemap (or hreflang in HTML <head>) for multilingual sites
8. No URLs in sitemap that return 301 redirects — all redirecting URLs should be updated to their final destination

---

PHASE 2: CORE WEB VITALS REVENUE IMPACT MODEL

2.1 COMMERCIAL PAGE CWV PRIORITIZATION

Map every CWV metric failure to its revenue pathway. For B2B SaaS, apply this priority tier to CWV remediation:

TIER 1 — Revenue-Critical Pages (fix LCP, INP, CLS here first, regardless of traffic volume):
- Pricing page (/pricing)
- Product/feature pages that target commercial-intent keywords (e.g., /product/contract-management, /features/ai-insights)
- Comparison/alternative pages (/vs/competitor, /alternatives/competitor)
- Demo request / free trial landing pages
- High-intent solution category pages (/solutions/legal-teams, /platform/security)

TIER 2 — Pipeline-Influencing Pages (fix after Tier 1):
- Top 20 organic traffic blog posts
- Case study hub and individual case study pages
- Integration pages that rank for "[Your Product] + [Integration]" commercial searches
- Homepage (high brand search volume but lower commercial intent)

TIER 3 — Fix for Quality Signal, Not Direct Conversion:
- Blog posts driving informational traffic
- About, team, careers pages
- Documentation (if on marketing domain)

2.2 LCP DIAGNOSTIC FRAMEWORK

For each Tier 1 and Tier 2 page failing LCP (>2.5s):

Step 1 — Identify LCP Element: Use Chrome DevTools Performance panel or PageSpeed Insights API to identify whether the LCP element is: (a) a hero image, (b) a background-image CSS property, (c) an H1 or large text block, or (d) a video poster frame. Each has a different optimization path.

Step 2 — Diagnose LCP Delay Components (Google's four LCP sub-parts):
- Time to First Byte (TTFB): If >600ms, the problem is server response — check hosting, caching, database query time, or CDN cache-hit rate
- Resource Load Delay: Time from TTFB to when the LCP resource starts loading — if high, the image/font is discovered late in the HTML (typical for background-image or dynamically injected hero images). Fix: Add <link rel="preload"> hint in <head>
- Resource Load Duration: Time to download the LCP resource — if high, the image is too large (>400KB), wrong format (JPEG instead of WebP), or served without CDN. Fix: Compress, convert to WebP/AVIF, serve from CDN edge node
- Render Delay: Time from resource load completion to LCP element appearing on screen — if high, render-blocking scripts or CSS are preventing paint. Fix: Defer non-critical scripts, inline critical CSS

Step 3 — Calculate Revenue Impact:
Using Google's research benchmark (1-second LCP improvement = 7% conversion rate lift):
- Current LCP: [X]s → Target LCP: 2.5s or below → Improvement: [X - 2.5]s → Estimated CR lift: [Y]%
- Monthly Tier 1 page visitors from organic: [N visitors]
- Current demo request CR: [Z%]
- Projected additional demo requests/month from LCP fix: N × Z% × Y% = [result]
- At your MQL-to-close rate and ACV: Estimated pipeline unlocked per month = [result × pipeline math]

2.3 INP REMEDIATION (B2B SaaS-SPECIFIC)

JavaScript-heavy B2B SaaS sites (built on React, Vue, Angular, or Next.js CSR) commonly fail INP due to:

CAUSE 1 — Long Tasks on Main Thread: Third-party marketing scripts (HubSpot, Intercom, Drift, Segment, Heap) executing synchronously on user interaction. Diagnostic: Run Chrome DevTools Performance trace during a form click and identify tasks >50ms blocking the main thread. Fix: Move marketing scripts to Web Workers, implement partytown.js for third-party script isolation, or gate Intercom/Drift loading behind a user gesture.

CAUSE 2 — Unoptimized React Re-renders: Forms, navigation menus, or pricing calculators triggering full component tree re-renders on every keystroke or interaction. Fix: Implement React.memo, useMemo, useCallback, or virtualization (react-window) for list components.

CAUSE 3 — Synchronous API Calls on Interaction: Demo request form submission triggers a synchronous API call to HubSpot/Salesforce before confirming submission. Users see frozen UI for 800ms–3s. Fix: Implement optimistic UI updates — show confirmation immediately, process API call in background.

CAUSE 4 — GTM Container Size: Google Tag Manager containers with 40+ tags firing on page interaction. Each tag evaluation adds latency. Fix: Audit GTM container, remove unused tags (common to find 15–25% of tags are orphaned), implement trigger conditions to fire tags only on relevant page types.

---

PHASE 3: INTERNAL LINK EQUITY ARCHITECTURE

3.1 EQUITY DISTRIBUTION AUDIT

Run a full crawl export and map internal link equity flow:

STEP 1 — Identify your "authority source" pages: Pages with the most external backlinks pointing to them (your most authoritative pages). For most B2B SaaS sites, this is: homepage, a few high-ranking blog posts, pricing page, and one or two comparison pages. Export from Ahrefs/Semrush: "Best by Links" filtered to your domain.

STEP 2 — Map equity flow to commercial pages: From each authority source, count the number of internal links leading to your Tier 1 commercial pages (pricing, product, comparison, demo request). Benchmark: Each Tier 1 commercial page should receive internal links from at least 10 other pages on the site with meaningful surrounding anchor text (not just "click here" or "learn more").

STEP 3 — Identify equity black holes: Pages with high inbound internal links that lead to dead ends (no outbound internal links to other pages). Classic example: A blog post with 50 internal links pointing to it, but it only links back to the homepage. This is a "traffic trap" — visitors read the post and leave, and equity doesn't flow forward to commercial pages. Fix: Add 2–3 contextual internal links from high-traffic informational posts to related commercial pages using intent-matching anchor text.

STEP 4 — Click depth analysis: Map how many clicks it takes to reach your highest-value commercial pages from the homepage. B2B SaaS benchmark: Pricing, product, and demo pages should be reachable in ≤2 clicks from homepage. If any Tier 1 page requires 4+ clicks, add it to the primary navigation or implement a persistent CTA/sidebar link.

3.2 CONTEXTUAL INTERNAL LINKING IMPLEMENTATION PLAN

For your top 20 content pages by organic traffic, provide a specific internal linking action:
- Page URL
- Current outbound internal links to Tier 1 commercial pages (count and targets)
- Gap: Missing links to which commercial pages
- Recommended anchor text (using buyer-intent language, not generic CTAs)
- Implementation: HTML link to add, exact placement in content (after paragraph X, before conclusion, in sidebar)

---

PHASE 4: STRUCTURED DATA & SCHEMA STRATEGY

4.1 B2B SAAS SCHEMA IMPLEMENTATION MATRIX

Map every schema type to the pages where it creates measurable SEO value:

SOFTWARE APPLICATION SCHEMA — Deploy on: all product feature pages, pricing page, homepage
Required properties: name, description, applicationCategory ("BusinessApplication"), operatingSystem, offers (price/priceCurrency for each plan), aggregateRating (if you have G2/Capterra reviews to cite), screenshot
Revenue impact: Enables rich results in Google and increases brand citation likelihood in AI search responses (ChatGPT, Perplexity, Claude) — these AI systems use structured data to understand product capabilities and recommend solutions

FAQPAGE SCHEMA — Deploy on: pricing page FAQ sections, comparison pages, product feature pages with FAQ sections
Revenue impact: FAQ rich results take 2–3x the SERP real estate of standard results, increasing CTR by 20–30% for bottom-of-funnel searches like "How does [Your Product] compare to [Competitor]?" or "What does [Your Product] cost?"

ARTICLE SCHEMA — Deploy on: all blog posts and thought leadership content
Required: datePublished, dateModified (critical — Google uses this to assess content freshness), author (linked to Person schema with sameAs pointing to LinkedIn profile), publisher (Organization schema)
Common mistake: Setting dateModified to today's date on old content without actual content updates — this is a signal manipulation Google now detects and may penalize

REVIEW / AGGREGATE RATING SCHEMA — Deploy on: homepage, pricing page, product pages
Source: G2 or Capterra review data (you must have permission to display this data)
Revenue impact: Star ratings in SERP results increase CTR by 15–25% for competitive queries

BREADCRUMB SCHEMA — Deploy on: all pages except homepage
Enables breadcrumb display in SERPs, helping users understand site structure and improving click-through rates for nested content (/blog/category/article-title)

ORGANIZATION SCHEMA — Deploy on: homepage only
Required: name, url, logo, sameAs (LinkedIn, Twitter/X, Crunchbase, G2 profile, Glassdoor), contactPoint, address
Revenue impact: Directly feeds knowledge panel in Google and increases brand entity recognition in AI search systems — when Perplexity or ChatGPT recommend solutions, they draw on Organization schema to understand and describe your company accurately

4.2 SCHEMA IMPLEMENTATION AUDIT

For your current schema deployment:
- Run site:yourcompany.com through Google's Rich Results Test API (or manually test 10 representative pages)
- Identify: (a) pages with no schema, (b) pages with schema validation errors (incorrect property types, missing required fields), (c) pages with outdated schema (SoftwareApplication schema without Offers — critical for pricing pages)
- For JavaScript-rendered pages: Confirm schema is in the initial HTML response, not injected by JavaScript after page load. Googlebot does not always execute JavaScript before assessing structured data.

---

PHASE 5: REVENUE-SORTED REMEDIATION BACKLOG

Output a complete prioritized backlog with this structure for each issue:

| Priority | Issue | Affected Pages | Revenue Impact Estimate | Specific Fix | Effort (Dev Hours) | Owner | Sprint Target |
|----------|-------|---------------|------------------------|--------------|-------------------|-------|---------------|

CRITICAL TIER — Examples:
- Pricing page failing JavaScript rendering (Googlebot sees blank page): Affects direct-to-demo organic conversions. Fix: Implement server-side rendering for pricing page or pre-render via Next.js static generation. Effort: 8–16 dev hours.
- 3 comparison pages not indexed ("Crawled — currently not indexed"): Affects highest-intent competitive queries. Fix: Increase word count to 1,200+, add unique data (pricing tables, feature comparison matrix), add 8+ internal links from related content. Effort: 4 hours SEO content specialist.
- LCP of 5.8 seconds on mobile for /pricing: Fix: Preload hero image, convert to WebP, defer Intercom script. Effort: 4 dev hours. Revenue impact: Estimated 14% conversion rate improvement = 6 additional demo requests/month at current traffic.

HIGH TIER — Examples:
- 47 blog posts with zero internal links to Tier 1 commercial pages
- SoftwareApplication schema missing from 12 product feature pages
- GTM container with 52 tags, 19 of which appear orphaned

MEDIUM TIER — Examples:
- 280 blog images missing width/height attributes (CLS risk)
- 94 pages with duplicate meta descriptions
- XML sitemap contains 23 URLs returning 301 redirects

LOW TIER — Examples:
- Missing Article schema dateModified on 15 posts
- 8 tag pages consuming crawl budget (low traffic, low value)
- 3 pages with slightly long title tags (62–65 characters vs. recommended <60)

---

PHASE 6: EXECUTIVE REPORTING — TRANSLATING TECHNICAL SEO TO REVENUE LANGUAGE

6.1 CMO-READY TECHNICAL SEO IMPACT SUMMARY

Provide a 5-bullet summary written in CFO/CMO language:

- "Our pricing page takes 5.8 seconds to load on mobile. Google's research shows that every 1-second improvement lifts conversion rates by 7%. Fixing this to under 2.5 seconds is projected to generate 8 additional demo requests per month — at our 22% close rate and $42K ACV, that's approximately $740K in additional pipeline per month from a one-time 8-hour engineering investment."
- "312 URLs are in our sitemap but not indexed by Google. After analysis, 47 of these are high-intent product and comparison pages that should be driving commercial traffic. We're essentially invisible for those searches — fixing indexation is our highest-leverage SEO action this quarter."
- "Our internal link structure sends 80% of link equity to the homepage and top navigation. Our pricing and comparison pages — where buyers make purchase decisions — receive fewer than 3 internal links each. A 2-week content linking sprint can increase equity flow to commercial pages by an estimated 4x."
- "Competitors rank with Software Application and FAQ schema on every product page. We have no structured data on 94% of our site. Schema-enabled pages earn 25–30% higher click-through rates for the same ranking position — this is a free ranking advantage we're leaving unclaimed."
- "Third-party marketing scripts (HubSpot, Intercom, Segment) add 2.1 seconds to our average page load. Implementing async loading for these scripts requires 6 development hours and would improve our Core Web Vitals score for 89% of affected pages."

## Example Input/Output

**Input Example:**
- Company: Nexivo — AI-powered procurement intelligence SaaS
- ACV: $68,000 | ARR: $24M | Series B
- CMS: Next.js 14 App Router on Vercel
- GSC data: 1,240 indexed pages; 187 "Crawled — currently not indexed"; 34% of URLs "Poor" CWV
- Problem: "We migrated from WordPress to Next.js 8 months ago. Organic traffic dropped 38% and has not recovered. Our /pricing page and 8 /solutions/ pages show 'Crawled — currently not indexed' in GSC. LCP on mobile is 6.2 seconds on our homepage. We have no schema markup anywhere on the site."

**Output Example (excerpt):**

**CRITICAL ISSUE #1 — JavaScript Rendering Failure (Pricing + Solutions Pages)**
Root Cause: Next.js pages using client-side rendering (CSR) are not being fully rendered by Googlebot before the indexation decision. GSC is seeing skeleton HTML without content. Confirm by fetching /pricing in GSC URL Inspection — if rendered content is missing, this is a CSR issue.
Fix: Convert /pricing and /solutions/* to Server Components (Next.js 14 default) or add generateStaticParams for static pre-rendering. Both approaches ensure Googlebot receives full HTML on first request.
Effort: 12–20 dev hours (requires RSC architecture understanding)
Revenue impact: These 9 pages target your highest-commercial-intent queries. Conservative estimate: Re-indexing generates 800 additional monthly organic sessions at a 3% demo request rate = 24 demo requests/month × 22% close × $68K ACV = **$359K additional monthly pipeline potential.**

**CRITICAL ISSUE #2 — LCP 6.2s on Homepage (Mobile)**
LCP Element: Hero section background-image (1.8MB JPEG, loaded via CSS, not preloaded)
Diagnosis breakdown: TTFB 280ms (acceptable for Vercel Edge) → Resource Load Delay: 2.4s (CSS background-image discovered late, no preload hint) → Load Duration: 2.8s (1.8MB uncompressed) → Render Delay: 0.7s (3 render-blocking script tags)
Fix sequence: (1) Convert hero to <img> tag or add <link rel="preload" as="image"> in _document.tsx head → (2) Convert to WebP at 85% quality (target: <200KB) → (3) Add priority prop to Next.js <Image> component → (4) Move Intercom script to after user gesture
Estimated result: LCP → 2.1s (from 6.2s) = 28.7% conversion rate improvement
Monthly homepage organic visitors: ~4,200 → current demo CR: 1.2% → projected lift: 1.54% → additional monthly demos: ~14 → pipeline: ~$1.1M

**SCHEMA IMPLEMENTATION PLAN:**
Priority 1 — Add SoftwareApplication schema to /pricing, all /solutions/* pages, all /features/* pages (JSON-LD in <head> via Next.js Metadata API). Include Offers property with plan pricing.
Priority 2 — Add FAQPage schema to pricing page FAQ section (4 questions already present, just need schema layer).
Priority 3 — Add Organization schema to homepage with sameAs pointing to G2, LinkedIn, Crunchbase profiles.
Estimated effort: 6 dev hours for schema layer across all pages using Next.js generateMetadata.
Expected outcome: Rich result eligibility for 18 product and comparison pages within 4–8 weeks of implementation.

## Success Metrics

- Percentage of Tier 1 commercial pages achieving "Good" CWV (target: >90% within 90 days of fixes)
- Crawled-but-not-indexed URL count in GSC (target: <50 after cleanup, with all Tier 1 pages indexed)
- Average internal link count pointing to Tier 1 commercial pages (target: >10 per page)
- Schema-enhanced pages as percentage of total (target: >80% of commercial pages within 60 days)
- Organic demo requests from Tier 1 commercial pages (monthly tracking — primary revenue KPI)
- Core Web Vitals score improvement in GSC Field Data report (90-day lag from fix to field data update)
- Crawl efficiency ratio: Valuable indexed pages / total crawled URLs (target: >65%)

## Related Prompts

- [AI-Powered B2B Organic Search SEO Performance Analytics & Pipeline Revenue Attribution Intelligence Engine](./AI-Powered-B2B-Organic-Search-SEO-Performance-Analytics-&-Pipeline-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B SEO Competitive Gap Analysis & Organic Market Share Capture Intelligence Engine](./AI-Powered-B2B-SEO-Competitive-Gap-Analysis-&-Organic-Market-Share-Capture-Intelligence-Engine.md)
- [CRO Conversion Rate Optimization Intelligence Engine](../../03_Content-&-Creative/Ad-&-Website-Copywriting/CRO-Conversion-Rate-Optimization-Intelligence-Engine.md)
- [AI-Powered GEO Performance Analytics & AI Search Share of Voice Intelligence Engine](../GEO-&-AI-Search-Analytics/AI-Powered-GEO-Performance-Analytics-&-AI-Search-Share-of-Voice-Intelligence-Engine.md)

## Integration Tips

- **Screaming Frog SEO Spider**: Schedule weekly crawls via CLI (screamingfrogseospider --crawl https://yoursite.com --headless --save-crawl --export-tabs "Response Codes,Page Titles,Meta Description,Canonical,Directives,Internal,External") and pipe output to a Google Sheet for automated tracking. Set alerts for new 4xx errors, missing canonical tags, and new noindex tags on commercial pages.
- **Google Search Console API**: Use GSC API to pull weekly indexation status for your Tier 1 URL list. Build a Google Sheets dashboard with Apps Script that alerts via Slack if any Tier 1 page drops out of the index or has a CWV score regression.
- **PageSpeed Insights API**: Automate weekly CWV monitoring for your top 50 URLs using the PSI API (free, no auth required). Feed results into a Looker Studio dashboard that shows LCP, INP, and CLS trends over time per page. Set Zapier alert if any Tier 1 page falls below "Good" threshold.
- **Ahrefs / Semrush API**: Pull weekly internal link counts for Tier 1 commercial pages. Alert if count drops (indicates a content deletion or sitemap change accidentally removed internal link sources). Export "Top Pages" report monthly to track equity distribution changes.
- **GTM / GA4**: Create a custom GA4 dimension for "page technical tier" (Tier 1 commercial / Tier 2 pipeline-influencing / Tier 3 informational) by mapping page paths in a lookup table. This lets you segment all conversion analysis by technical page tier to correlate CWV improvements with conversion rate changes.
- **Notion / Linear**: Import the prioritized remediation backlog directly into your sprint planning tool. Use the provided effort estimates and revenue impact scores as ticket acceptance criteria. Tag every ticket with "Technical SEO" and link to the relevant GSC or PageSpeed data as evidence.

## Troubleshooting

**Problem: GSC shows pages as "Crawled — currently not indexed" but the pages have strong content.**
Solution: The most common hidden cause for B2B SaaS is JavaScript rendering failure — Googlebot's initial crawl passes, but the rendered content is empty or incomplete. Confirm by using GSC URL Inspection → "Test Live URL" → "View Tested Page" → compare the rendered HTML to what a user sees. If the rendered version is blank or shows loading states, the fix is server-side rendering or static pre-rendering, not content improvement. Secondarily, check if the page is too similar to another indexed page (duplicate content) — use a text similarity tool to compare with your closest existing indexed pages.

**Problem: Core Web Vitals "Field Data" in GSC still shows "Poor" 8 weeks after implementing fixes.**
Solution: GSC Field Data uses Chrome User Experience Report (CrUX) data, which is a rolling 28-day average of real user sessions — it lags behind your actual improvements by 4–8 weeks. Verify your fix worked immediately using PageSpeed Insights "Lab Data" (Lighthouse) and Chrome DevTools. If Lab Data shows improvement but Field Data hasn't updated after 10 weeks, the issue may be that your traffic volume on that page is below CrUX's threshold (typically requires 100+ Chrome user sessions per month to populate field data) — in which case GSC will not show field data for that URL regardless of performance.

**Problem: Internal linking sprint was completed but commercial page rankings haven't improved after 6 weeks.**
Solution: Internal link equity changes take 4–12 weeks to be reflected in rankings because Googlebot must re-crawl and re-process the updated pages. Confirm the links are being crawled by checking GSC URL Inspection for your commercial pages — "Discovered via" should now list multiple internal sources. If Googlebot still hasn't re-crawled, manually request indexation via GSC URL Inspection for your Tier 1 commercial pages (limited to ~50 requests per day). If rankings still don't improve after 12 weeks, the issue is competitive — analyze the current top-ranking pages for your target keywords to identify content quality gaps that internal links alone cannot overcome.

## Version History
- v1.0: Initial creation (auto-generated)
