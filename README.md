# Bridgit (bridgit)

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

Bridgit is a Kitchener, Ontario-based construction technology company founded in 2012 by Mallorie Brodie and Lauren Lake. Its flagship product is Bridgit Bench, an AI-first workforce planning platform built exclusively for construction general contractors and subcontractors. Bench centralizes project staffing, role assignments, forecasting, utilization, time-off, internal resumes, and certifications, replacing the spreadsheets most contractors still use to plan their people across pursuits and active projects. Bridgit is trusted by nearly 40% of the ENR 400 and serves customers across North America, the United Kingdom, Australia, and New Zealand. The company has raised over $35M USD from investors including Autodesk, Salesforce Ventures, Sands Capital, BDC Capital, and Camber Creek. Bridgit Bench exposes a documented REST API (OpenAPI 3.0) for managing accounts, projects, people, roles, allocations, certifications, and groupings, and ships pre-built integrations across CRM (Salesforce, HubSpot, Microsoft Dynamics, Unanet, Zoho, Pipedrive), HRIS/ERP (Workday, BambooHR, UKG, Oracle, ADP, Namely), project management (Procore, Autodesk Build, CMiC, Trimble), and data warehouses (Snowflake, Office 365).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bridgit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bridgit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Construction
- Construction Technology
- Workforce Planning
- Workforce Management
- Resource Planning
- Project Staffing
- General Contractors
- Subcontractors
- Forecasting
- Utilization
- Certifications
- AEC
- SaaS

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Bridgit Bench API

The Bridgit Bench REST API lets developers build custom integrations against the Bench workforce planning platform — managing accounts, projects, people, roles, allocations (including hourly), phases, certifications, person and project custom fields, groupings, notes, tasks, attachments, workforce spend reports, and user/service-account administration. Authentication uses OAuth bearer tokens issued by POST /auth/signin against a service account; refresh tokens may be exchanged at POST /auth/token. All resource paths live under https://bench.gobridgit.com/rp/api/v1/.

- **Human URL:** [https://gobridgit.com/bridgit-bench-api-documentation/](https://gobridgit.com/bridgit-bench-api-documentation/)
- **Base URL:** `https://bench.gobridgit.com/rp/api/v1`

#### Tags

- Workforce Planning
- Projects
- People
- Roles
- Allocations
- Certifications
- Construction

#### Properties

- [Documentation](https://gobridgit.com/bridgit-bench-api-documentation/)
- [Swagger](https://bench.gobridgit.com/rp/swagger/index.html)
- [OpenAPI](openapi/bridgit-bench-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bridgit-bench.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bridgit-bench.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://gobridgit.com/bridgit-bench-api-documentation/)

## Common Properties

- [Website](https://gobridgit.com)
- [Product](https://gobridgit.com/bridgit-bench/)
- [General Contractors](https://gobridgit.com/general-contractors/)
- [Subcontractors](https://gobridgit.com/subcontractors/)
- [Integrations](https://gobridgit.com/integrations/)
- [Documentation](https://gobridgit.com/bridgit-bench-api-documentation/)
- [Swagger](https://bench.gobridgit.com/rp/swagger/index.html)
- [Support](https://help.gobridgit.com)
- [Blog](https://gobridgit.com/blog/)
- [Customers](https://gobridgit.com/customers/)
- [About](https://gobridgit.com/about/)
- [Careers](https://gobridgit.com/careers/)
- [Contact](https://gobridgit.com/contact/)
- [Login](https://bench.gobridgit.com)
- [Git Hub](https://github.com/Bridgit)
- [LinkedIn](https://www.linkedin.com/company/bridgit)
- [Twitter](https://twitter.com/gobridgit)
- [YouTube](https://www.youtube.com/@Gobridgit)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
