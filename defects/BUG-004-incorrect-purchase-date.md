# BUG-004: Purchase confirmation displays the incorrect month

## Summary

The purchase confirmation displays August instead of September in the transaction date.

## Environment

- Application: DemoBlaze
- Page: Cart — Purchase confirmation
- Browser: Google Chrome
- Operating system: macOS
- Test date: 16 September 2026
- Discovered during: TC-11

## Severity

Medium

## Priority

Medium

## Preconditions

- A product is present in the shopping cart
- The Place Order form is open

## Steps to Reproduce

1. Complete the purchase form with valid details
2. Click Purchase
3. Review the date in the confirmation

## Expected Result

The confirmation should display the correct purchase date:

`16/9/2026`

## Actual Result

The confirmation displays:

`16/8/2026`

The displayed month is one month behind the actual month.

## Evidence

![Incorrect purchase date](../evidence/screenshots/TC-11-purchase-confirmation.png)

## Status

New