# Trelica (trelica)

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

Trelica is a SaaS management platform (now part of 1Password SaaS Manager) providing application discovery, license optimization, contract management, and workflow automation for IT teams. The platform offers a REST API covering applications, users, people, contracts, workflows, assets, and audit logs with OAuth 2.0 authentication using Client Credentials and Authorization Code flows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/trelica/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Contract Management
- IT Management
- License Management
- SaaS Management
- Software Asset Management

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### Trelica REST API

The Trelica REST API provides programmatic access to the core areas of the Trelica SaaS management platform, including applications, people, contracts, workflows, assets, audit logs, and user management. The API uses OAuth 2.0 with either Client Credentials (for integrations) or Authorization Code flow (for third-party developer apps). The Users endpoint follows the SCIM protocol.

- **Human URL:** [https://trelica.gitbook.io/trelica-api](https://trelica.gitbook.io/trelica-api)
- **Base URL:** `https://app.trelica.com/api`

#### Tags

- Application Discovery
- Contract Management
- IT Management
- License Management
- SaaS Management
- Software Asset Management

#### Properties

- [Documentation](https://trelica.gitbook.io/trelica-api)
- [Documentation](https://help.trelica.com/hc/en-us/sections/7739034184093-API)
- [Authentication](https://help.trelica.com/hc/en-us/articles/7739283478941-Trelica-API)
- [OpenAPI](openapi/trelica-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/trelica-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/trelica-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Organization](https://github.com/trelica)
- [GitHub Repository](https://github.com/trelica/trelica-api-sdk)
- [GitHub Repository](https://github.com/trelica/powershell)
- [GitHub Repository](https://github.com/trelica/node)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/trelica)
- [Website](https://www.trelica.com)
- [Documentation](https://trelica.gitbook.io/trelica-api)
- [Help Center](https://help.trelica.com/hc/en-us/sections/7739034184093-API)
- [Authentication](https://help.trelica.com/hc/en-us/articles/7739283478941-Trelica-API)
- [GitHub Organization](https://github.com/trelica)
- [SDK](https://github.com/trelica/trelica-api-sdk)
- [SDK](https://github.com/trelica/node)
- [SDK](https://github.com/trelica/powershell)
- [JSON Schema](json-schema/trelica-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trelica-person-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/trelica-contract-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/trelica-application-structure.json)
- [JSON-LD](json-ld/trelica-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/trelica-spectral-rules.yml)
- [Vocabulary](vocabulary/trelica-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
