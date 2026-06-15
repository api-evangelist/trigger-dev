# Trigger.dev (trigger-dev)

Trigger.dev is an open source platform for building and deploying fully-managed AI agents and background workflows in TypeScript. It provides durable task execution without timeout constraints, automatic retries, scheduled cron tasks, queues with concurrency controls, real-time observability, React hooks for streaming run status, human-in-the-loop waitpoints, batch triggering, and a comprehensive Management API. Cloud-hosted at cloud.trigger.dev and self-hostable via Docker or Fly.io.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Developer-First
- Workflow Automation
- Background Jobs
- Durable Execution
- TypeScript
- AI Agents
- Realtime
- Open Source

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-22

## APIs

### Trigger.dev Management API

The Trigger.dev Management API provides comprehensive REST endpoints for managing workflow runs, tasks, schedules, deployments, queues, environment variables, batches, waitpoints, and query/dashboards. Enables programmatic control over the full lifecycle of background job workflows including triggering, monitoring, cancellation, replay, tagging, and observability. Authenticated via bearer token (secret API key prefixed tr_dev_/tr_prod_ or personal access token tr_pat_) at https://api.trigger.dev.

- **Human URL:** [https://trigger.dev/docs/management/overview](https://trigger.dev/docs/management/overview)
- **Base URL:** `https://api.trigger.dev`

#### Tags

- Workflow Automation
- Background Jobs
- Task Management
- Scheduling
- Deployments
- Queue Management
- Waitpoints
- Batches
- Environment Variables
- Query

#### Properties

- [Documentation](https://trigger.dev/docs/management/overview)
- [Getting Started](https://trigger.dev/docs/introduction)
- [Authentication](https://trigger.dev/docs/management/authentication)
- [OpenAPI](openapi/trigger-dev-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trigger-dev-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trigger-dev-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/trigger-dev-rules.yml)
- [SDK](https://www.npmjs.com/package/@trigger.dev/sdk)
- [JSON Schema](json-schema/trigger-dev-run-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trigger-dev-schedule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trigger-dev-waitpoint-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/trigger-dev-run-structure.json)
- [Example](examples/trigger-dev-trigger-task-example.json)
- [Example](examples/trigger-dev-list-runs-example.json)
- [Example](examples/trigger-dev-create-schedule-example.json)
- [Example](examples/trigger-dev-create-waitpoint-example.json)
- [Example](examples/trigger-dev-execute-query-example.json)
- [Example](examples/trigger-dev-retrieve-run-events-example.json)

### Trigger.dev Realtime API

The Trigger.dev Realtime API streams live run state and typed stream data to backend and frontend clients. Backend SDK methods include runs.subscribeToRun, runs.subscribeToRunsWithTag, and runs.subscribeToBatch. React hooks include useRealtimeRun, useRealtimeRunsWithTag, useRealtimeBatch, useRealtimeStream, useWaitToken, and trigger-plus-subscribe hooks. Powers progress UIs, AI streaming output, and human-in-the-loop interfaces.

- **Human URL:** [https://trigger.dev/docs/realtime/overview](https://trigger.dev/docs/realtime/overview)

#### Tags

- Realtime
- Streaming
- React
- WebSockets
- AI Streaming
- Frontend

#### Properties

- [Documentation](https://trigger.dev/docs/realtime/overview)
- [Authentication](https://trigger.dev/docs/realtime/auth)
- [SDK](https://www.npmjs.com/package/@trigger.dev/react-hooks)
- [Postman Collection](collections/trigger-dev-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trigger-dev-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/triggerdotdev)
- [Website](https://trigger.dev)
- [Documentation](https://trigger.dev/docs)
- [Getting Started](https://trigger.dev/docs/introduction)
- [Git Hub](https://github.com/triggerdotdev)
- [SDK](https://www.npmjs.com/package/@trigger.dev/sdk)
- [C L I](https://www.npmjs.com/package/trigger.dev)
- [Sign Up](https://cloud.trigger.dev/login)
- [Pricing](https://trigger.dev/pricing)
- [Pricing Plans](plans/trigger-dev-plans-pricing.yml)
- [Rate Limits](rate-limits/trigger-dev-rate-limits.yml)
- [Fin Ops](finops/trigger-dev-finops.yml)
- [Limits](https://trigger.dev/docs/limits)
- [Blog](https://trigger.dev/blog)
- [Changelog](https://trigger.dev/changelog)
- [Status Page](https://status.trigger.dev)
- [Self Hosting](https://github.com/triggerdotdev/docker)
- [Vocabulary](vocabulary/trigger-dev-vocabulary.yml)
- [JSON-LD](json-ld/trigger-dev-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
