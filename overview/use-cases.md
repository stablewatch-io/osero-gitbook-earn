---
icon: briefcase-blank
---

# Use Cases

Osero Earn is designed for any platform that holds or distributes stablecoins on behalf of users. The SDK and Transparency API are built to be platform-agnostic — the integration pattern is the same whether you are a consumer neobank or an institutional custodian.

## Who should integrate Osero Earn?

### Neobanks

|              |                                                                              |
| ------------ | ---------------------------------------------------------------------------- |
| **Use case** | Offer yield on stablecoin balances to retail customers as a savings product. |

Neobanks holding customer stablecoin balances have a natural opportunity to offer a savings product that competes with traditional high-yield savings accounts. Osero Earn provides the yield infrastructure and the transparency data needed to present the Sky Savings Rate as a credible, understandable product to retail customers — without requiring the bank to build or maintain any DeFi infrastructure.

### Custodians

|              |                                                                         |
| ------------ | ----------------------------------------------------------------------- |
| **Use case** | Enable institutional clients to earn yield on idle stablecoin holdings. |

Institutional clients often hold significant stablecoin balances in custodial accounts with no yield. Osero Earn allows custodians to offer a yield-bearing option on these idle balances. The Basel III-inspired risk framework and live Transparency API data are particularly compelling for institutional clients who require rigorous risk documentation and ongoing auditability.

### Exchanges

|              |                                                                           |
| ------------ | ------------------------------------------------------------------------- |
| **Use case** | Provide a savings rail for users who do not want active trading exposure. |

Exchanges hold large pools of user stablecoin balances across spot, margin, and off-exchange accounts. Osero Earn gives exchanges a way to offer a passive yield product to users who want their stablecoins working for them without active trading. This can reduce churn from users who would otherwise move funds off-platform to earn yield elsewhere.

### Wallets

|              |                                                                             |
| ------------ | --------------------------------------------------------------------------- |
| **Use case** | Embed the Sky Savings Rate as a native savings option within the wallet UX. |

Wallets that hold or display stablecoin balances can integrate Osero Earn to offer a one-tap savings option directly within their product. The SDK's wallet-agnostic `ExecutionPlan` model makes it straightforward to wire into any existing transaction flow, including account-abstraction setups.

## Integration requirements

To integrate Osero Earn, a distributor needs:

* A TypeScript-capable development environment
* User wallets holding USDC on at least one [supported chain](https://app.gitbook.com/s/FiS75u6KPKebPGXjRNOd/supported-chains)
* The `@osero/client` SDK ([installation guide](https://app.gitbook.com/s/FiS75u6KPKebPGXjRNOd/installation))

No smart contract deployment, DeFi protocol expertise, or onchain infrastructure management is required on the distributor's side.

## Coming soon: multi-stablecoin support

Through an upcoming integration with [Enso](https://www.enso.finance/), Osero Earn will extend support to accept deposits in any stablecoin or supported blockchain, with Enso handling the routing and conversion to USDC/USDS in a single bundled transaction. This will further widen the addressable user base for any distributor.
