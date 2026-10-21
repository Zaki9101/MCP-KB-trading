---
id: SETUP_VWAP_BREAK_LONG
kind: setup
scope: long-lane-a
tags: [VWAP, MORNING, vwap-break]
sources: [IG-05, IG-04]
status: sheet-stated
conflicts: none
---
Conditions: Stock basing below VWAP, then a green candle closes above VWAP with volume rising.
Entry: Close over VWAP.
Stop: Close back through VWAP; inside cap.
Target and exits: Ride; half if far (LOD / 50-200 SMA on the sheet).
Time: not stated
Refuse if: A wick above VWAP with no close; chasing before it confirms.
