---
icon: lock
---

# Security & Audits

Osero Earn does not use its own smart contracts to hold your final savings position.

Your position is held as sUSDS on Sky Protocol infrastructure. Osero prepares the route into sUSDS rather than replacing Sky’s underlying contracts with its own.

Before you receive sUSDS, your transaction may also involve Osero, your wallet, Enso, LI.FI, blockchain networks, and cross-chain infrastructure. Each component has its own risks, so using Osero involves more than just Sky Protocol infrastructure.

### Osero's trust boundary

Osero displays a route for the user to review. Wallets, route providers, networks, and Sky infrastructure remain separate systems, each with its own failure modes. Osero does not control them or remove their risks.

Sky audits cover specific Sky components. They do not cover Osero, every route used by the app, or your wallet and device. Always review the route and wallet requests before signing.

### Sky security in context

Sky Protocol, formerly MakerDAO, has operated for more than 11 years without a reported exploit affecting its core protocol or oracle system.

Its official security index includes more than 50 public security reports covering the core system, governance, savings, tokens, liquidity, bridges, and capital-allocation modules.

These reviews include work from firms such as ChainSecurity, Cantina, Trail of Bits, PeckShield, and Certora. Sky also describes its [development and formal verification practices](https://developers.skyeco.com/security/security-measures/development-practices/) and runs a [bug bounty program](https://developers.skyeco.com/security/bug-bounty-program/) through Immunefi.

This track record provides context on the security work behind Sky infrastructure, but it does not eliminate risk or guarantee that every contract, route, or transaction will work as expected.

### Sky Protocol audits

The reviews below cover Sky Protocol, not Osero Earn.

Sky’s official audit index lists completed security reviews and the specific protocol components covered by each one.

| Sky component | Listed review firms       |
| ------------- | ------------------------- |
| USDS          | ChainSecurity and Cantina |
| sUSDS         | ChainSecurity and Cantina |
| LitePSM       | ChainSecurity and Cantina |

LitePSM is part of Sky’s infrastructure for converting between USDS and supported stablecoins. Its security reviews are part of Sky’s audit record, rather than audits of the Osero Earn.

### What reviews cannot prove

Audits, formal checks, and bug bounty reports can reduce uncertainty, but they cannot prove that software is free from bugs or that every route will work as expected. They also do not guarantee that users will not lose funds. \
\
Review the current app details and [Sky's User Risk Documentation](https://docs.sky.money/legal/skybase-international/user-risks) before signing.
