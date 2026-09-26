# Test Execution Report – nopCommerce E-Commerce Application

## 1. Execution Summary

| Metric                    | Result |
| ------------------------- | -----: |
| Total Test Cases Designed |     82 |
| Test Cases Executed       |     10 |
| Passed                    |     10 |
| Failed                    |      0 |
| Blocked                   |      0 |
| Pass Rate                 |   100% |

## 2. Test Environment

**Application:** nopCommerce Demo Store
**Application Type:** E-Commerce Web Application
**Testing Type:** Manual Testing
**Execution Status:** Completed for selected representative test cases

## 3. Executed Test Cases

| Test Case ID | Test Description                                | Expected Result                                         | Actual Result                                                      | Status |
| ------------ | ----------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------------ | ------ |
| TC-001       | Register with valid details                     | User should be registered successfully                  | Registration completed successfully                                | PASS   |
| TC-003       | Register using an already registered email      | Application should prevent duplicate email registration | Existing email was not available for registration                  | PASS   |
| TC-004       | Register using invalid email format             | Application should display email validation error       | "Please enter a valid email address." was displayed                | PASS   |
| TC-005       | Submit registration with mandatory fields blank | Application should display mandatory-field validation   | "Last name is required." was displayed                             | PASS   |
| TC-008       | Login with valid credentials                    | User should be logged in successfully                   | Login completed successfully                                       | PASS   |
| TC-009       | Login with incorrect password                   | Application should reject login and display an error    | Incorrect-password error was displayed and login was rejected      | PASS   |
| TC-011       | Login with blank credentials                    | Application should display required-field validation    | "Please enter your email" was displayed                            | PASS   |
| TC-015       | Search for an existing product                  | Relevant product should be displayed                    | "Apple iPhone 16 128GB" was displayed                              | PASS   |
| TC-017       | Search for a non-existing product               | Application should indicate that no products were found | "No products were found that matched your criteria." was displayed | PASS   |
| TC-037       | Add a product to the shopping cart              | Selected product should be added to cart                | Apple iPhone 16 128GB was successfully added to the cart           | PASS   |

## 4. Test Execution Observations

* Valid registration and login workflows were successfully completed.
* Duplicate email registration was prevented.
* Email and mandatory-field validations were observed during negative testing.
* Invalid login credentials were rejected with an appropriate error message.
* Product search returned a relevant result for an existing product.
* Search with a non-existing product returned an appropriate no-results message.
* Product addition to the shopping cart was successfully verified.

## 5. Defect Summary

No confirmed defects were identified during the execution of the selected 10 test cases.

## 6. Conclusion

The selected representative test cases covering registration, authentication, input validation, product search, and shopping-cart functionality were executed successfully.

All 10 executed test cases passed. The remaining test cases in the project are documented as part of the planned test suite but were not executed during this execution cycle.
