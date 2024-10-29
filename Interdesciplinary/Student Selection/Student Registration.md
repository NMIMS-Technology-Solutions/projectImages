






    
  
# Student Registration
  
    
  

## Introduction  
  
    
  

In the **Student Registration** module, students register for interdisciplinary courses from two available sessions: Fall and Winter. During course selection, students can view detailed information about each course, including lecture time, venue, and the number of seats allocated. 
  
    
  

Entity Relationship Diagram(ERD)  
  

<img src="https://i.ibb.co/89scxKg/ERD.png" >
  

## Tables:  
  
    
  

1) Master Tables: user_course, user_event
  
2) Tables used for mapping: event, interdesciplinary_courses
    
  

## Diagram:  
  

<img src="https://i.ibb.co/N1jpKTF/Functional-diagram.png" >  
  
    
  

## Data Flow:  
  

<img src="https://i.ibb.co/F5ZDP7W/Flow-chart.png" >
  
    
  



1.  **Course Selection:**
    
    -   Students log into the registration module and select interdisciplinary courses from available sessions: Fall or Winter.
    -   Available courses are displayed with details including lecture time, venue, and allocated seats.
2.  **Course Details Viewing:**
    
    -   Students can view specific details of each course before selection, such as:
        -   **Lecture Time**: Scheduled time for each course lecture.
        -   **Venue**: Location where the lecture's will be held.
        -   **Allocated Seats**: Number of seats available for enrollment.
3.  **Registration Process:**
    
    -   Once a student selects a course, their registration is saved in the `user_course` table.
    -   The `user_course` table links each student with their selected courses and ensures seat allocation limits are maintained.
4.  **Data Storage:**
    
    -   Course information is stored in the `interdesciplinary_courses`  table.
    -   Student registration data is saved in the `user_course` table, linking student IDs with their selected courses.
5.  **Capacity Control:**
    
    -   The system checks the `numberOfSeats` field in `interdesciplinary_courses` to ensure seat availability before finalizing registration.

## Roles:

1.  **Student:**
    -   Students can browse and view course details, including lecture times, venues, and seat availability.
    -   Students can register for courses from two sessions (Fall and Winter) based on seat availability.
2.  **Admin:**
    -   Admins can update course details, manage seat allocations, and review registration statistics.
