# Research Protocol

**Status:** ACTIVE (21 Oct), subordinate to `LOCKED_STARTING_POINT.md`. Capital-movement evidence: announced/MoU = weak; signed = stronger; financed / under construction / operating = strongest.
**Applies to:** every teammate and every AI tool doing research for the case.
**Companions:** `SCREENING_APPROACH.md` (the funnel) · `ANALYSIS_PLAYBOOK.md` (how to reason) · `templates/` (logs).
Briefing references like "§15" point to `private/kpmg_briefing_notes.md`.

> Research exists to make a decision, not to fill slides. Stop when the decision is clear.

---

## 1. Start with the decision question

No research starts without a **research brief** of five lines, written in the row's notes or at the top of a memo:

```
DECISION:   What will this research decide? (e.g. "Does OPP-0xx pass G3?")
HYPOTHESIS: What do we currently believe, stated so it could be wrong?
KILL TEST:  What finding would make us drop or downgrade the idea?
TIME-BOX:   How long is this worth? (see §10)
STOP RULE:  We stop when ___ (decision is clear / time-box ends / source found)
```

If you can't name the decision, the research isn't ready to start.

---

## 2. Work from hypotheses

1. **Write what must be true** for the opportunity to work: 3–6 statements covering demand, scale, Kazakhstan advantage, executability and economics.
2. **Order them by risk.** Research first the claim that is most likely to be false *and* would kill the idea if it were. Don't start with the easy, confirming facts.
3. **Research one claim at a time** against its kill test.
4. **Update the thesis**, not just the notes. If a finding changes the story, rewrite the thesis sentence.

---

## 3. Evidence that confirms vs evidence that kills

Look for disconfirming evidence on purpose. One strong piece of evidence against a claim outweighs several weak confirmations.

| Claim | Would support it | Would weaken or kill it |
|---|---|---|
| **Demand exists** | Sustained trade or consumption volumes; named buyers; signed offtakes; structural drivers with evidence | Volumes falling; demand only in government plans; buyers locked into other suppliers |
| **Reachable scale** | Import volumes in markets with workable access (tariffs, logistics, standards); growth outlook from credible sources | Market needs certification Kazakhstan producers lack; transport cost exceeds product margin; market dominated by one supplier under long contracts |
| **Kazakhstan advantage** | A quantified cost or access gap on the main cost driver; existing comparable operations | The obvious competitor has the same advantage, more strongly; the advantage is temporary or subsidy-based |
| **Executability** | Comparable projects in similar countries; technology available from several holders; skills present | Technology held by very few firms unlikely to transfer it; critical input (water, power, skills) known to be scarce |
| **Investor economics** | Comparable listed companies' margins; plausible price vs cost logic; contractable revenue | Prices below plausible cost; returns rely on a single subsidy; global overcapacity |

For **non-obvious ideas** with little historical data, the evidence shifts toward a **causal chain** (why the change happens), **analogues** (where something similar has happened) and **leading indicators** (announced projects, policy changes, price signals). Missing history is a reason for UWT, not for FAIL.

---

## 4. Prefer primary, authoritative evidence

- **Go to the original.** If an article cites a dataset or report, find and cite the dataset or report itself.
- **Use the most authoritative body for the claim type:** statistics agencies for statistics, regulators for regulation, company filings for company data, legal texts for law.
- **Prefer recent data,** and note the year. If the latest data is old, say so.
- **Match the definition.** Check that the source measures what the claim says (product scope, HS code level, units, geography, year).

---

## 5. Source tiers

| Tier | Type | Examples (no specific claims implied) | Use |
|---|---|---|---|
| **T1** | Primary official data, laws, regulators, company filings | National statistics offices, central banks, customs data, government decrees, annual reports | Preferred for any number on a slide |
| **T2** | International organisations and official multilateral datasets | UN Comtrade, ITC Trade Map, World Bank, IMF, UNCTAD, OECD, IEA, USGS | Preferred for cross-country comparisons |
| **T3** | Industry bodies, research institutes, consultancy and data providers | Industry associations, academic papers, published consultancy studies | Acceptable; check the methodology |
| **T4** | Reputable press and trade media | Established business and trade publications | For events, announcements and deals; use T1–T3 for numbers where possible |
| **T5** | Everything else | Blogs, forums, unattributed web pages | Leads only; never the sole support for a claim |

**AI outputs are never a source.** AI can point to a source. A human opens it, confirms the claim and logs it.

---

## 6. Triangulate important numbers

**Important number** = any number that decides a gate or validation test, or appears as a headline on a slide (market size, investment size, cost advantage, growth rate, jobs).

- **Required at finalist and Top-5 stages:** ≥2 **independent** sources, *or* one T1/T2 source plus an independent cross-check (top-down vs bottom-up, a proxy, or a reasonableness check).
- **Independence check:** two articles quoting the same report count as one source.
- **Record the range,** not just the chosen value. Choose the base case explicitly and explain the choice.
- **Round to the precision the evidence supports.** "≈USD 1–1.5 bn" is more honest than "USD 1.284 bn".

---

## 7. When sources conflict

1. **Check the definitions first:** product scope, HS level, units, nominal vs real, currency, year, geography. Most conflicts disappear here.
2. **Check the reporting side for trade data:** exports reported by one country often don't match the partner's reported imports (mirror data). Note which side you use and why.
3. **Prefer** the higher tier, the more recent, the closer definitional match and the transparent methodology.
4. **If it's still unresolved,** show the range, use the conservative value in the base case, and test whether the decision changes across the range.
5. **Log the conflict** in `conflicts_note` (evidence log). If the decision changes across the range, escalate the question to the team.

---

## 8. Working links

- Link to the **specific page, table or dataset query**, not a homepage. Add a `locator` (page, table number, chart, HS code, query parameters).
- Record `accessed_date` when the source is first used.
- For PDFs, give the page number. For database queries, record the parameters so a reviewer can reproduce the result.
- **Paywalled or login-only:** mark it in `notes`, and find an open alternative for any headline number.
- **Link check:** every link in the final deliverables is reopened before submission (Sunday 25 Oct), and `link_checked_date` is filled in. Materials without working sources may be skipped by reviewers (§15).

---

## 9. Missing data and assumptions

KPMG allows reasonable assumptions when data is unavailable, but they must be stated and justified (§14). Use this ladder, from best to weakest:

1. **Direct data** for the exact claim
2. **Proxy data** (a related product, an analogue country, an earlier year adjusted)
3. **Derived calculation** from sourced components
4. **Reasoned assumption** with a stated basis (benchmark, expert view, analogue)
5. **Explicit placeholder** ("not publicly available, assumed X for illustration")

**Rules:**
- Every assumption gets an `assumption_id` with value or range, basis, sources, **sensitivity** (what changes if it is wrong) and **how to test** it.
- An assumption never appears on a slide as if it were a fact; it is labelled.
- Key assumptions are given as **ranges**, and the analysis shows whether the conclusion survives the range.
- Invented numbers without a basis are not allowed (§14).

---

## 10. Evidence standards by stage

Evidence requirements rise as the funnel narrows. Matches `SCREENING_APPROACH.md` §7.

Apply the four reasoning checks in §14 progressively within the existing stages and time-boxes; `LOCKED_STARTING_POINT.md` governs where older stage references differ. Early hypotheses do not require full comparable research. Serious survivors do; every shortlisted opportunity needs the agency counterfactual, and a serious opportunity needs the strongest NO case before PASS and again before final Top-5 entry.

| Level | Stage | Minimum evidence | Time-box per idea |
|---|---|---|---|
| **E0** | Discovery universe | Idea card only. No source required | ~1–2 min |
| **E1** | Longlist | Draft thesis + ≥1 evidence lead (link or named dataset) | ~5–10 min |
| **E2** | Shortlist (after gates) | Each PASS backed by a source or labelled assumption; each FAIL backed by evidence against; each UWT has a named test and owner; Q1 sized to order of magnitude | ~30 min–1 h |
| **E3** | Finalist | Q1–Q6 answered with sources; decisive return drivers identified for the opportunity type; assumptions logged | ~1–2 h |
| **E4** | Top 5 | V1–V5 complete: Kazakhstan vs best alternative, type-appropriate economics, triangulated market, challenge round, no open UWTs; every slide number traceable to an `evidence_id` | ~0.5 day |

---

## 11. Avoiding over-research of weak ideas

- **Kill-first ordering:** research the most dangerous claim first (§2).
- **Respect the time-box.** When it runs out, decide: PASS, FAIL, UWT with a smaller test, or PARK. "Keep researching" is not an option without a new time-box.
- **The "would it change the decision?" test:** before looking up another fact, ask whether any plausible answer would change the gate or ranking. If not, skip it.
- **Two-strike rule:** if two time-boxed attempts can't resolve a UWT, PARK the idea and record what's missing.
- **Don't polish before selection.** No slide-quality writing or charts before the Top 5 is chosen.
- **Daily check:** at the end of each day, list the ideas that consumed the most time and ask whether that was justified.

---

## 12. Logging evidence for slide citations

The **evidence log** is the bridge between research and slides.

**Flow:** find a source → add it to `sources_register` (once) → log each claim in `evidence_log` with `claim_type`, value, unit, period, geography and `source_ids` / `assumption_ids` → slides cite the `evidence_id`, which resolves to a citation.

**Claim types** (also used in `ANALYSIS_PLAYBOOK.md`): `fact` (stated in a source), `calculation` (derived from logged facts; formula in `calculation_note`), `assumption` (from the assumptions register), `inference` (a reasoned conclusion from evidence), `judgment` (the team's view).

**Slide citation format (proposal):**
- Footnote on the slide: *Source: Organisation, Title (Year), [short URL or link]; table/page.*
- For calculations: *Team calculation based on [source A], [source B]; see Excel tab X.*
- For assumptions: *Assumption A-0xx: [one line]; basis: [one line].*

**Calculations must be reproducible:** every calculation lives in the Excel workbook with its inputs linked to evidence IDs.

---

## 13. Use of AI in research

- **Allowed:** finding candidate sources, summarising long documents, data processing, calculations, translation, drafting the research brief, red-teaming.
- **Required:** a human opens each cited source and confirms the claim before it enters the evidence log (`verified_by`).
- **Not allowed:** citing AI output, logging numbers produced by AI without a source, or presenting AI-written narrative unedited (§22).

---

## 14. Four reasoning checks for serious survivors

These checks test the existing investor-location thesis; they do not create a new framework, ranking or weighted scorecard. Apply them as the opportunity advances, using the existing research brief, evidence logs and PASS / UWT / PARK / FAIL outcomes.

### 14.1 Application and evidence rules

- **Keep cheap screening cheap.** Run simple kill tests first, including captured status and reachable scale. Stop on an evidenced fatal weakness; do not spend time finding 2–3 comparables or base rates for an idea that already fails.
- **Deepen only serious survivors.** Research revealed preference for each serious survivor and the outside view for material opportunities during validation / deep research. Assess the agency counterfactual for every shortlisted opportunity. Construct the NO case before a serious opportunity receives PASS; revisit it before final Top-5 entry and when decisive evidence changes.
- **Use primary sources first:** company announcements, investor presentations, project filings, government investment announcements and management interviews. Use credible industry sources to fill gaps, tracing their claims to originals where possible (§4–§5).
- **Every material external finding needs a working URL,** including findings against the thesis. Record the source date, accessed date and relevant locator under §8; source IDs must resolve to those links. Verify that the linked source supports the exact claim.
- Label substantive statements **FACT / CALCULATION / ASSUMPTION / INFERENCE / JUDGMENT** (the existing `claim_type` codes in §12 remain lowercase). Distinguish a stated investor rationale from our inference about causation. Where evidence is unavailable, write **"not established"**, state what was searched and what remains unknown; do not fill the gap with invented facts or logic. Any assumption used to test the gap remains explicit under §9.
- Record the implication for the thesis and confidence. An unresolved decisive claim is UWT with a test, owner and time-box; FAIL needs evidence against the idea. A fatal contradiction is not offset by favorable findings elsewhere. Keep final selection with the human team.

### 14.2 Revealed preference: actual investor choices

**Question:** does our theoretical location logic match real investor behavior?

For every serious surviving opportunity, research **2–3 comparable real investment/location decisions where possible**. Explain why each is comparable on the activity, market, scale or deciding factor. Finding similar companies or plants alone is insufficient.

Establish who invested, the capacity/activity funded, realistically considered locations **if public**, the location ultimately chosen and the factors evidenced as driving that choice. Test whether those observed factors support or contradict the assumed deciding factor for Kazakhstan. If the alternatives or actual decision logic are not public, record **"not established"**; do not invent a shortlist or infer a motive merely from the chosen location. If fewer than 2–3 useful decisions are available, record the search limitation and its implication for confidence.

**Required record, per comparable:**

| Field | Required content |
|---|---|
| Comparable | Investor, project, capacity/activity, decision date and why comparable |
| Location decision | Chosen location; realistic alternatives if disclosed, otherwise "not established" |
| Observed deciding factors | Sourced rationale; distinguish investor statements from our inference and flag unpublished logic |
| Implication for our thesis | Supports / contradicts / inconclusive on Kazakhstan's assumed deciding factor, with the reason |
| Evidence | Source links / evidence IDs, dates, locators and claim-type labels |

### 14.3 Outside view / base rate: what happens to projects

**Question:** what normally happens to comparable projects, rather than what the announcement promises?

Build a small, explicitly defined comparable project set where possible. State the selection basis, geography, period and differences that limit transfer to Kazakhstan. Look for stalled, cancelled or delayed projects as well as operating successes; a list of completed plants alone cannot establish a completion rate.

For each project, distinguish **announced / MoU → signed / permitted → financed / FID → under construction → operating**. Record the specific milestone actually evidenced: signing is not a permit, FID is not proof of financing, and neither is operation. Record achieved dates, latest status as of the research date and any cancellation, stall or delay; separate planned dates from actual dates. An announcement is not evidence of eventual completion, and a project still progressing is not automatically a failure.

Ask whether comparable projects reach operation, where they fail, how long they take and which blockers recur. Check whether the industry has many announcements but few completed projects. Use observed timelines or ranges with their starting milestone; if there is no reliable comparison, say **"not established"**. Do not manufacture percentages. A numerical base rate requires real data with a defined cohort, denominator, observation period and treatment of projects still in progress; otherwise describe the small set without claiming statistical representativeness.

**Required record:** comparable project set and selection limits; each project's observed milestone/outcome and dates; observed time to operation or delays; main recurring blockers; implication for confidence in our thesis; source links / evidence IDs and claim-type labels.

### 14.4 Agency counterfactual: decision-changing intervention

For **every shortlisted opportunity**, ask:

> If Kazakhstan's investment-promotion agency did nothing, would this investment likely happen anyway?

First describe the likely investment decision without agency action: whether it proceeds in Kazakhstan, proceeds elsewhere, is delayed or does not proceed. Identify the specific friction and the exact action that could change that outcome. Test whether the agency can deliver or coordinate it and whether it is likely to change the investor's decision. Do not credit generic government "support" or assume that the existence of an instrument makes it decisive.

Possible interventions include closing an investor information gap; land/site coordination; infrastructure connection; licensing/permitting coordination; feedstock access; a buyer/offtake consortium; JV / partner identification; state-company coordination; financing/co-investment; an SEZ/customs/tax instrument; or cross-agency coordination. Tie any proposed action to an evidenced blocker rather than copying this list.

Classify the role, with an explicit basis:

- **STRONG AGENCY ROLE:** a specific, feasible agency intervention is likely to change whether or where the investor commits capital.
- **MODERATE AGENCY ROLE:** a specific intervention plausibly improves timing, scale or probability, but is only partly decisive.
- **WEAK AGENCY ROLE:** the investment likely happens anyway, or the proposed action does little to resolve the deciding friction.
- **UNCLEAR:** the counterfactual, blocker or decision-changing effect is not established.

**Required record:** counterfactual without agency; blocker; concrete agency action and responsible body/coordination route; whether the action is likely decision-changing and why; role classification; evidence/source links where applicable. Label the counterfactual and classification as INFERENCE or JUDGMENT as appropriate. Assess promotion actionability separately from investor economics; agency support cannot rescue a failed investor case.

### 14.5 Adversarial / NO case: attack the central thesis

Before a **serious opportunity receives PASS or enters the final Top 5**, construct the strongest case against it from all three perspectives:

| Perspective | Required challenge |
|---|---|
| Investor CFO | Why should I NOT allocate capital to Kazakhstan? Attack the return mechanism or decisive assumption. |
| Strongest rival location | Why does my location beat Kazakhstan on the factor that actually decides this investment? |
| Skeptical KPMG judge | What is the weakest assumption, missing evidence or reason this is not truly investor-ready? |

Each objection must attack the opportunity's **central causal thesis**, not become a generic risk list. Seek evidence supporting the objection before drafting a response. A response is valid only to the extent that evidence supports it; an optimistic assertion does not close the challenge. If no evidenced response exists, write **"not established"** and identify the unresolved test. Use the existing challenge round where applicable rather than creating a parallel review process.

**Required record:** strongest CFO objection; strongest rival-country/location argument; strongest judge objection; evidence/source links supporting each; response and supporting evidence if available; resulting PASS / UWT / FAIL status and whether/why it changes. Unresolved decisive objections remain UWT; evidenced fatal contradictions can produce FAIL regardless of other attractions. Do not promote unresolved decisive claims into a final Top-5 recommendation.

### 14.6 Existing opportunity-record fields

Use the four concise fields in `templates/longlist_template.csv`. Each can hold a short finding plus evidence IDs or a link to the detailed note containing the required fields above. Populate them progressively; early ideas need no full record. Once a check is due, missing evidence is recorded as **"not established"** with the gap/test, not left to imply completion.

- `revealed_preference_evidence`: actual location choices, observed deciding factors and implication for the thesis (§14.2).
- `outside_view_evidence`: comparable outcomes, timing, recurring blockers and implication for confidence (§14.3).
- `agency_counterfactual`: without-agency outcome, blocker, concrete action, decision-changing effect and role classification (§14.4).
- `strongest_no_case`: CFO / rival / judge objections, evidence, evidenced response if any and status impact (§14.5).
