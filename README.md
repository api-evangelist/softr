# Softr (softr)

Softr is a no-code platform for building client portals, internal tools, and web apps on top of Airtable, Google Sheets, and the native Softr Database. Its public REST APIs let you manage app users (create, invite, activate, magic links) and read and write records in Softr Databases programmatically using a Softr-Api-Key header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/softr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/softr/refs/heads/main/apis.yml)

## Tags

- No Code
- App Builder
- Client Portals
- User Management
- Database

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Softr Users Management API

Manage the end users of a published Softr app - create users, delete them, activate and deactivate accounts, send invitation emails, generate Magic Links, sync users, and validate auth tokens. Authenticated with a Softr-Api-Key and a Softr-Domain header.

- **Human URL:** [https://docs.softr.io/softr-api/api-setup-and-endpoints](https://docs.softr.io/softr-api/api-setup-and-endpoints)
- **Base URL:** `https://studio-api.softr.io/v1/api`

#### Tags

- Users
- Authentication
- Magic Link

#### Properties

- [Documentation](https://docs.softr.io/softr-api)
- [API Reference](https://docs.softr.io/softr-api/api-setup-and-endpoints)
- [OpenAPI](openapi/softr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/softr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/softr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Softr Database API

Public REST API for the native Softr Database - list databases, manage tables and table fields, and perform CRUD plus search over records. Authenticated with a Softr-Api-Key header; reads are limited to 40 req/s and writes to 30 req/s per token.

- **Human URL:** [https://docs.softr.io/softr-api/softr-database-api](https://docs.softr.io/softr-api/softr-database-api)
- **Base URL:** `https://tables-api.softr.io/api/v1`

#### Tags

- Database
- Records
- Tables

#### Properties

- [Documentation](https://docs.softr.io/softr-api/softr-database-api)
- [API Reference](https://docs.softr.io/softr-api/softr-database-api/records/get-records.md)
- [OpenAPI](openapi/softr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/softr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/softr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Softr Webhooks and Workflows

Softr Workflows fire outbound automations and HTTP webhook calls in response to app events (such as record or user changes), letting external systems react to activity inside a Softr app. There is no documented inbound public webhook subscription REST API.

- **Human URL:** [https://docs.softr.io/workflows](https://docs.softr.io/workflows)
- **Base URL:** `https://studio-api.softr.io/v1/api`

#### Tags

- Webhooks
- Workflows
- Automation

#### Properties

- [Documentation](https://docs.softr.io/workflows)

## Common Properties

- [GitHub Organization](https://github.com/softr-io)
- [LinkedIn](https://www.linkedin.com/company/softr)
- [Website](https://www.softr.io)
- [Documentation](https://docs.softr.io)
- [Plans](plans/softr-plans-pricing.yml)
- [Rate Limits](rate-limits/softr-rate-limits.yml)
- [Fin Ops](finops/softr-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
