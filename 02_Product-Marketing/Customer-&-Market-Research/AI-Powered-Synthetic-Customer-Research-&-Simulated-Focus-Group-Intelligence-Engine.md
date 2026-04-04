# AI-Powered Synthetic Customer Research & Simulated Focus Group Intelligence Engine

**Difficulty:** Advanced | **Time:** 20-30 min | **Tags:** b2b, research, persona, strategy, automation, product-marketing

## Overview
This prompt deploys AI as a synthetic customer research panel — simulating buyer interviews, focus groups, and message-testing sessions across your ICP segments to validate GTM hypotheses, pricing assumptions, and product messaging before you spend budget on actual market research. Use it when you need fast buyer insight with no recruiter lead time, or when you want to pre-validate a thesis before primary research.

## Quick Copy-Paste Version

You are a B2B buyer research simulation engine. I'll describe my product and target customer, and you'll simulate a focus group of 5 distinct buyers — each with a different title, company size, pain profile, and buying motivation.

My product: [CRM workflow automation platform for mid-market sales teams]
Target ICP: [VP of Sales and RevOps Directors at B2B SaaS companies, 100-500 employees, $10M-$100M ARR]

For each simulated buyer:
1. Assign them a realistic name, title, company, and background (2 sentences)
2. Have them respond to this question as their character would in a real focus group: "What would make you switch your current CRM workflow solution, and what would stop you?"
3. After all 5 respond, write a synthesis section: top 3 switching triggers, top 3 objections, and one surprising insight that contradicts conventional wisdom about this buyer.

Be brutally honest. These buyers are skeptical. Don't make them all love the product.

## Advanced Customizable Version

ROLE: You are a senior qualitative research strategist with 20 years running B2B focus groups and buyer interviews at firms like Forrester, Gartner, and McKinsey. You specialize in simulating realistic buyer panels using synthetic personas constructed from demographic, firmographic, psychographic, and behavioral data.

CONTEXT:
- Product/Service: [DESCRIBE: what it does, who it serves, key differentiators]
- Target ICP: [DESCRIBE: titles, company size, industry, tech stack, business model]
- Research Objective: [CHOOSE ONE OR MORE:
  - Validate messaging and positioning
  - Test pricing sensitivity and willingness-to-pay thresholds
  - Identify top objections and how buyers overcome them
  - Understand category awareness and incumbent solution loyalty
  - Map the buying committee and champion vs. blocker dynamics
  - Stress-test a value proposition before a product launch]
- Research stimulus: [PASTE: the landing page copy, email, pitch deck slide, pricing tier, or concept you want tested]

TASK — PHASE 1: PANEL CONSTRUCTION
Build a synthetic focus group of 6 buyers. Each buyer must represent a distinct archetype within the ICP. For each participant, define:
- Name, title, company name (fictional but realistic), industry vertical
- Company ARR/size, current tech stack, team size they manage
- Primary job-to-be-done (JTBD) in their role — what does winning look like for them?
- Current solution and switching cost (time, political, financial)
- Psychographic profile: are they early adopters, pragmatists, or skeptics?
- Emotional relationship with the problem category (anxious, resigned, actively shopping)

TASK — PHASE 2: MODERATED DISCUSSION
As a skilled moderator, run the following sequence with your panel. Each participant must respond in first person, in character, with realistic skepticism, jargon, and emotional subtext. Responses should be 3-5 sentences each. No participant should sound identical.

Round 1 — Awareness: "When did you last feel real pain around [PROBLEM AREA]? Walk me through what happened."
Round 2 — Status quo: "Why haven't you solved it yet? What's kept you on your current approach?"
Round 3 — Stimulus reaction: [Show them the research stimulus you defined above.] "What's your gut reaction — and what would you need to see to believe it?"
Round 4 — Buying process: "If you were going to move forward with something like this, who else would be in the room? What would kill it internally?"
Round 5 — Pricing / value: "What would fair look like for this? Where does it become a no-brainer vs. where does it feel like a risk?"

TASK — PHASE 3: RESEARCH SYNTHESIS REPORT
After the simulated discussion, write a structured research memo:

**Executive Summary (3 bullets):** The 3 most important findings a CMO or VP Product needs to act on immediately.

**Jobs-to-be-Done Map:** The functional, emotional, and social jobs this buyer is hiring your solution to do — ranked by priority.

**Messaging Resonance Score:** Rate each key message in the stimulus on a 1-5 scale with a one-line rationale from the panel's perspective.

**Top 5 Objections (with counter-strategies):** Each objection stated as the buyer would say it, followed by the most effective reframe.

**Pricing Sensitivity Bands:** Based on panel reactions, define: "no-brainer zone," "negotiation zone," and "walk-away zone" with rationale.

**Surprising Insight:** One finding that contradicts the most common assumption held by your marketing or product team about this buyer.

**Recommended Next Actions:** 3 specific changes to messaging, positioning, or go-to-market motion based on this research.

CONSTRAINTS:
- Buyers must disagree with each other at least twice during the discussion — this is a real panel, not a consensus machine
- At least one buyer must be a strong skeptic who never fully converts
- Surface real industry terminology, not generic business-speak
- Flag anywhere the research stimulus uses language buyers wouldn't use about their own problem
- Do not hedge findings with "this is simulated" disclaimers — present as professional research output

OUTPUT FORMAT: Structured markdown with headers. The panel discussion should read like a real transcript excerpt. The synthesis should read like a deliverable you'd present to the CMO.

## Example Input/Output

**Input Example:**
- Product: Pipeform — an AI-native CRM workflow automation layer that sits on top of Salesforce, auto-populating deal fields, generating follow-up emails, and flagging stale opportunities
- ICP: RevOps Directors and VP Sales at B2B SaaS companies, 150-600 employees, $15M-$80M ARR
- Research objective: Validate messaging and test pricing sensitivity for a $2,500/month team plan (up to 25 reps)
- Stimulus: "Pipeform eliminates 3 hours of Salesforce admin per rep per week. Your team keeps their existing CRM. Your pipeline stays accurate. Your forecast becomes trustworthy."

**Output Example (excerpt):**

*Panel Participant 2 — Marcus Webb, Director of RevOps, Cloudnine Analytics, 220 employees, $28M ARR:*

"Three hours per rep sounds like a press release number — I'd want to see the methodology. That said, our biggest Salesforce problem isn't time, it's data quality. Reps update fields wrong or not at all, and by the time I'm pulling forecast reports, I'm basically doing archaeological dig work. If Pipeform actually fixes field hygiene without adding another admin burden on my team, that's interesting. The 'sits on top of Salesforce' framing makes me nervous about integration complexity — we had a bad experience with a Salesloft configuration last year."

*Synthesis — Messaging Resonance Score:*
| Message | Score | Panel Rationale |
|---|---|---|
| "Eliminates 3 hours of admin per rep" | 2/5 | Buyers skeptical of generic time-save claims; want specificity on which tasks |
| "Your team keeps their existing CRM" | 4/5 | Strong resonance — switching cost fear is high; this is a relief |
| "Pipeline stays accurate" | 5/5 | The #1 pain for RevOps; this is the actual JTBD |
| "Forecast becomes trustworthy" | 4/5 | Emotionally resonant for VP Sales, less so for RevOps who own the forecast process |

*Surprising Insight:* Buyers don't frame this as a productivity problem — they frame it as a credibility problem. Inaccurate pipeline data makes RevOps leaders look unreliable to the CFO. The emotional job-to-be-done is "help me stop getting surprised in board meetings," not "save my reps time."

## Success Metrics
- Panel participants have distinct, believable voices with realistic disagreements
- Objections reflect actual buyer language, not generic concerns
- The surprising insight contradicts at least one assumption held by your team
- Messaging scores reveal actionable gaps, not just validation
- The output is presentation-ready without editing — usable directly in a research readout
- At least one round of discussion surfaces a buying committee dynamic or internal politics you hadn't anticipated

## Related Prompts
- [ICP Discovery Engine](./ICP-Discovery-Engine.md)
- [Voice of Customer Analysis](./Voice-of-Customer-Analysis.md)
- [Jobs-To-Be-Done Research & Messaging Translation Engine](../Positioning-&-Messaging/Jobs-To-Be-Done-Research-&-Messaging-Translation-Engine.md)
- [Win-Loss Analysis Automation](./Win-Loss-Analysis-Automation.md)

## Integration Tips
- **Notion:** Paste synthesis report directly into a Product Marketing workspace page; tag sections with persona names for team reference
- **HubSpot:** Use the "Top 5 Objections" output to build Sales Sequences and chatbot objection-handling scripts
- **Salesforce:** Map "Pricing Sensitivity Bands" to deal stages and qualification criteria in opportunity records
- **Dovetail / Condens:** Import transcript excerpt as a synthetic research note for qualitative tagging alongside real interview data
- **Google Slides:** Use Messaging Resonance Score table directly in a GTM readout deck — no reformatting required
- **Zapier / Make:** Trigger this prompt automatically when a new ICP definition is created in Notion or Airtable, generating a synthetic research report as a first-pass validation step before scheduling real customer interviews

## Troubleshooting
- **Problem:** All 6 buyers sound the same — the panel feels like one voice.
  **Solution:** Add explicit instruction: "Each participant must come from a different stage of category awareness — one actively evaluating, one satisfied with status quo, one unaware the problem is solvable." Forcing awareness-stage diversity creates natural disagreement.

- **Problem:** The messaging stimulus gets broadly positive reactions with no critical feedback.
  **Solution:** Add: "At least 2 of the 6 buyers must find one claim in the stimulus unbelievable or misleading. Surface the specific word or phrase that triggered skepticism." This prevents the model from defaulting to politely positive panel responses.

- **Problem:** The synthesis reads as vague or generic — the "surprising insight" is obvious.
  **Solution:** Prime the model with: "The surprising insight must contradict one of these specific assumptions our team holds: [list 2-3 internal beliefs about the buyer]." Anchoring to actual team assumptions forces the model to generate genuinely useful reframes rather than generic observations.

## Version History
- v1.0: Initial creation (auto-generated)
