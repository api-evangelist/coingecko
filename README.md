# CoinGecko (coingecko)

CoinGecko is a cryptocurrency data aggregator providing market data, analytics, and information on thousands of crypto assets, exchanges, derivatives, NFTs, and on-chain decentralized markets worldwide. The CoinGecko Developer Platform exposes three primary APIs: the public Crypto Market Data API (Demo plan and free tier), the commercial Pro API for higher rate limits and exclusive endpoints, and the Onchain DEX API powered by GeckoTerminal for decentralized exchange data across 250+ networks. Authentication uses x-cg-demo-api-key (Demo) or x-cg-pro-api-key (Pro) headers, with rate limits ranging from 30 calls per minute on Demo to 1,000 calls per minute on top Pro tiers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/coingecko/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
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
- **Modified:** 2026-04-28

## APIs

### CoinGecko Crypto Market Data API
The CoinGecko Crypto Market Data API provides comprehensive and reliable cryptocurrency price and market data through RESTful JSON endpoints. It offers over 70 endpoints covering real-time and historical prices, trading volumes, market capitalization, OHLCV data, exchange information, NFT metrics, derivatives data, and public treasury holdings for over 18,000 coins.

**Human URL:** [https://docs.coingecko.com](https://docs.coingecko.com)

**Base URL:** `https://api.coingecko.com/api/v3`

#### Tags

- Blockchain, Cryptocurrency, Exchanges, Market Data, NFTs, Prices

#### Properties

- [Documentation](https://docs.coingecko.com)
- [Pricing](https://www.coingecko.com/en/api/pricing)
- [Landing Page](https://www.coingecko.com/en/api)
- [OpenAPI](openapi/coingecko-crypto-market-data-api-openapi.yml)

### CoinGecko Pro API
The CoinGecko Pro API provides the same comprehensive cryptocurrency market data as the standard API but with enhanced performance, higher rate limits of up to 1,000 calls per minute, and faster data updates with prices cached every 30 seconds. It includes exclusive endpoints for advanced analytics, detailed market data, and historical granularity that are not available on the free Demo plan.

**Human URL:** [https://docs.coingecko.com/reference/introduction](https://docs.coingecko.com/reference/introduction)

**Base URL:** `https://pro-api.coingecko.com/api/v3`

#### Tags

- Commercial, Cryptocurrency, Enterprise, Market Data, Prices

#### Properties

- [Documentation](https://docs.coingecko.com/reference/introduction)
- [Pricing](https://www.coingecko.com/en/api/pricing)
- [OpenAPI](openapi/coingecko-pro-api-openapi.yml)

### CoinGecko Onchain DEX API
The CoinGecko Onchain DEX API, powered by GeckoTerminal, provides access to real-time decentralized exchange data across over 250 blockchain networks, 1,800 DEXes, and 30 million tokens. It offers more than 20 endpoints for querying liquidity pools, token data by contract address, OHLCV chart data, trending pools, and pool search functionality.

**Human URL:** [https://www.coingecko.com/en/api/dex](https://www.coingecko.com/en/api/dex)

**Base URL:** `https://api.coingecko.com/api/v3/onchain`

#### Tags

- Blockchain, Decentralized Exchanges, DeFi, DEX, Liquidity Pools, Onchain Data

#### Properties

- [Documentation](https://docs.coingecko.com/reference/endpoint-overview)
- [Landing Page](https://www.coingecko.com/en/api/dex)
- [OpenAPI](openapi/coingecko-onchain-dex-api-openapi.yml)

## Common Properties

- [Portal](https://www.coingecko.com/en/api)
- [Documentation](https://docs.coingecko.com)
- [Pricing](https://www.coingecko.com/en/api/pricing)
- [Website](https://www.coingecko.com)
- [Blog](https://blog.coingecko.com)
- [Support](https://support.coingecko.com)
- [Login](https://www.coingecko.com/en/developers/dashboard)
- [Status](https://status.coingecko.com/)
- [Terms of Service](https://www.coingecko.com/en/terms)
- [Privacy Policy](https://www.coingecko.com/en/privacy)
- [Coin JSON Schema](json-schema/coingecko-coin-schema.json)
- [Pool JSON Schema](json-schema/coingecko-pool-schema.json)
- [JSON-LD Context](json-ld/coingecko-context.jsonld)
- [Spectral Ruleset](rules/coingecko-rules.yml)
- [Naftiko Capabilities](capabilities/coingecko-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
