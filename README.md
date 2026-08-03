# Balancer (balancer)

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

Balancer is a DeFi AMM and programmable liquidity platform supporting weighted, stable, and custom pools (v2 and v3). Balancer publishes a public GraphQL API at `api-v3.balancer.fi` plus per-chain subgraphs. Smart-contract entry points (Vault and Router) are the primary write surface.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/balancer/refs/heads/main/apis.yml)

## Type
- **x-type:** protocol

## Tags
- Web3, DeFi, DEX, AMM, Liquidity, Multi-chain, GraphQL, Smart Order Router, Open Source

## APIs
- **Balancer GraphQL API** (`https://api-v3.balancer.fi/`) - public, GraphQL
- **Balancer Subgraph** (`https://api.thegraph.com/subgraphs/name/balancer-labs`) - per-chain
- **Balancer SOR SDK** (`https://github.com/balancer/b-sdk`) - client-side router
- **Balancer Smart Contracts** - Vault and Router on multiple chains

## Notes on OpenAPI
Balancer publishes a GraphQL schema rather than OpenAPI; introspection from the GraphQL endpoint is the canonical reference.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Portal](https://balancer.fi/)
- [Documentation](https://docs.balancer.fi/)
- [GitHub](https://github.com/balancer)
- [Forum](https://forum.balancer.fi/)
- [Plans](plans/balancer-plans-pricing.yml) - reconciled (open API + on-chain fee)
- [RateLimits](rate-limits/balancer-rate-limits.yml) - partially reconciled (fair-use)
- [FinOps](finops/balancer-finops.yml) - reconciled FOCUS-aligned

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
