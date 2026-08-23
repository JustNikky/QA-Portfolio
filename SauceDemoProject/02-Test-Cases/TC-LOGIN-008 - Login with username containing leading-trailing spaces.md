## TC-LOGIN-008 - Login with username containing leading/trailing spaces
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-008 |
| **Test type** | Validation / Negative |
| **Title** | Login with username containing leading/trailing spaces |
| **Module** | Login |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:** `standard_user` (one leading and one trailing space) <br>**Password:** `secret_sauce` |
| **Steps** | 1. Enter `standard_user` into the Username field, including one leading and one trailing space.<br><br>2. Enter `secret_sauce` into the Password field.<br><br>3. Click **Login**. |
| **Expected result** | Login is unsuccessful. The error message "Epic sadface: Username and password do not match any user in this service" is displayed. User remains on the login page. |
| **Actual result** | Login was unsuccessful. The error message "Epic sadface: Username and password do not match any user in this service" was displayed. User remained on the login page. |
| **Status** | **PASS** |
| **Defect** | N/A |
