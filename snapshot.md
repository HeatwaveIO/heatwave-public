# Heatwave public snapshot 2026-11-11T06:03:31Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-11T06:03:07+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 4.74% |  | 0 | 2026-11-11T05:56:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-10T17:00Z .. 2026-11-11T06:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-10T17:00Z | kPEPE | LONG | 1 | 5.651 | 3.843 | unknown (account read failed) | unknown (account read failed) | closed 0.5492R |
| 2026-11-10T17:00Z | ZEC | SHORT | 1 | 5.118 | 10.693 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-10T17:00Z | ADA | SHORT | 2 | 4.596 | 1.739 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-10T17:00Z | DOT | SHORT | 3 | 4.478 | 2.366 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-10T17:00Z | OP | SHORT | 4 | 3.713 | 2.144 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-10T17:00Z | AVAX | SHORT | 5 | 3.673 | 1.588 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-10T17:00Z | APT | SHORT | 6 | 3.134 | 2.684 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-10T18:00Z | AAVE | SHORT | 1 | 3.35 | 1.951 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-10T18:00Z | ZEC | SHORT | 2 | 2.525 | 4.698 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-11T02:00Z | ARB | LONG | 1 | 2.51 | 2.965 | unknown (account read failed) | unknown (account read failed) | open -0.8R so far |
| 2026-11-11T03:00Z | ARB | LONG | 1 | 2.78 | 2.997 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-11T04:00Z | INJ | LONG | 1 | 4.872 | 1.836 | unknown (account read failed) | unknown (account read failed) | pending |

