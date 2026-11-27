# Heatwave public snapshot 2026-11-27T14:28:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-27T14:27:56+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 13.172% |  | 0 | 2026-11-27T14:26:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-27T01:00Z .. 2026-11-27T14:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-27T03:00Z | ENA | LONG | 1 | 5.605 | 2.771 | unknown (account read failed) | unknown (account read failed) | closed 0.9516R |
| 2026-11-27T03:00Z | LINK | LONG | 2 | 4.395 | 2.455 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-27T03:00Z | WLD | LONG | 3 | 3.793 | 2.494 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-27T03:00Z | ADA | LONG | 4 | 3.565 | 1.899 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-27T03:00Z | ZEC | LONG | 5 | 2.865 | 5.787 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-27T03:00Z | HYPE | LONG | 6 | 2.796 | 3.651 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-27T05:00Z | LINK | LONG | 1 | 3.947 | 1.504 | unknown (account read failed) | unknown (account read failed) | closed -1.0863R |
| 2026-11-27T08:00Z | INJ | LONG | 1 | 2.679 | 2.207 | unknown (account read failed) | unknown (account read failed) | open -0.062R so far |

