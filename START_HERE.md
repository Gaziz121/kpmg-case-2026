# Start here

Use this guide to load the context needed for the assigned KPMG case task.

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
