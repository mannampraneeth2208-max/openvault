# OpenVault

## Overview

OpenVault is a **college makerspace / resource-access operations prototype** — **not** a credentials or secrets manager. It demonstrates how a shared workspace can track equipment reservations, manage member access, and expose a simple dashboard for campus makerspace operators.

## What It Is

- A **resource-management prototype** for makerspaces and campus labs.
- Tracks equipment checkouts, reservation slots, and member access permissions.
- Provides a lightweight web interface for operators and users.

## Tech Stack

- **Backend:** FastAPI with SQLAlchemy for database operations and API endpoints
- **Frontend:** Static HTML + CSS + vanilla JavaScript demo interface
- **Database:** SQLite (local development); easy to swap for PostgreSQL

## Demo Data

The prototype ships with **synthetic demo users** (students, instructors, and staff roles) and sample equipment records so the app can be run locally without real credentials.

## Running Locally

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Set up the database: `python app.py init-db`
4. Run the server: `python app.py`
5. Open `http://localhost:8000` in a browser.

## Notes

- This repository contains **only the prototype code**.
- The **full audited source archive is not yet committed**. The working tree reflects the latest development iteration; a complete, reviewed archive will be added in a future push.
- No real user data or production secrets are included.

## License

MIT
