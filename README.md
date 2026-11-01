# University of Bonn

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Bonn (Rheinische Friedrich-Wilhelms-Universitaet Bonn), founded in 1818, is a public research university in North Rhine-Westphalia, Germany, and a member of the German Universities Excellence Initiative. Like every institution it is a federation of buyers rather than an API producer, but it is an unusually self-hosted one: the surfaces in this profile run on the university's own hosts, inside its own computing centre, rather than on a vendor's multi-tenant platform. bonndata, the institutional cross-disciplinary research data repository, runs Dataverse 6.7.1 at bonndata.uni-bonn.de (CNAME bonndata-produktiv.rhrz.uni-bonn.de, 131.220.213.19) and exposes a genuinely public, anonymous, read-only REST API — /search, /datasets, /datasets/export, /info/version, /info/metrics — plus a full OAI-PMH 2.0 endpoint; every documented path was re-verified live on 2026-09-01 and /search returned 376 indexed datasets. bonndoc, the university publication server at bonndoc.ulb.uni-bonn.de, answers OAI-PMH in ten metadata formats. The university runs its own Shibboleth Identity Provider at shibboleth.uni-bonn.de and is the only uni-bonn.de entity in the 11,457-entity DFN-AAI federation aggregate. It self-hosts GitLab at gitlab.uni-bonn.de, whose REST API v4 answers anonymously across 195 public projects, and keeps a GitHub organization at github.com/unibonn. It is a DataCite member (BXBQ) minting DOIs under prefix 10.60507 through the bonndata repository client, is registered in ROR as 041nas322 and in re3data as r3d100014222. What it does NOT have is equally clear and is stated here rather than padded: no central developer portal, no institution-authored OpenAPI or AsyncAPI, no llms.txt, sitemap.xml, apis.json or agent card on any host it controls, no public course, timetable or student-information API (BASIS runs HISinOne behind sign-in, eCampus runs ILIAS), and no institutional open-data portal — opendata.bonn.de belongs to the City of Bonn, not the university. Library discovery (bonnus) is Ex Libris Primo, self-hosted on a university IP, with no public API. The four OpenAPI documents in this repo are API-Evangelist-authored descriptions of the public read subset of the Dataverse Native API as deployed by Bonn; the Dataverse contract itself belongs to the Dataverse project, and no vendor specification is saved under this institution.

**Areas:** University · Higher Education · Education · Germany · Public Research University · Research Data · Open Data · Open Science · Institutional Repository · Dataverse · OAI-PMH · Identity Federation

## University of Bonn on APIs.io

Everything profiled for University of Bonn is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-bonn/](https://apis.io/providers/university-of-bonn/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [bonndata OAI-PMH Metadata Endpoint](https://apis.io/apis/university-of-bonn/bonndata-oai-pmh/) — OAI-PMH 2.0 metadata-harvesting endpoint for bonndata, the University of Bonn institutional research data repository. Re-verified live 2026-09-01:…
- [University of Bonn Datasets API](https://apis.io/apis/university-of-bonn/university-of-bonn-datasets-api/) — Retrieve published datasets, their versions, and export metadata from bonndata. Re-verified live 2026-09-01:…
- [University of Bonn Info API](https://apis.io/apis/university-of-bonn/university-of-bonn-info-api/) — Repository version and software information for bonndata. Re-verified live 2026-09-01: GET /info/version returned…
- [University of Bonn Metrics API](https://apis.io/apis/university-of-bonn/university-of-bonn-metrics-api/) — Aggregate repository metrics for bonndata. Re-verified live 2026-09-01: GET /info/metrics/datasets returned {"status":"OK","data":{"count":376}}. Note the…
- [University of Bonn Search API](https://apis.io/apis/university-of-bonn/university-of-bonn-search-api/) — Search the published catalog of datasets, dataverses and files in bonndata. Re-verified live 2026-09-01: /search?q=*&type=dataset returned total_count 376…
- [bonndoc Publication Server OAI-PMH Endpoint](https://apis.io/apis/university-of-bonn/bonndoc-oai-pmh/) — OAI-PMH 2.0 endpoint for bonndoc, "Der Publikationsserver der Universitaet Bonn" — the university's DSpace-based publication and dissertation server,…
- [bonndoc DSpace REST API (bot-challenged)](https://apis.io/apis/university-of-bonn/bonndoc-dspace-rest/) — bonndoc runs DSpace 7-class software, which exposes a HAL/JSON REST API at /server/api. It is recorded with an honest limit rather than as a working…
- [University of Bonn GitLab REST API v4](https://apis.io/apis/university-of-bonn/gitlab-api/) — The University of Bonn self-hosts GitLab at gitlab.uni-bonn.de and its REST API v4 answers anonymous callers over the public project set. Verified live…
- [DFN-AAI Identity Federation — University of Bonn Shibboleth IdP](https://apis.io/apis/university-of-bonn/dfn-aai-idp/) — The University of Bonn operates its own SAML 2.0 / Shibboleth Identity Provider and publishes signed metadata from its own host —…
- [DataCite Membership — University of Bonn (BXBQ)](https://apis.io/apis/university-of-bonn/datacite-member/) — The University of Bonn is a DataCite member organization and mints DOIs for its research data. Verified 2026-09-01 at…
- [ROR Registry Record — University of Bonn](https://apis.io/apis/university-of-bonn/ror-record/) — The University of Bonn's Research Organization Registry identifier, https://ror.org/041nas322, verified live 2026-09-01. Domain uni-bonn.de, established…
- [re3data Registry Record — bonndata](https://apis.io/apis/university-of-bonn/re3data-record/) — bonndata is registered in re3data, the Registry of Research Data Repositories, as r3d100014222 with its own DOI https://doi.org/10.17616/R31NJNGU. Verified…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of Bonn Agentic Access](https://apis.io/agentic-access/university-of-bonn/university-of-bonn-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [bonnDataSearchItem](https://apis.io/schemas/university-of-bonn/university-of-bonn-search-item/)
- [bonnDataSearchResponse](https://apis.io/schemas/university-of-bonn/university-of-bonn-search-response/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [University Of Bonn Dataset Structure](https://apis.io/json-structure/university-of-bonn/university-of-bonn-dataset-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Bonn Context](https://apis.io/jsonld/university-of-bonn/university-of-bonn-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [bonndata Native API Vocabulary](https://apis.io/vocabularies/university-of-bonn/university-of-bonn-vocabulary/)

#### Examples (3)

Example requests and responses.

- [University Of Bonn Info Version Example](https://apis.io/examples/university-of-bonn/university-of-bonn-info-version-example/)
- [University Of Bonn Metrics Datasets Example](https://apis.io/examples/university-of-bonn/university-of-bonn-metrics-datasets-example/)
- [University Of Bonn Search Example](https://apis.io/examples/university-of-bonn/university-of-bonn-search-example/)

#### Collections (4)

Postman and Open Collection request collections.

- [bonndata Dataverse Native REST API (Public Read Subset) Datasets API](https://apis.io/collections/university-of-bonn/open-university-of-bonn-datasets-api/)
- [bonndata Dataverse Native REST API (Public Read Subset) Datasets Info API](https://apis.io/collections/university-of-bonn/open-university-of-bonn-info-api/)
- [bonndata Dataverse Native REST API (Public Read Subset) Datasets Metrics API](https://apis.io/collections/university-of-bonn/open-university-of-bonn-metrics-api/)
- [bonndata Dataverse Native REST API (Public Read Subset) Datasets Search API](https://apis.io/collections/university-of-bonn/open-university-of-bonn-search-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of Bonn — jsonschema rules](https://apis.io/rules/university-of-bonn/university-of-bonn-jsonschema-spectral-rules/)
- [University of Bonn API Rules](https://apis.io/rules/university-of-bonn/university-of-bonn-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Bonn Authentication](https://apis.io/security/university-of-bonn/university-of-bonn-authentication/)
- [University Of Bonn Domain Security](https://apis.io/security/university-of-bonn/university-of-bonn-domain-security/)
- [University Of Bonn Vulnerability Disclosure](https://apis.io/security/university-of-bonn/university-of-bonn-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Bonn Plans Pricing](https://apis.io/plans/university-of-bonn/university-of-bonn-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Bonn Rate Limits](https://apis.io/rate-limits/university-of-bonn/university-of-bonn-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Bonn Finops](https://apis.io/finops/university-of-bonn/university-of-bonn-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.uni-bonn.de/en)
- [Documentation](https://guides.dataverse.org/en/latest/api/native-api.html)
- [Support](https://www.hrz.uni-bonn.de/en)
- [Blog](https://www.uni-bonn.de/news/rss.xml)
- [Terms of service](https://www.uni-bonn.de/en/imprint)
- [Privacy policy](https://www.uni-bonn.de/en/data-protection)
- [GitHub](https://github.com/unibonn)

## API Evangelist rating

**Kin Score 42.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.8 |
| Contract quality | 50.9 |
| Contract governance | 28.0 |
| Operational transparency | 18.4 |
| Developer ergonomics | 28.6 |
| Access clarity | 39.5 |

**Agent readiness 22.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 38.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-bonn/](https://apis.io/providers/university-of-bonn/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Bonn: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-bonn/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
