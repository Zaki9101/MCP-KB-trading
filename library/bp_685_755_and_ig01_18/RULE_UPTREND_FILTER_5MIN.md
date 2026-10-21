---
id: RULE_UPTREND_FILTER_5MIN
kind: rule
scope: long-lane-a
tags: [PULLBACK, MORNING, trend-filter]
sources: [IG-08, IG-05]
status: sheet-stated
conflicts: none
---
Conditions: 5-min uptrend means price above 9 EMA, 20 EMA and VWAP, near the high of day. Daily above 5 SMAs.
Entry: First higher high with L2 confirming.
Stop: not stated
Target and exits: not stated
Time: not stated
Refuse if: Lower low or red close: wait. Below VWAP: no.
