# Wellbeing project foundation

## Objective
Establish a minimal repository structure and agent context for a university team project on physical and mental wellbeing through exercise, healthy eating, and sleep. The audience is university students. This task sets up the workspace only; it does not research claims, write the report, or choose a digital platform.

## Source and constraints
- `clases/ppt-8.pdf`, module 2, slides 7–14: research and dissemination project; five deliverables (research report, digital publication, progress presentation, dissemination campaign, final presentation). Slides 11–13 describe report sections, digital publication, campaign and audience interaction; slide 14 addresses brainstorming.
- At exploration, `main` had no commits; `.gitignore` and `clases/` were pre-existing untracked content. The first baseline commit now exists on `docs/wellbeing-foundation`; preserve the original materials.
- Documentation follows the class project's Spanish-language convention. Do not invent evidence, references, audience feedback, deadlines, grading rules, or a chosen publication platform.
- Commit and push were explicitly authorized after the scaffold was verified. Do not open a PR without separate authorization.
- TDD: not configured or applicable to documentation-only scaffolding. Runner: N/A (no executable project). Check: readback, paths/links, and Git status.
- Delivery strategy: ask-on-risk; initial forecast under 400 authored lines, no delivery planned.

## Tasks
- [x] F1: Establish context and file layout. Route: parent inline read-only exploration. Evidence: slides 7–14 extracted and mapped; no unsupported grading requirements added. Included in baseline commit `1733315e0563348838097048a021ca7ff4960d82`.
- [x] F2: Create minimal agent rules, report/research/dissemination/presentation workspaces and version-control workflow. Route: delegated `gentle-ai-worker` (multi-file write trigger); a focused second writer pass added the slide-13 interaction examples. Evidence: seven scaffold documents included in baseline commit `1733315e0563348838097048a021ca7ff4960d82`.
- [x] F3: Verify resulting paths, rules and Git state. Route: delegated `gentle-ai-verify` after native assessment was unassessable for untracked files. Evidence: links and slide mapping passed after correction; staged Markdown `git diff --cached --check -- '*.md' .gitignore` passed; `git status` and the `ppt-9.pdf` index/worktree hashes matched. The first commit `1733315e0563348838097048a021ca7ff4960d82` contains the verified scaffold. No executable runtime harness applies because this is documentation-only.

## Acceptance
- Root entry explains project, intended audience, source of requirements, where to work, and what remains undecided.
- Agent entry confines AI to verifiable claims and clear provenance, forbids fabricated citations/data, preserves human authorship and review, and explains the smallest workflow.
- Separate places exist for evidence, report, digital publication/campaign/audience feedback, and progress/final presentations, without pretending work is completed.
- Git workflow distinguishes branch, staging, work-unit commits, and push/PR; pre-existing untracked files remain untouched.

## Progress and next step
Scaffold and independent read-only verification complete. Initial work-unit commit: `1733315e0563348838097048a021ca7ff4960d82` on `docs/wellbeing-foundation`, with 12 explicit paths and no `.atl/` files. This follow-up records commit evidence; remote publication remains pending. Native review inspection stopped at `empty_candidate_base_ref_required` for the root commit, with no review lineage or approval; do not claim review closure. Platform, question and specific scope remain team decisions.
