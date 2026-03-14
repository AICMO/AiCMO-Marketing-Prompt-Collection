# Customer Lifetime Value Prediction & Acquisition Investment Intelligence Engine - Maximize Revenue Per Customer Acquired

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, saas, analytics, ltv, cac, acquisition, retention, revenue, automation, reporting

## Overview
Predicts customer lifetime value by segment using early behavioral and firmographic signals, then calculates optimal CAC targets, LTV:CAC ratios, and payback periods per segment to drive smarter acquisition budget allocation. Use this when planning quarterly budgets, deciding which ICPs to prioritize, or justifying aggressive acquisition spend to your CFO.

## Quick Copy-Paste Version

You are a senior B2B SaaS revenue analyst. I need a complete Customer Lifetime Value analysis and acquisition investment optimization report for my business.

Here is my data:
- Product/service: [brief description]
- Business model: [SaaS subscription / usage-based / transactional]
- Average contract value (ACV): [$X]
- Average customer lifespan: [X months/years OR churn rate: X% monthly/annually]
- Average gross margin: [X%]
- Current CAC by channel: [e.g., Google Ads: $X, LinkedIn: $X, Events: $X, SDR: $X]
- Customer segments: [e.g., SMB (<100 employees), Mid-Market (100-999), Enterprise (1000+)]
- Expansion revenue (NRR): [X% net revenue retention]
- Time to first value: [X days after signup/close]

Please deliver:
1. LTV calculation by segment using three models: simple (ACV × lifespan), margin-adjusted (ACV × lifespan × gross margin), and expansion-adjusted (incorporating NRR)
2. LTV:CAC ratio by channel and segment — flag any below 3:1 as underperforming
3. CAC payback period by segment (months to recover acquisition cost)
4. Recommended maximum CAC targets by segment to achieve 3:1 LTV:CAC
5. Budget reallocation recommendation: which segments/channels to increase vs. decrease spend
6. Top 3 early behavioral signals that predict high LTV (based on your data patterns)
7. Customer grade matrix: A (high LTV), B (medium LTV), C (low LTV) with profile of each
8. 90-day action plan to improve LTV across each grade
9. One-paragraph CFO-ready summary with the key investment thesis

Flag any data gaps that would improve the accuracy of this analysis. Format with tables where useful.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Analytics and Customer Economics with 15+ years of B2B SaaS experience. You specialize in cohort-based LTV modeling, unit economics optimization, and translating customer data into acquisition investment strategy. You have deep expertise in Salesforce, HubSpot, Gainsight, Amplitude, ChartMogul, and SQL-based cohort analysis.

COMPANY CONTEXT:
- Company: [Company Name]
- Stage: [Seed / Series A / B / C / Growth / Public]
- ARR: [$X]
- MRR: [$X]
- ACV (average contract value): [$X]
- ASP (average selling price, if different): [$X]
- Gross margin: [X%]
- Net Revenue Retention (NRR): [X%]
- Gross Revenue Retention (GRR): [X%]
- Monthly churn rate: [X%] OR Annual churn rate: [X%]
- Average sales cycle: [X days]
- Sales motion: [Inbound / Outbound / PLG / Channel / Hybrid]

CUSTOMER SEGMENTS TO ANALYZE:
Segment 1: [Name, e.g., SMB] — criteria: [e.g., <100 employees, <$50K ACV]
Segment 2: [Name, e.g., Mid-Market] — criteria: [e.g., 100-999 employees, $50K-$200K ACV]
Segment 3: [Name, e.g., Enterprise] — criteria: [e.g., 1000+ employees, >$200K ACV]
Segment 4 (optional): [Industry vertical, e.g., FinTech companies]

ACQUISITION DATA BY CHANNEL:
- Channel name | Monthly spend | Leads generated | Opportunities created | Closed-won deals | CAC
[Paste your data or describe it]

COHORT DATA (if available):
- Month 1 retention: [X%]
- Month 3 retention: [X%]
- Month 6 retention: [X%]
- Month 12 retention: [X%]
- Month 24 retention: [X%]
- Expansion revenue by cohort month: [X% of base ARR]

BEHAVIORAL SIGNALS AVAILABLE:
[List the product/behavioral data you track: e.g., login frequency, features used, seats added, API calls, integrations connected, support tickets, NPS scores]

ANALYSIS REQUESTED:

**1. LTV MODELING (run all three, recommend primary model)**

Model A — Simple LTV:
LTV = ACV × Average Customer Lifespan (years)
[Show calculation per segment]

Model B — Margin-Adjusted LTV:
LTV = ACV × Average Customer Lifespan × Gross Margin %
[Show calculation per segment]

Model C — Expansion-Adjusted LTV (recommended for SaaS with NRR > 100%):
LTV = (MRR × Gross Margin %) / Monthly Churn Rate
OR with expansion:
LTV = MRR × Gross Margin % × (1 / (Churn Rate - Expansion Rate))
[Show calculation per segment, note if expansion rate > churn rate = negative churn = infinite LTV]

Model D — Discounted Cash Flow LTV (for enterprises with long payback periods):
LTV = Σ (Monthly Revenue × Gross Margin %) / (1 + discount rate)^month
[Use 10% annual discount rate unless specified]

**2. CAC ANALYSIS**
For each channel and segment:
- Current CAC
- LTV:CAC ratio (flag <3:1 as warning, <1:1 as critical)
- CAC Payback Period = CAC / (MRR × Gross Margin %)
- Maximum allowable CAC to hit target LTV:CAC of [3:1 / 4:1 / specify]

**3. SEGMENT INVESTMENT MATRIX**
Create a 2×2 matrix plotting LTV (y-axis) vs. CAC Efficiency (x-axis):
- Stars (high LTV, low CAC): double down
- Question Marks (high LTV, high CAC): optimize or reduce spend
- Cash Cows (medium LTV, low CAC): maintain
- Dogs (low LTV, high CAC): cut or sunset

**4. EARLY LTV PREDICTION SIGNALS**
Based on the behavioral data provided, identify:
- Top 3 signals in first 30 days that predict top-quartile LTV (e.g., users who connect 3+ integrations in week 1 have 2.3× higher LTV)
- Top 3 signals that predict early churn / low LTV
- Recommended "LTV Health Score" formula using available signals
- Trigger points for CS intervention to rescue low-LTV-trajectory accounts

**5. BUDGET REALLOCATION RECOMMENDATION**
Current total acquisition budget: [$X/month]
- By channel: show current allocation vs. recommended allocation
- By segment: show current allocation vs. recommended allocation
- Expected impact on blended LTV:CAC ratio
- Expected impact on CAC payback period
- Projected ARR impact in 12 months if recommendations implemented

**6. LTV IMPROVEMENT ROADMAP**
For each customer grade (A/B/C):
- Grade A (top 20% by LTV): [retention strategies, expansion plays, advocacy programs]
- Grade B (middle 60% by LTV): [onboarding improvements, feature adoption, upsell sequences]
- Grade C (bottom 20% by LTV): [profitability threshold analysis, decide to serve or sunset segment]

**7. EXECUTIVE OUTPUT**
- One-page unit economics summary (LTV, CAC, payback, NRR by segment)
- CFO talking points: investment thesis for top 2 segments
- Board-ready KPI table with current state vs. 12-month targets

OUTPUT FORMAT: Use tables for all numeric comparisons. Bold key insights. Flag data quality gaps as [DATA GAP: X would improve accuracy]. End with 30-60-90 day action plan.

## Example Input/Output

**Input Example:**

Company: Meridian Analytics (B2B SaaS, Series B)
Product: Revenue intelligence platform for sales teams
ACV: $42,000 average
Gross margin: 76%
NRR: 118%
Annual churn: 14%
Segments: SMB (<100 employees, ACV $8K), Mid-Market (100-999 employees, ACV $45K), Enterprise (1000+ employees, ACV $180K)
CAC: SMB via Google Ads $2,400 | Mid-Market via SDR+Events $18,500 | Enterprise via ABM+Field $72,000

---

**Output Example (condensed):**

**LTV by Segment (Expansion-Adjusted Model):**

| Segment | ACV | Gross Margin | NRR | Effective Churn | LTV | Current CAC | LTV:CAC | Payback (mo) |
|---------|-----|-------------|-----|----------------|-----|-------------|---------|--------------|
| SMB | $8K | 76% | 104% | 10% net | $60,800 | $2,400 | 25.3:1 | 4.5 mo |
| Mid-Market | $45K | 76% | 119% | -5% net | $646,800* | $18,500 | 35:1 | 5.8 mo |
| Enterprise | $180K | 76% | 131% | -15% net | Capped at 10yr | $72,000 | 19:1 | 5.7 mo |

*Mid-Market has negative net churn — LTV model capped at 10-year horizon = $646,800

**Key Insight: SMB has a 25:1 LTV:CAC — nearly 9× the 3:1 minimum threshold — yet receives only 12% of acquisition budget. Mid-Market at 35:1 receives 31%. Recommendation: Shift 20% of Enterprise budget ($28K/mo) to SMB Google Ads and Mid-Market SDR — projected 12-month ARR impact: +$3.2M.**

**Early LTV Prediction Signals (from cohort analysis):**
1. Accounts connecting ≥3 CRM integrations in Day 1-14 → 3.1× higher 24-month LTV
2. Users inviting ≥5 colleagues in first 30 days → 2.4× higher expansion revenue
3. Completing onboarding checklist within 7 days → 68% lower churn probability

**30-Day Action Plan:**
- [ ] Add LTV:CAC ratio to weekly revenue dashboard in Tableau
- [ ] Tag all accounts in Salesforce with LTV Grade (A/B/C) based on 3-signal health score
- [ ] Brief CS team on Grade C intervention playbook — target 25 accounts this month
- [ ] Test $15K Google Ads budget increase to SMB segment; track CAC and first-30-day signals

## Success Metrics

- LTV:CAC ratio improves to ≥3:1 across all active segments within 2 quarters
- CAC payback period decreases by ≥15% within 6 months of budget reallocation
- Early LTV prediction signals achieve ≥70% accuracy in identifying top-quartile customers within 30 days
- CS team identifies at-risk Grade C accounts ≥30 days earlier than previous baseline
- CFO/board accepts LTV-based budget justification without requiring additional analysis

## Related Prompts

- [`../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Attribution-&-Revenue-Analytics/Multi-Touch-Attribution-&-Revenue-Marketing-Intelligence-Engine.md) — Use alongside to connect acquisition channel attribution to LTV by source
- [`../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md) — Align lead scoring thresholds with LTV grades
- [`../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Freemium-Conversion-&-PQL-Nurture-Automation-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Growth-Experimentation/Freemium-Conversion-&-PQL-Nurture-Automation-Engine.md) — Apply LTV segmentation to PLG conversion prioritization
- [`../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-Budget-Defense-&-CFO-Finance-Intelligence-Engine.md`](../../01_CMO-&-Leadership/Reporting-&-ROI/Marketing-Budget-Defense-&-CFO-Finance-Intelligence-Engine.md) — Use LTV analysis outputs directly in CFO budget presentations

## Integration Tips

- **Salesforce / HubSpot CRM:** Create a custom field `LTV_Grade` (A/B/C) and `Predicted_LTV` on the Account object. Populate via workflow automation triggered by early behavioral signals. Use for CS task prioritization and rep territory planning.
- **ChartMogul / Baremetrics:** Export cohort retention data directly into the Advanced prompt's "Cohort Data" section. These tools produce Month 1–24 retention curves ready to paste.
- **Amplitude / Mixpanel:** Build a behavioral cohort comparing "connected 3+ integrations in first 14 days" vs. not — export 12-month revenue retention difference to validate your LTV prediction signals.
- **Google Sheets / Notion:** Paste the output LTV:CAC table into a shared doc as the "Unit Economics Dashboard" — link from your weekly revenue review.
- **Zapier / Make:** Set up a zap that triggers when a new account completes onboarding milestone → grades the account → notifies CS Slack channel for Grade A accounts with expansion playbook, Grade C accounts with intervention playbook.
- **Gainsight / Totango:** Map LTV Grade to health score thresholds. Grade A = health score ≥75, Grade B = 40–74, Grade C = <40. Automate playbook assignment by grade.

## Troubleshooting

**Problem: LTV:CAC ratio looks unrealistically high (e.g., 40:1) for a specific segment.**
Solution: Check whether you're using simple vs. expansion-adjusted LTV. If NRR > 100%, expansion-adjusted LTV grows indefinitely — always cap at a realistic time horizon (5–10 years). Also verify CAC includes all marketing + sales costs (salaries, tools, overhead), not just ad spend.

**Problem: Not enough cohort data to build reliable LTV curves (company is <18 months old).**
Solution: Use industry benchmarks as a proxy: SaaS companies at your price point typically see 85–90% first-year retention for mid-market, 70–80% for SMB. Run the analysis with conservative (low) and optimistic (high) assumptions and present a range. Update the model quarterly as real cohort data accumulates.

**Problem: Different segments have the same CAC because costs aren't tracked by segment.**
Solution: Allocate CAC by segment using a time-based approach: estimate what % of your sales team's time is spent on each segment, then multiply total sales+marketing cost by that %. Alternatively, use deal count × average sales cycle length per segment to weight the allocation. Even a rough estimate is better than blended CAC.

## Version History
- v1.0: Initial creation (auto-generated)
