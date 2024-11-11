


# Super Admin Approval

# Introduction

This module allows the Super Admin to manage research forms by approving, rejecting, or placing them on hold based on the direction of the Vice Chancellor.

Entity Relationship Diagram (ERD)
<img src="https://i.ibb.co/Rpyy1TS/super-admin-erd.png" alt="super-admin-erd" border="0">
## Tables

1. journal_paper_article
2. book_publication
3. book_chapter_publication
4. conference
5. research_award
6. research_project
7. research_seminar
8. edited_book_publication
9. teaching_excellance_new
10. meeting_stackholders_new
11. branding_advertisement_new
12. patent_submission_grant
13. status
14. form_status 
15. e_content_development
16. case_study
17. ipr

## Diagram

<img src="https://i.ibb.co/HT5b5Ym/super-admin-functional.png" alt="super-admin-functional" border="0">

## Data Flow
<img src="https://i.ibb.co/RpMP8dS/super-admin-flow.png" alt="super-admin-flow" border="0"> 

1. **Super Admin Role in Chronicle Review**  
   When the Chronicle Admin submits the chronicle for approval, if the Vice Chancellor identifies inaccuracies in some forms, the Super Admin acts on behalf of the Vice Chancellor to address these issues.

2. **Form Management Actions**  
   The Super Admin can reject, approve, or place forms on hold. If a form is rejected, it will not appear in the chronicle. Approved forms will be included in the chronicle as intended.

3. **Hold Status and Future Review**  
   If a form is placed on hold, the Super Admin retains the ability to approve or reject it at a later date. If approved in the future, the form will appear in the chronicle; if rejected, it will remain excluded.


