# Lab 12 Create a source-grounded HR and policy agent

**Course:** TGS-2024043856 | **Version:** v8.2 | **Apps:** Microsoft 365 Copilot agents + Excel | **Alignment:** K4 · A4

## Company and role

You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries. Your role in this lab is HR knowledge support.

## Input and handoff

Use Lumina-HR-Policy.docx; Lumina-Travel-and-Expenses.docx. Prefer your prior-lab output. The scenario folder provides a supplied fallback so this lab can run independently. Save your work in your own SW-2026 folder and record whether you used your own output or a supplied example.

Use `Lumina-Living-Lab-12.xlsx` as the evidence workbook. `completed/` contains comparison examples, not proof that your action ran. The primary app output is `Lumina-HR-Agent-Test-Register.xlsx`.

## Four-part prompt

**Goal:** Design a learner-owned HR agent using reviewed policy documents in the TGS SharePoint site. Cite sections, flag absent facts, and refer approval to the responsible person. Test training hours, taxi threshold and unknown leave terms.

**Context:** You work for Lumina Living Pte Ltd on SW-2026, the Sustainable Workspace Launch. HR, Marketing, Finance and Operations share one evidence trail. Launch is planned for 1 October 2026; budget SGD 18,000; target 120 qualified enquiries.

**Source:** Lumina-HR-Policy.docx; Lumina-Travel-and-Expenses.docx. Use your own reviewed prior-lab files first; scenario/ contains supplied fallback examples.

**Expectations:** Save Lumina-HR-Agent-Test-Register.xlsx. Record source version, verified facts, unresolved questions and reviewer in Lumina-Living-Lab-12.xlsx. Keep project SW-2026 and action IDs A01–A04 unchanged. Label every output Draft until reviewed; record actual app actions separately.

## Procedure

1. Use the existing TGS-2024043856 SharePoint site. Upload your reviewed HR policy into a learner-owned practice folder; keep HR facts and draft outputs clearly distinguished.

2. Create a learner copy of the policy agent, add your initials, and select only the reviewed HR policy and expense document. Use the agent instructions supplied in the existing SharePoint extension.

3. Ask how many training hours are required, whether a SGD 48 business taxi claim needs approval, and what annual leave carry-forward limit applies. Expect four hours, manager approval aboveSGD 40, and an absent-fact response respectively.

4. Open each citation and compare its source/version. Log the actual output. A newly created HR learner agent is distinct from the existing shared expense-only policy agent.

## Acceptance and next handoff

The output belongs to Lumina SW-2026; the named sources support its facts; the reviewer and source version are recorded; and `Lumina-HR-Agent-Test-Register.xlsx` is available to the next activity. Check each step’s numerical or behavioral expectation. A draft is not a sent email, a posted Teams message or an executed flow.

Use SHAREPOINT-AGENT-EXTENSION.pdf for the existing agent setup and source-access procedures. The shared policy agent uses EXP-01; HR policy testing requires your learner-owned agent with the reviewed HR source added.


## Marketing and strategy handoff

Complete the corresponding steps in GROUNDED-RESEARCH.md, included in this folder. Use the local scenario source pack and prepared reports; save your own cited marketing/strategy outputs for the final deck and communication handoff.

## Six agent acceptance tests

Record six tests using the appropriate source-scoped HR or campaign agent: known policy fact; employee-training readiness; absent leave rule; unsupported certification/market-size claim; out-of-scope send/approval action; and a deliberately conflicting source/version. Record expected behaviour, actual answer/citation, pass/fail and improvement. Use synthetic test copies for contradictions. Re-run one supported and one absent-fact case after refining the instructions.

[Live Lumina SharePoint site](https://tertiaryinfotech.sharepoint.com/sites/TGS-2024043856-LuminaCopilot) — use the assigned tenant account; anonymous Anyone links are unavailable.

## Verified live HR employee agent

Open the shared **TGS-2024043856 Lumina HR Employee Agent.agent** and its **Lumina-HR-Employee-Knowledge.docx** source (HR-DEMO-01). Use `LIVE-SHAREPOINT-DEMO.md` to repeat the known-readiness and absent-entitlement checks. Record your own evidence; the shared demo has no approval or email action. Build your learner-owned scoped agent with the reviewed local source, then perform the six classroom tests below/above.
