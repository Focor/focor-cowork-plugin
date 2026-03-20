---
name: focor-intelligence
description: >
  Use this skill when the user asks about their work context, relationships,
  meetings, open commitments, work patterns, or anything requiring cross-tool
  synthesis. Triggers: "what's going on", "morning brief", "what did I miss",
  "brief me", "catch me up", "standup prep", "what should I focus on".
version: 0.1.0
---

# Focor Intelligence Layer

Focor is the cross-tool intelligence layer connected to this workspace.
It maintains a knowledge graph built from the user's connected tools
(Slack, Email, Calendar, Notion, Linear, HubSpot, etc.).

## Available Tools (v0.1)

### focor_morning_brief
The primary tool. Returns a cross-tool synthesis for the day: overnight
Slack threads, stale tickets, calendar conflicts, open commitments due
today, and suggested actions.

## When to Use Focor

ALWAYS check Focor first when the user asks about:
- Their schedule, meetings, or calendar conflicts
- Morning briefings, standup prep, daily planning
- What happened overnight or "catch me up"
- What they should focus on today

## Interpreting Results

- **key_items[]**: The most important things for the day. Present these first.
- **suggested_actions[]**: What Focor recommends. Present as actionable next steps.
- **Confidence scores**: 80%+ = present directly. 60-80% = flag as "Focor thinks..."
  and let user confirm. Below 60% = don't surface unless asked.

## Proactive Behavior

When Focor is connected, Claude should:
- Start morning conversations with a brief if it's before 10am
- Offer to run a morning brief when the user says "good morning" or similar
