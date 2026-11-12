# Business model assumptions review

Workflow template, version 0.1.0.

## Purpose

Help a founder or executive sponsor see a new or revised business model for what it is: a set of claims, some backed by something that happened and some only believed. The assistant lays the claims out in six blocks (customers, offer, channels, revenue, costs, partners), marks each claim evidenced or assumed by a fixed rule, ranks the assumed claims by a score from the sponsor's own ratings, and, for the riskiest few, names the cheapest test that could produce real evidence. The sponsor chooses which assumptions to invest in testing and sets the pass and fail lines. The assistant prepares; it never rates a claim, picks a test for the sponsor, makes a projection or valuation, recommends whether to go ahead, or sends, books, orders or changes anything.

## When to use it and when not to

Use it before serious money or time goes into a model: a new offer, a move from one-off sales to a subscription, a new customer group, a new channel, a changed price structure. Run it again when the model changes or when a test result comes back.

Do not use it:

- to judge one offer's wording for a buyer; use Offer review for that;
- to imagine how a decision fails before it is made; use Premortem before a decision;
- to decide whether a piece of work suits an AI build; use Workflow fit check;
- for a sales forecast, margin, lifetime value, funding round or valuation; this workflow template makes no such figures, and a finance adviser should;
- for the terms of a partner or supplier agreement, or any legal question; those go to the right adviser;
- to judge a person, including whether to hire someone.

## Roles

- **Sponsor:** the founder or executive who decides where the money and time go. Writes the brief, rates the assumed claims, sets the pass and fail lines, and chooses which assumptions to test.
- **Preparer:** the person who types the claims list and runs the assistant. Often the sponsor, or an operations lead acting for them.
- **Evidence owners:** whoever holds the records behind a claim, such as orders, receipts or timing notes. They confirm the evidence is as typed.

## Inputs

1. **The brief,** from the sponsor: the model and what is changing; the sponsor's role; the decision this review serves and its date; the review date; any context worth knowing, such as order counts or how many people were asked. If the model is missing, stop and ask. Anything else missing is printed as "not stated".
2. **The claims list,** one claim per row, in the order the sponsor wants them numbered. Default columns: `block,claim,evidence_kind,evidence,evidence_date,if_wrong,how_sure,test_idea,test_cost,test_days`. If the headers do not match, stop and ask which column is which; do not guess.
   - `block` is one of customers, offer, channels, revenue, costs or partners.
   - `evidence_kind` is one of: **paid** (money changed hands, such as a payment, deposit or order), **used** (people did the thing or kept doing it, from logs or records), **measured** (counted or timed from records, or a quote or receipt in writing), **said** (someone told us, in an interview, survey or call), **estimate** (our own or an outside estimate or benchmark). Blank means none.
   - `evidence` is a line on what was seen. `evidence_date` is the year and month, or the full date, of the observation.
   - `if_wrong` rates how badly the model suffers if the claim is false: 1 a small change, 2 a material change to price, plan or timing, 3 the model fails.
   - `how_sure` rates the sponsor's confidence: 1 fairly sure, 2 leaning, 3 a guess.
   - `test_idea`, `test_cost` and `test_days` are optional: a test the sponsor already has in mind, what it costs (one amount, in one currency, as typed; the amount is printed as typed and no currency is added if none is typed) and how many days it takes.
3. **Settings.** Defaults: [your risk score] is 6; [your riskiest count] is 5; [your evidence age limit] is 12 months. If none are given, use the defaults and say so in the Prepared line.

The assistant works only from what is typed or pasted. It needs no connection to any system, and it never asks for a password or a login code.

## The procedure

1. **Check the inputs.** The brief must name the model. Headers must match. Every `block` must be one of the six. `if_wrong` and `how_sure`, where given, must be 1, 2 or 3. `evidence_kind`, where given, must be one of the five. If a header, block, rating or kind is out of scale, stop and list the rows. A `test_cost` or `test_days` that is not a number is printed as typed and not used for ordering.
2. **Number the claims** C01, C02 and so on in the order given.
3. **Mark each claim.** It is EVIDENCED only if its kind is paid, used or measured and it has an evidence date. Print the kind and the date. Every other claim is ASSUMED, with a reason in brackets: said, estimate, no evidence (kind blank), or evidence undated (a counting kind with no date). Do not judge whether evidence is good or sufficient; the rule is the only test. Do not upgrade a claim because the evidence line sounds confident.
4. **Lay out the blocks** in the order customers, offer, channels, revenue, costs, partners. Under each, list its claims in number order with the claim, its mark and the evidence as typed ("none" if blank). A block with no claims prints "No claims supplied. Nothing in this block is known; ask the sponsor." and the assistant adds no claim of its own.
5. **Count evidence by block:** evidenced claims out of all claims in the block, and "All assumed." where none is evidenced. Then the total, evidenced and assumed.
6. **Score the assumed claims.** An assumed claim with both ratings gets score = if_wrong × how_sure, from 1 to 9. An assumed claim missing either rating is not ranked; list it as "Not yet rated" with what is missing. Evidenced claims are not scored.
7. **Rank** by score, highest first. Ties: higher if_wrong first; then the lower stated test_cost (a cost of 0 is stated; a claim with no stated cost after those with one); then the lower claim number.
8. **Mark the riskiest:** the first [your riskiest count] claims in rank order whose score is at least [your risk score]. List any other claim at or above the risk score on the "Also at or above" line, with its score.
9. **Name the cheapest evidence** for each riskiest claim, in rank order. If the sponsor gave a `test_idea`, print it with its cost and days (or "not stated"). If not, propose a test from the ladder below by the claim's block, labelled "Proposed", with cost and days "not stated". Print the pass and fail lines as "sponsor to set"; never set them. A sponsor's test is printed as typed; do not improve or replace it.
10. **The ladder,** cheapest first. Rung 1: look in records you already hold for what actually happened (result: measured). Rung 2: ask a few people who have done it what they did last time, not what they would do (result: said, which stays assumed until a rung 3 or 4 result follows). Rung 3: ask for a small written commitment, such as a deposit or an order (result: paid). Rung 4: run one small, capped trial with a real customer or channel (result: used or paid). Rung 5, building part of the model, is never proposed; it appears only if the sponsor names it. Default rung by block: customers 2, offer 3, channels 4, revenue 3, costs 1, partners 2. If the claim's evidence_kind is already said and its default rung is 2, propose rung 3 instead, because a rung 2 result can only add more said evidence. For a proposed test print "Result would be:" and the result in the ladder.
11. **Recheck old evidence.** Compare each evidenced claim's date with the review date, in whole months, counted by subtracting months and ignoring the day when a date has only a year and month. If it is more than [your evidence age limit] months before the review date, list it. If the review date is not stated, skip this step and say so.
12. **Open questions for the sponsor,** in this order: one per claim in the recheck list; one per assumed claim with a rating missing; one per block with no claims; one per claim whose evidence is undated; one per evidenced claim whose line says "we think" or "we expect"; then one question, if any claim is riskiest, asking for the pass and fail lines of those claims. Each gives the facts and asks only what is missing. Recommend nothing.
13. **Sponsor's choice:** one line for each riskiest claim, with three empty boxes. Leave them empty.
14. **Return the review** to the preparer for the sponsor.

## Exceptions and stop conditions

- **The model is not named, or the headers do not match:** stop and ask.
- **A block, rating or evidence kind is outside the allowed values:** stop and list the rows.
- **No assumed claim has both ratings:** produce the layout, the evidence counts and the questions, print "None." under ranked assumptions and the cheapest evidence, and ask for the ratings.
- **A block is empty:** print the empty wording and ask; do not invent claims.
- **Evidence kind is paid, used or measured but the line says "we think" or "we expect":** keep the sponsor's mark, and add a question asking whether the line describes something that happened. It comes after the undated-evidence questions and before the pass and fail question.
- **Asked to forecast revenue, work out margins, lifetime value or payback, value the business, or build a financial model:** decline. Claims containing figures are repeated as typed and never combined.
- **Asked whether to go ahead, which assumption matters most, or which model is best:** decline. The ranking follows the sponsor's own ratings; the sponsor decides.
- **Asked to rate a claim, set a pass or fail line, or pick a test for the sponsor:** decline and leave the empty wording.
- **Asked to propose alternative models, rewrite the offer or judge the offer's wording:** decline, and point to the related workflow templates in When to use it.
- **Asked to send the review, contact a customer or partner, place an order, make a payment or change a record:** decline. A person does these once the sponsor has chosen.
- **The review touches a legal question, the terms of an agreement, hiring or a person's performance:** decline that part and say who should take it.
- **The inputs contain bank details, passwords or other private data:** do not repeat them; ask the preparer to remove them.

## Output format

```
BUSINESS MODEL ASSUMPTIONS REVIEW: [model, in a few words]

Model: [model and what is changing].
Sponsor: [role]. Decision this serves: [decision / not stated]. Decision date: [weekday date / not stated].
Context: [from the brief / not stated]
Review date: [weekday date / not stated]. Prepared from the brief and the claims list[; default settings]. The review makes no projection or valuation.

THE MODEL, BLOCK BY BLOCK
CUSTOMERS
  C[nn] EVIDENCED ([kind], [date]). [claim] Evidence: [as typed].
  C[nn] ASSUMED ([said / estimate / no evidence / evidence undated]). [claim] Evidence: [as typed / none].
  [No claims supplied. Nothing in this block is known; ask the sponsor.]
OFFER
  [same, one line per claim]
CHANNELS
  [same]
REVENUE
  [same]
COSTS
  [same]
PARTNERS
  [same]

EVIDENCE BY BLOCK
[Block]: [n] of [m] evidenced.[ All assumed.][ No claims supplied.]
[one line per block, in the same order]
Total: [n] of [m] evidenced, [k] assumed.

RANKED ASSUMPTIONS
[rank]. C[nn] [Block]. If wrong [1-3], how sure [1-3], score [1-9].[ RISKIEST.] [claim]
[None. No assumed claim has both ratings.]
Not yet rated: [C numbers with what is missing / none].
Also at or above the risk score, beyond the first [n]: [C numbers with scores / none].

CHEAPEST EVIDENCE FOR THE RISKIEST
[rank]. C[nn] [claim]
  Test: [sponsor's test as typed / Proposed, rung [n]: text of the rung]. Cost: [amount / not stated]. Days: [n / not stated].
  Result would be: [result, for a proposed test only]
  Pass line: sponsor to set. Fail line: sponsor to set.
[None. No claim is riskiest.]
A paid, used or measured result moves a claim to evidenced.
A result that someone said does not.

EVIDENCED CLAIMS TO RECHECK
C[nn] [claim]: evidence dated [date], [n] months before the review date; the limit is [n] months.
[None. / Review date not stated; not checked.]

OPEN QUESTIONS FOR THE [SPONSOR ROLE]
[n]. [C number and block, or "Pass and fail lines"]: [the facts]. [The question.]
[None.]

SPONSOR'S CHOICE
C[nn] [ ] Test now  [ ] Later  [ ] Accept as is
[None.]

Prepared for the [sponsor role]'s decision. Nothing has been decided, sent, ordered, booked or changed. No projection or valuation has been made.
```

## Reviewer checklist

1. Every claim typed appears once, in its own block, with the evidence as typed. (Preparer)
2. Every EVIDENCED mark has a kind of paid, used or measured and a date; every other claim is ASSUMED. (Preparer)
3. Each block's evidence count matches its claims, and the total matches. (Preparer)
4. Every score is if_wrong times how_sure, and the ranking follows the stated tie order. (Preparer)
5. Exactly the first [your riskiest count] claims at or above the risk score are marked RISKIEST, and any others at or above it are on the "Also at or above" line. (Preparer)
6. Every test is either the sponsor's, as typed, or labelled Proposed with the default rung for its block (rung 3 in place of rung 2 for a claim already marked said); no pass or fail line is filled. (Sponsor)
7. Every month count in the recheck list is right. (Evidence owners)
8. No figure from the claims has been added, averaged, projected or compared with another. (Sponsor)
9. The sponsor's choice boxes are empty. (Sponsor)

## Acceptance tests

Proposed tests. None has been run.

1. **Ordinary list.** Thirteen claims across six blocks with ratings. Expected: all sections filled; evidence counts and ranking match a hand count.
2. **Tie on score.** Three claims score 9 with different stated costs, one unstated. Expected: lowest cost first, the unstated cost last.
3. **Said is not evidence.** A claim with kind said and a confident line. Expected: ASSUMED (said).
4. **Undated evidence.** Kind measured, no date. Expected: ASSUMED (evidence undated), and a question.
5. **Old evidence.** A measured claim dated fifteen months before the review date. Expected: EVIDENCED, listed under recheck with 15 months.
6. **Empty block.** No partner claims. Expected: the empty wording, "0 of 0 evidenced. No claims supplied.", and one question.
7. **Unrated claim.** An assumed claim with no how_sure. Expected: not ranked, listed as not yet rated, one question.
8. **More than five above the line.** Seven assumed claims score 6 or more. Expected: first five RISKIEST, the other two on the "Also at or above" line.
9. **Rating out of scale.** if_wrong given as 4. Expected: stops and lists the row.
10. **Headers changed.** Claims file headed `area,statement,source`. Expected: stops and asks which column is which.
11. **Asked for a forecast.** "What will revenue be in year two?" Expected: declines; the claims' figures are not combined.
12. **Asked what to test first.** Expected: declines to choose for the sponsor; points to the ranking and the choice line.
13. **Said claim at rung 2.** A riskiest customers claim with kind said and no test idea. Expected: Proposed, rung 3, with "Result would be: paid".

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above.

```
You prepare a business model assumptions review for a founder or executive
sponsor. You lay the model out in six blocks, mark each claim evidenced or
assumed by a fixed rule, rank the assumed claims from the sponsor's own
ratings, and name the cheapest test for the riskiest. You never rate a
claim, choose a test for the sponsor, set a pass or fail line, make a
forecast, margin, lifetime value or valuation, recommend whether to go
ahead, or send, book, order, pay for or change anything. The sponsor
decides; a person acts on the choices.

INPUTS. The brief (model, sponsor role, decision and date, review date,
context) and the claims list with columns block,claim,evidence_kind,
evidence,evidence_date,if_wrong,how_sure,test_idea,test_cost,test_days.
If the headers differ, stop and ask which column is which. If the model is
missing, stop and ask. Blocks: customers, offer, channels, revenue, costs,
partners. Kinds: paid, used, measured, said, estimate (blank = none).
if_wrong and how_sure are 1, 2 or 3. If a block, kind or rating is outside
these, stop and list the rows. Never ask for passwords or login codes.

STEPS.
1. Number the claims C01, C02 in the order given.
2. A claim is EVIDENCED only if its kind is paid, used or measured and it
   has an evidence date; print the kind and date. Every other claim is
   ASSUMED, with the reason in brackets: said, estimate, no evidence, or
   evidence undated. Never upgrade a claim because the evidence sounds
   confident, and never judge how good the evidence is.
3. List the blocks in the order customers, offer, channels, revenue,
   costs, partners, each with its claims in number order and the evidence
   as typed ("none" if blank). A block with no claims prints "No claims
   supplied. Nothing in this block is known; ask the sponsor." Invent no
   claim.
4. Count evidenced claims out of all claims per block ("All assumed."
   where none; "No claims supplied." where empty), then the total.
5. Score each assumed claim that has both ratings: if_wrong x how_sure.
   An assumed claim missing a rating is not ranked; list it under "Not yet
   rated" with what is missing. Evidenced claims are not scored. If no
   assumed claim has both ratings, print "None." under ranked assumptions
   and under the cheapest evidence, and ask for the ratings.
6. Rank by score, highest first. Ties: higher if_wrong, then lower stated
   test_cost (a cost of 0 is stated; unstated after stated), then lower
   claim number. A test_cost or test_days that is not a number is printed
   as typed and not used for ordering; add no currency to an amount.
7. RISKIEST = the first 5 ranked claims with a score of at least 6 (use
   the sponsor's settings if given: [your risk score] 6, [your riskiest
   count] 5, [your evidence age limit] 12 months; if none are given, say
   "default settings" in the Prepared line). List any other claim at or
   above 6 on the "Also at or above" line with its score.
8. For each riskiest claim, in rank order, print the sponsor's test_idea
   as typed with its cost and days ("not stated" if blank). If there is
   none, propose the default rung for its block, labelled "Proposed", with
   cost and days not stated, and add "Result would be:" with the rung's
   result. If the claim's kind is already said and its default rung is 2,
   propose rung 3 instead. Rungs: 1 look in records you already hold for what actually
   happened (measured); 2 ask a few people who have done it what they did
   last time, not what they would do (said, which stays assumed until a
   rung 3 or 4 result follows); 3 ask for a small written commitment, such
   as a deposit or an order (paid); 4 run one small, capped trial with a
   real customer or channel (used or paid). Defaults: customers 2, offer
   3, channels 4, revenue 3, costs 1, partners 2. Never propose building
   part of the model. Print the pass and fail lines as "sponsor to set";
   never fill them.
9. List each evidenced claim whose date is more than 12 months (or the
   sponsor's limit) before the review date, counted in whole months
   (subtract months; ignore the day when a date has only a year and
   month). If the review date is missing, say it was not checked.
10. Open questions, in this order: one per claim in the recheck list; one
    per assumed claim with a rating missing; one per empty block; one per
    claim with undated evidence; one per evidenced claim whose line says
    "we think" or "we expect"; then one asking for the pass and fail lines of
    the riskiest claims. State the facts and ask only what is missing.
    Recommend nothing.
11. Print the sponsor's choice line for each riskiest claim with three
    empty boxes. Leave them empty.
12. Use the output format exactly. Repeat figures from the claims exactly
    as typed; never add, average, project or compare them. End with:
    "Prepared for the [sponsor role]'s decision. Nothing has been decided,
    sent, ordered, booked or changed. No projection or valuation has been
    made."

If asked to forecast, value the business or work out margins, decline. If
asked whether to go ahead, which assumption matters most, or which test to
run, decline: the sponsor decides. If asked to rate a claim or set a pass
or fail line, decline and leave the empty wording. If asked for
alternative models or to rewrite the offer, decline. If the matter is
legal, about the terms of an agreement, or about hiring or judging a
person, decline and say who should take it. Do not repeat bank details or
other private data. Recheck every count, score, rank and month count
before you return the review.
```

## What to customize

- Who sponsors, and who may rate the claims.
- [your risk score], [your riskiest count] and [your evidence age limit].
- Which evidence kinds count. The default is paid, used or measured; a company that sells on long contracts may add a signed order as its own kind.
- The default rung for each block, if the ladder does not suit how you sell.
- Whether a claim with harm 3 and a score below the risk score should still be marked riskiest.
- The two rating scales; a wider scale needs a new risk score.
- Where the reviews are kept, so the next one starts from the last and shows which claims moved to evidenced.
- Which notes the assistant may read in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI. Editorially reviewed. Tried once on its invented example in Claude on 10 November 2026; the record of that run is published with the template. The instructions were then revised (which claims get a missing-rating question, a cost of 0, counting months, a place for the "we think" question, a stronger rung for a claim that is already only said, and the format paste line) and run once more on the same example; the record published with the template is the second run. Not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
