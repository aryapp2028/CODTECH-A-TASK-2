# CODTECH-A-TASK-2

**NAME** : ARYA P P

**COMPANY** : CODTECH IT SOLUTIONS

**INTERN ID** : CT08FSQ

**DOMAIN NAME** : SQL

**BATCH DURATION** : December 30th 2024 to January 30th 2025

**MENTOR NAME** : NEELA SANTHOSH KUMAR

OVERVIEW OF THE PROJECT:

PROJECT:STUDENT MANAGEMENT SYSTEM

#INTRODUCTION

The Student Management System is a database-driven application designed to efficiently manage student-related data, course information, and enrollment details. The system provides a centralized platform for educational institutions to store, retrieve, and analyze student and course data with ease. By leveraging relational database technology, the system ensures data consistency, integrity, and accessibility.

#OBJECTIVE

The primary objective of this system is to:
1.	Maintain detailed records of students, courses, and enrollments.
2.	Facilitate the management of academic information in a structured manner.
3.	Provide tools for querying and analyzing data to enhance decision-making processes.
4.	Ensure data security and integrity through proper database constraints and relationships.

#KEY FEATURES

1.	Student Records Management: Stores personal details like name, date of birth, email, and phone number.
2.	Course Management: Maintains course details such as course name, description, and credits.
3.	Enrollment Tracking: Links students with courses and records their grades.
4.	Data Retrieval: Supports SQL-based queries for fetching and analyzing data.
5.	Relational Integrity: Ensures proper relationships between entities using foreign keys.
6.	Scalability: Can be expanded to include additional features such as attendance tracking and fee management.

#DATABASE SCHEMA

1.	Students Table:
o	StudentID: Primary key, unique identifier for each student.
o	FirstName: First name of the student.
o	LastName: Last name of the student.
o	DOB: Date of birth of the student.
o	Email: Email address of the student.
o	PhoneNumber: Contact number of the student.

2.	Courses Table:
o	CourseID: Primary key, unique identifier for each course.
o	CourseName: Name of the course.
o	CourseDescription: Brief description of the course.
o	Credits: Number of credits assigned to the course.

3.	Enrollments Table:
o	EnrollmentID: Primary key, unique identifier for each enrollment.
o	StudentID: Foreign key referencing Students.StudentID.
o	CourseID: Foreign key referencing Courses.CourseID.
o	Grade: Grade achieved by the student in the course.

#LIMITATIONS

1.	Lack of user interface for non-technical users to interact with the database.
2.	Limited to academic records; does not include features like attendance or financial data.
3.	Manual SQL query execution required for data retrieval and analysis.
4.	No automated notification or alert system for updates or deadlines.

#FUTURE IMPROVEMENTS

1.	Development of a user-friendly web or mobile application interface.
2.	Integration of attendance and fee management modules.
3.	Implementation of data analytics dashboards for performance tracking.
4.	Inclusion of automated email and SMS notifications.
5.	Support for multiple languages and localization.

#SYSTEM STUDY

The system is based on a relational database model, ensuring that data is organized in interconnected tables. It employs SQL for data manipulation and retrieval, providing a robust and scalable solution. The study reveals that most academic institutions face challenges in managing student data due to scattered and unstructured storage. This system addresses these issues by consolidating data into a single platform.

#SYSTEM DESIGN

1.	Entity-Relationship (ER) Diagram: Represents the relationships between Students, Courses, and Enrollments.
2.	Normalization: Ensures data is stored in a structured manner without redundancy.
3.	Database Constraints: Includes primary keys, foreign keys, and data type restrictions to maintain integrity.
4.	Logical Flow:
o	Input: Data entry into Students and Courses tables.
o	Processing: Enrollments linking students to courses.
o	Output: Query results for analysis and reporting.

#MODULES

1.	Student Module:
o	Add, update, and delete student records.
o	View student details.

2.	Course Module:
o	Add, update, and delete course information.
o	View course details.

3.	Enrollment Module:
o	Register students for courses.
o	Assign and update grades.

4.	Reporting Module:
o	Generate reports on student performance.
o	Count and list students enrolled in each course.

#CONCLUSION

The Student Management System provides an efficient and reliable method for managing academic records. By leveraging relational databases, it ensures data integrity and accessibility. While the current system meets fundamental requirements, future enhancements will make it more comprehensive and user-friendly. This system is a stepping stone toward fully digitalized academic management.

#OUTPUT

![Image](https://github.com/user-attachments/assets/d74e5c4e-d498-4da3-83b0-58ed2fd2ac5b)

![Image](https://github.com/user-attachments/assets/ed2e68f2-bfad-4a3d-b0be-e747022ad88e)

![Image](https://github.com/user-attachments/assets/9f00a50c-3012-4dd1-b4c3-6861c2ffcc0d)

![Image](https://github.com/user-attachments/assets/0688ef56-d6cf-43c3-9b3e-688b76ddb856)

![Image](https://github.com/user-attachments/assets/e0ad0db8-2be2-48e8-93fe-3c54e4dde5bb)

![Image](https://github.com/user-attachments/assets/7dda0d00-1650-4eb5-a7f1-45a43903500a)

![Image](https://github.com/user-attachments/assets/2d1adc56-44ac-42dd-8e0c-f98af17f42cf)

![Image](https://github.com/user-attachments/assets/2c680135-6a3a-4f46-b4d0-50bd54796c2b)

![Image](https://github.com/user-attachments/assets/d7876188-85fb-4940-945b-7eff25b119c9)

