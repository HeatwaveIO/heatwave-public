# Heatwave public snapshot 2026-11-05T12:03:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-05T12:03:06+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -1.83% |  | 0 | 2026-11-05T11:56:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-04T23:00Z .. 2026-11-05T12:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-04T23:00Z | XLM | LONG | 1 | 3.361 | 1.664 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-05T02:00Z | WLD | SHORT | 1 | 5.498 | 2.091 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-05T09:00Z | INJ | LONG | 1 | 4.682 | 3.267 | unknown (account read failed) | unknown (account read failed) | open -0.297R so far |
| 2026-11-05T10:00Z | INJ | LONG | 1 | 3.095 | 2.601 | unknown (account read failed) | unknown (account read failed) | open -0.742R so far |
| 2026-11-05T11:00Z | INJ | LONG | 1 | 2.837 | 3.093 | unknown (account read failed) | unknown (account read failed) | pending |

