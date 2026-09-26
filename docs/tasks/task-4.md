# create auth models

db tables creation for auth realted models

## Steps

- [ ] **Define User model and schema** — Create the User model with fields for id, email, hashed_password, first_name, last_name, role, is_active, and timestamps.
- [ ] **Define Role and Permission models** — Create role-based access control (RBAC) tables to link users to specific roles and permissions within the school management system.
- [ ] **Setup database migration scripts** — Generate and configure database migration files (e.g., Alembic for SQLAlchemy) to create the auth-related tables.
- [ ] **Run and verify migrations** — Apply migrations to the development database and verify that tables, foreign keys, and indexes are correctly created.

## Acceptance criteria

- [ ] User, Role, and Permission tables are successfully created in the database via migrations.
- [ ] User model properly enforces unique constraints on the email field.
- [ ] Relationships between Users and Roles are correctly established with proper foreign key constraints.
- [ ] Database migration scripts run cleanly without errors on a fresh database instance.

GitHub issue: https://github.com/trace-organization/school-management-system/issues/1
