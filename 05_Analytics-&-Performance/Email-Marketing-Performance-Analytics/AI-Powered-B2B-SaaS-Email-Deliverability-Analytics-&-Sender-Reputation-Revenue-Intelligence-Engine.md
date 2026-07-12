# AI-Powered B2B SaaS Email Deliverability Analytics & Sender Reputation Revenue Intelligence Engine - Full-Funnel Inbox Placement Diagnostics, Spam Signal Detection & Revenue-Impact Measurement for Marketing Ops

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, email-deliverability, marketing-ops, analytics, sender-reputation, inbox-placement, email-marketing, revenue-intelligence, spam-filters, list-hygiene

## Overview
Transforms raw deliverability data from Google Postmaster Tools, Microsoft SNDS, Validity/250ok, Litmus, and your ESP into an actionable sender-reputation intelligence system that quantifies the direct revenue impact of deliverability degradation and prioritizes remediation by pipeline risk. Use it monthly for program health audits, immediately when open rates drop unexpectedly, and quarterly for board-level email infrastructure reporting.

## Quick Copy-Paste Version

You are a senior email deliverability analyst and marketing operations strategist with deep expertise in B2B SaaS email programs. Analyze my email deliverability data and produce a full sender reputation diagnostic with revenue impact modeling and a prioritized remediation plan.

My program context:
- ESP: [HubSpot / Marketo / Pardot / Klaviyo / Customer.io / Mailchimp / Other]
- Monthly email volume: [# emails/month across all sends]
- Sending domains: [e.g., hello@company.com, nurture@emails.company.com, sdrs@company.com]
- List size: [Total contacts] | Active (engaged last 90 days): [#] | Unengaged (no open/click 180+ days): [#]
- Average bounce rate (hard + soft): [%]
- Average spam complaint rate: [%]
- Average open rate (last 30 days): [%] vs. prior 30 days: [%]
- Click-to-open rate (CTOR): [%]
- Unsubscribe rate: [%]
- Google Postmaster Tools domain reputation: [High / Medium / Low / Bad]
- Microsoft SNDS IP status: [Green / Yellow / Red] (if known)
- Blocklist status: [Not listed / Listed on: specify which lists]

Revenue context:
- Monthly pipeline sourced from email: [$]
- Average email-influenced deal value: [$]
- What triggered this analysis: [Sudden open rate drop / Routine audit / Spam complaints spike / Blocklist hit / Pre-campaign health check]

Deliver:

1. DELIVERABILITY HEALTH SCORE — Score my program 0-100 across five dimensions: (a) bounce rate vs. industry benchmarks, (b) spam complaint rate vs. acceptable thresholds, (c) engagement rate trajectory, (d) domain/IP reputation signals, (e) list hygiene indicators. Flag each dimension as Green / Yellow / Red with the specific threshold being violated.

2. REVENUE IMPACT CALCULATION — Estimate the monthly pipeline at risk based on current deliverability performance: (a) calculate the estimated % of emails not reaching the inbox due to current reputation signals, (b) apply this to my monthly pipeline attribution to quantify revenue leakage in dollars, (c) project 90-day revenue impact if current trajectory continues without remediation.

3. ROOT CAUSE DIAGNOSIS — Identify the most likely root causes of any deliverability issues from the data provided. Rank causes by probability: engagement rate decay (list age/cold contacts), spam trap hits (list acquisition quality), content patterns (spam trigger words, image/text ratio), sending infrastructure (shared IP, DMARC/DKIM/SPF misconfiguration), sending behavior (volume spikes, frequency mismatches).

4. PRIORITIZED REMEDIATION PLAN — Provide a 30/60/90-day remediation roadmap with specific actions ordered by revenue protection impact: immediate actions (this week), short-term fixes (30 days), and structural reforms (90 days). Include which actions require ESP/IT support vs. which a marketer can implement alone.

5. MONITORING DASHBOARD SPEC — Define the 8 KPIs to monitor weekly, the anomaly thresholds that should trigger alerts, and the specific dashboard views to set up in [Google Postmaster Tools / ESP analytics / Validity].

Output as an executive-ready deliverability health report with a one-page summary, detailed diagnostic sections, and a copy-ready action plan table formatted for presentation to a VP Marketing or CMO.

## Advanced Customizable Version

ROLE: You are a Principal Email Deliverability Engineer and Marketing Operations Strategist with 12+ years of experience managing high-volume B2B SaaS email programs at companies sending 5M–50M+ emails/month. You have diagnosed and remediated deliverability crises at companies including [Salesforce, HubSpot, Gong, Outreach]-scale programs. You combine deep technical knowledge of mailbox provider algorithms (Google, Microsoft, Yahoo, Apple), list hygiene methodology, spam filter pattern recognition, and revenue attribution modeling to convert deliverability data into strategic business decisions — not just technical fixes.

CONTEXT:
Company: [Company name]
Industry: [B2B SaaS / B2B Services / etc.]
Revenue stage: [Series A / B / C / Public / etc.]
Primary ESP: [HubSpot / Marketo / Pardot / Salesforce Marketing Cloud / Klaviyo / Customer.io / ActiveCampaign / Other]
Secondary sending tools: [Outreach / Salesloft / Reply.io / Apollo / None] (for SDR sequences)
Sending infrastructure: [Dedicated IP(s) / Shared IP pool / Warm dedicated IPs (< 6 months)]
Monthly email volume by category:
  - Marketing nurture emails: [#/month]
  - SDR/sales sequences: [#/month]
  - Transactional (product notifications, onboarding): [#/month]
  - Event/webinar invitations: [#/month]
Sending domains:
  - Primary marketing domain: [e.g., marketing@company.com]
  - Subdomain for sequences: [e.g., outreach@sequences.company.com]
  - Corporate/transactional: [e.g., noreply@company.com]
Authentication status:
  - DMARC policy: [None / p=none / p=quarantine / p=reject] | Alignment: [Relaxed / Strict]
  - DKIM: [Configured / Partial / Missing] | Key length: [1024 / 2048]
  - SPF: [Pass / SoftFail / Fail / Missing] | Includes count: [#] (flag if > 10)
  - BIMI: [Deployed / Not deployed]

CURRENT PROGRAM METRICS (Last 30 days):
Total sends: [#]
Delivered: [#] | Delivery rate: [%]
Hard bounces: [#] | Rate: [%] | Primary reason: [Unknown user / Domain not found / Other]
Soft bounces: [#] | Rate: [%] | Primary reason: [Mailbox full / Reputation block / Rate limit]
Spam complaints: [#] | Rate: [%] (FBL-reported from providers that share this data)
Opens (machine-open-excluded if possible): [#] | Rate: [%]
Clicks: [#] | CTOR: [%]
Unsubscribes: [#] | Rate: [%]
Suppression list size: [#] | % of total database: [%]

REPUTATION SIGNALS:
Google Postmaster Tools:
  - Domain reputation: [High / Medium / Low / Bad]
  - IP reputation: [High / Medium / Low / Bad]
  - Spam rate trend: [Stable / Increasing / Decreasing]
  - Authentication (DKIM/DMARC) pass rate: [%]
Microsoft SNDS / JMRP:
  - IP status: [Green / Yellow / Red] (if available)
  - Complaint rate: [%] (if enrolled in JMRP)
Blocklist status (check MXToolbox):
  - Blocklisted: [Yes / No] | If yes, which lists: [Spamhaus / Barracuda / SpamCop / SURBL / Other]
  - Blocklist history last 12 months: [# incidents]
Validity/250ok or Litmus Spam Testing:
  - Inbox placement rate (IPR) overall: [%]
  - IPR by provider: Gmail [%] | Outlook/Exchange [%] | Yahoo [%] | Apple Mail [%]
  - Spam folder placement: [%] | Missing: [%]
  - Spam filter triggers identified: [List main issues if available]

LIST COMPOSITION & HYGIENE:
Total contactable database: [#]
Engaged (open OR click last 90 days): [#] | [%]
Semi-engaged (open OR click 91-180 days): [#] | [%]
Unengaged (no activity 181-365 days): [#] | [%]
Cold/dormant (no activity 365+ days): [#] | [%]
List sources: [Organic website / Purchased / Trade show / Partner / Content syndication / Trial signups] (list % from each)
Most recent list validation run: [Date] | Tool used: [ZeroBounce / NeverBounce / Kickbox / Emailable / None]
Known spam trap exposure: [Yes (how many) / No / Unknown]
Average list age: [months/years — when was majority of list acquired]

REVENUE & BUSINESS CONTEXT:
Monthly revenue attributed to email marketing: [$] | Attribution model: [First touch / Last touch / Multi-touch]
Monthly pipeline sourced from email: [$]
Typical email-touched deal: [$] | Average sales cycle: [days]
Email sends that most directly impact pipeline: [Specify top 2-3 campaign types, e.g., "webinar invites" or "MQL nurture sequence"]
Current business priority: [Pipeline growth / Expansion revenue / Customer retention / Brand awareness]
What triggered this analysis: [Unexpected open rate drop / Spam complaint spike / Blocklist notification / Pre-major-campaign audit / Routine quarterly health check / Investor/board request]

OBJECTIVE: Produce a comprehensive deliverability intelligence report that: (1) quantifies the revenue impact of current deliverability performance, (2) identifies the specific root causes of any degradation, (3) delivers a prioritized remediation plan with clearly owned action items, and (4) establishes an ongoing monitoring framework that catches future issues before they impact pipeline — all in a format ready for presentation to VP Marketing, CMO, and/or CTO.

---

DELIVERABLE 1 — SENDER REPUTATION HEALTH SCORECARD

Score the program across 7 dimensions (0–100 for each, weighted composite score):

Dimension 1: Bounce Rate Health [Weight: 20%]
- Hard bounce benchmark: B2B SaaS acceptable < 0.5%; warning 0.5–1%; critical > 1%
- Soft bounce benchmark: < 2% acceptable; > 5% requires investigation
- Score the data provided and identify primary bounce categories (invalid addresses, domain issues, blocks)
- Estimate % of bounces that are reputation-based blocks vs. invalid addresses (critical distinction)

Dimension 2: Spam Complaint Rate [Weight: 25%]
- Google FBL benchmark: < 0.08% green; 0.08–0.1% warning; > 0.1% critical (Google threshold)
- Yahoo FBL benchmark: < 0.3% acceptable
- Score complaint rate AND trend direction (rising complaint rate at 0.05% is worse than stable rate at 0.09%)
- Identify which send categories or segments are likely driving complaint spikes

Dimension 3: Engagement Rate Quality [Weight: 20%]
- B2B SaaS industry benchmarks: Open rate 20–28%; CTOR 10–15%
- Weight machine-open inflation: if Apple MPP or Gmail image prefetch inflates opens, apply correction factor
- Evaluate CTOR as the primary engagement signal (more reliable than open rate alone)
- Identify engagement decay rate: is performance improving, stable, or degrading month-over-month?

Dimension 4: Authentication & Infrastructure [Weight: 15%]
- DMARC p=reject with 100% alignment: maximum score
- DMARC p=quarantine or p=none: deduct points proportionally
- DKIM 2048-bit with proper rotation: maximum
- SPF with 10+ includes (SPF limit risk) or SoftFail: deduct
- BIMI deployment: bonus points (positive reputation signal to providers)
- Dedicated IP warm status: score based on volume vs. IP age alignment

Dimension 5: List Hygiene Index [Weight: 10%]
- % engaged contacts (90-day): > 40% = healthy; < 20% = critical
- Last validation run recency: < 90 days = excellent; 90–180 days = acceptable; > 180 days = risk
- List acquisition quality: organic/trial = highest score; purchased = significant deduction
- Suppression list maintenance: active suppression = positive signal

Dimension 6: Inbox Placement Rate [Weight: 5%]
- IPR > 90%: excellent; 85–90%: acceptable; 80–85%: concerning; < 80%: critical
- Weight by mailbox provider mix of your audience (if 60% of your buyers are on Outlook, prioritize Microsoft IPR)
- Spam vs. missing placement distinction: spam folder = reputation issue; missing = blocking issue

Dimension 7: Blocklist & Blocklist History [Weight: 5%]
- Active listing on Spamhaus SBL/XBL/CBL/DBL: critical (deduce heavily)
- Active listing on Barracuda, SpamCop: warning
- Clean history (12 months): maximum score; 1-2 incidents with fast resolution: partial score

COMPOSITE SCORE INTERPRETATION:
- 90-100: Excellent sender — optimize for revenue impact
- 75-89: Good sender — targeted improvements needed
- 60-74: At-risk sender — remediation required within 30 days
- 45-59: Degraded sender — urgent action required, campaigns at significant risk
- < 45: Crisis state — consider a full send pause and infrastructure rebuild

---

DELIVERABLE 2 — REVENUE IMPACT QUANTIFICATION

Calculate the current deliverability tax on pipeline using this framework:

Step 1: Inbox Reach Rate (IRR) Calculation
From inbox placement rate and bounce data, calculate IRR:
IRR = (Delivered Rate) × (Inbox Placement Rate) × (1 - Bounce Rate)
Express as: "Of every 100 emails sent, [X] reach the inbox"

Step 2: Revenue Leakage Estimate
Using the Monthly Pipeline from Email figure:
- Pipeline at Risk = Monthly Pipeline × (1 - IRR) × Nurture Influence Factor
  [Nurture Influence Factor = % of deals that required email nurture to advance — typically 60–80% in B2B]
- Express as: "Current deliverability issues are placing approximately $[X] in monthly pipeline at risk"

Step 3: Opportunity Cost of Disengaged Segments
If sending to cold/dormant contacts (180+ days) is degrading reputation:
- Estimate the volume of sends to cold contacts as % of total
- Model the reputation impact (each % of disengaged sends above threshold = ~X% decrease in overall IPR)
- Calculate pipeline cost of this practice: "Continuing to send to [X% cold] contacts is costing an estimated $[Y]/month in deliverability degradation"

Step 4: 90-Day Revenue Trajectory Without Remediation
If current trends continue:
- Project IPR deterioration rate based on observed trajectory
- Model the compounding effect on open rates, click rates, and pipeline conversion
- Express as: "Without remediation, deliverability degradation could cost an estimated $[X] in Q[X] pipeline if current trajectory continues"

Step 5: Remediation ROI
For the top 3 remediation actions, estimate:
- Implementation effort (hours)
- Time to impact (days/weeks)
- Estimated revenue protection or recovery ($)
- ROI expressed as "$ recovered per hour invested"

---

DELIVERABLE 3 — ROOT CAUSE ANALYSIS

Diagnose the most likely causes ranked by probability using the data provided. For each cause:
- Probability score (High / Medium / Low)
- Evidence from the data that supports this diagnosis
- The technical mechanism by which it's harming deliverability
- Specific data point to confirm or rule out (what additional data to pull)

Root Cause Categories to Evaluate:

A. LIST COMPOSITION ISSUES
- Spam trap contamination (pristine vs. recycled trap indicators)
- High proportion of invalid/abandoned addresses (hard bounce patterns)
- Acquired lists or co-registration leads (complaint rate spikes by segment)
- Role-based addresses (info@, sales@) mixed into marketing sends

B. ENGAGEMENT DECAY
- Over-sending to unengaged contacts (sending frequency vs. engagement correlation)
- Relevance mismatch (high unsubscribe + low CTOR = wrong content for segment)
- Send time misalignment (open rate by time-of-day analysis recommendation)

C. CONTENT & CREATIVE SIGNALS
- Spam trigger phrase patterns in subject lines or body copy
- Image-to-text ratio imbalance (high image, low text = suspicious to filters)
- Spammy link patterns (too many links, URL shorteners, suspicious domains)
- Unsubscribe link accessibility (hidden or difficult to find)

D. SENDING INFRASTRUCTURE
- Shared IP contamination (if on shared pool, another sender's behavior affects your reputation)
- Dedicated IP under-warming (volume spikes exceeding warm IP capacity)
- Multiple sending domains with different reputation signals creating confusion
- SPF record exceeding 10 DNS lookup limit (common when using multiple tools)

E. DMARC/DKIM/SPF MISCONFIGURATION
- DMARC not at p=reject (allowing spoofing that creates complaint attribution)
- DKIM signing gaps (some messages not signed = variable authentication)
- Subdomain policies not inheriting parent domain controls

F. BEHAVIORAL PATTERNS
- Sending large campaigns without warming
- Day-of-month sending spikes (end-of-quarter blasts to exhausted lists)
- SDR sequences layered on top of marketing cadence (total contact overload)

G. FEEDBACK LOOP GAPS
- Not enrolled in Yahoo/Microsoft FBL programs (missing complaint data)
- Not suppressing FBL complaints within 24 hours
- Not monitoring Google Postmaster Tools daily

---

DELIVERABLE 4 — PRIORITIZED REMEDIATION ROADMAP

Structure as a phased action plan with explicit ownership and time investment:

IMMEDIATE (This Week — Protect Revenue Now):
For each action:
- Specific action step (precise, not vague)
- Owner: [Marketer / Email Ops / IT/DevOps / ESP Support]
- Time to implement: [hours]
- Revenue protection estimate: [$]
- How to measure success: [specific metric with threshold]

Priority 1: [e.g., Pause all sends to contacts with no activity 365+ days]
Priority 2: [e.g., Submit blocklist removal request to Spamhaus within 24 hours with remediation plan]
Priority 3: [e.g., Pull list from ZeroBounce/NeverBounce for immediate invalid removal]
Priority 4: [e.g., Enable FBL enrollment with Yahoo/Microsoft if not active]

SHORT-TERM (30 Days — Structural Repair):
For each action:
- Action with specific implementation spec (not generic advice)
- Dependencies and sequencing (what must be done first)
- Expected outcome and timeline to see improvement in reputation signals
- Risk of this action (e.g., "sunsetting 40% of list will reduce deliverable volume short-term")

Priority 1: [e.g., Re-permission campaign to warm semi-engaged contacts before suppressing]
Priority 2: [e.g., Implement DMARC p=reject with DKIM 2048-bit rotation]
Priority 3: [e.g., Segment sending domains: marketing vs. SDR sequences vs. transactional]
Priority 4: [e.g., Audit and consolidate SPF record to resolve 10-lookup limit]

STRUCTURAL (60-90 Days — Sustainable Excellence):
For each action:
- Architecture change or program design decision
- Business case for change (revenue impact, risk reduction)
- Stakeholders required to approve
- Success metric at 90 days

Priority 1: [e.g., Move to dedicated IPs with a 6-week warming schedule]
Priority 2: [e.g., Implement list validation at point-of-capture in HubSpot/Marketo forms]
Priority 3: [e.g., Build engagement-based sending segments (Tier A: 30-day active, Tier B: 31-90 day, Tier C: sunset)]
Priority 4: [e.g., Deploy BIMI with verified mark certificate for brand trust signal]

---

DELIVERABLE 5 — DELIVERABILITY MONITORING FRAMEWORK

Define the ongoing intelligence system to prevent future crises:

Weekly KPI Dashboard (8 metrics with thresholds):
1. Domain Reputation Score (Google Postmaster Tools) — check daily, report weekly
2. Spam Rate (Google Postmaster Tools) — threshold: alert if > 0.08%
3. Inbox Placement Rate by Provider (Validity/Litmus) — threshold: alert if IPR drops > 5pp
4. Bounce Rate by Campaign Type — threshold: alert if hard bounce > 0.5% on any send
5. CTOR Trend (30-day rolling) — threshold: alert if CTOR drops > 15% month-over-month
6. Unsubscribe Rate by Segment — threshold: alert if any segment > 0.5% on single send
7. New List Source Bounce Rate — threshold: alert if new source > 2% hard bounce on first send
8. Blocklist Status (MXToolbox daily scan) — immediate alert if any listing detected

Monthly Deliverability Business Review:
- Template for reporting to VP Marketing: [Provide specific slide structure]
  - Slide 1: Sender Reputation Scorecard (composite score trend)
  - Slide 2: Revenue Impact Summary (pipeline at risk, pipeline protected through remediation)
  - Slide 3: Top 3 Issues & Status (open/resolved/in-progress)
  - Slide 4: Month's Actions Taken & Results
  - Slide 5: Next 30-Day Priority Actions

Anomaly Detection Triggers (immediate escalation):
- Google domain reputation drops from High → Medium: email engineering review within 48 hours
- Spam complaint rate crosses 0.08%: pause all non-transactional sends pending investigation
- Active Spamhaus listing: send pause, blocklist removal request within 2 hours
- Hard bounce rate > 2% on any single campaign: investigate list source before next send
- IPR drops below 85%: Litmus seed test within 24 hours to identify provider-specific blocks

Tool Stack Recommendation:
- Deliverability Monitoring: Google Postmaster Tools (free) + Validity Everest or 250ok ($)
- Inbox Testing: Litmus or Email on Acid
- List Validation: ZeroBounce, NeverBounce, or Kickbox
- Blocklist Monitoring: MXToolbox (free tier sufficient for most)
- FBL Management: Yahoo FBL + Microsoft SNDS/JMRP (both free enrollment)
- DMARC Monitoring: Dmarcian, Valimail, or EasyDMARC ($)

Output the full report in three formats:
1. Executive Brief (1 page): Composite score, revenue impact summary, top 3 actions — for CMO/VP Marketing
2. Technical Diagnostic (3-5 pages): Full scorecard breakdown, root cause analysis, tool-specific implementation steps — for Email Ops/Marketing Ops Manager
3. Action Plan Table (single-page): Actions | Owner | Deadline | Revenue Protection $ | Status — for weekly tracking

## Example Input/Output

**Input Example:**

Company: Veloxa (B2B SaaS, cloud security compliance platform, Series C)
ESP: HubSpot Marketing Hub Enterprise
Monthly email volume: ~280,000 sends/month (marketing) + ~95,000 SDR sequences via Outreach
Sending domains: marketing@veloxa.com, growth@communications.veloxa.com, outreach@sequences.veloxa.com
List size: 88,000 total contacts | Active 90-day: 14,200 (16%) | Unengaged 180+ days: 52,000 (59%)
Hard bounce rate: 1.8% | Soft bounce rate: 4.2%
Spam complaint rate: 0.12% (last 30 days)
Open rate (last 30): 16.1% vs. prior 30: 21.4% (a 25% drop in 45 days)
CTOR: 8.3%
Unsubscribe rate: 0.38%
Google Postmaster: Domain reputation: Low (was High 8 weeks ago)
Microsoft SNDS: Yellow
Blocklist: Active listing on Barracuda Reputation Block List (BRBL)
DMARC: p=none | DKIM: Configured | SPF: SoftFail on some SDR sends
Inbox Placement Rate (Validity): 73% overall (Gmail: 68%, Outlook: 79%, Yahoo: 71%)
Monthly pipeline sourced from email: $1.2M
What triggered this: "We hit a Barracuda blocklist and our campaign to 12,000 CISO prospects for our RSA Conference follow-up had a 40% lower open rate than expected. Quarter close in 6 weeks."

---

**Output Example (Condensed):**

**Veloxa Email Deliverability Intelligence Report — July 2026**

**EXECUTIVE BRIEF:**
Composite Sender Reputation Score: **42/100 — CRISIS STATE**
Estimated Pipeline at Risk (Monthly): **$394,000**
Immediate Revenue Protection Available (30-day remediation): **$280,000+**
Most Urgent Action: Barracuda blocklist removal + SDR sequence domain separation

**SCORECARD:**
- Bounce Rate: 18/100 🔴 Hard bounce 1.8% (3.6× above safe threshold; indicates 15,000+ invalid addresses in active database)
- Spam Complaint Rate: 12/100 🔴 0.12% (50% above Google's critical threshold of 0.08%; has triggered Low domain reputation)
- Engagement Quality: 38/100 🔴 CTOR 8.3% acceptable but open rate crash from 21.4%→16.1% signals active filtering/blocking; only 16% of list engaged in 90 days
- Authentication: 41/100 🟡 DKIM configured but DMARC at p=none offers zero protection; SPF SoftFail on SDR sends creating authentication gaps
- List Hygiene: 22/100 🔴 59% of list (52,000 contacts) unengaged 180+ days; estimated 12–18 spam traps in database based on bounce pattern
- Inbox Placement Rate: 30/100 🔴 73% IPR = 27% of emails missing inbox entirely; Gmail 68% IPR is consistent with "Low" domain reputation penalty
- Blocklist Status: 15/100 🔴 Active Barracuda BRBL listing detected; no Spamhaus listing (positive)

**REVENUE IMPACT:**
- Inbox Reach Rate: 100% × 73% IPR × (100% - 6% bounce rate) = 68.6% of sends reaching inbox
- Monthly pipeline leakage: $1.2M × (1 - 68.6%) × 70% nurture factor = **$264,000/month currently leaking**
- SDR sequence impact: Estimated 95,000 SDR sends/month with 73% IPR = ~25,600 sequences missing inbox/month; at 0.8% reply rate and $18,000 average deal, = **~$130,000/month in pipeline at risk from SDR email**
- 90-Day Trajectory Without Remediation: If Google domain reputation drops from Low → Bad (likely within 60 days at current trajectory), Gmail IPR will drop to 30–40%, placing an estimated **$720,000 in Q3 pipeline at risk**

**TOP 5 ROOT CAUSES (Ranked by Probability):**
1. 🔴 HIGH: 59% of sends going to disengaged contacts — primary driver of complaint rate; ISPs weight engagement signals heavily; every send to cold contacts further degrades reputation
2. 🔴 HIGH: DMARC at p=none — allows spoofed domains to generate complaints attributed to Veloxa; need p=reject immediately
3. 🟡 MEDIUM: SDR sequences on same IP pool as marketing — Outreach's aggressive sending cadence (3+ touches/week) is contaminating marketing domain reputation; separate immediately
4. 🟡 MEDIUM: No list re-validation in 18+ months — hard bounce rate of 1.8% suggests 15,000+ invalid addresses including potential spam traps
5. 🟡 MEDIUM: Barracuda listing originated from high-volume event campaign (RSA follow-up) to cold/purchased list; aggressive send volume to low-quality segment triggered listing

**30-DAY PRIORITIZED REMEDIATION:**

| Action | Owner | Days | Revenue Protection | Difficulty |
|---|---|---|---|---|
| 1. Submit Barracuda blocklist removal (include remediation evidence) | Email Ops | Today | $130k | Low |
| 2. Immediately suppress all contacts: no activity 365+ days from marketing sends | Marketing Ops | 2 days | $85k | Low |
| 3. Upgrade DMARC to p=quarantine then p=reject within 7 days | IT/DevOps | 3 days | $40k | Medium |
| 4. Separate Outreach sequences to sequences.veloxa.com (isolated domain) | Sales Ops + IT | 5 days | $90k | Medium |
| 5. Run full database through ZeroBounce; suppress invalid/spam trap high-risk | Email Ops | 7 days | $55k | Low |
| 6. Launch re-permission campaign for 90-180 day semi-engaged (18,000 contacts) | Marketing | 14 days | $45k | Medium |
| 7. Fix SPF SoftFail for SDR domain; ensure DKIM signing on all domains | IT | 7 days | $30k | Medium |

**6-Week RSA Follow-Up Recovery Plan:**
Given 6 weeks until quarter close, sequence the remediation to protect the CISO campaign:
- Week 1: Blocklist removal + suppression of 52,000 cold contacts
- Week 2: Database validation + DMARC upgrade
- Week 3: Re-send RSA follow-up ONLY to 14,200 engaged contacts (clean send to re-establish positive reputation signals)
- Week 4: Monitor Google Postmaster for domain reputation improvement (typically 4-6 weeks to recover from Low → Medium)
- Weeks 5-6: Expand to semi-engaged (re-permissioned) contacts with high-value CISO content

---

## Success Metrics

**Program Health KPIs (Track Monthly):**
- Composite Sender Score: Target 75+ within 90 days of remediation; 85+ within 6 months
- Domain Reputation (Google Postmaster): Recovery to "Medium" within 30 days of remediation; "High" within 90 days
- Spam Complaint Rate: Below 0.08% (Google threshold); below 0.05% target
- Hard Bounce Rate: Below 0.5% on all sends; flag any campaign exceeding 1%
- Inbox Placement Rate: Above 90% across all major providers within 60 days

**Revenue KPIs (Track Quarterly):**
- Pipeline Protected: Reduction in estimated monthly pipeline leakage as IPR improves
- Email-Sourced Pipeline per Deliverable Email: [Monthly pipeline ÷ Total inbox placements] — this is the true email revenue efficiency metric
- Campaign ROI Recovery: Target 25%+ improvement in email campaign pipeline contribution within 90 days

**Diagnostic Leading Indicators (Monitor Weekly):**
- CTOR trend: Should stabilize then improve as clean list receives relevant content
- Engagement Rate of Re-permissioned Segment: Should outperform cold database; validates list hygiene strategy
- Spam Trap Hits (if using seed network): Should decrease to zero within 60 days

## Related Prompts

- [Email Deliverability & List Health Optimization Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/Email-Deliverability-&-List-Health-Optimization-Engine.md) — strategy and campaign playbook for improving deliverability
- [AI-Powered B2B Email Revenue Attribution & Nurture Program Pipeline Contribution Intelligence Engine](../../05_Analytics-&-Performance/Email-Marketing-Performance-Analytics/AI-Powered-B2B-Email-Revenue-Attribution-&-Nurture-Program-Pipeline-Contribution-Intelligence-Engine.md) — attributing email program performance to revenue
- [AI-Powered B2B SaaS Email Program Competitive Benchmarking & Sender Intelligence Engine](../../05_Analytics-&-Performance/Email-Marketing-Performance-Analytics/AI-Powered-B2B-SaaS-Email-Program-Competitive-Benchmarking-&-Sender-Intelligence-Engine.md) — benchmark your program against competitors
- [AI-Powered B2B Cold Outbound Email Personalization & Prospecting Scale Intelligence Engine](../../04_Demand-&-Lead-Generation-&-Growth/Email-Marketing-&-Nurturing/AI-Powered-B2B-Cold-Outbound-Email-Personalization-&-Prospecting-Scale-Intelligence-Engine.md) — optimize outbound sequences that often create deliverability risk

## Integration Tips

**Google Postmaster Tools:**
- Enable domain authentication monitoring; export daily spam rate and reputation JSON via API for dashboard integration
- Connect to Looker Studio or Google Sheets for automated weekly reporting
- Set up email alerts when domain reputation drops below "High" — do not wait for weekly check

**HubSpot / Marketo / Pardot:**
- Build email health dashboard pulling: bounce rate by list source, CTOR by segment, unsubscribe rate by send frequency
- Create suppression list workflow: auto-suppress contacts with hard bounce OR 2+ soft bounces in 30 days
- Tag contacts by engagement tier (30-day active / 31-90 / 91-180 / 180+) using last-activity date field; use these tiers as send gates

**Validity Everest / 250ok:**
- Set up seed network tests for major campaign types (not every send, but all campaigns > 5,000 records)
- Configure automated alerts to Slack/Teams when IPR drops 5+ percentage points
- Use Validity's data to benchmark against industry peers in your vertical

**ZeroBounce / NeverBounce / Kickbox:**
- Integrate validation API at HubSpot/Marketo form level to validate at point-of-capture
- Schedule quarterly bulk validation of entire contactable database
- Flag "risky" category contacts (role-based, catch-all, disposable) for separate low-frequency engagement track

**Outreach / Salesloft (SDR Tools):**
- Configure dedicated sending domain for sequences (e.g., sequences.company.com) — never share IPs or domains with marketing automation
- Set daily sending limits per rep (100–150 emails/day max on new domain; increase after 90-day warm period)
- Route sequence bounces back to CRM and sync bounce data with marketing suppression list

**Dmarcian / Valimail:**
- Monitor DMARC aggregate reports daily during p=quarantine implementation; reject only after 100% DKIM/SPF alignment
- Alert on forensic reports that reveal spoofing/phishing attempts using your domain

**Salesforce CRM:**
- Create Email Deliverability Health Score field on Contact object; update via API daily from ESP bounce/complaint data
- Build Salesforce report: "Contacts Bounced/Complained Last 30 Days" → auto-exclude from SDR sequences and marketing sends
- Track pipeline by contact engagement tier to prove ROI of list hygiene investments

## Troubleshooting

**Problem: Google domain reputation dropped from High → Medium, but metrics look fine.**
Solution: Google's reputation signals are forward-looking; the drop often precedes visible open rate declines by 2-4 weeks. Run a Validity/Litmus inbox test immediately to measure true IPR — it's likely lower than your ESP reports. Check Google Postmaster's spam rate chart for any spike in the prior 14 days. If complaint rate is clean, the issue is likely aggregate engagement signals across your entire domain (not just Gmail sends) — suppress your cold segment for 30 days even before your open rates signal an issue.

**Problem: Spam complaint rate is 0.06% which seems low, but bounces are spiking.**
Solution: Complaint rate and bounce rate often signal different root causes. High bounces without high complaints typically indicate list quality issues (purchased/co-reg lists, old data) rather than content or frequency problems. Segment your bounce data by acquisition source — the source generating hard bounces > 2% needs to be suppressed or re-validated before another send. Note: you're only seeing complaints from Google FBL; Yahoo/AOL complaints are invisible unless you're enrolled in their FBL programs. Your true complaint rate may be 2-3× what you can see.

**Problem: We removed cold contacts and our pipeline from email dropped — how do we know remediation is working?**
Solution: Track pipeline-per-deliverable-email (monthly email pipeline ÷ total inbox placements) instead of absolute pipeline. Short-term pipeline will drop as send volume decreases, but pipeline per delivered email should increase — you're converting better on a cleaner, more engaged audience. Give the reputation recovery 45–60 days before evaluating full pipeline impact. Also run a re-permission campaign to recover engaged contacts who happened to not have interacted in 90+ days — some will re-engage and provide net-new pipeline from previously dormant contacts.

## Version History
- v1.0: Initial creation (auto-generated)
