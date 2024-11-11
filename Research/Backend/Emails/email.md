



  
  

# Email

  

## Introduction

  

This module enables the Admin to add and manage email addresses and email groups, which can be used to send the Chronicle via email every Monday. The Admin can create and configure email groups, ensuring the right recipients receive the Chronicle on time each week. This system streamlines the communication process by automating the distribution of the Chronicle to all designated recipients.

  

Entity Relationship Diagram(ERD)

<img src="https://i.ibb.co/dBkbmp8/emails-erd.png" alt="emails-erd" border="0">

## Tables:

  

1. chronicle_emails
2. email_groups

## Diagram:

<img src="https://i.ibb.co/VmrqV8Z/emails-functional.png" alt="emails-functional" border="0">

## Data Flow:

<img src="https://i.ibb.co/FWPBxt3/emails-flow.png" alt="emails-flow" border="0">

1. **Email Group Creation by Admin**  
   The Admin has the option to create multiple email groups, allowing for organized management of different recipient sets for sending the Chronicle.

2. **Adding Emails to Groups**  
   Within each email group, the Admin can add individual email addresses as needed. The Admin can specify the name of the person and their email ID when adding them to the group.

3. **Email Assignment to Specific Groups**  
   The Admin can assign added emails to specific groups, ensuring that the right individuals are included in the appropriate distribution lists.

4. **Chronicle Email Distribution**  
   Once the email groups and individual emails are configured, the added email addresses are used to send the Chronicle emails each Monday, ensuring that all designated recipients receive the updates.

5. **Flexible Email Management**  
   Admin can manage email groups and individual entries separately, allowing for easy customization and updates based on the needs of the Chronicle distribution process.


