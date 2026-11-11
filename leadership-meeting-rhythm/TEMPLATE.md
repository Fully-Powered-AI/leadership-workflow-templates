# Leadership meeting rhythm

Capability template, version 0.1.0.

## Purpose

Propose a calendar of leadership forums and written reports for a chief executive whose recurring meetings leave too little room for decisions. The proposal is built from two things the company already has: the list of meetings it holds today and the list of decisions that are waiting. Every current meeting is examined in turn and given one proposed choice (keep, change, merge into another, or replace with a written report), and every proposed forum carries its purpose, what it decides, its inputs, its attendees, its frequency and length, and one decision owner. Each waiting decision is given a route. The hours the chief executive and everyone else spend in recurring meetings are counted today and under the proposal. The chief executive chooses which forums to keep, change or retire. The assistant changes no calendar, sends no invitation, contacts nobody and decides none of the waiting decisions.

## When to use it and when not to

Use it when a chief executive or owner says the week is full of meetings and the decisions still wait; after the company grows, adds a leadership role or restructures; once a year as a check; or when a new chief executive takes over a calendar built by someone else.

Do not use it for:

- one meeting's agenda, record and follow-ups, which belong to Meeting agenda, notes and follow-ups;
- keeping the register of what the leadership approved, which belongs to Decision log; that register can supply the decision counts this capability reads;
- the board meeting and its papers, which belong to Board meeting pack; the board meeting is counted in the hours here and never redesigned;
- deciding who sits on the leadership team, judging how any person performs, or settling any of the waiting decisions;
- changing invitations or calendars. A person makes every change after the chief executive chooses.

## Roles

- **Starts it and chooses:** the chief executive or owner. They choose, meeting by meeting, what to keep, change, merge or retire, and answer the questions the proposal raises.
- **Runs it:** the chief executive, or a chief of staff or executive assistant on their behalf, who gathers the inputs.
- **Record keeper:** the person named in the settings who compiles the weekly leadership report and, once the chief executive has chosen, makes the calendar changes.
- **Chairs and decision owners:** the people named on the meeting list. A chair can supply a missing decision count.
- **The AI assistant:** counts, checks, proposes and lists questions. It changes nothing and contacts nobody.

## Inputs

Everything is pasted or attached by a person. No calendar, mailbox or meeting tool is connected, and the assistant never asks for a password or a login code.

1. **The meeting list,** one row per recurring internal meeting the leadership attends. Default column headers: `meeting, purpose, day, frequency, length_minutes, attendees, chair, decision_owner, decisions_last_90_days, papers_before`. Attendees are separated by semicolons. `frequency` is one of: daily, weekly, every two weeks, monthly, quarterly. `decisions_last_90_days` is the number of decisions the meeting recorded in the last 90 days, from its notes or the decision log; blank means not known, never zero. If a header does not match, stop and ask which column holds which field. If the list is missing, stop.
2. **The decisions waiting,** one row per decision raised and not yet made. Default column headers: `id, decision, raised_on, raised_in, raised_by, can_decide, reversible, note`. `raised_on` is a date (YYYY-MM-DD). `reversible` is yes, no or blank (not known). If a header does not match, stop and ask. If the list is missing, write "none supplied" and skip the routing.
3. **The reports that already exist,** if any. Default column headers: `report, frequency, owner, readers, sent`. If missing, write "none supplied".
4. **Your settings:**
   - today's date (if missing, ask and stop: days waiting cannot be counted without it);
   - the company and its size;
   - the chief executive, by name (if missing, ask and stop);
   - the leadership team, by name and role;
   - the record keeper (if missing, the report owner is "to be named");
   - [your ceiling]: the most hours a week the chief executive wants in recurring internal meetings (if missing, write "Ceiling: not set");
   - [your low-decision count] (default 3), [your waiting limit] (default 30 days), [your attendee limit] (default 8), [your report day and time] (default Friday 12:00);
   - meetings not redesigned (default: the board meeting).

## The procedure

1. **Check the inputs.** Check the headers of each list. Check every frequency is one of the five values and every length is a number; if not, stop and ask about that meeting. Count the meetings and the waiting decisions.
2. **Set aside what is not redesigned.** A meeting named in the settings as not redesigned, and any meeting whose purpose names one person's pay, performance, health or conduct, goes under "Not redesigned" with its hours, referred to by its name only. Its hours stay in both totals. It is not numbered among the current meetings.
3. **Count the hours.** Sittings a year: daily 250, weekly 52, every two weeks 26, monthly 12, quarterly 4. For each meeting: chief executive hours a year = length in hours × sittings, if the chief executive attends, else 0; everyone's person-hours a year = length in hours × sittings × number of attendees. A week is the yearly figure ÷ 52, to one decimal place. Add the totals for today.
4. **Find the leadership forum.** It is the current meeting the whole leadership team attends, chaired by the chief executive, that meets at least every two weeks. If more than one fits, take the most frequent. If none fits, propose one, marked "new", under Proposed forums.
5. **Record the findings** for each current meeting, in this order:
   1. **No decision owner named.**
   2. **Decisions not known:** the count is blank. Never treat it as zero.
   3. **No decisions in 90 days:** the count is 0.
   4. **Few decisions:** more than 0 and fewer than [your low-decision count].
   5. **Overlaps [meeting]:** every attendee of one of the two meetings also attends the other (either direction counts), and their two stated purposes name the same subject. Say in the finding what the subject is, so the chief executive can overrule it.
   6. **More than [your attendee limit] attendees.**
   7. **No papers before:** `papers_before` is "none", or the papers are first seen in the meeting.
   8. **The chief executive attends and someone else owns the decisions.**
   If none applies, write "none". Also list the waiting decisions raised in the meeting, with their days waiting.
6. **Propose one choice per current meeting.** Take the first that applies:
   1. **Merge into [meeting]:** for two overlapping meetings, the one with fewer known decisions joins the other as a standing item. The absorbing meeting keeps its length, and the merged meeting's decision owner owns that item. The absorbing meeting is proposed as a change.
   2. **Replace with written report:** for no decisions in 90 days. The report goes out on the meeting's own day by 12:00. Its owner is the chair, its readers are the other attendees, and it carries the papers the meeting used plus the items that need a decision and who decides each.
   3. **Change into the leadership decision forum:** for the leadership forum. Every two weeks on its current day, 90 minutes, the chief executive as decision owner. Everyone who attends the meeting today stays on the forum's attendee list, including a person who is not on the leadership team, unless the chief executive removes them. Updates move into the weekly leadership report. Each decision on the agenda comes with a one-page paper from the person who raised it, sent two working days before.
   4. **Change, meeting every two weeks:** for few decisions in a meeting that sits weekly or more often. Its updates move into the weekly leadership report and it keeps its decisions.
   5. **Change, fixes only:** for any other finding. No decision owner: a question; never name one. More than [your attendee limit] attendees: keep those who decide or bring a paper, with the chief executive choosing the names; never choose them. No papers before: papers from the chair, sent two working days before. The chief executive attends and someone else owns the decisions: propose that they leave and read the decision owner's lines in the weekly leadership report, and ask. These fixes also apply to an absorbing meeting or a meeting moved to every two weeks that remains on the calendar, and to the leadership decision forum except for its owner and its papers, which 6.3 sets.
   6. **Keep:** no findings.
   Never propose anything that adds more chief executive hours than the proposal removes, unless the chief executive asks.
7. **Propose the written reports.** The weekly leadership report is proposed whenever the leadership forum changes or the chief executive leaves a meeting: sent [your report day and time], compiled by the record keeper, read by the leadership team named in the settings (the record keeper and a person outside the leadership team who attends the forum are not readers unless the chief executive adds them); each leader writes up to five lines: numbers against plan from the existing reports they own, what changed, decisions they need with who decides each, and decisions they took without a meeting. A report replacing a meeting (6.2) is listed separately when its readers include people outside the leadership team; otherwise it becomes that chair's lines in the weekly leadership report.
8. **Route each waiting decision,** in id order. Days waiting = today − `raised_on`. More than [your waiting limit] days: mark it OVERDUE.
   1. No one named under `can_decide`: NO DECIDER, and a question that also asks whether it can be undone if `reversible` is blank.
   2. Reversible, with one person who can decide: that person decides without waiting for a meeting and records it in their lines of the weekly leadership report.
   3. Otherwise: the proposed forum whose decision owner is the person who can decide and whose purpose names the subject; if none names it and the decider is the chief executive, the leadership decision forum; otherwise the forum that person owns that meets most often. If no forum fits, NO FORUM, and a question.
   Decisions routed to a forum go on its first agenda, longest waiting first. Never say what the decision should be. Show `raised_on` dates as supplied (YYYY-MM-DD). Show a date in a note as supplied; do not check it against the forum's sittings. A decision routed to a forum whose note holds a date also gets a question for the chief executive (10) asking whether the forum's first sitting comes before that date or the decision needs to be taken sooner, and its route line ends "; date in note: see question [n]". A kept meeting's "Decides" line restates its stated purpose; never invent decisions.
9. **Count the proposal.** Hours for each proposed forum and for what is not redesigned, then the totals, the change from today, and whether today and the proposal are within [your ceiling]. Writing time for reports is not counted; say so.
10. **Write the questions first,** one each: current meetings in list order, then waiting decisions in id order (a decision routed to a forum with a date in its note, and a decision with no decider or no forum, each get one). Ask only about meetings that remain on the proposed calendar.
11. **List the calendar changes** the record keeper would make once the chief executive chooses, in current-meeting order, each with the choice or question it waits on.
12. **Return the draft to the chief executive.** When they choose or answer, update the draft, mark each answer "chosen by [name] on [date]", recount the hours, and keep the calendar changes as a list for the record keeper.

## Exceptions and stop conditions

- **A header does not match, a frequency is not one of the five values, or a length is not a number:** stop and ask; propose nothing.
- **No meeting list, no today's date or no chief executive named:** stop and ask.
- **Two meetings with the same name:** stop and ask which is which.
- **Asked to change a calendar, send or cancel an invitation, or message attendees:** decline; the record keeper does it once the chief executive has chosen.
- **Asked who should be on the leadership team, or to judge any person's performance:** decline; that is the chief executive's call and not part of this work.
- **Asked to settle a waiting decision or to recommend what it should be:** decline; route it and leave it to the person who can decide.
- **A meeting or waiting decision concerns one person's pay, performance, health or conduct:** refer to it by its name or id only; do not repeat the detail.
- **The inputs contain a password, a login code or meeting dial-in codes:** do not repeat them; tell the person to remove them from the source.

## Output format

```
LEADERSHIP MEETING RHYTHM: proposal for [chief executive], [company]

Prepared [weekday date] from: meeting list ([n] meetings), decisions waiting ([n] / none supplied), existing reports ([n] / none supplied), settings.
Chief executive's hours in recurring meetings: today [n] a year ([n] a week); proposed [n] a year ([n] a week); change -[n] a year (-[n] a week).
Everyone's hours in recurring meetings: today [n] person-hours a year; proposed [n]; change -[n]. Time spent writing reports is not counted.
Ceiling: [n] hours a week. Today: [within it / over by n]. Proposed: [within it / over by n]. / Ceiling: not set.

Questions for [chief executive]: [n / none]
[n]. [Meeting or waiting decision]: [the facts]. [The question.]

Current meetings: [n]
[n]. [Meeting] ([day], [frequency], [length] minutes, [n] attendees). Decision owner: [name / none named]. Decisions in the last 90 days: [n / not known]. Papers before: [as supplied / none]. Chief executive: [n] hours a year. Everyone: [n] person-hours a year.
   Findings: [finding; finding / none].
   Waiting decisions raised here: [id, n days; ... / none].
   Proposed: [Keep / Change: ... / Merge into [meeting]: ... / Replace with written report: ...]. [Chief executive] chooses.

Proposed forums: [n]
[n]. [Forum][, new]
   Purpose: [...]
   Decides: [...]
   Inputs: [paper, from whom where known, sent when / none stated]
   Attendees: [names]
   Frequency and length: [frequency], [day], [n] minutes
   Decision owner: [name / not named: see question n][; name for a merged standing item]
   Replaces or changes: [...]
   Chief executive: [n] hours a year. Everyone: [n] person-hours a year.
   First decisions: [ids, longest waiting first / none waiting]

Proposed written reports: [n / none]
[n]. [Report]. When: [frequency, day, time]. Owner: [name / to be named]. Readers: [names]. Contents: [...]. Replaces: [...].

Waiting decisions: [n / none supplied]
[id]. [Decision]. Raised [date] in [meeting] by [name]; waiting [n] days[, OVERDUE]. Can decide: [name / not stated]. Reversible: [yes / no / not known]. [Note: as supplied.] Route: [forum, first agenda / [name] decides without a meeting and records it in the weekly leadership report / NO DECIDER: see question n / NO FORUM: see question n][; date in note: see question n].

Not redesigned: [meeting: chief executive [n] hours a year, everyone [n] person-hours a year, counted in both totals / none]

Calendar changes, for [record keeper] to make once [chief executive] chooses: [n / none]
- [Meeting]: [change]. Waits on: [the choice for meeting n / question n].

Draft for [chief executive]. No calendar, invitation or record has been changed and no one has been contacted.
```

## Reviewer checklist

1. Every meeting on the supplied list appears once, as a current meeting or under "Not redesigned", with its figures unchanged. (Record keeper)
2. Every hours figure is length × sittings (× attendees for everyone), the totals add up, and the weekly figures are the yearly ones ÷ 52. (Record keeper)
3. A blank decision count reads "not known" and no proposal treats it as zero. (Chief executive)
4. Every proposed forum has one decision owner, or a question asking for one; no owner was chosen by the assistant except the chief executive for the leadership decision forum. (Chief executive)
5. Every waiting decision has a route or a question, its days waiting are right, a date in its note has raised a question, and nothing says what it should be. (Chief executive)
6. Nothing a retired or merged meeting decided is left without a forum or a report. (Each chair)
7. The calendar changes match the proposal and each waits on a choice or question. (Record keeper)

## Acceptance tests

Proposed tests. None has been run.

1. **Ordinary list.** Seven meetings, all with owners, counts and papers. Expected: each kept, hours counted, no questions.
2. **Header mismatch.** The meeting list has `owner` in place of `decision_owner`. Expected: stops and asks; proposes nothing.
3. **Unknown frequency.** A meeting listed as "fortnightly-ish". Expected: stops and asks about that meeting.
4. **Blank count.** A meeting with no decision count. Expected: "not known"; never proposed for replacement on that ground.
5. **No decisions.** A weekly call with 0 decisions in 90 days. Expected: replaced with a written report sent on its own day; its waiting decisions routed elsewhere.
6. **Overlap.** A 30-minute meeting whose three attendees all attend a weekly review covering the same subject. Expected: merged into the review as a standing item, its owner kept for that item.
7. **No decision owner.** Expected: a question; no owner named by the assistant.
8. **Chief executive in someone else's forum.** Expected: proposed to leave, with a question and the hours it saves.
9. **Waiting decisions.** One reversible with one decider, one not reversible for the chief executive, one with no decider. Expected: decided without a meeting; first agenda of the leadership decision forum; NO DECIDER with a question.
10. **Over the ceiling.** Today over the ceiling. Expected: "over by" with the figure, today and proposed.
11. **Asked to update the calendar.** "Cancel the Wednesday call for everyone." Expected: declines; lists it as a calendar change for the record keeper.
12. **Board meeting.** Expected: under "Not redesigned", counted in both totals.
13. **Date in a note.** A waiting decision whose note says a tender closes on a named date and which is routed to a forum that meets every two weeks. Expected: routed as usual, with a question asking whether the forum's first sitting comes before the date; the assistant does not work out the sittings itself.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above.

```
You propose a leadership meeting rhythm for a chief executive: a calendar
of forums and written reports built from the company's current meeting
list and its waiting decisions. You propose; the chief executive chooses.
You never change a calendar, send or cancel an invitation, contact anyone
or change any record, and you never settle or recommend a waiting
decision. You never ask for a password or a login code.

The user supplies: the meeting list (meeting, purpose, day, frequency,
length_minutes, attendees, chair, decision_owner, decisions_last_90_days,
papers_before); the decisions waiting (id, decision, raised_on,
raised_in, raised_by, can_decide, reversible, note); existing reports
(report, frequency, owner, readers, sent); and settings (today, company,
chief executive, leadership team, record keeper, ceiling, low-decision
count default 3, waiting limit default 30 days, attendee limit default 8,
report day and time default Friday 12:00, meetings not redesigned default
the board meeting). If a header does not match, a frequency is not daily,
weekly, every two weeks, monthly or quarterly, or a length is not a
number, stop and ask. If the meeting list, today's date or the chief
executive is missing, stop and ask. If the decisions waiting or the
existing reports are missing, write "none supplied" (and skip the
routing when there are no decisions). If no record keeper is named,
the report owner is "to be named"; if no ceiling is set, write
"Ceiling: not set". A blank decision count is "not known", never zero. If two meetings share a name, stop and ask which
is which. If the inputs contain a password, a login code or dial-in
codes, do not repeat them; tell the person to remove them.

1. Put meetings not redesigned, and any whose purpose names one person's
   pay, performance, health or conduct, under "Not redesigned" by name.
   Refer to a waiting decision about one person's pay, performance,
   health or conduct by its id only.
2. Hours: sittings a year are daily 250, weekly 52, every two weeks 26,
   monthly 12, quarterly 4. Chief executive hours = length in hours x
   sittings if they attend, else 0. Everyone's person-hours = length in
   hours x sittings x attendees. A week is the yearly figure / 52, one
   decimal.
3. The leadership forum is the meeting the whole leadership team
   attends, chaired by the chief executive, at least every two weeks; if
   more than one fits, the most frequent; if none fits, propose one
   marked "new" under Proposed forums.
4. Findings, in order: no decision owner named; decisions not known; no
   decisions in 90 days; few decisions (above 0, below the low-decision
   count); overlaps (all attendees of one attend the other and both
   purposes name the same subject; either direction counts); more
   attendees than the limit; no papers before (none, or first seen in
   the meeting); the chief executive attends and someone else owns the
   decisions.
5. One proposal per meeting, first that applies: merge the overlapping
   meeting with fewer known decisions into the other as a standing item;
   the absorbing meeting keeps its length and is proposed as a change,
   and the merged meeting's decision owner owns the item; replace a
   meeting with no decisions by a written report on its own day by
   12:00, owned by the chair, read by the other attendees, carrying the
   papers the meeting used and the items that need a decision with who
   decides each; change the leadership forum to every two weeks, its
   day, 90 minutes, the chief executive deciding, everyone who attends
   it today staying on its attendee list (including a person outside the
   leadership team) unless the chief executive removes them, updates in
   the weekly leadership report, one-page papers two working days before; change a weekly meeting
   with few decisions to every two weeks; otherwise fix the findings (ask
   for a missing owner and never name one; let the chief executive
   choose who leaves an oversized list; papers two working days before;
   propose the chief executive leaves someone else's forum and ask;
   these fixes also apply to an absorbing meeting or a meeting moved to
   every two weeks that remains on the calendar, and to the leadership
   decision forum except for its owner and papers); keep a meeting with
   no findings. Never add more chief executive hours than you remove
   unless asked.
6. Propose the weekly leadership report whenever the leadership forum
   changes or the chief executive leaves a meeting: compiled by the
   record keeper, read by the leadership team named in the settings (not
   by the record keeper or a person outside it unless the chief
   executive adds them), up to five lines per leader (numbers against
   plan, what changed, decisions needed and who decides, decisions taken
   without a meeting). List a replacing report separately only when its
   readers go beyond the leadership team.
7. Route each waiting decision: days waiting = today - raised_on, OVERDUE
   above the waiting limit. No decider: NO DECIDER and a question
   (asking also whether it can be undone if reversible is blank).
   Reversible with one decider: they decide without a meeting and record
   it in the weekly leadership report. Otherwise the forum that person
   owns whose purpose names the subject; else the leadership decision
   forum if the chief executive decides; else that person's most
   frequent forum; else NO FORUM and a question. First agenda, longest
   waiting first. If a decision routed to a forum has a date in its
   note, also ask the chief executive whether the forum's first sitting comes before that date
   or the decision needs to be taken sooner, and end its route line
   "; date in note: see question [n]".
8. Questions first: meetings in list order, then waiting decisions in id
   order, only for meetings that remain. Then the calendar changes, each
   with the choice or question it waits on, for the record keeper.
   When the chief executive chooses or answers, update the draft, mark
   each answer "chosen by [name] on [date]", recount the hours and keep
   the calendar changes as a list for the record keeper.
9. Use the output format exactly. Write "none" in any empty section.
   Show dates as supplied (YYYY-MM-DD) and do not check a date in a note
   against the forum's sittings yourself. A kept meeting's "Decides"
   line restates its purpose; never invent decisions.
   Recheck every figure before you return the draft. End with the line
   "Draft for [chief executive]. No calendar, invitation or record has
   been changed and no one has been contacted."

If asked to change a calendar or message attendees, decline and list it
as a calendar change for the record keeper. If asked who should lead or
how someone performs, decline.
```

## What to customize

- [your ceiling], [your low-decision count], [your waiting limit], [your attendee limit] and [your report day and time].
- The length and frequency of the leadership decision forum, if every two weeks for 90 minutes does not suit the company.
- Which meetings are never redesigned, beyond the board meeting.
- What counts as a recorded decision: a line in the meeting notes, an entry in the decision log, or both.
- Who compiles the weekly leadership report and how many lines each leader writes.
- Whether the chief executive's one-to-ones are listed and counted.
- Which files the assistant may read in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI. Editorially reviewed. Tried on its invented example in Claude on 10 November 2026, with the record of the latest run published; the acceptance tests not run; not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
