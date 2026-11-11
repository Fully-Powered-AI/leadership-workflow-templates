# Weekly owner business brief: an invented example

*Illustrative example with invented data.* The business, its customers, suppliers, deals, amounts and dates below are all invented. The business is an invented 30-person interior fit-out company, run by an owner, with a small online shop on the side. First come the exports and notes the owner supplied, in full, then the brief the capability returned. Every figure in the brief can be recomputed from the inputs.

## The inputs

### 1. Settings (typed by the owner)

```
Run date: Monday 2 November 2026
Currency: USD
Last week: 26 October to 1 November 2026. The week before: 19 to 25 October 2026.
Accounts held back from available cash: Tax reserve
Cash floor: 12000
Fall in net sales that counts: 10%
Quiet deal: 14 days or more without activity
Overdue invoice: more than 30 days past due
Stages in order: Lead, Proposal, Negotiation
Export dates: cash.csv 2026-10-30; sales.csv through 2026-11-01;
  pipeline_this_week.csv 2026-11-02; pipeline_last_week.csv 2026-10-26;
  receivables.csv 2026-10-30; calendar.csv covers 2026-11-02 to 2026-11-08
```

### 2. cash.csv

```
date,account,balance
2026-10-23,Operating,41200.00
2026-10-23,Tax reserve,12000.00
2026-10-23,Payroll,6500.00
2026-10-30,Operating,35650.00
2026-10-30,Tax reserve,12000.00
2026-10-30,Payroll,9100.00
```

### 3. sales.csv

```
date,channel,gross_sales,refunds
2026-10-20,Projects,14500.00,0.00
2026-10-21,Shop,2100.00,150.00
2026-10-22,Projects,9800.00,1200.00
2026-10-24,Shop,1750.00,0.00
2026-10-27,Projects,11200.00,0.00
2026-10-28,Shop,1900.00,300.00
2026-10-29,Projects,8600.00,0.00
2026-10-31,Shop,2350.00,0.00
```

### 4. pipeline_last_week.csv (exported 26 October)

```
deal,customer,stage,status,amount,expected_close,last_activity
C-fitout-2,Customer C,Negotiation,open,24000,2026-11-13,2026-10-22
D-showroom,Customer D,Proposal,open,18000,2026-11-27,2026-10-19
F-pantry,Customer F,Proposal,open,9500,2026-12-04,2026-10-23
G-reception,Customer G,Lead,open,6000,2026-12-18,2026-10-14
H-cabinets,Customer H,Negotiation,open,15000,2026-10-30,2026-10-20
J-bar,Customer J,Lead,open,,2026-12-31,2026-10-26
```

### 5. pipeline_this_week.csv (exported 2 November)

```
deal,customer,stage,status,amount,expected_close,last_activity
C-fitout-2,Customer C,Negotiation,won,24000,2026-11-13,2026-10-30
D-showroom,Customer D,Negotiation,open,18000,2026-11-27,2026-10-28
F-pantry,Customer F,Proposal,open,11000,2026-12-04,2026-10-30
G-reception,Customer G,Lead,open,6000,2026-12-18,2026-10-14
H-cabinets,Customer H,Negotiation,open,15000,2026-10-30,2026-10-20
J-bar,Customer J,Lead,lost,,2026-12-31,2026-10-29
K-lobby,Customer K,Lead,open,7500,2027-01-15,2026-11-02
```

### 6. receivables.csv (exported 30 October)

```
invoice,customer,amount_open,due_date
INV-2041,Customer B,3200.00,2026-09-18
INV-2055,Customer E,1850.00,2026-10-20
INV-2049,Customer A,5400.00,2026-10-02
```

### 7. calendar.csv

```
date,title,with,kind,amount
2026-11-03,Quarterly review,Customer C,meeting,
2026-11-04,Proposal presentation,Customer F,meeting,
2026-11-04,Supplier A invoice due,Supplier A,payment,6300.00
2026-11-04,Team lunch,,other,
2026-11-05,Rent,Landlord,payment,4200.00
2026-11-06,Delivery sign-off,Customer D,deadline,
2026-11-06,Payroll run,,payment,18400.00
2026-11-06,Insurance premium due,Insurer,payment,
```

### 8. The owner's notes (typed)

```
- Customer H told me on Friday they may take the cabinets work to another
  firm. Nobody has called them back.
- Supplier A says the October delivery slips to 12 November.
```

## The output

**WEEKLY OWNER BUSINESS BRIEF: week of Monday 2 November 2026**

**For:** the owner. Prepared 2 November 2026 from cash.csv (30 October), sales.csv (through 1 November), pipeline_this_week.csv (2 November), pipeline_last_week.csv (26 October), receivables.csv (30 October), calendar.csv (2 to 8 November) and the owner's notes. Missing: none. All amounts in USD.

**The one item to look at first (proposed by rule; you decide).** W1: H-cabinets, Customer H, $15,000. Cash after listed payments is not below the floor, so the rule takes the first item on the watch list, and this is it. The expected close of 30 October has passed with the deal still open, and your note says Customer H may take the work elsewhere. No cash item applies this week.

**Cash**
- Total in all accounts: $56,750 on 30 October ($59,700 on 23 October), down $2,950.
- Held back (Tax reserve): $12,000. Available: $44,750 ($47,700), down $2,950.
- Payments listed for the week: $28,900 in 3 payments. 1 more with no amount (question 1).
- If every listed payment is made and nothing arrives, available cash would be $15,850. The floor is $12,000, so it stays above the floor, before 1 payment with no amount.
- Source: cash.csv, as of 30 October.

**Sales**
- Net sales 26 October to 1 November: $23,750 (gross $24,050, refunds $300). The week before: $26,800. Down $3,050, 11.4%.
- By channel: Projects $19,800 ($23,100 the week before), down $3,300, 14.3%. Shop $3,950 ($3,700), up $250, 6.8%.
- Source: sales.csv, through 1 November. It is the only sales source used.

**Pipeline movement**
- Open this week (2 November): $57,500 across 5 deals. Last week (26 October): $72,500 across 5 deals with an amount; 1 open with no amount.
- Won: C-fitout-2, Customer C, $24,000. Lost: J-bar, Customer J, amount not given. New: K-lobby, Customer K, $7,500. Amount changed: F-pantry, Customer F, from $9,500 to $11,000. Stage moved: D-showroom, Customer D, from Proposal to Negotiation, moved forward. Missing from this week's export: none.
- Tie-out: $72,500 − $24,000 + $1,500 + $7,500 = $57,500. J-bar had no amount last week, so nothing is taken off for it.
- Source: pipeline_this_week.csv (2 November), pipeline_last_week.csv (26 October).

**This week's commitments (2 to 8 November)**
- Tue 3 November: Quarterly review, Customer C (meeting).
- Wed 4 November: Proposal presentation, Customer F (meeting).
- Wed 4 November: Supplier A invoice due, Supplier A, $6,300 (payment).
- Thu 5 November: Rent, Landlord, $4,200 (payment).
- Fri 6 November: Delivery sign-off, Customer D (deadline).
- Fri 6 November: Payroll run, $18,400 (payment).
- Fri 6 November: Insurance premium due, Insurer (payment, no amount).
- Not listed: 1 internal item.
- Source: calendar.csv, 2 to 8 November.

**Watch list** (largest amount first, then items with no amount)
1. **W1.** H-cabinets, Customer H, $15,000: expected close 30 October, 3 days ago, still open. Your note: "Customer H told me on Friday they may take the cabinets work to another firm. Nobody has called them back." Source: pipeline_this_week.csv, 2 November; your notes.
2. **W2.** G-reception, Customer G, $6,000: no activity since 14 October, 19 days. Source: pipeline_this_week.csv, 2 November.
3. **W3.** INV-2049, Customer A, $5,400: due 2 October, 31 days past due on 2 November. Source: receivables.csv, 30 October.
4. **W4.** INV-2041, Customer B, $3,200: due 18 September, 45 days past due on 2 November. Source: receivables.csv, 30 October.
5. **W5.** Net sales down 11.4% ($3,050), against a limit of 10%. Source: sales.csv, through 1 November.
6. **W6.** Insurance premium due Friday 6 November: no amount given. Source: calendar.csv, 2 to 8 November.
7. **W7.** Your note: "Supplier A says the October delivery slips to 12 November." Beside it, from the calendar: Wednesday 4 November, Supplier A invoice due, $6,300 (payment). Source: your notes; calendar.csv, 2 to 8 November.

**Questions for you**
1. The insurance premium due Friday 6 November has no amount in calendar.csv, so it is left out of the $28,900 and the $15,850 may be lower. What is the amount?
2. J-bar (Customer J) had no amount in last week's file and is lost this week with no amount, so it is in neither open total. Is there an amount to record for it?

**What is for you to decide:** which item comes first this week, and what to pass to someone else.

**Sources and gaps.** cash.csv: 6 rows used. sales.csv: 8 rows used, 0 left out. pipeline_this_week.csv: 7 rows used. pipeline_last_week.csv: 6 rows used. receivables.csv: 3 rows used, INV-2055 (13 days past due) not past the limit. calendar.csv: 8 rows, 7 listed and 1 internal item left out. Notes: 2. Not supplied: nothing.

Every figure traces to the files named above. The brief changes no record, contacts no one and sends nothing.
