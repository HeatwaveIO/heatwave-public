# Heatwave public snapshot 2026-10-28T08:18:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.833% | 2.713 | 3 | 2026-10-28T08:18:36+00:00 |  |
| propr_h6 | live | -5.409% | 0.591 | 1 | 2026-10-28T08:17:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T08:17:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.53% |  | 0 | 2026-10-28T08:16:33Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | AVAX | LONG | 9.0216 | 9.0004 | -0.295 | 9.07545 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:xuET6DYTtYWc @ 8.9498 | urn:prp-order:tEC7yb1bJ8kJ @ 9.193 |
| propr_2s | XRP | LONG | 1.3291 | 1.33005 | 0.167 | 1.333375 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:37bb34p1QQGS @ 1.3234 | urn:prp-order:TsgAVf8Vinqx @ 1.3462 |
| propr_2s | kPEPE | LONG | 0.004863 | 0.004884 | 0.186 | 0.004948 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:YVoY6WkuB4Zg @ 0.00475 | urn:prp-order:TEp8h5A5Ctk8 @ 0.005202 |
| propr_h6 | AVAX | LONG | 9.0216 | 9.00045 | -0.295 | 9.07545 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:xHjXCmiy8Evs @ 8.9498 | urn:prp-order:h94dhn37cCsu @ 9.193 |

## Signal scan 2026-10-27T19:00Z .. 2026-10-28T08:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open -0.159R so far |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | pending |

