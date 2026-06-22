# AI-Powered B2B SaaS Programmatic Display & Connected TV (CTV) Campaign Architecture & Full-Funnel Audience Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** programmatic, connected-tv, ctv, display-advertising, b2b-saas, demand-generation, the-trade-desk, dv360, account-based-targeting, full-funnel

## Overview
Designs a complete programmatic display and Connected TV (CTV) advertising architecture for B2B SaaS — covering DSP selection, audience segment construction, CTV inventory strategy, display creative specifications, frequency capping, brand safety configuration, and closed-loop pipeline attribution — producing a ready-to-execute campaign brief an AI agent can deploy via DSP APIs. Use when building top-of-funnel brand awareness at scale, layering account-based display targeting alongside ABM programs, or extending multi-channel reach beyond LinkedIn and paid search into streaming and display inventory.

## Quick Copy-Paste Version

You are a senior B2B SaaS programmatic media strategist. Design a complete programmatic display and Connected TV (CTV) campaign architecture for [Your SaaS Product] — a [brief product description] targeting [ICP: job title/department] at [company size/type] companies.

Build a full campaign structure with these components:

1. DSP SELECTION & RATIONALE:
   - Primary DSP recommendation (The Trade Desk / Google DV360 / Amazon DSP / Xandr)
   - Justification based on B2B audience data, inventory access, and CRM integration capability

2. CAMPAIGN STRUCTURE (full funnel):
   - Awareness: CTV / OTT streaming ads for cold ICP accounts
   - Consideration: Programmatic display retargeting for warm audiences and website visitors
   - Conversion: Account-based display for named accounts in active pipeline
   - Competitive: Display interception targeting audiences engaged with competitor content

3. AUDIENCE TARGETING STRATEGY:
   - First-party: CRM contact/account list upload via UID2 or IP-based matching
   - Third-party B2B segments: job function, seniority, company size, industry (from LiveRamp, Bombora, Dun & Bradstreet)
   - Contextual: keyword and content category targeting on relevant publisher inventory
   - Retargeting: website visitor pixel segments by page and recency

4. CREATIVE SPECIFICATIONS:
   - CTV: 15-second and 30-second non-skippable video specs and messaging framework
   - Display: IAB standard banner sizes (300×250, 728×90, 160×600, 300×600, 320×50 mobile)
   - Dynamic creative optimization (DCO) rules by audience segment and funnel stage

5. BRAND SAFETY & INVENTORY CONTROLS:
   - Private Marketplace (PMP) deal setup with premium B2B publishers
   - Block list categories: news, politics, user-generated content, low-quality inventory
   - Viewability standard: >70% in-view for display, 100% completion for CTV

6. MEASUREMENT & ATTRIBUTION:
   - View-through conversion windows by campaign type
   - IP-based account matching to CRM for pipeline influence tracking
   - Cross-channel lift study design to measure programmatic's incremental contribution

Output a complete implementation brief an AI agent or programmatic trader can execute directly, including audience configurations, creative briefs, DSP settings, and attribution setup.

## Advanced Customizable Version

ROLE: You are a B2B SaaS programmatic media architect with 10+ years building full-funnel display and CTV programs for enterprise software companies. You architect programmatic programs that create measurable brand awareness and account-level pipeline influence — not vanity impressions — using first-party data, B2B audience intelligence, and closed-loop CRM attribution to prove revenue contribution.

COMPANY CONTEXT:
- Product: [product name] — [one-sentence description]
- Category: [e.g., "AI-powered revenue forecasting platform for enterprise sales teams"]
- Primary ICP: [job title(s)] at [company type/size], e.g., "VP of Sales, CRO, VP Revenue Operations at B2B SaaS companies, 500–10,000 employees, Series C through public"
- ACV (Average Contract Value): $[X]
- Sales cycle: [X months]
- Target accounts in CRM: [X named accounts — Tier 1 / Tier 2]
- First-party data available: [CRM contact list / website pixel / trial user list / customer list]
- Monthly programmatic budget: $[X]
- Existing paid channels: [LinkedIn Ads / Google Ads / etc.]
- Top 3 competitors: [Competitor A], [Competitor B], [Competitor C]
- Geographic focus: [US / EMEA / global]
- Streaming platforms your ICP watches: [business news, financial media, streaming services — specify if known]

OBJECTIVE: Design a complete programmatic display and CTV campaign architecture that builds brand awareness among cold ICP accounts, influences open pipeline at named accounts, and provides measurable pipeline attribution via account-based tracking — filling the reach gap that paid social and paid search cannot cover.

---

DELIVERABLE 1 — DSP SELECTION & RATIONALE:

Evaluate and recommend a primary DSP based on the company context above, and explain why:

THE TRADE DESK (Recommended for most B2B SaaS):
- Strengths: Largest CTV inventory access (Hulu, Peacock, Paramount+, MAX, Tubi, streaming news), best-in-class B2B audience data marketplace (Bombora, Dun & Bradstreet, LiveRamp, Experian), UID2 framework for cookieless first-party identity, Koa AI bidding algorithm optimized for conversion goals
- Best for: Companies targeting enterprise audiences who consume streaming business content, need CTV + display in one platform, want deep B2B intent signal data from Bombora
- Minimum effective budget: $15,000/month to achieve meaningful frequency at scale
- API: Trade Desk API enables AI agent campaign management, audience creation, creative upload, and reporting extraction

GOOGLE DV360 (Best for Google-ecosystem companies):
- Strengths: Direct access to YouTube inventory (for companies running YouTube Ads), Google first-party audience data, tight integration with GA4 and Google Ads remarketing lists
- Best for: Companies already heavily invested in Google Analytics and Google Ads who want unified reporting across all Google channels; weaker on CTV and B2B third-party data than The Trade Desk
- Note: DV360 cannot access The Trade Desk's exclusive CTV supply paths; use Trade Desk if CTV is a priority

AMAZON DSP (Best for companies selling to tech/enterprise buyers on AWS):
- Strengths: Amazon first-party purchase and browsing signals; excellent for reaching tech buyers who use AWS, research solutions on G2/Capterra (both Amazon-owned properties), and consume streaming via Prime Video/Freevee
- Best for: DevTools, cloud infrastructure, and API/platform companies whose buyers research via Amazon properties

RECOMMENDATION FORMAT:
Primary DSP: [Name] — [2-sentence rationale tied to ICP and goals]
Secondary DSP (if budget allows for multi-DSP): [Name] — [1-sentence rationale]
Integration requirement: [CRM integration method — LiveRamp Connect, UID2, IP-match service]

---

DELIVERABLE 2 — CAMPAIGN STRUCTURE MAP:

Produce a hierarchical campaign architecture table:
| Campaign | Tactic | Audience | Inventory | Monthly Budget | Primary KPI |

Structure 5–6 campaigns across three funnel stages:

A) CTV AWARENESS CAMPAIGN (Cold ICP — Top of Funnel):
- Tactic: Connected TV / OTT non-skippable video
- Audience:
  * Primary: Third-party B2B segments — job function (Finance, Sales, Operations, IT/Engineering), seniority (Director, VP, C-Suite), company size (500+ employees), industry verticals matching ICP — sourced from Bombora or Dun & Bradstreet data marketplace in DSP
  * Secondary: IP-matched list of target accounts from CRM (Tier 1 named accounts — serve CTV to any device authenticated on account IP ranges)
- Inventory: Premium CTV supply — business news streaming (Bloomberg TV, CNBC streaming, Fox Business), general streaming (Hulu, Peacock, Paramount+ ad-supported tiers, Tubi), news/sports apps on smart TVs via programmatic guaranteed deals
- Ad format: 15-second (preferred for awareness efficiency) and 30-second non-skippable pre-roll or mid-roll
- Frequency cap: 3–5 impressions per household per week (CTV frequency uncapped becomes wasteful quickly)
- Creative angle: Category education — name the problem at executive level; no product demo; build mental availability before the buying cycle begins
- Brand safety: Premium PMP deals with named publishers only; block user-generated video inventory
- Budget: 30–35% of total programmatic spend
- Primary KPI: Unique account reach (% of named Tier 1 accounts with at least 3 CTV impressions/month), frequency achieved, video completion rate >90% (CTV industry norm is 95%+ due to non-skip)

B) PROGRAMMATIC DISPLAY — ABM ACCOUNT TARGETING (Mid-Funnel Named Accounts):
- Tactic: Programmatic display — account-based targeting
- Audience: IP-matched named account list (Tier 1 + Tier 2) — upload CRM account list to DSP via LiveRamp Connect or IP intelligence layer (Bombora, Demandbase, or 6sense segment pushed to DSP)
- Inventory: B2B publisher Private Marketplace (PMP) deals — business publications (WSJ, Bloomberg, Forbes, Harvard Business Review, TechCrunch, VentureBeat), vertical trade press matching ICP industry
- Ad format: IAB standard display banners — 300×250 (medium rectangle, highest volume), 728×90 (leaderboard), 160×600 (wide skyscraper), 300×600 (half page — premium placement), 320×50 (mobile banner)
- Creative angle: Proof and differentiation — customer outcomes by industry vertical, benchmark data, "Why companies like [ICP vertical] choose [Product]"
- Dynamic Creative Optimization (DCO): Serve vertical-specific creative variation based on which industry the account is classified in (e.g., Financial Services buyer sees financial services customer case study; Healthcare buyer sees healthcare outcome)
- Frequency cap: 5–7 impressions per user per week; 15–20 per user per month
- Budget: 25–30% of total programmatic spend
- Primary KPI: Named account reach rate (% of Tier 1 list with served impressions), account engagement lift (CRM accounts with more open pipeline activity vs. control group)

C) WEBSITE VISITOR RETARGETING — DISPLAY (Warm Audience Re-engagement):
- Tactic: Programmatic display — pixel-based retargeting
- Audience: Website pixel segments by page visited (segment in DSP via retargeting pixel):
  * High intent (≤7 days): Pricing page visitors, demo page non-converters, ROI calculator users
  * Mid intent (8–30 days): Feature page visitors, case study readers, blog visitors from ICP-relevant topics
  * Broad retargeting (31–90 days): All website visitors, homepage only — lowest priority, use only if budget allows
- Inventory: Open exchange + retargeting PMP deals; prioritize premium placements but allow broader inventory for retargeting since audience qualification comes from pixel, not publisher
- Ad format: 300×250, 300×600, 728×90 — personalized to page visited (pricing page visitor sees pricing-specific offer; case study reader sees related customer story)
- Frequency cap: 7–10 impressions per user per week for high-intent segments; 3–5 for broad retargeting
- Creative angle: Continuation of what they engaged with — if they read a case study, show a related customer outcome; if they visited pricing, show a risk-removal offer (free trial, money-back, ROI guarantee)
- Budget: 20–25% of total programmatic spend
- Primary KPI: Retargeting click-through rate >0.15% (B2B display benchmark: 0.08–0.12%; retargeting should exceed), view-through conversions within 7-day window

D) COMPETITIVE INTERCEPTION — DISPLAY (Competitor-Engaged Buyers):
- Tactic: Programmatic display — contextual + intent-based audience
- Audience:
  * Bombora Intent Surging segment: accounts showing elevated research activity on topics associated with [Competitor A/B/C] or your solution category — available directly in Trade Desk data marketplace
  * Contextual targeting: keyword and content category targeting on pages containing competitor product names, competitor review content, competitor comparison keywords (via semantic keyword contextual layer)
  * Behavioral: Buyers who have visited G2 or Capterra category pages (Amazon DSP excels here via G2 data; Trade Desk has G2 integration via data partnerships)
- Inventory: B2B review sites (direct deals if available), business publications, technology press where competitor evaluation content lives
- Ad format: 300×250, 728×90 with direct comparison messaging or migration offer
- Creative angle: Competitive comparison — address switching objection proactively; migration offer; "Why [X] teams switched to [Your Product]" — specific outcome with named customer proof
- Budget: 10–15% of total programmatic spend
- Primary KPI: CTR vs. benchmark, conversion rate on competitive landing page, demo-to-SQL rate from competitive audience (expect higher intent = higher SQL rate)

E) CRM CONTACT RETARGETING — DISPLAY (Known Buyers Across the Web):
- Tactic: Programmatic display — first-party CRM audience sync
- Audience: Upload CRM contact email list to DSP via LiveRamp IdentityLink or UID2 resolution — match to addressable cookieless IDs for display targeting. Segments:
  * Open opportunities: Influence buying committee members not yet engaged by sales
  * Trial users — unconverted: Re-engage with conversion offer
  * Churned customers (6–24 months): Win-back creative
  * Stalled opportunities (no activity >30 days): Pipeline acceleration creative
- Inventory: Open premium exchange with frequency control; overlap with publisher PMP for quality floor
- Ad format: 300×250, 300×600 — personalized by CRM segment
- Creative angle: Personalized by segment — trial users see "You're X% of the way there" activation nudge; churned customers see "See what's new since you left" reactivation; stalled opps see customer story specific to their industry
- Budget: 10–15% of total programmatic spend
- Primary KPI: CRM contact match rate (target >35% match via UID2/LiveRamp), view-through conversion rate, SQL reactivation rate for stalled opportunities

---

DELIVERABLE 3 — AUDIENCE TARGETING SPECIFICATIONS:

For each campaign, specify the complete audience build in the DSP:

THIRD-PARTY B2B DATA SEGMENTS (Trade Desk Data Marketplace / DV360 Audience Center):

BOMBORA INTENT SEGMENTS (available in Trade Desk directly):
- Topic: [Your solution category] — "Surging" filter: 60+ score (accounts researching heavily right now)
- Topic: [Competitor names] — "Surging" — competitive intent interception
- Topic: [Problem space keywords] — e.g., "Sales Forecasting Accuracy", "Revenue Operations Automation"
- Use: Add Bombora segments to CTV and display campaigns to bias impressions toward in-market accounts

DUN & BRADSTREET / TRANSUNION B2B AUDIENCE SEGMENTS:
- Job Function: [Finance, Sales & Marketing, IT, Operations, General Management — match to ICP]
- Seniority: [C-Suite, VP, Director — match to ICP]
- Company Size: [500–1,000 employees, 1,001–5,000, 5,001–10,000 — match to ICP]
- Industry: [SIC/NAICS codes matching target verticals]
- Revenue Range: [$50M–$500M, $500M–$2B annual revenue — match to ICP ACV profile]

IP-BASED ACCOUNT TARGETING CONFIGURATION:
- Tool: Use Bombora, Demandbase, or 6sense to generate IP ranges for named accounts → push as custom audience to Trade Desk or DV360 via API
- Minimum account list size: 200+ accounts for reliable delivery (smaller lists have delivery instability)
- Refresh cadence: Update IP list monthly as accounts cycle in/out of CRM target list

CONTEXTUAL TARGETING LAYER:
- Keyword categories: [list 20–30 contextual keywords relevant to your solution category — e.g., "revenue forecasting", "sales pipeline accuracy", "CRM data quality"]
- Content categories: Business & Finance, Technology, B2B Trade Publications, Software Reviews
- Negative content categories: Entertainment, Consumer Shopping, Sports, User-Generated Content
- Publisher domain whitelist (for premium PMP deals): [list 10–20 target publisher domains by vertical]

---

DELIVERABLE 4 — CREATIVE SPECIFICATIONS:

CONNECTED TV (CTV) CREATIVE BRIEF:

FORMAT: 15-second non-skippable pre-roll (preferred) + 30-second version
Resolution: 1920×1080 (HD), 3840×2160 (4K for premium supply) — provide both
File format: MP4 (H.264 codec), AAC audio, max 500MB
Safe zone: Keep all critical text and logo within 10% inner border (some CTV players crop edges)
Audio: Mastered at -14 LUFS (streaming standard); design for muted playback with captions (some viewers watch TV without sound on second screen — include burned-in or companion captions)
Companion banner: 300×250 display ad to run alongside CTV on apps that support it

15-SECOND CTV SCRIPT STRUCTURE:
- Seconds 0–3: Hook — visceral pain statement or provocative statistic. No company name. No logo. Force attention before viewer looks away.
- Seconds 4–10: Solution frame — introduce your category as the answer (not your product specifically); show what the world looks like when the problem is solved. Use motion graphics or live footage of ICP in their environment.
- Seconds 11–14: Brand reveal — product name + logo + one-line value statement
- Second 15: CTA card — URL or "Search [Product Name]" (CTV cannot be clicked; the call to action drives search or direct navigation from the companion device)

30-SECOND CTV SCRIPT STRUCTURE:
- Seconds 0–5: Hook — same visceral pain as 15-second version
- Seconds 6–18: Proof — one specific customer outcome with name and result (e.g., "[Company] reduced forecast error from 34% to 8% in 60 days"); show the product briefly
- Seconds 19–25: Competitive differentiation — one reason you're different, stated directly
- Seconds 26–30: Brand + CTA card

PSYCHOLOGICAL PRINCIPLES FOR CTV:
- Pattern interrupt: Open with something visually unexpected or an emotionally resonant statement to prevent the viewer from reaching for their phone
- Social proof at scale: Name a recognizable company in the customer example — even one name doubles credibility versus generic claims
- Category establishment: Position your product as the category solution, not a feature — "The revenue forecasting standard for enterprise sales teams" not "A forecasting tool"
- Search behavior trigger: CTV drives search, not clicks — include your brand name 2–3 times and a memorable URL or search term. Test "Search [Product]" vs "[URL]" in CTA card.

DISPLAY CREATIVE BRIEF (IAB Standard Sizes):

For each IAB format, provide:

AD UNIT: 300×250 Medium Rectangle (highest volume — allocate 40% of display impressions)
File format: HTML5 (animated, 15-sec max animation loop) or JPEG/PNG (static)
Max file size: 150KB (HTML5), 40KB (static image)

HEADLINE (35 characters max for legibility at small size): [Direct value statement — not a tagline. "Cut forecast error by 40%" not "The Future of Revenue"]
BODY COPY (50–75 characters): [Supporting proof or offer — "Join 300+ enterprise sales teams. Book a demo."]
CTA BUTTON: [Book a Demo / See How It Works / Get the Report / Start Free Trial]
LOGO PLACEMENT: Top-left corner (highest recognition position in display)
BACKGROUND: Brand color or clean white — avoid busy imagery at small sizes; legibility beats aesthetics
ANIMATION (if HTML5): Sequence: Logo → Problem statement → Solution reveal → CTA button pulse

AD UNIT: 728×90 Leaderboard (high-visibility desktop placement)
Use for: Header/footer placements on business publications
Creative approach: Wide format — use logo left, headline center, CTA button right; single scanning motion
Content: More horizontal space allows a customer proof stat or outcome number

AD UNIT: 300×600 Half Page (premium placement — high viewability, use for mid-funnel proof)
Use for: Sidebar premium placements, highest viewability scores
Creative approach: Vertical narrative — top: problem hook; middle: customer outcome with photo; bottom: CTA
This format supports a mini case study format — use it for retargeting campaigns

DYNAMIC CREATIVE OPTIMIZATION (DCO) RULES:
| Audience Segment | Headline Variable | Image Variable | CTA Variable |
|---|---|---|---|
| Financial Services accounts | "Forecast accuracy for CFO-driven sales orgs" | Financial dashboard image | "See Financial Services case study" |
| Healthcare accounts | "Revenue intelligence built for healthcare sales" | Healthcare team image | "See Healthcare customer story" |
| Technology companies | "Stop sandbagging. Start predicting." | Developer/tech office image | "Book a live demo" |
| Pricing page visitors | "Still evaluating? See the full ROI breakdown." | ROI calculator screenshot | "Get the ROI analysis" |
| Competitor-engaged audience | "Switching from [Competitor]? See what you're missing." | Comparison graphic | "Compare [Product] vs [Competitor]" |

DCO requires 3–5 creative variables per slot and a minimum audience segment size of 10,000 impressions to optimize reliably — do not attempt DCO on audiences below this threshold.

---

DELIVERABLE 5 — BRAND SAFETY & INVENTORY CONTROLS:

PRIVATE MARKETPLACE (PMP) DEAL CONFIGURATION:

Build PMP deals with premium B2B publishers to ensure quality inventory for CTV and display:

CTV PMP DEALS (negotiate directly with publisher ad sales or via DSP deal marketplace):
| Publisher | Deal Type | CPM Range | Inventory Type |
|---|---|---|---|
| Bloomberg Media | Programmatic Guaranteed | $35–55 CPM | Bloomberg TV streaming, Bloomberg app video |
| Hulu Business (via Trade Desk) | PMP | $28–45 CPM | Premium streaming video, non-skippable |
| Peacock Premium (NBCU) | PMP | $25–40 CPM | News, business, sports adjacency |
| Paramount+ / Pluto TV | PMP | $20–35 CPM | Streaming entertainment + news |
| Connected TV via Magnite/SpotX | PMP | $18–30 CPM | Aggregated CTV supply across apps |

DISPLAY PMP DEALS:
| Publisher | Deal Type | CPM Range | Audience Quality |
|---|---|---|---|
| WSJ / Barron's / MarketWatch | PMP | $18–30 CPM | C-Suite, Finance, Business leadership |
| Forbes / Fortune / Inc. | PMP | $12–22 CPM | Entrepreneurs, executives, VPs |
| TechCrunch / VentureBeat | PMP | $10–18 CPM | Tech decision-makers, startup/scale-up leaders |
| Harvard Business Review | PMP | $20–35 CPM | Senior executives, strategy buyers |
| Industry vertical publications | Direct PMP | $15–25 CPM | Highly targeted vertical ICP audiences |

OPEN EXCHANGE CONTROLS:
- Viewability standard: >70% in-view for display (IAB: 50% pixels visible for 1 second minimum), >95% completion for CTV
- Invalid traffic (IVT) filter: Enable pre-bid IVT filtering via DoubleVerify, Integral Ad Science (IAS), or HUMAN Security — block bot traffic before impression is served and charged
- Brand safety tier: Apply GARM (Global Alliance for Responsible Media) brand safety floor — minimum Standard tier, preferably Suitable tier for B2B
- Block list categories: Adult content, hate speech, misinformation/fake news, user-generated video, gambling, politics
- Domain block list: Maintain rolling block list of known MFA (Made-For-Advertising) sites — your DSP provides a starter list; augment with DoubleVerify's MFA detection
- Geo-fence: Block regions where your product is not available or compliant

VIEWABILITY TARGETS BY PLACEMENT TYPE:
| Placement | Viewability Target | Measurement Vendor |
|---|---|---|
| CTV / OTT | 100% completion (non-skip) | DoubleVerify or IAS CTV solution |
| Display — PMP Premium | >80% in-view | DoubleVerify Active View |
| Display — Open Exchange | >65% in-view | IAS or DoubleVerify pre-bid filter |
| Mobile display | >60% in-view | IAS mobile viewability filter |

---

DELIVERABLE 6 — BIDDING & BUDGET FRAMEWORK:

BUDGET ALLOCATION MATRIX:

| Campaign | Tactic | Monthly Budget | % of Total | Primary KPI Target |
|---|---|---|---|---|
| CTV Awareness | CTV/OTT non-skippable | $X | 30–35% | 90%+ VCR, 3–5 freq/HH/week, named account reach >40% |
| ABM Account Display | Programmatic display — IP-match | $X | 25–30% | Named account reach >60%, account engagement lift |
| Retargeting Display | Pixel-based programmatic retargeting | $X | 20–25% | CTR >0.15%, view-through conversion within 7 days |
| Competitive Interception | Contextual + intent display | $X | 10–15% | CTR vs. benchmark, competitive landing page conversion |
| CRM Contact Retargeting | First-party audience display | $X | 10–15% | Match rate >35%, SQL reactivation rate |
| **TOTAL** | | **$X** | **100%** | |

BIDDING STRATEGY BY TACTIC:
| Tactic | Bidding Model | Starting CPM/CPC | Optimization Signal |
|---|---|---|---|
| CTV Awareness | CPM (fixed or floor bid) | $25–45 CPM | Completion rate, reach, frequency |
| ABM Display | CPM with viewability floor | $12–25 CPM | Account reach rate, frequency |
| Retargeting Display | CPC or eCPM | $0.75–1.50 CPC | CTR, view-through conversions |
| Competitive Display | CPC | $0.60–1.20 CPC | Landing page conversion rate |
| CRM Contact | CPM | $10–20 CPM | Audience match rate, conversions |

SCALE GUIDANCE:
- CTV CPMs of $25–45 are standard and justified — you are reaching verified streaming households with non-skippable video, not bidding on banner blindness
- Display CPMs of $10–25 for quality B2B inventory are normal; if you see CPMs below $5 in open exchange without quality filters, reject — it is likely low-quality or fraudulent inventory
- Total budget efficiency metric to track: Cost Per Reached Account (total spend ÷ unique named accounts reached) — target <$200/account/month for CTV + display combined

---

DELIVERABLE 7 — MEASUREMENT & ATTRIBUTION FRAMEWORK:

MEASUREMENT METHODOLOGY FOR B2B PROGRAMMATIC:

Because most B2B buyers do not click display ads (average B2B display CTR: 0.08–0.12%), programmatic success must be measured through account-based and view-through attribution, not last-click:

ACCOUNT-BASED IMPACT MEASUREMENT:
- Tool: Integrate DSP reporting with CRM via ABM platform (6sense, Demandbase, Bombora) or direct account-matching layer
- Method: After running programmatic campaigns, compare pipeline activity for accounts that received impressions vs. a control group of similar accounts that did not — measure:
  * Pipeline acceleration: Do impressed accounts move through funnel stages faster?
  * Deal velocity: Are impressed accounts' sales cycles shorter?
  * Win rate lift: Do impressed accounts have higher close rates?
  * Pipeline influence: What % of closed-won accounts received programmatic impressions before close?

VIEW-THROUGH ATTRIBUTION CONFIGURATION:
| Campaign Type | View-Through Window | Click-Through Window | Rationale |
|---|---|---|---|
| CTV Awareness | 14 days | N/A (CTV is not clickable) | B2B CTV drives search/direct navigation within 2 weeks of viewing |
| Display — Awareness | 7 days | 30 days | Cold audience — give generous view window for brand recall effect |
| Display — Retargeting | 3 days | 30 days | Retargeting audience already knows brand; shorten view window to avoid over-attribution |
| Display — CRM Contacts | 7 days | 30 days | Known contacts — moderate view-through credit |

NOTE: View-through attribution is controversial and often over-reports conversions. Use it as a directional signal, not a primary budget justification metric. The most credible metric for programmatic is account-level pipeline influence measured via control group lift study.

INCREMENTAL LIFT STUDY DESIGN:
- Holdout group: Randomly exclude 15–20% of target accounts from receiving programmatic impressions (DSP holdout feature available in Trade Desk and DV360)
- Measurement period: 30–60 days
- Compare: Holdout accounts vs. exposed accounts on: demo request rate, pipeline open rate, sales velocity, close rate
- Report: Incremental lift in pipeline activity attributable to programmatic exposure — this is the board-ready attribution proof for programmatic investment

UTM + CRM ATTRIBUTION SETUP:
utm_source=programmatic&utm_medium=display&utm_campaign=[campaign_name]&utm_content=[creative_variant]&utm_term=[audience_segment]
utm_source=programmatic&utm_medium=ctv&utm_campaign=[campaign_name]&utm_content=[creative_id]&utm_term=[ctv_placement]
- Map UTM to CRM Lead Source = "Programmatic Display" or "CTV" for any view-through or click-through conversion
- Create CRM report: Programmatic-influenced pipeline — accounts that received impressions AND opened or advanced pipeline in same period

---

DELIVERABLE 8 — 90-DAY LAUNCH ROADMAP:

WEEKS 1–2 (Technical Foundation):
- DSP account setup and CRM integration configuration (LiveRamp Connect or UID2 data onboarding — allow 5–7 business days for first-party list matching)
- Deploy programmatic retargeting pixel on all key website pages (confirm pixel fires correctly across pricing, demo, feature, and case study pages)
- Build PMP deal IDs — contact publisher ad sales teams for preferred deal access (allow 1–2 week negotiation timeline)
- Develop CTV creative (15-second + 30-second scripts) and display creative (all IAB sizes in HTML5)
- Configure brand safety settings, viewability floors, and IVT pre-bid filters

WEEKS 3–4 (Initial Launch):
- Launch CTV Awareness campaign targeting cold ICP B2B segments + IP-matched Tier 1 named accounts
- Launch Retargeting Display campaign for website visitors accumulated during weeks 1–2
- Begin CRM contact list upload and activate CRM Contact Retargeting campaign once match rate confirmed
- Set up Competitive Interception campaign with Bombora competitor intent segments + contextual keyword layer

MONTH 2 (Optimization & ABM Layer):
- Review CTV: Frequency achieved per named account; VCR; adjust frequency caps if under- or over-serving
- Launch ABM Account Display campaign (by now CRM list has synced and IP ranges are calibrated)
- Activate DCO for display campaigns once audience segments exceed 10,000 impression threshold
- Build holdout group for lift study — begin 30-day measurement period
- Rotate creative: CTV 15-second and 30-second variations; A/B test two display headline approaches per campaign

MONTH 3 (Scale & Attribution Reporting):
- Complete lift study analysis — compare pipeline metrics for exposed vs. holdout accounts
- Present account-level pipeline influence report: # named accounts reached, pipeline influenced, closed-won accounts with programmatic exposure
- Expand CTV reach into additional streaming inventory if awareness metrics are strong
- Evaluate adding a second DSP (Amazon DSP or DV360) if Trade Desk coverage gaps exist for specific inventory types
- Refresh CTV creative (CTV creative fatigues faster than display — refresh at 4–6 week mark for accounts with >5 frequency)

---

## Example Input/Output

**Input Example:**
Product: Prism — AI-powered revenue forecasting and pipeline intelligence platform for enterprise sales teams
ICP: VP of Sales, CRO, VP Revenue Operations at B2B SaaS companies, 500–5,000 employees, Series C through pre-IPO
ACV: $95,000
Sales cycle: 4–6 months
Named accounts: 850 Tier 1, 2,200 Tier 2 in CRM
First-party data: 14,400 CRM contacts (emails), website pixel active, 380-company closed-won customer list
Monthly programmatic budget: $38,000
Existing channels: LinkedIn Ads, Google Ads
Competitors: Clari, Gong Forecast, Salesforce Einstein Forecasting
Geography: US + Canada

**Output Example (excerpt):**

---
**CAMPAIGN ARCHITECTURE**

| Campaign | Tactic | Audience | Inventory | Monthly Budget | Primary KPI |
|---|---|---|---|---|---|
| CTV — Executive Awareness | CTV non-skippable 15s + 30s | Bombora: Sales Forecasting + CRM Accuracy intent; D&B: VP/CRO/RevOps, 500–5K employees, SaaS; IP-matched 850 Tier 1 accounts | Bloomberg TV streaming, Hulu Business, Peacock — PMP deals | $13,300 | Named account reach >55%; freq 3–5/HH/wk; VCR >93% |
| ABM Display — Named Accounts | Programmatic display — IP-match | 850 Tier 1 + 2,200 Tier 2 IP-matched accounts via Bombora IP intelligence pushed to Trade Desk | WSJ/Barron's PMP, Forbes PMP, TechCrunch PMP + open exchange with viewability >75% | $9,500 | Named account reach >65%; frequency 5–7/user/wk |
| Retargeting — High Intent | Display — pixel retargeting | Pricing page visitors (7d), demo page non-converters (14d), ROI calculator users (30d) | Open premium exchange — viewability floor 70% | $7,600 | CTR >0.18%, view-through conversion within 5 days |
| Competitive Interception | Display — intent + contextual | Bombora: Clari + Gong Forecast intent surging; contextual: "sales forecast accuracy", "revenue intelligence" keywords | B2B tech press PMP, G2/Capterra adjacency via Amazon DSP partnership | $3,800 | CTR >0.14%, competitive landing page conversion >4% |
| CRM Contacts | Display — first-party email match | 14,400 CRM contacts matched via LiveRamp UID2 — segmented by pipeline stage | Open premium exchange + PMP | $3,800 | Match rate >38%; SQL reactivation 8% of stalled opps |
| **TOTAL** | | | | **$38,000** | |

---
**SAMPLE CTV SCRIPT — 15 SECOND:**

*[Seconds 0–3 — Black screen, white text only]:*
"Your VP of Sales is forecasting by gut feel. Again."

*[Seconds 4–10 — Animated: Pipeline chart stabilizing from chaos to clean prediction]:*
"Prism reads every deal signal in your CRM and tells you exactly which deals will close — before the quarter ends."

*[Seconds 11–14 — Product interface + logo reveal]:*
"Prism. Revenue clarity for enterprise sales."

*[Second 15 — CTA card]:*
"Search Prism Revenue Intelligence or visit prismai.com"

---
**SAMPLE DISPLAY AD COPY — ABM 300×250 (Financial Services Vertical DCO variant):**

HEADLINE: "Forecast accuracy CFOs can sign off on"
BODY: "Ironclad reduced commit variance by 44%. 20-min demo."
CTA: "See the Ironclad story"
IMAGE: CFO-level executive with clean pipeline dashboard, financial services aesthetic

PSYCHOLOGICAL PRINCIPLES:
- Specificity: "44%" is a real, provable number — more credible than "dramatically improved"
- Vertical resonance: CFO-specific language ("sign off on") targets the financial services decision dynamic precisely
- Proof before pitch: Customer story CTA reduces perceived sales pressure vs. "Book a Demo"

---
**ACCOUNT-BASED IMPACT MEASUREMENT (Month 3 report template):**
- Named accounts reached (CTV + Display): 1,247 of 3,050 target accounts (40.9%)
- Tier 1 accounts reached: 718 of 850 (84.5%)
- Pipeline influence: 94 named accounts had programmatic exposure AND opened/advanced pipeline in same 60-day period
- Closed-won accounts with programmatic exposure (Q3): 18 of 31 (58%) had ≥3 programmatic impressions in 90 days prior to close
- Estimated pipeline influenced: $3.2M (based on pipeline velocity in exposed vs. holdout group — +22% velocity lift for exposed accounts)
- Programmatic spend for period: $76,000
- Pipeline ROI (influenced): $3.2M ÷ $76,000 = **42x pipeline influence ratio** (does not equal closed ARR — use as directional signal)

---

## Success Metrics

**Technical Health (Weeks 1–2):**
- Retargeting pixel firing on all target pages: verified via DSP pixel debugger
- CRM list match rate (via LiveRamp/UID2): >35% of uploaded emails matched to addressable IDs
- IP-match coverage: >60% of Tier 1 named accounts matched to known IP ranges
- PMP deal activation: deal IDs active and delivering in DSP campaign manager

**CTV Awareness Benchmarks (Month 1):**
- Video Completion Rate (VCR): >92% (non-skippable CTV standard; below 85% indicates delivery quality issue)
- Named account reach rate: >40% of Tier 1 accounts with at least 1 impression in first 30 days
- Household frequency: 3–5 impressions/household/week (below 3 = insufficient awareness build; above 7 = waste)
- CPM vs. plan: Within 15% of negotiated PMP CPM

**Display Performance Benchmarks (Month 1–2):**
- Viewability rate: >72% for PMP placements, >65% for open exchange
- CTR: >0.12% overall, >0.18% for retargeting segments (B2B display CTR benchmark: 0.08–0.12%)
- Invalid traffic (IVT) rate: <5% (DoubleVerify/IAS measurement)
- CRM contact match rate: >35%

**Pipeline Attribution (Month 3):**
- Named accounts with programmatic exposure + pipeline activity: track as "programmatic influenced" accounts
- Lift study result: Exposed accounts should show ≥15% higher pipeline open rate vs. holdout group
- Closed-won accounts with prior programmatic exposure: target >50% (industry norm for well-run ABM display programs)
- Cost Per Reached Account (total spend ÷ unique accounts reached): target <$200/account/month

## Related Prompts
- [`../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-PPC-&-Social/AI-Powered-B2B-SaaS-LinkedIn-Ads-Campaign-Architecture-&-Pipeline-Attributed-Paid-Social-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-PPC-&-Social/AI-Powered-B2B-SaaS-LinkedIn-Ads-Campaign-Architecture-&-Pipeline-Attributed-Paid-Social-Revenue-Intelligence-Engine.md) — Layer programmatic CTV/display awareness with LinkedIn Ads for coordinated multi-channel demand creation
- [`../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-PPC-&-Social/AI-Powered-B2B-SaaS-Google-Ads-Campaign-Architecture-&-Paid-Search-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Paid-Advertising-PPC-&-Social/AI-Powered-B2B-SaaS-Google-Ads-Campaign-Architecture-&-Paid-Search-Revenue-Intelligence-Engine.md) — Use Google Ads to capture search demand that programmatic CTV creates at the awareness stage
- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-Account-Based-Experience-ABX-Orchestration-&-Full-Lifecycle-Revenue-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/AI-Powered-Account-Based-Experience-ABX-Orchestration-&-Full-Lifecycle-Revenue-Intelligence-Engine.md) — Integrate programmatic display into the full ABM account-based experience orchestration motion
- [`../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/AI-Powered-B2B-Revenue-Attribution-Model-Architecture-&-Unified-Measurement-Framework-Intelligence-Engine.md) — Build the attribution framework that gives programmatic display proper credit in a multi-touch revenue model

## Integration Tips

**The Trade Desk API / AI Agent Execution:**
- Use Trade Desk API to programmatically create campaigns, ad groups, creatives, and audience segments from this output
- Endpoints: `POST /campaign`, `POST /adgroup`, `POST /creative`, `POST /audience` — all configurable via JSON payload
- Automate creative rotation: API supports setting creative weight rules; configure an agent to pull performance data weekly and rebalance creative weights toward top-performing variants
- Budget pacing automation: Set up API-based budget alerts and auto-pause rules for campaigns exceeding CPM or CPC thresholds

**LiveRamp Integration (First-Party Data Onboarding):**
- Export CRM contact emails as CSV → upload to LiveRamp Connect → LiveRamp resolves to IdentityLink or UID2 → segment pushed to Trade Desk or DV360 as custom audience
- Onboarding timeline: Allow 5–7 business days for initial list processing; subsequent refreshes take 24–48 hours
- Audience refresh: Set up automated monthly CRM export → LiveRamp push via SFTP or API to keep audience lists current as contacts move through pipeline stages

**HubSpot / Salesforce Integration:**
- UTM parameters from programmatic display clicks flow into HubSpot/Salesforce contact records via standard UTM tracking
- Account-based view: Build a CRM report showing "Accounts with programmatic impression data" using ABM platform integration (6sense, Demandbase, or Bombora) that writes impression data back to CRM account records
- Pipeline influence report: Filter opportunities where "Last programmatic impression date" is within 90 days of opportunity open date — report monthly to leadership as "programmatic-influenced pipeline"

**Zapier / Make Automations:**
- Trigger: Programmatic retargeting campaign CPM exceeds target by 25% for 3 consecutive days → Slack alert to paid media manager with campaign link
- Trigger: Named account match rate drops below 30% → Slack alert to trigger CRM list refresh and LiveRamp re-upload
- Trigger: CTV VCR drops below 88% → Slack alert to creative team for quality investigation
- Trigger: Lift study holdout period ends (set calendar trigger at 30/60 days) → Automated Slack reminder to pull DSP exposure report and compare against CRM pipeline data

**Bombora Intent Data Integration:**
- Connect Bombora Account Surge data directly in Trade Desk data marketplace (no CSV needed — Bombora is a native data partner)
- Set up weekly Bombora surge report → auto-export to CRM → flag accounts showing elevated intent for sales outreach (programmatic creates the awareness; sales captures the intent signal)
- Layer Bombora intent segments on top of IP-matched named account audiences to prioritize impression delivery toward accounts most actively researching your category

## Troubleshooting

**Problem: CTV campaign reaching low household frequency (<2 per week) despite sufficient budget**
Solution: The CTV audience segment is too large relative to budget, or the PMP deal inventory is constrained. First, check if your Bombora + D&B audience segment has been sized properly — CTV audiences above 5 million households require $50,000+/month to reach meaningful frequency across the full audience. Narrow the audience: prioritize Tier 1 named accounts via IP-matching and add a company-size filter to the B2B segment to reduce the addressable universe to 1–2 million households. Second, check PMP deal delivery: contact your publisher rep to confirm the deal is clearing (PMP deals have floor prices — if your bid does not clear the floor, impressions will not be purchased). Third, if deals are clearing but volume is low, add open exchange CTV inventory with brand safety filters as a supplement to PMP.

**Problem: Display retargeting CTR is at or below open exchange benchmark (<0.08%) with no view-through conversions**
Solution: This indicates audience-creative mismatch or creative fatigue. First, check frequency: if the retargeting audience is seeing >10 impressions/user/week, they have habituated to the ad — it is now invisible (banner blindness). Reduce frequency cap to 5–7/week and rotate in new creative immediately. Second, check audience segment quality — pull a placement report and identify if impressions are concentrating on low-quality domains despite filters (common with open exchange). Tighten the domain whitelist or shift more budget to PMP deals. Third, review the creative's value proposition alignment with what the audience did on the site — a pricing page visitor seeing a top-of-funnel awareness ad will not respond; they need a specific conversion offer (free trial, ROI analysis, comparison guide) that directly addresses where they are in the buying process.

**Problem: CRM contact list match rate below 20% via LiveRamp, making CRM retargeting unreachable**
Solution: Low match rates are typically caused by uploading personal email addresses instead of work email addresses, or email formatting issues. Verify your CRM export uses the `work_email` field, not `personal_email` — LiveRamp's B2B identity graph is built on work email domains and professional identity. If work emails are correctly formatted but match rate is still low, your contact database may skew toward older contacts whose emails are no longer associated with an active online identity profile (common with contacts inactive for 12+ months). Filter your CRM export to contacts with email opens or CRM activity in the last 6 months — this cohort will have 40–60% higher match rates. As a fallback for accounts with low email match, switch to IP-based account targeting for those specific companies to ensure account-level coverage even when contact-level matching fails.

## Version History
- v1.0: Initial creation (auto-generated)
