# CAC Payback & Unit Economics Intelligence Engine - Know Your True Acquisition Cost by Channel, Cohort, and Segment

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** b2b, saas, analytics, cac, unit-economics, cohort-analysis, revenue-operations, automation

## Overview
Calculates fully-loaded Customer Acquisition Cost (CAC) by channel, segment, and cohort — then models payback periods, LTV:CAC ratios, and unit economics breakeven at every level of granularity. Use this when investors demand CAC payback proof, when you're diagnosing why growth is expensive, or when you need to determine which channels and segments are worth scaling vs. cutting.

## Quick Copy-Paste Version

You are a B2B SaaS finance and marketing analytics expert. Analyze my customer acquisition economics.

My data:
- Total sales & marketing spend (last 12 months): $[X]
- New customers acquired (last 12 months): [N]
- Breakdown by channel (% or $): [e.g., Paid Search 30%, Events 25%, Outbound SDR 20%, Content/Inbound 15%, Referral 10%]
- Average Contract Value (ACV): $[X]
- Average gross margin: [X]%
- Average logo churn rate: [X]% per year
- Sales cycle length: [X days/months]
- Typical time-to-revenue after close: [X days]

Please deliver:
1. Blended CAC — fully-loaded with sales, marketing, and overhead allocation
2. CAC by channel — which channels are most and least efficient to acquire customers through
3. CAC payback period — in months to recover acquisition cost from gross margin
4. LTV:CAC ratio — by channel and blended, using a 3-year and 5-year LTV horizon
5. Unit economics breakeven analysis — at what retention rate does each channel become profitable?
6. Efficiency benchmarks — how do my numbers compare to SaaS industry medians for my stage?
7. Top 3 levers to reduce CAC payback by 20% or more without cutting growth
8. Which channels/segments should I scale, hold, or cut based on unit economics?

Flag all assumptions. Show calculations. Output a decision-ready summary table.

## Advanced Customizable Version

ROLE: You are a VP of Marketing and Revenue Operations advisor with 15+ years building unit economics frameworks for B2B SaaS companies from Seed to Series D. You specialize in decomposing CAC by channel, cohort, and segment to identify where growth dollars are productive vs. destructive. You think in LTV:CAC, payback periods, and contribution margins — and you tie every recommendation to a financial outcome.

BUSINESS CONTEXT:
- Company: [Company Name]
- Stage: [Seed / Series A / Series B / Series C / Growth]
- ARR: $[X]
- ACV or ARPU: $[X average contract value or average monthly revenue per customer]
- Product type: [SaaS subscription / usage-based / transaction fee / hybrid]
- Sales motion: [Self-serve PLG / Inside Sales / Field Sales / Channel]
- Sales cycle: [< 30 days / 30–90 days / 90–180 days / 180+ days]
- Target segments: [SMB / Mid-Market / Enterprise — specify % of customer count and % of revenue by segment]
- Geographic focus: [US / EMEA / Global]
- Fiscal year: [Calendar year / specify if different]

SPEND DATA — provide for trailing 12 months and split by half or quarter if possible:

Sales Costs (fully-loaded):
- SDR/BDR salaries + commission: $[X]
- AE salaries + OTE commission: $[X]
- Sales management + operations: $[X]
- Sales tools (CRM, sales engagement, intelligence): $[X]
- Sales training + enablement: $[X]
- Subtotal Sales: $[X]

Marketing Costs (fully-loaded):
- Paid digital (search, social, display, retargeting): $[X]
  - Breakdown by channel if available: [Google: $X, LinkedIn: $X, Meta: $X, etc.]
- Content marketing (agency, writers, tools): $[X]
- Events and field marketing: $[X]
- Partner/affiliate commissions: $[X]
- Marketing headcount (fully-loaded with benefits): $[X]
- Marketing tools and technology: $[X]
- PR and brand: $[X]
- Subtotal Marketing: $[X]

Overhead Allocation (optional but improves accuracy):
- Estimated % of finance/ops supporting S&M: [X]%
- Recruiting costs for S&M hires: $[X]

REVENUE AND CUSTOMER DATA:
- New logos acquired (last 12 months): [N]
- Revenue from new logos in acquisition period: $[X]
- New ARR from new logos: $[X]
- By channel (% of new logos sourced by): 
  - Paid Search: [X]%
  - Paid Social: [X]%
  - Outbound SDR: [X]%
  - Content/Inbound: [X]%
  - Events: [X]%
  - Partner/Channel: [X]%
  - Referral/Word-of-Mouth: [X]%
  - Product-Led/Free Trial: [X]%
- Gross revenue retention (GRR): [X]%
- Net revenue retention (NRR): [X]%
- Logo churn rate: [X]% annually
- Gross margin on subscription revenue: [X]%
- Average customer lifetime (if known): [X months]

COHORT DATA (highly valuable — include if available):
For each acquisition cohort (by quarter or half-year):
- Cohort label: [e.g., Q1 2023]
- New customers in cohort: [N]
- Total ACV at acquisition: $[X]
- Revenue retained at 6, 12, 18, 24 months: [describe as % or absolute]
- Upsell/expansion revenue generated: $[X by period]

SEGMENT BREAKDOWN (include if selling to multiple segments):
For each major segment (SMB / Mid-Market / Enterprise):
- New logos acquired: [N]
- Average ACV: $[X]
- Average CAC (if known separately): $[X]
- Average gross margin: [X]%
- Logo churn by segment: [X]%
- Sales cycle by segment: [X months]

---

CAC ANALYSIS REQUIRED:

**Section 1: Fully-Loaded CAC Calculation**
Calculate blended CAC three ways:
- Simple CAC: (Total S&M Spend) / (New Customers)
- CAC including overhead allocation
- New ARR CAC: Total S&M Spend / New ARR — the metric SaaS investors use to compare across companies

Create a CAC breakdown table:
| Cost Category | Annual Spend | % of Total CAC | CAC Per Customer |
|--------------|-------------|----------------|-----------------|
| SDR/BDR | $X | X% | $X |
| AE Compensation | $X | X% | $X |
| Paid Digital | $X | X% | $X |
| Events | $X | X% | $X |
| Content/Marketing Ops | $X | X% | $X |
| Marketing Technology | $X | X% | $X |
| [Other categories] | $X | X% | $X |
| **Total Fully-Loaded** | **$X** | **100%** | **$X** |

Flag: What is the single largest cost driver? What is most controllable in the next 90 days?

**Section 2: CAC by Acquisition Channel**
For each channel, calculate:
- Channel-attributed CAC = Channel Spend / Customers Sourced by Channel
- Channel efficiency ratio = Blended CAC / Channel CAC (>1.0 means cheaper than average; <1.0 means more expensive)
- Channel payback period in months
- Channel LTV:CAC ratio

Present as:
| Channel | Channel Spend | New Logos | Channel CAC | vs. Blended | Payback | LTV:CAC |
|---------|--------------|-----------|-------------|-------------|---------|---------|

Flag: Multi-touch attribution caveat — channels that assist vs. source require different CAC treatment. Identify where channel attribution confidence is high vs. low.

**Section 3: CAC Payback Period Analysis**
Calculate payback period using two methods:

Method A — Gross Margin Payback:
- Formula: CAC / (ACV × Gross Margin %) × 12 = Payback in months
- Industry benchmarks: < 12 months (excellent, VC-fundable at scale); 12–18 months (good); 18–24 months (watch closely); > 24 months (unsustainable at scale without strong NRR)

Method B — Cumulative Cash Flow Payback:
- Model month-by-month contribution margin cash flows from an average new customer
- Include expansion revenue from NRR > 100%
- Show the cumulative cash flow curve until it crosses zero (actual payback point)
- If NRR > 120%, flag that payback may happen faster than Method A due to upsell

Create a payback period table by channel and segment showing both methods.

**Section 4: LTV:CAC Ratio Deep Dive**

Calculate LTV using two time horizons:
- LTV (3-year): ACV × Gross Margin × (1 - Annual Churn)^3 time-series discounted at 10% WACC
- LTV (5-year): Same calculation extended, including NRR-driven expansion

For each channel and segment, calculate:
- LTV:CAC at 3 years
- LTV:CAC at 5 years
- Minimum retention rate required for LTV:CAC ≥ 3x (the minimum for scalable growth)
- Current retention rate vs. required — are you above or below the threshold?

Industry benchmarks by stage:
- Seed/Series A: LTV:CAC > 2x (survival zone)
- Series B/C: LTV:CAC > 3x (fundable growth zone)
- Growth/Pre-IPO: LTV:CAC > 4x (efficient growth zone)

**Section 5: Cohort-Based Payback Analysis**
Using cohort data provided, analyze:
- How is CAC payback trending across cohorts? (Is it improving Q-over-Q or deteriorating?)
- Which cohorts have reached payback vs. which are still cash-negative?
- Revenue contribution by cohort at 12M, 24M, 36M from acquisition
- Cohort retention curves — are newer cohorts retaining better or worse than older cohorts?
- Net expansion revenue by cohort — which cohorts generate the most expansion ARR?

If no cohort data is provided, design the cohort tracking framework and identify the 5 data points needed to build it.

**Section 6: Unit Economics by Segment**
For each segment (SMB / Mid-Market / Enterprise):
- Fully-loaded CAC for segment
- Average ACV
- Gross margin
- Logo churn rate
- CAC payback period
- LTV:CAC ratio
- Minimum viable ACV to justify segment CAC (ACV below which the segment is economically unprofitable)
- Recommendation: Scale / Optimize / Deprioritize

Create a segment scorecard:
| Segment | CAC | ACV | Gross Margin | Payback | LTV:CAC | Verdict |
|---------|-----|-----|-------------|---------|---------|---------|

**Section 7: Sensitivity Analysis & Scenario Modeling**
Model what happens to unit economics under the following scenarios:
- Scenario 1 — CAC increases 20% (due to competitive bidding, headcount growth): New payback period, new LTV:CAC
- Scenario 2 — Logo churn increases 3 points (economic downturn, poor retention): Impact on LTV, required CAC reduction to maintain LTV:CAC > 3x
- Scenario 3 — NRR drops from current to 100% flat (no expansion): Full impact on LTV and payback
- Scenario 4 — ACV increases 15% (pricing power, move upmarket): Impact on payback period and LTV:CAC
- Scenario 5 — Gross margin improves 5 points (efficiency gains): Impact across all metrics

For each scenario, answer: Does the business remain fundable? What must be true to hit LTV:CAC ≥ 3x?

**Section 8: CAC Reduction Levers & Action Plan**
Identify and quantify the top 5 levers to reduce CAC payback by 20%+:

For each lever, provide:
- Current state (baseline metric)
- Target state (what good looks like)
- Estimated impact on CAC or payback period (in months)
- Time to impact (quick win < 90 days vs. strategic 6–12 months)
- Confidence level (High / Medium / Low)
- Specific action required

Common high-impact levers:
- Lead quality improvement (reduce unqualified demos — each unqualified demo costs SDR + AE time)
- Sales velocity improvement (shorter sales cycles reduce AE compensation per customer)
- Channel mix shift (move budget from high-CAC to low-CAC channels)
- Conversion rate optimization (higher MQL→SQL→Close rates reduce CAC denominator)
- Self-serve/PLG motion for SMB (remove S&M cost from small deal sizes)
- Partner/channel leverage (lower cost-per-customer via reseller channel)
- Customer success investment to reduce churn (payback period effectively shortens when customers stay longer)

**Section 9: Benchmark Comparison**
Compare all metrics against SaaS industry benchmarks by stage and ACV band:

| Metric | Your Current | Series [X] Median | Top Quartile | Your Percentile |
|--------|-------------|-------------------|--------------|----------------|
| Blended CAC Payback (months) | X | X | X | [Top/Mid/Bottom 25%] |
| LTV:CAC (3-year) | X | X | X | |
| S&M as % of Revenue | X | X | X | |
| New ARR CAC | $X | $X | $X | |
| NRR | X% | X% | X% | |
| Gross Margin | X% | X% | X% | |

Source benchmarks from: OpenView SaaS Benchmarks, Bessemer Atlas, KeyBanc SaaS Survey, Tomasz Tunguz research. Flag if your data falls in the bottom quartile for your stage — it requires explanation for investor conversations.

**OUTPUT REQUIREMENTS:**
- Executive summary: 150 words, investor-ready, answers "Is our unit economics story fundable at our stage?"
- All tables formatted for copy-paste into slides or board decks
- CAC payback timeline as a narrative chart description (months to payback with cumulative cash flow milestones)
- Color-coded verdict for each channel: Green (scale), Yellow (optimize), Red (cut or restructure)
- Top 10 prioritized actions ranked by expected impact on CAC payback period
- One-page "Unit Economics Summary Card" — the single table an investor or CFO wants to see

CONSTRAINTS:
- Never use "potential" or "could" — use quantified projections with stated assumptions
- Flag every input assumption that materially affects the output (if wrong, results change significantly)
- Separate what is mathematically certain from what requires behavioral/market assumptions
- All recommendations must be implementable without a new marketing technology purchase
- Prioritize reducing CAC payback over maximizing absolute LTV — payback period is the operational constraint at most growth stages

## Example Input/Output

**Input Example:**

Company: Meridian (B2B SaaS, Series B, $14M ARR, $28K ACV)
Period: Jan 2025 – Dec 2025
Total S&M spend: $4.1M (Sales $2.4M, Marketing $1.7M)
New logos: 78
Gross margin: 74%
Logo churn: 11% annual
NRR: 118%
Sales cycle: 65 days average

Channel breakdown of new logos:
- LinkedIn Ads: 22% of logos, $420K spend
- Google Search: 14% of logos, $280K spend
- Outbound SDR: 31% of logos, $940K S&M cost
- Events/Webinars: 18% of logos, $380K spend
- Content/Inbound: 11% of logos, est. $220K attribution
- Referral: 4% of logos, est. $30K attribution cost

---

**Output Example (abbreviated):**

**EXECUTIVE SUMMARY**
Meridian's blended CAC payback is 19.3 months — above the 12–18 month Series B benchmark, creating a cash efficiency problem as you scale. LTV:CAC at 3 years is 2.8x (below the 3x fundable threshold), but NRR of 118% extends effective payback to 15.1 months when expansion revenue is included. The primary issue: Outbound SDR has a $38,200 CAC with a 26-month payback — structurally unprofitable at $28K ACV unless churn drops below 8%. Recommended: Shift $350K from SDR into Content/Inbound and LinkedIn Ads (CAC: $8,400 and $12,900 respectively). Projection: Blended CAC drops to ~$44K, payback period to 15.8 months, LTV:CAC improves to 3.4x. Three quick wins: (1) Increase demo-to-close rate from 22% to 28% via better qualification ($8,200 CAC reduction), (2) Launch PLG self-serve for SMB tier, (3) Double referral program investment (highest-ROI channel at $9,600 CAC).

**Blended CAC Calculation**
| Cost Category | Annual Spend | % of Total | CAC Per Customer |
|--------------|-------------|------------|-----------------|
| AE Compensation | $1,240K | 30.2% | $15,900 |
| SDR/BDR | $680K | 16.6% | $8,700 |
| LinkedIn Ads | $420K | 10.2% | $5,400 |
| Events | $380K | 9.3% | $4,900 |
| Google Search | $280K | 6.8% | $3,600 |
| Sales Tools (CRM, SE, Intel) | $320K | 7.8% | $4,100 |
| Marketing Headcount | $460K | 11.2% | $5,900 |
| Content & Ops | $220K | 5.4% | $2,800 |
| Other | $100K | 2.4% | $1,300 |
| **Total Fully-Loaded** | **$4.1M** | **100%** | **$52,600** |

**CAC by Channel**
| Channel | Spend | Logos | Channel CAC | vs. Blended | Payback (GM) | LTV:CAC |
|---------|-------|-------|-------------|-------------|-------------|---------|
| Referral | $30K | 3 | $9,600 | 0.18x ✅ | 5.2 mo | 8.3x |
| Content/Inbound | $220K | 9 | $24,400 | 0.46x ✅ | 13.3 mo | 3.5x |
| LinkedIn Ads | $420K | 17 | $24,700 | 0.47x ✅ | 13.4 mo | 3.4x |
| Google Search | $280K | 11 | $25,500 | 0.48x ✅ | 13.9 mo | 3.3x |
| Events | $380K | 14 | $27,100 | 0.52x ✅ | 14.7 mo | 3.1x |
| Outbound SDR | $940K | 24 | $38,200 | 0.73x ⚠️ | 20.7 mo | 2.2x |

**Key Insight:** SDR-sourced customers require 20.7 months payback at $28K ACV. At Meridian's Series B stage, this is a material drag. The $940K SDR investment acquiring 24 customers compares unfavorably to $420K LinkedIn spend acquiring 17 customers with 35% faster payback. Recommendation: Restructure SDR motion toward Mid-Market accounts ($50K+ ACV) where payback drops to 11.6 months and deprioritize SDR-led SMB prospecting entirely.

## Success Metrics

- Blended CAC is calculated using fully-loaded S&M costs (not just ad spend)
- CAC payback is computed by channel, with at least 3 channels showing differentiated payback periods
- LTV:CAC is calculated at both 3-year and 5-year horizons with stated discount rate
- Segment analysis identifies at least one segment to scale and one to deprioritize
- Sensitivity analysis quantifies impact of churn worsening by 3 points and CAC increasing 20%
- Benchmark comparison places the company in a specific percentile vs. stage peers
- Action plan includes at least 3 levers that can reduce payback period within 90 days

## Related Prompts

- `../../05_Analytics-&-Performance/Customer-Lifetime-Value-Analytics/Customer-Lifetime-Value-Prediction-&-Acquisition-Investment-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`
- `../../05_Analytics-&-Performance/Marketing-Mix-Modeling-&-Budget-Optimization/Marketing-Mix-Modeling-&-Media-Investment-Intelligence-Engine.md`
- `../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-Budget-Defense-&-CFO-Finance-Intelligence-Engine.md`

## Integration Tips

- **HubSpot CRM:** Export "Deals > Closed Won by Original Source" report with associated contact and deal create dates. Use Original Source drill-down to get channel attribution. Combine with Marketing > Campaigns cost data. Run a Custom Report: Deals by Close Date + Contact Original Source to get channel-attributed logos.
- **Salesforce:** Build a custom report: Closed Won Opportunities + Primary Campaign Source + Close Date. Map Primary Campaign Source to your channel taxonomy. Export as CSV and aggregate spend per channel from your marketing finance tracker to calculate channel-level CAC. Use Salesforce Einstein or a BI tool to build cohort views by Close Quarter.
- **Google Sheets / Excel:** Build a "Unit Economics Dashboard" with three tabs: (1) Spend by Channel by Month, (2) New Logos by Channel by Month, (3) Formulas tab computing CAC, LTV, Payback by channel. Link to this prompt output for quarterly refreshes. Template available in the integrations directory.
- **Looker / Tableau / Power BI:** Connect CRM opportunity data + ad platform spend data into a single "Go-To-Market Performance" dataset. Build a CAC payback curve visualization (x-axis: months since acquisition, y-axis: cumulative contribution margin). Segment by cohort quarter to show improvement trend.
- **Carta / Stripe / Chargebee:** For subscription businesses, connect revenue data directly to calculate MRR by cohort and month. This enables the cumulative cash flow payback curve in Section 3 to be built dynamically rather than estimated.
- **Notion / Confluence:** Publish the "Unit Economics Summary Card" from Section 9 as a standing page in your investor/board reporting wiki. Update quarterly. Tag the CMO, CFO, and CEO as reviewers. Version history tracks improvement over time — which matters in fundraising narratives.
- **Zapier / Make:** Automate: Quarterly → pull Closed Won data from CRM + Spend data from Google Sheets → run through this prompt → generate updated Unit Economics Summary Card → post to Slack #executive-metrics and attach to Board deck folder in Google Drive.
- **Investor Data Rooms:** The output from Sections 1–6 maps directly to the "Unit Economics" tab investors expect in a Series B/C data room. The benchmark comparison (Section 9) pre-answers the diligence question "How do your economics compare to peers?"

## Troubleshooting

**Problem: "Our multi-touch attribution makes it impossible to calculate clean channel-level CAC — every deal touches 8+ channels."**
Solution: Use two parallel approaches. First, calculate "channel-sourced CAC" using first-touch or opportunity-creation source (what first generated the pipeline opportunity). Second, calculate "channel-influence CAC" using MQL touchpoints. The prompt's channel CAC table uses sourced CAC (cleaner for budget decisions). Flag influenced channels separately with a note: "LinkedIn influenced 60% of all deals but sourced 22% — its assist role is underrepresented in the channel CAC table." For fully blended deals, allocate a proportional share of shared channels based on touchpoint frequency. The important thing is to be consistent quarter-over-quarter so trends are meaningful.

**Problem: "Our SDR team insists their CAC looks worse because they work the hardest deals — the ones Content/Inbound can't close."**
Solution: This is the most common S&M tension. Segment the analysis: calculate SDR-sourced CAC separately for (a) deals where Content/Inbound had no prior touches vs. (b) deals where SDR followed up on an existing inbound lead. If (b) is significantly more efficient, you have a strong case for restructuring SDR as a "conversion assist" motion rather than a cold-sourcing engine — which typically reduces SDR headcount needs while improving their quota attainment. Also compare deal velocity: SDR-sourced deals that start cold often have longer sales cycles, multiplying the AE compensation cost per deal. Quantify this in the Section 2 table.

**Problem: "My NRR is 130%+ — doesn't that make my payback period look artificially long since I'm not capturing expansion in the CAC calculation?"**
Solution: You're right — traditional CAC payback undercounts the economics of high-NRR businesses. Use Method B (Cumulative Cash Flow Payback) from Section 3, which explicitly models expansion revenue month-by-month. A company with 130% NRR often reaches true cash payback 30–40% faster than gross margin payback suggests. Additionally, calculate "Expansion-Adjusted LTV:CAC" by adding expected net expansion ARR (NRR-100% × initial ACV) to the LTV numerator across your customer lifetime. This is the number to lead with in investor conversations — it shows the full unit economics picture, not just the static acquisition cost.

## Version History
- v1.0: Initial creation (auto-generated)
