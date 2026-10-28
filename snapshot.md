# Heatwave public snapshot 2026-10-28T09:48:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.634% | 2.912 | 2 | 2026-10-28T09:48:23+00:00 |  |
| propr_h6 | live | -5.236% | 0.764 | 1 | 2026-10-28T09:47:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T09:47:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.78% |  | 0 | 2026-10-28T09:46:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | XRP | LONG | 1.329 | 1.33135 | 0.42 | 1.3332 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:37bb34p1QQGS @ 1.3234 | urn:prp-order:TsgAVf8Vinqx @ 1.3462 |
| propr_2s | kPEPE | LONG | 0.004863 | 0.005016 | 1.354 | 0.004948 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:YVoY6WkuB4Zg @ 0.00475 | urn:prp-order:TEp8h5A5Ctk8 @ 0.005202 |
| propr_h6 | kPEPE | LONG | 0.004964 | 0.005016 | 0.473 | 0.005046 (+0.75R) | False | 2026-10-28T18:55Z | urn:prp-order:FPAZzRYuPQz7 @ 0.004854 | urn:prp-order:W31Su7Aq2Ynq @ 0.005302 |

## Signal scan 2026-10-27T20:00Z .. 2026-10-28T09:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open 0.201R so far |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | open 0.446R so far |

