# Heatwave public snapshot 2026-10-26T23:38:30Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 0.021% | 4.567 | 0 | 2026-10-26T23:38:28+00:00 |  |
| propr_h6 | live | -5.524% | 0.476 | 0 | 2026-10-26T23:37:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-26T23:37:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 3.362% |  | 0 | 2026-10-26T23:36:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-26T10:00Z .. 2026-10-26T23:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-26T18:00Z | HYPE | SHORT | 1 | 5.727 | 2.826 | armed_waiting_breakout | armed_waiting_breakout | open 0.037R so far |
| 2026-10-26T18:00Z | WLD | SHORT | 2 | 2.905 | 1.503 | not_top1 | not_top1 |  |
| 2026-10-26T19:00Z | HYPE | SHORT | 1 | 2.607 | 1.835 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open 0.09R so far |

