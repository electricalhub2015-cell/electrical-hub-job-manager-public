# ELECTRICAL HUB INC. Job Manager

A mobile-friendly job manager designed for phone use.

## Features
- Two job tabs: Accepted Jobs and Completed Jobs.
- Add, edit, search, complete, reopen, and delete jobs.
- Job site address, customer, phone, job date, description, notes, payment status, and ESA status.
- Shows invoice total including tax, total cost including tax, and total profit.
- Profit is calculated as **invoice total minus total cost**. No separate HST line or HST deduction is shown.
- Records are stored locally in the browser on the device.
- Export and import JSON backups.
- Progressive Web App files for supported browser installation and offline app shell.

## Important storage note
Local browser storage belongs to that browser on that device. It is not automatically synced to another phone or browser. Export backups regularly. Clearing browser/site data may erase locally stored jobs.

## Run
Serve this folder over HTTPS or localhost. Open `index.html` in a modern browser. For installation, use the browser's **Add to Home screen** option when available.

No build step is required.
