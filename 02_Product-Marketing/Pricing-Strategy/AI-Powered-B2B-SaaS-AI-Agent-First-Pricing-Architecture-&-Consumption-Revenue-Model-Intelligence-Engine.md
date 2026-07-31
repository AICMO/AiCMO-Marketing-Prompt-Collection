# AI-Powered B2B SaaS AI-Agent-First Pricing Architecture & Consumption Revenue Model Intelligence Engine

**Difficulty:** Advanced | **Time:** 30 min | **Tags:** pricing, ai-agents, consumption-based, usage-based, monetization, agentic-ai, api-pricing, product-marketing, revenue-model, b2b-saas

## Overview
Redesigns your pricing model for the reality that AI agents — not human users — are becoming the primary consumers of B2B SaaS APIs and platforms. Use this when 20%+ of your API calls originate from LLM orchestration frameworks (LangChain, LlamaIndex, Claude agents, AutoGen), when per-seat pricing is misaligning incentives with agent-heavy usage patterns, or when enterprise buyers are getting sticker shock from unbounded agent consumption costs. This prompt designs a dual-architecture pricing model that serves both human operators and AI agent consumers without breaking either business case.

## Quick Copy-Paste Version

You are a B2B SaaS pricing strategist specializing in AI-native and consumption-based revenue models. Help me redesign my pricing architecture for a world where AI agents are primary consumers of my product.

Company: [COMPANY NAME] — [PRODUCT DESCRIPTION, e.g., "data enrichment API platform"]
Current pricing model: [e.g., "$200/seat/month with 10,000 API calls/seat"]
% of API calls from AI agents/LLMs today: [e.g., 40%]
% from human users: [e.g., 60%]
Avg calls per human user/month: [e.g., 500]
Avg calls per AI agent workflow/month: [e.g., 8,000]
Primary human buyer title: [e.g., VP of Revenue Operations]
Primary AI agent operator title: [e.g., Head of AI Engineering]
Top 3 use cases for agent consumption: [e.g., "AI SDR enrichment, automated research workflows, LLM knowledge base hydration"]
Current overage situation: [e.g., "35% of customers exceed limits and churn when we enforce them"]

Run the following AI-agent pricing analysis:

1. CONSUMPTION PATTERN DIAGNOSIS
   - What is the ratio of agent-to-human API consumption, and how fast is it shifting?
   - Which pricing levers (seats, calls, tokens, outcomes, workflows) best align with agent value delivery?
   - Where is per-seat pricing creating perverse incentives or churn risk?

2. VALUE METRIC SELECTION
   - Identify the single best pricing unit for human users (e.g., seats, projects, records)
   - Identify the single best pricing unit for AI agent consumers (e.g., API calls, tokens processed, enriched records, successful outcomes, agent-hours)
   - Recommend a hybrid metric that serves both without creating pricing confusion

3. DUAL PRICING ARCHITECTURE DESIGN
   - Design a Human Operator tier: fixed/predictable pricing for teams running AI agents
   - Design an Agent Consumption tier: usage-based pricing for the agents themselves
   - Design an Enterprise Orchestration tier: capped/committed pricing for high-volume agent deployments
   - Define overage guardrails that prevent bill shock without triggering churn

4. ENTERPRISE BILL-SHOCK PREVENTION
   - Design spending caps and consumption alerts
   - Recommend committed-use discount tiers (e.g., 500K calls/month at $X, 2M at $Y)
   - Explain how to communicate unpredictable agent consumption in your pricing page and contracts

5. COMPETITIVE POSITIONING
   - How should I position this model against competitors still on per-seat pricing?
   - What messaging resonates with CTO/AI Engineering buyers vs. traditional business buyers?

6. MIGRATION PLAYBOOK
   - How to migrate existing per-seat customers to new model without churning them
   - Grandfathering strategy and communication sequence

Output a pricing architecture brief with specific price points, tier names, and a 60-day migration plan.

## Advanced Customizable Version

ROLE: You are a senior B2B SaaS pricing architect with deep expertise in API monetization, consumption-based revenue models, and the emerging economics of AI agent-driven software consumption. You understand the fundamentals of value-metric alignment, unit economics under agentic load, and enterprise procurement psychology when buyers face unpredictable AI consumption costs.

CONTEXT — COMPANY PROFILE:
Company: [COMPANY NAME]
Product: [PRODUCT NAME] — [DESCRIPTION: what it does, what data/capability it provides]
API/Platform category: [e.g., "data enrichment API", "document intelligence platform", "identity resolution engine", "knowledge retrieval service"]
Current revenue: [ARR]
Current pricing model: [e.g., per-seat SaaS / flat monthly / pure usage-based / hybrid]
Current price points: [TIER NAMES AND PRICES]
Gross margin: [e.g., 82%]
COGS structure: [e.g., "compute cost is $0.003/API call; data licensing at $0.001/enriched record"]

API CONSUMPTION DATA:
Total API calls/month (last 90 days avg): [NUMBER]
% attributed to human-initiated actions: [%]
% attributed to AI agent/LLM orchestration: [%]
% attributed to automated batch jobs (non-AI): [%]
Fastest-growing consumption source: [e.g., "LangChain integrations, +180% QoQ"]
Top 5 customers by API consumption vs. seat count ratio: [list ratios, e.g., "Customer A: 50 seats / 4M calls/month"]
Customers currently on overages: [% of customer base]
Average overage amount per month: [$]
Churn attributed to overage friction: [%]

AGENT CONSUMER PROFILES:
Primary agentic use cases you've observed:
  Use Case A: [e.g., "AI SDR agent enriching 2,000 leads/day before outreach"]
    - Trigger: [automated / event-driven / scheduled]
    - Calls per workflow run: [number]
    - Value delivered per run: [e.g., "$300 in pipeline per enrichment session"]
  Use Case B: [e.g., "LLM-powered proposal writer pulling product specs via API"]
    - Trigger: [automated / event-driven / scheduled]
    - Calls per workflow run: [number]
    - Value delivered per run: [e.g., "saves 3 hours/proposal at $150/hr"]
  Use Case C: [name + same fields]

BUYER PROFILES:
Human Operator (manages AI agents, approves budget):
  - Title: [e.g., Head of AI/Automation, VP Engineering, RevOps Director]
  - Budget ownership: [e.g., "software budget, not infrastructure"]
  - Pricing anxiety: [e.g., "unpredictable bills", "board-level scrutiny of AI spend"]
  - Success metric: [e.g., "cost-per-enriched-record under $0.05"]

AI Agent Operator (builds and runs the agents):
  - Title: [e.g., AI Engineer, Automation Lead, Prompt Engineer]
  - Pricing anxiety: [e.g., "rate limits that interrupt agent workflows", "no sandbox/dev environment pricing"]
  - Success metric: [e.g., "99.9% API uptime, sub-200ms latency, documented rate limits"]

Business Buyer (approves enterprise contract):
  - Title: [e.g., CTO, CFO, CPO]
  - Pricing anxiety: [e.g., "risk of runaway AI agent spend", "lack of audit trail for AI consumption"]
  - Success metric: [e.g., "predictable monthly invoice, ROI within 90 days"]

COMPETITIVE LANDSCAPE:
  Competitor A — [NAME]: [pricing model, approximate cost per call/unit]
  Competitor B — [NAME]: [pricing model, approximate cost per call/unit]
  Competitor C — [NAME]: [pricing model, approximate cost per call/unit]
  Open-source alternative: [NAME + self-hosting cost estimate]

TASK: Design a complete AI-Agent-First pricing architecture using the following modules:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 1: CONSUMPTION PATTERN ANALYSIS & VALUE METRIC SELECTION
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Analyze the consumption data and determine:

VALUE METRIC EVALUATION (score each 1–5 on alignment, scalability, and buyer acceptance):
  - Per seat: Does it map to agent-driven value? [SCORE + REASONING]
  - Per API call: Does it align with outcome value? [SCORE + REASONING]
  - Per enriched/processed record: [SCORE + REASONING]
  - Per successful outcome (e.g., per qualified lead, per completed proposal): [SCORE + REASONING]
  - Per agent-hour or agent-workflow-run: [SCORE + REASONING]
  - Per token processed (if LLM-adjacent): [SCORE + REASONING]
  - Committed capacity block (e.g., 1M calls/month): [SCORE + REASONING]

RECOMMENDATION:
  - Primary value metric for human-operated use: [METRIC + RATIONALE]
  - Primary value metric for agent-operated use: [METRIC + RATIONALE]
  - Whether a unified metric can serve both: [YES/NO + DESIGN IF YES]
  - Risk of chosen metric: [e.g., "call volume is gameable; mitigate by defining a 'call' precisely"]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 2: DUAL-ARCHITECTURE PRICING MODEL DESIGN
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Design three distinct pricing layers:

LAYER 1 — OPERATOR PLATFORM (fixed, predictable)
  Purpose: Seat-based access for human teams managing AI agents
  Includes: Dashboards, controls, monitoring, support SLA, compliance reporting
  Does NOT include: API consumption volume
  Price: [$X/seat/month] OR [$Y/month flat for teams up to Z seats]
  Minimum: [e.g., 3 seats]
  Rationale: Decouples platform value from consumption volume; gives human buyers a predictable anchor

LAYER 2 — AGENT CONSUMPTION (variable, metered)
  Purpose: Pay-for-what-agents-use pricing
  Metric: [CHOSEN VALUE METRIC, e.g., "per 1,000 enriched records"]
  Rate structure:
    - Tier 1: 0 to [VOLUME]: $[RATE] per [UNIT]
    - Tier 2: [VOLUME] to [VOLUME]: $[RATE] per [UNIT] (volume discount)
    - Tier 3: [VOLUME]+ : $[RATE] per [UNIT] (enterprise volume discount)
  Sandbox/development environment pricing: [e.g., "first 10,000 calls/month free for dev/test"]
  Rate limiting: [e.g., "default 100 calls/second; enterprise SLA: 500 calls/second"]

LAYER 3 — COMMITTED CAPACITY (enterprise, capped)
  Purpose: Annual committed usage blocks for large agent deployments
  Structure: [e.g., "500K calls/month block: $X/month; 2M calls/month block: $Y/month"]
  Overage policy: [e.g., "10% overage buffer included; alerts at 80%/95%/100% of commitment"]
  True-up frequency: [e.g., quarterly, with 30-day notice for tier changes]
  Rollover policy: [e.g., "unused capacity rolls over 1 month; no rollover beyond that"]

BILL-SHOCK PREVENTION ARCHITECTURE:
  - Real-time spend dashboard with per-agent breakdown
  - Configurable hard caps (auto-halt agent if spend threshold hit) or soft alerts
  - Recommended cap: [e.g., "default 150% of committed tier; configurable by customer"]
  - Notification sequence: Alert at 70% → Alert at 90% → Auto-email CFO/admin at 100%
  - Emergency overage pricing: [e.g., "above cap, calls still process at 2x standard rate to prevent agent failure"]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 3: UNIT ECONOMICS UNDER AGENTIC LOAD
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Model the unit economics at each consumption tier:

For each pricing tier, calculate:
  - Revenue per 1,000 API calls (RPM): [based on Layer 2 rates]
  - COGS per 1,000 API calls: [compute + data licensing + infra]
  - Gross margin at this tier: [%]
  - Break-even point: [minimum monthly calls to cover Operator Platform cost]
  - LTV:CAC ratio at this tier vs. per-seat model: [compare]

THRESHOLD ANALYSIS:
  - At what consumption volume does the new model outperform the old model in revenue?
  - At what consumption volume does gross margin fall below acceptable threshold (e.g., 70%)?
  - What is the "honeypot" tier — the tier that attracts high-volume agent deployers at healthy margin?

AGENT MULTIPLICATION FACTOR:
  Model what happens when a single human operator deploys 10 agents vs. 100 agents vs. 1,000 agents:
  - Revenue scaling: [show the math]
  - Does your COGS scale linearly, sublinearly, or superlinearly with agent count?
  - At what scale do you need to renegotiate upstream data/compute costs?

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 4: ENTERPRISE PROCUREMENT & CONTRACT DESIGN
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Design enterprise contract elements that address AI consumption anxiety:

AI SPEND GOVERNANCE ADDENDUM:
  Include in enterprise contracts:
  - Spend cap clause: [specific language]
  - Audit trail requirement: [e.g., "per-agent API call log retained 90 days"]
  - AI usage policy compliance: [e.g., "customer certifies agents comply with AUP"]
  - Unusual consumption pattern alert: [e.g., "vendor notifies customer if 7-day consumption exceeds 200% of 30-day average"]

PROCUREMENT PSYCHOLOGY FRAMEWORK:
  For CFO/Finance buyer:
  - Lead with: [e.g., "committed capacity with quarterly true-up — predictable quarterly accruals"]
  - Frame: [e.g., "infrastructure cost category, not software seat cost"]
  - Show: [specific ROI calculation the CFO can model in a spreadsheet]

  For CTO/Engineering buyer:
  - Lead with: [e.g., "SLA-backed rate limits, dedicated sandbox environment, 99.9% uptime SLA"]
  - Frame: [e.g., "build-vs-buy: self-hosting this capability costs $X/month in engineer time + infra"]
  - Show: [specific latency benchmarks and reliability data]

  For VP Operations/Business buyer:
  - Lead with: [e.g., "cost-per-outcome: $X per enriched lead, vs. $Y for manual research"]
  - Frame: [e.g., "variable cost that scales with your AI team's output — you only pay when agents produce value"]
  - Show: [ROI from existing customer who runs agent workflows]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 5: COMPETITIVE PRICING POSITIONING
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Position the new model against the competitive set:

AGAINST PER-SEAT COMPETITORS:
  Attack vector: [e.g., "their model penalizes you for deploying more agents — you pay for seats your agents don't need"]
  Defense: [e.g., "our model scales with agent output, not org chart size"]
  Proof point: [e.g., "at 100K calls/month, our pricing is X% lower than [COMPETITOR]'s 10-seat minimum"]

AGAINST PURE USAGE-BASED COMPETITORS:
  Attack vector: [e.g., "no predictability, finance can't budget, ops can't forecast"]
  Defense: [e.g., "we combine usage-based flexibility with committed capacity predictability"]
  Proof point: [e.g., "enterprises using committed tiers see 34% lower per-call cost vs. pure PAYG"]

AGAINST SELF-HOSTING:
  Attack vector: [e.g., "build your own data pipeline: 3 engineers, 4 months, ongoing maintenance"]
  Defense: [e.g., "our API call cost is $0.00X; self-hosting equivalent costs $0.0Y per call at full engineering cost"]
  Proof point: [e.g., "build-vs-buy TCO analysis shows 18-month payback for self-hosting vs. immediate value on day 1"]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
MODULE 6: CUSTOMER MIGRATION PLAYBOOK
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Design a 90-day migration without churning existing customers:

SEGMENTATION OF EXISTING CUSTOMERS:
  Segment A — "Agent-heavy" (>50% of usage from agents): [migration approach]
  Segment B — "Hybrid" (20–50% agent usage): [migration approach]
  Segment C — "Human-primary" (<20% agent usage): [migration approach]

MIGRATION SEQUENCE:
  Week 1–2: Shadow billing (show customers what they would pay under new model; no charge change)
  Week 3–4: Feedback collection and tier recommendation
  Week 5–8: Voluntary early migration incentive (e.g., 20% discount on committed tier for 12-month commit)
  Week 9–12: Mandatory migration for new customers; legacy price lock for existing customers for 6 months
  Month 4+: Full new model; legacy grandfathered pricing sunsets with 90-day notice

COMMUNICATION SEQUENCE:
  Email 1 (Week 1): "We're redesigning pricing to match how AI teams actually work"
  Email 2 (Week 2): "Your personalized usage analysis — see what you'd pay under our new model"
  Email 3 (Week 4): "Exclusive early-mover offer for migration before [DATE]"
  Exec call trigger: Any customer >$50K ACV gets a 1:1 briefing before Week 3

CHURN RISK MITIGATION:
  - Red flags: Customer requests their data export during shadow billing period
  - Response: Trigger CSM outreach within 24 hours with retention offer
  - Retention offer: [e.g., "lock in current per-seat price for 12 more months with 25% consumption credit"]

FINAL OUTPUT: AI-AGENT PRICING BRIEF
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Compile a one-page executive summary:
1. Current model diagnosis: Where per-seat is leaving money on the table or creating churn
2. Recommended dual-architecture: Layer 1 (Operator Platform) + Layer 2 (Agent Consumption) + Layer 3 (Committed Capacity) with specific prices
3. Revenue impact: Estimated ARR change at full migration (upside from agent-heavy customers vs. risk from human-primary customers)
4. Top 3 risks and mitigations
5. 30-day first action: The single change to implement immediately

CONSTRAINTS:
- Design for enterprise legal/finance approval — contracts must have predictable, auditable spend
- Every pricing recommendation must include specific dollar amounts, not just structures
- Distinguish between price changes that require a sales motion change vs. self-serve implementation
- Flag any recommendation that changes gross margin by more than 5 percentage points
- Provide a recommended price point for at least 3 tiers of committed capacity

## Example Input/Output

**Input Example:**

Company: Nexara Intelligence — we provide a B2B data enrichment and company intelligence API. Our customers use us to enrich leads, research accounts, and hydrate knowledge bases. Current pricing: $250/seat/month with 5,000 API calls included per seat. We have 180 customers, $4.2M ARR, 82% gross margin. In the last 6 months, 40% of API calls come from LangChain/AutoGen integrations, not direct human use. We have 35 customers on overages averaging $800/month; 8 of them churned last quarter citing "unpredictable billing." Our top competitor (Clearbit/HubSpot) charges per-record at $0.02/enriched company; Apollo is $0.005/record. Our COGS is $0.004/call (compute + data licensing).

**Output Example (excerpt from Module 2 — Dual Architecture Design):**

**Recommended Pricing Architecture for Nexara Intelligence**

**LAYER 1 — OPERATOR PLATFORM**
Name: Nexara Teams
Price: $149/seat/month (down from $250; this is now a pure control-plane cost, not bundled with calls)
Includes: Dashboard, agent monitoring console, API key management, webhook configuration, compliance log, support SLA (4hr response)
Does NOT include: API calls (unbundled)
Minimum: 2 seats
Rationale: Reduces the "seat tax" that was forcing customers to underpurchase seats to control costs, then run agents on a small team's credentials. Now operators pay a fair platform fee and agents pay for what they consume.

**LAYER 2 — AGENT CONSUMPTION**
Name: Nexara API Credits
Metric: Per 1,000 enriched records (standardized unit — 1 enriched record = 1 API call that returns a complete company profile)
Pricing tiers:
  - 0–50K records/month: $12.00/1,000 ($0.012/record)
  - 50K–250K records/month: $9.00/1,000 ($0.009/record)
  - 250K–1M records/month: $6.50/1,000 ($0.0065/record)
  - 1M+ records/month: custom (committed capacity, Module 3)
Sandbox environment: First 5,000 records/month free for dev/test API keys
Rate limiting: 50 calls/second by default; $199/month for 500 calls/second (agent-grade throughput SLA)

**Gross margin check:** At $0.012/record with COGS of $0.004/record = 67% gross margin at Tier 1. At $0.009 with same COGS = 56% gross margin at Tier 2. **FLAG: Tier 2 margin falls below 60% threshold.** Recommend adjusting Tier 2 rate to $0.0105/record to recover margin to 62%.

**LAYER 3 — COMMITTED CAPACITY**
Name: Nexara Enterprise
Blocks:
  - 500K records/month commit: $4,800/month ($0.0096/record; 20% discount vs. Tier 1)
  - 2M records/month commit: $16,000/month ($0.008/record; 33% discount)
  - 10M records/month commit: Custom (estimated $60,000–$80,000/month)
Overage buffer: 15% above committed volume included; alert at 80% and 100%
True-up: Quarterly, with 30-day notice to upgrade commitment tier
Rollover: Up to 10% of monthly commitment rolls to next month; no further rollover

**Revenue Impact Projection:**
- Current state: 180 customers × avg $1,944 MRR (blended) = $4.2M ARR
- Post-migration: Agent-heavy customers (72 customers) average bill increases from $1,800 to $3,200/month due to true agent consumption being priced correctly. Human-primary customers (108 customers) average bill decreases from $2,100 to $1,200/month (fewer seats needed + lower platform fee). Net ARR: **$5.1M ARR** (+21%) at 85% migration success rate.
- Gross margin improvement: Elimination of $86K/month in unpriced overages and removal of seat-subsidy for agent consumption improves blended GM from 82% to 84%.

---

**Module 6 — Migration Excerpt:**

The 8 churned customers who cited "unpredictable billing" were all in the agent-heavy segment at the 50K–200K calls/month range — precisely the customers the new committed tier is designed for. **All 8 would have had a lower, predictable bill under the new model.** Prioritize a win-back campaign to these 8 customers as the first action of the migration: offer them 3 months at the 500K committed tier at 40% discount as a re-engagement incentive. Expected recovery: 5 of 8 customers, adding ~$72K in ARR.

## Success Metrics

- Pricing architecture identifies at least 3 tiers (Operator Platform, Agent Consumption, Committed Capacity) with specific dollar prices
- Unit economics model shows gross margin at each consumption volume tier — flags any tier below target margin threshold
- Enterprise contract design includes specific billing protection clauses and audit trail requirements
- Migration playbook segments existing customers by agent vs. human usage ratio and provides distinct communication sequences
- Competitive positioning provides specific cost-per-call comparisons against at least 2 named competitors
- Revenue impact model shows net ARR change at 3 migration success scenarios (70%, 85%, 95%)

## Related Prompts

- [Pricing & Packaging Architecture](../../02_Product-Marketing/Pricing-Strategy/AI-Powered-B2B-SaaS-Pricing-&-Packaging-Architecture-&-Competitive-Price-Positioning-Revenue-Intelligence-Engine.md) — design the tier structure and feature gating before finalizing agent-first pricing
- [Pricing Model Migration](../../02_Product-Marketing/Pricing-Strategy/AI-Powered-B2B-SaaS-Pricing-Model-Migration-&-Business-Model-Transition-Revenue-Intelligence-Engine.md) — full playbook for migrating from per-seat to usage-based at scale
- [Agentic AI Product GTM Architecture](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-B2B-SaaS-Agentic-AI-Product-GTM-Architecture-&-Enterprise-Workforce-Automation-Revenue-Intelligence-Engine.md) — full go-to-market motion for products sold to AI-first buyers
- [Usage-Based Pricing GTM Strategy](../../02_Product-Marketing/Go-To-Market-Strategy/AI-Powered-B2B-SaaS-Usage-Based-Pricing-GTM-Strategy-&-Consumption-Revenue-Expansion-Intelligence-Engine.md) — complement this prompt with the sales motion and messaging changes required by the new pricing model

## Integration Tips

- **Stripe / Chargebee / Orb:** Use the metered billing API to implement Layer 2 (Agent Consumption) pricing. Orb specifically is built for usage-based SaaS and supports complex rate schedules with committed capacity + overage logic out of the box. Feed the tier structure from Module 2 directly into Orb's product catalog.
- **Segment / Amplitude:** Instrument every API call with agent metadata (agent ID, workflow name, trigger type) before the migration launch. This data is essential for shadow billing in Week 1–2 of Module 6. Without it, you cannot show customers their agent vs. human split.
- **Salesforce / HubSpot:** Build a custom "Agent Consumption Score" field on the Account object that pulls live from your billing system. Flag accounts above 50% agent consumption for proactive CSM outreach 30 days before migration communications begin.
- **Notion / Confluence:** Build a "Pricing Architecture Decision Log" using the Module 1 value metric evaluation as a template. Document every pricing decision with the rationale so that future pricing changes have a clear baseline.
- **Slack (internal):** Set up a #pricing-migration Slack channel that receives automatic alerts when any account's shadow bill exceeds 150% of their current bill — these are your highest-churn-risk accounts and need immediate human attention.
- **Metabase / Looker:** Build a "Agent Consumption Dashboard" for your CS team: shows each account's calls/month trend, human vs. agent split, projected bill under new model, and recommended committed tier. Run this in parallel during the shadow billing period.

## Troubleshooting

**Problem: The dual-architecture model produces conflicting signals — some customers would pay more, some much less, making ARR projections uncertain.**
Solution: Run a Monte Carlo simulation using your actual customer API consumption distribution. The prompt produces a deterministic model, but real migration outcomes depend on how accurately you've segmented customers. Pull 90-day API call logs segmented by agent vs. human attribution before running the prompt — this will narrow the variance substantially.

**Problem: The enterprise committed-capacity tiers feel arbitrary without knowing customer budget cycles.**
Solution: Add procurement data to the context: What is your average enterprise deal ACV? What budget cycle do your buyers operate on (annual, quarterly)? What is the average time from "pricing conversation" to "contract signed"? This context lets the prompt design committed tiers that align with how your customers actually think about and authorize spend.

**Problem: Sales team resists the new model because it's harder to explain than per-seat.**
Solution: The prompt's Module 4 (Procurement Psychology) produces buyer-specific narratives, but you also need a one-page sales sheet. Ask a follow-up prompt: "Using the pricing architecture above, create a one-page 'Why We Changed Our Pricing' FAQ sheet for sales reps to use in prospect conversations — one version for CTO buyers and one for VP Ops buyers."

## Version History
- v1.0: Initial creation (auto-generated)
