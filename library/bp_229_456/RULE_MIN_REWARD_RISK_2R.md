---
id: RULE_MIN_REWARD_RISK_2R
kind: rule
scope: long-lane-a
tags: [RISK, ANY, reward-risk]
sources: [BLUEPRINT_HANDBOOK p.427, BLUEPRINT_HANDBOOK p.433, BLUEPRINT_HANDBOOK p.441, BLUEPRINT_HANDBOOK p.446, BLUEPRINT_HANDBOOK p.714]
status: conflict
conflicts: TR p.144 and p.256 via BLUEPRINT_HANDBOOK p.441: open-break scalpers take 1:1 to 2:1
---
Conditions: Every trade, measured to the first target. 1R = dollar risk to the stop.
Entry: At least 2.0 reward:risk to the first target. 1.0-2.0 only at half size with a logged 60%+ win rate on that setup (editor note). Below 1.0 never. Level plays keep the room test of about 5x.
Stop: Not applicable.
Target and exits: 2.0R is the first-batch target, not a cap; the rest is trailed.
Time: Any.
Refuse if: First target under 1.0R; under 2.0R without the logged record.
