#  Test Execution Report – Sprint 1: Login Functionality

##  Summary
All 7 test cases were executed against the OrangeHRM demo login page.  
One test case failed because the system didn't handle uppercase and lowercase letters in the username correctly.

##  Test Results

| Test ID | What I'm testing                          | Expected Result                                      | Actual Result                         | Status |
|---------|-------------------------------------------|------------------------------------------------------|---------------------------------------|--------|
| TC001   | Login with valid credentials              | User is logged in                                    | User successfully logged in           | Pass   |
| TC002   | Login with invalid password               | Error message is shown                               | Error message displayed               | Pass   |
| TC003   | Login with empty fields                   | Validation message appears                           | Validation message displayed          | Pass   |
| TC004   | Case sensitivity of username and password | Login should fail                                    | Login succeeded with wrong casing     | Fail   |
| TC005   | Login with only user name                 | Login should fail                                    | Error message displayed               | Pass   |
| TC006   | Login with only password                  | Login should fail                                    | Error message displayed               | Pass   |
| TC007   | Login with HTML tags in username field    | Login should fail, error message should be displayed | Error message displayed, login failed | Pass   |

## Bug Reported
- **TC004** – Login succeeded even though username casing was incorrect  
  → Bug ID: 'OH-21' [View in Jira](https://annaborkowska2806.atlassian.net/browse/OH-21)

## Summary
- Total test cases: 7  
- Passed: 6  
- Failed: 1  
- Bug reported: 1