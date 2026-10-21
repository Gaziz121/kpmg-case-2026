# Data Sources: Kazakhstan Investment Research Arsenal

**Purpose:** where to find credible evidence, fast. This is not a list of opportunities.
**Compiled:** 20 Oct 2026.
**URL status:** ✓ = the address was opened or returned by search while compiling this list. Unmarked = a long-standing official address that wasn't re-checked. **Open every link before citing it.**
**P / S:** P = primary (the original producer of the data); S = secondary (compiles or interprets others' data).

---

## Quick map: which sources support which analysis

| Need | Best sources |
|---|---|
| **Product-level screening (HS6 and finer)** | ITC Trade Map · UN Comtrade · CEPII BACI · ITC Export Potential Map · Atlas of Economic Complexity · BNS foreign trade · WITS |
| **Country comparison** (Kazakhstan vs alternative locations) | Atlas of Economic Complexity · World Bank WDI · ILOSTAT · Ember / IEA · World Bank LPI · Enterprise Surveys · US State Dept Investment Climate Statements · OECD FDI restrictiveness |
| **Export-market analysis** (who imports, tariffs, access) | ITC Trade Map (importer side) · ITC Market Access Map · ITC Export Potential Map · Comtrade / BACI · neighbour statistics offices · WTO tariff data |
| **Rough project economics** (capex, costs, prices) | EBRD / IFC / ADB / AIIB project disclosures · World Bank PPI · company investor presentations · IRENA / NREL ATB · KOREM + marginal tariffs · BNS wages · World Bank commodity prices · Global Energy Monitor |

---

## 1. Kazakhstan production and industrial statistics

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| Bureau of National Statistics (BNS): industry, industrial production, construction, investment sections | https://stat.gov.kz/en/industries/business-statistics/ ✓ | Industrial output by activity code; physical output of key products; investment in fixed assets by sector | National + regions; activity codes, some product lines | P | English pages are thinner than Russian/Kazakh; national product codes don't map 1:1 to HS; some cells suppressed for confidentiality |
| BNS Taldau (indicator database) | https://taldau.stat.gov.kz | Time series for most BNS indicators, with downloads | National / regional; annual / monthly | P | Interface is mostly in Russian; indicator names are inconsistent |
| Kazakhstan open data portal | https://data.egov.kz | Government datasets (registries, regional data) | Varies | P | Patchy coverage and updates; mostly Russian |
| UNIDO INDSTAT | https://stat.unido.org | Manufacturing value added and output by ISIC, comparable across countries | Country × ISIC 2–4 digit | S | 1–3 year lag; Kazakhstan coverage may be incomplete |

## 2. Kazakhstan imports and exports (HS level)

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| BNS foreign and mutual trade | https://stat.gov.kz/en/industries/economy/foreign-market/ (section inferred from ✓ publication pages) | Official Kazakhstan exports and imports by commodity and partner, including trade with EAEU partners | National; commodity (national 10-digit classification) × partner | P | Deep tables are mostly in Russian; EAEU trade is based on statistical surveys, not customs declarations |
| ITC Trade Map | https://www.trademap.org | Kazakhstan exports and imports by HS2–HS6 (some national tariff lines), partners, unit values, growth, mirror data | Country × HS6 (some HS8/10) × partner; annual, some monthly | S (from national data / Comtrade) | Free registration needed; latest year sometimes estimated from mirror data |
| UN Comtrade | https://comtradeplus.un.org | Bilateral trade by HS6, quantities, unit values, API | Reporter × partner × HS6; annual / monthly | P (as reported by countries) | Exports and imports reported by the two sides often differ; quantities often missing |
| World Bank WITS (Kazakhstan profile) | https://wits.worldbank.org/CountryProfile/en/Country/KAZ/Year/LTST/Summarytext ✓ | Trade summaries, tariffs applied and faced, partner shares, product groups | Country × HS6 / product groups | S | Profiles are summaries; detailed queries need registration |

## 3. Trade demand in neighbouring countries

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| ITC Trade Map (importer view) | https://www.trademap.org | What Uzbekistan, Kyrgyzstan, Tajikistan, Turkmenistan, Afghanistan, China, Russia, Azerbaijan, Georgia and Iran import, from whom, at what unit value | Country × HS6 × partner | S | Several neighbours report late or not at all; mirror data needed (exports to them as reported by partners) |
| ITC Export Potential Map | https://exportpotential.intracen.org | Model estimate of Kazakhstan's unrealised export potential by product × target market; diversification candidates | Kazakhstan × HS6 × market | S (model) | A model output (supply, demand and market access) — useful for discovery, not as proof of competitiveness |
| ITC Market Access Map | https://www.macmap.org | Tariffs, preferences and non-tariff measures Kazakhstan's exports face in each market | Market × HS6 (tariff lines) | S | Registration; non-tariff measures are listed but their real effect needs judgement |
| Eurasian Economic Commission (EAEU statistics) | https://eec.eaeunion.org/en/news/statistics/ ✓ | EAEU external and mutual trade, macro indicators of member states | EAEU members; aggregates and commodity groups | P | Aggregated; navigation is mostly Russian; Russia's detailed data restricted since 2022 |
| Uzbekistan statistics agency | https://stat.uz/en | Uzbek production, trade, prices, regional data | Uzbekistan; national / regional | P | English coverage partial |
| Kyrgyzstan statistics committee | https://www.stat.gov.kg/en | Kyrgyz trade, production | Kyrgyzstan | P | Small market; limited detail |
| China customs statistics | http://stats.customs.gov.cn | China's imports by HS and origin, including by province (relevant for western China) | China; HS8 × partner × province | P | Interface hard to use (Chinese); access can be unreliable; use Trade Map for HS6 |

## 4. Global trade flows

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| CEPII BACI | https://www.cepii.fr/CEPII/en/bdd_modele/bdd_modele_item.asp?id=37 | Reconciled bilateral trade (one consistent value per flow) — best for world market sizing and supplier shares | ~200 countries × HS6; annual | S (cleaned Comtrade) | ~1–2 year lag; large files (needs scripts) |
| Atlas of Economic Complexity (Harvard Growth Lab) | https://atlas.hks.harvard.edu | Export composition, market share growth, product space, "growth opportunities" (products close to existing capabilities), cross-country comparison | Country × HS4/HS6 + services | S | Feasibility scores are model-based; HS4 is coarse for niches |
| Harvard Growth Lab: Kazakhstan research project | https://growthlab.hks.harvard.edu/project/kazakhstan ✓ | Growth diagnostic and diversification research specific to Kazakhstan | Kazakhstan | S | Research views, not data; check publication dates |
| WTO Stats + Tariff & Trade Data | https://stats.wto.org · https://ttd.wto.org | Merchandise and services trade aggregates; applied and bound tariffs | Country; HS6 for tariffs | P | Services trade data coarse |
| UNCTADstat | https://unctadstat.unctad.org | Trade, services trade, maritime and FDI series | Country | S/P | Aggregated |

## 5. FDI flows and investment trends

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| National Bank of Kazakhstan: external sector / direct investment statistics | https://nationalbank.kz/en (Statistics → external sector; a ✓ file download exists) | FDI inflows / stock into Kazakhstan by source country and activity | Kazakhstan × country × activity; quarterly | P | Flows routed via the Netherlands, Switzerland, etc. hide the real investor country; dominated by extractive sectors |
| UNCTAD World Investment Report (+ annex tables) | https://unctad.org/topic/investment/world-investment-report | FDI flows, announced greenfield projects by destination and sector, international project finance deals, top MNEs | Global / regional / country × sector | S | Annual; announced ≠ realised |
| IMF Coordinated Direct Investment Survey | https://data.imf.org | Bilateral FDI positions (who invests in Kazakhstan and in its competitors) | Country × counterpart country | P (as reported) | Positions, not projects; same conduit-country problem |
| fDi Markets (Financial Times) | https://www.fdimarkets.com | Project-level greenfield FDI: investor, sector, capex, jobs — for comparable countries too | Project-level, global | S | **Paid**; check NU library access; capex often estimated |
| Kazakh Invest | https://invest.gov.kz ✓ | Investment-project pool, regional guides, signed agreements, incentives | Kazakhstan; project / regional | S (promotional) | Promotional framing; announced values not verified |
| Prime Minister of Kazakhstan: press service | https://primeminister.kz/en ✓ | Announced projects, the import-substitution project pool, SEZ results, government priorities | Kazakhstan | P (official statements) | Announcements, not audited outcomes |
| OECD Data Explorer (FDI statistics, FDI Regulatory Restrictiveness Index) | https://data-explorer.oecd.org | FDI by partner / industry; how restrictive regulation is by sector, Kazakhstan vs others | OECD + selected economies, including Kazakhstan | S | Kazakhstan is covered for some series only |

## 6. Mining, minerals and reserves

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| USGS Mineral Commodity Summaries | https://www.usgs.gov/centers/national-minerals-information-center/mineral-commodity-summaries | World production and reserves by commodity and country; prices; uses | Country × commodity; annual | S (authoritative) | Kazakhstan reserves often missing or estimated; country-level only |
| USGS Minerals Yearbook: Kazakhstan chapter | https://www.usgs.gov/centers/national-minerals-information-center/europe-and-central-eurasia | Kazakhstan mineral industry: producers, plants, capacities, projects | Kazakhstan; company / facility | S | Published with a 2–4 year lag |
| BGS World Mineral Statistics | https://www.bgs.ac.uk/mineralsuk/statistics/world-mineral-statistics/ | Production and trade by mineral and country, long series | Country × commodity | S | Lag; production, not reserves |
| Unified Subsoil Use Platform (minerals.gov.kz) | https://minerals.gov.kz (described in ✓ official / industry articles) | Licence areas, auctions, geological information for investors | Kazakhstan; licence / block | P | Access and English coverage uncertain; detailed geology may need registration |
| EITI Kazakhstan | https://eiti.org/countries/kazakhstan (✓ eiti.org Kazakhstan page) | Extractive companies, production, payments to government, licence data | Kazakhstan; company / project | P (reconciled reports) | Lags 1–2 years; finances rather than geology |
| IEA Critical Minerals Data Explorer / Outlook | https://www.iea.org/data-and-statistics/data-tools/critical-minerals-data-explorer | Demand scenarios and supply concentration for critical minerals | Global × mineral | S | Scenarios; little country-level supply detail for Kazakhstan |
| Global Energy Monitor (GEM wiki and trackers) | https://gem.wiki ✓ · https://globalenergymonitor.org | Facility-level data for steel plants, iron-ore and coal mines, power plants in Kazakhstan and competitors: owners, capacities, status | Facility-level, global | S | Crowd-compiled from public sources; capex rarely included |

## 7. Agriculture and agri-food

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| FAOSTAT | https://www.fao.org/faostat/en/ | Production, yields, area, food balances, producer prices, agri trade | Country × crop / product; annual | S (from national data) | Lag; Kazakhstan producer prices patchy |
| FAO AQUASTAT | https://www.fao.org/aquastat/en/ | Water resources and withdrawal by country — key for water-intensive ideas | Country | S | Coarse; old reference years |
| BNS agriculture statistics | https://stat.gov.kz/en/industries/business-statistics/ ✓ (agriculture, forestry, fisheries section) | Kazakhstan crop and livestock output by region, processing | Kazakhstan × region | P | Russian-heavy detail |
| USDA FAS: GAIN reports + PSD Online | https://gain.fas.usda.gov · https://apps.fas.usda.gov/psdonline | Attaché reports on Kazakhstan and neighbours (grain, oilseeds, meat, policy); supply-demand balances | Country × commodity | S (expert) | US-perspective; only selected commodities |
| OECD-FAO Agricultural Outlook | https://www.agri-outlook.org | 10-year projections of global agri demand, prices, trade | Global / regional × commodity | S | Kazakhstan often in aggregates |

## 8. Energy, electricity, power costs and capacity

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| IEA: Kazakhstan country page | https://www.iea.org/countries/kazakhstan | Energy balance, power mix, policy overview | Kazakhstan | S | Detailed data behind a paywall |
| Ember electricity data | https://ember-energy.org/data/ | Generation mix, demand, emissions intensity; cross-country comparison | Country; monthly / annual | S | Kazakhstan series may be partly modelled |
| KOREM (electricity and capacity market operator) | https://korem.kz/en ✓ | Centralised trading and auction results, price signals, special trading for data-centre / crypto loads | Kazakhstan wholesale market | P | Wholesale only; navigation and archive in Russian; end-user prices differ |
| Marginal (cap) tariffs for electricity generation, official order | https://adilet.zan.kz/eng/docs/V1800017956 ✓ | Regulated price caps for generators by group | Kazakhstan; generator groups | P | Frequently amended; check the current version and end-user tariffs separately |
| Ministry of Energy | https://www.gov.kz/memleket/entities/energo ✓ | Policy, tariff policy, renewable auctions, energy balance plans | Kazakhstan | P | Scattered across press items |
| KEGOC (grid operator): annual reports, tariffs | https://www.kegoc.kz/en | Transmission network, interconnections, grid tariffs, capacity balance | Kazakhstan; grid zones | P | Industrial end-user price requires adding distribution and supply margins |
| Samruk-Energy reports | https://www.samruk-energy.kz ✓ | Generation assets, tariffs and results of the largest state power group | Company | P | One group's view |
| GlobalPetrolPrices: electricity prices | https://www.globalpetrolprices.com/electricity_prices/ | Quick cross-country household / business electricity price comparison | Country; quarterly | S | Method opaque; use for orientation only, not as a cited number |
| IRENA Renewable Power Generation Costs | https://www.irena.org/Publications | Cost and LCOE benchmarks by technology and region | Global / regional | S | Not Kazakhstan-specific |

## 9. Logistics and transport

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| World Bank Logistics Performance Index | https://lpi.worldbank.org | Logistics quality, Kazakhstan vs competitors; dwell / clearance times | Country | S (survey + big data) | Index, not route costs |
| CAREC Corridor Performance Measurement & Monitoring | https://www.carecprogram.org | Time and cost to cross borders and travel along Central Asian corridors | Corridor / border crossing | S | Report-based; sample of shipments |
| Middle Corridor / TITR association | https://middlecorridor.com/en/route ✓ | Route, members, volumes, tariff announcements on the Trans-Caspian route | Corridor | P (association) | Promotional; volumes and tariffs not systematic |
| BNS transport statistics | https://stat.gov.kz/en/industries/business-statistics/ ✓ (transport section) | Freight volumes and turnover by mode | Kazakhstan × mode / region | P | No route-level prices |
| Kazakhstan Temir Zholy (national railway) | https://www.railways.kz | Rail network, transit volumes, terminals, annual reports | Kazakhstan | P | Tariff detail limited in English |
| Freightos Baltic Index (container rates) | https://fbx.freightos.com | Global container freight rates by lane | Global lanes | S | Doesn't cover overland Central Asia routes directly |

## 10. Labour, wages and skills

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| BNS wages (dynamic tables) | https://stat.gov.kz/en/industries/labor-and-income/stat-wags/dynamic-tables/ ✓ (path varies; several ✓ variants) | Average wages by activity, region, occupation | Kazakhstan × activity × region | P | Average wages, not total employer cost; URL paths change |
| ILOSTAT | https://ilostat.ilo.org | Employment, wages, productivity; cross-country comparison | Country × sector | S | Gaps and lags for Central Asia |
| World Bank Enterprise Surveys | https://www.enterprisesurveys.org | Firm-reported constraints (skills, power outages, customs, corruption), Kazakhstan vs peers | Country; firm survey | P (survey) | Survey years are sporadic |
| UNESCO UIS | https://uis.unesco.org | Tertiary graduates by field (STEM pipeline) | Country | S | Lag; fields are broad |
| World Bank WDI | https://data.worldbank.org | Macro, labour, education, infrastructure indicators for any comparison | Country | S | Broad indicators only |

## 11. Special economic zones, incentives and investment policy

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| Adilet (official legal database) | https://adilet.zan.kz/eng | Tax Code, Entrepreneurial Code (investment preferences), SEZ law and decrees, subsoil code, tariff orders | Kazakhstan; legal text | P | English versions can lag amendments; check the Russian text for the current version |
| Prime Minister: SEZ roadmap and results | https://primeminister.kz/en/news/reviews/arnayy-ekonomikalyk-aymaktarda-12-trln-tengege-315-ke-zhuyk-zhoba-iske-asyryldy-256343 ✓ | SEZ projects, investment volumes, development plans | Kazakhstan; by SEZ | P (official statement) | Headline figures; no project economics |
| Kazakh Invest: investor guide / regional offices | https://invest.gov.kz ✓ | Incentives, SEZ and industrial-zone overviews, PPP support, regional contacts | Kazakhstan × region | S | Promotional; check the legal basis in Adilet |
| PwC Kazakhstan: investment preferences leaflet | https://www.pwc.com/kz/en/assets/tax-advisory-services-on-investment-preferences/leaflet-eng.pdf ✓ | Plain-English summary of preferences (tax exemptions, in-kind grants, investment contracts) | Kazakhstan | S | Date-dependent; verify against current law |
| Morgan Lewis: Investment Policy Concept to 2029 | https://www.morganlewis.com/pubs/2024/12/concept-of-investment-policy-of-the-republic-of-kazakhstan-approved-until-2029 ✓ | Summary of the government's 2029 investment policy priorities | Kazakhstan | S | Law-firm summary; cite the official concept where possible |
| US State Dept: Investment Climate Statement, Kazakhstan | https://www.state.gov/reports/2024-investment-climate-statements/kazakhstan | Independent view of the investment regime, SEZs, disputes, practical barriers | Kazakhstan | S | US perspective; check for a newer edition |
| Astana International Financial Centre (AIFC) | https://aifc.kz | English-law court, arbitration, financial-centre regime (relevant to investor protection) | Kazakhstan | P | Mainly financial-sector focus |

**Existing country diagnostics** (useful for hypotheses and evidence; not niche selection):
- OECD, *Diversifying Kazakhstan's Exports* (c. 2024): https://www.oecd.org/en/publications/diversifying-kazakhstan-s-exports_7f9cd8aa-en/full-report/component-2.html ✓
- IFC / World Bank, *Kazakhstan Country Private Sector Diagnostic* (2017): https://www.ifc.org/content/dam/ifc/doc/mgrt/kazakhstan-cpsd-2017.pdf ✓

## 12. Global industry and market data

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| World Bank Commodity Price Data (Pink Sheet) | https://www.worldbank.org/en/research/commodity-markets | Monthly prices and forecasts for metals, energy, agri | Global × commodity | S | Benchmark prices; not regional delivered prices |
| IEA reports and data | https://www.iea.org/data-and-statistics | Energy, minerals, electricity and data-centre demand outlooks | Global / regional | S | Many datasets paid |
| worldsteel data | https://worldsteel.org/data/ | Steel production, consumption, trade by country | Country | S (industry body) | Some detail for members only |
| International Aluminium Institute statistics | https://international-aluminium.org/statistics/ | Primary aluminium production, energy use by region | Regional | S (industry body) | Regional aggregates |
| OECD-FAO / IEA / IRENA outlooks | see above | Long-run demand for agri, energy, technology | Global | S | Scenario-based |
| Company and industry-body reports | company IR pages | Market sizes and segment growth | Varies | S | Check methodology; avoid uncited market-research teaser figures |

## 13. Comparable projects and project economics

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| EBRD Project Summary Documents | https://www.ebrd.com/work-with-us/project-finance/project-summary-documents.html | Real projects in Kazakhstan and comparable countries: sponsor, total project cost, financing, rationale | Project-level | P | Not every project discloses total cost; mainly projects EBRD finances |
| IFC Project Information & Data Portal | https://disclosures.ifc.org | Project cost, sponsor, environmental documents | Project-level | P | Same selection bias |
| ADB projects: Kazakhstan | https://www.adb.org/projects/country/kaz | Infrastructure / public-sector projects, costs, appraisal documents | Project-level | P | Mostly public-sector projects |
| AIIB project list | https://www.aiib.org/en/projects/list/index.html | Infrastructure projects in the region | Project-level | P | Few Kazakhstan projects |
| World Bank PPI Database | https://ppi.worldbank.org | Private participation in infrastructure: investment size, sponsors, contract type, by country and sector | Project-level, developing countries | P (compiled) | Infrastructure only; amounts at financial close |
| NREL Annual Technology Baseline | https://atb.nrel.gov | Capex, opex and capacity-factor benchmarks for energy technologies | Technology (US-based) | S | US costs; adjust for location |
| Company investor presentations and capital-markets days | company IR pages | Capex per unit of capacity, margins and costs for comparable plants | Company / project | P | Selective disclosure; check the date |

## 14. Public company filings and investor presentations

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| Kazakhstan Stock Exchange (KASE): issuer disclosures | https://kase.kz/en | Financial statements and reports of Kazakhstan-listed companies | Company | P | Smaller issuers report in Russian / Kazakh only |
| Astana International Exchange (AIX) | https://www.aix.kz | Listings and disclosures (incl. national companies' IPOs) | Company | P | Few issuers |
| Financial Statements Depository | https://www.dfo.kz | Financial statements of public-interest entities in Kazakhstan | Company | P | Russian interface; search by company ID |
| Samruk-Kazyna (sovereign wealth fund) | https://sk.kz | Annual reports of national companies (energy, rail, mining, etc.) | Group / company | P | State-company perspective |
| SEC EDGAR · LSE RNS · HKEX News | https://www.sec.gov/edgar/search/ · https://www.londonstockexchange.com/news · https://www.hkexnews.hk | Filings of multinationals active in or considering Central Asia: capex plans, segment margins, country risks | Company | P | Kazakhstan often isn't reported separately |

## 15. Potential strategic investors

| Source | URL | What it answers | Geography / granularity | P/S | Main limitation |
|---|---|---|---|---|---|
| fDi Markets | https://www.fdimarkets.com | Which companies made greenfield investments in comparable countries and sectors | Project / company | S | Paid |
| UNCTAD WIR annex: largest multinationals | https://unctad.org/topic/investment/world-investment-report | Largest multinationals by foreign assets and sector | Company | S | Very large firms only |
| Kazakh Invest + Prime Minister press releases | https://invest.gov.kz ✓ · https://primeminister.kz/en ✓ | Investors already in Kazakhstan; signed agreements; investors in talks | Company / project | P/S | Announcements, often non-binding |
| Foreign Investors' Council (decree on its establishment) | https://adilet.zan.kz/eng/docs/U980003985_ ✓ | The council exists; its member list identifies large foreign investors already present | Company | P | The member list itself must be found separately |
| EBRD / IFC / ADB project sponsors | see §13 | Sponsors that have actually invested in the region | Company | P | Biased toward projects these banks finance |
| Global Energy Monitor facility owners | https://gem.wiki ✓ | Owners and operators of comparable plants in competitor countries | Company / facility | S | Industrial and energy sectors only |
| Business associations (AmCham Kazakhstan, EU business association) | https://www.amcham.kz | Member companies present in Kazakhstan; members' concerns | Company | S | Membership lists may be partial |

---

## The 10 highest-value sources for this case

1. **ITC Trade Map:** HS6 imports and exports for Kazakhstan *and* each neighbour; the core of product screening and export-market sizing.
2. **ITC Export Potential Map:** a ready-made, model-based list of unrealised export potential for Kazakhstan by product and market; fast discovery input (treat as a hypothesis, not proof).
3. **Atlas of Economic Complexity:** products close to Kazakhstan's existing capabilities, plus comparison with alternative locations.
4. **CEPII BACI / UN Comtrade:** clean world market sizes and supplier shares (who is the best alternative location).
5. **BNS:** official Kazakhstan production, trade, wages, investment and regional data.
6. **National Bank of Kazakhstan + UNCTAD WIR:** where FDI comes from and which sectors attract greenfield projects.
7. **EBRD / IFC project disclosures + World Bank PPI:** real project costs and sponsors for comparable economics.
8. **KOREM + marginal tariffs + Ember / IEA:** electricity price and power mix, often the decisive cost driver.
9. **USGS / BGS + GEM:** resource and facility-level evidence for anything involving minerals or metals.
10. **Adilet + Kazakh Invest + PwC preferences leaflet:** the incentives and SEZ regime that change investor returns.

## Gaps we still have

- **Delivered-cost data.** There is no free source for factory-gate costs or rail / road freight rates on specific Kazakhstan routes. This needs company presentations, carriers' tariff announcements, or labelled assumptions.
- **Project-level greenfield FDI** (fDi Markets) is paid. Check NU library access; otherwise rebuild from UNCTAD annexes and press.
- **Russia's detailed trade data** has been restricted since 2022, so we rely on mirror data.
- **Kazakhstan reserve and geology data** is limited in English and may require access to the subsoil platform.
- **Paid market research** (BloombergNEF, Wood Mackenzie, CRU, Fastmarkets) is unavailable, so global segment sizes must come from industry bodies, IEA / IRENA or listed companies' disclosures.
- **Industrial end-user electricity and gas prices** need assembling from generation caps, grid tariffs and supplier margins; no single clean official series has been found yet.
