# Test Data – nopCommerce E-Commerce Application

## 1. Purpose

This document contains the test data used to validate different functional and validation scenarios in the nopCommerce manual testing project.

Sensitive or real personal information should not be used during testing. Test accounts and dummy data should be used wherever possible.

## 2. Customer Registration Data

| Data Type          | Example                                  |
| ------------------ | ---------------------------------------- |
| First Name         | Vinod                                    |
| Last Name          | QA                                       |
| Email – Valid      | Test account email used during execution |
| Email – Invalid    | vinod1429gmail.com                       |
| Email – Duplicate  | Previously registered test account email |
| Password – Valid   | Test password used during execution      |
| Password – Invalid | Incorrect test password                  |
| Required Field     | Blank                                    |

## 3. Login Test Data

| Scenario         | Email                 | Password              |
| ---------------- | --------------------- | --------------------- |
| Valid Login      | Registered test email | Correct test password |
| Invalid Password | Registered test email | Incorrect password    |
| Blank Login      | Blank                 | Blank                 |

## 4. Product Search Data

| Scenario             | Search Input        | Expected Use                    |
| -------------------- | ------------------- | ------------------------------- |
| Existing Product     | Apple iPhone        | Verify relevant product results |
| Non-existing Product | xyznonexistent98765 | Verify no-results handling      |

## 5. Shopping Cart Data

| Data               | Value                 |
| ------------------ | --------------------- |
| Product            | Apple iPhone 16 128GB |
| Quantity – Default | 1                     |
| Cart Action        | Add product to cart   |

## 6. Test Data Categories

The project uses the following test-data categories:

* Valid data
* Invalid data
* Duplicate data
* Blank data
* Existing product data
* Non-existing product data
* Boundary and negative test inputs

## 7. Data Handling Note

The examples in this document are dummy testing data. Actual passwords and other sensitive credentials should not be committed to a public GitHub repository.
