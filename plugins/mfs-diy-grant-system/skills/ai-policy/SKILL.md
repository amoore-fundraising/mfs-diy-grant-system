---
name: ai-policy
description: Draft the organization's AI Ethos and Policy from a short interview, using the bundled nonprofit AI policy template, calibrated to the team's comfort level and the sensitive information it holds. Use when the user says "write our AI policy," "we need an AI policy," "AI use policy," "what can staff put into AI," "update our AI policy," or when the Grant System Profile shows no AI policy.
---

# AI Policy Builder

Turn a short conversation into a finished AI Ethos and Policy the organization can adopt. Build it before the team puts organizational information into AI, so the rules are in place first.

Apply grant-guardrails throughout. Read organization-profile if a profile exists; it is not required for this skill.

This skill needs no uploaded documents. It is often the first thing a new organization does, before uploading anything else. If it was started from setup-grant-system, return to setup when the draft is done, and use the new policy's rules from then on.

## Inputs

- The template at `templates/ai-policy-template.md` in this skill's folder. Always start from it.
- Any existing AI, technology, privacy, or confidentiality policy the user shares. Keep their existing rules unless the user wants to change them.
- The mission, word for word, from the profile or an adopted source.

## Step 1: Interview

Ask these in three short rounds. Skip anything already answered by the profile or shared documents.

**Round 1: Where you are today**

1. How would you describe your team's comfort with AI: not using it, curious, or using it regularly?
2. Which AI tools does anyone use now, and on what kind of account (free, personal paid, or an organization plan)?
3. Who will this policy cover: staff only, or also volunteers, board members, and contractors?

**Round 2: What you need to protect**

4. What sensitive information do you hold? For example: donor records, health information, information about minors, court, school, or case records, immigration or financial details of the people you serve.
5. What concerns do you or your board have about AI?
6. Is there anything you never want AI used for? For example: deciding who gets services, or writing to the people you serve without staff review.

**Round 3: Who decides**

7. Who should approve new uses of AI? One person, or two people together for bigger steps?
8. Who will own the policy and answer questions about it?
9. Do you use a password manager, and is two-factor sign-in turned on for key accounts?
10. Do any of your funders, partners, or contracts limit how you can use AI or share data?

## Step 2: Choose a starting stance

The stance shapes the defaults. The user's own answers always override it. Tell the user which stance you chose and why, in one sentence.

| Stance | When | Defaults |
| --- | --- | --- |
| Careful start | Not using AI, strong concerns, or highly sensitive information | Fewer approved uses, two approvers for every Level 3 and 4 use, experimenting only with Green information |
| Guided use | Curious or some use, typical concerns | Template defaults |
| Active use | Using AI regularly, few concerns, low-sensitivity information | Broader approved uses, one approver for Level 3, two for Level 4 |

## Step 3: Fill in the template

Replace every bracket, section by section:

- **Header:** organization name, adoption date as `[DATE]`, approver (ask whether the ED or the board adopts it), next review six months after adoption.
- **Ethos (Section 1):** the mission word for word, and who the policy covers.
- **AI risk (Section 2):** add the concerns from the interview in plain language, and any areas where AI will not be used.
- **Safe Path (Section 3):** the approver from the interview.
- **How we use AI (Section 4):** approved uses that fit the stance, including grant research, drafting, and reporting with the Grant System. Ruled-out uses from the interview.
- **Data tiers (Section 5):** sort the sensitive information from the interview into the tiers. These always go in **Never**:
  - Health information, information about minors, and court, school, or case records about the people served
  - Passwords, credentials, bank account numbers, and ID numbers
- **Approved tools (Section 6):** the tools they plan to use (including Claude), their password manager, and current tools they want to keep. For each tool, list the account type and allowed data tiers. Mark any setting that must be confirmed, such as whether the plan can use the organization's information for training, as `[CONFIRM SETTING]`. Do not state a vendor's data practices from memory.
- **Levels of autonomy (Section 7):** the approvers from the interview.
- **Experimenting (Section 9):** the AI experiment log location. If they use the Grant System tracker, it is the AI Experiment Log tab or board.
- **Volunteers, board, and contractors (Section 11):** keep only if the policy covers them.
- **Transparency (Section 12):** draft a short funder disclosure statement, for example: "We use AI tools to help draft and organize grant materials. A member of our staff reviews and approves everything we submit, and all data and stories come from our own records."
- **Security (Section 15):** password manager and two-factor sign-in. If either is missing, keep the rule and list it as a quick win in the notes.
- **Governance and Questions (Sections 18 and 19):** the policy owner and contact.

Delete every "Template note" before handing it back. Keep the line crediting the template to Moore Fundraising Solutions.

## Writing rules

- Keep the template's plain-language voice and structure. Do not add sections.
- Never guess a fact. Anything unknown stays `[CONFIRM: what is needed]`.
- Plain language and short sentences. Do not use em dashes or the word "just."

## Step 4: Hand it back

1. Create the policy as a document named "[Organization] AI Ethos and Policy", saved as described in organization-profile, or as a file to download.
2. Give the user a short separate list (not part of the policy):
   - The stance chosen and why
   - Every `[CONFIRM]` and `[CONFIRM SETTING]` placeholder
   - Security quick wins
   - **A legal review recommendation** if they hold health information, information about minors, or court, school, or case records. The template provides policy guidance, not legal advice.
3. Explain the next steps: the ED or board reviews and adopts it, then the team learns the Safe Path in Section 3.
4. Once it is adopted, offer to copy its rules into Section 7 of the Grant System Profile and add the link and adoption date to Section 4. Change the profile only after the user says yes.
