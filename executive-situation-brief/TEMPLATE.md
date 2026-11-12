# Executive situation brief

Workflow template, version 0.1.0.

## Purpose

Prepare one brief for an executive before a conversation or decision that matters, such as a meeting with a key partner, a call with a major customer or a hard talk with a co-founder. The brief is built only from the records the executive has approved for it, and every line names the record it came from. It gives the short version in one sentence, how things got here, what has already been decided and promised, what each side has said in its own words, where the records disagree, the question to settle, the choices open, the dates that matter and the questions for the company's advisers. The executive chooses the position to take and any commitment to make. The assistant recommends nothing, profiles nobody, gives no legal or negotiating advice, and never sends, posts or changes anything.

## When to use it and when not to

Use it one to three working days before a conversation or decision where the other side's words and the company's earlier commitments matter: renewing or widening a partnership, a major customer's request for new terms (the brief is for the executive; an account manager's call plan for the same customer is the sales call preparation brief), a co-founder raising a change in roles (pay, equity and employment terms stay out), a supplier's request to change how the two companies work together. Run it again if a new record arrives before the day.

Do not use it for:

- preparing a sales or account meeting with a buyer, with a call plan. That is the sales call preparation brief;
- summarising what a set of reports, articles or studies found. That is the research summary brief;
- papers for a board meeting. That is the board meeting pack;
- deciding what position to take, what to offer or how to negotiate. The executive decides; the brief lays out the record;
- what an agreement means, whether a term can be enforced, or anything else that needs a lawyer. The brief lists those questions for the company's advisers and gives no view;
- anything about a person's employment, pay, performance or private life. Those stay with the people responsible for them;
- a person's personality, temperament or style. The brief records what people said and did, never what they are like.

## Roles

- **Runs it:** the executive, or someone preparing it for them, such as a chief of staff or an executive assistant.
- **Decides:** the executive. They approve which records are used, settle every point to check, choose the position and any commitment, and decide whether the brief is shared with anyone.
- **Settles figures and facts the records disagree on:** the person who owns that record, such as the finance lead or the sales director, as the executive directs.
- **Advisers:** the company's lawyer or accountant, for the questions the brief lists for them.
- **The AI assistant:** reads the approved records, prepares the brief and lists every gap. It contacts nobody and records nothing.

## Inputs

Everything is pasted or attached by a person. No mailbox, calendar, drive or customer system is connected, and the assistant never asks for a password, a login code or access to any system.

1. **The request:** today's date; who the brief is for; the subject; the other side (the organisation, or the person by role); whether it is a conversation (date, time, length, who attends from each side) or a decision (the date it is due); the question to settle, in the executive's words, if they have one; any choice the executive wants listed; and any setting that differs from the defaults. If the subject or the other side is missing, stop and ask. If there is no date, ask; until it is answered, write "date not given" and count no days.
2. **The approved records,** numbered R1, R2 and so on in the order supplied: emails, letters, meeting notes, a summary of the terms the two sides work under, a figures report, earlier briefs. Each needs a title, a date and who wrote it. A record marked draft, or one the person says is not approved, is not used; it is listed under "Not used". An undated record is used, marked "undated", and its date becomes a point to check. If no approved record is supplied, stop and ask; never write a brief from general knowledge or the internet.
3. **The decision log export,** if the company keeps one. Default column headers: `id`, `date_approved`, `topic`, `decision`, `approved_by`, `status`, `source`. Other columns are ignored, so the decisions export of the decision log workflow template works as it is. `status` is Active, Superseded or Withdrawn. If any of these seven headers is missing or named differently, stop, list the headers found and ask which column holds each. Never guess a mapping. If no log is supplied, write "No decision log supplied".
4. **Your settings:** [your staleness limit] (default: 90 days before the conversation or decision), [your history limit] (default: 8 entries), [your statement limit] (default: 4 statements for each side) and [your choice limit] (default: 5 choices, plus making no commitment).

## The procedure

1. **Check the inputs.** Confirm the subject, the other side and the date. Number the records and list each one's title, date and author. Read the log's headers against the defaults; on any mismatch, stop and ask. Set aside drafts and unapproved records under "Not used", with the reason.
2. **Cite everything.** Every statement in the brief ends with the record it came from, as [R3] or [Log D-036]. A statement that no record supports is not written. A figure the assistant works out, such as a total, shows its working.
3. **Leave out what is personal.** Anything in the records about a person's health, family, private life, pay or performance is left out of every section. Count such items under "Left out", by kind only, never repeating them. Bank details, passwords and login codes are left out too, and the person is told to remove them from the source.
4. **The short version.** One sentence of at most 35 words, giving where things stand on the subject, built from facts in the records and cited. It names no motive and recommends nothing, and draws no conclusion that no record states: where a comparison matters, give the two figures as the records give them ("480 units against 600 planned"), not "behind target". If a fact in it, or a total or comparison built on a figure, is one the records disagree on, use a wording both records support or leave it out; the same figure may still appear in the later sections as what a named record shows.
5. **How we got here.** Dated entries, oldest first, each one event from the records: what happened, who did it, and the record. Keep at most [your history limit] entries; if there are more, keep the ones that bear on the question to settle and say how many were left out.
6. **Already decided and already promised.**
   - Decisions: each decision on the subject from the log or the records, with its date, who approved it as recorded, and its status: In force, Replaced (by what and when), Withdrawn, or "Discussed, not decided" where a record shows it was talked about and nothing was agreed. Talked about is not decided.
   - Commitments: each promise either side made, as "[who] to [what] by [date]", with its status from the records only: Kept (with the date, and "after the date" if it was late); Outstanding (an exact date still ahead and no record says it is done); Overdue (a record says it is not done and its date has passed); or Not known (no record says). A promise with no date, or only a loose one ("second half of 2026"), is Not known unless a record says it is done; show the record's own words for the date. Add "date passed" to Not known where it applies. Not known becomes a point to check. A target, a plan figure or a forecast is not a commitment. A conditional offer ("we can commit to X if you give us Y") is a position, shown in step 7 and, if it is a choice, in step 10; it is a commitment only once a record shows it was agreed or promised without the condition.
7. **What each side has said.** For each party, the other side first, then the company (what the company has said to the other side): up to [your statement limit] statements, latest first (on the same date, in the order of the records), each in the party's own words where a record quotes them and marked as a note where a record summarises them, with the date and the record. One statement is one position the party took on one point in one record; split a record that takes several positions, and do not repeat a promise already listed under Commitments. A sentence that only reads what the terms mean goes to step 12 and is not repeated here. What the company wrote itself to the other side is quoted; what notes say it said is a note, even where the notes put its words in quotation marks. If more statements exist than the limit, keep the latest and end the party's list with "[n] further statements left out." Mark any statement dated more than [your staleness limit] before the conversation or decision OLDER THAN [n] DAYS. Where a party's later statement contradicts an earlier one on the same point, put the earlier one beneath it as "Earlier on the same point". A party with no statement in the records reads "No stated position in the records supplied." Never say what a party "really" wants, how they are likely to react, or what they are like. End the section with the line "Your position for this conversation: for you to decide."
8. **Where the records disagree.** Any fact, figure or date that two records give differently: each version with its record. Never choose between them, average them or explain the difference. Each becomes a point to check, addressed to the owner of the record where the records show one. Two readings of what the terms between the sides mean are not listed here; they go to step 12.
9. **The question to settle.** The executive's question, in their words. If they gave none, propose one question from the records, marked "PROPOSED: confirm", and make it a point to check. One question only.
10. **The choices open.** Each choice that the other side proposed in the records, that the company's own people proposed or discussed in the records (a leadership meeting counts), or that the executive listed in the request, up to [your choice limit], in that order: the other side's, then the company's own, then the executive's, each group in date order. If there are more, keep the ones that answer the question to settle and say how many were left out. One proposal is one choice: where a party's later record repeats or widens its earlier request, list the later one only and cite the earlier record under "In the records". For each: who raised it and where; what the records say it would involve (amounts, volumes, dates, conditions), or "nothing further in the records"; and, if agreeing to it on the day would go against a decision in force, which decision. Always add, last, "Make no commitment in this conversation", with any date in the records it runs into. Do not rank the choices, do not recommend one, and do not add a choice nobody raised.
11. **The dates that matter.** Every date in the records that falls on or after today and bears on the subject, in date order, with what falls due, the record, and the number of calendar days after (or before) the conversation or decision. A date the records give only loosely ("from April", "the second half") keeps the record's words, gets no count and goes after the exact dates, in the order it falls.
12. **For your advisers.** Any question in the records about what an agreement or the terms mean, whether something is permitted, tax, or a dispute: the question by kind, the records that raise it, and "No view is given here." If none: "None raised."
13. **Count the points to check** and list them first, one question each, with the section it affects and who can answer it. A gap is counted once even if it shows in several sections.
14. **Declined requests.** The executive's own question to settle is not a declined request: it stays in section 6, and the brief gives no recommended answer to it. Anything else the request asked for that this workflow template does not do (a view of a person's style, a recommended position, tactics, a legal view, sending something) is listed under "Asked for and not covered", with the reason in a few words. A declined request about a person is described without repeating any description of that person, and without naming the person unless the request does; if the request does not say which person, say "one of the attendees".
15. **Return the draft** to the person who ran it, for the executive. When someone answers a point to check, update the brief, mark the answer "settled by [name]" and recount. Nothing follows the closing line; anything the person needs to know, such as a date that looks wrong, goes under "To check first".

## Exceptions and stop conditions

- **No subject, no other side, or no approved record:** stop and ask.
- **A decision log header does not match the defaults:** stop, list the headers found and ask which column holds each.
- **Two records disagree:** show both with their records and ask; never choose.
- **A record is marked draft or not approved:** do not use it; list it under "Not used".
- **Asked how to handle a person, what they are like, or how they will react:** decline. The brief records what people said and did, never their personality or style.
- **Asked what position to take, what to offer, what to concede or how to negotiate:** decline. List the choices open, unranked; the executive decides.
- **Asked what the terms mean or whether something can be enforced:** decline, list it under "For your advisers" and give no view.
- **Asked to add facts from the internet, from memory or about the other side's business beyond the records:** decline and ask for an approved record that holds them.
- **Asked to send the brief, email the other side, book the meeting or log a decision:** decline. Return the text for a person to use.
- **The records raise a person's employment, pay, performance, health or private life:** leave it out and count it under "Left out" by kind only.
- **The records contain bank details, a password or a login code:** leave them out and tell the person to remove them from the source.

## Output format

```
EXECUTIVE SITUATION BRIEF: [subject]
DRAFT for [executive]. [n points to check before the conversation. / Nothing to check.]
For: [conversation with (other side, roles) on (weekday date), (time), (n) minutes, (place
or link) / decision due (weekday date) / date not given]. From us: [names and roles].
Prepared [today's date] by [who ran it], from [n] records (R1 to R[n], listed at the end)
[and the decision log export ([n] rows) / No decision log supplied].

To check first: [n, or None]
[n]. [Section]: [question]. Who can answer: [role].

1. THE SHORT VERSION
[One sentence, at most 35 words.] [R..]

2. HOW WE GOT HERE
- [date]: [what happened, who did it]. [R..]
[n earlier entries left out.] [Or "No history in the records supplied."]

3. ALREADY DECIDED AND ALREADY PROMISED
Decisions:
- [date] ([log id]): [decision]. Approved by: [as recorded]. [In force / Replaced by (what)
  on (date) / Withdrawn / Discussed, not decided]. [R.. / Log ..]
[Or "No decisions on this subject in the records supplied."]
Commitments:
- [Who] to [what] by [date, or the record's words]. [Kept (date[, after the date]) / Outstanding / Overdue / Not
  known[, date passed]]. [R..]
[Or "No commitments in the records supplied."]

4. WHAT EACH SIDE HAS SAID
[Other side (roles)]:
- [date]: "[their words]" / Note: [as the record summarises it]. [R..] [OLDER THAN n DAYS]
  [Earlier on the same point: (date) "(words)" (R..).]
[A party with nothing on record: "No stated position in the records supplied."]
[n further statements left out.]
[Our company]:
- [date]: "[words]" / Note: [...]. [R..] [OLDER THAN n DAYS]
[n further statements left out.]
Your position for this conversation: for you to decide.

5. WHERE THE RECORDS DISAGREE
- [Point]: [R..] says [..]; [R..] says [..]. To check ([n]).
[Or "None found."]

6. THE QUESTION TO SETTLE
[The question.] [(Your words.) / PROPOSED from (R..): confirm.]

7. THE CHOICES OPEN
[A]. [Choice]. Raised by: [party, (R..) / you, in your request].
     In the records: [amounts, volumes, dates, conditions, (R..) / nothing further in the
     records]. [Agreeing to it on the day would go against (decision, log id), in force.]
[Last]. Make no commitment in this conversation. Always open.
     Runs into: [dates in the records (R..) / no date in the records].
[n further choices left out.] Not ranked. No recommendation.

8. THE DATES THAT MATTER
- [Weekday date]: [what falls due]. [R..] [n] days [after / before] the conversation.
- [Loose date, in the record's words]: [what]. [R..] No exact date in the record.
[Or "No dates in the records supplied."]

9. FOR YOUR ADVISERS
- [Question, by kind] ([R..]). No view is given here.
[Or "None raised."]

RECORDS USED
R[n]. [Title], [kind], [date / undated], by [author].
[Decision log export, rows [ids].]
Not used: [record, reason], or "none".
Left out: [n items, by kind], or "nothing".
Asked for and not covered: [request, reason], or "nothing".

Draft for [executive]. Nothing has been sent, posted or changed.
```

## Reviewer checklist

1. Every statement names a record, and each one matches the record it names. (Whoever ran it)
2. No record marked draft or not approved has been used. (Executive)
3. Every quotation is in the party's own words, and every summary is marked as a note. (Whoever ran it)
4. Nothing describes a person's personality, style, motive or likely reaction. (Executive)
5. Nothing personal about anyone appears; "Left out" gives kinds only. (Executive)
6. Every disagreement between records shows both versions, and none has been settled by the assistant. (The owner of the record)
7. The choices are only those a party raised or the executive listed, unranked, with no recommendation, and making no commitment is among them. (Executive)
8. Every day count is right from the conversation date. (Whoever ran it)
9. Questions about what the terms mean sit under "For your advisers" with no view given. (Executive)

## Acceptance tests

Proposed tests. None has been run as a test. The template has been tried once on its invented example; see the version notes.

1. **Ordinary brief.** Five dated, approved records, a decision log with matching headers and a question in the executive's words. Expected: every section filled, every statement cited, the question kept as worded.
2. **Header mismatch.** The log uses `Owner` in place of `approved_by`. Expected: stops, lists the headers found and asks which column holds the approver; writes nothing else.
3. **No records.** The request names a subject and a partner but attaches nothing. Expected: stops and asks for approved records; adds nothing from general knowledge.
4. **Draft record.** One attachment is marked DRAFT. Expected: not used anywhere; listed under "Not used" with the reason.
5. **Records disagree.** The partner's email and the company's sales report give different figures for the same quarter. Expected: both shown with their records, one point to check, neither figure, and no total built on either, used in the short version.
6. **Profiling request.** "Tell me how to handle her; she's tough." Expected: declined and listed under "Asked for and not covered"; no description of the person anywhere.
7. **Personal matter.** Meeting notes mention a family matter of the other side's managing director. Expected: left out; "Left out: 1 item about a person's private life".
8. **Asked for a recommendation.** "Which option should I go with?" Expected: declined; the choices stay unranked.
9. **A reading of the terms.** The partner's email says exclusivity rolls over automatically. Expected: listed under "For your advisers" with no view.
10. **Choice against a decision in force.** The partner asks for something the leadership team has ruled out until a later date. Expected: the choice is listed with the decision it would go against; no advice on what to do.
11. **Old position.** The company's last word to the partner is 120 days old. Expected: marked OLDER THAN 90 DAYS.
12. **Unknown commitment.** The partner promised a forecast by a date now passed and no record shows it arrived. Expected: "Not known, date passed" and a point to check.
13. **Asked to send.** "Email this to Ana and the partner." Expected: declines and returns the text for a person to send.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above. The block tells the assistant to use that format and does not repeat it.

```
You prepare a situation brief for an executive before a conversation or
decision that matters. You prepare; the executive decides. You never
recommend a position, an offer or a choice, never describe what a person
is like or how they will react, and never give a legal or negotiating
view. You never send, post or email anything, book anything or change a
record. Work only from the records the person pastes or attaches and has
approved. Never ask for a password, a login code or access to any system.

Use the output format exactly, every section in order, with the wording
it gives for an empty section. Put "To check first" at the top, one
question per gap, counted once even if the gap shows in several sections.
Write a "left out" line ("[n] earlier entries left out", "[n] further
statements left out", "[n] further choices left out") only when the number
is more than none. Nothing follows the closing line; anything the person
needs to know, such as a date that looks wrong, goes under "To check
first".

1. If the subject, the other side or any approved record is missing, stop
   and ask. If the date is missing, ask; until answered, write "date not
   given" and count no days. Never fill a gap from general knowledge or
   the internet.
2. Number the records R1, R2 ... in the order supplied, with title, date
   and author. A record marked draft or not approved is not used; list it
   under "Not used" with the reason. An undated record is used, marked
   "undated", and its date is a point to check.
3. Decision log export, if supplied. Required headers: id, date_approved,
   topic, decision, approved_by, status, source. Ignore other columns. If
   any required header is missing or named differently, stop, list the
   headers found and ask which column holds each. Never guess.
4. Every statement ends with its record, as [R3] or [Log D-036]. Write
   nothing no record supports. Show the working for any figure you work
   out, such as a total.
5. Leave out anything about a person's health, family, private life, pay
   or performance, and any bank details, passwords or login codes. Count
   them under "Left out" by kind only, and tell the person to remove any
   bank details, passwords or login codes from the source.
6. The short version: one sentence, at most 35 words, facts only, cited.
   If the records disagree on a fact, or a total or comparison is built
   on a figure they disagree on, use a wording both support or leave it
   out. Draw no conclusion no record states: give the two figures
   ("480 units against 600 planned"), not "behind target".
7. How we got here: dated events, oldest first, at most [your history
   limit] (default 8); if there are more, keep the ones that bear on the
   question to settle and say how many were left out.
8. Decisions: date, log id, who approved, and In force, Replaced,
   Withdrawn, or Discussed, not decided. Talked about is not decided.
   Commitments: "[who] to [what] by [date]", Kept (with date, and "after
   the date" if late), Outstanding (exact date ahead, no record says
   done), Overdue (a record says not done, date passed), or Not known
   (no record says, or the date is missing or loose such as "second half
   of 2026"; add "date passed" where it applies; Not known is a point to
   check). A target, plan figure or forecast is not a commitment. A
   conditional offer is a position, not a commitment.
9. What each side has said: the other side first, then the company. Up to
   [your statement limit] (default 4) statements each, latest first, in
   their own words when quoted, or marked "Note:" when summarised, with
   date and record. One statement is one position on one point in one
   record; split a record that takes several, and do not repeat a promise
   already listed as a commitment. A sentence that only reads what the
   terms mean goes to "For your advisers", not here. If more exist than
   the limit, keep the latest and end the list "[n] further statements
   left out." Mark any statement older than [your staleness limit]
   (default 90 days) before the conversation OLDER THAN [n] DAYS. Where a
   later statement contradicts an earlier one on the same point, show the
   earlier one beneath it as "Earlier on the same point". For the
   company, use only what it has said to the other side: quote what it
   wrote itself to the other side; what notes say it said is a note, even
   where the notes put its words in quotation marks. Nothing on record:
   "No stated position in the records supplied." Never say what a party
   really wants or what they are like. End: "Your position for this
   conversation: for you to decide."
10. Where the records disagree: both versions with their records; never
    choose, average or explain. Each is a point to check for the record's
    owner. Readings of the terms go to "For your advisers" instead.
11. The question to settle: the executive's words, or one question you
    propose from the records, marked "PROPOSED: confirm" and listed as a
    point to check.
12. The choices open: only those the other side raised in the records, the
    company's own people raised or discussed in them (a leadership
    meeting counts) or the executive listed, at most [your choice limit]
    (default 5), in that order: the other side's, the company's own, the
    executive's, each in date order. If there are more, keep the ones
    that answer the question to settle and say how many were left out.
    One proposal is one choice: where a party's later record repeats or
    widens its earlier request, list the later one only and cite the
    earlier record under "what the records say". For each:
    who raised it and where, what the records say it involves or "nothing
    further in the records", and any decision in force that agreeing on
    the day would go against. Always add, last, "Make no commitment in
    this conversation" with the dates it runs into. Do not rank, do not
    recommend, do not add a choice nobody raised.
13. The dates that matter: dates on or after today from the records, in
    order, each with calendar days after (or before) the conversation.
    Loose dates keep the record's words, get no count and go last.
14. For your advisers: only questions the records themselves raise about
    what terms mean, permission, tax or a dispute, by kind, with records,
    and "No view is given here."
15. List under "Asked for and not covered" anything requested that you do
    not do, with the reason: a view of a person, a recommended position,
    tactics, a legal view, sending or booking anything. The executive's
    own question to settle is not listed here. For a request
    about a person, repeat no description of them and do not name them
    unless the request does; if it does not say which person, write "one
    of the attendees".

When someone answers a point to check, update the brief, mark it
"settled by [name]" and recount. If asked to send, email, book or log
anything, decline and return the text for a person to use. Every brief
ends: "Draft for [executive]. Nothing has been sent, posted or changed."
```

## What to customize

- Who runs it for the executive, and who owns each kind of record (figures, meeting notes, the terms the two sides work under).
- Which records may be given to the assistant, and in which AI product: ChatGPT, Claude, Copilot or Gemini. Agree who must approve a record before it is given to the assistant.
- [your staleness limit], [your history limit], [your statement limit] and [your choice limit].
- Your decision log's column headers, if they differ from the defaults. If your log comes from the decision log workflow template, its decisions export works as it is.
- Who the company's advisers are, so the questions listed for them reach the right person.
- Whether the brief is ever shared beyond the executive. By default it is for the executive only.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI. Editorially reviewed. The instructions were revised after review (what counts as a statement, how loose-dated promises and conditional offers are treated, the order of the choices, the short version, how a declined request about a person is worded), the example was brought into line, and the template was then tried once on its invented example on 10 November 2026 in Claude; the record is published with it. Edits were made to the instructions after that run and have not been run again: the advisers line takes only questions the records raise; a "left out" line is written only when something was left out, for entries, statements and choices alike; the pasted block now carries the quote-or-note rule for the company, the rule for keeping the entries and choices that bear on the question, and the "Earlier on the same point" label; a total built on a disputed figure is kept out of the short version; a later request that repeats an earlier one is one choice; the executive's own question is not a declined request; and nothing follows the closing line. Not yet tested in a client environment.
