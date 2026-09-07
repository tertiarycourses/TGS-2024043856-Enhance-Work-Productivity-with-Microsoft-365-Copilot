# Lab 14 Connect the recommendation to a reviewed action

**Course:** TGS-2024043856 | **Version:** v8.2 | **Apps:** Copilot Studio + Power Automate + Excel | **Alignment:** K4 · A4

## Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Operations action control.

## Input and handoff

Use Lumina-Routing-Test-Register.xlsx; Lumina-Service-Routing.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use `Lumina-Living-Lab-14.xlsx` as the evidence workbook. `completed/` contains comparison examples, not proof that your action ran. The primary app output is `Lumina-Action-Run-Register.xlsx`.

## Four-part prompt

**Goal:** Pass a reviewed routing recommendation to a separately configured training flow. Validate required fields, require human review and record the returned item/run ID. If no flow is configured, record Not run rather than claiming success.

**Context:** You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

**Source:** Lumina-Routing-Test-Register.xlsx; Lumina-Service-Routing.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

**Expectations:** Save Lumina-Action-Run-Register.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-14.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

## Procedure

1. Inspect the original controlled-action lab and the class’s configured training flow, if one is available. Confirm its connection identity, target test list, required fields and approval stage.

2. Pass only a reviewed recommendation with REQ-101 and SW-2026. Test missing required input and verify no write occurs for the invalid case.

3. For a valid approved run, open the destination item and compare every stored field with the request. Record the real item ID and run result.

4. Without a configured flow, complete the design and validation evidence, mark execution Not run, and retain the recommendation for the capstone.

## Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and `Lumina-Action-Run-Register.xlsx` is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Use SHAREPOINT-AGENT-EXTENSION.pdf for the existing agent setup and source-access procedures. The shared policy agent uses EXP-01; HR policy testing requires your learner-owned agent with the reviewed HR source added.


[Live Lumina SharePoint site](https://tertiaryinfotech.sharepoint.com/sites/TGS-2024043856-LuminaCopilot) — use the assigned tenant account; anonymous Anyone links are unavailable.
