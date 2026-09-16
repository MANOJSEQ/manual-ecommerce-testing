# Manual E-commerce Testing Portfolio

A manual QA testing project covering customer journeys on the DemoBlaze e-commerce website.

## Application Under Test

- Website: https://www.demoblaze.com/
- Type: Public e-commerce demonstration website
- Test date: 16 September 2026
- Tester: Manoj Sequeira

## Project Summary

This project demonstrates practical manual testing skills across product browsing, user accounts, shopping-cart management and purchase journeys.

Official requirements were not provided, so requirements and acceptance criteria were created by observing the application.

## Testing Covered

- Functional testing
- Positive and negative testing
- Boundary-value testing
- Exploratory testing
- Usability testing
- Basic accessibility testing
- Regression testing
- Professional defect reporting

## Test Results

- Total test cases: 15
- Passed: 13
- Failed: 2
- Pass rate: 86.7%
- Defects identified: 4

## Key Defects

| Defect | Severity |
|---|---|
| [Misleading missing-card validation](defects/BUG-001-misleading-card-validation.md) | Low |
| [Long customer name breaks confirmation layout](defects/BUG-002-long-name-breaks-confirmation-layout.md) | Medium |
| [Full credit-card number is exposed](defects/BUG-003-card-number-exposed.md) | High |
| [Purchase confirmation displays incorrect month](defects/BUG-004-incorrect-purchase-date.md) | Medium |

## Project Documents

- [Test plan](docs/test-plan.md)
- [Requirements and acceptance criteria](docs/requirements.md)
- [Manual test cases](test-cases/customer-journey-test-cases.md)
- [Test summary report](docs/test-results.md)
- [Screenshot evidence](evidence/screenshots)

## Main Findings

- Core browsing, login, cart and purchase journeys worked
- Product prices and cart totals were correct
- Negative login and duplicate-user validation worked
- Purchase validation messages require improvement
- Long input values are not handled correctly
- Payment-card information is displayed without masking
- Purchase confirmation displays an incorrect month

## Tools Used

- Google Chrome
- Visual Studio Code
- Markdown
- Git
- GitHub

## Skills Demonstrated

- Test planning
- Requirements analysis
- Test-case design
- Positive and negative testing
- Boundary-value analysis
- Exploratory testing
- Defect investigation
- Evidence collection
- Test reporting
- Risk-based release recommendations