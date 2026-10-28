# Heatwave public snapshot 2026-10-28T21:13:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.633% | 2.913 | 3 | 2026-10-28T21:13:28+00:00 |  |
| propr_h6 | live | -5.584% | 0.416 | 1 | 2026-10-28T21:13:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T21:12:47+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.732% |  | 0 | 2026-10-28T20:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | ARB | LONG | 0.17186 | 0.17557 | 0.649 | 0.17615 (+0.75R) | True | 2026-10-29T04:55Z | urn:prp-order:qSPwbZawSGDT @ 0.17216 | urn:prp-order:ecT1noVYL7YQ @ 0.19014 |
| propr_2s | ENA | LONG | 0.20988 | 0.21241 | 0.358 | 0.215182 (+0.75R) | False | 2026-10-29T05:55Z | urn:prp-order:r4GJJLLrCP4Z @ 0.20281 | urn:prp-order:3c364XbVNMV3 @ 0.22909 |
| propr_2s | kPEPE | LONG | 0.004985 | 0.005084 | 0.756 | 0.005083 (+0.75R) | True | 2026-10-29T05:55Z | urn:prp-order:pD3hUyxwTopG @ 0.005051 | urn:prp-order:LgzsPu8vqsna @ 0.005378 |
| propr_h6 | ENA | LONG | 0.20881 | 0.212585 | 0.629 | 0.21331 (+0.75R) | True | 2026-10-29T05:55Z | urn:prp-order:f7aAyVpHMxtY @ 0.20914 | urn:prp-order:gFvYkkE7fSEA @ 0.22909 |

## Signal scan 2026-10-28T08:00Z .. 2026-10-28T21:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | closed -1.0488R |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | no_breakout | no_breakout | none |
| 2026-10-28T13:00Z | kPEPE | LONG | 1 | 3.279 | 2.682 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | none |
| 2026-10-28T13:00Z | AAVE | SHORT | 1 | 3.66 | 2.39 | filled | filled | closed -1.0571R |
| 2026-10-28T19:00Z | kPEPE | LONG | 1 | 4.711 | 2.535 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open -0.182R so far |
| 2026-10-28T19:00Z | LINK | LONG | 2 | 4.004 | 1.907 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AAVE | LONG | 3 | 3.681 | 2.566 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ZEC | LONG | 4 | 2.958 | 1.845 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | SUI | LONG | 5 | 2.865 | 2.033 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ADA | SHORT | 1 | 3.765 | 1.806 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T19:00Z | ENA | SHORT | 2 | 3.212 | 4.316 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AVAX | SHORT | 3 | 3.148 | 1.565 | not_top1 | not_top1 |  |
| 2026-10-28T20:00Z | ENA | LONG | 1 | 2.954 | 3.138 | filled | filled | open 0.139R so far |
| 2026-10-28T21:00Z | kPEPE | LONG | 1 | 33.946 | 5.778 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T21:00Z | ENA | LONG | 2 | 3.758 | 3.772 | not_top1 | not_top1 |  |
| 2026-10-28T21:00Z | HYPE | LONG | 3 | 2.636 | 1.917 | not_top1 | not_top1 |  |

