## Title
TC-002 – User cannot log in with invalid credentials

## Related Feature / Module
Login/ Account

## Objective
Verify that the user cannot log in to an existing account using invalid credentials.

## Preconditions
- User is on the login page.
- User is not logged in to any existing account.

## Test Data
- test account : `invalidUser`
- test password : `invalidPassword1`

## Test Steps
1. Enter invalid username and password in the respective fields.  
2. Click the **Login** button. 


## Expected Result
- User is **not redirected** to the personal dashboard.  
- An error message is displayed: *"Invalid username or password."*
