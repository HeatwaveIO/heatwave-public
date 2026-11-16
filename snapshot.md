# Heatwave public snapshot 2026-11-16T16:43:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-16T16:42:58+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 17.592% |  | 0 | 2026-11-16T16:41:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-16T03:00Z .. 2026-11-16T16:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-16T12:00Z | HYPE | SHORT | 1 | 4.079 | 2.39 | unknown (account read failed) | unknown (account read failed) | closed -1.0366R |
| 2026-11-16T13:00Z | ZEC | SHORT | 1 | 4.363 | 3.63 | unknown (account read failed) | unknown (account read failed) | closed -1.029R |
| 2026-11-16T13:00Z | HYPE | SHORT | 2 | 3.555 | 1.73 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-16T14:00Z | ZEC | SHORT | 1 | 2.638 | 1.747 | unknown (account read failed) | unknown (account read failed) | closed -1.0458R |

