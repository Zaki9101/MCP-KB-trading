---
id: RULE_VWAP_TRADE_GATES
kind: rule
scope: long-lane-a
tags: [VWAP, MORNING, gates]
sources: [IG-20 header]
status: sheet-stated
conflicts: none
---
Conditions: L2 and tape must confirm every VWAP trade; chart-only = no trade. First target 2.0R or more.
Entry: Per setup.
Stop: Resting stop in the cap (10c on $1-$8, 20c any stock); about 30c after size-up gates; wider = skip.
Target and exits: T1 at 2.0R+, bank 25-50%, stop to entry.
Time: Window 9:35-11:00; VWAP fades 10:30-11:00.
Refuse if: No L2/tape confirm; stop wider than cap.
