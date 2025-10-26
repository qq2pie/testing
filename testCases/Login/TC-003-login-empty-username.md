# TC-004 – User cannot log in with an empty username field

## Related Feature / Module
Login / Account

## Objective
Verify that the user cannot log in to an existing account when the username field is left empty.

## Preconditions
- User is **not logged in** to any existing account.  
- User is on the **login page**.

## Test Data
- Username: `(empty)`  
- Password: *`testPassword1`*

## Test Steps
1. Enter a valid password (`testPassword1`) in the **Password** field.  
2. Leave the **Username** field empty.  
3. Click the **Login** button.

## Expected Result
- The login attempt fails.  
- The user is **not redirected** to the dashboard or account page.  
- A validation message is displayed: *"Username field cannot be empty."*
