---
id: RISK_SMALLEST_LIMIT_SIZING
kind: risk
scope: long-lane-a
tags: [RISK, ANY, sizing]
sources: [IG-36 panels 5-6]
status: sheet-stated
conflicts: source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: Shares = risk / stop, round down; use the smallest limit. Tier1 5% = $250 (of $5k daily stop).
Entry: n/a
Stop: Stop cap 10c ($1-$8)/20c; wider = skip (v1 rule R03).
Target and exits: n/a
Time: Any.
Refuse if: Never raise a cap.
