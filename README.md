# Trigger.dev

Trigger.dev is an open source platform for building and deploying fully-managed AI agents and background workflows in TypeScript. It provides durable task execution without timeout constraints, automatic retries, scheduled cron tasks, queues with concurrency controls, real-time observability, React hooks for streaming run status, human-in-the-loop waitpoints, batch triggering, and a comprehensive Management API. Cloud-hosted at cloud.trigger.dev and self-hostable via Docker or Fly.io.

> "Trigger.dev is the platform for building AI workflows in TypeScript." — trigger.dev

**APIs.yml:** [View APIs.yml](https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/apis.yml)

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-22

## APIs

### Trigger.dev Management API

REST endpoints (base URL `https://api.trigger.dev`) for managing workflow runs, tasks, schedules, deployments, queues, environment variables, batches, waitpoints, and TRQL query/dashboards. Authenticated with a bearer secret API key (`tr_dev_*`, `tr_prod_*`, `tr_stg_*`) or personal access token (`tr_pat_*`).

**Human URL:** [https://trigger.dev/docs/management/overview](https://trigger.dev/docs/management/overview)

**Tags:** Workflow Automation, Background Jobs, Task Management, Scheduling, Deployments, Queue Management, Waitpoints, Batches, Environment Variables, Query

**Properties:**

- [Documentation](https://trigger.dev/docs/management/overview)
- [Authentication](https://trigger.dev/docs/management/authentication)
- [Getting Started](https://trigger.dev/docs/introduction)
- [OpenAPI](openapi/trigger-dev-management-openapi.yml)
- [Spectral Rules](rules/trigger-dev-rules.yml)
- [SDK (npm)](https://www.npmjs.com/package/@trigger.dev/sdk)

### Trigger.dev Realtime API

Live streaming updates and React hooks (`useRealtimeRun`, `useRealtimeRunsWithTag`, `useRealtimeBatch`, `useRealtimeStream`, `useWaitToken`, trigger-plus-subscribe hooks) plus backend `subscribeToRun` / `subscribeToRunsWithTag` / `subscribeToBatch` methods. Powers progress UIs, AI streaming output, and human-in-the-loop interfaces.

**Human URL:** [https://trigger.dev/docs/realtime/overview](https://trigger.dev/docs/realtime/overview)

**Tags:** Realtime, Streaming, React, WebSockets, AI Streaming, Frontend

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [Trigger.dev Management API](openapi/trigger-dev-management-openapi.yml) | Full Management API: tasks, runs (list/retrieve/cancel/replay/reschedule/tags/events/result/trace/metadata), schedules, deployments, queues, env vars, batches, waitpoints (incl. list + callback), and TRQL query. |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [Trigger.dev Rules](rules/trigger-dev-rules.yml) | Spectral ruleset enforcing Trigger.dev API conventions (camelCase operationIds, versioned paths, bearer auth, required path params, run_ prefix, RunStatus enum). |

## Naftiko Capabilities

| Capability | Description |
|---|---|
| [capabilities/management-tasks.yaml](capabilities/management-tasks.yaml) | Trigger and batch-trigger task runs (2 operations). |
| [capabilities/management-runs.yaml](capabilities/management-runs.yaml) | List, retrieve, cancel, replay, reschedule, tag, and inspect events/result/trace/metadata for runs (10 operations). |
| [capabilities/management-schedules.yaml](capabilities/management-schedules.yaml) | Create, list, retrieve, update, delete, activate, deactivate schedules + timezones. |
| [capabilities/management-deployments.yaml](capabilities/management-deployments.yaml) | List, retrieve, get-latest, promote deployments. |
| [capabilities/management-queues.yaml](capabilities/management-queues.yaml) | List, retrieve, pause, resume, override and reset queue concurrency. |
| [capabilities/management-environment-variables.yaml](capabilities/management-environment-variables.yaml) | CRUD plus bulk import for environment variables. |
| [capabilities/management-batches.yaml](capabilities/management-batches.yaml) | Create and retrieve large-scale batches. |
| [capabilities/management-waitpoints.yaml](capabilities/management-waitpoints.yaml) | Create, retrieve, complete, list waitpoint tokens. |
| [capabilities/management-query.yaml](capabilities/management-query.yaml) | Execute TRQL queries for analytics and dashboards. |

## JSON Schema

| Schema | Description |
|---|---|
| [json-schema/trigger-dev-run-schema.json](json-schema/trigger-dev-run-schema.json) | JSON Schema for Trigger.dev run entities. |
| [json-schema/trigger-dev-schedule-schema.json](json-schema/trigger-dev-schedule-schema.json) | JSON Schema for Trigger.dev schedule entities. |
| [json-schema/trigger-dev-waitpoint-token-schema.json](json-schema/trigger-dev-waitpoint-token-schema.json) | JSON Schema for Trigger.dev waitpoint tokens. |

## JSON Structure

| Structure | Description |
|---|---|
| [json-structure/trigger-dev-run-structure.json](json-structure/trigger-dev-run-structure.json) | Structure documentation for Trigger.dev runs. |

## JSON-LD Context

| Context | Description |
|---|---|
| [json-ld/trigger-dev-context.jsonld](json-ld/trigger-dev-context.jsonld) | JSON-LD context for Trigger.dev workflow, runtime, query, and observability entities. |

## Examples

| Example | Description |
|---|---|
| [examples/trigger-dev-trigger-task-example.json](examples/trigger-dev-trigger-task-example.json) | Trigger a task with payload and options. |
| [examples/trigger-dev-list-runs-example.json](examples/trigger-dev-list-runs-example.json) | List runs with status and tag filtering. |
| [examples/trigger-dev-create-schedule-example.json](examples/trigger-dev-create-schedule-example.json) | Create a cron schedule. |
| [examples/trigger-dev-create-waitpoint-example.json](examples/trigger-dev-create-waitpoint-example.json) | Create a waitpoint token for a human-in-the-loop step. |
| [examples/trigger-dev-execute-query-example.json](examples/trigger-dev-execute-query-example.json) | Execute a TRQL query grouped by run status. |
| [examples/trigger-dev-retrieve-run-events-example.json](examples/trigger-dev-retrieve-run-events-example.json) | Retrieve OpenTelemetry-style events for a run. |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/trigger-dev-vocabulary.yml](vocabulary/trigger-dev-vocabulary.yml) | Domain vocabulary covering task execution, run lifecycle, scheduling, queues, deployments, workflow patterns, authentication, realtime/streaming, and query/observability. |

## Plans, Rate Limits, and FinOps

| File | Description |
|---|---|
| [plans/trigger-dev-plans-pricing.yml](plans/trigger-dev-plans-pricing.yml) | API Commons Plans 0.1 mapping for Free ($0), Hobby ($10/mo), Pro ($50/mo), and Enterprise tiers; per-second compute pricing and $0.000025/run invocation. |
| [rate-limits/trigger-dev-rate-limits.yml](rate-limits/trigger-dev-rate-limits.yml) | Per-tier and global limits: 1500 req/min API rate, concurrency, schedules, realtime connections, batch buckets, payload/output caps, queue depth ceilings. |
| [finops/trigger-dev-finops.yml](finops/trigger-dev-finops.yml) | FinOps Framework / FOCUS-aligned billing model with run, compute, realtime, schedule, and egress meters. |

## GitHub

Trigger.dev's GitHub organization (`triggerdotdev`) hosts 85+ repositories. Highlights:

- [triggerdotdev/trigger.dev](https://github.com/triggerdotdev/trigger.dev) — Main monorepo (~15,025 stars, TypeScript)
- [triggerdotdev/jsonhero-web](https://github.com/triggerdotdev/jsonhero-web) — Open-source JSON explorer (~10,740 stars)
- [triggerdotdev/apihero](https://github.com/triggerdotdev/apihero) — API proxy for reliability/observability (~176 stars)
- [triggerdotdev/examples](https://github.com/triggerdotdev/examples) — Example projects to fork (~108 stars)
- [triggerdotdev/docker](https://github.com/triggerdotdev/docker) — Self-hosting Docker templates (~94 stars)
- [triggerdotdev/schema-infer](https://github.com/triggerdotdev/schema-infer) — JSON Schema and TS type inference (~54 stars)
- [triggerdotdev/fly.io](https://github.com/triggerdotdev/fly.io) — Self-host on Fly.io (~39 stars)
- [triggerdotdev/skills](https://github.com/triggerdotdev/skills) — Best practices for AI agents and background jobs (~26 stars)
- [triggerdotdev/api-reference](https://github.com/triggerdotdev/api-reference) — Job code samples for SDK + REST

## Common Links

- **Website:** [https://trigger.dev](https://trigger.dev)
- **Documentation:** [https://trigger.dev/docs](https://trigger.dev/docs)
- **GitHub Org:** [https://github.com/triggerdotdev](https://github.com/triggerdotdev)
- **SDK (npm):** [https://www.npmjs.com/package/@trigger.dev/sdk](https://www.npmjs.com/package/@trigger.dev/sdk)
- **CLI (npm):** [https://www.npmjs.com/package/trigger.dev](https://www.npmjs.com/package/trigger.dev)
- **Sign Up / Cloud:** [https://cloud.trigger.dev/login](https://cloud.trigger.dev/login)
- **Pricing:** [https://trigger.dev/pricing](https://trigger.dev/pricing)
- **Limits:** [https://trigger.dev/docs/limits](https://trigger.dev/docs/limits)
- **Blog:** [https://trigger.dev/blog](https://trigger.dev/blog)
- **Changelog:** [https://trigger.dev/changelog](https://trigger.dev/changelog)
- **Status:** [https://status.trigger.dev](https://status.trigger.dev)
- **Self-Hosting (Docker):** [https://github.com/triggerdotdev/docker](https://github.com/triggerdotdev/docker)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
