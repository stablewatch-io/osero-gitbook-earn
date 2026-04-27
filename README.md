---
icon: circle-info
cover: .gitbook/assets/OS_Cover_Earn (1).png
coverY: 0
layout:
  width: default
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
---

# What is Osero Earn

Osero Earn enables wallets, neobanks, custodians, and exchanges to offer the **Sky Savings Rate** to their users without taking on asset management risk.

## The problem it solves

Platforms that hold or route stablecoins on behalf of users (wallets, neo-banks, custodians, exchanges) have no easy way to put those balances to work. Offering yield means taking on asset management risk, building infrastructure yourself, or finding a centralized counterparty you can actually trust with your users' funds.

Integrating directly with DeFi protocols requires in-house expertise across smart contract development, chain-specific routing, onchain infrastructure management, and ongoing protocol monitoring. For most companies, the cost of building and maintaining this capability far outweighs the benefit.

Osero Earn eliminates that complexity entirely. It packages the Sky Savings Rate into a developer-friendly SDK, creating a seamless bridge between the traditional development environment and the leading onchain yield product.

## Core value proposition

> **Any fintech, wallet, or financial platform can offer institutional-grade stablecoin yield to their users in hours, not months.**

Osero Earn achieves this through two tightly coupled components:

### 1. Integration SDK — `@osero/client`

An open-source TypeScript SDK that abstracts away all chain-specific routing and contract interactions. Given a wallet holding USDC, the SDK builds and executes the correct sequence of transactions to mint USDS or sUSDS on any supported chain handling approvals, PSM routing, and ERC-4626 vault deposits automatically.

[Read the full SDK documentation →](https://app.gitbook.com/s/FiS75u6KPKebPGXjRNOd/getting-started/readme)

### 2. Transparency SDK — _Coming Soon_

A live, auditable data feed that gives distributors and their users a real-time view of the assets, liquidity, and risk capital backing the Sky Savings Rate. This enables distributors to surface meaningful transparency data within their own product UI, building user trust without needing to operate any data infrastructure themselves.

[Read about Backing Transparency →](features/backing-transparency.md)

***

## Who is Osero Earn for?

Osero Earn is built for platforms that want to distinguish by offering their users the best risk-adjusted savings product.

| Distributor type | Primary use case                                                             |
| ---------------- | ---------------------------------------------------------------------------- |
| **Neobanks**     | Offer yield on stablecoin balances to retail customers as a savings product. |
| **Custodians**   | Enable institutional clients to earn yield on idle stablecoin holdings.      |
| **Exchanges**    | Provide a savings rail for users who do not want active trading exposure.    |
| **Wallets**      | Embed the Sky Savings Rate as a native savings option within the wallet UX.  |

[See the full use case overview →](overview/use-cases.md)
