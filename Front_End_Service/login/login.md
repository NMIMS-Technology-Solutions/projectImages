
  

  

  

  

# lms-frontend-service(Log In)

  

  

  

  

## Introduction
The **LMS Login Page** provides separate access for NMIMS and SVKM users, directing each to their organization-specific portal for secure login. It also includes a **Forgot Password** option for easy account recovery, enhancing user experience and security.


## Diagram:

  


  

  

  
  

## Data Flow:

  

  

  

<img  src="https://i.ibb.co/0M53Pht/flowdiagram.png">

  

  

  

  
  
-   **Access the Login Page**
    
    -   Users use the login page of their organization (either **NMIMS** or **SVKM**) to access the LMS.
    
-   **Enter Credentials**
    
    -   On the login page, users enter their **username** and **password**.
-   **Authentication**
    
    -   After submitting their credentials, the system verifies the username and password for accuracy.
-   **Successful Login**
    
    -   If the credentials are correct, users are logged in successfully.
-   **Dashboard Access**
    
    -   Upon successful login, users are redirected to their **dashboard**, where they can view the modules assigned to them.
