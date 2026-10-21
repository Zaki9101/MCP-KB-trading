---
id: RISK_SIZE_TO_LIQUIDITY
kind: risk
scope: long-lane-a
tags: [RISK, ANY, liquidity]
sources: [BLUEPRINT_HANDBOOK p.458, BLUEPRINT_HANDBOOK p.482, BLUEPRINT_HANDBOOK p.490]
status: book-stated
conflicts: none
---
Conditions: Fit size to the stock's volume and to where you can exit if wrong. Ask "what is my downside?" before sizing. Example error: 2,000 shares in a 20,000-share stock (10% of its volume).
Entry: size within tier and fitted to liquidity; if extra size cannot exit at the same reward:risk, do not add it.
Stop: not stated (the exit test assumes you can leave at your stop).
Target and exits: a big winner is also harder to exit; expand the timeframe when slippage damages reward:risk.
Time: any.
Refuse if: wide spread plus thin depth. No book gives a numeric volume limit: set your own (editor note).
