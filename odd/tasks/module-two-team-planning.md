# Module two team planning

## Objective
Prepare a provisional, internally consistent division of work for six named students and the Module 2 workshop artifacts in `clases/ppt-9.pdf` slide 18: project RACI, preliminary Gantt, and person-hour budget. Align research stages (slides 14–17) and project deliverables (`clases/ppt-8.pdf` slides 10–13). Keep allocations provisional until the six people confirm preferences and availability.

## Constraints
- The user authorized proposing a balanced initial assignment without providing individual preferences or availability. No role is a claim about someone's ability or consent.
- Use only work-area files `investigacion/planificacion.md`, `investigacion/raci.md`, `investigacion/gantt.md`, and `investigacion/presupuesto-hh.md` for the deliverable. No changes to protected base files.
- The user supplied the 2 November progress and 23 November final presentations, no classes on 12 and 26 October, and a November semester end. Use 2026 only as a provisional reference year pending confirmation; hours and other schedule details remain estimates, not attendance or completed work.
- No explicit authorization for new commits or push for this candidate; leave the changes uncommitted.
- TDD: N/A, documentation only. Runner: N/A. Checks: RACI unique A, task-ID coverage, Gantt dependencies, HH sums and markdown link/readback.
- Delivery strategy: ask-on-risk. Forecast under 400 authored lines.

## Tasks
- [ ] P1: Map six research stages and five deliverables into actionable activity IDs and balanced provisional roles. Route: parent inline read-only exploration. Outcome: A01–A12 cover the six stages, report, publication, campaign/interaction, advances and final presentation; checks passed. Commit pending explicit authorization.
- [ ] P2: Write linked activity plan, RACI, preliminary relative-week Gantt, and HH budget in four work-area paths. Route: delegated `gentle-ai-worker` (multi-file trigger); focused correction clarified obligatory audience interaction. Outcome: each ID occurs across all four, one A per RACI row, six contributors, relative W1–W6 and 103 HH base + 12 HH reserve; checks passed. Commit pending explicit authorization.
- [ ] P3: Independently verify requirements, arithmetic and internal links. Route: `gentle-ai-verify` and parent spot readback after correction. Outcome: six names and A01–A12 match; every Gantt bar/dependency and 12 HH rows checked; six personal totals 17,17,17,19,16,17 sum to 103; local links resolve. `git diff --check -- investigacion/planificacion.md` passed but does not cover untracked files; no runtime harness exists for docs. Commit pending explicit authorization.

## Acceptance
- Six names appear correctly and each receives meaningful tasks without asserting approval.
- Activity IDs match across RACI, Gantt, budget; all six module stages and the five class deliverables are represented.
- Gantt is genuinely schedulable with dependencies and relative weeks, without fake calendar dates.
- HH estimates have explicit per-activity and per-person totals, basis and contingency; totals reconcile exactly.
- Research methods, collection, results and dissemination format remain decisions to validate; no claims of actual study execution.

## Progress and next step
The provisional plan, RACI, Gantt and HH budget have been drafted and independently checked. The verifier found that audience interaction had been wrongly made optional; a focused correction and parent readback now state it is required, with modality undecided. The Gantt now maps W3 to the 2 November progress presentation and W6 to the 23 November final, marks 12 and 26 October as class-free, and plans no work after the final. A second read-only verifier confirmed date/week alignment and the A09 dependency correction; 2026 is still a tentative year. Human approval of roles, availability, calendar, method and hours remains pending. All task checkboxes stay open solely because closing substantial work units requires a work-unit commit, and no new commit or push was authorized for this candidate.
