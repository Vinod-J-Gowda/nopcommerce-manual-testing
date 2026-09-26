# Test Execution Report

## Project

nopCommerce Manual Testing Project

## Application

nopCommerce Demo Store

## Execution Summary

| Metric                    | Result |
| ------------------------- | -----: |
| Total Test Cases Designed |     82 |
| Test Cases Executed       |     15 |
| Passed                    |     14 |
| Failed                    |      1 |
| Blocked                   |      0 |
| Pass Rate                 | 93.33% |
| Confirmed Defects         |      1 |

## Test Environment

* Application: nopCommerce Demo Store
* Testing Type: Manual Testing
* Browser: Web Browser
* Environment: Demo/Test Environment

## Executed Test Cases

| Test Case ID | Test Case                           | Result | Actual Result                                                                                     |
| ------------ | ----------------------------------- | ------ | ------------------------------------------------------------------------------------------------- |
| TC-001       | Valid User Registration             | PASS   | Registration completed successfully                                                               |
| TC-003       | Duplicate Email Registration        | PASS   | Existing email was rejected                                                                       |
| TC-004       | Invalid Email Validation            | PASS   | "Please enter a valid email address." was displayed                                               |
| TC-005       | Blank Mandatory Registration Fields | PASS   | Mandatory field validation was displayed                                                          |
| TC-008       | Valid Login                         | PASS   | User logged in successfully                                                                       |
| TC-009       | Incorrect Password                  | PASS   | Incorrect-password error was displayed and login was rejected                                     |
| TC-011       | Blank Login Fields                  | PASS   | Email validation message was displayed                                                            |
| TC-015       | Search Existing Product             | PASS   | Apple iPhone 16 128GB was displayed                                                               |
| TC-017       | Search Non-Existing Product         | PASS   | "No products were found that matched your criteria." was displayed                                |
| TC-037       | Add Product to Cart                 | PASS   | Product was successfully added to cart                                                            |
| TC-038       | Update Product Quantity             | PASS   | Quantity was successfully changed from 1 to 2                                                     |
| TC-040       | Remove Product from Cart            | PASS   | Product was removed and cart displayed "Your Shopping Cart is empty!"                             |
| TC-053       | Checkout Flow / Payment Validation  | PASS   | Checkout progressed through address, shipping and payment steps; invalid card number was rejected |
| TC-026       | Product Details                     | PASS   | Product name, image, price, add-to-cart and wishlist options were displayed                       |
| TC-027       | Product Image Interaction           | FAIL   | Clicking the product image produced no response                                                   |

## Defect Summary

| Defect ID | Test Case | Description                             | Severity | Status |
| --------- | --------- | --------------------------------------- | -------- | ------ |
| BUG-001   | TC-027    | Product image does not respond to click | Minor    | Open   |

## Execution Observations

* Registration and login validations behaved as expected for the executed scenarios.
* Product search handled both existing and non-existing search terms correctly.
* Shopping cart addition, quantity update and product removal worked as expected.
* Checkout progressed through billing address, shipping method and payment method selection.
* Invalid credit card information was rejected with an appropriate validation message.
* A usability/functional issue was observed with product image interaction.

## Pass Rate Calculation

**Pass Rate = (Passed Test Cases / Executed Test Cases) × 100**

**Pass Rate = (14 / 15) × 100 = 93.33%**

## Execution Status

The current execution cycle is **In Progress**.

A total of **15 test cases have been executed**, with **14 passed and 1 failed**. One confirmed defect has been documented separately as **BUG-001**.

The remaining test cases are designed but have not yet been executed.
