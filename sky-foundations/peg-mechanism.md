---
icon: scale-unbalanced
---

# Peg Mechanism

### Who manages the USDS peg

Osero does not manage the USDS peg. Sky supports the peg through its underlying assets, liquidity, protocol mechanisms, and governance.

Osero provides an interface for accessing supported routes. It does not set Sky’s exchange terms or control the market price of USDS.

### What Lite Peg Stability Module (LitePSM) does

The Lite Peg Stability Module, or LitePSM, lets users swap USDS for stablecoins such as USDC. Sky governance sets the exchange ratios and fees.

USDS can also be converted at a 1:1 rate through the Sky converter. This is separate from Osero, and not every Osero route uses it.

### How market alignment can work

The steps below show one possible way market activity can support price alignment. They are not a guarantee that a route will be available or useful.

{% stepper %}
{% step %}
#### USDS moves away from its target value

Market prices can move. A price difference does not automatically mean a usable swap is available.
{% endstep %}

{% step %}
#### A participant checks the current LitePSM route

They review the asset, exchange ratio, fee, and current limits.
{% endstep %}

{% step %}
#### The participant may swap when the route makes economic sense

The decision depends on the current conditions and risks. It is separate from any route prepared through Osero.
{% endstep %}

{% step %}
#### This activity can help move the price closer to its target

Swaps can support market alignment, but they cannot force a fixed price or immediate redemption.
{% endstep %}
{% endstepper %}

### Limits of the mechanism

Sky’s backing, liquidity, and governance settings can change over time. Market conditions, networks, contracts, and counterparties can also affect how the system operates.

No peg mechanism guarantees a fixed market price or immediate redemption.

Read the [Sky LitePSM guide](https://developers.skyeco.com/guides/psm/litepsm/), [USDS documentation](https://developers.skyeco.com/protocol/tokens/usds/), and [User Risk Documentation](https://docs.sky.money/legal/skybase-international/user-risks) before using a savings product.
