# CRS_PROJECT_GNIOT
Course Registration System (Backend)
This project is a comprehensive backend solution for a Course Registration System, developed using Java, Spring Boot, and MySQL. It is designed to efficiently manage student enrollments, courses, and the registration process in an academic environment. The system provides a structured API for seamless integration with potential frontend applications, making it ideal for educational institutions.

Features:
Student Management:

The system allows the creation, updating, and deletion of student profiles.
Each student is assigned a unique ID, which is used to manage their course enrollments.
Students can view their registered courses, and administrators can manage student records through secure API endpoints.
Course Management:

Courses are created, updated, and removed by administrators through the backend.
Each course includes information such as the course name, description, and available credits.
The system enforces course prerequisites, ensuring that students meet the necessary criteria before enrolling in advanced courses.
Registration Process:

Students can register for courses via a well-structured API, with the system handling enrollment limits to prevent over-registration.
The system ensures real-time updates on course availability and allows students to drop courses when needed.
This feature dynamically updates student profiles and course availability, streamlining the registration process.
Database Integration:

The backend uses MySQL to store and manage all data related to students, courses, and registrations.
The relational database structure ensures efficient querying and data management, allowing scalability for institutions of any size.
The system supports transactions to maintain data consistency, especially during course enrollments and updates.

This project focuses on backend functionality, offering a scalable and secure foundation for a full-fledged Course Registration System. It can be extended with a frontend for a complete user experience.
