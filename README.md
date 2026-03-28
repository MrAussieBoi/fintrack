# 💸 FinTrack — Personal Finance Tracker

A simple, clean, single-file web app to track your income and expenses. Built with plain HTML, CSS, and JavaScript — no frameworks, no backend, no fuss.

> Built for a Coles Night Fill worker tracking their pay and spending.

---

## ✨ Features

- ➕ Log **income** (Coles wages) and **expenses** (food, entertainment, subscriptions)
- 💾 **Auto-saves** to your browser's local storage — data persists across sessions
- 📊 **Donut chart** showing your spending by category
- 📈 **Bar chart** showing monthly income vs expenses (last 6 months)
- 💰 **Savings rate** progress bar
- 🗓️ **Filter by month** to review any period
- ⬇️ **Export to CSV** for spreadsheets or tax time
- 📱 Fully **responsive** — works on mobile too

---

## 🚀 Getting Started

No install required. Just open the file in your browser:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/fintrack.git
cd fintrack

# Open in browser (macOS)
open index.html

# Open in browser (Windows)
start index.html
```

Or just double-click `index.html` in your file explorer.

---

## 📁 File Structure

```
fintrack/
└── index.html   # Everything — HTML, CSS, JS in one file
└── README.md
```

---

## 💡 Usage Tips

- **Logging a Coles shift?** Select `🟡 Coles Wage` as category and enter your hours in the optional hours field.
- **Under-18 casual rates (approx.):** Weekday ~$13.33/hr · Saturday ~$16.66/hr · Sunday ~$20.00/hr
- Use the **month filter** dropdown to see a specific pay period.
- Hit **Export CSV** before clearing data if you want a backup.

---

## 🛠️ Tech Stack

- Plain HTML5, CSS3, Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) for charts (loaded via CDN)
- [Google Fonts](https://fonts.google.com/) — Syne + DM Mono
- `localStorage` for persistent data storage

---

## 📜 License

MIT — do whatever you want with it.
