# Intent-Driven Account Prioritization Engine - AI-Powered Buying Signal Intelligence

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** intent-data, account-prioritization, outbound, abm, b2b, buying-signals, prospecting, revenue-operations

## Overview
Transforms raw intent signals — web research behavior, G2/review site activity, technology stack changes, job postings, news triggers, and LinkedIn engagement — into a ranked, action-ready account list with personalized outreach angles and timing recommendations per account. Use it when you need to stop spraying cold outreach and start hitting accounts at the exact moment they are in-market.

## Quick Copy-Paste Version

You are a B2B revenue intelligence analyst. I will give you a list of accounts and their recent intent signals. Your job is to score, rank, and generate outreach briefs for each account.

My company: [Company Name] — we help [ICP description, e.g., "mid-market SaaS companies with 100-500 employees"] achieve [specific outcome, e.g., "30% faster sales cycles"] by [your solution, e.g., "replacing manual CRM updates with AI-driven pipeline tracking"].

Accounts and signals:
[Paste account data in this format:]
- Account: [Company Name] | Signals: [list signals, e.g., "visited pricing page 3x this week, posted 2 RevOps job listings, using competitor X per LinkedIn, published CFO blog post on cost reduction"]
- Account: [Company Name] | Signals: [...]
(add as many accounts as needed)

For each account, deliver:
1. FIRE Score (0-100): Fit + Intent strength + Relationship warmth + Engagement recency — explain the breakdown
2. Tier classification: Tier 1 (act within 24hrs), Tier 2 (nurture this week), Tier 3 (monitor)
3. The single most compelling reason they are likely in-market RIGHT NOW
4. The specific pain point or trigger to lead with in outreach
5. Recommended first touch: channel (email/LinkedIn/phone/direct mail) + timing + opening line (under 2 sentences)
6. One insight that would make the SDR sound like they did 2 hours of research in the first message

Rank all accounts from highest to lowest priority. Tier 1 accounts must include a same-day outreach brief.

## Advanced Customizable Version

ROLE:
You are a Senior Revenue Intelligence Strategist with 15+ years of experience in demand generation and account-based selling at companies like 6sense, Bombora, Demandbase, and Gong. You specialize in converting raw intent data into prioritized, personalized pipeline — combining signal triangulation, temporal decay analysis, and buyer committee mapping to identify exactly which accounts to call today, this week, and next quarter.

CONTEXT:
Company: [Company Name]
Product/Service: [1-sentence description]
Target market: [e.g., "B2B SaaS companies, 50-500 employees, Series A-C, North America"]
Average deal size: [e.g., "$24,000 ACV"]
Sales cycle length: [e.g., "45-90 days"]
Primary ICP personas: [e.g., "VP Sales, RevOps Manager, CRO"]
Current tech stack (for fit scoring): [e.g., "Salesforce + Outreach + Gong customers = highest fit"]
Known competitors: [list 2-4 competitors]
Key differentiators vs. competitors: [list 2-3]
CRM in use: [HubSpot / Salesforce / Pipedrive / other]

INTENT DATA SOURCES AVAILABLE (check all that apply):
- First-party: website page visits (pricing, comparison, ROI calculator, case studies)
- First-party: product trial or freemium activity
- Third-party: Bombora surge data (topic clusters showing research spikes)
- Third-party: G2 or Capterra profile views or competitor comparison page views
- Technographic: BuiltWith / Clearbit / HG Insights (tech stack signals)
- Job postings: new hires in relevant roles (RevOps, Sales Ops, Marketing Ops, etc.)
- News triggers: funding rounds, acquisitions, executive changes, IPO filings
- LinkedIn: profile views of your team, content engagement, InMail opens
- Social: mentions of competitors, pain point keywords, industry hashtags
- Email: re-engagement of previously cold contacts (opens, clicks after 90+ day silence)

ACCOUNT LIST:
[Paste structured account data — one account per line with all available signals]

SCORING FRAMEWORK — FIRE MODEL:
Score each account 0-25 on each dimension (total max = 100):

F — FIT (0-25): How closely does this account match the ICP?
- Company size, industry, tech stack, revenue stage
- Penalize: wrong segment, missing tech dependencies, known budget constraints

I — INTENT (0-25): How strong are the buying signals?
- Weight signals by recency (last 7 days = full value; 8-30 days = 60%; 31-60 days = 25%; 60+ days = 10%)
- Weight signals by specificity (pricing page visit > blog post view; G2 competitor compare > generic category browse)
- Multiple signals from different sources = multiplicative bonus (signal triangulation)

R — RELATIONSHIP (0-25): What is the warmth of the existing relationship?
- Previous meeting, trial, demo, or open opportunity = high
- Known contact in the buying committee = medium
- Cold or no prior contact = low
- Past lost deal within 12 months = medium-high (re-engagement opportunity)

E — ENGAGEMENT (0-25): How recently and actively has this account engaged with your brand?
- Email opens or clicks in last 14 days = high
- Attended webinar, downloaded asset, or engaged with LinkedIn content = medium
- No engagement but shows intent signals = low (must rely on cold outreach)
- Previously engaged, now silent = medium (latent relationship)

TIER CLASSIFICATION:
- Tier 1 (FIRE score 70-100): In-market now. Assign to AE or SDR within 24 hours. Multi-channel blitz.
- Tier 2 (FIRE score 45-69): Showing early signals. Begin nurture sequence. Re-score in 14 days.
- Tier 3 (FIRE score 20-44): Fit exists but timing unclear. Monitor and automate light touches.
- Tier 4 (FIRE score 0-19): Poor fit or stale signals. Remove from active pipeline; add to suppression list.

OUTPUT FORMAT:

### PRIORITIZED ACCOUNT DASHBOARD

| Rank | Account | FIRE Score | Tier | Top Signal | Recommended Action |
|------|---------|-----------|------|------------|-------------------|
(fill in all accounts)

---

### TIER 1 OUTREACH BRIEFS (one per account)

**Account: [Name]**
- FIRE Breakdown: F=[X]/25 | I=[X]/25 | R=[X]/25 | E=[X]/25 | Total=[X]/100
- Why they are in-market NOW: [1-2 sentences of specific evidence]
- Buyer committee targets: [role 1], [role 2] (who to reach and in what order)
- Lead-with pain point: [the specific business problem surfaced by the signals]
- Recommended channel sequence: [e.g., "LinkedIn connection, then personalized email, then phone, then LinkedIn follow-up"]
- Timing: [e.g., "Email Day 1 today, LinkedIn Day 2, Phone Day 4"]
- Opening line for email: [Specific, non-generic opening that uses their situation without revealing the intent data source]
- Opening line for LinkedIn: [Connection request message or InMail opener]
- The insight that makes you sound like an insider: [one specific, researched observation about their business situation]
- Objection to anticipate: [most likely pushback + how to pre-handle it]

(repeat for all Tier 1 accounts)

---

### TIER 2 NURTURE PLAN
For each Tier 2 account: recommended nurture sequence type (educational drip, case study send, event invite, or re-engagement), cadence, and re-scoring trigger.

---

### SIGNAL GAPS AND DATA ENRICHMENT RECOMMENDATIONS
List any accounts where key data is missing and suggest specific enrichment actions (e.g., "Run Account X through Clearbit to confirm tech stack before scoring").

---

### PIPELINE FORECAST
Based on Tier 1 accounts: estimated meetings bookable this week, projected pipeline value if 30% convert to opportunity, and recommended daily outreach volume for the SDR team.

CONSTRAINTS:
- Never reference intent data explicitly in outreach copy — use the intelligence to inform the angle, not reveal the source
- Flag any accounts where signals may indicate a competitor is also actively targeting them
- If an account has a previous lost deal in CRM, note the loss reason and adjust the outreach angle accordingly
- Prioritize multi-threaded outreach across multiple contacts at Tier 1 accounts over single-contact sequences

## Example Input/Output

### Example Input

Company: Velocity Pipeline — AI-powered pipeline forecasting for B2B sales teams. Replaces spreadsheet-based forecasting in Salesforce with an AI layer that predicts close probability, flags deals at risk, and generates weekly forecast reports automatically.

ICP: VP Sales, CRO, and RevOps at B2B SaaS, 100-500 employees, Series B or C, using Salesforce.

Accounts and signals:
- Account: Meridian Cloud (HR Tech, 220 employees, Series C) | Signals: "Visited pricing page 4 times in 5 days, two VP Sales profile views on our LinkedIn team page, job posting for Senior RevOps Analyst published 6 days ago, Bombora surge on 'sales forecasting software' for 3 consecutive weeks"
- Account: Stackflow (DevTools SaaS, 85 employees, Series A) | Signals: "Downloaded our ROI calculator 2 weeks ago, one SDR email opened but not clicked, G2 category page view with no competitor comparison"
- Account: Proxima Health (HealthTech, 410 employees, Series B) | Signals: "New CRO hired 3 weeks ago per LinkedIn announcement, previously lost deal 14 months ago with loss reason 'status quo', no recent digital engagement"

### Example Output (abbreviated)

**PRIORITIZED ACCOUNT DASHBOARD**

| Rank | Account | FIRE Score | Tier | Top Signal | Recommended Action |
|------|---------|-----------|------|------------|-------------------|
| 1 | Meridian Cloud | 88/100 | Tier 1 | 4x pricing page + RevOps hire posting + 3-week Bombora surge | Multi-channel blitz today |
| 2 | Proxima Health | 64/100 | Tier 2 | New CRO hire + prior lost deal = re-engagement window | Personalized executive email this week |
| 3 | Stackflow | 41/100 | Tier 3 | ROI calculator download 14 days ago (signal decayed) | Add to educational nurture, re-score in 21 days |

---

**TIER 1 OUTREACH BRIEF — Meridian Cloud**
- FIRE Breakdown: F=22/25 | I=24/25 | R=12/25 | E=20/25 | Total=88/100
- Why they are in-market NOW: Meridian has been researching forecasting solutions consistently for 21+ days (sustained Bombora surge) while simultaneously building out a RevOps function via a new hire. Multiple high-intent page visits in a compressed window signal active vendor evaluation — someone internally is building a business case right now.
- Buyer committee targets: 1) VP Sales as primary champion, 2) the incoming Senior RevOps Analyst as evaluator and likely admin, 3) CFO or VP Finance as economic buyer for board-level approval
- Lead-with pain point: Their RevOps hire posting lists "Salesforce forecasting accuracy" as a core responsibility — they are trying to solve a systemic tooling problem with a single human hire. The conversation opener is why that approach fails without the right platform underneath it.
- Channel sequence: LinkedIn connection to VP Sales on Day 1, personalized email to VP Sales on Day 1 same day, email to existing Salesforce Admin contact in CRM on Day 2, phone call to VP Sales on Day 4, LinkedIn outreach to the new RevOps hire once they start on Day 7 to 14
- Opening email line: "You are about to hire someone to fix your forecast accuracy in Salesforce — before they start, it is worth 15 minutes to see why the RevOps hire alone rarely closes the gap."
- The insider insight: Meridian closed its Series C 4 months ago. Board pressure to demonstrate predictable ARR growth is almost certainly driving the forecasting initiative. Frame the conversation around investor-grade pipeline confidence, not just operational efficiency.
- Objection to anticipate: "We are handling this with the new RevOps hire." Pre-handle: position Velocity Pipeline as what makes the RevOps hire 3x more effective — not a replacement, a force multiplier.

---

**TIER 2 — Proxima Health**
A new CRO triggers a 90-day window where all incumbent vendors get re-evaluated. Send a "new chapter" executive email referencing the leadership transition and leading with what has changed in your product since the last evaluation. Do not reference why they passed previously. Set a LinkedIn alert on the CRO for any content about pipeline or forecasting challenges as a re-scoring trigger.

## Success Metrics

- **Signal-to-meeting rate**: Percentage of Tier 1 accounts that book a meeting within 14 days — target 15-25% for high-intent accounts versus the 2-5% cold outreach baseline
- **FIRE score accuracy**: Track whether Tier 1 accounts convert to opportunities at 3-5x the rate of Tier 3 accounts over 60-day cohorts to validate the scoring model
- **Time-to-first-touch**: Tier 1 accounts should receive first outreach within 24 hours of scoring — measure using CRM task completion timestamps
- **Personalization quality**: SDR-reported usefulness score for outreach briefs on a 1-5 scale — target 4.0 or above to confirm the briefs are saving meaningful research time
- **Pipeline influenced**: Aggregate deal value sourced from intent-prioritized accounts versus non-intent-sourced pipeline in the same period
- **Signal freshness**: Percentage of active accounts re-scored within the 14-day decay window to prevent stale prioritization from blocking genuinely hot accounts

## Related Prompts

- [Cold Email Sequence Builder](./Cold-Email-Sequence-Builder.md) — Turn prioritized accounts into complete multi-touch email cadences
- [Account-Based Marketing Automation](../Outbound-&-ABM/Account-Based-Marketing-Automation.md) — Scale personalized campaigns across your prioritized account list
- [Lead Scoring Automation](../Lead-Generation-Campaigns/Lead-Scoring-Automation.md) — Complement intent scoring with inbound behavioral lead scoring
- [SDR Automation](../Outbound-&-ABM/SDR-Automation.md) — Automate outreach execution for Tier 1 account blitzes

## Integration Tips

**6sense / Bombora / Demandbase**: Export weekly intent surge reports as CSV and paste the top 20-50 accounts into the Advanced Version. Set automated Slack or email alerts when accounts cross a defined surge threshold so the prompt runs on a daily cadence rather than weekly.

**Salesforce / HubSpot CRM**: After scoring, log the FIRE score as a custom field on the Account object. Create CRM views filtered by tier. Use workflow automation to auto-assign Tier 1 accounts to senior SDRs within 2 hours of each scoring run.

**LinkedIn Sales Navigator**: Use Account Alerts to track hiring signals, news triggers, and employee headcount changes. Feed these alerts into the intent signal input field on a weekly basis.

**Outreach.io / Salesloft**: Use the generated outreach briefs to customize the opening message of existing cadence sequences. Do not build a parallel sequence — modify the intro of the Tier 1 cadence with the personalized opening line generated here and let the remainder of the sequence run as normal.

**Clay**: Use Clay to enrich account data including job postings, tech stack, LinkedIn headcount growth, and recent funding news. Pipe enriched rows directly into the Advanced Version account list field for a fully automated weekly prioritization workflow.

**Zapier or Make**: Build an automation that triggers this prompt when a Bombora account crosses a defined surge score threshold, pulling account data from your CRM via API and posting the FIRE-scored output to a designated Slack channel for same-day SDR pickup.

**Google Sheets**: Maintain a live Intent Pipeline Dashboard in Sheets. Populate it from the dashboard table output, color-code rows by tier, and share with the SDR team for weekly standup reviews. Add a column for SDR notes on outreach results to close the feedback loop and improve future scoring calibration.

## Troubleshooting

**Problem: Too many accounts scoring as Tier 1, overwhelming SDR team capacity.**
Fix: Tighten the Fit criteria by raising the ICP bar — for example, require Salesforce CRM plus 150 or more employees instead of 100. Add a minimum Intent threshold requiring at least two independent signals from different sources before any account qualifies for Tier 1 regardless of total FIRE score. Cap Tier 1 at the number of accounts each SDR can genuinely work within 24 hours, typically 5 to 10 per rep, and promote overflow accounts to Tier 2.

**Problem: FIRE scores feel generic and outreach briefs are not differentiated enough between accounts.**
Fix: Add more specificity to the intent signal input. Instead of writing "visited pricing page," write "visited the pricing page 4 times on 3 separate days, most recent visit 2 days ago from a direct URL, session duration over 4 minutes." The more precise the signal description, the sharper the outreach angle. Also provide your actual competitive differentiators and known loss reasons so the model can tailor angles to real objections rather than defaulting to generic pain points.

**Problem: Prospects respond negatively, saying the outreach feels intrusive or surveillance-based.**
Fix: Review all generated opening lines for any phrasing that implies you monitored their behavior. The prompt instructs the model to use intent signals to inform message relevance without disclosing the source, but occasionally a draft will reference a signal too explicitly. Any opening line that could only have been written because of tracking data should be rewritten. The goal is to arrive with a highly relevant message at the right moment — not to signal that you have been watching.

## Version History
- v1.0: Initial creation (auto-generated)
