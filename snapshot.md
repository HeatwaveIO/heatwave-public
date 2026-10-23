# Heatwave public snapshot 2026-10-23T22:43:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.354% | 7.307 | 2 | 2026-10-23T22:41:23+00:00 |  |
| propr_h6 | live | -2.3% | 3.7 | 2 | 2026-10-23T22:41:43+00:00 |  |
| hyro_h6 | h6.16-hyro | -1.962% |  | 0 | 2026-10-23T22:42:25+00:00 |  |
| alp100 | {'alp100_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 2.574% |  | 0 | 2026-10-23T22:41:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | DOT | SHORT | 1.1236 | 1.08755 | 0.58 | 1.07695 (+0.75R) | False | 2026-10-23T23:55Z | urn:prp-order:B7go7CbYw4MA @ 1.1858 | urn:prp-order:4ab4FsEsbQSJ @ 0.9666 |
| propr_2s | ENA | SHORT | 0.208231 | 0.197805 | 1.91 | 0.204137 (+0.75R) | True | 2026-10-24T04:55Z | urn:prp-order:2BsS8c5A1Jtc @ 0.20796 | urn:prp-order:b2V2oFqxPUgg @ 0.19533 |
| propr_h6 | DOT | SHORT | 1.1231 | 1.08745 | 0.569 | 1.076075 (+0.75R) | False | 2026-10-23T23:55Z | urn:prp-order:6Hm529c1UrzB @ 1.1858 | urn:prp-order:EM6fxPCMJ9N4 @ 0.9666 |
| propr_h6 | ENA | SHORT | 0.20831 | 0.19773 | 1.967 | 0.204275 (+0.75R) | True | 2026-10-24T04:55Z | urn:prp-order:B2cGTHLpqMNr @ 0.20804 | urn:prp-order:3zcN4RZ1khXQ @ 0.19533 |

## Signal scan 2026-10-23T09:00Z .. 2026-10-23T22:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-23T09:00Z | kPEPE | LONG | 1 | 9.236 | 6.985 | filled | placed_not_filled (expired) | closed -0.6495R |
| 2026-10-23T10:00Z | DOT | LONG | 1 | 5.24 | 1.56 | no_breakout | no_breakout | none |
| 2026-10-23T10:00Z | kPEPE | LONG | 2 | 4.789 | 1.581 | not_top1 | not_top1 |  |
| 2026-10-23T11:00Z | kPEPE | LONG | 1 | 3.894 | 2.679 | skipped_symbol_in_use | filled | closed -1.0411R |
| 2026-10-23T12:00Z | kPEPE | LONG | 1 | 5.118 | 4.267 | no_breakout | no_breakout | none |
| 2026-10-23T12:00Z | ZEC | SHORT | 1 | 3.492 | 3.212 | no_breakout | no_breakout | none |
| 2026-10-23T14:00Z | kPEPE | LONG | 1 | 2.953 | 2.352 | no_breakout | no_breakout | none |
| 2026-10-23T14:00Z | DOT | SHORT | 1 | 3.227 | 4.845 | filled | filled | open 0.549R so far |
| 2026-10-23T15:00Z | kPEPE | LONG | 1 | 2.859 | 5.594 | no_breakout | no_breakout | none |
| 2026-10-23T17:00Z | ENA | SHORT | 1 | 2.868 | 3.788 | skipped_slots_full | skipped_slots_full | open 0.384R so far |
| 2026-10-23T19:00Z | ENA | SHORT | 1 | 2.75 | 2.195 | filled | filled | open 1.899R so far |
| 2026-10-23T20:00Z | WLD | SHORT | 1 | 3.519 | 2.425 | skipped_slots_full | skipped_slots_full | open 2.309R so far |

