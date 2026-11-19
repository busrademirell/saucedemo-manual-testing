# Test Summary

## 1. Project Overview

**Project Name:** SauceDemo Manual Testing

**Application:** SauceDemo

**Testing Type:** Manual Testing

**Project Objective:** To evaluate the functionality of the SauceDemo web application by executing manual test cases and identifying potential issues.

## 2. Test Scope

The following areas were tested:

- Login Functionality
- Product Listing and Sorting
- Shopping Cart Functionality
- Checkout Functionality
- User Account Behavior and Navigation
- Additional and Negative Test Scenarios
- Boundary Value Test Scenarios

## 3. Test Execution Summary

A total of 31 test cases were executed.

| Test Result | Number of Test Cases |
| ----------- | -------------------: |
| PASS        |                   27 |
| FAIL        |                    4 |
| Total       |                   31 |

**Pass Rate:** 87.1%

**Fail Rate:** 12.9%

## 4. Failed Test Cases

The following issues were identified during testing:

| Test Case ID | Issue Description                                                          | Result |
| ------------ | -------------------------------------------------------------------------- | ------ |
| TC-PROD-001  | Two product images did not match their descriptions.                       | FAIL   |
| TC-USER-001  | The same dog image was displayed for all products when using problem_user. | FAIL   |
| TC-USER-002  | Sorting options could not be selected when using problem_user (A to Z).    | FAIL   |
| TC-USER-003  | Sorting options could not be selected when using problem_user (Z to A).    | FAIL   |

## 5. Additional Observations

- The initial login with performance_glitch_user took a long time.
- A product detail page was displayed after login.
- After navigating back to the Products page and refreshing it, the user remained on the Products page.
- The expected navigation behavior was observed, so TC-USER-006 was marked as PASS.

## 6. Conclusion

Most of the tested functionalities worked as expected.

Login, shopping cart, checkout, logout, About navigation, and boundary value scenarios were successfully completed.

However, issues were identified in product image display and product sorting when using problem_user.

Further investigation is recommended for the identified issues.

Overall, 27 out of 31 test cases passed, while 4 test cases failed.
