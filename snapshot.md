# Heatwave public snapshot 2026-10-28T23:23:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -2.653% | 1.892 | 0 | 2026-10-28T23:23:33+00:00 |  |
| propr_h6 | live | -5.589% | 0.411 | 0 | 2026-10-28T23:23:43+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T23:22:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 1.138% |  | 0 | 2026-10-28T23:21:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-28T10:00Z .. 2026-10-28T23:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | no_breakout | no_breakout | none |
| 2026-10-28T13:00Z | kPEPE | LONG | 1 | 3.279 | 2.682 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | none |
| 2026-10-28T13:00Z | AAVE | SHORT | 1 | 3.66 | 2.39 | filled | filled | closed -1.0571R |
| 2026-10-28T19:00Z | kPEPE | LONG | 1 | 4.711 | 2.535 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open -0.357R so far |
| 2026-10-28T19:00Z | LINK | LONG | 2 | 4.004 | 1.907 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AAVE | LONG | 3 | 3.681 | 2.566 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ZEC | LONG | 4 | 2.958 | 1.845 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | SUI | LONG | 5 | 2.865 | 2.033 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ADA | SHORT | 1 | 3.765 | 1.806 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T19:00Z | ENA | SHORT | 2 | 3.212 | 4.316 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AVAX | SHORT | 3 | 3.148 | 1.565 | not_top1 | not_top1 |  |
| 2026-10-28T20:00Z | ENA | LONG | 1 | 2.954 | 3.138 | filled | filled | open -0.228R so far |
| 2026-10-28T21:00Z | kPEPE | LONG | 1 | 33.946 | 5.778 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T21:00Z | ENA | LONG | 2 | 3.758 | 3.772 | not_top1 | not_top1 |  |
| 2026-10-28T21:00Z | HYPE | LONG | 3 | 2.636 | 1.917 | not_top1 | not_top1 |  |
| 2026-10-28T22:00Z | kPEPE | LONG | 1 | 5.54 | 3.223 | skipped_off_hours | skipped_off_hours | pending |

