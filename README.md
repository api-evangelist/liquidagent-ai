# Liquid Agent

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

Liquid Agent is an agent-native money layer on Base: a USDC account for people (yield, payments and stocks from one balance, through the app) and, for AI agents, a permissionless HTTP API at api.liquidagent.ai that mints a self-custodied ERC-4626 vault holding Coinbase's tokenized NVDA, META, AAPL and GOOGL, buys in from $1, sets custom weights, rebalances and exits to USDC or in-kind any block. Reads are free and need no key; every write returns unsigned calldata the agent signs with its own wallet. Three paid surfaces settle per call in USDC over x402 v2: basket rebalancing signals ($0.04), a shareable portfolio page ($0.25) and an ERC-4337 / ERC-7677 gas sponsor (from $0.03) on Base, Polygon and Solana. The contract is a 17-operation OpenAPI 3.1.0 at api.liquidagent.ai/openapi.json, with an A2A agent card, llms.txt, agents.txt, an x402 resource catalog, an ERC-8004 on-chain identity and two provider-authored Agent Skills in the open-source examples repo.

**Areas:** Tokenized Stocks · DeFi · Investing · Agentic Commerce · x402 · Stablecoins · Account Abstraction · Gas Sponsorship · Base · Solana · AI Agents · Agent-Native

## Liquid Agent on APIs.io

Everything profiled for Liquid Agent is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/liquidagent-ai/](https://apis.io/providers/liquidagent-ai/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Liquid Agent Liquid Agent API](https://apis.io/apis/liquidagent-ai/liquidagent-ai-liquid-agent-api/) — The Liquid Agent API from Liquid Agent — 15 operation(s) for liquid agent.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [liquidagent-ai](https://apis.io/servers/liquidagent-ai/liquidagent-ai/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Liquidagent Ai Agentic Access](https://apis.io/agentic-access/liquidagent-ai/liquidagent-ai-agentic-access/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Liquidagent Ai Openapi Overlay](https://apis.io/overlays/liquidagent-ai/liquidagent-ai-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Liquidagent Ai Authentication](https://apis.io/security/liquidagent-ai/liquidagent-ai-authentication/)
- [Liquidagent Ai Domain Security](https://apis.io/security/liquidagent-ai/liquidagent-ai-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Liquidagent Ai Plans Pricing](https://apis.io/plans/liquidagent-ai/liquidagent-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Liquidagent Ai Rate Limits](https://apis.io/rate-limits/liquidagent-ai/liquidagent-ai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://liquidagent.ai/)
- [Pricing](https://api.liquidagent.ai/.well-known/x402-resources)
- [GitHub](https://github.com/LiquidAgent)
- [Status](https://api.liquidagent.ai/v1/status)

## API Evangelist rating

**Kin Score 43.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 54.8 |
| Contract governance | 18.2 |
| Operational transparency | 21.1 |
| Developer ergonomics | 47.6 |
| Access clarity | 42.1 |

**Agent readiness 30.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | flavored (partial credit) |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/liquidagent-ai/](https://apis.io/providers/liquidagent-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Liquid Agent: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/liquidagent-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
