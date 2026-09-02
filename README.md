---
icon: circle-info
cover: .gitbook/assets/OS_Cover_Earn (1).png
coverY: 0
layout:
  width: default
  cover:
    visible: true
    size: hero
    mask: none
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
  actions:
    visible: true
---

# What is Osero Earn

Osero Earn enables platforms to offer stablecoin savings to their users within a day.

It is an embedded SDK built for wallets, exchanges, fintechs, neobanks, custodians, and other financial platforms that want to add onchain savings without building the underlying DeFi infrastructure themselves.

Through Osero Earn, platforms can give their users access to the **Sky Savings Rate** while Osero handles the underlying infrastructure, without requiring platforms to manage the assets themselves.

## The Problem It Solves

Platforms that hold or support stablecoins, including wallets, neobanks, custodians, and exchanges, have no simple way to offer yield on those balances. Doing so often means building the infrastructure in-house, taking on asset management responsibilities, or relying on a centralized provider.

Integrating directly with DeFi protocols adds another layer of complexity. It requires expertise across smart contracts, multiple networks, routing, onchain infrastructure, and ongoing protocol monitoring. For most platforms, that means significant development and maintenance work for a feature that should be simple for users.

Osero Earn removes this complexity. It packages access to the Sky Savings Rate in a developer-friendly SDK, allowing platforms to add stablecoin savings without building and operating the underlying DeFi infrastructure themselves.

## Core Value Proposition

> **Osero Earn gives fintechs, wallets, exchanges, and other financial platforms everything they need to offer stablecoin savings to their users, without building the underlying DeFi infrastructure themselves.**
>
> **With a single integration, platforms can give users access to the Sky Savings Rate across multiple stablecoins and networks, while Osero handles the conversions, bridging, and onchain complexity required to get funds into and out of sUSDS.**
>
> **What would normally require months of development, specialized DeFi expertise, and ongoing infrastructure maintenance can be integrated within a day.**

## **A Single SDK for Stablecoin Savings**

`@osero/client` is an open-source TypeScript SDK that handles chain-specific routing and contract interactions required for integrating Osero Earn.

When a user deposits a supported stablecoin, the SDK prepares the required transaction flow into sUSDS, including token approvals, conversions, cross-chain routing, and other onchain interactions.

This gives platforms a single integration for offering stablecoin savings across supported assets and networks, without having to build and maintain the underlying DeFi infrastructure themselves.

[Read the full SDK documentation →](https://app.gitbook.com/s/FiS75u6KPKebPGXjRNOd/getting-started/readme)

## Who Is Osero Earn For?

Osero Earn is built for platforms that want to offer their users a competitive stablecoin savings product without becoming asset managers or building the underlying DeFi infrastructure themselves.

It is designed for wallets, fintechs, neobanks, exchanges, custodians, and other financial platforms looking to add yield as a native part of their product while giving users access to a strong risk-adjusted savings rate.

| Stablecoin platform type | Primary use case                                                                                         |
| ------------------------ | -------------------------------------------------------------------------------------------------------- |
| **Neobanks**             | Add stablecoin savings as a native product for their customers.                                          |
| **Custodians**           | Enable institutional clients to earn yield on idle stablecoin holdings.                                  |
| **Exchanges**            | Give users a way to earn on stablecoins when they’re not trading, without moving funds off the exchange. |
| **Wallets**              | Let users earn on the stablecoins they already hold, directly from the wallet.                           |

[See the full use case overview →](overview/use-cases.md)
