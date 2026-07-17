# DeFi Vault Safety Brief — 2026-07-17

**No safety alerts on holdings.** Steakhouse USDT/USDC Morpho vaults and Maple syrupUSDC remain clean — today's only wrinkles were a brief Morpho front-end outage (no on-chain impact) and another unrelated-protocol exploit.

## New since last brief (2026-07-16)

- **SAFETY (NEW, unrelated protocol):** Cascade (Polychain/Variant-backed Arbitrum "neo-brokerage") had its CLS vault hacked for $1.34M USDC on July 16 — funds laundered via Solana back to Ethereum as DAI; fourth exploit this month after Ostium, Summer.fi, and Bonzo; zero Steakhouse/Maple/Aave exposure. [CryptoTimes](https://www.cryptotimes.io/2026/07/16/polychain-backed-cascade-hacked-for-1-34m-in-locked-user-funds/)
- **OPERATIONAL (NEW):** Morpho's web app and API went down for ~3 hours on July 16 from a broad AWS CloudFront outage (also hit Hugging Face, UK National Lottery); on-chain lending contracts and Steakhouse vaults unaffected, no funds lost, fully restored. [crypto.news](https://crypto.news/morpho-restores-app-and-api-after-suspected-aws-cloudfront-outage/)

## Still active / unresolved

- **Morpho AlphaUSDC Delta V2 vault $18M loss (msY/MSUSD collapse)** — msY/USDC market still at 100% utilization, effectively frozen; no full recovery confirmed; Steakhouse USDT (0xbEef047a…) and USDC (0xBEEF0173…) vaults confirmed unaffected. [CryptoBriefing](https://cryptobriefing.com/morpho-blue-vault-msy-collapse-loss/)
- **Lazy Summer Protocol wind-down** — DAO must still decide protocol's future and compensation for the remaining ~$4M USDC; Summer.fi itself shutting down by Aug 31; zero exposure for Steakhouse/Maple.
- **Resolv USR make-whole** — recovery plan pays pre-incident USR/wstUSR holders 1:1 in USDC (post-incident holders 1:0.5); claims process via Merkl continues through Aug 26; Steakhouse zero exposure. [Resolv Labs](https://x.com/ResolvLabs/status/2036151331950604534)
- **Aave post-rsETH/KelpDAO bad-debt cleanup** — LlamaRisk's binding 4-layer risk framework still in community feedback, not yet at Snapshot vote; USDC/USDT mainnet liquidity normal. [Aave governance](https://governance.aave.com/t/arfc-aave-risk-framework/25114)
- **EU MiCA/USDT fallout** — Revolut remains the last major EU holdout: new USDT deposits stop July 30, forced fiat conversion of remaining balances by Aug 31; USDC/EURC and the Ethereum mainnet USDT contract unaffected.

**Bottom line:** Holdings clean, sixth quiet day in a row for Steakhouse/Maple directly — Cascade's exploit extends the July attack wave to watch (still zero holdings exposure), and Morpho's outage was infrastructure-only with no on-chain or fund impact; msY/AlphaUSDC and the Aave risk-framework vote remain the key unresolved ecosystem items.
