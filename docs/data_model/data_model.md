| Entity | Attributes | Types |
|--------|------------|--------|
| Student | id (PK), name, email | int, string, string |
| Teacher | id (PK), name, email | int, string, string |
| Subject | id (PK), name, teacher_id (FK) | int, string, int |
| Grade | id (PK), student_id (FK), subject_id (FK), grade, date | int, int, int, int, date |
| Deadline | id (PK), subject_id (FK), title, due_date | int, int, string, date |
| Reminder | id (PK), student_id (FK), deadline_id (FK), notify_time, enabled | int, int, int, time, bool |
