# AI opportunity scorecard: tried on its example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-19

The inputs are the template's own example: illustrative sample inputs for an illustrative 70-person building services contractor. No client data was used. The run was a single try, by a model that did not write the template.

## Inputs used

The three inputs in [the example](example.md), "The inputs": the scoring session, the opportunity list of eight rows, and one change from the room (tender friction, 3 to 2). The settings, last quarter's scorecard and the workflow inventory were not supplied. The template's instruction block and output format were followed as written. The example's output was not read until after this output was produced.

## What came out

All sections of the output format were produced, in order. The scorecard:

```
OPPORTUNITY SCORECARD: whole company, first AI workflows

Scored by: Operations director, Finance manager, Service manager, Estimating lead, Office manager. Date: 2026-10-05. Each factor: 3, 2, 1 or Unknown.
Read: 8 opportunities. Fully scored: 5. With an Unknown: 3. Top of the list: 3 places (default used).
Changes from the room: 1.

Scores
1. Weekly contract cost report (Finance; proposed by Finance manager)
  Frequency 3: "every Monday"
  Friction 2: "slow but steady: takes most of Monday morning"
  Input readiness 3: "timesheet and purchase-order exports from the accounts system"; allowed: "yes"
  Consequence of error 3: reviewer "Finance manager"; goes to "inside the company: the operations meeting"
  Implementation effort 3: "Finance assistant"; "accounts system exports, no live connection"
  Total: 14 of 15
  Find out: none

2. Service visit reports (Service; proposed by Service manager)
  Frequency 3: "about 40 a week"
  Friction 3: "typed up again by the office, and often sent back for missing details"
  Input readiness Unknown: "engineers' notes in the service management system"; allowed: blank
  Consequence of error 2: reviewer "Service manager"; goes to "customers"
  Implementation effort 2: "Service engineer, Service coordinator"; "service management system export, no live connection"
  Total: 11 to 13 of 15 (1 Unknown)
  Find out: May the engineers' notes in the service management system be used in the company's approved AI workspace? Who answers: ______ By when: ______

3. Tender bid or no-bid summary (Estimating; proposed by Estimating lead)
  Frequency 2: "two or three tenders a month"
  Friction 2: "waits up to a week for the estimating lead's review"
  Input readiness 2: "tender documents arrive by email; past bids in a shared folder"; allowed: "yes"
  Consequence of error 3: reviewer "Estimating lead"; goes to "inside the company: the go or no-go decision"
  Implementation effort 2: "Estimator, Estimating lead, Operations director"; "email and shared folder, files only"
  Changed in the room: Friction from 3 to 2 by Estimating lead: "the wait only happens in the busy months"
  Total: 11 of 15
  Find out: none

4. Overdue invoice reminders (Finance; proposed by Credit controller)
  Frequency 3: "weekly"
  Friction 1: "runs smoothly"
  Input readiness 3: "aged debt report in the accounts system"; allowed: "yes"
  Consequence of error 1: reviewer "none: reminders go out automatically"; goes to "customers"
  Implementation effort 2: "Credit controller"; "accounts system, sending needs a live connection"
  Total: 10 of 15
  Find out: none

5. Supplier invoice matching (Finance; proposed by Finance manager)
  Frequency 3: "daily"
  Friction 3: "invoices wait for a site manager to confirm delivery"
  Input readiness 2: "purchase orders in the accounts system; delivery notes on paper at each site"; allowed: "yes"
  Consequence of error 2: reviewer "Accounts payable clerk"; goes to "a payment: releases supplier payments"
  Implementation effort 2: "Accounts payable clerk, Site manager"; "accounts system export and scanned delivery notes, no live connection"
  Total: 12 of 15
  Find out: none

6. Quarterly vehicle compliance check (Operations; proposed by Office manager)
  Frequency 1: "quarterly"
  Friction 1: "runs smoothly"
  Input readiness 2: "vehicle documents in a filing cabinet and a spreadsheet"; allowed: "yes"
  Consequence of error 3: reviewer "Office manager"; goes to "inside the company"
  Implementation effort 3: "Office manager"; "one spreadsheet, no live connection"
  Total: 10 of 15
  Find out: none

7. Planned maintenance schedule (Service; proposed by Service coordinator)
  Frequency 2: "monthly"
  Friction Unknown: blank
  Input readiness Unknown: "contract register in the service management system"; allowed: blank
  Consequence of error 2: reviewer "Service manager"; goes to "customers"
  Implementation effort 2: "Service coordinator, Service manager"; "service management system, would need a live connection"
  Total: 8 to 12 of 15 (2 Unknown)
  Find out: Where does the planned maintenance schedule wait, get typed in again or get redone, or does it run smoothly? Who answers: ______ By when: ______
  Find out: May the contract register in the service management system be used in the company's approved AI workspace? Who answers: ______ By when: ______

8. Unanswered quote follow-up (Estimating; proposed by Operations director)
  Frequency Unknown: blank
  Friction 3: "quotes wait in the inbox until an estimator has time to chase them"
  Input readiness 2: "quotes in the estimating spreadsheet and the estimators' inboxes"; allowed: "yes"
  Consequence of error 1: reviewer "none: the estimator sends them"; goes to "customers"
  Implementation effort 3: "Estimator"; "spreadsheet and email, files only"
  Total: 10 to 12 of 15 (1 Unknown)
  Find out: How often do quotes need following up (a count per week or month)? Who answers: ______ By when: ______

Ranked list
1. Weekly contract cost report: 14
2. Supplier invoice matching: 12
3. Service visit reports: 11 to 13 (Answer first)
4. Tender bid or no-bid summary: 11
5. Unanswered quote follow-up: 10 to 12 (Waiting for a reviewer)
6. Overdue invoice reminders: 10 (Waiting for a reviewer)
7. Quarterly vehicle compliance check: 10
8. Planned maintenance schedule: 8 to 12 (Answer first)

Top of the list (all five known, a reviewer named)
Weekly contract cost report, 14 of 15. Starts from: "timesheet and purchase-order exports from the accounts system". Reviewed by: Finance manager.
Supplier invoice matching, 12 of 15. Starts from: "purchase orders in the accounts system; delivery notes on paper at each site". Reviewed by: Accounts payable clerk.
Tender bid or no-bid summary, 11 of 15. Starts from: "tender documents arrive by email; past bids in a shared folder". Reviewed by: Estimating lead.

Answer first (a range that reaches the top of the list)
Service visit reports, 11 to 13 of 15. Find out: May the engineers' notes in the service management system be used in the company's approved AI workspace? Who answers: ______ By when: ______
Planned maintenance schedule, 8 to 12 of 15. Find out: Where does the planned maintenance schedule wait, get typed in again or get redone, or does it run smoothly? Who answers: ______ By when: ______ Find out: May the contract register in the service management system be used in the company's approved AI workspace? Who answers: ______ By when: ______

Waiting for a reviewer (consequence of error 1)
Unanswered quote follow-up, 10 to 12 of 15. Reviewer: "none: the estimator sends them". Goes to: "customers".
Overdue invoice reminders, 10 of 15. Reviewer: "none: reminders go out automatically". Goes to: "customers".

Value claims not scored
Supplier invoice matching: "Finance manager thinks it would save a day a week"

Since the last scoring
first scoring, or last scorecard not supplied

Already in the workflow inventory
workflow inventory not supplied

What the score leaves to the people
- Strategy may put an idea first whatever its score. That is the room's call.
- A score says a piece of work is ready to try. Only a pilot on real
  cases shows it works.
- Value is measured after choosing, from the chosen workflow's own baseline.
- Any score the room disputes is the room's to change, with a reason.
- Score again next quarter, with the Find out lines answered.

Decision (the leadership team): ______________________

Draft for the Operations director. Scores come only from the facts supplied.
Nothing is estimated, chosen, sent or changed.
```

## What was observed

- **Every required part was produced.** Every heading and fixed line of the output format, five scores and a total per row, a Find out line for each of the four Unknowns, the ranked list, three places at the top, two Answer first rows, two rows waiting for a reviewer, one value claim set aside, and the two fallback lines. The decision line was left blank. Nothing was asked for and nothing stopped the run.
- **Every score, total, range and rank matched the published example.** The three top places were the weekly contract cost report (14), supplier invoice matching (12) and the tender summary (11).
- **Differences from the example were wording and layout only.** The example's header line says "settings not supplied; default used" where the format only says "[default used]", and I wrote "default used". The example is formatted in Markdown (bold headings, bullets) and this run kept the plain layout of the format. The wording of three Find out questions differs ("the company's approved AI workspace" here against "the approved AI workspace"; the planned maintenance friction question is worded differently; the quote follow-up frequency question is worded differently). The example adds a "How the figures were worked" section that the format does not ask for. No difference changed a score or a list.
- **Facts not in the inputs.** None in the scorecard. The only addition is the word "company's" in two Find out questions, which comes from the template's wording about the company's approved workspace. The example's output adds nothing beyond its inputs either.
- **Where the instructions needed a judgement or were open to two readings:**
  1. Input readiness for the weekly cost report: "timesheet and purchase-order exports from the accounts system" is two exports from one system. I read that as one place (3). The reading of "one place" does not say whether two exports count.
  2. Friction for the unanswered quote follow-up: quotes "wait in the inbox until an estimator has time". The readings give 3 for waiting at a handoff and 2 for slow but steady with no waiting named. Waiting for someone's time is neither. I scored 3, which matches the example, but it is a reading, and Unknown was equally defensible.
  3. The reviewer cells "none: reminders go out automatically" and "none: the estimator sends them" are not exactly "none". I treated them as "none".
  4. The output format's header line shows "[default used]" without saying how to word it when settings are supplied or not.
  5. The format gives no wording for a Find out question, or for how the Answer first section should repeat several Find out lines for one row. I repeated them in full on one line, which reads awkwardly.
  6. "Overdue invoice reminders" is scored 2 on effort because sending needs a live connection, although the template never sends anything. The effort factor measures the future workflow, which the template does not say.
  7. Tender friction: the cell reads as a handoff wait (3) and the room changed it to 2 with a reason. The template applies the change as given, as it should, but the printed score no longer fits the friction reading, which is by design and worth knowing.
- **Reviewer checklist.** All eight items hold on this output: each row appears once under Scores and once in the ranked list; each score quotes its cell; no blank was given a number; totals and ranges add up (for example, 6 known plus two Unknowns gives 8 to 12); every Unknown has a Find out line with who and when left blank; the room's change shows old score, new score, role and reason; no row with an Unknown or a consequence of 1 is under the top of the list; nothing states a value or names a winner.
- **Stops.** The template told the run to stop in no case here, so none of its stop conditions was exercised. Several acceptance tests (mismatched header, repeated name, asked to pick) were not tried, and the template says its tests have not been run.
- **Limits of this trial.** One run, one model, one product, on sample inputs. It shows the instructions can be followed to the published result on this example. It says nothing about messy real lists or other products.
