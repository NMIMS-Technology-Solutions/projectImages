


# Event Creation

# Introduction

This module enables the Admin to create events that include baskets of subjects for selection by students in the Open Elective program.

Entity Relationship Diagram (ERD)
<img src="https://i.ibb.co/9stjkGq/event-erd.png" alt="event-erd" border="0">
## Tables

1. event_master
2. basket
3. basket_event
4. student_event
5. subject_master
6. basket_subject

## Diagram

<img src="https://i.ibb.co/CBZp03t/event-functional-diagram.png" alt="event-functional-diagram" border="0">

## Data Flow
<img src="https://i.ibb.co/NC2MFht/event-flow-diagram.png" alt="event-flow-diagram" border="0">
 
 1. **Data Storage**
        
- All event details are stored in the `event_master` table.
-  All baskets for event are stored in the `basket` table. 
- All courses are stored in `subject_master` table.
-  The database is hosted on a PostgreSQL server.

1. **Event Creation by Semester** The Admin creates events on a semester-wise basis, organizing subject selection periods for students. 

2. **Basket Creation** Once an event is created, the Admin creates baskets specifically for that event, grouping related subjects. 

3. **Subject Addition to Baskets** After creating the baskets, the Admin adds subjects to each basket, organizing available options for students within the Open Elective program.

