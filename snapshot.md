# Heatwave public snapshot 2026-11-17T10:08:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-17T10:07:51+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 15.878% |  | 0 | 2026-11-17T09:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-16T21:00Z .. 2026-11-17T10:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-17T00:00Z | AVAX | SHORT | 1 | 4.879 | 1.502 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-17T04:00Z | AAVE | LONG | 1 | 4.31 | 3.089 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-17T05:00Z | INJ | LONG | 1 | 2.869 | 3.716 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-17T06:00Z | OP | SHORT | 1 | 3.609 | 3.314 | unknown (account read failed) | unknown (account read failed) | open 0.344R so far |
| 2026-11-17T07:00Z | OP | SHORT | 1 | 3.16 | 2.029 | unknown (account read failed) | unknown (account read failed) | open -0.221R so far |

