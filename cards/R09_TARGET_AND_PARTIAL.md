---
id: R09_TARGET_AND_PARTIAL
tags: [always, entry, manage]
source: BP p.714, p.460 (first target at least 2.0R; 1.0-2.0 only at half size with a logged 60% win rate), BP p.446 and p.714 (bank 25-50% at the first target), BP p.714 (ladders need 500+ shares)
conflict: scale-out schemes differ (BP p.442, p.446); the Ch.19 scheme governs
---
Rule: the first target is at least 2.0R (reward to risk). Between 1.0R and 2.0R only at half size with a logged win rate of 60% or more; in v1 this is PASS. Below 1.0R never. At the first target, bank 25 to 50% (default 50%). Ladders (more than one partial) need 500 or more shares. Under 500 shares: one partial only.
Refuse if: first target below 2.0R (PASS, name R09). Ladder requested under 500 shares (PASS, name R09).
Management: price reaches the first target and no partial is taken: TAKE_PROFIT, name R09.
