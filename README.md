# State Employees' Credit Union (state-employees-credit-union)

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

State Employees' Credit Union (SECU / NCSECU) is a member-owned, not-for-profit financial cooperative headquartered in Raleigh, North Carolina. Founded in 1937, it is a state-chartered credit union regulated by the Credit Union Division of the North Carolina Department of Commerce and federally insured by the NCUA (NMLS #430055). SECU is the second-largest natural-person credit union in the United States, serving nearly 2.9 million member-owners with roughly $56 billion in assets across 275 branches in all 100 North Carolina counties.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/state-employees-credit-union/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/state-employees-credit-union/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Credit Union
- United States
- North Carolina
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## Open-Finance & API Posture

SECU exposes **no public first-party developer API**. Probes of `developer.ncsecu.org` and `developers.ncsecu.org` do not resolve, and `api.ncsecu.org` returns HTTP 403 (a gated, undocumented backend, not a public product). No developer/API page, and no downloadable OpenAPI or Swagger definition, is published on ncsecu.org.

Consumer digital banking (Member Access) lets members **connect external accounts** for a 360-degree financial view — i.e. SECU acts as a data *recipient* for aggregation — and outbound consumer-permissioned data sharing is handled through third-party **data aggregators** (the common, non-mandated US pattern) rather than a documented first-party API surface.

There is **no publicly documented FDX-conformant data-access endpoint** and **no published CFPB Section 1033 data-rights posture** as of July 2026. (An FDX membership claim circulates in a member-support forum thread but is not confirmed by an authoritative SECU or FDX source, so it is not recorded here.)

This is therefore an **identity-only** record: no `apis[]` entries, because there is genuinely no public API to document.

## APIs

None. SECU publishes no public developer API. See the open-finance posture above.

## Common Properties

- [Website](https://www.ncsecu.org/)
- [About Us](https://www.ncsecu.org/about-us)
- [Online Services](https://www.ncsecu.org/services/online)
- [Terms of Use](https://www.ncsecu.org/pdfs/privacy-and-legal/SECUTermsOfUse.pdf)
- [Privacy Notice](https://onlineaccess.ncsecu.org/O/SECUContent/PDF/SECUPrivacyNotice_English.pdf)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
