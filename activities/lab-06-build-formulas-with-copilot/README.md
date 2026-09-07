# Lab 06 Build the sales and financial formulas in Excel

**Course:** TGS-2024043856 | **Version:** v8.2 | **Apps:** Excel + Copilot | **Alignment:** K3 · A2

## Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Finance calculations.

## Input and handoff

Use Lumina-Business-Data.xlsx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use `Lumina-Living-Lab-06.xlsx` as the evidence workbook. `completed/` contains comparison examples, not proof that your action ran. The primary app output is `Lumina-Analysis.xlsx`.

## Four-part prompt

**Goal:** From Campaign_Data, calculate revenue, cost, margin, conversion and return rates using formulas. Define the denominator for each rate. Check 96 source records and handle zero denominators explicitly.

**Context:** You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

**Source:** Lumina-Business-Data.xlsx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

**Expectations:** Save Lumina-Analysis.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-06.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

## Procedure

1. Save the source workbook as Lumina-Analysis.xlsx. Inspect the 96 records, one header row, record IDs and numeric columns.

2. Use the complete prompt to generate formulas. Review revenue minus cost for margin; use orders/clicks for conversion and returns/orders for return rate. Label zero-denominator cases rather than hiding undefined rates.

3. Reconcile revenue SGD 933,290.00, cost SGD 521,097.41 and margin SGD 412,192.59 against the original ranges. Check a zero-denominator test in a separate test row.

4. Save the workbook, formula evidence and control results for Lab 7.

## Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and `Lumina-Analysis.xlsx` is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.


## Financial data and Copilot analysis

Use scenario/Lumina-Sales-Mock-Data.csv (96 synthetic sales summaries) and Lumina-Financial-Analysis-Sample.xlsx as the comparison sample. Revenue means sales value; Orders means order count. This is not an invoice ledger. Costs omit overhead and tax, so margin is not net profit.

Ask Copilot to add margin, margin percentage, target variance and revenue per order formulas; explain each denominator. Build monthly and channel summaries. Verify totals against the raw CSV and inspect representative formulas before trusting the sample.

Save your own financial workbook. Transfer the checked financial charts and caveats into the Word management report and PowerPoint decision deck. Use the supplied completed sample only for comparison, not as proof that Copilot ran.
