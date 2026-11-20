# Lesson 21: Spot the statistical lie

**Student practice sheet**

Name: ____________________

These five claims come from the Edmonton bike shop you analysed in Lessons 22 and 23. Each one is built on a real number from `bike_shop_orders.csv` or `workshop_jobs.csv`, and each one gives the wrong impression. The evidence under each claim is everything you need; you don't have to run any code.

For each claim, work through the same three steps as the "Small Group Practice" slide:

1. Identify the technique being used (mean vs median, a percentage without context, a small or biased sample, correlation treated as causation, or a cherry-picked comparison). Some claims use more than one.
2. Name the missing information you'd need before believing it.
3. Rewrite the claim using only what the evidence supports. Use the four parts from "A reliable re-write has 4 parts": the actual number or rate (quantity), the baseline or comparison (reference), the sample, population and time period (scope), and no causal or universal language unless the evidence justifies it (caution).

## Claim 1

The owner's newsletter: "The typical order at our shop is \$610."

Evidence: the order file has 1,189 sales from November 2025 to October 2026 (duplicates, the 500-bike data-entry error and the one return removed). The mean order value is \$609.71 and the median is \$87. Bikes and e-bikes, which usually cost over \$1,000, make up 305 of the 1,189 orders. 912 orders (77%) are below the mean.

Explain which technique the claim uses.

*Your answer:*

Explain what information is missing.

*Your answer:*

Rewrite the claim.

*Your answer:*

## Claim 2

A social media post in March: "E-bike orders are up 1,100% this month!"

Evidence: e-bike orders by month were Nov 0, Dec 5, Jan 3, Feb 1, Mar 12, Apr 16, May 16, Jun 16, Jul 17, Aug 10, Sep 9, Oct 4.

Explain which technique the claim uses.

*Your answer:*

Explain what information is missing.

*Your answer:*

Rewrite the claim.

*Your answer:*

## Claim 3

A sign by the till in July: "Orders up 497%! Edmonton is riding with us."

Evidence: total orders by month were Nov 55, Dec 147, Jan 37, Feb 29, Mar 68, Apr 148, May 143, Jun 173, Jul 110, Aug 102, Sep 87, Oct 90. The sign compares June with February. The shop's order file starts in November 2025, so there's no earlier June to compare with.

Explain which technique the claim uses.

*Your answer:*

Explain what information is missing.

*Your answer:*

Rewrite the claim.

*Your answer:*

## Claim 4

The workshop's web page: "E-bike diagnostics: our top-rated service, with a perfect 5.0 average rating in March."

Evidence: customers can rate a job from 1 to 5 after pickup, and rating is optional. Ratings by service for March to October 2026:

| Service | Jobs | Jobs rated | Mean rating |
|---|---|---|---|
| Flat repair | 118 | 92 | 4.39 |
| Basic tune-up | 123 | 80 | 4.35 |
| Brake service | 65 | 44 | 4.23 |
| Full tune-up | 82 | 61 | 4.08 |
| E-bike diagnostic | 42 | 25 | 3.84 |

In March there were 3 e-bike diagnostics and 2 of them were rated, both 5.

Explain which technique the claim uses.

*Your answer:*

Explain what information is missing.

*Your answer:*

Rewrite the claim.

*Your answer:*

## Claim 5

A pitch to the owner from a staff member: "Premium members spend almost five times as much per order as non-members (\$329 vs \$70 median). If we get more customers to upgrade to Premium, sales will go up."

Evidence: median order value by membership type, split by whether the order was a bike or e-bike:

| Membership | Orders | Share that are bikes or e-bikes | Median, all orders | Median, bike and e-bike orders | Median, other orders |
|---|---|---|---|---|---|
| Non-member | 398 | 13% | \$70 | \$1,299 | \$65 |
| Basic | 476 | 21% | \$85 | \$1,299 | \$59 |
| Premium | 315 | 49% | \$329 | \$1,649 | \$59 |

Explain which technique the claim uses.

*Your answer:*

Explain what information is missing.

*Your answer:*

Rewrite the claim.

*Your answer:*
