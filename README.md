# Get It Done

This Flask application expects certain configuration values to be supplied via environment variables before it is run.

## Required environment variables

- `DATABASE_URL` – SQLAlchemy connection string for the application's database, e.g. `mysql+pymysql://user:password@localhost:8889/get-it-done`
- `SECRET_KEY` – Secret key used by Flask to sign session cookies.

Set these in your environment or in a `.env` file before starting the application.
