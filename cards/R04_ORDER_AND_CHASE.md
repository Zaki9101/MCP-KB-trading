---
id: R04_ORDER_AND_CHASE
tags: [always, entry]
source: BP p.712, p.736
conflict: the book does not name HIT_ASK, JOIN_BID, HIT_BID or JOIN_ASK; do not use those labels
---
Rule: limit order at the level. Marketable limit at most 3 cents over the ask, only on a confirmed momentum signal with a stop set before entry. Missed trigger: chase at most 3 cents. No market orders. Fill slippage budget: 5 cents (loss budget, not an offset).
Refuse if: the planned order is a market order, or the chase is above 3 cents over the trigger (PASS, name R04).
