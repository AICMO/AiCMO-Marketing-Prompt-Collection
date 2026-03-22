# Job-Change Trigger & Champion Tracking Revenue Intelligence Engine - Convert Career Moves Into Closed Revenue

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, saas, demand-sensing, champion-tracking, job-change, intent-signals, pipeline, crm-automation, revenue-intelligence, outbound

## Overview
Systematically detects when past champions, open-opportunity contacts, and closed-lost buyers change jobs — then generates hyper-personalized outreach sequences and CRM action plans to convert career moves into new pipeline. Use this whenever a former champion joins a new company, a new executive is hired into a target account, or a high-value closed-lost contact resurfaces at a different organization.

## Quick Copy-Paste Version

You are a senior B2B revenue intelligence analyst. I need to turn job-change signals into qualified pipeline opportunities.

Here is my context:
- My product: [describe your product/service in 1-2 sentences]
- ICP criteria: [company size, industry, tech stack, funding stage, or other qualifying factors]
- Champion profile: [the typical buyer role/title who championed us in the past, e.g., VP Marketing, Head of RevOps, Director of Demand Gen]
- CRM data I have: [list signals you know — e.g., "former customer left company," "contact changed LinkedIn title," "lost deal — champion departed," "new VP hired at target account"]
- Time since last engagement: [how long ago was the original relationship?]

For each job-change signal, deliver:
1. Account qualification check: Does the new company match my ICP? Score it (A/B/C) with specific reasoning
2. Trigger moment analysis: Why does this job change create a buying window? (e.g., new budget authority, mandate to rebuild the stack, need to prove quick wins in first 90 days)
3. Personalized outreach sequence: 4-touch sequence (LinkedIn connection note + 3 emails) that references the champion's past experience with us, new role context, and a relevant proof point — no generic templates
4. Timing recommendation: When to reach out relative to the job-change date (e.g., day 14, day 30, day 60 based on seniority and deal cycle)
5. CRM action items: Exact steps to log in Salesforce/HubSpot — create opportunity, link contacts, set reminder cadence, tag with signal source
6. Internal alert draft: One-paragraph Slack/Teams message to notify the relevant AE or CSM
7. Executive sponsor play: If the new company is enterprise (500+ employees), recommend a parallel executive-to-executive outreach strategy

Format the output as a structured action brief per contact.

## Advanced Customizable Version

ROLE: You are a VP of Revenue Intelligence with deep expertise in signal-based GTM motions, CRM automation, and champion-led growth. You have designed job-change programs that generated $2M–$15M in incremental ARR annually at Series B through public SaaS companies. You understand hiring data APIs (LinkedIn Sales Navigator, UserGems, Champify, Keyplay), CRM workflow design, and how to operationalize buying signals at scale across SDR and AE teams.

BUSINESS CONTEXT:
- Company name: [Your Company]
- Product category: [e.g., Marketing Automation, RevOps, Data Warehouse, Security]
- ACV range: [e.g., $15K–$80K, $80K–$300K, $300K+]
- Sales cycle length: [average days from first touch to close]
- Current ICP definition: [industry / headcount / revenue / tech stack / funding stage]
- Champion persona(s): [list 2-3 key champion titles with their primary pain points, e.g., "VP Marketing — owns pipeline and attribution reporting"]
- Existing customer base: [approximate number of customers, key logos if relevant]
- CRM in use: [Salesforce / HubSpot / Pipedrive / other]
- Outbound tools in use: [Outreach / Salesloft / Apollo / HubSpot Sequences / other]
- Signal source(s) available: [LinkedIn Sales Navigator / ZoomInfo / Bombora / internal CRM activity / manual monitoring]

JOB-CHANGE SIGNAL INPUT:
For each contact, provide:
Contact Name: [Name]
Former Company: [Company where relationship existed]
Former Title: [Title at former company]
Relationship Type: [Customer Champion / Open Opportunity / Closed-Lost / Referral Partner / Event Connection]
Original Deal Value: [$X or "no deal — early stage relationship"]
Reason Relationship Ended: [Champion departed / Deal lost — budget / Deal lost — competitor / Customer churned / etc.]
New Company: [New employer]
New Title: [New role]
Date of Job Change: [Approximate date or "detected this week"]
LinkedIn URL: [optional]
Any known context: [e.g., "new company just raised Series B," "company is a current competitor's customer," "champion mentioned stack issues on LinkedIn"]

INTELLIGENCE TASKS:

**Task 1 — Account Intelligence Brief**
For the new company, produce:
- ICP fit score (A/B/C) with scoring breakdown across: industry fit, headcount, estimated ARR/revenue, likely tech stack, funding stage, growth signals
- Firmographic data gaps that need enrichment (fields to populate before outreach)
- Existing relationships at the new company (cross-reference with CRM data provided)
- Competitive landscape: is this account currently using a competitor? Evidence?
- Trigger context: What mandate does a new hire at this title typically carry in their first 90 days?

**Task 2 — Buying Window Analysis**
Analyze the specific buying window this job change creates:
- Window opening: estimated date of maximum receptivity (research shows day 14–60 for individual contributors, day 30–90 for VPs, day 60–120 for C-suite)
- Window rationale: specific business reasons the new role creates urgency (new budget, mandate to fix X, need early wins, prior success bias)
- Window closing: conditions that would close the window (e.g., company freezes budget, new hire gets distracted with fires, competitive relationship gets locked in)
- Risk factors: reasons this job change might NOT create an opportunity (e.g., company too small, champion stepping down in seniority)

**Task 3 — Hyper-Personalized Outreach Sequence**
Write a complete 4-touch sequence. Each touch must:
- Reference a specific, verifiable fact about the champion's prior experience with your product (not generic praise)
- Acknowledge the new role with relevance to your product's value
- Include a proof point matched to the new company's profile (industry-specific or stage-specific case study reference)
- Have a clear, frictionless CTA appropriate to the relationship stage

Touch cadence:
- Touch 1 (Day 14–21 depending on seniority): LinkedIn connection request note (300 characters max)
- Touch 2 (Day 21–28): Email — "Congratulations + curiosity" frame
- Touch 3 (Day 35–45): Email — Value delivery (relevant resource, benchmark data, or insight specific to their new company's challenge)
- Touch 4 (Day 50–60): Email — Direct ask with social proof

Apply persuasion frameworks:
- **Familiarity bias**: Lead with shared history, not product pitch
- **New chapter framing**: Position the outreach as a natural continuation of a successful pattern, not a cold pitch
- **Reciprocity**: Give something valuable before asking for anything
- **Social proof**: Use role-specific proof points (e.g., "Two other new VPs of Marketing at [industry] companies got X result in their first quarter")

**Task 4 — Executive Sponsor Play (Enterprise accounts only)**
If the new company has 500+ employees:
- Draft a parallel exec-to-exec outreach (CEO/CMO to their peer) that references the champion connection without making it awkward
- Recommend timing relative to the individual outreach sequence (typically start exec play 2 weeks after first touch to champion)
- Suggest mutual LinkedIn connections or events to warm the exec intro

**Task 5 — CRM Workflow & Automation Blueprint**
Produce step-by-step CRM implementation:

*Salesforce:*
- New opportunity record: name convention, stage, close date estimate, amount
- Contact roles: Economic Buyer / Champion / Influencer assignments
- Custom fields to populate: Signal Source = "Job Change", Original Company, Original Deal ID
- Task sequence: create follow-up tasks with specific due dates
- Alert rule: trigger Slack notification to AE when contact's title/company changes
- Opportunity source tag: "Champion Re-Engagement"

*HubSpot:*
- Equivalent workflow triggers, deal stage, and property updates
- Enrollment criteria for job-change sequence in HubSpot Sequences
- List segmentation: "Job Change Signals — Active" smart list

**Task 6 — Internal Routing & Notification**
- Determine ownership: Which AE/CSM should own this? (Based on former account owner, territory rules, or relationship history)
- Draft the internal Slack message to route the opportunity (include context, recommended next step, and deadline)
- Escalation path if original AE is unavailable or territory has changed

**Task 7 — Program-Level Intelligence Report**
If analyzing multiple job changes in batch, produce:
- Pipeline value at stake: total estimated ARR opportunity from all detected signals
- Priority ranking: order contacts by: (1) ICP fit score, (2) original deal value, (3) relationship warmth, (4) buying window urgency
- Coverage gaps: contacts where data is insufficient to personalize outreach — flag for enrichment
- Benchmark: expected pipeline conversion rate from job-change signals (industry benchmark: 15–30% of champion re-engagements convert to qualified opportunities; best-in-class programs achieve 35–45%)

OUTPUT FORMAT:
For each contact: structured action brief with sections labeled as above.
For batch analysis: executive summary table + individual briefs.
Flag confidence level (High / Medium / Low) for ICP fit scores and timing recommendations.

---

## Example Input/Output

**Input:**
- Product: RevOps analytics platform (HubSpot/Salesforce connector with revenue attribution dashboards), ACV $28K, 4-month sales cycle
- ICP: B2B SaaS, 50–500 employees, Series A–C, HubSpot or Salesforce user
- Champion signal: Sarah Chen, formerly Head of Marketing Ops at Lattice (existing customer, champion for 18 months, product power user), just joined Rippling as Director of Revenue Operations. Job change detected via LinkedIn, 12 days ago.

**Output excerpt:**

**Account Intelligence Brief — Rippling**
- ICP Fit Score: A (strong match)
  - Industry: B2B SaaS ✓
  - Headcount: ~900 employees (above ICP ceiling — flag for enterprise motion consideration)
  - Funding: Series C, $145M raised (2023) ✓ — budget likely available
  - Tech stack signals: LinkedIn job postings reference Salesforce + HubSpot hybrid environment ✓
  - Growth signal: Rippling expanded HRIS into finance suite — RevOps complexity is increasing ✓
- Data gaps to enrich: current attribution tool (ZoomInfo or Bombora signal needed), existing contract with competitor (check G2 reviews by Rippling employees)

**Buying Window Analysis**
- Window opens: Day 30 post-hire (VP-equivalent title, needs to understand current state before taking action)
- Window rationale: Director of RevOps at a high-growth company typically owns attribution reporting within 60 days; Sarah's prior experience with our platform means she understands the value proposition and doesn't need to be educated — she needs a reason to advocate internally
- Window closes: Day 90 if she inherits existing vendor contracts locked in; Day 120 if budget planning cycle begins
- Risk: Rippling has internal data engineering capability — validate whether DIY is a real option

**Touch 1 — LinkedIn (Day 13, send tomorrow)**
"Sarah — congrats on the Rippling move! Loved watching the attribution workflows you built at Lattice become a template for the whole team. Would love to hear how you're thinking about RevOps at your new scale."

**Touch 2 — Email (Day 21)**
Subject: From Lattice's attribution playbook → Rippling's

Sarah,

The cohort attribution reports your team built at Lattice are still one of our most-shared examples internally — three other customers have replicated the model.

Rippling's GTM complexity is a different beast: multi-product, multi-segment, HRIS + finance data mixing with revenue. Curious whether attribution is already on your 90-day list or if you're still mapping the current state.

Either way, I have a 10-minute benchmark comparison of how Director/VP RevOps at Series C SaaS companies are solving exactly this in 2025 — happy to send over if useful.

[Name]

**CRM Actions (Salesforce)**
1. Create Opportunity: "Rippling — Champion Re-Engagement — Sarah Chen" | Stage: Awareness | Estimated Close: 90 days | Amount: $28,000
2. Create Contact: Sarah Chen, Director RevOps, Rippling | Link to Opportunity as Champion
3. Populate fields: Signal_Source__c = "Job Change", Original_Company__c = "Lattice", Original_Opp_ID__c = [Lattice Opp ID]
4. Create Tasks: T1 LinkedIn (today), T2 Email Day 21, T3 Email Day 35, T4 Email Day 50
5. Slack alert to AE @jordan: "🔁 Champion signal: Sarah Chen (Lattice power user) joined Rippling as Dir RevOps. A-fit account. Outreach sequence staged. Review by EOW."

---

## Success Metrics

**Sequence Performance**
- Connection acceptance rate (LinkedIn): >40% (vs. 15–20% cold)
- Email open rate: >55% (vs. 25–35% cold outreach)
- Reply rate: >20% (vs. 5–8% cold outreach)
- Meeting booked rate: >15% of contacts worked (vs. 2–4% cold)

**Pipeline Quality**
- Champion re-engagement to qualified opportunity conversion: 15–30% (benchmark), 35–45% (best-in-class)
- Average sales cycle vs. standard: expect 30–50% shorter cycle (existing trust reduces education phase)
- Win rate vs. standard new business: expect 1.5–2x higher (familiar buyers, lower perceived risk)

**Program-Level**
- Coverage: >80% of detected job changes actioned within 72 hours of signal
- CRM hygiene: 100% of job-change opportunities tagged with Signal_Source for attribution tracking
- Pipeline contribution: measure quarterly — champion re-engagement should represent 8–15% of new pipeline in mature programs

---

## Related Prompts

- `../../05_Analytics-&-Performance/Demand-Sensing-&-Market-Intelligence/AI-Powered-Demand-Sensing-&-Market-Signal-Intelligence-Engine.md` — Broader buying signal intelligence framework
- `../../05_Analytics-&-Performance/Demand-Sensing-&-Market-Intelligence/G2-Review-Mining-&-Voice-of-Market-Competitive-Intelligence-Engine.md` — Competitor signal mining from review sites
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md` — Activate intent signals for ABM targeting
- `../../04_Demand-&-Lead-Generation-&-Growth/Account-Based-Marketing/ABM-Buying-Committee-Engagement-&-Multi-Stakeholder-Intelligence-Engine.md` — Map and engage full buying committees at target accounts

---

## Integration Tips

**LinkedIn Sales Navigator**
- Set up "Lead alerts" for your contact list — Navigator notifies you within 48 hours of job changes
- Use "Account alerts" on closed-lost accounts to detect new exec hires
- Export job-change alerts weekly into a CSV → feed into your CRM automation or this prompt for batch processing

**HubSpot**
- Create a workflow: trigger on "Job Title changed" or "Company changed" contact property → enroll in Job Change Sequence → create Deal in "Champion Re-Engagement" pipeline
- Use HubSpot's built-in LinkedIn integration to sync Sales Navigator alerts directly to contact records
- Build a "Job Change Signals" dashboard showing contacts detected, outreach initiated, meetings booked, and deals created

**Salesforce + UserGems / Champify**
- UserGems and Champify automatically detect job changes from your CRM contacts and push them back as new leads — this prompt helps you operationalize their outputs
- Create a Salesforce Flow: when Signal_Source__c = "Job Change" on a new Opportunity → auto-assign to former account owner → send Slack notification via Zapier or Slack for Salesforce

**Zapier / Make Automation**
- Trigger: New row in Google Sheet (manually tracked job changes or CSV import from LinkedIn)
- Action 1: Create/update contact in CRM with new company and title
- Action 2: Send prompt output to AI model → generate personalized sequence
- Action 3: Push sequence into Outreach/Salesloft as a new prospect + enroll in champion re-engagement sequence
- Action 4: Post Slack notification to #revenue-signals channel

**Outreach / Salesloft**
- Create a dedicated sequence: "Champion Re-Engagement — [Seniority Level]" with variable fields for former company, former product use case, and new company industry
- Tag all prospects in this sequence with "Job Change" source for attribution reporting
- Set sequence reply detection to route responses directly to AE inbox (not SDR queue)

---

## Troubleshooting

**Problem: The champion is now at a company well outside our ICP (too small, wrong industry)**
Fix: Don't abandon the relationship — send a lightweight, non-sales congratulatory message to maintain warmth. Add to a "future pipeline" list for quarterly check-ins. Champion relationships compound over careers; they may move again to an ICP-fit company, or refer you to peers who are a fit. Never burn the bridge with a hard pitch to a non-ICP account.

**Problem: The champion's new company is already a customer or in an active deal**
Fix: Route immediately to the CSM or AE owning that account — this is an expansion signal, not a new business signal. The champion's arrival can accelerate expansion, unlock a new department, or provide internal advocacy for a renewal at risk. Update the opportunity in CRM with the new contact and coordinate the welcome.

**Problem: Outreach feels awkward or recipient doesn't remember the relationship strongly**
Fix: Lead with a specific product artifact they created or a result they achieved — not generic "loved working with you" language. If the relationship was thin (e.g., one demo call), lead with industry relevance and drop the "we've worked together" framing entirely. Use the proof point + new role angle instead. If truly uncertain about relationship strength, classify as "warm outbound" rather than champion re-engagement and adjust tone accordingly.

---

## Version History
- v1.0: Initial creation (auto-generated)
