# Fabio Copilot Ubiquitous Language

This dictionary defines the required language for the Fabio trading copilot.

Hermes must use these meanings consistently during pre-market, live alerts, journaling, and weekly review.

## Core Terms

| Term | Strict Meaning | Required Evidence | Common Failure Mode |
| --- | --- | --- | --- |
| AAA Setup | A trade environment where all required setup conditions are present, risk is defined, invalidation is clear, and the trader is not violating session rules. | Key level, trigger behavior, confirmation signal, invalidation, risk size, no-trade filter check. | Calling a partial setup AAA because price is moving fast. |
| Key Level | A price area the trader has pre-approved as meaningful before or during the session. | Premarket plan, prior high/low, VWAP/POC/volume area, liquidity zone, manual trader input, or chart evidence. | Treating every round number as important. |
| Important Number | A numeric reference that changes decision context. | Price, volume, delta, VWAP, overnight high/low, prior day high/low, ATR, economic release time, or risk limit. | Mentioning numbers without explaining why they matter. |
| Trigger | The specific behavior that moves a setup from watchlist to human review. | Break/reclaim, rejection, absorption, volume confirmation, retest, failed breakdown/breakout, or trader-defined signal. | Alerting just because price touched a level. |
| Confirmation | Evidence that the trigger is not random noise. | Follow-through, volume, order-flow clue, candle close, retest hold/fail, market internals, or trader-defined confirmation. | Treating one candle as enough. |
| Invalidation | The condition that proves the setup idea is wrong or no longer worth watching. | Price back below/above level, failed retest, volume failure, news shock, volatility expansion, risk rule breach. | Moving the invalidation after emotional attachment. |
| No-Trade Condition | A condition that blocks new trades regardless of setup excitement. | Daily loss hit, major news window, unclear levels, poor liquidity, revenge state, missed entry, platform issue, fatigue. | Letting a good-looking setup bypass risk rules. |
| Alert | A concise attention cue that a pre-defined condition is forming. | Level, condition, evidence, risk reminder. | Telling the trader what to buy/sell. |
| Journal Entry | A structured record of what happened, why, and what should improve. | Setup, entry reason, exit reason, screenshots/context, rule followed/broken, emotion, lesson. | Writing vague reflections that cannot improve behavior. |
| Memory Candidate | A short evidence-backed lesson that may improve future sessions. | Repeated pattern, evidence, applies-to, expiry/review date. | Saving every emotional thought as permanent memory. |

## Alert Labels

| Label | Meaning | Copilot Behavior |
| --- | --- | --- |
| Watch | A level or condition is approaching. | Give calm attention cue. |
| Forming | Some AAA criteria are present. | List present and missing evidence. |
| Human Review | Enough criteria may be present for trader judgment. | State evidence, invalidation, risk reminder. |
| Avoid | No-trade condition or invalidation is active. | Tell trader to stand down. |
| Journal | Something important happened. | Capture context for post-session review. |

## Required Live Alert Style

Every alert should fit this structure:

```text
Label:
Level/Context:
Evidence Present:
Evidence Missing:
Invalidation:
Risk Reminder:
```

Avoid:

- "Buy now"
- "Sell now"
- "Guaranteed"
- "This will work"
- long explanations during live conditions,
- alerts without invalidation,
- alerts without no-trade check.
