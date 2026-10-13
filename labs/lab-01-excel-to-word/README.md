# Lab 1: Prepare Work Orders and Draft the Operations Brief

**Topic 1 · 30 minutes · v9.0 · 14 October 2026**

You are Northstar Water Services’ maintenance coordinator. A Q3 export contains repeated IDs and inconsistent category labels. You will clean a copy in Excel, reconcile its controls, and use the verified result to draft a Word operations brief. The same site, status and assignment definitions underpin every later report.

**Learning outcome:** LO1: predict and mitigate integration challenges through verified cross-app grounding and handoffs.

**Expected outcome:** Northstar_Clean_Work_Orders.xlsx and Northstar_Operations_Brief.docx, with reconciled counts, reporting scope and a source register.

## Files

- [Instruction PDF](Lab-01-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-1)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Northstar-v9 is your own learner output folder.

## Steps

### 1. Copy data/Northstar_Work_Orders.xlsx to your OneDrive Northstar-v9 folder as Northstar_Clean_Work_Orders.xlsx. Open it in Excel, set Formulas > Calculation Options > Automatic, and read About_This_Data and Control. The workbook is the deliberately dirty 122-row input; the supplied CSV is a clean reference and must not replace the cleaning exercise. Open Copilot from Home > Copilot.

```text
EXCEL - CHAT ONLY:
Read About_This_Data and Control for Northstar Water Services. Explain what one water-pipe service work order represents, the reporting date, the five job categories and how current owners differ from proposed owners. Do not edit or infer customer impacts.
```

### 2. Use Chat only to inspect the named table before making changes. Record row count and the two exact repeated IDs. A Work_Order_ID is the row grain; do not count repeated export records twice.

```text
EXCEL - CHAT ONLY:
Inspect tblWorkOrders. Report row count, duplicate Work_Order_ID values, category spelling variants and missing Assigned_To. Do not edit. Treat 2026-09-30 as the fixed reporting date.
```

### 3. Choose Plan if available. Read the proposed cleaning plan before using Allow editing. The duplicates are exact repeated export records: keep one per ID. Trim and standardise category labels to Leak Repair, Valve Repair, Pipe Replacement, Pump Service, Meter Service; preserve missing owners and all unique source values. Save a copy of the raw sheet before the change.

```text
EXCEL - PLAN:
Plan to retain an untouched Raw_Export copy, remove only exact duplicate records by Work_Order_ID, and standardise category spelling in tblWorkOrders. Keep dates, statuses and assignments. Ask if two records with one ID differ.

EXCEL - ALLOW EDITING:
Apply the reviewed plan. Keep one identical record per repeated ID. Do not guess missing owners. Reconcile the cleaned table against Control.
```

### 4. Add a Checks sheet or use the supplied one. Ask for formulas, then inspect the table and formulas yourself. Overdue excludes Closed and Cancelled and uses strictly earlier than the fixed date, so a due-today job is not overdue. Copy verified values to data/templates/Evidence_Register.csv.

```text
EXCEL - ALLOW EDITING:
In Checks calculate total rows, closed, cancelled, backlog, overdue backlog, unassigned backlog and total Cost_SGD for tblWorkOrders. Use Control!B2 as reporting date. Define backlog as Status neither Closed nor Cancelled. Add the identity total = closed + cancelled + backlog. Do not change source data.
```

### 5. Open data/templates/Northstar_Operations_Brief_Template.docx in Word and save as Northstar_Operations_Brief.docx in OneDrive. In Copilot select the verified source file using Reference a file or /. If Word cannot use the workbook, copy your verified evidence table plus data/Northstar_Maintenance_Context.txt into the document and select that text; do not imply Word reads the Excel chat.

```text
WORD COPILOT:
Draft a one-page Northstar operations brief from the verified evidence supplied here. Include reporting scope/date, backlog and overdue findings, current assignment issues, proposed next actions and open questions. Keep observed facts separate from proposals. Preserve numbers and definitions. Use UNKNOWN for causes, approvals or capacity decisions not evidenced.
```

### 6. Compare every number and work-order ID in the Word brief to Checks and the evidence register. Add the OneDrive source link and all-filters scope. Log the Word prompt manually in Excel Prompt_Log because Excel cannot access the Word conversation. Save the cleaned workbook and brief for Lab 2.

```text
WORD COPILOT:
Audit this Northstar Water Services operations brief against the verified evidence table I supply. Return a discrepancy list for counts, cost, reporting scope, overdue definition and assignment claims. Identify missing source links as UNKNOWN. Do not change facts or approve work.
```

## Verification

- **Clean table:** 120 unique Work_Order_ID rows; five canonical job categories.
- **Portfolio identity:** 120 = 48 Closed + 12 Cancelled + 60 backlog.
- **Evidence handoff:** Overdue 50; unassigned backlog 6; total cost S$35,827.50. Word agrees with Excel.
- **No guessed owner:** Blank assignments remain blank; proposals labelled unapproved.

## Expected Outcome

Northstar_Clean_Work_Orders.xlsx and Northstar_Operations_Brief.docx, with reconciled counts, reporting scope and a source register.

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
