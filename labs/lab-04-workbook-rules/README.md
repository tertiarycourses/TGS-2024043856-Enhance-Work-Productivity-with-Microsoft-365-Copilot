# Lab 4: Create and Test Workbook .Rules for HR Service Reporting

**Topic 2 · 30 minutes · v9.2 · 20 October 2026**

Turn Lumina’s workbook conventions into a visible .Rules worksheet. Keep one rule per cell in column A, include a formula-driven reporting-date rule, test the output, and verify that the sheet travels with a copied workbook. A .Rules sheet is guidance for Copilot, not Excel formula enforcement or a security boundary.

**Learning outcome:** LO2: plan a controlled transition using Personalisation, .Rules and reusable Skills.

**Expected outcome:** Lumina_Rules_Workbook.xlsx with visible .Rules column A, a checked Rules_Test output and a copied-workbook sharing check.

## Files

- [Instruction PDF](Lab-04-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-4)
- `data/Lumina_HR_Cases.xlsx` — synthetic Lumina source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Lumina-HR-v9 is your own learner output folder.
- Lab 3 scope comparison; verified Lab1 clean source or supplied checkpoint.

## Steps

### 1. Open the clean workbook, save as Lumina_Rules_Workbook.xlsx and inspect Control. In Copilot use Add work content > Create workbook rules if offered; otherwise insert a sheet manually and rename it exactly .Rules, including the leading dot. Keep it visible. Rules are fully supported only in English.

```text
EXCEL - CHAT ONLY:
Inspect this Lumina workbook. Identify the source table, fixed reporting date, status vocabulary and current owners. List workbook-specific conventions that belong in .Rules rather than account Personalisation. Do not edit.
```

### 2. Open data/Lumina_Workbook_Rules.txt. Copy its lines into .Rules column A with one heading or rule per cell; no data in other columns is required for recognition. Check source preservation, backlog/overdue/rate definitions, S$ display, colours, scope and controlled replacements.

```text
EXCEL - PLAN:
Review the visible .Rules column A for this Lumina workbook. Identify ambiguous instructions or conflicts with the actual source and Control. Propose concise corrections, keeping one idea per cell. Do not edit the source or invent precedence between rules, preferences and Skills.
```

### 3. After reviewing any correction, update only .Rules. Add a formula in the next empty column-A cell: ="Reporting date: "&TEXT(Control!B2,"yyyy-mm-dd"). Recalculate and confirm it displays Reporting date:2026-09-30. Copilot reads the formula result on the next prompt; this does not rewrite dashboard values by itself.

```text
EXCEL - ALLOW EDITING:
Apply only my reviewed .Rules corrections. Keep the sheet visible, one instruction per column-A cell, and retain the reporting-date formula. Preserve source data, Control and unrelated sheets.
```

### 4. Request a Rules_Test summary without restating the formatting rules. Check counts against Control, source references, displayed date/scope, S$ units and proposal wording. The known baseline is120 total,60 backlog,50 overdue and 30/48 on-time Closed.

```text
EXCEL - ALLOW EDITING:
Create Rules_Test for Lumina Living from tblHRCases using the visible workbook .Rules. Include total, backlog, overdue, on-time Closed rate and recorded cost with formula/source evidence. Show date and All scope. Keep source owners and values unchanged.
```

### 5. Save As Lumina_Rules_Shared_Copy.xlsx. Open the copy and confirm .Rules is still present and visible in column A; you have not exported your account preferences. If testing a hidden sheet, use only a sandbox copy, hide .Rules, record that hidden rules are not used, then unhide before continuing. Do not claim native rule use when the feature is unavailable.

```text
EXCEL - CHAT ONLY:
In this copied Lumina workbook, identify the visible .Rules instructions and reporting-date formula result. Explain which guidance travels with the workbook and which account preferences do not. Verify Rules_Test against Control without changing records.
```

### 6. Record the sheet name, visibility, column, formula result, actual output checks and copied-workbook check in data/templates/Customisation_Test_Log.csv. Carry the rules-enabled workbook forward. If a prompt, Skill and rule disagree, ask for clarification and verify the output; no universal precedence is assumed.

```text
EXCEL - CHAT ONLY:
Compare Personalisation, .Rules and a reusable Skill for Lumina reporting. Place currency preferences, this workbook’s backlog/date rules and the repeatable Pareto workflow in the right scope. Identify conflicts requiring clarification and the checks a person still must perform.
```

## Verification

- **Recognition:** Exactly .Rules; visible worksheet; instructions in column A, one idea per cell.
- **Formula rule:** Reporting-date formula recalculates and displays2026-09-30; no source values changed.
- **Output controls:** 120 total;60 backlog;50 overdue;30/48 on-time;S$35,827.50 at All scope.
- **Workbook copy:** Visible .Rules travels with the copy; account preferences are not exported.

## Expected Outcome

Lumina_Rules_Workbook.xlsx with visible .Rules column A, a checked Rules_Test output and a copied-workbook sharing check.

## Checkpoint

If you fell behind, use data/checkpoints/Lumina_Verified_Checkpoint.xlsx and data/checkpoints/Lumina_Verified_Snapshot.docx. Record checkpoint used in Prompt_Log; then perform this lab, rather than claiming the checkpoint as your output.

## Troubleshooting

| If this happens | Fix |
|---|---|
| Copilot cannot find the source | Use the app file picker to select the actual OneDrive file. A typed local path or a different app chat is not shared context. If needed copy only the verified snapshot into the current app. |
| A total disagrees with Control | Clear dashboard filters to All, check table extent and duplicate IDs, recalculate, then compare definitions and reporting date. Reconcile before continuing. |
| The named feature is missing | Confirm the correct assigned account, English display language and app version. Use the stated manual practice route; record feature unavailable. This is not evidence that a native skill ran. |

## Challenge

Repeat the task for one different department and explain how the filter scope changes the result. Keep the original verified output.

## Reflection

Which evidence proves the output is correct, and which decision still needs a person?

> Lumina Living Pte Ltd and all of its employees, HR cases and HR policies are fictional. Use the verified 120-case baseline and fixed reporting date 30 September 2026. Current case owners are evidence; proposals are not approved. The HR agent answers from approved knowledge only and never approves requests, sends messages or reveals another employee’s data.
