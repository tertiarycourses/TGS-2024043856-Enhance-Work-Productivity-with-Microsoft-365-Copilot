# Lab 07: Run Deep Descriptive and Diagnostic Analysis in Excel

**Topic 02** · **Intermediate** · **Excel + Copilot** · **K3 · A2**

## Goal

Move from summary statistics to segmented drivers, anomalies and evidence-backed explanations.

## Expected output

Diagnostic workbook with KPI summary, segment analysis, anomaly log and management findings.

## Files

- `Lumina-Living-Lab-07.xlsx` — learner starter and control workbook
- `completed/Lumina-Living-Lab-07-completed.xlsx` — completed comparison copy
- `LAB-07-Instructions.pdf` — printable detailed guide
- Other Office files in this folder are specific to this lab

## Primary prompt

> Analyse the Campaign_Data table in four passes: descriptive, segmented, anomaly and diagnostic. Calculate volume, revenue, margin, conversion and return metrics; compare channel, region and product; flag unusual values using robust rules; then propose three likely drivers. Separate observed evidence from hypotheses and cite the supporting table or chart.

## Procedure

1. **Confirm the data table grain and period.**

   One row must represent one campaign-week-product combination.

2. **Ask Copilot for a staged analysis plan.**

   > Analyse the Campaign_Data table in four passes: descriptive, segmented, anomaly and diagnostic. Calculate volume, revenue, margin, conversion and return metrics; compare channel, region and product; flag unusual values using robust rules; then propose three likely drivers. Separate observed evidence from hypotheses and cite the supporting table or chart.

3. **Build descriptive KPI formulas and reconcile totals.**

   Use SUMIFS, COUNTIFS, AVERAGEIFS, MEDIAN and STDEV.S where appropriate.

4. **Create PivotTables for channel, region and product.**

   Show revenue, margin, conversion and return rate with consistent number formats.

5. **Create trend and variance charts.**

   Use native Excel charts and label period and unit.

6. **Investigate anomalies.**

   Record the row key, rule, observed value, possible cause and verification owner.

7. **Ask Copilot to critique the findings.**

   > Challenge these findings. Identify alternative explanations, missing data and any claim that is stronger than the evidence.

8. **Write the management findings.**

   Each finding must include evidence, caveat, action and owner.


## Acceptance test

The workbook separates facts from hypotheses, reconciles totals, documents anomalies and presents three defensible findings with caveats.

## Evidence

- Completed workbook with Prompt_Log and Evidence_Register
- App-specific artifact and a credential-safe screenshot
- Verification, exception and human-approval note

---

*Enhance Work Productivity with Microsoft 365 Copilot · TGS-2024043856 · Version v8.0 · © 2026 Tertiary Infotech Academy Pte Ltd*
