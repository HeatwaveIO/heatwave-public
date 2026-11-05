# Heatwave public snapshot 2026-11-05T13:53:32Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-05T13:52:48+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -1.83% |  | 0 | 2026-11-05T13:51:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-05T00:00Z .. 2026-11-05T13:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-05T02:00Z | WLD | SHORT | 1 | 5.498 | 2.091 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-05T09:00Z | INJ | LONG | 1 | 4.682 | 3.267 | unknown (account read failed) | unknown (account read failed) | open -0.585R so far |
| 2026-11-05T10:00Z | INJ | LONG | 1 | 3.095 | 2.601 | unknown (account read failed) | unknown (account read failed) | closed -1.0308R |
| 2026-11-05T11:00Z | INJ | LONG | 1 | 2.837 | 3.093 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-05T13:00Z | SUI | SHORT | 1 | 5.59 | 1.759 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-05T13:00Z | LINK | SHORT | 2 | 4.986 | 1.645 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | OP | SHORT | 3 | 3.268 | 2.033 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | DOT | SHORT | 4 | 2.936 | 2.308 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | ADA | SHORT | 5 | 2.824 | 2.009 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | SOL | SHORT | 6 | 2.627 | 1.7 | unknown (account read failed) | unknown (account read failed) |  |

