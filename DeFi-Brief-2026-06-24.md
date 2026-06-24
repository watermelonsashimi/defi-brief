# DeFi Vault Safety Brief — 2026-06-24

**No safety alerts.** Steakhouse USDT/USDC Morpho vaults and Maple syrupUSDC remain clean — no exploits, pauses, oracle failures, or curator/admin-key issues.

## New since last brief (2026-06-23)

**General DeFi Security**

- **jaredfromsubway.eth MEV bot drained $15M via honeypot (June 22)** — Attacker deployed 66 fake token contracts mimicking WETH/USDC/USDT to trick the bot's automated approval mechanism; funds laundered via Tornado Cash. No impact on tracked vaults — Morpho, Steakhouse, Maple, and Aave USDC/USDT pools unaffected. [CryptoTimes](https://www.cryptotimes.io/2026/06/22/ethereum-mev-bot-jaredfromsubway-drained-in-15m-honeypot-attack/) · [BleepingComputer](https://www.bleepingcomputer.com/news/security/jaredfromsubway-mev-bot-hacked-in-15-million-crypto-theft/)

## Still active / unresolved

- **Resolv USR make-whole** — 4.38M USDC claimable via Merkl until Aug 26; Steakhouse zero exposure.
- **Aave post-rsETH listing reform** — tighter bridge/oracle standards and cap reductions ongoing; USDC/USDT mainnet liquidity normal.

**Bottom line:** Holdings clean; notable June 22 MEV bot honeypot ($15M, jaredfromsubway.eth) is isolated from tracked vault infrastructure — no new safety or operational items for Steakhouse, Morpho, or Maple since yesterday.
