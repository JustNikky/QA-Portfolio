## BUG-PRODUCT-001 - Cart count displays 1 after login

---

| **Field** | **Value** |
|---|---|
| **Bug ID** | BUG-PRODUCT-001 |
| **Title** | Cart count set to 1 after login |
| **Related test case** | TC-PRODUCT-005 |
| **Module** | Product |
| **Severity** | Medium |
| **Priority** | Medium |
| **Environment** | SauceDemo web application |
| **Preconditions** | User is on the SauceDemo login page. |
| **Steps to reproduce** | 1. Enter `standard_user` into the Username field.<br><br>2. Enter `secret_sauce` into the Password field.<br><br>3. Click **Login**. <br><br>4. Verify the cart indicator. |
| **Expected result** | The cart count should display 0 or should not be displayed when the cart is empty. |
| **Actual result** | The cart indicator displays 1 immediately after login, even though no product has been added to the cart. |
| **Status** | Open |
| **Defect type** | Functional |
| **Description** | The cart indicator displays 1 immediately after login, even though no product has been added to the cart. |
