# Journal Memory Plan

## Purpose

The journal should become compounding trader memory, not a static graveyard of notes.

Every reviewed trade can produce a small memory candidate that improves future pre-market and live-session alerts.

## Memory Candidate Format

```text
Memory candidate:
Why it matters:
Evidence:
Applies to:
Expires/review date:
```

## What Should Become Memory

Save:

- repeated mistakes,
- repeated successful setup behavior,
- recurring emotional triggers,
- market conditions that damage decision quality,
- alerts that improved patience,
- no-trade rules that protected capital.

Do not save:

- one-off emotions,
- private account details,
- raw P&L exports,
- broker/account credentials,
- unreviewed claims.

## Future Sidecar

Later, add Claude Mem or a LightRAG sidecar.

Nightly process:

1. Read reviewed journal summaries.
2. Compress into memory candidates.
3. Index by setup, instrument, session, mistake, and rule.
4. Retrieve relevant lessons during next pre-market brief.

Example future warning:

```text
Ammar, last time this session opened after a gap with unclear levels, you overtraded. Keep alerts to Watch only until AAA confirmation appears.
```
