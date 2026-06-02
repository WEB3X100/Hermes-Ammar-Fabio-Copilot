# 06 - Weekly Review Audit

Run Friday after close or Sunday morning.

## Inputs

Manual weekly CSV or summary with:

```text
Symbol
Entry Date
Entry Time
Entry Price
Exit Date
Exit Time
Exit Price
Contracts
P&L
R Result
Setup Type
Rule Adherence Score
Emotion At Entry
Mistake Type
```

## Weekly Stats To Calculate

```text
Total trades:
Total P&L:
Total R:
Win rate:
Average R:
Best setup by P&L:
Best setup by average R:
Worst setup by P&L:
Best hour:
Worst hour:
```

## Setup Table

| Setup | Count | Win Rate | Avg R | Total R | Total P&L | Keep / Cut / Backtest |
| --- | ---: | ---: | ---: | ---: | ---: | --- |
| 9:25-9:35 immediate reversal |  |  |  |  |  |  |
| Continuation |  |  |  |  |  |  |
| 9:45+ final reversal |  |  |  |  |  |  |
| ORB |  |  |  |  |  |  |

## Time-Of-Day Review

Only review 9:00 AM to 11:30 AM ET for Phase 1.

| Time Block | Trades | Total R | Notes |
| --- | ---: | ---: | --- |
| 9:25-9:35 |  |  |  |
| 9:35-9:45 |  |  |  |
| 9:45-10:15 |  |  |  |
| 10:15-10:45 |  |  |  |
| 10:45-11:30 |  |  |  |

If a time block repeatedly loses money, it becomes restricted until retested.

## Emotional Leakage Score

Rate each 0-5:

```text
FOMO:
Revenge:
Boredom:
Fear:
Overconfidence:
Anxiety:
```

Most expensive emotion this week:

## Instinct Accuracy

Track every moment when your gut said "wait."

```text
Times gut said wait:
Times waiting was correct:
Times ignoring wait lost money:
Instinct accuracy %:
```

## A+ Setup Promotion Criteria

A setup can be promoted only if:

- 5+ occurrences this week
- win rate above 60%
- average R above 1.5
- no emotional trades included

Promoted setup:

Reason:

## Prompt G - Weekly Review

```text
Here is my trade data for the week: [PASTE CSV or summary]. Analyze: win rate per setup type, average R per setup, P&L by hour of day from 9:00-11:30 AM, and total P&L per setup. Identify the single most profitable setup, the single most expensive repeated mistake, and whether any setup should be promoted to A+ status based on 5+ occurrences, 60%+ win rate, and 1.5R+ average. What is the one rule I must protect next week? One sentence.
```

## One Rule For Next Week

```text
Next week I protect:
```
