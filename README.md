# Webflow API and Documentation (webflow-api-and-documentation-webflow)

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

Webflow provides a visual web development platform with a comprehensive REST API for programmatically managing sites, CMS collections, ecommerce, assets, users, and forms. The Webflow Data API v2 enables developers to build integrations, automate content workflows, and extend Webflow's core functionality. All V2 API endpoints start with https://api.webflow.com/v2 and support OAuth 2.0 and API key authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- CMS
- Content Management
- Ecommerce
- No-Code
- Publishing
- Web Development

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Webflow Data API

The Webflow Data API is a comprehensive RESTful API providing programmatic access to Webflow sites, workspaces, CMS collections and items, ecommerce products and orders, assets, users, forms, and webhooks. All V2 endpoints use https://api.webflow.com/v2 as the base URL and require OAuth 2.0 or API key authentication.

- **Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags

- CMS
- Content Management
- Ecommerce
- REST
- Sites

#### Properties

- [Documentation](https://developers.webflow.com/data/reference/rest-introduction)
- [OpenAPI](openapi/webflow-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/webflow-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webflow-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.webflow.com/data/reference/authentication)
- [Rate Limits](https://developers.webflow.com/data/reference/rate-limits)
- [Changelog](https://developers.webflow.com/data/v2.0.0/changelog)
- [JSON Schema](json-schema/webflow-site-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/webflow-collection-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/webflow-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/webflow-webhook-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Webflow Sites API

Site management endpoints for creating, updating, publishing, and deleting Webflow sites, plus managing custom domains, redirects, robots.txt, and site activity logs.

- **Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags

- Domains
- Publishing
- Sites

#### Properties

- [Documentation](https://developers.webflow.com/data/reference/rest-introduction)
- [OpenAPI](openapi/webflow-sites-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/webflow-sites.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webflow-sites.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webflow Collections API

CMS collection management endpoints for creating, listing, and deleting collections, and managing collection field configurations.

- **Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags

- CMS
- Collections
- Fields

#### Properties

- [Documentation](https://developers.webflow.com/data/reference/rest-introduction)
- [OpenAPI](openapi/webflow-collections-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/webflow-collections.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webflow-collections.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webflow CMS Items API

CMS item endpoints for creating, reading, updating, deleting, and publishing collection items, including support for bulk operations and live/staged item management.

- **Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags

- CMS
- Content Management
- Items

#### Properties

- [Documentation](https://developers.webflow.com/data/reference/rest-introduction)
- [OpenAPI](openapi/webflow-items-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/webflow-items.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webflow-items.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webflow Webhooks API

Webhook registration and management endpoints for receiving real-time event notifications from Webflow sites including form submissions, ecommerce events, and CMS changes.

- **Human URL:** [https://developers.webflow.com/data/reference/rest-introduction](https://developers.webflow.com/data/reference/rest-introduction)

#### Tags

- Events
- Notifications
- Webhooks

#### Properties

- [Documentation](https://developers.webflow.com/data/reference/rest-introduction)
- [OpenAPI](openapi/webflow-webhooks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/webflow-webhooks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/webflow-webhooks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/webflow-inc-)
- [Portal](https://developers.webflow.com/)
- [Getting Started](https://developers.webflow.com/data/reference/rest-introduction/quick-start)
- [Authentication](https://developers.webflow.com/data/reference/authentication)
- [Rate Limits](https://developers.webflow.com/data/reference/rate-limits)
- [Changelog](https://developers.webflow.com/data/v2.0.0/changelog)
- [SDK](https://developers.webflow.com/data/reference/sdks)
- [Website](https://webflow.com/)
- [Blog](https://webflow.com/blog)
- [Support](https://help.webflow.com/)
- [Community](https://forum.webflow.com/)
- [Academy](https://university.webflow.com/)
- [GitHub Organization](https://github.com/webflow)
- [Terms of Service](https://webflow.com/legal/terms)
- [Privacy Policy](https://webflow.com/legal/privacy)
- [Status Page](https://status.webflow.com/)
- [Marketplace](https://webflow.com/marketplace)
- [Spectral Rules](rules/webflow-spectral-rules.yml)
- [Vocabulary](vocabulary/webflow-api-and-documentation-webflow-vocabulary.yml)
- [JSON-LD](json-ld/webflow-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://webflow.com/integrations)
- [L L Ms Txt](https://webflow.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
