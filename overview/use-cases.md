---
icon: briefcase-blank
---

# Use Cases

Osero Earn is designed for any platform that holds or distributes stablecoins for its users. The SDK is platform-agnostic, so the same integration can work across different products, from consumer neobanks and wallets to exchanges and institutional custodians.

## Who should integrate Osero Earn?

### Neobanks

|              |                                                                 |
| ------------ | --------------------------------------------------------------- |
| **Use case** | Add stablecoin savings as a native product for their customers. |

Neobanks holding customer stablecoin balances can turn those balances into a savings product that competes with traditional high-yield savings accounts. Osero Earn provides the infrastructure to offer the Sky Savings Rate directly to retail customers, without requiring the neobank to build or maintain its own DeFi infrastructure.

### Custodians

|              |                                                                         |
| ------------ | ----------------------------------------------------------------------- |
| **Use case** | Enable institutional clients to earn yield on idle stablecoin holdings. |

Institutional clients often hold significant stablecoin balances in custody without earning yield. Osero Earn allows custodians to offer a yield-bearing option on those balances, backed by a Basel III-inspired capital-protection structure and transparent risk reporting designed to meet institutional clients' expectations.

### Exchanges

|              |                                                                                                          |
| ------------ | -------------------------------------------------------------------------------------------------------- |
| **Use case** | Give users a way to earn on stablecoins when they’re not trading, without moving funds off the exchange. |

Exchanges hold large stablecoin balances for users who aren’t always actively trading. Osero Earn gives those users a way to earn the Sky Savings Rate directly through the exchange, so they don’t need to move their funds elsewhere to find yield. This helps exchanges keep more user assets and activity on the platform.

### Wallets

|              |                                                                                |
| ------------ | ------------------------------------------------------------------------------ |
| **Use case** | Let users earn on the stablecoins they already hold, directly from the wallet. |

Wallets can use Osero Earn to add stablecoin savings directly to their existing product. Users can earn the Sky Savings Rate on the stablecoins they already hold, without leaving their wallet or seeking yield elsewhere. The SDK is designed to work with existing transaction flows, including account abstraction setups.

## Integration requirements

To integrate Osero Earn, a platform needs:

* A TypeScript-capable development environment
* Support for user wallets holding stablecoins on at least one supported network
* The `@osero/client` SDK ([installation guide](https://app.gitbook.com/s/FiS75u6KPKebPGXjRNOd/getting-started/installation))

No smart contract deployment, DeFi expertise, or onchain infrastructure management is required from the platform.
