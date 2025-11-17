# myTradingVitals

myTradingVitals is a browser-based trading journal and dashboard designed to track your **trades**, **performance metrics**, and **behavioral patterns** in one place — without logins, subscriptions, or a backend.

It runs as a single-page web app (HTML/CSS/JavaScript), so you can host it via GitHub Pages or just open `index.html` locally.

> ⚠️ **Disclaimer:** myTradingVitals is for **educational and tracking purposes only** and does **not** provide financial advice, recommendations, or guarantees of performance.

---

## Features

- **KPI Dashboard (“Vitals”)**
  - At-a-glance view of your core stats (e.g. win rate, average R, average P/L, number of trades, etc.).
  - Updates automatically as you add, edit, or import trades.

- **Trades Table**
  - Sortable, filterable list of all recorded trades.
  - Supports inline review via notes, tags, and other metadata.
  - Designed to help you spot patterns in execution and performance.

- **Filters Panel**
  - Filter trades by:
    - Date range
    - Ticker / symbol
    - Direction (long/short)
    - Tags / strategy labels
  - Lives above the trades table for quick access.

- **Quick Trade Panel**
  - Compact form for logging a new trade in seconds.
  - Collapsible via an accordion for a cleaner layout when not needed.

- **Import / Export**
  - **Import** trades from CSV to backfill your journal.
  - **Export** your current dataset to CSV for backup, spreadsheets, or additional analysis.
  - Import/Export panel is minimized into an accordion for reduced clutter.

- **Data-Formatting Rules Panel**
  - Accordion panel summarizing the expected CSV fields and formatting assumptions.
  - Acts as an in-app reference when preparing imports.

- **Theming & UI**
  - Light/Dark theme support.
  - Icons (calendar, etc.) styled to remain legible in dark mode.
  - Layout optimized as a single-page dashboard with collapsible sections to avoid overwhelm.

- **Local-First Storage**
  - Trades are stored in your browser (e.g. `localStorage`), so there’s no server-side database.
  - Your data stays on your device unless you choose to export it.

---

## Tech Stack

- **Frontend:** HTML5, CSS3, vanilla JavaScript
- **Hosting:** Any static host (e.g. GitHub Pages, Netlify, local file system)
- **Persistence:** Browser-based storage (no external database or authentication)
