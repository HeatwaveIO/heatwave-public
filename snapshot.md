# Heatwave public snapshot 2026-10-29T07:23:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -2.735% | 1.811 | 0 | 2026-10-29T07:23:23+00:00 |  |
| propr_h6 | live | -5.59% | 0.41 | 0 | 2026-10-29T07:23:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-29T07:22:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.626% |  | 0 | 2026-10-29T07:21:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-28T18:00Z .. 2026-10-29T07:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T19:00Z | kPEPE | LONG | 1 | 4.711 | 2.535 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | closed -0.3592R |
| 2026-10-28T19:00Z | LINK | LONG | 2 | 4.004 | 1.907 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AAVE | LONG | 3 | 3.681 | 2.566 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ZEC | LONG | 4 | 2.958 | 1.845 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | SUI | LONG | 5 | 2.865 | 2.033 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ADA | SHORT | 1 | 3.765 | 1.806 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | none |
| 2026-10-28T19:00Z | ENA | SHORT | 2 | 3.212 | 4.316 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AVAX | SHORT | 3 | 3.148 | 1.565 | not_top1 | not_top1 |  |
| 2026-10-28T20:00Z | ENA | LONG | 1 | 2.954 | 3.138 | filled | filled | closed -1.0326R |
| 2026-10-28T21:00Z | kPEPE | LONG | 1 | 33.946 | 5.778 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | none |
| 2026-10-28T21:00Z | ENA | LONG | 2 | 3.758 | 3.772 | not_top1 | not_top1 |  |
| 2026-10-28T21:00Z | HYPE | LONG | 3 | 2.636 | 1.917 | not_top1 | not_top1 |  |
| 2026-10-28T22:00Z | kPEPE | LONG | 1 | 5.54 | 3.223 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-29T01:00Z | kPEPE | LONG | 1 | 5.777 | 2.5 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-29T02:00Z | ZEC | LONG | 1 | 2.825 | 3.842 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-29T02:00Z | ADA | SHORT | 1 | 3.992 | 3.662 | skipped_off_hours | skipped_off_hours | open -0.029R so far |
| 2026-10-29T02:00Z | HYPE | SHORT | 2 | 3.768 | 2.02 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-29T02:00Z | SUI | SHORT | 3 | 2.922 | 3.066 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-29T03:00Z | kPEPE | LONG | 1 | 5.166 | 3.605 | skipped_off_hours | skipped_off_hours | open -0.159R so far |
| 2026-10-29T03:00Z | LTC | SHORT | 1 | 3.098 | 1.736 | skipped_off_hours | skipped_off_hours | open 0.111R so far |
| 2026-10-29T03:00Z | ADA | SHORT | 2 | 2.887 | 1.867 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-29T04:00Z | kPEPE | LONG | 1 | 5.568 | 1.795 | skipped_off_hours | skipped_off_hours | closed -0.0113R |
| 2026-10-29T05:00Z | kPEPE | LONG | 1 | 6.769 | 3.316 | skipped_off_hours | skipped_off_hours | open -0.592R so far |
| 2026-10-29T06:00Z | kPEPE | LONG | 1 | 3.602 | 3.069 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-29T07:00Z | NEAR | SHORT | 1 | 3.966 | 4.855 | skipped_off_hours | skipped_off_hours | pending |

