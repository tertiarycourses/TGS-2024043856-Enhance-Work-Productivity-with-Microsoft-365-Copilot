# Lab 8: Use the Dashboard Skill for Filters, Refresh and Safe Reruns

**Topic 3 · 30 minutes · v9.0 · 14 October 2026**

Continue Lab 7 by making four dropdown selectors control every KPI and chart. Test a single site, a zero-denominator selection and a combined category/owner filter. Then append two synthetic work orders in a sandbox copy and prove the dashboard expands. Optional PivotTable slicers use one source and shared connections; the portable dropdown route is the required working dashboard.

**Learning outcome:** LO3: evaluate Teams, Outlook and Microsoft 365 opportunities through a verified dashboard-to-presentation workflow.

**Expected outcome:** Northstar_Dashboard.xlsx with four working filters plus Northstar_Dashboard_Refresh_Test.xlsx, filter evidence and a verified baseline snapshot for PowerPoint.

## Files

- [Instruction PDF](Lab-08-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-8)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/water-service-dashboard/SKILL.md` — Reviewed dashboard Skill for reruns

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Northstar-v9 is your own learner output folder.
- Lab 7 dashboard or supplied formula checkpoint.
- Lab 7 reviewed water-service-dashboard Skill installed or explicitly labelled manual route.

## Steps

### 1. Open your Lab 7 baseline dashboard. Rejoin using data/checkpoints/Northstar_Verified_Checkpoint.xlsx only if needed; record that it is an example formula dashboard. Set all four selections B2:B5 to All and confirm 120. Save baseline before creating any refresh-test copy.

```text
EXCEL - CHAT ONLY:
@water-service-dashboard Before testing filters, report the baseline Northstar Water Services dashboard source, date and scope. Confirm 120 unique work orders and all four selectors All. Identify the baseline file that must remain untouched when making the refresh-test copy.
```

### 2. Use Data > Data Validation > Allow List to set dropdowns on B2 Site, B3 Job_Category, B4 Status and B5 Assigned_To. Include All plus the source values, using Filter_Lists if supplied. Ask Copilot to apply all four selections to EVERY KPI and chart summary. A selection of All bypasses only that filter; selected dimensions combine with AND.

```text
EXCEL - PLAN:
@water-service-dashboard Make Dashboard B2:B5 control all six KPIs and three chart summaries with AND logic. All bypasses its dimension. Use COUNTIFS/SUMIFS or SUMPRODUCT with structured table references. Blank owner means unassigned and must not disappear from All. Keep N/A for no closed jobs.

EXCEL - ALLOW EDITING:
@water-service-dashboard Apply the reviewed filter plan and dropdown lists. Keep existing source rows and chart positions. Show the selected scope beside the reporting date and make all charts recalculate from the same selected rows.
```

### 3. Choose Woodlands Hub in B2 and leave other selectors All. Filter the source table to the same site and compare rows, backlog, overdue and cost. Use Data > Clear on source table afterwards; dashboard selectors and source AutoFilter are distinct mechanisms. Record evidence in data/templates/Filter_Test_Log.csv.

```text
EXCEL - CHAT ONLY:
@water-service-dashboard For the dashboard selection Site = Woodlands Hub and all other dimensions All, list the expected six KPI values from tblWorkOrders and verify each chart sum matches the selected total. Do not infer that filtering the worksheet automatically changes formula measures.
```

### 4. Set Status to New with other selectors All. Confirm zero closed -> N/A. Then set Site = Woodlands Hub, Job_Category = Leak Repair, Assigned_To = Daniel Lee, Status = All, a combination with no rows; total, backlog, overdue, closed and cost must be 0 and rate N/A. Reset all four to All and verify baseline controls. Optional: create PivotTables from one tblWorkOrders source, insert slicers, and use Slicer > Report Connections for every PivotTable; unconnected KPI cells are a defect.

```text
EXCEL - CHAT ONLY:
@water-service-dashboard Check two dashboard edge cases without changing source data: Status New with other selectors All; then Site Woodlands Hub, Job_Category Leak Repair, Assigned_To Daniel Lee, Status All. Verify zero closed gives N/A and no selected rows gives zero count/cost with N/A rate. Show how all charts follow the same selection. Restore all selectors to All.
```

### 5. Save a COPY as Northstar_Dashboard_Refresh_Test.xlsx. In the last row of tblWorkOrders press Tab to append, then enter the two rows from data/Refresh_Test_Rows.csv with real Excel dates (YYYY-MM-DD). WO-2026-0121 is Assigned, due 2026-09-29 and cost 150; WO-2026-0122 is Closed on time and cost 250. No existing IDs are edited.

### 6. Recalculate with all selections All. If using PivotTables also Data > Refresh All and inspect source extent. Verify total122, closed49, backlog61, overdue baseline+1, cost baseline+400 and on-time numerator baseline+1 over49. If formulas do not expand, fix structured references/table extent. Keep this sandbox copy as refresh evidence; do not use its figures in the baseline presentation.

```text
EXCEL - CHAT ONLY:
@water-service-dashboard Verify the sandbox append test for the two new work orders. Reconcile total 122, closed 49, backlog 61, overdue increased by 1, cost increased by S$400 and on-time numerator increased by 1. Confirm no original source record changed and all three charts total 122 with All selections. Compare original IDs, statuses, owners, dates and costs to the saved baseline; all original 120 rows must match.
```

### 7. In the sandbox workbook request a controlled Skill rerun after the append. Review the named replacement areas, then approve only those areas. Verify one dashboard, three charts, original 120 source rows unchanged and both legitimate new rows retained. Keep the 120-row baseline separate for Lab 9.

```text
EXCEL - PLAN:
@water-service-dashboard Refresh the existing dashboard for the sandbox 122-row table and same reporting date. Preserve all original source records, both new rows, .Rules, Pareto_* and unrelated sheets. Identify named output replacements and ask before editing; keep one dashboard and three charts.

EXCEL - ALLOW EDITING:
@water-service-dashboard Apply only the reviewed sandbox dashboard rerun. Retain the chosen source/date and make every KPI and chart follow the four filters; reconcile 122 total,61 backlog,51 overdue,49 Closed,31/49 on-time and S$36,227.50. Do not alter the untouched baseline workbook.
```

### 8. Return to the untouched 120-row Northstar_Dashboard.xlsx. Set selectors All and record a frozen evidence snapshot dated 2026-09-30 for Lab 9. Copy data/templates/Northstar_Operations_Brief_Template.docx to Northstar_Verified_Snapshot.docx in Word and insert the reviewed summary and chart values. Save chart images if needed with right-click chart > Save as Picture; the slide copy will be a static snapshot, not a live dashboard.

```text
WORD COPILOT:
Using only the verified baseline dashboard evidence I paste here, prepare the frozen Northstar Water Services presentation snapshot. Include reporting date, All scope, 120-row baseline, six KPIs, chart values, source workbook link and limitations. Exclude the 122-row sandbox. Keep proposed priorities separate from observed facts.
```

## Verification

- **Woodlands control:** Total 24; backlog 8; overdue 7; closed 16; cost S$6,668.50; on-time 10/16.
- **Interactive scope:** Changing any of four filters affects all six KPI measures and all chart counts.
- **Edge case:** No Closed -> N/A; no rows -> zero count/cost and N/A rate.
- **Refresh sandbox:** 122 total;49 closed;61 backlog;51 overdue;S$36,227.50;31/49 on-time.
- **Handoff baseline:** Return to 120-row untouched baseline; date and All scope recorded.

## Expected Outcome

Northstar_Dashboard.xlsx with four working filters plus Northstar_Dashboard_Refresh_Test.xlsx, filter evidence and a verified baseline snapshot for PowerPoint.

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
