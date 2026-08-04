# SimpleLocalize (simplelocalize)

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
