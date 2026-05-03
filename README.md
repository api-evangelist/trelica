# Trelica

Trelica is a SaaS management platform (now part of 1Password SaaS Manager) providing application discovery, license optimization, contract management, and workflow automation for IT teams. The platform offers a REST API covering applications, users, people, contracts, workflows, assets, and audit logs with OAuth 2.0 authentication using Client Credentials and Authorization Code flows.

**Website:** [https://www.trelica.com](https://www.trelica.com)  
**API Docs:** [https://trelica.gitbook.io/trelica-api](https://trelica.gitbook.io/trelica-api)  
**Help Center:** [https://help.trelica.com/hc/en-us/sections/7739034184093-API](https://help.trelica.com/hc/en-us/sections/7739034184093-API)

## APIs

### Trelica REST API

The Trelica REST API provides programmatic access to the SaaS management platform covering applications, users, people, contracts, workflows, assets, and audit logs. Authentication uses OAuth 2.0 with Client Credentials (for integrations) or Authorization Code flow (for third-party apps). The Users endpoint follows the SCIM 2.0 protocol.

- **Base URL:** `https://app.trelica.com/api`
- **EU Base URL:** `https://eu.trelica.com/api`
- **Authentication:** OAuth 2.0 (Client Credentials / Authorization Code)
- **Documentation:** [https://trelica.gitbook.io/trelica-api](https://trelica.gitbook.io/trelica-api)
- **OpenAPI:** [openapi/trelica-rest-api-openapi.yml](openapi/trelica-rest-api-openapi.yml)

## Artifacts

| Type | File |
|---|---|
| OpenAPI Spec | [openapi/trelica-rest-api-openapi.yml](openapi/trelica-rest-api-openapi.yml) |
| JSON Schema (Application) | [json-schema/trelica-application-schema.json](json-schema/trelica-application-schema.json) |
| JSON Schema (Person) | [json-schema/trelica-person-schema.json](json-schema/trelica-person-schema.json) |
| JSON Schema (Contract) | [json-schema/trelica-contract-schema.json](json-schema/trelica-contract-schema.json) |
| JSON Structure (Application) | [json-structure/trelica-application-structure.json](json-structure/trelica-application-structure.json) |
| JSON-LD Context | [json-ld/trelica-context.jsonld](json-ld/trelica-context.jsonld) |
| Spectral Rules | [rules/trelica-spectral-rules.yml](rules/trelica-spectral-rules.yml) |
| Vocabulary | [vocabulary/trelica-vocabulary.yml](vocabulary/trelica-vocabulary.yml) |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/trelica-rest-api.yaml](capabilities/shared/trelica-rest-api.yaml) | Full Trelica REST API consumed definition |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/saas-management.yaml](capabilities/saas-management.yaml) | Unified SaaS portfolio management for IT teams (applications, people, contracts, workflows, assets, audit logs) |

## Examples

- [examples/trelica-list-applications-example.json](examples/trelica-list-applications-example.json)
- [examples/trelica-list-people-example.json](examples/trelica-list-people-example.json)

## SDKs & Integrations

- **TypeScript SDK:** [https://github.com/trelica/trelica-api-sdk](https://github.com/trelica/trelica-api-sdk)
- **Node.js SDK:** [https://github.com/trelica/node](https://github.com/trelica/node)
- **PowerShell Scripts:** [https://github.com/trelica/powershell](https://github.com/trelica/powershell)

## Tags

Contract Management, IT Management, License Management, SaaS Management, Software Asset Management
