# Heatwave public snapshot 2026-10-28T18:43:31Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T18:42:51+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 0.692% |  | 0 | 2026-10-28T18:41:32Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-28T05:00Z .. 2026-10-28T18:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T09:00Z | kPEPE | LONG | 1 | 4.987 | 2.255 | unknown (account read failed) | unknown (account read failed) | closed -1.0488R |
| 2026-10-28T10:00Z | kPEPE | LONG | 1 | 13.754 | 2.179 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-10-28T13:00Z | kPEPE | LONG | 1 | 3.279 | 2.682 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-10-28T13:00Z | AAVE | SHORT | 1 | 3.66 | 2.39 | unknown (account read failed) | unknown (account read failed) | closed -1.0571R |

