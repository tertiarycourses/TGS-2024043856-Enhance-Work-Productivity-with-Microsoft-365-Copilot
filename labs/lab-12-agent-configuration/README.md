# Lab 12: Configure Instructions Knowledge and Starter Prompts

**Topic 4 · 30 minutes · v9.0 · 14 October 2026**

Configure the private agent with precise instructions, selected knowledge and starter prompts. Verify the visible configuration before creating it.

**Learning outcome:** LO4: design a staff training plan for Microsoft Loop and Copilot Studio while configuring, testing and sharing a bounded Microsoft 365 business agent.

**Expected outcome:** Private configured agent or evidence-complete configuration record.

## Files

- [Instruction PDF](Lab-12-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-12)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/Northstar_Agent_Instructions.txt` — Reviewed instruction text
- `data/templates/Northstar_Agent_Test_Matrix.csv` — Eight-case test matrix
- `data/knowledge/` — four approved knowledge items plus the knowledge inventory and owner/configuration register

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Northstar-v9 is your own learner output folder.
- Microsoft 365 Copilot Agent Builder access in the assigned tenant. Availability depends on licence and admin policy; use the supplied configuration-and-test route when unavailable.

## Steps

### 1. Open the Lab 11 draft. On Configure, enter the concise description and complete bounded instructions. Keep within the documented 8,000-character instruction limit.

### 2. Add only approved Northstar knowledge. Prefer already-permissioned SharePoint or OneDrive items. Record the different access implication if using embedded files.

```text
AGENT BUILDER - INSTRUCTIONS:
You are the Northstar Operations Knowledge Agent for a fictional training company. Use only the configured Northstar knowledge sources for operational claims. Cite the source title in every answer containing a date, work-order count, status definition or assignment. Treat 30 September 2026 as the fixed reporting date for the supplied baseline. Distinguish current from proposed assignment. If evidence is absent or conflicting, say UNKNOWN and name the missing source or conflict. Do not invent causes, customer impact, safety impact, approval or live state. Do not send email, modify files, change work orders, approve assignments or claim an external action was completed. Agent Builder does not author external-service actions; route such requests to an authorised human workflow or separately governed Copilot Studio solution. Keep answers concise, include Sources, and name the human review owner.
```

### 3. Turn off broad web search for this internal scenario when policy permits. Record actual state because Agent Builder cannot fully block general AI knowledge.

### 4. Add four supported starter prompts.

```text
AGENT BUILDER - STARTER PROMPTS:
1. Summarise the verified 30 September 2026 backlog and cite the source. 2. Explain backlog and overdue definitions. 3. Compare current with proposed assignment without approving a change. 4. Give a staff practice plan from the enablement guide.
```

### 5. Use Try it for one supported and one missing-evidence question. Refine if the answer omits a citation or invents a fact.

### 6. Select Create only after both preview tests pass. Record private state, owner, instruction version and knowledge list.

## Verification

- **Instructions:** Purpose, citations, UNKNOWN and prohibited actions explicit.
- **Knowledge:** Items match inventory and existing permissions.
- **Prompts:** Four prompts are supported by knowledge.
- **Preview:** Grounded and UNKNOWN answers pass before Create.

## Expected Outcome

Private configured agent or evidence-complete configuration record.

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
