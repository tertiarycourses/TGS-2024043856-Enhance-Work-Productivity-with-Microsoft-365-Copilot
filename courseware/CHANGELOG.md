# Change log

## v9.5 — 21 October 2026

The deck now follows the standard WSQ admin pages. Added "Login to LMS and Download Course Material" after Ground Rules, showing the lms-tms.tertiaryinfotech.com TMS sign-in screen (courseware/assets/lms-login.png). Briefing for Assessment, Assessment & Funding and Assessment Flow now also appear in the front admin block. A "Courseware & Assessment on the LMS" slide sits before the end assessment block, which still runs Briefing → Assessment → Assessment Flow → Digital Attendance → Thank You. Practice Exam stays out because it was removed as non-applicable in v8.1. Labs, timing, K&A mapping and the WA/PP instruments are unchanged apart from the v9.5 version. v9.4 deliverables are in courseware/archive/v9.4, courseware/archive/assessment-v9.4 and assessment/fg-ap/archive-v9.4.

## v9.4 — 20 October 2026

Adopted the revised learning outcomes and topic titles. LO3 now reads "Evaluate opportunities in using Microsoft Copilot" and LO4 "Design a training plan for staff to use Microsoft Copilot"; LO1 and LO2 are unchanged. The topics are now 1 Overview of Microsoft Copilot, 2 Microsoft Copilot for Excel, 3 Create Interactive Dashboard with Microsoft Copilot and 4 Create Microsoft Agent. The deck (LO tiles, topic dividers, schedule, recaps), LG, LP, lab objectives, FG/AP, prompts page and README follow. Labs, slide count (241), timing, K&A mapping and the WA/PP instruments are unchanged apart from the v9.4 version. v9.3 deliverables are in courseware/archive/v9.3, courseware/archive/assessment-v9.3 and assessment/fg-ap/archive-v9.3.

## v9.3 — 20 October 2026

Removed Microsoft Loop from the course. LO4 now reads "Design a training plan for staff to use Microsoft Copilot Studio" (to be revised in TPG). Lab 14 tracks staff practice in an Excel staff enablement tracker (new data/templates/Staff_Enablement_Tracker.csv) with the same columns, and the Topic 4 concept slide, Learner Guide, Lesson Plan, Staff Enablement Plan, PP Task 4 wording and FG/AP follow it. Added three worked Lumina HR slides, each with numbered explanations: "What Is a Pareto Chart?" (Lab 5: overdue backlog by request type, 18/12/8/8/4, cumulative 36–100%, 80% reference), "What Is an Interactive Dashboard?" (Lab 7: four shared filters, scope line, six KPI tiles, formula finding titles, linked charts) and "Interactive: One Filter Changes Everything" (Lab 8: All vs Retail Sales). The images are rendered from real formula workbooks built by build/dashboard_example.py on the 120-case baseline, and appear in the LG and lab Screen Guides too. Added six live Microsoft 365 Agent Builder screenshots to Topic 4 (Labs 11–13): Agents > New agent, the "agents can access everything by default" notice, Configure (name, instructions, Skills), Knowledge with Cloud files/Outlook/Teams/Web search on Search all by default, suggested prompts, and a cited UNKNOWN answer from an earlier course agent. Captures are cropped to the agent pane, with no chat history. Deck now 241 slides. Removed the 14 empty iCloud duplicate lab folders. WA (4) and PP (4) counts, timing and K/A coverage unchanged. v9.2 deliverables are in courseware/archive/v9.2, courseware/archive/assessment-v9.2 and assessment/fg-ap/archive-v9.2.

## v9.2 — 20 October 2026

Added real Microsoft 365 Copilot interface screenshots, each with numbered explanations, as 10 new slides (deck now 232 slides) placed straight after the concept they illustrate: the Excel chat pane and the + grounding menu (Lab 1); the model picker with Allow editing / Plan / Chat only, and Outlook Copilot Work/Web (Lab 2); ••• > Personalization with the Customize Copilot box holding the four Lab 3 preferences (Lab 3); the OneDrive skills folder and the Custom skills list (Lab 5); Manage plugins & skills, the chart-design Skill and the @ Skill picker (Lab 6); and ••• > All Agents (Lab 11). The same screens and explanations are in the Learner Guide (under each concept section), the lab READMEs and README.pdf files ("Screen Guide"), and the Lesson Plan topic demonstrations. Images are in courseware/assets/screenshots/ and driven by build/ui_screenshots.py.

Of the 28 screenshots supplied on slides 2–27 of the hand-edited v9.1 deck, 13 are used. Duplicates were dropped, as were captures showing Northstar work-order data (Pareto of failure modes, two Northstar dashboards, a Northstar PowerPoint brief, the Northstar .Rules sheet and chat history); the course stays on the Lumina HR scenario. The Outlook capture is cropped to the Copilot pane and the Custom skills capture is cropped above the non-HR Skills. WA (4 questions), PP (4 tasks), timing and the one-screenshot rule are unchanged; assessments, FG and AP are re-issued as v9.2. The hand-edited v9.1 deck and all v9.1 deliverables are in courseware/archive/v9.1, courseware/archive/assessment-v9.1 and assessment/fg-ap/archive-v9.1.

## v9.1 — 18 October 2026

Returned the course use case to HR. Lumina Living Pte Ltd HR Shared Services cases (Case_ID, Department, Request_Type, HR officers) replace the Northstar Water Services work orders in all 14 labs, the deck, Learner Guide, Lesson Plan, FG/AP and assessments; the 120-case baseline, 30 September 2026 reporting date and every control figure are unchanged. Topic 4 now builds a grounded Lumina HR Policy Agent with HR Policy Handbook knowledge and the hr-policy-qa Skill, tested with an eight-case HR matrix before named-user sharing. The prompts page now shows each step's instruction directly before its prompt (step → prompt). The course closes with the 5 Principles of AI Security (data control, permission control, human in the loop, traceability, don't use the most powerful model) as the last teaching slide before the assessment block and as the Learner Guide's closing section. Lab README.pdf files are now generated from the same README.md, and recalc_dashboards.py prepares the LibreOffice-recalculated workbooks the validator checks. WA keeps four questions and PP four tasks. Superseded v9.0 files are in courseware/archive/v9.0, courseware/archive/assessment-v9.0 and archive/20261018-v9.0-northstar-superseded/.

## v9.0 — 14 October 2026

Rebuilt the course around the verified Northstar Water Services scenario and the approved C27 charcoal/cream design. The current package has four exact teaching topics, 14 connected labs, a minimum 200-slide concept-led deck, a detailed visual Learner Guide and an approved two-day schedule with 840 training minutes plus 120 assessment minutes. The baseline remains 120 unique work orders at 30 September 2026 with current and proposed assignments separated.

Topics 1 and 2 retain the C27 instructional sequence. Topic 3 merges dashboard and professional-presentation work. Topic 4 adds Microsoft 365 Agent Builder scope, permission-aware knowledge, instruction configuration, eight-case retrieval/guardrail testing, named-user sharing, Microsoft Loop staff enablement and the documented boundary to separately governed Copilot Studio actions.

Revised WA-SAQ and PP preserve four questions/tasks and the approved 60-minute duration per method. Every PP task is atomic and requires exactly one screenshot; the assessor supplies a blank four-sheet workbook before timing. Shared FG/AP copies exclude answer keys and item-level rubrics. Private answer documents retain the observable C/NYC criteria. Historical version rows remain in LG, LP, FG and AP.

Archived the superseded v8.2 courseware, assessments, build source and all 16 old activity folders under `archive/20261014-v8.2-pre-v9.0/` with SHA-256 manifests. No historical deliverable was deleted.

## v8.2 — 7 September 2026

Preserves the 138-slide v8.1 baseline, updates its lab callouts, and adds 11 visuals/examples (149 slides). All 16 labs follow Lumina Living SW-2026 across HR, Marketing, Finance and Operations. Includes 96 synthetic sales records, a 56-row mock employee register, financial analysis with editable charts, grounded market research, Word marketing/strategy reports and a professional six-slide presentation sample. The live SharePoint HR knowledge document and HR Employee Agent were created and tested; Admin, Training1 and Training2 are members. Anonymous sharing is unavailable in the current tenant. The full additional company source pack is supplied locally pending bulk upload.

Aligns PPT, LG, LP, activities and revised v8.2 assessments. Preserves four WA questions (K1–K4), four PP tasks (A1–A4) and 60 minutes for each instrument; practical tasks require independent revisions of the learner's class portfolio. Candidate papers remain separate from private answer keys.

## v8.1 Tea Break correction — 7 September 2026

Removed the Tea Break slide; retained Lunch Break. The deck now has 138 slides. Subsequent slide numbers and Lesson Plan slide references are updated.

## v8.1 correction — 7 September 2026

Removed the practice-exam page (former slide 14) at the user’s request. The deck now has 139 slides. Renumbered subsequent footers and Lesson Plan slide references; all other slide content, labs and assessments are retained.

## v8.1 — 7 September 2026

Retained all 127 existing slides and added 13 editable visual slides for SharePoint sources, policy decisions, routing, campaign facts, access and evidence. Added a detailed LG extension, LP delivery notes and self-contained Labs 12–16 supplements. Established a private TGS-prefixed SharePoint workspace and three source-specific agents. Existing assessment instruments and timetable retained. Applied both supplied ebooks to source verification and cross-application drafting exercises; current agent guidance checked against Microsoft documentation.


## v8.0 — 15 August 2026

Existing package: 127 slides, 16 activities, Learner Guide, Lesson Plan and WA/PP assessments.
