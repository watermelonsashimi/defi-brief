# DeFi Vault Safety Brief — 2026-09-26

**No safety alerts on holdings.** Steakhouse USDT/USDC Morpho vaults and Maple syrupUSDC remain clean — no new developments touching them.

## New since last brief (2026-09-25)

- **Aave V4 launches "Equities Hub" on Base (operational, watchlist, not holdings)** — Coinbase-issued tokenized stocks (AAPL, AMZN, GOOGL, META, MSFT, NVDA, TSLA) now usable as collateral to borrow USDC; capped at ~$29M collateral / ~$32M USDC supply / ~$21M borrow, isolated risk params per stock. [The Block](https://www.theblock.co/news/defi/2026-09-25-aave-v4-on-base-adds-coinbase-tokenized-stocks-as-collateral-for-usdc-loans-416372)

## Still active / unresolved

- **Aave V4 emergency-powers Snapshot vote (watchlist, not holdings)** — vote closed Sept 6 with reported ~645k votes in favor; still requires separate Security Council execution plus a still-finalizing Certora audit of the Risk Steward contracts before any powers are usable. [CryptoSlate](https://cryptoslate.com/aave-lending-proposal-would-grant-emergency-powers-without-requiring-public-reports-on-their-use/)
- **Aave V4 "Umbrella" bad-debt backstop proposal (TokenLogic, watchlist, not holdings)** — would have Aave's DAO absorb losses first for Core WETH/USDC/USDT markets on Ethereum; still in governance, no confirmed pass/activation yet. [CryptoSlate](https://cryptoslate.com/aave-v4-proposal-would-put-dao-funds-first-in-line-to-absorb-lending-losses/)
- **Aave USDT0 liquidity crunch on Monad (watchlist, not holdings)** — pool still deep in a liquidity crunch (~$4.4M withdrawable of a ~$55.9M pool, ~$51.5M borrowed, ~92% utilization); not a governance freeze, and does not touch Ethereum mainnet Steakhouse/Maple vaults. [KuCoin](https://www.kucoin.com/news/insight/USDT/6aa9256c7d10fa0007cda2c0)
- **Unconfirmed Morpho Blue "rebalance sandwich" report (Brinztech)** — single-source claim of a WETH/ENS flash-loan exploit on an unnamed vault (~13,178 shares minted); still no corroboration from Morpho, PeckShield, SlowMist, or rekt.news; no indication it touches Steakhouse vaults. [Brinztech](https://www.brinztech.com/breach-alerts/brinztech-alert-forensic-analysis-reveals-complex-exploit-mechanism-targeting-morpho-blue-vaults)
- **Term Finance governance attack ($8.5M, Aug 23-24)** — Term Labs shut down the exploited Meta Vaults and blocked new deposits (withdrawals still open); no new update found — still no full technical postmortem, though ~556 ETH recovery and reimbursement pledge stand as last reported. Not Steakhouse/Maple, no Morpho core bad debt. [crypto.news](https://crypto.news/term-labs-recovers-fixed-rate-positions-after-8-5m-governance-attack/)
- **Morpho AlphaUSDC Delta V2 vault $18M loss (msY/MSUSD collapse)** — msY/USDC market still frozen at 100% utilization, curator AlphaPing's collateral-verification service still offline, no unfreeze or backstop announced; Steakhouse USDT/USDC vaults confirmed unaffected. [CryptoBriefing](https://cryptobriefing.com/morpho-blue-vault-msy-collapse-loss/)

**Bottom line:** Holdings clean; the only new item is Aave's Base Equities Hub launch (tokenized-stock collateral for USDC), which doesn't touch Steakhouse or Maple. All prior open threads — the emergency-powers vote execution, the Umbrella proposal, the Monad USDT0 crunch, the unconfirmed Brinztech report, Term Finance's reimbursement, and the frozen msY/USDC Morpho market — remain unresolved but unchanged.
