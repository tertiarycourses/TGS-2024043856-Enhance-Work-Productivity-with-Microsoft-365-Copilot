# Lab 7: Create and Apply a Custom Interactive Dashboard Skill

**Topic 3 · 30 minutes · v9.0 · 14 October 2026**

Create water-service-dashboard/SKILL.md for the Northstar maintenance workflow, install it in Excel, then invoke it to plan and build an interactive dashboard. Six KPIs and three charts share four filter selections. Workbook .Rules supplies scope, display and review constraints; the Skill supplies the repeatable method.

**Learning outcome:** LO3: evaluate Teams, Outlook and Microsoft 365 opportunities through a verified dashboard-to-presentation workflow.

**Expected outcome:** Northstar_Dashboard.xlsx with a Dashboard layout, six verified measures, three labelled charts and a measure dictionary ready for Lab 8 filters.

## Files

- [Instruction PDF](Lab-07-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-7)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/water-service-dashboard/SKILL.md` — Reviewed interactive dashboard Skill fallback

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Northstar-v9 is your own learner output folder.
- Verified clean table from earlier labs or supplied clean checkpoint.

## Steps

### 1. Open the synthetic source and data/templates/water-service-dashboard/SKILL.md. In Microsoft 365 Copilot on the web draft the full reusable Skill from this specification. Save it inside a matching water-service-dashboard folder and review every guard/measure before installation. Log the web prompt manually.

```text
MICROSOFT 365 COPILOT WEB:
Write complete water-service-dashboard SKILL.md with YAML name/description. Require actual tblWorkOrders and report date in Control!B2; read visible .Rules. Preserve source IDs/statuses/owners, Technicians, Control, .Rules, Prompt_Log, Pareto_* and unrelated sheets. Plan first and ask before replacing only named dashboard outputs; rerun without duplicated charts. Dashboard B2:B5 select Site, Job_Category, Status, Assigned_To with All bypasses and AND logic. B7 total, B8 backlog excluding Closed/Cancelled, B9 backlog Due_Date before Control!B2, B10 Closed, B11 on-time Closed_Date<=Due_Date among Closed only with N/A if none, B12 recorded Cost_SGD across selected statuses. Create three formula-backed editable status/category/site charts sharing the exact filter scope. Use structured references, not fixed120-row ranges, and white/navy/blue/teal workbook design. Baseline check at 2026-09-30 All:120 total,48 Closed,12 Cancelled,60 backlog,50 overdue,30/48 on-time,35827.50 cost. Verify site/no-Closed/no-row tests, source preservation and a separate two-row append sandbox with 122 total,49 Closed,61 backlog,51 overdue,31/49 on-time and 36227.50 cost. These are snapshot tests, not universal future figures. Ask for missing inputs; never approve assignments, infer causes/savings or send email. Return the entire file.
```

### 2. Use Excel Settings (...) > Manage plugins & skills > Custom skills > Open skills folder (Create OneDrive folder if needed). Copy the reviewed water-service-dashboard folder into that app-created location, Refresh, enable and verify its exact name in Choose plugins & skills. If unavailable, paste the entire reviewed Skill before each prompt, remove @water-service-dashboard and record Manual practice - native Skill unavailable. Installing maintenance-reporting or water-service-pareto does not install this distinct Skill.

### 3. Open data/templates/Northstar_Dashboard_Starter.xlsx and save as Northstar_Dashboard.xlsx in OneDrive. If continuing your own workbook, copy its CLEAN tblWorkOrders into the starter, keeping exact headers and table name; do not create a second table. The starter has a labelled blank Dashboard and four selection cells B2:B5, initially All.

```text
EXCEL - CHAT ONLY:
@water-service-dashboard Inspect this Northstar Water Services dashboard starter. Confirm tblWorkOrders, 120 unique IDs, reporting date 2026-09-30 and selection cells B2:B5 initially All. Explain which source and control sheets must remain intact. Report discrepancies before any edits.
```

### 4. Read Control and confirm the fixed reporting date. Ask for a visual plan before edits. Keep source, Checks and Prompt_Log separate from the Dashboard view. A dashboard is a decision interface: each visual should answer a maintenance question rather than decorate the page.

```text
EXCEL - PLAN:
@water-service-dashboard Plan Dashboard for Northstar maintenance at 2026-09-30. Use selection cells B2:B5 for Site, Job_Category, Status, Assigned_To, all initially All. Reserve B7 total orders, B8 backlog, B9 overdue backlog, B10 closed, B11 on-time closure rate, B12 Cost_SGD. Place three charts for status, category and site with labels, units and scope. Preserve source data.
```

### 5. Ask Copilot to insert formulas for the six measures using structured table references. For now all selectors are All; in Lab 8 the same formulas must honour the four filters. Verify the denominator and use N/A, not 0%, if no Closed rows remain.

```text
EXCEL - ALLOW EDITING:
@water-service-dashboard Build the planned six KPI formulas from tblWorkOrders. Backlog excludes Closed/Cancelled. Overdue also requires Due_Date < Control!B2. On-time rate counts Closed_Date <= Due_Date among Closed rows only, and shows N/A when none. Recorded cost sums Cost_SGD of all included statuses. Link to table columns, never a fixed 120-row range. Keep source data unchanged.
```

### 6. Add formula-backed chart summaries for the six statuses, five categories and five sites. Use bar/column charts: category and site are nominal groups; a line chart would imply an order that is not present. Label count axes and avoid 3-D effects. Ask the skill for consistent style if available.

```text
EXCEL - ALLOW EDITING:
@water-service-dashboard Create three editable bar or column charts using formula-backed summaries: work-order count by Status, by Job_Category and by Site. Each summary must reconcile to the total selected orders. Use white background, navy titles, blue/teal accents, readable labels and a visible reporting date. Do not use category counts as evidence of causes or use colour alone for status.
```

### 7. In Checks confirm sum of each chart’s categories equals 120 with All filters. Compare six KPIs to Control and record the on-time numerator/denominator. Add data/templates/Evidence_Register.csv entries for each chart and metric. If Copilot has used hard-coded numbers, replace them with formulas before Lab 8.

```text
EXCEL - CHAT ONLY:
@water-service-dashboard Reconcile the Northstar Water Services dashboard with Control at All selections. Compare all six KPIs and totals of the Status, Job_Category and Site charts. Flag hard-coded values, fixed row ranges, inconsistent scopes and any interpretation that treats job-category frequency as a cause. Do not edit.
```

### 8. Create a measure dictionary on a new Measures sheet: metric, business definition, formula, source fields, date rule, scope and limitation. Ask Copilot to explain formulas, then read one overdue example and one closed example from the source table yourself. Save the baseline dashboard with all filters All.

```text
EXCEL - CHAT ONLY:
@water-service-dashboard Explain each Dashboard measure in plain English, including terminal statuses, strict overdue date rule, closed-only SLA denominator and meaning of recorded cost. Give one source-row example for overdue and one for on-time closure; cite Work_Order_ID. Do not guess a root cause or financial saving.
```

## Verification

- **Baseline:** Total 120; backlog 60; overdue 50; closed 48.
- **SLA and cost:** 30/48 = 62.5%; S$35,827.50.
- **Chart reconciliation:** Three count summaries each total 120; formulas reference tblWorkOrders.
- **Decision design:** Measures dictionary and source/date visible; no unsupported cause claims.

## Expected Outcome

Northstar_Dashboard.xlsx with a Dashboard layout, six verified measures, three labelled charts and a measure dictionary ready for Lab 8 filters.

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
