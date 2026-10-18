# Lab 14: Share the HR Agent with Named Users and Deliver Staff Enablement

**Topic 4 · 30 minutes · v9.1 · 18 October 2026**

Share Lumina HR Policy Agent only after the blocking tests pass. Verify that named users already have access to every knowledge file, retest as a user, then use Microsoft Loop to track staff practice, defects and retests as part of the LO4 staff training plan.

**Learning outcome:** LO4: design a staff training plan for Microsoft Loop and Copilot Studio while configuring, testing and sharing a grounded Microsoft 365 HR agent.

**Expected outcome:** A named-user sharing record, a test-user result, a Microsoft Loop enablement tracker and a rollback-ready owner plan.

## Files

- [Instruction PDF](Lab-14-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-14)
- `data/Lumina_HR_Cases.xlsx` — synthetic Lumina source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/Lumina_Staff_Enablement_Plan.md` — Staff training plan
- `data/templates/Lumina_HR_Agent_Test_Matrix.csv` — Sharing gate
- `data/knowledge/` — four approved knowledge items plus the knowledge inventory and owner/configuration register

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Lumina-HR-v9 is your own learner output folder.
- Microsoft 365 Copilot licence with Agent Builder enabled by your administrator. Skills in agents are a preview for Frontier-enrolled tenants; otherwise use the labelled manual route. Use the supplied configuration-and-test route when Agent Builder is unavailable.

## Steps

### 1. Confirm every blocking test passed in Lab 13. Assign the agent owner, knowledge owner (HR Director), HR reviewer and support roles in the owner/configuration register.

### 2. Open Share and review the user (Can chat) and owner (Can edit) roles. Start with one named test user or approved group; give users Can chat, not Can edit.

### 3. Verify the user already has permission to each OneDrive or SharePoint knowledge file. Do not broaden permissions for the exercise.

### 4. Share the link with the named test user only. If sharing is unavailable, finish the plan without claiming distribution. The user runs T01, T05 and T06 and you record the results.

### 5. Create a Microsoft Loop staff enablement tracker using only observed results.

```text
MICROSOFT LOOP COPILOT:
Create a Lumina HR Policy Agent staff enablement tracker with columns User, Role, Practice test, Evidence, Defect, Owner, Retest and Status. Include cited leave-policy retrieval, UNKNOWN, privacy and approval-refusal tests. Do not fabricate completion or approval.
```

### 6. Review data/templates/Lumina_Staff_Enablement_Plan.md: purpose, access, practice cases, escalation, owners, monthly review and rollback. Keep the LO4 focus on Microsoft Loop and Copilot Studio staff training.

### 7. Record the final private or named-user state, the actual link if available, test results and the next review date. Do not submit to the organisation catalogue or deploy to other channels.

## Verification

- **Gate:** All blocking retrieval, privacy and approval tests pass before sharing.
- **Sharing:** Named users only, with Can chat; knowledge access verified.
- **Loop plan:** Actual practice evidence, defect owner and retest visible.
- **Lifecycle:** Owners, review trigger and rollback assigned.

## Expected Outcome

A named-user sharing record, a test-user result, a Microsoft Loop enablement tracker and a rollback-ready owner plan.

## Checkpoint

If you fell behind, use data/checkpoints/Lumina_Verified_Checkpoint.xlsx and data/checkpoints/Lumina_Verified_Snapshot.docx. Record checkpoint used in Prompt_Log; then perform this lab, rather than claiming the checkpoint as your output.

## Troubleshooting

| If this happens | Fix |
|---|---|
| Copilot cannot find the source | Use the app file picker to select the actual OneDrive file. A typed local path or a different app chat is not shared context. If needed copy only the verified snapshot into the current app. |
| A total disagrees with Control | Clear dashboard filters to All, check table extent and duplicate IDs, recalculate, then compare definitions and reporting date. Reconcile before continuing. |
| The named feature is missing | Confirm the correct assigned account, English display language and app version. Use the stated manual practice route; record feature unavailable. This is not evidence that a native skill ran. |

## Challenge

Write one new employee HR question the handbook does not answer, run it and explain which instruction, Skill rule or knowledge boundary controlled the response.

## Reflection

Which evidence proves the output is correct, and which decision still needs a person?

> Lumina Living Pte Ltd and all of its employees, HR cases and HR policies are fictional. Use the verified 120-case baseline and fixed reporting date 30 September 2026. Current case owners are evidence; proposals are not approved. The HR agent answers from approved knowledge only and never approves requests, sends messages or reveals another employee’s data.
