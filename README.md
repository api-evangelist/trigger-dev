# Trigger.dev

Trigger.dev is an open source background jobs and workflow automation platform for TypeScript developers. It enables building and deploying fully-managed AI agents and background workflows with real-time observability, scheduled tasks, durable execution, and an extensive management API. Tasks are written in plain async TypeScript and can be triggered via REST API, SDK, or on a schedule. Supports cloud-hosted and self-hosted deployments.

**URL:** [View APIs.yml](https://raw.githubusercontent.com/api-evangelist/trigger-dev/refs/heads/main/apis.yml)

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-03

## APIs

### Trigger.dev Management API

The Trigger.dev Management API provides comprehensive REST endpoints for managing workflow runs, tasks, schedules, deployments, queues, environment variables, batches, and waitpoints. Authenticated via bearer token.

**Human URL:** [https://trigger.dev/docs/management/overview](https://trigger.dev/docs/management/overview)

#### Tags

- Workflow Automation, Background Jobs, Task Management, Scheduling, Queue Management, Deployments

#### Properties

- [Documentation](https://trigger.dev/docs/management/overview)
- [Getting Started](https://trigger.dev/docs/introduction)
- [OpenAPI](openapi/trigger-dev-management-openapi.yml)
- [SDK](https://www.npmjs.com/package/@trigger.dev/sdk)

### Trigger.dev Realtime API

Provides streaming updates and React hooks for monitoring workflow run status in real-time.

**Human URL:** [https://trigger.dev/docs/realtime/overview](https://trigger.dev/docs/realtime/overview)

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [Trigger.dev Management API](openapi/trigger-dev-management-openapi.yml) | Full Management API covering runs, tasks, schedules, queues, deployments, env vars, batches, and waitpoints |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [Trigger.dev Rules](rules/trigger-dev-rules.yml) | Spectral ruleset enforcing Trigger.dev API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/trigger-dev-management.yaml](capabilities/shared/trigger-dev-management.yaml) | Per-API consumed definition for Trigger.dev Management API |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [capabilities/workflow-automation.yaml](capabilities/workflow-automation.yaml) | Full workflow automation: task triggering, run monitoring, schedules, queues, waitpoints (13 tools) |

## JSON Schema

| Schema | Description |
|---|---|
| [json-schema/trigger-dev-run-schema.json](json-schema/trigger-dev-run-schema.json) | JSON Schema for Trigger.dev run entities |
| [json-schema/trigger-dev-schedule-schema.json](json-schema/trigger-dev-schedule-schema.json) | JSON Schema for Trigger.dev schedule entities |

## JSON Structure

| Structure | Description |
|---|---|
| [json-structure/trigger-dev-run-structure.json](json-structure/trigger-dev-run-structure.json) | Structure documentation for Trigger.dev runs |

## JSON-LD Context

| Context | Description |
|---|---|
| [json-ld/trigger-dev-context.jsonld](json-ld/trigger-dev-context.jsonld) | JSON-LD context for Trigger.dev workflow entities |

## Examples

| Example | Description |
|---|---|
| [examples/trigger-dev-trigger-task-example.json](examples/trigger-dev-trigger-task-example.json) | Trigger a task with payload and options |
| [examples/trigger-dev-list-runs-example.json](examples/trigger-dev-list-runs-example.json) | List runs with status and tag filtering |
| [examples/trigger-dev-create-schedule-example.json](examples/trigger-dev-create-schedule-example.json) | Create a cron schedule |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/trigger-dev-vocabulary.yml](vocabulary/trigger-dev-vocabulary.yml) | Domain vocabulary for Trigger.dev platform concepts |

## GitHub

- [triggerdotdev/trigger.dev](https://github.com/triggerdotdev/trigger.dev) — Main monorepo (14,763 stars) - TypeScript
- [triggerdotdev/api-reference](https://github.com/triggerdotdev/api-reference) — Job code samples for SDK and REST API integrations

## Common Links

- **Website:** [https://trigger.dev](https://trigger.dev)
- **Documentation:** [https://trigger.dev/docs](https://trigger.dev/docs)
- **GitHub:** [https://github.com/triggerdotdev/trigger.dev](https://github.com/triggerdotdev/trigger.dev)
- **SDK (npm):** [https://www.npmjs.com/package/@trigger.dev/sdk](https://www.npmjs.com/package/@trigger.dev/sdk)
- **Sign Up:** [https://cloud.trigger.dev/login](https://cloud.trigger.dev/login)
- **Pricing:** [https://trigger.dev/pricing](https://trigger.dev/pricing)
- **Blog:** [https://trigger.dev/blog](https://trigger.dev/blog)
- **Changelog:** [https://trigger.dev/changelog](https://trigger.dev/changelog)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
