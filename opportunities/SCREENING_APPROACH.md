# Opportunity Screening Approach

**Status:** PROPOSAL v2 (revised 20 Oct). The team has not adopted it yet.
**Scope:** How we discover and narrow investment opportunities. No niches have been researched, recommended or selected.
**Inputs:** Official case PDF and oral briefing notes (both in `private/`). Section references like "§8" point to `private/kpmg_briefing_notes.md`.
**Companion files:** `RESEARCH_PROTOCOL.md` (how evidence is gathered and logged) · `ANALYSIS_PLAYBOOK.md` (how to reason about each opportunity).
**Deadline:** 26 October 2026.

> The bar for every stage: *would a real strategic investor plausibly put capital into this in Kazakhstan, and can we prove why?*

---

## 0. Design principles

1. **Keep discovery and screening apart.** Discovery widens the set and screening narrows it. Mixing them causes anchoring: teams judge ideas while generating them and only "safe", data-rich ideas survive.
2. **Make ideas cheap to keep and cheap to kill.** Capturing an idea takes about a minute. Evidence requirements rise only when an idea earns more attention.
3. **Absence of evidence is not evidence of absence.** An idea is killed only by evidence *against* it, never just because historical data is thin. This protects non-obvious opportunities without quotas.
4. **Rigour increases as the funnel narrows.** Early tests ask "is this plausible enough to investigate?". The hard tests (the head-to-head comparison against the best alternative country, economics suited to the opportunity type) come at the finalist stage.
5. **The kill log is a deliverable.** KPMG wants to see how ideas were found and filtered and why the final five were chosen (§5, §6). Every killed or parked idea keeps a one-line reason.
6. **Questions first, scores only if useful.** Survivors are compared with analytical questions. Whether to score at all is a team decision once the team has seen the actual set of ideas. The Top 5 is a human portfolio decision (§5 below).
7. **Every claim needs a source with a working link** (§15). Evidence is logged *during* research (see `RESEARCH_PROTOCOL.md`).
8. **Keep it proportionate to six days.** Any step that costs more than it informs gets dropped.

---

## 1. The funnel

```
 STAGE 0  DISCOVERY UNIVERSE   one-line idea cards, ~1–2 min each, no source, no judgement
              │  quick triage: keep / merge / park (drop only with a stated reason)
 STAGE 1  LONGLIST             draft thesis + ≥1 evidence lead, ~5–10 min each
              │  early gates G1–G6 → PASS / FAIL / UNRESOLVED-WORTH-TESTING
 STAGE 2  SHORTLIST            survivors answered against analytical questions Q1–Q6
              │  team picks finalists by discussion
 STAGE 3  FINALISTS            validation tests V1–V5 (incl. rigorous Kazakhstan-vs-best-alternative test)
              │  human portfolio decision
 STAGE 4  TOP 5                + 1 chosen for the teaser
```

The number of ideas at each stage is not fixed. KPMG's real projects have had shortlists of roughly 37 and 82 (§6), so a large shortlist is fine as long as the logic is clear.

### Stage details

| Stage | Purpose | Entry rule | Effort per idea | Output |
|---|---|---|---|---|
| 0 Discovery universe | Keep every idea that might matter | An **idea card**: one-line idea, discovery lens, one line on why it might matter, contributor | ~1–2 min | Universe sheet |
| — Triage | Remove duplicates and nonsense, nothing else | On the universe | ~1 min, done as a group | Keep / Merge / Park (+ reason) |
| 1 Longlist | Make ideas comparable and testable | Kept at triage. Draft **thesis sentence** (the alternative-country slot may still be "?") + **≥1 evidence lead** (a link or a named dataset to check) | ~5–10 min | Longlist rows |
| Gates | Remove ideas with evidence of a fundamental flaw | On the longlist | ~15–30 min, only on the uncertain points | PASS / FAIL / UWT per gate + kill log |
| 2 Shortlist | Understand survivors well enough to compare them | No FAIL. Each UWT has a named test and owner | ~1–2 h | Short answers to Q1–Q6 with sources |
| 3 Finalists | Stress-test the serious contenders | Team selects by discussion | ~0.5 day | Finalist memo; V1–V5 completed |
| 4 Top 5 | Choose a defensible set | Finalist, all V-tests done | Team session | Top 5 + teaser choice, with written rationale |

**Idea card (Stage 0), the whole requirement:**

> *ID · idea in one line · lens · why it might matter (one line) · who added it*

**Thesis sentence (Stage 1 draft, sharpened as the idea advances):**

> *[Investor type] invests in [product / service / asset] in [Kazakhstan location], using [specific Kazakhstan advantage], to serve [identifiable payers] in [markets]. Main competing location: [country or "?"].*

**Triage rules (lightweight):** merge obvious duplicates. Park ideas too vague to turn into a thesis, with a note on what is missing. Drop an idea only if it is clearly outside the case scope or self-contradictory, and record the reason. "Not much data" is never a triage reason.

**Feedback loops (allowed, but limited):**
- **Reframe once.** An idea that FAILs a gate can return once in a new form, for example a different granularity, target market or value-chain step. This stops weak ideas from coming back again and again.
- **Splitting and merging.** A broad cluster can split into product-level rows, and narrow rows can merge into a cluster. Keep `related_ids` so the trail stays visible.
- **New discoveries are welcome at any stage,** but they enter as idea cards.

---

## 2. Discovery (separate from screening)

**Goal:** a diverse set of ideas that isn't anchored on the obvious sectors. KPMG expects obvious sectors to appear (§16), so let them, then deliberately go beyond them.

### 2.1 Discovery lenses

The lenses are grouped by where the idea starts. They are starting points, not a checklist. Each lens includes a question that prompts ideas and the kind of evidence that usually feeds it.

**A. Supply side: start from what Kazakhstan has**

| Lens | Prompt | Typical inputs |
|---|---|---|
| A1 Resource endowment | Which resources does Kazakhstan hold in globally significant amounts, and what is done with them today? | Geological / commodity statistics, export composition |
| A2 Value-chain step-up | Where does Kazakhstan export a raw or intermediate product that someone else processes one or two steps further? | Export data by HS chapter vs downstream imports of trading partners |
| A3 Installed base & by-products | What do existing plants, fields and farms produce as by-products, waste or spare capacity? | Industry reports, company disclosures |
| A4 Under-used assets | Which infrastructure, special economic zones, corridors, energy or land are under-used? | SEZ data, transport statistics |

**B. Demand side: start from who pays**

| Lens | Prompt | Typical inputs |
|---|---|---|
| B1 Neighbouring & regional demand | What do Central Asia, EAEU partners, western China and the Caspian / South Caucasus import in volume, and could they be served more cheaply from Kazakhstan? | Partner-country import data, tariff regimes |
| B2 Import gaps (KZ + region) | What does the region import at scale? *Never enough on its own; see gate G4.* | Trade statistics |
| B3 Anchor-customer demand | What do large operators already in Kazakhstan buy from abroad? | Procurement / local-content data, operator reports |
| B4 Global shortages & structural trends | Which global markets face structural supply gaps or rerouting? | International-agency outlooks, industry studies |

**C. Investor side: start from who invests**

| Lens | Prompt | Typical inputs |
|---|---|---|
| C1 Comparable-country FDI patterns | Which greenfield FDI went into countries with similar endowments or positions, and why not Kazakhstan? | UNCTAD, announced-project databases, press |
| C2 Supply-chain relocation | Which industries are actively diversifying their production locations, and what do they need from a host country? | Industry and consultancy studies |
| C3 Investors already present | What adjacent investments would the multinationals already in Kazakhstan logically make next? | Investment-agency materials, company reports |

**D. Change side: start from what's shifting**

| Lens | Prompt | Typical inputs |
|---|---|---|
| D1 Technology shifts | Which new technologies change where production is economic (for example energy-intensive, modular or digital processes)? | Technology and cost-curve reports |
| D2 Policy & trade-regime shifts | Which new incentives, trade agreements, carbon rules or standards change the economics? | Official policy documents |
| D3 Logistics & cost shifts | Which changes in routes, energy prices or freight costs alter Kazakhstan's position? | Transport and energy data |
| D4 Location-free services | Which digital or service exports don't depend on Kazakhstan being landlocked? | Services-trade data |

**E. Synthesis: where non-obvious ideas usually come from (§16)**

| Lens | Method |
|---|---|
| E1 Collision matrix | Cross a *trend* (B4 / D) with a *Kazakhstan asset* (A) and a *neighbour condition* (B1). Most cells are empty or silly. The few that aren't are candidates. |
| E2 Constraint inversion | List Kazakhstan's disadvantages (landlocked, distance, climate, small population) and ask which businesses *benefit from* or *don't care about* each one. |
| E3 Competitor weakness | Where are the credible alternative locations constrained (water, energy, sanctions, capacity, regulation)? |
| E4 Practitioner input | Short conversations with people in the industry, if any are reachable. Not scalable, but often the best source of non-obvious ideas. |

### 2.2 Anti-anchoring practices
- **Generate alone, then share.** Each team member generates ideas independently before seeing anyone else's list, AI output included.
- **Assign lenses to people.** Each person owns 2–3 lenses, so no lens goes unused. This spreads coverage; it is not a quota on outputs.
- **Tag obviousness.** Each idea is tagged `obvious` / `adjacent` / `non-obvious` for later reflection, not as a target.
- **No evaluation during discovery.** "That won't work" waits until the gates; triage only merges and parks.
- **AI ideas are labelled.** AI-generated ideas get `lens_source = AI` so the team can see how much of the universe came from humans.
- **Time-box discovery** so it doesn't eat the screening time.

---

## 3. Early gates

Gates **only kill or park ideas. They never rank them.** At this stage they ask whether an idea is *plausible enough to investigate*, not whether it is proven.

### 3.1 Outcome codes

| Code | Meaning | Rule |
|---|---|---|
| **PASS** | Plausible on available evidence | Move on |
| **FAIL** | There is **positive evidence** of a fundamental flaw | Needs a one-line reason + source. Thin or missing data is *not* a FAIL |
| **UWT** (unresolved, worth testing) | Can't tell yet, and the answer could change the decision | Must state **the test** (what evidence would resolve it) and an owner. Allowed into the shortlist; must be resolved before finalist validation |
| **PARK** | Can't tell, and testing isn't worth the time now | Kept in the parking lot with a note; can be revived |

**Advancement rule (proposed):** no FAIL → shortlist, with any number of UWTs as long as each has a named test. An idea where most gates are UWT is usually a sign it needs reframing, not that it should be killed.

**Protection for non-obvious ideas, without quotas:** a FAIL must cite evidence against the idea. When an idea tagged `non-obvious` is failed mainly on missing or historical data, a second teammate confirms it. Forward-looking evidence (structural drivers, analogue markets, announced projects, policy changes) counts at G2 and G3.

### 3.2 The six gates

| Gate | Early question (plausibility) | FAIL only when there is evidence that… | Briefing ref |
|---|---|---|---|
| **G1 Definable thesis** | Can we draft the thesis sentence (product/asset, payer, location, advantage)? | — (if it can't be drafted, PARK; don't FAIL) | §2, §24 |
| **G2 Credible paying demand** | Is there an identifiable payer, in a market that exists or is clearly forming? | demand doesn't exist or depends only on government wishes | §8 |
| **G3 Plausible strategic-investor scale** | Could the reachable market (domestic + realistic exports) plausibly support a strategic-investor-sized business? | the reachable market is structurally too small and can't be widened | §9 |
| **G4 Plausible Kazakhstan-specific advantage** | Is there a **specific, checkable** reason this could work better in Kazakhstan, worth investigating? *Generic geography and "we import it" don't count.* | the claimed advantage doesn't exist or is clearly held more strongly by the obvious competitors | §2, §10 |
| **G5 Executable** | Can investors realistically obtain the technology and know-how, with no critical input (water, power, skills, logistics) a structural showstopper? | technology transfer is implausible or a critical input is structurally unavailable | §12, §17 |
| **G6 Investor-economics plausibility** | Is there a **credible mechanism by which an investor earns an adequate return**: a payer, a revenue model and no obvious structural reason revenues can't cover costs plus the cost of capital? | returns depend entirely on subsidy; prices are capped below cost; or there is a large, structural cost disadvantage | §8 |

**Moved to the finalist stage:** the rigorous *Kazakhstan vs the strongest alternative location* comparison (V1) and the detailed economics (V2). At G4, naming the likely competitor is encouraged but not required.

**Red flags (not gates, but recorded):** sanctions or legal barriers; a thesis that mainly displaces existing domestic producers without adding value (§18); dependence on one fragile subsidy; severe environmental or water stress.

### 3.3 Economics by opportunity type

"Delivered cost below market price" fits manufacturing but not every opportunity. G6 asks the general question; at the shortlist and finalist stages, the economics follow the opportunity type. An idea can mix types (for example a cluster with an infrastructure anchor). The team uses whichever drivers are decisive.

| Opportunity type | What drives investor returns | Typical first check (G6 / shortlist) | Finalist-level analysis (V2) |
|---|---|---|---|
| **Export-oriented manufacturing / processing** | Delivered cost vs competitors, capacity utilisation, product price | Rough delivered cost vs prevailing import price in target markets | Unit-cost build-up vs the competitor location; capex per unit of capacity; margin and payback range |
| **Manufacturing for domestic / regional market** | The above + share of a limited market needed to reach minimum efficient scale | Reachable market vs minimum plant size | Same as above + share needed and how incumbents respond |
| **Resource extraction / upgrading** | Resource quality, position on the global cost curve, commodity price, capex intensity, fiscal terms | Is the resource known and of competitive quality? Is there an offtake market? | Position on the cost curve; sensitivity to the price deck; royalties and tax; offtake |
| **Infrastructure / logistics / energy** (asset-heavy) | Volumes or utilisation, tariff or contract structure, counterparty strength, regulated or contracted returns | Is there a contractable revenue stream and a credible counterparty? | Volume ramp, tariff logic, payback and IRR range, PPP / guarantee structure, counterparty risk |
| **Services / IT / digital** | Labour-cost and skills arbitrage, utilisation, client acquisition, scalability | Who buys, at what price, and is the talent pool real? | Unit economics per client or per engineer; wage-arbitrage benchmark; path to scale |
| **Platform / marketplace** | Transaction volume, take rate, network effects, cost of reaching scale | Is there a fragmented market with a pain point someone pays to solve? | Volume and take-rate scenarios; time and spend to critical mass; defensibility |
| **Agri-food** | Yield, input and water costs, seasonality, logistics and cold chain, export prices and access | Do agronomy and water allow it, and is there an export channel? | Per-hectare or per-unit economics; logistics to target markets; phytosanitary access |
| **Cluster / multi-asset** | The economics of the **anchor investment**, plus how follow-on investments reduce shared costs | Is there a viable anchor project on its own? | Anchor economics + sequencing + shared-infrastructure funding; avoid double-counting follow-on benefits |

The level of precision rises by stage: an order-of-magnitude logic at the gate, rough ranges at the shortlist, and stated-assumption ranges with sensitivities at the finalist stage. Full financial models are not a confirmed requirement (§26E).

---

## 4. Analytical questions for the shortlist and finalists

### 4.1 Why questions, not scores (for now)

Survivors are compared by answering six analytical questions in a few lines each, with sources. **No rating scale is assumed.** Once the team sees the actual shortlist, it decides whether scoring would help (§10, open questions). If the team does score later, the double-counting rules below still apply, and the team should check whether the leading group survives different weightings.

Changes from the original list of criteria, carried over from v1: **investor attractiveness** is the overall question these answer, not a separate item. **Market potential + exportability** are merged (Q1). **Strategic fit + economic impact** are merged (Q6). **Originality** is not scored; it matters through discovery and the portfolio discussion. **Evidence confidence** is noted separately from attractiveness for every answer.

### 4.2 The six questions

| # | Question | What it measures | Why it matters | Typical evidence | Double-counting rule |
|---|---|---|---|---|---|
| **Q1** | How large is the market a Kazakhstan-based business can *realistically* reach, and is it growing? | Reachable demand after logistics, tariffs, trade regimes | Strategic investors need scale; the domestic market is often too small (§9) | Trade / consumption data for target markets; growth outlooks; market-access check | Q1 = how big the reachable pie is. Why Kazakhstan gets a slice belongs in Q2 |
| **Q2** | What specific, durable advantage does Kazakhstan offer, and how does it compare with the strongest alternative location? | Size and durability of the edge (cost, resource, access, policy) | Prevents "demand + inputs = opportunity" errors (§10) | Shortlist: the decisive driver identified. Finalist: a side-by-side comparison (V1) | Q2 is about *relative position*; absolute returns go in Q3 |
| **Q3** | How would the investor make money, and what drives returns? | The economics mechanism for the opportunity type (§3.3) | "The economics must work for the investor" (§8) | Type-appropriate first check → V2 at the finalist stage | Q3 is the *base case*; execution risk goes in Q5 |
| **Q4** | What's the market structure, and how will incumbents respond? | Room in the market, incumbent strength, global overcapacity, price pressure, impact on local producers | A big market dominated by low-cost incumbents may still be unattractive | Market-share data, capacity reports, price trends | Q4 is about *firms*; location competition is in Q2 |
| **Q5** | How hard is it to execute, and what could go wrong? | Technology access, skills, infrastructure, permits, time to revenue, key dependencies | A strong idea that can't plausibly be executed is weak (§17) | Precedents in comparable countries, infrastructure and skills data | G5 = possible at all; Q5 = how hard. Count government support here only if it is concrete (an existing incentive) |
| **Q6** | What value does it create for Kazakhstan, and does it fit national direction? | (a) Policy fit and likely support; (b) exports, jobs, diversification, linkages, technology transfer | Required for relevance (§11) | Policy documents; rough jobs / export estimates | Must never compensate for weak Q1–Q3 (§8) |

Each answer also states its **confidence** (how solid the evidence is) and the **weakest assumption** (see `ANALYSIS_PLAYBOOK.md`).

### 4.3 Finalist validation tests (V1–V5)

| Test | Requirement |
|---|---|
| **V1 Kazakhstan vs best alternative** | Name the strongest competing location (where incumbents produce, where new capacity is going, or the neighbour with the closest endowment). Compare side by side on the **2–4 drivers that decide the economics** for this opportunity type. Kazakhstan must win, or match it with a clear additional reason (market access, policy, timing) |
| **V2 Economics for the opportunity type** | The finalist-level analysis from §3.3, with assumptions in the register and a sensitivity on the weakest one |
| **V3 Triangulated market** | Key market numbers from ≥2 independent sources, or a top-down and bottom-up cross-check |
| **V4 Challenge round** | A teammate who didn't build the case challenges it as a sceptical investment committee would (`ANALYSIS_PLAYBOOK.md` §8) |
| **V5 No open UWTs** | Every UWT from the gates is resolved: PASS or FAIL |

---

## 5. Top 5: a human portfolio decision

The Top 5 is chosen by the team in a discussion, **not** read off a sorted list, and there are **no diversity quotas**.

**Step 1: individual defensibility.** Each candidate must have passed V1–V5. An idea that is weak on its own is not rescued by "balancing" the set.

**Step 2: the set as a whole.** The team discusses:
- **Overlap:** are any two essentially the same bet (same thesis, same risk, same buyer)? If so, keep the stronger one or merge them.
- **Coherence:** do the five together say something credible about where Kazakhstan is investable?
- **Close exclusions:** is a candidate just outside the five stronger than the weakest inside? Argue it out explicitly.
- **Concentration:** if the five end up concentrated (one sector, one market, one risk), is that what the evidence says, or a symptom of anchoring? Concentration is allowed if justified.
- **Teaser fit:** which finalist has the clearest investor story, the best evidence and the most concrete numbers?

**Step 3: record it.** Write one paragraph per selected niche and one line per close exclusion. Once the team agrees, log the decision in `DECISIONS.md`.

Diversity that appears in the final set should result from the evidence, not from a rule.

---

## 6. Data structure

Templates are in `opportunities/templates/` (CSV, ready for Google Sheets or Excel). The longlist becomes the basis for Deliverable 1 (Excel + 1 slide).

| File | One row per | Used from |
|---|---|---|
| `discovery_universe_template.csv` | Idea card | Stage 0 |
| `longlist_template.csv` | Opportunity (from the longlist onwards) | Stage 1 |
| `evidence_log_template.csv` | Claim (fact, calculation, assumption, inference) | Any time evidence is found |
| `sources_register_template.csv` | Source | Any time a source is used |
| `assumptions_register_template.csv` | Assumption | Any time data is missing |

### 6.1 Discovery universe (deliberately minimal)

`card_id, idea, lens, why_it_might_matter, contributor, lens_source, obviousness, triage, triage_note, longlist_id`

### 6.2 Longlist (fields fill in as the idea advances)

**At longlist entry (~5–10 min):** `id, card_ids, name, thesis_sentence, granularity, hs_codes, opportunity_type, discovery_lens, lens_source, obviousness, product_or_service, payers, target_markets, kz_advantage_hypothesis, likely_competitor_location` (may be "?")`, evidence_leads, main_failure_risk, stage, owner`.

**At the gates:** `g1`–`g6` (PASS / FAIL / UWT / PARK), `gate_notes, uwt_tests, red_flags, kill_or_park_reason, reframed_from`.

**At the shortlist / finalist stages:** `q1`–`q6` (short answer or link to a memo), `confidence_note, weakest_assumption, v1_alt_location_result, v2_economics_result, v3_market_triangulated, v4_challenge_done, evidence_ids, related_ids, last_updated`.

Field values are listed in `templates/README.md`.

---

## 7. Evidence standards (summary)

Full rules are in `RESEARCH_PROTOCOL.md`.

| Level | Required to reach | Minimum evidence | Effort per idea |
|---|---|---|---|
| **E0** | Discovery universe | Idea card. No source | ~1–2 min |
| **E1** | Longlist | Draft thesis + ≥1 evidence lead (a link or a named dataset) | ~5–10 min |
| **E2** | Shortlist | Every gate PASS backed by a source or labelled assumption; every UWT has a test; Q1 sized to order of magnitude | ~30 min–1 h |
| **E3** | Finalist | Q1–Q6 answered with sources; decisive drivers identified; assumptions logged | ~1–2 h |
| **E4** | Top 5 | V1–V5 complete; all numbers traceable to an evidence ID | ~0.5 day |

---

## 8. Human judgement vs AI acceleration

### AI can speed up
- Generating *additional* hypotheses per lens, **after** humans have generated their own, labelled `lens_source = AI`
- Pulling and reshaping trade and statistical data; first-pass calculations
- Finding candidate sources (a human opens and checks each one)
- Drafting thesis sentences and gate notes for humans to edit
- Red-teaming: producing the strongest argument *against* an idea
- Checking consistency across the five analyses (numbers, terms, sources)

### Decisions that stay human
- Which lenses to prioritise and how much time to spend on discovery
- Every **FAIL** on an idea tagged non-obvious, and every triage drop
- Granularity choices: what counts as "the niche"
- Naming the strongest alternative location and judging V1
- Whether to score the shortlist at all, and how
- **Top 5 selection and teaser choice**
- The storyline and final wording of all deliverables (§22 warns against obviously AI-written work)

### Where mechanical scoring is dangerous
- **Ranking ideas of different granularity** (a broad cluster vs an HS-code product): their scores aren't comparable
- **Non-obvious ideas** where historical data doesn't exist yet: low data looks like low attractiveness
- **Additive scores hiding a fatal flaw:** a strong market can offset a near-fatal execution problem
- **False precision:** weighted totals to two decimals suggest a certainty we don't have
- **Choosing the Top 5 by sorting:** it ignores overlap between ideas and how the five fit together

### Where qualitative judgement must lead
- Theses built on structural shifts (technology, trade regime, rerouting), where the past says little about the future
- Lens E ideas (collisions, inversions), whose case rests on reasoning more than statistics
- Judging whether a technology holder would actually transfer know-how
- Judging how incumbents and competing countries are likely to respond

For these, the evidence standard shifts from historical data to a **clear causal chain + analogue cases + clearly labelled assumptions**, and UWT is used instead of FAIL until a real test has been run.

---

## 9. Proposed timeline (for discussion)

| Date | Focus |
|---|---|
| Wed 21 Oct | Team adopts the method; discovery by lens (independent, then shared); triage; longlist drafting |
| Thu 22 Oct | Gates and kill log; shortlist answers Q1–Q6; decide whether to score; pick finalists |
| Fri 23 Oct | Finalist validation V1–V5; Top 5 decision; teaser choice |
| Sat 24 Oct | Five analyses (5–8 slides each, assumed; the PDF wording is unclear) |
| Sun 25 Oct | Teaser (≤3 slides); Excel + summary slide; source and link checks |
| Mon 26 Oct | Final QA, submit |

---

## 10. Methodological risks

1. **Streetlight bias.** The screen favours ideas that already have rich trade data, which are mostly the obvious ones, and kills the non-obvious ideas KPMG rewards. *Mitigation:* FAIL requires evidence against the idea; the UWT code; forward-looking evidence accepted at G2 and G3; second-person check on non-obvious FAILs.
2. **Mismatched granularity.** Clusters, sub-sectors and HS-code products compared side by side make the comparison meaningless and produce a confusing Top 5. *Mitigation:* a granularity convention agreed before discovery, plus splitting and merging.
3. **UWT becomes a hiding place.** Too lenient early gates can carry too many unresolved ideas into the shortlist and overload the team. *Mitigation:* each UWT needs a named test and an owner; a time-box for resolving it; parking when testing isn't worth the time.

Other risks to watch: score-driven selection (scoring only if the team chooses it), the import-substitution trap (G4), treating the domestic market as enough (G3), economics framed for the wrong opportunity type (§3.3), and source debt piling up until the end (evidence log filled during research).

---

## 11. Open questions for the team

See `CURRENT_STATE.md` for the list to decide on 21 October.
