# Regression Test Suite – nopCommerce E-Commerce Application

## 1. Objective

The regression test suite contains previously defined functional test cases that should be re-executed after application changes, bug fixes, or new feature releases to verify that existing functionality continues to work as expected.

## 2. Regression Test Cases

| Test Case ID | Regression Test                            | Expected Result                                     |
| ------------ | ------------------------------------------ | --------------------------------------------------- |
| TC-001       | Register a new customer with valid details | Customer should be registered successfully          |
| TC-008       | Login with valid credentials               | Customer should be logged in successfully           |
| TC-009       | Login with an incorrect password           | Login should be rejected with an appropriate error  |
| TC-015       | Search for an existing product             | Relevant product should be displayed                |
| TC-017       | Search for a non-existing product          | Appropriate no-results message should be displayed  |
| TC-026       | Open a product details page                | Product information should be displayed correctly   |
| TC-037       | Add a product to the shopping cart         | Product should be added successfully                |
| TC-038       | Update product quantity in cart            | Cart quantity and total should be updated correctly |
| TC-040       | Remove a product from cart                 | Product should be removed successfully              |
| TC-053       | Proceed to checkout with a product in cart | Checkout process should be accessible               |
| TC-063       | Access order history                       | Customer should be able to view order history       |

## 3. When to Execute Regression Testing

Regression testing should be performed after:

* Bug fixes
* New feature implementation
* Changes to existing functionality
* Application configuration changes
* Major releases or deployments

## 4. Regression Testing Approach

The regression suite should prioritize critical business workflows and functionality that may be affected by application changes.

The scope of regression testing can be expanded or reduced depending on the nature and impact of the change.

## 5. Coverage

The regression suite covers:

* Customer registration
* Authentication
* Input validation
* Product search
* Product details
* Shopping cart
* Checkout
* Order management

## 6. Execution Status

The regression suite has been designed as part of the manual testing project.

Selected test cases from the regression suite were executed during the current test execution cycle. Detailed execution results are documented in the Test Execution Report.
