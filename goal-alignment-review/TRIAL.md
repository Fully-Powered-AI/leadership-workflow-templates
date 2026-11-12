# Goal alignment review: tried once on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (claude-sonnet-5-5)
- **Date:** 2026-11-10

The inputs are the invented example for this workflow template (Company K, first quarter of 2027). No client data was used. The assistant read the template's instruction block and output format, then the inputs only (settings, priorities, goals, tensions already raised and the not-doing list, all in `public/example.md`). It had not seen the published example's output when it produced the review below; the comparison came afterwards. The assistant did not write the template.

## What came out

GOAL ALIGNMENT REVIEW: Company K, first quarter of 2027

For: the chief executive. Prepared Monday 14 December 2026 by the chief of staff.
Read from: 4 company priorities; 12 team goals from 7 teams; tensions already raised (1); not-doing list (2 items). Settings: defaults used for the team-set marker, the team-set limit and the crowded count.
Goals with a company parent: 9 of 12 (2 with a direct link, 7 with indirect links only). Team-set: 1. No company parent: 2. Goals flagged: 5.
Tensions: 1 raised, 1 possible. Priorities flagged: 2 (1 with no team goal, 1 with no owner named). Questions: 14 (10 for owners, 4 for the chief executive).

THE MAP

- P1. Grow repeat orders from restaurant groups. Measure: repeat-order revenue from restaurant groups for the quarter, from $2.4M to $2.9M. Owner: Commercial director. Supported by: G01 Sales (indirect); G02 Sales (indirect); G03 Account Management (direct); G09 Marketing (indirect). Flags: none.
- P2. Ship orders complete and on the promised day. Measure: share of orders shipped complete on the promised day, from 91% to 96%. Owner: Head of operations. Supported by: G04 Warehouse (direct); G06 Purchasing (indirect). Flags: none.
- P3. Lift gross margin. Measure: gross margin for the quarter, from 27% to 29%. Owner: not named. Supported by: G05 Purchasing (indirect); G07 Finance (indirect); G10 Warehouse (indirect). Flags: no owner named, indirect support only.
- P4. Launch the equipment service plan. Measure: service plans signed by 31 March 2027: 40. Owner: Chief executive. Supported by: no team goal. Flags: no team goal.

Team-set goals: G12 Warehouse: Re-label every bin location.
No company parent: G08 Customer Service: Answer every order query within two working hours (blank); G11 Marketing: Exhibit at two trade shows in the coastal region (names P5, not on the list).

GOALS FLAGGED

- G03 Account Management: Grow repeat orders from the 30 largest restaurant groups. Owner: Head of account management. FLAG, help not planned: the goal needs Warehouse; no Warehouse goal (G04 under P2, G10 under P3, G12 team-set) shares P1 or names Account Management or G03. See question 3.
- G07 Finance: Hold discounts down. Owner: Finance director. FLAG, help not planned: the goal needs Sales; neither Sales goal (G01, G02, both under P1) shares P3 or names Finance or G07. See question 6.
- G08 Customer Service: Answer every order query within two working hours. Owner: Customer service lead. FLAG, no company parent: the parent field is blank. See question 7.
- G09 Marketing: Pass restaurant-group leads to sales. Owner: Marketing lead. FLAG, no target: the target field is blank. See question 8.
- G11 Marketing: Exhibit at two trade shows in the coastal region. Owner: Marketing lead. FLAG, parent not on the list, touches a not-doing item: the goal names P5, which is not on this quarter's list; it names the coastal region and N1 rules out new sales regions this quarter (possible; the owner confirms). See question 9.

GOALS THAT PULL AGAINST EACH OTHER

- T1. G05 Purchasing and G10 Warehouse. Raised by the Purchasing manager: "Full-pallet buying needs overflow space that the warehouse plans to give up." G05 raises full-pallet purchase orders from 60% to 85%; G10 cuts rented overflow pallet spaces from 300 to 0. See question 11.
- T2. G02 Sales and G07 Finance. Possible, same quantity: G02 raises the average discount on first orders from 8% to 15%; G07 holds the average discount across all orders at no higher than 10%, and first orders are part of all orders. Possible: for the two owners to confirm. See question 12.

PRIORITIES NOBODY OWNS

- P3 Lift gross margin. FLAG, no owner named, indirect support only: the owner field is blank, and none of its three goals (G05, G07, G10) is measured on gross margin. See question 13.
- P4 Launch the equipment service plan. FLAG, no team goal: no goal names P4. See question 14.

QUESTIONS FOR EACH OWNER

Head of sales
1. G01: measure is new restaurant-group accounts signed, target 12; P1 is measured on repeat-order revenue from restaurant groups. When 12 accounts are signed, what changes in that revenue, and by when?
2. G02: measure is the average discount on first orders, raised from 8% to 15%. When it reaches 15%, what changes in repeat-order revenue from restaurant groups, and by when? Also in T2.

Head of account management
3. G03: the goal needs Warehouse, and no Warehouse goal sits under P1 or names Account Management or G03. What help does G03 need from Warehouse, and has it been planned?

Purchasing manager
4. G05: measure is the share of purchase orders in full pallets, 60% to 85%; P3 is measured on gross margin. When 85% is reached, what changes in gross margin, and by when? Also in T1.
5. G06: measure is weekly stock-outs on the 200 fastest-moving items, 14 to 5; P2 is measured on the share of orders shipped complete on the promised day. When stock-outs reach 5 a week, what changes in that share, and by when?

Finance director
6. G07: measure is the average discount across all orders, no higher than 10%; P3 is measured on gross margin. When the discount is held at 10% or below, what changes in gross margin, and by when? Also, the goal needs Sales, and no Sales goal sits under P3 or names Finance or G07: what help does it need, and has it been planned? Also in T2.

Customer service lead
7. G08: the parent field is blank. Which priority does the goal serve, or is it a team-set goal, or should it come off the list?

Marketing lead
8. G09: the target is blank, and the measure (qualified restaurant-group leads passed to sales) is indirect to P1's repeat-order revenue. What is the target? When it is met, what changes in P1's measure, and by when?
9. G11: the goal names P5, which is not on this quarter's list: which listed priority does it serve, if any? It names the coastal region and N1 rules out new sales regions: is the coastal region a new sales region?

Warehouse manager
10. G10: measure is rented overflow pallet spaces, 300 to 0; P3 is measured on gross margin. When the overflow store is given up, what changes in gross margin, and by when? Also in T1.

FOR THE CHIEF EXECUTIVE TO SETTLE WITH THE DEPARTMENT HEADS

11. T1: G05 needs overflow space that G10 gives up. How are both met, or which gives way? With the Purchasing manager and the Warehouse manager.
12. T2: G02 raises the first-order discount to 15% while G07 holds the all-orders average to 10%. Do first orders count within the 10%, and if so which target gives way? With the Head of sales and the Finance director.
13. P3: gross margin has no owner and no goal measured on it. Who owns it, and which team takes the margin measure?
14. P4: no team goal supports the service plan (target 40 by 31 March 2027). Which teams take it on?

ALSO NOTED

- G04: needs people (two pickers on the late shift); for the headcount plan workflow template.

LEFT OUT

None.

Prepared for the chief executive. The chief executive settles every question with the department heads and approves the final goals. Nothing has been sent, no goal has been changed and no team or person has been rated.

## What was observed

- Every required part was produced, in the template's order, and nothing in the instructions made the assistant stop. The inputs had the expected headers, no duplicate ids, no names, no personal notes and no secrets.
- The result matches the published example's output in every count, every flag, both tensions, both priority flags, the order and numbering of the 14 questions, the one ALSO NOTED line and the closing line. The differences are in wording only: the example gives fuller sentences in the questions and tension lines, and shows the output as bulleted Markdown where the template's format shows plain lines.
- Every number and fact in the output is in the inputs. The example's output also adds nothing that is not in the inputs.
- Places where the template left a choice to the assistant:
  - G11 names a priority that is not on the list. The step on placing goals treats "parent not on the list" and "no company parent" as separate headings, but the flag step lists them as one kind with an "or". The assistant flagged it as "parent not on the list" only and listed it under no company parent, as the example does. A reader could count it as two kinds.
  - Whether a coastal-region trade show "touches a not-doing item" ("no new sales regions") is a judgement. The template marks it "possible" and has the owner confirm, which handled it, but nothing says how far to stretch the match.
  - Whether G12, re-labelling bin locations, touches "no change of warehouse software" is also a judgement. It was left unflagged because the goal does not mention software.
  - The instruction block gives no wording for questions about a blank parent or a blank target (only for an indirect link and, in the acceptance tests, a blank parent). The assistant chose its own wording; the example's differs a little.
  - The settings line for the team-set marker, limit and crowded count appears in the inputs as "use the defaults", and the header line has to say which were defaulted. The assistant said all three; it is a small guess about how to phrase it.
  - The instruction block numbers ten steps and the procedure eleven, and the block does not say to count teams or to list the closing line's exact text beyond a summary. Neither caused a wrong result.
  - The output format shows placeholders in square brackets, such as "[who decides]" and "[n]", and the assistant filled them in. The template says "Use the output format exactly" without saying whether bullets or plain lines are required.
- This was one run by one model on one example. It shows that the instructions can be followed to the published result on this input. It does not show how the template performs on a real company's goals, and it has not been tested in a client environment.

## Edits made after this run, not run again

After an independent review, these small edits were made to the template. The template was not run again on the example, and the record above is unchanged.

- The instruction block now tells the assistant to count the priorities, goals and teams for the header.
- It now says that a goal whose parent is not on the list carries only that one flag kind, even when it is placed under no company parent.
- It now gives model wording for the questions on a blank parent, a parent not on the list, a blank measure or target, help not planned and a not-doing match.
- It now says that Markdown bullets and bold are acceptable for the output, if the parts, order, headings and fixed wording are kept.
- The not-doing match is limited to goals whose wording or measure names the thing the item rules out.
- The role-only rule now covers the priority list's owner column as well as the goals export.
- The not-doing match now says that naming a thing of the same kind as the item is enough for "possible".
- Tension rows naming a goal id not in the export are now set aside in the instruction block too, as the procedure already said.
- Names in the priority list's owner column and the tensions input's raised_by column now have fixed replacement wording ("owner named, role not given", "raised by: role not given"), and the block's role-only step is re-wrapped.
- Model question wording now also covers a team-set goal over the limit and the four priority flags.
- A note now says that PRIORITIES NOBODY OWNS lists every flagged priority, including one flagged only as crowded or indirect support only, and the header may add "with other flags only" when there are any.
- The sources and credits now credit the default crowded count to the source's script and mention the post-acquisition use.
- The profile and version notes now say the template was tried once on 10 November 2026.
