# Heatwave public verification snapshot

Read-only mirror of the Heatwave trading server's verification snapshot, refreshed every 5 minutes.

- `snapshot.json` - machine-readable
- `snapshot.md` - human-readable

Contents: account status as percent of each account's start and R multiples, open positions with Propr venue order IDs
(entry, stop_market, take_profit_limit), the last 14 hours of hourly signal scans (every qualifier, its rank, breakout,
and why it was taken or skipped), the alp100 paper sleeves and the Coinbase shadow.

No dollar amounts, no account IDs and no credentials: the generator refuses to publish if any appear.
Paper / practice accounts only. This is a report produced by our own server, not an independent venue statement.
