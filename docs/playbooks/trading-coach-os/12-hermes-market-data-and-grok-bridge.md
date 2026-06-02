# 12 - Hermes Market Data And Grok Bridge

## Purpose

Hermes should become the research and intelligence layer that equips this AI Trading Coach with richer context, better data hygiene, and stronger review loops.

It must not become an execution system.

## Target Capability

Hermes should help Ammar answer:

- What scheduled catalysts can move ES/NQ today?
- Which instrument deserves priority?
- What levels/zones matter, based on data Ammar provides or approved feeds?
- Is DeepCharts showing buyer control, seller control, absorption, continuation, or balanced chop?
- Are X/news narratives aligned with actual market structure, or just noise?
- Did today's trades obey the rulebook?
- What should be improved tomorrow?

## Data Source Ladder

Use the highest reliable source available and label it.

1. Ammar-provided DeepCharts screenshots/data: primary order-flow evidence.
2. Ammar-provided levels from TradingView/broker/charting: primary level evidence.
3. Official/economic sources: FOMC, CPI, PPI, NFP, PMI, ISM, Fed speakers, Treasury, CME calendar.
4. Approved market data APIs once configured: Alpaca, Polygon, Databento, Nasdaq Data Link, FRED, Binance/crypto, or another feed Ammar chooses.
5. Grok/x_search: X-native articles, posts, social sentiment, breaking discussion.
6. General web/news: cite and verify freshness.

If a feed is not configured, do not fake it. Ask for the values or say the data is unavailable.

## Grok/x_search Use

Use Grok/x_search for:

- X articles and threads about market-moving narratives.
- Fintwit sentiment and positioning chatter.
- Breaking market rumors that need verification.
- Post-session context about why ES/NQ moved.

Do not use X chatter as a trade trigger. Treat it as context only.

## Pre-Market Output Contract

Hermes should produce a pre-market block that can be pasted into `premarket.md`:

```text
Date:
Session:
Scheduled catalysts:
Overnight surprise:
ES catalyst rating:
NQ catalyst rating:
ES/NQ priority:
Top levels to watch:
No-trade conditions:
DeepCharts read:
Rulebook reminder:
Wait condition:
```

## In-Session Output Contract

Before a trade, Hermes should ask:

```text
What side has momentum?
Are you with or against momentum?
If against, what proves momentum shifted?
What is the named setup?
Where is the stop?
Where is the target?
What invalidates the idea?
Is there at least 15 points of room?
Have you captured the screenshot?
Are any kill-switch rules active?
```

If any required answer is missing, the correct coach response is wait.

## Review Output Contract

After a session, Hermes should produce:

- Best trade.
- Worst trade.
- Rule breaks.
- Missed A+ setup.
- Emotional pattern.
- One behavioral fix for tomorrow.
- One rulebook candidate.
- One setup candidate for backtest/forward-test.

## Open Setup Questions

1. Which live or delayed market data provider should Hermes use first?
2. Should Hermes create daily folders under `~/TradingCoachLogs/YYYY-MM-DD/`?
3. What time should the ES/NQ pre-market brief run?
4. Should Hermes send the pre-market brief to Telegram?
5. Which X handles/lists should Grok/x_search monitor for ES/NQ context?
6. Which sources are banned as low-quality trading noise?

