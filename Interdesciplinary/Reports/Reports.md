









    
  
# Reports
  
    
  

## Introduction  
  
    
  

In the **Reports module**, the Admin can generate and download consolidated reports of student registrations and allocations. The Admin has the option to view and organize reports by school or by subject, allowing for detailed insights into student enrollment patterns and allocations. 
  
    
  

Entity Relationship Diagram(ERD)  
  

<img src="https://i.ibb.co/89scxKg/ERD.png" >
  

## Tables:  
  
    
  

1) Master Tables: user_course, user_event
  
2) Tables used for mapping: event, interdesciplinary_courses
    
  

## Diagram:  
  

<img src="https://i.ibb.co/6yKWXNc/Funcational-diagram.png" > 
  
    
  

## Data Flow:  
  

<img src="https://i.ibb.co/mzm0C6N/flow-diagram.png" >
  
    
  




1.  **Report Generation:**
    
    -   The Admin accesses the reports section to generate a consolidated student report.
    -   The system compiles data from the `student_course`, `student_cevent`, and `interdesciplinary_courses` tables to create the `consolidated_report`.
2.  **Report Download:**
    
    -   The Admin can download the consolidated report, which includes information on student registrations, organized by chosen filters such as:
        -   **School-wise Allocation**: Breakdown of student enrollments and course allocations by school.
        -   **Subject-wise Allocation**: Breakdown of student enrollments and course allocations by subject.
3.  **Report Content:**
    
    -   The consolidated report includes:
        -   **Student Details**: Basic student information (ID, name).
        -   **School Details**: School information for school-based filtering.
        -   **Course Information**: Details of the selected courses (subject, session, seats allocated).
        -   **Allocation Data**: Summary of registrations and seat allocation.
4.  **Data Storage and Retrieval:**
    
    -   Report data is dynamically generated from the `consolidated_report` view.

## Roles:

1.  **Admin:**
    -   Can access and generate consolidated student reports.
    -   Can filter reports by school or subject to obtain a detailed view of student course allocations.
