<!--
  GitHub Organization profile README
  Repo: AnyPerp/.github → profile/README.md
  Renders on https://github.com/AnyPerp
-->

<div align="center">

<img src="https://raw.githubusercontent.com/AnyPerp/anyperp/main/public/logo/anyperp-logo.svg" alt="AnyPerp" width="72" height="72" />

# AnyPerp

**Any token. A perp. Today.**

Permissionless, isolated perpetual markets on Robinhood Chain.

[Website](https://anyperp.fun) · [App](https://anyperp.fun/?surface=app) · [Docs](https://anyperp.fun/?surface=docs) · [Main repository](https://github.com/AnyPerp/anyperp) · [X](https://x.com/tradeanyperp)

<br />

<img src="https://raw.githubusercontent.com/AnyPerp/anyperp/main/public/github/github-og-light.png" alt="AnyPerp" width="100%" />

<br />

![status](https://img.shields.io/badge/status-testnet%20prototype-2d6a4f?style=flat-square)
![audit](https://img.shields.io/badge/audit-unaudited-6c757d?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-0b7285?style=flat-square)
![chain](https://img.shields.io/badge/chain-Robinhood%20testnet%2046630-1b4332?style=flat-square)

</div>

---

## Contributors

<table>
  <tr>
    <td align="center" width="140">
      <a href="https://github.com/tradeanyperp">
        <img src="https://github.com/tradeanyperp.png?size=100" width="72" height="72" alt="tradeanyperp" /><br />
        <b>tradeanyperp</b>
      </a>
      <br /><sub>Protocol · product</sub>
    </td>
    <td align="center" width="140">
      <a href="https://github.com/CallMESuper">
        <img src="https://github.com/CallMESuper.png?size=100" width="72" height="72" alt="CallMESuper" /><br />
        <b>CallMESuper</b>
      </a>
      <br /><sub>Super</sub>
    </td>
    <td align="center" width="140">
      <a href="https://github.com/nmayorga092">
        <img src="https://github.com/nmayorga092.png?size=100" width="72" height="72" alt="nmayorga092" /><br />
        <b>nmayorga092</b>
      </a>
      <br /><sub>Nicolás</sub>
    </td>
  </tr>
</table>

---

## What is AnyPerp?

AnyPerp is a **factory for isolated, oracle-priced perpetual markets**. A creator points at an existing ERC-20 on Robinhood Chain, picks a registered oracle route and risk tier, posts a bond, seeds market-local LP and insurance capital, and activates trading only when mechanical checks pass.

| | |
|---|---|
| **Product** | Isolated peer-to-pool perps (one market = one risk container) |
| **Network** | Robinhood Chain testnet `46630` (EVM / Arbitrum-style L2) |
| **Collateral** | Supported USD-style collateral only in the MVP (no coin margin) |
| **Affiliation** | **Not** a Robinhood product; not endorsed by Robinhood Markets, Inc. |
| **Safety** | Unaudited engineering prototype — **do not use real funds** |

Open factory ≠ open liability. Anyone may deploy a candidate; the contracts activate only after oracle quality, capital buffers, and tier envelopes clear.

---

## Core capabilities

| Capability | Description |
|---|---|
| **Permissionless create** | Any account can deploy a market candidate with bond + salt (CREATE2). |
| **Mechanical activation** | Validate → seed LP/insurance → activate only if oracle + capital + tier pass in-tx. |
| **Isolated vaults** | Per market: collateral vault, LP vault, insurance fund — no cross-market debit. |
| **Oracle-priced execution** | Index from registered adapters; fill at index ± bounded skew impact. |
| **Risk tiers** | Blue-chip → experimental envelopes; creators may tighten, never loosen. |
| **Governance** | Timelocked parameters; guardian can only pause / reduce-only. |

---

## Explore

- **Website:** [anyperp.fun](https://anyperp.fun)
- **Source:** [github.com/AnyPerp/anyperp](https://github.com/AnyPerp/anyperp)
- **X:** [@tradeanyperp](https://x.com/tradeanyperp)

---

<div align="center">

**AnyPerp** is open source under the [MIT License](https://github.com/AnyPerp/anyperp/blob/main/LICENSE).

Not affiliated with Robinhood. Unaudited. Testnet research only.

</div>
