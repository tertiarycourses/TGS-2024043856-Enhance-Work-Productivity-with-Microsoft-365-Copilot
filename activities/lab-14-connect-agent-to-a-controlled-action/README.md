# Lab 14: Connect an Agent to a Controlled Action

**Topic 04** · **Advanced Agent** · **Copilot Studio + Power Automate + Excel** · **K4 · A4**

## Goal

Add an action that writes a validated intake to a controlled queue while preserving approval and audit evidence.

## Expected output

Agent-to-queue flow with validation, approval state, response ID and run audit.

## Files

- `Lumina-Living-Lab-14.xlsx` — learner starter and control workbook
- `completed/Lumina-Living-Lab-14-completed.xlsx` — completed comparison copy
- `LAB-14-Instructions.pdf` — printable detailed guide
- Other Office files in this folder are specific to this lab

## Primary prompt

> Extend the Campaign Intake Agent with one controlled action: create a Draft queue record only after required fields pass validation. Return the Queue ID and Draft status. If data is missing, restricted or conflicting, do not call the action; explain the issue and route to a human. Never mark Approved and never send external email.

## Procedure

1. **Open the Action_Map workbook and inspect required input/output schema.**

   Campaign ID must remain the idempotency key.

2. **Create a Power Automate flow or agent action with explicit inputs.**

   Include Campaign ID, sponsor, route, summary and classification.

3. **Add validation before the write step.**

   Terminate safely when mandatory data is missing or restricted.

4. **Add the action to the agent.**

   > Extend the Campaign Intake Agent with one controlled action: create a Draft queue record only after required fields pass validation. Return the Queue ID and Draft status. If data is missing, restricted or conflicting, do not call the action; explain the issue and route to a human. Never mark Approved and never send external email.

5. **Test one valid, one incomplete and one duplicate case.**

   A duplicate Campaign ID must not create a second active queue record.

6. **Record the run ID, input hash, result and reviewer.**

   Use Run_Audit in the workbook.

7. **Review permissions and connection ownership.**

   Document the service/owner account and least-privilege scope.

8. **Keep the action in test mode.**

   Do not connect production mailboxes or lists during class.


## Acceptance test

Only validated cases create Draft records, duplicate submissions are controlled and every run has traceable evidence.

## Evidence

- Completed workbook with Prompt_Log and Evidence_Register
- App-specific artifact and a credential-safe screenshot
- Verification, exception and human-approval note

---

*Enhance Work Productivity with Microsoft 365 Copilot · TGS-2024043856 · Version v8.0 · © 2026 Tertiary Infotech Academy Pte Ltd*
