# Volunteer Project

Volunteer is a platform designed to connect volunteers with organizations in need. 
It allows volunteers to create profiles, showcase their skills, and apply for tasks, while organizations can post opportunities and manage volunteer assignments.

## Features

- **Volunteer Management**: Create accounts, list competencies, and apply for tasks.
- **Organization Management**: Post volunteer opportunities and track applications.
- **Admin Management**: Oversee users, verify competencies, and maintain system integrity.
- **Database**: MySQL database storing all users, competencies, and assignments.

## Database

- The repository contains `volunteer_db.sql`, which can be imported into MySQL to recreate the database structure and initial data.
- Tables include:
  - `volunteers`
  - `competencies`
  - `volunteer_assignments`

## How to Use

1. Import `volunteer_db.sql` into your MySQL server using phpMyAdmin or MySQL Workbench.
2. Connect the database to your web application (if applicable).

## Future Work

- Add a web interface using HTML, CSS, React.
- Implement authentication and authorization for volunteers, organizations, and admins.
- Expand functionality to track volunteer hours and reports.

