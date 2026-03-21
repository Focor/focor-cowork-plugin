# Focor — Claude Cowork Plugin

Cross-tool intelligence layer. Morning briefings, meeting prep, open commitments, and the context that matters.

## Installation

### Step 1: Add the Focor Marketplace

1. Open **Claude Cowork**
2. Go to **Settings** (gear icon)
3. Navigate to **Plugins** → **Browse plugins**
4. Click the **+** button next to the marketplace tabs
5. In the "Add marketplace" dialog, enter:
   ```
   Focor/focor-cowork-plugin
   ```
6. Click **Add**

### Step 2: Install the Plugin

1. You should now see **focor-marketplace** in your marketplace list
2. Click on the **Focor** plugin card
3. Click **Install**

### Step 3: Connect Your Focor Account

1. After installing, go to **Connectors** in the left sidebar under the Focor plugin
2. Click **Install** next to the focor connector
3. You'll be redirected to Focor's authorization page
4. Sign in with your Focor account and click **Allow**
5. You'll be redirected back to Claude Cowork — you're connected!

### Step 4: Start Using Focor

You can now use Focor in any conversation:

- Type **`/morning-brief`** to get your daily briefing
- Or just ask Claude naturally: *"What's going on today?"*, *"Brief me"*, *"Catch me up"*

## What's Included (v0.1)

| Feature | Description |
|---------|-------------|
| `/morning-brief` | Cross-tool synthesis for your day — calendar, overnight activity, overdue commitments, focus recommendations |
| `focor-intelligence` skill | Teaches Claude when and how to query Focor for context |

## Requirements

- A [Focor](https://focor.com) account
- At least one connected tool in Focor (Slack, Gmail, Calendar, Notion, Linear, etc.)

## Support

- Website: [focor.com](https://focor.com)
- Issues: [GitHub Issues](https://github.com/Focor/focor-cowork-plugin/issues)
