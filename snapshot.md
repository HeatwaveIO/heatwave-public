# Heatwave public snapshot 2026-11-05T16:33:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-05T16:32:49+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -4.088% |  | 0 | 2026-11-05T16:31:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-05T03:00Z .. 2026-11-05T16:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-05T09:00Z | INJ | LONG | 1 | 4.682 | 3.267 | unknown (account read failed) | unknown (account read failed) | closed -1.0245R |
| 2026-11-05T10:00Z | INJ | LONG | 1 | 3.095 | 2.601 | unknown (account read failed) | unknown (account read failed) | closed -1.0308R |
| 2026-11-05T11:00Z | INJ | LONG | 1 | 2.837 | 3.093 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-05T13:00Z | SUI | SHORT | 1 | 5.59 | 1.759 | unknown (account read failed) | unknown (account read failed) | closed 2.9815R |
| 2026-11-05T13:00Z | LINK | SHORT | 2 | 4.986 | 1.645 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | OP | SHORT | 3 | 3.268 | 2.033 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | DOT | SHORT | 4 | 2.936 | 2.308 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | ADA | SHORT | 5 | 2.824 | 2.009 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T13:00Z | SOL | SHORT | 6 | 2.627 | 1.7 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T14:00Z | WLD | SHORT | 1 | 4.174 | 1.714 | unknown (account read failed) | unknown (account read failed) | closed 2.9578R |
| 2026-11-05T15:00Z | AAVE | SHORT | 1 | 3.646 | 4.195 | unknown (account read failed) | unknown (account read failed) | closed 0.0227R |
| 2026-11-05T15:00Z | SOL | SHORT | 2 | 3.053 | 3.149 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T15:00Z | WLD | SHORT | 3 | 2.505 | 3.758 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | ZEC | LONG | 1 | 6.73 | 4.755 | unknown (account read failed) | unknown (account read failed) | open -0.067R so far |
| 2026-11-05T16:00Z | DOGE | SHORT | 1 | 14.129 | 4.312 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-05T16:00Z | ADA | SHORT | 2 | 8.647 | 5.46 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | XRP | SHORT | 3 | 7.034 | 3.482 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | WLD | SHORT | 4 | 6.963 | 7.461 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | LINK | SHORT | 5 | 6.904 | 5.369 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | DOT | SHORT | 6 | 6.259 | 5.011 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | LTC | SHORT | 7 | 6.191 | 5.127 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | BTC | SHORT | 8 | 6.074 | 3.637 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | SOL | SHORT | 9 | 5.913 | 4.3 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | AAVE | SHORT | 10 | 5.751 | 6.433 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | XLM | SHORT | 11 | 5.209 | 5.256 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | BNB | SHORT | 12 | 4.949 | 2.238 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | ENA | SHORT | 13 | 4.634 | 8.776 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | ETH | SHORT | 14 | 4.421 | 4.836 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | SUI | SHORT | 15 | 4.208 | 5.273 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | HYPE | SHORT | 16 | 3.773 | 3.639 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | INJ | SHORT | 17 | 3.733 | 4.403 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | AVAX | SHORT | 18 | 3.234 | 4.93 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | NEAR | SHORT | 19 | 3.039 | 6.509 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | OP | SHORT | 20 | 2.939 | 6.436 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | ARB | SHORT | 21 | 2.918 | 5.866 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-05T16:00Z | APT | SHORT | 22 | 2.905 | 7.288 | unknown (account read failed) | unknown (account read failed) |  |

