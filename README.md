# Balancer (balancer)

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
