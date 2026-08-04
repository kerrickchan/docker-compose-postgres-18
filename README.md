# Postgres

Docker Compose setup for PostgreSQL 18.

## Usage

```sh
docker compose up -d
```

## Environment Variables

| Variable              | Default      |
| --------------------- | ------------ |
| `POSTGRES_USER`     | `postgres` |
| `POSTGRES_PASSWORD` | `postgres` |
| `POSTGRES_DB`       | `postgres` |

Override by setting the variables in your shell or in a `.env` file.

## Connecting

```
postgresql://postgres:postgres@localhost:5432/postgres
```

## Data

Data is persisted in the `postgres_data` Docker volume.
