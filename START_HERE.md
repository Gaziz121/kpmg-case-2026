# Start here

Use this guide to load the context needed for the assigned KPMG case task.

## Locked starting point (read this first)

**Phase 0 (case framing / methodology) is CLOSED as of 21 Oct 2026. The project is in EXECUTION.**

- **`LOCKED_STARTING_POINT.md` is authoritative for day-to-day work.** Read it before any task. Do not redesign the method; reopen it only if real research exposes a contradiction, and record that as a team decision.
- In one line: the unit of analysis is an **investor location decision**, not a sector. Start from *which investor has to put capital somewhere, what decides where it goes, whether a specific place in Kazakhstan beats the strongest realistic rival on that factor for a large enough reachable market, and why the opportunity is still open*. Investor economics first; the KPMG oral briefing's principles are working tests throughout.
- Active supporting files: `opportunities/ANALYSIS_PLAYBOOK.md` (reasoning habits), `opportunities/RESEARCH_PROTOCOL.md` (evidence rules), `BENCHMARK_LESSONS.md` (quality bar), `DATA_SOURCES.md` (source map).
- `opportunities/SCREENING_APPROACH.md` is **reference / history**, superseded wherever it conflicts with the locked starting point.
- The 39-card pass in `opportunities/discovery/` is a Kazakhstan fact bank and one specific-assets discovery pass, **not** the primary opportunity universe.

## GITHUB SYNC POLICY

GitHub is the shared source of truth for all non-private project work: AI context, research, discovery outputs, analytical notes, benchmark lessons and project state. Google Drive holds official/private case materials, collaborative Sheets, models, Slides and final deliverables. Do not duplicate these artifacts unnecessarily.

- **Before substantive work:** check for local uncommitted changes (including untracked files) or an unresolved Git operation. If present, stop and tell the human; do not overwrite, reset or auto-stash their work. Otherwise sync safely with `origin/main` (fast-forward only), then re-read the latest `START_HERE.md` and task-relevant files.
- **During work:** change only task-relevant files. Prefer a separate research/output file to overwriting a teammate's work. Never modify `private/`, stage or push anything from it, or copy its contents into tracked files.
- **After creating or intentionally changing project files:** review the diff, fetch and safely reconcile with `origin/main` while preserving the intended task changes, then review the final diff. Stage only explicit intended files, commit with a descriptive message and automatically push to `origin/main`. Confirm push success and name the files pushed. Never force-push.
- **On any sync/push failure, missing permission or conflict:** stop and explain the problem. Preserve local work; do not silently resolve strategic/content conflicts or claim the work is shared before the push succeeds.
- **GitHub connector sessions:** read the latest repository version directly from GitHub, then the latest routing and task-relevant files. With write access, save completed task outputs back to the shared repository on `main` and verify success. With read-only access, clearly state that the result has **NOT been saved to GitHub**.

## Source routing

Before substantive work, after GitHub sync, identify the decision and which sources are required to answer it correctly. Read them directly from the system that owns them:

- **GitHub:** shared project context, research, analytical notes, methodology, benchmark lessons and current project state; follow the task-routing table below.
- **Google Drive:** use the existing [KPMG Case Competition 2026 folder](https://drive.google.com/drive/folders/1YZx-MiU48X_Z28pohdt6ypXvhZAxax-A) directly for official/private case materials, briefing notes and other private sources, `02 Master Opportunity Sheet` / the current collaborative tracker, financial models, the working deck and final deliverables.
- When both systems are needed and accessible, use both; do not ask the human to copy information between them. Read only task-relevant Drive artifacts, not everything in the folder.
- If a required Drive source is inaccessible, name the unavailable source, explain why access failed and why it matters to the decision. Do not guess its contents.
- Modify collaborative Drive artifacts only when the assigned task requires an update.

## Source hierarchy

- `Case Materials, KPMG Strategy & Operations.pdf` in Drive is the highest authority for formal requirements and outranks derived notes in a conflict. Consult it when interpreting requirements or deliverables.
- `kpmg_briefing_notes.md` in Drive contains important KPMG oral guidance, not formal written requirements. Consult relevant guidance for the task.
- `raw_briefing_transcript.md` in Drive is for verification only when oral wording is ambiguous.
- Human team decisions override AI-generated proposals. Never infer team agreement from an AI output or treat a proposal as adopted. Existing local source copies in `private/` remain read-only and must never be committed or pushed.

## Current state

Read `CURRENT_STATE.md` for the project stage, approvals and open questions (Phase 0 is closed; the method is locked). Respect documented proposal/adoption status. Flag discrepancies with newer work without inventing decisions. An explicit human task assignment authorizes that task within its stated scope; it does not imply broader approval or methodology adoption.

## Task routing

Load only relevant context; combine routes when a task spans them. Do not mechanically read every project file.

| Task involves | Read / consult |
|---|---|
| Any task | Read `LOCKED_STARTING_POINT.md` first. |
| Opportunity discovery or screening | Follow `LOCKED_STARTING_POINT.md` §4–§9. Consult `opportunities/SCREENING_APPROACH.md` only as reference (e.g. §3.3 economics by opportunity type). |
| Research or evidence gathering | Read `opportunities/RESEARCH_PROTOCOL.md`; use `DATA_SOURCES.md` as a source map where useful. |
| Strategic analysis, challenging a thesis or finalist review | Read `opportunities/ANALYSIS_PLAYBOOK.md`; consult `BENCHMARK_LESSONS.md` when useful as a quality benchmark. |
| Using the original 39-card pass | Read `LOCKED_STARTING_POINT.md` §14 first: fact bank and one specific-assets pass; no grandfathering. |
| An existing opportunity | Locate and read the relevant opportunity, discovery or research file before working, including relevant records in `opportunities/discovery/`. |
| Current team status or prior decisions | Read `CURRENT_STATE.md` and `DECISIONS.md` if it exists. |

For “Assess whether this opportunity deserves deeper research,” read its existing record, `LOCKED_STARTING_POINT.md` and the analysis playbook; also load the research protocol if gathering evidence.

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
