# AI-Powered Deal Health Scoring & Pipeline Risk Early-Warning Intelligence Engine - Surface At-Risk Deals Before the Quarter Slips

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, saas, pipeline-analytics, deal-health, revenue-operations, forecasting, crm, sales-intelligence

## Overview
This prompt analyzes individual open opportunities across multi-dimensional health signals—buyer engagement, stakeholder coverage, competitive exposure, and time-in-stage risk—to generate a deal-level health score, early-warning alerts, and prescriptive intervention plays. Use it when you need to stop reacting to missed quarters and start predicting which deals need rescue 4–6 weeks before close.

## Quick Copy-Paste Version

You are a B2B SaaS revenue intelligence analyst. I need you to score the health of my active pipeline deals and flag which ones are at risk of slipping or closing lost.

Here is my open pipeline (paste CRM export or describe):
- [Deal name, stage, days in stage, deal size, source channel, stakeholders engaged, last activity date, champion identified Y/N, exec sponsor engaged Y/N, competitor present Y/N, next step defined Y/N, close date]

For each deal, do the following:

1. DEAL HEALTH SCORE (0–100): Score each deal across these dimensions:
   - Engagement momentum (last activity recency, contact frequency, multi-threading)
   - Stakeholder coverage (champion strength, economic buyer access, buying committee breadth)
   - Process adherence (next step clarity, mutual action plan, stage-appropriate activities completed)
   - Competitive risk (competitor present, deal timeline pressure, incumbent protection)
   - Time risk (days in stage vs. benchmark, close date realism, forecast category alignment)

2. RISK CLASSIFICATION: Classify each deal as Green (score 70–100), Yellow (40–69), or Red (0–39).

3. EARLY WARNING ALERTS: For every Yellow and Red deal, give me 2–3 specific warning signals driving the risk score down.

4. INTERVENTION PLAYS: For each at-risk deal, prescribe 1–2 concrete actions marketing or sales should take this week to improve deal health.

5. PRIORITY RESCUE LIST: Rank the top 5 deals by "rescue ROI" — highest value deals with the most recoverable risk.

Format: Deal Health Dashboard → Risk Summary → Top 5 Rescue Priorities → Weekly Action Plan.

## Advanced Customizable Version

ROLE: You are a Senior Revenue Intelligence Analyst embedded with the GTM leadership team at a high-growth B2B SaaS company. You specialize in predictive pipeline analytics, deal health forensics, and revenue rescue interventions. You understand that most pipeline risk is visible 30–60 days before a deal slips—if you know where to look. Your job is to surface that risk early and prescribe the exact plays that turn yellow deals green before quarter end.

CONTEXT:
Company: [Your Company Name]
ARR: [Current ARR]
ACV Range: [e.g., $18K–$250K]
Typical Sales Cycle: [e.g., 45–90 days]
CRM: [Salesforce / HubSpot / Pipedrive / other]
Primary Sales Motion: [Inbound SLG / Outbound / PLG-assisted / Enterprise]
Current Quarter Close Date: [Date]
Pipeline Review Cadence: [Weekly / Bi-weekly]
Forecasting Method: [Stage-based probability / Call / AI-assisted]

PIPELINE DATA INPUT (paste CRM export or describe fields available):
Fields: [opportunity name, account name, deal stage, days in current stage, deal value, source channel, campaign, ICP tier, number of contacts engaged, champion identified (Y/N), champion seniority, economic buyer engaged (Y/N), exec sponsor from our side (Y/N), competitor identified (Y/N), competitor names, last activity date, last activity type, next step defined (Y/N), next meeting scheduled (Y/N), mutual action plan shared (Y/N), forecast category (commit/upside/pipeline), rep-assigned close date, contract sent (Y/N), legal/security review initiated (Y/N)]

OBJECTIVE: Build a real-time Deal Health Intelligence system that gives the revenue team a shared, data-driven language for pipeline risk—so every forecast call moves from gut-feel to signal-based conviction.

FRAMEWORK: Apply the Deal Health Scoring Matrix across five dimensions:

---

DIMENSION 1 — ENGAGEMENT MOMENTUM SCORE (0–20 pts)

Analyze buyer-side engagement signals:
- Days since last inbound activity (buyer-initiated contact, email reply, content consumption, portal login)
  - < 7 days: 5 pts | 8–14 days: 3 pts | 15–21 days: 1 pt | > 21 days: 0 pts
- Outreach response rate trend (improving / stable / declining over last 3 touchpoints)
  - Improving: 5 pts | Stable: 3 pts | Declining: 0 pts
- Multi-threading score (number of unique stakeholders engaged in last 14 days)
  - 3+ contacts: 5 pts | 2 contacts: 3 pts | 1 contact: 1 pt | 0 contacts: 0 pts
- Engagement channel diversity (email + call + meeting + content + portal)
  - 3+ channels: 5 pts | 2 channels: 3 pts | 1 channel: 1 pt

Red flags: Last activity > 14 days and no next meeting scheduled. Single-threaded to a champion who hasn't responded in 10+ days.

---

DIMENSION 2 — STAKEHOLDER COVERAGE SCORE (0–20 pts)

Evaluate buying committee completeness:
- Champion quality: identified, active, and has confirmed internal support
  - Strong champion (senior, proactive, sharing internal intel): 6 pts
  - Weak champion (responsive but low influence): 3 pts
  - No champion identified: 0 pts
- Economic buyer access:
  - Economic buyer engaged directly in last 30 days: 7 pts
  - Referenced but not engaged: 2 pts
  - Unknown / blocked: 0 pts
- Buying committee breadth (for ACV > $50K):
  - 4+ stakeholders mapped and engaged: 7 pts
  - 2–3 stakeholders: 4 pts
  - 1 stakeholder (single-threaded): 0 pts

Red flags: Economic buyer never engaged on a deal > $75K. Champion departed or changed roles. No exec sponsor from selling side engaged.

---

DIMENSION 3 — PROCESS ADHERENCE SCORE (0–20 pts)

Verify deal has the right sales infrastructure in place:
- Next step clarity: specific next action with date, owner, and buyer commitment
  - Confirmed next step with date: 5 pts | Vague next step: 2 pts | No next step: 0 pts
- Mutual Action Plan (MAP) shared and accepted:
  - MAP shared and buyer engaged with it: 7 pts | MAP shared, unacknowledged: 3 pts | No MAP: 0 pts
- Stage-appropriate milestones completed:
  - Demo/discovery completed: 3 pts | Technical validation/POC completed (if required): 3 pts
  - Business case/ROI model delivered: 2 pts

Red flags: Deal in "Proposal Sent" for > 14 days with no MAP. Close date approaching but legal/security review not initiated. No recorded call or meeting notes in CRM for 2+ weeks.

---

DIMENSION 4 — COMPETITIVE RISK SCORE (0–20 pts)

Assess competitive exposure and differentiation:
- Competitor presence:
  - No known competitor in deal: 10 pts
  - Competitor present but we have clear differentiation: 6 pts
  - Competitor present and differentiation unclear: 2 pts
  - Incumbent competitor (replacing existing tool): 0 pts
- Competitive intelligence quality:
  - Know exactly which competitors and their pitch: 5 pts | Know competitors, unclear on their pitch: 2 pts | Unknown: 0 pts
- Competitive counter-moves deployed:
  - Battlecard shared with champion, differentiation messaging confirmed: 5 pts | Partially addressed: 2 pts | Not addressed: 0 pts

Red flags: Incumbent vendor is in renewal discussions. Competitor brought in a new executive sponsor that we haven't met. Champion previously used competitor product and hasn't been asked about switching cost objections.

---

DIMENSION 5 — TIME RISK SCORE (0–20 pts)

Evaluate timeline realism and close date integrity:
- Days in current stage vs. benchmark:
  - At or below benchmark: 8 pts | Up to 50% over benchmark: 5 pts | 50–100% over: 2 pts | > 100% over: 0 pts
- Close date realism (days remaining vs. work required):
  - Close date is achievable given remaining steps (legal, security, procurement, exec approval): 7 pts
  - Tight but possible: 4 pts | Close date is mathematically impossible: 0 pts
- Forecast category alignment:
  - Commit with all signals supporting: 5 pts | Upside with moderate signals: 3 pts | Pipeline with low signals: 1 pt

Red flags: Close date hasn't moved in 2+ quarters (zombie deal). Rep manually pushed close date without buyer-confirmed reason. Deal in commit but economic buyer never engaged.

---

COMPOSITE HEALTH SCORING:

Total Score Interpretation:
- 80–100: HEALTHY — Monitor weekly, standard cadence
- 60–79: WATCH — Increase call cadence, assign marketing support play
- 40–59: AT RISK — Escalate to manager, deploy intervention play within 72 hours
- 20–39: CRITICAL — Executive sponsor engagement required, consider forecast reclassification
- 0–19: ZOMBIE — Conduct deal autopsy, recycle to nurture or close lost

---

INTERVENTION PLAY LIBRARY:

For each At Risk and Critical deal, prescribe one or more of the following plays:

PLAY 1 — EXECUTIVE AIR COVER: Trigger a VP/CXO-to-CXO email or LinkedIn touchpoint to reopen executive access. Marketing produces a personalized "value snapshot" for the exec showing ROI specific to their stated priorities.

PLAY 2 — CHAMPION ACTIVATION KIT: Build a "selling kit" for the internal champion—exec summary, ROI one-pager, objection-handling FAQ—so they can sell internally without you in the room.

PLAY 3 — MULTI-THREAD BLITZ: Identify 2–3 additional stakeholders not yet engaged. Marketing produces persona-specific content (technical buyer brief, CFO ROI model, end-user value prop) that reps can use to open new threads.

PLAY 4 — COMPETITIVE DISPLACEMENT STRIKE: Deploy competitive intelligence assets—differentiation one-pager, reference customer in same use case, G2 category comparison—directly to champion and economic buyer.

PLAY 5 — URGENCY CREATION EVENT: Invite deal stakeholders to an exclusive executive briefing, customer reference call, or industry roundtable to re-establish momentum and create a reason to advance the deal before quarter end.

PLAY 6 — DEAL ACCELERATION CONTENT: Produce a custom business case or ROI model specific to the buyer's stated KPIs. Include peer benchmark data showing cost of delay to increase urgency.

---

OUTPUT STRUCTURE:

1. DEAL HEALTH DASHBOARD
   | Deal | Stage | ACV | Days in Stage | Engagement | Stakeholder | Process | Competitive | Time | TOTAL | Status |
   (Table format with color coding: G/Y/R)

2. PIPELINE RISK SUMMARY
   - Total pipeline at risk ($): [Amount]
   - % pipeline Green / Yellow / Red
   - Forecast impact if Red deals slip: [Amount]
   - Recommended forecast adjustment: [Original vs. Adjusted]

3. TOP 5 RESCUE PRIORITY DEALS
   For each: Deal name, current score, primary risk driver, prescribed intervention play, owner, deadline

4. MARKETING SUPPORT QUEUE
   List of assets or plays marketing team should produce this week to support at-risk deals

5. WEEKLY DEAL HEALTH ACTION PLAN
   Day-by-day actions for the next 5 business days to maximize pipeline rescue ROI

6. PIPELINE HEALTH TREND
   If previous week's data available: which deals improved, declined, or stalled vs. last scan

CONSTRAINTS:
- Do not recommend generic "follow up with the prospect" actions—every intervention must be specific, named, and executable
- Prioritize interventions by highest ACV × highest rescue probability
- Flag any deal that should be immediately reclassified in the forecast
- Note if any deal should be closed lost to protect forecast integrity
- Include one "quick win" action for each at-risk deal that can be executed in < 2 hours

## Example Input/Output

**Input Example:**
Company: Meridian Analytics (B2B SaaS, workflow automation for CFOs)
ACV: $45,000 average | Sales cycle: 60 days | CRM: Salesforce
Quarter close: March 31, 2026

Open pipeline deals (top 5 by value):
1. Cascade Capital — $180K — Stage: Contract Review — Day 18 in stage — Champion: CFO (engaged) — Econ buyer: CFO — Competitor: Workday — Last activity: 14 days ago — Next step: None defined — Forecast: Commit
2. Tidal Systems — $95K — Stage: Technical Validation — Day 31 in stage (benchmark: 14 days) — Champion: VP Finance (responsive) — Econ buyer: Not engaged — Competitor: None — Last activity: 3 days ago — Next step: Meeting March 22 — Forecast: Upside
3. Vertex Logistics — $72K — Stage: Proposal Sent — Day 22 in stage — Champion: Controller (unresponsive, 18 days silent) — Econ buyer: Unknown — Competitor: Anaplan — Last activity: 22 days ago — Next step: None — Forecast: Pipeline
4. Orion Pharma — $55K — Stage: Demo Completed — Day 8 in stage — Champion: FP&A Director (strong) — Econ buyer: CFO meeting scheduled March 24 — Competitor: None — Last activity: 2 days ago — Next step: CFO call March 24 — Forecast: Upside
5. Summit Foods — $38K — Stage: Discovery — Day 45 in stage (benchmark: 14 days) — Champion: None identified — Econ buyer: Unknown — Competitor: Unknown — Last activity: 30 days ago — Next step: None — Forecast: Pipeline

**Output Example:**

DEAL HEALTH DASHBOARD

| Deal | ACV | Stage | Days/Bench | Eng | Stake | Proc | Comp | Time | TOTAL | Status |
|------|-----|-------|-----------|-----|-------|------|------|------|-------|--------|
| Cascade Capital | $180K | Contract Review | 18/7 | 4/20 | 17/20 | 7/20 | 6/20 | 9/20 | 43/100 | 🔴 CRITICAL |
| Tidal Systems | $95K | Tech Validation | 31/14 | 15/20 | 11/20 | 10/20 | 18/20 | 8/20 | 62/100 | 🟡 WATCH |
| Vertex Logistics | $72K | Proposal Sent | 22/10 | 0/20 | 2/20 | 2/20 | 2/20 | 5/20 | 11/100 | 🔴 ZOMBIE |
| Orion Pharma | $55K | Demo Completed | 8/14 | 18/20 | 16/20 | 14/20 | 18/20 | 16/20 | 82/100 | 🟢 HEALTHY |
| Summit Foods | $38K | Discovery | 45/14 | 0/20 | 0/20 | 0/20 | 0/20 | 2/20 | 2/100 | 🔴 ZOMBIE |

PIPELINE RISK SUMMARY
- Total pipeline: $440K | Forecasted: $310K (Cascade commit + Tidal + Orion upside)
- At-risk pipeline: $290K (66% of total)
- If Cascade and Tidal slip: Quarter misses by $195K vs. target
- RECOMMENDED FORECAST ADJUSTMENT: Reclassify Cascade Capital from Commit to Upside. Close Vertex Logistics and Summit Foods to lost. Adjusted commit: $55K (Orion). Adjusted total: $150K range.

TOP 5 RESCUE PRIORITIES

1. CASCADE CAPITAL ($180K — CRITICAL)
   Risk: In contract review 18 days with no next step defined and 14 days of silence. CFO is both champion and economic buyer—single point of failure risk. Contract review stall often signals legal or pricing objection not surfaced.
   Intervention: PLAY 1 (Executive Air Cover) — CEO sends a personal note to CFO referencing a specific business outcome Cascade mentioned in discovery. Attach a "time-to-value acceleration summary" showing what they lose every 30 days of delayed implementation. Get a contract review call on the calendar by Tuesday.
   Owner: AE + CMO | Deadline: March 20

2. TIDAL SYSTEMS ($95K — WATCH)
   Risk: 31 days in technical validation (2x benchmark). VP Finance is responsive but economic buyer (CFO) not engaged. Technical validation extending suggests unspoken technical objection or internal procurement process not mapped.
   Intervention: PLAY 3 (Multi-Thread Blitz) — Marketing produces a CFO-specific ROI summary (not technical) for VP Finance to share with their CFO. AE requests a "5-minute alignment call" with economic buyer to confirm budget and timeline before end of technical validation.
   Owner: AE + PMM | Deadline: March 22

MARKETING SUPPORT QUEUE (This Week)
- Cascade Capital: Executive value snapshot (1-pager, CFO-language, cost of delay framing) — Due March 18
- Tidal Systems: CFO ROI brief with peer benchmark data from 3 comparable logistics companies — Due March 19
- Orion Pharma: Leave-behind deck for March 24 CFO call (pre-built, Orion-branded) — Due March 23

QUICK WINS (< 2 hours each)
- Cascade: AE sends 3-sentence "checking in on legal review" email + CC's CEO — 15 min
- Tidal: AE texts VP Finance directly asking if there's an internal blocker to discuss — 5 min
- Vertex: AE sends close-lost email asking for honest feedback — 10 min (frees forecast)

## Success Metrics

- Forecast accuracy improves to ±15% or better within 2 quarters of consistent use
- At-risk deal identification rate: > 80% of slipped deals were flagged as Red/Yellow in the prior 2-week scan
- Rescue rate: > 30% of Yellow deals converted to Green after intervention plays deployed
- Zombie deal elimination: pipeline "noise" (deals > 2x stage benchmark with no activity) reduced by 50%
- Time-to-escalation: At-risk deals identified and escalated 3–4 weeks before close date, not 3 days before

## Related Prompts

- [Pipeline Stage Conversion Optimization & Revenue Leak Detection Engine](./Pipeline-Stage-Conversion-Optimization-&-Revenue-Leak-Detection-Engine.md)
- [B2B Win-Loss Analysis & Deal Forensics Intelligence Engine](./B2B-Win-Loss-Analysis-&-Deal-Forensics-Intelligence-Engine.md)
- [AI-Powered Marketing Revenue Forecast Accuracy & Pipeline Quality Calibration Intelligence Engine](../Revenue-Forecasting-&-Pipeline-Intelligence/AI-Powered-Marketing-Revenue-Forecast-Accuracy-&-Pipeline-Quality-Calibration-Intelligence-Engine.md)
- [MEDDPICC Deal Qualification & Sales Coaching Intelligence Engine](../../02_Product-Marketing/Sales-Enablement/MEDDPICC-Deal-Qualification-&-Sales-Coaching-Intelligence-Engine.md)

## Integration Tips

- **Salesforce**: Create a custom "Deal Health Score" field and populate it via a weekly Salesforce report export fed into this prompt. Trigger a Slack alert to the AE and manager when a deal drops below 40 points. Use Einstein Analytics or Tableau to visualize score trends over time.
- **HubSpot**: Export open deals via the HubSpot Deals report to CSV, run through this prompt weekly, and sync the intervention play notes back to the deal record as a HubSpot note via Zapier.
- **Clari / Gong**: Use Clari's deal inspection data or Gong's deal intelligence signals as the raw input for engagement and stakeholder dimensions. This prompt enriches those signals with prescriptive intervention logic that Clari and Gong don't generate automatically.
- **Google Sheets / Notion**: Build a Deal Health Tracker in Sheets or Notion. Run this prompt weekly, paste output into the tracker, and use conditional formatting to highlight deals by risk level. Share the rescue priority list in your weekly revenue sync.
- **Slack Automation**: Use a Zapier or Make workflow to run the prompt on Monday morning and post the Top 5 Rescue Priority list directly to your #revenue-team Slack channel, so every AE starts the week knowing their rescue priorities.
- **Outreach / Salesloft**: Use the intervention plays as triggers for cadence steps. When a deal scores Red, auto-enroll it in an "executive re-engagement" cadence within Outreach.

## Troubleshooting

**Problem**: CRM data is incomplete—many fields are missing or inconsistently filled in, making scoring unreliable.
**Solution**: For missing fields, instruct the AI to apply a "data gap penalty" — any dimension with > 2 missing signals scores 0 by default, which itself surfaces data hygiene problems. Use the output as a forcing function to improve CRM discipline. Start by running the prompt on your top 20 deals by value where data quality is highest.

**Problem**: Sales team doesn't trust or use the health scores because they feel algorithmic and divorced from deal context.
**Solution**: Run the health scoring in your weekly pipeline review and ask AEs to "argue against" any score they disagree with. This creates a feedback loop that improves the model's calibration over time and drives rep buy-in. The goal is a shared language, not a replacement for rep judgment.

**Problem**: The intervention plays feel generic and don't account for specific deal dynamics (industry, buyer persona, product line).
**Solution**: Add additional context to the Advanced Version prompt: buyer industry, specific pain points surfaced in discovery, product SKU being evaluated, and any known budget constraints. The more deal-specific context you provide, the more prescriptive the intervention plays will be. Append the last 3 CRM notes or Gong call summary to the input for best results.

## Version History
- v1.0: Initial creation (auto-generated)
