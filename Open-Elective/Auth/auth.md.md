


# Auth/Session

# Introduction

This module provides a secure and efficient authentication and session management system for the open elective project. It is designed to handle user login, authentication, and session tracking.

Entity Relationship Diagram (ERD)
<img src="https://i.ibb.co/TcL3J9X/open-elective-auth-erd.png" alt="open-elective-auth-erd" border="0">
## Tables

1. user_info
2. role
3. user_roles 
4. modules
5. module_mapping

## Diagram

<img src="https://i.ibb.co/XyCjYgX/open-elective-auth-functional.png" alt="open-elective-auth-functional" border="0">

## Data Flow
<img src="https://i.ibb.co/f2zHf94/open-elective-auth-flow.png" alt="open-elective-auth-flow" border="0">
 
 1. **Data Storage**
        
- All user details are stored in the `user_info` table.
-  All user roles are stored in the `role` table. 
-  The database is hosted on a PostgreSQL server.

2. **User Credential Verification** When a user enters their credentials, such as username and password, the system verifies these details by checking against the database. For password security, encryption is handled using Crypto.

3. **JWT Token Generation** After successful authentication, a JSON Web Token (JWT) is generated. This token is stored in cookies, enabling further authentication in a secure manner. 

4. **Session Data Storage** The user details are also stored in Redis to provide fast, efficient access to session information, supporting a smooth, authenticated experience across the application.

