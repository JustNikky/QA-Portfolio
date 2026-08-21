## TC-LOGIN-002 - Login with invalid username

---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-002 |
| **Test type** | Functional / Negative |
| **Title** | Login with invalid username |
| **Module** | Login |
| **Priority** | High |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:** `invalid username`<br>**Password:** `secret_sauce` |
| **Steps** | 1. Enter `invalid username` into the Username field.<br><br>2. Enter `secret_sauce` into the Password field.<br><br>3. Click **Login**. |
| **Expected result** | Login is unsuccessful and appropriate error message is displayed. User remains on the login page. |
| **Actual result** | Login was unsuccessful and appropriate error message was displayed. User remained on the login page. |
| **Status** | **PASS** |
| **Defect** | N/A |
