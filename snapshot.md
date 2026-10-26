# Heatwave public snapshot 2026-10-26T08:38:31Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 0.427% | 4.972 | 2 | 2026-10-26T08:38:22+00:00 |  |
| propr_h6 | live | -5.153% | 0.847 | 2 | 2026-10-26T08:37:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-26T08:37:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.598% |  | 0 | 2026-10-26T08:36:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | NEAR | SHORT | 4.441702 | 4.5208 | -0.534 | 4.330704 (+0.75R) | False | 2026-10-26T11:55Z | urn:prp-order:nFG4R9xUWCeK @ 4.5897 | urn:prp-order:piayoWVzw9Yg @ 3.9977 |
| propr_2s | ENA | SHORT | 0.20405 | 0.21003 | -0.958 | 0.19937 (+0.75R) | False | 2026-10-26T17:55Z | urn:prp-order:xHXBzkjKRzVq @ 0.21029 | urn:prp-order:WfFtJ9iCfsrf @ 0.18525 |
| propr_h6 | NEAR | SHORT | 4.441702 | 4.5173 | -0.511 | 4.330704 (+0.75R) | False | 2026-10-26T11:55Z | urn:prp-order:3rsBjknpMoLt @ 4.5897 | urn:prp-order:jksAGmmvyyET @ 3.9977 |
| propr_h6 | ENA | SHORT | 0.20403 | 0.20999 | -0.952 | 0.199335 (+0.75R) | False | 2026-10-26T17:55Z | urn:prp-order:yg1DwswvRuAk @ 0.21029 | urn:prp-order:4dYkY1J2YL2i @ 0.18525 |

## Signal scan 2026-10-25T19:00Z .. 2026-10-26T08:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-26T00:00Z | ENA | LONG | 1 | 5.417 | 2.212 | skipped_off_hours | skipped_off_hours | closed -1.0561R |
| 2026-10-26T00:00Z | ZEC | SHORT | 1 | 5.492 | 3.125 | skipped_off_hours | skipped_off_hours | open -0.943R so far |
| 2026-10-26T00:00Z | APT | SHORT | 2 | 3.083 | 1.628 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-26T01:00Z | ENA | LONG | 1 | 2.509 | 1.961 | skipped_off_hours | skipped_off_hours | closed -1.0568R |
| 2026-10-26T02:00Z | kPEPE | LONG | 1 | 2.666 | 1.889 | skipped_off_hours | skipped_off_hours | open 0.661R so far |
| 2026-10-26T02:00Z | NEAR | SHORT | 1 | 2.98 | 3.332 | skipped_off_hours | skipped_off_hours | open -0.545R so far |
| 2026-10-26T08:00Z | ENA | SHORT | 1 | 2.563 | 3.068 | skipped_off_hours | skipped_off_hours | open -0.95R so far |

