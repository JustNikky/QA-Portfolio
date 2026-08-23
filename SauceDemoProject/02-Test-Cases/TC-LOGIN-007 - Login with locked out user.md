## TC-LOGIN-007 - Login with locked out user

---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-007 |
| **Test type** | Functional / Negative |
| **Title** | Login with locked out user |
| **Module** | Login |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:** `locked_out_user` <br>**Password:** `secret_sauce` |
| **Steps** | 1. Enter `locked_out_user` into the Username field.<br><br>2. Enter `secret_sauce` into the Password field.<br><br>3. Click **Login**. |
| **Expected result** | Login is unsuccessful. The error message "Epic sadface: Sorry, this user has been locked out." is displayed. User remains on the login page. |
| **Actual result** | Login was unsuccessful. The error message "Epic sadface: Sorry, this user has been locked out." was displayed. User remained on the login page. |
| **Status** | **PASS** |
| **Defect** | N/A |
