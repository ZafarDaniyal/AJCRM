# Insurance CRM Tracker

A lightweight shared CRM for insurance sales teams.

## What it includes

- Shared login for 4 salespeople + owner
- Sales entry fields: customer name, phone number, address, date sold, exact premium amount
- Monthly sales log and leaderboard
- Owner-only hidden analytics sheet
  - total premium sold
  - total agent commissions
  - total agency commissions (what comes to the business)
- Owner CSV upload and monthly CSV export
- Competition mode toggle
  - ON: everyone can see all sales and leaderboard
  - OFF: each salesperson sees only their own data

## Default users

- Owner: `owner / owner123!`
- Salespeople: `sales1`, `sales2`, `sales3`, `sales4` with passcode `agent123!`

## Run locally

```bash
cd "/Users/daniyalzafar/Documents/New project"
python3 app.py
```

Open [http://localhost:8080](http://localhost:8080).

## Data storage

SQLite database file:

- `/Users/daniyalzafar/Documents/New project/data/crm.db`

## Notes

- Change default passcodes before production use.
- This is designed for internal team usage and can be deployed behind your own hosting/login controls.
