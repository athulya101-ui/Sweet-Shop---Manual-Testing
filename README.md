# Sweet-Shop-Manual-Testing
A web-based [sweet shop](https://sweetshop.netlify.app/) application that allows users to browse sweets, manage a shopping basket, log in, and proceed through the checkout and payment workflow.

## Project Overview

This project demonstrates a structured Software Quality Assurance and Testing process for the Sweet Shop web application.The project covers functional testing of the main application modules, preparation of detailed test cases, test execution, defect identification, validation of business logic, UI and security testing, and end-to-end testing of the shopping and checkout workflow.

## My Role

### Manual Tester / QA Tester

* Prepared and executed test cases covering the major Sweet Shop application modules.
* Tested Home, About, Sweets, Login, Basket, and Checkout functionalities.
* Performed Functional, Positive/Negative, UI, Validation, Security, Navigation, Non-functional, and Business Logic Testing.
* Verified navigation flow across the application.
* Validated product listing, product selection, and add-to-basket functionality.
* Tested login fields and invalid credential behavior.
* Verified basket contents, pricing, and checkout navigation.
* Tested billing address and payment field validations.
* Tested promo code functionality and discount application.
* Verified shipping charges and order pricing calculations.
* Identified, documented, and analyzed defects during test execution.
* Tested the application using Google Chrome, Firefox, Microsoft Edge, and Mobile.
* Performed end-to-end testing from product selection through checkout and payment.
* Evaluated security-related behavior of payment fields, including card number and CVV masking.
* Prepared the Test Summary Report and documented risks, observations, defects, and recommendations.
## Tools & Technologies
* Web Application Testing
* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Mobile Browser
* Functional Testing
* UI Testing
* Validation Testing
* Security Testing
* Navigation Testing
* Business Logic Testing
* Non-functional Testing
## Testing Scope

The testing scope includes the following major areas:

### Home
* Navigation between application pages
* Responsive page loading
* Access to Home, About, Sweets, Login, and Basket
### Login
* Email and password fields
* Login functionality
* Validation of invalid credentials
### About
* Static informational content
* Page layout and loading
### Sweets
* Display of available sweets
* Product images, names, and prices
* Add products to the basket
### Basket
* Display of selected products
* Display of item pricing and totals
* Basket-to-checkout navigation
### Checkout
* Billing information
* First Name
* Last Name
* Email
* Address
* Country
* City
* Zip Code
* Promo code functionality
* Payment information
* Name on Card
* Credit Card Number
* Expiration Date
* CVV
* Checkout submission
## Testing Types

The application was tested using multiple testing approaches:

* Functional Testing
* Positive Testing
* Negative Testing
* UI Testing
* Validation Testing
* Security Testing
* Navigation Testing
* Business Logic Testing
* Non-functional Testing
* End-to-End Testing
* Regression Testing
## Test Results

A total of 89 test cases were designed and executed.

|Result |	Count|
|--------|------|
|Total Test Cases |	89 |
|Passed |	66 |
| Failed |	23   |
|Blocked / Not Executed	| 0|

The test report identifies 23 defects across the application.
## Project Deliverables

* [Test Plan](https://docs.google.com/document/d/1WQDarkYXrhTWEgcQMx9LZFfBJx2koTX4GDm1bUw7qBA/edit?usp=sharing)
* [Manual Test Cases](https://docs.google.com/spreadsheets/d/1i4O1X64A5p2Qk9GVRBKw_UyjtwrtVREMZkOxY4k3qFY/edit?gid=0#gid=0)
* [Bug Report](https://docs.google.com/spreadsheets/d/1i4O1X64A5p2Qk9GVRBKw_UyjtwrtVREMZkOxY4k3qFY/edit?usp=sharing)
* [Test Execution Report](https://docs.google.com/spreadsheets/d/1i4O1X64A5p2Qk9GVRBKw_UyjtwrtVREMZkOxY4k3qFY/edit?gid=0#gid=0)
* [Test Summary Report](https://docs.google.com/document/d/1TQCx_ZoD4861FaMLw90slfovu3yd4EhnTNF9bEmw5RU/edit?usp=sharing)


## Key Highlights
* 89 test cases were designed and executed, with 66 passed and 23 failed.
* Navigation across the Home, About, and Sweets pages passed successfully.
* Product display and add-to-basket functionality were partially successful.
* The Login module contains validation defects where invalid email and password combinations can still allow access.
* The Basket module displays selected items and totals, but quantity increase/decrease functionality is unavailable.
* The Checkout module contains multiple validation issues involving billing and payment fields.
* The Promo Code functionality refreshes the page but does not apply the expected discount.
* Shipping charges may be calculated incorrectly.
* Payment fields allow invalid card information and do not adequately validate expiration dates and CVV values.
* Card number and CVV are not masked, creating a security concern.
* Clicking Continue to Checkout refreshes the page instead of completing the payment flow or redirecting to a confirmation/payment gateway.
* The application is currently partially functional, with significant defects affecting login validation, basket quantity management, checkout validation, payment security, pricing, and payment processing.
## End-to-End Workflow

Application Launch → Home → Sweets → Product Selection → Add to Basket → Basket → Checkout → Billing Details → Promo Code → Payment Details → Continue to Checkout → Payment Processing / Confirmation

The end-to-end workflow can be followed through product selection and checkout, but the final payment-processing stage is currently affected by the identified defects.

## Risks Identified

The major risks identified during testing include:

* Unauthorized access due to weak login validation.
* Failed transactions due to non-functional payment processing.
* Security vulnerabilities caused by unmasked payment fields.
* Incorrect order totals due to shipping and promotional-code logic.
* Poor user experience due to missing validation and error messages.
## Project Status

Overall Result: Pass with Defects

The Sweet Shop application supports basic navigation, product browsing, basket functionality, and checkout data entry. However, several important defects remain in login validation, basket quantity management, checkout validations, pricing and promo-code logic, payment-field security, and payment processing.Further defect fixing followed by full regression testing is recommended before considering the application production-ready.Testing confirmed that the application's core navigation and product browsing functionality are available, while several defects remain in critical areas such as authentication, basket quantity management, checkout validation, pricing, payment security, and payment processing.
