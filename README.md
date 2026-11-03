# Smart Expense Tracker

A full-stack personal finance app: track income and expenses, set budgets, view dashboards and reports, and manage savings goals.

## Tech stack

| Layer | Technology |
|---|---|
| Frontend | React, TypeScript, Vite, Tailwind CSS, Axios, React Router, Recharts, Lucide React |
| Backend | Python 3.12, FastAPI, SQLAlchemy, Pydantic, Alembic, JWT |
| Database | Neon serverless PostgreSQL |
| CI/CD | Git, GitHub, GitHub Actions |
| Hosting | Vercel (frontend), Render (backend), Neon (database) 

## Repository layout

```
frontend/   React + TypeScript app
backend/    FastAPI app, migrations, tests
docs/       Architecture, database design, API and development guides
.github/    CI workflows
```

## Local development

Frontend: http://localhost:5173
Backend: http://localhost:8000 (API docs at http://localhost:8000/docs)
Database: Neon PostgreSQL (cloud)

Setup instructions are in [docs/development-guide.md](docs/development-guide.md).

## Environment variables

See [.env.example](.env.example) for all variables. Copy the relevant section into `backend/.env` and `frontend/.env`. These files are git-ignored and must never be committed.

## Status

Phase 1 (foundation) in progress.
