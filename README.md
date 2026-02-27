# QA Assignment Test – Senior Specialist QA

## Profile
Name: Andi Fiqih Zulfikar Ashari  
Tools Used: Katalon Studio, MySQL, DBeaver 

---

# 1. SDLC & QA Responsibilities

## What is SDLC?

SDLC is a structured approach used to build software step by step, from planning and development to testing and deployment. Its goal is to ensure the software meets business needs while staying on timeline.

### Requirement Analysis
- Review all the business requirements. If the product/feature is already exist in production, we need to compare the existing behaviour with the new requirements to identify what missing and what need to be improved.
- Define initial test strategy.

### Design
- Review system design and identify integration and data validation points.
- Ensure the validation on the action items is gonna be processed by BE/FE (to make it easier for QA when got any errors in all the action item)

### Development
- Preparing all the test data that we need in the testing phase (User account, surrounding cases and etc).
- Prepare test cases, and determine which cases can be automate.

### Testing
- Execute all the functional test cases also include negative, boundary and edge cases are meet the acceptance criteria.
- Analyze the root cause of each bugs, it is come from BE / FE.
- Confirm the Bugs to the developers.
- Log and track defects
- Re-validate the bugs after fixing.

### Deployment
- Perform regression testing for all the features before deployment process.
- Perform sanity testing for all the features that want to be deploy is already working as expected (meets the acceptance criteria from the sprint development).

### Maintenance
- Maintain the regression test case by updating the test case when each sanity test is done.
- Update automation scripts by adding the sanity test.

---

# 2. Why QA Should Be Involved Early in SDLC?

When QA is involved early, potential issues can be spotted sooner, which helps reduce the cost of fixing defects later on. Because QA understands how the product currently works, we can quickly see whether a new requirement might affect existing features. We can also check that any new changes still align with standards and don’t break backward compatibility.

---

# 3. API Testing – Reqres

Endpoint Tested:
https://reqres.in/api/users

## Manual Test Cases (Google Docs)
API Test Case Document (Sheet Reqres Users API):
https://docs.google.com/spreadsheets/d/1Qhf4XtKeGR6Nw7AG8x8RH05qgZxtq2jTeSyi7t7HW1o/edit?usp=sharing

Coverage Includes:
- Positive test cases
- Negative test cases
- Boundary test cases
- Edge cases

## API Automation Repository
GitHub Repository:
https://github.com/fiqihz/Reqres-Users

Automation Features:
- Parameterized query testing
- Response validation
- JSON parsing & assertions
- Data-driven testing
- Recording video is attach on the Execution Recordings Folder

---

# 4. UI Testing – Saucedemo

Website Tested:
https://www.saucedemo.com/

## Manual Test Cases (Google Docs)
UI Test Case Document (Sheets Saucedemo UI):
https://docs.google.com/spreadsheets/d/1Qhf4XtKeGR6Nw7AG8x8RH05qgZxtq2jTeSyi7t7HW1o/edit?usp=sharing

Test Coverage:
- Login validation scenarios
- Error message validation
- Redirect validation

## UI Automation Repository
GitHub Repository:
https://github.com/fiqihz/saucedemo-project

Automation Features:
- Structured test case design
- Reusable test objects
- Login validation automation
- Recording video is attach on the Execution Recordings Folder

---

# 5. SQL Validation – EURUSD Total Volume

Business Rule:
- BUY = Positive volume
- SELL = Negative volume
- Total volume = Sum from all LP
- If net result negative → Direction = SELL
- If net result positive → Direction = BUY

SQL Query is attached in below repository:
https://github.com/fiqihz/Total-Volume---MySql

---

Thank you for reviewing this submission.