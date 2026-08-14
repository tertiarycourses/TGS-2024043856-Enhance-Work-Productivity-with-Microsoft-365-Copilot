# Lab 08: Forecast and Stress-Test a Campaign with Copilot

**Topic 02** · **Advanced** · **Excel + Analyst agent** · **K3 · A2**

## Goal

Use forecasting, scenarios and sensitivity analysis to evaluate a transition plan under uncertainty.

## Expected output

Forecast model with base, downside and upside scenarios, sensitivity table and decision guardrails.

## Files

- `Lumina-Living-Lab-08.xlsx` — learner starter and control workbook
- `completed/Lumina-Living-Lab-08-completed.xlsx` — completed comparison copy
- `LAB-08-Instructions.pdf` — printable detailed guide
- Other Office files in this folder are specific to this lab

## Primary prompt

> Using the historical monthly data, build a 6-month forecast for revenue and workload. Explain the method, assumptions and confidence limits. Then test downside, base and upside scenarios for conversion, average order value and service capacity. Identify the earliest month capacity is breached and recommend a guarded action. Do not claim certainty beyond the data.

## Procedure

1. **Review historical coverage and missing periods.**

   Record why the data is or is not suitable for forecasting.

2. **Ask Copilot or Analyst for a forecast plan.**

   > Using the historical monthly data, build a 6-month forecast for revenue and workload. Explain the method, assumptions and confidence limits. Then test downside, base and upside scenarios for conversion, average order value and service capacity. Identify the earliest month capacity is breached and recommend a guarded action. Do not claim certainty beyond the data.

3. **Create a Forecast sheet with explicit assumptions.**

   Keep hardcoded inputs separate from formula outputs.

4. **Build base, downside and upside cases.**

   Use cell references rather than embedding percentages in formulas.

5. **Create a sensitivity table for conversion and capacity.**

   Highlight the breach boundary without 3D effects.

6. **Compare Copilot findings with workbook calculations.**

   Resolve discrepancies before using the narrative.

7. **Document method limitations and monitoring triggers.**

   State what new evidence would change the decision.

8. **Save the model and a one-page decision summary.**

   The summary must include forecast range, breach month, action and guardrail.


## Acceptance test

All scenarios are formula-driven, forecast uncertainty is explicit and the recommended action is linked to a measurable trigger.

## Evidence

- Completed workbook with Prompt_Log and Evidence_Register
- App-specific artifact and a credential-safe screenshot
- Verification, exception and human-approval note

---

*Enhance Work Productivity with Microsoft 365 Copilot · TGS-2024043856 · Version v8.0 · © 2026 Tertiary Infotech Academy Pte Ltd*
