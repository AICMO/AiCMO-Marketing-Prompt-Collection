# AI-Powered Partner & Channel Attribution & Ecosystem Revenue Intelligence Engine - Prove the ROI of Your Partner Program Before the CFO Kills It

**Difficulty:** Advanced | **Time:** 25-30 min | **Tags:** b2b, analytics, attribution, partner-marketing, channel, ecosystem-led-growth, elg, saas, revenue-operations, salesforce, hubspot

## Overview
Designs and implements a rigorous attribution and ROI measurement framework for partner-sourced, partner-influenced, and co-marketing revenue — separating direct marketing contribution from ecosystem channel performance, building defensible partner ROI calculations, and automating the reporting that keeps partner programs funded. Use this when your CFO questions why you're paying partner managers if you can't prove partner revenue, when Sales takes credit for partner-sourced deals, or when you're scaling an Ecosystem-Led Growth (ELG) motion and need attribution infrastructure to match.

## Quick Copy-Paste Version

You are a senior B2B revenue operations analyst specializing in partner and channel attribution. I need you to design a complete attribution and ROI measurement framework for my partner/channel program.

My business context:
- Company type: [B2B SaaS / Enterprise Software / Professional Services]
- ARR: [$X]
- ACV: [$X average contract value]
- Average sales cycle: [X days]
- Partner program types active: [Reseller / Referral / Technology Integration / Co-Sell / MSP / Agency / Marketplace]
- Estimated % of revenue from partners: [X%]
- CRM: [HubSpot / Salesforce]
- Partner portal or PRM tool: [PartnerStack / Impartner / Alliances / Crossbeam / None — managed in CRM]
- Current partner attribution method: [Deal registration tags / Manual CRM fields / No formal tracking]
- Biggest partner attribution pain point: [e.g., "Sales takes credit for partner-sourced deals," "Can't separate partner-influenced from partner-sourced," "Co-marketing ROI is invisible"]

Please deliver:
1. Partner attribution taxonomy — define the 5 key partner revenue classifications (Partner-Sourced, Partner-Influenced, Co-Sell, Co-Marketing Influenced, Partner-Accelerated) with clear definitions and CRM field requirements for each
2. Attribution data architecture — the exact CRM configuration (fields, workflows, deal stages) needed to capture partner contribution accurately
3. Partner ROI calculation methodology — how to calculate ROI for each partner type with example formulas, including how to value partner-influenced vs. partner-sourced deals differently
4. The 5 core partner attribution reports — with metrics, dimensions, and filters needed to prove program ROI to finance
5. Partner vs. direct channel comparison — framework for comparing partner CAC, payback period, and LTV against direct marketing channels
6. 30-day implementation plan — steps to move from manual tracking to automated partner attribution

## Advanced Customizable Version

ROLE: You are a VP of Revenue Operations and Partner Analytics with 12 years of B2B SaaS experience building partner attribution programs at companies scaling from Series A through post-IPO. You have deep expertise in Ecosystem-Led Growth (ELG) strategy, partner revenue attribution in Salesforce and HubSpot, PRM tools (PartnerStack, Impartner, Crossbeam), and the organizational change management required to get Sales to stop claiming partner deals as self-sourced. You understand the technical implementation of deal registration, account mapping, and co-sell workflows and how they connect to marketing attribution.

COMPANY CONTEXT:
- Company Name: [Company Name]
- Stage / ARR: [Series B / $18M ARR | Series C / $52M ARR | etc.]
- Industry vertical: [e.g., HR Tech, DevSecOps, FinTech, MarTech]
- ICP: [job titles, company sizes, industries]
- ACV: [$X]
- Sales cycle: [X days average]
- Current partner revenue %: [X% of new ARR]
- Partner program goal: [Grow partner revenue to X% of ARR by [date]]
- Revenue split: [$X New Business | $X Expansion | $X Renewal]
- GTM motion: [Primarily direct / Hybrid direct + partner / ELG-first]

PARTNER PROGRAM INVENTORY:

For each active partner type, provide:

**Referral Partners** (e.g., agencies, consultants, VARs who refer leads):
- Number of active referral partners: [X]
- Average deals referred/quarter: [X]
- Referral deal close rate vs. direct: [X% vs. X%]
- Referral fee structure: [X% of ACV / flat fee / revenue share]
- How referrals are currently tracked in CRM: [Deal field / Tag / Manual note / No tracking]

**Technology Integration Partners** (ISVs, platform partners, marketplace listings):
- Number of integration partners: [X]
- Marketplace listings (e.g., HubSpot App Marketplace, Salesforce AppExchange, AWS Marketplace): [list]
- Deals influenced by integration co-sell: [X/quarter, estimated]
- Joint marketing activities: [co-branded content / co-webinars / joint case studies / none]

**Reseller / MSP / Channel Partners** (partners who transact on your behalf):
- Number of active resellers/MSPs: [X]
- Revenue transacted through channel: [$X ARR]
- Deal registration process: [Partner portal / CRM-based / Email-based / None]
- Revenue recognition: [Net / Gross reporting]

**Strategic Co-Sell Partners** (large partners you co-sell with for enterprise deals):
- Partner names (if shareable): [e.g., Salesforce, AWS, ServiceNow]
- Co-sell deal volume: [X deals/quarter]
- Average ACV lift on co-sell deals vs. direct: [X%]
- Co-sell tracking method: [Crossbeam / Salesforce Partner Community / Spreadsheet]

**Co-Marketing Partners** (partners you run joint campaigns with):
- Active co-marketing programs: [joint webinars / co-authored content / co-sponsored events / joint email campaigns]
- Co-marketing budget: [$X/quarter]
- Current co-marketing attribution method: [UTM tags / CRM campaign / No tracking]

CURRENT ATTRIBUTION STATE:
- Partner attribution method today: [Deal registration tags / Custom CRM fields / Manual sales rep entry / Crossbeam account mapping / No formal system]
- Data quality: [High — every partner deal is tagged / Medium — inconsistent / Low — most partner deals are untracked]
- Known attribution problems (select all that apply):
  ☐ Sales reps log partner deals as self-sourced to protect commission
  ☐ No distinction between "partner introduced the account" vs. "partner influenced deal in late stage"
  ☐ Co-marketing attribution invisible — can't tell which webinars or content pieces influenced partner-channel deals
  ☐ Deal registration happens but doesn't flow into marketing attribution reports
  ☐ Can't calculate true partner CAC because indirect costs (partner manager salary, PRM tooling, co-marketing spend) aren't factored in
  ☐ Partner-influenced pipeline is overclaimed by partner team and undercounted by Marketing
  ☐ Marketplace-sourced deals (AWS, Salesforce AppExchange) are miscategorized as "inbound"

TECHNICAL STACK:
- CRM: [HubSpot / Salesforce]
- PRM/Partner Portal: [PartnerStack / Impartner / Alliances / Reveal / Crossbeam / None]
- Account Mapping Tool: [Crossbeam / Reveal / Manual spreadsheet]
- Marketing Automation: [HubSpot / Marketo / Pardot]
- BI Tool: [Looker / Tableau / Power BI / HubSpot Reports / Salesforce Reports]
- Data Warehouse: [Snowflake / BigQuery / Redshift / None]
- Marketplace Platforms: [AWS Marketplace / Salesforce AppExchange / HubSpot App Marketplace / None]

DELIVERABLES REQUIRED:

**Section 1: Partner Revenue Classification Framework**

Define and operationalize the 6 partner revenue categories with airtight definitions:

| Category | Definition | CRM Evidence Required | Who Gets Credit | How to Measure |
|---|---|---|---|---|
| Partner-Sourced (Hard) | Partner introduced the account, no prior marketing or sales contact existed | Deal registration before any CRM activity; partner listed as "deal source" in CRM; confirmed by partner + verified by sales | Partner Channel | Pipeline Sourced, Closed-Won ARR |
| Partner-Sourced (Soft) | Account existed in CRM as a cold prospect; partner introductions triggered active sales cycle | Account had <2 CRM activities before partner introduction; deal registration date precedes first AE-owned activity | Shared: 70% Partner / 30% Marketing | Pipeline Influenced |
| Partner-Influenced | Marketing or sales had active relationship; partner accelerated deal close by providing advocacy, reference, or technical validation | Partner activity log in CRM; partner mentioned in deal notes or Gong transcript; deal closed within 30 days of partner introduction | Shared: 50% Partner / 50% Marketing | Pipeline Influenced |
| Co-Marketing Influenced | Prospect attended a co-marketing event/content before entering pipeline | Co-marketing campaign touchpoint in CRM before opportunity creation; UTM or campaign source = partner co-marketing | Co-Marketing Attribution | Pipeline Influenced |
| Partner-Accelerated | Deal was already in late stage; partner involvement shortened time-to-close | Opportunity age comparison: partner-involved vs. baseline for same ACV tier; stage velocity data from CRM | Shared: 30% Partner / 70% Sales | Time-to-Revenue, Cycle Compression |
| Marketplace-Transacted | Customer discovered, evaluated, or purchased via a marketplace listing | Lead source = [Marketplace name]; deal created via marketplace integration; contract signed through marketplace | Marketplace Channel | Marketplace ARR, MPPO (Marketplace Pipeline Passed to Owned) |

**Section 2: CRM Attribution Architecture**

Design the exact CRM field and workflow configuration for my stack:

For **Salesforce**:
- Custom Opportunity fields: `Partner_Source__c` (picklist: Direct/Referral/Reseller/Co-Sell/Marketplace), `Partner_Name__c` (lookup to Partner Account), `Partner_Attribution_Type__c` (picklist: Sourced-Hard/Sourced-Soft/Influenced/Co-Marketing/Accelerated/Marketplace), `Partner_Deal_Registration_Date__c` (date), `Partner_Influenced_Revenue__c` (currency, auto-calculated), `Co_Sell_Partner__c` (multi-select), `Co_Marketing_Campaign__c` (lookup to Campaign)
- Validation rules: If `Partner_Source__c = Referral`, then `Partner_Deal_Registration_Date__c` must be populated (enforces tracking discipline)
- Process Builder / Flow: Auto-tag opportunities as "Partner-Sourced" when deal registration record is created in PRM before opportunity close date
- Campaign Influence: Configure Salesforce Campaign Influence to include partner co-marketing campaigns, with `Partner_Co_Marketing__c = TRUE` flag on campaign records

For **HubSpot**:
- Custom Deal properties: `partner_source` (dropdown), `partner_name` (single-line text), `partner_attribution_type` (dropdown), `deal_registration_date` (date picker), `partner_influenced_revenue` (calculated number), `co_marketing_campaign` (association to Campaign)
- Workflow: When deal is created with `partner_source = Referral` AND `deal_registration_date` is not empty, enroll in "Partner Deal Tracking" workflow that adds deal to partner attribution dashboard list
- Attribution Report: Use HubSpot's Custom Report Builder with `partner_source` as a dimension across Pipeline, Closed-Won Revenue, and Close Rate

**Section 3: Partner ROI Calculation Methodology**

Design complete ROI formulas for each partner type:

**Referral Partner ROI:**
Gross Partner Revenue = Sum of ACV from partner-sourced deals (rolling 12 months)
Partner Program Costs = Referral fees paid + Partner manager time (% of salary) + Co-marketing spend + PRM tooling allocated cost
Partner CAC = Partner Program Costs / Number of partner-sourced deals
Partner LTV = Partner Gross Revenue × (1 / Churn Rate for partner-sourced cohort)
Partner CAC Payback = Partner CAC / (ACV × Gross Margin)
Partner Program ROI = (Gross Partner Revenue - Partner Program Costs) / Partner Program Costs × 100

Show benchmark comparison: Partner-sourced deals should typically show 30-50% lower CAC and 20-40% higher close rates than direct-sourced deals due to trust transfer. If your data doesn't show this, flag the partner program for restructuring.

**Technology Partner (Marketplace) ROI:**
Marketplace Revenue = ARR from marketplace-listed leads + Co-sell assisted ARR
Marketplace Costs = Listing fees + Marketplace transaction fees (typically 3-15% of ARR) + Technical integration costs (amortized) + Alliance manager time
Marketplace Net Revenue = Marketplace Revenue - Marketplace Transaction Fees
Marketplace ROI = (Marketplace Net Revenue - Non-Transaction Costs) / Non-Transaction Costs × 100
Marketplace ACV Lift = Average ACV of marketplace deals / Average ACV of comparable direct deals

Key metric: Track "MPPO" (Marketplace Pipeline Passed to Owned) — the % of marketplace leads that graduate to CRM-managed opportunities. This is the health metric for marketplace motion efficiency.

**Co-Sell Partner ROI:**
Co-Sell ACV Lift = (Average ACV of co-sell deals - Average ACV of direct comparable deals) / Average ACV of direct deals
Co-Sell Cycle Compression = (Average days-to-close for direct deals - Average days-to-close for co-sell deals) / Average days-to-close for direct deals
Co-Sell Deal Value = Co-Sell ACV Lift × Number of co-sell deals + (Revenue value of cycle compression × WACC adjustment)
Co-Sell Program Costs = Alliance manager time + Co-sell tooling (Crossbeam/Reveal) + Co-marketing spend with co-sell partners
Co-Sell ROI = Co-Sell Deal Value / Co-Sell Program Costs × 100

**Section 4: The 6 Core Partner Attribution Reports**

Report 1: **Partner Revenue Dashboard** (monthly, executive-facing)
- Dimensions: Partner Type, Partner Name, Quarter
- Metrics: Partner-Sourced ARR, Partner-Influenced ARR, Partner Close Rate vs. Direct Close Rate, Partner CAC vs. Direct CAC, Partner NRR Cohort vs. Direct NRR Cohort
- Visualization: Waterfall chart showing total new ARR split by source (Direct Marketing, Partner-Sourced, Marketplace, Co-Sell); trend line for partner % of new ARR over 8 quarters
- Alert: Auto-flag if any partner produces 0 deal registrations in a rolling 90-day window (partner at-risk signal)

Report 2: **Partner CAC & ROI Analysis** (quarterly, Finance/CFO)
- Dimensions: Partner Type, Individual Partner, Cohort (Quarter of First Deal)
- Metrics: Partner Acquisition Cost (all-in), Partner ACV, Partner Gross Margin, Partner CAC Payback (months), Partner LTV:CAC Ratio, Partner NRR (12-month cohort)
- Comparison view: Overlay partner metrics against direct channel metrics for same period
- Decision triggers: If Partner CAC Payback > 18 months, flag for partner tier review; if Partner LTV:CAC < 3x, flag for program restructuring

Report 3: **Co-Marketing Attribution Waterfall** (monthly, Marketing/Partner team)
- Dimensions: Co-Marketing Campaign, Partner Name, Campaign Type (webinar/content/event), Quarter
- Metrics: Campaign Registrations, MQLs from Co-Marketing, Opportunities Influenced, Pipeline Value, Closed-Won ARR, Co-Marketing ROI (ARR / Campaign Cost)
- Attribution logic: Count opportunity as "co-marketing influenced" if any contact on the deal attended/downloaded a co-marketing asset before opportunity creation date
- Filters: Partner name, campaign type, date range, deal stage

Report 4: **Deal Registration Velocity & Integrity Report** (weekly, Partner Operations)
- Dimensions: Partner Name, Deal Registration Date, Opportunity Stage at Registration, Days from Registration to Closed-Won
- Metrics: Deal registration volume by partner (trending), % of registered deals that progress to Qualified Opportunity, Average velocity from registration to Closed-Won, Registration-to-win rate by partner
- Integrity flags: Deals registered after opportunity was already in "Proposal" stage (retroactive gaming); deals registered by same partner for same account within 90 days of a prior registration (potential stuffing)

Report 5: **Partner vs. Direct Channel Comparison** (quarterly, CMO/Board)
- Head-to-head comparison table:

| Metric | Direct (Marketing-Sourced) | Referral Partners | Co-Sell Partners | Marketplace | Target |
|---|---|---|---|---|---|
| New ARR ($) | | | | | |
| % of Total New ARR | | | | | |
| CAC ($) | | | | | |
| CAC Payback (months) | | | | | |
| Close Rate | | | | | |
| Average Sales Cycle (days) | | | | | |
| Average ACV ($) | | | | | |
| 12-Month NRR (cohort) | | | | | |
| LTV:CAC Ratio | | | | | |

Report 6: **Partner Attribution Integrity Audit** (quarterly, RevOps)
- Purpose: Identify systemic attribution errors before they compound
- Audit checks: (1) % of closed-won deals with no partner attribution field completed, (2) Deals where Sales marked "Direct-Sourced" but partner submitted deal registration for same account in same quarter, (3) Marketplace leads that were reclassified as "Inbound" in CRM, (4) Co-sell deals missing partner co-sell contact in CRM, (5) Partner-influenced pipeline overclaim rate (partner claims > Marketing's attributed touchpoint data)
- Output: Attribution Integrity Score (% of deals with complete, accurate partner attribution data) with remediation actions

**Section 5: Organizational Alignment — The "Who Gets Credit" Problem**

This is where most partner attribution programs break. Design the credit allocation policy and enforcement mechanism:

Sales compensation alignment:
- Define "partner deal" vs. "self-sourced deal" with objective criteria (not sales rep assertion)
- If a registered deal closes, Sales receives full quota credit (do not penalize reps for working partner deals — this creates incentive to hide partner involvement)
- Partner manager's quota/OKR is Partner-Sourced ARR, NOT Partner-Influenced ARR (this creates inflated influence claims)
- Disputed attribution: 3-business-day resolution SLA; RevOps adjudicates using CRM activity timestamps, not human testimony

Finance alignment:
- Present partner ROI as "effective CAC" against direct CAC: "Our partner channel acquires customers at $X compared to $Y via direct marketing — a $Z savings per customer"
- Include full-cost accounting in partner ROI (don't just count referral fees — include partner manager salary, PRM tooling, co-marketing spend)
- Show partner cohort NRR vs. direct cohort NRR — partner-sourced customers with strong trust-transfer often show higher retention (this is your most powerful CFO argument)

**Section 6: Implementation Roadmap**

Week 1-2: Attribution audit
- Audit last 12 months of closed-won deals: what % have any partner attribution data?
- Interview 5 AEs: how do they currently log partner involvement? (You will find inconsistency)
- Map existing CRM fields to the attribution taxonomy above — identify gaps
- Deliverable: Partner attribution gap analysis (1-page scorecard)

Week 3-4: CRM infrastructure
- Build or configure the 7 custom CRM fields outlined in Section 2
- Create validation rules enforcing deal registration date on partner-tagged deals
- Set up PRM integration (PartnerStack/Impartner) → CRM sync if applicable
- Configure UTM parameters for co-marketing campaigns: `utm_source=partner_[name]`, `utm_medium=co_marketing`, `utm_campaign=[program_name]`
- Deliverable: CRM configured, UTM governance doc for co-marketing distributed to partner managers

Week 5-6: Report infrastructure
- Build Reports 1 and 4 (Partner Revenue Dashboard and Deal Registration Velocity) in CRM BI tool
- Run first attribution integrity audit — expect to find 40-60% of partner deals missing attribution data in historical records
- Do NOT retroactively reclassify historical deals without Sales leadership buy-in (creates trust problems)
- Deliverable: Two core reports live with current and forward-looking data

Week 7-8: Organizational rollout
- Train AEs on new deal attribution policy: 30-min session, focus on "why it benefits them" (partner deals count toward quota, logging them correctly makes partner manager invest more in their accounts)
- Train partner managers on deal registration enforcement: same-day registration policy for referred accounts
- Publish Attribution Policy doc in internal wiki with sign-off from Sales, Marketing, and Finance VPs
- Deliverable: Policy doc published, training complete, 90% AE compliance target set

Week 9-12: Analytics maturity
- Build remaining 4 reports
- Run first quarterly Partner vs. Direct comparison for CFO review
- Establish attribution review cadence: monthly partner ops review + quarterly executive review
- Deliverable: Full reporting suite live; Q1 Partner ROI report delivered to CFO with budget implication recommendations

OUTPUT FORMAT: Deliver as a structured Partner Revenue Intelligence Report. Include an executive summary (1 page), each section labeled with clear headers, all tables fully populated with formulas and example values, and a one-page "Partner Attribution Quick Reference" showing the 6 classification categories and CRM field requirements for an AE to reference when closing a partner deal.

## Example Input/Output

**Input Example:**

Company: Meridian (B2B SaaS, Series C, $41M ARR)
ICP: VP HR and CHRO at 500-5,000 employee companies
ACV: $72,000 | Sales cycle: 68 days average | Buying committee: 3-4 stakeholders
GTM: Direct inbound (55%) + Referral partner program (30%) + HubSpot App Marketplace (15%)
Partner types: 47 active referral partners (HR consultants + HRIS implementation firms), 3 co-sell partnerships (Workday, Rippling, BambooHR), HubSpot App Marketplace listing
Current attribution: Deal registration in PartnerStack, syncs to Salesforce via Zapier — but 60% of deals close without registration; Sales reps routinely mark partner deals as "Direct — AE Sourced" to protect full commission

**Output Example (excerpt):**

**Partner Attribution Assessment for Meridian:**

*Critical Finding:* Meridian's PartnerStack → Salesforce sync is functional but incomplete. The 40% registration compliance rate means your true partner-sourced revenue is likely 2-3x what Salesforce currently reports. Based on industry benchmarks for HR Tech companies with mature referral networks, companies with 47 active referral partners in your ACV range typically see 35-45% of closed-won revenue traceable to partner involvement when attribution is fully implemented. Your current reporting shows ~30%, suggesting ~5-15 percentage points of partner-influenced deals are being logged as "Direct."

---

**Partner Revenue Reclassification (last 12 months, Meridian):**

| Reported (Current) | Actual (Post-Attribution Fix) | Delta |
|---|---|---|
| Direct Marketing-Sourced: $22.5M (55%) | Direct Marketing-Sourced: $18.9M (46%) | -$3.6M reclassified |
| Partner-Sourced (Hard): $4.1M (10%) | Partner-Sourced (Hard): $9.8M (24%) | +$5.7M recovered from "Direct" |
| Partner-Influenced: $8.2M (20%) | Partner-Influenced: $8.6M (21%) | +$0.4M |
| Partner-Accelerated: $0 (0%) | Partner-Accelerated: $1.2M (3%) | +$1.2M new category |
| HubSpot Marketplace: $5.7M (14%) | HubSpot Marketplace: $6.1M (15%) | +$0.4M (marketplace mis-tagged as Inbound) |
| **Total New ARR** | **$40.6M** | **Reconciliation: $0.4M ARR in attribution investigation** |

*Budget implication:* Your partner team has been undercounting hard-sourced partner revenue by ~$5.7M/year (58% underreporting). The correct ROI on your partner program (47 partners, 2 partner managers at ~$180K OTE each, $220K co-marketing budget, $48K PartnerStack) is:

- Correct Partner Program Costs: $626,000/year
- Correct Partner-Sourced ARR: $9.8M (hard) + $8.6M (influenced at 50% credit) = $14.1M attributed revenue
- Partner Program ROI: ($14.1M - $626K) / $626K = **2,152% ROI**

Compare to direct marketing: $8.2M marketing spend generating $18.9M sourced revenue = **130% marketing ROI**.

*Recommendation:* Double the partner co-marketing budget from $220K to $440K. This is your highest-ROI acquisition channel by a factor of 16x. The program is chronically underfunded because attribution reporting made it look like a $4.1M program generating 6.5x ROI — impressive but not extraordinary. The corrected 2,152% ROI changes the investment thesis completely.

---

**Workday Co-Sell Analysis (Meridian):**

| Metric | Meridian Direct Deals | Workday Co-Sell Deals |
|---|---|---|
| Average ACV | $72,000 | $118,500 (+65%) |
| Average Sales Cycle | 68 days | 41 days (-40%) |
| Close Rate (from SQL) | 24% | 51% (+113%) |
| 12-Month NRR | 108% | 127% (+19pts) |
| Deals/Quarter | ~42 | ~8 |

*Workday co-sell is Meridian's highest-quality revenue pipeline: 65% higher ACV, 40% shorter sales cycle, double the close rate, and 19 points higher NRR — meaning Workday-co-sold customers expand dramatically more than direct customers. The limiting factor is not co-sell ROI; it's Workday's capacity to co-sell. Recommendation: Invest in achieving "Built for Workday" certification and dedicated Workday Alliance Manager to unlock co-sell capacity.*

## Success Metrics

- **Partner attribution coverage rate:** % of closed-won deals with complete partner attribution data — all 6 classification fields populated (target: >85% within 60 days of CRM implementation; >95% within 90 days)
- **Deal registration compliance:** % of partner-sourced deals with deal registration submitted before opportunity close date (target: >90% for tier-1 partners; >75% program-wide)
- **Attribution integrity score:** % of closed-won deals where partner attribution classification is confirmed accurate via RevOps audit (target: >92% data integrity score quarterly)
- **Partner CAC vs. Direct CAC ratio:** Partner-sourced CAC should be 25-50% lower than direct-sourced CAC for a healthy referral program; if it's higher, program economics need restructuring
- **Partner NRR cohort advantage:** Partner-sourced customer cohorts should show 5-15 points higher NRR than direct-sourced cohorts (trust-transfer hypothesis confirmed)
- **Partner program ROI vs. direct marketing ROI:** Healthy partner program should show 3-10x higher ROI than direct demand generation; if parity or lower, program restructuring is warranted
- **Attribution dispute rate:** % of partner deals disputed between Sales and Partner team — target <5% quarterly with clear resolution SLA
- **Marketplace MPPO (Pipeline Passed to Owned):** % of marketplace leads that convert to CRM opportunities (target: >35% for mature marketplace listings; benchmark: top HubSpot App Marketplace ISVs see 40-60% MPPO)
- **Co-marketing campaign attribution rate:** % of co-marketing campaigns with complete UTM coverage enabling revenue attribution (target: 100% for all future campaigns within 30 days of policy rollout)

## Related Prompts

- [Multi-Touch Attribution & Revenue Marketing Intelligence Engine](./Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md)
- [AI-Powered Incrementality Testing & Causal Revenue Attribution Intelligence Engine](./AI-Powered-Incrementality-Testing-&-Causal-Revenue-Attribution-Intelligence-Engine.md)
- [AI-Powered B2B Marketplace-Led Growth & App Store Revenue Intelligence Engine](../../02_Product-Marketing/Partner-&-Channel-Marketing/AI-Powered-B2B-Marketplace-Led-Growth-&-App-Store-Revenue-Intelligence-Engine.md)
- [Ecosystem-Led Growth ELG & Partner-Qualified Pipeline Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Ecosystem-Led-Growth-ELG-&-Partner-Qualified-Pipeline-Intelligence-Engine.md)

## Integration Tips

- **Crossbeam / Reveal (Account Mapping):** Use Crossbeam to map your CRM accounts against partner CRMs — this gives you a data-driven list of accounts where partners have existing relationships, enabling proactive co-sell motion identification. Crossbeam's "overlap reports" export directly to Salesforce/HubSpot and can auto-populate `Co_Sell_Partner__c` fields when account overlap exists. Set up automated Crossbeam alerts when a prospect in your pipeline appears in a partner's "Customer" segment — this is your co-sell trigger signal.
- **PartnerStack:** PartnerStack's native Salesforce integration creates a `PartnerStack Deal Registration` object linked to your Opportunity. Configure the sync to populate `Partner_Name__c`, `Partner_Attribution_Type__c = Sourced-Hard`, and `Partner_Deal_Registration_Date__c` automatically on deal registration. Use PartnerStack's revenue reporting to reconcile against Salesforce monthly and flag discrepancies — these discrepancies almost always point to attribution fraud (deals logged as self-sourced by AEs).
- **HubSpot App Marketplace:** Marketplace leads arrive via the HubSpot Marketplace API as Contacts with `Lead Source = HubSpot Marketplace`. Build a HubSpot workflow: when `Lead Source = HubSpot Marketplace`, auto-set `partner_source = Marketplace` and `partner_attribution_type = Marketplace-Transacted` on associated deals. Use HubSpot's Campaign reporting to track co-marketing campaigns with partners by creating Campaign records tagged `partner_co_marketing = true` and associating co-marketing email sends, landing pages, and form submissions.
- **Salesforce (with Impartner PRM):** Impartner writes deal registration data directly to Opportunity `Partner_Source__c` and `Partner_Deal_Registration_Date__c` fields via native connector. Build a Salesforce Validation Rule: `IF(ISPICKVAL(Partner_Source__c, "Referral") && ISBLANK(Partner_Deal_Registration_Date__c), TRUE, FALSE)` with error message "Referral deals require a deal registration date." This forces AEs to either enter the registration date or reclassify the source — eliminating the "accidentally Direct" partner deal problem. Run a Salesforce report monthly on Opportunities with `Partner_Source__c = Direct` created within 14 days of a PartnerStack deal registration for the same Account — this is your AE attribution gaming detection query.
- **Looker / Tableau (Partner Intelligence Dashboard):** Build a partner attribution dashboard with 3 tabs: (1) Executive view — partner ARR waterfall by partner type and quarter, (2) Partner manager view — individual partner performance, deal registration velocity, co-marketing campaign ROI, (3) RevOps view — attribution integrity score, dispute log, compliance rates. Connect to both CRM and PRM data sources for a unified view. Use a "Partner vs. Direct" toggle parameter to dynamically compare KPIs across acquisition channels without building separate reports.
- **Gong / Chorus (Call Intelligence):** Configure keyword tracking for partner mentions: "PartnerStack," "deal registration," "[partner company names]," "introduced by," "referred by." Run a quarterly audit: for deals where AE marked "Direct-Sourced," review Gong transcripts for partner mentions. This is your highest-fidelity attribution integrity check — recorded sales calls don't lie. Build a Gong tracker called "Partner Attribution Risk" for deals above $50K ACV where partner names are mentioned but CRM shows Direct source.

## Troubleshooting

**Problem: Sales reps systematically log partner-sourced deals as "Direct — AE Sourced" because partner deals appear to give credit to the partner manager rather than to the AE, creating a perceived commission threat.**
Solution: This is the #1 partner attribution failure mode and it's an incentive design problem, not a data problem. Fix it with three changes: (1) Explicitly communicate in writing that partner deal credit does NOT reduce AE quota attainment — the AE receives full quota credit for any deal regardless of partner attribution classification. (2) Create an AE incentive to *accurately log* partner deals: a small SPiFF ($500-$1,000) for AEs whose partner-logged deals result in a second deal from the same partner within 12 months (this aligns AE behavior with partner relationship health). (3) Run the Gong/Chorus audit monthly and surface examples of partner-mention deals logged as Direct — present them in the weekly Sales team meeting as attribution corrections, not accusations. After 60 days, most reps self-correct when they realize the audit exists and the incentive structure doesn't punish partner deal logging.

**Problem: Co-marketing attribution is completely dark — joint webinars with partners, co-branded content, and shared email blasts generate leads but they all show up as "Inbound/Direct" with no partner connection visible in the CRM.**
Solution: Implement a 3-layer co-marketing attribution stack: (1) UTM governance — all co-marketing campaign URLs must use `utm_source=partner_[partnername]` and `utm_medium=co_marketing` (retroactively fix existing campaigns; establish this as a launch checklist requirement). (2) Landing page tagging — any co-marketing landing page on your domain should have a hidden form field pre-populated with the partner's name via URL parameter, which writes to the HubSpot/Salesforce `Partner Attribution` field on form submission. (3) CRM Campaign association — create a Campaign record for each co-marketing program tagged `co_marketing_partner = [name]` and add all registrants/downloads as Campaign Members; this enables Campaign Influence attribution even when UTMs are incomplete. Accept that event-based co-marketing (in-person partner events where leads are collected via badge scan or business card) will always have weaker attribution — use self-reported "How did you hear about us?" survey data at deal creation as a proxy for these offline co-marketing touches.

**Problem: Partner program team is claiming a massive "partner-influenced pipeline" number that Marketing and Finance find implausible — partner managers are overcounting influence to justify their headcount.**
Solution: Partner-influenced pipeline is the most abused metric in partner programs. The fix is definitional rigor enforced in the CRM: set a strict definition of "partner-influenced" with objective, automatable criteria — specifically, a partner must have (a) had a documented meeting, call, or email with a named contact at the account, (b) logged in the CRM within the opportunity's active sales window, or (c) attended a co-marketing event where the prospect also attended, within 90 days before opportunity creation. "The partner knows someone at the company" does not qualify. "The partner sent one email 14 months ago" does not qualify. Build a Salesforce validation workflow: the `partner_influenced` flag can only be set TRUE if a qualifying activity record with a partner contact exists on the account. Remove the ability for partner managers to manually override influence flags without RevOps approval. This typically reduces overclaimed influence by 40-60% but increases credibility with Finance — a smaller, credible number is worth more than a large, questioned one.

## Version History
- v1.0: Initial creation (auto-generated) — 2026-04-04
