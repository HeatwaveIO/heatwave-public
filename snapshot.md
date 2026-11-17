# Heatwave public snapshot 2026-11-17T18:23:31Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-17T18:23:04+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 16.258% |  | 0 | 2026-11-17T18:21:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-17T05:00Z .. 2026-11-17T18:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-17T05:00Z | INJ | LONG | 1 | 2.869 | 3.716 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-17T06:00Z | OP | SHORT | 1 | 3.609 | 3.314 | unknown (account read failed) | unknown (account read failed) | closed 0.0222R |
| 2026-11-17T07:00Z | OP | SHORT | 1 | 3.16 | 2.029 | unknown (account read failed) | unknown (account read failed) | closed -1.0413R |
| 2026-11-17T12:00Z | LINK | LONG | 1 | 3.188 | 1.822 | unknown (account read failed) | unknown (account read failed) | closed -1.0448R |
| 2026-11-17T12:00Z | SOL | LONG | 2 | 2.584 | 2.014 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-17T12:00Z | ETH | SHORT | 1 | 2.734 | 1.999 | unknown (account read failed) | unknown (account read failed) | open -0.578R so far |
| 2026-11-17T13:00Z | INJ | LONG | 1 | 7.49 | 2.589 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-17T16:00Z | DOGE | SHORT | 1 | 5.199 | 3.522 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-17T16:00Z | SOL | SHORT | 2 | 3.748 | 4.142 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-17T17:00Z | ADA | SHORT | 1 | 5.325 | 1.695 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-17T17:00Z | AAVE | SHORT | 2 | 3.369 | 3.456 | unknown (account read failed) | unknown (account read failed) |  |

