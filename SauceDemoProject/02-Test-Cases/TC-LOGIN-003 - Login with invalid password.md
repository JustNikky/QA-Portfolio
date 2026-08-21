## TC-LOGIN-003 - Login with invalid password

---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-003 |
| **Test type** | Functional / Negative |
| **Title** | Login with invalid password |
| **Module** | Login |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:** `standard_user`<br>**Password:** `invalidpassword` |
| **Steps** | 1. Enter `standard_user` into the Username field.<br><br>2. Enter `invalidpassword` into the Password field.<br><br>3. Click **Login**. |
| **Expected result** | Login is unsuccessful. The error message "Epic sadface: Username and password do not match any user in this service" is displayed. User remains on the login page. |
| **Actual result** | Login was unsuccessful. The error message "Epic sadface: Username and password do not match any user in this service" was displayed. User remained on the login page. |
| **Status** | **PASS** |
| **Defect** | N/A |
