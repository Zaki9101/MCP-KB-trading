---
id: R06_DAILY_LOSS_AND_TIER1
tags: [always, entry, risk]
source: BP p.452 (50% of median winning day; period stop 30%), BP p.477 (10% of account line), IG-03 and IG-36 (Tier 1 = 5% of daily max), IG-24 (per-idea 25%)
conflict: daily loss $100, $150, $200 and 10% of account appear in other sections (BP p.472, p.476, p.477); this card uses the Ch.19 formula and the 10%-of-equity ceiling from Plan 1
---
Rule: daily max loss = the lower of (a) 50% of the median gross winning day and (b) 10% of account equity. Until enough winning days exist, use the bootstrap value in config, capped at 10% of equity. Tier 1 risk = 5% of daily max. Per-idea risk at most 25% of daily max. Period stop: 30% of the daily max lost in a window means no entries in that window.
Refuse if: no room left in the daily max (PASS, name R06). Risk budget gives fewer shares than the minimum (PASS, name R06). Equity or the median value is not in config (INSUFFICIENT_DATA, name R06).
