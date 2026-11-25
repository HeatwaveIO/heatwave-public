# Heatwave public snapshot 2026-11-25T20:08:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-25T20:07:55+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 18.084% |  | 0 | 2026-11-25T19:56:33Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-25T07:00Z .. 2026-11-25T20:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-25T08:00Z | SOL | SHORT | 1 | 2.886 | 1.948 | unknown (account read failed) | unknown (account read failed) | closed 0.0083R |
| 2026-11-25T14:00Z | OP | SHORT | 1 | 3.183 | 1.531 | unknown (account read failed) | unknown (account read failed) | closed -1.0545R |
| 2026-11-25T15:00Z | XLM | SHORT | 1 | 4.393 | 1.823 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-25T15:00Z | ADA | SHORT | 2 | 4.05 | 2.474 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T15:00Z | DOT | SHORT | 3 | 2.652 | 2.169 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T18:00Z | DOT | LONG | 1 | 9.043 | 3.419 | unknown (account read failed) | unknown (account read failed) | open 0.125R so far |
| 2026-11-25T18:00Z | BNB | LONG | 2 | 6.756 | 2.343 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T18:00Z | ADA | LONG | 3 | 5.522 | 2.924 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T18:00Z | NEAR | LONG | 4 | 3.692 | 4.317 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T18:00Z | HYPE | LONG | 5 | 3.144 | 4.063 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T18:00Z | AAVE | LONG | 6 | 3.124 | 4.154 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T18:00Z | XRP | LONG | 7 | 2.677 | 2.472 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T18:00Z | kPEPE | SHORT | 1 | 2.565 | 4.347 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-25T19:00Z | LINK | LONG | 1 | 6.006 | 2.008 | unknown (account read failed) | unknown (account read failed) | open 0.081R so far |
| 2026-11-25T19:00Z | NEAR | LONG | 2 | 4.195 | 2.146 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T19:00Z | HYPE | LONG | 3 | 2.519 | 2.036 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T20:00Z | ENA | LONG | 1 | 10.601 | 3.295 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-25T20:00Z | LINK | LONG | 2 | 2.901 | 1.749 | unknown (account read failed) | unknown (account read failed) |  |

