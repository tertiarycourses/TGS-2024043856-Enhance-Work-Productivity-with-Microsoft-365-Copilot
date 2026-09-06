# Microsoft 365 agents connected to SharePoint

TGS-2024043856 | Enhancement v8.1 | 7 September 2026

This extension continues Labs 12 to 16 using the existing Lumina Living scenario. Keep the original workbooks and activities. Build a source-grounded agent, inspect its citations, and record a human-reviewed result in the existing Excel evidence register.

## Training workspace

Open https://tertiaryinfotech.sharepoint.com/sites/TGS-2024043856-LuminaCopilot using your trainer-assigned work account. The site is private. Training 1 is the owner; Training 2 and TIA Admin are members. The site contains synthetic training content. Credentials must never appear in prompts, workbook cells or screenshots.

A consumer Microsoft account cannot replace a work account in this tenant. The original materials may show earlier consumer training addresses; use the tenant accounts assigned by the trainer for these SharePoint activities.

## Choose the correct agent surface

A SharePoint agent answers questions from selected SharePoint content and is stored as an .agent file. Microsoft 365 Copilot Agent Builder lets a maker configure an agent and select knowledge sources in the Copilot application. Copilot Studio supports more extensive workflow and action design. A knowledge source is not an action connector: adding a site does not grant the ability to send email, approve a claim or update a business record.

The available features depend on the account licence, tenant policy and current product surface. Before class, the trainer should open the actual agent with each assigned account and confirm that it can answer from the intended source. A missing licence or metered-usage configuration must be resolved by the tenant administrator; do not purchase or enable billing during the exercise.

## Lab 12 extension Create the policy agent

1. Open the supplied sharepoint-knowledge folder and read Lumina-Travel-and-Expenses.docx. Identify policy EXP-01, version 1.0, owner and effective date. Keep Lumina-Agent-Test-Cases.docx as a test fixture rather than the authoritative policy source.
2. Open the course SharePoint site and select Documents. Confirm the three policy, campaign and routing documents are present. If working in a separate practice site, use Create or upload, then Files upload, and upload the three source DOCX files.
3. Select Lumina-Travel-and-Expenses.docx. Open Copilot and choose Create an agent. Some tenants also expose Agent under Create or upload. Read the current labels rather than assuming every tenant has the same menu.
4. Set the agent name to TGS-2024043856 Lumina Policy Agent, adding your initials when making a separate learner copy. In Overview, describe its purpose as explaining fictional travel and expense policy with citations.
5. Open Sources. Confirm only the intended expense document is selected. A site title may group its selected files; inspect the file list beneath it. Keep source prioritisation enabled when available. Do not select unrelated sites or private personal files.
6. Open Behavior. Paste the policy instructions from agent-configs.json. Replace generic starter prompts with the taxi, receipt and meal questions supplied below. Save the agent.
7. If Sources displays Preparing, wait for the readiness indicator to clear and retest. Do not record a source-grounded pass when the answer comes only from general knowledge.
8. Ask: Can I claim a SGD 48 taxi fare for a client visit? Open its citation and compare it with the source. The expected explanation identifies manager approval above SGD 40, receipt and business purpose requirements, and the 14-calendar-day submission deadline. The response must not approve the claim.
9. Ask: What is Lumina Living annual leave carry-forward limit? Use only the supplied policy; say if not established. Record whether the agent explicitly reports that the supplied policy does not establish it. Correct guesses are not acceptable evidence.
10. In the existing Lab 12 Excel workbook, record prompt, actual response, citation, source version, verification outcome and reviewer. Retain a credential-safe screenshot.

## Lab 13 extension Recommend service routing

Create TGS-2024043856 Lumina Routing Agent using Lumina-Service-Routing.docx as its source. Use its matching instructions in agent-configs.json. Keep the original intake workbook as the controlled input and evidence register.

Prompt: Request REQ-101 reports a damaged chair and a delivery due tomorrow. Recommend the queue and priority. Return Request ID, recommended queue, recommended priority, cited rule, missing information and human reviewer. Do not submit a ticket.

Verify Operations and high priority against SR-01. A damaged item does not prove an unsafe product; urgent review requires the relevant reported facts. Try a request with no delivery date and require a clarification instead of an invented deadline. The learner manually records the approved recommendation in Excel after review.

## Lab 14 extension Separate knowledge from actions

Use the original controlled-action exercise after the routing recommendation. In a knowledge-only SharePoint agent, no business record is changed. If the class uses a separately configured Copilot Studio action or flow, inspect its connection identity, inputs and approval stage before testing. Record the actual action result identifier only after a successful run. Never use an agent sentence such as submitted successfully as proof of a write.

Use three distinct evidence states in Excel: Recommended, Human reviewed, and Action verified. A failed action stays failed even if the natural-language response sounds successful. Do not enable unattended production sends during this training.

## Lab 15 extension Draft a campaign update

Create TGS-2024043856 Lumina Campaign Agent with Lumina-Campaign-Brief.docx. Apply the campaign instructions in agent-configs.json. Ask: Draft a launch update including the budget, target enquiries, launch date and outstanding human reviews. Cite each factual claim and label it DRAFT FOR MARKETING REVIEW.

Check SGD 18000, 120 qualified enquiries and 1 October 2026 against CAM-2026-Q4. Ask the agent to add a carbon-neutral claim; it should flag the lack of supporting evidence. Transfer only verified facts into the existing Word or PowerPoint output. The agent does not automatically create or publish the full analysis-to-deck pipeline.

## Lab 16 extension Verify sharing and maintain sources

1. Open the site's membership panel and confirm the intended Training 1, Training 2 and admin identities. Site membership is separate from proof that a particular agent and source open correctly.
2. Locate the saved .agent file. Use its Share or Copy link command for the intended users. Prefer named people or people with existing access. Verify the underlying source remains in the same private course site.
3. Open the agent using the separately assigned Training 2 account. Confirm the expense source opens and the taxi question returns a valid citation. Repeat for the admin account when available. Do not label a membership-only check as a completed sign-in test.
4. In a learner-owned copy, change a harmless policy example and increment its version. Wait for source readiness and ask the same question again. Record the version and actual citation. Do not overwrite the shared class baseline without the trainer's direction.
5. Test an unknown answer, missing input, unsupported marketing claim and absent action result. Retain failures as well as passes in the original Lab 16 workbook.
6. Record agent owner, source owner, review date and retirement decision. Remove obsolete learner copies through the site's normal recoverable file workflow when instructed by the trainer.

## Evidence and troubleshooting

Use the existing Prompt_Log, Evidence_Register and Acceptance_Check sheets. For each test record account role, agent name, source filename and version, exact question, response excerpt, citation target, expected result, actual result, status and reviewer.

If the agent opens but a citation is inaccessible, inspect source permissions using the intended account. If a source is Preparing, verify readiness before repeating the test. If facts differ, inspect the cited document and source selection. If general knowledge appears, tighten the source and prompt and record the limitation; instructions alone are not a security boundary. If sharing fails, inspect both agent and source access rather than making the site public.

## Applying the two reference ebooks

Jess Stratton's Copilot for Microsoft 365 (Apress, 2024), Chapter 2, explains grounding through workplace context; Chapter 3, printed page 43 (PDF page 60), stresses factual verification even when prose sounds convincing. Apply both ideas here: select the authoritative SharePoint file, request its supporting section, and compare the response with that section before using it. A citation is a route to evidence, not an automatic pass.

Microsoft Copilot AI Integration in Office 365, Chapter 4, PDF pages 44–45, discusses Microsoft Graph as a connection to workplace information and the value of context across applications. Use this as a workflow concept: a maintained campaign brief supplies facts to an agent; a person verifies those facts; Word or PowerPoint turns them into an audience-appropriate draft. This course's source-only agents do not automatically orchestrate applications or write business records. Current Microsoft documentation and the live tenant determine available features.

For Lab 15, make a four-row fact ledger in the existing evidence workbook: budget, enquiry target, launch date and environmental claim. Enter the source section and verification decision beside each row. Draft a 90-word update for a sales manager using the three supported facts; leave the unsupported environmental claim out. Then adapt the same checked facts into a three-slide narrative: objective, campaign plan and decisions needed. Compare the numbers and date across the workbook, draft and deck. Record corrections before release.

For Lab 12, compare two prompts: Explain the expense policy; and Explain whether a SGD 48 client-visit taxi fare is eligible, cite the relevant section, identify missing facts, and do not approve it. Record which response gives a reviewable decision and why. This is an original practice exercise applying the ebooks' context and verification themes.

Reading references are retained privately in the reference folder; the teaching examples and diagrams are original. Neither ebook is the authority for current agent menus, licensing or product limits.

## Official product references

- Microsoft Learn, Copilot architecture: https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-architecture
- Microsoft Support, Create an agent in SharePoint: https://support.microsoft.com/en-US/sharepoint/copilot-in-sharepoint/create-an-agent-in-sharepoint
- Microsoft Learn, Add knowledge sources: https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder-add-knowledge
- Microsoft Learn, Share and manage agents: https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder-share-manage-agents

Product guidance checked 7 September 2026. The source documents and worked examples in this extension are original synthetic teaching material.
