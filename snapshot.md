# Heatwave public snapshot 2026-10-28T20:08:38Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.226% | 3.32 | 3 | 2026-10-28T20:08:33+00:00 |  |
| propr_h6 | live | -5.59% | 0.41 | 0 | 2026-10-28T20:08:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T20:07:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.472% |  | 0 | 2026-10-28T19:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | AAVE | LONG | 134.917642 | 137.68 | 0.869 | 137.300873 (+0.75R) | True | 2026-10-29T04:55Z | urn:prp-order:nd41o6Jvb5T7 @ 135.09 | urn:prp-order:usPw8TTRC55B @ 145.62 |
| propr_2s | ARB | LONG | 0.17186 | 0.17744 | 0.976 | 0.17615 (+0.75R) | True | 2026-10-29T04:55Z | urn:prp-order:qSPwbZawSGDT @ 0.17216 | urn:prp-order:ecT1noVYL7YQ @ 0.19014 |
| propr_2s | SUI | LONG | 0.941814 | 0.95349 | 0.632 | 0.955677 (+0.75R) | True | 2026-10-29T04:55Z | urn:prp-order:LfE2WUJUTgsK @ 0.94277 | urn:prp-order:wzb2o8W1P1gj @ 0.99997 |

## Signal scan 2026-10-28T07:00Z .. 2026-10-28T20:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | closed -1.0488R |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | no_breakout | no_breakout | none |
| 2026-10-28T13:00Z | kPEPE | LONG | 1 | 3.279 | 2.682 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | none |
| 2026-10-28T13:00Z | AAVE | SHORT | 1 | 3.66 | 2.39 | filled | filled | closed -1.0571R |
| 2026-10-28T19:00Z | kPEPE | LONG | 1 | 4.711 | 2.535 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open 0.03R so far |
| 2026-10-28T19:00Z | LINK | LONG | 2 | 4.004 | 1.907 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AAVE | LONG | 3 | 3.681 | 2.566 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ZEC | LONG | 4 | 2.958 | 1.845 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | SUI | LONG | 5 | 2.865 | 2.033 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ADA | SHORT | 1 | 3.765 | 1.806 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T19:00Z | ENA | SHORT | 2 | 3.212 | 4.316 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AVAX | SHORT | 3 | 3.148 | 1.565 | not_top1 | not_top1 |  |
| 2026-10-28T20:00Z | ENA | LONG | 1 | 2.954 | 3.138 | armed_waiting_breakout | armed_waiting_breakout | pending |

