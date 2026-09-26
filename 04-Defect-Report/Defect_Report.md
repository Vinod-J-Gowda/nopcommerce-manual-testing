# Defect Report

## Project

nopCommerce Manual Testing Project

## Application

nopCommerce Demo Store

## Defect Summary

| Field        | Details                                 |
| ------------ | --------------------------------------- |
| Defect ID    | BUG-001                                 |
| Test Case ID | TC-027                                  |
| Module       | Product Details                         |
| Title        | Product image does not respond to click |
| Severity     | Minor                                   |
| Priority     | Medium                                  |
| Status       | Open                                    |
| Environment  | Web application / Browser               |
| Test Type    | Functional / UI                         |
| Reported By  | QA Tester                               |

## Defect Description

The product image on the product details page does not respond when clicked.

## Preconditions

* User is on the product details page.
* A product with a displayed product image is available.

## Steps to Reproduce

1. Open the nopCommerce Demo Store.
2. Search for `Apple iPhone 16 128GB`.
3. Open the product details page.
4. Click on the displayed product image.

## Expected Result

The product image should provide an appropriate response when clicked, such as opening an enlarged image, gallery, or other supported image interaction.

## Actual Result

Clicking the product image produces no response.

## Severity Rationale

**Minor:** The issue does not prevent the user from viewing product information or purchasing the product, but it affects expected image interaction/usability.

## Current Status

**Open** — Defect observed during manual execution and requires further review.

## Execution Evidence

This defect was identified while executing **TC-027 — Product Image** during the manual testing cycle.

## Notes

Only defects actually observed during execution are recorded in this report. No defects are claimed for test cases that have not been executed.
