# AWS Step Functions

AWS Step Functions is a serverless orchestration service that enables developers to compose distributed applications and APIs using visual workflows called state machines. It supports Standard and Express workflows, activities, parallel execution, error handling, and integrates with 200+ AWS services using the Amazon States Language (ASL).

## APIs

- **[AWS Step Functions API](https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html)** — REST API for creating and managing state machines, starting and monitoring executions, managing activity workers, versioning, and aliasing. Uses AWS Signature Version 4 authentication.

## OpenAPI Specs

- [step-functions-openapi.yml](openapi/step-functions-openapi.yml)

## Rules

- [step-functions-rules.yml](rules/step-functions-rules.yml) — Spectral ruleset enforcing AWS Step Functions API conventions

## Capabilities

### Workflow Capabilities

- [workflow-orchestration.yaml](capabilities/workflow-orchestration.yaml) — Unified workflow orchestration covering state machine lifecycle, execution management, versioning, aliases, and activity workers (15 MCP tools)

### Shared Definitions

- [shared/step-functions.yaml](capabilities/shared/step-functions.yaml) — AWS Step Functions API consumed definition

## JSON Schema

- [step-functions-state-machine-schema.json](json-schema/step-functions-state-machine-schema.json) — Schema for state machine objects

## JSON Structure

- [step-functions-state-machine-structure.json](json-structure/step-functions-state-machine-structure.json) — Field structure documentation for state machines

## JSON-LD

- [step-functions-context.jsonld](json-ld/step-functions-context.jsonld) — JSON-LD context for Step Functions entities

## Examples

- [step-functions-start-execution-example.json](examples/step-functions-start-execution-example.json) — Start Execution example
- [step-functions-list-state-machines-example.json](examples/step-functions-list-state-machines-example.json) — List State Machines example

## Vocabulary

- [step-functions-vocabulary.yml](vocabulary/step-functions-vocabulary.yml) — Domain vocabulary for AWS Step Functions concepts including ASL state types

## Common Properties

- [Website](https://aws.amazon.com/step-functions/)
- [Documentation](https://docs.aws.amazon.com/step-functions/)
- [API Reference](https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html)
- [AWS Console](https://console.aws.amazon.com/states/)
- [Pricing](https://aws.amazon.com/step-functions/pricing/)
- [GitHub](https://github.com/aws)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
