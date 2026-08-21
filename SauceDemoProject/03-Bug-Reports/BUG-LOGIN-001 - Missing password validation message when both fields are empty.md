## BUG-LOGIN-001 - Missing password validation message when both fields are empty

---

| **Field** | **Value** |
|---|---|
| **Bug ID** | BUG-LOGIN-001 |
| **Title** | Missing password validation message when both fields are empty |
| **Related test case** | TC-LOGIN-006 |
| **Module** | Login |
| **Severity** | Medium |
| **Priority** | Medium |
| **Environment** | SauceDemo web application |
| **Preconditions** | User is on the SauceDemo login page |
| **Steps to reproduce** | 1. Leave the Username field empty.<br><br>2. Leave the Password field empty.<br><br>3. Click **Login**. |
| **Expected result** | Validation messages indicating that both username and password are required are displayed. User remains on the login page. |
| **Actual result** | Only the error message "Epic sadface: Username is required" is displayed. No validation message for the empty Password field is displayed. |
| **Status** | Open |
| **Defect type** | Functional / Validation |
| **Description** | When both the Username and Password fields are left empty, the application only displays a validation message for the Username field. The Password field is not identified as required, which may make it unclear to the user that both fields must be completed. |
