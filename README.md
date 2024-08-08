## Reachinbox Assignment

## SetUp And Installation :
* Download the zip file of the code or use git clone.
* npm i to install all the dependencies.
* inside src/index.js, Replace with your own domain and clientId.
* npm start to run.

## Sreenshots :


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
