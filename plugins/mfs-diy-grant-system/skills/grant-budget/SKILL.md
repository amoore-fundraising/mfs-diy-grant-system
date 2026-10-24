---
name: grant-budget
description: Build a project budget and budget narrative (budget justification) for a grant application from the organization's real budget figures, including match and indirect costs. Use when the user says "build the grant budget," "project budget for," "budget narrative," "budget justification," "how much should we ask for," "fill in the funder's budget form," or "what's our match."
---

# Grant Budget

Build a clear, accurate project budget and the narrative that explains it. Every figure must come from the organization's own numbers or the user.

Apply organization-profile and grant-guardrails throughout.

## Inputs

- The funder's budget form or instructions, including any limits on indirect costs, salaries, equipment, or food
- The organization's current approved operating budget
- Staff positions, FTE, and salaries for the program (ask the user; these may be sensitive, so confirm the AI policy allows them)
- Program costs the user provides
- The goal budget, if the profile links one (see goal-budget)
- Other funding already committed to the program, for match or leverage

Never invent a cost, salary, rate, or revenue figure. Any missing number is a yellow `[XX: what is needed]` cell.

## Step 1: Ask, in one round

Before building, confirm:

1. What the grant will pay for: the whole program, a part of it, or a new piece
2. The request amount, if already decided
3. The grant period
4. Which staff positions work on the program and what share of their time
5. Whether the funder allows indirect costs, and at what rate (from the guidelines)
6. Match required, and where it will come from

## Step 2: Build the budget

Build a spreadsheet saved as described in organization-profile, or fill in the funder's own form if it has one. Use these columns unless the funder sets its own:

| Line item | Total program cost | Request from this funder | Other sources | Notes |

- **Personnel:** one row per position (title only, no names), with FTE and share charged to the grant
- **Fringe:** the organization's fringe rate times salaries, if the user provides the rate
- **Non-personnel:** supplies, occupancy, travel, equipment, contracted services, and so on
- **Indirect:** only as the funder allows
- **Totals:** use formulas, not typed totals. Totals must add up.
- **Other sources:** committed funding only. Mark pending funding as pending.

If a goal budget exists, use it to show what full funding of the program would look like, and point out where this request fits.

## Step 3: Budget narrative

Write one short paragraph per budget category explaining what each line pays for and how it was calculated, for example: "Program Coordinator (0.5 FTE): $[XX] annual salary x 50% = $[XX]." Match the funder's word limit if there is one.

## Step 4: Check and hand back

- Confirm the request total matches the amount in the draft proposal. Flag any mismatch.
- Confirm the program budget does not exceed the organization's total budget.
- List every yellow placeholder.
- Remind the user that the person named in the profile to review grant budgets should review it before submission.

Never change an approved organizational budget. Accounting or audit questions go to the organization's accountant.
