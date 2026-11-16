# Heatwave public snapshot 2026-11-16T10:58:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-16T10:57:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 17.022% |  | 0 | 2026-11-16T10:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-15T21:00Z .. 2026-11-16T10:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-16T00:00Z | DOGE | LONG | 1 | 3.372 | 1.766 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-16T01:00Z | AVAX | SHORT | 1 | 3.544 | 2.169 | unknown (account read failed) | unknown (account read failed) | open 0.138R so far |
| 2026-11-16T02:00Z | DOGE | SHORT | 1 | 3.229 | 1.5 | unknown (account read failed) | unknown (account read failed) | open -0.258R so far |

