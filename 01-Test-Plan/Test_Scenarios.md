# Test Scenarios – nopCommerce E-Commerce Application

## 1. Registration

| ID    | Scenario                                                             | Type     | Priority |
| ----- | -------------------------------------------------------------------- | -------- | -------- |
| TS-01 | Verify that a new customer can register with valid mandatory details | Positive | High     |
| TS-02 | Verify registration with valid optional details                      | Positive | Medium   |
| TS-03 | Verify registration with an already registered email address         | Negative | High     |
| TS-04 | Verify validation for invalid email format                           | Negative | High     |
| TS-05 | Verify validation when mandatory registration fields are blank       | Negative | High     |
| TS-06 | Verify password and confirm-password mismatch validation             | Negative | High     |
| TS-07 | Verify password requirements and boundary conditions                 | Boundary | Medium   |

## 2. Login and Logout

| ID    | Scenario                                       | Type       | Priority |
| ----- | ---------------------------------------------- | ---------- | -------- |
| TS-08 | Verify login with valid registered credentials | Positive   | Critical |
| TS-09 | Verify login with an invalid password          | Negative   | High     |
| TS-10 | Verify login with an unregistered email        | Negative   | High     |
| TS-11 | Verify login with blank credentials            | Negative   | High     |
| TS-12 | Verify email format validation during login    | Negative   | Medium   |
| TS-13 | Verify Remember Me functionality               | Functional | Medium   |
| TS-14 | Verify successful logout and session behavior  | Functional | Critical |

## 3. Product Search

| ID    | Scenario                                                 | Type       | Priority |
| ----- | -------------------------------------------------------- | ---------- | -------- |
| TS-15 | Verify search using an existing product name             | Positive   | High     |
| TS-16 | Verify search using partial product name                 | Positive   | High     |
| TS-17 | Verify search using a non-existing product               | Negative   | Medium   |
| TS-18 | Verify search with blank input                           | Negative   | Medium   |
| TS-19 | Verify search using special characters                   | Negative   | Medium   |
| TS-20 | Verify search results are relevant to the search keyword | Functional | High     |

## 4. Categories and Navigation

| ID    | Scenario                                              | Type          | Priority |
| ----- | ----------------------------------------------------- | ------------- | -------- |
| TS-21 | Verify navigation to product categories               | Functional    | High     |
| TS-22 | Verify products displayed under the selected category | Functional    | High     |
| TS-23 | Verify navigation through main menu links             | Functional    | High     |
| TS-24 | Verify breadcrumb navigation                          | UI/Functional | Medium   |
| TS-25 | Verify navigation back to the home page               | Functional    | Medium   |

## 5. Product Details

| ID    | Scenario                                                               | Type       | Priority |
| ----- | ---------------------------------------------------------------------- | ---------- | -------- |
| TS-26 | Verify product name, image, and description are displayed correctly    | UI         | High     |
| TS-27 | Verify product price is displayed correctly                            | Functional | Critical |
| TS-28 | Verify product availability/stock information                          | Functional | High     |
| TS-29 | Verify product can be added to cart from the product page              | Functional | Critical |
| TS-30 | Verify product can be added to wishlist                                | Functional | High     |
| TS-31 | Verify product details remain consistent when navigating between pages | Functional | Medium   |

## 6. Wishlist

| ID    | Scenario                                                   | Type                | Priority |
| ----- | ---------------------------------------------------------- | ------------------- | -------- |
| TS-32 | Verify a product can be added to wishlist                  | Positive            | High     |
| TS-33 | Verify wishlist displays the added product                 | Functional          | High     |
| TS-34 | Verify a product can be removed from wishlist              | Functional          | Medium   |
| TS-35 | Verify wishlist behavior for logged-out users              | Negative/Functional | Medium   |
| TS-36 | Verify wishlist state is retained for a logged-in customer | Functional          | Medium   |

## 7. Shopping Cart

| ID    | Scenario                                                                  | Type       | Priority |
| ----- | ------------------------------------------------------------------------- | ---------- | -------- |
| TS-37 | Verify a product can be added to the shopping cart                        | Positive   | Critical |
| TS-38 | Verify multiple different products can be added to the cart               | Functional | Critical |
| TS-39 | Verify cart quantity can be increased                                     | Functional | Critical |
| TS-40 | Verify cart quantity can be decreased                                     | Functional | High     |
| TS-41 | Verify cart quantity boundary values                                      | Boundary   | High     |
| TS-42 | Verify product can be removed from the cart                               | Functional | High     |
| TS-43 | Verify product price and quantity are reflected correctly in the subtotal | Functional | Critical |
| TS-44 | Verify cart total is recalculated after quantity changes                  | Functional | Critical |
| TS-45 | Verify cart contents are retained during normal navigation                | Functional | Medium   |

## 8. Customer Account and Address

| ID    | Scenario                                                | Type       | Priority |
| ----- | ------------------------------------------------------- | ---------- | -------- |
| TS-46 | Verify customer can access the My Account page          | Functional | High     |
| TS-47 | Verify customer profile information can be viewed       | Functional | Medium   |
| TS-48 | Verify customer can add a new address                   | Positive   | High     |
| TS-49 | Verify mandatory address fields are validated           | Negative   | High     |
| TS-50 | Verify invalid address information is handled correctly | Negative   | High     |
| TS-51 | Verify an existing address can be edited                | Functional | Medium   |
| TS-52 | Verify an existing address can be deleted               | Functional | Medium   |

## 9. Checkout

| ID    | Scenario                                                                    | Type       | Priority |
| ----- | --------------------------------------------------------------------------- | ---------- | -------- |
| TS-53 | Verify checkout can be initiated with products in the cart                  | Functional | Critical |
| TS-54 | Verify checkout for a registered customer                                   | Positive   | Critical |
| TS-55 | Verify required billing/shipping information validation                     | Negative   | Critical |
| TS-56 | Verify valid billing/shipping information is accepted                       | Positive   | Critical |
| TS-57 | Verify shipping method selection                                            | Functional | High     |
| TS-58 | Verify payment method selection                                             | Functional | Critical |
| TS-59 | Verify order summary before order placement                                 | Functional | Critical |
| TS-60 | Verify checkout totals match cart and selected charges                      | Functional | Critical |
| TS-61 | Verify order placement with valid checkout information                      | Positive   | Critical |
| TS-62 | Verify checkout behavior when required information is invalid or incomplete | Negative   | Critical |

## 10. Order Management

| ID    | Scenario                                                                   | Type          | Priority |
| ----- | -------------------------------------------------------------------------- | ------------- | -------- |
| TS-63 | Verify successful order confirmation after order placement                 | Functional    | Critical |
| TS-64 | Verify order number/details are displayed correctly                        | Functional    | High     |
| TS-65 | Verify placed order appears in order history                               | Functional    | High     |
| TS-66 | Verify order details can be viewed from order history                      | Functional    | High     |
| TS-67 | Verify order information matches the information submitted during checkout | Functional    | High     |
| TS-68 | Verify customer can navigate between order history and account pages       | UI/Functional | Medium   |

## 11. UI and Input Validation

| ID    | Scenario                                                                        | Type          | Priority |
| ----- | ------------------------------------------------------------------------------- | ------------- | -------- |
| TS-69 | Verify mandatory fields display appropriate validation messages                 | Validation    | High     |
| TS-70 | Verify fields reject inappropriate input formats where applicable               | Negative      | High     |
| TS-71 | Verify fields handle minimum and maximum input lengths appropriately            | Boundary      | Medium   |
| TS-72 | Verify buttons and links are visible and usable                                 | UI            | Medium   |
| TS-73 | Verify page layout and major UI elements remain consistent across workflows     | UI            | Medium   |
| TS-74 | Verify validation/error messages are understandable and displayed appropriately | UI/Validation | High     |

## 12. Smoke, Regression and End-to-End

| ID    | Scenario                                                                                        | Type           | Priority |
| ----- | ----------------------------------------------------------------------------------------------- | -------------- | -------- |
| TS-75 | Verify application loads successfully and major navigation is accessible                        | Smoke          | Critical |
| TS-76 | Verify customer can log in and access account functionality                                     | Smoke          | Critical |
| TS-77 | Verify customer can search for and view a product                                               | Smoke          | Critical |
| TS-78 | Verify customer can add a product to cart and proceed to checkout                               | Smoke          | Critical |
| TS-79 | Verify customer can complete the complete purchase workflow                                     | End-to-End     | Critical |
| TS-80 | Verify cart, checkout, and order information remain consistent throughout the purchase workflow | End-to-End     | Critical |
| TS-81 | Execute critical functional cases after application changes to identify regressions             | Regression     | Critical |
| TS-82 | Verify the core customer journey remains functional after regression testing                    | Regression/E2E | Critical |

## Scenario Coverage Summary

| Module                     | Scenarios |
| -------------------------- | --------: |
| Registration               |         7 |
| Login / Logout             |         7 |
| Search                     |         6 |
| Categories & Navigation    |         5 |
| Product Details            |         6 |
| Wishlist                   |         5 |
| Shopping Cart              |         9 |
| Customer Account & Address |         7 |
| Checkout                   |        10 |
| Order Management           |         6 |
| UI & Validation            |         6 |
| Smoke / Regression / E2E   |         8 |
| **Total**                  |    **82** |
