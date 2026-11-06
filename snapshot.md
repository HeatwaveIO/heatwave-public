# Heatwave public snapshot 2026-11-06T16:48:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-06T16:48:11+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -4.09% |  | 0 | 2026-11-06T16:46:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-06T03:00Z .. 2026-11-06T16:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-06T04:00Z | ZEC | LONG | 1 | 4.939 | 3.054 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-06T06:00Z | ZEC | LONG | 1 | 4.104 | 1.641 | unknown (account read failed) | unknown (account read failed) | closed 1.4431R |
| 2026-11-06T08:00Z | ZEC | LONG | 1 | 2.862 | 1.609 | unknown (account read failed) | unknown (account read failed) | closed 2.9814R |
| 2026-11-06T10:00Z | ZEC | LONG | 1 | 3.728 | 3.287 | unknown (account read failed) | unknown (account read failed) | closed 0.0267R |
| 2026-11-06T10:00Z | kPEPE | LONG | 2 | 3.074 | 3.298 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-06T13:00Z | ZEC | LONG | 1 | 4.115 | 3.783 | unknown (account read failed) | unknown (account read failed) | open -0.232R so far |
| 2026-11-06T15:00Z | ZEC | LONG | 1 | 4.064 | 6.47 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-06T15:00Z | kPEPE | LONG | 2 | 2.833 | 3.671 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-06T16:00Z | ZEC | LONG | 1 | 2.613 | 4.455 | unknown (account read failed) | unknown (account read failed) | pending |

