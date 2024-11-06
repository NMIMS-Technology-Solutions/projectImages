
  

  

  

# MPC (Form B )

  

  

  

## Introduction

The **MPC Form B** module streamlines the review process for Multi Program Campus operations. Through **Form B**, Program Anchors can efficiently review and add remarks to Form A submissions, using criteria such as Program, Academic Session, Subject Name, and Academic Year to ensure a detailed and systematic assessment.
  

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

  

  

 
  


-   **Form A Submission by Course Anchor**
    
    -   The process begins with the **Course Anchor** completing and submitting **Form A**. This form records essential meeting details for a specific course, which are required for program review and analysis.
    -   Once Form A is submitted, its data becomes available in **Form B** for the Program Anchor to review.
-   **Form B Review by Program Anchor**
    
    -   The **Program Anchor** accesses **Form B** to review the Form A submissions. They filter and review meetings based on criteria such as **Academic Session, Academic Year, Program, and Subject Name**.
    -   The Program Anchor writes remarks on each meeting, providing insights and evaluations relevant to the specific program and session.
  


### Summary of Roles

-   **Course Anchor**:
    
    -   Completes and submits **Form A**, which records essential meeting details for specific courses required for program review and analysis.
    -   Ensures that once Form A is submitted, the data is made available for review in **Form B**.
-   **Program Anchor**:
    
    -   Accesses and reviews **Form B**, evaluating Form A submissions based on criteria such as **Academic Session, Academic Year, Program, and Subject Name**.
    -   Writes remarks on each meeting, offering insights and evaluations pertinent to the program and session.

