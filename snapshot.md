# Heatwave public snapshot 2026-11-03T07:33:36Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-03T07:32:49+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 1.89% |  | 0 | 2026-11-03T07:31:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-02T18:00Z .. 2026-11-03T07:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-02T18:00Z | HYPE | LONG | 1 | 4.345 | 2.098 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-02T18:00Z | ZEC | SHORT | 1 | 9.21 | 5.718 | unknown (account read failed) | unknown (account read failed) | closed 0.4381R |
| 2026-11-02T18:00Z | SOL | SHORT | 2 | 5.952 | 2.294 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T18:00Z | XLM | SHORT | 3 | 5.546 | 1.529 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T18:00Z | LINK | SHORT | 4 | 4.501 | 1.706 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T18:00Z | AVAX | SHORT | 5 | 4.41 | 1.882 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T18:00Z | AAVE | SHORT | 6 | 3.906 | 2.815 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T18:00Z | OP | SHORT | 7 | 2.673 | 1.929 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T19:00Z | HYPE | LONG | 1 | 3.202 | 1.611 | unknown (account read failed) | unknown (account read failed) | closed -1.0502R |
| 2026-11-02T19:00Z | ZEC | SHORT | 1 | 3.301 | 2.488 | unknown (account read failed) | unknown (account read failed) | closed 0.0062R |
| 2026-11-02T19:00Z | OP | SHORT | 2 | 2.534 | 1.639 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-02T20:00Z | SOL | SHORT | 1 | 4.057 | 1.574 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-02T20:00Z | ZEC | SHORT | 2 | 3.658 | 3.579 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-03T03:00Z | WLD | SHORT | 1 | 2.976 | 2.113 | unknown (account read failed) | unknown (account read failed) | open 0.056R so far |

