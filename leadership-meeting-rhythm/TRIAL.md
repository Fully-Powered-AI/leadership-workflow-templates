# Leadership meeting rhythm: trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-10

This record is of the second run. An earlier run, the same day, led to the first round of review edits (listed at the end). After a second review, the instruction block, the procedure, the output format and the example were changed again, so the template was run once more. The inputs are the invented Pellacombe Facilities example in `public/example.md`: the settings, the meeting list, the decisions waiting and the existing reports, with one change from the earlier run (the tender in W1 is now for schools refurbishment, not cleaning, so that the invented company is a building contractor). No client data was used.

## How the run went

This run was not independent. It was made by the model that also applied the review edits, with the example's earlier published output and the earlier run's record open beside it. It follows the fenced instruction block and the output format in `member/template.md` as they now stand, step by step, and checks that the revised block still produces the proposal the example shows, with the changes the new rules call for. It does not show how a model that had seen none of this would do. The hours and the days waiting were worked out again by hand and rechecked. Because the model had the example open, the output below was written to the example's wording where the block leaves the wording open (for instance the name "weekly pipeline note"); where the block decides the content, the output follows the block.

## What came out

```
LEADERSHIP MEETING RHYTHM: proposal for Joanna, Pellacombe Facilities

Prepared Tuesday 10 November 2026 from: meeting list (8 meetings), decisions waiting (6), existing reports (3), settings.
Chief executive's hours in recurring meetings: today 301 a year (5.8 a week); proposed 119 a year (2.3 a week); change -182 a year (-3.5 a week).
Everyone's hours in recurring meetings: today 1,667 person-hours a year; proposed 887; change -780. Time spent writing reports is not counted.
Ceiling: 4 hours a week. Today: over by 1.8. Proposed: within it.

Questions for Joanna: 4
1. Operations review: Priya owns its decisions and you attend every week, 52 hours a year. You also attend the service quality huddle, which would join it, where Ben owns the decisions (26 hours a year). The proposal has you leave both and read Priya's and Ben's lines in the weekly leadership report, which takes 78 hours a year off your calendar. Do you leave, or stay?
2. People catch-up: no decision owner is named, and its decisions in the last 90 days were not counted. Who decides there? Elif, as chair, can supply the count.
3. W1, whether to bid for the council schools refurbishment tender: its note says "Tender closes 4 December 2026", and it goes on the first agenda of the leadership decision forum, which meets every two weeks. Does the forum's first sitting come before that date, or does the decision need to be taken sooner?
4. W4, replace the van leasing supplier: no one is named who can decide, and whether it can be undone is not known. It has waited 35 days. Who decides, and can it be undone?

Current meetings: 7
1. Monday leadership meeting (Monday, weekly, 120 minutes, 7 attendees). Decision owner: none named. Decisions in the last 90 days: 2. Papers before: none. Chief executive: 104 hours a year. Everyone: 728 person-hours a year.
   Findings: no decision owner named; few decisions (2); no papers before.
   Waiting decisions raised here: W1, 50 days.
   Proposed: Change into the leadership decision forum (forum 1): every two weeks on Monday, 90 minutes, Joanna deciding; updates move into the weekly leadership report (report 1). Joanna chooses.
2. Operations review (Thursday, weekly, 60 minutes, 6 attendees). Decision owner: Priya. Decisions in the last 90 days: 9. Papers before: Service dashboard, sent Wednesday. Chief executive: 52 hours a year. Everyone: 312 person-hours a year.
   Findings: overlaps the service quality huddle (Ben, Priya and Joanna attend both, and both cover complaints); the chief executive attends and Priya owns the decisions.
   Waiting decisions raised here: W2, 33 days.
   Proposed: Change: absorbs the service quality huddle as a standing item on complaints and audit results, owned by Ben, at the same 60 minutes; Joanna leaves and reads Priya's lines in the weekly leadership report (question 1). Joanna chooses.
3. Sales pipeline call (Wednesday, weekly, 45 minutes, 5 attendees). Decision owner: Tomasz. Decisions in the last 90 days: 0. Papers before: Pipeline export, shared on screen in the call. Chief executive: 39 hours a year. Everyone: 195 person-hours a year.
   Findings: no decisions in 90 days; no papers before (first seen in the call); the chief executive attends and Tomasz owns the decisions.
   Waiting decisions raised here: W3, 41 days.
   Proposed: Replace with written report: the weekly pipeline note (report 2). Joanna chooses.
4. Monthly finance review (first Tuesday, monthly, 90 minutes, 4 attendees). Decision owner: Joanna. Decisions in the last 90 days: 3. Papers before: Management accounts, sent the day before. Chief executive: 18 hours a year. Everyone: 72 person-hours a year.
   Findings: none.
   Waiting decisions raised here: W4, 35 days.
   Proposed: Keep. Joanna chooses.
5. People catch-up (Tuesday, every two weeks, 60 minutes, 3 attendees). Decision owner: none named. Decisions in the last 90 days: not known. Papers before: none. Chief executive: 26 hours a year. Everyone: 78 person-hours a year.
   Findings: no decision owner named; decisions not known; no papers before.
   Waiting decisions raised here: W6, 21 days.
   Proposed: Change: a decision owner named (question 2); training, policy and staffing papers from Elif, sent two working days before. Joanna chooses.
6. Quarterly planning day (varies, quarterly, 360 minutes, 6 attendees). Decision owner: Joanna. Decisions in the last 90 days: 5. Papers before: Each lead's one-page review, sent a week before. Chief executive: 24 hours a year. Everyone: 144 person-hours a year.
   Findings: none.
   Waiting decisions raised here: none.
   Proposed: Keep. Joanna chooses.
7. Service quality huddle (Friday, weekly, 30 minutes, 3 attendees). Decision owner: Ben. Decisions in the last 90 days: 1. Papers before: none. Chief executive: 26 hours a year. Everyone: 78 person-hours a year.
   Findings: few decisions (1); overlaps the operations review (Ben, Priya and Joanna attend both, and both cover complaints); no papers before; the chief executive attends and Ben owns the decisions.
   Waiting decisions raised here: W5, 25 days.
   Proposed: Merge into the operations review: a standing item on complaints and audit results, owned by Ben. Joanna chooses.

Proposed forums: 5
1. Leadership decision forum
   Purpose: the leadership team's decisions, taken by the chief executive; updates are read in the weekly leadership report instead.
   Decides: the waiting decisions routed here and those raised in the weekly leadership report.
   Inputs: the weekly leadership report; a one-page paper for each decision on the agenda, from the person who raised it, sent two working days before.
   Attendees: Joanna; Marcus; Priya; Tomasz; Elif; Ben; Hana
   Frequency and length: every two weeks, Monday, 90 minutes
   Decision owner: Joanna
   Replaces or changes: changes the Monday leadership meeting (meeting 1).
   Chief executive: 39 hours a year. Everyone: 273 person-hours a year.
   First decisions: W1, W3
2. Operations review
   Purpose: contract performance, staffing gaps, complaints and audit results.
   Decides: operations decisions, Priya; complaints and audit actions, Ben.
   Inputs: Service dashboard, from Priya, sent Wednesday.
   Attendees: Priya; Ben; Area manager North; Area manager South; Area manager Central
   Frequency and length: weekly, Thursday, 60 minutes
   Decision owner: Priya; Ben for the complaints and audit item
   Replaces or changes: changes meeting 2; absorbs the service quality huddle (meeting 7); Joanna leaves (question 1).
   Chief executive: 0 hours a year. Everyone: 260 person-hours a year.
   First decisions: none waiting
3. Monthly finance review
   Purpose: management accounts and cash.
   Decides: decisions on the management accounts and cash, Joanna.
   Inputs: Management accounts, from Marcus, sent the day before.
   Attendees: Marcus; Joanna; Priya; Tomasz
   Frequency and length: monthly, first Tuesday, 90 minutes
   Decision owner: Joanna
   Replaces or changes: unchanged (meeting 4).
   Chief executive: 18 hours a year. Everyone: 72 person-hours a year.
   First decisions: none waiting
4. People catch-up
   Purpose: training, policy changes and staffing levels.
   Decides: training, policy and staffing-level decisions.
   Inputs: training, policy and staffing papers, from Elif, sent two working days before.
   Attendees: Elif; Joanna; Priya
   Frequency and length: every two weeks, Tuesday, 60 minutes
   Decision owner: not named: see question 2
   Replaces or changes: changes meeting 5: a decision owner and papers before.
   Chief executive: 26 hours a year. Everyone: 78 person-hours a year.
   First decisions: none waiting
5. Quarterly planning day
   Purpose: set next quarter's priorities.
   Decides: next quarter's priorities, Joanna.
   Inputs: each lead's one-page review, sent a week before.
   Attendees: Joanna; Marcus; Priya; Tomasz; Elif; Ben
   Frequency and length: quarterly, day varies, 360 minutes
   Decision owner: Joanna
   Replaces or changes: unchanged (meeting 6).
   Chief executive: 24 hours a year. Everyone: 144 person-hours a year.
   First decisions: none waiting

Proposed written reports: 2
1. Weekly leadership report. When: weekly, Friday, 12:00. Owner: Hana, with each leader writing their own lines. Readers: Joanna; Marcus; Priya; Tomasz; Elif; Ben. Contents: up to five lines per leader: numbers against plan (Priya from the service dashboard, Tomasz from the pipeline export, Marcus monthly from the management accounts), what changed, decisions needed and who decides each, decisions taken without a meeting. Replaces: the updates in the Monday leadership meeting; Joanna's attendance at the operations review and the service quality huddle.
2. Weekly pipeline note. When: weekly, Wednesday, 12:00. Owner: Tomasz. Readers: Joanna; Marcus; Account manager A; Account manager B. Contents: the pipeline export, plus the deals and renewals that need a decision and who decides each. Replaces: the sales pipeline call (meeting 3).

Waiting decisions: 6
W1. Whether to bid for the council schools refurbishment tender. Raised 2026-09-21 in the Monday leadership meeting by Tomasz; waiting 50 days, OVERDUE. Can decide: Joanna. Reversible: no. Note: Tender closes 4 December 2026. Route: leadership decision forum, first agenda; date in note: see question 3.
W2. Move night-shift supervisors from paper timesheets to the mobile app. Raised 2026-10-08 in the operations review by Priya; waiting 33 days, OVERDUE. Can decide: Priya. Reversible: yes. Route: Priya decides without a meeting and records it in the weekly leadership report.
W3. Price increase for contracts renewing in January. Raised 2026-09-30 in the sales pipeline call by Tomasz; waiting 41 days, OVERDUE. Can decide: Joanna. Reversible: no. Route: leadership decision forum, first agenda.
W4. Replace the van leasing supplier when the current leases end in March. Raised 2026-10-06 in the monthly finance review by Marcus; waiting 35 days, OVERDUE. Can decide: not stated. Reversible: not known. Route: NO DECIDER: see question 4.
W5. Adopt the new client complaints procedure. Raised 2026-10-16 in the service quality huddle by Ben; waiting 25 days. Can decide: Ben. Reversible: yes. Route: Ben decides without a meeting and records it in the weekly leadership report.
W6. Supervisors' training budget for next year. Raised 2026-10-20 in the people catch-up by Elif; waiting 21 days. Can decide: Joanna. Reversible: yes. Route: Joanna decides without a meeting and records it in the weekly leadership report.

Not redesigned: Board meeting: chief executive 12 hours a year, everyone 60 person-hours a year, counted in both totals.

Calendar changes, for Hana to make once Joanna chooses: 7
- Monday leadership meeting: becomes the leadership decision forum, every two weeks on Monday, 90 minutes. Waits on: the choice for meeting 1.
- Weekly leadership report: starts, Fridays by 12:00. Waits on: the choice for meeting 1.
- Operations review: adds the complaints and audit results item, still 60 minutes. Waits on: the choice for meeting 7.
- Operations review: Joanna comes off the invitation. Waits on: question 1.
- Sales pipeline call: the series ends and the weekly pipeline note starts, Wednesdays by 12:00. Waits on: the choice for meeting 3.
- People catch-up: the decision owner is named in the invitation, with papers two working days before. Waits on: question 2 and the choice for meeting 5.
- Service quality huddle: the series ends. Waits on: the choice for meeting 7.

Draft for Joanna. No calendar, invitation or record has been changed and no one has been contacted.
```

## What was observed

**Every required part was produced,** in the order the format gives: the header, the questions, the seven current meetings with findings and a proposal each, the five proposed forums, the two written reports, the six waiting decisions, the board meeting under "Not redesigned" and the calendar changes. The inputs were complete and well formed, so no stop condition applied.

**The figures were rechecked.** Each hours figure is the meeting's length in hours times its sittings a year, times its attendees for everyone's hours. The yearly totals are 301 and 1,667 today and 119 and 887 proposed; each weekly figure is the yearly one divided by 52, to one decimal place. The days waiting run from each raised date to 10 November 2026 (50, 33, 41, 35, 25 and 21).

**What the revised rules changed in the output.**
- The date in W1's note ("Tender closes 4 December 2026") now raises question 3, asking whether the leadership decision forum's first sitting comes before that date, and W1's route line ends "date in note: see question 3". The assistant does not work out the sittings itself. The question about W4 became question 4.
- The first question counts both meetings Joanna would leave, the operations review (52 hours) and the service quality huddle (26 hours), and says what the two together take off her calendar (78 hours a year). The weekly leadership report's "Replaces" line names both.
- Hana, who attends the Monday meeting but is not on the leadership team, stays on the leadership decision forum's attendee list and is not a reader of the weekly leadership report; she compiles it.

**Where the instructions still needed a guess or a reading.**
1. "The same subject" in the overlap test is judged by the assistant. This run judged "complaints" to be the same subject in the operations review's and the service quality huddle's purposes, and said so in the finding so that Joanna can overrule it.
2. The "Decides" line of a kept meeting has no source in the inputs other than its stated purpose. This run restated the purpose, as the block now says.
3. The block says to ask about a date in a note only for a decision routed to a forum. A reversible decision decided without a meeting (W2, W5, W6) has no date in its note here, so that case was not exercised.
4. The Purpose line of the leadership decision forum is the assistant's own wording from the template's description; it is not a fact about the company.
5. How to word a "Change, fixes only" proposal whose only fix is a question is left to the assistant.

**Facts not in the inputs.** None beyond the Purpose and Decides wording, which restates each meeting's stated purpose.

**The acceptance tests were not run.** The twelve earlier tests and the new thirteenth (a date in a note) are proposed only. This was one run on the example, and the template's statement that none has been run is correct.

**Earlier run and the edits made after it.** The first run, with the earlier text of the block, found these defects, which were then fixed: the block left out the stop on two meetings with the same name, the rule not to repeat a password, login code or dial-in code, the id-only reference to a decision about one person's pay, performance, health or conduct, and the leadership forum's tie-break and "new" fallback. The procedure was made to say that the overlap test counts either direction, that the finding names the subject, that a kept meeting's "Decides" line restates its stated purpose, and that dates are shown as supplied. The record of that run was replaced by this one; its output is not reproduced here.

**What this does not show.** It shows that one model, given the example's inputs and the revised instructions, can follow them and reach the proposal the example shows. It does not show that the template works on a real company's lists, in any other AI product, or with a different model.
