---
name: master-grant
description: Build the organization's Master Grant Narrative from scratch - the single source every proposal is drafted from - using the Theory of Change, program data, financials, past proposals, and sourced community data. Use when the user says "build our master grant," "create a master grant narrative," "we start every grant from scratch," "boilerplate," "grant library," or when the Grant System Profile shows no master grant. To refresh an existing one, use update-master-grant instead.
---

# Master Grant Builder

Build the Master Grant Narrative: one current document with everything a proposal needs, so each new grant starts from approved, sourced content instead of a blank page.

Apply organization-profile and grant-guardrails throughout.

## Inputs

Ask for, or find in file storage and the Claude Project files:

1. **Theory of Change** (strongly recommended). If there is none, offer to build one first with theory-of-change. If the user wants to go ahead without it, take programs and outcomes from their documents and the user, and mark the outcomes section `[CONFIRM: outcomes once Theory of Change is done]`.
2. **Annual or impact report**
3. **Program data** (from the grant tracker's Program Data, or reports)
4. **Current approved budget**, and the most recent audit, financial review, or 990
5. **Two or three recent proposals**, ideally ones that were funded
6. **Board list**, IRS determination letter, and other standard attachments
7. **Stories and quotes** shared with consent
8. **Strategic plan**, if any

## Step 1: Build a fact sheet (for your own use)

List every fact the master grant will use: program names, numbers served, outcome results, budget figures, founding year, service area, partners, accreditations. For each, record the figure, the year it applies to, and the source (document and page, or the user). Mark anything without a source `[CONFIRM: what is needed]`. When two sources disagree, ask the user instead of choosing.

## Step 2: Research the community need

1. Use the service area from the profile and the problem named in the Theory of Change.
2. Search for current local, state, and national data from credible public sources, such as:
   - U.S. Census Bureau American Community Survey
   - United for ALICE reports for the state
   - County Health Rankings and Roadmaps
   - County or city health department community health assessments
   - State agencies tied to the issue (health, education, human services, workforce)
   - Federal agencies tied to the issue
   - Local community needs assessments
3. Open every page a number comes from. A search snippet is not a source.
4. Prefer the most recent year and the most local geography.
5. Record each statistic with its exact wording, year, geography, and link.
6. Offer to save the list as a "Grant Data Sources" document in the folder the profile names, after the user says yes.

## Step 3: Draft the Master Grant Narrative

Title: "Master Grant Narrative - [Organization]"

1. **Purpose line:** "This document provides a structured framework for writing accurate, consistent, and compelling grant proposals that reflect [Organization]'s mission, tone, and verified data sources."
2. **How to Use This Document:** every data point needs a source; all data, quotes, and statistics come from verified sources; AI must never create facts. Link to the Grant Data Sources list.
3. **Context:**
   - Organization overview: founding year, service area, who is served, number served, staff and volunteers, facility
   - One paragraph per program, grouped by Theory of Change pathway
   - Financial overview from the budget, audit, or 990
   - Accreditations or recognition, if any
4. **Theory of Change Summary:** the Big Idea, pathways, Pathway to Impact, and a link to the full document
5. **Writing Guidance:**
   - Task: structure the need, connect need to each program's solution and outcomes, select the strongest evidence, keep responses concise
   - Success criteria, including the local data sources from Step 2
   - Audience Personas: include the ones that fit this organization from community foundation and United Way, corporate, specialty (health, education, and so on), government, and family or faith foundation reviewers. For each, give expectations, knowledge level, tone, and focus.
   - Tone: the organization's voice, from its own materials and the profile
6. **Grant Summary:** follow this formula:
   - Start with the problem
   - Describe the solution
   - Emphasize impact, including who will be served
   - Include the funding request: the amount, how it will be used, and how many people it will serve. If a figure is unknown, leave a highlighted blank.
7. **Needs Statement:** four to six paragraphs moving from national or state data to local data, then to how the organization responds. Follow with a **Citation Summary** listing every source with its link, and **Suggested Improvements** naming data that would make the need stronger.
8. **Mission, Vision, and Values** as the organization has written them. Do not rewrite them.
9. **Approved Terminology:** official program names, preferred terms for the people served, and terms to avoid
10. **Impact and Outcomes by Program:** for each program, outputs with numbers and year; short-term, intermediate, and long-term outcomes from the Theory of Change with any measured results and year; and how each is measured. Then a short **Future Tracking Priorities** list.
11. **Qualitative Impact and Participant Perspectives:** the consent process, a link to the stories folder, and approved quotes only
12. **Current Funders:** current and recent funders, with renewal and report dates if known (from the grant tracker's Funders list, if there is one)
13. **Important Documents Checklist:** each standard attachment (budget, audit or financial review, 990, IRS determination letter, board list, and so on), with a link where it exists and `[NEEDED]` where it does not

## Writing rules

- **Outputs are not outcomes.** Never present a count as an outcome.
- **No causal claims beyond the evidence.** Say the program contributes to a community change unless an evaluation shows it caused it.
- **Every number has a year and a source.**
- **Only approved stories and quotes.** Never write or combine stories.
- **Write for this organization only.** If you reused text from a past proposal, check that no other organization's name or program appears.
- Plain language and short sentences. Do not use em dashes or the word "just."

## Step 4: Hand it back

1. Create the document, saved as described in organization-profile, or as a file to download.
2. Give the user a short separate list: every `[CONFIRM]` and `[NEEDED]` placeholder, facts where sources disagreed, statistics more than three years old or not local, and sections where materials were thin.
3. Suggest adding it to the Claude Project's files so every proposal starts from it.
4. Offer to add the link to Section 4 of the Grant System Profile, and the voice description to Section 3. Change the profile only after the user says yes.
5. Remind the user to run a freshness check with update-master-grant every six months.
