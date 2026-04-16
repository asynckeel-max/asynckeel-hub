# 🧪 AsyncKeel Tutorial Outlines

## 1) AsyncKeel ile 10 dakikada production-ready auth sistemi kur

- **Target audience**: Indie developers launching first SaaS MVP
- **Prerequisites**:
  - Basic Python and FastAPI knowledge
  - Local PostgreSQL instance
  - AsyncKeel starter project cloned
- **Estimated reading time**: 12 minutes

### Step-by-step Outline
1. Install dependencies and run the project scaffold.
2. Configure environment variables for JWT and database.
3. Run initial migrations with Alembic.
4. Set up user registration and login endpoints.
5. Enable JWT access/refresh token flow.
6. Add bcrypt password hashing checks.
7. Test auth endpoints with sample requests.
8. Add quick production hardening checklist.

## 2) FastAPI'de JWT + refresh token implementasyonu (AsyncKeel ile)

- **Target audience**: Backend developers implementing secure token lifecycle
- **Prerequisites**:
  - Understanding of JWT basics
  - Familiarity with REST APIs
  - AsyncKeel auth module available locally
- **Estimated reading time**: 15 minutes

### Step-by-step Outline
1. Explain access vs refresh token responsibilities.
2. Configure token lifetimes and signing settings.
3. Implement login token issuance flow.
4. Implement refresh endpoint and rotation logic.
5. Handle token revocation/logout strategy.
6. Add common error responses (expired/invalid token).
7. Validate end-to-end flow with HTTP examples.
8. Share security pitfalls and mitigation checklist.

## 3) PostgreSQL + Alembic migration: sıfırdan production'a

- **Target audience**: Developers setting up reliable database workflows
- **Prerequisites**:
  - PostgreSQL fundamentals
  - SQLAlchemy model basics
  - AsyncKeel project bootstrapped
- **Estimated reading time**: 18 minutes

### Step-by-step Outline
1. Configure PostgreSQL connection settings.
2. Create first domain models with SQLAlchemy.
3. Generate and review Alembic migration files.
4. Apply migrations in local and staging environments.
5. Add rollback and migration safety practices.
6. Introduce migration naming/versioning conventions.
7. Cover deployment-time migration strategy.
8. Provide a production readiness checklist.

## 4) Rate limiting ve API versioning: best practices

- **Target audience**: API owners preparing for public traffic and backward compatibility
- **Prerequisites**:
  - Working FastAPI routes
  - Basic understanding of HTTP status codes
  - AsyncKeel API modules configured
- **Estimated reading time**: 14 minutes

### Step-by-step Outline
1. Define why rate limiting and versioning matter early.
2. Implement baseline rate limiting policy.
3. Return clear 429 and retry messaging patterns.
4. Introduce URL/header-based API versioning options.
5. Organize route modules by version.
6. Add deprecation communication strategy.
7. Test backward compatibility and load behavior.
8. Share a launch checklist for stable public APIs.
