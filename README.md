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

Vrije Universiteit Amsterdam (VU Amsterdam) is a public research university in the Netherlands, founded in 1880 and ranked #221 in the QS World University Rankings 2025. This repository catalogs the institution's public programmatic footprint as an [APIs.json](http://apisjson.org) profile for the API Evangelist network. VU operates no developer program and publishes no API contract of its own. It does operate two machine-readable protocol surfaces on its own domain — a live OAI-PMH 2.0 repository interface and a signed SAML 2.0 identity-provider metadata document in the SURFconext federation — and it is the tenant of several vendor platforms running under `vu.nl` subdomains.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/vrije-universiteit-amsterdam/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=vrije-universiteit-amsterdam-api-evangelist&utm_content=repo

## Type

- University (Public Research University)
- Index
- Consumer
- 3rd-Party

## Tags

University, Higher Education, Education, Netherlands, Europe, Research, Research Data, Research Repository, Identity Federation, OAI-PMH, Open Access, Public Research University

## Surfaces — and who actually operates them

Every surface below carries an operator. `institution` means VU runs the thing; `tenant` means VU is a customer of a platform someone else runs, under a VU subdomain. A tenancy is a real institutional fact and is recorded as one — but the contract belongs to the vendor, and is not stored here under VU's name.

**Institution-operated**

- **VU Research Portal OAI-PMH** — `https://research.vu.nl/ws/oai` — OAI-PMH 2.0, administered by the VU University Library (`pure.ub@vu.nl`). Fully harvestable: Identify, ListMetadataFormats, ListSets and a 108KB ListRecords pull of OpenAIRE CERIF person records all return 200. Serves `oai_dc` and `oai_cerif_openaire`.
- **VU Amsterdam SAML 2.0 identity provider** — `https://stsfed.login.vu.nl/adfs/ls/` — entityID `http://stsfed.login.vu.nl/adfs/services/trust`, signed metadata at `/FederationMetadata/2007-06/FederationMetadata.xml` (200, 116,822 bytes), carried in the SURFconext national IdP feed with `shibmd:Scope vu.nl` and republished to eduGAIN.

**Tenant deployments (vendor contracts, recorded but not stored here)**

- **Elsevier Pure REST web service** — `https://research.vu.nl/ws/api` — Pure API v5.34.3, contact `pure-support@elsevier.com`. API-key gated (401).
- **VU Yoda** — `https://portal.yoda.vu.nl` — Utrecht University software, maintained by SURF for VU. WebDAV at `data.yoda.vu.nl` (401); DataCite client `DELFT.VUDATA`, 171 DOIs.
- **DataverseNL** — `https://dataverse.nl/dataverse/vuamsterdam` — VU's collection on the shared national Dataverse service.
- **Canvas LMS** — `https://canvas.vu.nl/api/v1` — Instructure Canvas, live and credential-gated (401).
- **MyTimetable** — `https://rooster.vu.nl/api` — Semestry MyTimetable, live and credential-gated (401).

## Domain standard conformance (Kin Score `education` regime)

- [conformance/vrije-universiteit-amsterdam-conformance.yml](conformance/vrije-universiteit-amsterdam-conformance.yml)
- Conformant, with live evidence: **oai-pmh**, **saml**, **datacite**.
- Explicitly not claimed: `shibboleth` (VU runs ADFS, not Shibboleth), `orcid` (zero ORCID identifiers in VU's own CERIF output), `crossref`, `lti` (Canvas is LTI-certified by Instructure, not by VU), `scim`, `oneroster`, `ed-fi`, `caliper`, `qti`.

## Plans

- [plans/vrije-universiteit-amsterdam-plans-pricing.yml](plans/vrije-universiteit-amsterdam-plans-pricing.yml)

## Rate Limits

- [rate-limits/vrije-universiteit-amsterdam-rate-limits.yml](rate-limits/vrije-universiteit-amsterdam-rate-limits.yml)

## FinOps

- [finops/vrije-universiteit-amsterdam-finops.yml](finops/vrije-universiteit-amsterdam-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://vu.nl/en
- Research repository: https://research.vu.nl/
- Research data platform: https://portal.yoda.vu.nl
- Course catalog: https://studiegids.vu.nl/
- Identity federation: https://stsfed.login.vu.nl/FederationMetadata/2007-06/FederationMetadata.xml
- Research data documentation: https://rdm.vu.nl/
- AI policy: https://vu.nl/en/education/more-about/teaching-and-ai
- AI tooling: https://vu.nl/en/student/examinations/generative-ai-your-use-our-expectations
- GitHub (University Library): https://github.com/ubvu
- LinkedIn: https://www.linkedin.com/school/vrije-universiteit-amsterdam/
- Twitter/X: https://twitter.com/VUamsterdam

## Notes

- **96 files were removed on 2026-08-30.** The 26 OpenAPIs this repository held under VU's name were a single Elsevier Pure contract split per tag by our own refine step, plus 70 artifacts derived from it (collections, JSON Schema, JSON Structure, examples, JSON-LD, vocabulary, Spectral rules, authentication, agentic-access, capability edges). Nothing replaced them: VU authors no API contract, and this pipeline does not generate one on an institution's behalf.
- The June 2026 review concluded that no identity API was found. That was wrong — VU publishes signed SAML 2.0 IdP metadata, and it is one of only two genuinely first-party machine-readable surfaces the institution has.
- The official GitHub org (`Vrije-Universiteit-Amsterdam`) resolves but holds **zero** public repositories, confirmed via api.github.com; it is not listed as a pointer. The University Library org (`ubvu`) has 90 public repos and is the real code presence.
- No developer portal, no `llms.txt`, no `.well-known/security.txt` at any probed location.
- `dataverse.nl` and `publication.yoda.vu.nl` answer with an Anubis bot challenge (HTTP 200, interstitial body). `research.vu.nl` HTML pages sit behind a Cloudflare challenge (403) while its `/ws/` protocol endpoints stay open. Bot-blocked is a finding about the edge, not a gap in the institution.
- This profile is thin because a university is a federation of buyers, not a producer. It is a correct measurement, not a failed one — and a correct re-profile is expected to lower the score this repository previously earned on someone else's contract.

## Maintainers

- Kin Lane — kin@apievangelist.com
