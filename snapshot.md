# Heatwave public snapshot 2026-10-25T17:28:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | 2.237% | 6.783 | 0 | 2026-10-25T17:28:21+00:00 |  |
| propr_h6 | live | -3.996% | 2.004 | 0 | 2026-10-25T17:28:43+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-25T17:27:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-21T19:55:46+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 1.728% |  | 0 | 2026-10-25T17:26:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-25T04:00Z .. 2026-10-25T17:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-25T09:00Z | WLD | SHORT | 1 | 9.083 | 7.857 | no_breakout | no_breakout | none |
| 2026-10-25T12:00Z | WLD | SHORT | 1 | 2.981 | 2.983 | armed_waiting_breakout | armed_waiting_breakout | pending |
| 2026-10-25T14:00Z | kPEPE | LONG | 1 | 2.636 | 2.038 | armed_waiting_breakout | armed_waiting_breakout | pending |

