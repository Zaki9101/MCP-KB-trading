---
id: RULE_CHASE_CAP_ORDER_TYPE
kind: rule
scope: long-lane-a
tags: [RISK, ANY, order-type]
sources: [BLUEPRINT_HANDBOOK p.428, BLUEPRINT_HANDBOOK p.712]
status: conflict
conflicts: TR p.170 via BLUEPRINT_HANDBOOK p.428: chase 3-5c above the trigger, rarely 5-10c
---
Conditions: Placing an entry order.
Entry: Limit at the level by default. Marketable limit capped at 3c over the ask only on a confirmed momentum signal with the stop pre-set. Missed trigger: chase at most 3c (5c only after logged results at 3c). Never an uncapped market order. Below $5, buy mostly on the bid.
Stop: Pre-set before the order is sent.
Target and exits: When scaling out of a surging stock, a limit sell on the ask earns 1-2c more per share than hitting the bid.
Time: Any.
Refuse if: Price already beyond your written maximum.
