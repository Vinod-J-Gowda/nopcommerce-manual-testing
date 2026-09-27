# nopCommerce Manual Testing Project

## Project Overview

This project demonstrates end-to-end manual testing of the **nopCommerce Demo Store**, an e-commerce web application.

The project covers test planning, test-scenario design, test-case creation, manual execution, defect reporting, smoke testing, regression testing, and end-to-end testing.

**Application:** nopCommerce Demo Store
**Testing Type:** Manual Testing
**Environment:** Web Browser
**Project Status:** Completed

---

## Application Under Test

**nopCommerce Demo Store**

The application provides common e-commerce functionality including:

* User registration and login
* Product search
* Product details
* Wishlist
* Shopping cart
* Customer account management
* Address management
* Checkout
* Payment methods
* Order processing
* Order history
* Order details

---

## Testing Scope

The following functional areas were included in the test design:

* Registration
* Login and Logout
* Product Search
* Categories and Navigation
* Product Details
* Wishlist
* Shopping Cart
* Customer Account
* Address Management
* Checkout
* Payment
* Order Management
* UI and Input Validation

---

## Testing Techniques

The project demonstrates the following manual testing techniques:

* Functional Testing
* Positive Testing
* Negative Testing
* Boundary Value Testing
* Equivalence Partitioning
* UI Testing
* Input Validation Testing
* Smoke Testing
* Regression Testing
* End-to-End Testing

---

## Test Execution Summary

| Metric              | Result |
| ------------------- | -----: |
| Test Cases Designed |     82 |
| Test Cases Executed |     40 |
| Passed              |     39 |
| Failed              |      1 |
| Blocked             |      0 |
| Not Applicable      |      1 |
| Confirmed Defects   |      1 |
| Pass Rate           | 97.50% |

The 82 test cases represent the complete designed test suite. A representative subset was executed to validate the application's major functional areas and demonstrate practical testing techniques.

---

## End-to-End Flow Executed

A complete customer purchase flow was successfully tested:

**Product Search → Product Details → Add to Cart → Saved Address → Shipping → Payment → Order Confirmation → Order History → Order Details**

The order was successfully processed using the **Check / Money Order** payment method.

No real credit/debit card information was used.

---

## Defect Identified

### BUG-001 — Product Image Does Not Respond to Click

During testing of the product details page, clicking the product image produced no response.

| Attribute   | Value                       |
| ----------- | --------------------------- |
| Severity    | Minor                       |
| Priority    | Medium                      |
| Status      | Open                        |
| Test Case   | TC-027                      |
| Defect Type | Functional / UI Interaction |

The defect is documented in the `04-Defect-Report` folder.

The expected behavior should ultimately be confirmed against the application's intended UI specification before treating the issue as a confirmed product defect.

---

## Test Documentation

### Test Plan

Contains the overall testing scope, objectives, entry/exit criteria, testing types, and deliverables.

`01-Test-Plan/Test_Plan.md`

### Test Scenarios

Contains **82 designed test scenarios** covering the application's major functional areas.

`01-Test-Plan/Test_Scenarios.md`

### Test Cases

Contains the detailed master test-case suite corresponding to the designed scenarios.

`02-Test-Cases/Test_Cases.md`

### Test Execution

Contains the execution summary, executed test cases, observations, results, and testing-technique coverage.

`03-Test-Execution/Test_Execution_Report.md`

### Defect Report

Contains the documented defect and reproduction information.

`04-Defect-Report/Defect_Report.md`

### Smoke Testing

Contains the selected critical-path smoke test suite and representative execution.

`05-Smoke-Test/Smoke_Test_Suite.md`

### Regression Testing

Contains the selected regression test suite and representative regression execution.

`06-Regression-Test/Regression_Test_Suite.md`

### Test Data

Contains the test-data approach and examples used during testing.

`07-Test-Data/Test_Data.md`

---

## Skills Demonstrated

* Manual Test Case Design
* Test Scenario Design
* Functional Testing
* Positive and Negative Testing
* Boundary Value Analysis
* Equivalence Partitioning
* UI and Input Validation
* Smoke Testing
* Regression Testing
* End-to-End Testing
* Test Execution
* Defect Identification
* Defect Documentation
* Severity and Priority Classification
* Test Documentation
* GitHub-based QA Documentation

---

## Project Highlights

* Designed an **82-test-case manual testing suite** for an e-commerce application.
* Executed a representative subset of **40 test cases**.
* Recorded **39 passed and 1 failed** test cases.
* Identified and documented **1 observed UI/functional issue**.
* Tested positive, negative, boundary, and equivalence-partition scenarios.
* Performed smoke and regression testing on critical application functionality.
* Successfully executed an end-to-end order flow through order confirmation and order history.
* Maintained structured QA documentation using Markdown and GitHub.

---

## Repository Structure

```text
nopcommerce-manual-testing/
│
├── README.md
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
└── 07-Test-Data/
    └── Test_Data.md
```

---

## Conclusion

This project demonstrates a structured manual QA workflow from **test planning and test-case design through execution, defect reporting, smoke testing, regression testing, and end-to-end validation**.

The project is intended as a practical demonstration of manual testing and QA documentation skills.
