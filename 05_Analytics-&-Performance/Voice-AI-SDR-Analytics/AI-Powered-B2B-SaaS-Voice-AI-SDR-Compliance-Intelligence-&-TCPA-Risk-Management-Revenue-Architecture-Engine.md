# AI-Powered B2B SaaS Voice AI SDR Compliance Intelligence & TCPA Risk Management Revenue Architecture Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** voice-ai, tcpa-compliance, ai-sdr, risk-management, outbound-calling, do-not-call, regulatory-compliance, revenue-protection, b2b, saas

## Overview

This prompt builds a fully autonomous compliance intelligence system for Voice AI SDR programs — scanning prospect lists for TCPA risk, DNC status, and state-level calling restrictions before a single dial is made, monitoring call-time compliance in real time, and quantifying the revenue cost of over-restricting clean prospects versus the legal cost of dialing risky ones. Use it when scaling autonomous outbound calling to 10,000+ dials per month and needing to eliminate seven-figure TCPA exposure without throttling pipeline production.

## Quick Copy-Paste Version

You are a senior revenue operations and legal risk analyst with deep expertise in TCPA compliance, state telemarketing regulations, and AI-powered outbound calling programs. My company sells [PRODUCT/CATEGORY] to [ICP: job titles + company size + industry] and runs an autonomous Voice AI SDR program making [X] calls per month through [TOOL: e.g., Artisan, 11x, Orum, Relevance AI, custom-built].

Build a complete compliance intelligence and risk management architecture for our Voice AI SDR program.

1. PRE-DIAL RISK SCORING FRAMEWORK:
   - Score every prospect 0-100 on TCPA risk before dialing based on:
     * Federal DNC registry match (immediate disqualify if matched)
     * State-specific DNC registry coverage (flag if in CA, TX, FL, IL which have stricter rules)
     * Wireless number detection: % of list that are mobile numbers requiring express written consent
     * Prior opt-out or stop signal in CRM: any "do not call" flag from prior human SDR interactions
     * Litigant risk flag: match against known TCPA serial plaintiff databases
   - Assign each prospect a risk tier: Green (dial freely), Yellow (dial with disclosure script), Red (suppress until manual legal review)
   - Produce a list-level risk score: if >15% of a prospect segment is Red tier, escalate for compliance review before campaign launch

2. STATE-BY-STATE CALLING WINDOW COMPLIANCE:
   - Map all prospects to their local timezone and enforce calling windows: 8am-9pm local time for federal law, 8am-8pm for stricter states
   - Flag states with additional restrictions: Florida (prior express written consent required for all calls), California (CCPA interaction + TCPA overlap rules), Indiana (no calls on Sundays)
   - Calculate the % of your prospect universe that can be reached in any given hour and recommend optimal call scheduling windows to maximize reachable pool without compliance violations
   - Build a real-time calling calendar showing green/yellow/red windows by state across a rolling 7-day period

3. CALL CONTENT COMPLIANCE MONITORING:
   - Define a required disclosure checklist for each AI call: caller identification within first 30 seconds, company name stated, purpose of call stated, opt-out mechanism offered ("press 9 to be removed")
   - Audit transcript samples (random 5% of completed calls) against disclosure checklist — calculate Disclosure Compliance Rate (DCR) target: >99.5%
   - Flag calls where AI agent spoke over opt-out attempts or failed to honor "remove me" requests — these represent highest TCPA litigation exposure
   - Track opt-out execution lag: time between prospect saying "remove me" and CRM suppress record being created — must be <24 hours per FTC Safe Harbor guidelines

4. REVENUE vs. RISK TRADE-OFF MODELING:
   - Calculate the cost of over-suppression: for every 1,000 prospects incorrectly flagged as Red tier, estimate pipeline value lost based on your average conversion rates (prospect → meeting → opportunity → closed-won)
   - Calculate the cost of under-suppression: TCPA statutory damages are $500/call (negligent) to $1,500/call (willful) — model exposure at 0.1%, 0.5%, and 1.0% violation rates across your monthly call volume
   - Build a breakeven model: at what violation rate does TCPA litigation exposure exceed the pipeline value of the calls placed?
   - Recommend a compliance investment level (DNC scrubbing services, legal review hours, compliance tooling) justified by risk-adjusted pipeline preservation

5. AUTOMATED COMPLIANCE REPORTING:
   - Weekly: DNC match rate, Risk Tier distribution (% Green/Yellow/Red), Disclosure Compliance Rate, opt-out volume and suppression lag
   - Monthly: TCPA exposure estimate (calls × violation probability × average settlement cost), pipeline preserved by compliance posture, list hygiene decay rate
   - Quarterly: State regulation change tracking — identify new legislation affecting calling rights and auto-flag any prospects in newly restricted jurisdictions
   - Incident log: any call that receives a cease-and-desist, attorney threat, or TCPA complaint — track resolution timeline and root cause

Output: a compliance intelligence dashboard spec, prospect list risk scoring rubric, calling calendar template, and a risk/revenue trade-off decision matrix ready to share with your legal team and VP of Revenue.

## Advanced Customizable Version

**ROLE:** You are a dual-expertise analyst combining the judgment of a senior revenue operations leader (obsessed with pipeline yield) and a TCPA/telemarketing compliance attorney (obsessed with risk elimination). You understand that over-compliance kills pipeline and under-compliance kills companies.

**COMPANY CONTEXT:**
- Product: [PRODUCT NAME] — [one-sentence description of what it does]
- ICP: [primary job titles], [company size: e.g., 200-2,000 employees], [primary industries]
- Voice AI SDR tool: [TOOL NAME and version if known]
- Monthly dial volume: [X] calls to [Y] unique prospects
- Geographic concentration: [% of prospects in California / Florida / Texas / other high-risk states]
- CRM: [HubSpot / Salesforce / other] — [does it currently store DNC flags? Y/N]
- Prior TCPA exposure: [any prior complaints, litigation, or consent-decree history? Y/N]
- Current compliance posture: [do you scrub against federal DNC today? Y/N] [state DNC? Y/N] [wireless detection? Y/N]

**OBJECTIVE:** Build a risk-layered compliance intelligence architecture that protects the company from TCPA and state telemarketing law violations while preserving maximum pipeline-generating call volume — eliminating reckless dials without suppressing compliant ones.

**DELIVERABLE 1 — PROSPECT LIST COMPLIANCE AUDIT PROTOCOL**

Before any Voice AI SDR campaign launches, run every prospect list through this sequential scrubbing waterfall:

Step 1 — Federal DNC Suppression (SAN required, scrub within 31 days of campaign start):
- Expected match rate: 2-8% for B2B lists (higher for SMB contacts who registered personal cells)
- Tool options: SalesIntel DNC scrub, DataValidation, Compliance Point API
- Action: Hard suppress matched records — do not pass to Voice AI queue

Step 2 — State DNC Registry Suppression (for campaigns touching CA, TX, FL, CO, IN, LA, MA, MO, NV, OR, PA, TN, TX, WY):
- Each state has its own registry and subscription requirement
- Action: Flag prospects in covered states, apply state-specific rule overlays

Step 3 — Wireless Number Classification:
- Use carrier lookup API (e.g., Twilio Lookup, TeleSign) to classify every number as landline, VOIP, or wireless
- Wireless numbers to consumers require express written consent under TCPA Section 227(b)
- For B2B calling to employees on company-issued wireless lines: FCC Business-to-Business exemption may apply — document this determination
- Action: Flag personal wireless numbers as Yellow; suppress unless you have documented consent records

Step 4 — Internal Suppression List Cross-Reference:
- Pull all contacts with any of these CRM flags: Do_Not_Call = True, Opted_Out = True, Unsubscribed_All = True, TCPA_Complaint = True
- Pull all contacts from prior opt-out events in the last 5 years (FTC requires honoring opt-outs indefinitely)
- Action: Hard suppress all matched records

Step 5 — TCPA Litigant Risk Screening:
- Cross-reference against known serial plaintiff databases (ContactCenterCompliance, Litigation Guardian)
- These individuals actively file TCPA suits — one call = immediate lawsuit regardless of technical compliance
- Action: Hard suppress all matched records — pipeline value is zero, legal cost is unlimited

Step 6 — List Risk Score Calculation:
- Green (Risk Score 0-30): Passed all 5 steps, landline or VOIP, no prior opt-out signal → dial freely
- Yellow (Risk Score 31-60): Wireless number with arguable B2B exemption, or in moderate-risk state, or missing consent documentation → dial with enhanced disclosure script, log call purpose documentation
- Red (Risk Score 61-100): Any DNC match, hard opt-out history, known litigant, wireless personal number without consent → suppress and route to manual legal review queue
- List-Level Gate: If Red tier exceeds 12% of any segment, freeze campaign and require compliance officer sign-off before launch

**DELIVERABLE 2 — REAL-TIME CALL COMPLIANCE MONITORING SYSTEM**

Configure your Voice AI SDR platform to enforce these rules on every call:

Calling Window Enforcement:
- Federal rule: 8:00am–9:00pm local time, Monday–Saturday
- State overlays (apply automatically based on prospect's ZIP code timezone mapping):
  * California: No automated calls for marketing without prior express written consent (CIPA + TCPA intersection)
  * Florida: Prior express written consent required for all voice calls — flag all FL wireless numbers as Red
  * Indiana: No calls on Sundays, 9am-9pm weekdays only
  * Massachusetts: 8am-8pm, no calls on legal holidays
- Implement a time-window API check at dial time — if current time falls outside window, reschedule call to next valid window slot (do not abandon, reschedule)

Mandatory Disclosure Script Audit:
Within the first 30 seconds of every AI call, the following must be spoken in plain language:
1. "My name is [AI agent name], I'm calling on behalf of [Company Name]" — Caller ID disclosure
2. "I'm calling because [specific, honest reason — not a vague 'business opportunity']" — Purpose disclosure
3. "This call may be recorded for quality assurance" — Recording disclosure where state law requires (all 11 one-party consent states + 12 two-party consent states)
4. "If you'd like to be removed from our calling list, you can say 'remove me' or press 9 at any time" — Opt-out mechanism disclosure

Recording Consent by State — Two-Party Consent States (California, Connecticut, Florida, Illinois, Maryland, Massachusetts, Michigan, Montana, Nevada, New Hampshire, Oregon, Pennsylvania, Washington):
- Must obtain verbal consent before recording: "Do you consent to this call being recorded?" 
- If prospect says No: do NOT record (configure AI agent to disable recording flag), proceed with call unrecorded
- If AI agent cannot disable recording mid-call: do not call two-party consent state contacts with recording enabled

**DELIVERABLE 3 — OPT-OUT PROCESSING ARCHITECTURE**

Opt-out requests received during AI calls must be honored immediately and permanently. Build this processing flow:

Real-Time Suppression (during call):
- Train AI agent to recognize these opt-out signals: "remove me," "take me off your list," "don't call again," "stop calling," pressing DTMF 9
- Upon detection: AI agent must confirm receipt ("I've added you to our do-not-call list — you won't receive calls from us again"), immediately terminate the call, trigger webhook to CRM to set Do_Not_Call = True

CRM Update SLA:
- Suppression record must be written to CRM within 15 minutes of call end (not 24 hours — real-time is the defensible standard)
- Suppression must propagate to all connected systems: email marketing platform, SDR outreach tools, ad platforms (to exclude from paid targeting), LinkedIn Sales Navigator exclusion lists
- Suppression must be honored across all channels — a voice opt-out = a full-channel opt-out under best practices (even if not legally required for all channels)

Audit Trail Requirements:
- Log every opt-out event: timestamp, prospect ID, phone number, AI agent session ID, transcript excerpt confirming opt-out language detected
- Retain opt-out records for 5 years minimum (FTC recommendation)
- Generate a monthly opt-out volume report: total opt-outs, % of completed calls, opt-out reasons categorized (wrong person, not interested, already customer, send email instead)

**DELIVERABLE 4 — RISK-ADJUSTED ROI MODEL**

Build a 12-month financial model showing compliance investment ROI:

Inputs:
- Monthly call volume: [X] dials
- Green tier call volume: [X × % Green] = dials placed
- Average pipeline generated per 1,000 Green tier dials: $[Y] (use your current conversion data)
- Compliance suppression rate: % of total list suppressed by risk scoring
- Compliance tooling and legal review cost: $[Z]/month

Revenue Side:
- Pipeline preserved by calling only Green tier prospects vs. calling unscrubbed list: [calculate lift in meeting rate from calling cleaner lists — industry data shows 15-25% higher connect rates on scrubbed lists due to reduced hostility from accidental DNC dials]
- Pipeline lost by suppressing Yellow/Red tier: [Yellow tier × win rate if dialed] = pipeline opportunity cost of caution

Risk Side:
- TCPA exposure calculation: Total dials × estimated violation rate (use 0.05% as base case for scrubbed lists) × $1,500 per willful violation = Maximum exposure
- Expected litigation cost: Maximum exposure × probability of suit (use 0.1% of violations result in filed complaint) × average settlement cost ($25,000–$75,000 for individual suits, $1M–$10M for class actions)
- Class action trigger risk: If >40 plaintiffs share the same violation pattern, TCPA class action risk emerges — model separately

Decision Framework:
- If (Compliance Investment + Pipeline Opportunity Cost) < (Expected Litigation Cost + TCPA Exposure): compliance investment is positive ROI
- Calculate the violation rate at which compliance program breakeven is achieved
- Recommend compliance budget as % of Voice AI SDR program total cost

**FRAMEWORKS TO APPLY:**
- Expected Value (EV) analysis for risk/reward trade-offs
- Failure Mode and Effects Analysis (FMEA) for compliance failure scenarios
- Jobs-to-be-Done for understanding what legal team needs from compliance reporting vs. what revenue team needs
- Control Chart methodology for monitoring Disclosure Compliance Rate — flag when DCR drops below 3-sigma control limit (indicating a systemic AI script problem, not random variation)

**OUTPUT FORMAT:**
Produce seven artifacts:
1. Prospect List Scrubbing Waterfall — sequential steps, tools, expected suppression rates, estimated time to complete
2. Risk Tier Scoring Rubric — criteria for Green/Yellow/Red classification with point values for each risk factor
3. Calling Calendar Template — 7-day rolling view showing green/yellow/red windows by state, formatted for import into Google Sheets or Notion
4. Disclosure Script Checklist — 10-item checklist with pass/fail criteria, ready to use as QA rubric against call transcripts
5. Opt-Out Processing SLA Flowchart — step-by-step flow from prospect says "remove me" to full-system suppression confirmation
6. Risk-Adjusted ROI Model — 12-month spreadsheet-ready model with inputs, calculations, and sensitivity analysis
7. Compliance Dashboard Spec — KPI definitions, data sources, visualization type, and refresh cadence for each metric

## Example Input/Output

**Input:**
- Product: Meridian Analytics — AI-powered financial reporting platform for mid-market CFOs
- ICP: CFOs and VP Finance, 500-5,000 employee companies, financial services and healthcare
- Voice AI tool: 11x "Alice" autonomous SDR agent
- Monthly dials: 8,500 calls to 3,200 unique prospects
- Geographic concentration: 28% California, 15% Florida, 12% Texas, 45% all other states
- CRM: Salesforce — no current DNC flags stored
- Prior TCPA exposure: One informal attorney letter in 2024, resolved without suit
- Current compliance: Federal DNC scrub only, no wireless detection, no state DNC

**Output (excerpt):**

**List Risk Assessment — Meridian Analytics Voice AI SDR Campaign**

Current Compliance Gap Analysis:
- Estimated wireless number exposure: 34% of 3,200 prospects are mobile-first (financial executives disproportionately use personal cells) — 1,088 contacts requiring consent documentation before dialing
- California exposure: 28% = 896 prospects; CIPA intersection with TCPA creates per-call liability even for B2B calls using AI dialing systems — recommend pause on CA wireless numbers until legal review
- Florida exposure: 15% = 480 prospects; FL requires prior express written consent for all calls — all FL wireless numbers = Red tier immediately
- Known litigant risk: Based on industry averages, expect 0.2-0.4% of B2B lists to contain known TCPA plaintiffs — estimated 6-13 contacts in current list requiring suppression

Post-Scrubbing Call Volume Projection:
- Total list: 3,200 prospects / 8,500 dials
- After federal DNC scrub: -4.2% = -134 prospects, -357 dials
- After state DNC (CA, FL, TX): -2.8% additional = -90 prospects, -240 dials
- After wireless classification + suppression of high-risk CA/FL wireless: -8.4% = -269 prospects, -714 dials
- After internal opt-out and litigant suppression: -1.1% = -35 prospects, -94 dials
- Net dialable universe: 2,672 prospects (83.5% of original list), 7,095 dials/month

Risk-Adjusted ROI (Month 1):
- Compliance tooling cost: $2,800/month (DNC scrub APIs, wireless lookup, litigant database)
- Pipeline value of suppressed 528 prospects (assuming 2.1% meeting rate × $48,000 ACV × 0.22 win rate): $117,000 annual pipeline at risk
- TCPA exposure on unscrubbed list: 8,500 dials × 0.8% estimated violation rate × $1,500 = $102,000/month exposure
- After prior attorney letter: violation probability multiplier 2.3× (prior notice makes next violation "willful") = $234,600/month exposure
- Compliance investment payback: $2,800 investment eliminates $234,600 monthly exposure = 83:1 ROI in risk terms
- Recommendation: Implement full compliance stack immediately; prior attorney letter elevates next violation to willful — class action risk elevated

Disclosure Compliance Rate — Current Baseline:
- Based on 5% transcript audit sample (50 calls): Caller ID disclosure rate: 94% (failing — AI agent introduces itself after 45 seconds in fast-talkers persona variant)
- Company name disclosure: 88% (critical failure — regulatory minimum, not optional)
- Opt-out mechanism offered: 71% (severe gap — required on every call)
- Immediate remediation: Update all AI agent scripts to front-load disclosures in first 15 seconds; re-audit after 200 calls

## Success Metrics

A well-executed compliance intelligence prompt delivers these outcomes:

**Risk Metrics (measured weekly):**
- DNC match rate after scrubbing: <0.01% of dialed numbers match federal DNC (near-zero is achievable with proper scrubbing)
- Disclosure Compliance Rate (DCR): >99.2% of calls contain all required disclosures in first 30 seconds
- Opt-out processing SLA: 100% of opt-outs suppressed in CRM within 15 minutes of call end
- Red tier dial rate: 0% — no Red tier prospects should ever reach the dial queue
- TCPA complaint rate: <0.005% of completed calls receive a formal complaint

**Revenue Protection Metrics (measured monthly):**
- Pipeline preservation rate: >85% of pre-scrubbing projected pipeline retained post-scrubbing (validates that compliance does not destroy program economics)
- Suppression false positive rate: <8% of suppressed contacts, when manually reviewed, would have been safe to dial (validates risk scoring accuracy)
- Risk-adjusted ROI: Compliance program cost as % of TCPA exposure eliminated — target >20:1

**Operational Metrics (measured monthly):**
- List scrubbing cycle time: <4 hours from list upload to compliance-cleared dial queue
- State regulation change response time: New state legislation identified and list overlay updated within 5 business days of law effective date
- Opt-out propagation completeness: 100% of voice opt-outs reflected across all connected systems within 24 hours

## Related Prompts

- [Voice AI SDR Performance Analytics & Revenue Attribution](./AI-Powered-B2B-SaaS-Voice-AI-SDR-Performance-Analytics-&-Autonomous-Outbound-Call-Revenue-Attribution-Intelligence-Engine.md)
- [Voice AI SDR Conversation Quality Intelligence & Call Script Optimization](./AI-Powered-B2B-SaaS-Voice-AI-SDR-Conversation-Quality-Intelligence-&-Call-Script-Optimization-Revenue-Engine.md)
- [AI Voice Agent Outbound Architecture & Autonomous Phone Pipeline Prospecting](../../04_Demand-&-Lead-Generation-&-Growth/Conversational-Marketing/AI-Powered-B2B-SaaS-AI-Voice-Agent-Outbound-Architecture-&-Autonomous-Phone-Pipeline-Prospecting-Revenue-Intelligence-Engine.md)
- [LinkedIn Social Selling Program Analytics & Rep-Level Revenue Attribution](../../05_Analytics-&-Performance/Social-Selling-Analytics/AI-Powered-B2B-SaaS-LinkedIn-Social-Selling-Program-Analytics-&-Rep-Level-Revenue-Attribution-Intelligence-Engine.md)

## Integration Tips

**Salesforce / HubSpot CRM Integration:**
- Create a custom field `TCPA_Risk_Tier` (Green/Yellow/Red) populated by compliance API at list import
- Build workflow: if `TCPA_Risk_Tier = Red` AND `Contact_Owner = Voice_AI_Queue`, trigger alert to RevOps and remove from queue automatically
- Create a compliance suppression list view showing all contacts with `Do_Not_Call = True` for monthly legal team review
- Build a dashboard showing opt-out volume trend week-over-week — spikes indicate a script or targeting problem

**Voice AI Platform Integration (11x / Artisan / Orum / Relevance AI):**
- Pass `TCPA_Risk_Tier` as a custom field to the Voice AI platform — configure platform to only dial `Green` and pre-approved `Yellow` records
- Enable webhook on call completion to push: call duration, opt-out signal detected (Y/N), disclosure compliance flags, transcript URL
- Configure DTMF opt-out (press 9) to trigger immediate call termination webhook + CRM suppression write

**Twilio Lookup API (Wireless Classification):**
- Automate number classification at list ingestion: `https://lookups.twilio.com/v2/PhoneNumbers/{number}?Fields=line_type_intelligence`
- Map response field `line_type_intelligence.type` to: `landline` → Green eligible, `mobile` → Yellow/Red based on state, `voip` → VOIP business lines generally lower TCPA risk
- Batch process lists nightly; results cached for 30 days before re-verification

**Compliance Point / ContactCenterCompliance DNC Scrub:**
- Schedule automated federal DNC scrub via API every 31 days (required SAN subscription refresh cadence)
- Layer state DNC scrub for any states representing >5% of your prospect universe
- Export scrub results directly to Salesforce suppression list via native integration

**Zapier / Make (Integromat) Automation:**
- Trigger: New contact added to Voice AI SDR campaign list
- Action chain: 1) Twilio lookup → classify number type, 2) DNC scrub API call, 3) Litigant database check, 4) Score risk tier, 5) Write TCPA_Risk_Tier to CRM field, 6) If Red → notify RevOps Slack channel, 7) If Green → add to Voice AI queue
- Full automation cycle target: <8 minutes per contact from list upload to queue assignment

**Google Sheets Calling Calendar:**
- Build a timezone mapping sheet: prospect ZIP → timezone → current local time
- Use `=GOOGLEFINANCE()` equivalent or Apps Script to pull current time by timezone and auto-color calling windows green/yellow/red
- Share with Voice AI platform operator to manually verify window compliance during peak volume periods

## Troubleshooting

**Problem: Disclosure Compliance Rate (DCR) is dropping below 95%.**
Root cause: AI agent script variant testing has introduced a fast-open variant that skips the caller ID introduction. Check which script variant is running on failing calls — typically one script template has been modified without compliance review. Fix: institute a compliance gate on all AI agent script changes — no variant goes live without a 20-call pilot audit showing DCR >99%.

**Problem: Opt-out suppression lag is averaging 4+ hours instead of 15 minutes.**
Root cause: The CRM suppression webhook is queuing behind other automation workflows during peak hours, or the webhook URL has changed and calls are silently failing. Fix: implement a dead-man alert — if no opt-out suppression events are logged within 2 hours of an opt-out-flagged call, fire a PagerDuty alert to RevOps. Test webhook health daily with a synthetic test call.

**Problem: Post-scrubbing pipeline yield has dropped more than 15% below pre-scrubbing projections — compliance is destroying ROI.**
Root cause: Risk scoring model is over-classifying Yellow as Red, suppressing dialable contacts. Audit a random 50-record sample of Red tier suppressions — if >20% would pass manual legal review, recalibrate risk thresholds. Often caused by: over-weighting the state-of-residence flag for contacts in restrictive states who are being called on VOIP landlines (lower TCPA risk), or suppressing all wireless numbers rather than only non-consented personal wireless.

## Version History
- v1.0: Initial creation (auto-generated)
