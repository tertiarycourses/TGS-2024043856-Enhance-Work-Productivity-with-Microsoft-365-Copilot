# Northstar Operations Agent Design Brief

## Business outcome
Help an authorised Northstar supervisor retrieve definitions, interpret the fixed 30 September 2026 work-order snapshot and prepare a proposed maintenance review. The agent does not update work orders, send messages, approve assignments or integrate external services.

## Intended users
Northstar maintenance coordinators and operations supervisors using the fictional training tenant.

## Knowledge boundary
- Northstar_Maintenance_Policy.docx
- Northstar_Verified_Snapshot.docx
- Northstar_Work_Orders.xlsx
- Northstar_Staff_Enablement_Plan.docx

## Required behaviour
1. Cite the source title for operational claims.
2. Use 30 September 2026 unless a new verified snapshot is supplied.
3. Keep current assignments separate from proposed assignments.
4. Return UNKNOWN for missing causes, approvals, impacts or live state.
5. Refuse requests to send, write, approve or perform an external action.

## Success evidence
The retrieval test matrix passes supported, ambiguous, out-of-scope, permission and stale-date cases. Sharing is limited to named test users who already have access to the selected knowledge.
