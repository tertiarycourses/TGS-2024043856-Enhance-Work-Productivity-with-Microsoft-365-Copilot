# Lab 5: Create a Custom Pareto Chart Skill and Apply It

**Topic 2 · 30 minutes · v9.1 · 18 October 2026**

Author hr-case-pareto/SKILL.md with Copilot, install it in Excel and apply it to the same overdue HR-case queue. Build a descending count chart plus cumulative-percentage line, then check a controlled rerun and a second grouping. Contribution analysis does not establish root cause or force an 80/20 split.

**Learning outcome:** LO2: plan a controlled transition using Personalisation, .Rules and reusable Skills.

**Expected outcome:** hr-case-pareto/SKILL.md, Lumina_Pareto.xlsx with Pareto_Request_Type and Pareto_Department, and a verified rerun record.

## Files

- [Instruction PDF](Lab-05-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-5)
- `data/Lumina_HR_Cases.xlsx` — synthetic Lumina source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/hr-case-pareto/SKILL.md` — Reviewed Pareto Skill fallback

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Lumina-HR-v9 is your own learner output folder.
- Lab 4 visible .Rules and clean source; assigned Excel Skill feature checked.

## Steps

### 1. Open your rules-enabled workbook from Lab 4 or this lab’s clean rules-enabled data/Lumina_HR_Cases.xlsx. Save as Lumina_Pareto.xlsx. Read data/Pareto_Expected_Controls.json and the supplied Skill template before drafting your own file. Work only with synthetic data.

```text
EXCEL - CHAT ONLY:
For tblHRCases at Control!B2, All departments, count overdue backlog by Request_Type: Status neither Closed nor Cancelled and Due_Date strictly before the reporting date. Show category counts and total before charting. Preserve all records.
```

### 2. In Microsoft 365 Copilot on the web at https://copilot.cloud.microsoft, provide this self-contained specification. Copy the complete response into a plain-text editor and save UTF-8 SKILL.md inside a matching hr-case-pareto folder. Compare it to data/templates/hr-case-pareto/SKILL.md. If short of time, use the reviewed supplied file and record that choice.

```text
MICROSOFT 365 COPILOT WEB:
Write a complete SKILL.md named hr-case-pareto for a recurring HR service report. Require YAML name and description, actual source table, reporting date, scope, count metric and grouping column. Source tblHRCases has Case_ID, Request_Type, Department, Status and Due_Date. Overdue backlog excludes Closed/Cancelled and has Due_Date before the supplied date. Read visible workbook .Rules; preserve source IDs/statuses/owners and unrelated sheets. Count by grouping, sort count descending then label alphabetically for ties, and create formula-backed count, cumulative count, share and cumulative percentage. Build an editable combo chart: count columns and cumulative line on a 0%-100% right axis. Output only Pareto_<grouping column>; ask before replacing the matching output, rerun without duplicates, and leave zero-total percentages N/A. Verify counts, stable ties and final 100%; do not infer causes or force 80/20. Return the entire file.
```

### 3. In Excel use Copilot Settings (...) > Manage plugins & skills > Custom skills > Create OneDrive folder if needed > Open skills folder. Copy hr-case-pareto/SKILL.md into that app-created location, Refresh and enable it. Verify the name using Choose plugins & skills or @mention. If unavailable, paste the complete reviewed Skill before each request, remove @hr-case-pareto and record Manual practice - native Skill unavailable. Log web authoring manually.

### 4. Request a plan before building. Confirm the eligible total 50 and the five ordered category counts. After review, apply the Skill. Inspect Pareto_Request_Type, formulas, axes and source preservation; copying a static image does not meet the editable-chart goal.

```text
EXCEL - PLAN:
@hr-case-pareto Plan an overdue-backlog Pareto Chart by Request_Type from tblHRCases at 2026-09-30, All departments. Follow visible .Rules. Explain summary formulas, descending counts, alphabetical ties, cumulative percentages and the named output to create. Do not edit yet.

EXCEL - ALLOW EDITING:
@hr-case-pareto Apply the reviewed Request_Type Pareto plan. Create Pareto_Request_Type with a formula-backed summary and editable count-column/cumulative-percent-line combo chart. Keep source data and unrelated sheets unchanged.
```

### 5. Check counts against the supplied controls. Verify cumulative percentages 36%,60%,76%,92%,100% and two equal8-count categories in alphabetical order. The first four categories reach at least80%; do not call this proof that20% of categories cause80% of failures. If combo chart UI is absent, select the summary and use Insert > Combo > Custom Combination: Count clustered column, Cumulative_Percent line on secondary axis, right bounds 0 and 1; label both axes. Record a missing feature honestly.

```text
EXCEL - CHAT ONLY:
Verify Pareto_Request_Type against eligible source rows. Check total 50, descending counts, alphabetical tie order, cumulative percentages 36/60/76/92/100%, final 100% and labelled dual axes. State which category set first reaches 80%, and why this is contribution rather than a causal diagnosis.
```

### 6. Save a sandbox copy, rerun the same grouping after approving replacement of only Pareto_Request_Type, and compare source IDs/statuses/owners and sheet/chart counts. Then apply the Skill to Department to produce a distinct Pareto_Department output. Keep both reviewed summaries for later decision evidence.

```text
EXCEL - PLAN:
@hr-case-pareto Refresh the existing Pareto_Request_Type for the same source, date and All scope. Identify exactly what will be replaced and ask before replacement. Preserve every unrelated sheet and do not duplicate charts.

EXCEL - ALLOW EDITING:
@hr-case-pareto After the approved category rerun, create a separate overdue-backlog Pareto_Department for the same source/date/scope. Preserve Pareto_Request_Type and reconcile the new summary to 50 overdue cases.
```

## Verification

- **Eligible population:** Overdue backlog50; no Closed or Cancelled records included.
- **Category counts:** Payroll Query=18; Benefits Claim=12; Leave Request=8; Training Request=8; Onboarding=4
- **Cumulative percentages:** 36%,60%,76%,92%,100%; Leave Request precedes Training Request in the8-count tie.
- **Chart and rerun:** Editable columns plus cumulative line; right axis0%-100%; matching output replaced only after review, without duplicates.
- **Source and interpretation:** 120 original records preserved; Department grouping also totals50; no invented root cause.

## Expected Outcome

hr-case-pareto/SKILL.md, Lumina_Pareto.xlsx with Pareto_Request_Type and Pareto_Department, and a verified rerun record.

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
