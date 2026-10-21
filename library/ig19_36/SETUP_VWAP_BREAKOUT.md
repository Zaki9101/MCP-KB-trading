---
id: SETUP_VWAP_BREAKOUT
kind: setup
scope: long-lane-a
tags: [VWAP, MORNING, vwap-breakout]
sources: [IG-20 panel 1]
status: sheet-stated
conflicts: none
---
Conditions: Base under VWAP; green candle CLOSES above on rising volume (quiet base, volume up).
Entry: On that close, if the 4 real-break ticks hold and L2 + tape agree.
Stop: Under VWAP, resting, in the cap (10c on $1-$8, 20c any stock); close under = out.
Target and exits: T1 at 2.0R+, bank 25-50%, stop to entry.
Time: 9:35-11:00.
Refuse if: Weak-volume poke; any real-break tick missing.
