# DeFi Vault Safety Brief — 2026-06-06

**Safety alert (indirect / market-wide):** No exploit, pause, freeze, bad debt, oracle failure, or admin-key issue touching your Steakhouse USDT/USDC Morpho vaults, Morpho core, Maple, or Aave USDC/USDT markets. BUT a broad crypto selloff and a new STRC-backed stablecoin depeg are stressing the Morpho/DeFi-lending ecosystem this week — neither hits your held vaults directly, but both are worth watching.

## New since last brief (2026-06-05)

**Safety**

- **[NEW, last 24h] Market-wide liquidation cascade.** BTC fell below ~$64k (briefly under $63k); >$1.1B liquidated across crypto in 24h, $1.66B hitting DeFi tokens. Aave dropped ~4.1% on the tape but with **no protocol-specific failure, exploit, or governance event** — just risk-off + leverage unwind. Your USDT/USDC vaults lend against collateral, so watch for elevated liquidation/utilization activity if BTC keeps sliding. [CoinMarketCap](https://coinmarketcap.com/top-stories/6a1fcbefc3b57139305ddb43/) · [Crypto Briefing](https://cryptobriefing.com/bitcoin-falls-below-64000-triggers-11b-in-liquidations/)
- **Apyx apxUSD depeg to ~$0.93 (June 4).** STRC-backed (Strategy preferred-equity) synthetic dollar slipped off peg when STRC fell ~2% and BTC dropped. Triggered fears of cascading liquidations in **Morpho** lending markets. Apyx says its isolated apyUSD/apxUSD Morpho market oracle is driven by **dividend accrual, not STRC spot**, so STRC volatility doesn't trigger liquidations there; calls it "a feature, not a bug." apxUSD DeFi exposure is concentrated in Pendle (~$118M) and Curve (~$45M) — **no evidence of exposure in your Steakhouse USDT/USDC vaults** (isolated Morpho market). New systemic-risk vector (equity-backed stablecoins) worth tracking. [CoinDesk](https://www.coindesk.com/markets/2026/06/04/apyx-s-stablecoin-suffers-a-brief-depeg-protocol-says-its-a-feature-not-bug) · [The Defiant](https://thedefiant.io/news/defi/apxusd-loses-dollar-peg-bitcoin-slide-strc-backed-collateral)

**Operational**

- **Ether.fi weETH live as collateral in Steakhouse Prime vaults on Morpho** (weETH/USDC, weETH/USDT, weETH/ETH pairs). New collateral exposure in the Steakhouse Prime line — relevant to keep an eye on, though separate from your specific USDT/USDC vault addresses. [Steakhouse on Morpho](https://morpho.org/stories/steakhouse/)
- **Steakhouse High Yield V2 (Base) weekend liquidity squeeze.** Capital reallocated into cbXRP/SOL/cbDOGE markets where available liquidity fell near zero vs market size; rates spiked >20%. This is the Base HY vault, **not** your Ethereum USDT/USDC vaults, but signals how thin liquidity gets under stress. [Steakhouse Kitchen 2026-06-02](https://kitchen.steakhouse.financial/p/defi-markets-update-2026-06-02)

**General**

- USDT/USDC pegs holding ~$1.00 through the selloff. No issuer-side stress on Tether or Circle this window.

## Still active / unresolved

- **Resolv USR make-whole (orig. March 22 exploit, ~$25M / ~80M unbacked USR).** Steakhouse confirmed zero direct exposure in its main vaults — your USDT/USDC vaults unaffected. Tiered compensation plan (announced May 27) still rolling out; post-mortem fixes (mint caps, auto-pauses) ongoing. Tracking only. [OAK Research](https://oakresearch.io/en/analyses/investigations/the-resolv-usr-hack-curators-face-their-responsibilities)
- **Aave USDC utilization / Circle governance.** After April's KelpDAO-driven liquidity crunch, Circle's chief economist proposed recalibrating USDC parameters amid prolonged ~99–100% utilization. Aave reported liquidity fully restored by June via a $300M recovery fund. Watch USDC rate/utilization dynamics if this week's selloff re-pins utilization. [The Block](https://www.theblock.co/post/398577/circle-chief-economist-floats-higher-usdc-rates-on-aave-amid-kelpdao-fallout) · [Cryptopolitan](https://www.cryptopolitan.com/circle-steps-into-aave-governance/)

**Bottom line:** Your Steakhouse USDT/USDC vaults remain clean — no direct safety events. The week's risks are environmental: a market-wide liquidation cascade (BTC sub-$64k) and an isolated STRC-backed stablecoin depeg (apxUSD) that so far stays contained to its own Morpho market and Pendle/Curve, not your vaults.
