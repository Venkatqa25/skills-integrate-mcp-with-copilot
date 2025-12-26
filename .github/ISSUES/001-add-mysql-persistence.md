## Add MySQL persistence and schema

Add a persistent MySQL backend and include an importable `student.sql` schema so the app stores students, activities and enrollments in a database instead of memory.

Acceptance criteria:
- Add database configuration (connection string via env var)
- Provide `student.sql` (or migration scripts) to create required tables
- Application can connect and report DB status on startup

Suggested tables: `students`, `activities`, `enrollments`, `faculty`, `users`.

Priority: high
