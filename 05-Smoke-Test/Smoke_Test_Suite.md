# Smoke Test Suite – nopCommerce E-Commerce Application

## 1. Objective

The smoke test suite contains a small set of critical test cases used to verify that the major application workflows are functioning and that the application is stable enough for further testing.

## 2. Smoke Test Cases

| Test Case ID | Smoke Test                                           | Expected Result                                 |
| ------------ | ---------------------------------------------------- | ----------------------------------------------- |
| TC-001       | Register a new customer with valid details           | Customer should be registered successfully      |
| TC-008       | Login with valid credentials                         | Customer should be logged in successfully       |
| TC-015       | Search for an existing product                       | Relevant product should be displayed            |
| TC-026       | Open a product details page                          | Product details should be displayed correctly   |
| TC-037       | Add a product to the shopping cart                   | Product should be added to the cart             |
| TC-053       | Proceed to checkout with a cart containing a product | Checkout process should be accessible           |
| TC-063       | View order history                                   | Customer should be able to access order history |

## 3. Execution Strategy

Smoke testing should be performed after a new build or significant deployment to confirm that the application's critical workflows are operational.

If a critical smoke test fails, further detailed testing may be postponed until the underlying issue is investigated.

## 4. Coverage

The smoke suite provides basic coverage of:

* Customer registration
* Authentication
* Product search
* Product details
* Shopping cart
* Checkout
* Order management

## 5. Execution Status

The smoke suite has been designed as part of the manual testing project. The listed cases are included in the broader test case repository.

Selected cases from this suite were executed during the current test execution cycle.
