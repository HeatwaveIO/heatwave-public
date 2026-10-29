# Heatwave public snapshot 2026-10-29T18:08:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.572% | 2.974 | 1 | 2026-10-29T18:08:34+00:00 |  |
| propr_h6 | live | -5.59% | 0.41 | 0 | 2026-10-29T18:07:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-29T18:07:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -3.094% |  | 0 | 2026-10-29T17:56:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | HYPE | LONG | 88.132 | 94.3225 | 1.958 | 90.5035 (+0.75R) | True | 2026-10-29T21:55Z | urn:prp-order:HAEJdc7WWNnn @ 92.106 | urn:prp-order:hdNu6QY54FD5 @ 97.686 |

## Signal scan 2026-10-29T05:00Z .. 2026-10-29T18:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-29T05:00Z | kPEPE | LONG | 1 | 6.769 | 3.316 | skipped_off_hours | skipped_off_hours | closed -1.03R |
| 2026-10-29T06:00Z | kPEPE | LONG | 1 | 3.602 | 3.069 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-29T07:00Z | NEAR | SHORT | 1 | 3.966 | 4.855 | skipped_off_hours | skipped_off_hours | closed -1.0166R |
| 2026-10-29T08:00Z | kPEPE | LONG | 1 | 6.084 | 3.219 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-29T10:00Z | kPEPE | LONG | 1 | 3.847 | 2.014 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | closed 2.9672R |
| 2026-10-29T11:00Z | HYPE | LONG | 1 | 22.043 | 8.3 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open 0.985R so far |
| 2026-10-29T11:00Z | kPEPE | LONG | 2 | 3.797 | 3.936 | not_top1 | not_top1 |  |
| 2026-10-29T12:00Z | HYPE | LONG | 1 | 19.62 | 3.606 | filled | skipped_refused | open 1.478R so far |
| 2026-10-29T12:00Z | kPEPE | LONG | 2 | 2.966 | 2.04 | not_top1 | not_top1 |  |
| 2026-10-29T13:00Z | HYPE | LONG | 1 | 8.971 | 2.705 | skipped_symbol_in_use | skipped_refused | open 0.788R so far |
| 2026-10-29T14:00Z | HYPE | LONG | 1 | 9.429 | 2.774 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | closed 0.0211R |
| 2026-10-29T15:00Z | kPEPE | LONG | 1 | 2.717 | 4.656 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open 1.122R so far |
| 2026-10-29T16:00Z | HYPE | LONG | 1 | 7.9 | 4.245 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open -0.277R so far |
| 2026-10-29T16:00Z | kPEPE | LONG | 2 | 6.249 | 8.853 | not_top1 | not_top1 |  |
| 2026-10-29T16:00Z | DOT | LONG | 3 | 2.988 | 1.767 | not_top1 | not_top1 |  |
| 2026-10-29T16:00Z | ZEC | LONG | 4 | 2.801 | 4.82 | not_top1 | not_top1 |  |
| 2026-10-29T16:00Z | LINK | LONG | 5 | 2.613 | 1.562 | not_top1 | not_top1 |  |
| 2026-10-29T17:00Z | kPEPE | LONG | 1 | 8.718 | 7.496 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-29T17:00Z | HYPE | LONG | 2 | 7.366 | 3.306 | not_top1 | not_top1 |  |
| 2026-10-29T17:00Z | ZEC | LONG | 3 | 4.967 | 4.2 | not_top1 | not_top1 |  |
| 2026-10-29T17:00Z | ENA | LONG | 4 | 3.109 | 2.413 | not_top1 | not_top1 |  |
| 2026-10-29T18:00Z | HYPE | LONG | 1 | 6.788 | 3.619 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-29T18:00Z | kPEPE | LONG | 2 | 3.277 | 2.861 | not_top1 | not_top1 |  |

