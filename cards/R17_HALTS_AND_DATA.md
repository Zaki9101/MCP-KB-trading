---
id: R17_HALTS_AND_DATA
tags: [always]
source: BP p.712 (L2 and tape confirmation), Plan 1 section 5 (stale data and halts; the thresholds are config values)
conflict: none material
---
Rule: no entries during a halt or a LULD pause. Stale market data (quote, level 2, or bars older than the config limit) means no entries. Missing level 2 or tape means no momentum entry. Resting broker stops stay live.
Refuse if: halted (PASS, name R17). Data stale or missing (INSUFFICIENT_DATA, name R17).
If the screen capture is unreadable, answer INSUFFICIENT_DATA and ask for a new capture. Never guess the number.
