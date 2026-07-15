# DeFi Vault Safety Brief — 2026-07-15

**No safety alerts.** Steakhouse USDT/USDC Morpho vaults and Maple syrupUSDC remain clean — no exploits, pauses, oracle failures, or new incidents since July 14.

## New since last brief (2026-07-14)

- **OPERATIONAL:** Summer.fi published its post-mortem on the July 6 Lazy Summer $6M exploit — confirmed root cause is stale on-chain NAV pricing on Silo vault tokens tainted by November 2025's Stream Finance collapse, exploited via a ~3-month premeditated attack (not a code bug); compensation still undecided by governance. Zero Steakhouse/Maple exposure. [Summer.fi post-mortem](https://blog.summer.fi/lazy-summer-usdc-vault-exploit-post-mortem-what-happened-and-what-comes-next/) · [Summer forum retrospective](https://forum.summer.fi/t/lazy-summer-protocol-exploit-july-6-2026-ba-labs-risk-curator-retrospective/856)
- **OPERATIONAL:** Steakhouse's H1 2026 recap: zero bad debt across all curated vaults through June 30 despite the Resolv exploit and Aave rsETH bad-debt event; total deposits grew $1.55B→$1.7B; Robinhood Chain USDG vault now ~6,000 depositors. Confirms continued clean track record for the curator behind the Steakhouse USDT/USDC vaults. [Steakhouse Kitchen](https://kitchen.steakhouse.financial/p/defi-markets-update-2026-07-14)

## Still active / unresolved

- **Morpho AlphaUSDC Delta V2 vault $18M loss (msY/MSUSD collapse)** — msY/USDC market still at 100% utilization, effectively frozen; no full recovery confirmed; Steakhouse USDT (0xbEef047a…) and USDC (0xBEEF0173…) vaults confirmed unaffected. [CryptoBriefing](https://cryptobriefing.com/morpho-blue-vault-msy-collapse-loss/) · [crypto.news](https://crypto.news/mainstreet-defends-msusd-backing-after-85-price-drop/)
- **Summer.fi Lazy Summer vaults** — root cause now confirmed (see above); redemption RFC for the remaining ~$4M USDC and compensation decision still pending DAO vote; zero exposure for Steakhouse/Maple. [Summer.fi forum RFC](https://forum.summer.fi/t/rfc-next-steps-for-exploited-usdc-vaults-on-ethereum/855)
- **Resolv USR make-whole** — 4.38M USDC claimable via Merkl through Aug 26; Re7 Labs' separate 223K USDC pool for March USR victims also open; Steakhouse zero exposure.
- **Aave post-rsETH/KelpDAO bad-debt cleanup** — LlamaRisk's binding 4-layer risk framework (V3/V4/Horizon, $50K bug-bounty floor, 3-verifier bridge minimum) still in community feedback, not yet at Snapshot vote; USDC/USDT mainnet liquidity normal. [Aave governance](https://governance.aave.com/t/arfc-aave-risk-framework/25114)
- **EU MiCA/USDT fallout** — Revolut remains the last major EU holdout: USDT purchases halted July 6, new deposits stop July 30, forced fiat conversion of remaining balances by Aug 31; USDC/EURC and the Ethereum mainnet USDT contract unaffected.

**Bottom line:** Holdings clean, fifth quiet day in a row — Summer.fi's post-mortem and Steakhouse's clean H1 recap are the only incremental developments; msY/AlphaUSDC and the Aave risk-framework vote remain the key unresolved ecosystem items to watch; nothing touches Steakhouse or Maple.
