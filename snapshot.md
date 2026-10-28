# Heatwave public snapshot 2026-10-28T02:23:35Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.069% | 3.477 | 3 | 2026-10-28T02:22:27+00:00 | signal / management step failed: HTTP Error 429: Too Many Requests (3 consecutive cycles) |
| propr_h6 | live | -5.33% | 0.67 | 1 | 2026-10-28T02:22:42+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T02:22:51+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -1.492% |  | 0 | 2026-10-28T02:21:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | ADA | LONG | 0.20717 | 0.20683 | -0.184 | 0.208558 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:2HbEtSGnMUKq @ 0.20532 | urn:prp-order:ULDuuB4GEaRw @ 0.21288 |
| propr_2s | XLM | LONG | 0.17248 | 0.172025 | -0.206 | 0.174138 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:dReuidEPNsRG @ 0.17027 | urn:prp-order:bmK2MJMrn9cV @ 0.17911 |
| propr_2s | BNB | LONG | 745.891189 | 745.18 | -0.173 | 748.982081 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:nw7HA1n5qZRZ @ 741.77 | urn:prp-order:KmWrAkw5acH1 @ 758.29 |
| propr_h6 | ATOM | LONG | 1.643778 | 1.6428 | -0.069 | 1.654411 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:R3jChtY5sc7a @ 1.6296 | urn:prp-order:Pzj8N8LSAbTv @ 1.6864 |

## Signal scan 2026-10-27T13:00Z .. 2026-10-28T02:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open 0.061R so far |

