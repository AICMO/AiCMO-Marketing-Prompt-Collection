# Customer Reference Program & Peer Validation Intelligence Engine - Build, Match, and Scale Enterprise Reference Selling

**Difficulty:** Advanced | **Time:** 25 min | **Tags:** customer-reference-program, peer-selling, enterprise-sales, social-proof, b2b-saas, customer-advocacy, deal-acceleration, win-rate

## Overview
Build a systematic customer reference program that matches the right advocate to the right prospect at the right moment in the sales cycle, prepares references for calls, prevents reference burnout, and tracks program ROI. Use this when your enterprise sales cycles exceed $50K ACV and buyers demand peer validation before signing — transforming ad-hoc reference requests into a structured competitive advantage.

## Quick Copy-Paste Version

You are a senior enterprise sales and customer marketing strategist specializing in customer reference programs for B2B SaaS companies.

My business context:
- Company: [Your Company Name]
- Product: [What you sell, e.g., enterprise data governance platform]
- Deal size range: [e.g., $75K–$400K ACV]
- Sales cycle length: [e.g., 4–9 months]
- Active customer base: [e.g., 210 accounts]
- CRM: [Salesforce / HubSpot / other]
- CS platform: [Gainsight / ChurnZero / Totango / spreadsheet]
- Industries served: [e.g., Financial Services, Healthcare, Manufacturing]
- Current reference process: [ad-hoc / no formal program / basic list]

Deliver a complete customer reference program system with these components:

1. REFERENCE POOL QUALIFICATION CRITERIA
   - 8 signals that identify a customer as reference-ready (health score, NPS, product adoption depth, relationship tenure, executive sponsor access, deal similarity)
   - Scoring rubric: assign each signal a weight and define a Reference Readiness Score (RRS) threshold
   - Tier the reference pool: Tier 1 (executive references, any prospect), Tier 2 (practitioner references, matched use case), Tier 3 (written/video only, no live calls)
   - Red flags: who should NEVER be used as a reference and why

2. REFERENCE MATCHING ENGINE
   - Matching matrix: map reference attributes (industry, company size, tech stack, use case, buyer persona, geography, deal complexity) to prospect attributes
   - Prioritization logic when multiple matches exist: deal size weighting, reference freshness, call frequency limits
   - When to use a reference vs. a case study vs. an analyst quote (decision tree)
   - Reference gap analysis: which ICP segments lack reference coverage and how to fill gaps

3. REFERENCE RECRUITMENT CAMPAIGN
   - 3-touch email sequence to recruit customers into the program (subject lines + full body copy, production-ready)
   - What to offer references: recognition tiers, co-marketing benefits, product roadmap access, executive access
   - Reference program charter: what you're asking them to do, time commitment, how you'll protect them from burnout
   - CSM talk track: how to ask during a QBR or health check without making it feel transactional

4. REFERENCE PREPARATION PLAYBOOK
   - Pre-call briefing template: send to reference 48 hours before each call (prospect background, deal stage, key concerns, talking points to emphasize, topics to avoid)
   - Reference coaching guide: how to structure their story (Challenge → Evaluation → Decision → Results — with specific numbers)
   - 5 questions the prospect is most likely to ask — with suggested answers for each
   - What to tell the reference about deal confidentiality and competitive sensitivity

5. REFERENCE CALL FACILITATION
   - Reference call agenda template (30-min and 60-min formats)
   - Opening script for AE to set context for both parties
   - 3 questions the AE should seed to guide the conversation toward your differentiation
   - Post-call debrief template: what to capture from the reference and the prospect within 24 hours

6. REFERENCE BURNOUT PREVENTION SYSTEM
   - Maximum call frequency by reference tier (calls per quarter)
   - Rotation logic: how to track and limit reference usage in CRM
   - Reference appreciation playbook: what to do after each call (thank-you, outcome share, recognition)
   - Annual reference refresh: how to re-qualify, retire, and recruit references each year

7. PROGRAM ROI DASHBOARD
   - 10 metrics to track weekly and monthly (reference call volume, win rate lift, deal velocity impact, deal size delta, reference satisfaction score, pool coverage ratio, recruitment conversion rate, burnout rate, gap coverage %, pipeline influenced)
   - How to calculate Reference Program ROI: formula with benchmark values
   - Attribution model: how to credit reference-assisted deals in Salesforce/HubSpot

Make every deliverable production-ready with specific copy and formulas. Use realistic industry benchmarks throughout.

## Advanced Customizable Version

You are a world-class enterprise customer marketing strategist and sales engineering consultant with 15+ years building systematic customer reference programs for B2B SaaS companies at Gartner, Forrester, and VC-backed growth-stage companies. You have designed reference programs that lifted win rates by 23–35% on reference-assisted deals.

### Company Profile
- **Company:** [Company Name]
- **Product Category:** [e.g., AI-powered procurement intelligence platform]
- **ACV Range:** [e.g., $80K–$600K]
- **Sales Cycle:** [e.g., 5–11 months]
- **Primary Buyer Personas:** [e.g., CPO, CFO, VP Operations]
- **Active Customer Count:** [e.g., 175 enterprise accounts]
- **Current NPS:** [e.g., 42]
- **Industries:** [e.g., Retail, CPG, Healthcare Systems]
- **CRM:** [Salesforce / HubSpot]
- **CS Platform:** [Gainsight / ChurnZero / Totango / Spreadsheet]
- **Annual New Logo Target:** [e.g., 45 logos]
- **Current Reference Program Maturity:** [None / Ad-hoc / Informal list / Formal program]

---

### SECTION 1: REFERENCE POOL ARCHITECTURE

**Reference Readiness Score (RRS) Model**

Score each customer 0–100 across these weighted dimensions:

| Dimension | Weight | Scoring Criteria |
|---|---|---|
| NPS Score | 20% | Promoter (9–10) = 100, Passive (7–8) = 50, Detractor = 0 |
| Product Adoption Depth | 20% | Using 4+ core modules = 100, 2–3 = 60, 1 = 20 |
| Relationship Health | 15% | Executive sponsor engaged + CSM green = 100, CSM green only = 60 |
| Quantified ROI | 15% | Documented ROI with specific metrics = 100, anecdotal = 50, none = 0 |
| Tenure | 10% | 12+ months = 100, 6–11 months = 70, <6 months = 0 |
| Logo & Relevance Value | 10% | Top-decile brand in target ICP = 100, midmarket = 60, SMB = 30 |
| Executive Access | 5% | C-suite willing to take calls = 100, VP level = 70, manager only = 30 |
| Past Reference Behavior | 5% | Has done references before and rated highly = 100, first time = 50 |

**Tier Definitions:**
- **Tier 1 (RRS 80–100):** Executive + practitioner calls for any qualified prospect; co-marketing eligible; roadmap advisory board candidates
- **Tier 2 (RRS 60–79):** Practitioner-level calls for matched use case and industry only; limited to 2 calls/quarter
- **Tier 3 (RRS 40–59):** Written case study, G2 review, video testimonial only — no live calls

**Disqualification Flags (automatic exclusion regardless of RRS):**
- Active renewal negotiation or contract dispute
- Open escalation or critical support ticket
- Champion departure in last 90 days
- Pending churn risk flag in CS platform
- Legal hold or compliance review in progress

---

### SECTION 2: REFERENCE MATCHING INTELLIGENCE ENGINE

**Primary Matching Attributes (must match ≥3 of 5):**
1. **Industry vertical** — exact match preferred; adjacent industry acceptable if use case identical
2. **Company size band** — within one ARR tier (e.g., $100M–$500M, $500M–$2B)
3. **Primary use case** — must match the prospect's stated primary pain (not just product)
4. **Buyer persona** — reference's champion should mirror prospect's primary decision-maker title
5. **Tech stack** — shared ERP, CRM, or adjacent platform increases credibility

**Secondary Matching Attributes (tiebreakers):**
- Geographic region (especially EMEA/APAC regulatory context)
- Business model (B2B vs B2C vs marketplace)
- Growth stage (VC-backed vs PE-backed vs public vs bootstrapped)
- Competitive displacement (if prospect is switching from same incumbent)

**Reference Selection Priority Logic:**
1. If multiple Tier 1 matches exist: prioritize lowest call frequency in last 90 days, then highest RRS
2. Maximum 1 reference call per prospect (second call requires VP CS approval)
3. Never use the same reference for a prospect if that reference was used in a lost deal for a similar company

**Reference vs. Alternative Proof Decision Tree:**
Is the deal >$100K ACV? 
  → YES: Does a Tier 1 or Tier 2 match exist?
    → YES: Offer live reference call (Stage 4–5 of sales cycle)
    → NO: Use case study + analyst quote + offer to find match within 14 days
  → NO ($25K–$100K):
    → Does a video testimonial from matched ICP exist?
      → YES: Share video + G2 reviews (no live call)
      → NO: Offer written case study only

---

### SECTION 3: REFERENCE RECRUITMENT CAMPAIGN

**Email Sequence: Reference Program Recruitment**

**Email 1 — The Recognition Ask (send at NPS survey 9–10 + health score green):**

Subject: [First Name], would you share your story with [Company]'s future customers?

Hi [First Name],

[CSM First Name] just showed me your recent results — [specific metric, e.g., "17% reduction in procurement cycle time"] — and I had to reach out directly.

Results like yours are exactly what procurement leaders at companies like [Reference's Company] are desperately looking for when evaluating platforms like ours. They want to hear from someone who's actually done the work — not a sales deck.

Would you be open to joining [Company]'s Customer Advisory Network? Here's exactly what it involves:

- **Occasional 30-minute reference calls** with qualified prospects (we cap this at 2 per quarter — we protect your time aggressively)
- **Co-marketing opportunities**: featured in our annual report, speaking slot at [Company] Summit, LinkedIn amplification
- **Early roadmap access**: quarterly sessions with our CPO before features go to GA
- **Executive roundtable access**: invitation-only dinners with peer leaders from companies like [Customer 1], [Customer 2]

There's no obligation and you can opt out anytime. We'll always send a prospect profile 48 hours before any call so you can decide if it's a fit.

Interested? Just reply "yes" and I'll send over the 2-page program charter.

[Signature]

---

**Email 2 — The Follow-Up with Social Proof (send 5 days after Email 1 if no response):**

Subject: Quick follow-up — what [Peer Company Name] got from this program

Hi [First Name],

Wanted to follow up on my note from last week about our Customer Advisory Network.

[Peer Reference Name] at [Peer Company] has been part of the program for 8 months. She told us it's led to three executive relationships she wouldn't have had otherwise — two of which turned into partnerships.

It's not purely altruistic. Our most active references consistently get:
- Product priorities they care about moved faster on our roadmap
- Peer connections with leaders solving identical problems
- Speaking opportunities that build their personal brand

If this sounds like it might be valuable, I'd love a 15-minute call to walk through the program. Are you free this week?

[Scheduling link]

[Signature]

---

**Email 3 — Final Ask with Minimal Commitment Option (send 7 days after Email 2):**

Subject: Last ask — a smaller way to participate

Hi [First Name],

I don't want to keep nudging you if the timing isn't right. Totally understood.

One smaller option: would you be willing to be listed in our reference pool for now, with the agreement that we always ask you first before committing you to any call? You'd have full veto power every single time.

That way, when the perfect match comes along — a company almost identical to yours — you'll hear about it and can decide then.

Worth a yes on that?

[Signature]

---

**CSM QBR Talk Track:**

"[Customer Name], based on everything you've achieved over the past [X months], I wanted to bring up something. We're building a customer advisory network of our most successful customers — people whose results are compelling enough that future buyers want to hear directly from them. You're exactly the kind of profile we're looking for. I want to be upfront: it involves occasional reference calls — we cap it at 2 per quarter and always give you full context before committing. In exchange, we open doors to our executive team, early roadmap access, and peer relationships with leaders in your space. Is that something you'd want to explore?"

---

### SECTION 4: REFERENCE PREPARATION PLAYBOOK

**Pre-Call Briefing Template (send 48 hours before each call):**

REFERENCE CALL BRIEFING
Reference: [Your Name] | [Company] | [Title]
Prospect: [Prospect Company] | [Prospect Name, Title]
Call Date/Time: [Date] | [Time Zone]
AE Facilitating: [AE Name] | [AE Phone]

ABOUT THE PROSPECT
- Company: [Prospect Co] — [brief 2-sentence description]
- Industry: [Industry] | Employees: [#] | ARR: [estimated]
- Primary Pain: [1–2 sentences: what problem they're trying to solve]
- Where they are in evaluation: [Stage — e.g., "Finalists: us and [Competitor]"]
- Key decision-maker on call: [Name, Title, LinkedIn URL]

WHAT THEY MOST WANT TO HEAR
1. How you handled [specific integration challenge or business process]
2. What the implementation experience was actually like (timeline, resources, bumps)
3. Quantified business outcomes — especially [specific metric relevant to their pain]

TALKING POINTS WE'D LOVE YOU TO EMPHASIZE
- [Specific outcome or differentiator to highlight]
- [Any experience with a competing product that gives you credibility to compare]
- [Your relationship with [Company]'s support/CS team — if positive]

TOPICS TO AVOID
- Pricing (you don't know their deal structure)
- [Any functionality gap the prospect hasn't raised that could create new objections]
- [Internal company information shared with CSM in confidence]

LIKELY QUESTIONS FROM PROSPECT — SUGGESTED FRAMING
Q: "What was implementation really like?"
A: Frame it honestly — acknowledge complexity, then emphasize what made it work (exec sponsorship, dedicated resource on your team, [Company] implementation team's responsiveness)

Q: "Would you buy it again?"
A: Powerful if authentic — only say yes if you genuinely would, and explain why with specifics.

Q: "What would you do differently?"
A: Being honest here builds credibility. One honest "I wish we had done X earlier" is more persuasive than perfect praise.

AFTER THE CALL
- We'll share the outcome with you within 5 business days (win, loss, or still in process)
- We'll send a thank-you [and a small token of appreciation — see program tier]
- Max 1 more reference call from you this quarter — you're protected

Questions? Call [AE Name] directly at [phone].

---

**Reference Coaching Guide — Story Structure**

Train references to tell their story using the C.A.R.E. framework:

- **Challenge:** What problem were you trying to solve? What was it costing you? (Quantify: time, money, risk, missed opportunity)
- **Alternatives:** What else did you consider? Why weren't they enough? (This is where competitive differentiation happens organically)
- **Results:** What specifically changed after going live? Give the most credible number you can, even if it's directional.
- **Experience:** How is working with [Company] day-to-day? CSM, support, roadmap responsiveness — what stands out?

---

### SECTION 5: REFERENCE CALL FACILITATION

**30-Minute Call Agenda:**

| Minute | Activity | Owner |
|---|---|---|
| 0–2 | AE intro: set context, thank reference, set agenda | AE |
| 2–5 | Prospect intro: company, role, what they're trying to solve | Prospect |
| 5–18 | Reference tells their story using C.A.R.E. framework | Reference |
| 18–26 | Open Q&A from prospect | Prospect leads |
| 26–29 | AE seeds 1 closing question: "Is there anything about [Company]'s [specific differentiator] you've experienced that surprised you?" | AE |
| 29–30 | AE closes: thanks reference, outlines next steps with prospect | AE |

**AE Opening Script:**
"[Reference Name], thank you so much for making time today — I know you're busy and we genuinely appreciate it. [Prospect Name], [Reference Name] has been a customer of ours for [X months/years] and has seen some really compelling results in [their primary use case]. I'll let them tell their story directly. [Reference Name], would you mind starting with a bit about what challenge you were facing before you started looking at platforms like ours?"

**3 Questions AE Seeds During Call:**

1. "Can you share how the implementation compared to what you expected going in?" *(surfaces realistic expectations + reframes any concerns the prospect has)*
2. "What's one thing you wish you'd asked us during your evaluation that would have helped you move faster?" *(reframes prospect hesitation as something they can solve now)*
3. "If a colleague at a similar company asked you whether to consider [Company], what would you tell them?" *(generates organic endorsement without scripting)*

**Post-Call Debrief (complete within 24 hours):**

POST-REFERENCE CALL DEBRIEF

Date: _____ | Reference: _____ | Prospect: _____

WHAT LANDED WELL
- [Specific comments or moments that visibly moved the prospect]

PROSPECT OBJECTIONS RAISED
- [Any new concern surfaced during call]

REFERENCE SENTIMENT
- Did the reference seem comfortable? Y/N
- Did they stick to agreed talking points? Y/N
- Any topics they went off-script on?

DEAL IMPACT ASSESSMENT (AE judgment)
- Deal velocity: Accelerated / No change / Slowed
- Prospect confidence: Increased / Neutral / Decreased
- Reference call influenced move to next stage: Y/N

ACTION ITEMS
- [ ] Thank reference within 24 hours
- [ ] Log reference call in CRM with outcome
- [ ] Share deal outcome with reference when known
- [ ] Update reference call frequency counter in CS platform

---

### SECTION 6: REFERENCE BURNOUT PREVENTION SYSTEM

**Call Frequency Limits by Tier:**
- **Tier 1 references:** Max 2 calls/quarter, max 6/year
- **Tier 2 references:** Max 1 call/quarter, max 3/year
- **Any reference:** 2-week cooling off period between any consecutive calls

**Tracking in Salesforce/HubSpot:**
- Create a "Reference Activity" custom object linked to the Account record
- Fields: Call Date, Prospect Company, Deal Stage at Time of Call, Deal Outcome (update when known), AE Name, Reference Satisfaction Rating (post-call survey)
- Build a dashboard view: Reference Call Count (rolling 90 days) — flag any reference approaching quarterly limit

**Post-Call Appreciation Playbook:**
- Within 24 hours: Personalized thank-you email from AE (specific, not templated — mention one thing they said that was particularly helpful)
- Within 7 days: CSM sends a small token based on reference tier (Tier 1: $100 charity donation in their name or curated gift; Tier 2: handwritten note + branded gift)
- When deal closes (won): Share the win — "You helped make this happen." Consider co-marketing announcement if reference consents.
- When deal closes (lost): Thank them for their time, share brief context. Maintain the relationship — the next deal may be a better fit.

**Annual Reference Refresh Process:**
- Each January: Run all references through updated RRS scoring
- Retire references with: RRS below 40, 12+ months inactive in product, champion departure without replacement, voluntary opt-out
- Re-qualify references who have hit call frequency limits: send a re-enrollment email with a reset value proposition
- Gap analysis: identify ICP segments with <3 Tier 1 references — assign CSMs with green accounts in those segments to recruitment outreach within 30 days

---

### SECTION 7: PROGRAM ROI DASHBOARD

**10 Weekly/Monthly Metrics:**

| Metric | Frequency | Benchmark | Formula |
|---|---|---|---|
| Reference-Assisted Win Rate | Monthly | +23–35% lift vs unassisted | Deals won with reference / Deals closed with reference |
| Reference-Assisted Deal Velocity | Monthly | 15–22% faster | Avg days to close (reference) vs (no reference) |
| Reference-Assisted ACV Premium | Monthly | 8–12% higher | Avg ACV (reference deals) vs (baseline) |
| Reference Pool Coverage Ratio | Monthly | ≥1.5x | Tier 1+2 references / # of ICP segments |
| Reference Utilization Rate | Monthly | 40–60% of pool active | References used in last 90 days / Total pool |
| Reference Satisfaction Score | Per call | ≥4.2/5.0 | Post-call survey (1-question NPS-style) |
| Reference Burnout Rate | Quarterly | <5% opt-outs | References who opted out / Total pool |
| Recruitment Conversion Rate | Monthly | 35–50% | References recruited / Recruitment emails sent |
| Gap Coverage Completion | Quarterly | <3 uncovered segments | ICP segments with <2 Tier 1 references |
| Pipeline Influenced | Monthly | 25–40% of enterprise pipeline | Reference-assisted pipeline / Total enterprise pipeline |

**Reference Program ROI Formula:**
Reference Program ROI = 
  (Reference-Assisted Deals Won × ACV × Win Rate Lift %) 
  ÷ 
  (Program Manager Time + Appreciation Budget + Reference Recruitment Cost)

Example:
- 18 reference-assisted deals won × $145K ACV × 28% win rate lift = $730,800 incremental revenue
- Program cost: 0.25 FTE PM ($40K) + $18K appreciation budget + $5K tools = $63,000
- ROI = $730,800 / $63,000 = 11.6x

**CRM Attribution Model:**
- Add "Reference Assisted" checkbox to Opportunity in Salesforce/HubSpot
- Required field when "Reference Call" Activity type is logged
- Run monthly report: Win Rate and ACV by "Reference Assisted = True/False"
- Report to board as: "Reference Program influenced $X pipeline, contributed to $Y closed revenue at Z% win rate vs N% for unassisted deals"

---

## Example Input/Output

**Input:**
- Company: Veridian Analytics (enterprise data observability platform)
- ACV: $120K–$550K
- Customers: 140 enterprise accounts, NPS 44
- Industries: Financial Services, Healthcare, SaaS
- Challenge: 3 deals lost in Q3 where buyers said "we couldn't find a peer reference in our exact space"

**Output Excerpt — Reference Gap Analysis:**

Veridian's reference pool (62 Tier 1+2 references) has 3 uncovered ICP segments:
- Healthcare payer segment: 0 Tier 1, 1 Tier 2 reference (RRS 67) — Recommend: CSM-led outreach to Baptist Health (NPS 9, green health, 14 months tenure) as primary recruitment target within 30 days
- Regional bank segment (<$5B assets): 1 Tier 2 only — Recruitment target: Cascade Community Bank (NPS 10, full module adoption, champion is VP Data who previously spoke at a Veridian webinar)
- PE-backed portfolio company: 0 references — Explore co-reference arrangement with Veridian's PE firm relationships

**Reference Match for Active Deal:**
- Prospect: Anthem subsidiary, VP Data Governance, 8,000-employee payer, evaluating against Collibra
- Best match: BlueCross BlueShield of Kansas City (Tier 1, RRS 89, Healthcare payer, identical use case: claims data lineage, same VP-level champion, displaced Collibra in 2024)
- Match score: 5/5 primary attributes — recommend immediate introduction with 48-hour briefing package

---

## Success Metrics

- Reference-assisted win rate: 23–35% higher than unassisted enterprise deals
- Deal velocity: 15–22% faster to close when reference call occurs in Stage 4
- ACV premium: 8–12% higher average deal size on reference-assisted deals
- Reference pool coverage: ≥1.5 references per ICP segment within 90 days of program launch
- Reference satisfaction: ≥4.2/5.0 post-call score (protect your advocates)
- Program ROI: 8–15x return on program investment within 12 months

## Related Prompts

- `../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/Customer-Advocacy-Referral-Revenue-Engine.md` — referral program automation for self-serve and SMB segments
- `../../06_Customer-Success-&-Retention/Customer-Advocacy-&-Referral/G2-Review-Social-Proof-Automation-Engine.md` — automated review generation for digital social proof
- `../../06_Customer-Success-&-Retention/Customer-Success-Automation/QBR-EBR-Automation-Engine.md` — executive business reviews where reference recruitment conversations happen
- `../../02_Product-Marketing/Sales-Enablement/Sales-Battlecard-&-Competitive-Enablement-Engine.md` — arm references with competitive talking points

## Integration Tips

- **Salesforce:** Create custom Reference Activity object linked to Account and Opportunity; add "Reference Assisted" checkbox to Opportunity; build dashboards for win rate lift and pipeline influence
- **HubSpot:** Use custom properties on Contact (Reference Tier, RRS Score, Calls YTD) and Deal (Reference Assisted: yes/no); automate reference briefing delivery via workflow triggered by "Reference Call Scheduled" stage
- **Gainsight/ChurnZero:** Add Reference Readiness Score to customer health model; create CTAs triggered when RRS crosses 80 threshold; track call frequency to prevent burnout
- **ReferenceEdge or Influitive:** Dedicated reference management platforms that handle matching, scheduling, gamification, and ROI reporting natively — evaluate when pool exceeds 75 references
- **Notion:** Build your reference pool tracker as a filterable database with RRS scores, match attributes, and call history — shareable with AEs for self-serve matching on smaller deals
- **Zapier:** Automate post-call thank-you email trigger (when Salesforce Reference Activity logged → send AE-authored HubSpot email to reference within 24 hours)

## Troubleshooting

**Problem: Reference pool is too small to cover ICP segments — deals stall waiting for a match.**
Fix: Launch a time-boxed "Reference Sprint" — identify the 20 highest-NPS accounts in your most critical ICP segment, task CSMs to make the reference ask in every QBR or check-in for 30 days, and offer a compelling time-limited incentive (e.g., 1:1 roadmap session with CPO). Set a pool coverage target of minimum 2 Tier 1 references per segment before enabling self-serve AE access.

**Problem: References are burning out — same 5 customers getting asked for every deal.**
Fix: This is a math and process problem. Enforce the 2-calls/quarter limit in CRM with a hard block (AE cannot log a reference call for a contact that has hit their limit without VP CS approval). Aggressively expand the pool — run recruitment campaigns quarterly. Consider "evergreen reference content" (pre-recorded 20-minute video interview with reference) that can substitute for live calls on sub-$75K deals.

**Problem: AEs are bypassing the program and calling references directly — untracked, unmanaged.**
Fix: Make the official program easier than the workaround. Build a 2-minute Salesforce flow where AEs submit a reference request and receive a match recommendation within 4 business hours. Pair with a policy: any reference call not logged in CRM is ineligible for commission credit on influenced deals. Report on reference utilization in the weekly sales call — positive visibility creates compliance.

## Version History
- v1.0: Initial creation (auto-generated)
