---
id: RISK_TIER_SIZING_CEILING
kind: risk
scope: long-lane-a
tags: [RISK, ANY, position-size]
sources: [BLUEPRINT_HANDBOOK p.457, BLUEPRINT_HANDBOOK p.458, BLUEPRINT_HANDBOOK p.461, BLUEPRINT_HANDBOOK p.463, BLUEPRINT_HANDBOOK p.470, BLUEPRINT_HANDBOOK p.471, BLUEPRINT_HANDBOOK p.715]
status: conflict
conflicts: BLUEPRINT_HANDBOOK p.470 (CP worksheet): risk approx. 5% of account per trade against a 10% daily cap; p.472 (NB sim): $50 per trade against $150 daily (33%); p.457 (PB): A+ at least 30% of the daily stop
---
Conditions: Tier = percent of the daily stop. Tier1 = 5% (first lot); Tier2 10%, Tier3 15%, Tier4 20%.
Entry: shares = tier dollar risk / stop distance. Hard ceiling 25% of the daily stop for all lots of one idea, A+ setups with a documented record only. First lot at most 300 shares. Each morning, shares you can afford are only a ceiling; cut to the dollar risk. Leverage changes share count, never dollar risk.
Stop: per the cent caps.
Target and exits: never size a trade so it can erase more than one or two previous winners.
Time: any; change per-trade risk intraday only in small steps.
Refuse if: all-in sizing; a size that breaks the 25% ceiling.
