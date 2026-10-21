---
id: R07_GIVEBACK
tags: [always, risk, manage]
source: BP p.455, p.491, p.463; IG-03; IG-24 (off until a profitable open)
conflict: 30% (BP p.133, p.355-356) and 10-15% (CAM p.131) appear in other books; the Ch.19 staged rule governs. 50% is rejected (BP p.455).
---
Rule: measured on the day's peak P&L, marked to market. Stage 1 at 15% given back: 10-minute break, then half size and A-grade only. Stage 2 at 30% given back: close everything and stop for the day. The rule is dormant until the peak P&L passes the profitable-open threshold in config.
Refuse if: stage 1 is active and the entry is inside the 10-minute break (PASS, name R07). Stage 2 is active (PASS, name R07, and for an open trade: EXIT).
Management: stage 2 on an open position gives EXIT. Stage 1 on an open position gives HOLD and no new entries.
