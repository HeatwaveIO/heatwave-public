# Heatwave public snapshot 2026-10-25T07:53:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.237% | 6.783 | 0 | 2026-10-25T07:53:23+00:00 |  |
| propr_h6 | live | -3.996% | 2.004 | 0 | 2026-10-25T07:52:42+00:00 |  |
| hyro_h6 | h6.16-hyro | -1.967% |  | 0 | 2026-10-25T07:52:51+00:00 |  |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 2.288% |  | 0 | 2026-10-25T07:51:32Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-24T18:00Z .. 2026-10-25T07:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-24T19:00Z | kPEPE | LONG | 1 | 3.754 | 2.536 | skipped_slots_full | skipped_room_clamp | closed 0.0066R |
| 2026-10-24T19:00Z | ZEC | SHORT | 1 | 4.266 | 3.494 | no_breakout | no_breakout | none |
| 2026-10-24T19:00Z | DOT | SHORT | 2 | 3.424 | 1.544 | not_top1 | not_top1 |  |

