# Heatwave public snapshot 2026-10-24T22:38:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.493% | 7.039 | 2 | 2026-10-24T22:38:34+00:00 |  |
| propr_h6 | live | -3.862% | 2.138 | 1 | 2026-10-24T22:37:42+00:00 |  |
| hyro_h6 | h6.16-hyro | -2.042% |  | 0 | 2026-10-24T22:37:52+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 3.18% |  | 0 | 2026-10-24T22:36:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | DOGE | SHORT | 0.074948 | 0.077307 | -0.89 | 0.072959 (+0.75R) | False | 2026-10-25T00:55Z | urn:prp-order:HPFrw3oytQeE @ 0.0776 | urn:prp-order:ht95EavDiPPx @ 0.069044 |
| propr_2s | kPEPE | LONG | 0.004347 | 0.00451 | 1.495 | 0.004429 (+0.75R) | True | 2026-10-25T01:55Z | urn:prp-order:eNzekxE3Fskx @ 0.004429 | urn:prp-order:7DT4dhEEiFfC @ 0.004626 |
| propr_h6 | DOGE | SHORT | 0.074947 | 0.077307 | -0.89 | 0.072957 (+0.75R) | False | 2026-10-25T00:55Z | urn:prp-order:hQRWa4Mk6Ho4 @ 0.0776 | urn:prp-order:PHBTXv7xhgMg @ 0.069044 |

## Signal scan 2026-10-24T09:00Z .. 2026-10-24T22:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-24T10:00Z | NEAR | SHORT | 1 | 4.541 | 2.31 | placed_not_filled (expired) | placed_not_filled (expired) | closed -0.6955R |
| 2026-10-24T15:00Z | DOGE | SHORT | 1 | 4.023 | 2.835 | filled | filled | open -0.905R so far |
| 2026-10-24T15:00Z | NEAR | SHORT | 2 | 3.365 | 5.092 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | SOL | SHORT | 3 | 2.714 | 1.847 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | ETH | SHORT | 4 | 2.512 | 1.744 | not_top1 | not_top1 |  |
| 2026-10-24T16:00Z | kPEPE | LONG | 1 | 2.55 | 2.238 | filled | skipped_room_clamp | open 1.477R so far |
| 2026-10-24T16:00Z | ETH | SHORT | 1 | 3.206 | 2.661 | no_breakout | no_breakout | none |
| 2026-10-24T16:00Z | AAVE | SHORT | 2 | 3.005 | 1.718 | not_top1 | not_top1 |  |
| 2026-10-24T19:00Z | kPEPE | LONG | 1 | 3.754 | 2.536 | skipped_slots_full | skipped_room_clamp | open 0.513R so far |
| 2026-10-24T19:00Z | ZEC | SHORT | 1 | 4.266 | 3.494 | armed_waiting_breakout | armed_waiting_breakout | pending |
| 2026-10-24T19:00Z | DOT | SHORT | 2 | 3.424 | 1.544 | not_top1 | not_top1 |  |

