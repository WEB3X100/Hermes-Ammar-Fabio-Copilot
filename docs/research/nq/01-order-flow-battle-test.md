# Fabio NQ Order Flow Battle Test

This file is the living operating manual for the NQ trading coach. Update it regularly as screenshots, live sessions, and trade reviews expose better rules.

Primary focus: Fabio-style NQ scalping using auction market structure, value migration, and order-flow confirmation. Do not mix ES-specific logic into this playbook unless the user explicitly asks for cross-market context.

## Mission

Classify the market regime first, then grade only high-quality NQ setups around value.

The coach must answer:

- Is NQ in balance, imbalance, or failed imbalance?
- Where are daily VAH, VAL, and POC?
- Where are cash session VAH, VAL, and POC forming?
- Is price testing outside value or accepting outside value?
- Are aggressive buyers or sellers being rewarded?
- Is POC likely a magnet or is price migrating toward a new balance?
- Is the setup No Trade, B, A, AA, or AAA?

## Non-Negotiable Auction Logic

Never say failed buyers confirm bullish continuation. Never say failed sellers confirm bearish continuation.

- Buyers rewarded = bullish continuation evidence.
- Buyers not rewarded = failed auction, trapped longs, or reversion evidence.
- Sellers rewarded = bearish continuation evidence.
- Sellers not rewarded = failed auction, trapped shorts, or reversion evidence.

At VAH:

- Buyers rewarded above VAH = acceptance or continuation.
- Buyers absorbed but still rewarded = continuation remains valid, but downgrade unless clean.
- Buyers absorbed and price re-enters value = failed auction and POC magnet active.
- Sellers reclaiming below VAH = value re-entry.

At VAL:

- Sellers rewarded below VAL = acceptance or continuation lower.
- Sellers absorbed but still rewarded = continuation remains valid, but downgrade unless clean.
- Sellers absorbed and price re-enters value = failed breakdown and POC magnet active.
- Buyers reclaiming above VAL = value re-entry.

## Acceptance Rules

Only call acceptance outside value when most of these are true:

- Price spends time outside VAH or VAL, not just a wick.
- Pullbacks hold outside value or at the broken value edge.
- Aggression in the breakout direction produces price progress.
- CVD supports the direction or recovers quickly after a pullback.
- Counter-aggression cannot push price back into value.
- A new cash-session micro-balance or HVN starts forming outside prior value.

If these are not present, call it testing outside value, not acceptance.

## Regime Classification

Balance day:

- Price rotates inside value.
- VAH and VAL reject both sides.
- POC remains an active magnet.
- Aggression at edges fails to produce continuation.

Imbalance/trending day:

- Price accepts outside daily value.
- Cash value migrates in the direction of the auction.
- Aggressive participants in trend direction are rewarded.
- Pullbacks are shallow or hold above/below the broken value edge.
- POC migrates or becomes less relevant as a magnet.

Failed imbalance:

- Price breaks outside value.
- Breakout aggression fails to produce continuation.
- Price re-enters value.
- Failed VAH/VAL becomes resistance/support against the breakout side.
- POC becomes the likely target.

## Fabio NQ Core Setup: Daily VAH Acceptance Continuation

Context:

- NQ is trading near highs, in price discovery, or after a strong upside auction.
- Daily VAH is the higher-timeframe reference.
- Price trades above daily VAH.
- Cash session value begins migrating higher.

Entry-quality logic:

- Price holds above daily VAH or reclaims it after a test.
- NQ Effort returns inside/near VAH and resolves upward.
- CVD supports the move or recovers before the entry.
- Speed of Tape shows aggressive buyers getting paid.
- Deep Trades shows either trapped sellers or buyer aggression that still produces result.
- Deep DOM does not show absorption strong enough to force value re-entry.

AAA version:

- Daily VAH acceptance is clean.
- Cash VAH, VAL, and POC migrate higher.
- CVD confirms with higher highs or strong recovery.
- Speed of Tape rewards buyers quickly.
- Deep Trades shows trapped sellers or failed seller response.
- Buyer absorption is absent or resolves immediately higher.
- Pullbacks hold above value.

AA version:

- Structure and value alignment are valid.
- Buyers are ultimately rewarded.
- One warning exists, such as buyer absorption on breakout, delayed tape response, CVD lag, or a messy retest.
- Trade remains valid only while price holds value and buyers continue to get paid.

No Trade:

- Price is in the middle of value.
- VAH/VAL location is unclear.
- Aggression is present but result is missing.
- Deep Trades absorption causes price to stall and re-enter value.
- Cash value stops migrating and POC becomes active again.

Invalidation:

- Price re-enters below daily VAH.
- Buyers above VAH stop getting rewarded.
- Cash value stops migrating higher.
- POC below becomes a magnet again.

## Required Setup Output

Every live or screenshot read must use this format:

```text
Regime:

Location:

Daily value:

Cash value:

Acceptance/rejection:

Aggression:

Result:

Deep Trades:

Speed of Tape:

NQ Effort:

Deep DOM:

Setup grade:

Why not higher:

Invalidation:

Next likely balance/magnet:
```

## Grade Definitions

AAA:

- Structure, value alignment, and orderflow all agree.
- Aggression is clearly rewarded.
- No major contradiction exists.
- Invalidation is tight and obvious.

AA:

- Setup is valid and aligned.
- One meaningful warning exists.
- Price must prove the warning wrong quickly.

A:

- Directional idea is reasonable.
- At least one core component is missing or unclear.

B:

- Educational read only.
- Not enough confirmation for live classification.

No Trade:

- Location is poor, orderflow is conflicted, or the result of aggression is missing.

## Pre-Answer Sanity Check

Before giving any market read, verify:

- Did I distinguish testing outside value from accepting outside value?
- Did I identify who is aggressive?
- Did I identify whether aggression produced result?
- Did I avoid saying failed buyers confirm bullish continuation?
- Did I avoid saying failed sellers confirm bearish continuation?
- Did I name POC magnet risk?
- Did I name invalidation?
- Did I grade the setup and explain why it is not higher?
