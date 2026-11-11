# Heatwave public snapshot 2026-11-11T22:23:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-11T22:23:13+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 5.49% |  | 0 | 2026-11-11T22:21:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-11T09:00Z .. 2026-11-11T22:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-11T09:00Z | ZEC | SHORT | 1 | 2.764 | 3.498 | unknown (account read failed) | unknown (account read failed) | closed -1.0254R |
| 2026-11-11T10:00Z | kPEPE | LONG | 1 | 3.579 | 2.009 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-11T20:00Z | kPEPE | LONG | 1 | 5.952 | 2.51 | unknown (account read failed) | unknown (account read failed) | pending |

