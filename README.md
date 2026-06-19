# l1-radar-snapshot

Auto-generated **public data feed** for the *L1 Chain Radar* daily cloud routine.

`snapshot.json` holds the latest single-day cross-chain snapshot (TVL, stablecoin mcap,
DEX volume, fees, active addresses, tx count, native price + cross-chain shares and
day-over-day share deltas) for ~31 L1/L2 chains, plus total market mcap and dominance.

All figures are re-aggregated from **public APIs** (DeFiLlama, CoinGecko, growthepie). No
proprietary content lives here — the analytical design docs are kept in a separate private repo.

Regenerated nightly by `main.py export-snapshot` in the local L1 dashboard project and pushed here.
The routine reads it via the raw URL:
`https://raw.githubusercontent.com/bluesinsoul/l1-radar-snapshot/main/snapshot.json`
