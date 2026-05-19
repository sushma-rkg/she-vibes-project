# Personal Finance Tracker

A personal finance tracking system built to reduce the friction of managing day-to-day money decisions. The project captures expenses, stores structured financial data, and generates useful reports and summaries through automated workflows.

## What It Does

* Tracks daily expenses and transactions
* Stores financial data in Supabase
* Uses automated workflows built in n8n
* Captures contextual notes alongside expenses
* Organizes and structures financial records for reporting
* Reduces manual spreadsheet work

## Who It's For

This project is designed for:

* Individuals who want a lightweight personal finance system
* People who prefer automation over manual tracking
* Users building personal operating systems with tools like n8n and Supabase
* Anyone interested in agentic workflows for personal productivity

## Tech Stack

* n8n — workflow automation
* Supabase — backend database and storage
* Telegram — input interface for expense capture
* Python — scripting and processing utilities
* Git + GitHub — version control

## How to Run Locally

### 1. Clone the repository

```bash id="xk7j1r"
git clone https://github.com/sushma-rkg/she-vibes-project.git
```

### 2. Move into the project folder

```bash id="22ml5j"
cd she-vibes-project
```

### 3. Configure environment variables

Create a `.env` file and add:

* Supabase credentials
* Telegram bot token
* Any API keys required for workflows

### 4. Start n8n

```bash id="g7m0j4"
n8n start
```

### 5. Import workflows

Import the workflow JSON files into n8n and connect them to your local environment.

## What's Coming Next

* Automated weekly and monthly financial reports
* Better categorization of expenses
* Natural language expense logging
* AI-generated financial summaries
* Budget tracking and alerts
* Feedback loops and behavioural insights

## Status

Currently under active development. Early workflows and backend integrations are functional.
