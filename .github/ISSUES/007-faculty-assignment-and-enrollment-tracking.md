## Faculty assignment and enrollment tracking

Add a `faculty` model and link activities/students to assigned faculty. Track multiple enrollment mappings and provide admin reports.

Acceptance criteria:
- `faculty` table and API endpoints to list/add faculty
- `enrollments` table linking `student_id`, `activity_id`, `faculty_id` (nullable)
- Admin report: students per activity, faculty assignments

Priority: low
