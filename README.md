# Locked BONK Snapshots

Welcome to the repository containing historical snapshots of wallets locked with BONK tokens. These wallets have engaged in locking their tokens for various durations on [bonkrewards.com](https://bonkrewards.com).

## Snapshot Frequency

Snapshots of locked wallets are taken on a weekly basis.

## File Format

The snapshots are saved in JSON format, following a standardized naming convention to facilitate easy identification and access:

```
locked_wallets_unique_<timestamp>_duration.json
```

### Components Explained:

- **timestamp**: Epoch time indicating the exact moment the snapshot was captured. To convert this timestamp into a human-readable date, please utilize [Epoch Converter](https://www.epochconverter.com/).

- **duration**: Reflects the lock period of the BONK tokens within the wallet. Possible durations include:
  - `1m` for a 1-month lock
  - `3m` for a 3-month lock
  - `6m` for a 6-month lock

## Utilizing the Data

The data contained within these snapshots can serve a multitude of purposes, from historical analysis of token locking trends to airdrops for lockers.