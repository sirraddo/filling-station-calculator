# Filling Station Calculator

An installable, offline-capable app built for filling station operations — combines a full calculator, cash counting, pump sales tracking, product offload calculations, and POS reconciliation in one tool.

## Features
- **Calculator** — standard + scientific mode (sin/cos/tan/log/ln/√/x²/1/x/π), running tape with Sum All, Undo, keyboard support on laptop
- **Count Cash** — Naira denomination counter (₦1000 down to ₦5)
- **Pump Sales** — closing/opening meter readings → litres sold → price → total amount
- **Offload Calc** — Rotor Gauge method `(Side A + Side B) ÷ 2 × 200 × Density` and Meter method `Meter Reading ÷ 1.75`, with optional product/truck/driver fields
- **POS Calc** — up to 3 sales amounts minus POS payment = remaining cash
- **Breakdown** — enter any amount, get the fewest notes/coins needed
- **Change Due** — price vs amount given → change + breakdown
- **Reconciliation** — daily opening/cash-in/cash-out vs actual count, shows over/short
- **History** — every save is named and searchable, with full detail preserved (not just totals)
- **Note Guide** — official security-feature checks for identifying genuine Naira notes
- **Settings** — PIN lock (SHA-256, on-device only), text size, high contrast, CSV export, manual cross-device backup

## Security & data notes
- PIN lock gates the app screen; it does not encrypt the underlying data file.
- All data lives only in this browser's local storage — clearing browsing data wipes it. Export a backup regularly from Settings.
- No auto-sync between devices — use Export/Import Backup in Settings to move data manually.

## Files
- `index.html` — the whole app
- `manifest.json`, `sw.js` — PWA install + offline support
- `icon.svg`, `icon-192.png`, `icon-512.png` — app icons

## Deploy
Create a GitHub repo, upload these 7 files, enable GitHub Pages (Settings → Pages → Deploy from branch → main → root).
