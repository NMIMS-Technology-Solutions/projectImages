


# SAP MASTER SERVICES

  

## Introduction

  

sap-master is a project implemented as a REST API that enables SAP to send data to the LMS server in JSON format. It includes functions to sanitize the data, ensuring integrity and security. Additionally, it utilizes Kafka to transmit data to other connected services, facilitating seamless integration and communication.

  

Entity Relationship Diagram(ERD)

<img src="https://i.ibb.co/ns9Kntf/sap-master-inc-ERD.png" >

## Diagram:

<img src="https://i.ibb.co/sqxm4FV/Functional-diagram.png" >

## Data Flow:

<img src="https://i.ibb.co/0MSPrTk/flow-diagram.png" >

### 1. **Data Reception from SAP**

-   API services (e.g., event, student event, student attendance) receive JSON data from SAP.

### 2. **Store in `sap_master_inc` Database**

-   The JSON data received from SAP is first stored in the `sap_master_inc` database.

### 3. **Data Conversion**

-   Data is processed and converted as needed for compatibility with the user management system.

### 4. **Data Transfer to `usermanagement` Database**

-  After conversion, data flows to the `usermanagement` database for further use.

### 5. **Services to send the data from SAP to LMS**

 - organization
 - campus
 - event-master
 - image
 - permanent-faculty
 - program-master
 - sap-number-change
 - student-event
 - student-master
 - student-master-tcs
 - student-reg-tcs
 - student-roll-no
 - subject
 - subject-enroll
 - visiting-faculty
 - organization-bulk
 - campus-bulk
 - event-master-bulk
 - image-bulk
 - permanent-faculty-bulk
 - program-master-bulk
 - sap-number-change-bulk
 - student-event-bulk
 - student-master-bulk
 - student-master-tcs-bulk
 - student-reg-tcs-bulk
 - student-roll-no-bulk
 - subject-bulk
 - subject-enroll-bulk
 - visiting-faculty-bulk
 - attendence-slot
 - admin-program
