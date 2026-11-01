# Trigger.dev

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

Trigger.dev is an open source platform for building and deploying fully-managed AI agents and background workflows in TypeScript. It provides durable task execution without timeout constraints, automatic retries, scheduled cron tasks, queues with concurrency controls, real-time observability, React hooks for streaming run status, human-in-the-loop waitpoints, batch triggering, and a comprehensive Management API. Cloud-hosted at cloud.trigger.dev and self-hostable via Docker or Fly.io.

**Areas:** Developer-First · Workflow Automation · Background Jobs · Durable Execution · TypeScript · AI Agents · Real-Time · Open Source

## Trigger.dev on APIs.io

Everything profiled for Trigger.dev is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/trigger-dev/](https://apis.io/providers/trigger-dev/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Trigger.dev Realtime API](https://apis.io/apis/trigger-dev/trigger-dev-realtime/) — The Trigger.dev Realtime API streams live run state and typed stream data to backend and frontend clients. Backend SDK methods include runs.subscribeToRun,…
- [Trigger.dev Batches API](https://apis.io/apis/trigger-dev/trigger-dev-batches-api/) — Create and retrieve large-scale batch runs.
- [Trigger.dev Deployments API](https://apis.io/apis/trigger-dev/trigger-dev-deployments-api/) — List deployments and promote versions to production.
- [Trigger.dev Environment Variables API](https://apis.io/apis/trigger-dev/trigger-dev-environment-variables-api/) — Create, read, update, delete, and import environment variables per project and environment.
- [Trigger.dev Query API](https://apis.io/apis/trigger-dev/trigger-dev-query-api/) — Execute TRQL queries against runs, tasks, and metrics for dashboards and analytics.
- [Trigger.dev Queues API](https://apis.io/apis/trigger-dev/trigger-dev-queues-api/) — Manage task queues including pause, resume, and concurrency overrides.
- [Trigger.dev Runs API](https://apis.io/apis/trigger-dev/trigger-dev-runs-api/) — List, retrieve, cancel, replay, reschedule, tag, and inspect run events, results, and traces.
- [Trigger.dev Schedules API](https://apis.io/apis/trigger-dev/trigger-dev-schedules-api/) — Create and manage cron schedules with IANA timezone support.
- [Trigger.dev Tasks API](https://apis.io/apis/trigger-dev/trigger-dev-tasks-api/) — Trigger individual or batched task runs.
- [Trigger.dev Waitpoints API](https://apis.io/apis/trigger-dev/trigger-dev-waitpoints-api/) — Create, list, retrieve, and complete waitpoint tokens for human-in-the-loop workflows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Trigger Dev Agentic Access](https://apis.io/agentic-access/trigger-dev/trigger-dev-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Trigger.dev Run](https://apis.io/schemas/trigger-dev/trigger-dev-run/)
- [Trigger.dev Schedule](https://apis.io/schemas/trigger-dev/trigger-dev-schedule/)
- [Trigger.dev Waitpoint Token](https://apis.io/schemas/trigger-dev/trigger-dev-waitpoint-token/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Trigger Dev Run Structure](https://apis.io/json-structure/trigger-dev/trigger-dev-run-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Trigger Dev Context](https://apis.io/jsonld/trigger-dev/trigger-dev-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Trigger.dev Vocabulary](https://apis.io/vocabularies/trigger-dev/trigger-dev-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Trigger Dev Create Schedule Example](https://apis.io/examples/trigger-dev/trigger-dev-create-schedule-example/)
- [Trigger Dev Create Waitpoint Example](https://apis.io/examples/trigger-dev/trigger-dev-create-waitpoint-example/)
- [Trigger Dev Execute Query Example](https://apis.io/examples/trigger-dev/trigger-dev-execute-query-example/)
- [Trigger Dev List Runs Example](https://apis.io/examples/trigger-dev/trigger-dev-list-runs-example/)
- [Trigger Dev Retrieve Run Events Example](https://apis.io/examples/trigger-dev/trigger-dev-retrieve-run-events-example/)
- [Trigger Dev Trigger Task Example](https://apis.io/examples/trigger-dev/trigger-dev-trigger-task-example/)

#### Collections (19)

Postman and Open Collection request collections.

- [Trigger.dev Management Batches API](https://apis.io/collections/trigger-dev/open-trigger-dev-batches-api/)
- [Trigger.dev Management Batches Deployments API](https://apis.io/collections/trigger-dev/open-trigger-dev-deployments-api/)
- [Trigger.dev Management Batches Environment Variables API](https://apis.io/collections/trigger-dev/open-trigger-dev-environment-variables-api/)
- [Trigger.dev Management API](https://apis.io/collections/trigger-dev/open-trigger-dev-management/)
- [Trigger.dev Management Batches Query API](https://apis.io/collections/trigger-dev/open-trigger-dev-query-api/)
- [Trigger.dev Management Batches Queues API](https://apis.io/collections/trigger-dev/open-trigger-dev-queues-api/)
- [Trigger.dev Management Batches Runs API](https://apis.io/collections/trigger-dev/open-trigger-dev-runs-api/)
- [Trigger.dev Management Batches Schedules API](https://apis.io/collections/trigger-dev/open-trigger-dev-schedules-api/)
- [Trigger.dev Management Batches Tasks API](https://apis.io/collections/trigger-dev/open-trigger-dev-tasks-api/)
- [Trigger.dev Management Batches Waitpoints API](https://apis.io/collections/trigger-dev/open-trigger-dev-waitpoints-api/)
- [Trigger.dev Management Batches API](https://apis.io/collections/trigger-dev/postman-trigger-dev-batches-api/)
- [Trigger.dev Management Batches Deployments API](https://apis.io/collections/trigger-dev/postman-trigger-dev-deployments-api/)
- [Trigger.dev Management Batches Environment Variables API](https://apis.io/collections/trigger-dev/postman-trigger-dev-environment-variables-api/)
- [Trigger.dev Management Batches Query API](https://apis.io/collections/trigger-dev/postman-trigger-dev-query-api/)
- [Trigger.dev Management Batches Queues API](https://apis.io/collections/trigger-dev/postman-trigger-dev-queues-api/)
- [Trigger.dev Management Batches Runs API](https://apis.io/collections/trigger-dev/postman-trigger-dev-runs-api/)
- [Trigger.dev Management Batches Schedules API](https://apis.io/collections/trigger-dev/postman-trigger-dev-schedules-api/)
- [Trigger.dev Management Batches Tasks API](https://apis.io/collections/trigger-dev/postman-trigger-dev-tasks-api/)
- [Trigger.dev Management Batches Waitpoints API](https://apis.io/collections/trigger-dev/postman-trigger-dev-waitpoints-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Trigger.dev — jsonschema rules](https://apis.io/rules/trigger-dev/trigger-dev-jsonschema-spectral-rules/)
- [Trigger.dev API Rules](https://apis.io/rules/trigger-dev/trigger-dev-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Trigger Dev Authentication](https://apis.io/security/trigger-dev/trigger-dev-authentication/)
- [Trigger Dev Domain Security](https://apis.io/security/trigger-dev/trigger-dev-domain-security/)
- [Trigger Dev Trust Center](https://apis.io/security/trigger-dev/trigger-dev-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Trigger Dev Plans Pricing](https://apis.io/plans/trigger-dev/trigger-dev-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Trigger Dev Rate Limits](https://apis.io/rate-limits/trigger-dev/trigger-dev-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Trigger Dev Finops](https://apis.io/finops/trigger-dev/trigger-dev-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://trigger.dev)
- [Documentation](https://trigger.dev/docs)
- [Getting started](https://trigger.dev/docs/introduction)
- [Pricing](https://trigger.dev/pricing)
- [Changelog](https://trigger.dev/changelog)
- [Blog](https://trigger.dev/blog)
- [Status](https://status.trigger.dev)

## API Evangelist rating

**Kin Score 52.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 69.1 |
| Contract governance | 27.3 |
| Operational transparency | 36.8 |
| Developer ergonomics | 51.2 |
| Access clarity | 39.5 |

**Agent readiness 27.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/trigger-dev/](https://apis.io/providers/trigger-dev/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Trigger.dev: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/trigger-dev/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
