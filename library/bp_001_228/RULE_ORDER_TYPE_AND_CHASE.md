---
id: RULE_ORDER_TYPE_AND_CHASE
kind: rule
scope: long-lane-a
tags: [RISK, ANY, execution]
sources: [BLUEPRINT_HANDBOOK p.008, BLUEPRINT_HANDBOOK p.030, BLUEPRINT_HANDBOOK p.161, BLUEPRINT_HANDBOOK p.209, BLUEPRINT_HANDBOOK p.212]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.173 (NB) buys at ask +5c and sells at bid -5c; p.161 (NB) allows 5c slippage; p.209 (TR) chases 3-5c. Ch.19 p.712: cap 3c.
---
Conditions: Execution rule for every entry and exit.
Entry: Marketable limit only on a confirmed signal with a pre-set stop: default offset +$0.01-$0.02 over the ask (under the bid on exits), hard cap 3 cents. $0.05 only after a logged record at your size where 3 cents repeatedly failed to fill. Missed the trigger: chase at most 3c.
Stop: Never an uncapped market order.
Target and exits: n/a.
Time: Any time.
Refuse if: Ask re-pricing faster than a 3-cent order fills: pass the trade rather than raise the offset.
