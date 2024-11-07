


# Student Response

# Introduction

This module enables students to select subjects from designated baskets within specific events in the Open Elective program.

Entity Relationship Diagram (ERD)
<img src="https://i.ibb.co/61ZWbpG/student-erd.png" alt="student-erd" border="0">
## Tables

1. event_master
2. basket
3. subject_master
4. student_sub_allocation
5. student_sub_allocation_audit

## Diagram

<img src="https://i.ibb.co/nfRcLwC/student-selection-functional.png" alt="student-selection-functional" border="0">

## Data Flow
<img src="https://i.ibb.co/QFxQZt1/student-selection-flow.png" alt="student-selection-flow" border="0">
 
 1. **Data Storage**
        
- All student responses are stored in the `student_sub_allocation` table

2. **Event Scheduling for Subject Selection** Once the Admin creates an event, a specific selection period is scheduled, during which students can choose their subjects for that event.

 3. **Student Subject Selection** During the selection period, each student selects 5 subjects from each basket within the event, allowing them to tailor their choices in the Open Elective program.

