# Volume Profile Framing Skill

This file stores the rules and case studies for framing NQ before scenario building. Do not move to orderflow or execution until the profile frame is clear.

## Core Objective

Frame the auction using value first:

- Prior session VAH, VAL, and POC
- Overnight VAH, VAL, and POC
- Current day developing VAH, VAL, and POC
- Composite profile HVNs and LVNs
- Multi-session value overlap
- Balance extremes
- POC magnet risk
- Areas where price may reject, accept, or migrate to the next balance

## March 24 Case Study

User framing:

- The day looks balanced while price remains between the upper red zone and lower blue zone.
- The blue zone contains a strong low-volume node aligned with current day VAL.
- The red zone contains three value areas and two POCs, making it a strong potential rejection zone.
- If price remains in balance and shows weakness at extremes, the preferred read is mean reversion back to POC.
- If price breaks either side with strong momentum, wait for a pullback and look for continuation toward the next POC.

Coach additions:

- Treat the red zone as a high-confluence supply/rejection shelf only if price fails to accept above it.
- Treat the blue zone as a lower balance edge, not automatic support. It becomes support only if sellers fail below/inside it.
- If price trades in the middle between the red and blue zones, it is likely poor location unless POC rejection or strong imbalance appears.
- The large composite profile on the right suggests a broader auction with important magnets above current price. If price accepts above the red zone, do not keep forcing mean reversion.
- The lower blue zone has LVN characteristics. If price slices through it with speed, it can become a continuation area rather than a bounce zone.

## Required Volume Profile Frame Output

Use this template before scenario building:

```text
Volume Profile Frame

1. Higher-Timeframe Value:
2. Overnight Value:
3. Current Auction Location:
4. Upper Balance Edge:
5. Lower Balance Edge:
6. Key HVNs:
7. Key LVNs:
8. POC Magnet:
9. Acceptance Areas:
10. Failed Auction / Rejection Areas:
11. Balance or Imbalance Read:
12. Clean Trade Locations:
13. No-Trade Zones:
```

## Framing Rules

- Multiple overlapping value areas increase the importance of a zone.
- Multiple POCs near one zone make that zone a stronger magnet or rejection shelf.
- LVNs are not automatically support/resistance. They are decision points.
- HVNs/POCs are magnets when price remains inside balance.
- VAH and VAL are tradeable edges only if price reacts there.
- Middle of balance is usually a no-trade area.
- If price accepts outside value, stop treating old POC as the primary magnet.
- If price re-enters value after a failed breakout, POC magnet becomes active again.

## Decision Language

Use precise language:

- "Testing above value" means price is outside value but acceptance is not proven.
- "Accepting above value" means price holds outside value, pullbacks hold, and value begins migrating.
- "Rejecting above value" means price fails outside value and re-enters.
- "Balanced" means price is rotating between known value extremes.
- "Imbalanced" means price is migrating away from accepted value.
