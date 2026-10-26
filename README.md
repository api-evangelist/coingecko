# CoinGecko (coingecko)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Aggregator
- Blockchain
- Cryptocurrency
- Decentralized Exchanges
- DeFi
- DEX
- Exchanges
- Liquidity Pools
- Market Data
- NFTs
- Onchain Data
- Prices

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-29

## APIs

### CoinGecko Crypto Market Data API

The CoinGecko Crypto Market Data API provides comprehensive and reliable cryptocurrency price and market data through RESTful JSON endpoints. It offers over 70 endpoints covering real-time and historical prices, trading volumes, market capitalization, OHLCV data, exchange information, NFT metrics, derivatives data, and public treasury holdings for over 18,000 coins.

- **Human URL:** [https://docs.coingecko.com](https://docs.coingecko.com)
- **Base URL:** `https://api.coingecko.com/api/v3`

#### Tags

- Blockchain
- Cryptocurrency
- Exchanges
- Market Data
- NFTs
- Prices

#### Properties

- [Documentation](https://docs.coingecko.com)
- [Pricing](https://www.coingecko.com/en/api/pricing)
- [Landing  Page](https://www.coingecko.com/en/api)
- [OpenAPI](openapi/coingecko-crypto-market-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coingecko-crypto-market-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coingecko-crypto-market-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CoinGecko Pro API

The CoinGecko Pro API provides the same comprehensive cryptocurrency market data as the standard API but with enhanced performance, higher rate limits of up to 1,000 calls per minute, and faster data updates with prices cached every 30 seconds. It includes exclusive endpoints for advanced analytics, detailed market data, and historical granularity that are not available on the free Demo plan.

- **Human URL:** [https://docs.coingecko.com/reference/introduction](https://docs.coingecko.com/reference/introduction)
- **Base URL:** `https://pro-api.coingecko.com/api/v3`

#### Tags

- Commercial
- Cryptocurrency
- Enterprise
- Market Data
- Prices

#### Properties

- [Documentation](https://docs.coingecko.com/reference/introduction)
- [Pricing](https://www.coingecko.com/en/api/pricing)
- [OpenAPI](openapi/coingecko-pro-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coingecko-pro-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coingecko-pro-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/coingecko-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### CoinGecko Onchain DEX API

The CoinGecko Onchain DEX API, powered by GeckoTerminal, provides access to real-time decentralized exchange data across over 250 blockchain networks, 1,800 DEXes, and 30 million tokens. It offers more than 20 endpoints for querying liquidity pools, token data by contract address, OHLCV chart data, trending pools, and pool search functionality.

- **Human URL:** [https://www.coingecko.com/en/api/dex](https://www.coingecko.com/en/api/dex)
- **Base URL:** `https://api.coingecko.com/api/v3/onchain`

#### Tags

- Blockchain
- Decentralized Exchanges
- DeFi
- DEX
- Liquidity Pools
- Onchain Data

#### Properties

- [Documentation](https://docs.coingecko.com/reference/endpoint-overview)
- [Landing  Page](https://www.coingecko.com/en/api/dex)
- [OpenAPI](openapi/coingecko-onchain-dex-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coingecko-onchain-dex-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coingecko-onchain-dex-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/coingecko)
- [LinkedIn](https://www.linkedin.com/company/coingecko)
- [Portal](https://www.coingecko.com/en/api)
- [Documentation](https://docs.coingecko.com)
- [Pricing](https://www.coingecko.com/en/api/pricing)
- [Website](https://www.coingecko.com)
- [Blog](https://blog.coingecko.com)
- [Support](https://support.coingecko.com)
- [Login](https://www.coingecko.com/en/developers/dashboard)
- [Status Page](https://status.coingecko.com/)
- [Terms of Service](https://www.coingecko.com/en/terms)
- [Privacy Policy](https://www.coingecko.com/en/privacy)
- [JSON Schema](json-schema/coingecko-coin-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/coingecko-pool-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/coingecko-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral  Ruleset](rules/coingecko-rules.yml)
- [L L Ms Txt](https://docs.coingecko.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
