# SimpleLocalize

SimpleLocalize is a web-based translation management platform that helps small and growing teams save time on handling localization files and translation strings. It provides a REST API for managing translations, languages, projects, and customers, along with integrations for CI/CD pipelines, frameworks, and AI-powered tools.

**URL:** [https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/simplelocalize/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-02

## APIs

### SimpleLocalize Translation API

The SimpleLocalize Translation API provides REST endpoints to create, read, update, and delete translations. It supports querying translations by key, language, namespace, text content, review status, and customer ID. The API also supports bulk import and export of translation files in 30+ formats including JSON, YAML, XLIFF, Android XML, iOS Strings, and more.

**Human URL:** https://simplelocalize.io/docs/api/get-started/
**Base URL:** https://api.simplelocalize.io

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/get-started/)
- [OpenAPI](https://api.simplelocalize.io/openapi/docs)
- [Swagger UI](https://api.simplelocalize.io/openapi/ui)
- [OpenAPI](openapi/simplelocalize-openapi.yml)

### SimpleLocalize Language API

The SimpleLocalize Language API provides endpoints to create, list, update, and delete languages within a project.

**Human URL:** https://simplelocalize.io/docs/api/language-api/

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/language-api/)

### SimpleLocalize Projects API

The SimpleLocalize Projects API allows creation and listing of translation projects using Personal Token authentication.

**Human URL:** https://simplelocalize.io/docs/api/translation-project-management/

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/translation-project-management/)

### SimpleLocalize Customer API

The SimpleLocalize Customer API enables creation and management of customer-specific translation segments for white-label and multi-tenant use cases.

**Human URL:** https://simplelocalize.io/docs/api/customer-specific-api/

#### Properties

- [Documentation](https://simplelocalize.io/docs/api/customer-specific-api/)

## OpenAPI Specifications

- [SimpleLocalize OpenAPI](openapi/simplelocalize-openapi.yml)

## Capabilities

- [Translation Management](capabilities/translation-management.yaml) - Unified translation management workflow combining translation CRUD, language management, project management, customer segmentation, and CDN publication

### Shared Definitions

- [SimpleLocalize](capabilities/shared/simplelocalize.yaml)

## Rules

- [SimpleLocalize Rules](rules/simplelocalize-rules.yml)

## JSON Schemas

- [Translation Schema](json-schema/simplelocalize-translation-schema.json)
- [Language Schema](json-schema/simplelocalize-language-schema.json)
- [Project Schema](json-schema/simplelocalize-project-schema.json)

## JSON Structures

- [Translation Structure](json-structure/simplelocalize-translation-structure.json)

## JSON-LD

- [SimpleLocalize Context](json-ld/simplelocalize-context.jsonld)

## Examples

- [List Translations](examples/simplelocalize-list-translations-example.json)
- [Create Translation](examples/simplelocalize-create-translation-example.json)

## Vocabulary

- [SimpleLocalize Vocabulary](vocabulary/simplelocalize-vocabulary.yml)

## Common Links

- **Website:** https://simplelocalize.io/
- **Documentation:** https://simplelocalize.io/docs/
- **Pricing:** https://simplelocalize.io/pricing/
- **Blog:** https://simplelocalize.io/blog/
- **GitHub:** https://github.com/simplelocalize
- **CLI:** https://github.com/simplelocalize/simplelocalize-cli
- **GitHub Action:** https://github.com/simplelocalize/github-action-cli
- **VS Code Extension:** https://github.com/simplelocalize/vscode-simplelocalize
- **MCP Server:** https://github.com/simplelocalize/simplelocalize-mcp-server
- **Terms of Service:** https://simplelocalize.io/terms-of-service/
- **Privacy Policy:** https://simplelocalize.io/privacy-policy/

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
