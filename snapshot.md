# Heatwave public snapshot 2026-11-25T15:53:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-25T15:52:54+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 18.45% |  | 0 | 2026-11-25T15:51:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-25T02:00Z .. 2026-11-25T15:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-25T08:00Z | SOL | SHORT | 1 | 2.886 | 1.948 | unknown (account read failed) | unknown (account read failed) | closed 0.0083R |
| 2026-11-25T14:00Z | OP | SHORT | 1 | 3.183 | 1.531 | unknown (account read failed) | unknown (account read failed) | closed -1.0545R |
| 2026-11-25T15:00Z | XLM | SHORT | 1 | 4.393 | 1.823 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-25T15:00Z | ADA | SHORT | 2 | 4.05 | 2.474 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-25T15:00Z | DOT | SHORT | 3 | 2.652 | 2.169 | unknown (account read failed) | unknown (account read failed) |  |

