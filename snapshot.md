# Heatwave public snapshot 2026-10-23T23:53:46Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 3.112% | 7.657 | 1 | 2026-10-23T23:51:35+00:00 |  |
| propr_h6 | live | -2.01% | 3.99 | 1 | 2026-10-23T23:51:42+00:00 |  |
| hyro_h6 | h6.16-hyro | -1.962% |  | 0 | 2026-10-23T23:52:34+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 3.094% |  | 0 | 2026-10-23T23:51:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | DOT | SHORT | 1.1236 | 1.0842 | 0.633 | 1.07695 (+0.75R) | True | 2026-10-23T23:55Z | urn:prp-order:Bn6ppky6mQ8T @ 1.1205 | urn:prp-order:4ab4FsEsbQSJ @ 0.9666 |
| propr_h6 | DOT | SHORT | 1.1231 | 1.0842 | 0.62 | 1.076075 (+0.75R) | True | 2026-10-23T23:55Z | urn:prp-order:RAAp1aJ4PW7b @ 1.12 | urn:prp-order:EM6fxPCMJ9N4 @ 0.9666 |

## Signal scan 2026-10-23T10:00Z .. 2026-10-23T23:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-23T10:00Z | DOT | LONG | 1 | 5.24 | 1.56 | no_breakout | no_breakout | none |
| 2026-10-23T10:00Z | kPEPE | LONG | 2 | 4.789 | 1.581 | not_top1 | not_top1 |  |
| 2026-10-23T11:00Z | kPEPE | LONG | 1 | 3.894 | 2.679 | skipped_symbol_in_use | filled | closed -1.0411R |
| 2026-10-23T12:00Z | kPEPE | LONG | 1 | 5.118 | 4.267 | no_breakout | no_breakout | none |
| 2026-10-23T12:00Z | ZEC | SHORT | 1 | 3.492 | 3.212 | no_breakout | no_breakout | none |
| 2026-10-23T14:00Z | kPEPE | LONG | 1 | 2.953 | 2.352 | no_breakout | no_breakout | none |
| 2026-10-23T14:00Z | DOT | SHORT | 1 | 3.227 | 4.845 | filled | filled | open 0.614R so far |
| 2026-10-23T15:00Z | kPEPE | LONG | 1 | 2.859 | 5.594 | no_breakout | no_breakout | none |
| 2026-10-23T17:00Z | ENA | SHORT | 1 | 2.868 | 3.788 | skipped_slots_full | skipped_slots_full | open 0.256R so far |
| 2026-10-23T19:00Z | ENA | SHORT | 1 | 2.75 | 2.195 | filled | filled | open 1.664R so far |
| 2026-10-23T20:00Z | WLD | SHORT | 1 | 3.519 | 2.425 | skipped_slots_full | skipped_slots_full | open 2.264R so far |
| 2026-10-23T23:00Z | kPEPE | LONG | 1 | 3.796 | 2.813 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-23T23:00Z | WLD | SHORT | 1 | 9.117 | 8.455 | skipped_off_hours | skipped_off_hours | pending |
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

