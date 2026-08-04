# Microsoft NuGet (microsoft-nuget)

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

NuGet is the package manager for .NET, hosted by Microsoft. It provides APIs for searching, downloading, publishing, and managing .NET packages through the NuGet Gallery and private feeds.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-nuget/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-nuget/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- .NET
- Microsoft
- NuGet
- Package Management

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### NuGet Server API

The NuGet Server API (v3) provides RESTful access to the NuGet package registry. Developers can search packages, download package content, retrieve package metadata and versions, push new packages, and manage package listings. The API uses a service index pattern for resource discovery and supports both nuget.org and private feeds.

- **Human URL:** [https://learn.microsoft.com/en-us/nuget/api/overview](https://learn.microsoft.com/en-us/nuget/api/overview)
- **Base URL:** `https://api.nuget.org/v3/`

#### Tags

- .NET
- NuGet
- Package Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/nuget/api/overview)
- [Reference](https://learn.microsoft.com/en-us/nuget/api/search-query-service-resource)
- [OpenAPI](openapi/microsoft-nuget-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-nuget.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-nuget.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.nuget.org/)
- [Website](https://www.nuget.org/)
- [GitHub Organization](https://github.com/NuGet)
- [Documentation](https://learn.microsoft.com/en-us/nuget/)
- [Getting Started](https://learn.microsoft.com/en-us/nuget/quickstart/install-and-use-a-package-in-visual-studio)
- [Terms of Service](https://www.nuget.org/policies/Terms)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Support](https://support.microsoft.com/)
- [Status Page](https://status.nuget.org/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
