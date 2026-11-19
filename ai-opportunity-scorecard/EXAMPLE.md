# AI opportunity scorecard: an example

*Illustrative example with sample data.* The company, the roles, the ideas and the dates below are all illustrative. The company is an illustrative 70-person building services contractor that installs and maintains heating, cooling and electrical systems for commercial customers. Its operations director brought eight ideas to a leadership session and ran the workflow template on them. First come the inputs, in full, then the scorecard it returned. Nothing here describes a real organization or a measured result.

## The inputs

### 1. The scoring session

```
Team or outcome: whole company, first AI workflows
Roles in the room: Operations director, Finance manager, Service manager,
  Estimating lead, Office manager
Date: 2026-10-05
Settings: not supplied
Last quarter's scorecard: not supplied
Workflow inventory: not supplied
```

### 2. The opportunity list

```
opportunity,team,proposed_by,how_often,friction,records,ai_use_allowed,reviewer,output_goes_to,roles_involved,systems,notes
Weekly contract cost report,Finance,Finance manager,every Monday,"slow but steady: takes most of Monday morning",timesheet and purchase-order exports from the accounts system,yes,Finance manager,inside the company: the operations meeting,Finance assistant,"accounts system exports, no live connection",
Service visit reports,Service,Service manager,about 40 a week,"typed up again by the office, and often sent back for missing details",engineers' notes in the service management system,,Service manager,customers,"Service engineer, Service coordinator","service management system export, no live connection",
Tender bid or no-bid summary,Estimating,Estimating lead,two or three tenders a month,waits up to a week for the estimating lead's review,tender documents arrive by email; past bids in a shared folder,yes,Estimating lead,inside the company: the go or no-go decision,"Estimator, Estimating lead, Operations director","email and shared folder, files only",
Overdue invoice reminders,Finance,Credit controller,weekly,runs smoothly,aged debt report in the accounts system,yes,none: reminders go out automatically,customers,Credit controller,"accounts system, sending needs a live connection",
Supplier invoice matching,Finance,Finance manager,daily,invoices wait for a site manager to confirm delivery,purchase orders in the accounts system; delivery notes on paper at each site,yes,Accounts payable clerk,a payment: releases supplier payments,"Accounts payable clerk, Site manager","accounts system export and scanned delivery notes, no live connection",Finance manager thinks it would save a day a week
Quarterly vehicle compliance check,Operations,Office manager,quarterly,runs smoothly,vehicle documents in a filing cabinet and a spreadsheet,yes,Office manager,inside the company,Office manager,"one spreadsheet, no live connection",
Planned maintenance schedule,Service,Service coordinator,monthly,,contract register in the service management system,,Service manager,customers,"Service coordinator, Service manager","service management system, would need a live connection",
Unanswered quote follow-up,Estimating,Operations director,,quotes wait in the inbox until an estimator has time to chase them,quotes in the estimating spreadsheet and the estimators' inboxes,yes,none: the estimator sends them,customers,Estimator,"spreadsheet and email, files only",
```

### 3. Changes from the room

```
Tender bid or no-bid summary | Friction | 2 | Estimating lead | the wait
  only happens in the busy months
```

## The output

**OPPORTUNITY SCORECARD: whole company, first AI workflows**

Scored by: Operations director, Finance manager, Service manager, Estimating lead, Office manager. Date: 2026-10-05. Each factor: 3, 2, 1 or Unknown.
Read: 8 opportunities. Fully scored: 5. With an Unknown: 3. Top of the list: 3 places (settings not supplied; default used).
Changes from the room: 1.

**Scores**

1. **Weekly contract cost report** (Finance; proposed by Finance manager)
   - Frequency 3: "every Monday"
   - Friction 2: "slow but steady: takes most of Monday morning"
   - Input readiness 3: "timesheet and purchase-order exports from the accounts system"; allowed: "yes"
   - Consequence of error 3: reviewer "Finance manager"; goes to "inside the company: the operations meeting"
   - Implementation effort 3: "Finance assistant"; "accounts system exports, no live connection"
   - Total: 14 of 15
   - Find out: none
2. **Service visit reports** (Service; proposed by Service manager)
   - Frequency 3: "about 40 a week"
   - Friction 3: "typed up again by the office, and often sent back for missing details"
   - Input readiness Unknown: "engineers' notes in the service management system"; allowed: blank
   - Consequence of error 2: reviewer "Service manager"; goes to "customers"
   - Implementation effort 2: "Service engineer, Service coordinator"; "service management system export, no live connection"
   - Total: 11 to 13 of 15 (1 Unknown)
   - Find out: May the engineers' notes in the service management system be used in the approved AI workspace? Who answers: ______ By when: ______
3. **Tender bid or no-bid summary** (Estimating; proposed by Estimating lead)
   - Frequency 2: "two or three tenders a month"
   - Friction 2: "waits up to a week for the estimating lead's review"
   - Input readiness 2: "tender documents arrive by email; past bids in a shared folder"; allowed: "yes"
   - Consequence of error 3: reviewer "Estimating lead"; goes to "inside the company: the go or no-go decision"
   - Implementation effort 2: "Estimator, Estimating lead, Operations director"; "email and shared folder, files only"
   - Changed in the room: Friction from 3 to 2 by Estimating lead: "the wait only happens in the busy months"
   - Total: 11 of 15
   - Find out: none
4. **Overdue invoice reminders** (Finance; proposed by Credit controller)
   - Frequency 3: "weekly"
   - Friction 1: "runs smoothly"
   - Input readiness 3: "aged debt report in the accounts system"; allowed: "yes"
   - Consequence of error 1: reviewer "none: reminders go out automatically"; goes to "customers"
   - Implementation effort 2: "Credit controller"; "accounts system, sending needs a live connection"
   - Total: 10 of 15
   - Find out: none
5. **Supplier invoice matching** (Finance; proposed by Finance manager)
   - Frequency 3: "daily"
   - Friction 3: "invoices wait for a site manager to confirm delivery"
   - Input readiness 2: "purchase orders in the accounts system; delivery notes on paper at each site"; allowed: "yes"
   - Consequence of error 2: reviewer "Accounts payable clerk"; goes to "a payment: releases supplier payments"
   - Implementation effort 2: "Accounts payable clerk, Site manager"; "accounts system export and scanned delivery notes, no live connection"
   - Total: 12 of 15
   - Find out: none
6. **Quarterly vehicle compliance check** (Operations; proposed by Office manager)
   - Frequency 1: "quarterly"
   - Friction 1: "runs smoothly"
   - Input readiness 2: "vehicle documents in a filing cabinet and a spreadsheet"; allowed: "yes"
   - Consequence of error 3: reviewer "Office manager"; goes to "inside the company"
   - Implementation effort 3: "Office manager"; "one spreadsheet, no live connection"
   - Total: 10 of 15
   - Find out: none
7. **Planned maintenance schedule** (Service; proposed by Service coordinator)
   - Frequency 2: "monthly"
   - Friction Unknown: blank
   - Input readiness Unknown: "contract register in the service management system"; allowed: blank
   - Consequence of error 2: reviewer "Service manager"; goes to "customers"
   - Implementation effort 2: "Service coordinator, Service manager"; "service management system, would need a live connection"
   - Total: 8 to 12 of 15 (2 Unknown)
   - Find out: Where, if anywhere, does the planned maintenance schedule wait, get typed in again or get redone? Who answers: ______ By when: ______
   - Find out: May the contract register in the service management system be used in the approved AI workspace? Who answers: ______ By when: ______
8. **Unanswered quote follow-up** (Estimating; proposed by Operations director)
   - Frequency Unknown: blank
   - Friction 3: "quotes wait in the inbox until an estimator has time to chase them"
   - Input readiness 2: "quotes in the estimating spreadsheet and the estimators' inboxes"; allowed: "yes"
   - Consequence of error 1: reviewer "none: the estimator sends them"; goes to "customers"
   - Implementation effort 3: "Estimator"; "spreadsheet and email, files only"
   - Total: 10 to 12 of 15 (1 Unknown)
   - Find out: How often do quotes need a follow-up: how many a week or a month? Who answers: ______ By when: ______

**Ranked list**

1. Weekly contract cost report: 14
2. Supplier invoice matching: 12
3. Service visit reports: 11 to 13 (Answer first)
4. Tender bid or no-bid summary: 11
5. Unanswered quote follow-up: 10 to 12 (Waiting for a reviewer)
6. Overdue invoice reminders: 10 (Waiting for a reviewer)
7. Quarterly vehicle compliance check: 10
8. Planned maintenance schedule: 8 to 12 (Answer first)

**Top of the list (all five known, a reviewer named)**

- Weekly contract cost report, 14 of 15. Starts from: "timesheet and purchase-order exports from the accounts system". Reviewed by: Finance manager.
- Supplier invoice matching, 12 of 15. Starts from: "purchase orders in the accounts system; delivery notes on paper at each site". Reviewed by: Accounts payable clerk.
- Tender bid or no-bid summary, 11 of 15. Starts from: "tender documents arrive by email; past bids in a shared folder". Reviewed by: Estimating lead.

**Answer first (a range that reaches the top of the list)**

- Service visit reports, 11 to 13.
  - Find out: May the engineers' notes in the service management system be used in the approved AI workspace? Who answers: ______ By when: ______
- Planned maintenance schedule, 8 to 12.
  - Find out: Where, if anywhere, does the planned maintenance schedule wait, get typed in again or get redone? Who answers: ______ By when: ______
  - Find out: May the contract register in the service management system be used in the approved AI workspace? Who answers: ______ By when: ______

**Waiting for a reviewer (consequence of error 1)**

- Unanswered quote follow-up, 10 to 12. Reviewer: "none: the estimator sends them". Goes to: "customers".
- Overdue invoice reminders, 10. Reviewer: "none: reminders go out automatically". Goes to: "customers".

**Value claims not scored**

- Supplier invoice matching: "Finance manager thinks it would save a day a week"

**Since the last scoring**

first scoring, or last scorecard not supplied

**Already in the workflow inventory**

workflow inventory not supplied

**What the score leaves to the people**

- Strategy may put an idea first whatever its score. That is the room's call.
- A score says a piece of work is ready to try. Only a pilot on real cases shows it works.
- Value is measured after choosing, from the chosen workflow's own baseline.
- Any score the room disputes is the room's to change, with a reason.
- Score again next quarter, with the Find out lines answered.

Decision (the leadership team): ______________________

Draft for the Operations director. Scores come only from the facts supplied. Nothing is estimated, chosen, sent or changed.

## How the figures were worked (not part of the output)

- **Totals.** Contract cost report 3 + 2 + 3 + 3 + 3 = 14. Supplier invoice matching 3 + 3 + 2 + 2 + 2 = 12. Tender summary 2 + 2 + 2 + 3 + 2 = 11, after the room's change to friction (11 + 1 = 12 before it). Overdue reminders 3 + 1 + 3 + 1 + 2 = 10. Vehicle check 1 + 1 + 2 + 3 + 3 = 10.
- **Ranges.** Service visit reports: known 3 + 3 + 2 + 2 = 10, one Unknown, so 11 to 13. Planned maintenance: known 2 + 2 + 2 = 6, two Unknowns, so 8 to 12. Quote follow-up: known 3 + 2 + 1 + 3 = 9, one Unknown, so 10 to 12.
- **Order.** Middles: 14, 12, 12, 11, 11, 10, 10, 10. Supplier invoice matching sits above service visit reports because it is fully scored; the tender summary above quote follow-up for the same reason. Overdue reminders sit above the vehicle check on frequency (3 against 1), and planned maintenance last because it has Unknowns.
- **Answer first.** The third place in the top of the list is 11. Service visit reports can reach 13 and planned maintenance 12, so both are listed. Quote follow-up can reach 12 but scores 1 on consequence of error, so it waits for a reviewer instead.
