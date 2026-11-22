# Heatwave public snapshot 2026-11-22T16:23:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-22T16:22:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 20.974% |  | 0 | 2026-11-22T16:21:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-22T03:00Z .. 2026-11-22T16:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-22T03:00Z | ADA | SHORT | 1 | 7.269 | 1.522 | unknown (account read failed) | unknown (account read failed) | closed -1.0805R |
| 2026-11-22T03:00Z | INJ | SHORT | 2 | 2.882 | 1.814 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-22T09:00Z | ETH | LONG | 1 | 2.663 | 1.926 | unknown (account read failed) | unknown (account read failed) | open 0.106R so far |
| 2026-11-22T09:00Z | AAVE | SHORT | 1 | 16.046 | 3.001 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-22T09:00Z | BTC | SHORT | 2 | 5.339 | 2.281 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-22T10:00Z | OP | LONG | 1 | 11.356 | 1.852 | unknown (account read failed) | unknown (account read failed) | open 0.193R so far |
| 2026-11-22T10:00Z | BTC | LONG | 2 | 4.086 | 2.774 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-22T10:00Z | WLD | LONG | 3 | 3.816 | 1.97 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-22T10:00Z | ETH | LONG | 4 | 3.796 | 2.34 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-22T10:00Z | DOT | LONG | 5 | 2.568 | 1.638 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-22T11:00Z | ENA | LONG | 1 | 3.46 | 2.365 | unknown (account read failed) | unknown (account read failed) | closed -1.0344R |

