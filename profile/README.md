# GriffNode

**Non-custodial crypto payment gateway.** Accept BTC, ETH, LTC, DOGE, DASH and stablecoins (USDT, USDC, DAI) with no KYC, no chargebacks, and no custody. Funds settle straight into the merchant's own wallet. GriffNode never holds or can spend a cent.

- Website: https://griffnode.com
- Docs: https://docs.griffnode.com
- MCP server: run the whole gateway from any AI client, see the docs

## Official SDKs

- JavaScript / TypeScript: [@griffnode/js-sdk](https://www.npmjs.com/package/@griffnode/js-sdk) ([source](https://github.com/GriffNode/js-sdk))
- Python: [griffnode](https://pypi.org/project/griffnode/) ([source](https://github.com/GriffNode/python-sdk))
- Ruby: [griffnode](https://rubygems.org/gems/griffnode) ([source](https://github.com/GriffNode/ruby-sdk))
- Rust: [griffnode](https://crates.io/crates/griffnode) ([source](https://github.com/GriffNode/rust-sdk))
- PHP: [source](https://github.com/GriffNode/php-sdk)
- Go: [source](https://github.com/GriffNode/go-sdk)
- Java: [source](https://github.com/GriffNode/java-sdk)
- C# / .NET: [source](https://github.com/GriffNode/csharp-sdk)

## Plugins

- [WooCommerce](https://github.com/GriffNode/woocommerce-plugin)
- [WordPress](https://github.com/GriffNode/wordpress-plugin)

## Why non-custodial

A merchant connects an xPub (extended public key). We derive a fresh receiving address for every payment, so funds go from the customer straight into the merchant's own wallet. An xPub can only receive, never spend, so there is no balance for anyone to freeze, hack, or seize. On-chain settlement is final, which is why there are no chargebacks.

Learn more at [griffnode.com](https://griffnode.com).
