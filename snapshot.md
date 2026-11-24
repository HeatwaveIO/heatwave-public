# Heatwave public snapshot 2026-11-24T12:38:38Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-24T12:37:55+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 18.442% |  | 0 | 2026-11-24T12:36:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-23T23:00Z .. 2026-11-24T12:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-24T03:00Z | ZEC | SHORT | 1 | 2.662 | 3.168 | unknown (account read failed) | unknown (account read failed) | open 0.581R so far |
| 2026-11-24T10:00Z | HYPE | SHORT | 1 | 2.597 | 1.549 | unknown (account read failed) | unknown (account read failed) | open -0.382R so far |
| 2026-11-24T12:00Z | NEAR | SHORT | 1 | 2.545 | 1.874 | unknown (account read failed) | unknown (account read failed) | pending |

