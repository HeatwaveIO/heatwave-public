# Heatwave public snapshot 2026-10-24T07:38:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.064% | 6.61 | 1 | 2026-10-24T07:36:30+00:00 |  |
| propr_h6 | live | -3.002% | 2.998 | 1 | 2026-10-24T07:36:43+00:00 |  |
| hyro_h6 | h6.16-hyro | -2.042% |  | 0 | 2026-10-24T07:37:52+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 3.878% |  | 0 | 2026-10-24T07:36:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | ARB | SHORT | 0.1677 | 0.16967 | -0.365 | 0.16365 (+0.75R) | False | 2026-10-24T09:55Z | urn:prp-order:JKDQEsbWAJCw @ 0.1731 | urn:prp-order:f8UXf7G5BgPe @ 0.15986 |
| propr_h6 | ARB | SHORT | 0.167857 | 0.16967 | -0.346 | 0.163925 (+0.75R) | False | 2026-10-24T09:55Z | urn:prp-order:VmGLUMRgkGs6 @ 0.1731 | urn:prp-order:Vu9cSa1bucET @ 0.15986 |

## Signal scan 2026-10-23T18:00Z .. 2026-10-24T07:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-23T19:00Z | ENA | SHORT | 1 | 2.75 | 2.195 | filled | filled | closed 1.4756R |
| 2026-10-23T20:00Z | WLD | SHORT | 1 | 3.519 | 2.425 | skipped_slots_full | skipped_slots_full | closed 2.9607R |
| 2026-10-23T23:00Z | kPEPE | LONG | 1 | 3.796 | 2.813 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-23T23:00Z | WLD | SHORT | 1 | 9.117 | 8.455 | skipped_off_hours | skipped_off_hours | open 0.015R so far |
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
| 2026-10-24T00:00Z | kPEPE | LONG | 1 | 6.191 | 1.683 | skipped_off_hours | skipped_off_hours | closed -1.0689R |
| 2026-10-24T00:00Z | DOGE | SHORT | 1 | 5.684 | 1.666 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-24T00:00Z | LTC | SHORT | 2 | 5.239 | 2.039 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | WLD | SHORT | 3 | 3.69 | 1.864 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | SUI | SHORT | 4 | 3.408 | 2.036 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | DOT | SHORT | 5 | 3.376 | 1.914 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | ZEC | SHORT | 6 | 3.263 | 2.444 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | ENA | SHORT | 7 | 2.892 | 3.1 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T01:00Z | ARB | SHORT | 1 | 2.56 | 2.771 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-24T07:00Z | kPEPE | LONG | 1 | 3.425 | 1.79 | skipped_off_hours | skipped_off_hours | pending |

