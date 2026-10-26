# Heatwave public snapshot 2026-10-26T03:08:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.237% | 6.783 | 0 | 2026-10-26T03:08:23+00:00 |  |
| propr_h6 | live | -3.996% | 2.004 | 0 | 2026-10-26T03:08:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-26T03:07:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 5.382% |  | 0 | 2026-10-26T02:56:32Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-25T14:00Z .. 2026-10-26T03:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-25T14:00Z | kPEPE | LONG | 1 | 2.636 | 2.038 | no_breakout | no_breakout | none |
| 2026-10-26T00:00Z | ENA | LONG | 1 | 5.417 | 2.212 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-26T00:00Z | ZEC | SHORT | 1 | 5.492 | 3.125 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-26T00:00Z | APT | SHORT | 2 | 3.083 | 1.628 | skipped_off_hours | skipped_off_hours |  |
| 2026-10-26T01:00Z | ENA | LONG | 1 | 2.509 | 1.961 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-26T02:00Z | kPEPE | LONG | 1 | 2.666 | 1.889 | skipped_off_hours | skipped_off_hours | pending |
| 2026-10-26T02:00Z | NEAR | SHORT | 1 | 2.98 | 3.332 | skipped_off_hours | skipped_off_hours | pending |

