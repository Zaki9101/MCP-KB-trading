---
id: RULE_ENTRY_METHOD_BY_MARKET_STRENGTH
kind: rule
scope: long-lane-a
tags: [RISK, ANY, entry-method]
sources: [BLUEPRINT_HANDBOOK p.285, BLUEPRINT_HANDBOOK p.428, BLUEPRINT_HANDBOOK p.429, BLUEPRINT_HANDBOOK p.430, BLUEPRINT_HANDBOOK p.431, BLUEPRINT_HANDBOOK p.712]
status: conflict
conflicts: TR p.123-127 via BLUEPRINT_HANDBOOK p.429-430: buy before the trigger whenever the market is very strong
---
Conditions: Any trigger entry. A 1-5 min chart break with no Level 2 or tape confirmation is not a trade.
Entry: Default regular (on the trigger, tape confirms) or conservative (held retest). Aggressive, before the trigger, only if all hold: market trending your way, buying pressure rising (ask thinning), gradual approach, Tier1 or half the planned lot. Never aggressive on an opening-range break.
Stop: At the structural level for the chosen method; a better price is never a reason for more shares.
Target and exits: Not applicable.
Time: Any.
Refuse if: Sharp run into the trigger (makes traps, not breakouts); chart-only trigger.
