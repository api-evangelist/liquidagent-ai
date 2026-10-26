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

Liquid Agent is an agent-native money layer on Base. For people it is a USDC account (yield, payments and stocks from one balance, through the app at liquidagent.ai); for AI agents it is a permissionless HTTP API at api.liquidagent.ai that mints a self-custodied ERC-4626 vault holding Coinbase's tokenized NVDA, META, AAPL and GOOGL, buys in from $1, sets custom weights, rebalances and exits to USDC or in-kind any block. Reads are free and need no key; every write returns unsigned calldata the agent signs with its own wallet. Three paid surfaces settle per call in USDC over x402 v2: basket rebalancing signals ($0.04), a shareable portfolio page ($0.25) and an ERC-4337 / ERC-7677 gas sponsor (from $0.03) on Base, Polygon and Solana.

## Public surface (as profiled 2026-09-19)

- Website: https://liquidagent.ai/ (Vercel-hosted single-page app; the human product)
- API host and documentation: https://api.liquidagent.ai (the guide at /v1/guide is the only human-readable reference; docs.liquidagent.ai is a dead deployment)
- OpenAPI 3.1.0, 17 operations: https://api.liquidagent.ai/openapi.json (saved to `openapi/`)
- A2A agent card: https://api.liquidagent.ai/.well-known/agent-card.json (saved and graded in `a2a/`)
- x402 discovery manifest and resource catalog: /.well-known/x402, /.well-known/x402-resources (saved in `well-known/`)
- ERC-8004 registration (agentId 74094 on Base): /.well-known/erc8004.json
- llms.txt and agents.txt: https://api.liquidagent.ai/llms.txt, /agents.txt
- Self-measured status endpoint: https://api.liquidagent.ai/v1/status
- Open-source examples, spec and two provider-authored Agent Skills (MIT): https://github.com/LiquidAgent/liquidagentx402

Not found: an MCP server, a client library in any registry, OAuth/OIDC discovery, security.txt, an API catalog, a changelog, rate-limit documentation, terms or privacy pages, a sandbox or testnet.
