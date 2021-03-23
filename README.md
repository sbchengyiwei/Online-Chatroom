# Online-Chatroom
An online chat application developed by java spring boot and HTML css. You can download the code and open it as a Maven project in IntelliJ.
### Layers: 
- The back-end with Spring Boot;
- The front-end with Thymeleaf;
- Application tests with Selenium;


## The Back-End
The back-end is all about security and connecting the front-end to database data and actions.
1. Managing User Access with Spring Security
Restricted unauthorized users from accessing pages other than the login and signup pages. 
2. Handling Front-End Calls with Controllers
Writed controllers for the application that bind application data and functionality to the front-end. 
3. Making Calls to the Database with MyBatis Mappers
Implemented MyBatis mapper interfaces for each of the model types. 
## The Front-End
Developed HTML templates for the required application pages. Inserted Thymeleaf attributes to supply the back-end data and functionality described by the following individual page requirements:
1. Login Page
Everyone should be allowed access to this page, and users can use this page to login to the application.
Show login errors, like invalid username/password, on this page.
Login page: http://localhost:8080/login
2. Signup Page
Everyone are allowed access to this page, and potential users can use this page to sign up for a new account.
Validated that the username supplied does not already exist in the application, and show such signup errors on the page when they arise
Sign Up page: http://localhost:8080/signup
3. Home Page
The home page has a logout button that allows the user to log out of the application and keep their data private.
The home page is the center of the application and hosts the required pieces of functionality - chating with various fonts and saving their chat record as a copy.
Home page: http://localhost:8080/home

## Testing
1. Writed Tests for User Signup, Login, and Unauthorized Access Restrictions.
Writed a test that verifies that an unauthorized user can only access the login and signup pages.
Writed a test that signs up a new user, logs in, verifies that the home page is accessible, logs out, and verifies that the home page is no longer accessible.
2. Writed Tests for Note Creation, Viewing, Editing, and Deletion.
Writed a test that creates a note, and verifies it is displayed.
Writed a test that edits an existing note and verifies that the changes are displayed.
Writed a test that deletes a note and verifies that the note is no longer displayed.
3. Writed Tests for Credential Creation, Viewing, Editing, and Deletion.
Writed a test that creates a set of credentials, verifies that they are displayed, and verifies that the displayed password is encrypted.
Writed a test that views an existing set of credentials, verifies that the viewable password is unencrypted, edits the credentials, and verifies that the changes are displayed.
Writed a test that deletes an existing set of credentials and verifies that the credentials are no longer displayed.
