[data-signals.md](https://github.com/user-attachments/files/34104406/data-signals.md)
# The Signals · FinWise

> Module 4 · Data & Analytics. The data pattern you found and the indicators you'll steer by.

## The data pattern

The headline metric is a 2% trial-to-paid conversion rate (98.0% of trials never convert), but the real pattern behind it is a flat line, closest to a Ceiling: conversion stayed between 1.87% and 2.08% in all 13 months while modeling usage ranged from 10.8% to 58.3%, session duration fell about 5 minutes in Jul 2024, and sessions per user dropped from 9 to 3 and recovered, because (my revised hypothesis, untested) conversion is not driven by the in-product usage signals I picked, so the leak sits at the decision to pay itself, and my earlier idea that trial users work alone with nothing shared to keep is still an untested assumption, since the data has no invite or sharing column. Monthly averages also can't show what individual trial users do, so I'd need user-level trial data before betting on any leading indicator.

_Metric patterns: Conversion, This looks like a Ceiling pattern, though not a clean one, because it never moved before flatlining: it stays between 1.87% and 2.08% in all 13 months, and its largest month-to-month change is only 0.13 points. There is no cliff and no decline, so I flagged it as a flat line at about 2% instead.. Modeling usage, This doesn't fit cleanly, so I flagged it: it is a noisy upward trend, from 10.8% (Nov 2023) to 58.3% (Apr 2024), then 58.1% (Sep 2024). The only sharp move is Oct 2024, down 22 points to 36.0%, which could be the start of a Cliff, but it is a single month, so I can't call it yet.. Import usage, This looks closest to a Ceiling because it dipped, recovered and then held in a band: it fell about 12 points in Jan 2024 (42.7% to 30.6%), stayed near 30–32% through Mar, then recovered and has held at 41–45% since Jul 2024. I flagged it because the early dip looks like a Cliff that reversed.. Session duration, This looks like a Cliff pattern because it held at 11–14 minutes from Dec 2023 to Jun 2024, then dropped about 5 minutes (12.1 to 7.0) in Jul 2024, and fell further to 5.1 in Aug. It has partly recovered to 8.95 minutes by Oct, so it hasn't flatlined.. Sessions/user, This doesn't fit cleanly, so I flagged it: it is a U-shape. It fell steadily from 9 to 3 between Oct 2023 and Jan 2024, then recovered to 9 by Sep and Oct 2024. The decline looks like a Slow Leak, but it lasted only three months and reversed, so I wouldn't call it one.._

_Correlation test: Revised._

_____

## Leading indicators

- **% of trial users who connect their bank and see their own categorized cash position and runway in their first session:** It is the North Star's import-to-output step in FinWise terms (my M2 Aha moment), and a user who sees their real numbers early has a reason to pay at the paywall.
- **% of trial users who invite their accountant, bookkeeper or co-owner within 7 days:** It tests my M1 collaboration-loop bet: a small-business owner who shares their cash picture with their accountant has work to pay to keep.

_____

## Lagging indicators

- **Trial → paid conversion (baseline ~2%):** It is the Revenue-stage leak from M1 (98.0% of trials never convert), and it only rises if both leading indicators move first.

_____

