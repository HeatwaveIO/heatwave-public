# Heatwave public snapshot 2026-10-28T03:18:36Z

percent of each account's start and R; no dollar amounts, no account IDs

## Accounts

| Account | Mode | Equity vs start | Cushion to floor | Open | Last cycle | Error |
|---|---|---|---|---|---|---|
| propr_2s | live | -1.219% | 3.327 | 3 | 2026-10-28T03:17:24+00:00 |  |
| propr_h6 | live | -5.263% | 0.737 | 1 | 2026-10-28T03:18:41+00:00 |  |
| hyro_h6 | h6.16-hyro | None% |  | 0 | 2026-10-28T03:17:49+00:00 | HyroError: need exactly one active Hyro trial challenge |
| alp100 | {'alp100_mode': 'live', 'orbA_mode': 'live'} | -0.51% |  | None | 2026-10-26T13:30:44+00:00 |  |
| coinbase | SHADOW (real orders blocked) | -0.764% |  | 0 | 2026-10-28T03:16:30Z |  |

## Open Propr positions

| Account | Coin | Side | Entry | Mark | R | BE trigger | BE moved | Time exit | Stop order | TP order |
|---|---|---|---|---|---|---|---|---|---|---|
| propr_2s | ADA | LONG | 0.20717 | 0.206525 | -0.349 | 0.208558 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:2HbEtSGnMUKq @ 0.20532 | urn:prp-order:ULDuuB4GEaRw @ 0.21288 |
| propr_2s | XLM | LONG | 0.17248 | 0.171615 | -0.391 | 0.174138 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:dReuidEPNsRG @ 0.17027 | urn:prp-order:bmK2MJMrn9cV @ 0.17911 |
| propr_2s | BNB | LONG | 745.891189 | 745.845 | -0.011 | 748.982081 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:nw7HA1n5qZRZ @ 741.77 | urn:prp-order:KmWrAkw5acH1 @ 758.29 |
| propr_h6 | ATOM | LONG | 1.643778 | 1.64755 | 0.266 | 1.654411 (+0.75R) | False | 2026-10-28T11:55Z | urn:prp-order:R3jChtY5sc7a @ 1.6296 | urn:prp-order:Pzj8N8LSAbTv @ 1.6864 |

## Signal scan 2026-10-27T14:00Z .. 2026-10-28T03:00Z (decision times)

qualifying = RVOL >= 2.5, side OR width >= 1.5%, trend agrees; the executor takes Top-1 per side

| Decision | Coin | Side | Rank | RVOL | Width % | propr_2s | propr_h6 | Replay be075 |
|---|---|---|---|---|---|---|---|---|
| 2026-10-28T02:00Z | kPEPE | LONG | 1 | 12.713 | 7.261 | skipped_off_hours | skipped_off_hours | open -0.251R so far |
| 2026-10-28T03:00Z | kPEPE | LONG | 1 | 4.657 | 3.123 | skipped_off_hours | skipped_off_hours | replay unavailable |

