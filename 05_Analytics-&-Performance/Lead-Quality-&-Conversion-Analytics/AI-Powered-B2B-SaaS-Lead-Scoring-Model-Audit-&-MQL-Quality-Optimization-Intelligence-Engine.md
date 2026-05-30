# AI-Powered B2B SaaS Lead Scoring Model Audit & MQL Quality Optimization Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** lead-scoring, mql-quality, demand-generation, revenue-operations, predictive-analytics, b2b, saas, pipeline-efficiency, sales-marketing-alignment, conversion-optimization

## Overview
Generates a comprehensive AI-driven audit of your lead scoring model — diagnosing why MQLs fail to convert to pipeline, rebuilding scoring logic with predictive signals, and creating a closed-loop feedback system between sales and marketing. Use it when your MQL-to-SQL conversion rate is below benchmark (<25%), when sales is rejecting more than 30% of marketing leads, when pipeline quality has degraded despite volume targets being hit, or when you suspect your lead scoring model was built on assumptions that no longer reflect your actual buyers.

## Quick Copy-Paste Version

You are a senior revenue operations architect with 15+ years optimizing B2B SaaS go-to-market systems. I need a complete audit and rebuild of my lead scoring model.

My current situation:
- Product: [What your product does, primary use case, price point]
- ICP: [Company size, industry, key personas you sell to]
- Current MQL definition: [What score threshold triggers an MQL and what signals contribute]
- Current MQL-to-SQL rate: [% of MQLs that sales accepts as SQLs]
- Current MQL-to-Opportunity rate: [% that become active pipeline opportunities]
- Sales rejection reasons: [Top 3 reasons sales rejects our MQLs]
- Primary lead sources: [e.g., inbound demo requests, content downloads, webinar attendees, paid search, outbound]
- CRM: [HubSpot / Salesforce / other]
- Marketing automation: [Marketo / HubSpot / Pardot / other]

Build me the following:

1. LEAD SCORING MODEL DIAGNOSTIC
   - Identify the top 3-5 structural flaws in my current scoring model
   - Flag which scoring signals are likely noise vs. signal
   - Identify missing behavioral and firmographic signals I should be capturing
   - Calculate the "ghost MQL problem": leads scoring above threshold with zero buying intent

2. ICP-CALIBRATED SCORING FRAMEWORK
   - Rebuild scoring with two dimensions: fit score (firmographic) + engagement score (behavioral)
   - Assign specific point values to firmographic attributes (company size, industry, tech stack, revenue)
   - Assign point values to behavioral signals (page visits, content downloads, demo requests, pricing page visits, repeat visits)
   - Build a 4-quadrant lead prioritization matrix (High Fit + High Engagement = work immediately; High Fit + Low Engagement = nurture; Low Fit + High Engagement = flag for review; Low Fit + Low Engagement = disqualify)

3. SALES FEEDBACK LOOP ARCHITECTURE
   - Design a structured rejection reason taxonomy (5-7 categories, not free text)
   - Create a weekly scoring model calibration process using rejection data
   - Build a "shadow scoring" protocol: score historical closed-won deals backward to identify what winning leads looked like before they converted
   - Define MQL grade tiers (A/B/C/D) with different SLA commitments from sales for each tier

4. PREDICTIVE SIGNAL INTEGRATION
   - Identify 5 high-predictive signals I can start tracking immediately without new tooling
   - Build a "buying committee engagement" scoring layer: score the ACCOUNT, not just the individual lead
   - Identify intent signal sources to layer into scoring (G2 research activity, competitor review visits, job postings, technographic changes)

5. MEASUREMENT & GOVERNANCE
   - Define the 5 KPIs that prove my scoring model is working
   - Build a quarterly scoring model review process
   - Set the threshold review protocol: when to adjust score thresholds vs. rebuild the model entirely

Output each section with specific scoring logic, point values, and implementation steps — not conceptual frameworks.

## Advanced Customizable Version

### Role
You are an elite revenue operations architect, demand generation analytics strategist, and B2B SaaS lead lifecycle engineer. You specialize in building predictive lead scoring systems that align marketing qualified leads with actual buyer behavior — not just digital engagement activity. You have audited and rebuilt lead scoring models for B2B SaaS companies from $5M to $500M ARR across verticals including financial services, healthcare technology, HR tech, cybersecurity, and developer tools. You understand that most lead scoring models fail not because of wrong tools, but because of wrong signals, wrong thresholds, and zero feedback loops from sales to marketing.

---

### Context

**Company & Product Profile:**
- Company stage: [Seed / Series A / Series B / Series C+ / Public]
- ARR: [Current ARR or revenue range]
- Product: [What it does, primary use case, and value proposition]
- Primary buyer persona: [Title(s), department, company size they represent]
- Average ACV: [Annual contract value — e.g., $15,000 / $80,000 / $250,000+]
- Sales motion: [Self-serve / Inside sales / Enterprise field sales / PLG + Sales assist]
- Average sales cycle: [e.g., 14 days / 45 days / 6 months]

**Current Lead Scoring Architecture:**
- Scoring platform: [HubSpot / Marketo / Pardot / Salesforce Einstein / Manual spreadsheet / None]
- Fit score signals currently used: [List the firmographic signals — e.g., company size, industry, revenue, title, geography]
- Engagement score signals currently used: [List behavioral signals — e.g., page visits, form fills, email opens, webinar attendance, content downloads]
- Current MQL threshold: [Score that triggers MQL — e.g., "score ≥ 75"]
- Scoring decay: [Do scores decay over time? If so, at what rate?]
- Account-level scoring: [Yes/No — do you score accounts or only individuals?]

**Pipeline Quality Diagnostics:**
- MQL volume (monthly): [How many MQLs are generated per month]
- MQL-to-SQL conversion rate: [%]
- SQL-to-Opportunity conversion rate: [%]
- Opportunity-to-Close rate: [%]
- Sales lead rejection rate: [% of MQLs rejected by sales within the SLA window]
- Top sales rejection reasons: [What does sales say when they reject leads? List verbatim if possible]
- Average days from MQL to first sales touch: [SLA performance]
- Scoring model age: [When was the current model last substantially updated?]

**Lead Source Breakdown:**
- [Source 1]: [% of MQLs] — [MQL-to-close rate if known]
- [Source 2]: [% of MQLs] — [MQL-to-close rate if known]
- [Source 3]: [% of MQLs] — [MQL-to-close rate if known]
- [Source 4]: [% of MQLs] — [MQL-to-close rate if known]

**Data & Tech Stack:**
- CRM: [Platform + key fields available]
- Marketing automation: [Platform + integrations]
- Intent data available: [G2 / Bombora / 6sense / Demandbase / None]
- Enrichment tools: [ZoomInfo / Clearbit / Clay / Apollo / None]
- Conversation intelligence: [Gong / Chorus / Salesloft / None]
- PLG / product analytics: [Amplitude / Mixpanel / Heap / Pendo / None — and whether product usage data flows into your CRM/MAP]

**Historical Performance Data:**
- Closed-won analysis: [Do you have data on what scoring signals your closed-won customers showed before converting?]
- Lead age at conversion: [Typical days from first touch to closed-won]
- Multi-touch attribution model: [First-touch / Last-touch / Linear / Time-decay / Custom]
- Ghost MQL rate: [% of MQLs that are never contacted by sales within 30 days — if known]

---

### Objective
Produce a complete lead scoring model audit and rebuild specification — with actionable thresholds, signal weights, feedback loops, and governance processes that an MOps or RevOps team can implement within 30 days.

---

### Deliverable 1: Lead Scoring Model Diagnostic

**Section A: Structural Flaw Analysis**

Diagnose the scoring model against these six common failure patterns:

1. **Activity-as-intent inflation**: Does the model reward all behavioral activity equally, causing leads who download whitepapers out of curiosity to score the same as leads actively researching pricing? Identify which signals are "curiosity triggers" vs. "buying intent signals" in the current model.

2. **Firmographic data gaps**: Are fit signals based on accurate, enriched data — or on self-reported form fills that are frequently inaccurate (e.g., 60% of "VP" titles on contact forms are not actually VP-level)? Flag which fit signals require enrichment validation.

3. **Threshold drift**: Was the MQL threshold set empirically (based on which score correlated with pipeline conversion) or arbitrarily (e.g., "let's start with 50")? If arbitrary, the threshold is likely wrong — either too permissive (flooding sales with junk) or too restrictive (blocking high-intent buyers who haven't consumed enough content).

4. **Score decay absence**: Leads without decay decay decay: a lead who scored 80 from a webinar 14 months ago and has never re-engaged is not an MQL — they're a cold contact being mislabeled. Does decay exist? Is it calibrated to typical buying cycle length?

5. **Individual vs. account blindness**: B2B buying decisions involve 6-10 stakeholders. A single contact at an account scoring above threshold while 3 other stakeholders at the same account have shown buying signals represents a far stronger signal than scoring individuals in isolation. Is account-level scoring missing entirely?

6. **No closed-loop calibration**: Has the scoring model ever been validated against closed-won data? A well-calibrated model should show a meaningful score differential between leads that became customers and leads that were rejected or never converted. Without this validation, the model is a hypothesis, not an intelligence system.

**Section B: Signal Audit**

For each current scoring signal, classify:
| Signal | Type | Points | Likely Validity | Recommended Action |
|---|---|---|---|---|
| [Current signal 1] | Fit/Behavioral | [Points] | High/Medium/Low | Keep/Adjust/Remove |
| [Current signal 2] | Fit/Behavioral | [Points] | High/Medium/Low | Keep/Adjust/Remove |
| [Continue for each signal] | | | | |

**Signals to add immediately (high predictive value, typically missing):**
- Pricing page visits (3+ visits in 30 days = strongest non-demo intent signal)
- Integration/API docs visits (signals technical evaluation)
- Customer case study downloads filtered by matching industry
- Competitor comparison page visits
- Career page visits for your target job titles at the account
- G2/Capterra review activity for your product or competitors
- Repeat visits within 14-day window (indicates active evaluation, not casual browsing)
- Job postings at the target account for roles your product supports
- Technology stack changes (e.g., adopting a platform you integrate with)

---

### Deliverable 2: Rebuilt Scoring Framework

**Dual-Dimension Model Architecture**

Dimension 1: ICP Fit Score (firmographic — max 100 points)

| Attribute | Best Fit | Strong Fit | Moderate Fit | Poor Fit |
|---|---|---|---|---|
| Company size (employees) | [Your ideal range: e.g., 201-2,000] = 25 pts | [Adjacent: e.g., 2,001-10,000] = 18 pts | [Acceptable: e.g., 51-200] = 10 pts | [Outside: <50 or >10K] = 0-5 pts |
| Industry | [Top 3 ICP industries] = 25 pts | [Adjacent industries with proven success] = 15 pts | [Unproven but logical] = 8 pts | [Outside TAM] = 0 pts |
| Title/Seniority | [Primary buyer title] = 20 pts | [Secondary buyer or influencer title] = 12 pts | [Practitioner who uses but doesn't buy] = 6 pts | [No influence on purchase] = 0 pts |
| Technology stack | [Using must-have integration tool] = 15 pts | [Using nice-to-have integration] = 8 pts | [No stack overlap] = 0 pts | [Using competitor] = 0-2 pts |
| Revenue/Funding | [ARR/Revenue range where ACV makes sense] = 10 pts | [Adjacent range] = 6 pts | [Borderline] = 3 pts | [Out of range] = 0 pts |
| Geography | [Target regions] = 5 pts | [Expansion markets] = 3 pts | [All others] = 0-1 pts | | |

Dimension 2: Engagement Score (behavioral — max 100 points, with decay)

| Behavior | Points | Decay Rate | Buying Intent Level |
|---|---|---|---|
| Demo/trial request (any form) | 50 pts | No decay for 30 days | Critical — immediate routing |
| Pricing page visit (3+ times in 30 days) | 35 pts | 50% decay at 14 days | Critical |
| ROI calculator completion | 30 pts | 50% decay at 14 days | High |
| Competitor comparison page visit | 25 pts | 50% decay at 14 days | High |
| Integration/API documentation visit | 20 pts | 50% decay at 21 days | High (technical evaluator) |
| Case study download (ICP-matched industry) | 15 pts | 50% decay at 30 days | Medium-High |
| Pricing page visit (1-2 times) | 12 pts | 50% decay at 21 days | Medium |
| Webinar attendance (live) | 10 pts | 50% decay at 30 days | Medium |
| Multiple case study downloads (3+ assets) | 10 pts | 50% decay at 30 days | Medium |
| Email click-through to product page | 8 pts | 50% decay at 21 days | Medium |
| Blog post — bottom-of-funnel topic | 6 pts | 50% decay at 21 days | Low-Medium |
| Webinar registration (no-show) | 3 pts | 50% decay at 14 days | Low |
| General blog visit | 2 pts | 75% decay at 14 days | Low |
| Email open (no click) | 1 pt | Immediate decay at 7 days | Minimal |

**Lead Prioritization Matrix (2x2)**

| | High Engagement (≥50 behavioral pts) | Low Engagement (<50 behavioral pts) |
|---|---|---|
| **High Fit (≥70 fit pts)** | **MQL Grade A** — Route to sales within 4 hours. SLA: contact within same business day. High confidence, active buying signal. | **MQL Grade B** — Route to sales within 24 hours. SLA: contact within 2 business days. Strong ICP fit, re-engage to accelerate intent. |
| **Low Fit (<70 fit pts)** | **MQL Grade C** — Flag for human review. Either the prospect has self-selected out of ICP (flag for segment discussion) or your ICP definition needs updating. Route to SDR for qualification call only. | **Disqualify** — Return to long-term nurture. Score < minimum threshold. Do not send to sales. |

**Account-Level Scoring Layer**

Aggregate individual contact scores at the account level using this formula:

Account Score = (Highest individual contact score × 0.5) + (Sum of all other contact scores × 0.25) + (Number of unique contacts engaged × 10 pts, max 30)

Account-level MQL trigger: Account score ≥ 60, with at least 2 unique contacts engaged in 30 days = flag for Account-Based Sales Development (ASD) outreach.

---

### Deliverable 3: Sales Feedback Loop Architecture

**MQL Rejection Taxonomy (replace free-text rejection with structured dropdown)**

Sales must select exactly ONE primary rejection reason:

1. **Not in ICP** — Company size, industry, or use case is outside our target market. This lead should never have been an MQL. [Indicates: fit score needs recalibration]
2. **Wrong Persona** — Contact is not a buyer, decision-maker, or influencer. [Indicates: persona scoring needs adjustment]
3. **No Budget Authority** — Contact acknowledged interest but has no budget control and no relationship with budget holder. [Indicates: persona or company-size scoring may be off]
4. **Not Currently Evaluating** — Company is interested but has no active initiative or timeline. [Indicates: engagement score inflated by curiosity, not buying intent]
5. **Already Using Competitor / Locked In** — Contract with competitor in place; no realistic path to conversion within 12 months. [Indicates: technographic exclusion signals may be missing]
6. **Bad Timing — Revisit in X Months** — Good ICP, genuine interest, but wrong moment. SDR to set a reminder for future outreach. [Not a scoring problem — a timing problem]
7. **Duplicate / Already in Pipeline** — This contact or account is already in active pipeline or has been rejected within 90 days. [Indicates: CRM deduplication issue, not scoring issue]

**Weekly Scoring Calibration Process**

Every Monday, marketing operations reviews:
- Rejection volume and breakdown by reason code (target: <20% rejection rate overall; <5% for Grade A MQLs)
- Rejection rate by lead source (reveals which channels produce lowest-quality fit)
- Rejection rate by top firmographic signals (reveals which fit signals are unreliable)
- Age of rejected leads (reveals how long ghost MQLs sit before rejection)

Scoring model adjustment triggers:
- If rejection reason #1 (Not in ICP) > 10% of rejections → Raise ICP fit threshold by 5 points
- If rejection reason #4 (Not Currently Evaluating) > 25% of rejections → Behavioral signals generating false buying intent; recalibrate engagement signal weights
- If Grade A MQL rejection rate > 10% → Emergency review: A-grade leads should almost never be rejected

**Closed-Won Backward Scoring Analysis**

Run this analysis quarterly:
1. Pull last 90 days of closed-won customers from CRM
2. For each, reconstruct their behavioral and firmographic score at the moment they became an MQL
3. Compare against the scores of rejected or stalled leads
4. Identify: at what combined score did 80% of your closed-won customers sit when they first engaged?
5. If that score is significantly different from your current MQL threshold → adjust threshold to match actual winning-lead score distribution

---

### Deliverable 4: Predictive & Intent Signal Integration

**Tier 1 — Signals Available Without New Tooling (implement within 2 weeks):**

1. **Repeat visit cadence tracking**: Monitor unique session count within a 21-day rolling window. 3+ sessions from the same IP/contact in 21 days = active evaluation signal (+20 pts if not already scored for individual visits)
2. **Page depth analysis**: Contacts who view 5+ unique pages in a single session demonstrate deeper exploration than high-bounce visitors. Weight page-depth visits at 1.5× individual page visit scores
3. **Return visitor frequency from email**: Track clicks from email → website → return organic visit within 48 hours. Shows email-driven research behavior
4. **Form abandonment capture**: Contacts who start but don't complete a demo request or contact form have intent without conversion. Trigger a behavioral nurture sequence and add +8 pts to engagement score
5. **Referral source weighting**: Visitors from competitor review sites (G2, Capterra, TrustRadius), peer communities (Reddit, Slack groups), or customer advocacy links convert at 2-3× the rate of general organic visitors. Add source-specific point multiplier (×1.5)

**Tier 2 — Signals Requiring Intent Data Integration (6sense, Bombora, G2 Buyer Intent):**

- G2 product page visits: contacts actively researching your product on G2 — (+30 pts; route immediately regardless of threshold)
- Bombora surge topics aligned to your product category: account showing research spike on key topics — triggers account-level MQL review
- Competitor page activity: researching your competitors signals active vendor evaluation — (+15 pts; flag for competitive battle card outreach)
- Job posting intent: target account posting jobs your product would support (e.g., posting for "Revenue Operations Manager" signals RevOps platform consideration) — (+10 pts at account level)

**Tier 3 — PLG Product Signal Integration (requires product data → CRM sync):**

- Free trial activation + active usage within 7 days → Product Qualified Lead (PQL); route immediately to PLG-AE regardless of scoring threshold
- Trial user invites additional team members → Account expansion signal; upgrade PQL priority
- Trial user accessing premium features repeatedly → High conversion likelihood; trigger upgrade campaign
- Free tier user hitting usage limits → Conversion trigger; trigger upgrade or sales outreach

---

### Deliverable 5: Measurement & Governance Framework

**5 KPIs That Prove the Scoring Model is Working:**

1. **MQL-to-SQL Conversion Rate**: Target ≥35% (industry benchmark: 25-35%); measure weekly, review monthly. A meaningful improvement here indicates better lead quality reaching sales.
2. **MQL-to-Closed-Won Conversion Rate by Grade**: Grade A leads should close at 2-3× the rate of Grade B; Grade B at 1.5× Grade C. If Grade A and B converge, grading is not predictive.
3. **Sales Lead Rejection Rate by Grade**: Grade A rejection rate should be <10%; Grade B <25%; Grade C <40%. Rejection rates above these thresholds signal miscalibrated scoring.
4. **Speed-to-First-Touch SLA Compliance**: Measure % of Grade A MQLs contacted within 4-hour SLA; Grade B within 24-hour SLA. Poor compliance wastes the scoring model's value.
5. **Pipeline Revenue Per MQL by Source**: Which lead sources generate the most pipeline revenue per MQL? This should drive budget reallocation quarterly — not just volume metrics.

**Quarterly Scoring Model Review Protocol:**

| Review Element | Frequency | Owner | Output |
|---|---|---|---|
| Rejection reason analysis | Weekly | MOps | Scoring calibration adjustments |
| MQL grade performance by source | Monthly | Demand Gen + MOps | Budget allocation recommendations |
| Closed-won backward scoring analysis | Quarterly | RevOps + MOps | Threshold adjustment or model rebuild |
| Fit signal accuracy audit (enrichment check) | Quarterly | MOps + Data Ops | Data quality improvement plan |
| Intent signal evaluation | Quarterly | MOps | New signal incorporation or vendor review |
| Sales satisfaction survey (5 questions to SDR team) | Quarterly | Sales Ops + MOps | Qualitative quality feedback |

**Threshold Adjustment vs. Full Rebuild Decision Rules:**

- **Adjust threshold only**: When rejection rate changes materially (>5 percentage point shift) but the distribution of closed-won scores remains stable
- **Recalibrate signal weights**: When closed-won customers consistently show different behavioral patterns than current MQL triggers suggest
- **Full model rebuild**: When ≥3 of these conditions are true simultaneously: (1) MQL-to-SQL rate has declined >10 percentage points from peak; (2) ICP has shifted (new segments, new personas, new ACV bands); (3) Sales motion has changed (e.g., PLG added, enterprise motion launched); (4) New intent data sources are available; (5) Marketing automation or CRM platform has been replaced

---

## Example Input/Output

**Input Example:**

Product: Workforce analytics platform for mid-market and enterprise companies — helps HR and Finance leaders understand headcount costs, attrition risk, and compensation benchmarking. ACV: $35,000. Sales cycle: 60-90 days.

ICP: 500-5,000 employee companies. Primary buyer: CHRO or VP People. Secondary buyer: CFO or VP Finance.

Current scoring: Fit (company size, industry, title) + engagement (email opens = 2 pts, content downloads = 5 pts, webinar attendance = 10 pts, demo request = 25 pts). MQL at 50 points.

MQL-to-SQL rate: 18% (benchmark is 30%)
Sales rejection rate: 44% — sales says "most of these leads aren't actually evaluating anything"
Lead volume: 380 MQLs/month

**Output Example (Excerpt):**

**Structural Flaw Analysis — WorkForce Analytics Co:**

*Primary flaw: Activity-as-intent inflation from email opens.*

With email opens worth 2 points and a 50-point MQL threshold, a contact can reach MQL status after 25 email opens — with zero behavioral intent signals. In high-volume email programs (weekly sends), this is an almost guaranteed ghost MQL generator. An HR Director who opened 3 months of weekly HR trends newsletters has demonstrated media habit, not purchase evaluation.

*Secondary flaw: Webinar attendance as a strong signal.*

Webinars in the HR technology space attract practitioners learning about trends — not buyers evaluating vendors. 10 points for webinar attendance means someone who attended "2025 Compensation Trends Webinar" plus opened 20 emails is now an MQL. This explains the 44% rejection rate: most rejected leads are practitioners-as-content-consumers, not buyers-as-evaluators.

*Missing signal: Pricing page and ROI calculator.*

There is no behavioral event capture for pricing page visits or ROI calculator completions — your two highest-intent behavioral signals. A contact who visits your pricing page 3 times in 14 days is in active evaluation; a contact who attended your webinar is reading your newsletter. These two leads are not equivalent, but your scoring model treats them similarly.

**Rebuilt Scoring Framework — Immediate Priorities:**

Re-weight email engagement:
- Email open: Reduce from 2 pts to 0.5 pts (high volume, low signal)
- Email click → product page: 5 pts (demonstrated intent to learn about product)
- Email click → pricing page: 15 pts (buying intent)

Add missing signals:
- Pricing page visit (1-2 sessions): 12 pts
- Pricing page visit (3+ sessions in 30 days): 35 pts [new MQL-trigger signal even below threshold]
- ROI calculator start: 15 pts
- ROI calculator completion: 30 pts

Adjust MQL threshold:
- Current: 50 points
- Recommended: 65 points fit + engagement combined, but with mandatory minimum engagement score of 25 pts (prevents pure fit-based ghost MQLs)

**Projected Impact:**

Based on signal re-weighting analysis, estimated MQL-to-SQL rate improvement: 18% → 28-32% within 90 days of implementation. Estimated MQL volume reduction: 380/month → 240-260/month. Net result: fewer MQLs, but 40-50% more pipeline per MQL generated. Sales satisfaction with lead quality expected to improve; rejection rate expected to decline from 44% to 20-25%.

---

## Success Metrics
- MQL-to-SQL conversion rate improvement: target ≥ 35% within 90 days of model rebuild (from <25% baseline)
- Sales lead rejection rate reduction: target <20% overall, <10% for Grade A MQLs (from >30% baseline)
- Pipeline value per MQL: target 20-35% increase in average pipeline opportunity size sourced from MQLs within two quarters
- Speed-to-first-touch SLA compliance: ≥90% of Grade A MQLs contacted within 4-hour SLA
- Scoring model confidence: closed-won backward scoring analysis shows ≥70% of closed-won customers scored in Grade A or B territory at time of MQL conversion
- Ghost MQL rate: reduce to <5% (MQLs that are never contacted within 30 days)
- Revenue Operations alignment: quarterly scoring review adopted as a standing process with cross-functional attendance (Marketing + Sales + RevOps)

## Related Prompts
- [AI-Powered B2B Lead Source Quality Scoring & Channel Revenue Contribution Intelligence Engine](./AI-Powered-B2B-Lead-Source-Quality-Scoring-&-Channel-Revenue-Contribution-Intelligence-Engine.md)
- [AI-Powered B2B Lead Velocity Rate & Pipeline Generation Momentum Intelligence Engine](./AI-Powered-B2B-Lead-Velocity-Rate-&-Pipeline-Generation-Momentum-Intelligence-Engine.md)
- [AI-Powered B2B SaaS CRO Analytics & Experimentation Intelligence Engine](../Conversion-Rate-Optimization-Analytics/AI-Powered-B2B-SaaS-CRO-Analytics-&-Experimentation-Intelligence-Engine.md)
- [AI-Powered B2B Revenue Operations Intelligence & Marketing-Sales Unified Pipeline Analytics Engine](../Sales-Enablement-Analytics/AI-Powered-B2B-Revenue-Operations-Intelligence-&-Marketing-Sales-Unified-Pipeline-Analytics-Engine.md)

## Integration Tips
- **Salesforce / HubSpot CRM**: Build the dual-dimension scoring model natively using custom fields for Fit Score and Engagement Score as separate properties. Create a composite "MQL Grade" field (A/B/C) derived from the 2x2 matrix logic. Route leads using assignment rules triggered on MQL Grade, not just overall score. Configure rejection reason as a required picklist on the Lead/Contact record that sales must complete before marking "Disqualified."
- **Marketo / Pardot / HubSpot Marketing Automation**: Build separate scoring programs for Fit and Engagement dimensions. Set decay rules on engagement scores using "Score is not changed" triggers with a specified number of days. Track page-depth visits using progressive profiling or custom JavaScript events piped into your MAP.
- **6sense / Demandbase**: Layer AI intent scores from your ABM platform into the account-level scoring formula. Map 6sense buying stage to a point multiplier: "Awareness" stage accounts = 0 account-level bonus; "Decision" stage accounts = +20 pts on every contact at that account. Route "Decision" stage accounts to direct AE outreach regardless of individual contact score.
- **Gong / Chorus**: Mine rejected lead calls for rejection language patterns. Use call transcripts to identify the top 5 verbatim rejection reasons from sales — this gives you qualitative signal data to supplement the structured rejection taxonomy. Feed insights quarterly into the scoring model calibration process.
- **Zapier / Make.com**: Automate the weekly rejection report by triggering a Slack or email digest every Monday morning. Pull CRM data on rejections from the previous 7 days, broken down by rejection reason, lead grade, and lead source. Send to Marketing + Sales Ops + Demand Gen leadership automatically.
- **Google Sheets / Looker / Tableau**: Build the lead scoring performance dashboard with four panels: (1) MQL grade distribution over time; (2) Rejection rate by grade and by source; (3) MQL-to-pipeline conversion by grade; (4) Closed-won backward score analysis scatter plot. Refresh weekly from CRM data.

## Troubleshooting

**Problem:** After implementing the new scoring model, MQL volume dropped 40% and the demand gen team is panicking about missing volume targets.
**Solution:** Volume drop after recalibration is expected and healthy — it signals the old model was generating ghost MQLs. Reframe the conversation from "MQL volume" to "pipeline value generated by MQLs." If pipeline quality improves (higher MQL-to-SQL rate, higher average deal size from MQL-sourced pipeline), the revenue outcome is better even with fewer MQLs. Simultaneously, adjust MQL volume targets downward and pipeline influence targets upward in OKRs. A 40% volume reduction with a 50% conversion rate improvement produces more pipeline value, not less.

**Problem:** Sales is still rejecting Grade A MQLs at a high rate (>15%) after the model rebuild.
**Solution:** Grade A lead rejection at this rate signals one of three issues: (1) Fit scoring is miscalibrated — pull a sample of 20 Grade A rejections and review them manually with an experienced SDR to identify the pattern; (2) Sales is not following the routing SLA — Grade A MQLs not contacted within 4 hours lose momentum; contact the sales ops team about SLA enforcement; (3) The MQL definition has not been communicated or accepted by sales leadership — run a 30-minute "MQL definition alignment session" with your VP Sales, VP Marketing, and a sample of SDR team leaders to review the new scoring logic and get explicit buy-in on the Grade A threshold.

**Problem:** Product usage data (PLG signals) is not flowing into your CRM or marketing automation platform, making Tier 3 scoring impossible.
**Solution:** This is a RevOps infrastructure problem before it's a scoring problem. As an interim measure, export weekly product usage reports from Amplitude/Mixpanel/Pendo and manually enrich CRM records via CSV upload or Zapier automation. Build the case for a real-time product data integration by quantifying the conversion rate uplift from PLG-sourced leads vs. purely inbound leads — in most PLG companies, product-qualified leads convert at 3-5× the rate of non-product-engaged leads. Use that data to justify the engineering time to build the integration properly.

## Version History
- v1.0: Initial creation (auto-generated)
