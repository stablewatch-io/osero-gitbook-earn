---
icon: shield
---

# Capital Protection

Sky Protocol's risk management framework is inspired by **Basel III** — the international banking regulation standard that governs capital adequacy requirements at traditional financial institutions. This framework introduces a structured, tiered approach to loss absorption that protects depositors even in the event of a position impairment.

***

## The Basel III-inspired framework

Under Basel III, banks are required to hold capital buffers in proportion to the risk of their assets. If a loan goes bad, the bank's own capital absorbs the loss before depositors are affected. Sky Protocol applies the same logic to its allocation strategies.

Allocations backing USDS and sUSDS are made by specialised economic actors within the Sky Ecosystem called **Agents**. Agents are authorised to borrow USDS from Sky Protocol in order to deploy capital across approved strategies. In exchange for this borrowing capacity, Agents are subject to strict capital requirements.

***

## Junior Risk Capital — held by Agents

Agents are required to hold **Junior Risk Capital** proportional to the inherent risk of each underlying investment they manage. This capital sits "junior" in the loss-absorption stack, meaning it is the first to absorb losses if a position is impaired.

The amount of junior capital required scales with the risk profile of the underlying asset, riskier allocations require proportionally more risk capital from the managing Agent. This creates a strong incentive alignment: Agents bear the first loss, so they are economically motivated to manage risk carefully.

***

## Senior Risk Capital — held by Sky Protocol

Sky Protocol itself holds **Senior Risk Capital** as an additional layer of protection. This capital sits above the junior layer and provides a further backstop in scenarios where losses exceed the Agent's junior capital.

***

## The loss-absorption stack

In the event that a position managed by a Agent suffers an impairment, losses are absorbed in the following order:

<figure><img src="../.gitbook/assets/OS_Image_The loss-absorption stack.png" alt=""><figcaption></figcaption></figure>

This structure means that a position would need to wipe out both the Agent's capital and Sky Protocol's senior capital before any loss reaches depositors — a meaningfully higher barrier than all other DeFi yield products provide.

***

## The Risk Capital feed

Osero Earn's [Transparency SDK](backing-transparency.md) surfaces this structure in real time through the Risk Capital feed, which provides:

* A live breakdown of all junior and senior risk capital positions under the Sky Savings Rate
* Attribution by entity (which Agent holds which capital)
* Real-time values for each capital position

Stablecoin platforms can integrate this feed into their product UI to communicate the loss-absorption structure to their users in a clear, auditable way — a transparency standard that is familiar to institutional clients and increasingly valued by sophisticated retail users.
