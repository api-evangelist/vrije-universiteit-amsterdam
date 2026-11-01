# Vrije Universiteit Amsterdam

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

Vrije Universiteit Amsterdam (VU Amsterdam) is a public research university in the Netherlands, founded in 1880 and ranked #221 in the QS World University Rankings 2025. It operates no public developer program, no API portal, and no first-party API contract: every OpenAPI previously attributed to VU in this repository was Elsevier's Pure API v5.34.3 (contact pure-support@elsevier.com), the same product contract at least nine other universities ship, and it has been removed. What VU genuinely operates and publishes machine-readably is two protocol surfaces on its own domain — a live OAI-PMH 2.0 repository interface at research.vu.nl/ws/oai serving OpenAIRE CERIF and Dublin Core, administered by the University Library, and a signed SAML 2.0 identity-provider metadata document at stsfed.login.vu.nl published into the SURFconext national federation and onward to eduGAIN. Everything else programmable under a vu.nl subdomain is a vendor product VU is the tenant of: the Elsevier Pure REST web service, VU Yoda (Utrecht University software maintained by SURF for VU), Instructure Canvas, and Semestry MyTimetable — all credential-gated. Research data is also published to the national DataverseNL service. The University Library GitHub organisation (ubvu) is the institution's active open-source presence with 90 public repositories; the official VU GitHub organisation has none.

**Areas:** University · Higher Education · Education · Netherlands · Europe · Research · Research Data · Research Repository · Identity Federation · OAI-PMH · Open Access · Public Research University

## Vrije Universiteit Amsterdam on APIs.io

Everything profiled for Vrije Universiteit Amsterdam is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vrije-universiteit-amsterdam/](https://apis.io/providers/vrije-universiteit-amsterdam/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [VU Research Portal OAI-PMH](https://apis.io/apis/vrije-universiteit-amsterdam/research-portal-oai/) — OAI-PMH 2.0 metadata harvesting interface for the Vrije Universiteit Amsterdam Repository, served from the institution's own domain and administered by the…
- [VU Amsterdam SAML 2.0 identity provider (SURFconext / eduGAIN)](https://apis.io/apis/vrije-universiteit-amsterdam/identity-federation/) — Vrije Universiteit Amsterdam operates its own SAML 2.0 identity provider on Microsoft ADFS and publishes signed, machine-readable federation metadata for…
- [Elsevier Pure REST web service — VU Amsterdam deployment](https://apis.io/apis/vrije-universiteit-amsterdam/pure-web-service-deployment/) — VU Amsterdam's tenancy of the Elsevier Pure research information system, reachable at research.vu.nl/ws/api and API-key gated (GET /524/persons returns HTTP…
- [VU Yoda research data repository](https://apis.io/apis/vrije-universiteit-amsterdam/yoda/) — VU Amsterdam's research data management and publication platform, running at portal.yoda.vu.nl. Yoda is open-source iRODS-based software built by Utrecht…
- [VU Amsterdam collection on DataverseNL](https://apis.io/apis/vrije-universiteit-amsterdam/dataverse-nl/) — Vrije Universiteit Amsterdam publishes research datasets into DataverseNL, the shared national Dataverse service, under the collection…
- [VU Amsterdam Canvas LMS API](https://apis.io/apis/vrije-universiteit-amsterdam/canvas/) — Instructure Canvas deployed for VU Amsterdam at canvas.vu.nl. The Canvas REST API is live and credential-gated — GET /api/v1/accounts returns HTTP 401 with…
- [VU Amsterdam timetable (MyTimetable)](https://apis.io/apis/vrije-universiteit-amsterdam/timetable/) — VU Amsterdam's class timetable at rooster.vu.nl, running Semestry MyTimetable (the vendor is named in an HTML comment in the served page). A JSON REST API…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [VU Amsterdam Research (Pure) Vocabulary](https://apis.io/vocabularies/vrije-universiteit-amsterdam/vrije-universiteit-amsterdam-vocabulary/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Vrije Universiteit Amsterdam Domain Security](https://apis.io/security/vrije-universiteit-amsterdam/vrije-universiteit-amsterdam-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Vrije Universiteit Amsterdam Plans Pricing](https://apis.io/plans/vrije-universiteit-amsterdam/vrije-universiteit-amsterdam-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Vrije Universiteit Amsterdam Rate Limits](https://apis.io/rate-limits/vrije-universiteit-amsterdam/vrije-universiteit-amsterdam-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Vrije Universiteit Amsterdam Finops](https://apis.io/finops/vrije-universiteit-amsterdam/vrije-universiteit-amsterdam-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://vu.nl/en)
- [Documentation](https://rdm.vu.nl/)
- [Support](https://vu.nl/en/about-vu/more-about/contact)
- [Blog](https://vu.nl/en/news)
- [Terms of service](https://vu.nl/en/about-vu/more-about/disclaimer)
- [Privacy policy](https://vu.nl/en/about-vu/more-about/privacy-statement-vrije-universiteit-amsterdam)
- [GitHub](https://github.com/ubvu)

## API Evangelist rating

**Kin Score 21.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 4.4 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vrije-universiteit-amsterdam/](https://apis.io/providers/vrije-universiteit-amsterdam/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vrije Universiteit Amsterdam: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vrije-universiteit-amsterdam/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
