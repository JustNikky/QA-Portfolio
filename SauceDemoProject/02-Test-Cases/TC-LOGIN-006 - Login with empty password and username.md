## TC-LOGIN-006 - Login with empty password and username

---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-006 |
| **Test type** | Functional / Negative |
| **Title** | Login with empty password and username |
| **Module** | Login |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:**  <br>**Password:** |
| **Steps** | 1. Leave the Username field empty.<br><br>2. Leave the Password field empty. <br><br>3. Click **Login**. |
| **Expected result** | Login is unsuccessful. Validation messages indicating that both username and password are required are displayed. User remains on the login page. |
| **Actual result** | Login is unsuccessful. Only the error message "Epic sadface: Username is required" is displayed. No validation message for the empty password field is displayed. |
| **Status** | **FAIL** |
| **Defect** | BUG-LOGIN-001 |


