# AI-Powered B2B Marketing Qualified Account (MQA) Scoring & Pipeline Handoff Intelligence Engine

**Difficulty:** Advanced | **Time:** 25-35 min | **Tags:** mqa, account-scoring, b2b, pipeline, demand-gen, ABM, revenue-operations, buying-committee, lead-to-account, automation

## Overview

Designs and operates a full account-level Marketing Qualified Account (MQA) scoring system — aggregating buying signals across all contacts, channels, and behaviors within a target account to determine when an entire buying committee is ready for a sales conversation. Use this when your team has outgrown traditional MQL-based handoffs and needs AI-driven account-level intelligence to prioritize pipeline, reduce sales cycle friction, and hit higher conversion rates from marketing to closed-won.

---

## Quick Copy-Paste Version

You are an AI-powered B2B revenue intelligence agent specializing in account-level buying signal aggregation and Marketing Qualified Account (MQA) scoring.

**My Company:** [Your company name and URL]
**Product/Solution:** [What you sell — e.g., cloud data platform for mid-market financial services firms]
**ICP Definition:** [e.g., CFO or VP Finance at 200-2,000 employee companies in FinTech or Insurance, using Snowflake, $20M-$500M ARR]
**Current CRM:** [e.g., Salesforce + HubSpot / Marketo]
**Sales Motion:** [e.g., mid-market direct / enterprise field / PLG + sales assist]
**Average Deal Size & Sales Cycle:** [e.g., $45K ACV, 60-90 day cycle]

Design a complete MQA scoring system and produce the following outputs:

**1. MQA SCORING MODEL**
Build a weighted scoring matrix that aggregates signals across these dimensions:
- Firmographic fit score (0-25 pts): Company size, industry vertical, tech stack match, funding stage, growth signals
- Intent signal score (0-25 pts): 3rd-party intent (Bombora, 6sense), G2 category research, competitor comparison pages viewed, pricing page visits
- Engagement depth score (0-25 pts): Multi-contact engagement across the buying committee (not just one lead), content consumption by persona, event attendance, demo requests
- Buying stage velocity score (0-25 pts): Speed of engagement acceleration, recency of signals, SDR outbound response, email reply rate

**2. MQA THRESHOLD DEFINITION**
Define the minimum score and signal combination required to declare an account MQA. Include:
- Hard floor (minimum firmographic fit before any signal score counts)
- Soft threshold (score at which SDR is alerted to begin engagement)
- Hot threshold (score at which AE is assigned and pipeline record created)
- Blacklist conditions (score reset triggers: competitor customer, legal hold, existing customer)

**3. BUYING COMMITTEE MAP**
For an account that crosses MQA threshold, generate the buying committee identification protocol:
- Champion (day-to-day user/advocate): How to identify, what content they consumed, suggested first outreach
- Economic Buyer (budget authority): How to identify, engagement gaps, executive outreach strategy
- Technical Evaluator: How to identify, security/compliance content needed
- Blocker/Gatekeeper: Risk signals, mitigation plays

**4. PIPELINE HANDOFF PLAYBOOK**
Generate the exact marketing-to-sales handoff protocol:
- MQA alert format (what the SDR/AE receives in Slack/CRM)
- Account research summary template (pre-populated from signals)
- Recommended first outreach channel and personalization angle
- SLA: Time-to-first-touch requirement and consequence if missed
- Handoff quality gate checklist (what marketing confirms before passing)

**5. MQA DECAY & RECYCLING RULES**
Define when an MQA loses qualification:
- Score decay rate (points lost per day of no engagement)
- Recycle trigger (score threshold at which account returns to marketing nurture)
- Re-qualification conditions
- Suppression list management

Produce all outputs in structured, CRM-ready format that can be configured directly in Salesforce, HubSpot, or Marketo.

---

## Advanced Customizable Version

### Role & Context

You are a senior Revenue Operations architect and B2B demand generation strategist with 15+ years of experience designing lead-to-revenue systems for high-growth SaaS companies. You specialize in the transition from MQL-based (contact-level) to MQA-based (account-level) demand generation — the industry shift happening as buying committees grow larger, sales cycles lengthen, and marketing teams are held accountable for pipeline quality, not just lead volume.

You understand that:
- The average B2B enterprise deal now involves 6-10 stakeholders (Gartner)
- 77% of B2B buyers describe their last purchase as "very complex or difficult" (Gartner)
- MQL → opportunity conversion averages just 13% industry-wide; MQA-based programs achieve 22-35%
- Dark social and anonymous intent signals account for 60-70% of the actual research journey
- Sales teams reject 50-80% of MQLs because "not enough account context"

Your MQA framework is built on the principle that **marketing should pass accounts, not contacts** — and only after a buying committee has shown sufficient coordinated buying behavior to justify sales investment.

You apply the FIRE framework for MQA prioritization:
- **F**it: How closely does the account match our ICP? (firmographic + technographic)
- **I**ntent: What signals indicate active research or purchase readiness?
- **R**elationship: How engaged are multiple stakeholders within the account?
- **E**xcitement: What is the velocity and acceleration of engagement?

### Input Parameters

COMPANY CONTEXT:
- Company name + URL: [your-company.com]
- Product category: [e.g., Revenue Intelligence / Security Operations / HR Automation]
- Core value proposition: [one sentence]
- Primary buyer persona: [e.g., VP of Engineering at Series B-D SaaS companies]
- Secondary buyer personas: [e.g., CTO (economic buyer), Lead DevOps Engineer (technical evaluator)]
- ACV / deal size: [e.g., $28K-$120K ARR]
- Sales cycle length: [e.g., 45-90 days mid-market / 6-12 months enterprise]
- Win rate from demo to close: [e.g., 28%]
- Current MQL volume and quality: [e.g., 350 MQLs/month, 15% convert to opportunity]
- CRM + MAP stack: [e.g., Salesforce + Marketo + 6sense + Bombora]

ICP DEFINITION:
- Company size range: [employees + ARR]
- Industries/verticals: [specific, not generic]
- Geographic focus: [e.g., North America + UK]
- Growth stage: [e.g., Series B through pre-IPO]
- Tech stack requirements: [must-have tools that indicate fit]
- Exclusion criteria: [company types, sizes, or conditions to exclude]

SIGNAL DATA SOURCES AVAILABLE:
- CRM behavioral data: [yes/no + what's tracked]
- MAP engagement data: [email opens, clicks, form fills — yes/no]
- Website visitor intelligence: [e.g., 6sense, Clearbit Reveal, Warmly — yes/no]
- 3rd-party intent data: [e.g., Bombora, G2 Buyer Intent, TechTarget — yes/no]
- Product usage data (if PLG): [yes/no + what signals are surfaced]
- Event/webinar attendance: [yes/no]
- SDR outbound engagement: [reply rates, call connects — yes/no]
- Content downloads + gated asset consumption: [yes/no]

CURRENT STATE:
- Current MQL definition: [how you define MQL today]
- Current marketing-to-sales SLA: [e.g., SDR follows up within 4 business hours]
- Primary sales complaint about MQL quality: [e.g., "leads aren't ready," "only one person engaged," "no context"]
- Marketing team structure: [e.g., demand gen team of 4, MOPs resource shared]

### Deliverables

#### MODULE 1: MQA SCORING MODEL ARCHITECTURE

**A. Firmographic Fit Scoring (Max 25 Points)**

Design a tiered fit scoring system:

| Dimension | Signal | Points |
|-----------|--------|--------|
| Company size | Exact ICP range | 8 |
| Company size | Adjacent range (±20%) | 4 |
| Industry vertical | Primary ICP industry | 7 |
| Industry vertical | Secondary ICP industry | 3 |
| Tech stack match | 2+ ICP tech stack signals | 6 |
| Tech stack match | 1 ICP tech stack signal | 3 |
| Growth stage | Funding/growth signal in ICP range | 4 |

Customize point values based on your ICP weighting. Define a minimum firmographic floor (e.g., 12/25 minimum before intent signals are counted).

**B. Intent Signal Scoring (Max 25 Points)**

| Signal Type | Source | Points |
|-------------|--------|--------|
| 3rd-party intent surge | Bombora/6sense: Category surge score 70+ | 10 |
| G2 category research | G2 Buyer Intent: competitor comparison viewed | 8 |
| Pricing page visit | Website (any stakeholder) | 7 |
| Demo request (any stakeholder) | Form fill or chatbot | 10 (immediate MQA trigger) |
| ROI calculator used | Gated or ungated | 6 |
| Competitor alternative research | Intent platform | 7 |
| Job posting for role that buys your category | LinkedIn/Indeed signal | 5 |

**C. Engagement Depth Scoring (Max 25 Points)**

The key differentiator from MQL: multiple contacts within the account must be engaged.

| Signal | Points |
|--------|--------|
| 2+ unique contacts engaged (any channel) | 8 |
| 3+ unique contacts engaged | 12 |
| 4+ unique contacts engaged (buying committee coverage) | 16 |
| Economic buyer (VP+) engaged | +5 bonus |
| Content consumed matching buying stage (middle/bottom funnel) | 4 |
| Webinar/event attendance (any stakeholder) | 3 |
| SDR outbound replied by any stakeholder | 5 |

**D. Velocity & Recency Scoring (Max 25 Points)**

| Signal | Points |
|--------|--------|
| 3+ signals in the last 7 days | 10 |
| 5+ signals in the last 14 days | 8 |
| Score increased 15+ points in 30 days | 7 |
| Engagement from a previously cold contact | 5 |

**E. Negative Scoring / Suppression Rules**

| Condition | Impact |
|-----------|--------|
| Known competitor customer | Score → 0, suppress until contract end date |
| Existing active customer | Route to CS/expansion, suppress from demand gen |
| Recently lost deal (< 90 days) | -15 points, route to AE for re-engagement |
| Blacklisted domain (e.g., competitor, investor) | Exclude permanently |
| Single contact with high score but zero multi-contact signals | Flag as "pseudo-MQA" — requires SDR validation |

#### MODULE 2: MQA THRESHOLD DEFINITIONS & ALERT TIERS

Define three escalation tiers:

**TIER 1: WARM ACCOUNT (Score 45-64)**
- Action: Add to SDR outbound sequence
- Outreach type: LinkedIn + personalized email, no phone
- SLA: First touch within 48 hours
- Goal: Surface additional stakeholders and deepen engagement

**TIER 2: HOT ACCOUNT / MQA (Score 65-84)**
- Action: SDR-qualified, create opportunity in CRM, AE briefed
- Outreach type: Email + phone + LinkedIn
- SLA: First touch within 4 business hours
- Goal: Book discovery call, multi-stakeholder meeting preferred

**TIER 3: BURNING ACCOUNT (Score 85+)**
- Action: Immediate AE + SDR joint play, marketing executes targeted paid ads to account
- Outreach type: All channels simultaneously including executive outreach
- SLA: First touch within 1 hour during business hours
- Goal: Same-day meeting, compress discovery + demo

#### MODULE 3: BUYING COMMITTEE INTELLIGENCE PROTOCOL

For each MQA-qualified account, generate this intelligence package automatically:

**ACCOUNT INTELLIGENCE BRIEF (AE/SDR-ready)**
ACCOUNT: [Company Name] | MQA Score: [XX/100] | Tier: [HOT/BURNING]
SCORE BREAKDOWN: Fit: XX | Intent: XX | Engagement: XX | Velocity: XX

BUYING COMMITTEE STATUS:
✅ Champion identified: [Name, Title] — [Last engagement: content downloaded, date]
⚠️ Economic Buyer gap: VP-level contact not yet engaged — recommended outreach: [executive email template]
✅ Technical contact: [Name, Title] — [Engaged with: security whitepaper, integration docs]
❌ Procurement/Legal: Not identified — risk flag for enterprise deals

TOP 3 BUYING SIGNALS:
1. [Most significant signal — e.g., "Pricing page visited 3x by 2 different contacts in 5 days"]
2. [Second signal — e.g., "Bombora intent surge: 'Cloud Data Warehouse' category, score 82/100"]
3. [Third signal — e.g., "VP Engineering replied to SDR outbound, requested more info"]

RECOMMENDED FIRST PLAY:
Channel: [Email / LinkedIn / Phone / Executive outreach]
Personalization hook: [Specific signal to reference]
Talk track: [2-sentence recommendation]

CONTENT TO REFERENCE IN OUTREACH:
- [Case study most relevant to their industry/size]
- [ROI calculator pre-seeded with their company profile]
- [Competitor comparison page if competitive signals detected]

#### MODULE 4: MARKETING-TO-SALES HANDOFF PLAYBOOK

**Handoff Quality Gate Checklist (Marketing must confirm before MQA alert fires):**
- [ ] Firmographic data complete and verified (company size, industry, HQ)
- [ ] Account owner assigned in CRM (no orphan accounts)
- [ ] At minimum 2 unique contacts identified and loaded into CRM
- [ ] Lead source and attribution chain captured
- [ ] Score breakdown documented (not just total score)
- [ ] Recommended talk track and personalization hook populated
- [ ] Relevant content assets linked in the account record
- [ ] No existing open opportunity, active customer, or suppression flag

**Slack/CRM Alert Template:**
🔥 BURNING MQA ALERT — [Company Name] | Score: 87/100

📊 Why now: Pricing page (3 visits, 2 contacts) + Bombora intent surge (score 84) + 
   SDR reply from Sarah Chen, VP Engineering

👥 Buying Committee:
• Champion: Sarah Chen, VP Eng (highly engaged)
• Gap: CFO not identified (deal risk — recommend LinkedIn InMail to [CFO Name])
• Technical: James Liu, Sr. DevOps (downloaded K8s integration guide yesterday)

⚡ SLA: First touch by [TIME] — 1-hour rule applies
🎯 Recommended play: Executive-led email from AE, reference Q4 infrastructure budget cycle + Bombora surge

📁 Account brief: [CRM link]
📣 Owner: [AE Name] | SDR: [SDR Name]

#### MODULE 5: MQA DECAY, RECYCLING & GOVERNANCE RULES

**Score Decay Model:**
- Tier 3 (Burning): -3 points/day after 7 days without new signal
- Tier 2 (Hot/MQA): -2 points/day after 14 days without new signal
- Tier 1 (Warm): -1 point/day after 21 days without new signal

**Recycle Conditions:**
- Account falls below Tier 1 threshold (< 45 points) → return to marketing nurture
- SDR marks "not ready" after outreach → -10 points, add to 30-day nurture sequence, reassess
- Account goes dark after meeting booked → flag for AE follow-up, marketing re-engage with targeted content

**Re-Qualification Trigger:**
- New intent surge detected (score increase of 15+ points)
- New executive hire in buying committee role
- Company funding event (Series X, IPO filing)
- Product trial started (if PLG)

---

## Example Input/Output

**Input Example:**
- Company: Axiom DataOps (fictional) — cloud data pipeline automation for mid-market SaaS
- ICP: VP Engineering or CTO at 150-1,500 employee SaaS companies, using Snowflake or Databricks, Series B+
- CRM stack: Salesforce + Marketo + 6sense + Bombora
- Deal size: $35K-$90K ACV, 60-day cycle

**Output Example (MQA Alert for Target Account: NovaStar Analytics):**

MQA SCORE: 79/100 | TIER: HOT | SLA: 4-hour first touch

SCORE BREAKDOWN:
• Firmographic Fit: 22/25 — 400-person SaaS company, FinTech vertical (ICP primary), Snowflake + dbt in stack
• Intent Signals: 21/25 — Bombora surge: "Data Pipeline Automation" (score 76), competitor 
  Fivetran comparison page viewed 2x
• Engagement Depth: 22/25 — 3 unique contacts engaged: CTO (downloaded architecture guide), 
  Sr. Data Engineer (attended webinar), VP Eng (opened 4 emails)
• Velocity: 14/25 — Score increased 18 points in 12 days (accelerating)

BUYING COMMITTEE:
✅ Technical champion: David Park, Sr. Data Engineer — highly engaged
✅ CTO: Monica Reyes — lurking (content consumption, no form fill)
⚠️ VP Engineering: Opened emails only, not yet converted
❌ Economic buyer / CFO: Not identified — HIGH RISK for deal velocity

RECOMMENDED PLAY:
Send executive email from our Head of Sales to Monica Reyes (CTO) referencing:
"Q4 data infrastructure audit + Bombora category surge signal"

Subject: "Data pipeline investment timing for NovaStar"
Opening hook: "NovaStar's team has been exploring data pipeline automation — I wanted to reach out
directly given the timing of your Q4 planning cycle..."

---

## Success Metrics

**MQA Model Effectiveness:**
- MQL → MQA conversion rate increase: Target 40% reduction in total MQLs passed with 25%+ increase in opportunities created
- Marketing-sourced pipeline quality: MQA-sourced opportunities should close at 2x+ the rate of traditional MQL-sourced
- Sales acceptance rate: Target > 80% (vs. industry average of 30-50% for MQL programs)
- Time-to-first-touch SLA compliance: > 90% of Tier 2/3 MQAs touched within SLA window
- Score accuracy: Track correlation between MQA score at handoff and opportunity close rate — recalibrate scoring quarterly

**Pipeline Velocity:**
- Days from MQA alert to discovery call booked: Target < 5 business days
- Days from discovery to demo: Target < 7 days
- Multi-stakeholder meeting rate: > 60% of MQA-sourced meetings include 2+ buying committee members
- MQA-to-close win rate: Target 22-35% (vs. 13% MQL industry benchmark)

**Operational Health:**
- Score model recalibration frequency: Quarterly (compare predicted vs. actual close rates)
- SDR feedback loop completion: 100% of MQAs get disposition logged within 72 hours
- False positive rate (MQA passed but rejected by sales): Target < 20%

---

## Related Prompts

- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md)
- [`../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Lead-Scoring-Model-Optimization-&-Predictive-Buying-Signal-Intelligence-Engine.md)
- [`../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md`](../../05_Analytics-&-Performance/Lead-Quality-&-Conversion-Analytics/Marketing-Lead-Quality-&-Sales-Handoff-Intelligence-Engine.md)
- [`../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Buying-Committee-Engagement-&-Multi-Stakeholder-Intelligence-Engine.md`](../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Buying-Committee-Engagement-&-Multi-Stakeholder-Intelligence-Engine.md)

---

## Integration Tips

**Salesforce:**
- Create a custom MQA Score field on the Account object (formula field pulling from Engagement Score + Intent Score + Fit Score sub-fields)
- Build a "MQA Alert" Process Builder / Flow that fires when score crosses thresholds
- Use Account Teams to auto-assign SDR + AE when Tier 2/3 threshold is crossed
- Custom report: "MQA Pipeline Dashboard" — track MQA volume, SLA compliance, and pipeline conversion weekly

**HubSpot:**
- Use HubSpot's Company Score property to replicate MQA scoring with custom weighted formula
- Workflows: Auto-create Deals when Company Score hits MQA threshold, assign to owner, send Slack notification via Zapier
- Association: Ensure all contacts are properly associated to Company records for multi-contact engagement aggregation

**6sense / Bombora Integration:**
- Push 6sense Account Score + Stage into Salesforce as custom fields; include in MQA formula
- Set Bombora composite intent score (combining category surge + topic engagement) as an auto-populated CRM field via native connector

**Marketo:**
- Use Account-Based Marketing features (available in Marketo Engage) to score at account level
- RTP (Web Personalization) can be configured to show different CTAs when an account reaches MQA status
- Smart Campaigns: auto-add Account contacts to "MQA Tier 1 Nurture" or "MQA Tier 2 SDR Sequence" based on score

**Slack:**
- Use Salesforce → Slack native integration or Zapier to fire MQA alerts to #mqa-alerts channel
- Include deep link to CRM account record, SDR/AE mention, and recommended first play in every alert

---

## Troubleshooting

**Problem: Sales team is still rejecting MQA-passed accounts at high rates (> 30%)**
Solution: Run a 90-day retrospective — pull all passed MQAs and compare score at handoff vs. close outcome. Identify which scoring dimensions have lowest predictive validity. Typically, firmographic fit is over-weighted and intent/engagement velocity are under-weighted. Recalibrate using a simple logistic regression on historical data, or use 6sense/Clari's built-in account scoring AI.

**Problem: MQA volume is too low — scoring threshold is filtering out too many accounts**
Solution: Check if firmographic "hard floor" is set too high. A common mistake is requiring 18/25 fit points before any intent score counts — this eliminates accounts where you don't have clean data. Temporarily lower the floor to 12/25 and audit the accounts that enter the warm tier to validate they're genuinely your ICP. Also ensure your intent data sources are firing — check Bombora/6sense connector health.

**Problem: Score decay is causing accounts to cycle out of MQA before sales can follow up**
Solution: Pause score decay for Tier 2/3 MQAs for the first 72 hours post-alert — decay should only begin if no SDR activity is logged. Audit SLA compliance. If SDRs are missing the 4-hour SLA, the decay model isn't the issue — it's the handoff process. Implement a secondary alert at 2 hours to the SDR manager if no CRM activity is logged.

---

## Version History
- v1.0: Initial creation (auto-generated)
