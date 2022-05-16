This app is creates a data pipeline of the Spotify songs you've
recently listened to (the last 24h). It extracts the data from
Spotify API using a token, validates the data (checks for
duplicates, null values, etc.) and saves it to SQLite database.
An airflow DAG is included to schedule the job.

Stack used:
- Apache airflow (scheduling)
- Pandas (validation)
- SQLite (database)
- SQLAlchemy (ORM)