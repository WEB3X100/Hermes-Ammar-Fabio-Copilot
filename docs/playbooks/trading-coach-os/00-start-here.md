# 00 - Start Here

## Purpose

This OS exists to make each trading day cleaner than the last. It does that by forcing preparation before the open, a hard gate before every entry, evidence capture during trades, same-day review, overnight system audit, and weekly statistical review.

The goal is not to trade more. The goal is to trade fewer, cleaner ES/NQ setups that match Ammar's strengths: fast pattern recognition, scalping temperament, order-flow reading, and avoiding choppy low-value markets.

## Phase 1 Boundary

- Coach Only: the human executes all trades.
- ES/NQ only: GC is parked for later and is not part of Phase 1.
- Manual capture: DeepCharts screenshots and notes are captured by the trader.
- Markdown first: these files are the source of truth.
- No trade signals, no broker API, no automation.

## Daily Folder Convention

Real trading logs and screenshots stay outside Git:

```text
~/TradingCoachLogs/YYYY-MM-DD/
  premarket.md
  trade-01.md
  trade-01-before.png
  trade-01-after.png
  trade-02.md
  trade-02-before.png
  trade-02-after.png
  daily-review.md
```

Use this repo for reusable templates, not private trading history.

## Six-Phase Daily Loop

1. **Pre-market analysis**: map news, levels, sentiment, no-trade conditions.
2. **In-session execution**: use the 10-second trade gate before every entry.
3. **Same-day review**: autopsy each trade and select tomorrow's one behavioral fix.
4. **Overnight OS audit**: protect one rule and define one possible system upgrade.
5. **Weekly review audit**: calculate performance by setup/time/emotion and protect one rule next week.
6. **Backtest/forward-test**: validate any new setup before it can enter the live rulebook.

## Daily Command

Before market open, write this at the top of `premarket.md`:

```text
Today I am paid to wait for my setup. If the setup is unclear, I do not trade.
My job is not to predict. My job is to read location, effort, efficiency, and result.
```

## Reusable Asset Definition

A reusable trading asset is a setup rule, checklist, prompt, review template, or decision gate that can be used repeatedly and improves future execution.

It must do at least one of these:

- reduce hesitation
- reduce rule-breaking
- improve setup filtering
- improve review quality
- improve risk discipline
- improve pattern recognition

If it does not make future trades cleaner, safer, or more measurable, it does not belong in this OS.

## Non-Negotiable

The rulebook beats opinion. The gate beats impulse. The daily stop beats revenge. The weekly review beats memory.
