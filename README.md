# AWS Step Functions (step-functions)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AWS Step Functions is a serverless orchestration service that enables developers to compose distributed applications and APIs using visual workflows called state machines. It supports Standard and Express workflows, activities, parallel execution, error handling, and integrates with over 200 AWS services. Step Functions uses the Amazon States Language (ASL) for defining workflow logic as JSON-based state machine definitions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Composition
- Serverless Orchestration
- Workflow
- AWS
- State Machine
- Automation

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### AWS Step Functions API

The AWS Step Functions API enables creating, managing, and executing state machines and activities. Key operations include creating and deleting state machines, starting and stopping executions, listing execution history, managing state machine versions and aliases, tagging resources, and sending task heartbeats from activity workers. The API uses AWS Signature Version 4 (SigV4) authentication.

- **Human URL:** [https://aws.amazon.com/step-functions/](https://aws.amazon.com/step-functions/)
- **Base URL:** `https://states.{region}.amazonaws.com`

#### Tags

- Serverless
- Workflow
- State Machine
- Orchestration
- AWS

#### Properties

- [Documentation](https://docs.aws.amazon.com/step-functions/)
- [Reference](https://docs.aws.amazon.com/step-functions/latest/apireference/Welcome.html)
- [Getting Started](https://docs.aws.amazon.com/step-functions/latest/dg/getting-started.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/openapi/step-functions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Pricing](https://aws.amazon.com/step-functions/pricing/)
- [Postman Collection](collections/step-functions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/step-functions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://aws.amazon.com/step-functions/)
- [Documentation](https://docs.aws.amazon.com/step-functions/)
- [GitHub Organization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/states/)
- [Pricing](https://aws.amazon.com/step-functions/pricing/)
- [Blog](https://aws.amazon.com/blogs/compute/category/compute/aws-step-functions/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
