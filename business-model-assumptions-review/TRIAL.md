# Trial: Business model assumptions review, run on its invented example (second run)

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (claude-sonnet-5-5)
- **Date:** 2026-11-10

The inputs were the invented example in [example.md](example.md): the brief and the thirteen-row claims list for "Company A", an invented plant-care business. No client data was used. This is the second run. The first run, on an earlier wording of the template, found that the proposed test for a claim already marked "said" could only produce more "said" evidence; the template was revised (that claim now gets rung 3), along with some smaller wording points, and this run follows the revised instruction block and output format, using the inputs only. The example's own review was read after the output was produced, not before. The template was written by someone else; this run did not write or change it.

## What came out

```
BUSINESS MODEL ASSUMPTIONS REVIEW: Monthly plant-care subscription

Model: Monthly plant-care subscription for small offices, revised from one-off plant sales; from selling plants once to a monthly price that includes a visit to keep them healthy.
Sponsor: Founder. Decision this serves: Whether to move the whole sales effort to the subscription from January 2027. Decision date: Friday 11 December 2026.
Context: Company A had 60 one-off plant orders from 2025-11 to 2026-10, and 12 offices now pay for occasional care visits. 9 office managers were asked about the subscription in October 2026.
Review date: Tuesday 10 November 2026. Prepared from the brief and the claims list; default settings. The review makes no projection or valuation.

THE MODEL, BLOCK BY BLOCK
CUSTOMERS
  C01 EVIDENCED (used, 2026-09). Offices of 10 to 50 staff with someone who orders for the office are the buyers. Evidence: 41 of the 60 one-off orders last year came from offices of that size.
  C02 ASSUMED (said). Office managers will pay monthly rather than per order. Evidence: 6 of the 9 office managers asked said monthly billing suits them.
OFFER
  C03 ASSUMED (said). Offices want the plants kept alive, not only supplied. Evidence: 4 of the 9 office managers asked said dead plants were why they stopped buying.
  C04 ASSUMED (no evidence). One visit of 45 minutes a month keeps a 12-plant office healthy. Evidence: none.
CHANNELS
  C05 EVIDENCED (used, 2026-06). Building managers keep referring tenants. Evidence: Two building managers sent 7 orders last year.
  C06 ASSUMED (estimate). Referrals and the web form will bring 5 new subscribing offices a month. Evidence: Founder's estimate: 60 orders last year is 5 a month.
REVENUE
  C07 ASSUMED (no evidence). Offices will pay $85 a month for the 12-plant service. Evidence: none.
  C08 ASSUMED (said). Subscribers stay at least 12 months. Evidence: 2 of the 9 office managers asked said they would stay a year.
COSTS
  C09 EVIDENCED (measured, 2026-09). A visit takes no more than 45 minutes including travel. Evidence: Timed 6 visits in September; the longest was 45 minutes.
  C10 ASSUMED (no evidence). Replacing dead plants costs under 4% of subscription revenue. Evidence: none.
  C11 EVIDENCED (measured, 2025-08). Van cost is $9 a visit. Evidence: August 2025 fuel receipts divided by 31 visits.
PARTNERS
  C12 ASSUMED (said). The wholesale grower will hold its prices for a year. Evidence: The grower's sales rep said so on a call.
  C13 ASSUMED (no evidence). A second grower could supply us if the first fails. Evidence: none.

EVIDENCE BY BLOCK
Customers: 1 of 2 evidenced.
Offer: 0 of 2 evidenced. All assumed.
Channels: 1 of 2 evidenced.
Revenue: 0 of 2 evidenced. All assumed.
Costs: 2 of 3 evidenced.
Partners: 0 of 2 evidenced. All assumed.
Total: 4 of 13 evidenced, 9 assumed.

RANKED ASSUMPTIONS
1. C08 Revenue. If wrong 3, how sure 3, score 9. RISKIEST. Subscribers stay at least 12 months.
2. C07 Revenue. If wrong 3, how sure 3, score 9. RISKIEST. Offices will pay $85 a month for the 12-plant service.
3. C06 Channels. If wrong 3, how sure 3, score 9. RISKIEST. Referrals and the web form will bring 5 new subscribing offices a month.
4. C02 Customers. If wrong 3, how sure 2, score 6. RISKIEST. Office managers will pay monthly rather than per order.
5. C04 Offer. If wrong 2, how sure 3, score 6. RISKIEST. One visit of 45 minutes a month keeps a 12-plant office healthy.
6. C10 Costs. If wrong 2, how sure 3, score 6. Replacing dead plants costs under 4% of subscription revenue.
7. C12 Partners. If wrong 2, how sure 2, score 4. The wholesale grower will hold its prices for a year.
8. C03 Offer. If wrong 3, how sure 1, score 3. Offices want the plants kept alive, not only supplied.
Not yet rated: C13 (how_sure missing).
Also at or above the risk score, beyond the first 5: C10 (6).

CHEAPEST EVIDENCE FOR THE RISKIEST
1. C08 Subscribers stay at least 12 months.
  Test: Look up how long the 12 current care offices have stayed. Cost: 0. Days: 2.
  Pass line: sponsor to set. Fail line: sponsor to set.
2. C07 Offices will pay $85 a month for the 12-plant service.
  Test: Offer 3 current customers a written 3-month order at $85 a month. Cost: 120. Days: 21.
  Pass line: sponsor to set. Fail line: sponsor to set.
3. C06 Referrals and the web form will bring 5 new subscribing offices a month.
  Test: Proposed, rung 4: run one small, capped trial with a real customer or channel. Cost: not stated. Days: not stated.
  Result would be: used or paid
  Pass line: sponsor to set. Fail line: sponsor to set.
4. C02 Office managers will pay monthly rather than per order.
  Test: Proposed, rung 3: ask for a small written commitment, such as a deposit or an order. Cost: not stated. Days: not stated.
  Result would be: paid
  Pass line: sponsor to set. Fail line: sponsor to set.
5. C04 One visit of 45 minutes a month keeps a 12-plant office healthy.
  Test: Keep 3 of the 12 current care offices on a monthly 45-minute visit for 3 months and photograph the plants each month. Cost: 180. Days: 90.
  Pass line: sponsor to set. Fail line: sponsor to set.
A paid, used or measured result moves a claim to evidenced.
A result that someone said does not.

EVIDENCED CLAIMS TO RECHECK
C11 Van cost is $9 a visit: evidence dated 2025-08, 15 months before the review date; the limit is 12 months.

OPEN QUESTIONS FOR THE FOUNDER
1. C11 Costs: the van cost evidence is dated 2025-08, 15 months before the review date, against a limit of 12 months. Is this still the van cost per visit?
2. C13 Partners: the claim "A second grower could supply us if the first fails" has if wrong 2 and no how_sure rating. What is your how_sure rating (1 fairly sure, 2 leaning, 3 a guess)?
3. Pass and fail lines: C08, C07, C06, C02 and C04 are the riskiest. What pass and fail lines do you set for each test?

SPONSOR'S CHOICE
C08 [ ] Test now  [ ] Later  [ ] Accept as is
C07 [ ] Test now  [ ] Later  [ ] Accept as is
C06 [ ] Test now  [ ] Later  [ ] Accept as is
C02 [ ] Test now  [ ] Later  [ ] Accept as is
C04 [ ] Test now  [ ] Later  [ ] Accept as is

Prepared for the Founder's decision. Nothing has been decided, sent, ordered, booked or changed. No projection or valuation has been made.
```

## What was observed

- Every required part was produced: the six blocks, the evidence counts, the ranking, the riskiest list, the cheapest evidence, the recheck list, the open questions and the empty choice boxes. Nothing in the run called for a stop, and no refusal case came up.
- The marks, scores and ranking came out as the rules say. The three-way tie at score 9 was settled by lowest stated cost (0, then 120, then unstated), and the three-way tie at 6 by higher if_wrong, then lowest stated cost.
- C02 is marked "said" and its default rung for customers is 2, so under the revised rule it was given rung 3 (a small written commitment) with the result "paid". The first run proposed rung 2 here, which could not have moved the claim to evidenced.
- Compared with the example's published review, the numbers, marks, ranking, tests, recheck item and choice lines are identical. The differences are wording only: the title (the example adds "for small offices"); "how_sure missing" against "how sure is missing"; "C10 (6)" against "C10 (score 6)"; and the phrasing of the three open questions, where this run's were shorter and the example's explain more.
- No fact appears in either output that is not in the inputs, with one small exception in the example: its third question says the pass and fail lines are "none set" and asks about them "before any test starts", which is a reasonable reading of the template rather than something typed in the inputs.
- The costs in the inputs carry no currency. The template says the amount is printed as typed and no currency is added, and this run printed "Cost: 0", "Cost: 120" and "Cost: 180" as typed.
- The "Proposed" tests printed the rung text without its bracketed result, and the result went on its own "Result would be:" line.
- The instruction block says to use the output format exactly; the template now tells the reader to paste the output format after the block, and this run had the whole template.
- Some rules were not exercised by this input: a non-numeric cost or days, the "None." wording when no assumed claim has both ratings, non-default settings, and any stop or refusal case.
- This is one run on one example, by one model, in one product. It does not show how the template behaves with real company data, with other products, or with inputs that trip the stop rules.
