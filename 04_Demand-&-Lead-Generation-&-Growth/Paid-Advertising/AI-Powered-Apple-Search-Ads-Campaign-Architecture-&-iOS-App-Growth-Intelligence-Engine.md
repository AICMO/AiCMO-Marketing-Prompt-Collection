# AI-Powered Apple Search Ads Campaign Architecture & iOS App Growth Intelligence Engine - Complete ASA Strategy for Mobile App User Acquisition

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** apple-search-ads, mobile-app-marketing, user-acquisition, ios, app-store-optimization, performance-marketing, paid-media

## Overview
Architect, launch, and autonomously optimize a full-funnel Apple Search Ads program that drives high-intent iOS app installs at scale — covering campaign structure across all four placements (Search Results, Today Tab, Product Page Ads, Search Tab), bidding strategy, Creative Sets, Custom Product Pages, and SKAdNetwork attribution. Use this engine when you need to build a self-optimizing ASA system that consistently beats target CPA while growing download volume.

## Quick Copy-Paste Version

You are a senior Apple Search Ads strategist and mobile growth expert. Build a complete ASA campaign architecture for the following app:

App Name: [Your App Name]
App Category: [Games / Productivity / Health & Fitness / Finance / Shopping / Other]
Primary goal: [New user installs / Reactivation / In-app purchase / Subscription starts]
Monthly ASA budget: $[Amount]
Target CPA (cost per acquisition): $[X]
Target CPI (cost per install): $[X]
Primary competitor apps: [App 1, App 2, App 3]
Key differentiator: [What makes your app different]
Current MMP: [AppsFlyer / Adjust / Branch / Kochava / None]

Deliver:

1. CAMPAIGN STRUCTURE (placement-separated architecture)
   - Search Results — Exact Match brand + competitor + category campaigns
   - Search Results — Broad Match discovery campaigns
   - Search Tab — Discovery placement for new audience reach
   - Today Tab — Brand awareness for high-intent users browsing the App Store
   - Product Page Ads — Cross-sell targeting users browsing competitor/related apps

2. KEYWORD STRATEGY
   - Tiered keyword list: brand (protect), category (capture), competitor (displace), long-tail (efficiency)
   - Exact Match vs. Broad Match vs. Search Match allocation per campaign
   - Negative keyword exclusion strategy to prevent wasted spend
   - Bid recommendations per keyword tier based on intent signal

3. CREATIVE SETS & CUSTOM PRODUCT PAGES
   - How to map Custom Product Pages (CPP) to keyword intent groups
   - Creative Set configuration per campaign type
   - A/B test framework for CPP screenshot variations
   - Localized CPP strategy for top 3 international markets

4. BIDDING & BUDGET STRATEGY
   - CPT (cost per tap) bid floors and ceilings per campaign type
   - CPA goal configuration for automated bidding campaigns
   - Budget allocation across placements (% split recommendation)
   - Learning phase minimum spend and duration
   - Dayparting / budget pacing rules

5. ATTRIBUTION & MEASUREMENT (SKAdNetwork + ATT)
   - SKAdNetwork conversion value mapping (what events = which value 0–63)
   - MMP postback configuration for Apple Search Ads
   - ATT consent rate optimization tactics
   - iOS 14+ privacy-safe reporting workarounds
   - Incrementality test design for ASA spend validation

6. AUDIENCE TARGETING STRATEGY
   - Apple's demographic and device targeting parameters
   - Returning users vs. new users campaign separation
   - Redownload suppression and exclusion list setup
   - Lookalike equivalent using ASA's "All Users" audience signals

7. 30-DAY LAUNCH PLAN
   - Week 1: Campaign build, tracking validation, brand campaign activation
   - Week 2: Category and competitor campaigns, first creative test
   - Week 3: Broad match discovery scale, CPP performance review
   - Week 4: CPA goal activation on mature campaigns, budget reallocation

Output as an executable campaign brief ready for immediate implementation by a media buyer, growth team, or AI agent.

## Advanced Customizable Version

ROLE: You are an Apple Search Ads performance architect and iOS growth strategist with 10+ years managing $500K–$5M/month ASA programs across consumer apps, B2B SaaS mobile, gaming, fintech, and health tech verticals. You combine App Store algorithm intelligence, direct response bidding psychology, and SKAdNetwork measurement expertise to build acquisition systems that compound efficiency as they scale. You understand how ASA auctions interact with organic App Store rankings and design campaigns to maximize both paid and organic lift simultaneously.

APP CONTEXT:
- App Name: [APP_NAME]
- App Store URL/ID: [URL or Apple ID]
- Business model: [Free-to-play / Freemium / Paid upfront / Subscription / In-app purchases]
- Primary monetization event: [Subscription start / In-app purchase / Registration / Trial activation]
- Average revenue per user (ARPU 90-day): $[X]
- Target payback period: [30 / 60 / 90 / 180 days]
- Target CPA for primary monetization event: $[X]
- Target CPI (cost per install): $[X]
- Monthly ASA budget: $[BUDGET]
- Current App Store rating: [X.X stars / X reviews]
- Current organic install volume (monthly): [X installs]
- Current primary acquisition channels: [Meta / Google UAC / Organic / Other]
- Primary competitors: [App 1 (category leader), App 2, App 3]

AUDIENCE PROFILE:
Primary User:
- Demographics: [Age range / Gender if relevant]
- Device: [iPhone only / iPad only / Both]
- Use context: [When/why they open the app]
- Jobs-to-be-done: [The outcome users hire this app to achieve]
- Strongest purchase motivators: [Speed / Price / Status / Trust / Habit formation]

BUSINESS OBJECTIVES:
- Primary KPI: [CPA for [EVENT] / ROAS / Day-7 retention rate / Subscription CVR]
- Secondary KPI: [Install volume / Share of voice / Organic rank lift]
- Budget constraint: Hard cap at $[X]/month OR flexible up to $[X] if CPA < $[X]
- Geographic priority: [Primary: US/CA/UK / Secondary: AU/DE/FR / Tertiary: Global rollout]

COMPETITIVE CONTEXT:
- Market position: [Category leader / Challenger / Niche specialist]
- Key displacement target: [Competitor app you want to steal users from]
- Unique value vs. competitors: [Your differentiator in one line]
- Current share of voice in App Store search: [High / Medium / Low / Unknown]

TECHNICAL CONTEXT:
- MMP: [AppsFlyer / Adjust / Branch / Kochava / None — direct attribution only]
- Analytics stack: [Amplitude / Mixpanel / Firebase / Custom]
- ATT consent rate: [X%] or [Unknown — optimize from scratch]
- Custom Product Pages built: [X pages targeting X intent groups] or [None yet]
- Creative assets available: [Screenshots only / Screenshots + App Preview video / Full creative suite]

---

DELIVERABLE 1: CAMPAIGN ARCHITECTURE — Full Placement Strategy

Build a campaign architecture that separates intent signals by placement and match type:

TIER 1 — BRAND DEFENSE (Exact Match, Search Results)
- Purpose: Own your brand name, prevent competitor conquesting
- Keywords: [App name], [App name + descriptor], common misspellings
- Bid strategy: High CPT to maintain >95% impression share
- Budget allocation: 10-15% of total ASA budget
- Creative: Brand-specific CPP emphasizing core value prop

TIER 2 — CATEGORY CAPTURE (Exact Match + Broad, Search Results)
- Purpose: Capture users actively searching for your app's category
- Keyword strategy: Category head terms + intent-qualified mid-tail
- Examples for [CATEGORY]: [Category term 1], [Category term 2], [Category term 3 — best-in-class for your category]
- Match type split: 60% Exact Match (control CPT), 40% Broad Match (discovery)
- Bid strategy: CPT floors at $[recommended based on category] — use CPA goal once >100 conversions/week

TIER 3 — COMPETITOR DISPLACEMENT (Exact Match, Search Results)
- Purpose: Intercept users searching for competitor apps
- Keyword targets: [Competitor 1 name], [Competitor 2 name], "[Competitor 1] alternative", "[Competitor 2] vs [Your App]"
- Creative requirement: Custom Product Page with direct competitor comparison messaging
- Bid strategy: Aggressive CPT bids — accept higher CPI for strategic share-of-voice value
- Conversion event: Track quality signals (Day-7 retention, subscription) not just installs

TIER 4 — SEARCH MATCH DISCOVERY (Broad/Search Match, Search Results)
- Purpose: Surface unknown high-performing keywords via Apple's algorithm
- Configuration: Search Match enabled, minimal manual keywords, low CPT floor
- Mining cadence: Weekly search term report review; promote winners to Exact Match
- Budget cap: 15% of total budget until keyword list matures

TIER 5 — BROWSE PLACEMENTS (Today Tab + Search Tab)
- Today Tab: Premium placement for brand awareness; target users not yet in purchase funnel
- Search Tab: High-intent users browsing App Store; complement Search Results campaigns
- Creative requirement: App Preview video required for Today Tab; strong first frame hook
- Budget: 10-20% combined; measure downstream conversion at 7-day window

TIER 6 — PRODUCT PAGE ADS (Competitor + Related App Targeting)
- Purpose: Reach users actively viewing competitor app pages
- Targeting: Competitor apps, complementary apps in adjacent categories
- Creative: CPP optimized for category comparison + social proof
- Budget: 5-10%; pure efficiency play for low-cost brand trial exposure

---

DELIVERABLE 2: KEYWORD STRATEGY FRAMEWORK

For [APP_CATEGORY], build a comprehensive keyword universe organized by intent tier:

BRAND KEYWORDS (Protect — Exact Match):
List: [App name], [App name misspellings], [Founder/Brand association terms if relevant]
Bid floor: [Aggressive — protect impression share at all costs]

CATEGORY KEYWORDS (Capture — Exact + Broad):
Head terms: [2-3 highest volume terms for your category]
Mid-tail: [5-7 intent-qualified terms with strong purchase signal]
Long-tail efficiency: [10-15 specific use-case queries]
Negative keywords: [Terms that drive installs but signal wrong user type — e.g., "free" if you're paid, "kids" if you're adult-focused]

COMPETITOR KEYWORDS (Displace — Exact Match):
Primary targets: [Top 3 competitors + their key product names]
Secondary targets: [2-3 mid-tier competitors worth intercepting]
Bid strategy: Accept 20-30% higher CPT vs. category keywords; measure quality not just volume

SEASONAL/EVENT KEYWORDS (Opportunistic):
Identify: [Seasonal triggers for your category — New Year's for fitness, tax season for finance, etc.]
Pre-build campaigns: Activate 2 weeks before peak season with elevated budgets

KEYWORD HYGIENE:
- Weekly: Review Search Match reports, promote 5+ performing terms, add negatives for wasted spend
- Monthly: Pause keywords with >$[X] CPA and <0.5% CVR over 30-day window
- Quarterly: Full competitive keyword audit using ASA Search Popularity data + third-party ASO tools

---

DELIVERABLE 3: CUSTOM PRODUCT PAGES — Conversion Architecture

Build a CPP strategy that aligns landing experience to search intent:

CPP 1 — DEFAULT (Brand and General Category Traffic):
Message: Core value proposition — [Primary benefit in headline]
Screenshots: [Feature 1 showcase], [Social proof screen], [Key differentiator visual]
App Preview: 30-second demonstration of primary use case

CPP 2 — COMPETITOR CONQUEST:
Message: "[Competitor] users: Here's why [Your App] [does X better]"
Screenshots: Direct comparison feature screens + migration simplicity messaging
Social proof: Reviews specifically mentioning competitive switch

CPP 3 — PROBLEM-SPECIFIC (High-intent category terms):
Message: Solve [specific problem] — e.g., "Track every dollar without spreadsheets"
Screenshots: Problem → solution visual narrative
App Preview: Show the aha moment users experience in first session

CPP 4 — LOCALE-SPECIFIC (Top international markets):
Message: Locally translated with culturally relevant proof points
Screenshots: Localized UI screenshots + market-specific social proof
Activation: US mature → replicate framework to [UK / CA / AU / DE] in priority order

A/B TEST FRAMEWORK:
- Test 1 screenshot per CPP every 2 weeks; measure TTR (tap-through rate) and install CVR
- Winning variant becomes control; challenger must beat by >15% to rotate
- Never run more than 2 variants simultaneously per CPP

---

DELIVERABLE 4: BIDDING STRATEGY — Automated + Manual Hybrid

PHASE 1 — Learning (Days 1-14):
- Use Manual CPT bidding across all campaigns
- Brand: CPT = $[1.20-2.00 depending on category]
- Category exact: CPT = $[0.60-1.20]
- Competitor: CPT = $[0.80-1.50]
- Discovery: CPT floor = $[0.25-0.50]
- Goal: Accumulate 50+ conversions per ad group before switching to automation

PHASE 2 — Automated Optimization (Day 15+, where >50 weekly conversions):
- Activate CPA Goal bidding: Set target = [Target CPA × 1.2] initially, tighten over 30 days
- Budget allocation shift: Move 40% of budget to CPA Goal campaigns
- Manual CPT retained for: Brand defense, new keyword tests, low-volume long-tail

PHASE 3 — Scale (60+ days):
- CPA Goal on all mature campaigns; Manual for exploration only
- Introduce bid multipliers: Device (iPhone 14+ vs. older) if LTV data shows signal
- Review bid caps: Ensure CPT cap doesn't constrain delivery during peak hours

BUDGET PACING RULES:
- Daily budget = Monthly budget ÷ 30, with 15% buffer for auction volatility
- Brand campaign: Never underfund — set at 2× projected daily spend
- Category campaigns: Standard daily budget with weekly review
- Automatic spending alert: Pause if CPA exceeds [Target × 2] for 48 consecutive hours

---

DELIVERABLE 5: ATTRIBUTION & MEASUREMENT ARCHITECTURE

SKAN 4.0 CONFIGURATION:
Conversion value mapping for [PRIMARY BUSINESS MODEL]:

For Subscription App:
- Values 0-5: Install only (no in-app action)
- Values 6-15: Onboarding completed / key activation event
- Values 16-30: Trial started / paywall viewed
- Values 31-45: Trial active Day 3-7 (retention signal)
- Values 46-55: Subscription started (primary conversion)
- Values 56-63: High-value subscriber (upgrade / multi-month)

For In-App Purchase App:
- Values 0-10: Install / onboarding
- Values 11-25: First engagement / key feature used
- Values 26-40: Micro-purchase ($1-$5)
- Values 41-55: Mid-tier purchase ($5-$25)
- Values 56-63: High-value purchase ($25+)

MMP CONFIGURATION ([MMP NAME]):
- Postback window: 24-hour (default) → extend to 72-hour for subscription apps with long trials
- Fraud protection: Enable [MMP's fraud prevention suite] — block bots and click injection
- Revenue event: Map subscription_started / purchase_completed as primary revenue postback
- Cohort reporting: Build Day-1, Day-7, Day-30 cohort views for LTV projection

ATT CONSENT OPTIMIZATION:
- Pre-permission prompt: Explain value of personalization before iOS native popup
- Optimal timing: Trigger ATT prompt after user completes [Key activation event — not on app open]
- Messaging: "[App name] works better when it can show you relevant content. Allow tracking to [User benefit]"
- Target: ATT consent rate ≥ 45% (industry average); above 55% is excellent
- Consented user attribution: Full deterministic via MMP
- Non-consented attribution: SKAN probabilistic — do NOT exclude from measurement

INCREMENTALITY VALIDATION:
- Test design: PSA holdout test — run 90 days, 80% exposed / 20% holdout
- Market selection: Choose 2 similar geographic markets (e.g., Colorado vs. Utah for US app)
- Measurement: Organic install rate uplift in exposed vs. holdout market
- Decision threshold: ASA-driven incrementality lift > 30% = scale; <10% = pause and audit

---

DELIVERABLE 6: COMPETITIVE INTELLIGENCE & SHARE OF VOICE

SEARCH POPULARITY MONITORING:
- Weekly: Check Search Popularity score for top 20 keywords (ASA interface)
- Monthly: Full competitor keyword audit via ASO tools ([AppFollow / Sensor Tower / data.ai])
- Alert trigger: If competitor gains >20% impression share on brand term → increase brand bid immediately

COMPETITOR APP INTELLIGENCE:
- Monitor: Competitor's ASA creative rotation (screenshot changes = new CPP test)
- Monitor: Competitor's review velocity — spike = new campaign or incentive program
- Monitor: Competitor's keyword expansion — new bid activity on adjacent terms

ORGANIC + PAID SYNERGY:
- ASA keyword performance data → inform App Store metadata optimization
- High-CTR keywords in ASA → confirm in app title/subtitle/keyword field
- High-volume Search Match discoveries → add to ASO keyword set
- Organic rank tracking: Monitor top 50 keywords weekly; ASA can lift organic rank

---

DELIVERABLE 7: REPORTING DASHBOARD & OPTIMIZATION CADENCE

DAILY METRICS (automated monitoring):
- Spend vs. budget pacing (flag if >110% or <80%)
- CPI and CPA vs. target (alert if CPA > [Target × 1.5])
- Impressions and TTR by campaign (low TTR < 3% = creative fatigue signal)

WEEKLY REVIEW (30-minute automated report):
- Keyword performance: Pause, scale, or bid-adjust by CPA tier
- New keyword discovery: Search Match report → add winners to Exact Match campaigns
- Creative performance: CPP screenshot TTR and install CVR by variant
- Budget reallocation: Shift budget toward top-performing campaigns

MONTHLY ANALYSIS:
- Cohort LTV analysis: Day-30 revenue per install by campaign/keyword
- Incrementality check: Compare ASA spend periods vs. organic baseline
- Competitive share-of-voice report: Position vs. top 3 competitors per keyword
- CPP refresh: Rotate underperforming screenshots; build new challenger variants

QUARTERLY STRATEGIC REVIEW:
- Full keyword taxonomy audit: Add seasonal terms, prune dead weight
- Placement mix assessment: Evaluate Today Tab and Product Page Ads ROI
- Geographic expansion decision: Scale to new markets based on organic traction signals
- Budget growth model: If CPA < target → increase by 20% increments; test ceiling

---

## Example Input/Output

**Input:**
- App: Helio Finance — personal budgeting app for millennials
- Goal: Subscription starts (7-day free trial → $9.99/month)
- Monthly budget: $25,000
- Target CPA (subscription start): $12.00
- Competitors: Mint, YNAB, Monarch Money
- MMP: AppsFlyer
- Current ATT consent rate: 38%

**Output (excerpt):**

**Campaign Structure:**
- Campaign 1 — Brand Exact Match: Keywords: "helio finance", "helio budget app" | CPT: $1.40 | Budget: $2,500/mo
- Campaign 2 — Category Exact: Keywords: "budgeting app", "personal finance app", "expense tracker", "money management app" | CPT: $0.85 | Budget: $8,000/mo
- Campaign 3 — Competitor Exact: Keywords: "mint app", "ynab", "monarch money", "mint alternative" | CPT: $1.10 | Budget: $4,500/mo
- Campaign 4 — Search Match Discovery: All match types | CPT floor: $0.30 | Budget: $3,000/mo
- Campaign 5 — Today Tab: App Preview required | CPT: $1.60 | Budget: $4,000/mo
- Campaign 6 — Product Page Ads: Targeting Mint + YNAB product pages | Budget: $3,000/mo

**Custom Product Pages:**
- CPP Default: "See every dollar, stress less" → Core budgeting screenshots
- CPP Competitor (Mint users): "Mint is shutting down. Helio syncs in 60 seconds." → Migration-focused
- CPP Category Intent: "Stop guessing where your money goes" → Problem/solution narrative

**SKAN Conversion Values:**
- 0-5: Install only | 6-15: Completed onboarding | 16-25: Linked 1+ bank account | 26-35: Active Day 3 | 36-45: Active Day 5 + viewed premium | 46-55: Trial started | 56-63: Subscription converted

**30-Day CPA Projection:**
- Week 1-2: Learning phase — CPA $22-28 (expected)
- Week 3: CPA $16-18 as bidding matures
- Week 4+: CPA $10-13 with CPA Goal optimization enabled
- Month 2 target: $9-11 CPA at 2,200+ subscription starts

**ATT Improvement Plan:**
- Move ATT prompt from app open to post-first-budget-creation (activation event)
- Add pre-permission screen: "Helio shows you budgeting tips based on your spending patterns — allow to personalize your experience"
- Expected lift: 38% → 52% consent rate over 30 days

---

## Success Metrics

**Primary KPIs:**
- CPA (cost per [primary conversion event]) vs. target: ≤ target CPA
- CPI (cost per install): ≤ $2.50 for most categories (varies significantly by vertical)
- TTR (tap-through rate): ≥ 5% Search Results; ≥ 2% Today Tab
- Install CVR (tap-to-install): ≥ 60% (below 50% = App Store listing problem)

**Secondary KPIs:**
- Day-7 retention rate for ASA installs vs. organic baseline: ASA cohort within 10% of organic
- Trial-to-paid conversion rate for ASA cohort: ≥ organic benchmark
- ROAS at 90-day LTV: ≥ 1.5× for growth stage; ≥ 3× for efficiency stage
- Share of voice on top 10 category keywords: ≥ 30% impression share

**Quality Signals:**
- Subscription/purchase rate within 7 days of install: ≥ 15% for monetized apps
- Feature activation rate for ASA users vs. organic: Within 20% parity (lower = bid on wrong keywords)
- Churn rate for ASA cohort at 30 days: Within 15% of organic cohort

**Red Flags — Pause and Investigate:**
- CPA > 2× target for 72 hours straight
- TTR < 2% on Search Results placements (creative fatigue)
- Install CVR < 40% (App Store listing conversion problem, not an ASA problem)
- SKAN reporting showing 0 conversion values beyond value 5 (attribution misconfiguration)

---

## Related Prompts

- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising/AI-Powered-TikTok-Ads-Campaign-Architecture-&-Creative-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising/AI-Powered-Meta-Ads-Campaign-Architecture-&-Advantage-Plus-Intelligence-Engine.md`
- `../../04_Demand-&-Lead-Generation-&-Growth/Inbound-Marketing/App-Store-Optimization-&-Mobile-User-Acquisition-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Paid-Media-&-PPC-Performance-Analytics/Paid-Media-Performance-Analytics-&-ROAS-Intelligence-Engine.md`

---

## Integration Tips

**AppsFlyer / Adjust / Branch:**
- Connect MMP to ASA via API — automatic cost data pull eliminates manual CSV imports
- Configure revenue events as postback events for LTV-based optimization
- Use MMP's audience builder to create suppression lists (existing subscribers) and sync back to ASA

**Amplitude / Mixpanel:**
- Build cohort comparison: ASA installs vs. organic installs → Day-7, Day-30, Day-90 retention and revenue
- Use behavioral analytics to identify which keywords correlate with highest LTV users
- Feed LTV cohort data back into SKAN value mapping updates quarterly

**Notion / Google Sheets — Campaign Management:**
- Keyword performance tracker: Import weekly ASA reports → auto-calculate CPA, TTR, CVR per keyword
- CPP test log: Track creative variants, launch dates, TTR, install CVR, and winner declarations
- Budget pacing dashboard: Daily spend vs. monthly cap with automated pause logic via Zapier/Make

**Zapier / Make (Automation):**
- Trigger: If ASA daily spend > 110% of daily budget → Slack alert + pause campaign
- Trigger: If CPA exceeds [target × 2] for 3 days → reduce CPT bids by 20% automatically
- Trigger: Weekly ASA keyword report downloaded → append to Google Sheets + flag new keywords for review

**App Store Connect:**
- Custom Product Pages built in App Store Connect → reference CPP IDs in ASA campaign targeting
- Use Xcode's StoreKit Testing to validate SKAN postback configuration before launch
- Monitor App Analytics tab for organic uplift correlated with ASA campaign activity periods

---

## Troubleshooting

**Problem 1: Campaigns stuck in "limited" delivery with very low impressions**
*Root cause:* CPT bids too low for competitive auction, or daily budget too restrictive during learning phase.
*Fix:* For brand campaigns, increase CPT bid by 50% and check Search Popularity scores — if Apple rates the keyword <5/100, demand is too low to scale. For category campaigns, check if Search Popularity ≥ 15/100; if not, switch to broader category terms. Ensure daily budget ≥ $150/campaign during first 14 days of learning.

**Problem 2: High install volume but CPA for in-app event (subscription/purchase) is 5× target**
*Root cause:* Bidding on high-volume keywords that attract window shoppers, not buyers — keyword intent mismatch. Also check if SKAN configuration is miscounted (all users landing in value 0-5 means conversion events aren't firing).
*Fix:* Audit Search Match keywords for off-target queries (add negatives for non-buyer intent terms). Verify SKAN postback in MMP — check that conversion value ≥ 6 events are firing in test. Shift budget toward long-tail, problem-specific keywords with lower install volume but higher purchase intent.

**Problem 3: ATT consent rate below 30% — attribution is mostly probabilistic, data is unreliable**
*Root cause:* ATT prompt triggered too early (first app open), before user has experienced any value — cold request for tracking permission fails.
*Fix:* Delay ATT prompt until after first meaningful activation event (e.g., after user connects first bank account, completes first workout, sends first message). Add a pre-permission screen explaining the benefit in user terms. Redesign prompt copy: avoid "allow tracking" framing — use "personalize your experience" language. Test prompt timing and copy as A/B experiment with 2-week measurement window.

---

## Version History
- v1.0: Initial creation (auto-generated)
