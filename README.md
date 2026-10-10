# university-course-management-system
🛠️ Tech Stack

Database Engine: MySQL / MariaDB

Environment: XAMPP (Apache & MySQL)

Management Tool: phpMyAdmin

🗄️ Database Structure

The project consists of 5 relational tables:

Departments — Stores department details (DepartmentID, DepartmentName)

Students — Stores student personal info & enrollment dates

Courses — Stores course titles and credits linked to departments

Instructors — Stores instructor details and salaries

Enrollments — Junction table mapping students to their courses

🚀 Setup & Installation

Open XAMPP Control Panel and start Apache and MySQL.

Open phpMyAdmin (http://localhost/phpmyadmin).

Create a database named university_db.

Import or run the SQL file (university_db.sql) in the SQL tab.

📊 Key Highlights & Queries Covered

This project includes 16 SQL queries demonstrating:

CRUD Operations: Basic Insert, Select, Update, Delete queries.

Aggregations: COUNT, AVG, MAX, GROUP BY, and HAVING filters.

Set Operations: INTERSECT and conditional OR filtering.

Joins: INNER JOIN and LEFT JOIN across multiple tables.

Subqueries: Complex data fetching using nested queries and relational constraints.
