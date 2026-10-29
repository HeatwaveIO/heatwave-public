# Heatwave public snapshot 2026-10-29T02:33:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -2.641% | 1.905 | 2 | 2026-10-29T02:33:36+00:00 |  |
| propr_h6 | live | -5.59% | 0.41 | 1 | 2026-10-29T02:32:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-29T02:32:50+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.394% |  | 0 | 2026-10-29T02:31:33Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | HYPE | SHORT | 78.398 | 78.4055 | -0.004 | 77.0195 (+0.75R) | False | 2026-10-29T11:55Z | urn:prp-order:4zJ8K4MqYkGu @ 80.236 | urn:prp-order:yUxZSXKRMvxU @ 73.88 |
| propr_2s | SUI | SHORT | 0.90565 | 0.90499 | 0.02 | 0.880533 (+0.75R) | False | 2026-10-29T11:55Z | urn:prp-order:QQC2mU7ExM26 @ 0.93914 | urn:prp-order:3sxoPFRc2vsZ @ 0.82738 |
| propr_h6 | HYPE | SHORT | 78.382 | 78.3905 | -0.005 | 76.9915 (+0.75R) | False | 2026-10-29T11:55Z | urn:prp-order:Cn8Np8hCkkhs @ 80.236 | urn:prp-order:xDU6D6pPsWYT @ 73.88 |

## Signal scan 2026-10-28T13:00Z .. 2026-10-29T02:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T13:00Z | kPEPE | LONG | 1 | 3.279 | 2.682 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | none |
| 2026-10-28T13:00Z | AAVE | SHORT | 1 | 3.66 | 2.39 | filled | filled | closed -1.0571R |
| 2026-10-28T19:00Z | kPEPE | LONG | 1 | 4.711 | 2.535 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | open -0.899R so far |
| 2026-10-28T19:00Z | LINK | LONG | 2 | 4.004 | 1.907 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AAVE | LONG | 3 | 3.681 | 2.566 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ZEC | LONG | 4 | 2.958 | 1.845 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | SUI | LONG | 5 | 2.865 | 2.033 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | ADA | SHORT | 1 | 3.765 | 1.806 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | none |
| 2026-10-28T19:00Z | ENA | SHORT | 2 | 3.212 | 4.316 | not_top1 | not_top1 |  |
| 2026-10-28T19:00Z | AVAX | SHORT | 3 | 3.148 | 1.565 | not_top1 | not_top1 |  |
| 2026-10-28T20:00Z | ENA | LONG | 1 | 2.954 | 3.138 | filled | filled | closed -1.0326R |
| 2026-10-28T21:00Z | kPEPE | LONG | 1 | 33.946 | 5.778 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T21:00Z | ENA | LONG | 2 | 3.758 | 3.772 | not_top1 | not_top1 |  |
| 2026-10-28T21:00Z | HYPE | LONG | 3 | 2.636 | 1.917 | not_top1 | not_top1 |  |
| 2026-10-28T22:00Z | kPEPE | LONG | 1 | 5.54 | 3.223 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-29T01:00Z | kPEPE | LONG | 1 | 5.777 | 2.5 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-29T02:00Z | ZEC | LONG | 1 | 2.825 | 3.842 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-29T02:00Z | ADA | SHORT | 1 | 3.992 | 3.662 | skipped_off_hours | skipped_off_hours | open 0.165R so far |
| 2026-10-29T02:00Z | HYPE | SHORT | 2 | 3.768 | 2.02 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-29T02:00Z | SUI | SHORT | 3 | 2.922 | 3.066 | skipped_off_hours | skipped_off_hours |  |

