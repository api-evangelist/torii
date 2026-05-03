# Torii

Torii is the market leading SaaS Management Platform built to bring all your software into one place. Discover shadow IT, enforce governance, cut costs, and operationalize every app. Torii integrates with 180+ SaaS applications to provide license and usage data, automate user onboarding and offboarding workflows, manage SaaS contracts and renewals, and maintain compliance audit trails.

**Website:** [https://www.toriihq.com](https://www.toriihq.com)
**Developer Documentation:** [https://developers.toriihq.com](https://developers.toriihq.com)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Apps, Compliance, Cost Optimization, Governance, IT Management, SaaS Management

## APIs

### Torii SaaS Management API

Programmatic access to the Torii SaaS Management Platform. Manage apps, users, contracts, licenses, audit logs, and file uploads. Supports custom integration data sync, workflow execution monitoring, and SCIM 2.0 user provisioning.

**Human URL:** [https://developers.toriihq.com/reference/introduction-1](https://developers.toriihq.com/reference/introduction-1)
**Base URL:** `https://api.toriihq.com/v1.0`

**Tags:** Apps, Audit, Contracts, Files, Metadata, Parsings, SaaS Management, SCIM, Users

**Authentication:** Bearer API key (generated in Torii Settings > API Access)

**Properties:**
- [Documentation](https://developers.toriihq.com/reference/introduction-1)
- [OpenAPI](openapi/torii-torii-openapi.yml)
- [SpectralRules](rules/torii-rules.yml)
- [NaftikoCapability](capabilities/shared/torii-saas-management.yaml)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [openapi/torii-torii-openapi.yml](openapi/torii-torii-openapi.yml) | Torii SaaS Management API — OpenAPI 3.1 |

### Spectral Rules

| File | Description |
|---|---|
| [rules/torii-rules.yml](rules/torii-rules.yml) | Spectral ruleset for Torii API conventions |

### Naftiko Capabilities

| File | Description |
|---|---|
| [capabilities/saas-governance.yaml](capabilities/saas-governance.yaml) | SaaS governance workflow capability (REST + MCP, 14 tools) |
| [capabilities/shared/torii-saas-management.yaml](capabilities/shared/torii-saas-management.yaml) | Shared Torii SaaS Management API definition |

### JSON Schema

| File | Description |
|---|---|
| [json-schema/app.json](json-schema/app.json) | JSON Schema for App entity |
| [json-schema/user.json](json-schema/user.json) | JSON Schema for User entity |
| [json-schema/contract.json](json-schema/contract.json) | JSON Schema for Contract entity |
| [json-schema/audit-log-entry.json](json-schema/audit-log-entry.json) | JSON Schema for Audit Log Entry |
| [json-schema/field-metadata.json](json-schema/field-metadata.json) | JSON Schema for Field Metadata |
| [json-schema/parsing-request.json](json-schema/parsing-request.json) | JSON Schema for Parsing Request |
| [json-schema/scim-user.json](json-schema/scim-user.json) | JSON Schema for SCIM User |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/torii-app-structure.json](json-structure/torii-app-structure.json) | App, User, Contract, and Audit Log object model structure |

### JSON-LD Context

| File | Description |
|---|---|
| [json-ld/torii-context.jsonld](json-ld/torii-context.jsonld) | JSON-LD context for Torii domain vocabulary |

### Examples

| File | Description |
|---|---|
| [examples/torii-list-apps-example.json](examples/torii-list-apps-example.json) | GET /apps — list organization apps |
| [examples/torii-sync-custom-integration-example.json](examples/torii-sync-custom-integration-example.json) | POST /services/sync/custom — sync custom app data |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/torii-vocabulary.yml](vocabulary/torii-vocabulary.yml) | Domain vocabulary for the Torii SaaS Management Platform |

## Features

- Shadow IT Discovery
- App Lifecycle Management (discovered, managed, closed)
- License Optimization and Waste Detection
- SaaS Contract and Renewal Management
- Workflow Automation (20+ built-in actions)
- User Onboarding and Offboarding
- SCIM 2.0 User Provisioning
- Compliance Audit Logs
- Custom Application Data Integration
- Browser Extension
- 180+ Native SaaS Integrations

## Common Properties

- [Website](https://www.toriihq.com/)
- [Developer Documentation](https://developers.toriihq.com)
- [Pricing](https://www.toriihq.com/pricing)
- [Login](https://app.toriihq.com/login)
- [Terms of Service](https://www.toriihq.com/terms)
- [Security](https://www.toriihq.com/security)
- [Partners](https://www.toriihq.com/partners)
- [LinkedIn](https://www.linkedin.com/company/toriihq/)

## Timestamps

- **Created:** 2025-07-15
- **Modified:** 2026-05-03

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
