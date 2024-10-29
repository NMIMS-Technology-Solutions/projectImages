



    
  
# Event Creation and Course Allocation 
  
    
  

## Introduction  
  
    
  

In the **Event Creation and Course Allocation** module, the Admin creates an event for a specified date range. Once the event is created, the Admin can add courses for the event. During course creation, the Admin specifies details such as lecture time, venue, and session (Fall or Winter). 
  
    
  

Entity Relationship Diagram(ERD)  
  

<img src="https://i.ibb.co/3k0FdgP/ERD.png" >
  

## Tables:  
  
    
  

1) Master Tables: event
  
2) Tables used for mapping: interdesciplinary_courses, user_event, users 
    
  

## Diagram:  
  

<img src="https://i.ibb.co/Ss9hYx3/Functional-diagram.png" >  
  
    
  

## Data Flow:  
  

<img src="https://i.ibb.co/fD9yv6S/Flow-diagram.png" > 
  
    
  


1.  **Event Creation:**
    
    -   The Admin creates an event and sets the date range (start and end dates) for the event.
    -   Event data is stored in the `event` table on the MySQL server.

2.  **Course Addition:**
    
    -   After creating an event, the Admin adds courses to it by specifying:
        -   **Lecture Time:** Scheduled time for each lecture.
        -   **Venue:** Location where the course lectures will take place.
        -   **Session:** Semester or session, e.g., Fall or Winter.
    -   Course details are stored in the `interdesciplinary_courses` table.
3.  **Event-Course Mapping:**
    
    -   Each course is associated with an event in the `interdesciplinary_courses` table, linking each course to the specific event.
4.  **Data Storage:**
    
    -   Event information is saved in the `event` table, and course information in the `interdesciplinary_courses` table.
    -   The `interdesciplinary_courses` table is used to retrieve data for event-specific courses.

## Roles:

1.  **Admin:**
    -   Admin can create events by setting the event name and date range.
    -   Admin can add courses to events and set lecture time, venue, and session for each course.
2.  **Participants (Students):**
    -   Students can view events and courses linked to their session, location, and schedule, And select the courses.
