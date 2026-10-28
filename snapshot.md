# Heatwave public snapshot 2026-10-28T14:33:39Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.898% | 2.648 | 3 | 2026-10-28T14:33:20+00:00 |  |
| propr_h6 | live | -5.469% | 0.531 | 2 | 2026-10-28T14:33:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T14:32:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 1.278% |  | 0 | 2026-10-28T14:33:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | AAVE | SHORT | 131.83 | 131.54 | 0.094 | 129.505 (+0.75R) | False | 2026-10-28T22:55Z | urn:prp-order:GdY4TARpadvX @ 134.93 | urn:prp-order:nsfzw9fFV93y @ 122.33 |
| propr_2s | ENA | SHORT | 0.19838 | 0.194225 | 0.761 | 0.194285 (+0.75R) | True | 2026-10-28T22:55Z | urn:prp-order:x5pTbtRUKR9N @ 0.1981 | urn:prp-order:vNdUgNQneQqR @ 0.18136 |
| propr_2s | UNI | SHORT | 7.0067 | 7.01375 | -0.052 | 6.905225 (+0.75R) | False | 2026-10-28T22:55Z | urn:prp-order:dDkHifrWbKS8 @ 7.142 | urn:prp-order:BLLHMi5m2ddD @ 6.5984 |
| propr_h6 | ENA | SHORT | 0.203 | 0.194075 | 2.374 | 0.20018 (+0.75R) | False | 2026-10-28T21:55Z | urn:prp-order:nGNUxaf6JLSK @ 0.20676 | urn:prp-order:EWBsXk5zhdED @ 0.19172 |
| propr_h6 | AAVE | SHORT | 131.88 | 131.505 | 0.123 | 129.5925 (+0.75R) | False | 2026-10-28T22:55Z | urn:prp-order:rpEM9WPGVQJm @ 134.93 | urn:prp-order:qrfP2UEMnb9a @ 122.33 |

## Signal scan 2026-10-28T01:00Z .. 2026-10-28T14:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | closed 0.1102R |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-28T04:00Z | kPEPE | LONG | 1 | 3.099 | 4.186 | skipped_off_hours | skipped_off_hours | closed -0.7501R |
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | skipped_symbol_in_use | filled | closed -1.0488R |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | armed_waiting_breakout | armed_waiting_breakout | pending |
| 2026-10-28T13:00Z | kPEPE | LONG | 1 | 3.279 | 2.682 | not_picked_by_executor (data / timing) | not_picked_by_executor (data / timing) | pending |
| 2026-10-28T13:00Z | AAVE | SHORT | 1 | 3.66 | 2.39 | filled | filled | open 0.384R so far |

