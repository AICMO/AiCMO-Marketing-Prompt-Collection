---
name: cleanup
description: Clean up stale discovery research and outdated findings. Run periodically to keep Researches/discovery/ fresh and relevant.
user-invocable: false
---

# Cleanup Skill

> Keep discovery research fresh — remove stale data, consolidate findings

## When to Run

- When `Researches/discovery/` files are older than 14 days
- When findings reference outdated trends or tools
- When files grow beyond ~200 lines (consolidate, don't just append)

## Cleanup Process

### 1. Check Staleness

Read each file in `Researches/discovery/`. Check the `Last updated:` header.

| Age | Action |
|-----|--------|
| < 7 days | Keep as-is |
| 7-14 days | Review — remove anything obviously outdated |
| > 14 days | Full refresh — re-research and rewrite |

### 2. Remove Outdated Entries

Delete findings where:
- The trend/tool no longer exists or is no longer relevant
- The demand signal was temporary (one-time event, not sustained)
- The repo already fully covers the use case (gap is filled)
- Competitor analysis references repos that are now archived/dead

### 3. Consolidate

If a file exceeds ~200 lines:
- Merge duplicate/overlapping entries
- Remove lowest-priority items (Low priority + low automation score)
- Keep top 20 findings per file, ranked by impact

### 4. Cross-Reference with Repo

Check if discoveries have been acted on:
- Scan recent `git log` for auto-commits that match discovery priorities
- Mark completed items (prompt was created/improved)
- Remove completed items from the priority list

## Storage Rules

- Always preserve the `Last updated:` header — update it after cleanup
- Never delete the files themselves, only prune contents
- Keep at least 5 entries per file (don't over-prune)
