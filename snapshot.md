# Heatwave public snapshot 2026-10-26T15:53:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 0.021% | 4.567 | 0 | 2026-10-26T15:53:22+00:00 |  |
| propr_h6 | live | -5.524% | 0.476 | 0 | 2026-10-26T15:53:43+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-26T15:52:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 3.006% |  | 0 | 2026-10-26T15:51:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-26T02:00Z .. 2026-10-26T15:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-26T02:00Z | kPEPE | LONG | 1 | 2.666 | 1.889 | skipped_off_hours | skipped_off_hours | closed 0.3089R |
| 2026-10-26T02:00Z | NEAR | SHORT | 1 | 2.98 | 3.332 | skipped_off_hours | skipped_off_hours | closed -1.033R |
| 2026-10-26T08:00Z | ENA | SHORT | 1 | 2.563 | 3.068 | skipped_off_hours | skipped_off_hours | closed -1.0365R |
| 2026-10-26T09:00Z | ENA | LONG | 1 | 4.098 | 4.293 | no_breakout | no_breakout | none |

