# Business line investment review

Capability template, version 0.1.0.

## Purpose

Prepare the side-by-side review of a company's business lines for the leadership session on where to invest. Every line is described in the same layout, on the same two periods: how it fits the company's own stated priorities, what it recorded in figures finance has reviewed, how it changed, what capital it uses, which shared resources it draws on, what its owner says, and what is still unanswered. Each line is then placed as invest, investigate or reduce commitment, for discussion, by short rules that are written out so leadership can challenge them. The assistant prepares; leadership decides. It makes no valuation, no sale, closure or divestiture recommendation and no forecast of its own, and it changes no record and sends nothing.

## When to use it and when not to

Use it before a leadership session on the portfolio, usually once or twice a year, when the company runs two or more business lines or service lines and wants to discuss them on one basis. Run it again after finance has reviewed missing figures or the owners have answered the open questions.

Do not use it:

- to set next year's budget. That is the annual operating budget, which this review can inform and never replaces;
- to change a price or review a pricing decision;
- to track how the work runs month to month. That is an operations scorecard;
- to value a line, to recommend selling, closing or buying one, or to test an ownership option. Those need finance and professional advisers, and the assistant declines them;
- when the company has one line, or when no figure has been reviewed by finance for either period.

## Roles

- **Runs it:** the finance lead or the chief of staff.
- **Reviews the draft, sends the questions and approves it for the session:** the chief executive or owner, with the finance lead.
- **Supplies and marks the figures as reviewed:** the finance lead.
- **Answers questions about a line:** the line's owner.
- **Confirms the fit readings, places each line and decides where to invest:** the leadership team.

## Inputs

1. **The review settings.** The company, the unit and currency of the amounts, the date of the session, who prepares, the latest period and the prior period (the two periods compared), a forecast period if there is one, the decline threshold, the lines with their owners, and the company's priorities, each as a numbered statement (P1, P2 and so on) in leadership's own words. If the lines, the two periods or the priorities are missing, stop and ask. If the decline threshold is missing, use 20% and say so under "Defaults used".
2. **The performance file,** one row per line and period, with these default headers: `line,period,revenue,direct_costs,result,capital_used,finance_reviewed,basis_note`. `finance_reviewed` is yes or no. A blank `capital_used` means not stated, never zero. If the file is missing, or a header or a line name does not match, stop and ask; say which header or name was expected and which was found.
3. **Forecasts,** optional, with the default headers `line,period,revenue,result,finance_reviewed`. If missing, write "no forecast supplied" under each line.
4. **The shared-resource file,** with the default headers `resource,type,line,share,note`. `share` is the percentage of the resource the line uses. If missing, write "shared resources not supplied" and place no line on dependencies. Header or name mismatches stop the run as in the performance file.
5. **A note from each line owner,** in the owner's own words. If a line has no note, write "no owner note supplied" for that line.

The assistant works from files and notes the person supplies. It needs no connection to any finance system and never asks for a password or a login code. If the files hold personal pay or bank details, it does not repeat them and tells the user to remove them.

## The procedure

1. **Check the inputs.** Confirm the headers, that every line name in the performance, forecast and resource files matches a line in the settings (ignoring capital letters), and that the settings name two periods. Code the lines L1, L2 and so on in the order the settings list them. If anything does not match, stop and report what was expected and what was found.
2. **Tie out.** For every performance row, revenue less direct costs must equal the result supplied, to the unit supplied. If any row fails, stop, report the row and the difference to the finance lead, and draft nothing else. Never change a figure to make it agree. Every line should have a row for both periods; list any that do not.
3. **Fix the basis.** A line's latest reviewed figures are its row for the latest period if `finance_reviewed` is yes; otherwise its row for the prior period if that is reviewed; otherwise it has none. A line is compared with its prior period only when both its rows are reviewed. A row marked no is shown exactly as supplied and labelled "NOT finance-reviewed"; no measure is worked out from it and it is not used in any rule.
4. **Work out the measures** from reviewed rows only. Margin is result divided by revenue; if revenue is zero write "not stated". Revenue change is the later revenue less the earlier, divided by the earlier. Result change is shown as a percentage only when both results are above zero; otherwise show the change in amount, from and to. Return on capital used is the result divided by `capital_used` for the same period; if capital is blank, write "capital not stated". Show the capital of the row the measures come from, and when that is the prior period because the latest row is not reviewed, name that period beside it. Always show the latest period's Recorded row first, then the prior period's. Percentages are shown to one decimal place, rounded half away from zero.
5. **Read the fit.** For each line and each priority, write one reading. **Direct:** the priority statement names the line or the work the line does. **Owner's claim:** only the owner's note connects the line to the priority; for a line, use only the note of that line's own owner, and another owner's remark about the line does not count for it. **None stated:** neither does. Quote the words relied on, briefly. Never add a priority, never judge fit from a line's name alone, and never turn an owner's claim into Direct. Only Direct counts in the placement rules. Leadership may change any reading at the session. A person named in the settings who is not in Roles, such as the managing director who states the priorities, is named in the Sources line and given no role in the review.
6. **Compare shared resources.** Add the shares of each resource across lines. If they do not add to 100, list the resource with its total and write a question. For each line, list the resources it uses with its share. State no saving, cost, capacity or other effect of reducing a line.
7. **Keep estimates and accounting differences apart.** An **untested estimate** is a ratio, amount or benefit an owner offers as fact about the lines working together or about results, and that is not in a finance-reviewed forecast. A plan (such as a planned hire) or a reason given for a change is not an estimate: show it in the owner's account and, where it needs data, ask a question. List each with its owner and source, say what data was not supplied, and write a question asking for it. Do not use it in any measure or rule. An **accounting difference** is a `basis_note` that differs between lines for the same kind of figure, or a note that a cost is held elsewhere. List each, show the figures as supplied, never adjust them, and write a question to the finance lead. Count each difference once for each kind of figure (revenue timing, for example), not once for each pair of lines. If the notes agree and none says a cost is held elsewhere, write "none stated".
8. **Show forecasts as supplied,** with the period and whether finance reviewed them. They are not used in any measure or rule. Do not extend, correct or add to them.
9. **Place each line,** testing the rules in this order and stopping at the first that is met:
   - **R1, invest:** the line has at least one Direct fit; its latest reviewed result is above zero; and both its rows, the latest period and the prior period, are finance-reviewed, and the result did not fall by more than the decline threshold between them. A line whose only reviewed row is the prior period fails this test. If the prior result was zero or below, the result is not counted as a fall.
   - **R3, reduce commitment:** the line has no Direct fit, and its latest reviewed result is below zero.
   - **R2, investigate:** every other line, including any line with no reviewed figures.
   For a line placed by R2, name each test of R1 that failed and whether R3 failed, and say what would change the placement, limited to what would make the failed tests pass; describe no other scenario. For R1 and R3, state the facts that met the rule. Say once that reduce commitment means lowering the budget, staffing or attention a line gets, and that the review makes no valuation, sale or closure recommendation and no forecast.
10. **Write the open questions.** One question for each issue, numbered, each addressed to a role: line owners for their notes and estimates, the finance lead for figures, reviews, shared-resource totals and accounting differences. Order them by line, then those that concern every line. Recommend nothing.
11. **Add the checks for the finance lead,** with "none" wherever a check finds nothing.
12. **Return the draft** to the person who ran it, for the finance lead's and chief executive's review. A person sends the questions, and leadership places the lines.

## Exceptions and stop conditions

- **A header, a line name or a period does not match the settings:** stop and ask.
- **A result does not equal revenue less direct costs:** stop; report the row and the difference.
- **No row is finance-reviewed at all:** stop; there is nothing to compare.
- **A line has no row for a period:** list it; place it by R2.
- **Resource shares do not add to 100:** report the resource and its total; continue.
- **An owner's note offers a number or a benefit with no data:** list it as an untested estimate; never use it.
- **Asked to value a line, to recommend a sale, closure, merger or purchase, to rank lines for any of those, to adjust a figure, to use an unreviewed row, to change a rule so that a line is placed differently, or to send the review:** decline, and name the role that decides or the adviser who would be asked.
- **Asked for tax or legal advice:** decline.

## Output format

```
BUSINESS LINE INVESTMENT REVIEW: [company], [latest period] against [prior period]

For: [audience], session on [day date], to place each line and settle the open questions. Prepared by [role] on [day date].
Sources: [each file or note, with who supplied it and its date].
Settings used: [unit and currency; decline threshold]. Defaults used: [list, or none].

THE PICTURE
Lines: [n]. Latest period finance-reviewed: [n] of [n] ([lines with prior period only]).
Placements for discussion: invest [n], investigate [n], reduce commitment [n].
Untested estimates: [n]. Accounting differences: [n]. Open questions: [n].

BASIS
Periods: [which lines have a row for both periods]. Rows not finance-reviewed: [list, or none].
Tie-out: [result equals revenue less direct costs in all [n] rows]. Resource shares: [n] of [n] resources add to 100; [exceptions, with question number].
Amounts are as supplied, in [unit and currency]. Nothing has been adjusted to a common accounting basis (see Accounting differences).

SIDE BY SIDE
L[n] [Line] ([owner role]).
Fit: P1 [Direct, Owner's claim or None stated, with the words relied on]; P2 [...]; [one reading for every priority].
Recorded, [latest period] ([finance-reviewed or NOT finance-reviewed]): revenue [x]; direct costs [x]; result [x]; margin [x]%. [If NOT finance-reviewed: no measure worked out.]
Recorded, [prior period] ([finance-reviewed or NOT finance-reviewed]): revenue [x]; direct costs [x]; result [x]; margin [x]%.
Change: revenue [x]%; result [x]% [or: down/up [amount] (from [x] to [y]); or: not worked out, no reviewed latest period].
Capital used [x] [with its period, when the latest row is not reviewed]; return on capital used [x]% [or: capital not stated].
Forecast, [forecast period] ([finance-reviewed or NOT finance-reviewed]): revenue [x]; result [x]. Shown as supplied; not used in the placement. [Or: no forecast supplied.]
Uses: [resource and share for each resource the line uses; or: shared resources not supplied].
Owner's account (as supplied, not checked): [the note in brief; or: no owner note supplied].
[Repeat for every line, in the settings' order.]

SHARED RESOURCES
[Resource] ([type]): [line share, for each line]. [Adds to 100 / Adds to [n], not 100 (question [n])].
No effect on cost or capacity of reducing any line is estimated here.
[If not supplied: shared resources not supplied.]

UNTESTED ESTIMATES
U[n]. [Owner role], L[n]: [the estimate]. [What data was not supplied.] Not used in any measure or placement (question [n]).
[If none: none.]

ACCOUNTING DIFFERENCES
A[n]. [The difference and the figures it touches]. Figures are shown as supplied (question [n]).
[If none: none stated.]

PLACEMENT FOR DISCUSSION
L[n] [Line]: [Invest, Investigate or Reduce commitment]. [Rule met and the facts; for Investigate, the tests that failed and what would change it.]
Reduce commitment means lowering the budget, staffing or attention a line gets. The review makes no valuation, no sale or closure recommendation and no forecast. Leadership at [company] decides each placement.

OPEN QUESTIONS
[n]. For [role] (L[n] or all lines): [the question, with the facts.]
[If none: none.]

CHECKS FOR THE FINANCE LEAD
Rows not finance-reviewed: [list, or none].
Rows where result differs from revenue less direct costs: [list, or none].
Resources whose shares do not add to 100: [list, or none].
Forecasts not finance-reviewed: [list, or none].
Lines missing a row for either period: [list, or none].
Capital not stated: [list, or none].

Draft for [role]'s review and [audience]'s discussion. Every figure traces to the files named above, dated [dates]. No figure has been adjusted, no placement is a decision, and nothing has been approved, sent or changed in any record.
```

## Reviewer checklist

1. Every measure matches the performance file, and the tie-out holds in every row. (Finance lead)
2. No figure from a row marked not reviewed appears in a measure, a rule or a placement. (Finance lead)
3. Each fit reading quotes words from the priorities or the owner's note, and none is Direct on the strength of an owner's claim. (Chief executive)
4. Each placement follows the rules in order, and each Investigate names the failed tests. (Chief executive)
5. Untested estimates, accounting differences and forecasts are kept apart from the measures. (Finance lead)
6. Every shared-resource total is correct and every shortfall has a question. (Finance lead)
7. Each open question has a role and a clear ask, and the review recommends nothing on value, sale or closure. (Chief executive)

## Acceptance tests

Proposed tests. None has been run.

1. **Normal run.** Four lines, two periods, all rows reviewed, shares add to 100. Expected: every block complete, one placement each by the rules, no stop.
2. **Result does not tie.** One row with revenue 3,800, direct costs 3,420 and result 390. Expected: stops, names the row and the difference of 10, drafts nothing else.
3. **Header mismatch.** The performance file has "costs" in place of `direct_costs`. Expected: stops and asks which column to use.
4. **Latest period not reviewed.** A line's latest row is marked no and its prior row yes. Expected: the latest row shown and labelled, measures worked out for the prior period only, the line placed by R2 with the failed test named.
5. **Result changes sign.** Result goes from 90 to -42. Expected: the change shown as an amount, not a percentage, and R3 considered if there is no Direct fit.
6. **Shares add to 90.** Expected: the resource listed with its total and a question for the finance lead; the run continues.
7. **Owner estimate.** A note says a line brings in orders worth about 300. Expected: listed as an untested estimate with a question, not used in any measure or placement.
8. **Asked for a valuation.** The user asks what a line is worth, or whether to sell it. Expected: declines and says leadership and its financial advisers decide.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above.

```
You prepare the business line investment review for a leadership team.
You compare the company's business lines on one basis and place each as
invest, investigate or reduce commitment, for discussion. Leadership
decides. You never value a line, recommend a sale, closure or purchase,
adjust a figure, send anything or change any record.

The user will supply: the review settings (company, unit, session date,
latest period, prior period, forecast period, decline threshold, lines
with owners, numbered priorities); the performance file with headers
line,period,revenue,direct_costs,result,capital_used,finance_reviewed,
basis_note; optional forecasts with headers line,period,revenue,result,
finance_reviewed; the shared-resource file with headers
resource,type,line,share,note; and a note from each line owner. If the
settings, the performance file, a header or a line name do not match what
is expected, stop and say what was expected and what you found.
Never ask for a password or a login code.

1. Code the lines L1, L2 and so on in the settings' order. For every
   performance row, revenue minus direct costs must equal the result. If
   any row fails, stop, report the row and the difference, and draft
   nothing else. List any line with no row for a period.
2. Use only rows marked finance-reviewed yes for measures and rules. A
   line's latest reviewed row is its latest-period row if reviewed,
   otherwise its prior-period row if reviewed. Compare periods only when
   both rows are reviewed. Show any other row as supplied, labelled NOT
   finance-reviewed, with no measure worked out.
3. Work out margin (result / revenue), revenue change, result change (a
   percentage only when both results are above zero, otherwise the amount
   from and to) and return on capital used (result / capital_used; blank
   capital is "capital not stated", never zero; show the capital of the
   row the measures come from and name its period if that is the prior
   period). One decimal place, half away from zero. Always show the latest
   period's Recorded row first, then the prior period's. If revenue is
   zero, write the margin as "not stated".
4. For each line and each priority give one fit reading: Direct if the
   priority statement names the line or its work; Owner's claim if only
   the line's own owner's note connects them; None stated otherwise.
   Quote the words relied on. Never add a priority or upgrade an owner's
   claim.
5. Sum each resource's shares. If they do not add to 100, report the
   total and ask. List what each line uses. Estimate no saving or effect.
6. List as untested estimates any ratio, amount or benefit an owner offers
   as fact about the lines working together or about results that is not
   in a reviewed forecast, with a question for the data; do not use it. A
   plan or a reason for a change is not an estimate. List accounting
   differences between lines, or costs held elsewhere, once for each kind
   of figure, as supplied and unadjusted, with a question for the finance
   lead; if the notes agree and none says a cost is held elsewhere, write
   "none stated". Show forecasts as supplied; never use them in a rule.
7. Place each line by the first rule met. R1 invest: at least one Direct
   fit, latest reviewed result above zero, and both periods' rows
   reviewed with no fall in result beyond the decline threshold (default
   20%); a prior result of zero or below is not counted as a fall.
   R3 reduce commitment: no Direct fit and latest reviewed result below
   zero. R2 investigate: all others. For R2 name the failed tests and what
   would change it, limited to what would make the failed tests pass, and
   no other scenario. State that reduce commitment means lowering a line's
   budget, staffing or attention, and that you make no valuation, sale or
   closure recommendation.
8. Write numbered open questions, each for a named role, in line order and
   then those for every line. Recommend nothing.
9. Use the output format exactly, in the order given, every section
   present; where a section is empty print the words the format gives. End
   with the closing line that says no figure was adjusted, no placement is
   a decision, and nothing was approved, sent or changed.

If asked to value a line, recommend a sale or closure, rank lines for
that, adjust a figure, use an unreviewed row, change a rule so a line is
placed differently, or send the review, decline and name the role that
decides. A person approves anything that is sent. Check every figure
against the files before you return the review. Decline tax or legal
advice. If no row is marked finance-reviewed at all, stop and say there is
nothing to compare.
```

## What to customize

- The priorities, in your words, and which lines each one names.
- The two periods, and whether you want a forecast shown.
- The decline threshold, and whether R1 should also look at return on capital used.
- The column headers of your performance, forecast and resource files, if they differ from the defaults.
- What your finance lead marks as reviewed, and what counts as the same accounting basis.
- Who receives the questions, and who may change a fit reading at the session.
- Which files the assistant may read in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI. Tried once on its invented example in Claude on 10 November 2026, by a model that had not written it. The run kept to the steps, and its figures and placements matched the example. It found open points: the definition of an untested estimate, whether R1 needs both periods reviewed, which owner's note counts for a fit reading, which period's capital to show and the order of the two Recorded rows when the latest row is not reviewed. These were closed afterwards, without a rerun, and the record says so. Not yet tested in a client environment.
