---
name: organization-profile
description: Find and read the organization's Grant System Profile (name, mission, programs, terminology, voice, key document links, grant tracker, approvers, AI policy rules, and its own processes) before any grant task, and explain how to reach the grant tracker. Apply automatically before funder research, proposals, budgets, reviews, award management, reports, and master grant updates.
---

# Organization Profile

Every skill in the Grant System starts here. The organization keeps its details in a document called "[Organization] Grant System Profile". Read it before doing any grant work, so everything Claude writes uses the organization's own names, voice, links, approvers, and AI policy rules.

## Step 1: Find the profile

Look in this order and stop at the first place you find it:

1. Files already in this conversation or in the current Claude Project's knowledge, with "Grant System Profile" in the title.
2. Connected file storage (Google Drive or Microsoft 365): search for a document whose title contains "Grant System Profile".

Then:

- If exactly one is found, use it.
- If more than one is found, list them and ask the user which is current. Do not choose one yourself.
- If none is found, tell the user plainly: "I couldn't find your Grant System Profile. You can upload it here, connect the file storage where it lives, or say 'set up my grant system' and I'll help you build one." Do not draft grant content until a profile is available. Simple questions that do not depend on the organization's details can still be answered.

Read the profile once per conversation. Read it again if the user says it changed.

## Step 2: Use what it says

- **Organization, programs, and terminology (Sections 1 to 3):** use official program names exactly, the preferred terms for the people served, and the voice described. Never use the words the organization avoids.
- **Key documents (Section 4):** open documents from these links, or from the Claude Project files. Always read the current version; do not work from memory. If a document is listed as "none yet," say so when it matters, and suggest the skill that builds it (ai-policy, theory-of-change, master-grant, goal-budget).
- **Where things live (Section 5):** use the named file storage, grants folder, folder naming pattern, email, and grant tracker. See "The grant tracker" below.
- **People and approvals (Section 6):** name the right person when something needs approval, signing, or budget review.
- **AI policy rules (Section 7):** follow them on every task. If the profile and the adopted AI policy ever differ, the policy wins; point out the difference to the user.
- **How we do things here (Section 8):** follow each process listed when it applies, and tell the user when one applies (for example, "This request is over $25,000, so it goes to the board for review").
- **Anything else (Section 9):** take it into account.

## The grant tracker

The grant tracker is where the organization keeps its grant deadlines, funders, prospects, and program numbers. Section 5 of the profile says which kind it is. It has five parts:

| Part | What it holds |
| --- | --- |
| Grant Calendar | Each grant and report: funder, program, request, type, deadline, internal dates, owner, status, report due dates, link to the grant folder |
| Funders | Current and past funders: relationship status, last contact, next step, renewal date |
| Prospects | Funders being researched: fit rating, focus match, typical grant size, next deadline, link |
| Program Data | Each program's outputs, outcome measures, and service units, by quarter |
| AI Experiment Log | New AI uses tried: date, what was tried, tool, data tier, result |

**Spreadsheet tracker (the default).** A Google Sheet or Excel workbook named "[Organization] Grant Tracker", with one tab per part. Before writing to it, read the tab's column headers and use them exactly.

- If Claude can edit the file through a connector, show the user the rows to add or change, and make the change only after they say yes.
- If Claude cannot edit the file (no connector, or the file was uploaded), show the rows as a small table the user can paste in, and say which tab they go on.

**monday.com tracker (optional).** If Section 5 names a monday.com workspace and monday.com is connected, each part is a board with the same name. Read each board's columns and status labels before writing to it, and post notes as updates on the item. If the profile names monday.com but it is not connected, tell the user and give the changes as a table instead.

**No tracker yet.** Answer from what the user shares, and offer to create a tracker with setup-grant-system.

Whenever a skill says "the Grant Calendar," "the Funders list," "the Prospects list," "Program Data," or "the AI Experiment Log," it means that part of the grant tracker, in whichever form the organization uses.

## Saving documents

When a skill creates a document (a draft, budget, brief, or report):

- If file storage is connected, save it in the grant's folder using the folder naming pattern in Section 5, and give the user the link.
- If not, give the user the document as a file to download, or in the chat if it is short, and tell them where the profile says it belongs.

## Step 3: Handle gaps

- Any field still showing "[Fill in" or "[Link" is unknown. Do not guess it. Use a `[CONFIRM: what is needed]` placeholder and tell the user which field is blank, so they can fill it in.
- If something in the profile looks out of date (for example, a staff member the user says has left, or a link that does not open), tell the user and suggest updating the profile. Do not edit the profile unless the user asks you to.
