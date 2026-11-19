# Weekly Token Digest

**Repo:** `for-toolathlon/weekly-token-digest`
**Pulled:** 2026-11-19 11:39 UTC (etherscan / Alchemy USD quote)

## Current USD prices

| Token | Current Price | As-of |
| --- | ---: | --- |
| ETH | $1,807.02 | 2026-11-19T11:39:32Z |
| BTC | $64,057.82 | 2026-11-19T11:39:31Z |
| LINK | $9.209 | 2026-11-19T11:39:31Z |
| UNI | $5.225 | 2026-11-19T11:39:29Z |
| USDC | $1.00091 | 2026-11-19T11:36:58Z |

## 7-day change (2026-11-13 → 2026-11-19)

| Token | 7-day Change | 7-day % Change |
| --- | ---: | ---: |
| ETH | (242.25) | -12.00% |
| BTC | (8,375.30) | -11.73% |
| LINK | (1.06325) | -10.49% |
| UNI | (0.88314) | -14.55% |

## USDC contract sanity check

- Symbol quote (USDC rate against ETH/BTC in the latest fetch): $1.00091 (2026-11-19T11:36:58Z)
- Contract quote from address `0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48` on eth-mainnet: $1.001 (2026-11-19T11:38:53Z)
- Difference: $1.001 − $1.00091 = $0.00009 ≈ $0.0001

The contract quote sits within $0.01 of the symbol quote, so USDC's price agreement check resolutions: **MATCH** — the contract and symbol quotes agree to the cent (well inside the $0.01 mismatch threshold).
