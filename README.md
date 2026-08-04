# Bandung Institute of Technology (itb)

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
