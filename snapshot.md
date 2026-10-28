# Heatwave public snapshot 2026-10-28T10:43:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.45% | 3.096 | 3 | 2026-10-28T10:43:21+00:00 |  |
| propr_h6 | live | -5.321% | 0.679 | 2 | 2026-10-28T10:42:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T10:42:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.498% |  | 0 | 2026-10-28T10:41:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | XRP | LONG | 1.329 | 1.32865 | -0.062 | 1.3332 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:37bb34p1QQGS @ 1.3234 | urn:prp-order:TsgAVf8Vinqx @ 1.3462 |
| propr_2s | kPEPE | LONG | 0.004863 | 0.00496 | 0.858 | 0.004948 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:YVoY6WkuB4Zg @ 0.00475 | urn:prp-order:TEp8h5A5Ctk8 @ 0.005202 |
| propr_2s | BNB | LONG | 753.07 | 756.425 | 0.451 | 758.65 (+0.75R) | False | 2026-10-28T18:55Z | urn:prp-order:RXaPZWoDmUAR @ 745.63 | urn:prp-order:k4tm7yX9RhZb @ 773.67 |
| propr_h6 | BNB | LONG | 753.07 | 756.435 | 0.452 | 758.65 (+0.75R) | False | 2026-10-28T18:55Z | urn:prp-order:UEaLsY7qV85U @ 745.63 | urn:prp-order:zXgorJKQp2j3 @ 773.67 |
| propr_h6 | TRX | LONG | 0.332463 | 0.33238 | -0.058 | 0.333538 (+0.75R) | False | 2026-10-28T18:55Z | urn:prp-order:B52Y8RGYyxiK @ 0.33103 | urn:prp-order:QDH3Ptq53wNk @ 0.33679 |

## Signal scan 2026-10-27T21:00Z .. 2026-10-28T10:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open 0.056R so far |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | open -0.252R so far |
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | open -0.018R so far |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | armed_waiting_breakout | armed_waiting_breakout | pending |

