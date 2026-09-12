# Md.Mahbubul Islam

** Software Quality Assurance (SQA) Engineer | Manual & Automation Testing**

📧 Email: mahbubfaisal.cse@gmail.com
🔗 [LinkedIn: https://www.linkedin.com/in/mahbubfaisal/  

---

## About Me

SQA Engineer focused on delivering reliable, maintainable, and
high-quality software through structured testing and continuous
quality improvement.

- Manual & Functional Testing
- API Testing (Postman, Newman)
- UI Automation (Playwright, Selenium)
- Database Testing (SQL)
- Regression, Smoke & Sanity Testing
- Bug Reporting & QA Documentation
- Performance Testing (JMeter)
- Agile QA workflows and STLC

I enjoy finding defects, analyzing root causes, and building
well-structured test processes that improve software quality.

---

## Skills & Tools

| Testing | Automation | Tools |
|---|---|---|
| Manual Testing | Playwright | Postman |
| Functional Testing | Selenium | Jira |
| Regression Testing | JavaScript | Git |
| Smoke & Sanity | Newman | GitHub |
| UI/UX Testing |  | VS Code |
| API Testing |  | MySQL Workbench |
| Database Testing |  | JMeter |
| Performance Testing |  |  |

| QA Process | Database | Other |
|---|---|---|
| STLC | SQL | REST API |
| Test Planning | MySQL | Agile |
| Test Case Design |  | CI/CD Basics |
| Bug Reporting |  |  |
| QA Documentation |  |  |

---

## Projects

### 🧪 EverShop Demo – Manual Testing & Bug Reporting

A manual SQA project focused on exploratory, functional, validation, UI, and responsive testing of the EverShop Demo e-commerce application.

🔍 What I Tested
- User Registration, Login & Password Reset
- Input Validation & Authentication
- Product Listing & Add to Cart
- Checkout Process
- UI & Responsive Design across Desktop, Tablet and Mobile
  
🐞 Key Findings
- Identified and documented 9 functional, validation, and UI defects
- Classified bugs based on severity and defect type
- Covered issues affecting account access, data validation, product interaction, and responsive usability
  
📋 QA Documentation
- Detailed Bug Reports with reproduction steps
- Actual vs. Expected Results
- Severity & Bug Type Classification
- Screenshot and video evidence
- Centralized Excel-based bug report

 📊 Business Impact of Identified Bugs

The identified defects could have affected customer experience, data quality, security, checkout usability, and potential revenue.

| Bug | Potential Business Impact |
|---|---|
| **B-001 – Reset Password Not Working** | Customers may lose account access, increasing support requests and potential customer churn. |
| **B-002 – Password Accepts Only Lowercase Characters** | Restrictive validation may frustrate users and increase registration abandonment. |
| **B-003 – Invalid Email Format Accepted** | Incorrect email data may affect order communication, account recovery, marketing, and customer support. |
| **B-004 – Password Accepts Only Numeric Characters** | Weak password validation may reduce account security and increase the risk of unauthorized access. |
| **B-005 – Single-Character Name Accepted** | Poor customer data quality may affect orders, invoices, customer identification, and communication. |
| **B-006 – Numeric Name Accepted** | Invalid customer information may result in inaccurate customer records and reduced data reliability. |
| **B-007 – Single-Character Phone Number Accepted** | Invalid phone numbers may cause delivery communication failures, delayed orders, or failed deliveries. |
| **B-008 – Oversized Add to Cart Button on Tablet** | Poor responsive UI may reduce usability and negatively affect the shopping experience. |
| **B-009 – Double-Click Add to Cart Selects Next Product** | Customers may accidentally interact with the wrong product, leading to incorrect orders, cart abandonment, and loss of trust. |

### 🧪 QA Brains Platform Testing

- Designed **150+ manual test cases** covering multiple application modules.
- Performed functional, UI/UX, usability, compatibility, performance
  and security testing.
- Created professional QA artifacts including:
  - Test Plan
  - Test Cases
  - Bug Reports
  - Test Execution Report
  - Test Summary Report
- Documented defects with reproduction steps and video evidence.
  
  ### 🐞 Bug Summary
| Bug ID  | Severity | Priority | Business Impact                                                        |
| ------- | -------- | -------- | ---------------------------------------------------------------------- |
| BUG-001 | Critical | P1       | Prevents users from logging in, blocking account access.               |
| BUG-002 | Critical | P1       | Allows duplicate accounts, causing data integrity issues.              |
| BUG-003 | Critical | P1       | Accepts invalid emails, resulting in unreliable user data.             |
| BUG-004 | Major    | P1       | Prevents password recovery and may lock users out of their accounts.   |
| BUG-005 | Major    | P1       | Allows incomplete orders, potentially affecting order processing.      |
| BUG-006 | Major    | P2       | Accepts invalid customer names, reducing data quality.                 |
| BUG-007 | Average  | P3       | Accepts invalid ZIP codes, potentially affecting delivery information. |

**Total Bugs:** 7
**Critical:** 3 | **Major:** 3 | **Average:** 1


📄 [View Project](https://github.com/mahbubfaisalcse/QABrains-Practice-Site-Testing)

---

### 🗄️ Search Functionality & Product Page QA Testing

📌 Project Overview
- Manual QA testing project for an e-commerce product & search page
- Designed and executed functional test cases for key user workflows
- Performed UI/UX, usability, and responsive testing
- Validated API functionality using Postman
- Performed cross-browser compatibility testing
- Evaluated basic performance-related scenarios
- Identified and documented defects with Expected vs. Actual Results
- Applied QA practices including test scenario design, execution, and defect reporting
  
🛠️ Tools & Skills
Manual Testing • Test Case Design • Functional Testing • UI/UX Testing • API Testing (Postman) • Bug Reporting • Responsive Testing • Compatibility Testing • Performance Testing

📄 [View Project](https://github.com/mahbubfaisalcse/Test-Cases-and-Product-Page-QA)

---

### 🎭 Swag Labs UI Automation with Playwright

📌 Project Overview
- Automated Swag Labs (SauceDemo) web application using Playwright & JavaScript
- Automated login scenarios for Standard, Locked-Out, and Performance Glitch users
- Validated product sorting, add-to-cart, and checkout workflows
- Verified product names and total price calculations
- Validated checkout success messages, URLs, and error messages
- Implemented Page Object Model (POM) for reusable and maintainable test automation
- Used assertions and validations to verify expected application behavior
- Managed project with Node.js, Git & GitHub
  
🛠️ Tools & Technologies
Playwright • JavaScript • Node.js • Page Object Model (POM) • Git • GitHub

📄 [View Project](https://github.com/mahbubfaisalcse/Swag-Labs-UI-Automation-With-Playwright)

---

### 🔌 API Automation

📌 Project Overview
- Automated ReqRes REST APIs using Postman & JavaScript
- Implemented token-based authentication and Bearer Token handling
- Tested login, user retrieval, user verification, and profile management
- Automated PUT and PATCH requests with response validation
- Covered negative scenarios including 400, 401, and 404 responses
- Created automated status code, response body, and data assertions
- Used collection variables for reusable test data and authentication
- Executed API tests using Postman Collection Runner & Newman
- Supported HTML test reporting through Newman

| Method   | Scenario         | Validation           |
| -------- | ---------------- | -------------------- |
| POST     | Login            | Status, token        |
| GET      | User Profile     | User data            |
| GET      | User by ID       | Name & email         |
| PUT      | Update User      | Response & timestamp |
| PATCH    | Partial Update   | Updated field        |
| Negative | Invalid requests | 4xx responses        |
  
🛠️ Tools & Technologies
Postman • JavaScript • REST API • Newman • Bearer Token Authentication • API Assertions • Positive & Negative Testing

📄 [View Project](https://github.com/mahbubfaisalcse/API-Automation)

---

## QA Focus

```text
Manual Testing       ████████████████████
API Testing          ██████████████████
SQL / DB Testing     █████████████████
Playwright           ████████████████
Selenium             █████████████
Performance Testing  ███████████
