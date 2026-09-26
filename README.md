# nopCommerce Manual Testing Project

## Project Overview

This project demonstrates manual testing of the **nopCommerce Demo Store**, an e-commerce web application.

The project covers functional testing of key customer-facing workflows including registration, authentication, product search, product details, wishlist, shopping cart, checkout, and order management.

The testing approach includes positive testing, negative testing, boundary-value testing, smoke testing, regression testing, UI validation, and end-to-end workflow testing.

## Application Under Test

* **Application:** nopCommerce Demo Store
* **Application Type:** E-Commerce Web Application
* **Testing Approach:** Manual Testing
* **Test Environment:** Web Browser

## Testing Scope

The project covers:

* User Registration
* Login and Logout
* Product Search
* Product Categories and Navigation
* Product Details
* Wishlist
* Shopping Cart
* Customer Account and Address Management
* Checkout
* Order Management
* Input Validation
* UI Validation

## Testing Types

* Functional Testing
* Positive Testing
* Negative Testing
* Boundary Value Analysis
* Equivalence Partitioning
* Smoke Testing
* Regression Testing
* End-to-End Testing
* UI Testing
* Input Validation Testing

## Test Coverage

| Metric                  | Result |
| ----------------------- | -----: |
| Test Scenarios Designed |     82 |
| Test Cases Designed     |     82 |
| Test Cases Executed     |     10 |
| Passed                  |     10 |
| Failed                  |      0 |
| Confirmed Defects       |      0 |
| Execution Pass Rate     |   100% |

> The 100% pass rate applies only to the 10 test cases executed during the current test cycle. The remaining test cases were designed but not executed.

## Test Execution

The executed test cases covered:

* Valid customer registration
* Duplicate email validation
* Invalid email validation
* Mandatory-field validation
* Valid login
* Invalid password handling
* Blank login validation
* Existing product search
* Non-existing product search
* Adding a product to the shopping cart

All 10 selected test cases passed during the execution cycle.

## Project Artifacts

### 01 – Test Plan

Contains the overall testing objective, scope, approach, testing types, entry/exit criteria, environment, deliverables, and out-of-scope areas.

### 02 – Test Cases

Contains 82 detailed test cases with:

* Test Case ID
* Scenario ID
* Preconditions
* Test Steps
* Test Data
* Expected Result

### 03 – Test Execution

Contains the execution report for the selected test cases, including actual results and pass/fail status.

### 04 – Defect Report

Contains the defect summary and documentation of confirmed defects identified during execution.

### 05 – Smoke Test

Contains a small set of critical test cases used to verify the application's major workflows.

### 06 – Regression Test

Contains test cases that can be re-executed after application changes, bug fixes, or releases.

### 07 – Test Data

Contains representative valid, invalid, duplicate, blank, and product-search test data used during testing.

## Skills Demonstrated

* Manual Testing
* Test Case Design
* Test Scenario Design
* Positive and Negative Testing
* Boundary Value Analysis
* Equivalence Partitioning
* Smoke Testing
* Regression Testing
* End-to-End Testing
* Functional Testing
* UI Validation
* Input Validation
* Test Execution
* Defect Documentation
* Test Data Preparation
* GitHub-based Test Documentation

## Project Structure

```text
nopcommerce-manual-testing/
│
├── 01-Test-Plan/
│   ├── Test_Plan.md
│   └── Test_Scenarios.md
│
├── 02-Test-Cases/
│   └── Test_Cases.md
│
├── 03-Test-Execution/
│   └── Test_Execution_Report.md
│
├── 04-Defect-Report/
│   └── Defect_Report.md
│
├── 05-Smoke-Test/
│   └── Smoke_Test_Suite.md
│
├── 06-Regression-Test/
│   └── Regression_Test_Suite.md
│
├── 07-Test-Data/
│   └── Test_Data.md
│
└── README.md
```

## Conclusion

This project demonstrates a structured manual-testing workflow from test planning and scenario identification through test-case design, execution, defect reporting, smoke testing, and regression-test planning.
