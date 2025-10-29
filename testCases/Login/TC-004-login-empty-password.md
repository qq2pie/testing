# TC-004 – User cannot log in with an empty password field

## Related Feature / Module
Login / Account

## Objective
Verify that the user cannot log in to an existing account when the password field is left empty.

## Preconditions
- User is **not logged in** to any existing account.  
- User is on the **login page**.

## Test Data
- Username: `testUser1`  
- Password: *(empty)*

## Test Steps
1. Enter a valid username (`testUser1`) in the **Username** field.  
2. Leave the **Password** field empty.  
3. Click the **Login** button.

## Expected Result
- The login attempt fails.  
- The user is **not redirected** to the dashboard or account page.  
- A validation message is displayed: *"Password field cannot be empty."*