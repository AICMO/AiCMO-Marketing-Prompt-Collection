# AI-Powered B2B SaaS Real-Time Social Listening Intelligence & Prospect Engagement Trigger Revenue Intelligence Engine

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** social-selling, linkedin, social-listening, intent-signals, b2b, pipeline, automation, demand-gen, prospect-engagement

## Overview

This prompt builds a fully autonomous, AI-powered social listening engine that monitors your target prospects' LinkedIn (and community) activity in real-time, classifies their posts and comments by purchase intent strength, and generates hyper-contextual engagement responses that start authentic conversations leading to pipeline. Use it when you want to replace cold outreach with warm, signal-triggered social selling — catching buyers exactly when they're expressing pain, evaluating solutions, or ready for a conversation.

## Quick Copy-Paste Version

You are a senior B2B social selling strategist with deep expertise in AI-powered prospect monitoring and intent-based engagement. My company sells [PRODUCT/CATEGORY] to [ICP: job titles at company types, e.g., VP Operations at mid-market manufacturing companies].

Build a complete real-time social listening and prospect engagement system for LinkedIn that includes:

1. SIGNAL LIBRARY — 20 types of LinkedIn activity from prospects that indicate buying intent. For each signal, specify:
   - Exact signal description (e.g., "prospect posts asking for vendor recommendations in our category")
   - Intent tier: T1 = Active Buying (respond within 2 hours), T2 = Problem Aware (respond within 24 hours), T3 = Category Interest (engage within 72 hours)
   - Recommended engagement type: Public comment, Reaction only, DM, Share with note

2. MONITORING SETUP — Define the exact search queries and alert configurations for LinkedIn Sales Navigator and social monitoring tools to surface these signals automatically. Include:
   - LinkedIn Sales Navigator Boolean keyword strings for tracking prospect posts
   - 10 specific hashtags to monitor in the target category
   - 5 thought leader accounts whose comment sections are hunting grounds for prospects
   - Recommended monitoring cadence by signal tier

3. ENGAGEMENT RESPONSE PLAYBOOK — For the top 8 signal types, write the exact engagement response:
   - Public comment (under 150 characters) that adds genuine value without pitching
   - Follow-up DM if they react positively to your comment (within 48 hours)
   - Escalation message if they engage but don't respond to DM (Day 7)

4. ESCALATION LOGIC — Define the precise rules for when to escalate from public engagement to direct message to meeting request:
   - Engagement threshold (e.g., 2 comments from you + 1 reaction from them = DM trigger)
   - DM-to-meeting sequence: 3-message sequence with exact copy
   - Disqualification rules: when to stop engaging (no reciprocal action after 4 touches)

5. TRACKING FRAMEWORK — Design a simple CRM tagging and pipeline attribution system:
   - 5 LinkedIn engagement activity types to log in CRM
   - Pipeline stage entry criteria for social-sourced leads
   - Weekly metrics to track: impressions, comment replies, DM acceptance rate, meetings booked per 100 signals

Output: A complete, ready-to-deploy social listening and engagement playbook, with all copy written, monitoring queries specified, and tracking fields defined. No manual steps — every action should be completable by an AI agent or SDR in under 5 minutes per engagement.

## Advanced Customizable Version

### ROLE & CONTEXT
You are an elite B2B revenue intelligence architect specializing in real-time social signal capture and AI-powered buyer engagement. You have engineered social listening systems that generate 15–30% of pipeline for B2B SaaS companies by catching prospects at the moment of expressed pain — before they ever enter a vendor selection process. You apply behavioral economics, social proof psychology, and the "reciprocity principle" to convert LinkedIn engagement into warm conversations without ever making a cold ask. You think in systems: every signal has a defined response, every response has an escalation rule, and every escalation has a conversion metric.

### COMPANY CONTEXT
Company name: [e.g., DataBridge AI]
Product category: [e.g., AI-powered revenue operations intelligence / cybersecurity posture management]
Value proposition in one sentence: [e.g., We help RevOps teams eliminate forecast blindspots using AI-powered deal signal analysis]
ICP Primary: [e.g., VP Revenue Operations and RevOps Directors at B2B SaaS companies, 150–1,500 employees, Series B–D]
ICP Secondary: [e.g., VP Sales and CROs at same companies who own the problem]
Average deal size: [$ARR range, e.g., $35K–$120K ARR]
Average sales cycle: [e.g., 60–90 days]
Current CRM: [HubSpot / Salesforce]
Sales engagement tool: [Outreach / Salesloft / Apollo / HubSpot Sequences]
LinkedIn Sales Navigator tier: [Core / Advanced / Advanced Plus]
Additional monitoring tools available: [e.g., Mention, Brand24, Sprout Social, Kaspr, Phantombuster]
Team executing this: [e.g., 2 SDRs + 1 marketing manager / fully automated via AI agent]

### SIGNAL INTELLIGENCE ARCHITECTURE

**Section 1 — Master Signal Library (25 Signal Types)**

For each of these 25 LinkedIn activity patterns from target prospects, provide:
- **Signal Name** (descriptive label)
- **Signal Description** (exactly what the prospect posted/commented/did)
- **Intent Tier**: T1 (Active Evaluation — respond within 2 hours), T2 (Problem Aware — respond within 24 hours), T3 (Category Interest — respond within 72 hours), T4 (Passive Monitoring — log and watch)
- **Psychological State** (what's driving this post — fear, ambition, frustration, curiosity, social proof seeking)
- **Engagement Type**: Public Comment | Reaction + Comment | DM | Tag in your own post | Share with insight
- **Disqualification Check**: one question to verify they're ICP before engaging

Signal categories to cover across all 25:
- Direct vendor request signals (T1): "Anyone have experience with [your category]?", "Looking for recommendations for [problem you solve]"
- Problem expression signals (T1-T2): Posts venting about a pain your product solves, asking for advice on solving a specific problem
- Competitor mention signals (T1): Commenting on a competitor's post, sharing competitor content, criticizing a competitor
- Category content engagement (T2-T3): Liking/commenting on category thought leader posts, sharing industry reports on your topic
- Career/org change signals (T2): New job title, new company, team expansion in relevant function
- Conference and event signals (T2-T3): Attending events in your space, posting about industry trends
- Budget/initiative signals (T1-T2): Mentions of digital transformation, tech stack consolidation, cost reduction, headcount freeze
- Passive browsing indicators (T3-T4): Profile views from ICP accounts, engagement with your company page or competitor page

**Section 2 — Monitoring Infrastructure Setup**

Design the complete technical monitoring setup:

**LinkedIn Sales Navigator Alerts:**
- 5 Boolean keyword alert strings for the LinkedIn search engine to track prospect posts (use AND/OR/NOT operators, quoted phrases)
- Saved search configuration: how to set up prospect account lists with post tracking enabled
- News and update alert categories to enable per account
- Recommended alert frequency by tier (T1: real-time, T2: daily digest, T3: weekly)

**Keyword Monitoring (for tools like Mention, Brand24, or native LinkedIn hashtag follows):**
- 15 specific hashtags to follow, with their signal relevance rated High/Medium/Low
- 10 exact phrases to create keyword alerts for (including pain-language phrases your ICP uses)
- 5 competitor brand names + product names to monitor
- 8 thought leader accounts where ICP prospects frequently engage in comments

**Community Monitoring (Slack, Reddit, industry forums):**
- 3 Slack communities where your ICP congregates, with monitoring approach for each
- 2 Reddit communities relevant to your category
- Recommended monitoring cadence: daily check-in schedule by platform

**Automation Layer:**
- Zapier/Make workflow: how to pipe Sales Navigator alerts → Slack notification → CRM activity log
- Phantombuster or Clay sequence: automated prospect post scraping and alert routing
- AI agent prompt: a reusable prompt for your AI assistant to classify incoming signals by tier and draft initial engagement copy on demand

**Section 3 — Engagement Response Playbook (for the top 12 signals)**

For each of the 12 highest-value signal types, produce a complete engagement kit:

**Signal: [Name]**
- Trigger: [Exact behavioral description]
- Intent Tier: [T1/T2/T3]
- Verification question: [Quick ICP check before engaging]

**Public Comment Response (if applicable):**
- [Exact comment text, under 175 characters, adds genuine insight, no pitch, ends with either a question or a thought-provoking statement]
- Tone: [Expert validation / Contrarian insight / Data enrichment / Empathetic acknowledgment]
- Avoid: [What NOT to say to avoid appearing like a vendor]

**Reaction-Only Protocol (if public comment would be premature):**
- [When to use Insightful/Support reactions vs. comment]
- Follow-up window: [Hours until next touch if they react back]

**DM Trigger Conditions:**
- [Specific engagement threshold that justifies moving to DM, e.g., "They replied to my comment + liked 2+ of my posts"]
- DM Message 1 (initial reach): [Exact text, under 300 characters, references specific post content, no ask]
- DM Message 2 (value add, Day 5): [Exact text, shares a relevant resource, still no meeting ask]
- DM Message 3 (soft ask, Day 12): [Exact text, connects their problem to your category, proposes a low-friction next step]
- Break-up message (Day 21 if no response): [Graceful exit, leaves door open]

**Section 4 — Escalation Decision Engine**

Define precise, binary escalation rules that an AI agent or SDR can execute without judgment calls:

**Public Engagement → DM Escalation Rules:**
| Engagement Pattern | Escalation Trigger | Wait Time Before DM |
|---|---|---|
| Prospect replied to your comment | Yes — immediate DM | 4 hours |
| Prospect liked your comment | Yes — if 2+ likes over 7 days | 48 hours |
| Prospect viewed your profile after your comment | Yes | 24 hours |
| Prospect posted a T1 signal again within 7 days | Yes — urgency escalation | 2 hours |
| No reaction to 3 comments over 14 days | No — continue T3 monitoring | — |

**DM → Meeting Escalation Rules:**
- Reply rate: any substantive reply to DM 1 or 2 triggers meeting ask
- Engagement signal: if they like/react to DM 1, send DM 2 within 24 hours
- Meeting ask timing: never before DM 2 (unless they explicitly ask about your product)
- Meeting ask framing: [Exact framing that positions it as value-exchange, not a sales pitch]

**Disqualification Rules (stop sequence and remove from active monitoring):**
- Zero reciprocal engagement after 4 touches over 30 days
- Profile indicates they're a competitor, researcher, or journalist
- Company falls outside ICP (wrong size, wrong industry, wrong buying stage)
- Prospect explicitly disengages (removes connection, says not interested)

**Section 5 — AI Agent Execution Framework**

Provide a complete prompt system for an AI agent to execute this program autonomously:

**Daily Briefing Prompt** (AI analyzes overnight signals and produces a prioritized engagement queue):
[Complete AI agent prompt that ingests: list of saved prospect accounts, their LinkedIn activity from the last 24 hours, engagement history with each, and outputs: ranked engagement queue by intent tier, pre-drafted comment and DM responses, escalation flags for accounts crossing threshold]

**On-Demand Engagement Drafter** (for any individual signal):
[Complete AI agent prompt that takes: prospect name, company, title, exact post text, our product category, and outputs: verified ICP check, signal tier classification, recommended engagement type, 3 comment variations ranked by quality, 1 DM draft if escalation is warranted]

**Weekly Intelligence Digest Prompt**:
[AI agent prompt that analyzes the week's social engagement activity and outputs: top 10 accounts showing increased buying signals, 5 accounts to deprioritize, suggested adjustments to keyword monitoring strings based on new language patterns observed in prospect posts]

**Section 6 — CRM Tracking & Pipeline Attribution**

Design the complete measurement framework:

**CRM Activity Types to Log** (create these custom activity types):
1. LinkedIn Signal Detected — [required fields: signal type, intent tier, prospect post URL, date detected]
2. LinkedIn Comment Posted — [required fields: comment text, prospect reaction Y/N, time to reaction]
3. LinkedIn DM Sent — [required fields: message number (1/2/3), send date, reply received Y/N]
4. LinkedIn DM Reply Received — [required fields: reply sentiment, next action triggered]
5. Social-Sourced Meeting Booked — [required fields: signal-to-meeting days, total touches, first touch type]

**Lead Source Attribution Rules:**
- Social Listening Sourced: prospect entered pipeline within 90 days of first LinkedIn signal detection
- Social Assisted: existing pipeline deal had 3+ LinkedIn engagement touches within 60 days of close
- First-Touch Credit: assign to social listening if signal detection preceded all other touches

**Weekly Metrics Dashboard:**
- Signals detected by tier (T1/T2/T3/T4)
- Comments posted vs. prospect reactions received (reaction rate %)
- DMs sent vs. replies received (DM acceptance rate %)
- Meetings booked from social listening (per 100 T1 signals)
- Pipeline created from social listening ($ARR, # opportunities)
- Average signal-to-meeting days by tier
- Top 5 signal types generating the highest meeting conversion rate

**Monthly Review Prompt:**
[AI prompt that takes the monthly metrics dashboard and outputs: which signal types are overperforming, which engagement scripts have the highest reply rates, recommended changes to monitoring keywords, and 3 A/B test ideas for improving DM conversion]

### PERSONA-SPECIFIC ENGAGEMENT VARIATIONS

For each of the 3 primary ICP personas, customize the engagement approach:

**Persona A — [Economic Buyer, e.g., VP Revenue Operations]**
- LinkedIn behavior patterns: what they typically post about, who they follow, what content they share
- Pain signals specific to this persona: 5 exact post types that indicate they're in-market
- Engagement tone: [e.g., peer-to-peer strategic, not vendor-to-buyer]
- Proof points that resonate in public comments: [e.g., benchmark data, peer case studies]
- DM hook that works: [first DM line that gets replies from this persona]

**Persona B — [Technical Champion, e.g., RevOps Manager]**
- LinkedIn behavior patterns: forums they participate in, questions they ask, content they create
- Pain signals specific to this persona: 5 exact post types indicating evaluation mode
- Engagement tone: [e.g., practitioner-to-practitioner, tactical and specific]
- Proof points that resonate: [e.g., integration specifics, workflow efficiency data]
- DM hook that works: [first DM line that gets replies from this persona]

**Persona C — [Executive Sponsor, e.g., CRO / VP Sales]**
- LinkedIn behavior patterns: what they amplify, what they create, where they appear in comments
- Pain signals specific to this persona: 5 exact post types indicating awareness phase
- Engagement tone: [e.g., board-level outcomes, revenue impact, competitive positioning]
- Proof points that resonate: [e.g., pipeline acceleration data, win rate improvement]
- DM hook that works: [first DM line that gets replies from this persona]

## Example Input/Output

**Input Example:**

Company: Nexora (AI-powered contract intelligence for legal and procurement teams)
ICP: VP Legal, General Counsel, and Chief Procurement Officers at mid-market B2B companies (250–2,500 employees)
ACV: $48K–$160K ARR
Sales cycle: 75–110 days
CRM: Salesforce
Sales engagement: Salesloft
LinkedIn Sales Navigator: Advanced Plus

**Output Example (Signal Library — T1 Signals, 3 of 12):**

---

**T1 Signal #1: Direct Vendor Request**
- Signal: Prospect posts "Anyone have recommendations for contract management software? We've outgrown our current setup."
- Intent Tier: T1 — respond within 90 minutes
- Psychological state: Urgency + social proof seeking — they're actively evaluating and want peer validation
- ICP verification: Check profile — do they have "Legal" or "Procurement" in title + company has 250+ employees?
- Engagement type: Public Comment (always before DM — builds context for DM later)
- Comment: "Several GC teams we've worked with hit this same inflection point around 1,500+ contracts/year. Key criteria they found mattered most: AI clause extraction, Salesforce/CRM sync, and audit trail depth. Happy to share a comparison framework if helpful — just DM me."
- Tone: Expert validation, peer voice, ends with low-friction offer
- DM trigger: If they reply to comment OR react positively → DM within 4 hours
- DM Message 1: "Hi [Name] — saw your post on contract software. We've helped 3 procurement teams at [their industry]-stage companies go from spreadsheet chaos to full contract intelligence in under 8 weeks. No pitch — genuinely happy to share the evaluation framework they used if that would save you time. Worth a quick look?"

---

**T1 Signal #2: Competitor Frustration**
- Signal: Prospect comments on a competitor's LinkedIn post: "We've been a customer for 2 years and the audit trail feature still doesn't work properly. Anyone else seeing this?"
- Intent Tier: T1 — respond within 2 hours
- Psychological state: Active dissatisfaction — they are in the consideration gap between current vendor and alternative
- ICP verification: Does their role involve contract oversight at an ICP-size company?
- Engagement type: Public Comment (on the competitor's post — high visibility)
- Comment: "Audit trail gaps are one of the most common reasons legal teams switch from [competitor category]. If you're evaluating alternatives, the thing that usually matters most at the [industry] scale is [specific technical capability]. Happy to share what best-in-class looks like — no agenda, just helpful context."
- Tone: Empathetic, expert, non-salesy acknowledgment of their frustration
- DO NOT: Mention your company name in the comment — let them come to you
- DM trigger: Any reply or reaction to your comment → immediate DM
- DM Message 1: "Hi [Name] — jumped in on that post because the audit trail issue is something I've helped a few teams navigate. Genuinely not trying to sell you — but if you're thinking about alternatives, I'd rather give you an honest picture of the landscape than let you discover it through 6 vendor demos. 30-minute market map call?"

---

**T1 Signal #3: Budget Signal — Tech Stack Consolidation**
- Signal: Prospect posts: "Q3 initiative: reducing our SaaS spend by 20% through consolidation. Painful but necessary. Anyone done this successfully?"
- Intent Tier: T1 — respond within 4 hours (consolidation creates buying opportunity if you replace 2+ tools)
- Psychological state: Budget pressure + seeking peer validation + solution shopping
- ICP verification: Is their role one that owns contract or legal ops budget? Would consolidation affect their contract/procurement stack?
- Engagement type: Public Comment + share your own related post within 24 hours
- Comment: "We've seen this pattern a lot in the past 6 months — the consolidation pain is real, but teams who approach it strategically actually end up with better tooling AND lower spend. Two criteria that usually predict success: (1) prioritize platforms with native integrations over point solutions, (2) measure per-contract cost, not per-seat cost. Let me know if a benchmarking call would help."
- DM trigger: Reply to comment OR 2+ reactions within 48 hours → DM
- DM Message 1: "Hi [Name] — saw your consolidation post. We've helped 4 legal/procurement teams cut their contract tooling spend by 30–40% while actually improving output quality. I put together a 1-page consolidation framework specifically for teams your size — happy to send it over. Useful?"

---

**Output Example (Weekly Metrics Dashboard — Week 3):**

| Metric | Week 3 Actual | Target | Status |
|---|---|---|---|
| T1 signals detected | 14 | 10+ | ✅ |
| T2 signals detected | 31 | 25+ | ✅ |
| Comments posted | 22 | 20+ | ✅ |
| Prospect reactions to comments | 9 | 30%+ rate | ✅ (41%) |
| DMs sent | 7 | — | — |
| DM replies received | 3 | 35%+ rate | ✅ (43%) |
| Meetings booked | 2 | 1–3/week | ✅ |
| Pipeline created | $96K ARR | — | — |
| Avg. signal-to-meeting days | 11 days | <21 days | ✅ |

**Top-performing signal type this week:** Competitor frustration comment (100% DM reply rate, 2 meetings booked)
**Underperforming signal type:** Budget/consolidation posts (0 DM replies — try revised DM Message 1 next week)

## Success Metrics

- **Signal-to-meeting conversion rate**: target 8–15% for T1 signals (8–15 meetings per 100 T1 signals detected)
- **DM acceptance rate**: 30–50% reply rate on Message 1 (benchmark: cold email = 5–12%)
- **Comment reaction rate**: 25–40% of targeted comments receive at minimum a reaction from the prospect
- **Pipeline attribution**: 15–25% of new pipeline attributed to social listening within 6 months of program launch
- **Signal-to-meeting cycle**: T1 signals should convert to meetings within 7–21 days on average
- **Social selling index (SSI) impact**: your team's LinkedIn SSI scores should increase 10–15 points within 60 days
- **Cost per meeting**: social listening meetings should cost 60–80% less than cold outreach meetings (no ad spend, minimal SDR time per signal if AI-assisted)
- **Pipeline velocity**: social-sourced opportunities should close 20–35% faster due to pre-existing relationship and demonstrated expertise

## Related Prompts

- [LinkedIn Social Selling Program Architecture & Revenue Team Pipeline Intelligence Engine](./AI-Powered-B2B-SaaS-LinkedIn-Social-Selling-Program-Architecture-&-Revenue-Team-Pipeline-Intelligence-Engine.md) — build the overall program framework that this listening engine feeds
- [Trigger Event Signal-Based Social Selling & Buyer Intent Pipeline Intelligence Engine](./AI-Powered-B2B-SaaS-Trigger-Event-Signal-Based-Social-Selling-&-Buyer-Intent-Pipeline-Intelligence-Engine.md) — complement real-time listening with proactive trigger-event outreach
- [Dark Social Community Selling & Off-LinkedIn Pipeline Intelligence Engine](./AI-Powered-B2B-SaaS-Dark-Social-Community-Selling-&-Off-LinkedIn-Pipeline-Intelligence-Engine.md) — extend social listening beyond LinkedIn into Slack and industry communities
- [ABM Intent Data Activation & Buying Signal Prioritization Engine](../Account-Based-Marketing/ABM-Intent-Data-Activation-&-Buying-Signal-Prioritization-Engine.md) — combine social signals with third-party intent data for full-coverage account prioritization

## Integration Tips

**LinkedIn Sales Navigator:**
- Enable "Account News" and "Lead News" alerts for your saved prospect lists — these surface posts, job changes, and company news automatically
- Use Advanced Plus "TeamLink" to identify shared connections with prospects before engaging — warm introduction context dramatically increases DM reply rates
- Build a "Social Listening Queue" saved search with keyword alerts set to daily email digest for T2/T3 signals

**HubSpot Integration:**
- Create a custom activity type "LinkedIn Signal Detected" and log all T1/T2 signals as activities on the contact record
- Use HubSpot Sequences to create a "Social Listening Follow-Up" track that triggers after a DM reply is received — automates reminder tasks and next-touch scheduling
- Add a custom contact property "Social Selling Stage" (values: Signal Detected → Comment Engaged → DM Accepted → Meeting Booked) for pipeline reporting

**Salesforce Integration:**
- Build a custom object "Social Signal" linked to Contacts and Opportunities — log signal type, tier, date, and engagement outcome
- Create a Salesforce report "Social Signal Pipeline" that tracks opportunities where a Social Signal activity preceded opportunity creation within 90 days
- Use Einstein Activity Capture to correlate LinkedIn InMail activity with Salesforce contact records for attribution

**Automation via Zapier/Make:**
- Zap 1: LinkedIn Sales Navigator alert email → parse signal details → create HubSpot/Salesforce activity + Slack notification to assigned SDR
- Zap 2: Prospect replies to LinkedIn DM (detected via Dux-Soup or Phantombuster monitoring) → trigger Slack alert with context + recommended next action
- Zap 3: Meeting booked (Calendly/Chili Piper) → auto-tag opportunity source as "Social Listening" + log full engagement history as opportunity notes

**Clay Integration:**
- Build a Clay table that ingests your ICP account list → enriches with LinkedIn activity data via Phantombuster → auto-scores accounts by signal tier weekly
- Use Clay's AI column to auto-draft personalized comment responses for T1 signals → push to Slack for 1-click approval before posting

**Slack Workflow:**
- Create a "#social-signals" Slack channel where all T1 signal alerts are routed
- Use Slack Workflow Builder to prompt the SDR to mark each signal as "Engaged," "Skipped," or "Watch" — feeds your weekly conversion funnel

## Troubleshooting

**Problem: Low comment reaction rate — prospects aren't engaging with your comments.**
Solution: Your comments are likely too long, too generic, or subtly pitchy. Apply the "3-second test": read your comment aloud — if a stranger would think you're selling something, rewrite it. Best-performing comments are under 100 words, add one specific data point or framework, and end with a genuine question. Avoid: "Great post!", anything mentioning your company, and calls-to-action like "Check out our platform."

**Problem: High DM send rate, very low reply rate (below 20%).**
Solution: You're DMing too early or your Message 1 is asking for too much. The #1 DM mistake is sending a meeting ask without sufficient pre-established credibility. Enforce a minimum of 2 prior public engagements (comment or share) before any DM. Also verify your Message 1 offers something specific and low-friction (a framework, a benchmark, a resource) — not a call to learn about your product. A/B test 3 different Message 1 variations on equal signal batches and measure reply rate.

**Problem: Too many signals to action — team is overwhelmed by the volume.**
Solution: You're over-indexing on T3/T4 signals. Implement strict tier discipline: T1 signals only are actioned by SDRs within the defined SLA; T2 signals go into a weekly batch review; T3 signals are AI-auto-monitored with no human time invested unless they upgrade to T2. If T1 volume is still too high, tighten your keyword alert strings to require 2+ qualifying terms (e.g., post must mention both a pain-point phrase AND a role/function indicator to qualify as T1). For teams with true volume at scale, implement an AI agent layer that auto-classifies and auto-drafts all responses for human 1-click approval.

## Version History
- v1.0: Initial creation (auto-generated)
