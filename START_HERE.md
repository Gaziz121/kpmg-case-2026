# Start here

Use this guide to load the context needed for the assigned KPMG case task.

## GITHUB SYNC POLICY

GitHub is the shared source of truth for all non-private project work: AI context, research, discovery outputs, analytical notes, benchmark lessons and project state. Google Drive holds official/private case materials, collaborative Sheets, models, Slides and final deliverables. Do not duplicate these artifacts unnecessarily.

- **Before substantive work:** check for local uncommitted changes (including untracked files) or an unresolved Git operation. If present, stop and tell the human; do not overwrite, reset or auto-stash their work. Otherwise sync safely with `origin/main` (fast-forward only), then re-read the latest `START_HERE.md` and task-relevant files.
- **During work:** change only task-relevant files. Prefer a separate research/output file to overwriting a teammate's work. Never modify `private/`, stage or push anything from it, or copy its contents into tracked files.
- **After creating or intentionally changing project files:** review the diff, fetch and safely reconcile with `origin/main` while preserving the intended task changes, then review the final diff. Stage only explicit intended files, commit with a descriptive message and automatically push to `origin/main`. Confirm push success and name the files pushed. Never force-push.
- **On any sync/push failure, missing permission or conflict:** stop and explain the problem. Preserve local work; do not silently resolve strategic/content conflicts or claim the work is shared before the push succeeds.
- **GitHub connector sessions:** read the latest repository version directly from GitHub, then the latest routing and task-relevant files. With write access, save completed task outputs back to the shared repository on `main` and verify success. With read-only access, clearly state that the result has **NOT been saved to GitHub**.

## Source hierarchy

- `private/Case Materials, KPMG Strategy & Operations.pdf` is the highest authority for formal requirements. Consult it when interpreting requirements or deliverables.
- `private/kpmg_briefing_notes.md` contains important KPMG oral guidance, not formal written requirements. Consult relevant guidance for the task.
- `private/raw_briefing_transcript.md` is for verification only when oral wording is ambiguous.
- Human team decisions override AI-generated proposals. Never infer team agreement from an AI output or treat a proposal as adopted. Keep private source materials in `private/`.

## Current state

Read `CURRENT_STATE.md` for the project stage, approvals and open questions. Respect documented proposal/adoption status. Flag discrepancies with newer work without inventing decisions. An explicit human task assignment authorizes that task within its stated scope; it does not imply broader approval or methodology adoption.

## Task routing

Load only relevant context; combine routes when a task spans them. Do not mechanically read every project file.

| Task involves | Read / consult |
|---|---|
| Opportunity discovery or screening | Read `opportunities/SCREENING_APPROACH.md`. |
| Research or evidence gathering | Read `opportunities/RESEARCH_PROTOCOL.md`; use `DATA_SOURCES.md` as a source map where useful. |
| Strategic analysis, challenging a thesis or finalist review | Read `opportunities/ANALYSIS_PLAYBOOK.md`; consult `BENCHMARK_LESSONS.md` when useful as a quality benchmark. |
| An existing opportunity | Locate and read the relevant opportunity, discovery or research file before working, including relevant records in `opportunities/discovery/`. |
| Current team status or prior decisions | Read `CURRENT_STATE.md` and `DECISIONS.md` if it exists. |

For “Assess whether this opportunity deserves deeper research,” read its existing record, the screening approach and analysis playbook; also load the research protocol if gathering evidence.

## Default AI behaviour

Unless explicitly told otherwise:

- Identify the decision the work must inform and plan the analytical work yourself; do not require step-by-step research instructions.
- Identify what must be true and seek evidence both for and against the hypothesis.
- Use authoritative sources where practical, perform relevant calculations, and follow the routed files' evidence and verification rules.
- Identify the weakest assumption; distinguish fact, calculation, assumption, inference and judgment where useful.
- Return a decision-ready conclusion with supporting evidence, uncertainty and the next decisive test where needed. Keep effort proportionate to the task and stage.

Stop and ask the human only when:

- A material strategic choice must be made.
- Two plausible directions would materially change the work.
- Critical information is unavailable and a consequential assumption is required.
- The requested work would change the agreed project scope.

Humans retain final strategic decisions, including Top 5 selection and teaser choice. Present recommendations for their judgment without recording them as agreed decisions.

## Architecture rule

Do not expand this repository proactively. Add or change architecture only when an observed workflow problem requires it. Prefer the smallest change that solves the problem.
