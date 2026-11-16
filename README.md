# My Money

A simple personal money tracker in one HTML file (HTML, CSS, JavaScript, no build step).

## Features
- Total money across all accounts
- Separate accounts for each bank / e-wallet, each with its own balance
- ASB account to track savings
- Record expenses, income and transfers (e.g. bank → ASB)
- Monthly summary: spent, income, saved to ASB
- Donut chart of spending by category, with month tabs
- Hide / show balances with the eye button
- Simple Apple-style light interface
- Works offline: changes are queued and sync when you're back online (Claude Artifact version)
- Home screen icon (when the page is hosted, e.g. GitHub Pages)

## How to run
Open `index.html` in a browser.

## Where data is saved
- **Opened from this file or GitHub Pages:** data is saved in that browser only (localStorage).
- **Opened as a Claude Artifact on claude.ai:** data is saved privately to your Claude account and syncs across devices.
