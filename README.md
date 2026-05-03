# Software AG

Software AG provides enterprise integration and API management through webMethods, a platform for connecting applications, processes, and people across hybrid cloud and on-premises environments. The webMethods platform includes API Gateway, Developer Portal, Integration Server, and cloud-native integration services. Software AG was acquired by IBM in 2024.

**URL:** [https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/software-ag/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- API Management
- Enterprise Integration
- iPaaS
- webMethods
- Integration Platform
- API Gateway

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### webMethods API Gateway Service Management API

The webMethods API Gateway Service Management API provides REST endpoints for managing APIs within the API Gateway platform. It supports creating, reading, updating, and deleting REST, SOAP, WebSocket, and OData APIs, as well as managing policies, applications, and gateway endpoints.

**Base URL:** `http://localhost:5555/rest/apigateway`
**Version:** 11.0
**Authentication:** Basic Authentication

**Tags:** API Management, API Gateway, Enterprise Integration, webMethods

#### Properties

- [Documentation](https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/gtw_manage_apis.html)
- [OpenAPI Spec](openapi/webmethods-api-gateway-openapi.yml)
- [GitHub Repository](https://github.com/SoftwareAG/webmethods-api-gateway)
- [JSON Schema](json-schema/webmethods-api-schema.json)
- [JSON Structure](json-structure/webmethods-api-structure.json)
- [Spectral Rules](rules/webmethods-api-gateway-rules.yml)
- [Naftiko Capabilities](capabilities/api-management.yaml)

### webMethods Developer Portal

The webMethods Developer Portal provides a marketplace for publishing and discovering REST, SOAP, and OData APIs for third-party developers and partners.

**Tags:** Developer Portal, API Management, API Marketplace, webMethods

#### Properties

- [Documentation](https://documentation.softwareag.com/webmethods/compendiums/v10-5/C_API_Management/api-mgmt-comp/co-oview_what_is_api_portal.html)
- [GitHub Repository](https://github.com/SoftwareAG/webmethods-developer-portal)

### webMethods Integration Server

The webMethods Integration Server is a comprehensive integration platform for connecting enterprise applications, databases, legacy systems, and cloud services.

**Tags:** Integration, Enterprise, Middleware, webMethods, iPaaS

#### Properties

- [Documentation](https://documentation.softwareag.com/)

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [webmethods-api-gateway-openapi.yml](openapi/webmethods-api-gateway-openapi.yml) | API Gateway Service Management API (v11.0) — 15 operations across APIs, Applications, Policies, and Publishing |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [webmethods-api-gateway-rules.yml](rules/webmethods-api-gateway-rules.yml) | 12 Spectral rules enforcing webMethods naming conventions, security, and documentation standards |

## Capabilities

### Workflow Capabilities

| Capability | Description |
|---|---|
| [api-management.yaml](capabilities/api-management.yaml) | Unified API lifecycle management: create, activate, publish, and monitor APIs in webMethods API Gateway |

### Shared Definitions

| Shared Definition | API |
|---|---|
| [webmethods-api-gateway.yaml](capabilities/shared/webmethods-api-gateway.yaml) | webMethods API Gateway Service Management REST and MCP adapters |

## JSON Schema

| Schema | Description |
|---|---|
| [webmethods-api-schema.json](json-schema/webmethods-api-schema.json) | JSON Schema for the webMethods API Gateway API resource |

## JSON Structure

| Structure | Description |
|---|---|
| [webmethods-api-structure.json](json-structure/webmethods-api-structure.json) | Structure documentation for API, Application, Policy, and Package resources |

## JSON-LD

| Context | Description |
|---|---|
| [software-ag-context.jsonld](json-ld/software-ag-context.jsonld) | Linked data context mapping webMethods concepts to schema.org |

## Examples

| Example | Description |
|---|---|
| [webmethods-list-apis-example.json](examples/webmethods-list-apis-example.json) | GET /apis — List all APIs in the gateway |
| [webmethods-create-api-example.json](examples/webmethods-create-api-example.json) | POST /apis — Create a new API from an OpenAPI spec |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [software-ag-vocabulary.yml](vocabulary/software-ag-vocabulary.yml) | webMethods platform vocabulary covering API Management, Enterprise Integration, Consumer Management, and API Types |

## Common Properties

- [Developer Portal](https://developer.softwareag.com/)
- [Website](https://www.softwareag.com/)
- [GitHub Organization](https://github.com/SoftwareAG)
- [Documentation](https://documentation.softwareag.com/)
- [Tech Community](https://techcommunity.softwareag.com/)
- [LinkedIn](https://www.linkedin.com/company/software-ag)
- [Twitter](https://twitter.com/SoftwareAG)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
