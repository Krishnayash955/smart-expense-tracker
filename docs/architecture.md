# Architecture

Modular monorepo with a React SPA frontend and a FastAPI backend talking to Neon PostgreSQL.

Backend layering: `api` (routes) -> `services` (business logic) -> `repositories` (database access) -> `models` (SQLAlchemy). `schemas` holds Pydantic request/response models.

_To be expanded as features are built._
