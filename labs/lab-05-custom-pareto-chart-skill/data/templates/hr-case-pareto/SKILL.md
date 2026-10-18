---
name: hr-case-pareto
description: Create or refresh a verified Pareto Chart of Lumina HR-case overdue backlog by a requested grouping column.
---
# HR-case Pareto Chart
## Required inputs
Require the actual source table, report date, selected scope, grouping column and count metric. Ask for missing inputs. In this course use tblHRCases, Control!B2 (2026-09-30), all departments and overdue-backlog count grouped by Request_Type or Department. Do not assume access to a web chat or another workbook.
## Source and workbook rules
Read the visible .Rules worksheet in column A. Preserve HR_Cases, HR_Officers, Control, Prompt_Log, .Rules, source IDs, statuses, owners and unrelated sheets. Resolve conflicting requirements explicitly; do not promise a universal precedence order or treat instructions as a security boundary.
## Method
Count rows where Status is neither Closed nor Cancelled and Due_Date is strictly before the report date. Group by the requested column. Sort count descending, then group label alphabetically for ties. Build a formula-backed Count, Cumulative_Count, Share and Cumulative_Percent summary. The last cumulative percentage is 100% when the total is positive; for zero total show N/A and explain there is no Pareto distribution.
## Output
Create only Pareto_<grouping column>, for example Pareto_Request_Type or Pareto_Department. Ask before replacing an existing matching output. Rebuild that output after review without duplicating summaries or charts. Preserve all other sheets and source records.
Create an editable Excel combo chart: descending count columns on the left axis and cumulative percentage line on the right axis fixed at 0%-100%. Label both axes, grouping, metric, date and scope. If the combo UI is unavailable, supply the correct summary and explain the manual combo-chart route; do not claim the chart exists.
## Checks
Reconcile the summary count to the eligible source rows. Check stable tie ordering, monotonic cumulative percentages and final 100%. Identify the first category set that reaches at least 80%; do not force a literal 80/20 split. Counts show contribution, not root cause, policy priority or approved actions. A rerun must preserve source records and unrelated outputs.
