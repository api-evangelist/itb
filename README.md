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

Institut Teknologi Bandung (ITB) is a public technical university in Bandung, Indonesia. This repository catalogs ITB's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile. ITB publishes no developer portal, no API gateway and no specification of any kind. Its verifiable institution-operated machine-readable surfaces are two protocol endpoints with no contract behind them — Apereo CAS ticket validation at `login.itb.ac.id` and a live OAI-PMH 2.0 data provider at `journals.itb.ac.id` — plus registry memberships in Crossref and ROR.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/itb/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=itb-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Institute of Technology, Research, Indonesia, Southeast Asia, Authentication, Single Sign-On, Scholarly Publishing, OAI-PMH, Digital Library, Research Repository

## APIs

Every entry carries an `x-operator` recording **who runs the thing it describes**, which for a university is rarely the same answer as who the data belongs to.

- **ITB Single Sign-On (CAS)** — `x-operator: institution`. Campus-wide single sign-on built on the Apereo CAS protocol; `/cas/p3/serviceValidate` returns machine-readable `cas:serviceResponse` XML. Docs: https://login.itb.ac.id/
- **ITB Journals OAI-PMH** — `x-operator: institution`. Live, unauthenticated OAI-PMH 2.0 data provider across 20 journal sets, on ITB's own host and administered by ITB (`journal@itb.ac.id`). The software is Open Journal Systems 3.2.1.0 from the Public Knowledge Project, so PKP's generic OJS contract is deliberately **not** attributed to ITB. Base URL: https://journals.itb.ac.id/index.php/index/oai
- **Crossref Membership (LPPM ITB)** — `x-operator: registry`. Member 3613, DOI prefix 10.5614, 6,568 DOIs. A membership fact about ITB, not an ITB-operated API.
- **ROR Registration** — `x-operator: registry`. https://ror.org/00apj8t60

## Plans

- [plans/itb-plans-pricing.yml](plans/itb-plans-pricing.yml)

## Rate Limits

- [rate-limits/itb-rate-limits.yml](rate-limits/itb-rate-limits.yml)

## FinOps

- [finops/itb-finops.yml](finops/itb-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://itb.ac.id/
- LinkedIn: https://www.linkedin.com/school/institut-teknologi-bandung/
- Authentication: https://login.itb.ac.id/
- Research Repository: https://digilib.itb.ac.id/
- GitHub Organization: https://github.com/STEI-ITB
- Blog: https://itb.ac.id/berita
- Conformance: [conformance/itb-conformance.yml](conformance/itb-conformance.yml)
- Plans: [plans/itb-plans-pricing.yml](plans/itb-plans-pricing.yml)
- Rate Limits: [rate-limits/itb-rate-limits.yml](rate-limits/itb-rate-limits.yml)
- FinOps: [finops/itb-finops.yml](finops/itb-finops.yml)
- Review: [review.yml](review.yml)

## Notes

- ITB publishes **no developer portal, no API gateway, no OpenAPI/AsyncAPI/apis.json, no `llms.txt` and no API terms of service**. `api.itb.ac.id` and `data.itb.ac.id` do not resolve; no open-data portal (CKAN, Socrata or otherwise) was found.
- The CAS SSO ticket-validation endpoints resolve and return CAS XML, but service registration and account provisioning are restricted to ITB-affiliated applications, and no specification is published for the surface.
- `journals.itb.ac.id` exposes a **live OAI-PMH 2.0 data provider** (`verb=Identify` and `verb=ListSets` both 200; 20 sets). This surface was not in the June 2026 profile. The co-located OJS REST API is credential-gated (403).
- **No SAML or Shibboleth federation surface exists.** `shibboleth.itb.ac.id` resolves in DNS but accepts no connection, and the CAS server 404s on both `/cas/idp/metadata` and OIDC discovery.
- ITB has **no DataCite** provider or repository account (`api.datacite.org` returns 0 records); its DOI registration runs through Crossref.
- The Ganesha Digital Library (GDL) repository is publicly browseable, but its previously documented OAI-PMH endpoint (`OAI-v2-script.php`) and RSS feed (`gdl.xml`) still return 404 after a platform migration.
- `lib.itb.ac.id` has degraded from HTTP 200 at the June 2026 review to **HTTP 500 "Database Error"** and is no longer emitted as a pointer.
- **No CNAME tenancy** was found on any ITB host — `journals`, `login` and `digilib` are plain A records, so no vendor platform is hiding behind an institution hostname.
- There is no central official ITB GitHub organization — only faculty and student orgs, of which `STEI-ITB` (School of Electrical Engineering and Informatics, 12 public repos, last push 2022) is the verifiable faculty one.
- All entries reflect only surfaces verified live as of 2026-09-01. No endpoints were fabricated and no vendor contract was saved under ITB's name.

## Maintainers

- Kin Lane — kin@apievangelist.com
