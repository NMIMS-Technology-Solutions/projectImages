


# Student Allocation & Reports

# Introduction

This module enables the Admin to initiate the allocation of students to their selected subjects for a specific event and to generate detailed reports on the allocation outcomes.

Entity Relationship Diagram (ERD)
<img src="https://i.ibb.co/0XLhSxj/allocation-erd.png" alt="allocation-erd" border="0">
## Tables

1. event_master
2. basket
3. student_sub_allocation
4. final_allocation
5. unallocated_students

## Diagram

<img src="https://i.ibb.co/TqJq0tF/allocation-functional.png" alt="allocation-functional" border="0">

## Data Flow
<img src="https://i.ibb.co/GQsMbsX/allocation-flow-new.png" alt="allocation-flow-new" border="0">

 1. **Data Storage**
        
- All finally allocated students data are stored in the `final_allocation` table

2. **Student Subject Selection Completion** Once students have selected subjects within an event, the selection phase concludes, and the allocation process begins. 

3. **Subject Allocation by Admin** The Admin initiates the allocation of subjects to students based on their selections. Allocation is carried out on a first-come, first-served basis, ensuring that students are assigned to their chosen subjects as availability allows.

4. **Report Generation** After allocation, reports are generated to summarize both allocated and unallocated students, providing a clear overview of the event’s subject assignment outcomes.

5. **Notification via Email** An email notification is sent to students who have been successfully allocated subjects, confirming their subject assignments.

