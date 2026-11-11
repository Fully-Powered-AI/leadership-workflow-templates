# Executive situation brief: tried once on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-10
- **Template version:** 0.1.0

This is a record of one run of the capability template on its own invented example. The company, the people, the records and the figures are invented, and no client data was used. It shows what the template produced once, on one set of inputs. It is not a test in any company's environment.

This is the second run on the same example. A first run earlier the same day showed where the instructions left room to guess; the instructions, the output format and the example were revised, and the run recorded here was made on the revised instructions. What the first run found, and what was changed, is at the end.

## The inputs used

The inputs are exactly those in [the worked example](example.md), under "The inputs": the request, six records (R1 to R6), the decision log export and the note that the East price sheet v2 was marked DRAFT. The pasted instructions and the output format, as they stood in the template after the revision, were given as the session's instructions, and the inputs were sent as one message. The run was a fresh session started from Claude Code with no tools, no access to any file and no memory of the first run. The assistant that revised the template did not do the run; it did not see the example's own brief. It sent nothing.

## What came out

The complete output, as returned, including the note it added after the draft:

```
EXECUTIVE SITUATION BRIEF: Partner D, North renewal and the East region
DRAFT for Noor (CEO). 3 points to check before the conversation.
For: conversation with Partner D (managing director, sales director) on Thursday 5 November 2026, 10:00, 60 minutes, video call. From us: Noor (CEO), Ana (sales director).
Prepared Tuesday 3 November 2026 by Tomas (chief of staff), from 6 records (R1 to R6, listed at the end) and the decision log export (3 rows).

To check first: 3
1. Already decided and already promised: Has the company matched Partner D's North campaign spend (up to $8,000) yet, and by what date does the "second half" match end? Who can answer: Ana (sales director) or Priya (finance lead).
2. Already decided and already promised: Did Partner D send its 2027 North forecast? It was due by the end of October. Who can answer: Ana (sales director) or Noor (CEO), who received the 2 October email.
3. Where the records disagree: Were Partner D's Q3 2026 units 310 or 270? Who can answer: Priya (finance lead), who owns R4.

1. THE SHORT VERSION
Partner D, sole North distributor to 31 March 2027, shipped 750 units against 900 planned to 30 September and asked for East, where D-036 allows no new partner arrangements before 1 December. [R1] [R4] [R2] [R3] [Log D-036]

2. HOW WE GOT HERE
- 15 December 2025: Noor approved renewing Partner D as sole North distributor from 1 January 2026 to 31 March 2027, with a 2026 target of 1,200 units. [Log D-014]
- 12 January 2026: Priya (finance lead) summarised the terms: North region, 18% off list on all orders, renewal by agreement of both sides, and either side may give notice of non-renewal by 31 December 2026. [R1]
- 14 July 2026: At the quarterly review, first-half units were 480 against 600 planned. Partner D asked to be the East distributor as well. Ana was to send a co-marketing proposal by 31 July. [R2]
- 21 July 2026: Noor approved matching Partner D's North campaign spend up to $8,000 in H2 2026. [Log D-029]
- 6 August 2026: Ana emailed Partner D's sales director the co-marketing proposal. [R6]
- 1 October 2026: Priya's sales report showed 750 units shipped against 900 planned to 30 September. Working: 230 + 250 + 270 = 750 shipped; 300 + 300 + 300 = 900 planned. [R4]
- 2 October 2026: Partner D's managing director emailed Noor about 2027. The email covered 1,500 units a year across North and East if Partner D has both regions exclusively, about 1,000 units in North without East, and a further 4% discount on East orders. [R3]
- 20 October 2026: The leadership team decided on no new East partner arrangements before the 2027 plan is approved on 1 December. They discussed a non-exclusive East trial for Partner D but did not decide it. [R5] [Log D-036]
0 earlier entries left out.

3. ALREADY DECIDED AND ALREADY PROMISED
Decisions:
- 15 December 2025 (D-014): Renew Partner D as sole North distributor, 1 January 2026 to 31 March 2027, 2026 target 1,200 units. Approved by: Noor. In force. [Log D-014] [R1]
- 21 July 2026 (D-029): Match Partner D's North campaign spend up to $8,000 in H2 2026. Approved by: Noor. In force. [Log D-029]
- 20 October 2026 (D-036): No new partner arrangements in the East region before the 2027 plan is approved on 1 December. Approved by: Leadership team. In force. [Log D-036] [R5]
- 20 October 2026 (no log id): Offer Partner D a non-exclusive East trial. Discussed, not decided. It comes back with the 2027 plan. [R5]
Commitments:
- Ana to send Partner D a co-marketing proposal by 31 July 2026. Kept (6 August 2026, after the date). [R2] [R6]
- The company to match Partner D's spend on North campaigns up to $8,000, by "the second half" (H2 2026). Not known. [R6] [Log D-029]
- Partner D to send its 2027 North forecast by the end of October 2026. Not known, date passed. [R3]

4. WHAT EACH SIDE HAS SAID
Partner D (managing director, sales director):
- 2 October 2026: "For 2027 we can commit to 1,500 units a year across North and East if we have both regions exclusively from April 2027." [R3]
- 2 October 2026: "Without East, we will plan for about 1,000 units in North next year." [R3]
- 2 October 2026: "We would need a further 4% discount on East orders to cover the cost of opening there." [R3]
- 14 July 2026: Note: Partner D asked to be the company's distributor in the East region as well, "so the numbers work for us". [R2] OLDER THAN 90 DAYS
Our company:
- 6 August 2026: "On East, as Noor said in July, we'll come back to it once North is back on target." (Ana to Partner D's sales director) [R6] OLDER THAN 90 DAYS
- 14 July 2026: "We'll look at East once North is back on target." (Noor, with Partner D present) [R2] OLDER THAN 90 DAYS
Your position for this conversation: for you to decide.

5. WHERE THE RECORDS DISAGREE
- Q3 2026 units: R3 says Partner D's "Q3 orders with you were 310 units"; R4 says 270 units were shipped in Q3. To check (3).

6. THE QUESTION TO SETTLE
"Do we offer Partner D anything on East before the 2027 plan is approved on 1 December, and if so, what do we ask in return?" (Your words.)

7. THE CHOICES OPEN
A. Make Partner D the distributor in the East region as well. Raised by: Partner D, at the quarterly review on 14 July 2026 (R2).
     In the records: Partner D said "so the numbers work for us" (R2). Nothing further in R2. Agreeing to it on the day would go against D-036 (no new partner arrangements in the East region before 1 December), in force.
B. Give Partner D both North and East exclusively from April 2027. Raised by: Partner D, email of 2 October 2026 (R3).
     In the records: Partner D would commit to 1,500 units a year across North and East. Partner D would need a further 4% discount on East orders. Without East, Partner D would plan for about 1,000 units in North next year (R3). Agreeing to it on the day would go against D-036, in force.
C. Offer Partner D a non-exclusive East trial. Raised by: the company's leadership meeting, 20 October 2026 (R5).
     In the records: discussed, not decided; it comes back with the 2027 plan (R5). Nothing further in the records. Agreeing to it on the day would go against D-036, in force.
D. Renew North only, on the current terms. Raised by: you, in your request.
     In the records, the current terms are: North region, Partner D as the only distributor, 18% off list on all orders, term 1 January 2026 to 31 March 2027, renewal by agreement of both sides (R1). The 2026 target is 1,200 units (R1, Log D-014). Without East, Partner D would plan for about 1,000 units in North next year (R3).
E. Make no commitment in this conversation. Always open.
     Runs into: 1 December 2026, 2027 plan approval (R5, Log D-036); 31 December 2026, deadline for non-renewal notice (R1); 31 March 2027, end of the current term (R1, Log D-014); April 2027, Partner D's requested start for both regions (R3).
0 further choices left out. Not ranked. No recommendation.

8. THE DATES THAT MATTER
- Tuesday 1 December 2026: The 2027 plan is due for approval. D-036 applies until then, and the non-exclusive East trial comes back with the plan. [R5] [Log D-036] 26 days after the conversation.
- Thursday 31 December 2026: Last date for either side to give notice that it will not renew. [R1] 56 days after the conversation.
- Wednesday 31 March 2027: The current term ends. [R1] [Log D-014] 146 days after the conversation.
- "H2 2026" / "the second half": the period for the company's North campaign spend match up to $8,000. [Log D-029] [R6] No exact date in the record.
- "from April 2027": the start Partner D asked for to have North and East exclusively. [R3] No exact date in the record.

9. FOR YOUR ADVISERS
- What the terms mean: Partner D's email says, "As we read the current terms, if we reach 1,000 units this year the North exclusivity rolls over anyway." R1 states renewal is "by agreement of both sides", with notice of non-renewal possible by 31 December 2026. R1 is a summary prepared by finance; the full agreement is not among the records supplied. (R1, R3) No view is given here.
- What the terms mean: how notice of non-renewal is given, and what applies if neither side gives notice by 31 December 2026. (R1) No view is given here.

RECORDS USED
R1. Partner D: partnership terms summary, terms summary, Monday 12 January 2026, by Priya (finance lead). Marked APPROVED.
R2. Quarterly review with Partner D: notes, meeting notes, Tuesday 14 July 2026, by Ana (sales director).
R3. Email from Partner D's managing director to Noor, subject "2027", email, Friday 2 October 2026, by Partner D's managing director.
R4. Partner D units by quarter, 2026: sales report, report, Thursday 1 October 2026, by Priya (finance lead).
R5. Leadership meeting: notes, meeting notes, Tuesday 20 October 2026, by Tomas (chief of staff).
R6. Email from Ana to Partner D's sales director, email, Thursday 6 August 2026, by Ana (sales director).
Decision log export, rows D-014, D-029, D-036. All required headers present.
Not used: East price sheet v2. It is marked DRAFT across the top and is not one of the approved records.
Left out: 1 item, a private family matter (R2). No bank details, passwords or login codes found.
Asked for and not covered: "how to handle" one of the attendees. This asks for a view of a person and for tactics, which this brief does not give. A recommended answer to the question to settle (whether to offer anything on East, and what to ask in return) is also not covered, because the brief does not recommend positions.

Draft for Noor (CEO). Nothing has been sent, posted or changed.
```

The note after the draft, also as returned:

> I used Tuesday 3 November 2026 as today, as your request says, but my system clock says 10 November 2026. If the clock is right, the 5 November call has already happened, so please confirm the date before relying on the day counts.

## What was observed

Every section of the output format was produced, in order. Nothing made the assistant stop: the decision log's seven headers matched, and the subject, the other side and approved records were all present. The draft price sheet was set aside under "Not used", the family matter in the July notes was left out and counted by kind, the request for advice on handling a person was declined and listed without repeating any description of the person, and neither Q3 figure was chosen. The statements for each side stayed within the limit of four, and the sentence in the partner's email that reads the terms appears only under "For your advisers". The $8,000 match is Not known, with the record's words "the second half" and a point to check. The choices are in the order the revised instructions give: the other side's, the company's own, the executive's, then making no commitment. The short version gives the two figures (750 against 900) and draws no conclusion from them. Day counts (26, 56 and 146 days), the OLDER THAN 90 DAYS marks and the Q3 disagreement are the same as in the published example.

### Differences from the published example

The published example was corrected by hand to follow the revised rules; it is not this run's output. It was changed again after this record was written, so the differences below are against the example as it was when the run was made, and the example now differs further (see the last three bullets of this list).

- **Points to check:** the same three, in a different order (this run puts the $8,000 match first).
- **Choices:** five here. This run lists Partner D's request of 14 July to be the East distributor (R2) as a choice of its own, ahead of the 2 October offer; the example lists four.
- **How we got here:** this run has the 12 January terms summary as an entry; the example does not.
- **Left out:** this run names "a private family matter (R2)" and says no bank details, passwords or login codes were found; the example says "1 item about a person's private life".
- **Asked for and not covered:** this run also lists a recommended answer to the question to settle, which the executive's own question asks for ("what do we ask in return?"). The example lists only the request about a person.
- **Records used:** this run writes the kind of record twice in some lines ("terms summary, terms summary", "email, Friday ...") and adds "Marked APPROVED".
- **The short version:** the content differs. This run's sentence gives Partner D as sole North distributor to 31 March 2027, 750 units shipped against 900 planned, and the East request against D-036; the example's sentence differs in what it covers and in its citations, which the example gives as one bracket and this run gives as separate [R1] [R4] [R2] [R3] [Log D-036]. The example's sentence was later changed so that it leaves out the 750 total, which rests on the Q3 figure the brief lists as disputed; this run's sentence still contains it.
- **Small format differences:** this run heads the executive as "Noor (CEO)", labels the company's statements "Our company:" where the example writes "Company K, to Partner D:", cites records separately where the example groups them, and adds a sentence to the advisers bullet that the full agreement is not among the records supplied. None introduces a fact from outside the inputs.
- **The hand-written example** also quotes Noor's 14 July statement as a quotation, and now marks it as a note, while this run quoted it; see the loose points below.

### Facts not in the inputs

None found that came from outside the records. One item went beyond them: the second bullet under "For your advisers" (how notice of non-renewal is given, and what applies if neither side gives notice) is a question no record raises. It is a question about what the terms say, not a fact, but the instructions allowed it; they were changed afterward (see below).

### Where the instructions were still loose

- **"[n] left out" lines.** The run wrote "0 earlier entries left out." and "0 further choices left out." where the format shows these lines only for when something was left out.
- **Text after the draft.** The run added a note below the closing line, asking the executive to confirm the date because its own clock read 10 November 2026. The template does not say whether anything may follow the closing line.
- **A request that is also the question.** The run listed "what do we ask in return" under "Asked for and not covered" as well as keeping it as the question to settle.
- **A choice from a July request.** The run turned a request made at the July review into a choice. The instructions allowed this (the other side raised it), but the 2 October offer already covers East. The run therefore gave five choices where the hand-written example gives four.
- **A total built on a disputed figure.** The run's short version leads with 750 units against 900 planned. That total includes the Q3 figure of 270, which the same brief lists as disputed (310 in R3, 270 in R4). The instructions at the time said only to leave out or reword "a fact" the records disagree on.
- **Quote or note for the company.** The run quoted Noor's 14 July statement, which comes from meeting notes (R2), without marking it as a note. The procedure said what notes say the company said is a note; the pasted instructions then did not carry that rule.

## Edits made after this run, not run again

- The pasted instruction on "For your advisers" now takes only questions the records themselves raise.
- The general paragraph of the pasted instructions now says to write a "left out" line only when something was left out, for entries, statements and choices alike. (This was first an instruction under how we got here only.)
- The pasted instructions now carry the rule that what the company wrote itself is quoted and what notes say it said is a note, even where the notes put its words in quotation marks; the rule for keeping the entries and choices that bear on the question to settle; and the "Earlier on the same point" label.
- A total or comparison built on a figure the records disagree on is now kept out of the short version, and the illustration uses the undisputed first-half figures (480 against 600).
- Where a party's later record repeats or widens its earlier request, the brief lists one choice, the later one, and cites the earlier record.
- The executive's own question to settle is no longer listed under "Asked for and not covered".
- Nothing follows the closing line; anything the person needs to know, such as a date that looks wrong, goes under "To check first".

None of these edits was run. The example's brief was edited by hand to match the revised rules and was not regenerated; a fresh run on the revised instructions may differ from both this record and the example.

## What the first run found, and what was changed

The first run, also on 10 November 2026 and by an assistant that had not written the template, produced a similar brief on the earlier instructions and an independent reviewer then read it against the template. It found, and the revision changed:

- **What counts as a statement.** The instructions now define one statement as one position on one point in one record, send a reading of the terms to "For your advisers" only, say that a promise already listed as a commitment is not repeated, and add a "[n] further statements left out" line.
- **Commitments with a loose or missing date.** They are now Not known unless a record says they are done, with the record's own words for the date. A target, plan figure or forecast is not a commitment, and a conditional offer is a position.
- **The short version.** It may not draw a conclusion no record states ("behind target"); it gives the two figures instead.
- **Choices raised inside the company.** A leadership meeting's proposal counts, and the choices now have an order.
- **Quote or note.** What the company wrote itself to the other side is quoted; what notes say it said is a note.
- **Bank details, passwords and login codes.** The pasted instructions now tell the person to remove them from the source.
- **A declined request about a person.** It is worded without repeating any description of the person, and without naming them unless the request does; when the request does not say who, "one of the attendees".
- **The example** said the declined request was about Partner D's managing director, which the request did not say. It now says "one of the attendees".
