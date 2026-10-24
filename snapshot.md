# Heatwave public snapshot 2026-10-24T03:38:38Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.629% | 7.175 | 2 | 2026-10-24T03:36:30+00:00 |  |
| propr_h6 | live | -2.447% | 3.553 | 2 | 2026-10-24T03:36:42+00:00 |  |
| hyro_h6 | h6.16-hyro | -2.042% |  | 0 | 2026-10-24T03:37:52+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 3.276% |  | 0 | 2026-10-24T03:36:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | ARB | SHORT | 0.1677 | 0.17199 | -0.794 | 0.16365 (+0.75R) | False | 2026-10-24T09:55Z | urn:prp-order:JKDQEsbWAJCw @ 0.1731 | urn:prp-order:f8UXf7G5BgPe @ 0.15986 |
| propr_2s | kPEPE | LONG | 0.004566 | 0.004583 | 0.246 | 0.004618 (+0.75R) | False | 2026-10-24T09:55Z | urn:prp-order:m1erWyCmWb9H @ 0.004497 | urn:prp-order:Gw2cCQpQjwWc @ 0.004805 |
| propr_h6 | ARB | SHORT | 0.167857 | 0.17196 | -0.783 | 0.163925 (+0.75R) | False | 2026-10-24T09:55Z | urn:prp-order:VmGLUMRgkGs6 @ 0.1731 | urn:prp-order:Vu9cSa1bucET @ 0.15986 |
| propr_h6 | kPEPE | LONG | 0.004563 | 0.004582 | 0.288 | 0.004613 (+0.75R) | False | 2026-10-24T09:55Z | urn:prp-order:ZDSFp34JoPvA @ 0.004497 | urn:prp-order:Vx8yzB5p5JzQ @ 0.004805 |

## Signal scan 2026-10-23T14:00Z .. 2026-10-24T03:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-23T14:00Z | kPEPE | LONG | 1 | 2.953 | 2.352 | no_breakout | no_breakout | none |
| 2026-10-23T14:00Z | DOT | SHORT | 1 | 3.227 | 4.845 | filled | filled | closed 0.5674R |
| 2026-10-23T15:00Z | kPEPE | LONG | 1 | 2.859 | 5.594 | no_breakout | no_breakout | none |
| 2026-10-23T17:00Z | ENA | SHORT | 1 | 2.868 | 3.788 | skipped_slots_full | skipped_slots_full | closed 0.3246R |
| 2026-10-23T19:00Z | ENA | SHORT | 1 | 2.75 | 2.195 | filled | filled | open 1.442R so far |
| 2026-10-23T20:00Z | WLD | SHORT | 1 | 3.519 | 2.425 | skipped_slots_full | skipped_slots_full | closed 2.9607R |
| 2026-10-23T23:00Z | kPEPE | LONG | 1 | 3.796 | 2.813 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-23T23:00Z | WLD | SHORT | 1 | 9.117 | 8.455 | skipped_off_hours | skipped_off_hours | open -0.252R so far |
| 2026-10-23T23:00Z | ENA | SHORT | 2 | 6.428 | 6.829 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | ZEC | SHORT | 3 | 5.959 | 6.422 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | LTC | SHORT | 4 | 4.235 | 2.476 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | XRP | SHORT | 5 | 3.87 | 2.194 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | NEAR | SHORT | 6 | 3.867 | 4.953 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | DOT | SHORT | 7 | 3.662 | 4.124 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | SOL | SHORT | 8 | 3.223 | 2.145 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | AAVE | SHORT | 9 | 3.15 | 4.103 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | ARB | SHORT | 10 | 3.084 | 5.269 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | ETH | SHORT | 11 | 3.067 | 2.239 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | SUI | SHORT | 12 | 2.898 | 4.083 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-23T23:00Z | AVAX | SHORT | 13 | 2.71 | 3.26 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | kPEPE | LONG | 1 | 6.191 | 1.683 | skipped_off_hours | skipped_off_hours | open 0.192R so far |
| 2026-10-24T00:00Z | DOGE | SHORT | 1 | 5.684 | 1.666 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-24T00:00Z | LTC | SHORT | 2 | 5.239 | 2.039 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | WLD | SHORT | 3 | 3.69 | 1.864 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | SUI | SHORT | 4 | 3.408 | 2.036 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | DOT | SHORT | 5 | 3.376 | 1.914 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | ZEC | SHORT | 6 | 3.263 | 2.444 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | ENA | SHORT | 7 | 2.892 | 3.1 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T01:00Z | ARB | SHORT | 1 | 2.56 | 2.771 | skipped_off_hours | skipped_off_hours | pending |

