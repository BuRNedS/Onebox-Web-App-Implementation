## Reachinbox Assignment

## SetUp And Installation :
* Download the zip file of the code or use git clone.
* npm i to install all the dependencies.
* inside src/index.js, Replace with your own domain and clientId.
* npm start to run.

## Sreenshots :
* Login Page :
  
 ![Login Page](https://github.com/user-attachments/assets/60becbfd-0eea-4d93-a6ea-1a5192cf1b25)

* Home Page :
  
![Home Page](https://github.com/user-attachments/assets/d524110b-d527-432e-be02-d5eab587b913)

* Email List Page :
  
![Email List Page](https://github.com/user-attachments/assets/8bcc6063-8cde-470f-b4ae-fac3c889dbb7)

* Email Reply Page :
  
![Email Reply Page](https://github.com/user-attachments/assets/c33c5ab7-c5f3-49df-87e2-bee78d34b643)

* Email Delete Page :
  
![Delete Page](https://github.com/user-attachments/assets/69782b45-fcd4-456c-a0c0-0111e6a80a1f)

* Light Mode Page :

![Light Mode](https://github.com/user-attachments/assets/7183f5c7-db21-4f52-99b8-0c695d57ba24)


## The assignment is to use the designs and APIs provided and create a functional web app as per the following
## instructions -
1. Implement the login page - Use the design provided
2. Once logged in the user should be taken to the onebox screen. /google-login
3. Implement fetching of data in onebox using api integration
/onebox/list
GET /onebox/:thread_id
DELETE /onebox/:thread_id
4. Implement keyboard shortcuts in onebox - “D” should delete. “R” should open Reply box
5. Implement custom text editor (Need to Add Custom button in editor like “SAVE” and “Variables”)
6. Implement Reply - Clicking on send should send Reply
POST /reply/:thread_id
{from: “email”, to:”email”, “subject”: “”, “body”: “<html></html>”}
7. Implement both - light and dark mode
