# Vrije Universiteit Amsterdam (vrije-universiteit-amsterdam)

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

Vrije Universiteit Amsterdam (VU Amsterdam) is a public research university in the Netherlands, ranked #221 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an [APIs.json](http://apisjson.org) profile for the API Evangelist network. VU Amsterdam has no centralized public developer portal; its verifiable programmatic surface is concentrated in research infrastructure — the Elsevier Pure VU Research Portal (OAI-PMH + gated REST web service) and research data shared through DataverseNL.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/vrije-universiteit-amsterdam/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=vrije-universiteit-amsterdam-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Netherlands, Research, Open Data, Repository

## APIs

- **VU Research Portal OAI-PMH** — Live OAI-PMH 2.0 harvesting endpoint for the VU Amsterdam Repository (Elsevier Pure). Base: `https://research.vu.nl/ws/oai`. Docs: https://helpcenter.pure.elsevier.com/en_US/data-sources-and-integrations/what-is-the-oai-base-url
- **VU Research Portal Pure Web Service (REST)** — Elsevier Pure REST web service at `research.vu.nl/ws/api`; present but gated/authenticated (HTTP 302). Docs: https://helpcenter.pure.elsevier.com/web-service/harvesting-content-from-the-pure-web-services-changes
- **VU Amsterdam research data on DataverseNL** — Datasets published via DataverseNL, which exposes documented Native/Search REST APIs. Collection: https://dataverse.nl/dataverse/vuamsterdam — Docs: https://guides.dataverse.org/en/latest/api/

## Plans

- [plans/vrije-universiteit-amsterdam-plans-pricing.yml](plans/vrije-universiteit-amsterdam-plans-pricing.yml)

## Rate Limits

- [rate-limits/vrije-universiteit-amsterdam-rate-limits.yml](rate-limits/vrije-universiteit-amsterdam-rate-limits.yml)

## FinOps

- [finops/vrije-universiteit-amsterdam-finops.yml](finops/vrije-universiteit-amsterdam-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://vu.nl/en
- GitHub (official org): https://github.com/Vrije-Universiteit-Amsterdam
- Source Code (University Library): https://github.com/ubvu
- LinkedIn: https://www.linkedin.com/school/vrije-universiteit-amsterdam/
- Twitter/X: https://twitter.com/VUamsterdam

## Notes

- No public, centralized API developer portal was found for VU Amsterdam.
- The OAI-PMH endpoint was verified live (HTTP 200, valid Identify XML naming the "Vrije Universiteit Amsterdam Repository").
- The Pure REST web service base responds with HTTP 302 — it exists but requires authentication/an API key; it is not a fully open public API.
- DataverseNL is a shared national service; the REST API is provided by the Dataverse software, not a VU-specific endpoint.
- The official GitHub org shows no public repositories; the ubvu (University Library) org is the active open-source presence (~86 public repos).
- No course/timetable/SIS or public identity (SSO/OAuth) API was found in public sources. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
