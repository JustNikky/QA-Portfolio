## TC-LOGIN-004 - Login with empty username

---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-004 |
| **Test type** | Functional / Negative |
| **Title** | Login with empty username |
| **Module** | Login |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:** ``<br>**Password:** `secret_sauce` |
| **Steps** | 1. Leave the Username field empty.<br><br>2. Enter `secret_sauce` into the Password field.<br><br>3. Click **Login**. |
| **Expected result** | Login is unsuccessful. The error message "Epic sadface: Username is required" is displayed. User remains on the login page. |
| **Actual result** | Login was unsuccessful. The error message "Epic sadface: Username is required" was displayed. User remained on the login page. |
| **Status** | **PASS** |
| **Defect** | N/A |
