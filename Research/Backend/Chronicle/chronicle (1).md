


# Chronicle Creation & Approval

# Introduction

This module enables the Chronicle Admin to create a chronicle, which is then verified by the Vice Chancellor and released every Monday.

Entity Relationship Diagram (ERD)
<img src="https://i.ibb.co/fQwJZ9D/research-erd.png" alt="research-erd" border="0">
## Tables

1. chronicle_edition
2. status
3. chronicle_volume_no


## Diagram

<img src="https://i.ibb.co/f1SbXxQ/chronicle-functional-new.png" alt="chronicle-functional-new" border="0">

## Data Flow
<img src="https://i.ibb.co/c178vgX/chronicle-flow.png" alt="chronicle-flow" border="0">
 

1. **Chronicle Creation by Chronicle Admin**  
   The Chronicle Admin compiles the chronicle using various components, including the Vice Chancellor’s Note, approved research forms, Teaching Excellence submissions, Meeting Stakeholders updates, Branding & Advertisement forms, and the "News of the Week" contributed by the librarian. Each of these elements is combined to create a comprehensive chronicle.

2. **Weekly Data Collection**  
   The chronicle is created based on data of current week, ensuring that the content is timely and relevant.

3. **Vice Chancellor Approval**  
   Once the chronicle draft is complete, it is sent to the Vice Chancellor for review and approval.

4. **Email Scheduling**  
   After approval by the Vice Chancellor, the Chronicle Admin schedules an email to distribute the chronicle to its intended recipients.

