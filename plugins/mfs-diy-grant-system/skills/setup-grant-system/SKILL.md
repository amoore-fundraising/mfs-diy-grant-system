---
name: setup-grant-system
description: Set up the Grant System for a nonprofit - run the readiness checklist on the six foundations (strategic plan, theory of change, clean financials, program data and stories, master grant, AI policy), build the Grant System Profile, create the grant tracker, and suggest a folder structure. Use when the user says "set up my grant system," "get started," "are we ready for AI grant writing," "readiness checklist," "build our profile," "create our grant tracker," or when organization-profile cannot find a Grant System Profile.
---

# Set Up the Grant System

Help a nonprofit get its grant system running in one sitting, or across a few short sessions. Work through the steps in order. The user can stop after any step and pick up later.

Apply grant-guardrails throughout. Keep each message short. Ask questions in small groups, never a long form all at once.

## Step 1: Welcome and plan

Tell the user, in a few sentences:

- The Grant System helps them find funders, plan deadlines, draft proposals and budgets, check grants before submitting, manage awards, and write reports.
- It works from their own documents. The better those are, the better the drafts.
- Setup has four parts: a readiness check, the Grant System Profile, the grant tracker, and a folder plan. It usually takes 30 to 60 minutes.

Ask whether they want to start with the readiness check or skip to building the profile.

Invite them to upload or link anything they already have: strategic plan, theory of change or logic model, annual report, budget, 990, past proposals, program data, AI policy. Reading these first means fewer questions.

## Step 2: Readiness check

Use `templates/readiness-checklist.md` in this skill's folder.

1. For each of the six foundations, check what the user shared and ask one or two short questions about the rest. Suggest a score using the checklist's definitions and let the user confirm or change it. The user's score stands.
2. Note the technology basics, unscored.
3. Give a short summary: the score for each foundation, the total, what the total means, and the two or three most important next steps in the checklist's suggested order.
4. Offer the checklist as a document they can keep and share with their board.

Be encouraging and honest. A low score is a starting point, not a grade. Do not lecture.

## Step 3: Build the Grant System Profile

Use `templates/grant-system-profile.md` in this skill's folder.

1. Fill in everything you can from the documents the user shared. Note where each fact came from.
2. Ask for the rest one section at a time, in plain language. For example: "What are the official names of your programs, and how would you describe each in one sentence?"
3. Copy the mission word for word from an adopted source. Never reword it.
4. For Section 4, mark documents they do not have as "none yet".
5. For Section 7:
   - If they have an adopted AI policy, copy its rules in the policy's own words.
   - If not, keep the default "Never" list from the template, and suggest building a policy with ai-policy next.
6. Leave anything the user does not know as "[Fill in]". Do not guess.
7. Show the finished profile and ask for changes.
8. Save it as "[Organization] Grant System Profile":
   - In connected file storage (Google Drive or Microsoft 365), if available, after the user says yes.
   - Otherwise, give it as a file to download.
   - Either way, suggest adding it to a Claude Project named "[Organization] Grants" along with their key documents, so every grant conversation starts with it.

## Step 4: Create the grant tracker

Explain that the grant tracker keeps deadlines, funders, prospects, program numbers, and an AI experiment log in one place. Ask which they prefer:

- **Google Sheets or Excel (recommended for most):** create a workbook named "[Organization] Grant Tracker" using `templates/grant-tracker-columns.md`. Add dropdowns for the option columns and freeze the header rows. Save it to connected file storage after the user says yes, or give it as a file to download. If the user already has grants listed somewhere, offer to fill in the Grant Calendar and Funders tabs from it, and show the rows before adding them.
- **monday.com (if they already use it):** if monday.com is connected, offer to create a "Grants" workspace with one board per tracker part, using the same columns. Show the plan and create it only after the user says yes. If it is not connected, give them the column list to set up themselves.
- **Already have a tracker:** ask them to share it. Compare it to the five parts and suggest only what is missing. Do not rebuild it.

Add the tracker type and link to Section 5 of the profile.

## Step 5: Folder plan

Suggest this structure in their file storage, and adjust it to anything they already use:

- Grants
  - [Funder name]
    - [Year]: application, budget, attachments, award letter, Commitments Sheet, reports
  - Grant Data Sources: saved community statistics and their links
  - Stories and Quotes: only stories shared with consent
  - Standard Attachments: current budget, audit or financial review, 990, IRS determination letter, board list
  - Foundations: strategic plan, theory of change, master grant, AI policy, goal budget

Offer to create the folders if file storage is connected, after the user says yes. Add the links to Section 4 and Section 5 of the profile.

## Step 6: Next steps

End with a short list, based on their readiness check:

1. The first foundation to build, and the skill that builds it: ai-policy, theory-of-change, master-grant, or goal-budget.
2. A first real task to try, such as "Find funders for [program]" or "What's due in the next 30 days?"
3. A reminder to update the profile whenever programs, staff, approvers, or links change.

Do not set up recurring reports or reminders unless the user asks.

## Rules

- Never ask for passwords, portal logins, bank account numbers, or ID numbers.
- Do not create, save, or change anything in their file storage, email, or tracker without a yes.
- If the user shares information their AI policy (or the default "Never" list) keeps out of AI, stop and ask for a version without it.
- Plain language and short sentences. Do not use em dashes or the word "just."
