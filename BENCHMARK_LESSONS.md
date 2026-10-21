# Benchmark Lessons: What Winning Case Decks Actually Do

**Purpose:** show what strong case reasoning looks like in published winning solutions, so the team can apply the *behaviours* to the KPMG case. We copy no frameworks or recommendations.
**Compiled:** 20 Oct 2026.
**Method and limits:** all three cases come from the official CBS Case Competition library (https://www.casecompetition.com/library/), which publishes the case **and** the placed solutions. The decks were read through automated text extraction, so charts and visual layouts may be under-represented. **Spot-check any number against the original PDF before quoting it.** What follows reconstructs only what is *observable* in the case and the deck; it does not claim to know the teams' or judges' reasoning.

**Why these three:** each competition published the case brief alongside the winning deck, and together they cover the three needs.

| # | Case | Why selected |
|---|---|---|
| A | **European Energy, CBS GLOBAL 2025:** battery storage expansion across 10 markets (1st place: TrueSouth Consulting) | Investment / infrastructure allocation under a capital limit; narrows 10 countries × 2 project types × 3 contract types to 4 markets; heavy quantification |
| B | **Ørsted, CBS GLOBAL 2023:** offshore wind auction prioritisation to 2030 (1st place: Kosciuszko Consulting) | Narrowing a large set of auctions; an explicit decision matrix of rejected alternatives; a creative leap tied to a measurable mechanism |
| C | **Vestas, CBS Invitational 2023:** entering Power-to-X / green hydrogen (1st place: University of Hong Kong) | Nascent market with thin data; narrows by value chain, region and business model; the closest analogue to a non-obvious opportunity |

**Not selected:**
- *Smith National MBA 2025, "The Arctic Bridge"* is a national infrastructure / PPP case, but only the case package is public (https://smith.queensu.ca/mba_programs/mba/case-competition/case-package.pdf). No winning deck has been published.
- *NIBS* and others: no official, verifiable winning decks found in the time available.

---

## Case A: European Energy, battery storage (BESS) expansion 2026–2028

Case: https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2025/11/European-Energy-BESS-Case-Final.pdf
Winning deck: https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2025/11/CBS_2025_Final_Cleaned_Up.pdf

1. **Decision.** Where and how to deploy a **€300m equity budget (max €100m/yr)** for battery storage in 2026–28. That meant choosing among 10 countries, retrofit vs standalone projects, and three contract types (tolling, floor or merchant), and sequencing the entries.
2. **How they narrowed it.** In three visible steps:
   - **Economics first:** for each country, find the best project-and-contract combination by NPV per MW and total NPV, using the case's own cost and revenue data.
   - **Context second:** add four qualitative indices (negative-price frequency, regulatory support, competition, company capabilities). The deck does not disclose their weights.
   - **Fit third:** check against the client's stated corporate objectives.
   - The result is four markets, each with a different role.
3. **Evidence that mattered most.** The case's unit economics turned into NPV comparisons, plus **the client's own numbers used diagnostically**. The deck points out that Denmark and Lithuania make up a large share of the client's production but a much smaller share of its energy-sales revenue, and that revenue fell while volume rose. That diagnosis motivates storing energy where prices are low.
4. **Rejected alternatives.** Czechia, Romania and Greece were dropped explicitly as a trade-off, with a stated reason (weak demand and price volatility). Poland and the UK were demoted to "small wins" (no active pipeline, limited retrofit potential). Implicitly, the team rejected holding every asset: some markets are built to sell.
5. **Creative insight.** **Different business model per market**, not just a different market:
   - **Retrofit and hold** where the client's own solar assets suffer from low prices.
   - **Build and sell ("flip")** in Germany, where buyers pay premium valuations. Selling recycles equity after about 2 years instead of tying it up for the asset's life, and hedges the risk that newer battery technology makes the assets obsolete.
6. **What they quantified.** Portfolio NPV (~€400m), IRR (~15% at a 7% discount rate), capacity (1,705), allocation by year and market, payback timing, valuation premium of German assets over Western Europe, and NPV for all six project × contract combinations per country (appendix).
7. **How they established feasibility.** Through existing presence and capabilities (an index), grant availability, short build times in the chosen year-1 markets, debt assumptions by contract type, a cash buffer in the timeline, and a probability × impact risk matrix with six named risks.
8. **From evidence to recommendation.** Diagnose the client's problem (price erosion) → mechanism (storage captures price spreads) → compare options on economics → filter on context → assign each market a role → sequence by speed and cash needs → show portfolio returns.
9. **What was weak or questionable.**
   - The capacity figure is labelled both MW and MWh.
   - The NPV horizon is inconsistent (18 vs 20 years), and € and $ are mixed.
   - The weights of the qualitative indices are not shown.
   - A sentiment-analysis appendix contains a code error that makes its output constant.
   - The "optimisation" claim adds apparent rigour that the main argument doesn't need.
10. **Transferable to KPMG.**
    - **Investor economics as the first filter, context as the second.** This mirrors KPMG's "economics must work for the investor".
    - **The opportunity = place + business model.** The same niche can be attractive under one investor model (export platform, build and sell, joint venture) and not another.
    - **Explicit, reasoned rejections** shown on the main slides.
    - **Start from a diagnosed problem,** not a generic trend.
11. **Do not copy.** Analytics for show (optimisation, sentiment scoring) that a judge can't verify and that contain errors; undisclosed index weights; mixed units.

---

## Case B: Ørsted, offshore wind auction prioritisation to 2030

Case: https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/GLOBAL-case-2023.pdf
Winning deck: https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/3A-Kosciusko-Consulting.pdf

1. **Decision.** Which upcoming auctions (2023–26) to pursue to win about 8 GW within a DKK 200bn capital limit, how to differentiate against intensifying competition, and how to support industry health.
2. **How they narrowed it.**
   - **By volume:** they concentrated on the two countries holding the largest share of upcoming tender capacity (stated as 39% of the tenders considered).
   - **By what decides the auction:** they examined each country's auction criteria (price vs system integration vs ecology), concluded the client's edge lies in non-price criteria, and steered away from competing on price.
3. **Evidence that mattered most.** Tender capacity by country; **the scoring criteria that decide who wins**; price benchmarks (market average vs the client's past bids); competitors' differentiation moves; national hydrogen targets, budgets and network timelines in the chosen countries.
4. **Rejected alternatives.** A decision matrix compared four ways to differentiate: community microgrids, buying decommissioned oil platforms, hybrid wind-solar with pumped hydro, and hydrogen production. Each rejected option has a one-line disadvantage: not scalable; costs undercut the economics; only works with special geography and decades-long payback. Hydrogen was selected despite its stated weakness (a nascent market without distribution).
5. **Creative insight.** **Linking the differentiator to the mechanism that decides the win.** Pairing offshore wind with electrolysis (built with electrolyser partners) targets the system-integration score in the chosen countries. The deck then models the effect as a **higher assumed win rate** once hydrogen capability exists (30% → 45%).
6. **What they quantified.** Capacity reached (30.24 GW by 2030); CAPEX + DEVEX (DKK 166bn vs the 200bn limit); expected GW under base and worst-case win rates; a +20% CAPEX stress test; avoided CO2; electricity output.
7. **How they established feasibility.**
   - **Precedents:** the client's track record of 30 wind farms, existing hydrogen partnerships in the industry, and comparable projects.
   - **A partner screen:** electrolyser makers filtered on capacity and technology fit, with a stated reason for excluding one technology.
   - A phased plan (pilot → off-taker trials → scale) and a risk table with mitigations.
8. **From evidence to recommendation.** Where is the volume? → What decides who wins there? → What is our credible edge on that criterion? → Which differentiator delivers that edge (vs rejected alternatives)? → What does it do to the win rate and the budget?
9. **What was weak or questionable.**
   - **The win-rate uplift (the core of the case) is assumed, not evidenced.**
   - The hydrogen output figure (6 Mt from about 28,000 GWh of electricity) is implausibly high under standard electrolysis assumptions. The physical conversion was not sanity-checked.
   - The worst-case sensitivity doesn't clearly reconcile with the 30 GW target.
   - Currency labels are mixed, and the stated cost headroom doesn't match the budget arithmetic.
10. **Transferable to KPMG.**
    - **Find out what actually decides the buyer's or investor's choice,** then show Kazakhstan's advantage on *that* criterion, not on generic ones.
    - **A visible rejected-alternatives matrix** with one-line reasons (this is exactly the kill-log logic KPMG asked to see).
    - **Connect the creative idea to a quantified mechanism** (here, win rate) instead of leaving it as narrative.
11. **Do not copy.** Building the case on an assumed uplift without evidence; trend enthusiasm (hydrogen) without unit economics; unchecked physical conversions.

---

## Case C: Vestas, creating a Power-to-X (green hydrogen) business by 2030

Case: https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/CCC-2023-Final-Case.pdf (the case document restricts public quotation, so this file only paraphrases it)
Winning deck: https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/The-University-of-Hong-Kong-2.pdf

1. **Decision.** Which parts of an immature value chain the client should lead, how to use its capabilities and partners, and what 2030 targets to set, in a market with uncertain demand and limited regulation.
2. **How they narrowed it.** In three sequential screens:
   - **Value chain:** of six stages, lead the three where existing know-how transfers (development, design, service) and use partners for the rest (electrolyser supply, construction, operations).
   - **Region:** seven regions compared qualitatively on six criteria (resources, policy, partners, existing presence, demand, legacy) → **pilot in the EU, then expand to North America**.
   - **Business model:** joint venture vs consortium vs transactional sales, compared on risk sharing, know-how, capital, speed and flexibility → joint venture.
3. **Evidence that mattered most.** The client's market position and capabilities; policy support by geography; **competitors' entry structures** (several rivals' hydrogen joint ventures); the client's **own joint-venture history** as proof it can run one.
4. **Rejected alternatives.** Making electrolysers in-house (the capability doesn't transfer), operating plants (limited expertise), and China (foreign-ownership limits, in an appendix). Other regions were deprioritised for now.
5. **Creative insight.** **Pilot inside the existing customer base.** Identify customers' under-used wind plants, propose adding an electrolyser, prove the concept, then service it. This turns an uncertain new market into a sale to existing customers, and turns a capability gap into a partnership.
6. **What they quantified.** Market growth to 2030; 2030 targets (share of EU green hydrogen, EBIT margin, return on capital); JV size and ownership split; a company-level financial projection (revenue, EBIT, free cash flow) with segment margins; market-penetration scenarios.
7. **How they established feasibility.** Mostly through **precedent and structure**: the client's prior joint venture, competitors' comparable joint ventures, existing hydrogen investments and pilots, and partner-selection criteria. A risk table covers partner failure, partner opportunism and slower demand.
8. **From evidence to recommendation.** Where does our capability transfer? → Where is the first market most favourable? → Which structure closes the capability gap fastest with the least capital? → What pilot proves it? → What targets follow?
9. **What was weak or questionable.**
   - The financials model the whole company, not the hydrogen business, so the new venture's own economics (price vs cost, path to price parity) are never shown.
   - The headline market-share target is not built from the bottom up.
   - Internal inconsistencies: upfront R&D differs between the text and the model, the client's market share is stated two ways, and the margin target vs the model output don't match.
10. **Transferable to KPMG.**
    - For **non-obvious, thin-data niches**, define the opportunity by the **value-chain step where Kazakhstan's capability transfers**, and name what partners provide.
    - Use **precedents and comparable entries** (who has done a similar joint venture or plant elsewhere) as feasibility evidence when market data is scarce.
    - **Staged entry** (pilot → scale) as a way to cut risk for the investor.
11. **Do not copy.** Company-level financials in place of the unit economics of the opportunity itself; targets stated without derivation.

---

## Synthesis across the three cases

- **All three narrowed in visible sequential screens,** not one big scoring model. Each screen answered a different question: where is the volume or value, what decides success there, where is our edge.
- **All three named rejected options with a one-line reason** on the main slides. Rejection was part of the argument.
- **All three tied the recommendation to the client's own diagnosed situation** (falling revenue per unit, losing on price, capability gaps), not to a generic trend.
- **The creative leap was always a recombination with a mechanism:** storage plus resale, wind plus electrolysis linked to auction scoring, existing customers plus partner technology. None was "a new sector" on its own.
- **Feasibility was mostly argued through precedent and structure** (track record, comparable joint ventures, partners, phased pilots), not through deep engineering.
- **Even winners had visible errors** (unit labels, currency, inconsistent figures, an implausible conversion, a buggy appendix). Consistency and sanity checks are an inexpensive way to stand out, and KPMG explicitly scores quality and consistency.
- **The weakest point in each was the same type:** the decisive assumption (win-rate uplift, market-share target, index weights) was asserted rather than evidenced. That is where a sceptical judge would push.

---

## 10 behaviours of strong case teams

1. **They answer in the first slide.** Each winning deck opens with the recommendation and its headline numbers (capacity, NPV / IRR, budget used, 2030 targets) before any analysis.
2. **They don't research everything equally.** Each narrowed first on the dimension holding most of the value (largest tender volume, best NPV per MW, transferable capability) and analysed only the survivors in depth.
3. **They find out what actually decides the outcome.** Ørsted's winners analysed the auction scoring criteria per country; European Energy's started from the client's revenue-vs-volume problem. The analysis then focused on that deciding factor.
4. **They show what they rejected and why.** Markets, technologies, regions and business models were dropped with one-line reasons on the main slides, which makes the final choice look earned.
5. **They treat business model as part of the opportunity.** Hold vs sell, joint venture vs build in-house, retrofit vs standalone: the same market was attractive under one model and not another.
6. **Their creative leap is a recombination with a mechanism.** Each novel idea joined two existing elements and said *how* it creates value (price spreads captured, higher auction score, sales to existing customers).
7. **They establish feasibility through precedent.** Track record, competitors' comparable deals, existing partners and pilots carried most of the feasibility argument where hard data was thin.
8. **They give each choice a role in a sequenced plan.** Fast, grant-supported markets first; build-and-sell to recycle capital; pilot then scale. The order itself managed risk and cash.
9. **They stress-test the variable that matters most,** such as win rate, capital costs or a bear/base/bull case, rather than spreading sensitivity across everything.
10. **Their weakest point is an unproven decisive assumption, so the best place to add strength is there.** In every case the number the recommendation depended on most was asserted. A team that evidences its key assumption, or shows the answer survives a range, beats these benchmarks.
