# MFS DIY Grant System

A free, do-it-yourself AI grant system for small and midsized nonprofits, created by Moore Fundraising Solutions.

It helps your team get ready for AI grant writing, then supports the whole grant cycle: finding funders, planning deadlines, drafting proposals and budgets, checking before you submit, managing awards, and writing reports.

## Start with your foundations

AI can draft a grant in minutes, but only as well as what you feed it. This system works from your own documents, so it does its best work when these six foundations are in place:

1. Strategic plan
2. Theory of change
3. Clean financials
4. Program data and stories
5. Master grant
6. AI policy

The setup skill includes a readiness checklist so you can see where you stand. Four skills help you build the foundations you are missing: your AI policy, theory of change, master grant, and goal budget.

## What it does

| Stage | Skill | Ask Claude things like |
| --- | --- | --- |
| Always on | organization-profile | (applies automatically: finds and reads your Grant System Profile) |
| Always on | grant-guardrails | (applies automatically: accuracy, sources, and AI policy rules) |
| Get started | setup-grant-system | "Set up my grant system." "Are we ready for AI grant writing?" |
| Foundations | ai-policy | "Write our AI policy." |
| Foundations | theory-of-change | "Build our theory of change." |
| Foundations | master-grant | "Build our master grant narrative." |
| Foundations | goal-budget | "Build our goal budget." "What would full funding look like?" |
| Find | funder-research | "Find funders for our youth program." "Is this foundation a good fit?" |
| Plan | grant-calendar | "Add this grant to the calendar." "What's due this month?" |
| Start | start-grant | "We're applying to the Community Foundation. Here are the guidelines." |
| Write | draft-proposal | "Draft the LOI." "Answer these questions in 250 words each." |
| Write | grant-budget | "Build the project budget and budget narrative." |
| Review | review-before-submit | "Is this ready to submit?" |
| After | award-and-stewardship | "We got the grant." "The award letter came in." "Thank the funder." |
| Report | draft-grant-report | "The interim report is due." "Enter this quarter's numbers." |
| Maintain | update-master-grant | "We have new numbers." "Is our master grant current?" |

## What you need

- **A paid Claude plan** (Pro, Max, Team, or Enterprise). Plugins are not available on the free plan.
- **Recommended:** connect the file storage where your grant files live (Google Drive or Microsoft 365) in Claude's connector settings. Without it, you can upload files to a Claude Project instead.
- **Optional:** Gmail or Outlook, for saving email drafts. monday.com, if you already use it to track grants.

## Install

1. In Claude, open **Customize** in the sidebar, then **Plugins**.
2. Select **Add marketplace** and enter: `amoore-fundraising/mfs-diy-grant-system`
3. Find **MFS DIY Grant System** and select **Install**.
4. Turn on **Sync automatically** for the marketplace so you get updates.

If your organization uses a Claude Team or Enterprise plan, your administrator may need to allow outside plugins first.

## Get started

1. Create a Claude Project called "[Your Organization] Grants".
2. Upload your key documents to the Project: strategic plan, theory of change, annual report, budget, past proposals, and AI policy, if you have them.
3. In a chat in that Project, type: **Set up my grant system**

Claude will walk you through the readiness checklist, build your Grant System Profile, create your grant tracker (a Google Sheet or Excel workbook), and suggest a folder plan. Then it will point you to the first foundation to build.

## Your Grant System Profile

Everything specific to your organization lives in one document called "[Your Organization] Grant System Profile". Claude reads it before every grant task. Keep "Grant System Profile" in the title so Claude can find it, and update it when your programs, staff, approvers, or links change.

## How it stays safe

- Claude never invents facts, numbers, or stories. Unknowns become clear placeholders for you to fill in.
- Outside statistics are always cited, with the source and year.
- Your AI policy decides what information can be used. Until you adopt one, health information, information about minors, case records, passwords, and account numbers stay out.
- Claude drafts. People approve, submit, sign, and send.
- Claude asks before changing your files, tracker, or email.

## Want help?

Moore Fundraising Solutions can build your foundations and set up your grant system for you.

Moore Fundraising Solutions, Appleton, Wisconsin
moorefundraisingsolutions.com | amoore@moorefundraisingsolutions.com | (920) 698-3215

## License

Free for nonprofits to use and adapt under the Creative Commons Attribution-NonCommercial 4.0 License. See LICENSE. This plugin provides general guidance, not legal, tax, or accounting advice.

## Version history

- 1.0.0: First public version. Adds setup with a readiness checklist, the AI policy, theory of change, master grant, and goal budget skills, and a spreadsheet grant tracker. monday.com is now optional.
