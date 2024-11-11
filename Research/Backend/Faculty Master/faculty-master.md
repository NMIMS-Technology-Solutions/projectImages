



  
  

# Faculty Master

  

## Introduction

  

This module lets faculty members add other faculty as either internal (within the institution) or external (outside the institution) when completing research forms

Entity Relationship Diagram(ERD)

<a href="https://ibb.co/1T0hvFk"><img src="https://i.ibb.co/HqK1F5j/faculty-erd.png" alt="faculty-erd" border="0"></a>

## Tables:

1. faculties
2. user
3. faculty_type

## Diagram:

<img src="https://i.ibb.co/wCb6t4M/faculty-functional.png" alt="faculty-functional" border="0">

## Data Flow:

<img src="https://i.ibb.co/C16qfp5/faculty-flow.png" alt="faculty-flow" border="0">

1. **Internal and External Faculty Options in Research Forms**  
   Research forms provide an option to add faculty collaborators as either internal or external, ensuring proper categorization of contributors.

2. **Faculty Master Creation**  
   To streamline this process, a Faculty Master has been established. This allows faculty members to add others to the master list as either internal or external, creating a centralized source for selection in research forms.

3. **Dropdown Selection in Research Forms**  
   When filling out research forms, users can access a dropdown list populated with names from the Faculty Master. This dropdown enables them to quickly select collaborators, whether internal or external, without repeatedly entering information.

4. **Two Methods for Adding Faculty**  
   - **Manual Entry:** This option allows faculty to add collaborators from different school campuses by filling in their details manually. This is particularly useful for adding faculty members who do not already exist in the dropdown list.
   - **Selection from List:** Faculty members from the logged-in user’s campus can be added directly by selecting them from an existing list, marking them as either internal or external.

5. **Cross-Campus Collaboration Support**  
   This setup not only simplifies the process of adding collaborators but also allows for cross-campus collaboration by letting faculty members add colleagues from other campuses as needed.





