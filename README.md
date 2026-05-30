 Corimba.github.io
SpendWise — AI Personal Expense Tracker

> Track spending. Get AI-driven insights.

SpendWise is a fully client-side web application built with HTML, CSS, and JavaScript that helps individuals log, categorise, and understand their personal finances — supercharged with an AI engine powered by Claude.

---

 Getting Started

1. Download `SpendWise.html`
2. Open it in any modern browser (Chrome, Firefox, Edge)
3. Create a free account and start tracking

No server, no installation, no internet required for core features.

---
Features

Expense Tracking
- Add, edit, and delete expenses with categories
- Search, filter, and sort your full expense history
- Real-time dashboard with monthly/weekly stats and category breakdowns

 Afford-It Evaluator *(Star Feature)*
Enter any purchase price and the AI instantly analyses your finances to tell you whether you can afford it right now. If not, it generates a personalised action plan showing exactly what to cut and how long to save.

AI Savings Goal Planner
Set a savings goal (e.g. new laptop, holiday, emergency fund) and the AI builds a realistic month-by-month savings plan based on your actual spending habits.

 AI Financial Suite
| Feature | Description |
|---|---|
| Deep Spending Analysis | Patterns, anomalies, and cost-cutting opportunities |
| Financial Health Score | Animated score out of 100 with letter grade |
| Smart Budget Planner | Per-category monthly targets |
| Savings Tips Generator | 7 tips tied to your real data |
| Predictive Alerts | Forecast overspending before it happens |
| Monthly Summary | Your finances explained in plain language |
| AI Chat | Ask anything about your expenses |

 Agile Project Board
A full Scrum board for managing the project using Agile methodology — drag-and-drop Kanban, sprint burndown chart, story points, and an AI Sprint Review feature.

---

 AI Setup

AI features require a free Anthropic API key.

1. Go to [console.anthropic.com/keys](https://console.anthropic.com/keys)
2. Sign up and click **Create Key**
3. Open SpendWise → click ** API Key Settings** in the sidebar
4. Paste your key and click **Save & Connect AI**

Your key is stored only in your browser and is never shared with anyone except Anthropic's API directly.

---

Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Engine | Claude Sonnet (Anthropic API) |
| Storage | Browser localStorage |
| Fonts | Inter, JetBrains Mono (Google Fonts) |

---

 Project Structure

```
SpendWise.html        ← Entire application in one file
README.md             ← This file
```

The entire app ships as a single HTML file with no dependencies to install, no build step, and no backend.

---

 Development Process

Built using **Agile/Scrum methodology** in 2-week sprints:

- **Sprint 1** — Auth, core expense CRUD, dashboard
- **Sprint 2** — AI Suite, Financial Health Score, Spending Analysis
- **Sprint 3** — Afford-It Evaluator, Savings Goal Planner, Agile Board

---

 Multi-User Support

Each user has their own account with isolated data. All user accounts and expenses are stored separately in localStorage, keyed by user ID.

---

 Known Limitations

- Data is stored in the browser — clearing browser data will erase expenses
- AI features require an internet connection and a valid API key
- Not yet available as a mobile app (PWA planned for a future sprint)


