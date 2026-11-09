# XentFi — Arbitrum-Tailored Stablecoin Infrastructure

**One API for wallets, checkout, fiat on/off-ramps, agent payments, treasury operations, and deep L2 liquidity.**

[Website](https://app.xentfi.com) · [Developer Docs](https://docs.xentfi.com) · [API Reference](https://docs.xentfi.com/api-reference) · [Dashboard](https://dash.xentfi.com) · [GitHub](https://github.com/xentfi)

---

## Overview

XentFi is a stablecoin infrastructure platform built in Africa for African payment corridors, with an architecture designed to expand into global markets. It gives fintechs, payment companies, platforms, and developers a unified integration layer for building stablecoin-powered financial products without having to assemble and maintain separate blockchain, wallet, and payment integrations.

On **Arbitrum One**, XentFi leverages high-throughput, low-cost Layer 2 execution to supercharge cross-border B2B clearing and automated machine-to-machine commerce.

XentFi is designed around a single API and operating layer spanning:

- **Wallet-as-a-Service (WaaS):** create and manage master wallets and customer deposit addresses.
- **Checkout and payment links:** accept digital-asset payments through hosted checkout flows.
- **On-ramps and off-ramps:** connect fiat payment flows with stablecoin settlement.
- **Agent infrastructure:** provision and manage agents, agent wallets, and agent payment activity.
- **Treasury and settlement automation:** configure rules to consolidate and distribute funds.
- **Transfers and swaps:** move assets across supported networks and execute supported swaps.
- **Order-book and liquidity services:** provide access to trading and liquidity workflows as part of the broader XentFi platform.

The goal is to make stablecoin infrastructure usable as a practical payment and treasury layer—not just a way to hold digital assets.

---

## Why XentFi on Arbitrum

Businesses building across African and emerging-market payment corridors often need to connect multiple providers, Layer 2 networks, wallets, compliance processes, and settlement systems. Each additional integration increases engineering and operational overhead.

By anchoring high-frequency settlement and multi-chain liquidity routing natively on **Arbitrum One**, XentFi solves key enterprise challenges:
* **Sub-Cent Gas Fees & Instant Finality:** Eliminates the high transaction friction of L1 execution, making micro-settlements and high-volume merchant clearing economically viable.
* **Deep Liquidity & Native Asset Mobility:** Unifies fiat gateways with Arbitrum's robust ecosystem of USDC, EURC, and decentralized liquidity pools.
* **Unified API Abstraction:** Teams can build customer-facing products and backend financial workflows on the same infrastructure, then extend those workflows seamlessly across L2 corridors.

**Market approach:** Africa-first, with planned and ongoing expansion toward corridors including the United States, Brazil, and Mexico.

---

## Arbitrum Integration & Execution

XentFi integrates Arbitrum One as a primary production Layer 2 execution layer for high-speed stablecoin settlement, automated treasury rebalancing, and programmatic escrow workflows. 

This connects Arbitrum-based stablecoin settlement to real-world payment use cases: moving value into digital dollars, using stablecoins in payment workflows, and converting back toward local fiat rails. Arbitrum is part of XentFi's core multi-chain production network strategy.

The integration makes Arbitrum available through the exact same developer experience used for wallets, payments, and treasury operations across the XentFi platform.

---

## Traction

- **$10M+ in cumulative transaction volume** across XentFi's supported infrastructure.
- **Mainnet operations:** XentFi is live on mainnet.
- **L2 & Multi-chain infrastructure:** Robust support across major networks, anchored by deep integration with Arbitrum One, Ethereum, Base, Optimism, Polygon, BNB Chain, and Solana.

---

## Developer Resources

| Resource | Link |
|---|---|
| Main website | https://app.xentfi.com |
| Documentation | https://docs.xentfi.com |
| Quickstart | https://docs.xentfi.com/quickstart |
| API reference | https://docs.xentfi.com/api-reference |
| Authentication | https://docs.xentfi.com/api-reference/authentication |
| API errors | https://docs.xentfi.com/api-reference/errors |
| Development environment | https://docs.xentfi.com/development |
| Sample projects | https://docs.xentfi.com/projects |
| Release notes | https://docs.xentfi.com/release-notes/changelog |
| Dashboard | https://dash.xentfi.com |
| GitHub | https://github.com/xentfi |
| Support | mailto:support@xentfi.com |

### Product Documentation

- [Master wallets](https://docs.xentfi.com/essentials/master-wallets)
- [Customer deposit addresses](https://docs.xentfi.com/essentials/addresses)
- [Payment links and checkout](https://docs.xentfi.com/essentials/payment-links)
- [Automated settlement](https://docs.xentfi.com/essentials/auto-settlement)
- [Transfers and swaps](https://docs.xentfi.com/essentials/transfers-swaps)
- [AML and compliance](https://docs.xentfi.com/essentials/aml-compliance)
- [Webhooks](https://docs.xentfi.com/essentials/webhooks)
- [Security](https://docs.xentfi.com/essentials/security)
- [Asset recovery](https://docs.xentfi.com/essentials/asset-recovery)

### SDKs and Packages

Public developer packages:

- **Agent / MCP SDK:** [`@xentfi/mcp-sdk`](https://www.npmjs.com/package/@xentfi/mcp-sdk) — `npm install @xentfi/mcp-sdk`. Adds policy-governed XentFi wallet and payment tools to MCP-compatible agent runtimes. [Source repository](https://github.com/xentfi/xentfi-mcp-server).
- **x402 payment facilitator:** [`@xentfi/x402-facilitator`](https://www.npmjs.com/package/@xentfi/x402-facilitator) — `npm install @xentfi/x402-facilitator`. TypeScript package for XentFi's x402 payment facilitator.

---

## Getting Started

1. Create an account through the [XentFi dashboard](https://dash.xentfi.com).
2. Generate sandbox API credentials.
3. Follow the [Quickstart](https://docs.xentfi.com/quickstart) to authenticate and make your first API request.
4. Build and test with the SDKs or REST API, targeting Arbitrum testnets/mainnet.
5. Configure webhooks, validate your integration in the supported test environment, and request production access when ready.

---

## Built for Africa, Designed for Global Corridors

XentFi's initial focus is solving payment and settlement infrastructure challenges across African markets. Its multi-chain and API-first architecture on Arbitrum One is designed to support expansion into additional corridors—including the US, Brazil, and Mexico—through local payment integrations, liquidity partners, and regulatory-compliant operating models.

---

## Contact

- Website: https://app.xentfi.com
- Documentation: https://docs.xentfi.com
- Developer support: dev@xentfi.com
- General support: support@xentfi.com
- X: https://x.com/xentfi
- GitHub: https://github.com/xentfi
- LinkedIn: https://linkedin.com/company/xentfi