# Smoke Test Suite

## 1. Objective

The purpose of the smoke test suite is to quickly verify that the application's critical functionality is operational before performing deeper testing.

The smoke suite focuses on basic, business-critical user flows rather than exhaustive functional coverage.

---

## 2. Application

**Application:** nopCommerce Demo Store

**Testing Type:** Manual Smoke Testing

**Environment:** Web Browser

---

## 3. Smoke Test Cases

| Test Case | Test Area          | Test Objective                                      | Result |
| --------- | ------------------ | --------------------------------------------------- | ------ |
| TC-001    | Registration       | Verify that a user can register successfully        | PASS   |
| TC-008    | Login              | Verify that a registered user can log in            | PASS   |
| TC-015    | Search             | Verify that an existing product can be searched     | PASS   |
| TC-026    | Product Details    | Verify that product details can be accessed         | PASS   |
| TC-037    | Shopping Cart      | Verify that a product can be added to the cart      | PASS   |
| TC-053    | Checkout           | Verify that the checkout/payment flow is accessible | PASS   |
| TC-057    | Order Confirmation | Verify that an order can be successfully processed  | PASS   |

---

## 4. Representative Smoke Execution

A critical-path smoke flow was executed during the final testing cycle:

**Home Page → Search → Product Details → Add to Cart**

### Execution Results

| Step                        | Result |
| --------------------------- | ------ |
| Search for existing product | PASS   |
| Open product details        | PASS   |
| Add product to cart         | PASS   |

The critical path completed successfully.

---

## 5. Smoke Testing Approach

Smoke testing was used to verify that major application functionality was operational before deeper testing activities.

The selected areas covered:

* User access
* Product search
* Product navigation
* Shopping cart
* Checkout
* Order processing

---

## 6. Expected Outcome

The application should allow the user to perform the basic critical workflows without encountering blocking failures.

The representative smoke execution completed successfully.

---

## 7. Conclusion

The nopCommerce demo application passed the representative smoke test flow used in this project.

The smoke suite is maintained separately from the full master test suite so that these critical checks can be quickly repeated after a new build or significant application change.
