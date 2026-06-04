# Tel Aviv University (tel-aviv-university)

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
