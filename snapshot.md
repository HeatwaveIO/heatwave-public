# Heatwave public snapshot 2026-10-25T04:28:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.237% | 6.783 | 0 | 2026-10-25T04:28:22+00:00 |  |
| propr_h6 | live | -3.996% | 2.004 | 0 | 2026-10-25T04:28:42+00:00 |  |
| hyro_h6 | h6.16-hyro | -2.044% |  | 1 | 2026-10-25T04:27:52+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 1.588% |  | 0 | 2026-10-25T04:26:33Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-24T15:00Z .. 2026-10-25T04:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-24T15:00Z | DOGE | SHORT | 1 | 4.023 | 2.835 | filled | filled | closed -1.038R |
| 2026-10-24T15:00Z | NEAR | SHORT | 2 | 3.365 | 5.092 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | SOL | SHORT | 3 | 2.714 | 1.847 | not_top1 | not_top1 |  |
| 2026-10-24T15:00Z | ETH | SHORT | 4 | 2.512 | 1.744 | not_top1 | not_top1 |  |
| 2026-10-24T16:00Z | kPEPE | LONG | 1 | 2.55 | 2.238 | filled | skipped_room_clamp | closed 1.3274R |
| 2026-10-24T16:00Z | ETH | SHORT | 1 | 3.206 | 2.661 | no_breakout | no_breakout | none |
| 2026-10-24T16:00Z | AAVE | SHORT | 2 | 3.005 | 1.718 | not_top1 | not_top1 |  |
| 2026-10-24T19:00Z | kPEPE | LONG | 1 | 3.754 | 2.536 | skipped_slots_full | skipped_room_clamp | closed 0.0066R |
| 2026-10-24T19:00Z | ZEC | SHORT | 1 | 4.266 | 3.494 | no_breakout | no_breakout | none |
| 2026-10-24T19:00Z | DOT | SHORT | 2 | 3.424 | 1.544 | not_top1 | not_top1 |  |

