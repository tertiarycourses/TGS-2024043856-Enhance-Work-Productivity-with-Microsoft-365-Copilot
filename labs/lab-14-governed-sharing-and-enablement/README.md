# Lab 14: Share with Named Users and Deliver the Staff Enablement Plan

**Topic 4 · 30 minutes · v9.0 · 14 October 2026**

Share only after blocking tests pass. Verify named users already have source access, retest acquisition and retrieval, then use Microsoft Loop for staff training evidence.

**Learning outcome:** LO4: design a staff training plan for Microsoft Loop and Copilot Studio while configuring, testing and sharing a bounded Microsoft 365 business agent.

**Expected outcome:** Named-user sharing record, test-user result, Loop enablement component and rollback-ready owner plan.

## Files

- [Instruction PDF](Lab-14-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-14)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/Northstar_Staff_Enablement_Plan.md` — Staff training plan
- `data/templates/Northstar_Agent_Test_Matrix.csv` — Sharing gate
- `data/knowledge/` — four approved knowledge items plus the knowledge inventory and owner/configuration register

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Northstar-v9 is your own learner output folder.
- Microsoft 365 Copilot Agent Builder access in the assigned tenant. Availability depends on licence and admin policy; use the supplied configuration-and-test route when unavailable.

## Steps

### 1. Confirm every blocking test passes. Assign agent owner, knowledge owner, supervisor and support roles.

### 2. Open Share and review user versus owner roles. Start with one named test user or approved group.

### 3. Verify that the user already has permission to each SharePoint or OneDrive source. Do not broaden permissions for the exercise.

### 4. Share the link with the named training test user only. If sharing is unavailable, finish the plan without claiming distribution. The user runs T01, T05 and T06.

### 5. Create a Microsoft Loop rollout tracker using only observed results.

```text
MICROSOFT LOOP COPILOT:
Create a Northstar agent staff enablement tracker with columns User, Role, Practice test, Evidence, Defect, Owner, Retest and Status. Include grounded retrieval, UNKNOWN, permission and external-action-refusal tests. Do not fabricate completion or approval.
```

### 6. Review the plan: purpose, access, four practice cases, escalation, owner, monthly review and rollback. Keep the approved LO4 focus on Microsoft Loop and Copilot Studio training.

### 7. Record final private or named-user state, actual link if available, test result and next review. Do not submit to an org catalog or multi-channel deployment.

## Verification

- **Gate:** All blocking retrieval, permission and action-boundary tests pass.
- **Sharing:** Named users only; role and knowledge access verified.
- **Loop plan:** Actual practice evidence, defect owner and retest visible.
- **Lifecycle:** Owners, review trigger and rollback assigned.

## Expected Outcome

Named-user sharing record, test-user result, Loop enablement component and rollback-ready owner plan.

## Checkpoint

If you fell behind, use data/checkpoints/Northstar_Verified_Checkpoint.xlsx and data/checkpoints/Northstar_Verified_Snapshot.docx. Record checkpoint used in Prompt_Log; then perform this lab, rather than claiming the checkpoint as your output.

## Troubleshooting

| If this happens | Fix |
|---|---|
| Copilot cannot find the source | Use the app file picker to select the actual OneDrive file. A typed local path or a different app chat is not shared context. If needed copy only the verified snapshot into the current app. |
| A total disagrees with Control | Clear dashboard filters to All, check table extent and duplicate IDs, recalculate, then compare definitions and reporting date. Reconcile before continuing. |
| The named feature is missing | Confirm the correct assigned account, English display language and app version. Use the stated manual practice route; record feature unavailable. This is not evidence that a native skill ran. |

## Challenge

Run one additional adversarial prompt and explain which instruction or knowledge boundary controlled the response.

## Reflection

Which evidence proves the output is correct, and which decision still needs a person?

> Northstar Water Services is fictional. Use the verified 120-row baseline and fixed reporting date 30 September 2026. Current assignments are evidence; proposals are not approved. Agent labs use retrieval, configuration, testing and supported sharing only; they never claim external-service actions.
