---
icon: droplet
---

# Position Liquidity

A core component of Sky Protocol's risk management framework, and a key differentiator from other DeFi yield sources, is the concept of **Actively Stabilising Collateral**. This is the pool of highly liquid assets that Sky Protocol maintains to protect the peg of USDS and sUSDS and to ensure that redemption demand can always be met.

## What is Actively Stabilising Collateral?

Actively Stabilising Collateral refers to assets held in the most liquid forms available within the Sky Ecosystem — specifically:

* **Cash stablecoins** held directly in reserve, redeemable immediately with no market impact
* **Liquid onchain money market positions** that can be exited rapidly with minimal price impact

Together, these assets give Sky Protocol the capacity to respond quickly to large redemption events or peg pressure without needing to unwind longer-duration or less-liquid positions.

## Why it matters for stablecoin platforms

For stablecoin platforms offering the Sky Savings Rate to retail or institutional users, liquidity is a critical trust signal. Users want to know that their savings are not locked in illiquid positions that could prevent or delay redemption.

The size of Sky's Actively Stabilising Collateral relative to total USDS supply provides a meaningful buffer. It means that even in scenarios of elevated redemption pressure, the protocol has substantial capacity to honour withdrawals from immediately accessible reserves before needing to touch longer-duration allocations.

## The Liquidity feed

Osero Earn's [Transparency API](backing-transparency.md) surfaces this data in real time through the Liquidity feed, which distinguishes between:

| Liquidity tier             | Description                                                                                                 |
| -------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **Idle stablecoins**       | Cash stablecoins held in reserve, immediately redeemable                                                    |
| **Onchain DeFi positions** | Positions in protocols like Morpho, SparkLend, and Aave Horizon that can be liquidated with no price impact |

Distributors can integrate this feed into their product UI to give users a live view of available liquidity.

## Relationship to peg stability

The peg stability of USDS, and by extension sUSDS, depends on the ability of the PSM (Peg Stability Module) to absorb flows in both directions. When users deposit USDC, the PSM mints USDS. When users redeem, the PSM burns USDS and returns USDC.

The PSM's capacity to function smoothly is directly supported by the availability of Actively Stabilising Collateral. A well-capitalised reserve of liquid assets means the PSM can handle large bilateral flows without creating peg instability, which in turn protects the value of every user's sUSDS position.

