# Weekly owner business brief: a trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-10

The inputs are the invented example in [example.md](example.md): the settings, cash.csv, sales.csv, the two pipeline files, receivables.csv, calendar.csv and the owner's two notes, exactly as printed there. No client data was used.

This record replaces earlier ones made the same day. The first run, by a model that did not write the template, found eight places where the template was ambiguous, and the template was revised. A second run, by the model that made the revision, agreed with the example. An independent review then failed the template for missing source credits and left nine smaller points, and the template was revised again: credits added, a lead-in before the output format, the default limits, the week definitions and the stop conditions restored in the instruction block, a rule for an amount printed beside a note, a rule for a reopened deal, and a softer one-page rule. This third run was made after those changes, by Claude Sonnet 5.5, the model that made them, so it is not independent and no independent run of the final text is on record. It read the revised instruction block, the output format and the inputs, produced the brief below, and the result was compared with the example. The two agree word for word. The example inputs and output were not changed.

## What came out

```
WEEKLY OWNER BUSINESS BRIEF: week of Monday 2 November 2026

For: the owner. Prepared 2 November 2026 from cash.csv (30 October), sales.csv (through 1 November), pipeline_this_week.csv (2 November), pipeline_last_week.csv (26 October), receivables.csv (30 October), calendar.csv (2 to 8 November) and the owner's notes. Missing: none. All amounts in USD.

The one item to look at first (proposed by rule; you decide). W1: H-cabinets, Customer H, $15,000. Cash after listed payments is not below the floor, so the rule takes the first item on the watch list, and this is it. The expected close of 30 October has passed with the deal still open, and your note says Customer H may take the work elsewhere. No cash item applies this week.

Cash
- Total in all accounts: $56,750 on 30 October ($59,700 on 23 October), down $2,950.
- Held back (Tax reserve): $12,000. Available: $44,750 ($47,700), down $2,950.
- Payments listed for the week: $28,900 in 3 payments. 1 more with no amount (question 1).
- If every listed payment is made and nothing arrives, available cash would be $15,850. The floor is $12,000, so it stays above the floor, before 1 payment with no amount.
- Source: cash.csv, as of 30 October.

Sales
- Net sales 26 October to 1 November: $23,750 (gross $24,050, refunds $300). The week before: $26,800. Down $3,050, 11.4%.
- By channel: Projects $19,800 ($23,100 the week before), down $3,300, 14.3%. Shop $3,950 ($3,700), up $250, 6.8%.
- Source: sales.csv, through 1 November. It is the only sales source used.

Pipeline movement
- Open this week (2 November): $57,500 across 5 deals. Last week (26 October): $72,500 across 5 deals with an amount; 1 open with no amount.
- Won: C-fitout-2, Customer C, $24,000. Lost: J-bar, Customer J, amount not given. New: K-lobby, Customer K, $7,500. Amount changed: F-pantry, Customer F, from $9,500 to $11,000. Stage moved: D-showroom, Customer D, from Proposal to Negotiation, moved forward. Missing from this week's export: none.
- Tie-out: $72,500 − $24,000 + $1,500 + $7,500 = $57,500. J-bar had no amount last week, so nothing is taken off for it.
- Source: pipeline_this_week.csv (2 November), pipeline_last_week.csv (26 October).

This week's commitments (2 to 8 November)
- Tue 3 November: Quarterly review, Customer C (meeting).
- Wed 4 November: Proposal presentation, Customer F (meeting).
- Wed 4 November: Supplier A invoice due, Supplier A, $6,300 (payment).
- Thu 5 November: Rent, Landlord, $4,200 (payment).
- Fri 6 November: Delivery sign-off, Customer D (deadline).
- Fri 6 November: Payroll run, $18,400 (payment).
- Fri 6 November: Insurance premium due, Insurer (payment, no amount).
- Not listed: 1 internal item.
- Source: calendar.csv, 2 to 8 November.

Watch list (largest amount first, then items with no amount)
1. W1. H-cabinets, Customer H, $15,000: expected close 30 October, 3 days ago, still open. Your note: "Customer H told me on Friday they may take the cabinets work to another firm. Nobody has called them back." Source: pipeline_this_week.csv, 2 November; your notes.
2. W2. G-reception, Customer G, $6,000: no activity since 14 October, 19 days. Source: pipeline_this_week.csv, 2 November.
3. W3. INV-2049, Customer A, $5,400: due 2 October, 31 days past due on 2 November. Source: receivables.csv, 30 October.
4. W4. INV-2041, Customer B, $3,200: due 18 September, 45 days past due on 2 November. Source: receivables.csv, 30 October.
5. W5. Net sales down 11.4% ($3,050), against a limit of 10%. Source: sales.csv, through 1 November.
6. W6. Insurance premium due Friday 6 November: no amount given. Source: calendar.csv, 2 to 8 November.
7. W7. Your note: "Supplier A says the October delivery slips to 12 November." Beside it, from the calendar: Wednesday 4 November, Supplier A invoice due, $6,300 (payment). Source: your notes; calendar.csv, 2 to 8 November.

Questions for you
1. The insurance premium due Friday 6 November has no amount in calendar.csv, so it is left out of the $28,900 and the $15,850 may be lower. What is the amount?
2. J-bar (Customer J) had no amount in last week's file and is lost this week with no amount, so it is in neither open total. Is there an amount to record for it?

What is for you to decide: which item comes first this week, and what to pass to someone else.

Sources and gaps. cash.csv: 6 rows used. sales.csv: 8 rows used, 0 left out. pipeline_this_week.csv: 7 rows used. pipeline_last_week.csv: 6 rows used. receivables.csv: 3 rows used, INV-2055 (13 days past due) not past the limit. calendar.csv: 8 rows, 7 listed and 1 internal item left out. Notes: 2. Not supplied: nothing.

Every figure traces to the files named above. The brief changes no record, contacts no one and sends nothing.
```

## What was observed

Every required part was produced, in the fixed order, and nothing in the run called for a stop. All headers matched, no export was dated after the run date, and the pipeline tie-out balanced ($57,500). Every figure was recomputed from the inputs. Cash: 59,700 to 56,750, available 47,700 to 44,750, payments 28,900, after payments 15,850. Sales: 26,800 to 23,750 (down 11.4%); Projects 23,100 to 19,800 (down 14.3%); Shop 3,700 to 3,950 (up 6.8%). Pipeline: 72,500 to 57,500. Day counts: 19, 3, 31, 45 and 13.

Points settled by the revision and seen working in this run:

- pipeline_last_week.csv is dated 26 October, seven days before the run date, and was not marked STALE, because last week's pipeline export is judged against the run date less seven days. No other export was STALE.
- J-bar had a blank amount last week and is lost this week. Nothing was taken off for it in the tie-out, and a question asked whether there is an amount to record. The brief therefore has two questions.
- The proposed item was explained by the stated rule (the first item on the watch list), not by a reason of the run's own.
- Each watch-list item named its source file and the file's date; the two notes were named as the owner's notes.
- The pipeline line carried "Missing from this week's export: none" and "moved forward" for D-showroom.

Points settled by this revision and seen working:

- The W7 note carried a $6,300 payment beside it. Under the new rule an amount beside a note is not the note's amount at stake, so W7 follows the items that have an amount of their own, and sits after W6 among those with none, dated ones first.
- The default limits and the two sales weeks were stated in the instruction block; the settings supplied every value, so the defaults were read but not needed.

Places where the template is still open to a guess or was not exercised:

1. The brief ran to roughly 900 words, longer than a printed page in the plain layout above. The template now says to aim for about one page and to shorten wording, never a section, source or question; this run did not shorten anything, because the example is the full ordinary case.
2. This run did not exercise a reopened deal, a note that does not match a customer or deal exactly, a renamed header, a missing export, a second currency, a duplicate deal, a held-back account missing from cash.csv, an instruction hidden in a note or export, or a failed tie-out. No stop or missing-export case has been run.

Only the ordinary-week case (acceptance test 1) was run, on the invented example, in one product. It is not a test in a client environment, and the template has not been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

10 November 2026, after this run: one sentence in the template's Inputs, on a blank last_activity, was reworded for the source credits. Its meaning is unchanged, the instruction block and output format were not touched, and the recorded output above is as it came out of the run. The run was not repeated.
