---
id: RULE_STOP_ENTRY_ONE_TICK
kind: rule
scope: long-lane-a
tags: [CONTINUATION, ANY, signal-bar-entry]
sources: [BLUEPRINT_HANDBOOK p.546, BLUEPRINT_HANDBOOK p.551, BLUEPRINT_HANDBOOK p.575, BLUEPRINT_HANDBOOK p.578, BLUEPRINT_HANDBOOK p.712]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.551 (BRK1 p84-85, p117-119): a plain buy stop order one tick above the signal bar; Ch.19 p.712 forbids uncapped market orders and caps a marketable limit at 3c over the ask; source says 'cut shares' for over-cap stops; v1 rule is skip (R03)
---
Conditions: A valid long signal bar has closed (price-action setups on the 5-min chart; one tick = one cent in stocks).
Entry: trigger one tick above the signal bar high; fill with a marketable limit capped at 3c over the ask (Ch.19). Against a strong trend, place the order only after the signal bar closes. Stocks: one-tick traps are common; a couple of ticks beyond the bar can work better (test on your own fills).
Stop: inside the Ch.19 cent caps; if the setup's stop is wider, skip (v1 rule R03).
Target and exits: not stated.
Time: Ch.19 windows.
Refuse if: unfilled: cancel and look for the next location; most stop orders never fill.
