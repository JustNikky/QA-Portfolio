## TC-LOGIN-009 - Password is masked
---

| **Field** | **Value** |
|---|---|
| **Test case ID** | TC-LOGIN-009 |
| **Test type** | UI / Functional |
| **Title** | Password is masked |
| **Module** | Login |
| **Priority** | Medium |
| **Preconditions** | User is on the SauceDemo login page |
| **Test data** | **Username:** `standard_user` <br>**Password:** `secret_sauce` |
| **Steps** | 1. Enter `standard_user` into the Username field. <br><br>2. Enter `secret_sauce` into the Password field. <br><br>3. Verify that the entered password is displayed as masked characters. |
| **Expected result** | Password characters are masked and are not displayed as plain text while entering the password. |
| **Actual result** | Password characters are masked and are not displayed as plain text while entering the password. |
| **Status** | **PASS** |
| **Defect** | N/A |
