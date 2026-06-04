# University of Bonn (university-of-bonn)

The University of Bonn (Rheinische Friedrich-Wilhelms-Universität Bonn) is a public research university in Bonn, Germany, ranked #227 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an APIs.json provider profile. Its primary machine-readable surface is **bonndata**, the institutional research data repository built on the open-source Dataverse platform, exposing a public REST API and an OAI-PMH endpoint.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-bonn/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-bonn-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Data, Germany

## APIs

- **bonndata Dataverse Native REST API** — Public REST search/data-access API for the bonndata research data repository (Dataverse). Docs: https://guides.dataverse.org/en/latest/api/native-api.html — Base: https://bonndata.uni-bonn.de/api
- **bonndata OAI-PMH Metadata Endpoint** — OAI-PMH metadata harvesting endpoint for bonndata. Docs: https://guides.dataverse.org/en/latest/admin/harvestserver.html — Base: https://bonndata.uni-bonn.de/oai

## Plans

- [plans/university-of-bonn-plans-pricing.yml](plans/university-of-bonn-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-bonn-rate-limits.yml](rate-limits/university-of-bonn-rate-limits.yml)

## FinOps

- [finops/university-of-bonn-finops.yml](finops/university-of-bonn-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uni-bonn.de/en
- GitHub: https://github.com/unibonn
- LinkedIn: https://www.linkedin.com/school/university-of-bonn/
- Plans: plans/university-of-bonn-plans-pricing.yml
- RateLimits: rate-limits/university-of-bonn-rate-limits.yml
- FinOps: finops/university-of-bonn-finops.yml
- Review: review.yml

## Notes

All cataloged APIs were verified live on 2026-06-03: the bonndata Dataverse search API returned JSON (362 indexed records) and the OAI-PMH endpoint returned a valid response to `verb=Identify`. The `unibonn` GitHub organization was confirmed (158 public repositories). No separately branded university developer portal, public student/timetable SIS API, or documented public library (Alma/Primo) API was found; those systems run on standard vendor platforms without published public developer docs. The City of Bonn operates a municipal open-data portal (opendata.bonn.de), which is distinct from the university. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
