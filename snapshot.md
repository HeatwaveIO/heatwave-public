# Heatwave public snapshot 2026-11-13T21:18:40Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-13T21:17:50+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 12.88% |  | 0 | 2026-11-13T21:16:31Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-13T08:00Z .. 2026-11-13T21:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-13T08:00Z | ZEC | SHORT | 1 | 4.355 | 2.201 | unknown (account read failed) | unknown (account read failed) | closed -1.0363R |
| 2026-11-13T11:00Z | ARB | SHORT | 1 | 3.884 | 1.68 | unknown (account read failed) | unknown (account read failed) | none |
| 2026-11-13T12:00Z | ZEC | LONG | 1 | 2.656 | 1.953 | unknown (account read failed) | unknown (account read failed) | closed 0.009R |
| 2026-11-13T13:00Z | INJ | LONG | 1 | 2.72 | 2.899 | unknown (account read failed) | unknown (account read failed) | open -0.24R so far |
| 2026-11-13T14:00Z | INJ | LONG | 1 | 4.441 | 5.574 | unknown (account read failed) | unknown (account read failed) | open -0.324R so far |
| 2026-11-13T14:00Z | BTC | SHORT | 1 | 2.928 | 1.64 | unknown (account read failed) | unknown (account read failed) | open 0.309R so far |
| 2026-11-13T16:00Z | INJ | LONG | 1 | 3.935 | 2.928 | unknown (account read failed) | unknown (account read failed) | closed 0.0155R |
| 2026-11-13T18:00Z | XLM | LONG | 1 | 3.271 | 1.612 | unknown (account read failed) | unknown (account read failed) | open -0.788R so far |
| 2026-11-13T20:00Z | INJ | LONG | 1 | 3.982 | 3.583 | unknown (account read failed) | unknown (account read failed) | pending |

