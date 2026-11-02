# Heatwave public snapshot 2026-11-02T07:58:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-02T07:57:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.324% |  | 0 | 2026-11-02T07:56:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-01T18:00Z .. 2026-11-02T07:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-01T20:00Z | APT | SHORT | 1 | 3.92 | 2.026 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-02T02:00Z | SOL | LONG | 1 | 5.357 | 1.537 | unknown (account read failed) | unknown (account read failed) | open -0.799R so far |
| 2026-11-02T04:00Z | ZEC | LONG | 1 | 2.672 | 1.989 | unknown (account read failed) | unknown (account read failed) | open -0.596R so far |
| 2026-11-02T07:00Z | HYPE | LONG | 1 | 6.125 | 2.597 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-02T07:00Z | NEAR | SHORT | 1 | 3.459 | 3.683 | unknown (account read failed) | unknown (account read failed) | open -0.176R so far |
| 2026-11-02T07:00Z | ENA | SHORT | 2 | 2.767 | 2.136 | unknown (account read failed) | unknown (account read failed) |  |

