# DeFi Vault Safety Brief — 2026-06-25

**No safety alerts for tracked holdings.** Steakhouse USDT/USDC Morpho vaults and Maple syrupUSDC remain clean. Environmental watch: Aave V3 Pendle PT token matures today — oracle wind-down risk for Aave USDT market.

## New since last brief (2026-06-24)

**Safety**

- **SecondFi (Cardano) wallet exploit — June 24 (NEW):** ~$2.4M drained from 374 wallets, up to $20M at risk; flaw in proprietary wallet-generation software — Cardano only, zero exposure to tracked Ethereum DeFi vaults. [CoinDesk](https://www.coindesk.com/business/2026/06/24/secondfi-loses-usd2-4-million-in-cardano-wallet-exploit-with-up-to-usd20-million-at-risk)

**Operational**

- **Aave V3 — PT-srUSDe-25JUN2026 matures today (NEW):** Pendle PT collateral expires on Aave V3 Core; oracle pricing shifts at maturity and large unborrowed positions must unwind or be liquidated — bad debt risk to Aave's USDT market if positions linger post-maturity. Risk stewards pre-tightened parameters June 12; rollover to PT-srUSDe-22OCT2026 already proposed. Steakhouse vaults hold no PT-srUSDe collateral directly, but Aave USDT pool is watchlist exposure. [Aave Gov — Proposal 466](https://vote.onaave.com/proposal/?proposalId=466) · [Risk Stewards June 12](https://governance.aave.com/t/risk-stewards-pt-parameter-changes-on-aave-v3-2026-06-12/25140)

## Still active / unresolved

- **Aave PT-srUSDe maturity (today):** Monitor Aave V3 Core USDT market for bad debt if large positions fail to unwind post-June 25 maturity.
- **Resolv USR make-whole** — 4.38M USDC claimable via Merkl until Aug 26; Steakhouse zero exposure.
- **Aave post-rsETH listing reform** — tighter bridge/oracle standards and cap reductions ongoing; USDC/USDT mainnet liquidity normal.

**Bottom line:** Tracked vaults clean; two new items — Cardano wallet exploit (SecondFi, no EVM exposure) and Aave V3 PT-srUSDe maturity today (indirect USDT market risk, being managed by risk stewards).
