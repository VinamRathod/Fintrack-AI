# FinTrack AI

**Your Personal Finance Command Center**

FinTrack AI is a comprehensive personal finance management application designed to help users monitor income, control expenditure, manage budgets, track investments, and achieve savings objectives. The platform integrates AI-driven insights and a proprietary financial health scoring system to support informed financial decision-making.

**Live Application:** https://lively-madeleine-25a6e3.netlify.app/

---

## Key Features

- **Income and Expense Management** — Record multiple income sources and categorize expenditures across predefined categories, including Food, Rent, Travel, Health, Shopping, Entertainment, Education, and Utilities
- **Multi-Currency Support** — Compatible with INR, USD, EUR, GBP, JPY, and AED
- **Analytical Dashboard**
  - Bar chart representation of expenses by category
  - Donut chart illustrating expense distribution
  - Line chart comparing income and expenses over a six-month period
- **Financial Health Score** — A proprietary 0–100 rating calculated from savings rate, expense ratio, and investment allocation
- **Monthly Budget Management** — Establish and monitor monthly spending limits
- **Investment Portfolio Tracking** — Monitor asset allocation across Gold, Stocks, and Cryptocurrency, complete with AI-generated allocation advice and visual breakdowns
- **Savings Goal Tracking** — Define financial goals and monitor progress through a dedicated visual tracker, including a completion celebration effect
- **AI-Generated Insights** — Receive personalized financial recommendations derived from spending patterns, savings rate, and income data
- **Dark and Light Mode** — Fully themeable interface with persisted user preference
- **Data Privacy** — All information is stored locally within the user's browser via `localStorage`; no external server or database is utilized

---

## Technology Stack

| Layer | Technology |
|---|---|
| Markup and Styling | HTML5, CSS3 (Custom Properties / Theming) |
| Logic | Vanilla JavaScript (ES6+) |
| Data Visualization | Chart.js 4.4.1 (via CDN) |
| Typography | Google Fonts — Syne, DM Sans |
| Data Persistence | Browser localStorage |
| Deployment | Netlify |

This is a single-file, static web application with no backend server, database, or build pipeline required.

---

## Getting Started

### Prerequisites
- A modern web browser (no Node.js or build tools required)

### Installation

```bash
git clone https://github.com/VinamRathod/fintrack-ai.git
cd fintrack-ai
```

Open `Final.html` directly in your preferred web browser to run the application locally. No additional setup, dependencies, or environment configuration is required.

---

## Usage Guide

1. Add income sources within the Income section
2. Record expenditures by category within the Expenses section
3. Review spending trends within the Analytics dashboard
4. Evaluate overall financial standing via the Financial Health Score
5. Establish a Monthly Budget Limit to maintain spending discipline
6. Monitor Investment Portfolio allocation and receive AI-generated advice
7. Create and track progress toward Savings Goals

---


## Future Enhancements

- Cloud synchronization and user account support
- Report exportation (PDF/CSV)
- Recurring transaction support
- Bill payment reminders

---

## Contribution Guidelines

Contributions, issue reports, and feature requests are welcome. Please refer to the issues page for further details: https://github.com/VinamRathod/fintrack-ai/issues

---

## Author

**Vinam Rathod**
GitHub: https://github.com/VinamRathod
