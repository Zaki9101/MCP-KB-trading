---
id: RISK_HARD_STOP_ORDERS
kind: risk
scope: long-lane-a
tags: [RISK, ANY, stop-order]
sources: [BLUEPRINT_HANDBOOK p.713, IG-01, IG-02]
status: book-stated
conflicts: none
---
Conditions: Resting broker stop on 100% of size above Tier1, when holding through news, and after any violated stop. A tape-based mental stop is allowed only on starter size in liquid names with a hard catastrophic stop behind it.
Entry: not stated
Stop: Hard stop stays live on every share.
Target and exits: not stated
Time: not stated
Refuse if: Mental-only stop on more than starter size.
