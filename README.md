# Ledgerly — Personal Budget Manager

A standalone personal budget management app built with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, no backend — just a single file you open in any browser.

---

## What It Does

Ledgerly lets you create and manage multiple monthly budgets from a single file. It's designed for people who want a clean, private budgeting tool without signing up for anything or connecting a bank account.

### Core Features

**Multi-Budget Management**
Create as many named budgets as you need. Each budget is fully independent with its own accounts, bills, income, and schedule history.

**Multi-Step Budget Creation**
A guided setup flow walks you through four steps: naming your budget, adding accounts, setting up bills, and configuring income sources — so nothing gets missed.

**Account Tracking**
Add checking, savings, credit, loan, or custom accounts. Each account tracks its current balance, optional credit limit, and running transaction totals.

**Bill Templates & Monthly Scheduler**
Create reusable bill templates with a default amount, due date, and linked account. Override amounts and due dates month-by-month using the scheduler without changing your template defaults. Copy one month's schedule forward to the next with a single click.

**Income Templates & Scheduler**
Set up recurring income sources with default deposit amounts and pay dates (supports multiple deposit days per source). Schedule adjustments per month the same way bills work.

**Interactive Budget Dashboard**
Each budget opens to a full dashboard showing:
- Net worth across all accounts
- Monthly cash flow (income vs. bills)
- Projected end-of-month balance
- Account-by-account breakdown
- Color-coded bill and income calendar
- Scrollable month-by-month projected transaction table

**Alerts & Reminders System**
Automatic smart alerts surface conditions like upcoming bills, low balances, high credit utilization, and unassigned transactions. Alerts can be silenced individually or dismissed, and support browser-based notifications.

**Data Persistence**
All budget data is saved automatically to the browser's `localStorage`. Nothing leaves your device.

---

## How to Use It

1. Download `budget-app.html`
2. Open it in any modern browser
3. Click **New Budget** and follow the setup steps
4. Your data saves automatically as you work

No installation. No server. No account required.

---

## Tech Stack

- HTML5
- CSS3 (custom properties, CSS Grid, Flexbox, animations)
- Vanilla JavaScript (ES6+)
- Browser `localStorage` for persistence
- Google Fonts: DM Serif Display, Plus Jakarta Sans, JetBrains Mono

---

## Design Notes

The UI is built with a dark theme using a full custom design system — CSS variables handle all colors, spacing, typography, and motion. Components include stat cards, modals, toast notifications, a calendar grid, a projected transaction table, and a multi-step form with animated step indicators.

---

## Project Status

Active development. Planned additions include:
- CSV export for transaction history
- Budget duplication across months
- Spending category tracking
- Light mode toggle

---

## Author

**Stephen J. Bridgett**
[stephenjbridgett.com](https://stephenjbridgett.com) · [GitHub](https://github.com/SteveJayB)
