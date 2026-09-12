# Scenario Building Skill

This file stores the pre-market scenario-building logic that follows Volume Profile Framing. Do not build scenarios until the value map is clear.

## Core Objective

Turn the volume profile frame into conditional NQ scenarios:

- Balance mean reversion
- Failed auction back to POC
- Acceptance outside value
- Imbalance continuation toward the next POC/HVN
- LVN speed move / liquidation path
- No-trade chop zone

## March 24 Case Study

Base scenario from user:

- If price remains between the red upper zone and blue lower zone, treat the day as balanced.
- If price weakens at either extreme, look for mean reversion back to POC.
- If price makes a strong momentum move through either side, wait for pullback continuation toward the next POC.

Coach refinement:

- Balance scenario is valid only while price keeps rejecting the red/blue extremes and returning toward the middle/POC.
- Do not short the red zone just because it is a red zone. Short only if buyers fail there and price cannot accept above.
- Do not long the blue zone just because it is a blue zone. Long only if sellers fail there and price cannot accept below.
- If price breaks the blue LVN with speed and sellers are rewarded, the blue zone flips from support candidate into a downside continuation gateway.
- If price accepts above the red zone, the stacked value/POC area becomes a launch base, not a rejection point.
- If price is in the middle of balance, wait. The edge is poor unless orderflow shows a clear failed auction or POC rejection.

## Required Scenario Output

Use this template:

```text
Scenario Build

Primary Regime:

Scenario A - Balance / Mean Reversion:
Trigger:
Confirmation:
Target:
Invalidation:

Scenario B - Upside Acceptance / Continuation:
Trigger:
Confirmation:
Target:
Invalidation:

Scenario C - Downside Acceptance / Continuation:
Trigger:
Confirmation:
Target:
Invalidation:

No-Trade Conditions:

What Would Change My Mind:
```

## Scenario Rules

- Every scenario must be conditional. Use if/then language.
- A zone is not a trade. A reaction at a zone creates the trade idea.
- For mean reversion, require failed aggression at an extreme plus re-entry or rotation back toward POC.
- For continuation, require acceptance outside value plus a pullback that holds.
- For LVN continuation, require speed through the LVN and failure to reclaim it.
- For squeeze/liquidation scenarios, require trapped aggression and price moving against that side.
- If price is between major extremes and near no clear edge, label it no trade.

## Fabio-Style Scenario Priority

1. Identify the active value area.
2. Identify whether price is inside value or outside value.
3. If inside value, default to balance logic and POC magnet.
4. If outside value, decide whether price is testing or accepting.
5. If testing fails, scenario becomes reversion to POC.
6. If acceptance holds, scenario becomes continuation to next POC/HVN.
7. Only after this should orderflow be used to grade the setup.
