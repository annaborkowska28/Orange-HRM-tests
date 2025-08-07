# Test Execution Report – Sprint 2: Employee Management

## Summary  
All 6 test cases were executed manually against the OrangeHRM demo site, focusing on the Employee Management feature in the PIM module.  
All tests passed successfully, and the feature behaved as expected in each scenario.

---

## Test Results  

| Test ID    | What I'm testing                          | Expected Result                                  | Actual Result                                  | Status |
|------------|-------------------------------------------|--------------------------------------------------|------------------------------------------------|--------|
| TC-PIM-01  | Add employee with valid data              | Employee is added and visible in the list        | Employee added successfully                    | Pass   |
| TC-PIM-02  | Add employee with missing fields          | Validation messages are displayed                | Validation messages shown                      | Pass   |
| TC-PIM-03  | Search employee by name                   | Matching employee appears in search results      | Employee found via search                      | Pass   |
| TC-PIM-04  | Edit employee details                     | Changes are saved and reflected in the profile   | Details updated and saved                      | Pass   |
| TC-PIM-05  | Delete employee                           | Employee is removed and success message appears  | Employee deleted with confirmation             | Pass   |
| TC-PIM-06  | Upload employee photo                     | Photo is uploaded and confirmation is shown      | Photo uploaded and confirmation displayed      | Pass   |

---

## Bugs Reported  
- No bugs were found during this round of testing.  
- Minor UX note: After uploading a photo, the system does not redirect to the employee profile automatically 
- (suggested improvement, not reported as a bug).

---

## Summary  
- Total test cases: 6  
- Passed: 6  
- Failed: 0  
- Bugs reported: 0