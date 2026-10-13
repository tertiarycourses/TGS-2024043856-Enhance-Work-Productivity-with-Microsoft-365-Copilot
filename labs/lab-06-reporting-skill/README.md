# Lab 6: Create, Use and Improve the Maintenance Reporting Skill

**Topic 2 · 30 minutes · v9.0 · 14 October 2026**

Reuse the Skill-authoring and installation method from Lab 5 to create maintenance-reporting. Apply it in Excel and PowerPoint, test missing inputs and a controlled rerun, then refine v2 using actual evidence. The supplied reviewed template supports rejoining; it is not proof of native execution.

**Learning outcome:** LO2: plan a controlled transition using Personalisation, .Rules and reusable Skills.

**Expected outcome:** Northstar_Skill_Report.xlsx with Maintenance_Summary and Assignment_Proposals, Northstar_Skill_Update.pptx, SKILL.md v2 and a before/after improvement log.

## Files

- [Instruction PDF](Lab-06-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-6)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/maintenance-reporting/SKILL.md` — Reviewed reporting Skill fallback
- `data/templates/Transition_Plan.csv` — LO2 controlled transition checkpoint

## Prerequisites

- Labs 1–2 verified brief and four-slide update; Lab 5 Skill-authoring method.

## Steps

### 1. Use Microsoft 365 Copilot on the web to draft maintenance-reporting/SKILL.md from the complete specification below. Review it against data/templates/maintenance-reporting/SKILL.md, save the complete file as v1 in your Northstar-v9 output folder, then install it using the same Excel app-created custom Skills folder and Refresh route practised in Lab5. If a native Skill menu is missing, use the full reviewed file as pasted instructions, remove @mention and label the route manual.

```text
MICROSOFT 365 COPILOT WEB:
Write complete maintenance-reporting SKILL.md with YAML name/description. Require actual tblWorkOrders or a verified Word snapshot, report date and filter scope. Respect visible .Rules. Define backlog, overdue and Closed-only on-time rate. Preserve IDs/statuses/current owners; keep assignment proposals separate and approvals UNKNOWN. Create a verified Excel summary and improve a supplied four- or eight-slide PowerPoint report from selected evidence. Ask for missing inputs and before replacing only named outputs; rerun without duplicates or source changes. Keep the existing design and source/date notes. Never send email or approve assignments. Return the entire file.
```

### 2. Copy the Lab 6 reviewed SKILL.md to your output folder and retain v1. Open this lab’s clean workbook or your Lab 1 cleaned workbook. Save as Northstar_Skill_Report.xlsx. Read Technicians: primary category and available hours are synthetic planning inputs, not approvals. Check that your skill is enabled in Excel.

### 3. Invoke the skill in Plan or Chat only, review its proposed output boundaries, then allow editing. Inspect the resulting formulas and charts. Summary counts must reconcile to Control, and the source table must remain 120 unique records.

```text
EXCEL - PLAN:
@maintenance-reporting Build Maintenance_Summary for tblWorkOrders at 2026-09-30 with all filters All. Include total, closed, cancelled, backlog, overdue, on-time closed rate and recorded cost; show formulas and source scope. Plan first. Preserve source records.

EXCEL - ALLOW EDITING:
Apply that reviewed summary plan. Add Assignment_Proposals for unassigned backlog only. Use tblTechnicians primary category and available hours as planning inputs; show category/capacity checks, current owner and proposed owner separately. Leave manager decision UNKNOWN. Do not change Assigned_To.
```

### 4. Check the unassigned backlog count against Control. A technician with the same category may still lack usable capacity: use available hours minus known proposed hours, flag conflicts, and do not convert a suggestion into confirmed assignment. Export your verified summary into the Word snapshot template, preserving measures and date.

```text
EXCEL - CHAT ONLY:
@maintenance-reporting Review Assignment_Proposals against tblWorkOrders and tblTechnicians. Check each suggested owner has the matching water-service job category, capacity limitations are visible and original Assigned_To values are unchanged. Leave manager approval UNKNOWN; do not assign or schedule a technician.
```

### 5. In PowerPoint select the reviewed Word snapshot and open the four-slide update from Lab2 or data/checkpoints/Northstar_Initial_Update_Checkpoint.pptx. Use Copilot > + > Choose skills > Manage skills > Add skill to upload the reviewed maintenance-reporting file, or use the app’s own supported Skills folder. Verify it in PowerPoint separately from Excel. If missing, paste the complete reviewed Skill plus snapshot as manual instructions and remove @mention. Apply the following refinement after review.

```text
POWERPOINT COPILOT:
@maintenance-reporting Improve this existing four-slide Northstar update from the selected verified Word snapshot. Preserve slide count, all values and source/date/scope notes; use clear claim headlines and the existing design. Keep assignment suggestions explicitly proposed and do not assume access to Excel chat.
```

### 6. Create a new EMPTY workbook with no table, open a fresh Copilot chat and run a missing-input test for a different reporting period with no source selected. A proper skill asks for source/date/scope rather than inventing metrics. If it guesses, record the failure and revise the skill’s input guard. Return to Northstar_Skill_Report.xlsx and Save As Northstar_Skill_Rerun_Test.xlsx. Run the second summary request in this copy of the report workbook, not in the empty workbook; only named outputs may be replaced after review, with no duplicated source or output sheets. Compare a before/after copy of Work_Orders sorted by Work_Order_ID for status, owner, dates and cost; every original source value must match.

```text
EXCEL - CHAT ONLY:
@maintenance-reporting Prepare my next maintenance report. I need a DIFFERENT reporting period from the course example and have not supplied any source, date or scope. This empty workbook contains no work orders. Tell me what you need; do not invent data.

EXCEL - PLAN:
@maintenance-reporting Rebuild the existing Maintenance_Summary for the same table, date and scope. Describe what will be replaced, ask before replacement and keep source/unrelated sheets. Do not duplicate outputs.
```

### 7. In a plain text editor improve SKILL.md: require an input guard, category/capacity evidence, source provenance per claim and a clear rerun rule. Retain YAML name maintenance-reporting and add a body version note v2. Re-upload/Refresh in BOTH Excel and PowerPoint. Record actual before/after changes, or already present - retained for safeguards that your v1 already contains. Do not fabricate differences. Rerun the smoke tests and compare values. If using the manual route, replace the pasted instructions in both apps.

```text
MICROSOFT 365 COPILOT WEB:
Improve this supplied maintenance-reporting skill to v2 using only my actual smoke-test and rerun findings pasted here. Add explicit missing-input and no-duplicate-output guards. Keep Excel source and current owners protected. Return the complete revised SKILL.md and a short before/after change log; do not fabricate test evidence.
```

### 8. Complete Transition_Plan.csv for Baseline, Pilot, Staff readiness and Controlled rollout. Include a .Rules or Skill rerun test, success measure and last-passing rollback record.

## Verification

- **Source preserved:** 120 unique orders; current owner/status unchanged.
- **Skill outputs:** Backlog 60; overdue 50; on-time closed 30/48; cost S$35,827.50.
- **Improvement evidence:** Input guard and rerun tested; v1/v2 retained; PowerPoint four-slide output accurate.
- **LO2 checkpoint:** Four transition stages have owners, evidence, success measures and rollback triggers.

## Expected Outcome

Northstar_Skill_Report.xlsx with Maintenance_Summary and Assignment_Proposals, Northstar_Skill_Update.pptx, SKILL.md v2 and a before/after improvement log.

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
