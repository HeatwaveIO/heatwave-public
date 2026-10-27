# Heatwave public snapshot 2026-10-27T18:53:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 0.021% | 4.567 | 1 | 2026-10-27T18:52:58+00:00 |  |
| propr_h6 | live | -5.524% | 0.476 | 1 | 2026-10-27T18:53:41+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-27T18:52:48+00:00 | HyroError: list_challenges: Could not reach the HyroTrader API: Request timed out after 15000ms.. Check the network and the HYRO_API_URL setting, then retry. |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.49% |  | 0 | 2026-10-27T18:51:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | HYPE | LONG | 81.06 | 81.06 | 0.0 | 81.8145 (+0.75R) | False | 2026-10-28T03:55Z | urn:prp-order:peXyUdqsis5i @ 80.054 | urn:prp-order:3nfWK2tL5FoV @ 84.078 |
| propr_h6 | HYPE | LONG | 81.06 | 81.06 | 0.0 | 81.8145 (+0.75R) | False | 2026-10-28T03:55Z | urn:prp-order:SBCtXTPcyt2X @ 80.054 | urn:prp-order:LgyFVFQLqZna @ 84.078 |

## Signal scan 2026-10-27T05:00Z .. 2026-10-27T18:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-27T10:00Z | ENA | SHORT | 1 | 3.495 | 2.994 | no_breakout | no_breakout | closed -1.0393R |
| 2026-10-27T11:00Z | ENA | SHORT | 1 | 7.111 | 3.706 | no_breakout | no_breakout | none |
| 2026-10-27T11:00Z | AAVE | SHORT | 2 | 2.569 | 1.839 | not_top1 | not_top1 |  |

