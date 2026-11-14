# Heatwave public snapshot 2026-11-14T18:33:37Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-14T18:33:14+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 15.92% |  | 0 | 2026-11-14T18:31:34Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-14T05:00Z .. 2026-11-14T18:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-14T05:00Z | INJ | LONG | 1 | 2.794 | 2.159 | unknown (account read failed) | unknown (account read failed) | closed 0.0122R |
| 2026-11-14T05:00Z | HYPE | SHORT | 1 | 4.149 | 2.862 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-14T06:00Z | INJ | LONG | 1 | 3.378 | 2.3 | unknown (account read failed) | unknown (account read failed) | closed -1.0445R |
| 2026-11-14T06:00Z | HYPE | SHORT | 1 | 2.662 | 1.604 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-14T07:00Z | INJ | LONG | 1 | 2.587 | 2.866 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-14T07:00Z | OP | SHORT | 1 | 3.287 | 1.815 | unknown (account read failed) | unknown (account read failed) | closed 2.9662R |
| 2026-11-14T07:00Z | TIA | SHORT | 2 | 2.759 | 1.871 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T08:00Z | TIA | SHORT | 1 | 3.316 | 2.35 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-14T08:00Z | ENA | SHORT | 2 | 2.922 | 2.459 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T08:00Z | WLD | SHORT | 3 | 2.768 | 2.144 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T13:00Z | INJ | LONG | 1 | 2.797 | 2.165 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-14T15:00Z | APT | SHORT | 1 | 12.513 | 4.482 | unknown (account read failed) | unknown (account read failed) | open 0.087R so far |
| 2026-11-14T15:00Z | LINK | SHORT | 2 | 9.048 | 3.197 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | OP | SHORT | 3 | 8.505 | 3.886 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | LTC | SHORT | 4 | 6.141 | 2.88 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | AVAX | SHORT | 5 | 4.824 | 4.12 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | XLM | SHORT | 6 | 3.823 | 1.881 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | ETH | SHORT | 7 | 3.812 | 2.762 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | DOGE | SHORT | 8 | 3.673 | 2.727 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | SOL | SHORT | 9 | 3.265 | 2.471 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | DOT | SHORT | 10 | 3.078 | 2.748 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | WLD | SHORT | 11 | 2.88 | 3.116 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | SUI | SHORT | 12 | 2.763 | 2.873 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | BNB | SHORT | 13 | 2.584 | 1.709 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T15:00Z | INJ | SHORT | 14 | 2.545 | 3.548 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T16:00Z | LTC | SHORT | 1 | 3.662 | 1.65 | unknown (account read failed) | unknown (account read failed) | open -0.161R so far |
| 2026-11-14T16:00Z | kPEPE | SHORT | 2 | 3.575 | 3.278 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | AVAX | SHORT | 1 | 6.457 | 3.166 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-14T17:00Z | APT | SHORT | 2 | 6.085 | 4.284 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | SOL | SHORT | 3 | 5.98 | 2.864 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | kPEPE | SHORT | 4 | 5.834 | 5.327 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | INJ | SHORT | 5 | 5.228 | 8.835 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | ARB | SHORT | 6 | 4.793 | 4.103 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | XLM | SHORT | 7 | 4.52 | 2.563 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | LTC | SHORT | 8 | 3.808 | 1.845 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | DOT | SHORT | 9 | 3.759 | 2.943 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | ETH | SHORT | 10 | 3.65 | 1.729 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | WLD | SHORT | 11 | 3.627 | 4.511 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | DOGE | SHORT | 12 | 3.348 | 2.585 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | HYPE | SHORT | 13 | 3.182 | 3.634 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | OP | SHORT | 14 | 2.976 | 3.58 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | LINK | SHORT | 15 | 2.941 | 2.76 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | XRP | SHORT | 16 | 2.934 | 2.367 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | ENA | SHORT | 17 | 2.816 | 4.012 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | BNB | SHORT | 18 | 2.799 | 2.701 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | ADA | SHORT | 19 | 2.768 | 2.441 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T17:00Z | SUI | SHORT | 20 | 2.534 | 3.079 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | XLM | SHORT | 1 | 41.513 | 2.994 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-14T18:00Z | DOT | SHORT | 2 | 8.073 | 2.158 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | INJ | SHORT | 3 | 7.077 | 5.321 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | XRP | SHORT | 4 | 6.717 | 2.618 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | ADA | SHORT | 5 | 5.904 | 2.432 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | ENA | SHORT | 6 | 4.419 | 3.678 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | SOL | SHORT | 7 | 3.947 | 2.279 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | ETH | SHORT | 8 | 3.906 | 2.472 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | BTC | SHORT | 9 | 3.726 | 1.823 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | AVAX | SHORT | 10 | 3.476 | 2.044 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | LTC | SHORT | 11 | 3.287 | 2.289 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | DOGE | SHORT | 12 | 2.885 | 2.414 | unknown (account read failed) | unknown (account read failed) |  |
| 2026-11-14T18:00Z | HYPE | SHORT | 13 | 2.788 | 3.745 | unknown (account read failed) | unknown (account read failed) |  |

