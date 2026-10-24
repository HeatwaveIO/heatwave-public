# Heatwave public snapshot 2026-10-24T15:23:31Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.127% | 6.673 | 1 | 2026-10-24T15:21:32+00:00 |  |
| propr_h6 | live | -2.963% | 3.037 | 1 | 2026-10-24T15:21:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-24T15:22:52+00:00 | HyroError: list_challenges: Could not reach the HyroTrader API: Request timed out after 15000ms.. Check the network and the HYRO_API_URL setting, then retry. |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.948% |  | 0 | 2026-10-24T15:21:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | DOGE | SHORT | 0.075461 | 0.075319 | 0.066 | 0.073857 (+0.75R) | False | 2026-10-25T00:55Z | urn:prp-order:yxCnX2pzCiPu @ 0.0776 | urn:prp-order:TZ8xYSoVZLQL @ 0.069044 |
| propr_h6 | DOGE | SHORT | 0.075461 | 0.075353 | 0.05 | 0.073857 (+0.75R) | False | 2026-10-25T00:55Z | urn:prp-order:HgiZRuZrk2yx @ 0.0776 | urn:prp-order:zVd1HjePoXYv @ 0.069044 |

## Signal scan 2026-10-24T02:00Z .. 2026-10-24T15:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-24T07:00Z | kPEPE | LONG | 1 | 3.425 | 1.79 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-24T10:00Z | NEAR | SHORT | 1 | 4.541 | 2.31 | placed_not_filled (expired) | placed_not_filled (expired) | open -0.29R so far |
| 2026-10-24T15:00Z | DOGE | SHORT | 1 | 4.023 | 2.835 | placed_not_filled (resting) | placed_not_filled (resting) | pending |
| 2026-10-24T15:00Z | NEAR | SHORT | 2 | 3.365 | 5.092 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | SOL | SHORT | 3 | 2.714 | 1.847 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | ETH | SHORT | 4 | 2.512 | 1.744 | not_top1 | not_top1 |  |

