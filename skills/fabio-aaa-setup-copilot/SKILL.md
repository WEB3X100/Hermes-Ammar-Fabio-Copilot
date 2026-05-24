---
name: fabio-aaa-setup-copilot
description: "Check whether a Fabio-style setup is Watch, Forming, Human Review, Avoid, or Journal without making trade calls."
version: 1.0.0
platforms: [linux, macos, windows]
metadata:
  hermes:
    tags: [fabio, setup-copilot, AAA-setup, alerts, human-execution]
---

# Fabio AAA Setup Copilot

Use when price approaches a key level or a setup may be forming.

## Output

```text
Label:
Level/Context:
Evidence Present:
Evidence Missing:
Invalidation:
No-Trade Check:
Risk Sentinel Message:
Trader Alert Draft:
```

## Rules

- Use Watch/Forming/Human Review/Avoid/Journal labels.
- Do not say buy or sell.
- Do not alert without invalidation.
- Do not alert without no-trade check.
- Escalate to Risk Sentinel before trader-facing alert.
