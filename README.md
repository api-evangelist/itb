# Bandung Institute of Technology (itb)

Institut Teknologi Bandung (ITB) is a public research university in Bandung, Indonesia, ranked #256 in the QS World University Rankings 2025. This repository catalogs ITB's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. ITB does not publish a dedicated developer portal or documented public API program; its verifiable machine-readable surfaces are limited to a CAS-based single sign-on service and an institutional digital library.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/itb/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=itb-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Indonesia, Authentication, Digital Library

## APIs

- **ITB Single Sign-On (CAS)** — Campus-wide single sign-on built on the Apereo CAS protocol. Docs: https://login.itb.ac.id/
- **ITB Digital Library (Ganesha Digital Library)** — Institutional repository of theses, dissertations, and research on the GDL platform; historical OAI-PMH/RSS endpoints no longer resolve. Docs: https://lib.itb.ac.id/en/digilib/

## Plans

- [plans/itb-plans-pricing.yml](plans/itb-plans-pricing.yml)

## Rate Limits

- [rate-limits/itb-rate-limits.yml](rate-limits/itb-rate-limits.yml)

## FinOps

- [finops/itb-finops.yml](finops/itb-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://itb.ac.id/
- LinkedIn: https://www.linkedin.com/school/institut-teknologi-bandung/
- Authentication: https://login.itb.ac.id/
- Plans: [plans/itb-plans-pricing.yml](plans/itb-plans-pricing.yml)
- Rate Limits: [rate-limits/itb-rate-limits.yml](rate-limits/itb-rate-limits.yml)
- FinOps: [finops/itb-finops.yml](finops/itb-finops.yml)
- Review: [review.yml](review.yml)

## Notes

- No public developer portal or documented API program was found for ITB.
- The CAS SSO login endpoint (https://login.itb.ac.id/cas/login) resolves (HTTP 200), but service registration and account provisioning are restricted to ITB-affiliated applications.
- The Ganesha Digital Library (GDL) repository is publicly browseable, but its previously documented OAI-PMH endpoint (`OAI-v2-script.php`) and RSS feed (`gdl.xml`) now return HTTP 404 after a platform migration; no current harvesting endpoint could be confirmed.
- There is no central official ITB GitHub organization — only student- and department-run orgs (e.g., STEI-ITB, HMIF ITB, GDSC ITB, PPTIK).
- `api.itb.ac.id` and `data.itb.ac.id` do not resolve; no open-data portal was found.
- All entries reflect only surfaces verified live as of 2026-06-03. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
