




  
  

# Author Master

  

## Introduction

  

This module lets faculty members add other faculty with particular author type when completing research forms.

Entity Relationship Diagram(ERD)

<img src="https://i.ibb.co/cbCDXKy/author-erd.png" alt="author-erd" border="0">

## Tables:

1. master_input_data
2. user
3. master_inputs

## Diagram:

<img src="https://i.ibb.co/FBcZkvh/master-functional.png" alt="master-functional" border="0">

## Data Flow:

<img src="https://i.ibb.co/N6FzyX0/master-flow.png" alt="master-flow" border="0">

1. **Author Selection in Research Forms**  
   Research forms provide an option to add authors, requiring users to select authors from a dropdown list during form completion.

2. **Author Master Setup**  
   To streamline author selection, an Author Master has been created. Faculty members can add authors to this master list, making them readily available in dropdowns for future research form submissions.

3. **Two Methods for Adding Authors**  
   - **Manual Entry:** Faculty can manually add author details, selecting the author type and specifying the school campus. This method enables faculty to add authors from other campuses, as the default list only includes authors from the logged-in user’s campus.
   - **Selection from List:** Faculty can select from an existing list of authors associated with their campus and simply mark the author type.

4. **Cross-Campus Collaboration Support**  
   This setup allows faculty to add authors from other campuses as needed, ensuring flexible and accurate selection options when completing research forms.






