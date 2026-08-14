# Lab 13: Build an Intake and Routing Agent

**Topic 04** · **Intermediate Agent** · **Copilot Studio / Agent Builder + Excel** · **K4 · A4**

## Goal

Build a retrieval-and-routing agent that validates inputs and escalates exceptions.

## Expected output

Working intake agent, controlled instructions, knowledge source and routed test results.

## Files

- `Lumina-Living-Lab-13.xlsx` — learner starter and control workbook
- `completed/Lumina-Living-Lab-13-completed.xlsx` — completed comparison copy
- `LAB-13-Instructions.pdf` — printable detailed guide
- Other Office files in this folder are specific to this lab

## Primary prompt

> You are the Lumina Living Campaign Intake Agent. Use only the approved campaign process knowledge. Ask for Campaign Name, Sponsor, Objective, Audience, Budget Band, Launch Date and Data Classification. Validate completeness; summarise the request; recommend one route: Standard Review, Fast-Track Review or Specialist Review. Explain the rule used. Never approve, send or modify the official register. Escalate conflicting, restricted or incomplete cases.

## Procedure

1. **Create the agent in the tenant surface demonstrated by the trainer.**

   Use Agent Builder or Copilot Studio according to available licensing.

2. **Add the approved process document as knowledge.**

   Do not connect a broad SharePoint site for a narrow lab agent.

3. **Paste and refine the system instructions.**

   > You are the Lumina Living Campaign Intake Agent. Use only the approved campaign process knowledge. Ask for Campaign Name, Sponsor, Objective, Audience, Budget Band, Launch Date and Data Classification. Validate completeness; summarise the request; recommend one route: Standard Review, Fast-Track Review or Specialist Review. Explain the rule used. Never approve, send or modify the official register. Escalate conflicting, restricted or incomplete cases.

4. **Configure conversation starters.**

   Use one complete, one incomplete and one policy question.

5. **Run the ten test cases from Excel.**

   Capture actual route, explanation, citation and pass/fail.

6. **Fix instructions or knowledge gaps.**

   Change one variable at a time and retest.

7. **Publish only to the trainer-approved test audience.**

   Record version and owner in Agent_Register.


## Acceptance test

The agent gathers mandatory fields, cites approved knowledge, routes correctly and refuses approval or external-send requests.

## Evidence

- Completed workbook with Prompt_Log and Evidence_Register
- App-specific artifact and a credential-safe screenshot
- Verification, exception and human-approval note

---

*Enhance Work Productivity with Microsoft 365 Copilot · TGS-2024043856 · Version v8.0 · © 2026 Tertiary Infotech Academy Pte Ltd*
