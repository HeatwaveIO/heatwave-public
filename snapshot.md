# Heatwave public snapshot 2026-11-03T20:53:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-03T20:52:49+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.116% |  | 0 | 2026-11-03T20:51:33Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-03T07:00Z .. 2026-11-03T20:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-03T08:00Z | AAVE | SHORT | 1 | 12.651 | 2.004 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-03T12:00Z | ARB | LONG | 1 | 6.402 | 2.295 | unknown (account read failed) | unknown (account read failed) | open -0.882R so far |
| 2026-11-03T12:00Z | ZEC | LONG | 2 | 2.625 | 2.421 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-03T13:00Z | XRP | LONG | 1 | 7.191 | 2.446 | unknown (account read failed) | unknown (account read failed) | open -0.281R so far |
| 2026-11-03T13:00Z | ZEC | LONG | 2 | 4.514 | 3.036 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-03T15:00Z | HYPE | LONG | 1 | 5.032 | 2.455 | unknown (account read failed) | unknown (account read failed) | pending |

