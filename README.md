# Homebase (homebase)

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
