---
name: fabio-live-alert-watchlist
description: "Turn the session plan into concise Watch/Forming/Human Review/Avoid alerts for a human trader."
version: 1.0.0
platforms: [linux, macos, windows]
metadata:
  hermes:
    tags: [fabio, live-alerts, watchlist, setup-copilot, risk-sentinel]
---

# Fabio Live Alert Watchlist

Use during the live session after pre-market levels and no-trade conditions are defined.

## Alert Format

```text
Label:
Level/Context:
Evidence Present:
Evidence Missing:
Invalidation:
Risk Reminder:
```

## Rules

- Alerts are attention cues, not trade instructions.
- Avoid long explanations during live conditions.
- Risk Sentinel can block or downgrade alerts.
- Do not click, place, modify, or cancel trades.
