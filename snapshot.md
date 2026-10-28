# Heatwave public snapshot 2026-10-28T02:18:30Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -0.817% | 3.729 | 2 | 2026-10-28T02:18:20+00:00 |  |
| propr_h6 | live | -5.33% | 0.67 | 1 | 2026-10-28T02:17:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T02:17:52+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -1.622% |  | 0 | 2026-10-28T02:16:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | ADA | LONG | 0.20721 | 0.20792 | 0.376 | 0.208627 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:2HbEtSGnMUKq @ 0.20532 | urn:prp-order:ULDuuB4GEaRw @ 0.21288 |
| propr_2s | XLM | LONG | 0.17248 | 0.172785 | 0.138 | 0.174138 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:dReuidEPNsRG @ 0.17027 | urn:prp-order:bmK2MJMrn9cV @ 0.17911 |
| propr_h6 | ATOM | LONG | 1.6438 | 1.6492 | 0.38 | 1.65445 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:q3ab8BiTfKL5 @ 1.6296 | urn:prp-order:JHiL8a5GT7EV @ 1.6864 |

## Signal scan 2026-10-27T13:00Z .. 2026-10-28T02:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | pending |

