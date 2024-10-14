

# Attendance

## Introduction

The attendance module in the LMS, integrated with SAP, enables faculty to efficiently mark and manage student attendance on a daily basis. Additionally, students can view their attendance records, ensuring transparency and easy access to their attendance status.

Entity Relationship Diagram(ERD)
<img  src="https://i.ibb.co/VC75Jhz/Screenshot-2024-10-07-151454.png">
## Tables:

1) Master Tables: users, user_course, course from school database

2)  Attendance Table: timetable from timetable_metadata database and student_course_attendence from School database.

## Diagram:
<img src="https://i.ibb.co/VYQPDYf/Screenshot-2024-10-09-134755.png">

## Data Flow:
<img src="https://i.ibb.co/0M53Pht/flowdiagram.png">

1. **Data Transmission**:

	-   Daily attendance data is transmitted from the SAP system to our system.
	-   The data is stored in the timetable_metadata database, specifically in the timetable table on the MySQL server.

2.  **Faculty Access**:

	-   Faculty members access the system to view their attendance slots.
	-   The application retrieves relevant data by combining information from three tables:

-   **Timetable Table**: Provides the schedule.
-   **Course Table**: Contains details about the courses being taught.
-   **Usercourse Table**: Holds information about student enrollments in these courses.

4.  **Attendance Marking**:

	-   By default, all students are marked as present.
	-   Faculty members can mark any student as absent using a toggle feature.

5.  **Data Storage**:

	-   Once attendance is recorded, the data is stored in the student_course_attendance table.
	-   This table is used to retrieve attendance data for viewing and editing purposes.

6.  **Faculty Updates**:
	
	-   Faculty can easily access and update attendance records, ensuring accurate and up-to-date information.

7.  **Student Access**:
	-   Attendance data received from SAP is stored in both a MySQL database and a text format.
	-   Students can retrieve and view their attendance records accurately.