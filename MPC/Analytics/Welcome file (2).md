
  

  

  

  

# MPC (Analytics )

  

  

  

  

## Introduction

  

The **Analytics Tab** in the MPC Module provides a comprehensive report of all meetings, organized by school. It offers insights into the total number of meetings conducted, allowing users to review and analyze meeting activity across different schools efficiently.

  

Entity Relationship Diagram(ERD)  

<img  src="https://i.ibb.co/VC75Jhz/Screenshot-2024-10-07-151454.png">

  

  

  

## Tables:
  

- user

- user_organization

- user_role

- user_session_info

- subject

- session_master

- role

- program

- program_campus

- point_master

- organization

- mpc_user_role

- mpc_role

- master_form

- form_user

- form_a

- form_b

- form_b_point_master

- admin_program

- campus

  
  

  

## Diagram:

  

  

  

<img  src="https://i.ibb.co/VYQPDYf/Screenshot-2024-10-09-134755.png">

  

  

  

  

## Data Flow:

  

  

  

<img  src="https://i.ibb.co/0M53Pht/flowdiagram.png">

  

1.  **Complete Meeting Details in Form B**
    
    -   Program Anchors fill in all required details for each meeting in **Form B**.
    -   Once all fields are completed, the form is finalized and submitted.
2.  **Review and Approval**
    
    -   The submitted Form B is reviewed for accuracy and completeness by the Program Anchor.
    -   After approval, the meeting details become accessible in the Analytics section.
3.  **Analytics Display**
    
    -   In the **Analytics Tab**, users can view comprehensive meeting data filtered by school, campus, program, and semester.
    -   Meeting statistics are organized based on these criteria, allowing for an in-depth view of conducted meetings.
4.  **Report Viewing and Downloading**
    
    -   Users can choose to view the data visually in graph format for quick insights.
    -   Alternatively, the report can be downloaded as an Excel file for further analysis or record-keeping.

### Roles Summary

-   **Program Anchors**: Responsible for completing Form B with all meeting details, ensuring accuracy, and submitting the form for analytics access.
-   **Analytics Users**: Access the Analytics Tab to review meeting data. They can view reports organized by school, campus, program, and semester and download them as needed.
