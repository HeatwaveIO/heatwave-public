# Heatwave public snapshot 2026-10-28T10:03:34Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.356% | 3.189 | 3 | 2026-10-28T10:03:20+00:00 |  |
| propr_h6 | live | -5.209% | 0.791 | 2 | 2026-10-28T10:02:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T10:02:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.61% |  | 0 | 2026-10-28T09:56:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | XRP | LONG | 1.329 | 1.33235 | 0.598 | 1.3332 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:37bb34p1QQGS @ 1.3234 | urn:prp-order:TsgAVf8Vinqx @ 1.3462 |
| propr_2s | kPEPE | LONG | 0.004863 | 0.005018 | 1.372 | 0.004948 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:YVoY6WkuB4Zg @ 0.00475 | urn:prp-order:TEp8h5A5Ctk8 @ 0.005202 |
| propr_2s | BNB | LONG | 753.07 | 755.285 | 0.298 | 758.65 (+0.75R) | False | 2026-10-28T18:55Z | urn:prp-order:RXaPZWoDmUAR @ 745.63 | urn:prp-order:k4tm7yX9RhZb @ 773.67 |
| propr_h6 | kPEPE | LONG | 0.004964 | 0.005017 | 0.482 | 0.005046 (+0.75R) | True | 2026-10-28T18:55Z | urn:prp-order:WMRX1hcWRQ1v @ 0.00497 | urn:prp-order:W31Su7Aq2Ynq @ 0.005302 |
| propr_h6 | BNB | LONG | 753.07 | 755.28 | 0.297 | 758.65 (+0.75R) | False | 2026-10-28T18:55Z | urn:prp-order:UEaLsY7qV85U @ 745.63 | urn:prp-order:zXgorJKQp2j3 @ 773.67 |

## Signal scan 2026-10-27T21:00Z .. 2026-10-28T10:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open 0.212R so far |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | open 0.014R so far |
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | open 0.482R so far |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |

