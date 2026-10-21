---
id: RULE_VWAP_REAL_BREAK_4_TICK
kind: rule
scope: long-lane-a
tags: [VWAP, MORNING, real-break]
sources: [IG-20 real vs false box]
status: sheet-stated
conflicts: none
---
Conditions: Real break = buy only if all 4: (1) volume above the candles before; (2) a full 5-min candle closes above VWAP; (3) higher highs/lows, no exhaustion; (4) no major resistance rejected (prior close, 50 SMA, daily level, premarket high).
Entry: Buy when all 4 tick.
Stop: Under VWAP, in cap.
Target and exits: See setup cards.
Time: 9:35-11:00.
Refuse if: Any of the 4 missing.
