# Lab 8: Use the Dashboard Skill for Filters, Refresh and Safe Reruns

**Topic 3 · 30 minutes · v9.1 · 18 October 2026**

Continue Lab 7 by making four dropdown selectors control every KPI and chart. Test a single department, a zero-denominator selection and a combined category/owner filter. Then append two synthetic HR cases in a sandbox copy and prove the dashboard expands. Optional PivotTable slicers use one source and shared connections; the portable dropdown route is the required working dashboard.

**Learning outcome:** LO3: evaluate Teams, Outlook and Microsoft 365 opportunities through a verified dashboard-to-presentation workflow.

**Expected outcome:** Lumina_Dashboard.xlsx with four working filters plus Lumina_Dashboard_Refresh_Test.xlsx, filter evidence and a verified baseline snapshot for PowerPoint.

## Files

- [Instruction PDF](Lab-08-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-8)
- `data/Lumina_HR_Cases.xlsx` — synthetic Lumina source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/hr-case-dashboard/SKILL.md` — Reviewed dashboard Skill for reruns

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Lumina-HR-v9 is your own learner output folder.
- Lab 7 dashboard or supplied formula checkpoint.
- Lab 7 reviewed hr-case-dashboard Skill installed or explicitly labelled manual route.

## Steps

### 1. Open your Lab 7 baseline dashboard. Rejoin using data/checkpoints/Lumina_Verified_Checkpoint.xlsx only if needed; record that it is an example formula dashboard. Set all four selections B2:B5 to All and confirm 120. Save baseline before creating any refresh-test copy.

```text
EXCEL - CHAT ONLY:
@hr-case-dashboard Before testing filters, report the baseline Lumina Living dashboard source, date and scope. Confirm 120 unique HR cases and all four selectors All. Identify the baseline file that must remain untouched when making the refresh-test copy.
```

### 2. Use Data > Data Validation > Allow List to set dropdowns on B2 Department, B3 Request_Type, B4 Status and B5 Assigned_To. Include All plus the source values, using Filter_Lists if supplied. Ask Copilot to apply all four selections to EVERY KPI and chart summary. A selection of All bypasses only that filter; selected dimensions combine with AND.

```text
EXCEL - PLAN:
@hr-case-dashboard Make Dashboard B2:B5 control all six KPIs and three chart summaries with AND logic. All bypasses its dimension. Use COUNTIFS/SUMIFS or SUMPRODUCT with structured table references. Blank owner means unassigned and must not disappear from All. Keep N/A for no closed cases.

EXCEL - ALLOW EDITING:
@hr-case-dashboard Apply the reviewed filter plan and dropdown lists. Keep existing source rows and chart positions. Show the selected scope beside the reporting date and make all charts recalculate from the same selected rows.
```

### 3. Choose Retail Sales in B2 and leave other selectors All. Filter the source table to the same department and compare rows, backlog, overdue and cost. Use Data > Clear on source table afterwards; dashboard selectors and source AutoFilter are distinct mechanisms. Record evidence in data/templates/Filter_Test_Log.csv.

```text
EXCEL - CHAT ONLY:
@hr-case-dashboard For the dashboard selection Department = Retail Sales and all other dimensions All, list the expected six KPI values from tblHRCases and verify each chart sum matches the selected total. Do not infer that filtering the worksheet automatically changes formula measures.
```

### 4. Set Status to New with other selectors All. Confirm zero closed -> N/A. Then set Department = Retail Sales, Request_Type = Leave Request, Assigned_To = Daniel Lee, Status = All, a combination with no rows; total, backlog, overdue, closed and cost must be 0 and rate N/A. Reset all four to All and verify baseline controls. Optional: create PivotTables from one tblHRCases source, insert slicers, and use Slicer > Report Connections for every PivotTable; unconnected KPI cells are a defect.

```text
EXCEL - CHAT ONLY:
@hr-case-dashboard Check two dashboard edge cases without changing source data: Status New with other selectors All; then Department Retail Sales, Request_Type Leave Request, Assigned_To Daniel Lee, Status All. Verify zero closed gives N/A and no selected rows gives zero count/cost with N/A rate. Show how all charts follow the same selection. Restore all selectors to All.
```

### 5. Save a COPY as Lumina_Dashboard_Refresh_Test.xlsx. In the last row of tblHRCases press Tab to append, then enter the two rows from data/Refresh_Test_Rows.csv with real Excel dates (YYYY-MM-DD). HR-2026-0121 is Assigned, due 2026-09-29 and cost 150; HR-2026-0122 is Closed on time and cost 250. No existing IDs are edited.

### 6. Recalculate with all selections All. If using PivotTables also Data > Refresh All and inspect source extent. Verify total122, closed49, backlog61, overdue baseline+1, cost baseline+400 and on-time numerator baseline+1 over49. If formulas do not expand, fix structured references/table extent. Keep this sandbox copy as refresh evidence; do not use its figures in the baseline presentation.

```text
EXCEL - CHAT ONLY:
@hr-case-dashboard Verify the sandbox append test for the two new HR cases. Reconcile total 122, closed 49, backlog 61, overdue increased by 1, cost increased by S$400 and on-time numerator increased by 1. Confirm no original source record changed and all three charts total 122 with All selections. Compare original IDs, statuses, owners, dates and costs to the saved baseline; all original 120 rows must match.
```

### 7. In the sandbox workbook request a controlled Skill rerun after the append. Review the named replacement areas, then approve only those areas. Verify one dashboard, three charts, original 120 source rows unchanged and both legitimate new rows retained. Keep the 120-row baseline separate for Lab 9.

```text
EXCEL - PLAN:
@hr-case-dashboard Refresh the existing dashboard for the sandbox 122-row table and same reporting date. Preserve all original source records, both new rows, .Rules, Pareto_* and unrelated sheets. Identify named output replacements and ask before editing; keep one dashboard and three charts.

EXCEL - ALLOW EDITING:
@hr-case-dashboard Apply only the reviewed sandbox dashboard rerun. Retain the chosen source/date and make every KPI and chart follow the four filters; reconcile 122 total,61 backlog,51 overdue,49 Closed,31/49 on-time and S$36,227.50. Do not alter the untouched baseline workbook.
```

### 8. Return to the untouched 120-row Lumina_Dashboard.xlsx. Set selectors All and record a frozen evidence snapshot dated 2026-09-30 for Lab 9. Copy data/templates/Lumina_HR_Service_Brief_Template.docx to Lumina_Verified_Snapshot.docx in Word and insert the reviewed summary and chart values. Save chart images if needed with right-click chart > Save as Picture; the slide copy will be a static snapshot, not a live dashboard.

```text
WORD COPILOT:
Using only the verified baseline dashboard evidence I paste here, prepare the frozen Lumina Living presentation snapshot. Include reporting date, All scope, 120-row baseline, six KPIs, chart values, source workbook link and limitations. Exclude the 122-row sandbox. Keep proposed priorities separate from observed facts.
```

## Verification

- **Retail Sales control:** Total 24; backlog 8; overdue 7; closed 16; cost S$6,668.50; on-time 10/16.
- **Interactive scope:** Changing any of four filters affects all six KPI measures and all chart counts.
- **Edge case:** No Closed -> N/A; no rows -> zero count/cost and N/A rate.
- **Refresh sandbox:** 122 total;49 closed;61 backlog;51 overdue;S$36,227.50;31/49 on-time.
- **Handoff baseline:** Return to 120-row untouched baseline; date and All scope recorded.

## Expected Outcome

Lumina_Dashboard.xlsx with four working filters plus Lumina_Dashboard_Refresh_Test.xlsx, filter evidence and a verified baseline snapshot for PowerPoint.

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
