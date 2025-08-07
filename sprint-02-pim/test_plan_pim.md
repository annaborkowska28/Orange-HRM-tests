# Test Plan – Employee Management (OrangeHRM)

## Test Goal  
Verify that the Employee Management feature in the PIM module works correctly across various scenarios.

---

## Related Story  
- **Story:** "Testing the employee management feature"  
- **Sprint:** Sprint 2 – PIM Module Testing

---

## Scope  
This test plan is about checking if the Employee Management feature in the PIM module works properly. I want to check:

- If employees can be added with valid data  
- How the system handles missing fields  
- If employees can be searched by name  
- Whether editing employee details works correctly  
- If deletion of employees functions properly  
- Whether uploading a photo works as expected

---

## Test Cases  

| Test ID   | What I'm testing                 | Expected Result                                 |
|-----------|----------------------------------|-------------------------------------------------|
| TC-PIM-01 | Add employee with valid data     | Employee is added and visible in the list       |
| TC-PIM-02 | Add employee with missing fields | Error messages are displayed, no redirection    |
| TC-PIM-03 | Search employee by name          | Matching employee appears in search results     |
| TC-PIM-04 | Edit employee details            | Changes are saved and visible in the profile    |
| TC-PIM-05 | Delete employee                  | Employee is removed and success message appears |
| TC-PIM-06 | Upload employee photo            | Photo is uploaded and confirmation is shown     |

---

## Tools  
- **Jira + Xray** – for creating and tracking test cases  
- **OrangeHRM Demo** – as the test environment  
- **GitHub** – for documentation and version control

---

## Execution Plan  
Tests will be performed manually using the OrangeHRM demo site. Results will be documented in `test-execution_pim.md`.