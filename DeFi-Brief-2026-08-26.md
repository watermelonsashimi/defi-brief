# DeFi Vault Safety Brief — 2026-08-26

**No losses to holdings.** Steakhouse USDT/USDC and Maple syrupUSDC are unaffected — but a Morpho oracle-exploit liquidation cascade hit a Steakhouse-curated market yesterday (no bad debt) and a separate governance attack drained a Morpho-linked vault elsewhere.

## New since last brief (2026-08-25)

- **[NEW] Morpho PT-reUSD TWAP oracle exploit — $36.4M liquidated (Aug 25, 04:28-08:00 UTC).** A wallet manipulated Pendle's YT-reUSD price, moving the 15-min TWAP oracle on a Morpho market that accepts PT-reUSD as collateral and is curated by Steakhouse; 33 liquidations across ~19-20 borrowers, no bad debt. Steakhouse confirmed lenders in its vaults were unaffected, briefly pulled funds from the market, then restored them. [CryptoTimes](https://www.cryptotimes.io/2026/08/25/morphos-15-minute-twap-oracle-exploited-in-36-4m-liquidation-attack/) / [CryptoBriefing](https://cryptobriefing.com/morpho-liquidations-pendle-reusd-cascade/)
- **[NEW] Term Finance governance attack — $8.5M drained (Aug 23-24).** Attacker bought majority voting power for ~$951, passed malicious proposals, drained Term's Yearn V3 Meta Vaults incl. a Parity Core ETH vault with allocations spread across Morpho lending markets ($6.8M withdrawn); Term shut down all its Meta Vaults. Not Steakhouse/Maple; no reported Morpho bad debt. [CoinDesk](https://www.coindesk.com/markets/2026/08/24/ethereum-lending-app-term-finance-loses-usd8-5-million-after-attacker-buys-voting-power) / [Cointelegraph](https://cointelegraph.com/news/term-finance-8-5m-vault-governance-exploit)
- **Aave Snapshot passed** for the 50-reserve deprecation + 6-chain wind-down (923,400 votes for, <1% against) — moves to binding on-chain vote next; mainnet USDC/USDT markets unaffected. [Aave governance](https://governance.aave.com/t/arfc-aave-risk-framework/25114)
- **Aave Risk Stewards proposal (TokenLogic, Aug 24)** to adjust stablecoin interest-rate curves across markets, incl. USDC/USDT. [Aave governance](https://governance.aave.com/t/risk-stewards-august-2026-stablecoin-interest-rate-adjustments/25519)

## Still active / unresolved

- **Morpho AlphaUSDC Delta V2 vault $18M loss (msY/MSUSD collapse)** — msY/USDC market still frozen at 100% utilization, peg not restored (msUSD ~$0.25-0.33); Steakhouse USDT/USDC vaults confirmed unaffected. [CryptoBriefing](https://cryptobriefing.com/morpho-blue-vault-msy-collapse-loss/)
- **Resolv USR make-whole claims** — final day (Aug 26) to claim via Merkl/recovery portal; Steakhouse zero exposure.
- **Aave risk-framework rollout** — LlamaRisk's binding 4-layer framework still in community feedback, not yet Snapshot.
- **EU MiCA/USDT fallout** — Revolut's forced fiat conversion of EEA/Switzerland USDT balances due by Aug 31; Ethereum mainnet USDT contract unaffected.

**Bottom line:** Steakhouse/Maple holdings took no losses, but the PT-reUSD TWAP exploit is a live demonstration of oracle-manipulation risk on a Steakhouse-curated Morpho market (contained this time) and the Term Finance governance attack is a fresh precedent for vote-buying attacks on Morpho-linked vaults — both worth watching even though neither hit our vaults directly; Resolv's claims window closes today.
