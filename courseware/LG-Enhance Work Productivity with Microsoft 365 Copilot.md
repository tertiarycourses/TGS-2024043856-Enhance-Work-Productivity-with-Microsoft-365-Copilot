Tertiary Infotech Academy Pte Ltd

UEN: 201200696W

LEARNER GUIDE

For

Enhance Work Productivity with Microsoft 365 Copilot

TGS Ref No: TGS-2024043856

Conducted by

Tertiary Infotech Academy Pte Ltd

UEN: 201200696W

Version 8.2

DOCUMENT VERSION CONTROL RECORD

| Version Number | Effective Date of Release | Summary of Included Changes | Author |

| 8.0 | 15 August 2026 | Rebuilt from the v7 legacy coverage with sixteen progressive Microsoft 365 Copilot labs, deep Excel analysis, native PowerPoint charts and governed agent pipelines. | Dr Alfred Ang |

| 8.1 | 7 September 2026 | Retains v8.0 content; adds SharePoint agents, synthetic knowledge, visual mechanisms and Labs 12–16 extensions. | Dr Alfred Ang |

| 8.2 | 7 September 2026 | From v8.1 (7 September 2026): unified 16 Lumina SW-2026 labs, three worked prompt examples, shared data, charts and app handoffs; LG/LP/PPT and lab resources updated. | Dr Alfred Ang |

TABLE OF CONTENTS

| How to Use This Guide | 4 |

| Learning Outcomes and Skills Framework Alignment | 4 |

| Prompt and Verification Framework | 5 |

| Excel Conventions Used in Every Lab | 5 |

| Topic 01: Microsoft 365 Copilot Foundations, Word and PowerPoint | 5 |

| Lab 01: Set Up Microsoft 365 Copilot and Prompt Safely | 6 |

| Lab 02: Draft a Project Brief in Word from Excel Evidence | 8 |

| Lab 03: Refine a Responsible Copilot Use Policy in Word | 10 |

| Lab 04: Build a PowerPoint Story from Word and Excel | 12 |

| Lab 05: Enhance PowerPoint with Native Charts and Speaker Notes | 14 |

| Topic 02: Copilot for Excel: From Questions to Deep Analysis | 16 |

| Lab 06: Build and Audit Excel Formulas with Copilot | 16 |

| Lab 07: Run Deep Descriptive and Diagnostic Analysis in Excel | 18 |

| Lab 08: Forecast and Stress-Test a Campaign with Copilot | 20 |

| Topic 03: Copilot for Outlook, Teams and Loop | 22 |

| Lab 09: Triage an Outlook Inbox and Draft a Controlled Reply | 22 |

| Lab 10: Run an Action-Oriented Teams Meeting | 24 |

| Lab 11: Build a Living Implementation and Training Plan in Loop | 26 |

| Topic 04: Microsoft 365 Copilot Agents and Governed Pipelines | 28 |

| Lab 12: Design a Scoped Microsoft 365 Copilot Agent | 28 |

| Lab 13: Build an Intake and Routing Agent | 30 |

| Lab 14: Connect an Agent to a Controlled Action | 32 |

| Lab 15: Create an Analysis-to-Deck Agent Pipeline | 34 |

| Lab 16: Operate a Governed End-to-End Copilot Pipeline | 36 |

| Quick Prompt Reference and Assessment Flow | 38 |

| Microsoft 365 agents connected to SharePoint | 39 |

| Lumina Living connected workflow (current labs) | 43 |

How to Use This Guide

This guide is the operational companion to the visual slide deck. It contains the complete click-by-click procedures, full prompts, evidence requirements and acceptance tests for sixteen connected Lumina Living activities. The PowerPoint deliberately omits detailed procedures so learners can focus on concepts, decisions, controls and examples during instruction.

Course and Repository Access

Courseware and assessment portal: https://lms-tms.tertiaryinfotech.com/

Hands-on activity repository: https://github.com/tertiarycourses/TGS-2024043856-Enhance-Work-Productivity-with-Microsoft-365-Copilot

Microsoft learning path: https://learn.microsoft.com/en-us/training/paths/draft-analyze-present-microsoft-365-copilot/

Microsoft 365 Copilot agents module: https://learn.microsoft.com/en-us/training/modules/copilot-and-copilot-agents/

Clone the repository or download the ZIP, then keep the complete activities/ folder tree.

Every activity folder includes an Excel workbook and printable PDF instructions.

The two training account usernames are listed in activities/tools.md; the trainer distributes passwords separately.

Feature names and locations can vary by licence, tenant configuration and Microsoft rollout. Use the trainer-approved route when a named experience is unavailable.

Learning Outcomes

LO1: Predict and mitigate challenges in integrating Microsoft 365 Copilot into a workflow.

LO2: Develop a plan for implementing Microsoft 365 Copilot and transitioning from a legacy workflow.

LO3: Evaluate productivity opportunities across Teams, Outlook and Microsoft 365 Copilot Chat.

LO4: Design a staff enablement plan and a governed Copilot agent pipeline.

Skills Framework Alignment

| Code | Type | Criterion |

| K1 | Knowledge | Relevant systems and software |

| K2 | Knowledge | Organisation processes |

| K3 | Knowledge | Systems transition process |

| K4 | Knowledge | Emerging technology trends including artificial intelligence and automation |

| A1 | Ability | Anticipate potential issues in systems transition |

| A2 | Ability | Plan for smooth transition from old systems to new systems |

| A3 | Ability | Identify opportunities to adopt emerging technologies |

| A4 | Ability | Plan staff training for new systems and software |

Prompt and Verification Framework

Goal — state the outcome or decision needed.

Context — identify audience, workflow and constraints.

Source — name the file, meeting, thread or approved knowledge base to use.

Expectations — specify format, tone, length, evidence and refusal requirements.

Verify — compare facts, numbers, names, dates and citations with authoritative evidence.

Approve — retain a named human decision before send, publish, official write or status change.

Excel Conventions Used in Every Lab

The learner workbook is the structured control layer even when the primary activity occurs in Word, PowerPoint, Outlook, Teams, Loop or an agent builder.

Keep source data, assumptions, formulas, outputs, prompts, evidence and acceptance checks on named sheets.

Use formulas for derived values and inspect them before reuse. Completed workbooks must contain zero formula errors.

Use native Excel or PowerPoint charts where the data story benefits from a chart; do not paste a chart screenshot as the source artifact.

Record limitations and exceptions instead of hiding missing or conflicting evidence.

Topic 01: Microsoft 365 Copilot Foundations, Word and PowerPoint

Grounding · responsible use · prompt design · drafting · presentation storytelling

Key concepts

Grounding: Copilot combines the prompt with permitted work or web context; access permissions still apply.

Prompt contract: State goal, context, source and expectations, then verify before using the result.

Human accountability: Copilot proposes; the user checks evidence, tone, sensitivity and final release.

Cross-app story: Word shapes the narrative, Excel supplies evidence and PowerPoint communicates the decision.

Responsible AI: Fairness, reliability, privacy, inclusiveness, transparency and accountability guide use.

Transition risk: Licensing, data quality, permissions, adoption and over-trust need explicit controls.

Lab 01: Set Up Microsoft 365 Copilot and Prompt Safely

| Alignment | K1 · A1 |

| Level and apps | Foundation · Microsoft 365 Copilot Chat + Excel |

| Folder | activities/lab-01-set-up-and-prompt-safely |

| Excel workbook | activities/lab-01-set-up-and-prompt-safely/Lumina-Living-Lab-01.xlsx |

| Expected output | Completed setup, grounding and prompt-review register in Excel. |

Goal. Establish the licensed work surface, distinguish work from web grounding and record safe-use controls.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Using the attached workbook and only the information it contains, summarise the three highest-priority readiness gaps for Lumina Living. For each gap, cite the sheet and row evidence, state the risk, propose one control, and label anything you cannot verify.

Detailed procedure

| 1 | Sign in with the training account allocated by the trainer and confirm the Microsoft 365 Copilot work surface is available.Do not paste the password into the workbook, prompt history or screenshots. |

| 2 | Open the workbook and review the Readiness_Register table.Confirm that the fields Owner, Evidence, Risk and Control are present. |

| 3 | Select work-grounded context when available and attach the workbook.If work grounding is unavailable, continue with the attached file and record the limitation. |

| 4 | Submit the supplied prompt without adding unsupported company facts.PromptUsing the attached workbook and only the information it contains, summarise the three highest-priority readiness gaps for Lumina Living. For each gap, cite the sheet and row evidence, state the risk, propose one control, and label anything you cannot verify. |

| 5 | Verify every cited row and revise any unsupported statement.Record Pass, Corrected or Not verifiable in Prompt_Review. |

| 6 | Save the workbook with your initials and retain one screenshot of the grounded response.Use the Evidence_Register sheet; do not capture credentials. |

Acceptance test

The register identifies the active Copilot surface, grounding source, three evidence-backed gaps and a verification status for every claim.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 02: Draft a Project Brief in Word from Excel Evidence

| Alignment | K1 · A1 |

| Level and apps | Foundation · Word + Excel + Copilot |

| Folder | activities/lab-02-draft-a-project-brief-in-word |

| Excel workbook | activities/lab-02-draft-a-project-brief-in-word/Lumina-Living-Lab-02.xlsx |

| Expected output | Two-page launch brief with cited objectives, milestones, risks and open questions. |

Goal. Turn a structured campaign register into a concise Word project brief without inventing scope or dates.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Draft a two-page project brief for Lumina Living's Q4 Sustainable Workspace campaign. Use only the attached Campaign_Register workbook. Include purpose, measurable objectives, scope, milestones, roles, top risks and open questions. Mark missing information as [TO CONFIRM]. Use a confident, neutral business tone.

Detailed procedure

| 1 | Open the Campaign_Register workbook and filter Status to Active.Check that the active rows reconcile to the Summary control. |

| 2 | Open the supplied Word brief template.Keep the headings and document metadata block. |

| 3 | Attach or reference the workbook in Copilot for Word.Use the file picker rather than copying confidential rows into a web-grounded chat. |

| 4 | Create the first draft using the supplied prompt.PromptDraft a two-page project brief for Lumina Living's Q4 Sustainable Workspace campaign. Use only the attached Campaign_Register workbook. Include purpose, measurable objectives, scope, milestones, roles, top risks and open questions. Mark missing information as [TO CONFIRM]. Use a confident, neutral business tone. |

| 5 | Compare each date, owner and target with the workbook.Highlight corrected facts in yellow during review, then remove highlighting after approval. |

| 6 | Ask Copilot to tighten the executive summary to 120 words.PromptRewrite only the executive summary in no more than 120 words. Preserve every verified number and [TO CONFIRM] marker. |

| 7 | Save the final brief and record the filename in the workbook Evidence_Register.Do not overwrite the starter template. |

Acceptance test

The brief matches the workbook, contains no invented facts and retains [TO CONFIRM] markers for missing evidence.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 03: Refine a Responsible Copilot Use Policy in Word

| Alignment | K1 · A1 |

| Level and apps | Intermediate · Word + Excel + Copilot |

| Folder | activities/lab-03-refine-a-policy-with-word |

| Excel workbook | activities/lab-03-refine-a-policy-with-word/Lumina-Living-Lab-03.xlsx |

| Expected output | Approved policy draft, issue log and staff quick-reference checklist. |

Goal. Use Word Copilot to consolidate review feedback while retaining governance controls and an audit trail.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Revise the attached Responsible Copilot Use Policy using the Review_Log workbook. Resolve only items marked Approved. Preserve the sections on data classification, human review, prohibited inputs, attribution, incident escalation and record retention. Add a one-page staff checklist and a change summary table.

Detailed procedure

| 1 | Open the policy draft and Review_Log workbook side by side.Sort the log by Decision and confirm the Approved count. |

| 2 | Ask Copilot to list proposed changes before editing.PromptCompare the policy with the Review_Log. List the exact edits required for rows marked Approved. Do not apply Pending or Rejected suggestions. |

| 3 | Validate the proposed edits against the log.Mark each approved item Ready or Needs clarification in the workbook. |

| 4 | Request the controlled revision.PromptRevise the attached Responsible Copilot Use Policy using the Review_Log workbook. Resolve only items marked Approved. Preserve the sections on data classification, human review, prohibited inputs, attribution, incident escalation and record retention. Add a one-page staff checklist and a change summary table. |

| 5 | Review policy language for enforceability and plain language.Replace vague words such as appropriate with a named owner, trigger or action where the source supports it. |

| 6 | Record each accepted change and its source row.Complete the Change_Evidence sheet. |

| 7 | Save the revised policy as a new version.Keep the original draft unchanged for comparison. |

Acceptance test

Every change traces to an Approved review row, all mandatory controls remain, and the policy includes a usable staff checklist.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 04: Build a PowerPoint Story from Word and Excel

| Alignment | K1 · A1 |

| Level and apps | Intermediate · PowerPoint + Word + Excel + Copilot |

| Folder | activities/lab-04-build-a-powerpoint-story |

| Excel workbook | activities/lab-04-build-a-powerpoint-story/Lumina-Living-Lab-04.xlsx |

| Expected output | Eight-slide leadership deck with one message per slide and a documented evidence map. |

Goal. Convert the approved brief and performance data into a decision-led presentation structure.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Create an eight-slide leadership presentation for the Sustainable Workspace campaign using the attached project brief and workbook. Build a decision-led story: context, customer need, campaign idea, target audience, timeline, budget, risks and approval request. Use concise slide titles that state the takeaway. Do not invent numbers.

Detailed procedure

| 1 | Review the Project_Brief and Presentation_Data workbook.Complete the Evidence_Map before generating slides. |

| 2 | Open the supplied blank deck and confirm the 16:9 layout.Retain the Lumina Living theme and footer. |

| 3 | Create an outline with Copilot.PromptCreate an eight-slide leadership presentation for the Sustainable Workspace campaign using the attached project brief and workbook. Build a decision-led story: context, customer need, campaign idea, target audience, timeline, budget, risks and approval request. Use concise slide titles that state the takeaway. Do not invent numbers. |

| 4 | Review the outline before creating slides.Every slide must answer why it matters or what decision is needed. |

| 5 | Generate the presentation and replace generic imagery with editable shapes or approved visuals.Do not use decorative charts or unsupported statistics. |

| 6 | Check every number against the workbook.Record slide number, source sheet and cell range in Evidence_Map. |

| 7 | Run a final accessibility and legibility check.Check title size, contrast, alt text and reading order. |

Acceptance test

The deck contains eight coherent slides, all quantitative claims trace to the workbook and the final slide asks for a specific decision.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 05: Enhance PowerPoint with Native Charts and Speaker Notes

| Alignment | K1 · A1 |

| Level and apps | Intermediate · PowerPoint + Excel + Copilot |

| Folder | activities/lab-05-enhance-powerpoint-with-charts |

| Excel workbook | activities/lab-05-enhance-powerpoint-with-charts/Lumina-Living-Lab-05.xlsx |

| Expected output | Polished deck with native trend, contribution and variance charts plus verified speaker notes. |

Goal. Use native PowerPoint charts to strengthen a leadership narrative and prepare a concise delivery.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Improve the attached leadership deck using the workbook as the only numerical source. Recommend where a trend chart, contribution chart and variance chart add decision value. For each, state the takeaway title, the correct chart type, the data range and one caveat. Then draft speaker notes of 60-90 words per chart slide.

Detailed procedure

| 1 | Open the workbook Chart_Data sheet and reconcile totals.The control row must show PASS before charting. |

| 2 | Ask Copilot to recommend chart placements.PromptImprove the attached leadership deck using the workbook as the only numerical source. Recommend where a trend chart, contribution chart and variance chart add decision value. For each, state the takeaway title, the correct chart type, the data range and one caveat. Then draft speaker notes of 60-90 words per chart slide. |

| 3 | Insert native PowerPoint charts using Insert > Chart.Use line for time trend, bar for contribution and clustered column for actual versus target. |

| 4 | Edit the embedded chart data to match the workbook.Do not paste chart screenshots. |

| 5 | Apply takeaway titles and direct labels where appropriate.Remove redundant legends and decorative 3D effects. |

| 6 | Add and review speaker notes.Notes must explain meaning, caveat and decision; they must not repeat every visual label. |

| 7 | Validate charts by comparing three sample points with the workbook.Record checks in Chart_QA. |

| 8 | Save the enhanced deck and export a PDF for review.Confirm charts remain editable in the PPTX. |

Acceptance test

The PPTX contains three editable native charts, sample values reconcile, and each chart communicates a decision-relevant takeaway.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Topic 02: Copilot for Excel: From Questions to Deep Analysis

Tables · formulas · diagnostics · scenario analysis · forecasting · Analyst agent

Key concepts

Analysis-ready data: One header row, one record per row, stable types and an Excel Table.

Progressive analysis: Start descriptive, then diagnostic, predictive and prescriptive.

Formula audit: Accept suggested formulas only after checking logic, references and edge cases.

Evidence chain: Question, method, result, caveat and action should be traceable in the workbook.

Scenario thinking: Separate assumptions from formulas and compare base, downside and upside cases.

Deep analysis: Use Analyst or advanced Copilot features to explore multiple files, patterns and forecasts when licensed.

Lab 06: Build and Audit Excel Formulas with Copilot

| Alignment | K3 · A2 |

| Level and apps | Foundation · Excel + Copilot |

| Folder | activities/lab-06-build-formulas-with-copilot |

| Excel workbook | activities/lab-06-build-formulas-with-copilot/Lumina-Living-Lab-06.xlsx |

| Expected output | Formula-driven campaign table with revenue, margin, conversion, status and error controls. |

Goal. Use Copilot to propose calculated columns while retaining formula transparency and controls.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

In the Campaign_Data table, propose formulas for Revenue, Margin, Margin_Percent, Conversion_Rate and Target_Status. Use structured references, make divisions zero-safe, and reference thresholds from the Assumptions sheet. Explain each formula and identify two edge cases to test before applying it.

Detailed procedure

| 1 | Convert the Campaign_Data range to an Excel Table.Name it tblCampaign and confirm one header row. |

| 2 | Inspect blanks, zeros and unexpected types.Record exceptions before generating formulas. |

| 3 | Submit the formula prompt.PromptIn the Campaign_Data table, propose formulas for Revenue, Margin, Margin_Percent, Conversion_Rate and Target_Status. Use structured references, make divisions zero-safe, and reference thresholds from the Assumptions sheet. Explain each formula and identify two edge cases to test before applying it. |

| 4 | Apply one formula at a time and inspect the full column.Reject any formula with hardcoded thresholds or mismatched row references. |

| 5 | Test zero impressions, zero revenue and negative cost.Use a copy of the test rows; do not corrupt the source table. |

| 6 | Create a Controls sheet.Count blanks, formula errors, negative values and rows with Review status. |

| 7 | Save the audited workbook.All controls must show PASS or an owned exception. |

Acceptance test

All derived columns use auditable formulas, zero denominators are handled intentionally and the Controls sheet contains no unexplained errors.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 07: Run Deep Descriptive and Diagnostic Analysis in Excel

| Alignment | K3 · A2 |

| Level and apps | Intermediate · Excel + Copilot |

| Folder | activities/lab-07-run-deep-descriptive-analysis |

| Excel workbook | activities/lab-07-run-deep-descriptive-analysis/Lumina-Living-Lab-07.xlsx |

| Expected output | Diagnostic workbook with KPI summary, segment analysis, anomaly log and management findings. |

Goal. Move from summary statistics to segmented drivers, anomalies and evidence-backed explanations.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Analyse the Campaign_Data table in four passes: descriptive, segmented, anomaly and diagnostic. Calculate volume, revenue, margin, conversion and return metrics; compare channel, region and product; flag unusual values using robust rules; then propose three likely drivers. Separate observed evidence from hypotheses and cite the supporting table or chart.

Detailed procedure

| 1 | Confirm the data table grain and period.One row must represent one campaign-week-product combination. |

| 2 | Ask Copilot for a staged analysis plan.PromptAnalyse the Campaign_Data table in four passes: descriptive, segmented, anomaly and diagnostic. Calculate volume, revenue, margin, conversion and return metrics; compare channel, region and product; flag unusual values using robust rules; then propose three likely drivers. Separate observed evidence from hypotheses and cite the supporting table or chart. |

| 3 | Build descriptive KPI formulas and reconcile totals.Use SUMIFS, COUNTIFS, AVERAGEIFS, MEDIAN and STDEV.S where appropriate. |

| 4 | Create PivotTables for channel, region and product.Show revenue, margin, conversion and return rate with consistent number formats. |

| 5 | Create trend and variance charts.Use native Excel charts and label period and unit. |

| 6 | Investigate anomalies.Record the row key, rule, observed value, possible cause and verification owner. |

| 7 | Ask Copilot to critique the findings.PromptChallenge these findings. Identify alternative explanations, missing data and any claim that is stronger than the evidence. |

| 8 | Write the management findings.Each finding must include evidence, caveat, action and owner. |

Acceptance test

The workbook separates facts from hypotheses, reconciles totals, documents anomalies and presents three defensible findings with caveats.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 08: Forecast and Stress-Test a Campaign with Copilot

| Alignment | K3 · A2 |

| Level and apps | Advanced · Excel + Analyst agent |

| Folder | activities/lab-08-forecast-and-stress-test |

| Excel workbook | activities/lab-08-forecast-and-stress-test/Lumina-Living-Lab-08.xlsx |

| Expected output | Forecast model with base, downside and upside scenarios, sensitivity table and decision guardrails. |

Goal. Use forecasting, scenarios and sensitivity analysis to evaluate a transition plan under uncertainty.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Using the historical monthly data, build a 6-month forecast for revenue and workload. Explain the method, assumptions and confidence limits. Then test downside, base and upside scenarios for conversion, average order value and service capacity. Identify the earliest month capacity is breached and recommend a guarded action. Do not claim certainty beyond the data.

Detailed procedure

| 1 | Review historical coverage and missing periods.Record why the data is or is not suitable for forecasting. |

| 2 | Ask Copilot or Analyst for a forecast plan.PromptUsing the historical monthly data, build a 6-month forecast for revenue and workload. Explain the method, assumptions and confidence limits. Then test downside, base and upside scenarios for conversion, average order value and service capacity. Identify the earliest month capacity is breached and recommend a guarded action. Do not claim certainty beyond the data. |

| 3 | Create a Forecast sheet with explicit assumptions.Keep hardcoded inputs separate from formula outputs. |

| 4 | Build base, downside and upside cases.Use cell references rather than embedding percentages in formulas. |

| 5 | Create a sensitivity table for conversion and capacity.Highlight the breach boundary without 3D effects. |

| 6 | Compare Copilot findings with workbook calculations.Resolve discrepancies before using the narrative. |

| 7 | Document method limitations and monitoring triggers.State what new evidence would change the decision. |

| 8 | Save the model and a one-page decision summary.The summary must include forecast range, breach month, action and guardrail. |

Acceptance test

All scenarios are formula-driven, forecast uncertainty is explicit and the recommended action is linked to a measurable trigger.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Topic 03: Copilot for Outlook, Teams and Loop

Inbox triage · thread summaries · meeting intelligence · shared plans · human-send controls

Key concepts

Communication workflow: Triage, understand, draft, coach, approve and send.

Meeting lifecycle: Prepare, facilitate, capture, assign and follow through.

Work context: Ground summaries and actions in authorised files, chats, meetings and email.

Human-send gate: Copilot drafts messages; a responsible person verifies recipients, facts and attachments before sending.

Loop as living plan: Components keep tasks, decisions and status synchronised across apps.

Opportunity evaluation: Adopt only when value, risk, readiness, owner and success measure are explicit.

Lab 09: Triage an Outlook Inbox and Draft a Controlled Reply

| Alignment | K2 · A3 |

| Level and apps | Intermediate · Outlook + Excel + Copilot |

| Folder | activities/lab-09-triage-and-draft-in-outlook |

| Excel workbook | activities/lab-09-triage-and-draft-in-outlook/Lumina-Living-Lab-09.xlsx |

| Expected output | Inbox triage register, verified thread summary and one approval-ready draft reply. |

Goal. Use Copilot to summarise, prioritise and draft without bypassing recipient and fact checks.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Using the Inbox_Register and the selected email thread, produce: (1) a five-line summary, (2) decisions and unanswered questions, (3) priority with rationale, and (4) a draft reply that acknowledges the issue, answers only supported points, assigns next actions and requests missing information. Do not send. Flag any recipient, date or attachment that requires verification.

Detailed procedure

| 1 | Open the Inbox_Register and review the priority rules.Confirm VIP, deadline, risk and dependency fields. |

| 2 | Select one supplied thread in Outlook or the lab message pack.Do not use a live personal mailbox for this exercise. |

| 3 | Generate a thread summary.PromptUsing the Inbox_Register and the selected email thread, produce: (1) a five-line summary, (2) decisions and unanswered questions, (3) priority with rationale, and (4) a draft reply that acknowledges the issue, answers only supported points, assigns next actions and requests missing information. Do not send. Flag any recipient, date or attachment that requires verification. |

| 4 | Verify people, dates, commitments and attachment names.Record each check in Draft_QA. |

| 5 | Refine tone for the recipient.PromptMake the reply concise, constructive and accountable. Preserve all verified facts and open questions. |

| 6 | Run the human-send gate.Check To, Cc, subject, commitments, confidentiality and attachments. |

| 7 | Save the draft without sending.Record Draft ready and the approver in the workbook. |

Acceptance test

The draft remains unsent, all facts and recipients are checked, and the triage register shows priority, owner and next action.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 10: Run an Action-Oriented Teams Meeting

| Alignment | K2 · A3 |

| Level and apps | Intermediate · Teams + Excel + Copilot |

| Folder | activities/lab-10-run-an-action-oriented-teams-meeting |

| Excel workbook | activities/lab-10-run-an-action-oriented-teams-meeting/Lumina-Living-Lab-10.xlsx |

| Expected output | Meeting brief, decision log, action register and reviewed follow-up message. |

Goal. Use meeting preparation, Facilitator or recap capabilities to convert discussion into owned outcomes.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Prepare a 30-minute campaign readiness meeting using the Meeting_Register. Create an outcome-led agenda, five decision questions and required pre-reads. After the simulated meeting, summarise decisions, actions, owners, due dates, risks and unresolved questions. Do not invent agreement; label uncertain items for confirmation.

Detailed procedure

| 1 | Review the Meeting_Register and filter unresolved risks.Select only items requiring group decision. |

| 2 | Generate the agenda and decision questions.PromptPrepare a 30-minute campaign readiness meeting using the Meeting_Register. Create an outcome-led agenda, five decision questions and required pre-reads. After the simulated meeting, summarise decisions, actions, owners, due dates, risks and unresolved questions. Do not invent agreement; label uncertain items for confirmation. |

| 3 | Configure meeting AI settings according to the trainer demonstration.Use Facilitator or recap only where the training tenant permits it. |

| 4 | Run the simulated discussion and capture notes.Participants must confirm sensitive or consequential statements. |

| 5 | Review the recap against the notes.Correct owners, dates and decisions before sharing. |

| 6 | Transfer approved actions into the Excel register.One action per row with owner, due date and status. |

| 7 | Draft the follow-up message.State decisions, actions and unresolved questions; retain a human-send gate. |

Acceptance test

The action register reconciles with the reviewed meeting recap and every action has one owner, due date and status.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 11: Build a Living Implementation and Training Plan in Loop

| Alignment | K2 · A3 · A4 |

| Level and apps | Advanced · Loop + Teams + Excel + Copilot |

| Folder | activities/lab-11-build-a-loop-implementation-plan |

| Excel workbook | activities/lab-11-build-a-loop-implementation-plan/Lumina-Living-Lab-11.xlsx |

| Expected output | Loop workspace design, transition backlog, training matrix and adoption dashboard. |

Goal. Translate adoption risks into a living implementation plan and role-based staff enablement schedule.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Create a Microsoft Loop implementation workspace for the Copilot rollout. Use the Transition_Register to produce objectives, workstreams, milestones, risks, decisions, a role-based training matrix and weekly adoption measures. Keep accountable owners and due dates. Distinguish confirmed decisions from proposals.

Detailed procedure

| 1 | Review the Transition_Register and identify workstreams.Group by People, Process, Data, Technology and Governance. |

| 2 | Create a Loop workspace and page structure.Use pages for Overview, Backlog, Decisions, Training and Measures. |

| 3 | Generate the initial plan.PromptCreate a Microsoft Loop implementation workspace for the Copilot rollout. Use the Transition_Register to produce objectives, workstreams, milestones, risks, decisions, a role-based training matrix and weekly adoption measures. Keep accountable owners and due dates. Distinguish confirmed decisions from proposals. |

| 4 | Convert key lists to Loop tables or task lists.Keep shared components small and decision-focused. |

| 5 | Share one component into Teams or Outlook.Verify access before sharing. |

| 6 | Update the Excel Training_Matrix from the approved Loop plan.Record role, task, learning method, evidence and owner. |

| 7 | Define adoption measures and review cadence.Include usage, quality, time saved, error rate and exception count. |

| 8 | Save evidence screenshots without credentials.Record the workspace link only in the private class copy. |

Acceptance test

The plan covers transition risks and staff training, distinguishes decisions from proposals and has measurable adoption controls.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Topic 04: Microsoft 365 Copilot Agents and Governed Pipelines

Agent types · instructions · knowledge · actions · approvals · monitoring · staff enablement

Key concepts

Agent role: An agent applies scoped instructions and knowledge to a repeatable business outcome.

Agent spectrum: Retrieval agents answer; task agents act; autonomous agents coordinate multi-step work.

Pipeline: Intake, validate, classify, enrich, produce, approve, deliver and monitor.

Least privilege: Give the agent only the data and actions required for its defined role.

Approval boundary: Consequential writes, sends and status changes require visible human approval.

Operational readiness: Pilot with test cases, exception handling, owners, metrics, training and rollback.

Lab 12: Design a Scoped Microsoft 365 Copilot Agent

| Alignment | K4 · A4 |

| Level and apps | Foundation Agent · Microsoft 365 Copilot agents + Excel |

| Folder | activities/lab-12-design-a-copilot-agent |

| Excel workbook | activities/lab-12-design-a-copilot-agent/Lumina-Living-Lab-12.xlsx |

| Expected output | Agent design canvas, knowledge register, risk controls and ten acceptance tests. |

Goal. Define an agent's job, knowledge, boundaries, test cases and ownership before building it.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Design a Campaign Intake Agent for Lumina Living. It should answer process questions, validate an intake record and recommend the next route. Define its purpose, intended users, allowed knowledge, required inputs, outputs, refusal rules, escalation conditions and success measures. The agent must not approve budgets, send email or change official status.

Detailed procedure

| 1 | Review the Agent_Design workbook and sample intake records.Identify which fields are mandatory, sensitive and decision-critical. |

| 2 | Write one measurable agent outcome.Avoid a broad goal such as help with campaigns. |

| 3 | Draft the agent design.PromptDesign a Campaign Intake Agent for Lumina Living. It should answer process questions, validate an intake record and recommend the next route. Define its purpose, intended users, allowed knowledge, required inputs, outputs, refusal rules, escalation conditions and success measures. The agent must not approve budgets, send email or change official status. |

| 4 | Map allowed knowledge and actions.Apply least privilege; exclude personal or unrelated files. |

| 5 | Write ten tests including happy path, missing data, conflicting data, prompt injection and prohibited action.Record expected result before running each test. |

| 6 | Assign owner, approver and monitoring cadence.Separate content owner from technical owner where appropriate. |

| 7 | Review the design against A4 staff-training needs.Identify which users need orientation, practice and support. |

Acceptance test

The agent has a narrow purpose, explicit non-actions, least-privilege knowledge and ten test cases with expected outcomes.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 13: Build an Intake and Routing Agent

| Alignment | K4 · A4 |

| Level and apps | Intermediate Agent · Copilot Studio / Agent Builder + Excel |

| Folder | activities/lab-13-build-an-intake-and-routing-agent |

| Excel workbook | activities/lab-13-build-an-intake-and-routing-agent/Lumina-Living-Lab-13.xlsx |

| Expected output | Working intake agent, controlled instructions, knowledge source and routed test results. |

Goal. Build a retrieval-and-routing agent that validates inputs and escalates exceptions.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

You are the Lumina Living Campaign Intake Agent. Use only the approved campaign process knowledge. Ask for Campaign Name, Sponsor, Objective, Audience, Budget Band, Launch Date and Data Classification. Validate completeness; summarise the request; recommend one route: Standard Review, Fast-Track Review or Specialist Review. Explain the rule used. Never approve, send or modify the official register. Escalate conflicting, restricted or incomplete cases.

Detailed procedure

| 1 | Create the agent in the tenant surface demonstrated by the trainer.Use Agent Builder or Copilot Studio according to available licensing. |

| 2 | Add the approved process document as knowledge.Do not connect a broad SharePoint site for a narrow lab agent. |

| 3 | Paste and refine the system instructions.PromptYou are the Lumina Living Campaign Intake Agent. Use only the approved campaign process knowledge. Ask for Campaign Name, Sponsor, Objective, Audience, Budget Band, Launch Date and Data Classification. Validate completeness; summarise the request; recommend one route: Standard Review, Fast-Track Review or Specialist Review. Explain the rule used. Never approve, send or modify the official register. Escalate conflicting, restricted or incomplete cases. |

| 4 | Configure conversation starters.Use one complete, one incomplete and one policy question. |

| 5 | Run the ten test cases from Excel.Capture actual route, explanation, citation and pass/fail. |

| 6 | Fix instructions or knowledge gaps.Change one variable at a time and retest. |

| 7 | Publish only to the trainer-approved test audience.Record version and owner in Agent_Register. |

Acceptance test

The agent gathers mandatory fields, cites approved knowledge, routes correctly and refuses approval or external-send requests.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 14: Connect an Agent to a Controlled Action

| Alignment | K4 · A4 |

| Level and apps | Advanced Agent · Copilot Studio + Power Automate + Excel |

| Folder | activities/lab-14-connect-agent-to-a-controlled-action |

| Excel workbook | activities/lab-14-connect-agent-to-a-controlled-action/Lumina-Living-Lab-14.xlsx |

| Expected output | Agent-to-queue flow with validation, approval state, response ID and run audit. |

Goal. Add an action that writes a validated intake to a controlled queue while preserving approval and audit evidence.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Extend the Campaign Intake Agent with one controlled action: create a Draft queue record only after required fields pass validation. Return the Queue ID and Draft status. If data is missing, restricted or conflicting, do not call the action; explain the issue and route to a human. Never mark Approved and never send external email.

Detailed procedure

| 1 | Open the Action_Map workbook and inspect required input/output schema.Campaign ID must remain the idempotency key. |

| 2 | Create a Power Automate flow or agent action with explicit inputs.Include Campaign ID, sponsor, route, summary and classification. |

| 3 | Add validation before the write step.Terminate safely when mandatory data is missing or restricted. |

| 4 | Add the action to the agent.PromptExtend the Campaign Intake Agent with one controlled action: create a Draft queue record only after required fields pass validation. Return the Queue ID and Draft status. If data is missing, restricted or conflicting, do not call the action; explain the issue and route to a human. Never mark Approved and never send external email. |

| 5 | Test one valid, one incomplete and one duplicate case.A duplicate Campaign ID must not create a second active queue record. |

| 6 | Record the run ID, input hash, result and reviewer.Use Run_Audit in the workbook. |

| 7 | Review permissions and connection ownership.Document the service/owner account and least-privilege scope. |

| 8 | Keep the action in test mode.Do not connect production mailboxes or lists during class. |

Acceptance test

Only validated cases create Draft records, duplicate submissions are controlled and every run has traceable evidence.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 15: Create an Analysis-to-Deck Agent Pipeline

| Alignment | K4 · A4 |

| Level and apps | Advanced Pipeline · Microsoft 365 Copilot + Analyst + PowerPoint + Excel |

| Folder | activities/lab-15-create-an-analysis-to-deck-pipeline |

| Excel workbook | activities/lab-15-create-an-analysis-to-deck-pipeline/Lumina-Living-Lab-15.xlsx |

| Expected output | Three-stage pipeline specification, analysis workbook, chart-led decision deck and approval log. |

Goal. Orchestrate intake, Excel analysis and a PowerPoint decision pack with human approval between stages.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

For each Approved-for-Analysis queue item: validate the workbook, produce a descriptive and diagnostic analysis, identify three evidence-backed findings, create a six-slide decision deck with native charts, and stop at Ready for Review. Record sources, assumptions and exceptions. Do not publish or email the deck until a named reviewer approves it.

Detailed procedure

| 1 | Review Pipeline_Control and choose one Approved-for-Analysis item.Confirm reviewer and required output. |

| 2 | Define the three stages and their entry/exit criteria.Stage 1 Validate; Stage 2 Analyse; Stage 3 Present. |

| 3 | Run the analysis prompt with the attached workbook.PromptFor each Approved-for-Analysis queue item: validate the workbook, produce a descriptive and diagnostic analysis, identify three evidence-backed findings, create a six-slide decision deck with native charts, and stop at Ready for Review. Record sources, assumptions and exceptions. Do not publish or email the deck until a named reviewer approves it. |

| 4 | Verify formulas, totals, segments and anomalies.No deck generation until the analysis control is PASS. |

| 5 | Create the six-slide PowerPoint with native charts.Use takeaway titles and keep chart data editable. |

| 6 | Record source ranges for every quantitative slide.Complete Deck_Evidence. |

| 7 | Run the reviewer checkpoint.Reviewer can Approve, Return for correction or Reject. |

| 8 | Update pipeline status without sending.Stop at Ready for Review or Approved for Delivery. |

Acceptance test

The pipeline stops at review, the workbook reconciles, the deck has editable charts and every quantitative claim has a source range.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Lab 16: Operate a Governed End-to-End Copilot Pipeline

| Alignment | K1-K4 · A1-A4 |

| Level and apps | Capstone Pipeline · Microsoft 365 Copilot agents + Outlook + Teams + Excel |

| Folder | activities/lab-16-operate-a-governed-copilot-pipeline |

| Excel workbook | activities/lab-16-operate-a-governed-copilot-pipeline/Lumina-Living-Lab-16.xlsx |

| Expected output | End-to-end pilot run, approved Outlook draft, Teams handover, monitoring dashboard and staff training plan. |

Goal. Operate the complete intake-to-delivery pipeline with approvals, exception handling, monitoring and staff handover.

Before you begin

Use only the synthetic files supplied in this lab folder.

Start from the learner Excel workbook; open completed/ only after your own attempt.

Confirm the Microsoft 365 surface and licence available in the training tenant.

Never include a password, recovery code or unrelated personal data in a prompt or screenshot.

Keep consequential actions—approval, external send, official status change—behind a named human checkpoint.

Primary prompt

Operate the Lumina Living campaign pipeline on the attached pilot cases. Process each case through Intake, Validation, Routing, Analysis, Deck, Approval and Delivery Draft. At every stage record status, owner, timestamp, evidence and exception. Produce an Outlook draft and Teams handover only for approved cases; never send automatically. Summarise throughput, cycle time, exception rate, rework and human overrides, then recommend whether to expand, revise or stop the pilot.

Detailed procedure

| 1 | Review the Pilot_Cases and Pipeline_Control sheets.Confirm stage owners and approval rules. |

| 2 | Process all pilot cases through intake and validation.Incomplete or restricted cases must divert to exception handling. |

| 3 | Run routing and analysis only for eligible cases.PromptOperate the Lumina Living campaign pipeline on the attached pilot cases. Process each case through Intake, Validation, Routing, Analysis, Deck, Approval and Delivery Draft. At every stage record status, owner, timestamp, evidence and exception. Produce an Outlook draft and Teams handover only for approved cases; never send automatically. Summarise throughput, cycle time, exception rate, rework and human overrides, then recommend whether to expand, revise or stop the pilot. |

| 4 | Create or validate the decision deck for one approved case.Check charts, sources and limitations. |

| 5 | Complete the human approval checkpoint.Approver signs the Approval_Log before any delivery draft. |

| 6 | Create an Outlook draft and Teams handover.Verify recipients and keep both unsent/unpublished until trainer review. |

| 7 | Calculate pilot KPIs in Excel.Use formulas for throughput, median cycle time, exception rate, rework and override rate. |

| 8 | Create the staff training and support plan.Map role, task, risk, learning activity, evidence and support owner. |

| 9 | Write the scale decision.Choose Expand, Revise or Stop with evidence, guardrails and next review date. |

Acceptance test

All pilot cases have a complete audit trail, delivery remains human-controlled and the scale decision is supported by measured operational evidence.

Evidence to retain

Completed Excel workbook with Prompt_Log, Evidence_Register and Acceptance_Check updated.

The app-specific Word, PowerPoint, Outlook, Teams, Loop or agent artifact named in the expected output.

A credential-safe screenshot or PDF of the final state.

A short explanation of source verification, limitation, exception and human approval.

Quick Prompt Reference

| Purpose | Reusable prompt pattern |

| Grounded summary | Using only [source], summarise [topic] for [audience]. Cite the supporting section or row and mark anything unverified. |

| Draft from evidence | Create [artifact] for [audience] using [sources]. Preserve verified facts, label missing information and follow [tone/format]. |

| Deep Excel analysis | Analyse in descriptive, segmented, anomaly and diagnostic passes. Separate observations from hypotheses and cite the supporting table or chart. |

| Agent guardrail | Use only [knowledge]. You may [allowed actions]. You must not [prohibited actions]. Escalate when [conditions]. |

| Critique | Challenge this output. Identify unsupported claims, alternative explanations, missing evidence, risk and the minimum verification required. |

Assessment Flow

Complete TRAQOM / SSG digital attendance.

Complete assessment digital attendance.

Sit the 60-minute Written Assessment followed by the 60-minute Practical Performance assessment.

Upload completed papers and required evidence to the LMS.

Sign the Assessment Summary Record.

LMS: https://lms-tms.tertiaryinfotech.com/

Support

Email: enquiry@tertiaryinfotech.com

Telephone: +65 6100 0613

Website: www.tertiarycourses.com.sg

Microsoft 365 agents connected to SharePoint

TGS-2024043856 | Enhancement v8.1 | 7 September 2026

This extension continues Labs 12 to 16 using the existing Lumina Living scenario. Keep the original workbooks and activities. Build a source-grounded agent, inspect its citations, and record a human-reviewed result in the existing Excel evidence register.

Training workspace

Open https://tertiaryinfotech.sharepoint.com/sites/TGS-2024043856-LuminaCopilot using your trainer-assigned work account. The site is private. Training 1 is the owner; Training 2 and TIA Admin are members. The site contains synthetic training content. Credentials must never appear in prompts, workbook cells or screenshots.

A consumer Microsoft account cannot replace a work account in this tenant. The original materials may show earlier consumer training addresses; use the tenant accounts assigned by the trainer for these SharePoint activities.

Choose the correct agent surface

A SharePoint agent answers questions from selected SharePoint content and is stored as an .agent file. Microsoft 365 Copilot Agent Builder lets a maker configure an agent and select knowledge sources in the Copilot application. Copilot Studio supports more extensive workflow and action design. A knowledge source is not an action connector: adding a site does not grant the ability to send email, approve a claim or update a business record.

The available features depend on the account licence, tenant policy and current product surface. Before class, the trainer should open the actual agent with each assigned account and confirm that it can answer from the intended source. A missing licence or metered-usage configuration must be resolved by the tenant administrator; do not purchase or enable billing during the exercise.

Lab 12 extension Create the policy agent

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

Lab 13 extension Recommend service routing

Create TGS-2024043856 Lumina Routing Agent using Lumina-Service-Routing.docx as its source. Use its matching instructions in agent-configs.json. Keep the original intake workbook as the controlled input and evidence register.

Prompt: Request REQ-101 reports a damaged chair and a delivery due tomorrow. Recommend the queue and priority. Return Request ID, recommended queue, recommended priority, cited rule, missing information and human reviewer. Do not submit a ticket.

Verify Operations and high priority against SR-01. A damaged item does not prove an unsafe product; urgent review requires the relevant reported facts. Try a request with no delivery date and require a clarification instead of an invented deadline. The learner manually records the approved recommendation in Excel after review.

Lab 14 extension Separate knowledge from actions

Use the original controlled-action exercise after the routing recommendation. In a knowledge-only SharePoint agent, no business record is changed. If the class uses a separately configured Copilot Studio action or flow, inspect its connection identity, inputs and approval stage before testing. Record the actual action result identifier only after a successful run. Never use an agent sentence such as submitted successfully as proof of a write.

Use three distinct evidence states in Excel: Recommended, Human reviewed, and Action verified. A failed action stays failed even if the natural-language response sounds successful. Do not enable unattended production sends during this training.

Lab 15 extension Draft a campaign update

Create TGS-2024043856 Lumina Campaign Agent with Lumina-Campaign-Brief.docx. Apply the campaign instructions in agent-configs.json. Ask: Draft a launch update including the budget, target enquiries, launch date and outstanding human reviews. Cite each factual claim and label it DRAFT FOR MARKETING REVIEW.

Check SGD 18000, 120 qualified enquiries and 1 October 2026 against CAM-2026-Q4. Ask the agent to add a carbon-neutral claim; it should flag the lack of supporting evidence. Transfer only verified facts into the existing Word or PowerPoint output. The agent does not automatically create or publish the full analysis-to-deck pipeline.

Lab 16 extension Verify sharing and maintain sources

1. Open the site's membership panel and confirm the intended Training 1, Training 2 and admin identities. Site membership is separate from proof that a particular agent and source open correctly.

2. Locate the saved .agent file. Use its Share or Copy link command for the intended users. Prefer named people or people with existing access. Verify the underlying source remains in the same private course site.

3. Open the agent using the separately assigned Training 2 account. Confirm the expense source opens and the taxi question returns a valid citation. Repeat for the admin account when available. Do not label a membership-only check as a completed sign-in test.

4. In a learner-owned copy, change a harmless policy example and increment its version. Wait for source readiness and ask the same question again. Record the version and actual citation. Do not overwrite the shared class baseline without the trainer's direction.

5. Test an unknown answer, missing input, unsupported marketing claim and absent action result. Retain failures as well as passes in the original Lab 16 workbook.

6. Record agent owner, source owner, review date and retirement decision. Remove obsolete learner copies through the site's normal recoverable file workflow when instructed by the trainer.

Evidence and troubleshooting

Use the existing Prompt_Log, Evidence_Register and Acceptance_Check sheets. For each test record account role, agent name, source filename and version, exact question, response excerpt, citation target, expected result, actual result, status and reviewer.

If the agent opens but a citation is inaccessible, inspect source permissions using the intended account. If a source is Preparing, verify readiness before repeating the test. If facts differ, inspect the cited document and source selection. If general knowledge appears, tighten the source and prompt and record the limitation; instructions alone are not a security boundary. If sharing fails, inspect both agent and source access rather than making the site public.

Applying the two reference ebooks

Jess Stratton's Copilot for Microsoft 365 (Apress, 2024), Chapter 2, explains grounding through workplace context; Chapter 3, printed page 43 (PDF page 60), stresses factual verification even when prose sounds convincing. Apply both ideas here: select the authoritative SharePoint file, request its supporting section, and compare the response with that section before using it. A citation is a route to evidence, not an automatic pass.

Microsoft Copilot AI Integration in Office 365, Chapter 4, PDF pages 44–45, discusses Microsoft Graph as a connection to workplace information and the value of context across applications. Use this as a workflow concept: a maintained campaign brief supplies facts to an agent; a person verifies those facts; Word or PowerPoint turns them into an audience-appropriate draft. This course's source-only agents do not automatically orchestrate applications or write business records. Current Microsoft documentation and the live tenant determine available features.

For Lab 15, make a four-row fact ledger in the existing evidence workbook: budget, enquiry target, launch date and environmental claim. Enter the source section and verification decision beside each row. Draft a 90-word update for a sales manager using the three supported facts; leave the unsupported environmental claim out. Then adapt the same checked facts into a three-slide narrative: objective, campaign plan and decisions needed. Compare the numbers and date across the workbook, draft and deck. Record corrections before release.

For Lab 12, compare two prompts: Explain the expense policy; and Explain whether a SGD 48 client-visit taxi fare is eligible, cite the relevant section, identify missing facts, and do not approve it. Record which response gives a reviewable decision and why. This is an original practice exercise applying the ebooks' context and verification themes.

Reading references are retained privately in the reference folder; the teaching examples and diagrams are original. Neither ebook is the authority for current agent menus, licensing or product limits.

Official product references

- Microsoft Learn, Copilot architecture: https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-architecture

- Microsoft Support, Create an agent in SharePoint: https://support.microsoft.com/en-US/sharepoint/copilot-in-sharepoint/create-an-agent-in-sharepoint

- Microsoft Learn, Add knowledge sources: https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder-add-knowledge

- Microsoft Learn, Share and manage agents: https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder-share-manage-agents

Product guidance checked 7 September 2026. The source documents and worked examples in this extension are original synthetic teaching material.

Lumina Living connected workflow

Current v8.2 activity instructions below define the class tasks and assessment preparation. Earlier lab pages retain technique explanations; use these current source files, outputs and acceptance checks where they differ.

Open the live TGS-2024043856-LuminaCopilot SharePoint site

Sign in with the trainer-assigned tenant account. Membership verified: TIA Training1 Owner; TIA Admin and TIA Training2 Members. Anonymous Anyone links are not offered in this tenant. The live Lumina-HR-Employee-Knowledge.docx (HR-DEMO-01) and TGS-2024043856 Lumina HR Employee Agent were created and tested on 7 September 2026. They contain department-level synthetic employee readiness and HR rules. The full 56-row employee register and additional financial/marketing source pack are supplied locally; upload them before selecting them as additional agent knowledge.

Three four-part prompt examples

Lumina Living Pte Ltd | SW-2026 | v8.2

HR policy in Word

Goal: Draft a staff enablement and responsible Copilot use policy for Lumina Living.

Context: You support HR for project SW-2026. The audience is 56 assigned staff and their managers; the launch is 1 October 2026.

Source: Use Lumina-HR-Facts.docx and Lumina-Travel-and-Expenses.docx only. Cite HR-01 or EXP-01 sections.

Expectations: Produce a two-page draft with responsibilities, four-hour training requirement, review and escalation rules, and a staff checklist. Flag missing facts; do not invent leave or pay terms. Label DRAFT FOR HR REVIEW.

Business analysis in Excel

Goal: Identify three evidence-backed findings for the SW-2026 readiness decision and create charts.

Context: Mei needs a management briefing from January–June historical trading data and the 7 September staff-readiness snapshot. October targets are plans, not actual results.

Source: Use Lumina-Business-Data.xlsx: Campaign_Data, Monthly, Channels and HR_Readiness.

Expectations: Use formulas for revenue, cost, margin and completion; create a monthly revenue line chart, channel-margin bar chart and training-completion bar chart. Verify 96 records and 47/56 trained; cite ranges and label assumptions. Carry the checked charts into a one-page Word report.

Marketing presentation and handoff

Goal: Create a six-slide SW-2026 decision presentation, then prepare a consistent team handoff.

Context: The audience is Lumina leadership and HR, Marketing, Finance and Operations leads. They need a launch-readiness decision, not a sales pitch.

Source: Use Lumina-Management-Report.docx, Lumina-HR-Policy.docx and Lumina-Campaign-Brief.docx; use the verified Excel chart data.

Expectations: Show budget SGD 18,000, target 120 enquiries, launch 1 October, verified charts, risks and named decisions. Then draft a 150-word Outlook email, a 120-word Teams update and Loop tasks with unchanged action IDs. Review before a manual sandbox post; do not claim a send or post occurred.

Lab 01 Set up the Lumina project and compare prompts

Course: TGS-2024043856 | Version: v8.2 | Apps: Microsoft 365 Copilot Chat + Excel | Alignment: K1 · A1

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Project intake and source register.

Input and handoff

Use Lumina-Company-Brief.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-01.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is SW-2026-Source-Register.xlsx.

Four-part prompt

Goal: Identify the project objective, four department owners, source authority and missing facts. Compare a vague prompt with a complete Goal–Context–Source–Expectations prompt.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Company-Brief.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save SW-2026-Source-Register.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-01.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Create a personal SW-2026 folder in your assigned OneDrive or SharePoint location. Keep the shared class baseline unchanged.

2. Read the Company Brief and inventory the files in scenario/. Record owner, version, purpose and confidentiality in the original Excel evidence workbook.

3. In Copilot Chat, compare “Help with our launch” with the complete four-part prompt above. Record both outputs and the missing facts they reveal.

4. Save your project source register and hand its file link to Lab 2.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and SW-2026-Source-Register.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Lab 02 Draft the cross-department launch brief in Word

Course: TGS-2024043856 | Version: v8.2 | Apps: Word + Excel + Copilot | Alignment: K1 · A1

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Project brief.

Input and handoff

Use Lumina-Company-Brief.docx; Lumina-Campaign-Brief.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-02.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Launch-Brief.docx.

Four-part prompt

Goal: Create a two-page launch brief with objectives, owners, dates, dependencies, HR training and business evidence needs. Cite the supplied source sections and identify unresolved questions.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Company-Brief.docx; Lumina-Campaign-Brief.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Launch-Brief.docx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-02.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open Word and save a new Lumina-Launch-Brief.docx in your personal project folder. Open Copilot and select the reference-file control or attach the named sources available in your tenant.

2. Use the four-part prompt. If file referencing is unavailable, paste the relevant source excerpts with filenames and section labels.

3. Check budget, enquiry target, launch date and the four owners against the brief. Add a Dependencies section linking HR training, business analysis and Operations readiness.

4. Save the draft and source/evidence links. This Word brief becomes the narrative input to Lab 4.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Launch-Brief.docx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Marketing and strategy handoff

Complete the corresponding steps in GROUNDED-RESEARCH.md, included in this folder. Use the local scenario source pack and prepared reports; save your own cited marketing/strategy outputs for the final deck and communication handoff.

Lab 03 Create and review the HR policy in Word

Course: TGS-2024043856 | Version: v8.2 | Apps: Word + Excel + Copilot | Alignment: K1 · A1

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is HR staff enablement.

Input and handoff

Use Lumina-HR-Facts.docx; Lumina-Travel-and-Expenses.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-03.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-HR-Policy.docx.

Four-part prompt

Goal: Create a two-page staff enablement policy with four-hour training, responsible use, review, escalation and a staff checklist. Do not invent leave, salary or remote-working entitlements. Label DRAFT FOR HR REVIEW.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-HR-Facts.docx; Lumina-Travel-and-Expenses.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-HR-Policy.docx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-03.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open the HR source facts and the expense policy. In Word, create Lumina-HR-Policy.docx and use example 1 from PROMPT-EXAMPLES.md.

2. Compare each policy clause with its source. Keep four-hour training, named review and escalation; flag the unspecified IT contact.

3. In the original Review_Log sheet, record proposed revision, source clause, reviewer decision and rationale. Apply only Approved revisions.

4. Use Word review tools to retain changes, add the staff checklist, save a new policy version and hand the reviewed copy to Labs 4, 9 and 12.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-HR-Policy.docx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Lab 04 Generate the leadership presentation from Word

Course: TGS-2024043856 | Version: v8.2 | Apps: PowerPoint + Word + Excel + Copilot | Alignment: K1 · A1

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Leadership narrative.

Input and handoff

Use Lumina-Launch-Brief.docx; Lumina-HR-Policy.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-04.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Leadership-Draft.pptx.

Four-part prompt

Goal: Create six slides: launch decision, business evidence needed, HR readiness, campaign plan, risks and actions. Leave quantitative historical charts for the verified data handoff in Labs 5–8. Preserve source references in notes.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Launch-Brief.docx; Lumina-HR-Policy.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Leadership-Draft.pptx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-04.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open the reviewed Word launch brief and HR policy. Use PowerPoint Copilot to create a presentation from the launch brief where available.

2. Ask for the six-slide narrative below. Review the generated outline before accepting slides. Add HR implications from the reviewed policy.

3. Give each slide a decision-led title and place source filenames/sections in speaker notes. Mark missing analytical figures Pending Lab 7 verification.

4. Save Lumina-Leadership-Draft.pptx. Lab 5 introduces chart transfer; Labs 7 and 15 replace provisional evidence with the learner’s verified analysis.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Leadership-Draft.pptx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Lab 05 Add Excel visualizations to Word and PowerPoint

Course: TGS-2024043856 | Version: v8.2 | Apps: PowerPoint + Excel + Copilot | Alignment: K1 · A1

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Evidence visuals.

Input and handoff

Use Lumina-Business-Data.xlsx; Lumina-Management-Report.docx; Lumina-Decision-Deck.pptx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-05.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Visual-Evidence.pptx.

Four-part prompt

Goal: Use the Monthly, Channels and HR_Readiness tables to produce three charts. Add them to the Word report and the presentation. Keep PowerPoint chart data editable, show units and source ranges, and reconcile totals.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Business-Data.xlsx; Lumina-Management-Report.docx; Lumina-Decision-Deck.pptx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Visual-Evidence.pptx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-05.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open scenario/Lumina-Business-Data.xlsx. Inspect Monthly, Channels and HR_Readiness. For this early chart-transfer practice, use the supplied verified dataset; Labs 6–8 reproduce and extend it.

2. In Excel, use Copilot or Insert Chart to create a line chart from Monthly!A1:B7, a column chart from Channels!A1:A5 and D1:D5, and a completion chart from HR_Readiness!A1:A5 and E1:E5.

3. Open the Word report. Copy the charts from Excel; use an embedded chart if supported, or a clearly labelled image with source range and date. Verify labels and numbers after pasting.

4. Open the PowerPoint decision draft. Paste an editable Excel chart or use Insert Chart and copy the verified values into its data sheet. Do not assume Copilot preserves editability.

5. Change a value in a learner copy and check the handoff behavior. Record whether each chart is embedded, linked or an image; manually refresh static copies. Save both artifacts.

Acceptance and next handoff

Verify all three chart values, labels and source ranges. Record reviewer, source version and chart editability. Save the updated Word report and Lumina-Visual-Evidence.pptx for the next activity.

Lab 06 Build the sales and financial formulas in Excel

Course: TGS-2024043856 | Version: v8.2 | Apps: Excel + Copilot | Alignment: K3 · A2

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Finance calculations.

Input and handoff

Use Lumina-Business-Data.xlsx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-06.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Analysis.xlsx.

Four-part prompt

Goal: From Campaign_Data, calculate revenue, cost, margin, conversion and return rates using formulas. Define the denominator for each rate. Check 96 source records and handle zero denominators explicitly.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Business-Data.xlsx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Analysis.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-06.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Save the source workbook as Lumina-Analysis.xlsx. Inspect the 96 records, one header row, record IDs and numeric columns.

2. Use the complete prompt to generate formulas. Review revenue minus cost for margin; use orders/clicks for conversion and returns/orders for return rate. Label zero-denominator cases rather than hiding undefined rates.

3. Reconcile revenue SGD 933,290.00, cost SGD 521,097.41 and margin SGD 412,192.59 against the original ranges. Check a zero-denominator test in a separate test row.

4. Save the workbook, formula evidence and control results for Lab 7.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Analysis.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Financial data and Copilot analysis

Use scenario/Lumina-Sales-Mock-Data.csv (96 synthetic sales summaries) and Lumina-Financial-Analysis-Sample.xlsx as the comparison sample. Revenue means sales value; Orders means order count. This is not an invoice ledger. Costs omit overhead and tax, so margin is not net profit.

Ask Copilot to add margin, margin percentage, target variance and revenue per order formulas; explain each denominator. Build monthly and channel summaries. Verify totals against the raw CSV and inspect representative formulas before trusting the sample.

Save your own financial workbook. Transfer the checked financial charts and caveats into the Word management report and PowerPoint decision deck. Use the supplied completed sample only for comparison, not as proof that Copilot ran.

Lab 07 Analyze sales, revenue and financial performance

Course: TGS-2024043856 | Version: v8.2 | Apps: Excel + Copilot | Alignment: K3 · A2

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Management analysis.

Input and handoff

Use Lumina-Analysis.xlsx; Lumina-HR-Facts.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-07.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Management-Report.docx.

Four-part prompt

Goal: Produce three evidence-backed findings, the three charts and a one-page management report. Distinguish margin from net profit, historical results from targets, and observation from causal explanation.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Analysis.xlsx; Lumina-HR-Facts.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Management-Report.docx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-07.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open your Lab 6 workbook or the scenario fallback. Use example 2 to request analysis, then inspect the actual formulas and ranges.

2. Verify Events has the highest historical margin at SGD 121,247.22; do not repeat earlier generic example findings about other channels. Check 47/56 trained and nine outstanding.

3. Create the three charts from Lab 5. Write a one-page management report in Word using the checked figures and chart images/objects.

4. Record each claim, source range, chart, caveat and proposed action in the evidence workbook. Save report and workbook for Labs 8, 9 and 15.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Management-Report.docx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Financial data and Copilot analysis

Use scenario/Lumina-Sales-Mock-Data.csv (96 synthetic sales summaries) and Lumina-Financial-Analysis-Sample.xlsx as the comparison sample. Revenue means sales value; Orders means order count. This is not an invoice ledger. Costs omit overhead and tax, so margin is not net profit.

Ask Copilot which months and channels contribute most revenue and margin, where sales miss target, and whether growth changes month to month. Create revenue/cost, actual/target and channel-margin charts. Check aggregation before drawing conclusions; compare observations with hypotheses about their causes.

Save your own financial workbook. Transfer the checked financial charts and caveats into the Word management report and PowerPoint decision deck. Use the supplied completed sample only for comparison, not as proof that Copilot ran.

Lab 08 Test launch scenarios and update the decision pack

Course: TGS-2024043856 | Version: v8.2 | Apps: Excel + Analyst agent | Alignment: K3 · A2

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Business planning.

Input and handoff

Use Lumina-Analysis.xlsx; Lumina-Management-Report.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-08.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Scenario-Analysis.xlsx.

Four-part prompt

Goal: Use June revenue as a baseline. Model explicitly assumed -10%, 0% and +10% changes with formulas and a comparison chart. Label these illustrative scenarios, not a forecast inferred from six data points. Update the report caveat and deck.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Analysis.xlsx; Lumina-Management-Report.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Scenario-Analysis.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-08.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. In your analysis workbook add a Scenarios sheet with June revenue linked from Monthly, plus assumption cells -10%,0%,+10%.

2. Calculate scenario revenue as baseline*(1+assumption). Verify the base case equals SGD 217,705. Create a comparison chart and label assumptions.

3. Ask Copilot to explain the scenario implications and what data would be needed for a defensible forecast. Do not present the three scenarios as predictions.

4. Update your Word report and deck caveat. Retain the historical analysis and save Lumina-Scenario-Analysis.xlsx.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Scenario-Analysis.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Financial data and Copilot analysis

Use scenario/Lumina-Sales-Mock-Data.csv (96 synthetic sales summaries) and Lumina-Financial-Analysis-Sample.xlsx as the comparison sample. Revenue means sales value; Orders means order count. This is not an invoice ledger. Costs omit overhead and tax, so margin is not net profit.

Ask Copilot to model revenue changes of -10%,0%,+10% from June and hold the historical direct-cost ratio constant as an explicit assumption. Chart revenue and margin by scenario. Explain missing overhead, working-capital and seasonality data; do not label this a validated forecast.

Save your own financial workbook. Transfer the checked financial charts and caveats into the Word management report and PowerPoint decision deck. Use the supplied completed sample only for comparison, not as proof that Copilot ran.

Marketing and strategy handoff

Complete the corresponding steps in GROUNDED-RESEARCH.md, included in this folder. Use the local scenario source pack and prepared reports; save your own cited marketing/strategy outputs for the final deck and communication handoff.

Transition-plan rehearsal

Using A01–A04 from the shared action register, create a transition table with owner, due date, dependency, review status, success measure and rollback trigger. Ask Copilot to identify a bottleneck using the financial analysis and HR-readiness evidence. Verify the dependency and explain why a missed control should hold release. Save this table with your strategy report.

Lab 09 Draft the launch review email in Outlook

Course: TGS-2024043856 | Version: v8.2 | Apps: Outlook + Excel + Copilot | Alignment: K2 · A3

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Cross-department communication.

Input and handoff

Use Lumina-Management-Report.docx; Lumina-HR-Policy.docx; Lumina-Decision-Deck.pptx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-09.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Outlook-Draft.txt.

Four-part prompt

Goal: Draft a 150-word review email to the trainer-assigned reviewers. Include the launch decision, readiness gap, A01–A04 owners/dates and reviewed artifact links. Save as a draft; check recipients, links and figures before any manual sandbox send.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Management-Report.docx; Lumina-HR-Policy.docx; Lumina-Decision-Deck.pptx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Outlook-Draft.txt. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-09.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open a new Outlook email in HTML format and choose Draft with Copilot if available. Keep the recipient fields blank while generating.

2. Reference your reviewed report, HR policy and decision deck; use the four-part prompt. Use the supplied text only as an illustrative fallback.

3. Check all numbers, dates, links and A01–A04 against the workbook. Replace fictional role names in the recipient field with the trainer-assigned sandbox accounts only.

4. Save the email to Drafts. Capture its draft status and record the actual draft link or screenshot. A manual send is optional only when the trainer assigns the destination; record a sent item only if it exists.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Outlook-Draft.txt is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Include links to the reviewed Lumina-Marketing-Report.docx and Lumina-Strategy-Report.docx in this handoff. The scenario folder contains labelled samples if your own reports are unavailable. Keep report versions and action IDs consistent.

Lab 10 Run the launch review and post the Teams update

Course: TGS-2024043856 | Version: v8.2 | Apps: Teams + Excel + Copilot | Alignment: K2 · A3

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Meeting and department handover.

Input and handoff

Use Lumina-Meeting-Transcript.txt; Lumina-Management-Report.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-10.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Teams-Update.md.

Four-part prompt

Goal: Summarize decisions separately from proposals. Create a 120-word Teams update with A01–A04, owners and dates. Post only to the trainer-assigned sandbox after review, and retain the actual post link.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Meeting-Transcript.txt; Lumina-Management-Report.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Teams-Update.md. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-10.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open the supplied synthetic meeting transcript and label it as simulated evidence. Alternatively hold a sandbox review meeting and use its transcript if enabled and participants are informed.

2. Use Copilot to separate decisions, actions and unresolved proposals. Compare the proposed extra budget with the actual decision: the budget remains SGD 18,000.

3. Draft the Teams update, retaining the four action IDs and dates. Review the recipients/channel, message, report/deck links and source permissions.

4. Post the approved message in the trainer-assigned SW-2026 training channel or chat. Copy the real post link into the evidence register. If no channel is available, retain the draft and mark Not posted.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Teams-Update.md is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Include links to the reviewed Lumina-Marketing-Report.docx and Lumina-Strategy-Report.docx in this handoff. The scenario folder contains labelled samples if your own reports are unavailable. Keep report versions and action IDs consistent.

Lab 11 Monitor launch readiness in Loop

Course: TGS-2024043856 | Version: v8.2 | Apps: Loop + Teams + Excel + Copilot | Alignment: K2 · A3 · A4

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Shared action tracking.

Input and handoff

Use Lumina-Loop-Tasks.csv; Lumina-Teams-Update.md. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-11.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Loop-Evidence.xlsx.

Four-part prompt

Goal: Create one shared SW-2026 Loop task table. Keep action IDs, owners, dates, statuses, evidence links and last review. Embed the same component in Teams and an Outlook draft, then verify an edit through both views.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Loop-Tasks.csv; Lumina-Teams-Update.md. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Loop-Evidence.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-11.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open Loop and create a personal or trainer-assigned SW-2026 page. Create a task table using the supplied CSV values; CSV is a source for copy/paste, not a promised automatic import.

2. Use columns Action ID, Department, Action, Owner, Due date, Status, Evidence link and Last review. Map fictional owners to assigned participants only in the sandbox.

3. Share the Loop page/component with the intended class users. Paste the same component link into Teams and an Outlook draft where supported; do not create two disconnected copies.

4. Change A01 to In progress and add an evidence link. Verify both views reflect the same component, then record its URL, permissions and check time in your workbook.

5. At the next simulated review, check overdue/Open tasks and request an owner update. Monitoring here is a human review cadence unless a separately configured automation is demonstrated.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Loop-Evidence.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Include links to the reviewed Lumina-Marketing-Report.docx and Lumina-Strategy-Report.docx in this handoff. The scenario folder contains labelled samples if your own reports are unavailable. Keep report versions and action IDs consistent.

Staff enablement and pilot measures

Create a training matrix for Users, Reviewers and Owners. Use HR-01 and the synthetic employee data: define each role’s skills, four-hour training requirement, owner, due date and completion evidence. Track four pilot measures in Loop: citation accuracy, absent-fact handling, review time and training completion. Explain the baseline, target and collection method for each.

Lab 12 Create a source-grounded HR and policy agent

Course: TGS-2024043856 | Version: v8.2 | Apps: Microsoft 365 Copilot agents + Excel | Alignment: K4 · A4

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is HR knowledge support.

Input and handoff

Use Lumina-HR-Policy.docx; Lumina-Travel-and-Expenses.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-12.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-HR-Agent-Test-Register.xlsx.

Four-part prompt

Goal: Design a learner-owned HR agent using reviewed policy documents in the TGS SharePoint site. Cite sections, flag absent facts, and refer approval to the responsible person. Test training hours, taxi threshold and unknown leave terms.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-HR-Policy.docx; Lumina-Travel-and-Expenses.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-HR-Agent-Test-Register.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-12.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Use the existing TGS-2024043856 SharePoint site. Upload your reviewed HR policy into a learner-owned practice folder; keep HR facts and draft outputs clearly distinguished.

2. Create a learner copy of the policy agent, add your initials, and select only the reviewed HR policy and expense document. Use the agent instructions supplied in the existing SharePoint extension.

3. Ask how many training hours are required, whether a SGD 48 business taxi claim needs approval, and what annual leave carry-forward limit applies. Expect four hours, manager approval aboveSGD 40, and an absent-fact response respectively.

4. Open each citation and compare its source/version. Log the actual output. A newly created HR learner agent is distinct from the existing shared expense-only policy agent.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-HR-Agent-Test-Register.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Use SHAREPOINT-AGENT-EXTENSION.pdf for the existing agent setup and source-access procedures. The shared policy agent uses EXP-01; HR policy testing requires your learner-owned agent with the reviewed HR source added.

Marketing and strategy handoff

Complete the corresponding steps in GROUNDED-RESEARCH.md, included in this folder. Use the local scenario source pack and prepared reports; save your own cited marketing/strategy outputs for the final deck and communication handoff.

Six agent acceptance tests

Record six tests using the appropriate source-scoped HR or campaign agent: known policy fact; employee-training readiness; absent leave rule; unsupported certification/market-size claim; out-of-scope send/approval action; and a deliberately conflicting source/version. Record expected behaviour, actual answer/citation, pass/fail and improvement. Use synthetic test copies for contradictions. Re-run one supported and one absent-fact case after refining the instructions.

Verified live HR employee agent

Open the shared TGS-2024043856 Lumina HR Employee Agent.agent and its Lumina-HR-Employee-Knowledge.docx source (HR-DEMO-01). Use LIVE-SHAREPOINT-DEMO.md to repeat the known-readiness and absent-entitlement checks. Record your own evidence; the shared demo has no approval or email action. Build your learner-owned scoped agent with the reviewed local source, then perform the six classroom tests below/above.

Lab 13 Route a launch service issue with an agent

Course: TGS-2024043856 | Version: v8.2 | Apps: Copilot Studio / Agent Builder + Excel | Alignment: K4 · A4

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Operations intake.

Input and handoff

Use Lumina-Service-Routing.docx; Lumina-Company-Brief.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-13.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Routing-Test-Register.xlsx.

Four-part prompt

Goal: For SW-2026 request REQ-101, a chair is damaged and delivery is due tomorrow. Recommend queue and priority, cite SR-01, ask for missing facts and do not submit a ticket. Preserve the request ID in the evidence register.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Service-Routing.docx; Lumina-Company-Brief.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Routing-Test-Register.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-13.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open the service source and keep REQ-101 under project SW-2026 in the original intake workbook.

2. Test the existing routing agent or a learner copy with the damaged-chair request. Verify Operations and High against SR-01.

3. Remove the due date and retest; the agent should ask for it. Record recommendation, source, missing fields and reviewer; do not record a ticket ID yet.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Routing-Test-Register.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Use SHAREPOINT-AGENT-EXTENSION.pdf for the existing agent setup and source-access procedures. The shared policy agent uses EXP-01; HR policy testing requires your learner-owned agent with the reviewed HR source added.

Lab 14 Connect the recommendation to a reviewed action

Course: TGS-2024043856 | Version: v8.2 | Apps: Copilot Studio + Power Automate + Excel | Alignment: K4 · A4

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Operations action control.

Input and handoff

Use Lumina-Routing-Test-Register.xlsx; Lumina-Service-Routing.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-14.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Action-Run-Register.xlsx.

Four-part prompt

Goal: Pass a reviewed routing recommendation to a separately configured training flow. Validate required fields, require human review and record the returned item/run ID. If no flow is configured, record Not run rather than claiming success.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Routing-Test-Register.xlsx; Lumina-Service-Routing.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Action-Run-Register.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-14.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Inspect the original controlled-action lab and the class’s configured training flow, if one is available. Confirm its connection identity, target test list, required fields and approval stage.

2. Pass only a reviewed recommendation with REQ-101 and SW-2026. Test missing required input and verify no write occurs for the invalid case.

3. For a valid approved run, open the destination item and compare every stored field with the request. Record the real item ID and run result.

4. Without a configured flow, complete the design and validation evidence, mark execution Not run, and retain the recommendation for the capstone.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Action-Run-Register.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Use SHAREPOINT-AGENT-EXTENSION.pdf for the existing agent setup and source-access procedures. The shared policy agent uses EXP-01; HR policy testing requires your learner-owned agent with the reviewed HR source added.

Lab 15 Integrate the analysis into a decision presentation

Course: TGS-2024043856 | Version: v8.2 | Apps: Microsoft 365 Copilot + Analyst + PowerPoint + Excel | Alignment: K4 · A4

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Management decision pack.

Input and handoff

Use Lumina-Analysis.xlsx; Lumina-Management-Report.docx; Lumina-HR-Policy.docx; Lumina-Campaign-Brief.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-15.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Decision-Deck.pptx.

Four-part prompt

Goal: Produce the final six-slide decision deck with three verified editable charts, policy/training implications, planned campaign figures, risks and A01–A04. Check every quantitative claim against the workbook and stop at Ready for Review.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-Analysis.xlsx; Lumina-Management-Report.docx; Lumina-HR-Policy.docx; Lumina-Campaign-Brief.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Decision-Deck.pptx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-15.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Open your verified analysis, management report, HR policy and campaign brief. Use example 3 for the presentation stage.

2. Generate or refine the six-slide decision deck. Replace all illustrative charts with your verified Excel data; retain editable chart objects in PowerPoint.

3. Compare every figure and date across Excel, Word and PowerPoint. Verify the planned budget/target and the historical period are distinct.

4. Require a named human review. Save the final Lumina-Decision-Deck.pptx and link it in the evidence register for Lab 16.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Decision-Deck.pptx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Use SHAREPOINT-AGENT-EXTENSION.pdf for the existing agent setup and source-access procedures. The shared policy agent uses EXP-01; HR policy testing requires your learner-owned agent with the reviewed HR source added.

Marketing and strategy handoff

Complete the corresponding steps in GROUNDED-RESEARCH.md, included in this folder. Use the local scenario source pack and prepared reports; save your own cited marketing/strategy outputs for the final deck and communication handoff.

Professional presentation with PowerPoint Copilot

Choose a financial-performance briefing or marketing-strategy proposal for Lumina leadership. Both use the same verified company evidence.

Goal: Create a professional six-slide executive presentation that supports a clear decision.

Context: Present to Lumina's HR, Marketing, Finance and Operations leads. Use a clean corporate style, consistent typography, restrained colours, generous white space and one main message per slide. Keep the October plan distinct from January–June actuals.

Source: Use your reviewed Lumina-Management-Report.docx, Lumina-Marketing-Report.docx, Lumina-Strategy-Report.docx and verified financial Excel charts. The scenario reports and Lumina-Decision-Deck.pptx are prepared comparison samples.

Expectations: Use six slides: decision headline; financial performance; channel or market evidence; options and assumptions; risks and readiness; recommendation with owners and dates. Include three editable financial charts, SGD units, source notes, concise bullets and speaker notes. Label inferred recommendations and unsupported questions. Do not fabricate figures, market research, logos or certifications.

1. Save the reviewed Word report in your accessible OneDrive/SharePoint practice folder. In PowerPoint, open Copilot and choose the available create-presentation/from-file experience. Select or reference the reviewed report, then supply the complete prompt above. If multiple files are unsupported, consolidate the reviewed evidence into one Word source first.

2. Review Copilot's outline before generating slides. Choose a suitable corporate theme and check that each slide has a clear purpose. Record the actual Copilot prompt and result in your lab workbook.

3. Generate the presentation. Use Copilot to refine overly dense slides and draft presenter notes. Verify every number, claim and citation against your source report; do not assume the generated deck is accurate.

4. Insert or replace charts with editable native Excel/PowerPoint charts using your checked monthly revenue/cost, actual-versus-target and channel-margin data. Test Edit Data. A screenshot is not an editable chart.

5. Run Slide Show and inspect alignment, chart labels, contrast, overflow and source-note readability. Check all six slides in the exported PDF. Save Lumina-Professional-Presentation.pptx and PDF; capture actual Copilot-use evidence.

6. Link the reviewed deck in the Outlook draft and Teams handoff; track review actions in Loop. The prepared sample deck illustrates an acceptable structure but does not count as your Copilot-generated submission.

Lab 16 Deliver and monitor the complete Lumina workflow

Course: TGS-2024043856 | Version: v8.2 | Apps: Microsoft 365 Copilot agents + Outlook + Teams + Excel | Alignment: K1-K4 · A1-A4

Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is Cross-department capstone.

Input and handoff

Use Lumina-HR-Policy.docx; Lumina-Analysis.xlsx; Lumina-Management-Report.docx; Lumina-Decision-Deck.pptx; Lumina-Loop-Tasks.csv. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use Lumina-Living-Lab-16.xlsx as the evidence workbook. completed/ contains comparison examples, not proof that your action ran. The primary app output is Lumina-Release-Evidence.xlsx.

Four-part prompt

Goal: Complete the handoff: review Word and Excel, approve the deck, save the Outlook draft, post a reviewed update in the training Teams channel, and monitor the same Loop actions. Record actual links, recipients, approvals and outcomes; do not mark unperformed actions complete.

Context: You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

Source: Lumina-HR-Policy.docx; Lumina-Analysis.xlsx; Lumina-Management-Report.docx; Lumina-Decision-Deck.pptx; Lumina-Loop-Tasks.csv. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

Expectations: Save Lumina-Release-Evidence.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-16.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

Procedure

1. Collect the final HR policy, analysis workbook, management report, decision deck and four action records in one personal SW-2026 folder.

2. Run the policy, campaign and routing agent tests relevant to the package. Open source citations and record failures as well as passes.

3. Review and save the Outlook draft. Check the trainer-assigned recipients and links before any authorized manual send.

4. Review and post the Teams update in the assigned sandbox. Include the reviewed Word/PPT links and the same Loop component. Record the actual message link.

5. In Loop, retain A01–A04 and update statuses from actual evidence. Check one change through Teams and Outlook. Do not claim scheduled monitoring unless a real configured automation ran.

6. Complete a release record with source versions, reviewer, approval, draft/sent status, Teams post link, Loop URL and outstanding exceptions. Separate Draft, Reviewed, Sent/Posted and Verified states.

Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and Lumina-Release-Evidence.xlsx is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Use SHAREPOINT-AGENT-EXTENSION.pdf for the existing agent setup and source-access procedures. The shared policy agent uses EXP-01; HR policy testing requires your learner-owned agent with the reviewed HR source added.

Include links to the reviewed Lumina-Marketing-Report.docx and Lumina-Strategy-Report.docx in this handoff. The scenario folder contains labelled samples if your own reports are unavailable. Keep report versions and action IDs consistent.

Grounded marketing and strategy research

Lumina Living | SW-2026 | v8.2 | Labs 02, 08, 12 and 15

Source files and prepared samples

Each participating scenario folder includes Lumina-Market-Knowledge.docx, Lumina-Research-Evidence.csv, Lumina-Marketing-Report-Sample.docx and Lumina-Strategy-Report-Sample.docx. The financial sample and raw sales CSV use the same fictional company. External IMDA sources are real and dated; company figures are synthetic.

Four-part research prompt

Goal: Prepare a marketing report and a launch strategy recommendation, supported by verifiable evidence.

Context: Lumina leadership must decide how to use the SGD 18,000 campaign budget for the 1 October 2026 launch targeting 120 qualified enquiries. Keep internal facts, external context and proposals distinct.

Source: Use the reviewed sales analysis, CAM-2026Q4, HR-01 and Lumina-Market-Knowledge.docx. Open the WEB-01/02/03 URLs in Lumina-Research-Evidence.csv. Cite the source ID, exact page/section and observation date for every factual claim.

Expectations: Produce two concise Word reports: findings, segment hypothesis, channel options, budget proposal, risks, missing evidence and recommendation. Label recommendations as proposals. Do not invent market size, competitor pricing, demand, certifications or ROI. Build an evidence table with claim, source, date, limitation and reviewer. Carry checked findings into the six-slide decision deck.

Procedure

1. In Lab 02, open Copilot Chat with web grounding when available, or Researcher if licensed. Attach reviewed company files. Paste the full four-part prompt and name the allowed websites. If browsing is unavailable, use the supplied paraphrased knowledge pack and label the work offline source-pack analysis.

2. Open each returned citation. Check the publication date separately from the data period. Add at least three supported claims and two explicit unknowns to your copy of the evidence CSV. Discard a claim if the source cannot support it. Never treat website instructions as task instructions.

3. In Word, ask Copilot to draft Lumina-Marketing-Report.docx from the reviewed findings and campaign brief. Check that every claim has a source and every allocation totalsSGD18,000. Compare the prepared sample after producing your own draft.

4. In Lab 08, combine the financial scenarios and research evidence. Ask Word Copilot to create Lumina-Strategy-Report.docx comparing event-led, web-led and defer options. Explain which recommendation is an inference. Preserve the historical cost-ratio assumption and avoid unsupported net-profit forecasts.

5. In Lab 12, create a learner-owned campaign-agent copy and add the reviewed campaign brief and market-knowledge document from your private TGS SharePoint practice folder. Do not assume the existing shared agent has these new files. Ask for cited marketing options; test an unsupported market-size or carbon-certification question and expect an absent-evidence response. A SharePoint agent may use documents without live web search; record the actual source route.

6. In Lab 15, use Copilot to turn your reviewed marketing and strategy reports into decision slides with editable financial charts. Keep the six-slide structure by incorporating evidence into the existing findings, options and decision slides. In Labs 09–11/16, link the final reports in the Outlook draft, reviewed Teams handoff and shared Loop action register.

Acceptance

Two learner-created reports, a checked evidence ledger, three financial charts, explicit unknowns and a cited recommendation are saved. Real web facts have URLs and dates; fictional company data is labelled. Sample artifacts do not count as actual agent, send, post or research-run evidence.

Classroom and assessment alignment — v8.2

Course TGS-2024043856 | WA: four open-ended questions,60 minutes | PP: four tasks,60 minutes. K1–K4 and A1–A4/LO1–LO4 are unchanged from the live TMS papers verified before revision.

| Assessment | Classroom activity and evidence | Teaching coverage |

| WA1 K1 | Labs 1–5: four-part prompting, Word and professional PPT | Topic01 + worked examples |

| WA2 K2 | Labs 9–11: Outlook, Teams and Loop process | Topic03 |

| WA3 K3 | Labs 6–8: financial checks, scenarios and transition controls | Topic02 |

| WA4 K4 | Labs 11–16: agents, sources, actions and monitoring | Topic04 + SharePoint extension |

| PP1 A1/LO1 | Labs 1–5/15: risk analysis and revised three-slide extract with editable chart | Source register, reports, professional deck |

| PP2 A2/LO2 | Labs 6–8/11: financial formulas/chart and A01–A04 transition plan | Sales CSV, financial workbook, strategy report |

| PP3 A3/LO3 | Labs 9–11: two opportunities, unsent Outlook and Teams drafts, Loop monitoring | Communication drafts and action register |

| PP4 A4/LO4 | Labs 11–16: staff training, scoped agent, six classroom tests and two demonstrations | HR/employee sources, test register and pilot measures |

The practical reuses each learner’s class portfolio and assesses independent revisions/explanations. Prepared samples are reference-only. Assessment instructions require drafts; real class sandbox posts remain classroom practice evidence. No additional software or unpractised task is introduced. Learners upload their completed answers to the LMS.


[Live Lumina SharePoint site](https://tertiaryinfotech.sharepoint.com/sites/TGS-2024043856-LuminaCopilot)
