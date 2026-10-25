# MFS DIY Grant System

A free, do-it-yourself AI grant system for small and midsized nonprofits, created by Moore Fundraising Solutions.

It helps your team find funders, keep track of deadlines, draft proposals and budgets, check grants before you submit, manage awards, and write reports.

## Start with what you have

You do not need perfect documents to begin. The system reads whatever you already have, such as an annual report, a budget, past grants, or your website, and works from there. Anything missing is marked clearly so you can fill it in.

When you are ready, it can also help you strengthen your grants over time with an AI policy, a theory of change, a master grant, a program budget, and a goal budget. These are always optional.

## What you need

- **A paid Claude plan** (Pro, Max, Team, or Enterprise). Plugins are not available on the free plan.
- **Nonprofit discount:** nonprofits can get up to 75% off Claude Team and Enterprise plans. Learn more at [claude.com/solutions/nonprofits](https://claude.com/solutions/nonprofits).
- **Recommended:** connect the file storage where your grant files live (Google Drive or Microsoft 365). Without it, you can upload files to a Claude Project instead.
- **Optional:** Gmail or Outlook, for saving email drafts. monday.com, if you already use it to track grants.

## Install

1. In Claude, click **Customize** in the left sidebar. (Use the sidebar, not the chat box.)
2. Click the **Plugins** tab.
3. Click **Add**, then **Add marketplace**.
4. Choose **Add from a repository** and enter: `https://github.com/amoore-fundraising/mfs-diy-grant-system`
5. Find **MFS DIY Grant System** in the list and click **Install**.
6. **Check that it is turned on.** If the plugin shows as disabled, turn it on.
7. Open a **new** chat. A chat that was already open will not see the plugin.

If your organization uses a Claude Team or Enterprise plan, your administrator may need to allow outside plugins first.

## Protect your information first

Before you upload any organizational information:

- **On a personal Pro or Max plan:** click your name, then **Settings**, then **Privacy**, and turn off **Help improve our AI models**.
- **On a Team or Enterprise plan:** your chats are covered by Anthropic's commercial terms and are not used to train AI models by default.
- **AI policy:** if your organization does not have one, the setup will offer to help you write one before you upload anything. Until you adopt one, leave out health information, information about minors, case, court, or school records, passwords, and account or ID numbers.

## Get started

1. Create a Claude Project called "[Your Organization] Grants".
2. In a new chat in that Project, type: **Set up my grant system**

Claude will check your account and AI policy, ask you to upload what you have, build your Grant System Profile, offer a simple grant tracker, and suggest a few optional ways to strengthen your grants.

## What it does

| Stage | Skill | Ask Claude things like |
| --- | --- | --- |
| Always on | organization-profile | (applies automatically: finds and reads your Grant System Profile) |
| Always on | grant-guardrails | (applies automatically: accuracy, sources, and AI policy rules) |
| Get started | setup-grant-system | "Set up my grant system." |
| Find | funder-research | "Find funders for our youth program." "Is this foundation a good fit?" |
| Plan | grant-calendar | "Add this grant to the calendar." "What's due this month?" |
| Start | start-grant | "We're applying to the Community Foundation. Here are the guidelines." |
| Write | draft-proposal | "Draft the LOI." "Answer these questions in 250 words each." |
| Write | grant-budget | "Build the project budget and budget narrative." |
| Review | review-before-submit | "Is this ready to submit?" |
| After | award-and-stewardship | "We got the grant." "The award letter came in." "Thank the funder." |
| Report | draft-grant-report | "The interim report is due." "Enter this quarter's numbers." |
| Maintain | update-master-grant | "We have new numbers." "Is our master grant current?" |
| Strengthen (optional) | ai-policy | "Help us write an AI policy." |
| Strengthen (optional) | theory-of-change | "Help us build a theory of change." |
| Strengthen (optional) | master-grant | "Build our master grant narrative." |
| Strengthen (optional) | goal-budget | "What would full funding look like?" |

## Your Grant System Profile

Everything specific to your organization lives in one document called "[Your Organization] Grant System Profile". Claude reads it before every grant task. Keep "Grant System Profile" in the title so Claude can find it, and update it when your programs, staff, approvers, or links change.

## How it stays safe

- Claude never invents facts, numbers, or stories. Unknowns become clear placeholders for you to fill in.
- Outside statistics are always cited, with the source and year.
- Your AI policy decides what information can be used.
- Claude drafts. People approve, submit, sign, and send.
- Claude asks before changing your files, tracker, or email.

## Want help?

Moore Fundraising Solutions can set up your grant system and build these pieces with you, including working with your bookkeeper on program budgets.

Moore Fundraising Solutions, Appleton, Wisconsin
moorefundraisingsolutions.com | amoore@moorefundraisingsolutions.com | (920) 698-3215

## License

Free for nonprofits to use and adapt under the Creative Commons Attribution-NonCommercial 4.0 License. See LICENSE. This plugin provides general guidance, not legal, tax, or accounting advice.

## Version history

- 1.1.0: Setup now starts with what you have. It checks your account privacy and AI policy before any upload, then offers optional ways to strengthen your grants instead of a readiness score. Grant budgets can be estimated from staff time when costs are not tracked by program.
- 1.0.0: First public version.
