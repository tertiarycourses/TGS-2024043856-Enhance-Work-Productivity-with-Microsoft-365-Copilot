# Lab 11: Define the Northstar Operations Agent and Knowledge Boundary

**Topic 4 · 30 minutes · v9.0 · 14 October 2026**

Translate the Northstar workflow into a bounded agent design. Inventory approved knowledge, permissions, fixed date and prohibited external actions before opening Agent Builder.

**Learning outcome:** LO4: design a staff training plan for Microsoft Loop and Copilot Studio while configuring, testing and sharing a bounded Microsoft 365 business agent.

**Expected outcome:** Completed agent design brief, knowledge inventory and owner register for a private agent.

## Files

- [Instruction PDF](Lab-11-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-11)
- `data/Northstar_Work_Orders.xlsx` — synthetic Northstar source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/Northstar_Agent_Design_Brief.md` — Agent scope template
- `data/templates/Northstar_Agent_Test_Matrix.csv` — Eight-case test matrix
- `data/knowledge/` — four approved knowledge items plus the knowledge inventory and owner/configuration register

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Northstar-v9 is your own learner output folder.
- Microsoft 365 Copilot Agent Builder access in the assigned tenant. Availability depends on licence and admin policy; use the supplied configuration-and-test route when unavailable.

## Steps

### 1. Open the supplied design brief and knowledge inventory. Confirm that every source is synthetic, dated and owned by a named training role. Keep the agent private.

### 2. In Microsoft 365 Copilot select New agent. If unavailable, complete the configuration record and label Feature unavailable; do not claim creation.

### 3. Describe a retrieval-and-drafting agent with no sends, work-order writes, assignment approval or external-service actions.

```text
AGENT BUILDER - DESCRIBE:
Create a private Northstar Operations Knowledge Agent for maintenance coordinators. It answers from the selected policy, fixed snapshot, work-order workbook and enablement plan. It cites sources, separates current from proposed assignments and returns UNKNOWN when evidence is missing. It does not send, modify, approve or use external services.
```

### 4. Review name, description and draft instructions against the approved brief. Record the reviewed configuration.

### 5. Classify each source as SharePoint, OneDrive or embedded. Record owner, user access and whether the selected licence supports it.

### 6. Save a private draft or completed paper configuration. Record the actual state and carry it to Lab 12.

## Verification

- **Scope:** One retrieval-and-drafting outcome; no external actions.
- **Knowledge:** Every source has owner, permission, date and supported type.
- **Truth boundary:** Missing causes, approvals and live state remain UNKNOWN.
- **State:** Private draft or accurately labelled configuration-only route.

## Expected Outcome

Completed agent design brief, knowledge inventory and owner register for a private agent.

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
