# 🛒 OpenCart E-Commerce — Manual QA Project

> **Type:** Personal Practice Project | **Testing Type:** Manual Functional Testing | **Date:** April 2026

---

## 📁 Folder Structure

```
QA/
└── Demo Open Cart Project/
    ├── OpenCart_Test_Plan.docx       ← Test Plan (scope, strategy, schedule)
    ├── OpenCart_Test_Cases.xlsx      ← 31 Manual Test Cases
    ├── OpenCart_Bug_Report.xlsx      ← Bug Report with defects found
    └── README.md                     ← Project overview (this file)
```

---

## 📌 Project Overview

This is a manual QA practice project performed on the **OpenCart demo e-commerce website** (`demo.opencart.com`). The goal was to apply real-world QA processes — writing a test plan, designing test cases, executing them, and logging defects — to simulate the role of a QA Executive in a professional environment.

---

## 🌐 Application Under Test

| Field | Details |
|---|---|
| Application | OpenCart E-Commerce |
| URL | https://demo.opencart.com |
| Type | Web Application |
| Testing Type | Manual Functional Testing |

---

## 📋 What's Included

### 1. `OpenCart_Test_Plan.docx`
A professional test plan document covering:
- Project scope (in-scope and out-of-scope)
- Test strategy and techniques used
- Test environment details
- Entry and exit criteria
- Modules under test with test case count
- Defect management approach
- Roles, schedule, and risks

### 2. `OpenCart_Test_Cases.xlsx`
Excel sheet with **30 manually written test cases** across 6 modules:

| Module | Test Cases |
|---|---|
| User Registration | 6 |
| Login / Logout | 6 |
| Product Search | 4 |
| Shopping Cart | 5 |
| Checkout | 5 |
| Order Confirmation | 4 |
| **Total** | **30** |

Each test case includes: TC ID, Module, Title, Pre-Conditions, Test Steps, Test Data, Expected Result, Actual Result, Status, Severity, and Priority.

### 3. `OpenCart_Bug_Report.xlsx`
Bug report sheet logging defects found during test execution:

| Bug ID | Module | Severity | Status |
|---|---|---|---|
| BUG_001 | Login / Logout | High | Open |

**BUG_001 Summary:** Clicking "Forgotten Password" on the Login page directly displays a success message — *"An e-mail with a confirmation link has been sent"* — without showing a form or asking for the user's email address. This is a critical flow defect in the password recovery module.

---

## 🧪 Testing Techniques Applied

- **Equivalence Partitioning** — Grouping valid and invalid inputs
- **Boundary Value Analysis** — Testing min/max field lengths
- **Positive Testing** — Verifying correct behavior with valid data
- **Negative Testing** — Verifying graceful handling of invalid inputs
- **Exploratory Testing** — Unscripted testing to discover unexpected bugs

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel / Google Sheets | Test cases & bug report |
| Microsoft Word | Test plan document |
| Google Chrome | Test execution (browser) |
| demo.opencart.com | Application under test |

---

## 👤 About This Project

This project was created as part of my QA learning journey to practice real-world manual testing skills. All test artifacts — test plan, test cases, and bug reports — follow industry-standard formats used by QA teams in professional environments.

---

*OpenCart QA Practice Project — April 2026*
