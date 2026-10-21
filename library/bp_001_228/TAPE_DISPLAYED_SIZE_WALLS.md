---
id: TAPE_DISPLAYED_SIZE_WALLS
kind: tape
scope: long-lane-a
tags: [TAPE, ANY, walls]
sources: [BLUEPRINT_HANDBOOK p.058, BLUEPRINT_HANDBOOK p.095, BLUEPRINT_HANDBOOK p.096]
status: book-stated
conflicts: none
---
Conditions: Displayed size is a hint, never a trigger. Ignore large orders far from price until price nears them. Distance from the inside market: more than 3c = unconfirmed; more than 5-10c = likely fake, ignore; 20-50c+ = fake. Fake signs together: abnormal size for that book, one market maker, no tape interaction, cancels on approach.
Entry: Big ask ahead: wait for its size to decrease and enter only when little remains; a wall counts only after prints test it.
Stop: Use a level as stop reference only if prints confirm it.
Target and exits: n/a.
Time: Any time.
Refuse if: Trading a wall that prints have not tested. A thick ask zone over a weak bid.
