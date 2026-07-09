# DeFi Vault Safety Brief — 2026-07-09

**No safety alerts.** Steakhouse USDT/USDC Morpho vaults and Maple syrupUSDC remain clean — no exploits, pauses, oracle failures, or new incidents since July 8.

## New since last brief (2026-07-08)

- **NEW, SAFETY:** Summer.fi published its Lazy Summer post-mortem — root cause was an operational offboarding error (an impaired Ark left in the vault's price calc after its cap was zeroed), not a smart-contract bug; attacker spent ~3 months prepping, using stale tokens from November's Stream Finance collapse to inflate vault value ~9.5% and drain $6.04M. Confirms no Morpho-core, Steakhouse, or Maple exposure. [Summer.fi post-mortem](https://blog.summer.fi/arbitrum-usdc-vault-post-mortem-what-happened-and-what-comes-next/) · [CryptoTimes](https://www.cryptotimes.io/2026/07/08/6m-lazy-summer-exploit-traces-back-to-novembers-stream-finance-collapse/)
- **OPERATIONAL:** Steakhouse's curator footprint keeps growing — new Steakhouse-curated USDG vault live on Robinhood Chain via Robinhood Earn (~$17M TVL, 1,600+ depositors in 6 days) and Steakhouse vaults now accessible through Elwood's institutional portfolio module; Steakhouse now curates ~$1.5B (~53% of Morpho stablecoin TVL). Doesn't touch the Ethereum USDT/USDC vaults held. [fintech.global](https://fintech.global/2026/07/07/robinhood-taps-morpho-to-power-new-onchain-earn-product/)

## Still active / unresolved

- **Morpho AlphaUSDC Delta V2 vault $18M loss (msY/MSUSD collapse)** — msY/USDC market still at 100% utilization, effectively frozen; no full recovery confirmed; Steakhouse USDT (0xbEef047a…) and USDC (0xBEEF0173…) vaults confirmed unaffected. [CryptoBriefing](https://cryptobriefing.com/morpho-blue-vault-msy-collapse-loss/) · [crypto.news](https://crypto.news/mainstreet-defends-msusd-backing-after-85-price-drop/)
- **Summer.fi Lazy Summer vaults** — remain paused; governance now deciding on user compensation and safe resumption timeline following the post-mortem; still zero exposure for Steakhouse/Maple.
- **Resolv USR make-whole** — 4.38M USDC claimable via Merkl through Aug 26; Re7 Labs opened a separate 223K USDC pool for March USR exploit victims; Steakhouse zero exposure.
- **Aave post-rsETH/KelpDAO bad-debt cleanup** — LlamaRisk's binding 4-layer risk framework still moving through governance since June; USDC/USDT mainnet liquidity normal.
- **EU MiCA/USDT fallout** — USDT remains delisted from MiCA-licensed EU exchanges (Coinbase, Kraken, Crypto.com, Revolut by Aug 31) since July 1; USDC/EURC unaffected; no impact to Ethereum mainnet USDT contract or Steakhouse USDT vault.

**Bottom line:** Holdings clean, no action needed — the Summer.fi post-mortem confirms zero Steakhouse/Maple exposure and points to an operational (not contract) flaw; msY/AlphaUSDC remains the key unresolved ecosystem risk to watch.
