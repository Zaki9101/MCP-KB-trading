---
id: RULE_VWAP_FALSE_BREAK_NO_BUY
kind: rule
scope: long-lane-a
tags: [VWAP, MORNING, false-break]
sources: [IG-20 real vs false box, IG-20 panel 2]
status: sheet-stated
conflicts: none
---
Conditions: False break (fade, all 5 tick): weak volume on the attempt (#1 sign); candle wicks above VWAP with no close above and drops back; rejects a major resistance (most reliable); late morning 10:30-11:00; sellers hit the bid, red prints speed up.
Entry: Do not buy. Short side is out of scope.
Stop: n/a
Target and exits: n/a
Time: 10:30-11:00 per Ch. 19.
Refuse if: Weight most: #3 resistance rejection and #5 tape. No L2/tape confirm = no trade.
