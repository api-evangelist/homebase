# Homebase (homebase)

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

Homebase is an all-in-one workforce management platform built for small businesses and hourly teams. Founded in 2014 and headquartered in San Francisco, California, Homebase provides employee scheduling, time tracking, payroll, team communication, and HR tools that help small business owners manage their teams efficiently. The platform serves over 100,000 businesses across restaurants, retail, and service industries. Homebase offers a REST API enabling developers and integration partners to access scheduling, time tracking, and workforce data programmatically.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/homebase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/homebase/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=homebase-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=homebase-api-evangelist&utm_content=repo)

## Tags

scheduling, time-tracking, payroll, HR, workforce-management, team-communication, employee-scheduling, small-business, hourly-workers, integrations

## APIs

### Homebase API

The Homebase REST API provides programmatic access to employee scheduling, time tracking, payroll synchronization, and team management features. Authenticated via API key, it enables third-party developers and partners to build custom integrations with the Homebase workforce management platform.

- **Documentation:** [https://app.joinhomebase.com/api-docs](https://app.joinhomebase.com/api-docs)
- **Base URL:** https://app.joinhomebase.com/api/public

## Plans / Rate Limits / FinOps

- **Plans and Pricing:** [plans/homebase-plans-pricing.yml](plans/homebase-plans-pricing.yml) — Four tiers: Basic (free), Essentials ($24.95/location/month), Plus ($59.95/location/month), and All-in-One ($99.95/location/month), with a 20% annual billing discount and optional payroll and add-on services.
- **Rate Limits:** [rate-limits/homebase-rate-limits.yml](rate-limits/homebase-rate-limits.yml) — Rate limits are enforced per API key; specific thresholds are not publicly disclosed. Implement exponential backoff on HTTP 429 responses.
- **FinOps:** [finops/homebase-finops.yml](finops/homebase-finops.yml) — FOCUS-aligned cost framework covering per-location subscription costs, payroll per-employee charges, and add-on service optimization strategies.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Property | URL |
|---|---|
| Website | https://www.joinhomebase.com/ |
| Documentation | https://app.joinhomebase.com/api-docs |
| LinkedIn | https://www.linkedin.com/company/homebase-app |
| Blog | https://www.joinhomebase.com/blog/ |
| Pricing | https://www.joinhomebase.com/pricing |
| Status Page | https://status.joinhomebase.com/ |
| X (Twitter) | https://x.com/joinhomebase |
| Support | https://support.joinhomebase.com/s/ |
| Integrations | https://www.joinhomebase.com/integrations |

## Maintainers

**Kin Lane** — kin@apievangelist.com
