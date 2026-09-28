# Wellbeing project foundation

## Objective
Establish a minimal repository structure and agent context for a university team project on physical and mental wellbeing through exercise, healthy eating, and sleep. The audience is university students. This task sets up the workspace only; it does not research claims, write the report, or choose a digital platform.

## Source and constraints
- `clases/ppt-8.pdf`, module 2, slides 7–14: research and dissemination project; five deliverables (research report, digital publication, progress presentation, dissemination campaign, final presentation). Slides 11–13 describe report sections, digital publication, campaign and audience interaction; slide 14 addresses brainstorming.
- Repository currently has no commits on `main`; `.gitignore` and `clases/` are pre-existing untracked content. Preserve both and do not claim a baseline commit exists.
- Documentation follows the class project's Spanish-language convention. Do not invent evidence, references, audience feedback, deadlines, grading rules, or a chosen publication platform.
- Commit and push were explicitly authorized after the scaffold was verified. Do not open a PR without separate authorization.
- TDD: not configured or applicable to documentation-only scaffolding. Runner: N/A (no executable project). Check: readback, paths/links, and Git status.
- Delivery strategy: ask-on-risk; initial forecast under 400 authored lines, no delivery planned.

## Tasks
- [ ] F1: Establish context and file layout. Route: parent inline read-only exploration. Outcome observed: slides 7–14 extracted and mapped; no unsupported grading requirements added. Check passed. Commit evidence pending.
- [ ] F2: Create minimal agent rules, report/research/dissemination/presentation workspaces and version-control workflow. Route: delegated `gentle-ai-worker` (multi-file write trigger); a focused second writer pass added the slide-13 interaction examples. Outcome observed: seven scaffold documents exist. Commit evidence pending.
- [ ] F3: Verify resulting paths, rules and Git state. Route: delegated `gentle-ai-verify` after native assessment was unassessable for untracked files. Outcome observed: links and slide mapping passed after correction; `git status --short`, `git diff --check` and file-existence check passed; parent read back key files and reran Git status/diff check. Limit: `git diff --check` ignores untracked content; no baseline hashes prove unchanged pre-existing files. Commit evidence pending.

## Acceptance
- Root entry explains project, intended audience, source of requirements, where to work, and what remains undecided.
- Agent entry confines AI to verifiable claims and clear provenance, forbids fabricated citations/data, preserves human authorship and review, and explains the smallest workflow.
- Separate places exist for evidence, report, digital publication/campaign/audience feedback, and progress/final presentations, without pretending work is completed.
- Git workflow distinguishes branch, staging, work-unit commits, and push/PR; pre-existing untracked files remain untouched.

## Progress and next step
Scaffold and independent read-only verification complete. The user has now explicitly authorized a commit and push. Initial baseline paths include `.gitignore`, `clases/`, scaffold documents, and this task document; `.atl/` remains ignored. Commit identity and publication result are pending verification. Platform, question and specific scope remain team decisions.
