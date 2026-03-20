# Focor Data Model — v0.1

Minimal reference for understanding morning briefing responses.

## Briefing Response

```
{
  briefing_text: string,     // AI-generated summary of the day
  key_items: [               // Ranked items requiring attention
    {
      title: string,
      type: string,          // e.g. "meeting", "deadline", "follow-up"
      urgency: string,       // "high" | "medium" | "low"
      source: string         // Where this came from (Slack, Calendar, etc.)
    }
  ],
  suggested_actions: [       // Recommended next steps
    {
      action: string,
      reason: string
    }
  ]
}
```

## Confidence System

All extracted data carries a confidence score (0.0 - 1.0):

**Routing thresholds:**
- >= 0.80: Present directly to user
- 0.60 - 0.79: Flag as "Focor thinks..." — let user confirm
- < 0.60: Don't surface unless explicitly asked
