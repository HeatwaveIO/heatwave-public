# Heatwave public snapshot 2026-11-24T18:28:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-24T18:27:53+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 18.444% |  | 0 | 2026-11-24T18:26:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-24T05:00Z .. 2026-11-24T18:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-24T10:00Z | HYPE | SHORT | 1 | 2.597 | 1.549 | unknown (account read failed) | unknown (account read failed) | open 1.289R so far |
| 2026-11-24T12:00Z | NEAR | SHORT | 1 | 2.545 | 1.874 | unknown (account read failed) | unknown (account read failed) | closed -0.0R |
| 2026-11-24T14:00Z | DOT | SHORT | 1 | 7.227 | 2.065 | unknown (account read failed) | unknown (account read failed) | open -0.434R so far |

