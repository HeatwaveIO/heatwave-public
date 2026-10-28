# Heatwave public snapshot 2026-10-28T08:08:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.677% | 2.869 | 2 | 2026-10-28T08:08:28+00:00 |  |
| propr_h6 | live | -5.342% | 0.658 | 1 | 2026-10-28T08:08:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T08:07:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.092% |  | 0 | 2026-10-28T07:56:33Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | AVAX | LONG | 9.0106 | 9.0224 | 0.194 | 9.0562 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:NfXUhssuHUt9 @ 8.9498 | urn:prp-order:WXW2snDEb72g @ 9.193 |
| propr_2s | XRP | LONG | 1.3291 | 1.33035 | 0.219 | 1.333375 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:cPCzngtPSY54 @ 1.3234 | urn:prp-order:VYCz1phWBZjQ @ 1.3462 |
| propr_h6 | AVAX | LONG | 9.0106 | 9.0226 | 0.197 | 9.0562 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:H6YZjrUQmwMr @ 8.9498 | urn:prp-order:fYcWiwHpU3e7 @ 9.193 |

## Signal scan 2026-10-27T19:00Z .. 2026-10-28T08:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open -0.111R so far |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | pending |

