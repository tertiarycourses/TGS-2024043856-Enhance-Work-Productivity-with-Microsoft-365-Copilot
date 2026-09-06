# Lab 15: Create an Analysis-to-Deck Agent Pipeline

**Topic 04** · **Advanced Pipeline** · **Microsoft 365 Copilot + Analyst + PowerPoint + Excel** · **K4 · A4**

## Goal

Orchestrate intake, Excel analysis and a PowerPoint decision pack with human approval between stages.

## Expected output

Three-stage pipeline specification, analysis workbook, chart-led decision deck and approval log.

## Files

- `Lumina-Living-Lab-15.xlsx` — learner starter and control workbook
- `completed/Lumina-Living-Lab-15-completed.xlsx` — completed comparison copy
- `LAB-15-Instructions.pdf` — printable detailed guide
- Other Office files in this folder are specific to this lab

## Primary prompt

> For each Approved-for-Analysis queue item: validate the workbook, produce a descriptive and diagnostic analysis, identify three evidence-backed findings, create a six-slide decision deck with native charts, and stop at Ready for Review. Record sources, assumptions and exceptions. Do not publish or email the deck until a named reviewer approves it.

## Procedure

1. **Review Pipeline_Control and choose one Approved-for-Analysis item.**

   Confirm reviewer and required output.

2. **Define the three stages and their entry/exit criteria.**

   Stage 1 Validate; Stage 2 Analyse; Stage 3 Present.

3. **Run the analysis prompt with the attached workbook.**

   > For each Approved-for-Analysis queue item: validate the workbook, produce a descriptive and diagnostic analysis, identify three evidence-backed findings, create a six-slide decision deck with native charts, and stop at Ready for Review. Record sources, assumptions and exceptions. Do not publish or email the deck until a named reviewer approves it.

4. **Verify formulas, totals, segments and anomalies.**

   No deck generation until the analysis control is PASS.

5. **Create the six-slide PowerPoint with native charts.**

   Use takeaway titles and keep chart data editable.

6. **Record source ranges for every quantitative slide.**

   Complete Deck_Evidence.

7. **Run the reviewer checkpoint.**

   Reviewer can Approve, Return for correction or Reject.

8. **Update pipeline status without sending.**

   Stop at Ready for Review or Approved for Delivery.


## Acceptance test

The pipeline stops at review, the workbook reconciles, the deck has editable charts and every quantitative claim has a source range.

## Evidence

- Completed workbook with Prompt_Log and Evidence_Register
- App-specific artifact and a credential-safe screenshot
- Verification, exception and human-approval note

---

*Enhance Work Productivity with Microsoft 365 Copilot · TGS-2024043856 · Version v8.0 · © 2026 Tertiary Infotech Academy Pte Ltd*

## SharePoint agent extension

Continue with [SHAREPOINT-AGENT-EXTENSION.pdf](SHAREPOINT-AGENT-EXTENSION.pdf). The matching Markdown source, agent-configs.json and sharepoint-knowledge folder are included here. Keep using this lab’s original Excel evidence workbook.
