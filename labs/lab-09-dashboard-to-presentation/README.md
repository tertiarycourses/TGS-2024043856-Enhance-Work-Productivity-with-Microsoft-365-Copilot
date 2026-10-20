# Lab 9: Turn Dashboard Evidence into a Management Story

**Topic 3 · 30 minutes · v9.2 · 20 October 2026**

Continue the baseline dashboard from Topic 3. Build a slide evidence register and a Word presentation brief before asking PowerPoint Copilot for an eight-slide management deck. The story connects HR-case status, department backlog, service delivery and assignment proposals to a specific decision; it does not introduce unsupported savings or causes.

**Learning outcome:** LO3: evaluate Teams, Outlook and Microsoft 365 opportunities through a verified dashboard-to-presentation workflow.

**Expected outcome:** Lumina_Presentation_Brief.docx, Lumina_HR_Management_Draft.pptx and a slide-by-slide evidence register tied to the 120-row dashboard snapshot.

## Files

- [Instruction PDF](Lab-09-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-9)
- `data/Lumina_HR_Cases.xlsx` — synthetic Lumina source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Lumina-HR-v9 is your own learner output folder.
- Verified Lab 8 baseline dashboard and frozen evidence snapshot.

## Steps

### 1. Open the untouched baseline Lumina_Dashboard.xlsx from Lab 8; confirm All selectors, total120 and report date2026-09-30. Do not use the 122-row sandbox. If needed use this lab’s checkpoint and record rejoin. Copy verified metric/chart values to data/templates/Slide_Evidence_Register.csv with source sheet/table, scope and date.

```text
EXCEL - CHAT ONLY:
For the untouched 120-row Lumina Living baseline dashboard at 2026-09-30, All selectors, return a presentation evidence table: six KPIs, backlog by department, status and request-type counts, unassigned backlog and relevant source references. Do not use the refresh-test copy or infer employee impact, policy breach, causes or savings.
```

### 2. Open data/templates/Lumina_Presentation_Brief_Template.docx in Word. Add the verified summary and chart values plus the OneDrive workbook link. Save as Lumina_Presentation_Brief.docx. Copilot must see selected files or pasted evidence; the link alone and the Excel conversation do not guarantee accessible context.

```text
WORD COPILOT:
Using this verified 120-row Lumina HR service snapshot, draft an eight-slide management presentation brief. For each slide give one claim headline, supporting measure/chart, source/date/scope, limitation and speaker note. Structure: overview, portfolio, department backlog, status/category mix, SLA/overdue, assignment/capacity, proposed actions/trade-offs, decision/next review. Do not invent causes, savings, approval or future dates; use UNKNOWN when absent.
```

### 3. Review the brief against source values. A bar showing counts by department is not a severity index; if you want backlog by department, count only nonterminal statuses. Correct any misleading headline and fill the slide evidence register. Suggested actions must cite a finding and say proposed.

```text
WORD COPILOT:
Review this eight-slide Lumina Living brief against the supplied baseline evidence. Check each headline has a supporting value, correct units, source/date/scope and an explicit limitation. Rewrite unsupported claims as questions or proposed actions. Do not change verified figures or invent approvals.
```

### 4. Open the supplied PowerPoint template, save as Lumina_HR_Management_Draft.pptx and open Copilot. Choose Create presentation from file if offered, or reference the Word brief while editing the existing deck. Select your reviewed OneDrive Word brief; direct workbook-to-deck creation is not assumed. Invoke @hr-case-reporting if available.

```text
POWERPOINT COPILOT:
@hr-case-reporting Create or update an eight-slide management presentation from the selected Lumina_Presentation_Brief.docx. Follow the existing white/navy/blue template. One evidence-based message per slide, short visible text, charts or tables for numerical evidence, source/as-at/scope in notes, and a final decision request. Keep values exact, and label all next actions as proposed. Do not add extra slides or invented facts.
```

### 5. Replace approximate or invented charts with your reviewed Excel charts: copy chart in Excel, then PowerPoint Home > Paste > Paste Special > Microsoft Excel Chart Object for an editable embedded chart when supported; otherwise paste a static image and label it snapshot. Embedded copies and images do not automatically follow the original workbook. Use direct verified values if a chart object is unsupported.

### 6. Inspect all eight slides and notes. Check chart title, axis, unit, status definition, date and scope. Each numeric headline must match one register row. Confirm the deck uses baseline120, not refresh122. Save for Lab 10; do not represent the draft as an approved plan.

```text
POWERPOINT COPILOT:
Audit the eight-slide Lumina Living management draft against the selected presentation brief and evidence register. Confirm baseline 120, source notes, chart labels and units, correct backlog exclusions and proposed-action wording. List needed corrections and preserve slide count; do not claim Excel charts update automatically.
```

## Verification

- **Evidence continuity:** Every deck figure maps to the 120-row Lab 8 baseline and slide evidence register.
- **Eight-slide narrative:** Observation -> implication -> proposed action -> decision; no invented cause/savings.
- **Chart semantics:** Backlog charts exclude Closed/Cancelled; embedded/image copies labelled snapshot.

## Expected Outcome

Lumina_Presentation_Brief.docx, Lumina_HR_Management_Draft.pptx and a slide-by-slide evidence register tied to the 120-row dashboard snapshot.

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
