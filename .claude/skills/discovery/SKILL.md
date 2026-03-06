---
name: discovery
description: Research market demand for marketing prompts/AI automation use cases. Find what's most valuable, in-demand, and fully automatable. Store findings in Researches/discovery/.
user-invocable: false
---

# Discovery Skill

> Research what marketing prompts and AI automation use cases are most valuable right now

## When to Run

Before deciding what to create or improve in the repo. Discovery informs priority — don't guess what's valuable, research it.

## Research Process

### 1. Market Demand Research

Web search for current demand signals:
- `"most useful AI marketing prompts {current_year}"`
- `"marketing tasks AI agents automate {current_year}"`
- `"ChatGPT marketing use cases most popular"`
- `"AI marketing automation workflows"`
- `"marketing prompt engineering best practices {current_year}"`
- `"what marketing tasks can be fully automated AI"`

### 2. Automation Potential Research

Focus on what can run end-to-end without humans:
- `"AI agent marketing no human in the loop"`
- `"fully automated marketing workflows AI"`
- `"marketing tasks AI replaces completely"`
- `"autonomous marketing agent use cases"`

### 3. Competitor Analysis

Check what other prompt libraries prioritize:
- `"marketing prompt library github"`
- `"AI marketing prompt collection best"`
- `"marketing AI templates most starred github"`

### 4. Trend Detection

What's emerging and underserved:
- `"AI marketing trends {current_year} new"`
- `"marketing AI capabilities nobody uses"`
- `"underrated AI marketing use cases"`

## What to Capture

For each finding, record:

| Field | Description |
|-------|-------------|
| **Use case** | What the prompt/workflow does |
| **Demand signal** | How you know it's in-demand (search volume, mentions, stars, etc.) |
| **Automation score** | 1-5: can it run fully autonomous? (5 = no human needed) |
| **Repo coverage** | Does the repo already have this? Quality level? |
| **Priority** | High / Medium / Low based on demand x automation x gap |

## Storage

Write findings to `Researches/discovery/`:

- `Researches/discovery/market-demand.md` — Current demand signals, ranked use cases
- `Researches/discovery/automation-candidates.md` — Use cases scored by automation potential
- `Researches/discovery/competitor-analysis.md` — What other libraries do well/miss
- `Researches/discovery/trends.md` — Emerging opportunities

Each file should have a `Last updated: YYYY-MM-DD` header. Append new findings, don't overwrite — build a rolling knowledge base.

## How to Use Findings

When deciding what to create/improve in the repo-improver workflow:
1. Read `Researches/discovery/` first
2. Cross-reference with repo gaps (empty/sparse directories)
3. Pick the highest-impact action: high demand + high automation + low/no coverage = top priority
