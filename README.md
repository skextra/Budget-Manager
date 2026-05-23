# Budget Calculator

A feature-rich, interactive budget calculator built with vanilla HTML, CSS, and JavaScript. Track your income, manage expenses, set savings goals, and visualize your spending — all in one clean dashboard.

---

## Live Features

- **Income tracker** — Add multiple income sources with labels and monthly amounts
- **Expense tracker** — Log all your monthly expenses across categories like housing, food, transport, and utilities
- **Savings goals** — Set financial targets, track your current savings, and see how many months until you reach each goal
- **Spending breakdown** — An interactive donut chart that visualizes your expenses by category
- **Smart tips** — Personalized financial advice based on your income, expenses, and savings rate
- **4 summary metrics** — Total income, total expenses, net balance, and savings rate always visible at a glance
- **Step-by-step flow** — A 4-step wizard with a progress bar guides you through entering your data

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and layout |
| CSS3 | Styling, responsive grid, dark mode support |
| Vanilla JavaScript | All logic — no frameworks |
| Chart.js | Donut chart for spending breakdown |

No build tools. No npm. No frameworks. Just open the file and it works.

---

## Project Structure

```
budget-calculator/
│
├── index.html        # Main HTML file (structure)
├── style.css         # All styles and layout
├── script.js         # JavaScript logic
└── README.md         # This file
```

---

## How It Works

The app is divided into 4 steps:

**Step 1 — Income**
Enter all your monthly income sources. You can add or remove rows dynamically.

**Step 2 — Expenses**
Log every expense with a label and monthly amount. Categories are used to color-code the breakdown chart.

**Step 3 — Savings goals**
Add goals like "Emergency fund" or "Vacation". Enter your target amount and how much you have saved so far. The app calculates how many months it will take to reach each goal based on your current surplus.

**Step 4 — Results**
See your full financial summary: a donut chart of spending, all 4 key metrics, a savings goal progress tracker, and a personalized tip.

---

## Key JavaScript Concepts Used

This project is great for beginners because it covers the core building blocks of JavaScript:

- `document.getElementById()` — selecting elements on the page
- `.textContent` — updating text displayed on the page
- `.style.display` — showing and hiding elements
- `addEventListener` / `onclick` — responding to button clicks
- Arrays and `.push()` / `.splice()` — storing and managing lists of data
- `.reduce()` — adding up totals from arrays
- `if / else` — making decisions based on values
- Template literals `` `Hello ${name}` `` — building dynamic HTML strings
- `Number()` — converting input values to numbers

---

## What I Learned Building This

- How to break a UI into reusable components
- How to manage state (data) in plain JavaScript without a framework
- How to dynamically render lists from arrays
- How to integrate a third-party chart library (Chart.js)
- How to design a multi-step user flow with a progress indicator

---

## Future Improvements

- [ ] Export budget as PDF or CSV
- [ ] Monthly vs annual toggle
- [ ] Currency switcher
- [ ] Local storage to save data between sessions
- [ ] 50/30/20 rule checker
- [ ] Dark mode toggle

---

## Author

Built by **[Your Name]** as a self-assigned JavaScript learning project.

Feel free to fork, improve, and make it your own!

---

## License

MIT License — free to use and modify.