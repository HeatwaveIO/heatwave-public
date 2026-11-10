# Heatwave public snapshot 2026-11-10T10:08:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-10T10:07:51+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 1.31% |  | 0 | 2026-11-10T09:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-09T21:00Z .. 2026-11-10T10:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-09T22:00Z | AVAX | LONG | 1 | 5.761 | 1.575 | unknown (account read failed) | unknown (account read failed) | closed -1.0528R |
| 2026-11-10T04:00Z | AAVE | SHORT | 1 | 5.449 | 2.366 | unknown (account read failed) | unknown (account read failed) | closed -0.0013R |
| 2026-11-10T05:00Z | kPEPE | LONG | 1 | 5.94 | 3.086 | unknown (account read failed) | unknown (account read failed) | open -0.152R so far |
| 2026-11-10T05:00Z | AAVE | SHORT | 1 | 6.94 | 2.071 | unknown (account read failed) | unknown (account read failed) | open 0.065R so far |
| 2026-11-10T07:00Z | AAVE | SHORT | 1 | 4.63 | 1.648 | unknown (account read failed) | unknown (account read failed) | open 0.049R so far |
| 2026-11-10T08:00Z | ARB | LONG | 1 | 3.336 | 2.227 | unknown (account read failed) | unknown (account read failed) | pending |

