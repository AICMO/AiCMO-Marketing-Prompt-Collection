# AI-Powered B2B SaaS Interactive Pricing Configurator & Self-Serve Deal Qualification Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** interactive-content, pricing, self-serve, lead-generation, b2b-saas, deal-qualification, conversion-optimization, demand-generation, product-led-growth, revenue-operations

## Overview
This prompt architects a complete interactive pricing configurator that lets buyers self-select their package, see dynamic pricing estimates, and automatically qualify and route themselves to the right sales motion — from self-serve checkout to enterprise white-glove — without human intervention until the deal is worth it.

## Quick Copy-Paste Version

You are a B2B SaaS pricing experience architect and conversion optimizer. I need a complete interactive pricing configurator that lets buyers build their own package, see dynamic estimates, and self-qualify into the right sales motion.

Company: [Your Company]
Product: [One sentence description of what it does and for whom]
Pricing Model: [Per seat / Usage-based / Modular feature tiers / Hybrid]
ACV Range: [e.g., "$8,000–$500,000 ACV depending on package and scale"]
Primary ICP: [Job titles and company size, e.g., "RevOps Directors and VP Sales at B2B SaaS, 100–2,000 employees"]
Routing Thresholds: [Self-serve = under $X ACV / Sales-assisted = $X–$Y / Enterprise = over $Y]
CRM: [HubSpot / Salesforce / other]

Build me:

1. CONFIGURATOR QUESTION FLOW — A 5–8 question sequence that captures company size, use case, must-have features, and scale expectations. Each question must serve double duty: it helps the buyer build their package AND it scores them for routing.

2. DYNAMIC PRICING LOGIC — How to calculate and display pricing estimates in real time as buyers make selections. Include confidence ranges ("Starting at $X/month") that are honest without commoditizing the product.

3. DEAL ROUTING DECISION TREE — The exact logic that routes each buyer to self-serve checkout, a sales-qualified meeting, or an enterprise discovery call based on their configurator inputs.

4. LEAD CAPTURE & PROGRESSIVE PROFILING — When and how to gate contact info (not too early, not too late) and what data to capture to pre-populate CRM with qualified deal context.

5. PERSONALIZED PRICING PAGE OUTPUT — The results page design and copy that shows the buyer their custom configuration, price estimate, and the exact next step matched to their deal tier.

6. SALES HANDOFF BRIEF — An AI-generated deal brief automatically sent to the assigned rep the moment a buyer completes the configurator, including all qualification signals, package selections, and recommended discovery questions.

Every component must execute autonomously — question logic, scoring, routing, CRM creation, and rep notification must all fire without a human touching anything until the meeting is booked.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS pricing experience architect and revenue conversion specialist with 15 years of experience designing self-serve buying experiences at companies ranging from PLG-led startups to enterprise software leaders. Your expertise spans:
- Interactive pricing configurator architecture: multi-variable pricing engines that are transparent without being commoditizing
- Buyer journey routing: deal tier logic that maximizes revenue by putting the right buyers in the right motion (self-serve, sales-assisted, enterprise)
- Progressive profiling and gating strategy: when to ask for email, company, role, and company size without destroying completion rates
- Value-based pricing communication: showing buyers why your price is right for them specifically, not just a number on a page
- Integration with CPQ tools: Salesforce CPQ, DealHub, Zuora, Chargebee, and custom HubSpot quote automation
- AI-powered deal intelligence: using configurator inputs to auto-generate MEDDPICC-qualified deal briefs for sales reps
- A/B testing pricing pages: package framing, anchoring, decoy pricing, and CTA conversion optimization
- PLG conversion flows: converting self-serve free trial users to paid plans through in-app configurator experiences

OBJECTIVE: Design a complete Interactive Pricing Configurator & Self-Serve Deal Qualification System. Every component must be AI-executable — question routing, pricing calculation, lead scoring, CRM record creation, sales assignment, and rep notification must all operate autonomously from the moment a buyer lands on the configurator to the moment a rep receives a pre-qualified deal brief.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Product Description: [One sentence: what it does, for whom, and the primary measurable outcome]
- Product Category: [e.g., "Revenue Intelligence," "Marketing Analytics," "HR Tech," "DevSecOps Platform"]
- Pricing Model: [Per seat / Usage-based (volume tiers) / Modular features / Hybrid seat + usage]
- Pricing Tiers (if applicable): [e.g., "Starter ($299/mo), Growth ($999/mo), Enterprise (custom)"]
- ACV Range: [e.g., "$6,000–$480,000 ACV across self-serve to enterprise"]
- Minimum ACV for Sales Involvement: [e.g., "$15,000+ — below this, self-serve checkout only"]
- Enterprise ACV Threshold: [e.g., "$75,000+ — dedicated enterprise AE + solutions engineer"]
- Sales Cycle Length by Tier: [e.g., "Self-serve: instant; Mid-market: 30–60 days; Enterprise: 90–180 days"]

ICP PROFILE:
- Primary Buyer: [Decision maker, e.g., "VP of Revenue Operations, VP Sales, CRO"]
- Technical Evaluator: [e.g., "Sales Operations Manager, RevOps Analyst"]
- Economic Buyer (enterprise only): [e.g., "CFO, COO, CEO"]
- Primary Company Size Range: [e.g., "100–2,000 employees (mid-market); 2,000+ (enterprise)"]
- Key Industries: [e.g., "B2B SaaS, Fintech, Business Services, Manufacturing with complex sales cycles"]

PRICING CONFIGURATOR ARCHITECTURE:

**Phase 1: Configurator Entry & Context Setting**

Design the above-the-fold experience for the pricing/configurator page:
- Headline that frames the configurator as a service (not a gate): [e.g., "Build your plan in 90 seconds — see pricing matched to how you actually work"]
- Trust signals to display: [customer logos, G2/Gartner rating, "used by X+ companies"]
- Progress indicator design: [step-by-step progress bar vs. conversational single-page scroll]
- Entry question to set context before gating: [e.g., "What's your primary goal?" before asking for email]

**Phase 2: Question Architecture (5–8 questions maximum)**

Design each configurator question to serve two functions simultaneously:
1. Help the buyer make a better decision about their package
2. Capture qualification signals that score and route the deal

QUESTION SET — design the following question types with specific answer options:

Q1 — PRIMARY USE CASE (determines product module/tier):
[Design a use-case selection question with 4–6 specific options, each mapping to a product module or tier]

Q2 — COMPANY SCALE INDICATOR (determines ACV range):
[Design a scale question — team size, data volume, number of accounts managed, or other relevant volume metric — that lets buyer self-select their tier without you asking "what's your budget?"]

Q3 — MUST-HAVE CAPABILITIES (determines feature tier):
[Multi-select question: "Which of these are non-negotiable for you?" with 6–8 specific capabilities, each tagged to Basic/Advanced/Enterprise tier]

Q4 — INTEGRATION REQUIREMENTS (surfaces technical complexity / enterprise signals):
[Multi-select: "Which tools must this connect to on day one?" — specific integrations like Salesforce, HubSpot, SAP, Workday, etc.]

Q5 — CURRENT ALTERNATIVE / STATUS QUO (competitive intelligence + urgency signal):
[e.g., "What are you using today to solve this?" — options including named competitors, spreadsheets, homegrown tools, nothing]

Q6 — TIMELINE (urgency scoring):
[e.g., "When are you looking to have this live?" — options: ASAP / 1–3 months / 3–6 months / Exploring options]

Q7 — DECISION PROCESS (enterprise buying signal):
[e.g., "Who else is involved in evaluating this?" — Individual decision / Small team / Formal procurement / IT/Security review required]

Q8 (OPTIONAL) — COMPANY CONTEXT (progressive profiling):
[Company name + industry if not already captured via enrichment]

**Phase 3: Lead Gate & Progressive Profiling**

Design the gating strategy:
- Gate position: [After Q2 or Q3 — after enough context is shared to make the results valuable, before the full results are shown]
- Gate fields to capture: [Work email (required) / First name (required) / Company name (auto-enrich from email domain via Clearbit/Apollo) / Phone (optional, enterprise tier only)]
- Gate copy: ["See your custom plan — we'll send your configuration to this email so you can share with your team"]
- IP enrichment triggers: [Auto-populate company name, size, and industry from email domain using Clearbit Reveal or ZoomInfo IntelligenceOS]
- Re-engagement if abandoned before gate: [Exit-intent popup with "Save your configuration" CTA that captures just email]

**Phase 4: Dynamic Pricing Calculation Engine**

Build the pricing logic:

PRICING DISPLAY RULES:
- Self-serve tiers (under [minimum ACV]): Show exact monthly and annual pricing with a "Start free trial" or "Subscribe now" CTA
- Mid-market deals ([minimum ACV] to [enterprise threshold]): Show pricing range with anchoring ("Plans from $X/month, most teams our size pay $Y") + "See exact pricing" CTA → leads to meeting booking
- Enterprise deals (over [enterprise threshold]): Show "Custom pricing built for your scale" with "Get enterprise quote" CTA → leads to enterprise discovery call

PRICING CALCULATION VARIABLES:
- Base tier price (from use case + must-have capabilities selections)
- Scale multiplier (from company size / volume indicator)
- Integration complexity surcharge (if 3+ enterprise integrations selected)
- Volume discount curve (annual vs. monthly, multi-year commitment signal)
- Competitive displacement discount (if named competitor selected as status quo)

PRICING CONFIDENCE DISPLAY:
- For self-serve: exact price
- For mid-market: "Starting at $[X]/month — most [company size] teams pay $[X]–$[Y]/month"
- For enterprise: "Teams like yours typically invest $[range]/year — let's build your exact plan"

**Phase 5: Deal Routing Decision Tree**

Build the automated routing logic:

ROUTING TIER 1 — SELF-SERVE:
Trigger conditions: [List specific question responses that indicate self-serve: e.g., team size < X, no enterprise integrations selected, timeline "ASAP", no IT/security review required, ACV calculation < $[threshold]]
→ CTA: "Start your [free trial / free plan / purchase now]" → direct to checkout or trial activation
→ CRM action: Create Contact + Deal in pipeline "Self-Serve," assign to lifecycle automation, trigger onboarding email sequence

ROUTING TIER 2 — SALES-ASSISTED (MID-MARKET):
Trigger conditions: [Specific responses indicating mid-market: company size $X–$Y range, 1–2 enterprise integrations, formal evaluation timeline, small team decision]
→ CTA: "See your exact pricing — book a 20-minute call" → Calendly/Chili Piper booking page, pre-populated with all configurator data
→ CRM action: Create Contact + Deal in pipeline "Mid-Market," assign to appropriate AE queue based on territory, trigger "Hot Lead Alert" to rep with deal brief

ROUTING TIER 3 — ENTERPRISE:
Trigger conditions: [Specific responses indicating enterprise: company size > X, Salesforce/SAP/Workday integrations, IT/security review required, formal procurement, ACV calculation > $[enterprise threshold]]
→ CTA: "Get your enterprise plan — connect with our enterprise team" → Enterprise discovery call booking with dedicated enterprise AE
→ CRM action: Create Contact + Deal in pipeline "Enterprise," assign to enterprise team, trigger SDR enrichment workflow, alert Enterprise AE and Solutions Engineer simultaneously

HYBRID ROUTING EDGE CASES:
[Define what happens when signals are mixed — e.g., small company but enterprise integrations, or individual decision-maker at large company. Include explicit fallback routing for each edge case.]

**Phase 6: Personalized Results Page**

Design the configurator output page:

ABOVE THE FOLD:
- Personalized headline: "[First name]'s custom [Product Name] plan" or "Your [use case] plan" (personalized from Q1 and gate)
- Configuration summary: Visual card showing selected use case, key features, integrations — what they built
- Pricing display: Tier-appropriate pricing (see Phase 4 display rules)
- Primary CTA: Routing-appropriate (see Phase 5)

BELOW THE FOLD:
- "What's included": Feature breakdown based on their selections, with checkmarks for included and "upgrade to add" for excluded capabilities
- Social proof: 2–3 customer quotes specifically selected from ICP-matched customers (matched by company size or use case from Q1/Q2)
- ROI context: One-line ROI statement specific to their use case: e.g., "RevOps teams our size typically save X hours/week and increase pipeline accuracy by Y%"
- "Compare your plan" link: Optional comparison table showing their configured tier vs. other tiers
- Share / save option: "Email this configuration to your team" — captures additional stakeholder email addresses for multi-threading

**Phase 7: AI-Generated Sales Rep Deal Brief**

Design the deal brief automatically sent to the assigned rep within 60 seconds of configurator completion:

DEAL BRIEF FORMAT:
Subject: [Company Name] — [Tier] Lead | [ACV Estimate] | [Timeline] | Configurator Complete

- DEAL SNAPSHOT: Company, contact, title, email, phone (if captured), company size, industry
- CONFIGURATION SELECTED: Exact answers to all 8 questions — what they're trying to do, what they need, when they need it
- ACV ESTIMATE: AI-calculated range based on configuration
- ROUTING RATIONALE: Why this lead was routed to this tier (specific signals that triggered it)
- COMPETITIVE INTEL: What they're replacing or comparing against (from Q5)
- RECOMMENDED DISCOVERY QUESTIONS: 3–5 AI-generated questions specific to this buyer's configuration, designed to surface MEDDPICC qualification data in the first call
- NEXT STEP: Meeting time (if already booked via Calendly), or "Follow up within [X hours] — lead is [hot/warm]"
- RISK FLAGS: Any signals that suggest deal complexity (e.g., IT security review, long timeline, individual decision-maker at large company)

**Phase 8: Integration Specifications**

MAP EVERY DATA POINT TO YOUR TECH STACK:

HubSpot Integration:
- Contact properties to create/update from configurator: [list each question → specific HubSpot property]
- Deal properties to auto-populate: Deal Name, Deal Stage, Close Date (estimated from timeline question), Amount (from ACV estimate), Deal Type, Configurator Source
- Workflows to trigger: [Self-serve: onboarding email sequence / Mid-market: rep alert + meeting reminder / Enterprise: SDR enrichment + AE + SE alerts]
- List membership: Auto-add to configurator segmentation lists by tier for paid retargeting

Salesforce Integration (if applicable):
- Lead/Contact object fields to create
- Opportunity creation with specific stage, owner, and record type based on routing tier
- Task creation for rep follow-up with priority and due date
- Salesforce CPQ trigger: auto-generate draft quote for self-serve and mid-market tiers

Additional Integrations:
- Clearbit/Apollo/ZoomInfo: Enrich company data from email domain at gate
- Chili Piper / Calendly: Embed meeting scheduling directly in results page
- Slack/Teams: Rep and manager deal brief notification
- Segment/Customer Data Platform: Configurator events for remarketing and product analytics
- Intercom/Drift: Trigger chat proactively when high-ACV buyer completes configurator

**Phase 9: A/B Testing Roadmap**

Define 5 tests to run in the first 90 days post-launch:

TEST 1 — GATE POSITION: Gate after Q2 vs. Q3 (impact: completion rate vs. lead quality)
TEST 2 — PRICING DISPLAY: Exact range vs. "starting at" vs. "most companies pay" framing (impact: mid-market meeting conversion rate)
TEST 3 — CTA COPY: "See my plan" vs. "Build my plan" vs. "Get my pricing" (impact: configurator start rate)
TEST 4 — ENTERPRISE ROUTE CTA: "Get enterprise quote" vs. "Talk to enterprise team" vs. "Book enterprise demo" (impact: enterprise meeting booking rate)
TEST 5 — RESULTS PAGE SOCIAL PROOF: Industry-matched customer quote vs. company-size-matched vs. use-case-matched (impact: CTA click rate from results page)

SUCCESS METRICS TO TRACK:
- Configurator start rate (visitors who begin vs. page visits)
- Completion rate (starters who reach results page)
- Gate conversion rate (completers who fill out contact form)
- Routing accuracy (% of deals that land in the correct sales tier)
- Self-serve conversion (completers who subscribe without sales involvement)
- Meeting book rate (mid-market and enterprise CTA → confirmed meeting)
- ACV accuracy (how close configurator ACV estimate is to closed ACV)
- Time-to-first-contact (how fast rep engages after configurator completion)

OUTPUT FORMAT:
Deliver a complete Interactive Pricing Configurator System Spec including:
1. Question flow with all answer options and their scoring weights
2. Pricing calculation formula with variables
3. Routing decision tree with all trigger conditions
4. Results page wireframe with copy for each routing tier
5. Deal brief template with variable-filled examples
6. Integration mapping table (configurator input → CRM field → workflow trigger)
7. 90-day A/B testing roadmap with hypotheses and success metrics
8. Launch checklist for technical implementation

Every deliverable must be production-ready — specific enough that a web developer and marketing ops specialist can implement directly without interpretation.

## Example Input/Output

**Input Example:**

Using Vantara, an AI-powered revenue intelligence platform for B2B SaaS RevOps and Sales leaders.

Configurator inputs from a prospect:
- Use Case: "Improve forecast accuracy and call-to-close prediction"
- Scale: "We have 45 AEs managing 800+ active opportunities at any time"
- Must-have capabilities: "CRM activity scoring, deal risk alerts, pipeline review automation"
- Integrations required: Salesforce, Gong, Slack
- Status quo: "Salesforce native reporting + Excel spreadsheets"
- Timeline: "1–3 months"
- Decision process: "Small team — me + VP Sales + our Salesforce admin"
- Email: sarah.chen@meridianhr.com (auto-enriched: Meridian HR Solutions, 620 employees, HR Tech)

**Output Example:**

*Routing: Mid-Market Sales-Assisted (estimated ACV: $48,000–$72,000)*

---

**Results Page (Sarah Chen's Custom Vantara Plan):**

"Your Revenue Intelligence Plan for Meridian's 45-AE Sales Team"

**What you've configured:**
✅ Deal Risk Intelligence (real-time opportunity scoring)
✅ CRM Activity Analysis (Salesforce-native, no additional data entry)
✅ Gong Integration (call intelligence → deal signals)
✅ Pipeline Review Automation (weekly digest + Slack alerts)
✅ Forecast Accuracy Engine (AI-powered call-to-close prediction)

**Your plan: Growth** | Starting at $3,800/month for your team size | Annual plans include 2 months free

Most RevOps leaders managing 40–50 AEs at $250M–$500M ARR companies invest $42,000–$68,000/year.

**Next step: See your exact quote →** [Book 20-min call — pick a time that works]

---

**Auto-generated deal brief to Vantara AE (sends within 45 seconds):**

Subject: 🔥 Meridian HR — Mid-Market Lead | $48K–$72K ACV | Books in 1–3mo | Configurator Complete

**Company:** Meridian HR Solutions | 620 employees | HR Tech | meridianhr.com
**Buyer:** Sarah Chen, RevOps Director | sarah.chen@meridianhr.com
**Stage:** Actively evaluating — timeline 1–3 months

**Configuration selected:**
- Deal risk intelligence + CRM activity scoring + Gong integration
- 45 AEs, 800+ active opps
- Replacing: Salesforce native reports + Excel

**ACV estimate:** $48,000–$72,000 (confirmed Growth tier)

**Recommended discovery questions:**
1. "You mentioned forecast accuracy — what's your current forecast miss rate, and what does a 10-point improvement in accuracy mean for your VP Sales' credibility with the board?"
2. "Your Salesforce admin is in the evaluation — what's their biggest concern about adding a new tool to the Salesforce instance?"
3. "You're replacing Excel spreadsheets — who's building those today, and how many hours/week is that costing?"

**Risk flags:** Three-person decision team (ensure Sarah is the champion, not just the researcher — confirm VP Sales is engaged). Salesforce admin involvement = technical gate, not blocker.

**Action:** Follow up within 2 hours. She just booked — confirm via calendar invite.

---

## Success Metrics

- **Configurator start rate:** >35% of pricing page visitors begin the flow (benchmark: static pricing pages convert at 2–8%)
- **Completion rate:** >65% of starters reach the results page
- **Gate conversion:** >55% of completers submit contact info
- **Routing accuracy:** >85% of completed configurators routed to the correct deal tier (validate via deal close data at 90 days)
- **Self-serve conversion:** >20% of self-serve tier completers subscribe within 14 days without sales contact
- **Meeting book rate:** >40% of mid-market and enterprise completers book a meeting within 48 hours
- **Rep response time:** 100% of mid-market and enterprise leads contacted within 2 hours of completion (automated brief + Slack notification)
- **ACV accuracy:** Configurator ACV estimate within ±25% of closed ACV for 70%+ of deals

## Related Prompts

- [Interactive Content ROI Calculator & Assessment Tool](./AI-Powered-B2B-SaaS-Interactive-Content-ROI-Calculator-&-Assessment-Tool-Architecture-Lead-Generation-Intelligence-Engine.md)
- [Self-Guided Interactive Demo & PLG Content Experience](./AI-Powered-B2B-SaaS-Self-Guided-Interactive-Demo-&-Product-Led-Growth-Content-Experience-Architecture-Revenue-Intelligence-Engine.md)
- [Demand Capture CRO & High-Intent Funnel Conversion](../../04_Demand-&-Lead-Generation-&-Growth/Conversion-Rate-Optimization/AI-Powered-B2B-SaaS-Demand-Capture-CRO-&-High-Intent-Funnel-Conversion-Intelligence-Engine.md)
- [Usage-Based Pricing GTM Strategy](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-B2B-SaaS-Usage-Based-Pricing-GTM-Strategy-&-Consumption-Revenue-Expansion-Intelligence-Engine.md)

## Integration Tips

- **HubSpot:** Use HubSpot's Forms API to capture configurator submissions as custom properties. Build separate pipelines for each routing tier. Use Workflows to auto-create deals, assign owners, and trigger email sequences based on configurator tier. Use Lists to build retargeting audiences for LinkedIn and Google Ads.
- **Salesforce:** Map every configurator question to a Lead field. Use Process Builder or Flow to auto-create Opportunities with correct Record Type, Stage, and assigned owner when a lead completes the configurator. Trigger Salesforce CPQ to draft a quote for self-serve and mid-market completers.
- **Chili Piper / Calendly:** Embed the scheduling widget directly in the results page with pre-filled context from configurator. Use Chili Piper's Concierge for instant lead routing to the right rep calendar based on territory and tier.
- **Clearbit / Apollo.io:** Use Reveal to enrich company data from email domain at the gate — auto-populate company name, industry, employee count, and tech stack to reduce form friction and improve segmentation.
- **Segment / CDP:** Fire Segment events for each question answer and configurator completion. Use these events to trigger in-product experiences for trial users who complete a configurator, and feed data into your marketing analytics for attribution.
- **Slack / Teams:** Use Zapier or native integrations to send the deal brief to a dedicated Slack channel (#pricing-leads or #hot-leads) and DM the assigned rep simultaneously. Include a "Claim this lead" button for reps in territories without auto-assignment.
- **Intercom / Drift:** Set up a bot to proactively open on the configurator results page for high-ACV completers — "I see you're evaluating an enterprise plan — can I answer any questions right now?"

## Troubleshooting

**Problem:** Configurator start rate is below 25% — visitors land on the page but don't begin.
**Solution:** Move the configurator above the fold and replace any static pricing table with a teaser of the first configurator question. Add social proof near the CTA ("Join 1,400+ revenue teams who built their plan in 90 seconds"). Reduce cognitive load by showing the 5-step progress bar upfront — buyers abandon when they don't know how long something takes.

**Problem:** Completion rate drops sharply at the gate (email capture step).
**Solution:** Audit your gate copy — if it sounds like "give us your info to see pricing," buyers bail. Reframe to "send your configuration to this email so you can share it with your team." Test gating after the results are previewed (blur/lock the bottom half of results until email submitted). Also test removing phone number from the gate — it consistently kills completion rate.

**Problem:** Routing accuracy is low — enterprise signals are routing to mid-market, or self-serve leads are getting AE time.
**Solution:** Review your routing decision tree logic. Add an explicit override: if Salesforce + SAP/Workday + IT/security review = enterprise regardless of other signals. For the other direction, add a self-serve cap: if AE count < 10 AND no Salesforce integration AND individual decision = self-serve regardless of timeline. Train the logic on your first 60 days of closed deals — match what the configurator predicted vs. what the deal actually was, then adjust the weights.

## Version History
- v1.0: Initial creation (auto-generated)
