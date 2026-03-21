# Focor for Claude Cowork

**Give Claude the full picture.** Focor connects your tools — Slack, Gmail, Calendar, Notion, Linear, HubSpot — and synthesizes them into a single intelligence layer that Claude can query in real time.

No more context-switching. No more "let me check Slack." Just ask Claude, and Focor fills in the rest.

---

## Why Focor?

Without Focor, Claude only knows what you tell it. With Focor, Claude knows:

- **Who you're meeting with** — and the full relationship context: last interaction, open commitments, communication history
- **What happened overnight** — Slack threads, emails, ticket updates, synthesized into what actually matters
- **What's falling through the cracks** — overdue follow-ups, stale promises, forgotten commitments
- **When you work best** — energy patterns, focus windows, and optimal timing for deep work

Focor doesn't just give Claude more data. It gives Claude **judgment** — confidence-scored, source-traced intelligence from a knowledge graph built across all your tools.

### The difference

| | Without Focor | With Focor |
|---|---|---|
| Morning planning | You manually check Slack, email, calendar | Claude briefs you with a prioritized synthesis |
| Meeting prep | You scramble to remember context | Claude knows every open loop, last interaction, and what's on their mind |
| Follow-ups | Things slip through the cracks | Claude flags overdue commitments with the exact source |
| Context | You copy-paste between tools | Claude has cross-tool context automatically |

---

## Installation

### 1. Add the Focor Marketplace

1. Open **Claude Cowork**
2. Go to **Settings** (gear icon)
3. Navigate to **Plugins** → **Browse plugins**
4. Click the **+** button next to the marketplace tabs
5. In the "Add marketplace" dialog, enter:
   ```
   Focor/focor-cowork-plugin
   ```
6. Click **Add**

### 2. Install the Plugin

1. You should now see **focor-marketplace** in your marketplace list
2. Click on the **Focor** plugin card
3. Click **Install**

### 3. Connect Your Focor Account

1. After installing, go to **Connectors** in the left sidebar under the Focor plugin
2. Click **Install** next to the focor connector
3. You'll be redirected to Focor's authorization page
4. Sign in with your Focor account and click **Allow**
5. You'll be redirected back to Claude Cowork — you're connected!

### 4. Start Using Focor

Type **`/morning-brief`** to get your daily briefing, or just ask Claude naturally:

> *"What's going on today?"*
> *"Brief me on my day"*
> *"Catch me up"*
> *"What should I focus on?"*

---

## What's Included

| Feature | Description |
|---------|-------------|
| **`/morning-brief`** | Cross-tool synthesis for your day — calendar overview, overnight activity, overdue commitments, and a focus recommendation |
| **Focor Intelligence skill** | Teaches Claude when and how to use Focor — automatically triggers on context-related questions |

### Coming soon

- `/prep-meeting` — Full meeting prep with attendee context, open loops, and talking points
- `/check-loops` — Review open commitments and follow-ups across all tools
- `/focus-now` — Get a single focus recommendation based on your energy patterns and priorities

---

## How It Works

```
Your tools (Slack, Gmail, Calendar, Notion, Linear, ...)
        |
        v
   Focor Knowledge Graph
   Cross-tool synthesis, relationship intelligence, commitment tracking
        |
        v
   Claude Cowork + Focor Plugin
   Natural language access to everything that matters
```

Focor builds a knowledge graph from your connected tools. The plugin gives Claude direct access to query that graph — so when you ask a question, Claude doesn't just search one tool, it synthesizes across all of them.

Every response includes **source tracing** (where the information came from) and **confidence scores** (how certain Focor is about each insight).

---

## Requirements

- A [Focor](https://focor.com) account
- At least one connected tool in Focor (Slack, Gmail, Calendar, Notion, Linear, HubSpot, etc.)

## Links

- [Focor](https://focor.com) — Create your account
- [GitHub Issues](https://github.com/Focor/focor-cowork-plugin/issues) — Report bugs or request features

---

Built by [Focor](https://focor.com)
