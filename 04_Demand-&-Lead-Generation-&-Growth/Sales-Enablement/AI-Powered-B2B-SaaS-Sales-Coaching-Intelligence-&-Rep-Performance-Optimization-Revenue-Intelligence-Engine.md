# AI-Powered B2B SaaS Sales Coaching Intelligence & Rep Performance Optimization Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** b2b-saas, sales-coaching, conversation-intelligence, gong, chorus, clari, rep-performance, sales-enablement, revenue-intelligence, call-analysis, deal-intelligence, win-rate-improvement, ramp-acceleration

## Overview
Deploys an AI-powered sales coaching program that continuously analyzes every rep's calls, emails, and deal activities — converting conversation data into automated coaching alerts, next-best-action recommendations, and rep-level performance scorecards. Use this when you have 5+ AEs and want to systematically improve win rates, compress new-rep ramp time, and scale top-rep behaviors without adding sales management headcount.

## Quick Copy-Paste Version

You are an AI Sales Coaching Intelligence Architect. Design a complete AI-powered sales coaching and rep performance optimization program for the company described below.

COMPANY SNAPSHOT:
- Company: [Your company name and product — e.g., "Meridian, a revenue forecasting platform for enterprise CFO teams"]
- Stage: [e.g., "Series B, $22M ARR, 12 AEs, 4 SDRs, 3 Sales Managers"]
- ICP: [e.g., "CFO/VP Finance at 500–5,000 employee companies in SaaS and Financial Services"]
- Avg deal size & cycle: [e.g., "$45K ACV, 60-day avg sales cycle, 3.2 buyer stakeholders"]
- Sales tools: [e.g., "Salesforce CRM, Gong for call recording, Outreach for sequences, Clari for forecasting"]
- Current overall win rate: [e.g., "26%; top 3 reps at 41%, bottom 3 at 14%"]
- Primary win/loss drivers identified: [e.g., "Wins: strong discovery, early multithreading. Losses: single-threaded, never reached economic buyer"]

DELIVERABLES:

1. BEHAVIORAL SIGNAL ARCHITECTURE: Define the 15 key signals the AI tracks per rep across discovery, demo, and negotiation calls — including talk/listen ratio, question quality, next-step commitment rate, objection handling, economic buyer access patterns, and multithreading velocity. Include specific thresholds that trigger automated coaching alerts.

2. REP PERFORMANCE SCORECARD: Build a 5-dimension Revenue Performance Score (0–100, updated weekly) using Gong/call data and CRM data inputs. Include benchmark values for top-quartile performers in each dimension.

3. AUTOMATED COACHING PLAYBOOK: Design AI-generated coaching workflows triggered by specific signal combinations — e.g., "rep talk ratio >65% AND 2+ deals stalled >21 days" triggers a specific Slack coaching message. Write the actual message templates, including specific talk tracks and suggested next actions.

4. TOP-REP BEHAVIORAL BLUEPRINT: Codify the patterns of your top-performing reps into a replicable playbook covering exact discovery question sequences, champion qualification criteria, multithreading timing, and objection handling language.

5. NEW-REP RAMP CURRICULUM: Design a 90-day AI-monitored ramp program — which calls new reps shadow in weeks 1–4, which milestones must be hit before independent selling access, and how AI monitors ramp trajectory versus historical benchmarks.

6. DEAL-LEVEL AI COACHING: How AI surfaces deal-specific risks (missing economic buyer, no next step booked, single-threaded at Stage 3, stage-duration outlier) and generates rep-specific guidance — including the exact Slack notification format and suggested action for each risk pattern.

7. MANAGER INTELLIGENCE WORKFLOW: How a frontline manager uses AI to run weekly 1:1s — automated rep performance briefs, curated call clips, deal-specific coaching questions, and how to measure coaching effectiveness over 30/60/90 days.

Output as an implementation blueprint a VP of Sales and RevOps can hand directly to their Gong admin and Salesforce developer to configure and launch within 4 weeks.

## Advanced Customizable Version

ROLE: You are a Senior AI Sales Performance Architect with 14+ years building high-performance B2B SaaS sales organizations. You've deployed AI-powered coaching programs at companies from Series A ($5M ARR) to pre-IPO ($150M ARR) that reduced new-rep ramp time by 35–50%, improved company-wide win rates by 8–15 percentage points, and scaled top-rep behaviors across entire sales floors without proportional management headcount growth. You are expert in Gong, Chorus, Clari, Salesforce, HubSpot, Outreach, and Salesloft data architecture.

CONTEXT:
Company: {{COMPANY_NAME}} — {{PRODUCT_DESCRIPTION}}
ARR & headcount: {{ARR}}, {{AE_COUNT}} AEs, {{SDR_COUNT}} SDRs, {{MANAGER_COUNT}} frontline managers
ICP: {{TARGET_TITLES}}, {{COMPANY_SIZE_RANGE}}, {{VERTICALS}}
Average ACV: {{ACV}} | Average sales cycle: {{SALES_CYCLE_DAYS}} days | Avg buying committee: {{STAKEHOLDER_COUNT}} stakeholders
Sales tool stack: CRM: {{CRM}} | Call intelligence: {{CALL_INTELLIGENCE_PLATFORM}} | Sequencing: {{SEQUENCING_TOOL}} | Forecasting: {{FORECASTING_TOOL}}
Overall win rate: {{WIN_RATE}}% | Top-quartile rep win rate: {{TOP_WIN_RATE}}% | Bottom-quartile: {{BOTTOM_WIN_RATE}}%
Primary win drivers: {{WIN_DRIVER_1}}, {{WIN_DRIVER_2}}
Primary loss drivers: {{LOSS_DRIVER_1}}, {{LOSS_DRIVER_2}}
New-rep avg ramp to first quota attainment: {{RAMP_MONTHS}} months
Current coaching method: {{COACHING_DESCRIPTION — e.g., "ad-hoc 1:1s, monthly call reviews, no systematic program"}}
AI coaching tooling budget: {{BUDGET}}
Call recording consent requirements: {{CONSENT_REQUIREMENTS — e.g., "1-party consent US, GDPR for EU prospects"}}

OBJECTIVE: Design a production-ready AI Sales Coaching Intelligence program that:
1. Automatically ingests and analyzes 100% of rep call, email, and deal activity data
2. Converts behavioral signal analysis into rep-specific and deal-specific coaching interventions
3. Codifies top-rep behaviors into systematically teachable playbooks for the full team
4. Reduces average ramp time to first quota attainment by 35%+
5. Improves company-wide win rate by 8–12 percentage points within 12 months
6. Scales to any AE team size without proportional growth in management headcount

---

SECTION 1 — BEHAVIORAL SIGNAL INTELLIGENCE ARCHITECTURE

**The 20-Signal Rep Performance Model:**

Build the complete signal set the AI tracks and scores per rep. Organize into five categories:

**A. Discovery Intelligence Signals**
| Signal | Data Source | Top-Rep Benchmark | Coaching Alert Threshold |
|--------|-------------|-------------------|--------------------------|
| Discovery call talk ratio | Gong/Chorus | 35–40% rep talk | >58% triggers coaching |
| Questions per hour of discovery | Gong NLP | 18–24 questions/hr | <12/hr triggers alert |
| MEDDIC element coverage in call 1 | Gong + Salesforce | Metrics + Economic Buyer + Decision Criteria | <3 elements = risk flag |
| Pain-to-impact question sequence | Gong NLP | 3+ pain→impact ladder questions | 0 questions = coaching trigger |
| Next-step commitment rate | Gong + Calendar | ≥75% of calls end with booked next step | <48% triggers manager alert |

**B. Demo & Evaluation Signals**
| Signal | Data Source | Top-Rep Benchmark | Coaching Alert Threshold |
|--------|-------------|-------------------|--------------------------|
| Champion engagement score | Gong + Email | >70 pts (Champion Engagement Model) | <40 pts = deal risk flag |
| Unique personas per demo | Gong speaker ID | 2.4+ personas per evaluation | <2 = single-thread risk |
| Feature-to-outcome language ratio | Gong NLP | <30% feature talk; >70% outcome language | Inverted ratio = coaching trigger |
| Objection interception rate | Gong | Handles 85%+ objections with prepared response | <60% = training flag |
| Demo-to-next-step conversion | Gong + Salesforce | ≥70% book follow-on in demo call | <45% = deal risk |

**C. Deal Velocity & Hygiene Signals**
| Signal | Data Source | Top-Rep Benchmark | Coaching Alert Threshold |
|--------|-------------|-------------------|--------------------------|
| Days stalled per stage vs. median | Salesforce | Stage 2: ≤18 days; Stage 3: ≤22 days | >1.5× median = coaching prompt |
| Economic buyer identified timing | Gong + Salesforce | EB named by opportunity day 21, 82% of deals | Missing EB day 30+ = deal risk |
| Buying committee breadth | Salesforce contacts | 3.2 avg contacts at Stage 3 | <2 contacts at Stage 3 = risk |
| CRM notes quality score | Salesforce + AI audit | Full MEDDIC captured after each call | Sparse notes = hygiene alert |
| Forecast commit accuracy | Clari | ±8% monthly commit accuracy | >25% variance = forecast coaching |

**D. Pipeline Generation Signals**
| Signal | Data Source | Top-Rep Benchmark | Coaching Alert Threshold |
|--------|-------------|-------------------|--------------------------|
| Discovery calls held per week | Calendar + Salesforce | 8–12 per week (mid-market AE) | <5/week = pipeline risk alert |
| Outbound sequence reply rate | Outreach/Salesloft | 14–18% reply rate | <8% = messaging coaching trigger |
| Inbound lead follow-up speed | CRM timestamp | <5 min for marketing-sourced leads | >60 min = urgent manager alert |

**E. Ramp Trajectory Signals (New Reps Only)**
| Signal | Data Source | Milestone Benchmark | Coaching Alert Threshold |
|--------|-------------|---------------------|--------------------------|
| Discovery call quality score at day 21 | Gong AI Score | ≥65/100 by week 3 | <50 = accelerated coaching mode |
| Days to first closed-won | Salesforce | Historical median: 67 days | >90 days = ramp risk escalation |

---

SECTION 2 — REP PERFORMANCE INTELLIGENCE SCORECARD

**The Revenue Performance Score (RPS) — 0 to 100, Updated Every Sunday:**

**Dimension 1: Pipeline Health (20 pts)**
- Discovery calls held vs. weekly quota: 8 pts (full points at ≥100% of target)
- Pipeline coverage ratio vs. 3.5× benchmark: 7 pts
- New opportunities opened this week: 5 pts

**Dimension 2: Discovery Quality (25 pts)**
- Talk ratio score: 8 pts (40% talk = 8pts; each 5% above 40% = −2 pts; floor at 0)
- MEDDIC element coverage rate across calls this week: 9 pts
- Next-step commitment rate: 8 pts

**Dimension 3: Deal Progression (20 pts)**
- Stage velocity vs. team median: 10 pts
- Economic buyer identification timing: 5 pts
- Buying committee breadth at Stage 3: 5 pts

**Dimension 4: Win Rate Indicators (25 pts)**
- Multithreading score (active contacts per deal): 10 pts
- Champion engagement score across pipeline: 10 pts
- Feature-to-outcome language ratio in demos: 5 pts

**Dimension 5: Forecast Discipline (10 pts)**
- CRM notes quality last 5 calls: 5 pts
- Forecast accuracy last 30 days: 5 pts

**Score Interpretation and Coaching Response:**
- 80–100: Elite performer — surface as peer coaching model; invite to record playbook calls
- 65–79: Solid performer — targeted coaching on 1–2 lowest-scoring dimensions
- 50–64: Developing — structured 30-day improvement plan with weekly manager check-in
- <50: At-risk — daily AI coaching alerts + mandatory manager escalation within 48 hrs

---

SECTION 3 — AUTOMATED COACHING INTERVENTION PLAYBOOK

**AI-Triggered Coaching Messages (Delivered via Slack):**

**Trigger 1: High Talk Ratio + Deal Stall**
- Condition: Rep talk ratio >60% in last 3 discovery calls AND 2+ deals stalled >21 days in Stage 2
- AI Slack Message:
  > "Hey [Rep Name] — coaching note from this week. Your last 3 discovery calls show you talking 63% of the time (benchmark: 38%). This pattern is correlated with slower deal progression — when reps talk less and ask more, prospects reveal budget, urgency, and decision criteria that stall deals in evaluation.
  >
  > I've queued a 4-minute Gong clip from [Top Rep Name]'s Northbrook call from last month — she used silence after 'What's driving urgency this quarter?' for 6 seconds and the CFO disclosed they were losing $190K/year to the problem. Your [CompanyName] call is Thursday. Try opening with that question before sharing any product details. The next step commitment you get will be stronger."

**Trigger 2: Single-Threaded Deal at Stage 3**
- Condition: Opportunity at Stage 3 with only 1 contact in Salesforce for 14+ days
- AI Slack Message:
  > "Deal risk: [Opportunity Name] at $[ACV] is single-threaded at [Contact Name] and has been for 17 days. 71% of single-threaded Stage 3 deals in your segment end in no-decision. Based on [Company]'s size and your ACV, the Economic Buyer is likely the [CFO/VP Finance]. I've drafted a champion email you can send [Contact Name] today to get EB pulled into your next call: [Link to draft]. Two minutes to send. Want me to also pull their finance leadership from LinkedIn?"

**Trigger 3: Missing Economic Buyer by Day 30**
- Condition: Opportunity is 30+ days old, Stage 2+, no Economic Buyer field populated in Salesforce
- AI Slack Message:
  > "[Rep Name], [Opportunity Name] is 31 days old with no Economic Buyer identified. Deals without EB access by day 30 lose at 2.3× the rate of EB-qualified opportunities at your ACV. Based on [Company]'s org size, the EB is most likely the [CFO/CTO/VP Finance]. Here's a question to use in your next call with [Champion Name]: 'If this gets to contract, who needs to sign off on the budget — and have they seen the ROI model yet?' I can add this to your next call brief automatically if you want."

**Trigger 4: Pipeline Coverage Below 2.5× with <60 Days in Quarter**
- Condition: Rep pipeline coverage drops below 2.5× quota with fewer than 60 days remaining in the quarter
- AI Slack Message:
  > "Pipeline alert: Your current coverage is 2.2× vs. the 3.5× needed for quota reliability. You need $[X] in new pipeline this week to stay on track. I've identified 11 ICP-fit accounts in your territory with active G2 and intent signals this week — they're queued in Outreach with personalized first-touch emails ready to launch: [Link]. Also, you have 4 closed-lost opps from Q3 of last year in your territory that went cold due to timing — worth a Voice AI reactivation call through this week."

---

SECTION 4 — TOP-REP BEHAVIORAL BLUEPRINT

**Codifying Elite Performance into a Replicable Playbook:**

AI analyzes the top 20% of reps by win rate (minimum 15 closed deals in trailing 12 months) across the 5-dimension signal model. Output each pattern as a teachable behavior:

**Discovery Call DNA of Elite Performers:**
1. First 8 minutes: Zero product discussion. Pure situation and pain discovery.
2. Signature question sequence: "Walk me through how this problem costs you today" → "What have you already tried to fix it?" → "What happens to your team if this isn't solved by [fiscal quarter]?" → "Who else in the organization feels this most directly?"
3. MEDDIC mapping on call 1: Top reps capture Metrics (quantified pain) in 73% of first calls vs. 31% for bottom quartile. Train reps to always ask "What would fixing this be worth to you in dollars or hours?"
4. Closing discovery: "If we can show you [specific outcome], what would the decision process look like from there?" — top reps book the next step inside discovery 81% of the time vs. 34% average.

**Demo Call DNA of Elite Performers:**
1. Opens with confirmation: "Before I share anything, let me make sure I've got the right focus — what are the 3 outcomes that matter most for this evaluation?" Anchors demo to buyer priorities, not product features.
2. Persona-specific demos: Top reps run 2.4 distinct demo tracks per evaluation vs. 1.1 for the bottom quartile. They tailor messaging to each role's specific metrics.
3. ROI framing throughout: Every capability is tied to a dollar figure or time savings before advancing. "This automation saves the average Controller 4.5 hours per close cycle. At your team size, that's about $85K annually in recovered capacity."
4. Objection handling: Uses "Feel / Felt / Found" for pricing objections. Validates concern before countering. Never argues. Pivots to ROI proof immediately.

**Multithreading Playbook:**
- Opportunity day 1–7: Map all potential stakeholders using LinkedIn + company news. Identify Economic Buyer, Decision Maker, Champion, and Blocker for every deal.
- Day 8–14: Send champion a "stakeholder alignment email" — "I want to make sure everyone who will benefit from this is included in what we show you. Who else should see this on your team?"
- Day 15+: Never advance stage without 2+ active contacts engaged in prior 14 days. If single-threaded, AI sends Trigger 2 alert before next call.

---

SECTION 5 — NEW-REP RAMP ACCELERATION CURRICULUM

**AI-Monitored 90-Day Ramp Program:**

**Days 1–21: Observation Phase**
- Shadow 3 discovery calls/week from top-quartile reps. AI curates highest-quality call clips daily — sorted by next-step conversion rate and MEDDIC coverage score.
- Review AI-annotated transcripts: Gong annotates moments of excellent questioning, objection handling, and next-step commitments with coaching commentary.
- Talk track certification: New rep recites elevator pitch, 3 discovery openers, and 2 objection responses — AI scores via Gong voice analysis. Must score ≥70/100 to advance.
- Milestone gate: Discovery call shadow quality score ≥70 before independent prospecting access.

**Days 22–45: Guided Selling Phase**
- Run discovery calls with manager or senior rep listening (50% of calls minimum).
- AI scores every solo call and delivers coaching debrief via Slack within 2 hours of call end.
- Build first pipeline: Target $[0.75× standard monthly quota target] in new opportunities.
- Milestone gate: Discovery call quality score ≥65/100; next-step commitment rate ≥55%.

**Days 46–90: Independent Selling with AI Guardrails**
- Full independent selling. All 20 behavioral signals active. Deal-level AI alerts running.
- Weekly AI ramp report sent to manager with milestone trajectory vs. historical comp set.
- Target: First closed-won deal by day 90; RPS ≥55 by end of week 12.

**Ramp Acceleration Triggers:**
- Closed deal in <45 days: Fast-track to full quota in month 4 instead of month 6.
- RPS <50 at day 45: Activate extended observation phase with daily manager coaching sessions.
- Discovery score <50 at day 21: Reset timeline — re-run weeks 1–2 with dedicated shadow rep assignment.

---

SECTION 6 — MANAGER COACHING INTELLIGENCE WORKFLOW

**AI-Powered Weekly Cadence for Frontline Sales Managers:**

**Monday: Automated Team Intelligence Brief (delivered 7 AM)**
AI sends manager a brief containing:
- Team RPS scores ranked lowest to highest with week-over-week change indicators
- Deal risk alerts: All opportunities with 2+ simultaneous risk signals
- Pipeline health: Coverage ratio per rep, forecast accuracy trend, call activity trend
- Recommended 1:1 priorities: "This week, coach [Rep A] on economic buyer access and [Rep B] on discovery talk ratio"
- Pre-queued call clips: AI surfaces 2 specific clips per at-risk rep for use in 1:1 coaching

**Wednesday: Deal Intelligence Flash (delivered 8 AM)**
AI surfaces:
- Deals most likely to slip using Clari risk modeling with specific risk explanations
- Highest-leverage deals where manager intervention could shift win probability ≥15%
- Deal of the week: AI nominates the single deal most likely to close with targeted enablement, with a specific recommended action for the manager to take

**Friday: Coaching Effectiveness Loop (delivered 5 PM)**
- Did coached reps improve the target signal this week? (e.g., did Rep A's talk ratio improve from 63% to 48% after Monday's coaching note?)
- Closed deal debrief: AI auto-generates win/loss analysis on every closed opportunity using call data + CRM stage data, ready for manager review in 15 minutes
- Coaching ROI tracker: Improvement delta per rep per coached dimension, trended over 30/60/90 days

**1:1 Facilitation Guide for Managers:**
AI pre-generates 3 coaching conversation starters per rep based on their signal data:
- "I see your talk ratio was 68% this week — walk me through the Thornfield discovery call. What question got the best response?"
- "You have two deals stalled past stage median. Let's look at what EB access looks like in both — who's the economic buyer and when did you last talk to them?"
- "Your next-step rate dropped to 41% this week. Let's roleplay your close for the Morrison demo Thursday."

---

SECTION 7 — TECHNICAL IMPLEMENTATION ARCHITECTURE

**Gong Configuration:**
- Enable AI Trackers for each of the 20 behavioral signals in the Signal Intelligence Architecture
- Create automated Gong Engage alerts routing to per-rep Slack channels based on trigger thresholds
- Configure Gong Deals for deal-level risk scoring correlated with behavioral signal data
- Set Weekly Rep Scorecards to auto-generate every Sunday at 6 AM, delivered to manager + rep simultaneously

**Salesforce Configuration:**
- Custom field: "Rep Performance Score" (populated via Gong API daily)
- Custom field: "Economic Buyer Identified Date" — required field to advance Stage 2 → Stage 3
- Custom object: "AI Coaching Intervention Log" — records every automated coaching message sent per rep with timestamp and trigger condition
- Validation rule: Opportunity cannot advance to Stage 3 without minimum 2 active contacts and Economic Buyer field populated

**Slack Configuration:**
- Dedicated private channel per rep: `#coaching-[repname]` — only rep and manager can view
- Manager intelligence channel: `#sales-intelligence-[teamname]`
- Gong + Salesforce webhooks deliver alerts to the appropriate channels in real time
- Weekly scorecard posted Sunday 7 PM via Slack Bot with direct link to Gong dashboard

**Clari Configuration:**
- Enable AI-suggested forecast categories that incorporate Gong behavioral signal data
- Configure deal risk alerts at opportunity level based on combined signal model
- Build manager dashboard view: team coverage ratio, commit accuracy trend, activity-to-pipeline correlation

**4-Week Implementation Timeline:**
- Week 1: Gong signal tracker configuration + Salesforce custom field deployment
- Week 2: Slack webhook integration + automated alert testing with dummy data
- Week 3: Manager training on coaching intelligence workflow + first live coaching cycle
- Week 4: Baseline RPS measurement for all reps + calibration of alert thresholds to eliminate false positives

---

## Example Input/Output

**Input:**

Company: Vexlar — AI-powered accounts payable automation for mid-market CFOs
ARR: $18M | AEs: 8 | SDRs: 6 | Managers: 2
ICP: CFO, Controller, VP Finance at 200–2,000 employee companies in Manufacturing and Professional Services
ACV: $38K | Sales cycle: 52 days | Avg buying committee: 2.8 stakeholders
Tools: Salesforce, Gong, Outreach, Clari
Overall win rate: 24% | Top 3 reps: 39% | Bottom 3 reps: 11%
New rep ramp to quota: 5.5 months
Primary wins: Fast ROI proof, early CFO access
Primary losses: Single-threaded, status quo preference (no urgency created)

**Output (Excerpt — Automated Coaching Intervention for Rep Jenna Clarke):**

*Signal trigger: Talk ratio 64% across 3 calls + 2 deals stalled >21 days in Stage 2*

> "Hey Jenna — quick AI coaching note from this week. Your last 3 discovery calls had you at 64% talk time (Vexlar benchmark: 38%). I also see two deals — Thornfield Manufacturing and Acosta Professional — both stalled in Stage 2 for 24+ days with no next step locked.
>
> These two patterns are connected. When talk time is high, prospects share less unprompted pain — which makes it harder to create urgency and harder to earn the next meeting.
>
> For your Thornfield call Thursday, try opening with: 'Before we pick up where we left off — what's changed in your AP process in the last two weeks that's creating the most friction?' Then wait. Don't fill the silence. Top reps at Vexlar hold silence 6–9 seconds after open questions.
>
> I queued a 3-minute clip from Marcus's Northbrook call last month — he used this exact question and the CFO disclosed they were losing $180K/year to duplicate payments. That unlocked the deal. Link: [Gong clip].
>
> For Acosta: they haven't replied to your last two emails. Want me to draft a pattern-interrupt email that leads with an AP automation benchmark specific to Professional Services firms their size? I can have it ready in 60 seconds."

**Rep RPS Score This Week: Jenna Clarke**
| Dimension | Score | Benchmark | Gap |
|-----------|-------|-----------|-----|
| Pipeline Health | 16/20 | 18/20 | −2 |
| Discovery Quality | 11/25 | 21/25 | −10 |
| Deal Progression | 13/20 | 17/20 | −4 |
| Win Rate Indicators | 17/25 | 22/25 | −5 |
| Forecast Discipline | 8/10 | 9/10 | −1 |
| **Total RPS** | **65/100** | **87/100** | **−22** |

*Manager recommendation: Focus coaching on Discovery Quality this week. One coaching session on talk ratio + question sequencing could move Jenna 10–15 points in 30 days.*

---

## Success Metrics

**30-Day Targets:**
- All reps have baseline RPS scores established
- 100% of calls ingested and analyzed by AI signal model
- Automated coaching messages generating ≥60% acknowledged-action rate from reps
- Manager 1:1 prep time reduced from 45 min to 15 min per rep per week

**90-Day Targets:**
- New-rep ramp time trending 20%+ faster than pre-program historical baseline
- Company-wide discovery call quality score improved by ≥10 RPS points
- Single-threaded deal rate at Stage 3 reduced by ≥30%
- Economic buyer identified by day 30 rate improved from baseline by ≥20 percentage points

**12-Month Targets:**
- Overall company win rate improved by 8–12 percentage points
- New-rep ramp to first quota attainment reduced by 35–50%
- Bottom-quartile rep RPS improved by ≥20 points (behavior transfer from top reps)
- Coaching ROI: Each 1% win rate improvement at $38K ACV = approximately $[pipeline × 0.01] in additional closed revenue annually

## Related Prompts

- `./AI-Powered-B2B-SaaS-Sales-Enablement-Content-Factory-&-Pipeline-Acceleration-Revenue-Intelligence-Engine.md`
- `./AI-Powered-B2B-SaaS-Sales-Rep-Onboarding-Content-Library-&-Revenue-Ramp-Acceleration-Intelligence-Engine.md`
- `../Sales-Call-Automation/AI-Powered-B2B-Enterprise-Sales-Negotiation-Intelligence-&-Multi-Stakeholder-Deal-Closing-Acceleration-Engine.md`
- `../../05_Analytics-&-Performance/Sales-Enablement-Analytics/AI-Powered-B2B-Sales-Onboarding-Analytics-&-New-Rep-Revenue-Ramp-Intelligence-Engine.md`

## Integration Tips

**Gong:**
- Use Gong's REST API to push rep signal scores to Salesforce daily via Zapier or native Gong CRM sync
- Enable Gong Deals for correlated deal-level behavioral + pipeline risk scoring
- Configure Gong Engage to deliver coaching resources to reps within 2 hours of a trigger-crossing call

**Salesforce:**
- Build a Sales Coaching Lightning App for managers combining RPS scores, deal risk, and coaching log in one view
- Use Salesforce Flow to automatically create coaching tasks when RPS drops below 50 for any rep
- Connect Gong + Salesforce data via Tableau or Salesforce Analytics Studio for quarterly leadership-level coaching ROI reporting

**Slack:**
- Use Zapier, Make, or native Gong/Salesforce Slack apps for real-time alert delivery to rep-specific coaching channels
- Build a Slack Workflow that allows any rep to type `/deal-review [opportunity name]` and receive an instant AI deal risk assessment
- Schedule manager team intelligence brief as a recurring Slack bot message on Monday mornings

**Outreach / Salesloft:**
- Sync rep RPS scores to Outreach custom fields and dynamically adjust prospecting sequence priority for low-pipeline reps
- Create trigger-based sequence enrollment: reps below 2.5× coverage are auto-enrolled in a prospecting reactivation sequence for their top ICP accounts

## Troubleshooting

**Problem: Reps treat AI coaching as surveillance and disengage from the program**
- Fix: Co-design the signal model with reps in a 45-minute working session before launch. Name it a "performance intelligence" system, not a monitoring system. Sequence the rollout so reps see their own scores for 2 weeks before managers get access. If the first 3 automated coaching messages are genuinely useful and non-punitive, adoption builds quickly. Reps who improve their RPS week-over-week should receive positive reinforcement messages alongside the coaching alerts.

**Problem: Gong signal thresholds generate too many false-positive coaching alerts**
- Fix: Start with 5 core signals only — talk ratio, next-step commitment rate, single-thread flag at Stage 3, missing EB by day 30, and stage stall duration. Run for 30 days and calibrate thresholds against actual win/loss outcomes in your specific data before expanding to the full 20-signal model. Adjust thresholds to achieve a 15–20% alert rate across the team (too frequent = noise; too rare = no behavior change).

**Problem: Managers don't know how to translate AI coaching briefs into effective 1:1 conversations**
- Fix: Run a 2-hour manager enablement session before launch. Provide a 1:1 facilitation playbook with 5 scripted conversation starters per signal type. Key principle: the AI surfaces the data, the manager drives the dialogue. "I see your talk ratio was 68% this week — walk me through what happened in the Thornfield call" is more effective than "The AI says you talk too much." Measure manager coaching effectiveness by tracking whether coached signals improve the following week.

## Version History
- v1.0: Initial creation (auto-generated)
