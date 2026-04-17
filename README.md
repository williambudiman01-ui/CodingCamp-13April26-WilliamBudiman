# Expense & Budget Visualizer

A mobile-friendly web app to track daily spending, built with HTML, CSS, and Vanilla JavaScript.

## Features

### Required (MVP)
- **Input Form** — Add transactions with Item Name, Amount, and Category (Food, Transport, Fun). Validates all fields before submitting.
- **Transaction List** — Scrollable list showing name, amount, and category. Each item can be deleted.
- **Total Balance** — Displayed at the top, updates automatically on add/delete.
- **Visual Chart** — Pie chart (Chart.js) showing spending distribution by category, updates automatically.

### Optional Challenges (3 of 5)
- ✅ **Sort Transactions** — Sort by newest, oldest, amount (high/low), or category.
- ✅ **Dark/Light Mode Toggle** — Switch themes with a button in the header; preference is saved.
- ✅ **Highlight Spending Over Limit** — Set a spending limit; a warning appears when exceeded and items over the limit are highlighted.

### Bonus
- **Custom Categories** — Add your own categories beyond Food, Transport, Fun.
- **Monthly Summary** — View spending grouped by month and category (📅 button).

## Tech Stack
- HTML5
- CSS3 (CSS Variables for theming)
- Vanilla JavaScript (ES6+)
- [Chart.js](https://www.chartjs.org/) via CDN

## Data Storage
All data is stored in the browser's **localStorage** — no backend required.

## Folder Structure
```
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
└── README.md
```

## How to Run
Open `index.html` directly in any modern browser (Chrome, Firefox, Edge, Safari).
No build step or server needed.

## Deployment
Published via GitHub Pages.
