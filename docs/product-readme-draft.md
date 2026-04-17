# AsyncKeel (Product README Draft)

AsyncKeel is a backend-first SaaS boilerplate built with FastAPI to help indie developers ship API products faster. It provides a production-oriented foundation for authentication, data access, API standards, and operational basics so you can focus on product logic instead of rebuilding backend infrastructure from scratch.

## Features

- JWT authentication (access + refresh token flows)
- User registration and login endpoints
- Email verification workflow
- Database layer with SQLAlchemy + PostgreSQL integration
- Alembic migrations for versioned schema changes
- RESTful API conventions
- API versioning support
- Rate limiting
- CORS configuration
- Pagination utilities for list endpoints
- Centralized error handling patterns
- Logging and request observability baseline

## Quick Start

```bash
# 1) Clone and enter project
git clone https://github.com/asynckeel-max/asynckeel-core.git
cd asynckeel-core

# 2) Install dependencies
pip install -r requirements.txt

# 3) Configure environment
cp .env.example .env

# 4) Run database migrations
alembic upgrade head

# 5) Start API server
uvicorn app.main:app --reload
```

Test a sample endpoint:

```bash
curl http://127.0.0.1:8000/api/v1/health
```

## Project Structure

```text
app/
  api/            # API routes (versioned endpoints)
  core/           # Settings, security, shared utilities
  models/         # SQLAlchemy models
  schemas/        # Pydantic request/response schemas
  services/       # Business logic
alembic/          # Migration scripts
tests/            # Automated tests
```

## Configuration

Use `.env` to configure runtime values. Common variables:

- `APP_ENV` (development, staging, production)
- `DATABASE_URL` (PostgreSQL connection string)
- `JWT_SECRET_KEY` (token signing secret)
- `JWT_ACCESS_TOKEN_EXPIRE_MINUTES`
- `JWT_REFRESH_TOKEN_EXPIRE_MINUTES`
- `CORS_ALLOW_ORIGINS`
- `RATE_LIMIT_DEFAULT`
- `LOG_LEVEL`

## Contributing

Contribution guidelines are maintained in the hub repository:

- https://github.com/asynckeel-max/asynckeel-hub/blob/main/community/CONTRIBUTING.md

## License

AsyncKeel is released under the MIT License.
