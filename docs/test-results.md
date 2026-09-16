# DemoBlaze Test Summary Report

## Test Execution Summary

- Test date: 16 September 2026
- Tester: Manoj Sequeira
- Browser: Google Chrome
- Operating system: macOS
- Total test cases: 15
- Passed: 13
- Failed: 2
- Pass rate: 86.7%

## Results

| Status | Count |
|---|---:|
| Pass | 13 |
| Fail | 2 |
| Not Run | 0 |
| Total | 15 |

## Failed Test Cases

| Test ID | Reason |
|---|---|
| TC-13 | Missing-card validation incorrectly mentions the completed Name field |
| TC-14 | A very long customer name breaks the confirmation layout |

## Defects Identified

| Defect ID | Summary | Severity | Priority |
|---|---|---|---|
| BUG-001 | Missing-card validation incorrectly mentions the Name field | Low | Medium |
| BUG-002 | Long customer name breaks the confirmation layout | Medium | Medium |
| BUG-003 | Full credit-card number is exposed | High | High |
| BUG-004 | Purchase confirmation displays the incorrect month | Medium | Medium |

## Key Findings

- Core browsing, login, cart and purchase journeys worked successfully
- Product prices and cart totals were calculated correctly
- Negative login and sign-up validation worked
- Purchase-form validation requires clearer messages
- Boundary values are not handled correctly
- Sensitive payment information is displayed without masking
- Purchase confirmation shows an incorrect transaction month

## Recommendation

The application should not be considered production-ready until the exposed credit-card number is fixed. The incorrect date and confirmation-layout defects should also be corrected before release.