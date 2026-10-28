# Heatwave public snapshot 2026-10-28T13:43:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -2.238% | 2.308 | 3 | 2026-10-28T13:43:28+00:00 |  |
| propr_h6 | live | -5.473% | 0.527 | 2 | 2026-10-28T13:43:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T13:42:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.83% |  | 0 | 2026-10-28T13:41:32Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | kPEPE | LONG | 0.004863 | 0.004846 | -0.15 | 0.004948 (+0.75R) | False | 2026-10-28T17:55Z | urn:prp-order:YVoY6WkuB4Zg @ 0.00475 | urn:prp-order:TEp8h5A5Ctk8 @ 0.005202 |
| propr_2s | AAVE | SHORT | 131.83 | 132.5 | -0.216 | 129.505 (+0.75R) | False | 2026-10-28T22:55Z | urn:prp-order:GdY4TARpadvX @ 134.93 | urn:prp-order:nsfzw9fFV93y @ 122.33 |
| propr_2s | ENA | SHORT | 0.19838 | 0.19858 | -0.037 | 0.194285 (+0.75R) | False | 2026-10-28T22:55Z | urn:prp-order:TSkehGPni2vJ @ 0.20384 | urn:prp-order:vNdUgNQneQqR @ 0.18136 |
| propr_h6 | ENA | SHORT | 0.203 | 0.198755 | 1.129 | 0.20018 (+0.75R) | False | 2026-10-28T21:55Z | urn:prp-order:nGNUxaf6JLSK @ 0.20676 | urn:prp-order:EWBsXk5zhdED @ 0.19172 |
| propr_h6 | AAVE | SHORT | 131.88 | 132.515 | -0.208 | 129.5925 (+0.75R) | False | 2026-10-28T22:55Z | urn:prp-order:rpEM9WPGVQJm @ 134.93 | urn:prp-order:qrfP2UEMnb9a @ 122.33 |

## Signal scan 2026-10-28T00:00Z .. 2026-10-28T13:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | closed 0.1102R |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | open -0.786R so far |
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | closed -1.0488R |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | armed_waiting_breakout | armed_waiting_breakout | pending |
| 2026-10-28T13:00Z | kPEPE | LONG | 1 | 3.279 | 2.682 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T13:00Z | AAVE | SHORT | 1 | 3.66 | 2.39 | filled | filled | open -0.016R so far |

