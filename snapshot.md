# Heatwave public snapshot 2026-11-14T01:48:33Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s |  | None% |  | None |  | snapshot read failed (rc 1) |
| propr_h6 |  | None% |  | None |  | snapshot read failed (rc 1) |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-11-14T01:47:56+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | 14.986% |  | 0 | 2026-11-14T01:46:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|

## Signal scan 2026-11-13T12:00Z .. 2026-11-14T01:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-11-13T12:00Z | ZEC | LONG | 1 | 2.656 | 1.953 | unknown (account read failed) | unknown (account read failed) | closed 0.009R |
| 2026-11-13T13:00Z | INJ | LONG | 1 | 2.72 | 2.899 | unknown (account read failed) | unknown (account read failed) | closed -0.4372R |
| 2026-11-13T14:00Z | INJ | LONG | 1 | 4.441 | 5.574 | unknown (account read failed) | unknown (account read failed) | closed -0.4694R |
| 2026-11-13T14:00Z | BTC | SHORT | 1 | 2.928 | 1.64 | unknown (account read failed) | unknown (account read failed) | closed 0.4028R |
| 2026-11-13T16:00Z | INJ | LONG | 1 | 3.935 | 2.928 | unknown (account read failed) | unknown (account read failed) | closed 0.0155R |
| 2026-11-13T18:00Z | XLM | LONG | 1 | 3.271 | 1.612 | unknown (account read failed) | unknown (account read failed) | closed -1.0836R |
| 2026-11-13T20:00Z | INJ | LONG | 1 | 3.982 | 3.583 | unknown (account read failed) | unknown (account read failed) | pending |
| 2026-11-13T22:00Z | SOL | SHORT | 1 | 6.111 | 1.867 | unknown (account read failed) | unknown (account read failed) | open 0.574R so far |
| 2026-11-13T23:00Z | INJ | LONG | 1 | 4.665 | 2.015 | unknown (account read failed) | unknown (account read failed) | open 0.048R so far |
| 2026-11-13T23:00Z | TIA | SHORT | 1 | 6.468 | 4.612 | unknown (account read failed) | unknown (account read failed) | open -0.031R so far |
| 2026-11-13T23:00Z | SOL | SHORT | 2 | 3.943 | 1.655 | unknown (account read failed) | unknown (account read failed) |  |

