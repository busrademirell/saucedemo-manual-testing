# SauceDemo Manual Testing

A manual testing project for the SauceDemo e-commerce web application.

## Project Overview

The purpose of this project is to evaluate the functionality of the SauceDemo application through manual testing, identify potential defects, and document test results.

The project includes positive, negative, and boundary value test scenarios.

## Application Under Test

- **Application:** SauceDemo
- **Test URL:** https://www.saucedemo.com/
- **Testing Type:** Manual Testing
- **Operating System:** Windows
- **Browser:** Google Chrome
- **Device:** Desktop Computer

## Test Scope

The following functionalities were tested:

- Login and logout functionality
- Product listing and product information
- Product sorting
- Shopping cart operations
- Checkout process
- User account behavior and navigation
- Negative test scenarios
- Boundary value testing

## Test Execution Summary

A total of **31 test cases** were executed.

| Test Result | Number of Test Cases |
| ----------- | -------------------: |
| PASS        |                   27 |
| FAIL        |                    4 |
| Total       |                   31 |

- **Pass Rate:** 87.1%
- **Fail Rate:** 12.9%

## Identified Issues

The following issues were identified during testing:

1. **Product Image Mismatch:** Two product images did not match their descriptions.
2. **Incorrect Product Images:** The same dog image was displayed for all products when using the `problem_user` account.
3. **Sorting Functionality:** Sorting options could not be selected when using the `problem_user` account.

Detailed bug reports are available in the `bug-reports` folder.

## Project Structure

```text
saucedemo-manual-testing/
│
├── bug-reports/
│   ├── BUG-001_Product-Image-Mismatch.md
│   ├── BUG-002_Same-Product-Image.md
│   └── BUG-003_Sorting-Options-Not-Selectable.md
│
├── screenshots/
│   ├── TC-PROD-001_Bolt-Shirt.png
│   ├── TC-PROD-001_TestAllTheThings.png
│   ├── TC-USER-001_Product-Images.png
│   └── TC-USER-002_003_Sorting-Options.png
│
├── test-plan.md
├── test-cases.md
├── test-summary.md
└── README.md
```

## Test Documentation

- [Test Plan](test-plan.md)
- [Test Cases and Execution Results](test-cases.md)
- [Test Summary](test-summary.md)

## Bug Reports

- [BUG-001: Product Image Mismatch](bug-reports/BUG-001_Product-Image-Mismatch.md)
- [BUG-002: Same Image Displayed for All Products](bug-reports/BUG-002_Same-Product-Image.md)
- [BUG-003: Sorting Options Cannot Be Selected](bug-reports/BUG-003_Sorting-Options-Not-Selectable.md)

## Conclusion

This project provided practical experience in manual software testing, test case design, test execution, defect identification, and bug reporting.

The test results and identified issues are documented with supporting evidence where applicable.
