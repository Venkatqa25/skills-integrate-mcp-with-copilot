## Migrate activities from in-memory store to DB

Move the current in-memory `activities` data into the DB and update endpoints to use persistence. Enforce `max_participants` when signing up.

Acceptance criteria:
- `activities` table with name, description, schedule, max_participants
- Signup endpoint checks capacity before adding enrollment
- Existing sample data migrated or provided as seed script

Priority: medium
