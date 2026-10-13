# Lab 2: Create the Cross-App Maintenance Update

**Topic 1 · 30 minutes · v9.0 · 14 October 2026**

Continue the verified operations brief from Lab 1. You will turn it into an initial PowerPoint update, then prepare an Outlook reply to a synthetic maintenance thread. You will test how grounding differs between an attached file, a chat transcript and a reviewed summary, and reconcile the same facts across all four apps.

**Learning outcome:** LO1: predict and mitigate integration challenges through verified cross-app grounding and handoffs.

**Expected outcome:** Northstar_Initial_Update.pptx, an unsent Outlook draft and Northstar_Cross_App_Evidence.csv with Excel, Word, PowerPoint and Outlook figures reconciled.

## Files

- [Instruction PDF](Lab-02-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-2)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/Integration_Risk_Register.csv` — LO1 controlled checkpoint for three integration risks

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Northstar-v9 is your own learner output folder.
- Verified Lab 1 workbook and Word brief, or supplied checkpoint and snapshot.

## Steps

### 1. Open your Lab 1 Word brief and cleaned workbook. If needed use this lab’s verified checkpoint and snapshot, clearly recording rejoin. Read data/Northstar_Email_Thread.txt. It asks for a portfolio update, not authorisation to reassign technicians.

```text
WORD COPILOT:
From this selected verified Northstar Water Services operations brief, extract a handoff table with reporting date, filter scope, total, closed, cancelled, backlog, overdue, unassigned backlog and recorded cost. Separate facts, proposed next actions and open decisions. Keep every value traceable to the supplied brief.
```

### 2. Open data/templates/Northstar_Management_Deck_Template.pptx in PowerPoint and save as Northstar_Initial_Update.pptx. For this initial update use four slides by keeping the first four layout slides and deleting the remaining unused template slides. Open Copilot and select your Word brief with Reference a file; if the command is unavailable, paste the reviewed brief into the prompt.

```text
POWERPOINT COPILOT:
Using this verified Northstar Word brief, create a four-slide initial update: scope and portfolio; backlog and overdue work; current assignments and proposed actions; decision required. Use the existing white/navy/blue design. Preserve all verified metrics. Add source/date notes. Do not invent completed work, savings or approved reassignment.
```

### 3. Review all four slides. Check status definitions, units and date, and correct any invented claim. Save a reconciled CSV using data/templates/Evidence_Register.csv: one row per claim and a source link. This is the bridge between app outputs; app chats are not automatically shared.

```text
POWERPOINT COPILOT:
Audit these four Northstar Water Services slides against the selected verified operations brief. For each numeric claim give the source, date and scope; flag unsupported service-restoration, safety, customer-impact or approval claims. Propose corrections without changing the checked values.
```

### 4. In Outlook create a new training draft addressed to operations.manager@example.invalid with subject DRAFT - Northstar maintenance update - review required. Do not send. Paste the synthetic thread into the draft or use it as quoted context; Copilot summarises the supplied text, not a real mailbox thread. Open Copilot > Draft with Copilot; UI names may differ.

```text
OUTLOOK COPILOT:
Draft a concise reply to the synthetic thread quoted below, using the verified Northstar brief and these checked metrics. State the 30 September 2026 scope, backlog/overdue findings, proposed next actions and the decision requested. Explain that assignments are unapproved proposals. Do not claim the attachments have been sent. Keep as a draft.
```

### 5. If your Outlook offers reference attachments, attach the verified Word brief and choose it as context. Otherwise paste the reviewed metrics into the drafting prompt. Replace any placeholder summary with exact checked values; inspect recipients, subject, tone and attachment names. Save only the draft and a local TXT copy of its reviewed body.

### 6. Ask Word Copilot to compare your pasted slide/email summaries with the brief, then perform the same comparison yourself. Add the cross-app prompt log entries manually. Keep all four source links with the reconciliation record; any mismatch must be fixed before the skill labs.

```text
WORD COPILOT:
Compare these pasted PowerPoint and Outlook summaries with this verified Word brief. List inconsistent figures, status definitions, dates, owner claims or approved-action wording. Do not resolve a conflict by guessing. Return a discrepancy table with source and correction needed.
```

### 7. Complete Integration_Risk_Register.csv using the observed Northstar evidence from Labs 1-2. Enter the impact, preventive control, owner and observable rollback or escalation trigger for all three supplied risk rows.

## Verification

- **Four apps:** Excel Checks, Word brief, four-slide update and unsent Outlook draft share the same date and values.
- **Cross-app grounding:** Named file or pasted verified evidence is provided in each app; no assumed shared chat.
- **Draft boundary:** example.invalid recipient; nothing sent and no assignment approved.
- **LO1 checkpoint:** Integration Risk Register has all three rows, fixed date/baseline evidence and no invented cause or approval.

## Expected Outcome

Northstar_Initial_Update.pptx, an unsent Outlook draft and Northstar_Cross_App_Evidence.csv with Excel, Word, PowerPoint and Outlook figures reconciled.

## Checkpoint

If you fell behind, use data/checkpoints/Northstar_Verified_Checkpoint.xlsx and data/checkpoints/Northstar_Verified_Snapshot.docx. Record checkpoint used in Prompt_Log; then perform this lab, rather than claiming the checkpoint as your output.

## Troubleshooting

| If this happens | Fix |
|---|---|
| Copilot cannot find the source | Use the app file picker to select the actual OneDrive file. A typed local path or a different app chat is not shared context. If needed copy only the verified snapshot into the current app. |
| A total disagrees with Control | Clear dashboard filters to All, check table extent and duplicate IDs, recalculate, then compare definitions and reporting date. Reconcile before continuing. |
| The named feature is missing | Confirm the correct assigned account, English display language and app version. Use the stated manual practice route; record feature unavailable. This is not evidence that a native skill ran. |

## Challenge

Repeat the task for one different site and explain how the filter scope changes the result. Keep the original verified output.

## Reflection

Which evidence proves the output is correct, and which decision still needs a person?

> Northstar Water Services is fictional. Use the verified 120-row baseline and fixed reporting date 30 September 2026. Current assignments are evidence; proposals are not approved. Agent labs use retrieval, configuration, testing and supported sharing only; they never claim external-service actions.
