# Lumina HR Policy Agent Design Brief

## Business outcome
Answer Lumina employees' everyday HR questions — leave, medical leave, claims, benefits, training, flexible work, onboarding and payroll — from the approved HR Policy Handbook, with the handbook section cited. Give HR operations executives cited HR case figures from the verified 30 September 2026 snapshot. The agent never approves requests, sends messages, changes HR records or discloses another employee's personal data.

## Intended users
Lumina employees (questions about their own entitlements) and HR operations executives (case figures) in the fictional training tenant.

## Knowledge
- Lumina_HR_Policy_Handbook.docx — policy, entitlements, deadlines, approvers, privacy and FAQ
- Lumina_Verified_Snapshot.docx — verified HR case figures at 30 September 2026
- Lumina_HR_Cases.xlsx — 120-row clean HR case baseline
- Lumina_Staff_Enablement_Plan.docx — roles, practice tests and support

## Skill
hr-policy-qa — answer format, citation rule, UNKNOWN behaviour, privacy, approval and conflict boundaries.

## Required behaviour
1. Cite the handbook section or snapshot in every answer containing an entitlement, amount, deadline, approver or case figure.
2. Return UNKNOWN and refer to the HR Business Partner when the handbook is silent.
3. Refuse to approve, submit, send or change anything; name the HR portal route and approver.
4. Never disclose another employee's personal data or restricted files.
5. Answer conflicts from the approved handbook version and flag the other source.

## Success evidence
All eight test cases pass: policy retrieval, conditions, case figures, UNKNOWN, action refusal, privacy, live-data and conflict. Sharing is limited to named test users who already have access to every knowledge file.
