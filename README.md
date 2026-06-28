# L1 Radar Feed

Machine-written daily snapshot of cross-chain L1/L2 metrics, distilled from the local
`CoinResearch/L1` pipeline (`chains.db`: DeFiLlama TVL/stablecoins/DEX/fees, CoinGecko
prices, growthepie/Dune activity). Consumed by the **L1 Chain Radar** cloud routine,
which can't reach those APIs directly.

- `snapshot.json` — latest day + day-over-day share deltas for the tracked chains.
- `design-docs/*.md` — per-chain metric guidelines the routine follows.

Raw signals only — no composite scores. `null` means NO DATA (not zero). Overwritten daily.
