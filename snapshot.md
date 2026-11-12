# Heatwave public snapshot 2026-11-12T08:08:31Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-12T08:08:07+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 7.104% |  | 0 | 2026-11-12T07:56:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-11T19:00Z .. 2026-11-12T08:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-11T20:00Z | kPEPE | LONG | 1 | 5.952 | 2.51 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-11T23:00Z | XLM | SHORT | 1 | 6.751 | 2.363 | unknown (account read failed) | unknown (account read failed) | open 0.098R so far |
| 2026-11-11T23:00Z | DOGE | SHORT | 2 | 2.783 | 2.315 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-11T23:00Z | ADA | SHORT | 3 | 2.519 | 2.463 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-12T00:00Z | AVAX | SHORT | 1 | 4.292 | 1.848 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-12T00:00Z | INJ | SHORT | 2 | 3.851 | 4.335 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-12T00:00Z | DOGE | SHORT | 3 | 2.661 | 2.112 | unknown (account read failed) | unknown (account read failed) |  |

