# Regression Test Suite

## 1. Objective

The purpose of the regression test suite is to verify that previously working functionality continues to operate correctly after changes, updates, or other testing activities.

This suite contains selected high-value test cases from the master test suite.

---

## 2. Application

**Application:** nopCommerce Demo Store

**Testing Type:** Manual Regression Testing

**Environment:** Web Browser

---

## 3. Regression Test Cases

| Test Case | Test Area        | Test Objective                                  | Result |
| --------- | ---------------- | ----------------------------------------------- | ------ |
| TC-001    | Registration     | Verify that user registration continues to work | PASS   |
| TC-008    | Login            | Verify that valid login continues to work       | PASS   |
| TC-009    | Login Validation | Verify incorrect-password handling              | PASS   |
| TC-015    | Search           | Verify product search continues to work         | PASS   |
| TC-026    | Product Details  | Verify product details remain accessible        | PASS   |
| TC-037    | Shopping Cart    | Verify products can be added to cart            | PASS   |
| TC-038    | Cart Quantity    | Verify cart quantity can be updated             | PASS   |
| TC-040    | Cart Removal     | Verify products can be removed from cart        | PASS   |
| TC-053    | Checkout         | Verify checkout flow remains accessible         | PASS   |
| TC-057    | Order Processing | Verify an order can be successfully processed   | PASS   |
| TC-063    | Order History    | Verify processed orders appear in order history | PASS   |
| TC-064    | Order Details    | Verify order details remain accessible          | PASS   |

---

## 4. Representative Regression Execution

A previously tested cart functionality was re-tested during the final testing cycle.

### Test

**Cart Quantity Update**

### Initial State

* Product: Apple iPhone 16 128GB
* Quantity: 1

### Action

The quantity was increased from **1 to 2** and the cart was updated.

### Result

The cart successfully reflected the updated quantity and corresponding price.

**Regression Result: PASS**

---

## 5. Regression Testing Approach

Regression testing in this project focuses on rechecking important existing functionality after other testing activities have been performed.

Selected regression areas include:

* Registration
* Login
* Search
* Product details
* Shopping cart
* Checkout
* Order processing
* Order history
* Order details

---

## 6. Expected Outcome

Previously working functionality should continue to operate correctly without introducing new failures.

The representative regression test completed successfully.

---

## 7. Conclusion

The selected regression test cases provide repeatable coverage of critical e-commerce functionality.

The representative cart regression test passed successfully, demonstrating that previously verified functionality continued to work during the testing cycle.
