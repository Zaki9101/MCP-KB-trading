---
id: TAPE_HIDDEN_BUYER
kind: tape
scope: long-lane-a
tags: [TAPE, ANY, hidden-orders]
sources: [IG-12]
status: sheet-stated
conflicts: none
---
Conditions: A buyer's bid of the same size and price unchanged after you sell 50 is support.
Entry: not stated
Stop: Use the unchanged bid as the long stop.
Target and exits: not stated
Time: not stated
Refuse if: Chasing a hidden seller ask that never shrinks on green prints: exit longs.
