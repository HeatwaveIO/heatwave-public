# Heatwave public snapshot 2026-10-24T15:13:55Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.127% | 6.673 | 0 | 2026-10-24T15:11:21+00:00 |  |
| propr_h6 | live | -2.963% | 3.037 | 0 | 2026-10-24T15:11:43+00:00 |  |
| hyro_h6 | h6.16-hyro | -2.042% |  | 0 | 2026-10-24T15:12:51+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.948% |  | 0 | 2026-10-24T14:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-24T02:00Z .. 2026-10-24T15:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-24T07:00Z | kPEPE | LONG | 1 | 3.425 | 1.79 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-24T10:00Z | NEAR | SHORT | 1 | 4.541 | 2.31 | placed_not_filled (expired) | placed_not_filled (expired) | open -0.367R so far |
| 2026-10-24T15:00Z | DOGE | SHORT | 1 | 4.023 | 2.835 | armed_waiting_breakout | armed_waiting_breakout | pending |
| 2026-10-24T15:00Z | NEAR | SHORT | 2 | 3.365 | 5.092 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | SOL | SHORT | 3 | 2.714 | 1.847 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | ETH | SHORT | 4 | 2.512 | 1.744 | not_top1 | not_top1 |  |

