# DeFi Vault Safety Brief — 2026-07-07

**No safety alerts for our holdings.** Steakhouse USDT/USDC Morpho vaults and Maple syrupUSDC remain clean; NEW overnight is an unrelated $6M exploit on Summer.fi's Lazy Summer vaults that used a Morpho flash loan as its funding leg — Morpho core unaffected, zero exposure for our vaults.

## New since last brief (2026-07-06)

- **[NEW, SAFETY]** Summer.fi's Lazy Summer Protocol lost ~$6M (July 6) to a share-accounting exploit on its LazyVault_LowerRisk_USDC vault; attacker funded the attack with a $65.4M flash loan sourced from Morpho. Morpho states its own contracts are unaffected and safe; Summer.fi's guardians paused all Lazy Summer vaults. Not a Steakhouse/Morpho-curated vault — no exposure to our holdings. [CoinDesk](https://www.coindesk.com/web3/2026/07/06/defi-protocol-summer-fi-halts-lazy-summer-vaults-after-usd6-million-exploit) · [CryptoTimes](https://www.cryptotimes.io/2026/07/06/summer-finance-hit-by-suspected-flash-loan-exploit-worth-nearly-6m/)

## Still active / unresolved

- **Morpho AlphaUSDC Delta V2 vault $18M loss (msY/MSUSD collapse)** — msY/USDC market still at 100% utilization, effectively frozen; no full recovery confirmed; Steakhouse USDT (0xbEef047a…) and USDC (0xBEEF0173…) vaults confirmed unaffected. [CryptoBriefing](https://cryptobriefing.com/morpho-blue-vault-msy-collapse-loss/) · [crypto.news](https://crypto.news/mainstreet-defends-msusd-backing-after-85-price-drop/)
- **Resolv USR make-whole** — 4.38M USDC claimable via Merkl through Aug 26; Steakhouse zero exposure.
- **Aave post-rsETH/KelpDAO bad-debt cleanup** — LlamaRisk's binding 4-layer risk framework (bug-bounty floor, 3-verifier bridge minimum) still moving through governance since June; cap reductions ongoing via Risk Stewards; USDC/USDT mainnet liquidity normal.
- **EU MiCA/USDT fallout** — USDT remains delisted from MiCA-licensed EU exchanges (Coinbase, Kraken, Crypto.com, Revolut by Aug 31) since July 1; USDC/EURC unaffected; no impact to Ethereum mainnet USDT contract or Steakhouse USDT vault.

**Bottom line:** Holdings clean, no action needed — the Summer.fi hack is a reminder that flash loans drawn against Morpho liquidity can still break poorly-coded vaults elsewhere, but it doesn't touch Steakhouse or Maple; the msY/AlphaUSDC crisis remains the key unresolved ecosystem risk to watch.
