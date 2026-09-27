# Test Execution Report

## 1. Project Information

| Field            | Details                            |
| ---------------- | ---------------------------------- |
| Application      | nopCommerce Demo Store             |
| Application Type | E-commerce Web Application         |
| Testing Type     | Manual Testing                     |
| Environment      | Web Browser                        |
| Test Suite       | 82 designed test cases             |
| Execution Status | Representative execution completed |
| Defect Status    | 1 confirmed defect                 |

---

## 2. Execution Summary

| Metric                    | Result |
| ------------------------- | -----: |
| Total Test Cases Designed |     82 |
| Test Cases Executed       |     40 |
| Passed                    |     39 |
| Failed                    |      1 |
| Blocked                   |      0 |
| Not Applicable            |      1 |
| Confirmed Defects         |      1 |
| Pass Rate                 | 97.50% |

**Note:** The 82 test cases represent the complete designed test suite. A representative subset was executed to validate the major functional areas and testing techniques rather than executing every designed case.

---

## 3. Executed Test Cases

| Test Case ID | Scenario                            | Result | Observation                                                                    |
| ------------ | ----------------------------------- | ------ | ------------------------------------------------------------------------------ |
| TC-001       | Valid user registration             | PASS   | Registration completed successfully                                            |
| TC-003       | Duplicate email registration        | PASS   | Application prevented registration with an existing email                      |
| TC-004       | Invalid email format                | PASS   | Validation message displayed for invalid email                                 |
| TC-005       | Blank mandatory registration fields | PASS   | Required-field validation displayed                                            |
| TC-008       | Valid login                         | PASS   | User logged in successfully                                                    |
| TC-009       | Incorrect password                  | PASS   | Login rejected and incorrect-password validation displayed                     |
| TC-011       | Blank login fields                  | PASS   | Required email validation displayed                                            |
| TC-015       | Search for existing product         | PASS   | Existing product was returned                                                  |
| TC-017       | Search for non-existing product     | PASS   | No-products-found message displayed                                            |
| TC-026       | Product details verification        | PASS   | Product name, image, price, description and actions displayed                  |
| TC-027       | Product image interaction           | FAIL   | Clicking the product image produced no response                                |
| TC-028       | Product price verification          | PASS   | Product price displayed correctly                                              |
| TC-029       | Add product to wishlist             | PASS   | Product added successfully                                                     |
| TC-030       | Verify wishlist item                | PASS   | Product appeared in wishlist                                                   |
| TC-031       | Remove product from wishlist        | PASS   | Product removed successfully                                                   |
| TC-032       | Wishlist persistence                | PASS   | Wishlist state remained correct after refresh                                  |
| TC-033       | Add multiple products to wishlist   | PASS   | Multiple products appeared in wishlist                                         |
| TC-034       | Remove one wishlist item            | PASS   | Selected item removed while remaining items stayed                             |
| TC-035       | Move wishlist products to cart      | PASS   | Selected wishlist products were added to cart                                  |
| TC-037       | Add product to cart                 | PASS   | Product added successfully                                                     |
| TC-038       | Update cart quantity                | PASS   | Quantity and cart total updated correctly                                      |
| TC-040       | Remove product from cart            | PASS   | Product was removed and empty-cart message displayed                           |
| TC-041       | Cart price calculation              | PASS   | Unit price, quantity and total were consistent                                 |
| TC-042       | Cart quantity update                | PASS   | Quantity and price updated correctly                                           |
| TC-043       | Cart quantity boundary              | PASS   | Quantity of zero removed the product and cart totals updated                   |
| TC-044       | Invalid cart quantity               | PASS   | Application displayed quantity validation                                      |
| TC-045       | Empty cart state                    | PASS   | Empty-cart message displayed                                                   |
| TC-046       | Customer information                | PASS   | Customer information fields displayed                                          |
| TC-047       | Update customer information         | PASS   | Customer information update succeeded                                          |
| TC-048       | Verify updated customer information | PASS   | Updated information persisted after refresh                                    |
| TC-049       | Change password validation          | PASS   | Required-field validation displayed                                            |
| TC-050       | Password mismatch validation        | PASS   | Password mismatch validation displayed                                         |
| TC-051       | Address book empty state            | PASS   | Empty address-book state displayed                                             |
| TC-052       | Add new address                     | PASS   | New address was added successfully                                             |
| TC-053       | Checkout/payment validation         | PASS   | Checkout and payment validation flow worked without using real payment details |
| TC-054       | Checkout using saved address        | PASS   | Saved address was available and accepted during checkout                       |
| TC-056       | Check/Money Order payment flow      | PASS   | Payment instructions displayed correctly                                       |
| TC-057       | Order confirmation                  | PASS   | Order was successfully processed and order number generated                    |
| TC-063       | Verify order in order history       | PASS   | Created order appeared in order history                                        |
| TC-064       | Verify order details                | PASS   | Order details, payment, shipping and totals were displayed correctly           |

---

## 4. Additional Testing Technique Coverage

The execution also demonstrated the following testing techniques:

### Equivalence Partitioning

A valid and invalid search-input partition were considered.

* Valid partition: `computer`
* Invalid partition: previously tested non-existing search keyword
* Valid input returned an applicable product.
* Invalid input returned the no-products-found message.

### UI / Validation Testing

The First Name field in Customer Info was cleared and the form was submitted.

**Actual result:** `First name is required.`

**Result:** PASS

### Smoke Testing

A representative critical-path smoke flow was executed:

**Home → Search → Product Details → Add to Cart**

All steps completed successfully.

### Regression Testing

A previously tested cart quantity function was re-tested:

**Quantity 1 → Quantity 2 → Cart updated**

The existing functionality continued to work successfully.

### End-to-End Testing

A complete customer purchase flow was successfully executed using the test account:

**Product → Cart → Saved Address → Shipping → Payment → Order Confirmation → Order History → Order Details**

---

## 5. Failed Test Case

### TC-027 — Product Image Interaction

**Result:** FAIL

The product image did not respond when clicked.

A defect was documented as:

**BUG-001 — Product image does not respond to click**

Refer to the `04-Defect-Report` folder for details.

---

## 6. Checkout Execution Note

Checkout was tested through order confirmation using the **Check / Money Order** payment method.

No real credit/debit card information was entered.

Credit-card validation was also tested separately using invalid test data, resulting in the expected card-number validation.

---

## 7. Test Execution Conclusion

The representative execution validated the major functional areas of the nopCommerce application, including:

* Registration
* Login
* Search
* Product details
* Wishlist
* Shopping cart
* Customer information
* Address management
* Checkout
* Payment method handling
* Order confirmation
* Order history
* Order details

The project also demonstrates practical use of positive, negative, boundary, equivalence partitioning, UI validation, smoke, regression and end-to-end testing techniques.

The test execution phase is considered **complete for the portfolio project**. The remaining designed test cases were retained as part of the master test suite and were not claimed as executed.
