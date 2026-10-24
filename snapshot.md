# Heatwave public snapshot 2026-10-24T00:03:39Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 3.073% | 7.619 | 0 | 2026-10-24T00:01:24+00:00 |  |
| propr_h6 | live | -2.039% | 3.961 | 0 | 2026-10-24T00:01:43+00:00 |  |
| hyro_h6 | h6.16-hyro | -1.962% |  | 0 | 2026-10-24T00:02:33+00:00 | HTTPError: HTTP Error 429: Too Many Requests |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 2.924% |  | 0 | 2026-10-23T23:56:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-23T11:00Z .. 2026-10-24T00:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-23T11:00Z | kPEPE | LONG | 1 | 3.894 | 2.679 | skipped_symbol_in_use | filled | closed -1.0411R |
| 2026-10-23T12:00Z | kPEPE | LONG | 1 | 5.118 | 4.267 | no_breakout | no_breakout | none |
| 2026-10-23T12:00Z | ZEC | SHORT | 1 | 3.492 | 3.212 | no_breakout | no_breakout | none |
| 2026-10-23T14:00Z | kPEPE | LONG | 1 | 2.953 | 2.352 | no_breakout | no_breakout | none |
| 2026-10-23T14:00Z | DOT | SHORT | 1 | 3.227 | 4.845 | filled | filled | closed 0.5674R |
| 2026-10-23T15:00Z | kPEPE | LONG | 1 | 2.859 | 5.594 | no_breakout | no_breakout | none |
| 2026-10-23T17:00Z | ENA | SHORT | 1 | 2.868 | 3.788 | skipped_slots_full | skipped_slots_full | open 0.325R so far |
| 2026-10-23T19:00Z | ENA | SHORT | 1 | 2.75 | 2.195 | filled | filled | open 1.791R so far |
| 2026-10-23T20:00Z | WLD | SHORT | 1 | 3.519 | 2.425 | skipped_slots_full | skipped_slots_full | open 2.532R so far |
| 2026-10-23T23:00Z | kPEPE | LONG | 1 | 3.796 | 2.813 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-23T23:00Z | WLD | SHORT | 1 | 9.117 | 8.455 | skipped_off_hours | skipped_off_hours | replay unavailable |
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
| 2026-10-24T00:00Z | kPEPE | LONG | 1 | 6.191 | 1.683 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-24T00:00Z | DOGE | SHORT | 1 | 5.684 | 1.666 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-24T00:00Z | LTC | SHORT | 2 | 5.239 | 2.039 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | WLD | SHORT | 3 | 3.69 | 1.864 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | SUI | SHORT | 4 | 3.408 | 2.036 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | DOT | SHORT | 5 | 3.376 | 1.914 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | ZEC | SHORT | 6 | 3.263 | 2.444 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-24T00:00Z | ENA | SHORT | 7 | 2.892 | 3.1 | skipped_off_hours | skipped_off_hours |  |

