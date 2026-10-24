# Heatwave public snapshot 2026-10-24T14:18:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.127% | 6.673 | 1 | 2026-10-24T14:16:22+00:00 |  |
| propr_h6 | live | -2.963% | 3.037 | 1 | 2026-10-24T14:16:42+00:00 |  |
| hyro_h6 | h6.16-hyro | -2.042% |  | 0 | 2026-10-24T14:17:59+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.948% |  | 0 | 2026-10-24T14:16:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | NEAR | SHORT | 4.425 | 4.265 | 1.566 | 4.34835 (+0.75R) | False | 2026-10-24T19:55Z | urn:prp-order:x1WPkKiiEGPN @ 4.5272 | urn:prp-order:ktEp2Z1iFG9N @ 4.1184 |
| propr_h6 | NEAR | SHORT | 4.425 | 4.26895 | 1.527 | 4.34835 (+0.75R) | False | 2026-10-24T19:55Z | urn:prp-order:zbrRBgEk9wUi @ 4.5272 | urn:prp-order:7xAfPXf5xhoK @ 4.1184 |

## Signal scan 2026-10-24T01:00Z .. 2026-10-24T14:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-24T01:00Z | ARB | SHORT | 1 | 2.56 | 2.771 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-24T07:00Z | kPEPE | LONG | 1 | 3.425 | 1.79 | skipped_off_hours | skipped_off_hours | none |
| 2026-10-24T10:00Z | NEAR | SHORT | 1 | 4.541 | 2.31 | placed_not_filled (crossing) | placed_not_filled (crossing) | open 0.036R so far |

