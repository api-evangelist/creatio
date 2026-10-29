# Creatio

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

Creatio is a global software vendor of an AI-native no-code platform for customer relationship management (CRM) and workflow / business process automation. Its product line spans Sales Creatio, Marketing Creatio, and Service Creatio, built on Studio Creatio — a no-code toolkit with visual designers, AI agents, and a business process engine. Creatio serves banking, insurance, manufacturing, high tech, retail, CPG, pharmaceuticals, telecom, the public sector, and other industries. For integrations, Creatio exposes platform data and processes over an OData 4 service (recommended), a legacy OData 3 service, and the RESTful DataService web service, secured with forms (cookie) authentication via AuthService.svc or OAuth 2.0 through the Creatio Identity Service. Extensions and connectors are distributed through the Creatio Marketplace. This profile was enriched by the API Evangelist enrichment pipeline from Creatio's public developer documentation.

**Areas:** Company · Software-as-a-Service · CRM · No-Code · Low-Code · Business Process Management · Workflow Automation · Sales · Marketing · Customer Service · OData · AI Agents

## Creatio on APIs.io

Everything profiled for Creatio is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/creatio/](https://apis.io/providers/creatio/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Creatio OData API](https://apis.io/apis/creatio/creatio-odata-api/) — OData 4 (recommended) and legacy OData 3 access to Creatio platform entities. The OData 4 service is at /0/odata with EDMX metadata at /0/odata/$metadata;…
- [Creatio DataService API](https://apis.io/apis/creatio/creatio-dataservice-api/) — RESTful DataService web service for reading and writing platform records via InsertQuery, SelectQuery, UpdateQuery, DeleteQuery, and BatchQuery over HTTP…
- [Creatio Business Process Service](https://apis.io/apis/creatio/creatio-business-process-service/) — ProcessEngineService.svc runs Creatio business processes from an external application over HTTP. Execute() runs a process by schema name, passing incoming…
- [Creatio Webhook Service](https://apis.io/apis/creatio/creatio-webhook-service/) — Inbound webhook receiver. Lets an external app push data into Creatio in real time over an authenticated POST, writing a record into a target object named…
- [Creatio Clear Bundles API](https://apis.io/apis/creatio/creatio-clear-bundles-api/) — The Clear Bundles API from Creatio — 1 operation(s) for clear bundles.
- [Creatio Minify Content API](https://apis.io/apis/creatio/creatio-minify-content-api/) — The Minify Content API from Creatio — 1 operation(s) for minify content.
- [Creatio Odata API](https://apis.io/apis/creatio/creatio-odata-api/) — The Odata API from Creatio — 1 operation(s) for odata.
- [Creatio Process Content API](https://apis.io/apis/creatio/creatio-process-content-api/) — The Process Content API from Creatio — 1 operation(s) for process content.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Creatio Webhooks](https://apis.io/asyncapis/creatio/creatio-webhooks/)

#### JSON Schema (4)

The data models the API reads and writes.

- [PostClearBundlesRequest](https://apis.io/schemas/creatio/creatio-post-clear-bundles-request/)
- [PostMinifyContentRequest](https://apis.io/schemas/creatio/creatio-post-minify-content-request/)
- [Post0OdataOdataidRequest](https://apis.io/schemas/creatio/creatio-post0-odata-odataid-request/)
- [Post0OdataOdataidResponse](https://apis.io/schemas/creatio/creatio-post0-odata-odataid-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Creatio Context](https://apis.io/jsonld/creatio/creatio-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Creatio API Rules](https://apis.io/rules/creatio/creatio-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Creatio Authentication](https://apis.io/security/creatio/creatio-authentication/)
- [Creatio Domain Security](https://apis.io/security/creatio/creatio-domain-security/)
- [Creatio Trust Center](https://apis.io/security/creatio/creatio-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Creatio Plans Pricing](https://apis.io/plans/creatio/creatio-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Creatio Rate Limits](https://apis.io/rate-limits/creatio/creatio-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.creatio.com/)
- [Documentation](https://academy.creatio.com/docs)
- [Getting started](https://academy.creatio.com/docs/developer/integrations_and_api/integration_options)
- [API reference](https://academy.creatio.com/docs/developer/integrations_and_api/data_services/odata/overview)
- [Pricing](https://www.creatio.com/products/pricing)
- [Sign up](https://www.creatio.com/trial)
- [Support](https://community.creatio.com/)
- [Blog](https://www.creatio.com/blog)
- [Security](https://www.creatio.com/our-technologies/security)
- [Terms of service](https://www.creatio.com/legal)
- [Privacy policy](https://www.creatio.com/privacy-policy)

## API Evangelist rating

**Kin Score 62.1** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.4 |
| Contract quality | 28.3 |
| Contract governance | 35.6 |
| Operational transparency | 65.8 |
| Developer ergonomics | 71.4 |
| Access clarity | 92.1 |

**Agent readiness 23.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/creatio/](https://apis.io/providers/creatio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Creatio: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/creatio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
