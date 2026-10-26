# Software AG (software-ag)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Software AG provides enterprise integration and API management through webMethods, a platform for connecting applications, processes, and people across hybrid cloud and on-premises environments. The webMethods platform includes API Gateway, Developer Portal, Integration Server, and cloud-native integration services. Software AG was acquired by IBM in 2024.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Management
- Enterprise Integration
- iPaaS
- webMethods
- Integration Platform
- API Gateway

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### webMethods API Gateway Service Management API

The webMethods API Gateway Service Management API provides REST endpoints for managing APIs within the API Gateway platform. It supports creating, reading, updating, and deleting REST, SOAP, WebSocket, and OData APIs, as well as managing policies, applications, and gateway endpoints.

- **Human URL:** [https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/co-oview_what_is_api_portal.html](https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/co-oview_what_is_api_portal.html)
- **Base URL:** `http://localhost:5555/rest/apigateway`

#### Tags

- API Management
- API Gateway
- Enterprise Integration
- webMethods

#### Properties

- [Documentation](https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/gtw_manage_apis.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/openapi/webmethods-api-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Repository](https://github.com/SoftwareAG/webmethods-api-gateway)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-schema/webmethods-api-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-structure/webmethods-api-structure.json)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/rules/webmethods-api-gateway-rules.yml)
- [Postman Collection](collections/webmethods-api-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webmethods-api-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### webMethods Developer Portal

The webMethods Developer Portal provides a marketplace for publishing and discovering REST, SOAP, and OData APIs for third-party developers and partners. It enables developer onboarding, API subscription management, and API consumption analytics.

- **Human URL:** [https://www.softwareag.com/en_corporate/resources/api/ds/webmethods-developer-portal.html](https://www.softwareag.com/en_corporate/resources/api/ds/webmethods-developer-portal.html)
- **Base URL:** `https://www.softwareag.com/`

#### Tags

- Developer Portal
- API Management
- API Marketplace
- webMethods

#### Properties

- [Documentation](https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/co-oview_what_is_api_portal.html)
- [GitHub Repository](https://github.com/SoftwareAG/webmethods-developer-portal)
- [Postman Collection](collections/webmethods-api-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webmethods-api-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### webMethods Integration Server

The webMethods Integration Server is a comprehensive integration platform that enables connectivity between enterprise applications, databases, legacy systems, and cloud services. It provides flow services, adapters, and REST API exposure for business process integration.

- **Human URL:** [https://documentation.softwareag.com/](https://documentation.softwareag.com/)
- **Base URL:** `https://www.softwareag.com/`

#### Tags

- Integration
- Enterprise
- Middleware
- webMethods
- iPaaS

#### Properties

- [Documentation](https://documentation.softwareag.com/)
- [Postman Collection](collections/webmethods-api-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webmethods-api-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.softwareag.com/)
- [Website](https://www.softwareag.com/)
- [GitHub Organization](https://github.com/SoftwareAG)
- [Documentation](https://documentation.softwareag.com/)
- [Blog](https://techcommunity.softwareag.com/)
- [LinkedIn](https://www.linkedin.com/company/software-ag)
- [Twitter](https://twitter.com/SoftwareAG)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/json-ld/software-ag-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/vocabulary/software-ag-vocabulary.yml)
- [Integrations](https://www.softwareag.com/en/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
