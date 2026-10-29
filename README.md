# CoinGecko

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

CoinGecko is a cryptocurrency data aggregator providing market data, analytics, and information on thousands of crypto assets, exchanges, derivatives, NFTs, and on-chain decentralized markets worldwide. The CoinGecko Developer Platform exposes three primary APIs: the public Crypto Market Data API (Demo plan and free tier), the commercial Pro API for higher rate limits and exclusive endpoints, and the Onchain DEX API powered by GeckoTerminal for decentralized exchange data across 250+ networks. Authentication uses x-cg-demo-api-key (Demo) or x-cg-pro-api-key (Pro) headers, with rate limits ranging from 30 calls per minute on Demo to 1,000 calls per minute on top Pro tiers.

**Areas:** CoinGecko · Aggregator · Blockchain · Cryptocurrency · Decentralized Exchanges · DeFi · Decentralized Exchange · Liquidity Pools · Market Data · NFT · On-Chain Data · Prices

## CoinGecko on APIs.io

Everything profiled for CoinGecko is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/coingecko/](https://apis.io/providers/coingecko/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [CoinGecko Asset Platforms API](https://apis.io/apis/coingecko/coingecko-asset-platforms-api/) — List all asset platforms (blockchains) supported by CoinGecko.
- [CoinGecko Categories API](https://apis.io/apis/coingecko/coingecko-categories-api/) — List cryptocurrency categories and their market data.
- [CoinGecko Coins API](https://apis.io/apis/coingecko/coingecko-coins-api/) — Comprehensive coin data including current prices, market data, historical data, tickers, and OHLCV charts.
- [CoinGecko Companies API](https://apis.io/apis/coingecko/coingecko-companies-api/) — Public company cryptocurrency holdings data.
- [CoinGecko Contract API](https://apis.io/apis/coingecko/coingecko-contract-api/) — Query coin data by contract address on a specific asset platform.
- [CoinGecko Derivatives API](https://apis.io/apis/coingecko/coingecko-derivatives-api/) — Derivatives market data including tickers and exchange information.
- [CoinGecko DEXes API](https://apis.io/apis/coingecko/coingecko-dexes-api/) — List decentralized exchanges on specific networks.
- [CoinGecko Exchange Rates API](https://apis.io/apis/coingecko/coingecko-exchange-rates-api/) — BTC exchange rates against other currencies.
- [CoinGecko Exchanges API](https://apis.io/apis/coingecko/coingecko-exchanges-api/) — Exchange data including volumes, tickers, and status updates.
- [CoinGecko Global API](https://apis.io/apis/coingecko/coingecko-global-api/) — Global cryptocurrency and DeFi market data.
- [CoinGecko Networks API](https://apis.io/apis/coingecko/coingecko-networks-api/) — List and query supported blockchain networks.
- [CoinGecko OHLCV API](https://apis.io/apis/coingecko/coingecko-ohlcv-api/) — Open, High, Low, Close, Volume candlestick chart data for liquidity pools.
- [CoinGecko Ping API](https://apis.io/apis/coingecko/coingecko-ping-api/) — Check API server status
- [CoinGecko Pools API](https://apis.io/apis/coingecko/coingecko-pools-api/) — Query liquidity pool data including specific pools, top pools, new pools, and multi-pool lookups.
- [CoinGecko Search API](https://apis.io/apis/coingecko/coingecko-search-api/) — Search for coins, exchanges, and categories.
- [CoinGecko Simple API](https://apis.io/apis/coingecko/coingecko-simple-api/) — Simple price and token price lookups without the overhead of full coin data responses.
- [CoinGecko Token Lists API](https://apis.io/apis/coingecko/coingecko-token-lists-api/) — Token list endpoints for paid plan subscribers providing standardized token lists by asset platform.
- [CoinGecko Tokens API](https://apis.io/apis/coingecko/coingecko-tokens-api/) — Query token data by contract address including price, volume, top pools, and token information.
- [CoinGecko Trades API](https://apis.io/apis/coingecko/coingecko-trades-api/) — Recent trade data for specific liquidity pools.
- [CoinGecko Trending API](https://apis.io/apis/coingecko/coingecko-trending-api/) — Trending coins, NFTs, and categories on CoinGecko.
- [CoinGecko Trending Pools API](https://apis.io/apis/coingecko/coingecko-trending-pools-api/) — Discover trending liquidity pools across networks based on web visits and onchain activity.
- [CoinGecko NF Ts API](https://apis.io/apis/coingecko/coingecko-nfts-api/) — NFT collection data including floor prices and market information.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [CoinGecko WebSocket API](https://apis.io/asyncapis/coingecko/coingecko-asyncapi/)

#### Event channels (4)

Individual events and webhooks the provider emits.

- [/v1](https://apis.io/channels/coingecko/coingecko-websocket-api-v1/)
- [/v1](https://apis.io/channels/coingecko/coingecko-websocket-api-v1-2/)
- [/v1](https://apis.io/channels/coingecko/coingecko-websocket-api-v1-3/)
- [/v1](https://apis.io/channels/coingecko/v1/)

#### MCP servers (3)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/coingecko/](https://apis.io/servers/coingecko/coingecko/)
- [Moved to /providers/coingecko/](https://apis.io/servers/coingecko/coingecko-2/)
- [Moved to /providers/coingecko/](https://apis.io/servers/coingecko/coingecko-3/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Coingecko Agentic Access](https://apis.io/agentic-access/coingecko/coingecko-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [CoinGecko Coin](https://apis.io/schemas/coingecko/coingecko-coin/)
- [CoinGecko Onchain Liquidity Pool](https://apis.io/schemas/coingecko/coingecko-pool/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Coingecko Context](https://apis.io/jsonld/coingecko/coingecko-context/)

#### Collections (47)

Postman and Open Collection request collections.

- [CoinGecko Crypto Market Data Asset Platforms API](https://apis.io/collections/coingecko/open-coingecko-asset-platforms-api/)
- [CoinGecko Crypto Market Data Asset Platforms Categories API](https://apis.io/collections/coingecko/open-coingecko-categories-api/)
- [CoinGecko Crypto Market Data Asset Platforms Coins API](https://apis.io/collections/coingecko/open-coingecko-coins-api/)
- [CoinGecko Crypto Market Data Asset Platforms Companies API](https://apis.io/collections/coingecko/open-coingecko-companies-api/)
- [CoinGecko Crypto Market Data Asset Platforms Contract API](https://apis.io/collections/coingecko/open-coingecko-contract-api/)
- [CoinGecko Crypto Market Data API](https://apis.io/collections/coingecko/open-coingecko-crypto-market-data-api/)
- [CoinGecko Crypto Market Data Asset Platforms Derivatives API](https://apis.io/collections/coingecko/open-coingecko-derivatives-api/)
- [CoinGecko Crypto Market Data Asset Platforms DEXes API](https://apis.io/collections/coingecko/open-coingecko-dexes-api/)
- [CoinGecko Crypto Market Data Asset Platforms Exchange Rates API](https://apis.io/collections/coingecko/open-coingecko-exchange-rates-api/)
- [CoinGecko Crypto Market Data Asset Platforms Exchanges API](https://apis.io/collections/coingecko/open-coingecko-exchanges-api/)
- [CoinGecko Crypto Market Data Asset Platforms Global API](https://apis.io/collections/coingecko/open-coingecko-global-api/)
- [CoinGecko Crypto Market Data Asset Platforms Networks API](https://apis.io/collections/coingecko/open-coingecko-networks-api/)
- [CoinGecko Crypto Market Data Asset Platforms NFTs API](https://apis.io/collections/coingecko/open-coingecko-nfts-api/)
- [CoinGecko Crypto Market Data Asset Platforms OHLCV API](https://apis.io/collections/coingecko/open-coingecko-ohlcv-api/)
- [CoinGecko Onchain DEX API](https://apis.io/collections/coingecko/open-coingecko-onchain-dex-api/)
- [CoinGecko Crypto Market Data Asset Platforms Ping API](https://apis.io/collections/coingecko/open-coingecko-ping-api/)
- [CoinGecko Crypto Market Data Asset Platforms Pools API](https://apis.io/collections/coingecko/open-coingecko-pools-api/)
- [CoinGecko Pro API](https://apis.io/collections/coingecko/open-coingecko-pro-api/)
- [CoinGecko Crypto Market Data Asset Platforms Search API](https://apis.io/collections/coingecko/open-coingecko-search-api/)
- [CoinGecko Crypto Market Data Asset Platforms Simple API](https://apis.io/collections/coingecko/open-coingecko-simple-api/)
- [CoinGecko Crypto Market Data Asset Platforms Token Lists API](https://apis.io/collections/coingecko/open-coingecko-token-lists-api/)
- [CoinGecko Crypto Market Data Asset Platforms Tokens API](https://apis.io/collections/coingecko/open-coingecko-tokens-api/)
- [CoinGecko Crypto Market Data Asset Platforms Trades API](https://apis.io/collections/coingecko/open-coingecko-trades-api/)
- [CoinGecko Crypto Market Data Asset Platforms Trending API](https://apis.io/collections/coingecko/open-coingecko-trending-api/)
- [CoinGecko Crypto Market Data Asset Platforms Trending Pools API](https://apis.io/collections/coingecko/open-coingecko-trending-pools-api/)
- …and 22 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [CoinGecko — asyncapi rules](https://apis.io/rules/coingecko/coingecko-asyncapi-spectral-rules/)
- [CoinGecko — jsonschema rules](https://apis.io/rules/coingecko/coingecko-jsonschema-spectral-rules/)
- [CoinGecko API Rules](https://apis.io/rules/coingecko/coingecko-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Coingecko Authentication](https://apis.io/security/coingecko/coingecko-authentication/)
- [Coingecko Domain Security](https://apis.io/security/coingecko/coingecko-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Coingecko Plans Pricing](https://apis.io/plans/coingecko/coingecko-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Coingecko Rate Limits](https://apis.io/rate-limits/coingecko/coingecko-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Coingecko Finops](https://apis.io/finops/coingecko/coingecko-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.coingecko.com)
- [Documentation](https://docs.coingecko.com)
- [Pricing](https://www.coingecko.com/en/api/pricing)
- [Support](https://support.coingecko.com)
- [Blog](https://blog.coingecko.com)
- [Terms of service](https://www.coingecko.com/en/terms)
- [Privacy policy](https://www.coingecko.com/en/privacy)
- [GitHub](https://github.com/coingecko)
- [Status](https://status.coingecko.com/)

## API Evangelist rating

**Kin Score 45.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 59.2 |
| Contract governance | 13.6 |
| Operational transparency | 26.3 |
| Developer ergonomics | 36.9 |
| Access clarity | 46.1 |

**Agent readiness 36.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 28.7** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/coingecko/](https://apis.io/providers/coingecko/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for CoinGecko: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/coingecko/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
