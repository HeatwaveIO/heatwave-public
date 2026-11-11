# Heatwave public snapshot 2026-11-11T20:48:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-11T20:47:51+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 5.136% |  | 0 | 2026-11-11T20:46:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-11T07:00Z .. 2026-11-11T20:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-11T07:00Z | ZEC | SHORT | 1 | 3.288 | 4.237 | unknown (account read failed) | unknown (account read failed) | closed -1.0267R |
| 2026-11-11T08:00Z | AVAX | LONG | 1 | 3.287 | 1.856 | unknown (account read failed) | unknown (account read failed) | closed -0.0167R |
| 2026-11-11T08:00Z | kPEPE | LONG | 2 | 2.706 | 1.958 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-11T08:00Z | DOT | SHORT | 1 | 4.571 | 1.534 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-11T08:00Z | ZEC | SHORT | 2 | 2.657 | 3.936 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-11T09:00Z | ZEC | SHORT | 1 | 2.764 | 3.498 | unknown (account read failed) | unknown (account read failed) | closed -1.0254R |
| 2026-11-11T10:00Z | kPEPE | LONG | 1 | 3.579 | 2.009 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-11T20:00Z | kPEPE | LONG | 1 | 5.952 | 2.51 | unknown (account read failed) | unknown (account read failed) | pending |

