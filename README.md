# Softr (softr)

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
