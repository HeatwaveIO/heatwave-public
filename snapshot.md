# Heatwave public snapshot 2026-10-23T22:58:41Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 3.433% | 7.982 | 1 | 2026-10-23T22:56:28+00:00 |  |
| propr_h6 | live | -1.805% | 4.195 | 1 | 2026-10-23T22:56:42+00:00 |  |
| hyro_h6 | h6.16-hyro | -1.962% |  | 0 | 2026-10-23T22:57:34+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.252% |  | 0 | 2026-10-23T22:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | DOT | SHORT | 1.1236 | 1.0745 | 0.789 | 1.07695 (+0.75R) | True | 2026-10-23T23:55Z | urn:prp-order:Bn6ppky6mQ8T @ 1.1205 | urn:prp-order:4ab4FsEsbQSJ @ 0.9666 |
| propr_h6 | DOT | SHORT | 1.1231 | 1.07475 | 0.771 | 1.076075 (+0.75R) | True | 2026-10-23T23:55Z | urn:prp-order:RAAp1aJ4PW7b @ 1.12 | urn:prp-order:EM6fxPCMJ9N4 @ 0.9666 |

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
| 2026-10-23T14:00Z | DOT | SHORT | 1 | 3.227 | 4.845 | filled | filled | open 0.837R so far |
| 2026-10-23T15:00Z | kPEPE | LONG | 1 | 2.859 | 5.594 | no_breakout | no_breakout | none |
| 2026-10-23T17:00Z | ENA | SHORT | 1 | 2.868 | 3.788 | skipped_slots_full | skipped_slots_full | open 0.854R so far |
| 2026-10-23T19:00Z | ENA | SHORT | 1 | 2.75 | 2.195 | filled | filled | open 2.763R so far |
| 2026-10-23T20:00Z | WLD | SHORT | 1 | 3.519 | 2.425 | skipped_slots_full | skipped_slots_full | open 2.756R so far |

