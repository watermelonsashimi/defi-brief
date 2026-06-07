# DeFi Vault Safety Brief — 2026-06-05

**No safety alerts.** No new hacks, pauses, depegs, oracle failures, or curator/admin-key issues touching the Steakhouse USDT/USDC Morpho vaults, Morpho core, Maple, or Aave USDC/USDT markets in the last 3 days.

_Note: This is the first brief in this folder — no prior briefs to compare against. Items below are what surfaced in roughly the last 3 days (and recent unresolved context). Safety scan looked back further given no baseline exists._

## New since last brief

**Operational**

- Trezor launched native "Stablecoin Earn" in Trezor Suite — USDC/USDT deposits route into Steakhouse-curated Morpho vaults, signed on-device. Relevant to your held vaults (more deposit inflow / broader retail access via curator). [Steakhouse on Morpho](https://morpho.org/stories/steakhouse/)
- Aave appointed Bitwise as asset issuer for Aave Horizon (tokenized yield fund, institutional access), ~June 2. Governance/ops, no direct USDC/USDT market parameter change. [Aave governance](https://governance.aave.com/t/direct-to-aip-may-june-2026-funding-update/25000)
- Steakhouse published its weekly DeFi Markets Update (2026-06-02) — routine curator market commentary, no safety flags. [Steakhouse kitchen](https://kitchen.steakhouse.financial/p/defi-markets-update-2026-06-02)

**General**

- Maple's new Borrower Hub is live; legacy dashboard sunsets June 30, 2026. Operational migration only, security/compliance preserved end-to-end. [Las Vegas Sun / Maple](https://lasvegassun.com/news/2026/may/21/introducing-the-maple-borrower-hub-the-operating-l/)
- Circle reportedly engaging in Aave governance amid ~99% USDC utilization on Aave (unconfirmed timing/details). Watch for USDC supply/rate dynamics if utilization stays pinned. [Cryptopolitan](https://www.cryptopolitan.com/circle-steps-into-aave-governance/)

## Still active / unresolved

- Resolv USR exploit (originated March 22, 2026; ~$25M extracted, ~80M unbacked USR minted) — ~15 Morpho vaults hit, ~$180M in liquidations, Morpho TVL fell ~$10B→$7B. **Steakhouse confirmed zero direct exposure in its main vaults (your USDT/USDC vaults unaffected).** Gauntlet-curated vaults bore the losses. Resolv compensation/tiered make-whole plan announced May 27 is still rolling out. Tracking only because make-whole and post-mortem fixes (mint caps, auto-pauses) are ongoing. [OAK Research](https://oakresearch.io/en/analyses/investigations/the-resolv-usr-hack-curators-face-their-responsibilities) · [The Defiant](https://thedefiant.io/news/hacks/defi-has-seen-resolv-s-usd25m-usr-exploit-many-times-before)

**Bottom line:** Your Steakhouse USDT/USDC vaults look clean — no safety events in the window, and they avoided the only major recent incident (Resolv); the only items of note are routine operational expansions (Trezor, Aave Horizon).
