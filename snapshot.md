# Heatwave public snapshot 2026-10-31T05:43:39Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-31T05:42:48+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -1.778% |  | 0 | 2026-10-31T05:41:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-10-30T16:00Z .. 2026-10-31T05:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-30T16:00Z | kPEPE | LONG | 1 | 2.817 | 6.925 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-10-30T17:00Z | kPEPE | LONG | 1 | 3.095 | 2.748 | unknown (account read failed) | unknown (account read failed) | closed -1.0291R |
| 2026-10-30T18:00Z | kPEPE | LONG | 1 | 5.32 | 4.467 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-10-30T19:00Z | HYPE | LONG | 1 | 3.698 | 2.14 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-10-30T19:00Z | kPEPE | LONG | 2 | 3.237 | 3.101 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-10-30T19:00Z | ENA | SHORT | 1 | 3.082 | 3.134 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-10-30T20:00Z | kPEPE | LONG | 1 | 3.668 | 2.106 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-10-31T00:00Z | OP | LONG | 1 | 5.32 | 4.884 | unknown (account read failed) | unknown (account read failed) | closed -1.0164R |
| 2026-10-31T05:00Z | kPEPE | LONG | 1 | 4.071 | 2.6 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-10-31T05:00Z | WLD | SHORT | 1 | 4.54 | 2.248 | unknown (account read failed) | unknown (account read failed) | pending |

