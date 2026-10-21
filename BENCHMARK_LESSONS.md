# Benchmark Lessons: What Separates Winning Case Thinking from Finalist Work

**Purpose:** learn the *thinking behaviours* that make a winning case solution, so the team can apply them to the KPMG case. We copy no frameworks or recommendations, and this file contains no Kazakhstan opportunities.
**Compiled:** 20 Oct 2026. **Deepened:** 21 Oct 2026 (second pass: decision-trajectory reconstruction).
**Reading time:** about 15–20 minutes. Part 1 covers the cases; Part 2 is the synthesis to use during the competition.

**Method and limits**
- All three cases come from the official CBS Case Competition library (https://www.casecompetition.com/library/), which publishes each case brief **and** its winning deck.
- The decks were read through automated text extraction, so charts are under-represented. **Spot-check any number against the original PDF before quoting it.**
- We reconstruct only the **observable decision trajectory**: what the brief asked, what the deck chose, and what it shows. We cannot see the teams' private reasoning or the judges' scoring, so nothing here claims to know why they won.
- Labels: **(inference)** = our reading, not stated in the material. **[verify]** = needs checking against the PDF.

| # | Case | Brief | Winning deck |
|---|---|---|---|
| A | European Energy: battery storage (BESS) expansion, CBS GLOBAL 2025 (1st: TrueSouth Consulting) | [case](https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2025/11/European-Energy-BESS-Case-Final.pdf) | [deck](https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2025/11/CBS_2025_Final_Cleaned_Up.pdf) |
| B | Ørsted: offshore wind auction prioritisation, CBS GLOBAL 2023 (1st: Kosciuszko Consulting) | [case](https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/GLOBAL-case-2023.pdf) | [deck](https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/3A-Kosciusko-Consulting.pdf) |
| C | Vestas: entering Power-to-X (green hydrogen), CBS Invitational 2023 (1st: HKU, "Causeway Consulting") | [case](https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/CCC-2023-Final-Case.pdf) (public quotation restricted, so we paraphrase) | [deck](https://usercontent.one/wp/www.casecompetition.com/wp-content/uploads/2023/03/The-University-of-Hong-Kong-2.pdf) |

**Corrections to the 20 Oct version** (found by re-reading the briefs next to the decks)
1. **Ørsted:** the worst-case sensitivity (8.19 GW) *does* reconcile with the target. The case gives ~22 GW as already secured, so only 8 GW is missing. A different problem appears instead (see B-5).
2. **European Energy:** sales falling from €133.6m to €94.5m is a **−29%** drop, not the −17% the deck states.
3. **All three:** the "creative leap" was **partly seeded by the case brief itself**. European Energy's brief stresses asset rotation and that 73% of revenue comes from project sales. Ørsted's brief lists system integration and Power-to-X as differentiators. Vestas's brief describes JV models and a high-margin service business. What the winners added is described under "Creative leap" in each case.

---

# PART 1 — The three cases

## Case A — European Energy: €300m into battery storage, 2026–28

**1. Starting problem.** Allocate €300m of equity (max €100m/yr) across 10 pre-listed countries. Within each, choose retrofit (adding batteries to existing solar) vs standalone, and tolling vs floor vs merchant contracts. The case also asks for a go-to-market plan and for "business model innovation".
- The brief supplies per-country revenue, cost of capital (WACC), timelines, debt shares and the client's identified potential in MW.
- It also says the client earns 73% of revenue from **project sales** (50+ divestments in five years).
- Approximate weighting: Analysis 30% · Solution 30% · Creativity 15% · Feasibility 15% · Visuals 10%.

**2. Conventional approach (inference).** Compute NPV for 10 countries × 2 project types × 3 contract types. Rank by NPV and fill the budget top-down. Add a market-attractiveness scorecard. Propose one business model for every market, with a generic "innovation" idea (AI trading, virtual power plant) in the slot reserved for it.

**3. Decision tree (observable).**
1. **What is the client's real problem?** The deck answers: price erosion. Energy sales fell while production rose, and Denmark + Lithuania produce 41% of output but earn 16% of energy revenue. These client figures come from the company's annual report, **not the case**.
2. **Economic screen:** best project × contract per country by NPV per MW. Merchant retrofit ranks 1st and 3rd.
3. **Context screen:** four indices (negative prices, regulation, competition, the client's capabilities); weights not disclosed.
4. **Fit screen** against the client's strategy.
5. **One role per market** (the key move):
   - Denmark and Lithuania: retrofit and hold (fix the client's own price problem, fast, 30% grants).
   - Australia: co-develop with the client's active solar pipeline.
   - Germany: build standalone, sign tolling at 80% debt, **sell after ~2 years**.
6. **Sequencing:** fast, grant-backed retrofits in year 1; Germany and Australia in years 2–3.

**4. What they rejected.**
- *Explicit:* Czechia, Romania and Greece (low demand and volatility; also 7–9% cost of capital and no client potential for retrofits in the data). Poland and the UK demoted (no active pipeline, little retrofit potential).
- *Implicit:*
  - Holding everything (rejected through the flip model).
  - Floor contracts (dominated on NPV).
  - **Finland**, which has high revenue in the data, 5% cost of capital and all three contract options. Its exclusion is not explained on the main slides [verify].

**5. Decisive analysis.** Three things the recommendation actually depends on:
- **(a) The production-vs-revenue diagnosis.** It justifies starting with retrofits in the client's own markets. Without it, Denmark would not be first: its revenue per MW is mid-table in the case data.
- **(b) NPV per MW by project and contract.** It picks merchant retrofit and German standalone.
- **(c) The German valuation premium (~€46k vs €37k/MW) plus 80% debt on tolling deals.** This drives the flip: equity comes back after ~2 years instead of ~15.

Remove the sentiment-analysis appendix or the mixed-integer optimisation and the recommendation still stands. They were decoration.

**6. Creative leap.** Treat the **annual capital cap as a design variable, not just a limit**.
- *Connected facts:* (i) the €100m/yr cap, (ii) the 80% debt share on tolling, (iii) the client's habit of selling projects, (iv) premium buyer valuations in Germany.
- *Result:* a flipped German project recycles equity within the planning window, so the same €300m can do more than hold-only. It also hedges the risk that the batteries become technologically obsolete.
- *Why not obvious:* the case presents "hold vs sell" as a side note, and contract choice, debt share and buyer valuations sit in different sections of the brief.
- *Support:* economics (debt share and timeline from the case) plus a market valuation benchmark (external). The precedent is the client's own divestment record.
- *Measurable value:* claimed (equity release after 2 vs 15 years). The incremental NPV of flip vs hold is **not shown separately**.

**7. Human judgment visible.**
- Choosing "price erosion" as the framing problem.
- Assigning *different* business models to different markets.
- Accepting merchant price risk in retrofits (they rated it a high-probability risk yet still chose it).
- Choosing Australia (non-European, with a volatility concern) for its pipeline fit.
- Deciding the €100m/yr cap should be worked around, not merely respected.

**8. Analysis vs insight.**
- *A. Reproducible analysis:* the NPV grid, the index scoring, the timeline, the risk matrix.
- *B. Insight:* the diagnosis using outside client data; the flip-as-capital-recycling mechanism; one role per market.

**9. Why this could have stood out.** It likely differentiated the solution that the portfolio was argued as a *system*: each market had a role, and the roles hedged each other (long-term merchant holds vs short-term sales). A generic answer ranks markets. This one designed how capital moves between them.

**10. Weaknesses.**
- Revenue decline mis-stated (−17% vs −29%).
- MW vs MWh; € and $ mixed.
- NPV horizon of 18 years against the case's 15-year asset life. An NPV of €400m on €300m equity at 15% IRR / 7% WACC does not obviously reconcile [verify].
- Index weights hidden. Sentiment code bug (the output is always 5).
- "Optimised with MILP" claimed but not shown to change the allocation.
- **Flip-vs-hold value never isolated.** That is the number the creative idea rests on.

**11. What a generic AI answer would have done.**
- A PESTEL of European storage, then a 10-country table with NPV.
- Recommend the top NPV markets (Germany, Finland, Lithuania), all "hold", with a balanced mix of contract types.
- An "innovation" slide listing AI trading, virtual power plants and second-life batteries.
- A Gantt chart and a risk table.

*Where the winners departed:* they started from the **client's own P&L problem**, used outside company data, gave markets **different business models**, and turned a constraint into a lever.

**12. Lessons for us.**
1. **Diagnose before ranking:** find the investor's actual pain point or objective and let it decide what goes first.
2. **The same opportunity has different value under different ownership models** (hold, build-and-sell, joint venture). Decide the model as deliberately as the market.
3. **Read the brief's constraints as levers.** Ask what a rule (budget cap, debt share, timeline) makes possible, not only what it forbids.

---

## Case B — Ørsted: which auctions to chase for 8 GW by 2030

**1. Starting problem.** About 22 GW is secured; 8 GW more must be won in auctions held 2023–26, within DKK 200bn of development and construction spend (DEVEX + CAPEX). The case also asks (2) how to differentiate and (3) how to improve the industry's health.
- It explicitly requires stated assumptions and implied win rates.
- It provides a list of central vs lease auctions by year, cost add-ons for differentiation, Wood Mackenzie ratings of how much each criterion matters by region, and a lease rule (at most 20% won by one developer).

**2. Conventional approach (inference).** Bid on as many auctions as possible across core markets. Compete on price, given Ørsted's scale. List all differentiators (local content, biodiversity, recycling). Build a capacity × win-rate model to show 8 GW is reachable. Treat Q3 (industry health) with a supply-chain partnership slide.

**3. Decision tree (observable).**
1. **Where is the volume?** Germany + the Netherlands = 39% of the considered tender GW. Concentrate there.
2. **What decides the win there?** Non-price criteria (system integration, ecology, sustainability). Decision: **do not compete on price**.
3. **Which system-integration play?** A decision matrix of four options (microgrids, oil-platform reuse, wind + solar + pumped hydro, hydrogen) → hydrogen.
4. **Make or partner?** Partner with electrolyser makers. Screen 15–16 makers on capacity and technology, choose PEM over alkaline, shortlist three.
5. **Physical design:** clustered North Sea zones → a few central offshore electrolysers.
6. **Quantify:** win rate 30% → 45% once hydrogen capability exists; CAPEX vs budget; stress tests.

**4. What they rejected.**
- *Explicit:* microgrids (not scalable); platform reuse (permits and cabling); hybrid + pumped hydro (geography, payback); price competition; in-house electrolysers; alkaline technology.
- *Implicit:* lease auctions (Portugal 7 GW, US, Norway); Asian markets (Taiwan, Japan); floating; new markets. **None of these is given a reason on the main slides**, even though they account for most of the tendered volume.

**5. Decisive analysis.**
- **(a) Tender volume by country.** Picks the geography.
- **(b) Auction criteria by country.** Picks the basis for competing. This is the analysis that turns the recommendation from "bid cheaper" into "bid differently".
- **(c) The win-rate × capacity model.**

*Critical observation:* in the deck's own sensitivity table, even the worst case (20% before / 35% after hydrogen) yields 8.19 GW. That already covers the 8 GW gap. So **by the deck's own numbers the hydrogen uplift is not needed to hit the target**. Its real value would have to be economic: winning on non-price criteria lets Ørsted avoid bidding prices down. The deck notes the price gap (its past bid 506 vs market average 582 DKK/MWh) but **never quantifies the price benefit**. The sensitivity also assumes all 2025 tenders are contested, while the strategy focuses on two countries [verify].

**6. Creative leap.** Make the differentiator **mechanically tied to how the auction is scored**.
- *Connected facts:* (i) German and Dutch tenders reward system integration, (ii) both countries have national hydrogen targets and pipelines due ~2027, (iii) the North Sea zones are clustered, so one central electrolyser can serve several farms.
- *Why not obvious:* the brief lists Power-to-X as one differentiator among many. The winners linked it to *specific* scoring criteria in *specific* countries and to a *physical* geography that made it cheaper.
- *Support:* policy data and precedent (the existing Ørsted–Yara and RWE projects). The win-rate uplift itself is judgment only.
- *Measurable value:* asserted (+15 percentage points of win rate), not evidenced.

**7. Human judgment visible.**
- Deciding to avoid price competition despite being the scale leader.
- Concentrating on two countries.
- Choosing hydrogen despite its listed weaknesses (nascent market, no distribution).
- Choosing PEM over alkaline.
- Choosing *not* to analyse lease auctions or Asia.

**8. Analysis vs insight.**
- *A. Reproducible analysis:* tender volumes, CAPEX arithmetic, partner list, risk table.
- *B. Insight:* "find out what decides the win, then build the advantage on that criterion"; clustering zones to make central electrolysis economic.

**9. Why this could have stood out.** It likely differentiated the solution that the creative element was not decoration: it was attached to the deciding mechanism (scoring criteria → win rate), and the alternatives were visibly killed. Judges could follow *why* hydrogen, not just *that* hydrogen.

**10. Weaknesses.**
- The win-rate uplift (the core claim) is assumed.
- Hydrogen output is **~12× overstated**: 28,000 GWh at roughly 50–55 kWh per kg gives ~0.5 Mt, not 6 Mt.
- Electrolyser CAPEX (DKK 30m/MW) for 8 GW would be ~DKK 240bn, more than the stated total of 166bn, so the electrolyser size is undefined.
- Budget headroom written as 40 but is 34. "$" used for DKK.
- Q3 (industry health) is answered thinly (biodiversity and steel ideas, mostly in the appendix).
- The sensitivity analysis shows the creative idea is not needed for the target, but the deck doesn't notice this.

**11. What a generic AI answer would have done.**
- Market overview, then a Porter's Five Forces on competitors.
- "Prioritise core markets with high capacity" (UK, Germany, Netherlands, Taiwan).
- A long list of differentiators (local content, biodiversity, innovation, digital twins) with no selection.
- A win-rate table with arbitrary percentages, plus generic industry-health ideas.

*Where the winners departed:* they identified the **scoring mechanism** as the decisive variable, **chose one** differentiator with a visible kill matrix, and linked it to physical geography.

**12. Lessons for us.**
1. **Ask "what decides the choice?"**, meaning the investor's or buyer's actual selection criteria, before asking "what is attractive?".
2. **Run the "if this disappeared" test on our own creative idea.** If the recommendation survives without it, the idea is not yet doing work. Find the number it changes.
3. **Every implicit exclusion of a large option needs a one-line reason**, or a judge will ask.

---

## Case C — Vestas: building a Power-to-X business by 2030

**1. Starting problem.** Which parts of a six-stage value chain should Vestas lead, which 2030 goals should it set, and how should it use capabilities and partners? Constraints from the brief:
- No PtX operations before 2025.
- Vestas is loss-making in 2022 (EBIT ≈ −11%, free cash flow ≈ −€874m).
- Demand is uncertain, and lenders want 10–20-year offtake agreements.
- The brief describes four partnership models and lists Vestas's existing customers and its high-margin service business.

**2. Conventional approach (inference).**
- Recommend vertical integration ("own the full PtX solution"), possibly building electrolysers in-house as Siemens Gamesa is doing.
- Target the biggest hydrogen demand region.
- Set a large market-share target from top-down market sizing.
- Write a long roadmap.

**3. Decision tree (observable).**
1. **Value chain:** lead development, design and service (capabilities transfer); partner for supply, construction and operations.
2. **Region:** seven regions × six criteria → EU pilot (onshore Germany, offshore Denmark), then US/Canada.
3. **Structure:** JV vs consortium vs transactional → JV with an electrolyser maker; Vestas 51% for control; ~€800m.
4. **First customers:** existing Vestas customers with under-used wind plants.
5. **Targets:** 12% of EU green hydrogen production; 13% EBIT margin; 20% ROCE by 2030.

**4. What they rejected.**
- Electrolyser manufacturing in-house (the Siemens Gamesa route), plant operations, construction.
- China (ownership limits; appendix).
- Other regions deprioritised: Middle East, Australia and Latin America despite strong resources.
- Consortium and transactional models (a criteria table sourced to Deloitte).

**5. Decisive analysis.**
- **(a) Capability-transfer mapping** across value-chain stages. Picks the role.
- **(b) JV precedents:** Vestas's own MHI JV history plus competitors' JVs (Siemens Energy–Air Liquide, Acciona–Plug). These prove the structure is executable.

The 7-region comparison is largely qualitative and **the company-wide financial model does not change any choice**. The PtX venture's own economics (cost per kg vs the grey hydrogen price) are never modelled.

**6. Creative leap.** **Enter a new market by selling into the existing installed base.**
- *Connected facts:* (i) Vestas services >140 GW under long contracts, (ii) some customer plants are under-used (curtailment or low prices), (iii) an electrolyser added to such a plant turns stranded electricity into a product, (iv) Vestas's highest margins are in service.
- *Result:* pilot with existing customers, then service the electrolyser.
- *Why not obvious:* the brief frames PtX as a new market needing new customers. The winners reframed it as an **extension of the service relationship**, which reduces demand risk and plays to the highest-margin capability.
- *Support:* precedent and judgment. The size of curtailment at existing customers is not quantified.
- *Measurable value:* implied through the margin ordering (Power Solutions < PtX < Service) but not built bottom-up.

**7. Human judgment visible.**
- Choosing to **not** build electrolysers despite a competitor doing so.
- Taking 51% control in a JV for a loss-making company.
- Piloting with the installed base.
- Choosing the EU over cheaper-hydrogen regions because of demand and policy certainty.

**8. Analysis vs insight.**
- *A. Reproducible analysis:* market sizing, the region scorecard, the JV comparison table, the company forecast.
- *B. Insight:* "lead where know-how transfers, partner where it doesn't"; the installed base as a beachhead; service margin as the profit engine.

**9. Why this could have stood out.** It likely differentiated the solution that it **reduced the client's riskiest uncertainty (demand) using an asset the client already owned** (its customers), and backed executability with named precedents instead of optimism.

**10. Weaknesses.**
- The financials model the whole company; the PtX venture's own economics are absent.
- The market-share target is not derived.
- Upfront investment stated as €800m vs ~€1bn in the model; 14.4× written as 13.4×.
- Claims "no external financing needed" while listing financing as a key challenge.
- Market share stated three ways. The timeline starts the JV in 2023, before the 2025 operations limit (probably fine, but unflagged).

**11. What a generic AI answer would have done.**
- Hydrogen market overview, then "Vestas should become an integrated PtX solutions provider".
- Enter the regions with the cheapest renewables.
- Mention partnerships generically.
- Set "10% market share by 2030" and list risks.

*Where the winners departed:* a **make-vs-partner decision tied to capability transfer**, an **installed-base entry route**, and **precedent-based feasibility**.

**12. Lessons for us.**
1. For thin-data opportunities, **define the opportunity as the step where an existing capability transfers**, and name exactly what a partner must supply.
2. **Feasibility evidence = precedent:** who has already done this structure or plant somewhere comparable.
3. **Show the opportunity's own unit economics**, not a company-level forecast. This was the gap in an otherwise winning deck.

---

# PART 2 — Cross-case synthesis

## A. Finalist-level work (what strong, competent teams do)
- Answer up front, with headline numbers.
- Narrow in visible stages: volume or value → context → fit.
- Quantify returns against the budget; run a sensitivity analysis and a risk matrix.
- Use a clean scorecard or decision matrix; build a phased timeline.
- Cover every sub-question of the brief.

All of this is necessary and reproducible by any well-resourced team or an AI system. **It is the entry ticket, not the differentiator.**

## B. Winner-level differentiation (what goes beyond competent execution)
1. **They find the deciding mechanism:**
   - the client's revenue-per-MWh erosion (Case A);
   - the auction scoring criteria (Case B);
   - where a capability transfers (Case C).

   The recommendation is built on that mechanism, not on general attractiveness.
2. **Business model and structure are part of the answer:** hold vs flip, partner vs make, JV with 51% control. The same market becomes attractive only under a specific model.
3. **The creative leap connects 2–4 facts from *different* parts of the brief and outside data,** usually with one seeded by the brief itself. Winners noticed which hint was a *lever* and attached it to a mechanism that moves a number (equity recycling, win rate, demand risk).
4. **Rejections are argued, not just listed.** Killing plausible alternatives in a visible matrix makes the final choice look earned.
5. **They use an asset the client already has** (its own sales record, track record, installed base) as both the advantage and the feasibility proof.

**The shared weakness is also the shared opportunity:** in all three decks the number the recommendation depends on most (flip value, win-rate uplift, PtX economics) is asserted, not evidenced. Each deck also contains arithmetic errors a judge could find in minutes. **A team that evidences its decisive assumption and is arithmetically clean beats these benchmarks on the dimensions they were weakest.**

## C. The human edge (do not delegate entirely to AI)
- **Choosing the framing problem:** what the investor's real decision or pain is.
- **Deciding which mechanism decides the outcome,** and therefore what to analyse deeply and what to skip.
- **Connecting facts across sources into a new thesis.** AI can list facts; noticing that two of them together create value is judgment.
- **Choosing the business model or structure** under which an opportunity becomes attractive.
- **Prioritising despite imperfect data:** committing to one idea and killing appealing ones.
- **Deciding which assumption is decisive,** and what level of evidence is enough.
- **Narrative:** what the judge must believe after slide 1.

## D. How we should use AI
**AI should do aggressively:**
- **Research and extraction:** sources, datasets, filings, trade data, precedent deals.
- **Calculations:** NPVs, unit economics, physical conversions, cross-checks.
- **Precedent search:** "who built this plant or JV elsewhere, at what cost and scale?"
- **Alternative generation:** at least 3 competing models or framings for each idea.
- **Falsification:** argue the strongest case against our thesis; find the competitor location that beats us.
- **Sensitivity checks:** at what value of the key assumption does the recommendation flip?
- **QA:** units, currencies, totals, internal consistency between slides, and "does the worst case still meet the claim?" (all three winners failed here).

**Humans must retain:** framing · interpretation of what evidence means · creative synthesis · trade-offs · final selection (Top 5, teaser) · the narrative · the decision of which questions are worth answering.

## E. Warning signs: our answer is turning into polished but generic AI work
1. Our five niches look like the five largest export sectors.
2. Each niche's "why Kazakhstan" could be pasted into another niche unchanged ("resources, location, government support").
3. We can't state, in one sentence, the mechanism that makes the investor money in Kazakhstan *rather than* in the best rival location.
4. All niches share the same business model (build a plant, sell output) with no ownership or structure choice.
5. Rejected options appear only in an appendix, or have no reason attached.
6. Slides are full of market-size charts but none shows the decisive assumption with a range.
7. The creative idea survives the "if this disappeared, would the recommendation change?" test only as decoration.
8. Numbers are precise (e.g., "USD 1.284bn") but untriangulated, or units and currencies are mixed.
9. Sources are mostly AI-summarised press, and nobody on the team has opened the primary source for headline numbers.
10. No team member can explain a slide's logic without reading it.

## F. Questions to ask ourselves during the competition
1. What are we seeing that another competent team using the same public data would probably miss?
2. Which two or three facts become valuable only when connected, and are they from different sources?
3. What actually decides the investor's location choice for this activity? Have we shown Kazakhstan's position on *that* criterion?
4. Which single assumption determines this recommendation, and at what value does it flip?
5. Under which ownership model (JV, offtake-equity, build-and-sell, export platform) does this become attractive, and under which does it fail?
6. What asset already exists (a plant, operator, flow, contract or customer base) that makes this cheaper or less risky to execute here than elsewhere?
7. What would we recommend if we were forbidden from choosing the three most obvious sectors?
8. Which large option did we drop without writing down why?
9. What hint in the KPMG brief or briefing are we treating as background that might be a lever?
10. If a sceptical judge had five minutes, which number on our slide would they recompute, and does it survive?

---

## Where this file fits
Benchmark only. It does not change `opportunities/SCREENING_APPROACH.md`, `RESEARCH_PROTOCOL.md` or `ANALYSIS_PLAYBOOK.md`, and records no team decision.
