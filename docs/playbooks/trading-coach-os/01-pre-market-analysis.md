# 01 - Pre-Market Analysis

Run this between 7:00 AM and 9:20 AM ET.

## Outcome

By 9:20 AM, you must know:

- whether ES or NQ has priority
- the top two levels to watch
- the no-trade conditions for the day
- whether the session is likely buyer control, seller control, or balanced chop
- which setups are allowed today

## Step 1 - News And Macro Scan

Record:

```text
Date:
Major scheduled news:
Fed speakers:
CPI/PPI/NFP/FOMC/PMI/ISM:
Major earnings/gaps:
Geopolitical or overnight surprise:
Market-moving catalyst rating for ES: high / medium / ignore
Market-moving catalyst rating for NQ: high / medium / ignore
```

Do not trade through major scheduled releases unless a setup has already completed and risk is protected.

## Step 2 - Key Ranges For The Day

Record:

```text
HTF bias:
Daily/weekly context:
H4 direction:
H1 direction:
Primary regime expectation: balance / compression / expansion / trend / slow grind / unclear
Prior session POC:
Prior session VAH:
Prior session VAL:
Overnight high:
Overnight low:
VWAP anchors in directional bias:
Supply zones:
Demand zones:
Low-volume nodes:
Range/juice between key zones:
Balance edges:
Trend continuation levels:
High-risk middle zones:
No-trade zones:
```

No trade is allowed unless there are at least 15 points of room to the next target zone.

## Step 2A - Location Grades

Grade the top locations before the open:

```text
Location 1:
Grade: A / B / C / F
Why this grade:
Expected playbook:
Invalidation:

Location 2:
Grade: A / B / C / F
Why this grade:
Expected playbook:
Invalidation:
```

Grading standard:

- A: mapped level plus order-flow history plus clean room to target.
- B: mapped level with partial confluence.
- C: level exists but regime or reward is unclear.
- F: middle, chase, or emotional idea.

Only A and selected B ideas can be considered live. C and F are observation only.

## Step 3 - DeepCharts Sentiment Read

From DeepCharts, record:

```text
Instrument:
Total volume:
Delta:
Delta %:
Delta NT:
Total Effort:
Delta Effort:
Profile shape: P / b / D / neutral
Buyer control / seller control / balanced chop:
```

Interpretation:

- Delta loud but ineffective = possible absorption/reversal.
- Delta efficient and accepting = possible continuation.
- Delta Effort rising = aggression is getting result.
- Delta Effort falling = aggression is losing effectiveness.
- Delta NT expanding = more participants joining.
- Delta NT stalling = same side pressing without recruitment.

## Step 4 - ES/NQ Priority

Score each 1-5:

| Factor | ES | NQ |
| --- | ---: | ---: |
| Setup quality at key zones |  |  |
| Catalyst strength |  |  |
| Volume environment |  |  |
| Range available |  |  |
| Cleanliness / lack of chop |  |  |
| Total |  |  |

Priority instrument:

Reason:

## Step 5 - Today's No-Trade Conditions

Write at least three before the open:

```text
1.
2.
3.
```

Examples:

- Do not trade if 9:30 footprint volume is at or below 10K.
- Do not trade if 5-minute footprint volume is below 20K.
- Do not trade if there are fewer than 15 points to the next zone.
- Do not trade if profile is balanced and no side has control.
- Do not trade if I cannot name the setup before entry.

## Prompt A - Pre-Market News And Range Scan

```text
Today is [DATE]. ES/NQ pre-market. News headlines: [PASTE]. Overnight high [X], overnight low [X], prior session POC [X], VAH [X], VAL [X]. Low-volume nodes: [X]. High-risk middle zones: [X]. Rate each catalyst high/medium/ignore for ES and NQ. Classify today's expected regime as balance, compression, expansion, trend, slow grind, or unclear. Which instrument do I prioritize? What are the top 2 key levels to watch at the open, what grade does each location deserve, and what would invalidate each idea?
```

## Prompt B - Pre-Market Sentiment Read

```text
DeepCharts pre-market data: Total volume [X], Delta [X], Delta% [X], Delta NT [X], Total Effort [X], Delta Effort [X]. Profile shape: [P/b/D/neutral]. Is delta loud but ineffective (absorption) or efficient and accepting (continuation)? Is Delta Effort rising or falling? Give me a one-line verdict: buyer control / seller control / balanced chop, and why.
```
