# Heatwave public snapshot 2026-11-06T14:48:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-06T14:48:06+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -4.09% |  | 0 | 2026-11-06T14:46:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-06T01:00Z .. 2026-11-06T14:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-06T01:00Z | ZEC | LONG | 1 | 2.997 | 3.931 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-06T01:00Z | OP | SHORT | 1 | 3.34 | 2.966 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-06T04:00Z | ZEC | LONG | 1 | 4.939 | 3.054 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-06T06:00Z | ZEC | LONG | 1 | 4.104 | 1.641 | unknown (account read failed) | unknown (account read failed) | open 2.347R so far |
| 2026-11-06T08:00Z | ZEC | LONG | 1 | 2.862 | 1.609 | unknown (account read failed) | unknown (account read failed) | closed 2.9814R |
| 2026-11-06T10:00Z | ZEC | LONG | 1 | 3.728 | 3.287 | unknown (account read failed) | unknown (account read failed) | open 0.648R so far |
| 2026-11-06T10:00Z | kPEPE | LONG | 2 | 3.074 | 3.298 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-06T13:00Z | ZEC | LONG | 1 | 4.115 | 3.783 | unknown (account read failed) | unknown (account read failed) | open 0.042R so far |

