# Lab 06: Build and Audit Excel Formulas with Copilot

**Topic 02** · **Foundation** · **Excel + Copilot** · **K3 · A2**

## Goal

Use Copilot to propose calculated columns while retaining formula transparency and controls.

## Expected output

Formula-driven campaign table with revenue, margin, conversion, status and error controls.

## Files

- `Lumina-Living-Lab-06.xlsx` — learner starter and control workbook
- `completed/Lumina-Living-Lab-06-completed.xlsx` — completed comparison copy
- `LAB-06-Instructions.pdf` — printable detailed guide
- Other Office files in this folder are specific to this lab

## Primary prompt

> In the Campaign_Data table, propose formulas for Revenue, Margin, Margin_Percent, Conversion_Rate and Target_Status. Use structured references, make divisions zero-safe, and reference thresholds from the Assumptions sheet. Explain each formula and identify two edge cases to test before applying it.

## Procedure

1. **Convert the Campaign_Data range to an Excel Table.**

   Name it tblCampaign and confirm one header row.

2. **Inspect blanks, zeros and unexpected types.**

   Record exceptions before generating formulas.

3. **Submit the formula prompt.**

   > In the Campaign_Data table, propose formulas for Revenue, Margin, Margin_Percent, Conversion_Rate and Target_Status. Use structured references, make divisions zero-safe, and reference thresholds from the Assumptions sheet. Explain each formula and identify two edge cases to test before applying it.

4. **Apply one formula at a time and inspect the full column.**

   Reject any formula with hardcoded thresholds or mismatched row references.

5. **Test zero impressions, zero revenue and negative cost.**

   Use a copy of the test rows; do not corrupt the source table.

6. **Create a Controls sheet.**

   Count blanks, formula errors, negative values and rows with Review status.

7. **Save the audited workbook.**

   All controls must show PASS or an owned exception.


## Acceptance test

All derived columns use auditable formulas, zero denominators are handled intentionally and the Controls sheet contains no unexplained errors.

## Evidence

- Completed workbook with Prompt_Log and Evidence_Register
- App-specific artifact and a credential-safe screenshot
- Verification, exception and human-approval note

---

*Enhance Work Productivity with Microsoft 365 Copilot · TGS-2024043856 · Version v8.0 · © 2026 Tertiary Infotech Academy Pte Ltd*
