# Templates

Empty templates (header row only). Method: `../SCREENING_APPROACH.md`. Evidence rules: `../RESEARCH_PROTOCOL.md`.

| File | One row per | Stage | Notes |
|---|---|---|---|
| `discovery_universe_template.csv` | Idea card | Discovery | ~1–2 min per card; no source needed |
| `longlist_template.csv` | Opportunity | Longlist → Top 5 | Columns fill in left to right as the idea advances |
| `evidence_log_template.csv` | Claim | Any | Every number or claim on a slide traces to an `evidence_id` |
| `sources_register_template.csv` | Source | Any | One row per source, reused across claims |
| `assumptions_register_template.csv` | Assumption | Any | Basis, sensitivity and how to test it |

**Code values**
- `lens`, `discovery_lens`: A1–A4, B1–B4, C1–C3, D1–D4, E1–E4 (Screening §2)
- `lens_source`: human / AI / practitioner
- `obviousness`: obvious / adjacent / non-obvious
- `triage`: keep / merge / park / drop (drop needs `triage_note`)
- `granularity`: cluster / sub-sector / product / HS-code
- `opportunity_type`: export-manufacturing / domestic-manufacturing / resource / infrastructure / services-digital / platform / agri-food / cluster / mixed
- `stage`: discovery / longlist / shortlist / finalist / top5 / parked / killed
- Gates `g1`–`g6`: PASS / FAIL / UWT / PARK (FAIL needs evidence + reason; UWT needs an entry in `uwt_tests`)
- `claim_type`: fact / calculation / assumption / inference / judgment
- `confidence`: high / medium / low
- `source_tier`: T1–T5 (Research Protocol §5)
- `locator`: page, table, chart or HS code inside the source

`q1`–`q6` hold short text answers or a link to a memo. No rating scale is assumed.
