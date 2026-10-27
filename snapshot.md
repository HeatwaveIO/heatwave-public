# Heatwave public snapshot 2026-10-27T15:23:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 0.021% | 4.567 | 0 | 2026-10-27T15:23:34+00:00 |  |
| propr_h6 | live | -5.524% | 0.476 | 0 | 2026-10-27T15:23:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-27T15:22:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.896% |  | 0 | 2026-10-27T15:21:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-27T02:00Z .. 2026-10-27T15:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-27T02:00Z | TIA | SHORT | 1 | 2.544 | 2.247 | skipped_off_hours | skipped_off_hours | closed 0.1044R |
| 2026-10-27T04:00Z | WLD | SHORT | 1 | 2.862 | 1.585 | skipped_off_hours | skipped_off_hours | closed 0.3347R |
| 2026-10-27T10:00Z | ENA | SHORT | 1 | 3.495 | 2.994 | armed_waiting_breakout | armed_waiting_breakout | closed -1.0393R |
| 2026-10-27T11:00Z | ENA | SHORT | 1 | 7.111 | 3.706 | armed_waiting_breakout | armed_waiting_breakout | pending |
| 2026-10-27T11:00Z | AAVE | SHORT | 2 | 2.569 | 1.839 | not_top1 | not_top1 |  |

