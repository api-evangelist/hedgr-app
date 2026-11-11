# HEDGR

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

HEDGR is the AI FX agent for SME finance teams, built by Timmy Elenjical, a former JPMorgan and Bank of America emerging‑markets FX trader. Hedgr Ltd, registered in England and Wales, offers a platform that connects to accounting systems like Xero, QuickBooks, Sage, and provides AI‑driven foreign‑currency insights without executing trades. It supports spreadsheet uploads, offers a 30‑day free trial, and provides tiered pricing for UK and South Africa markets.

**Areas:** Finance · AI · FX · SME · Accounting · Platform

## HEDGR on APIs.io

Everything profiled for HEDGR is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hedgr-app/](https://apis.io/providers/hedgr-app/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [HEDGR Health API](https://apis.io/apis/hedgr-app/hedgr-app-health-api/) — Public liveness and operational status checks.
- [HEDGR MCP API](https://apis.io/apis/hedgr-app/hedgr-app-mcp-api/) — Model Context Protocol endpoint for agents calling Hedgr's read-only dashboard tools.
- [HEDGR OAuth discovery API](https://apis.io/apis/hedgr-app/hedgr-app-oauth-discovery-api/) — RFC 8414 / RFC 9728 metadata used to authenticate against the MCP endpoint.
- [HEDGR Partner API](https://apis.io/apis/hedgr-app/hedgr-app-partner-api-api/) — REST API for broker and FX dealing firms: clients that share their portfolio, deal reporting, signed webhooks. Docs: https://hedgr.app/partner-api.
- [HEDGR Rates API](https://apis.io/apis/hedgr-app/hedgr-app-rates-api/) — Public FX reference rates.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [HEDGR Agentic Access](https://apis.io/agentic-access/hedgr-app/hedgr-app-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [ApiCatalog](https://apis.io/schemas/hedgr-app/hedgr-app-api-catalog/)
- [AuthorizationServerMetadata](https://apis.io/schemas/hedgr-app/hedgr-app-authorization-server-metadata/)
- [JsonRpcRequest](https://apis.io/schemas/hedgr-app/hedgr-app-json-rpc-request/)
- [McpDiscovery](https://apis.io/schemas/hedgr-app/hedgr-app-mcp-discovery/)
- [McpServerCard](https://apis.io/schemas/hedgr-app/hedgr-app-mcp-server-card/)
- [ProtectedResourceMetadata](https://apis.io/schemas/hedgr-app/hedgr-app-protected-resource-metadata/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Hedgr App Context](https://apis.io/jsonld/hedgr-app/hedgr-app-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [HEDGR API Rules](https://apis.io/rules/hedgr-app/hedgr-app-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [HEDGR Authentication](https://apis.io/security/hedgr-app/hedgr-app-authentication/)
- [HEDGR Domain Security](https://apis.io/security/hedgr-app/hedgr-app-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [HEDGR Scopes](https://apis.io/scopes/hedgr-app/hedgr-app-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [HEDGR Plans Pricing](https://apis.io/plans/hedgr-app/hedgr-app-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://hedgr.app/)
- [Documentation](https://hedgr.app/developer-docs)
- [API reference](https://hedgr.app/openapi.json)
- [Pricing](https://hedgr.app/pricing)
- [Security](https://hedgr.app/security)
- [Terms of service](https://hedgr.app/terms)
- [Privacy policy](https://hedgr.app/privacy)

## API Evangelist rating

**Kin Score 56.4** — strong · rubric 0.27.0 · scored 2026-11-11

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 61.2 |
| Contract governance | 79.1 |
| Operational transparency | 10.5 |
| Developer ergonomics | 35.0 |
| Access clarity | 67.9 |

**Agent readiness 59.0** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 36.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hedgr-app/](https://apis.io/providers/hedgr-app/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HEDGR: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hedgr-app/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
