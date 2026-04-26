# OpenCart Manual Testing Project

A complete manual testing project for the OpenCart e-commerce demo application, covering functional and UI testing across 12 modules.

## Project Overview

| Item | Details |
|---|---|
| Application Tested | OpenCart Demo |
| Application URL | https://demo.opencart.com |
| Testing Type | Manual Testing |
| Test Management | Microsoft Excel |
| Bug Tracking | Jira |

## Modules Tested
1. User Registration
2. User Login
3. User Logout
4. Forgot Password
5. Search
6. Shopping Cart: Add to Cart (Product Listing Page)
7. Shopping Cart: Remove from Cart
8. Shopping Cart: Update Cart
9. Product Detail Page
10. Shopping Cart: Add to Cart (Product Detail Page)
11. Order Confirmation
12. Checkout

## Testing Artifacts
- **Test Plan**: defines scope, objectives, environment, and entry/exit criteria
- **Test Scenarios**: 12 high level scenarios covering all modules
- **Test Cases**: detailed test cases with steps, test data, expected and actual results, and pass/fail status
- **Bug Reports**: 7 bugs logged and tracked in Jira with screenshots and severity/priority classification

## Bugs Found

| Bug ID | Summary | Severity | Priority |
|---|---|---|---|
| OMT-1 | Privacy policy checkbox missing * symbol | Medium | Medium |
| OMT-2 | Name fields accept numbers and special characters | Medium | Medium |
| OMT-3 | Empty search bar returns no results instead of prompt | Low | Low |
| OMT-4 | Out of stock products can be added to cart | High | High |
| OMT-5 | Invalid quantity silently removes cart items | High | High |
| OMT-6 | Invalid quantity on product page shows misleading success message | Medium | Medium |
| OMT-7 | Negative quantity on product page silently removes cart items | High | High |

## Tools Used
- Microsoft Excel (test cases and scenarios)
- Jira (bug tracking)
- Snipping Tool (bug screenshots)
- Brave Browser (test execution)
