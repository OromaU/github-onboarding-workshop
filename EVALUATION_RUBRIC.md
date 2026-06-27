# Workshop Contributor Evaluation Rubric

**Microsoft Naija Security User Group — GitHub Onboarding Workshop · June 2026**

Use this rubric to provide structured, consistent feedback to members as they submit Pull Requests during the workshop. Score each criterion from 1 to 5, then total the scores for an overall grade.

---

## Scoring Summary Sheet

| Criterion | Score (1–5) | Facilitator Notes |
|-----------|-------------|-------------------|
| 1. Completeness of Lab Answers | | |
| 2. Adherence to Security Best Practices | | |
| 3. Quality of README Markdown Formatting | | |
| 4. Professionalism of Pull Request Comments | | |
| **Total** | **/20** | |

**Overall Grade:**

| Total Score | Grade | Description |
|-------------|-------|-------------|
| 18 – 20 | Excellent | Outstanding work — ready to mentor others |
| 14 – 17 | Good | Solid understanding with minor gaps |
| 10 – 13 | Satisfactory | Core concepts understood, needs more practice |
| 6 – 9 | Developing | Significant gaps — additional support recommended |
| 1 – 5 | Incomplete | Substantial rework required before sign-off |

---

## Criterion 1 — Completeness of Lab Answers

*Did the member fill in all required fields, checklists, and reflection questions across the section templates they submitted?*

| Score | Label | Description |
|-------|-------|-------------|
| **5** | Exemplary | All fields, checklists, and reflection questions answered in full. Answers are specific, personal, and demonstrate genuine engagement with the material. No placeholder text remaining. |
| **4** | Proficient | Nearly all fields completed. One or two minor items left blank or answered too briefly, but the overall submission is thorough and shows clear understanding. |
| **3** | Satisfactory | Most required fields completed. Some checklist items unticked without explanation, or some reflection questions answered with only one sentence. Placeholder text partially replaced. |
| **2** | Developing | Less than half the fields completed. Several checklist items skipped. Reflection questions mostly unanswered or left as the original prompt text. |
| **1** | Incomplete | Very few fields filled in. The majority of the template is unchanged from the original. No meaningful engagement with the lab content. |

**Facilitator Feedback Template:**
```
Completeness — Score: X/5
[Your specific feedback here. Reference the exact fields or questions that were 
missed. Example: "Great job completing all lab checklists. The reflection on 
Section 3 about .gitignore patterns was particularly thorough."]
```

---

## Criterion 2 — Adherence to Security Best Practices

*Does the member's submission demonstrate understanding and application of the security principles taught in the workshop?*

| Score | Label | Description |
|-------|-------|-------------|
| **5** | Exemplary | All security practices correctly applied and articulated. 2FA enabled, email privacy turned on, branch protection configured, no secrets in any file, `.gitignore` includes security-relevant patterns, and security reasoning is clearly explained in reflection answers. |
| **4** | Proficient | Most security practices correctly applied. Minor gap in one area — e.g. Dependabot not yet enabled, or one reflection answer lacks specific security reasoning. No security violations present. |
| **3** | Satisfactory | Core practices in place (2FA, email privacy, no committed secrets) but some best practices not applied — e.g. branch protection not configured, `.gitignore` missing key patterns, or security reflection answers are vague. |
| **2** | Developing | Some security awareness shown but notable gaps — e.g. repository created as Public when it should be Private, collaborator granted Admin instead of Read access, or `.gitignore` missing entirely. No committed secrets. |
| **1** | Incomplete | Security practices largely absent or incorrectly applied. May include a repository without 2FA, credentials or tokens present in any committed file, or fundamental misunderstanding of public vs. private repository implications. Requires immediate follow-up. |

> **Auto-fail condition:** Any submission containing an actual secret, token, password, or credential in a committed file must be flagged immediately regardless of score. The member should be guided to revoke the credential and the file corrected before any score is given.

**Facilitator Feedback Template:**
```
Security Practices — Score: X/5
[Your specific feedback here. Reference what was done well and what needs 
improvement. Example: "2FA is enabled and email privacy is on — well done. 
Branch protection was not configured on main — revisit Section 2 settings 
and add a rule requiring at least one reviewer."]
```

---

## Criterion 3 — Quality of README Markdown Formatting

*Is the member's README draft in Section 4 (or the README in their own repo) well-structured, correctly formatted, and using Markdown effectively?*

| Score | Label | Description |
|-------|-------|-------------|
| **5** | Exemplary | README uses a logical hierarchy of headings (`#`, `##`, `###`). Code is wrapped in fenced code blocks with language identifiers. Table of Contents links work correctly. Bold/italic used purposefully, not decoratively. Badges present. No raw Markdown symbols visible in the rendered preview. Reads professionally end-to-end. |
| **4** | Proficient | Good overall structure with correct heading hierarchy. Code blocks used for all code. Minor formatting inconsistency — e.g. one section missing a heading, or a link using incorrect syntax but mostly renders correctly. Table of Contents present. |
| **3** | Satisfactory | Basic Markdown used correctly — headings, bold, bullets. Code blocks present but missing language identifiers. Table of Contents missing or links not working. Some formatting errors visible in the rendered preview (e.g. asterisks showing as raw text). Readable but not polished. |
| **2** | Developing | Minimal Markdown usage. Headings inconsistent or missing. Most content written as plain prose without lists, code blocks, or tables where they would be appropriate. Raw Markdown symbols visible in rendered output. |
| **1** | Incomplete | Little to no Markdown formatting applied. Content is plain text. File may be missing sections entirely or contain only the original template prompts with no actual content added. |

**Facilitator Feedback Template:**
```
Markdown Quality — Score: X/5
[Your specific feedback here. Reference what rendered well and what did not.
Example: "The heading hierarchy is clear and consistent. Code blocks are 
correctly fenced with python identifier — great work. The Table of Contents 
links are broken — check that your heading text matches the anchor exactly, 
including hyphens and lowercase."]
```

---

## Criterion 4 — Professionalism of Pull Request Comments

*Is the Pull Request title clear? Does the description explain what was added and why? Are any review comments or responses written respectfully and constructively?*

| Score | Label | Description |
|-------|-------|-------------|
| **5** | Exemplary | PR title follows the format `docs: add [Name] - Section [N] notes`. Description clearly explains what was added, references relevant section numbers, and mentions any challenges faced. If the member reviewed a colleague's PR, their comments are specific, constructive, and respectful. Responses to reviewer feedback are prompt and professional. |
| **4** | Proficient | PR title is clear and descriptive even if not following exact format. Description is present and informative. Any review comments are helpful and polite. Minor improvement possible — e.g. description could be slightly more specific. |
| **3** | Satisfactory | PR title is present but generic (e.g. "Update README.md"). Description is brief — one sentence or a vague summary. Review comments, if any, are appropriate but not substantive. Gets the job done but lacks detail. |
| **2** | Developing | PR title is auto-generated or unclear (e.g. "Patch 1"). No description provided. The reviewer or facilitator cannot easily understand what was changed without reading the diff. |
| **1** | Incomplete | No PR title or description. OR PR comments contain unprofessional, dismissive, or disrespectful language. Requires a conversation with the member about professional communication standards. |

**Facilitator Feedback Template:**
```
PR Professionalism — Score: X/5
[Your specific feedback here. Reference the PR title, description, and any 
comments. Example: "Your PR title and description are clear and well-written. 
The description explains exactly what you added and references the section 
number — this makes it easy to review. Next time, try to also mention any 
open questions you have for the reviewer."]
```

---

## Complete Feedback Template

*Copy and paste this into your PR review comment when giving final feedback:*

```markdown
## Workshop Evaluation Feedback

Hi [Member Name], thank you for submitting your work! Here is your structured feedback:

---

### Criterion 1 — Completeness of Lab Answers: X/5
[Your feedback]

### Criterion 2 — Adherence to Security Best Practices: X/5
[Your feedback]

### Criterion 3 — Quality of README Markdown Formatting: X/5
[Your feedback]

### Criterion 4 — Professionalism of Pull Request Comments: X/5
[Your feedback]

---

**Total Score: X/20**

**Overall:** [Excellent / Good / Satisfactory / Developing / Incomplete]

**Key Takeaway:**
[One sentence summarising the most important thing this member should focus on next.]

**Next Steps:**
- [ ] [Action item 1]
- [ ] [Action item 2]

Great effort today — keep building on this foundation!

*— MNSUG Facilitator*
```

---

## Quick Reference Card

*For fast scoring during the workshop session:*

| Score | Completeness | Security | Markdown | PR Quality |
|-------|-------------|---------|----------|------------|
| **5** | All fields answered, specific and personal | All practices applied, clearly explained | Exemplary structure, code blocks, TOC, badges | Clear title, detailed description, great review comments |
| **4** | Nearly complete, one minor gap | Most practices applied, no violations | Good structure, minor inconsistency | Clear title, informative description |
| **3** | Most fields done, some brief answers | Core practices in place, some gaps | Basic formatting, TOC missing or broken | Generic title, brief description |
| **2** | Less than half complete | Notable security gaps, no secrets committed | Minimal Markdown, errors visible | No description, unclear title |
| **1** | Mostly unchanged from template | Practices absent or misapplied | Plain text, no formatting | No title/description, or unprofessional |

---

*Microsoft Naija Security User Group · June 2026 · Facilitator Use Only*
