# Heatwave public snapshot 2026-11-26T09:13:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-26T09:12:53+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 15.452% |  | 0 | 2026-11-26T08:56:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-25T20:00Z .. 2026-11-26T09:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-25T20:00Z | ENA | LONG | 1 | 10.601 | 3.295 | unknown (account read failed) | unknown (account read failed) | closed 0.0257R |
| 2026-11-25T20:00Z | LINK | LONG | 2 | 2.901 | 1.749 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T21:00Z | ENA | LONG | 1 | 4.692 | 1.809 | unknown (account read failed) | unknown (account read failed) | closed 0.0053R |
| 2026-11-25T21:00Z | NEAR | LONG | 2 | 3.323 | 4.343 | unknown (account read failed) | unknown (account read failed) |  |

