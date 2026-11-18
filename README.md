# Offline Ledger Lab

A dependency-free local-first browser simulation. Create synthetic entries, simulate offline mode, queue writes, retry them, and inspect the state machine.

## Run locally

Open `index.html` or serve the folder with `python3 -m http.server 4173`. No npm, server, account, or network connection is required.

## Study path

Read the state object, the IndexedDB open path, and the queue/retry functions. Compare online and offline transitions, then inspect the memory fallback.

## Inclusive behavior

All actions are buttons, the timeline is a readable ordered list, status changes use a polite live region, and the lab does not require animation or pointer gestures.

## Privacy and durability

Only synthetic entries are created. Data remains in this browser when IndexedDB is available. Browser storage is best-effort and is not a backup.

## License

MIT. See `LICENSE`.
