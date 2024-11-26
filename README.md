### README.md

Project Objective: 
Create a personal account for users of a (online cosmetics shop) website to provide them with a tool for managing personal data, client card (CC) balance, and purchase history. 
The personal account will be available on both the desktop and mobile versions of the website.

Current Status: 
Currently, customers have the ability to obtain and activate a client card (discount loyalty card). Procedures for accruing and deducting bonus points from the card have also been developed. 
However, users can only check their card balance in the store by contacting a salesperson.

Tasks: 
Create a personal account on the website where users can: View information about their personal data. Check their client card balance. Review purchase history. Functional Requirements

Registration and Authorization: 
Users must be able to register or change their phone number by incoming phone number or SMS code. Ability to recover the password via email.

User Profile: 
View and edit personal information (Full Name, email address, phone number). Information about the client card (CC) and current balance.

Purchase History: 
View purchase history, including date, amount, and status (successful/canceled).

CC Information Block: 
Information about accrued and deducted points from the CC. Ability to receive notifications about important events related to the CC.

Technical Requirements: 
Technology Stack: Frontend: Vue.js for creating the user interface. Backend: Open-source project Saleor, implemented on Django and GraphQL for processing requests and managing data. 
Authentication and Security: 
Use of JWT (JSON Web Token) for managing user sessions.

