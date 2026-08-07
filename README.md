# Masareef — Allowance Manager

Single-file (`index.html`) iPhone-style money manager for a 120 SAR monthly allowance.

- Open `index.html` in Safari on iPhone → Share → **Add to Home Screen**.
- Data syncs live to Firebase Realtime Database and is cached in `localStorage` for offline use.

Month types only affect **new** allowance money — existing balances always carry over.

| Month type | Hangout | Savings | PS/Mobily |
|---|---|---|---|
| 🍔 Hangout | 65 | 40 | 15 |
| 🏠 No Hangout | 20 | 85 | 15 |
| ❓ Not sure yet | 40 | 65 | 15 |
