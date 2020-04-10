# Simple user management system
This is a simplified version of a service that allows users to authenticate. The idea is that students understand the general concepts behind sign-up, log-in and user creation and management. Developed using:
- node.js
- Express.js
- PostgreSQL

## Assignment
You, as a student, are suposed to do the following:
- Create a API using the stack before that will allow the API clients (your users) to perform the following operations:
    - Sign up: User creation
    - Log in: Enter the application using the user credentials

### Use cases
- As a user of the API, I want to signup (create a new user) with my user name, email and password.
- As a user of the API, I want to login with the email and password and get redirected to the home page of the application where I will see my user name.

### Guidelines
- Thing about the database structure. What information are you going to need from the users?
    - Which table(s) are you going to need?
    - What columns are you going to need?
- Once a user has been created (signup), What would the API response be?
- Once a user has logged in (using his/her email and password), What would the API response be?
- Try to do the assignment by yourself. It is the best way to learn.
- If blocked, check this repository and try to understand. Avoid copy-pasting code 🙂.

## Useful links
https://medium.com/@aeadedoyin/getting-started-with-postgresql-on-windows-201906131300-ee75f066df78
https://chocolatey.org/packages/postgresql
https://dba.stackexchange.com/questions/29767/permission-denied-in-file-trying-to-import
https://stackoverflow.com/questions/5598517/find-the-host-name-and-port-using-psql-commands
https://kb.objectrocket.com/postgresql/how-to-use-nodejs-to-insert-into-a-postgresql-table-958#just+the+code
https://kb.objectrocket.com/postgresql/node-postgres-parameterized-query-954