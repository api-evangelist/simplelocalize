# SimpleLocalize (simplelocalize)

SimpleLocalize is a web-based translation management platform that helps small and growing teams save time on handling localization files and translation strings. It provides a REST API for managing translations, languages, projects, and customers, along with integrations for CI/CD pipelines, frameworks, and AI-powered tools.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Localization
- Translation
- Internationalization

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### SimpleLocalize Translation API

The SimpleLocalize Translation API provides REST endpoints to create, read, update, and delete translations. It supports querying translations by key, language, namespace, text content, review status, and customer ID. The API also supports bulk import and export of translation files in 30+ formats including JSON, YAML, XLIFF, Android XML, iOS Strings, and more.

- **Human URL:** [https://simplelocalize.io/docs/api/get-started/](https://simplelocalize.io/docs/api/get-started/)
- **Base URL:** `https://api.simplelocalize.io`

#### Tags

- Translation
- Localization
- Import
- Export

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/get-started/)
- [OpenAPI](https://api.simplelocalize.io/openapi/docs) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Swagger U I](https://api.simplelocalize.io/openapi/ui)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/openapi/simplelocalize-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/simplelocalize.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/simplelocalize.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SimpleLocalize Language API

The SimpleLocalize Language API provides endpoints to create, list, update, and delete languages within a project. Each language is identified by a unique key and requires API key authentication via the X-SimpleLocalize-Token header.

- **Human URL:** [https://simplelocalize.io/docs/api/language-api/](https://simplelocalize.io/docs/api/language-api/)
- **Base URL:** `https://api.simplelocalize.io`

#### Tags

- Languages
- Localization

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/language-api/)
- [Postman Collection](collections/simplelocalize.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/simplelocalize.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SimpleLocalize Projects API

The SimpleLocalize Projects API allows creation and listing of translation projects. It uses Personal Token authentication (Bearer) rather than API keys, enabling multi-project management workflows.

- **Human URL:** [https://simplelocalize.io/docs/api/translation-project-management/](https://simplelocalize.io/docs/api/translation-project-management/)
- **Base URL:** `https://api.simplelocalize.io`

#### Tags

- Projects
- Management

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/translation-project-management/)
- [Postman Collection](collections/simplelocalize.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/simplelocalize.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SimpleLocalize Customer API

The SimpleLocalize Customer API enables creation and management of customer-specific translations. Customers represent end-user segments with their own translation overrides, identified by a unique customer key.

- **Human URL:** [https://simplelocalize.io/docs/api/customer-specific-api/](https://simplelocalize.io/docs/api/customer-specific-api/)
- **Base URL:** `https://api.simplelocalize.io`

#### Tags

- Customers
- Localization

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/customer-specific-api/)
- [Postman Collection](collections/simplelocalize.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/simplelocalize.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/simplelocalize)
- [Website](https://simplelocalize.io/)
- [Documentation](https://simplelocalize.io/docs/)
- [Pricing](https://simplelocalize.io/pricing/)
- [Blog](https://simplelocalize.io/blog/)
- [Git Hub Org](https://github.com/simplelocalize)
- [C L I](https://github.com/simplelocalize/simplelocalize-cli)
- [Github Action](https://github.com/simplelocalize/github-action-cli)
- [V S Code Extension](https://github.com/simplelocalize/vscode-simplelocalize)
- [M C P](https://github.com/simplelocalize/simplelocalize-mcp-server)
- [SDK](https://github.com/simplelocalize/simplelocalize-cli-npm)
- [Terms of Service](https://simplelocalize.io/terms-of-service/)
- [Privacy Policy](https://simplelocalize.io/privacy-policy/)
- [Integrations](https://simplelocalize.io/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
