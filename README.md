# Tel Aviv University (tel-aviv-university)

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

Tel Aviv University (TAU) is Israel's largest public research university, ranked #209 in the QS World University Rankings 2025. This repository catalogs TAU's public developer/API footprint as an [APIs.json](https://apisjson.org) provider profile. TAU publishes no centralized public developer portal; its confirmed machine-accessible surface is limited to standard third-party platform endpoints (ExLibris Primo/Alma) plus unofficial community tooling.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/tel-aviv-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tel-aviv-university-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Israel, Library, Discovery, Research

## APIs

- **TAU Libraries Primo Discovery (DaTA Search)** — ExLibris Primo discovery (institution code 972TAU_INST:TAU); standard Primo Search REST API behind it. Docs: https://developers.exlibrisgroup.com/primo/apis/ — Discovery: https://tau.primo.exlibrisgroup.com/discovery/search?vid=972TAU_INST:TAU&lang=en
- **TAU Libraries Alma / OAI-PMH Metadata Harvesting** — Alma-backed library platform exposing standard OAI-PMH and Alma REST APIs (institution-provisioned). Docs: https://developers.exlibrisgroup.com/alma/integrations/oai/
- **Unofficial tau-tools (Moodle / IMS / course data)** — community/student wrapper of TAU Moodle, IMS grade system, and course/plan data. Not official. Docs: https://github.com/arazimproject/tau-tools

## Plans

- [plans/tel-aviv-university-plans-pricing.yml](plans/tel-aviv-university-plans-pricing.yml)

## Rate Limits

- [rate-limits/tel-aviv-university-rate-limits.yml](rate-limits/tel-aviv-university-rate-limits.yml)

## FinOps

- [finops/tel-aviv-university-finops.yml](finops/tel-aviv-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://english.tau.ac.il/
- GitHub: https://github.com/arazimproject
- LinkedIn: https://il.linkedin.com/school/tel-aviv-university/
- Twitter/X: https://x.com/telavivuni
- Review: [review.yml](review.yml)

## Notes

All cataloged URLs were probed live on 2026-06-03. No TAU-specific public developer portal or open-data API program was found. The Primo/Alma APIs are platform-standard (ExLibris) and require institution-provisioned API keys — they are documented by ExLibris, not by TAU. The `tau-tools` library is unofficial third-party/community tooling and may break or conflict with TAU terms of use. No endpoints were fabricated; absence of a public API is reported honestly.

## Maintainers

- Kin Lane — kin@apievangelist.com
