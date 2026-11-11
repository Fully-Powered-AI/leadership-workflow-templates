# Goal alignment review: an invented example

*Illustrative example with invented data.* The company, its priorities, its goals and every figure below are invented. Company K is an invented 80-person wholesale distributor of commercial kitchen equipment with seven teams. Its chief of staff runs a goal alignment review on the drafted goals for the first quarter of 2027, for the chief executive. First come the inputs the chief of staff supplied, in full, then the review the capability returned.

## The inputs

### 1. Settings

```
Company: Company K, a wholesale distributor of commercial kitchen equipment
Period: first quarter of 2027 (January to March)
Today: Monday 14 December 2026
Who decides: the chief executive
Run by: chief of staff
Team-set marker, team-set limit, crowded count: use the defaults
```

### 2. Company priorities (from the leadership offsite notes)

```
priority_id,priority,measure,owner
P1,Grow repeat orders from restaurant groups,"Repeat-order revenue from restaurant groups for the quarter, from $2.4M to $2.9M",Commercial director
P2,Ship orders complete and on the promised day,"Share of orders shipped complete on the promised day, from 91% to 96%",Head of operations
P3,Lift gross margin,"Gross margin for the quarter, from 27% to 29%",
P4,Launch the equipment service plan,Service plans signed by 31 March 2027: 40,Chief executive
```

### 3. Team goals (exported from the goals spreadsheet)

```
goal_id,team,goal,measure,target,owner_role,parent_priority,needs_from
G01,Sales,Win new restaurant-group accounts,New restaurant-group accounts signed,12,Head of sales,P1,Marketing
G02,Sales,Use a first-order discount to win new accounts,Average discount on first orders,Raise from 8% to 15%,Head of sales,P1,
G03,Account Management,Grow repeat orders from the 30 largest restaurant groups,Repeat-order revenue from the 30 largest restaurant groups,"From $1.8M to $2.2M",Head of account management,P1,Warehouse
G04,Warehouse,"Ship orders complete and on the promised day, adding two pickers to the late shift",Share of orders shipped complete on the promised day,From 91% to 96%,Warehouse manager,P2,Purchasing
G05,Purchasing,Buy in full pallets to cut freight cost,Share of purchase orders placed in full pallets,From 60% to 85%,Purchasing manager,P3,
G06,Purchasing,Cut stock-outs on the 200 fastest-moving items,Stock-outs a week on the 200 fastest-moving items,From 14 to 5,Purchasing manager,P2,
G07,Finance,Hold discounts down,Average discount across all orders,No higher than 10%,Finance director,P3,Sales
G08,Customer Service,Answer every order query within two working hours,Share of order queries answered within two working hours,From 70% to 90%,Customer service lead,,
G09,Marketing,Pass restaurant-group leads to sales,Qualified restaurant-group leads passed to sales,,Marketing lead,P1,
G10,Warehouse,Give up the rented overflow store,Pallet spaces rented in the overflow store,From 300 to 0,Warehouse manager,P3,
G11,Marketing,Exhibit at two trade shows in the coastal region,Trade shows attended in the coastal region,2,Marketing lead,P5,
G12,Warehouse,Re-label every bin location,Bin locations re-labelled,All 4200,Warehouse manager,team-set,
```

### 4. Tensions already raised

```
goal_a,goal_b,raised_by,note
G05,G10,Purchasing manager,Full-pallet buying needs overflow space that the warehouse plans to give up.
```

### 5. What we are not doing this quarter

```
- No new sales regions this quarter.
- No change of warehouse software this quarter.
```

## The output

**GOAL ALIGNMENT REVIEW: Company K, first quarter of 2027**

- **For:** the chief executive. Prepared Monday 14 December 2026 by the chief of staff.
- **Read from:** 4 company priorities; 12 team goals from 7 teams; tensions already raised (1); not-doing list (2 items). Settings: defaults used for the team-set marker, the team-set limit and the crowded count.
- **Goals with a company parent:** 9 of 12 (2 with a direct link, 7 with indirect links only). **Team-set:** 1. **No company parent:** 2. **Goals flagged:** 5.
- **Tensions:** 1 raised, 1 possible. **Priorities flagged:** 2 (1 with no team goal, 1 with no owner named). **Questions:** 14 (10 for owners, 4 for the chief executive).

**The map**

- **P1. Grow repeat orders from restaurant groups.** Measure: repeat-order revenue from restaurant groups for the quarter, from \$2.4M to \$2.9M. Owner: Commercial director.
  Supported by: G01 Sales (indirect); G02 Sales (indirect); G03 Account Management (direct); G09 Marketing (indirect).
  Flags: none.
- **P2. Ship orders complete and on the promised day.** Measure: share of orders shipped complete on the promised day, from 91% to 96%. Owner: Head of operations.
  Supported by: G04 Warehouse (direct); G06 Purchasing (indirect).
  Flags: none.
- **P3. Lift gross margin.** Measure: gross margin for the quarter, from 27% to 29%. Owner: not named.
  Supported by: G05 Purchasing (indirect); G07 Finance (indirect); G10 Warehouse (indirect).
  Flags: no owner named, indirect support only.
- **P4. Launch the equipment service plan.** Measure: service plans signed by 31 March 2027: 40. Owner: Chief executive.
  Supported by: no team goal.
  Flags: no team goal.

Team-set goals: G12 Warehouse: Re-label every bin location.

No company parent: G08 Customer Service: Answer every order query within two working hours (blank); G11 Marketing: Exhibit at two trade shows in the coastal region (names P5, not on the list).

**Goals flagged**

- **G03 Account Management:** Grow repeat orders from the 30 largest restaurant groups. Owner: Head of account management. **FLAG, help not planned:** the goal needs Warehouse, and none of Warehouse's goals (G04 under P2, G10 under P3, G12 team-set) shares P1 or names Account Management or G03. See question 3.
- **G07 Finance:** Hold discounts down. Owner: Finance director. **FLAG, help not planned:** the goal needs Sales, and neither Sales goal (G01 and G02, both under P1) shares P3 or names Finance or G07. See question 6.
- **G08 Customer Service:** Answer every order query within two working hours. Owner: Customer service lead. **FLAG, no company parent:** the parent field is blank. See question 7.
- **G09 Marketing:** Pass restaurant-group leads to sales. Owner: Marketing lead. **FLAG, no target:** the target field is blank. See question 8.
- **G11 Marketing:** Exhibit at two trade shows in the coastal region. Owner: Marketing lead. **FLAG, parent not on the list, touches a not-doing item:** the goal names P5, which is not on this quarter's list; it names the coastal region, and N1 says no new sales regions this quarter (possible). See question 9.

**Goals that pull against each other**

- **T1. G05 Purchasing and G10 Warehouse.** Raised by the purchasing manager: full-pallet buying needs overflow space that the warehouse plans to give up. G05 raises the share of purchase orders placed in full pallets from 60% to 85%; G10 takes the pallet spaces rented in the overflow store from 300 to 0. See question 11.
- **T2. G02 Sales and G07 Finance.** Possible, same quantity: G02 raises the average discount on first orders from 8% to 15%; G07 holds the average discount across all orders at no higher than 10%, and first orders are part of all orders. Possible: for the two owners to confirm. See question 12.

**Priorities nobody owns**

- **P3 Lift gross margin.** **FLAG, no owner named, indirect support only:** the owner field is blank, and its three goals (G05 Purchasing, G07 Finance, G10 Warehouse) are all measured on something other than gross margin. See question 13.
- **P4 Launch the equipment service plan.** **FLAG, no team goal:** no goal in the export names P4. See question 14.

**Questions for each owner**

*Head of sales*

1. **G01:** the measure is new restaurant-group accounts signed, target 12; P1 is measured on repeat-order revenue from restaurant groups. When 12 new accounts are signed, what changes in repeat-order revenue from restaurant groups, and by when?
2. **G02:** the measure is the average discount on first orders, raised from 8% to 15%. When it reaches 15%, what changes in repeat-order revenue from restaurant groups, and by when? Also in T2.

*Head of account management*

3. **G03:** the goal needs Warehouse, and no Warehouse goal is filed under P1 or names Account Management or G03. What help does G03 need from Warehouse this quarter, and has the warehouse manager taken it on?

*Purchasing manager*

4. **G05:** the measure is the share of purchase orders placed in full pallets, from 60% to 85%; P3 is measured on gross margin. When 85% is reached, what changes in gross margin, and by when? Also in T1.
5. **G06:** the measure is weekly stock-outs on the 200 fastest-moving items, from 14 to 5; P2 is measured on the share of orders shipped complete on the promised day. When stock-outs fall to 5 a week, what changes in that share, and by when?

*Finance director*

6. **G07:** the measure is the average discount across all orders, no higher than 10%; P3 is measured on gross margin. When the average discount is held at 10% or below, what changes in gross margin, and by when? The goal needs Sales, and neither Sales goal is filed under P3 or names Finance or G07: what help does G07 need from Sales, and has the head of sales taken it on? Also in T2.

*Customer service lead*

7. **G08:** the parent field is blank. Which of P1 to P4 does this goal serve? If none, should it be Customer Service's team-set goal, or come off the list for this quarter?

*Marketing lead*

8. **G09:** the target is blank, and the measure is qualified restaurant-group leads passed to sales; P1 is measured on repeat-order revenue from restaurant groups. What is the target for the quarter? Once it is set, when it is met, what changes in repeat-order revenue from restaurant groups, and by when?
9. **G11:** the goal names P5, which is not on this quarter's list. Which of P1 to P4 does it serve, if any? It also names the coastal region, and the not-doing list says no new sales regions this quarter (N1): is the coastal region a new sales region for Company K?

*Warehouse manager*

10. **G10:** the measure is pallet spaces rented in the overflow store, from 300 to 0; P3 is measured on gross margin. When the overflow store is given up, what changes in gross margin, and by when? Also in T1.

**For the chief executive to settle with the department heads**

11. **T1:** Purchasing plans to raise full-pallet buying from 60% to 85% of purchase orders, and the purchasing manager says this needs overflow space that Warehouse plans to give up, from 300 rented pallet spaces to 0. Which goal gives way, or how are both met? With the purchasing manager and the warehouse manager.
12. **T2:** Sales plans to raise the average first-order discount from 8% to 15%, and Finance plans to hold the average discount across all orders at no higher than 10%. Do first-order discounts count within the 10% limit, and if so, which target gives way? With the head of sales and the finance director.
13. **P3:** gross margin has no owner named, and none of its three goals is measured on gross margin itself. Who owns P3 this quarter, and does any team take on the margin measure?
14. **P4:** the equipment service plan has no team goal, and its target is 40 plans signed by 31 March 2027. Which teams take it on, and with what goals, before the quarter starts?

**Also noted**

- G04: needs people (two pickers for the late shift); for the headcount plan capability.

**Left out**

- None.

Prepared for the chief executive. The chief executive settles every question with the department heads and approves the final goals. Nothing has been sent, no goal has been changed and no team or person has been rated.
