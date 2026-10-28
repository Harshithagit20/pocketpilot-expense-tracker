# PocketPilot — Smart Expense Tracker

PocketPilot is a responsive personal-finance dashboard built with HTML, CSS, and vanilla JavaScript. It helps users record income and expenses, understand spending by category, monitor a monthly budget, search transactions, and export their data.

## Features
- Dashboard cards for balance, monthly income, expenses, and savings rate
- Spending breakdown with a dynamic donut chart
- Monthly budget progress and editable budget limit
- Add and delete income/expense transactions
- Search and filter transaction history
- Export transactions to CSV
- Persists data in browser `localStorage`
- Responsive layout for desktop, tablet, and mobile
- Accessible form labels, modal dialog semantics, and status messages

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser. No dependencies, package installation, or database setup are required.

For the best development workflow, open the folder in VS Code and use the Live Server extension.

## Deploy with GitHub Pages
1. Create a public GitHub repository named `pocketpilot-expense-tracker`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for GitHub Pages to publish the site. The live URL will be shown in the Pages settings.

## Tech stack
- HTML5
- CSS3 (responsive layout, custom chart styling, transitions)
- JavaScript (DOM manipulation, form validation, filtering, CSV generation)
- Browser localStorage API

## Data note
This is a front-end demo. Data is stored in the current browser on the current device and is not synced to a server. The dashboard includes sample transactions so the UI is immediately usable. Clear the site's local storage to restore the initial sample data.

## Future improvements
- Authentication and cloud database sync
- Recurring transactions
- Category-level budget limits
- Monthly trend comparisons
- Unit tests for transaction calculations

## Resume bullet
**PocketPilot — Smart Expense Tracker:** Built a responsive personal-finance dashboard using HTML, CSS, and JavaScript with transaction CRUD, category-based spending visualization, monthly budget tracking, localStorage persistence, search/filter controls, and CSV export; deployed as a static site using GitHub Pages.
