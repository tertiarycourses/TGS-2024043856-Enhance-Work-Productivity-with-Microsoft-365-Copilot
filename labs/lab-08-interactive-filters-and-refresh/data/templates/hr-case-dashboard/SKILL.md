---
name: hr-case-dashboard
description: Build or refresh an interactive Lumina HR-case dashboard with source-linked measures, four shared filters and verified charts.
---
# Interactive HR-case dashboard
## Inputs and context
Require the actual tblHRCases source, report date in Control!B2, requested output workbook and filter scope. Ask when inputs are absent. Read visible .Rules column A. Do not assume access to a web chat or an Excel conversation from another file.
## Preserve and review
Preserve HR_Cases, tblHRCases, source IDs/statuses/current owners, HR_Officers, Control, .Rules, Prompt_Log, Pareto_* and unrelated sheets. Plan before editing. Create or replace only Dashboard, Dashboard_Summaries, Filter_Lists and the specifically reviewed verification cells. Ask before replacing existing outputs. Retain one dashboard and one chart per requested visual on reruns.
## Interaction contract
Dashboard B2:B5 are Department, Request_Type, Status and Assigned_To, initially All. All bypasses that dimension; all other selections combine with AND logic. Blank owner records remain included by All. Use validation dropdown lists and structured references; worksheet AutoFilter alone is not proof that KPI formulas change.
## Measures
B7 total selected HR cases. B8 backlog: Status neither Closed nor Cancelled. B9 overdue backlog: backlog plus Due_Date strictly earlier than Control!B2. B10 Closed count. B11 on-time closed rate: selected Closed_Date <= Due_Date among Closed rows only; N/A when Closed count is zero. B12 recorded Cost_SGD across every selected status; it is not a budget or saving.
## Visuals
Build three editable status, request-type and department bar/column charts from formula-backed summaries of the same selected rows. Each chart total equals B7. Respect workbook .Rules formatting, visible scope/date, white/navy/blue/teal design and labels/units. Use references that expand with tblHRCases, never fixed 120-row ranges.
## Verification and refresh
At the course baseline (2026-09-30, All): total120, Closed48, Cancelled12, backlog60, overdue50, on-time30/48 and recorded cost35827.50. These are checks for this synthetic snapshot, not universal future values. Test a department, no Closed rows and no selected rows. Append only the supplied two test rows in a separate sandbox: total122, Closed49, backlog61, overdue51, on-time31/49 and recorded cost36227.50. Compare all original120 records to the saved baseline and reconcile every chart. Return to the untouched120-row baseline for PowerPoint.
## Boundaries
Do not approve assignments, invent causes/employee impacts/savings, send email or claim native Skill execution without observed evidence. The PowerPoint handoff is a dated static snapshot, not an automatically linked dashboard.
