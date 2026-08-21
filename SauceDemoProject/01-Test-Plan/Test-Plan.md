# Test Plan

## 1. Introduction

The purpose of this test plan is to define the testing approach, scope, objectives, and activities for testing the SauceDemo web application.

SauceDemo is a sample e-commerce web application provided by Sauce Labs for demonstrating software testing practices. The application simulates an online shopping experience, including user login, product browsing, shopping cart management, and checkout.

---

## 2. Objectives

The main objectives of testing are:

- Verify that the core application features work as expected
- Identify and document defects
- Validate the main user workflow from login to order completion
- Verify that the application handles invalid input correctly
- Ensure that fixes do not introduce new defects

---

## 3. Scope

### 3.1 In Scope

The following application features are included in the scope of testing:

- **Login** – valid and invalid login attempts and login validation
- **Product Catalogue** – product display, product information, and product sorting
- **Shopping Cart** – adding, viewing, and removing products
- **Checkout** – customer information, order overview, and order completion
- **Logout** – successful user logout

### 3.2 Out of Scope

The following areas are outside the scope of this testing cycle:

- **Performance Testing** – load, stress, and response time testing
- **Security Testing** – security vulnerabilities, penetration testing, and authentication security
- **API Testing** – direct testing of backend APIs
- **Database Testing** – validation of database structure, queries, and data integrity
- **Cross-Browser Testing** – testing across multiple browsers
- **Mobile Testing** – testing on mobile devices and mobile browsers

---

## 4. Test Strategy

Testing will be performed primarily using manual testing techniques.

The following testing approaches will be used:

- **Functional Testing** – will be performed to verify that the application features included in the scope behave according to the expected results.
- **Regression Testing** – will be performed to verify that existing functionality continues to work correctly after defects are identified and fixed.
- **Exploratory Testing** – will be used to explore the application beyond predefined test cases and identify unexpected behavior or potential usability issues.
- **System Testing** – will be performed at the system level, validating the application as a whole from an end-user perspective.

---

## 5. Test Environment

| Item | Details |
|---|---|
| **Application** | SauceDemo Web Application |
| **URL** | https://www.saucedemo.com/ |
| **Operating System** | Windows 10 |
| **Browser** | Google Chrome |
| **Testing Type** | Manual web application testing |

---

## 6. Test Data

The following test data will be used during testing.

### 6.1 User Accounts

| Username | Password | Purpose |
|---|---|---|
| `standard_user` | `secret_sauce` | Valid login and standard user workflows |
| `locked_out_user` | `secret_sauce` | Testing locked account behavior |
| `problem_user` | `secret_sauce` | Testing unexpected application behavior |

### 6.2 Checkout Data

| Field | Test Data |
|---|---|
| First Name | Test |
| Last Name | User |
| Postal Code | 12345 |

### 6.3 Login Validation Requirements

- Username is required
- Password is required
- Invalid credentials must prevent login
- When both required fields are empty, the user should be informed that both fields are required
  
---

## 7. Entry Criteria

Testing can begin when the following conditions are met:

- The application is available and accessible
- The test environment is prepared
- Required test data is available
- The testing scope has been defined
- Test cases have been created and reviewed

---

## 8. Exit Criteria

Testing can be considered complete when the following conditions are met:

- All planned test cases have been executed
- Test results have been documented
- All identified defects have been reported
- No unresolved critical defects remain without documentation
- Test results have been reviewed and evaluated
- The Test Summary Report has been completed

---

## 9. Defect Management

All identified defects will be documented and tracked throughout the testing process.

Each defect report will contain the following information:

- Defect ID
- Title
- Description
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Test environment
- Supporting evidence, such as screenshots, where applicable

Defects will be retested after fixes are implemented. If a defect is still reproducible, it may be reopened for further investigation.

---

## 10. Risks and Assumptions

### 10.1 Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Application becomes unavailable | Testing cannot continue | Verify application availability before testing and retry later |
| Internet connectivity issues | Test execution may be interrupted | Ensure a stable internet connection |
| Application changes during testing | Existing test results may become invalid | Document application changes and repeat affected tests |
| A critical defect blocks further testing | Some test cases cannot be executed | Document the blocking defect and continue with unaffected areas |

### 10.2 Assumptions

The following assumptions are made for this testing cycle:

- The application will be available during testing
- The provided test accounts will be available and functional
- The test environment will remain stable throughout testing
- The application functionality will remain unchanged during the planned test execution

---

## 11. Deliverables

The following deliverables will be created as part of the testing process:

- **Test Plan** – defines the testing scope, objectives, strategy, environment, and approach.
- **Test Cases** – contains the planned test scenarios and detailed test steps.
- **Test Execution Results** – records the outcome of each executed test case.
- **Bug Reports** – documents identified defects and their details.
- **Test Summary Report** – provides an overview of the testing results, identified defects, and overall test outcome.

---

## 12. Test Schedule

| Activity | Planned Sequence |
|---|---:|
| Test planning | 1 |
| Test case creation | 2 |
| Test execution | 3 |
| Defect reporting | 4 |
| Retesting and regression testing | 5 |
| Test summary report | 6 |
