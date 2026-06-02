---
name: fabio-weighted-story-builder
description: Use when building an ES/NQ market story from supplied DeepCharts values, screenshots, pre-market levels, Fabio/team terminology, backtest observations, and weighted confirmations. This skill helps rank evidence, compare permutations, explain why a setup is wait/watch/ready/invalid, and improve coach-only decision support without giving blind trade calls.
---

# Fabio Weighted Story Builder

## Core Rule

Build the story from evidence in weighted order. Do not start with opinion.

Separate:

- observed data
- interpretation
- confidence
- rulebook implication
- wait/trade-readiness discipline

Never invent levels, volume, delta, or screenshot details.

## Evidence Weighting

Default weights:

| Evidence | Weight | Meaning |
| --- | ---: | --- |
| Location at key level | 5 | No meaningful location usually means no trade. |
| Regime fit | 5 | The model must match the market condition. |
| Effort versus result | 5 | Aggression getting paid vs absorbed is core. |
| Trapped participants | 4 | Stronger when the pain is obvious. |
| Volume / participation | 4 | Protects from dead tape. |
| Delta / Delta Effort / Delta NT | 4 | Useful only at the right location. |
| Room to target | 4 | No 15+ points of juice means skip. |
| Pre-market thesis alignment | 3 | Helpful, but not enough alone. |
| Screenshot clarity | 3 | If it cannot be journaled, it is probably not clean. |
| Trader state | blocker | Revenge, boredom, or daily stop overrides setup quality. |

Update weights only when Ammar supplies new reviewed examples or team feedback.

## Story-Building Order

1. State the observed data only.
2. Identify regime.
3. Grade location.
4. Name the setup or mark it candidate-only.
5. Compare effort versus result.
6. Identify who is trapped and who is rewarded.
7. Check volume, room to target, and timing.
8. Run 2-4 alternate interpretations.
9. Pick the highest-weight story.
10. Give readiness: WAIT, WATCH, READY, or INVALID.

## Permutation Discipline

Compare possible stories quickly:

```text
Story A: absorption reversal
Story B: efficient continuation
Story C: balance edge fade
Story D: middle chop / no-trade
```

For each story, score only the evidence provided:

```text
Location:
Regime fit:
Effort/result:
Trapped side:
Volume:
Room:
Timing:
Blocker:
```

Choose the story with the strongest weighted evidence. If two stories are close, default to `WAIT`.

## Output Format

```text
Readiness: WAIT / WATCH / READY / INVALID
Dominant story:
Observed:
Interpretation:
Confidence: low / medium / high
Why not the alternate story:
Rulebook implication:
Next evidence needed:
```

## Reference Loading

Read `references/evidence-weights.md` when updating or auditing the weighting model.

Read `references/story-patterns.md` when adding Fabio/team story templates from screenshots, backtests, mentorship notes, or reviewed trade examples.
