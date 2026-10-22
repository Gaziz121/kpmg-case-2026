# Execution plan: four owned inputs, one controlled merge

**Date:** 22 October 2026 (Almaty time).
**Scope:** current user-assigned execution/work allocation. Subordinate to `LOCKED_STARTING_POINT.md`; no methodology changes or opportunity selections are made here.
**Authority:** the assignments below authorize the named tasks. Individual research, rankings, screening recommendations and this file's production targets do not establish team-approved strategic decisions. Record team decisions only after explicit team agreement, with attribution.

## 1. Independent block: ownership and permitted inputs

Run the four streams simultaneously for approximately 60 minutes. There is no new human brainstorming stage. Each person creates and edits only their own output below, using the common format in §3. Paths are defined now; no research records or empty per-person files are created by this plan.

All four may consult the official case, raw briefing, locked starting point and relevant research-protocol instructions. The clean streams have the narrower loading rules in §2.

| Owner / working IDs | Task and purpose | Owned output under `opportunities/discovery/` | Additional permitted sources | Forbidden inputs / actions during this block |
|---|---|---|---|---|
| Gaziz / `GZ-###` | Consolidate only existing work Gaziz personally initiated or managed, including his Claude / Argon / other AI runs. Extract hypotheses, normalize, recover sources and deduplicate within that material. | `gaziz_consolidation_2026-10-22.md` | Gaziz-originated material that is accessible within the authorized scope; linked original evidence for verification. | Other participants' working outputs; importing Aibek's material as Gaziz-originated; new broad discovery; selecting winners; editing a shared master. |
| Aibek / `AB-###` | Consolidate only work Aibek personally produced or added, including his 59-hypothesis list and related findings. Same extraction and normalization task. | `aibek_consolidation_2026-10-22.md` | Aibek-originated material and linked original evidence for verification. | Other participants' working outputs; importing Gaziz's material as Aibek-originated; new broad discovery; selecting winners; editing a shared master. |
| Sagadat / `SG-###` | Clean discovery: (1) investor capital decisions; (2) regional customer problems. | `sagadat_clean_discovery_2026-10-22.md` | Only the restricted packet in §2 and live external research. | All previous opportunity lists, model outputs, rankings, favorites, both consolidations and Beknur's discovery until both of Sagadat's passes are complete. No winner selection or shared-master edits. |
| Beknur / `BK-###` | Clean discovery: (1) specialized services; (2) open assets / partnerships / entry structures. | `beknur_clean_discovery_2026-10-22.md` | Only the restricted packet in §2 and live external research. | All previous opportunity lists, model outputs, rankings, favorites, both consolidations and Sagadat's discovery until both of Beknur's passes are complete. No winner selection or shared-master edits. |

Consolidators remove rankings, stars, Top-5 labels and promotional wording from hypothesis records, while preserving original provenance separately (§3). Aibek's lens, priorities and prior deferrals remain his individual positions. A preparer cannot grant a hypothesis PASS by preparing it.

Do not infer ownership of the old 39-card pass or any other source from where it is stored. The relevant consolidator includes it only if its originating workflow belongs to that person; flag unresolved ownership for the merge. Existing human ideas follow the same attribution rule. The synthetic OKED list remains a coverage reference, not a set of investment hypotheses.

**Nobody may inspect, edit, stage or commit anything inside `Claude outputs/`.** The Gaziz assignment does not override this restriction. Log an unavailable source rather than accessing protected material or guessing its contents.

## 2. Clean-discovery packet and stopping rules

For each of their two routes, Sagadat and Beknur start a separate fresh AI context with only:

1. Their assigned route and the execution/output rules in this file, which contain no opportunity recommendations.
2. `private/Case Materials, KPMG Strategy & Operations.pdf` (formal authority).
3. `private/raw_briefing_transcript.md` (oral primary source).
4. `LOCKED_STARTING_POINT.md`.
5. Relevant evidence, source, uncertainty and time-box rules from `opportunities/RESEARCH_PROTOCOL.md`.
6. Live web research, prioritizing primary sources.

The explicit clean-discovery assignment is a task-specific exception to general project-context loading: do not load `CURRENT_STATE.md`, `DECISIONS.md`, briefing summaries, prior chat histories, discovery files, the OKED reference, or earlier model reports into these contexts. Read these execution instructions without following links to excluded material. Do not search the repository for candidate ideas. If a tool automatically injects excluded context, disclose the exposure and restart the affected route in a context with the permitted packet only; do not call the exposed run clean. The permitted methodology itself contains historical examples, so this is isolation from prior discovery outputs, not a claim of perfect experimental blindness.

| Owner | Route 1: approximately 20 minutes | Route 2: approximately 20 minutes |
|---|---|---|
| Sagadat | Identifiable strategic investors facing build, expansion, diversification, market-entry or supply-chain decisions; establish why Kazakhstan could compete for that capital. | Specific regional buyers with delivered-cost, lead-time, reliability, qualification or access problems that a Kazakhstan operation might solve. Avoid import-substitution shortcuts. |
| Beknur | MRO, servicing, testing, certification, qualification, asset operation and recurring B2B services with identifiable payers. | Specific brownfield, JV, acquisition, tolling or contracted-operation openings; assets or partnerships becoming available. An existing asset alone is insufficient. |

Use the remaining approximately 20 minutes to verify useful sources, prune vague leads and write cards. Keep both routes isolated from prior lists until the owner's independent block is complete.

- Up to two usable distinct hypotheses per route; no minimum; at most four per person. A route may return zero. Include a brief route-completion note even when it returns no cards.
- Roughly 150–200 words per card, excluding links and field names. Show the causal chain: **external fact → investor/customer problem → capital decision → Kazakhstan hypothesis**.
- Provide 2–3 strong initial source links supporting specific claims; prefer company annual reports, investor presentations, capex announcements, procurement plans, operator materials, project disclosures, regulatory/trade data and relevant industry associations. Do not pad citations or fabricate a missing source; record the gap as `not established`.
- Label substantive statements FACT / CALCULATION / ASSUMPTION / INFERENCE / JUDGMENT. Unknown fields remain `not established` or `unknown`.
- No ranking, stars, Top 5, detailed DCF/IRR, long sector reports or promotional language. Do not solve the whole case.
- Stop a route when its time-box ends or two usable distinct hypotheses have been found. Stop pursuing a lead if it remains only a sector/trend, lacks an articulable investor decision or paying market, relies on a generic Kazakhstan advantage, or encounters an evidenced fatal contradiction. Record an evidence-backed rejection without turning missing evidence into FAIL.
- Stop the independent discovery block at approximately 60 minutes. Do not extend it because a model offers more ideas.

## 3. One common working-output format

Each owner creates the named Markdown file in the existing discovery directory. Use the following header, replacing bracketed fields with the exact assignment from §1–§2. State the actual read restrictions in the file, not merely a link to this plan.

```text
# [Owner] — [consolidation / clean discovery] — 2026-10-22
Owner: [Gaziz / Aibek / Sagadat / Beknur]
Date: 2026-10-22
Purpose: [assigned task and, for discovery, both routes]
Status: WORKING INPUT — NOT TEAM-APPROVED
Mode: [CONSOLIDATION / CLEAN DISCOVERY]
Allowed sources: [explicit permitted packet and owner-specific source scope]
Forbidden sources/actions: [explicit excluded lists/outputs, other owners' edits,
                          shared-master edits, and Claude outputs/]
Context exposure: [none known / describe actual exposure and affected route]
Freeze: WORKING [replace with FROZEN and Almaty timestamp; report commit separately]
```

Under `## Hypotheses`, use one fenced CSV block with exactly this header. It is the common exchange format; it does not replace the existing longlist/evidence templates used later.

```csv
id,opportunity_name,investor_type,capital_decision,buyer_reachable_market,trigger_why_now,kz_location_asset,strongest_alternative,plausible_kz_deciding_advantage,why_still_open,cheapest_falsification_test,initial_evidence_links,important_unknowns
```

Use one record per hypothesis. Quote CSV cells containing commas or quotation marks; double quotation marks inside quoted cells. Keep each record on one physical line. Separate multiple evidence links with ` ; ` and include useful dates/locators. This lets the merge owner extract the same CSV block from all four files without interpreting different layouts. Do not add a fabricated example row. Zero hypotheses means a header-only block plus the route-completion note.

Assign `GZ-001`, `AB-001`, `SG-001` or `BK-001` onward within the correct stream. IDs are stable once issued: do not reuse a removed/merged ID. Nobody issues final `OP-###` IDs during independent work.

**Consolidation outputs only:** add `## Provenance — not for initial screening` with a separate fenced CSV block:

```csv
id,original_source_provenance,original_rankings_stars_labels,aliases_duplicate_mappings
```

Use one provenance row per original occurrence; repeat the retained working ID when several originals map to it. Retain original record IDs/locators, contributor/model identity, original ranking/labels, aliases and mappings of absorbed working IDs. Missing provenance remains `not established`. Never copy these fields into the hypothesis CSV. Clean outputs have no inherited rankings or prior-list provenance to import; their external evidence remains in the common hypothesis fields.

## 4. Git and publishing safety

- Each person works in a separate local checkout, syncing safely before substantive work under `START_HERE.md`. Do not run independent agents against the same checkout/index. If only one checkout is available, serialize repository editing and Git operations; parallel research can continue outside that shared checkout.
- During the independent block, each person edits only their named working output. Existing research, another owner's output, shared masters, `CURRENT_STATE.md` and `DECISIONS.md` are not parallel writing targets.
- Gaziz coordinates **one publishing turn at a time**. This is a publication/merge responsibility, not authority to select opportunities. Each owner publishes only their explicit owned file from their own checkout under the existing sync policy; do not include another person's files.
- Before each publication, fetch and safely reconcile with the current `origin/main` while preserving intended work. Review the final diff, stage only the intended path, commit and push without force. A disjoint filename helps avoid content conflicts but does not eliminate branch divergence or push races.
- On unexpected local changes, sync/push failure, missing permission or content conflict, stop and report under the existing policy. No reset, auto-stash, overwrite, force-push or silent substantive conflict resolution. Do not inspect another person's protected work to reconcile it.
- Each owner reports their frozen output path and published commit directly at handoff. Others wait for the freeze before consuming that stream. AI assistants do not message other people or chats without explicit authorization.

## 5. Freeze, controlled merge and screening handoff

**At approximately minute 60:** each owner freezes their output and completes publication in the coordinated turns. Record the freeze timestamp in the file; report the resulting commit at handoff (do not try to embed a commit's own hash into its contents). Keep the four snapshots unchanged after handoff. Gaziz is the single merge owner for this operation; any transfer of that responsibility must be explicit before editing begins. The other three discuss and review, but do not simultaneously edit the master.

Once all four frozen outputs are available, Gaziz:

1. Extracts the four hypothesis blocks; checks the common header, ID uniqueness, missing fields and source mappings. Missing fields are not silently invented. Incomplete/unavailable streams are disclosed rather than claimed as incorporated.
2. Deduplicates by the **investor capital decision**, not sector, asset, feedstock or product family. Preserves materially different variants; flags uncertain merges for the group instead of silently collapsing them.
3. Assigns neutral `OP-001`, `OP-002`, etc. IDs and retains every source/working-ID mapping underneath. Multiple appearances do not increase evidential strength.
4. Creates `opportunities/discovery/master_universe_2026-10-22.csv` with the same 13-column hypothesis header, now using `OP-###` in `id`. This is the neutral initial screening view, not a selected team longlist or a set of PASS decisions.
5. Creates `opportunities/discovery/master_universe_provenance_2026-10-22.csv`, separately, with `opportunity_id,working_id,contributor,original_source_provenance,original_rankings_stars_labels,aliases_duplicate_mappings`. Preserve all occurrences, including clean-stream working-ID mappings. Leave inherited-rank fields `not applicable` for clean discoveries. These two merge files are defined for that phase, not created in advance.
6. Checks the neutral view for contributor/model names, original ranking, stars, Top-5 labels, working-ID prefixes and repeated-mention counts. Remove recommendation language and author-revealing links to prior AI reports from that view; preserve them in the provenance file. Keep analytically necessary company names, locations, primary-source links and evidence visible. Do not order records by prior ranking or mention frequency.
7. Divides the neutral `OP-###` records into four non-overlapping queues with reasonably balanced effort, minimizing each person's own prepared material where practical. Give screeners only their neutral records and necessary evidence, not the provenance file or four source outputs. Recognition is possible; disclose it rather than claiming perfect anonymity.

The merge owner alone publishes the two merge files. No four-way master editing. Target a 15–30 minute merge/handoff after the inputs freeze; if intake or publication is incomplete, start screening ready batches and disclose outstanding work rather than extend discovery or select a funded pool before the remaining inputs are considered.

Screeners record recommendations in separately owned files, created when screening starts:

- `opportunities/discovery/gaziz_screening_2026-10-22.md`
- `opportunities/discovery/aibek_screening_2026-10-22.md`
- `opportunities/discovery/sagadat_screening_2026-10-22.md`
- `opportunities/discovery/beknur_screening_2026-10-22.md`

Each carries the owner/date/working-input status and records `OP-###`, PASS / UWT / PARK / FAIL recommendation, reason, evidence, important unknowns and next test with owner/time-box. Screeners do not edit the master or provenance file. Initial judgments are recorded before provenance is consulted for later evidence recovery. The merge owner incorporates reviewed results only after the screening handoff.

## 6. Decisions and the rest of execution

The sequence is: four owned inputs → controlled merge/deduplication → neutral universe → four cross-screening queues → cheap falsification → reconvene → funded survivors → opportunity owner plus independent challenger.

- Apply existing PASS / UWT / PARK / FAIL rules and progressive evidence standards. FAIL requires evidence; missing evidence is not FAIL. No new scorecard or mandatory survivor quota.
- Neither preparing a record nor recommending PASS grants team approval. At reconvening, humans explicitly agree what receives further research. Keep individual positions attributed; never silently promote research into `CURRENT_STATE.md` or `DECISIONS.md`. Any agreed updates to those shared files have one named editor and a separate publishing turn.
- For serious survivors, assign a different challenger from the owner. The challenger presents the initial status recommendation; the owner supplies evidence and corrects factual omissions. Follow the protocol's revealed-preference, outside-view, agency-counterfactual and strongest-NO-case requirements progressively.
- After this sprint, freeze open-ended discovery. Reopen a route only when a specific later fact exposes a materially different investor decision, with an explicit bounded test and a decision about which existing work it displaces. A request for more ideas is insufficient.
- Retain the operating targets: 22 October consolidation/screening and funded assignments; 23 October validation/cross-review; final five and teaser choice targeted by midday 24 October; production on 24–25 October; final checks and submission on 26 October before the confirmed cutoff. These are execution targets, not claims that selection has occurred. Protect production and QA time; do not fill five slots by disguising unresolved decisive evidence.
