# Test Assignment:

**Create a small application, that will have next pages that will look nice (using Material UI):**
- Login Page
    - username/email input
    - password input
    - submit button
- Register Page
  - username/email input
  - password input
  - repeat password
  - submit button
- Reset Password Page
    - username/email input
    - submit button
- Home Page
  - show the name of application (choose the one you'd like)
  - some hello words 
  - header on the top, with 1 link to settings page and small icon LOGOUT
  - on click on settings we shoudl redirect user to the settings page
  - on click on logout we should logout user and redirect him to login page
- Settings page
  - Header title: Settings Page
  - User info:
    - readonly input with his username/email
    - button LOGOUT

**Use cases, that should be covered:**

- When user is not logged in, when he enters a route he cannot enter, he will be redirected to /login page
- When user logged in, he will be redirected to HOME page

**Requirements**

- Create this small application using **TypeScript/React/MaterialUI/NodeJS** and the DB you prefer.
- Add at lest some unit test for BE part and for frontend as well, add please at least some unit tests using Jest and RTL

Application repo should have next scripts, in order to check how it works:

`lint` (using eslint) <br />
`build` (a build version) <br />
`start` (to run application locally) - this should start the FE webpack to rebuild app on changes + this should start a backend NODEJS server <br />

