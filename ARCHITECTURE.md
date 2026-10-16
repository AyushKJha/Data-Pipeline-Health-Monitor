# Data Pipeline Health Monitor

A single-owner application for data engineers to monitor local CSV/SQLite datasets using typed forms and persistent collections.

Node.js 24+, SQLite, server-side validation, idempotent CRUD requests, reviewed browser interface. Database is excluded from GitHub. Owner app data stays on the worker.

- Connect a local dataset via CSV or SQLite import
- Run freshness checks on tables
- Validate schema consistency
- Show incident reports with suggested fixes