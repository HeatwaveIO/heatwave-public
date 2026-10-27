# Heatwave public snapshot 2026-10-27T19:53:38Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -0.079% | 4.467 | 1 | 2026-10-27T19:53:19+00:00 |  |
| propr_h6 | live | -5.522% | 0.478 | 1 | 2026-10-27T19:53:41+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-27T19:52:49+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.598% |  | 0 | 2026-10-27T19:51:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | HYPE | LONG | 81.489 | 81.4055 | -0.058 | 82.56525 (+0.75R) | False | 2026-10-28T03:55Z | urn:prp-order:YmV6dgdsm5ej @ 80.054 | urn:prp-order:Z8sYFnQVRJLa @ 84.078 |
| propr_h6 | HYPE | LONG | 81.354 | 81.3795 | 0.02 | 82.329 (+0.75R) | False | 2026-10-28T03:55Z | urn:prp-order:Zoncrsf5otv2 @ 80.054 | urn:prp-order:3FzWDz3yf7Jx @ 84.078 |

## Signal scan 2026-10-27T06:00Z .. 2026-10-27T19:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-27T10:00Z | ENA | SHORT | 1 | 3.495 | 2.994 | no_breakout | no_breakout | closed -1.0393R |
| 2026-10-27T11:00Z | ENA | SHORT | 1 | 7.111 | 3.706 | no_breakout | no_breakout | none |
| 2026-10-27T11:00Z | AAVE | SHORT | 2 | 2.569 | 1.839 | not_top1 | not_top1 |  |

