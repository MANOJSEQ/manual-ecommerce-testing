# DemoBlaze Customer Journey Test Cases

| Test ID | Requirement | Test Scenario | Test Type | Priority | Expected Result | Status |
|---|---|---|---|---|---|---|
| TC-01 | RQ-01 | Open the homepage | Positive | High | Products and categories are displayed | Pass |
| TC-02 | RQ-01 | Select the Laptops category | Positive | Medium | Only laptop products are displayed | Pass |
| TC-03 | RQ-02 | Open a product details page | Positive | High | Product name, price, description and Add to cart button appear | Pass |
| TC-04 | RQ-03 | Sign up with a unique username and password | Positive | High | Account is created successfully | Pass |
| TC-05 | RQ-03 | Sign up using an existing username | Negative | Medium | A duplicate-user error is displayed | Pass |
| TC-06 | RQ-04 | Log in with valid credentials | Positive | High | Customer is logged in and username is displayed | Pass |
| TC-07 | RQ-04 | Log in with an incorrect password | Negative | High | Login is rejected with a helpful error | Pass |
| TC-08 | RQ-05 | Add one product to the cart | Positive | High | The selected product appears in the cart | Pass |
| TC-09 | RQ-05 | Add two products and verify the total | Positive | High | Cart total equals the sum of both product prices | Pass |
| TC-10 | RQ-05 | Remove a product from the cart | Positive | High | Product is removed and total is updated | Pass |
| TC-11 | RQ-06 | Complete a purchase with valid details | Positive | Critical | Purchase confirmation displays an order ID and correct amount | Pass |
| TC-12 | RQ-07 | Submit the purchase form with all fields empty | Negative | Critical | Purchase is prevented and required fields are identified | Pass |
| TC-13 | RQ-07 | Submit the purchase form without a credit card | Negative | High | Purchase is prevented and a helpful validation message appears | Fail |
| TC-14 | RQ-07 | Enter a very long customer name | Boundary | Medium | The form handles the value safely without breaking the page | Fail |
| TC-15 | RQ-01 | Navigate important controls using only the keyboard | Accessibility | Medium | Controls are reachable and visible focus is provided | Pass |