A FastAPI application template with authentication implemented.
The code follows a clean DDD approach where auth is a feature.

Uses JWT authentication. Access tokens are sent in JSON body. Refresh tokens are sent via HTTP only cookies as well as JSON body so that mobile application can also use it.

Refresh token rotation and revoking strategy implemented.

PostgreSQL (18) table has `users` and `refresh_tokens` tables.

UnitOfWork design pattern implemented.
