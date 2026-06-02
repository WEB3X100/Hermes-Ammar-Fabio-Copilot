# 09 - Backtest And Forward-Test Protocol

No new setup becomes live until it passes validation.

## Step 1 - Setup Hypothesis

Write the setup in full:

```text
Setup name:
Market: ES / NQ
Location criteria:
Order-flow criteria:
Entry trigger:
Invalidation:
Stop placement:
Target / TP logic:
Breakeven logic:
No-trade conditions:
Expected time window:
Why this should work:
```

If the setup cannot be written clearly, it cannot be traded.

## Step 2 - Historical Sample

Find 50-100 instances using DeepCharts replay or saved screenshots.

Log:

```text
Date:
Instrument:
Time:
Setup appeared: Y/N
Location valid: Y/N
Order-flow criteria met: Y/N
Entry trigger occurred: Y/N
Outcome: win / loss / breakeven / no-trade
R result:
Screenshot path:
Notes:
```

## Step 3 - Statistics

Minimum live-trading threshold:

- at least 50 instances
- win rate >= 55%
- average R >= 1.5
- logical reason for edge
- not dependent on one weird day

If a setup only works under narrow timing like "9:46 to 10:03 except Mondays," it is likely curve-fit noise.

## Step 4 - Forward Test

Before full size:

- paper trade or smallest size for 2 weeks
- execute every valid signal
- do not cherry-pick
- log every no-trade
- review rule adherence, not just P&L

## Step 5 - Live Promotion

Promote only if forward test confirms:

- rules can be executed emotionally
- drawdown is tolerable
- setup is visible in real time
- screenshots confirm the pattern
- average R remains positive

## Reusable Asset Test

Before adding anything to the OS, ask:

```text
Does this reduce hesitation?
Does this reduce rule-breaking?
Does this improve setup filtering?
Does this improve review quality?
Does this improve risk discipline?
```

If no, it is not a reusable asset.

## Promotion Log

```text
Date promoted:
Asset/setup:
Evidence count:
Win rate:
Average R:
Failure mode:
Owner:
Review date:
```
