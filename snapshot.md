# Heatwave public snapshot 2026-11-01T13:48:31Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-01T13:47:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -1.362% |  | 0 | 2026-11-01T13:46:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-01T00:00Z .. 2026-11-01T13:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-01T05:00Z | TIA | LONG | 1 | 4.116 | 1.911 | unknown (account read failed) | unknown (account read failed) | open -0.712R so far |
| 2026-11-01T05:00Z | AVAX | LONG | 2 | 2.908 | 2.06 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-01T06:00Z | AVAX | LONG | 1 | 8.904 | 1.816 | unknown (account read failed) | unknown (account read failed) | closed -1.0536R |

