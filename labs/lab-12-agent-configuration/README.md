# Lab 12: Build the HR Agent: Instructions, Knowledge, Skill and Starter Prompts

**Topic 4 · 30 minutes · v9.1 · 18 October 2026**

Configure Lumina HR Policy Agent with reviewed instructions, the four OneDrive knowledge files and the hr-policy-qa Skill, add starter prompts, then preview a grounded answer and a missing-evidence answer before you create it. Grounding comes from the knowledge; the Skill sets how every answer is structured, cited and bounded.

**Learning outcome:** LO4: design a staff training plan for Microsoft Loop and Copilot Studio while configuring, testing and sharing a grounded Microsoft 365 HR agent.

**Expected outcome:** A private configured HR agent (or an evidence-complete configuration record) whose preview answers are cited and whose missing-evidence answer is UNKNOWN.

## Files

- [Instruction PDF](Lab-12-Instructions.pdf)
- [Copy-ready prompts](https://tertiarycourses.github.io/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot/prompts/#lab-12)
- `data/Lumina_HR_Cases.xlsx` — synthetic Lumina source
- `data/templates/` — learner starting templates
- `data/checkpoints/` — clearly labelled rejoin evidence
- `data/templates/Lumina_HR_Agent_Instructions.txt` — Reviewed instruction text
- `data/templates/hr-policy-qa/SKILL.md` — hr-policy-qa Skill for the agent (compress the folder to .zip before upload)
- `data/templates/Lumina_HR_Agent_Test_Matrix.csv` — Eight-case test matrix
- `data/knowledge/` — four approved knowledge items plus the knowledge inventory and owner/configuration register

## Prerequisites

- Microsoft 365 account with Copilot available in Word, Excel, PowerPoint and Outlook. Availability depends on the assigned licence and tenant settings; confirm access with the trainer before class.
- Desktop Excel on Windows or Mac is recommended; save working copies to your assigned OneDrive course folder with AutoSave on. Do not overwrite the supplied input.
- Download this whole lab folder. All files are synthetic; Lumina-HR-v9 is your own learner output folder.
- Microsoft 365 Copilot licence with Agent Builder enabled by your administrator. Skills in agents are a preview for Frontier-enrolled tenants; otherwise use the labelled manual route. Use the supplied configuration-and-test route when Agent Builder is unavailable.

## Steps

### 1. Open your Lab 11 draft and select Configure. Set Name to Lumina HR Policy Agent (30 characters maximum) and Description to: Answers Lumina employees’ HR policy questions from the approved handbook, with cited sections. Replace Instructions with the reviewed text below; it is well under the 8,000-character limit. Accept a suggested improvement only if it keeps the sources, citations and boundaries.

```text
AGENT BUILDER - INSTRUCTIONS:
# Role You are Lumina HR Policy Agent, an HR helpdesk assistant for employees of Lumina Living Pte Ltd, a fictional company used for training. # Sources Answer only from the knowledge files: Lumina_HR_Policy_Handbook.docx (version 2026.3) for policy questions, and Lumina_Verified_Snapshot.docx and Lumina_HR_Cases.xlsx (120 synthetic HR cases, reporting date 30 September 2026) for HR case figures. Follow the hr-policy-qa skill. If the files do not contain the answer, reply UNKNOWN, name the missing policy and refer the employee to their HR Business Partner. # Answer style Give the answer first, then the conditions, the next step and Sources (handbook section or snapshot). Be concise, friendly and professional. Use a short table for comparisons. # Boundaries Never approve, reject, submit or change leave, claims, training requests or HR cases, and never send messages. Never disclose another employee's personal data. Refer grievance, harassment, whistle-blowing and disciplinary matters to the HR Director without detail. Live leave balances and case status are only in the HR portal. If sources conflict, answer from the approved handbook and flag the conflict for HR. You cannot perform external actions; route workflow requests to an authorised person or a separately governed Copilot Studio solution.
```

### 2. Under Knowledge add the four files from OneDrive Lumina-HR-v9/agent-knowledge (Browse, or paste each share link). Turn on Only use specified sources if it is shown. Wait until no file shows Preparing. Link from OneDrive rather than uploading from your device: during the Skills preview an agent cannot combine uploaded files with a Skill.

### 3. Under Skills select Add and upload hr-policy-qa.zip from Lab 11. Confirm hr-policy-qa appears and is enabled. If Skills is not shown (Skills need a Frontier-enrolled tenant and a Copilot licence), paste the complete hr-policy-qa SKILL.md body at the end of Instructions and record Manual practice - Skills unavailable in the owner/configuration register.

### 4. Turn off web search where your tenant policy allows, so HR answers come from the selected knowledge. Record the actual setting: Agent Builder cannot fully block general AI knowledge, so citations and tests remain the real evidence.

### 5. Add the four starter prompts below. Each one must be answerable from the knowledge files.

```text
AGENT BUILDER - STARTER PROMPTS:
1. How many days of annual leave do I get, and how do I apply? 2. What can I claim for a GP visit, and by when? 3. How do I request a training course? 4. How many HR cases are overdue at 30 September 2026?
```

### 6. Open Try it and run the grounded test. Expected: 18 days from the third year of service, apply at least 5 working days ahead, line manager approves, cited to section 1 Annual leave.

```text
AGENT - TRY IT:
How many days of annual leave do I get in my third year of service, and how far ahead must I apply? Cite the handbook section.
```

### 7. Run the missing-evidence test. Expected: UNKNOWN, the missing policy named and a referral to the HR Business Partner. If either preview fails, tighten the instruction or knowledge and retest. Select Create only after both pass; keep the agent private and record owner, instruction version v1.0, knowledge list and Skill state.

```text
AGENT - TRY IT:
Can I take a three-month unpaid sabbatical?
```

## Verification

- **Instructions:** Role, sources, citation, UNKNOWN, privacy and approval boundaries explicit.
- **Knowledge:** Four OneDrive files match the inventory; Only use specified sources recorded.
- **Skill:** hr-policy-qa enabled, or the manual route labelled.
- **Preview:** 18 days cited to section 1; sabbatical returns UNKNOWN before Create.

## Expected Outcome

A private configured HR agent (or an evidence-complete configuration record) whose preview answers are cited and whose missing-evidence answer is UNKNOWN.

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
