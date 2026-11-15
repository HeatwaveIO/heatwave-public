# Heatwave public snapshot 2026-11-15T17:33:39Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-15T17:32:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 15.91% |  | 0 | 2026-11-15T17:31:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-15T04:00Z .. 2026-11-15T17:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-15T04:00Z | AAVE | LONG | 1 | 5.188 | 2.233 | unknown (account read failed) | unknown (account read failed) | closed 0.0118R |
| 2026-11-15T04:00Z | XRP | LONG | 2 | 3.334 | 1.52 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T04:00Z | INJ | SHORT | 1 | 3.971 | 1.532 | unknown (account read failed) | unknown (account read failed) | closed -1.0522R |
| 2026-11-15T05:00Z | AAVE | LONG | 1 | 3.612 | 1.799 | unknown (account read failed) | unknown (account read failed) | closed 0.0048R |
| 2026-11-15T05:00Z | AVAX | SHORT | 1 | 6.702 | 1.606 | unknown (account read failed) | unknown (account read failed) | closed -1.0803R |
| 2026-11-15T09:00Z | BTC | LONG | 1 | 4.013 | 2.197 | unknown (account read failed) | unknown (account read failed) | open -0.586R so far |
| 2026-11-15T09:00Z | LINK | LONG | 2 | 2.926 | 1.657 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T09:00Z | ETH | LONG | 3 | 2.552 | 1.975 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T09:00Z | DOT | SHORT | 1 | 3.481 | 1.657 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-15T10:00Z | HYPE | LONG | 1 | 5.728 | 3.444 | unknown (account read failed) | unknown (account read failed) | open -0.643R so far |
| 2026-11-15T10:00Z | LTC | LONG | 2 | 4.756 | 1.933 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T10:00Z | DOT | LONG | 3 | 4.082 | 2.058 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T10:00Z | INJ | LONG | 4 | 3.59 | 4.15 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T10:00Z | LINK | LONG | 5 | 3.229 | 1.759 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T10:00Z | AAVE | LONG | 6 | 2.913 | 2.342 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-15T10:00Z | AVAX | SHORT | 1 | 3.516 | 2.435 | unknown (account read failed) | unknown (account read failed) | open -0.216R so far |
| 2026-11-15T10:00Z | APT | SHORT | 2 | 2.516 | 2.306 | unknown (account read failed) | unknown (account read failed) |  |

