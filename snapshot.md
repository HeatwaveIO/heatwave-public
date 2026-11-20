# Heatwave public snapshot 2026-11-20T01:03:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-20T01:03:09+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 13.358% |  | 0 | 2026-11-20T00:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-19T12:00Z .. 2026-11-20T01:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-19T18:00Z | HYPE | LONG | 1 | 2.852 | 3.508 | unknown (account read failed) | unknown (account read failed) | closed -1.0394R |
| 2026-11-19T18:00Z | APT | SHORT | 1 | 4.271 | 2.705 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-19T18:00Z | DOT | SHORT | 2 | 4.001 | 2.347 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-19T18:00Z | TIA | SHORT | 3 | 3.369 | 2.226 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-19T18:00Z | LTC | SHORT | 4 | 3.257 | 1.54 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-19T18:00Z | BTC | SHORT | 5 | 3.219 | 1.894 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-19T18:00Z | AAVE | SHORT | 6 | 2.711 | 2.126 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-19T19:00Z | APT | SHORT | 1 | 2.604 | 1.869 | unknown (account read failed) | unknown (account read failed) | open 0.088R so far |
| 2026-11-19T21:00Z | HYPE | SHORT | 1 | 2.986 | 2.299 | unknown (account read failed) | unknown (account read failed) | open 0.009R so far |

