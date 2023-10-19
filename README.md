# Moralis Price API

With [Moralis' Price API](https://moralis.io/api/price/), you can unlock the power of real-time and historical cryptocurrency price data. As your trusted source for comprehensive price information across all major Ethereum Virtual Machine (EVM) chains, Moralis ensures you have the edge in the fast-paced world of crypto trading and development.

In this article, you will explore the Moralis Price API and how it can help you while developing dapps.

## Quick Start to Price API

1. [Get an API key](https://docs.moralis.io/web3-data-api/evm/get-your-api-key)
2. Explore the [documentation guides](https://docs.moralis.io/web3-data-api/evm/market-data-api/)
3. Explore the [full list of endpoints](https://docs.moralis.io/web3-data-api/evm/reference)

## Price Endpoints

Experience the most accurate and up-to-date cryptocurrency price data, optimizing your projects and ensuring you're always one step ahead in the crypto market. Embrace the Moralis Price API today and supercharge your development and trading endeavors.

| No. | Method                   | Description             | API Reference                                                                                              | URL                                                        |
|-----|--------------------------|-------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| 1   | `getTokenPrice`          | Get ERC20 token price    | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-token-price) | [https://deep-index.moralis.io/api/v2.2/erc20/:address/price](https://deep-index.moralis.io/api/v2.2/erc20/:address/price)                     |
| 2   | `getMultipleTokenPrices` | Get multiple token prices | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-multiple-token-prices) | [https://deep-index.moralis.io/api/v2.2/erc20/prices](https://deep-index.moralis.io/api/v2.2/erc20/prices)                   |
| 3   | `getTopERC20TokensByPriceChange` | Get the top ERC20 tokens by price change   | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-top-erc20-tokens-by-price-movers) | [https://deep-index.moralis.io/api/v2.2/market-data/erc20s/top-movers](https://deep-index.moralis.io/api/v2.2/market-data/erc20s/top-movers)                     |
| 4   | `getNFTLowestPrice`      | Get lowest price         | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-nft-lowest-price) | [https://deep-index.moralis.io/api/v2.2/nft/:address/lowestprice](https://deep-index.moralis.io/api/v2.2/nft/:address/lowestprice) |                |

## Market API Endpoints

| No. | Method                                   | Description                                | API Reference                                                                                                                             | URL                                                                       |
|-----|------------------------------------------|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| 1   | `getTopERC20TokensByMarketCap`           | Get the top ERC20 tokens by market cap     | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-top-erc20-tokens-by-market-cap) | [https://deep-index.moralis.io/api/v2.2/market-data/erc20s/top-tokens](https://deep-index.moralis.io/api/v2.2/market-data/erc20s/top-tokens)                     |
| 2   | `getTopERC20TokensByPriceChange`         | Get the top ERC20 tokens by price change   | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-top-erc20-tokens-by-price-movers) | [https://deep-index.moralis.io/api/v2.2/market-data/erc20s/top-movers](https://deep-index.moralis.io/api/v2.2/market-data/erc20s/top-movers)                     |
| 3   | `getTopNFTCollectionsByMarketCap`        | Get the top NFT collections by market cap  | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-top-nft-collections-by-market-cap) | [https://deep-index.moralis.io/api/v2.2/market-data/nfts/top-collections](https://deep-index.moralis.io/api/v2.2/market-data/nfts/top-collections)                     |
| 4   | `getTopNFTCollectionsByTradingVolume`    | Get the top NFT collections by trading volume | [Method Documentation](https://docs.moralis.io/web3-data-api/evm/reference/get-top-nft-collections-by-trading-volume) | [https://deep-index.moralis.io/api/v2.2/market-data/nfts/hottest-collections](https://deep-index.moralis.io/api/v2.2/market-data/nfts/hottest-collections)                     |

## Token Coverage

Moralis Price API allows you to instant access prices for all tokens as soon as they start trading on decentralized exchanges. No more waiting for approvals or gatekeeping – you get the latest price data right away. Say goodbye to incomplete and delayed price data.

## Up-to-the-Second Updates

Our Price API updates with every block, ensuring you receive the most current crypto price data available. Take it a step further by setting up instant webhook alerts using [Moralis Streams](https://moralis.io/streams/), so you always know when prices change.

## Batch Requests

Simplify your code and speed up execution by sending an array of coins to the Moralis Price API. Receive prices for all specified tokens in a single response, making your data retrieval process cleaner and faster.

## Historical Price

While our API offers a token's latest price by default, you can delve into the past. Query the Moralis Price API for historical prices at any specific point in time. Input a timestamp or block number, and unlock the token's price history for in-depth analysis.

## EVM Chains Supported

The Moralis Price API is your go-to solution, providing support for decentralized exchanges (DEXs) across all major EVM chains, including Ethereum, Binance Smart Chain, Polygon, and more.

## ⭐️ Star us

If this Price API helps you - please star this project, every star makes us very happy!

## 🤝 Need help?

If you need help with using the Price API or have other questions - don't hesitate to write in our community forum and we will check asap. [Forum link](https://forum.moralis.io/). We are answering questions 24/7
