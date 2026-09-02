---
icon: shield-check
---

# Sky Savings Rate

The Sky Savings Rate (SSR) is the mechanism behind the sUSDS position available through the Osero Earn.

Osero App gives you access to sUSDS, while Sky Protocol sets the rate and operates the underlying savings system.

### What is the Sky Savings Rate?

The Sky Savings Rate is the variable rate earned by sUSDS. As it accrues, each sUSDS token represents more USDS over time, without requiring you to claim rewards manually.

The yield is reflected in the value of sUSDS itself, rather than paid out as separate rewards.

The rate is set through Sky Protocol governance and can change over time. The rate shown in Osero App is the current rate, not a guaranteed future return.

### Key protocol statistics

| Metric                  | Value   |
| ----------------------- | ------- |
| Total sUSDS Supply      | $4.6B   |
| Total Stablecoin Supply | $10.01B |
| Total Collateral        | $13.84B |
| Total Instant Liquidity | $4.2B   |
| Total Risk Capital      | $183.9M |

_Data as of July 27, 2026._

These figures are snapshots and can change as protocol positions and parameters are updated.

### What backs the Sky Savings Rate?

The rate is supported by income generated from a mix of onchain and offchain assets.

| Asset class                   | Allocation | Example counterparties           |
| ----------------------------- | ---------- | -------------------------------- |
| USDC Stablecoins              | 48.63%     | Coinbase Prime                   |
| Onchain Crypto-Backed Lending | 19.04%     | Morpho, SparkLend, Aave/Horizon  |
| Short Duration Treasury Bills | 15.95%     | BlackRock, Janus Henderson       |
| OTC Crypto-Backed Lending     | 9.90%      | Maple, Galaxy, Anchorage Digital |
| AAA Corporate Debt            | 5.01%      | BNY Mellon, Janus Henderson      |
| Other                         | 1.47%      | Apollo                           |

_Data as of July 27, 2026._

The allocation spreads exposure across several sources, but it does not remove asset, counterparty, market, or liquidity risk.

### Sky Protocol’s risk framework

Sky uses a layered capital structure designed to absorb potential losses. Agents provide **Junior Risk Capital** for the positions they manage, while Sky provides **Senior Risk Capital** as an additional layer of protection.

If a relevant position suffers a loss, it is intended to be absorbed in the following order:

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

This structure can mitigate some losses, but it does not guarantee that users will not lose funds.

For a detailed explanation, see [Capital Protection](/broken/pages/5JSePco5QbMSDzExw1jx).
