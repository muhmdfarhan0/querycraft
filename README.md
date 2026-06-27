# QueryCraft — AI SQL Generator

> Describe your query in plain English. Get production-ready SQL instantly.

**[🚀 Live Demo](https://muhmdfarhan0.github.io/querycraft)**

## What it does

QueryCraft turns plain English into SQL using Groq AI (llama-3.3-70b).
Paste your schema, describe what you want, get SQL with:

- Full explanation of every step
- Performance optimization tips
- Support for PostgreSQL, MySQL, SQLite, SQL Server, BigQuery
- In-browser sample data testing
- Query history saved locally

## Getting Started (2 minutes)

### 1. Get a free Groq API key

Go to [console.groq.com](https://console.groq.com) → Sign up free → Create API key → Copy it

### 2. Deploy to GitHub Pages

```bash
git clone https://github.com/muhmdfarhan0/querycraft
cd querycraft
# Already deployed at:
# https://muhmdfarhan0.github.io/querycraft
```

### 3. Use it

- Open your GitHub Pages URL
- Paste your Groq API key in the top bar (stored locally, never sent anywhere except Groq)
- Paste your database schema
- Describe your query in plain English
- Click Generate SQL

## Why Groq?

Groq runs on custom LPU hardware — responses come back in under 1 second. The free tier is very generous for personal use.

## Tech Stack

- Pure HTML + CSS + Vanilla JS (no frameworks)
- Groq API (llama-3.3-70b-versatile)
- highlight.js for SQL syntax highlighting
- localStorage for API key + query history

## License

MIT — fork it, ship it, make it yours.
