# Heatwave public snapshot 2026-11-22T02:23:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-22T02:23:00+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 21.166% |  | 0 | 2026-11-22T02:21:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-21T13:00Z .. 2026-11-22T02:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-21T13:00Z | SUI | LONG | 1 | 3.332 | 2.11 | unknown (account read failed) | unknown (account read failed) | closed 0.2693R |
| 2026-11-21T13:00Z | ARB | SHORT | 1 | 7.681 | 2.12 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-21T13:00Z | ENA | SHORT | 2 | 3.685 | 1.838 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-21T13:00Z | LTC | SHORT | 3 | 2.515 | 1.751 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-21T14:00Z | BTC | LONG | 1 | 3.84 | 3.546 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-21T14:00Z | ETH | LONG | 2 | 2.87 | 3.125 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-21T14:00Z | ADA | LONG | 3 | 2.709 | 2.806 | unknown (account read failed) | unknown (account read failed) |  |

