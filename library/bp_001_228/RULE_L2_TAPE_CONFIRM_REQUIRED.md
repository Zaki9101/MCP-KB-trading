---
id: RULE_L2_TAPE_CONFIRM_REQUIRED
kind: rule
scope: long-lane-a
tags: [TAPE, ANY, confirmation]
sources: [BLUEPRINT_HANDBOOK p.008, BLUEPRINT_HANDBOOK p.009, BLUEPRINT_HANDBOOK p.179]
status: book-stated
conflicts: none
---
Conditions: 1-min to 5-min momentum entries need Level 2 and tape confirmation and volume that fits the setup (dry pullback, rising break). Displayed size is a hint; act only after prints test it and it holds or fails.
Entry: Enter on the setup trigger only when the book confirms (ask being taken, bid holding, prints speeding in the trade direction).
Stop: n/a.
Target and exits: n/a.
Time: Any time.
Refuse if: Chart-only breakout on 1-5 min charts: no trade. Any bid-side gap or a thin bid under a thick ask.
