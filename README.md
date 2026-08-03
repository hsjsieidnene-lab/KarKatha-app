KarKatha · GST Annual Reconciliation Dashboard
KarKatha is a browser-based workspace for reconciling a business's annual GST data — output tax, Input Tax Credit (ITC), and cash ledger — in one place. It is built as a single self-contained HTML app (no backend server required) with optional cloud sync for teams.
🔗 Live app: hosted via GitHub Pages on this repository
👤 Built by: Saurabh Kumar Pandey
✨ Features
Import data — drag & drop or paste CSV exports directly from the GST portal:
Electronic Cash Ledger
Electronic Credit Ledger
Electronic Liability Register
Tax Liability report
ITC report
RCM Liability/ITC report
Reverse Charge report
The app automatically identifies which report each file is, so you can drop multiple files at once.
Annual snapshot & overview — a single dashboard view of the full year's GST position.
Monthly breakdown — month-wise view of output tax, ITC, and cash ledger movement.
Cash credit table — track cash ledger balances and credits.
Interest, Late Fee & Penalty tracking — records amounts paid separately from regular tax.
Reconciliation
Cash ledger reconciliation
Output tax reconciliation
RCM Summary — Reverse Charge Mechanism liability and ITC in one section.
Annual summary — consolidated year-end figures.
Dark mode toggle.
Cloud sync (team workspace) — sign in to save and share data across devices/team members (via Firebase Authentication + Firestore).
Quick link to GST Portal login for convenience.
PWA-ready — includes a web app manifest and icons so it can be installed on mobile/desktop like a native app.
🛠️ Tech Stack
Plain HTML, CSS, and JavaScript — no build step required
Firebase (Auth + Firestore) for optional cloud sync
SheetJS (xlsx) for spreadsheet/CSV parsing
Deployed via GitHub Pages (Jekyll build workflow)
🚀 Getting Started
Open the live app (via GitHub Pages) or open index.html locally in a browser.
Sign in (if cloud sync/team login is enabled), or continue without login for local use.
Go to Import data and drag & drop your GST portal CSV exports, or use Paste CSV content if file upload isn't working.
Review your Annual Snapshot, Monthly breakdown, and Reconciliation sections.
Check the Annual summary for final consolidated figures.
📄 License
Licensed under BSL-1.0 (Boost Software License 1.0). See LICENSE for details.
🤝 Contributing
This repository started as a public template. Contributions, issues, and feature requests are welcome.
