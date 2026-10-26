# Heatwave public snapshot 2026-10-26T04:03:36Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 1.906% | 6.451 | 2 | 2026-10-26T04:03:34+00:00 |  |
| propr_h6 | live | -4.228% | 1.772 | 2 | 2026-10-26T04:02:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-26T04:02:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 6.26% |  | 0 | 2026-10-26T03:56:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | ZEC | SHORT | 1185.3 | 1193.25 | -0.223 | 1158.525 (+0.75R) | False | 2026-10-26T09:55Z | urn:prp-order:rcWNtG8fNsw2 @ 1221 | urn:prp-order:YJdLWpsBNJkq @ 1073 |
| propr_2s | NEAR | SHORT | 4.441702 | 4.47695 | -0.238 | 4.330704 (+0.75R) | False | 2026-10-26T11:55Z | urn:prp-order:nFG4R9xUWCeK @ 4.5897 | urn:prp-order:piayoWVzw9Yg @ 3.9977 |
| propr_h6 | ZEC | SHORT | 1184.9 | 1193.15 | -0.229 | 1157.825 (+0.75R) | False | 2026-10-26T09:55Z | urn:prp-order:aNTH8tfKrEPp @ 1221 | urn:prp-order:zDAufqXZNCBe @ 1073 |
| propr_h6 | NEAR | SHORT | 4.441702 | 4.4764 | -0.234 | 4.330704 (+0.75R) | False | 2026-10-26T11:55Z | urn:prp-order:3rsBjknpMoLt @ 4.5897 | urn:prp-order:jksAGmmvyyET @ 3.9977 |

## Signal scan 2026-10-25T15:00Z .. 2026-10-26T04:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-26T00:00Z | ENA | LONG | 1 | 5.417 | 2.212 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-26T00:00Z | ZEC | SHORT | 1 | 5.492 | 3.125 | skipped_off_hours | skipped_off_hours | open -0.084R so far |
| 2026-10-26T00:00Z | APT | SHORT | 2 | 3.083 | 1.628 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-26T01:00Z | ENA | LONG | 1 | 2.509 | 1.961 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-26T02:00Z | kPEPE | LONG | 1 | 2.666 | 1.889 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-26T02:00Z | NEAR | SHORT | 1 | 2.98 | 3.332 | skipped_off_hours | skipped_off_hours | open -0.172R so far |

