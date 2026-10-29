# Heatwave public snapshot 2026-10-29T21:48:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -2.001% | 2.545 | 0 | 2026-10-29T21:48:28+00:00 |  |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-29T21:47:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -1.762% |  | 0 | 2026-10-29T21:46:32Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-29T08:00Z .. 2026-10-29T21:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-29T08:00Z | kPEPE | LONG | 1 | 6.084 | 3.219 | skipped_off_hours | unknown (account read failed) | none |
| 2026-10-29T10:00Z | kPEPE | LONG | 1 | 3.847 | 2.014 | not_picked_by_executor (data / timing) | unknown (account read failed) | closed 2.9672R |
| 2026-10-29T11:00Z | HYPE | LONG | 1 | 22.043 | 8.3 | not_picked_by_executor (data / timing) | unknown (account read failed) | closed 0.8672R |
| 2026-10-29T11:00Z | kPEPE | LONG | 2 | 3.797 | 3.936 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T12:00Z | HYPE | LONG | 1 | 19.62 | 3.606 | filled | unknown (account read failed) | open 1.084R so far |
| 2026-10-29T12:00Z | kPEPE | LONG | 2 | 2.966 | 2.04 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T13:00Z | HYPE | LONG | 1 | 8.971 | 2.705 | skipped_symbol_in_use | unknown (account read failed) | closed 0.0193R |
| 2026-10-29T14:00Z | HYPE | LONG | 1 | 9.429 | 2.774 | not_picked_by_executor (data / timing) | unknown (account read failed) | closed 0.0211R |
| 2026-10-29T15:00Z | kPEPE | LONG | 1 | 2.717 | 4.656 | not_picked_by_executor (data / timing) | unknown (account read failed) | closed 0.024R |
| 2026-10-29T16:00Z | HYPE | LONG | 1 | 7.9 | 4.245 | not_picked_by_executor (data / timing) | unknown (account read failed) | closed -1.0246R |
| 2026-10-29T16:00Z | kPEPE | LONG | 2 | 6.249 | 8.853 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T16:00Z | DOT | LONG | 3 | 2.988 | 1.767 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T16:00Z | ZEC | LONG | 4 | 2.801 | 4.82 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T16:00Z | LINK | LONG | 5 | 2.613 | 1.562 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T17:00Z | kPEPE | LONG | 1 | 8.718 | 7.496 | not_picked_by_executor (data / timing) | unknown (account read failed) | pending |
| 2026-10-29T17:00Z | HYPE | LONG | 2 | 7.366 | 3.306 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T17:00Z | ZEC | LONG | 3 | 4.967 | 4.2 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T17:00Z | ENA | LONG | 4 | 3.109 | 2.413 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T18:00Z | HYPE | LONG | 1 | 6.788 | 3.619 | not_picked_by_executor (data / timing) | unknown (account read failed) | pending |
| 2026-10-29T18:00Z | kPEPE | LONG | 2 | 3.277 | 2.861 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T19:00Z | kPEPE | LONG | 1 | 4.052 | 3.944 | not_picked_by_executor (data / timing) | unknown (account read failed) | pending |
| 2026-10-29T19:00Z | HYPE | LONG | 2 | 3.592 | 1.749 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | HYPE | LONG | 1 | 21.295 | 5.574 | not_picked_by_executor (data / timing) | unknown (account read failed) | pending |
| 2026-10-29T21:00Z | kPEPE | LONG | 2 | 18.064 | 9.397 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | ZEC | LONG | 3 | 12.386 | 9.85 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | BNB | SHORT | 1 | 687.305 | 11.171 | not_picked_by_executor (data / timing) | unknown (account read failed) | pending |
| 2026-10-29T21:00Z | XLM | SHORT | 2 | 31.077 | 5.713 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | LINK | SHORT | 3 | 22.635 | 7.334 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | XRP | SHORT | 4 | 21.186 | 5.045 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | ADA | SHORT | 5 | 21.139 | 8.099 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | ETH | SHORT | 6 | 20.863 | 4.885 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | DOT | SHORT | 7 | 20.208 | 10.959 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | AVAX | SHORT | 8 | 17.091 | 7.311 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | AAVE | SHORT | 9 | 16.846 | 7.645 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | SOL | SHORT | 10 | 15.228 | 5.4 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | DOGE | SHORT | 11 | 13.82 | 6.613 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | ENA | SHORT | 12 | 13.205 | 13.997 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | BTC | SHORT | 13 | 12.919 | 3.355 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | SUI | SHORT | 14 | 12.241 | 8.379 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | APT | SHORT | 15 | 11.574 | 11.299 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | TIA | SHORT | 16 | 11.217 | 10.473 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | WLD | SHORT | 17 | 9.678 | 11.071 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | ARB | SHORT | 18 | 8.627 | 11.463 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | LTC | SHORT | 19 | 8.594 | 6.921 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | OP | SHORT | 20 | 8.141 | 10.497 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | INJ | SHORT | 21 | 6.821 | 9.19 | not_top1 | unknown (account read failed) |  |
| 2026-10-29T21:00Z | NEAR | SHORT | 22 | 5.404 | 7.546 | not_top1 | unknown (account read failed) |  |

