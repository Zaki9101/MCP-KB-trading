---
id: EXIT_TIME_STOP
kind: exit
scope: long-lane-a
tags: [EXIT, ANY, time-stop]
sources: [BLUEPRINT_HANDBOOK p.441, BLUEPRINT_HANDBOOK p.713]
status: conflict
conflicts: CEP p.103 via BLUEPRINT_HANDBOOK p.441: under 1 minute; PB p.197: 30 minutes; PB p.53-54: hours too long
---
Conditions: Trade not progressing.
Entry: Not applicable.
Stop: Write the time stop per setup before entry.
Target and exits: Level 2 momentum entry: about 1 minute without progress = out. Trade2Hold: 30 minutes without progress = out. Never hold a stuck trade for hours.
Time: Any.
Refuse if: Holding past the written time stop.
