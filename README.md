# Othoba.com – Manual Testing Project

## 📌 Project Overview

This repository contains the complete **Manual Testing documentation** for **Othoba.com**, an e-commerce website.

The project demonstrates the end-to-end QA testing process, including test planning, test scenario design, test case preparation, test execution, and bug reporting.

**Application:** Othoba.com<br>
**Testing Type:** Manual Testing<br>
**Browser:** Google Chrome<br>
**Prepared By:** Mahmuda Binte Sayeed<br>
**Reviewed By:** Sabiul Islam Rashed

---

## 📂 Testing Documentation

The complete testing documentation is organized into the following sheets:

| # | Sheet                        | Description                                                                             |
| - | ---------------------------- | --------------------------------------------------------------------------------------- |
| 1 | 📋 **Test Plan**             | Contains the testing objectives, scope, approach, resources, and testing strategy.      |
| 2 | 🧠 **Mind Map**              | Defines the overall testing scope and areas to be tested.                               |
| 3 | 📝 **Test Scenario**         | Covers high-level scenarios derived from the application's features and requirements.   |
| 4 | 🧪 **Test Case**             | Contains detailed test cases with steps, test data, expected and actual results.        |
| 5 | 🐞 **Bug Report**            | Documents identified defects with reproduction steps, severity, priority, and evidence. |
| 6 | 📈 **Test Case Summary Report**   | Provides an overall summary of testing activities, findings, and results.          |
| 7 | 📊 **Test Matrix** | Provides a structured overview of test scenarios, test cases, modules, testing types, and their execution status. |

---

## 🧠 Mind Map
<img width="890" height="1925" alt="Mind Map for Othoba com (3)" src="https://github.com/user-attachments/assets/4be7294b-89e3-4b5e-8a4d-14710aaef7ff" />

---

## 🧩 Modules Covered

| # | Module | Test Cases | Focus Areas |
|---|--------|:----------:|-------------|
| 1 | Registration | 44 | Field validation, OTP, reCAPTCHA, duplicates, DOB, password rules, security |
| 2 | Login | 2 | Sign in, OTP button position |
| 3 | Home Page | 23 | Navigation, search bar, banners, prices, responsiveness, performance |
| 4 | Search | 15 | Keywords, suggestions, case sensitivity, partial/numeric input, responsiveness |
| 5 | Category | 16 | Listing, sorting, filters, pagination, subcategory, out of stock |
| 6 | Wishlist | 11 | Add/remove, duplicates, login requirement, add to cart |
| 7 | Cart | 15 | Quantity, subtotal/total, discount, persistence, checkout |
| 8 | Payment | 19 | Payment methods, COD, gateway, success/failure/cancel, retry, amounts |
| 9 | Order Placement | 17 | Confirmation, order ID, summary, history, negative cases, notifications |
| 10 | Order Tracking | 12 | Timeline, shipped/delivered status, courier, tracking link |
| 11 | Product Details | 26 | Images, price, variants, quantity validation, security, layout |
| | **Total** | **200** | |

---

## 🧪 Types of Testing Performed

| Type | Description |
|------|-------------|
| **Functional** | Verifies that features behave according to requirements. |
| **Validation** | Checks input fields, formats, and error/validation messages. |
| **UI Testing** | Verifies layout, visual elements, and content display. |
| **Negative** | Checks system behavior with invalid or unexpected input/actions. |
| **Boundary** | Tests limits such as excessively long names or passwords. |
| **Compatibility** | Tests responsiveness and behavior across devices and browsers. |
| **Performance** | Checks page load time. |
| **Security** | Tests script injection and HTML injection handling. |

---

## 📊 Test Execution Summary

**Total Test Cases:** 200

| Status     | Count |
| ---------- | ----: |
| ✅ Passed   |   171 |
| ❌ Failed   |    29 |
| ⏸️ No Run  |     0 |
| 🚫 Blocked |     0 |

---
## ▶️ How to Execute

1. Open the test case sheet and pick a module.
2. Review the preconditions and prepare the required test data.
3. Perform each test case on the application.
4. Compare the actual behavior with the expected result.
5. Mark the status as **Pass**, **Fail**, or **Blocked**.
6. For failures, log a defect with steps to reproduce, screenshots, and environment details.
---

## 🐞 Bug Reporting

Identified defects are documented with:

* Bug/Issue Description
* Reproduction Steps
* Environment
* Module
* Priority
* Severity
* Expected Result
* Actual Result
* Screenshot/Recording
* Final Status

Examples of identified issues include:

* Invalid email accepted without proper domain validation
* Invalid phone number validation issues
* Numeric and special characters accepted in name fields
* Missing password validation
* Password mismatch validation
* Existing email/phone validation issues
* OTP verification issues
* Search-related issues
* Wishlist and product-related issues

---

---

## 🔗 End-to-End Flow Covered

```
Registration → Login → Home Page → Search / Category → Product Details
      → Wishlist / Cart → Payment → Order Placement → Order Tracking
```
---

## 📊 Test Summary (fill after execution)

| Module | Total | Passed | Failed | Blocked | Not Executed |
|--------|:-----:|:------:|:------:|:-------:|:------------:|
| Registration | 44 | | | | |
| Login | 2 | | | | |
| Home Page | 23 | | | | |
| Search | 15 | | | | |
| Category | 16 | | | | |
| Wishlist | 11 | | | | |
| Cart | 15 | | | | |
| Payment | 19 | | | | |
| Order Placement | 17 | | | | |
| Order Tracking | 12 | | | | |
| Product Details | 26 | | | | |
| **Total** | **200** | | | | |

---

## 🔗 Complete Test Documentation

The complete testing documentation is available in Google Sheets:

[View Complete Othoba Manual Testing Documentation](https://docs.google.com/spreadsheets/d/1_uY-bXm8tnfY45knyyf4xldDoElLvfTXtwaWCCX_nCU/edit?usp=sharing&utm_source=chatgpt.com)

---

## 🎯 Project Objective

The objective of this project is to demonstrate practical QA skills in:

* Test planning
* Mind mapping
* Test scenario design
* Test case design
* Test execution
* Bug reporting
* Test result analysis
* QA documentation

---

## 👩‍💻 Tester

**Mahmuda Binte Sayeed**
Software QA Engineer | Manual Tester
