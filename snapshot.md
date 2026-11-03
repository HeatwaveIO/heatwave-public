# Heatwave public snapshot 2026-11-03T08:03:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-03T08:02:47+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 1.92% |  | 0 | 2026-11-03T07:56:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-02T19:00Z .. 2026-11-03T08:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-02T19:00Z | HYPE | LONG | 1 | 3.202 | 1.611 | unknown (account read failed) | unknown (account read failed) | closed -1.0502R |
| 2026-11-02T19:00Z | ZEC | SHORT | 1 | 3.301 | 2.488 | unknown (account read failed) | unknown (account read failed) | closed 0.0062R |
| 2026-11-02T19:00Z | OP | SHORT | 2 | 2.534 | 1.639 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T20:00Z | SOL | SHORT | 1 | 4.057 | 1.574 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-02T20:00Z | ZEC | SHORT | 2 | 3.658 | 3.579 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-03T03:00Z | WLD | SHORT | 1 | 2.976 | 2.113 | unknown (account read failed) | unknown (account read failed) | open 0.575R so far |
| 2026-11-03T08:00Z | AAVE | SHORT | 1 | 12.651 | 2.004 | unknown (account read failed) | unknown (account read failed) | pending |

