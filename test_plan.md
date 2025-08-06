# Test Plan – Login Functionality (OrangeHRM)

##  Test Goal
Check if the login feature in OrangeHRM works correctly in different situations.

## Related Story
Story: "Check login functionality"  
Sprint: Sprint 1 - Login Tests

## Scope
This test plan focuses only on the login page. I want to check:
- If users can log in with correct credentials
- What happens when wrong data is entered
- How the system reacts to empty fields
- If login is case-sensitive (uppercase vs lowercase)
- If the system handles strange input like HTML code

## Test Cases

| Test ID | What I'm testing                          | Expected Result                                      |
|---------|-------------------------------------------|------------------------------------------------------|
| TC001   | Login with valid credentials              | User is logged in                                    |
| TC002   | Login with invalid password               | Error message is shown                               |
| TC003   | Login with empty fields                   | Validation message appears                           |
| TC004   | Case sensitivity of username and password | Login should fail                                    |
| TC005   | Login with only user name                 | Login should fail                                    |
| TC006   | Login with only password                  | Login should fail                                    |
| TC007   | Login with HTML tags in username field    | Login should fail, error message should be displayed |

## Tools
- Jira + Xray – for creating and tracking tests  
- OrangeHRM Demo – as the test environment  
- GitHub – for documentation

## Execution Plan
Tests will be done manually using the demo site. Results will be saved in `test-execution-report.md`.