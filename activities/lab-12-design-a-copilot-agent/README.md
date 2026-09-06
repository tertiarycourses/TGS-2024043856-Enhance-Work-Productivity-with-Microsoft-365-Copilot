# Lab 12: Design a Scoped Microsoft 365 Copilot Agent

**Topic 04** · **Foundation Agent** · **Microsoft 365 Copilot agents + Excel** · **K4 · A4**

## Goal

Define an agent's job, knowledge, boundaries, test cases and ownership before building it.

## Expected output

Agent design canvas, knowledge register, risk controls and ten acceptance tests.

## Files

- `Lumina-Living-Lab-12.xlsx` — learner starter and control workbook
- `completed/Lumina-Living-Lab-12-completed.xlsx` — completed comparison copy
- `LAB-12-Instructions.pdf` — printable detailed guide
- Other Office files in this folder are specific to this lab

## Primary prompt

> Design a Campaign Intake Agent for Lumina Living. It should answer process questions, validate an intake record and recommend the next route. Define its purpose, intended users, allowed knowledge, required inputs, outputs, refusal rules, escalation conditions and success measures. The agent must not approve budgets, send email or change official status.

## Procedure

1. **Review the Agent_Design workbook and sample intake records.**

   Identify which fields are mandatory, sensitive and decision-critical.

2. **Write one measurable agent outcome.**

   Avoid a broad goal such as help with campaigns.

3. **Draft the agent design.**

   > Design a Campaign Intake Agent for Lumina Living. It should answer process questions, validate an intake record and recommend the next route. Define its purpose, intended users, allowed knowledge, required inputs, outputs, refusal rules, escalation conditions and success measures. The agent must not approve budgets, send email or change official status.

4. **Map allowed knowledge and actions.**

   Apply least privilege; exclude personal or unrelated files.

5. **Write ten tests including happy path, missing data, conflicting data, prompt injection and prohibited action.**

   Record expected result before running each test.

6. **Assign owner, approver and monitoring cadence.**

   Separate content owner from technical owner where appropriate.

7. **Review the design against A4 staff-training needs.**

   Identify which users need orientation, practice and support.


## Acceptance test

The agent has a narrow purpose, explicit non-actions, least-privilege knowledge and ten test cases with expected outcomes.

## Evidence

- Completed workbook with Prompt_Log and Evidence_Register
- App-specific artifact and a credential-safe screenshot
- Verification, exception and human-approval note

---

*Enhance Work Productivity with Microsoft 365 Copilot · TGS-2024043856 · Version v8.0 · © 2026 Tertiary Infotech Academy Pte Ltd*

## SharePoint agent extension

Continue with [SHAREPOINT-AGENT-EXTENSION.pdf](SHAREPOINT-AGENT-EXTENSION.pdf). The matching Markdown source, agent-configs.json and sharepoint-knowledge folder are included here. Keep using this lab’s original Excel evidence workbook.
