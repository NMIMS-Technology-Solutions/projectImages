 
# RESCHEDULING -ADMIN
 
## Introduction
Rescheduling allows the admin to manage lectures by adding regular lectures, scheduling extra lectures, canceling lectures (including canceling against extra lectures), canceling all lectures for a specific day, or just canceling individual lectures. Admins can also modify lecture details such as date, time, faculty, and room, as well as reschedule or update lecture.

## Data Flow:
 
<img  src="https://raw.githubusercontent.com/NMIMS-Technology-Solutions/projectImages/b0c481502612625f0b3dc687726dae0e6639ed2a/infra_images/management%20master%20data/management-%20master%20data.png">
 
## **Entity Relationship Diagram (ERD)**

<img  src="">
  
## **1) Master Tables**
 
- dbo.academic_calendar
- dbo.academic_year
- dbo.organizations
- dbo.campuses
- dbo.buildings
- dbo.holiday_types
- dbo.faculty_types
- dbo.faculties

##  ADD REASON TYPE AND REASON 

## ADD REGULAR  LECTURE

 
##  ADD EXTRA CLASS


 ## CANCEL LECTURE 



## RESCHEDULE LECTURE
 


## MODIFY LECTURE
 


## Cancel Against Extra Class
 

## Cancel



## Cancel for the day



## FETCH LECTURE 


##  CHANGE THE DATE , SLOTS AND FACULTY 



##  CHANGE THE ROOM AND FACULTY 


## SEND EVENTS TO SAP
**[Room approval API](../room-approval/room-approval.md)**

## SAP RESULT


## REVERT ALL 

## UPDATE THE EVENT TO  FINAL TIMESHEET