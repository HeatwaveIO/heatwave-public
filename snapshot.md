# Heatwave public snapshot 2026-11-11T13:48:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-11T13:47:51+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.826% |  | 0 | 2026-11-11T13:46:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-11T00:00Z .. 2026-11-11T13:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-11T02:00Z | ARB | LONG | 1 | 2.51 | 2.965 | unknown (account read failed) | unknown (account read failed) | closed -1.0362R |
| 2026-11-11T03:00Z | ARB | LONG | 1 | 2.78 | 2.997 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-11T04:00Z | INJ | LONG | 1 | 4.872 | 1.836 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-11T07:00Z | ZEC | SHORT | 1 | 3.288 | 4.237 | unknown (account read failed) | unknown (account read failed) | open -0.327R so far |
| 2026-11-11T08:00Z | AVAX | LONG | 1 | 3.287 | 1.856 | unknown (account read failed) | unknown (account read failed) | open -0.404R so far |
| 2026-11-11T08:00Z | kPEPE | LONG | 2 | 2.706 | 1.958 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-11T08:00Z | DOT | SHORT | 1 | 4.571 | 1.534 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-11T08:00Z | ZEC | SHORT | 2 | 2.657 | 3.936 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-11T09:00Z | ZEC | SHORT | 1 | 2.764 | 3.498 | unknown (account read failed) | unknown (account read failed) | open -0.484R so far |
| 2026-11-11T10:00Z | kPEPE | LONG | 1 | 3.579 | 2.009 | unknown (account read failed) | unknown (account read failed) | pending |

