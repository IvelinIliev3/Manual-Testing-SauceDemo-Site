# Manual QA Portfolio | SauceDemo Project

This repository contains professional testing documentation for the [SauceDemo](https://www.saucedemo.com) e-commerce platform. The goal is to demonstrate my ability to analyze requirements, create structured test cases, and identify software defects.

## 🚀 Project Overview
- **Target Application:** SauceDemo (Swag Labs)
- **Type of Testing:** Manual Functional Testing, UI/UX Testing, Regression Testing
- **Tools Used:** Google Sheets, GitHub, Chrome DevTools

## 📑 Test Cases
The following table highlights key functional test scenarios:


| ID | Test Scenario | Priority | Expected Result |
|:---|:---|:---:|:---|
| TC01 | Login with valid `standard_user` | High | User is redirected to the Inventory page |
| TC02 | Login with locked out user | High | Error message: "Sorry, this user has been locked out." |
| TC03 | Add item to cart from Home page | Medium | Cart badge updates and button text changes to "Remove" |
| TC04 | Verify Checkout information validation | High | Error is shown if First/Last Name is missing during checkout |
| TC05 | Sort products by price (Low to High) | Low | Items are displayed in ascending order by price |

## 🐛 Bug Reports (Example)
**Issue:** Product images not loading for `problem_user`.  
**Severity:** Medium  
**Status:** Open  
**Steps to Reproduce:**
1. Log in as `problem_user`.
2. Observe the product gallery on the main page.
**Actual Result:** All products show a broken image placeholder.
