PostgreSQL is a powerful, open source object-relational database system. This package deploys a standalone PostgreSQL server with persistent storage.

Environment variables:

- POSTGRES_DB: The name of the default database to create
- POSTGRES_USER: The superuser/owner username
- POSTGRES_PASSWORD: The superuser password

Data is persisted under `${APP_DATA_DIR}/data/postgres`.
