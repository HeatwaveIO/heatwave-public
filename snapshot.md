# Heatwave public snapshot 2026-10-28T11:28:39Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.228% | 3.318 | 3 | 2026-10-28T11:28:28+00:00 |  |
| propr_h6 | live | -5.268% | 0.732 | 3 | 2026-10-28T11:28:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T11:27:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.12% |  | 0 | 2026-10-28T11:26:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | kPEPE | LONG | 0.004863 | 0.004962 | 0.876 | 0.004948 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:YVoY6WkuB4Zg @ 0.00475 | urn:prp-order:TEp8h5A5Ctk8 @ 0.005202 |
| propr_2s | BNB | LONG | 753.07 | 760.62 | 1.015 | 758.65 (+0.75R) | True | 2026-10-28T18:55Z | urn:prp-order:42YW7KeGQzqp @ 753.42 | urn:prp-order:k4tm7yX9RhZb @ 773.67 |
| propr_2s | xyz:BRENTOIL | LONG | 111.23 | 111.235 | 0.007 | 111.7775 (+0.75R) | False | 2026-10-28T20:55Z | urn:prp-order:XduMkUB2k1Mr @ 110.5 | urn:prp-order:VoVeysXTT4bG @ 113.42 |
| propr_h6 | BNB | LONG | 753.07 | 760.65 | 1.019 | 758.65 (+0.75R) | True | 2026-10-28T18:55Z | urn:prp-order:Uwyb549s2BP9 @ 753.42 | urn:prp-order:zXgorJKQp2j3 @ 773.67 |
| propr_h6 | TRX | LONG | 0.332463 | 0.332265 | -0.138 | 0.333538 (+0.75R) | False | 2026-10-28T18:55Z | urn:prp-order:B52Y8RGYyxiK @ 0.33103 | urn:prp-order:QDH3Ptq53wNk @ 0.33679 |
| propr_h6 | xyz:BRENTOIL | LONG | 111.23 | 111.235 | 0.007 | 111.7775 (+0.75R) | False | 2026-10-28T20:55Z | urn:prp-order:TAPabboCQnss @ 110.5 | urn:prp-order:Bsaek1vZiJT8 @ 113.42 |

## Signal scan 2026-10-27T22:00Z .. 2026-10-28T11:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open 0.064R so far |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | open -0.238R so far |
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | open 0.009R so far |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | armed_waiting_breakout | armed_waiting_breakout | pending |

