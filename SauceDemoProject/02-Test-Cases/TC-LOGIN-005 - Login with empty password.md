## TC-LOGIN-005 - Login with empty password

---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-005 |
| **Test type** | Functional / Negative |
| **Title** | Login with empty password |
| **Module** | Login |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:** `standard_user`  <br>**Password:** |
| **Steps** | 1. Enter `standard_user` into the Username field.<br><br>2. Leave Password field empty. <br><br>3. Click **Login**. |
| **Expected result** | Login is unsuccessful. The error message "Epic sadface: Password is required" is displayed. User remains on the login page. |
| **Actual result** | Login was unsuccessful. The error message "Epic sadface: Password is required" was displayed. User remained on the login page. |
| **Status** | **PASS** |
| **Defect** | N/A |

